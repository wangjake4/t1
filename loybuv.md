代发 wailian999

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhongyouzk.top/Article/details/gtkazauayy.html

[R50] awk 求和
来源：http://dali.tanke756.top/Article/details/gtdcuuyhes.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinqigufen.top/Article/details/gtitsrotfr.html

[R51] 排序去重取前几
来源：http://dali.xuanzx.com/Article/details/gtibveqitl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.nwbrower.top/Article/details/gthaahzgut.html

[R52] 统计行数
来源：http://dali.aibaodan.cn/Article/details/gtyemipexf.html

wc -l a.txt
来源：http://dali.guowangkeji.top/Article/details/gtxhcixyoo.html

[R53] 查看文件头与实时尾
来源：http://dali.cucudq.cn/Article/details/gtzjajmuzs.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhixingplan.top/Article/details/gtcuwfnpvz.html

[R54] 比较两个文件
来源：http://dali.pengpengdd.cyou/Article/details/gttzqkerpf.html

diff a.txt b.txt
来源：http://dali.hnxiangtu.top/Article/details/gtsabckjgb.html

[R55] 压缩与解压
来源：http://dali.hywenlv.cn/Article/details/gthdqgbhkk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.sufxvd.cn/Article/details/gtbvzhefyy.html

[R56] 远程拷贝
来源：http://dali.zhoulong.xyz/Article/details/gtyxrffclj.html

scp file user@host:/path/
来源：http://dali.jlsjyb.cn/Article/details/gtsjcbabmx.html

[R57] 远程执行命令
来源：http://dali.aibaodan.cn/Article/details/gtsiivbqau.html

ssh user@host 'uptime'
来源：http://dali.yuxming.cn/Article/details/gtnrmxyzdk.html

[R58] 下载文件
来源：http://dali.jlsjyb.cn/Article/details/gtquxaansk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gtnsugcgnb.html

[R59] 发 POST JSON
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfxxavxzt.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.kuanghao11.cn/Article/details/gttcdnexlh.html

[R60] 只看 HTTP 状态码
来源：http://dali.yj20258888.top/Article/details/gtmexnwqvt.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yueranfly.top/Article/details/gthcnjtuxf.html

[R61] 磁盘占用
来源：http://dali.mhx1999.top/Article/details/gtlyedowar.html

df -h;  du -sh *
来源：http://dali.vqdsnc.cn/Article/details/gtdazqbsob.html

[R62] 找最占空间的文件
来源：http://dali.hongshengwenyu.top/Article/details/gttjmndqdc.html

du -ah . | sort -rh | head -10
来源：http://dali.iojbl.cn/Article/details/gtyevprxos.html

[R63] 内存与进程
来源：http://dali.hongshengwenyu.top/Article/details/gtcvdhnrrr.html

free -h;  ps aux | grep nginx
来源：http://dali.zdqjudy.top/Article/details/gtsvwhjrwu.html

[R64] 结束进程
来源：http://dali.pengpengdd.cyou/Article/details/gtncwlfkrz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.tianlin.xyz/Article/details/gtxljsntkl.html

[R65] 查看端口占用
来源：http://dali.jqgufenzy.top/Article/details/gtqnupadni.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.iojbl.cn/Article/details/gtlcqrhqzd.html

[R66] 定时任务
来源：http://dali.guowangkeji.top/Article/details/gtghmrlpwo.html

crontab -e;  crontab -l
来源：http://dali.hysaishi.cn/Article/details/gtugfxcbap.html

[R67] 生成随机十六进制串
来源：http://dali.ivvv.top/Article/details/gthoknibjm.html

openssl rand -hex 16
来源：http://dali.tanke756.top/Article/details/gthekcfalx.html

[R68] 计算文件校验值
来源：http://dali.zhongyouzk.top/Article/details/gtfvkbcibn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.bjfxy.top/Article/details/gtgejdtxmu.html

[R69] 生成随机密码
来源：http://dali.zycfv.cn/Article/details/gtbuzaiyfz.html

head -c 16 /dev/urandom | base64
来源：http://dali.sysykeji.top/Article/details/gthgyjdcnd.html

[R70] 时间戳与互转
来源：http://dali.sufxvd.cn/Article/details/gtpkupzmkk.html

date +%s;  date -d @1700000000
来源：http://dali.316326.xyz/Article/details/gthuxkwedd.html

[R71] 日期格式化
来源：http://dali.fzhhl.top/Article/details/gtbvhpyetj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shanyushiyangtech.top/Article/details/gtnonffzlw.html

[R72] 等待端口就绪
来源：http://dali.hammf.cn/Article/details/gtvdvvegwa.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ybcxt.top/Article/details/gtxrjjvafl.html

[R73] 分割大日志
来源：http://dali.jqgfzy.top/Article/details/gtvmuqdtnp.html

split -l 1000 big.log part_
来源：http://dali.chenzaomai.com/Article/details/gtnebbrohx.html

[R74] 批量重命名
来源：http://dali.9152youxi.cn/Article/details/gtwdyebwlg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqfzpouok.html

[R75] 导出环境变量
来源：http://dali.shuidangran.top/Article/details/gtnjkwxuax.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.redwolf501.top/Article/details/gtfxuejxtv.html

[R76] 使用临时文件
来源：http://dali.redwolf501.top/Article/details/gtplwkbcgd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shanyushiyangtech.top/Article/details/gtpvlsmzda.html

[R77] 读取用户输入
来源：http://dali.c1oappe.top/Article/details/gtnhhctabv.html

read -rp "请输入: " ans
来源：http://dali.sxryk.cn/Article/details/gtrkynccqc.html

[R78] 交互式菜单
来源：http://dali.gzhubu.top/Article/details/gtmonfjaoj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.haohaochexian.top/Article/details/gthqmogsbi.html

[R79] 解析命令行选项
来源：http://dali.ivvv.top/Article/details/gtwddykijw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zycfv.cn/Article/details/gtkwwjuusm.html

[R80] 查看脚本执行耗时
来源：http://dali.yj202588.top/Article/details/gtmbieunsw.html

time ./run.sh
来源：http://dali.zhengqikj.top/Article/details/gtovkfymnv.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtyrvquvlp.html

S. C / C++ 专题
来源：http://dali.hysaishi.cn/Article/details/gtcolierfk.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtlpelsnvg.html

[S01] C：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtiyamxiwd.html

#include <stdio.h>
来源：http://dali.9152youxi.cn/Article/details/gtehnuvzzt.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gaohongyu789.top/Article/details/gtgdikgakc.html

[S02] C：变量与格式化输出
来源：http://dali.guowangkeji.top/Article/details/gtmtliktpf.html

int a = 10; printf("%d\n", a);
来源：http://dali.ehwqpu.com/Article/details/gtypinoraj.html

[S03] C：读入整数
来源：http://dali.fengsongda.top/Article/details/gtprlekdjp.html

int x; scanf("%d", &x);
来源：http://dali.aizwys.cn/Article/details/gtjvnyvdmk.html

[S04] C：字符串复制
来源：http://dali.snrcjt.cn/Article/details/gtwsjnpxfe.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.guannengcc.top/Article/details/gtzhpmwldg.html

[S05] C：字符串长度
来源：http://dali.bjfxy.top/Article/details/gtynprqzsg.html

strlen(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtdcteljyn.html

[S06] C：字符串比较
来源：http://dali.cdnleiting.top/Article/details/gtqhmkarue.html

strcmp(a, b) == 0
来源：http://dali.mhx1999.top/Article/details/gtrkxtelxv.html

[S07] C：数组遍历求和
来源：http://dali.jinqigfzy.top/Article/details/gtwswaktwh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.vqdsnc.cn/Article/details/gtrftkfhwb.html

[S08] C：动态内存分配与释放
来源：http://dali.shzxlz.cn/Article/details/gtsqbnmdwk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.tian-w.cn/Article/details/gtvdpqvnbg.html

[S09] C：结构体定义与初始化
来源：http://dali.pycfn.com/Article/details/gtssodciah.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hfpthk.cn/Article/details/gtuvbwypxr.html

[S10] C：指针与解引用
来源：http://dali.cdnleiting.top/Article/details/gtuflheehp.html

int *p = &a;  *p = 5;
来源：http://dali.gogol.net.cn/Article/details/gtigipgjsw.html

[S11] C：逐行读文件
来源：http://dali.jianghu66.top/Article/details/gtysggcwle.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.mhx1999.top/Article/details/gtpidwdjpa.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.chenzaomai.com/Article/details/gtlekevgri.html

fclose(f);
来源：http://dali.wangshuangyany.cn/Article/details/gttzduphmw.html

[S12] C：写文件
来源：http://dali.bjfxy.top/Article/details/gttmvjippr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yonumen.top/Article/details/gtbzxtvnel.html

[S13] C：宏定义
来源：http://dali.zhiwuduotai.top/Article/details/gtbiqszkxx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jqgfzy.top/Article/details/gtnrutfwmz.html

[S14] C：枚举
来源：http://dali.mhx1999.top/Article/details/gthbsbofth.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.pycfn.com/Article/details/gtstqshmre.html

[S15] C：类型转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtllrelpjb.html

(double) a / b
来源：http://dali.gaohongyu789.top/Article/details/gtakgchzdh.html

[S16] C：位操作置位
来源：http://dali.hnqzz.top/Article/details/gtsmxbqjvh.html

x |= (1 << 3);
来源：http://dali.jinqigfzy.top/Article/details/gtofgfqhzm.html

[S17] C：安全拼接字符串
来源：http://dali.wangdashe.top/Article/details/gtemzhcmwi.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhengqikj.top/Article/details/gtyrldupri.html

[S18] C：命令行参数
来源：http://dali.chenzaomai.com/Article/details/gtemwdwuif.html

int main(int argc, char **argv)
来源：http://dali.wangdashe.top/Article/details/gtqgusthhi.html

[S19] C：快速排序
来源：http://dali.chenjidiqi.icu/Article/details/gtmbbpksfz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cashguo.top/Article/details/gtydcjiiyr.html

[S20] C：二分查找
来源：http://dali.ybcxt.top/Article/details/gtnlheddqs.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.wangshuangyany.cn/Article/details/gtltvlhbgp.html

[S21] C：字符类别判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtysvqfwaz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.guannengcc.top/Article/details/gtcbulncmb.html

[S22] C：字符串转数字
来源：http://dali.yj202588.top/Article/details/gtuhbkydqm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.daria6918.cn/Article/details/gtftfwvxat.html

[S23] C：随机数
来源：http://dali.xuanzx.com/Article/details/gtflqjpnpj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.mhx1999.top/Article/details/gtxjtrvfni.html

[S24] C：获取本地时间
来源：http://dali.cucudq.cn/Article/details/gtqriqshcl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtznkcgdml.html

[S25] C：内存拷贝
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzeysziqy.html

memcpy(dst, src, n);
来源：http://dali.shangyingyoupin.top/Article/details/gtxrbxavzt.html

[S26] C：内存清零
来源：http://dali.svipenyu.cn/Article/details/gttwtzczvz.html

memset(a, 0, sizeof a);
来源：http://dali.snrcjt.cn/Article/details/gtmjuetemi.html

[S27] C：定义常量
来源：http://dali.yvedp.cn/Article/details/gthpkeqzqp.html

const double PI = 3.14159;
来源：http://dali.pycfn.com/Article/details/gtubfyyepr.html

[S28] C：静态变量
来源：http://dali.yuxming.cn/Article/details/gtmvkgcpdf.html

static int counter = 0;
来源：http://dali.snrcjt.cn/Article/details/gtsobheast.html

[S29] C：变参函数
来源：http://dali.shuidangran.top/Article/details/gtvnxuhxhe.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.chenzaomai.com/Article/details/gteqrdscpu.html

[S30] C：头文件保护
来源：http://dali.cdnleiting.top/Article/details/gtothlzhnj.html

#ifndef X_H
来源：http://dali.smart0.xyz/Article/details/gtwotkpzxv.html

#define X_H
来源：http://dali.c1oappe.top/Article/details/gtjklxrjqn.html

#endif
来源：http://dali.bjfxy.top/Article/details/gtwxzqcdpq.html

[S31] C++：Hello World
来源：http://dali.nwbrower.top/Article/details/gtfxortihn.html

#include <iostream>
来源：http://dali.ppjwa.cn/Article/details/gttdvznulw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zdqjudy.top/Article/details/gtwlogfpxf.html

[S32] C++：字符串
来源：http://dali.shuidangran.top/Article/details/gtyemylvyz.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gtdzrvvtgh.html

[S33] C++：vector 增删
来源：http://dali.yvedp.cn/Article/details/gtopaaeduw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jiagoushi.top/Article/details/gtamnpwtqa.html

[S34] C++：遍历 vector
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwsuhidb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.haohaochexian.top/Article/details/gtyvrtiavc.html

[S35] C++：map
来源：http://dali.smart0.xyz/Article/details/gtjxdnndkk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtohzcrkpp.html

[S36] C++：unordered_map
来源：http://dali.guannengcc.top/Article/details/gtutwqnpuf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yueranfly.top/Article/details/gtpkpfhvsy.html

[S37] C++：set
来源：http://dali.aizwys.cn/Article/details/gtzyjhkanu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cucudq.cn/Article/details/gtchwxjxnk.html

[S38] C++：排序
来源：http://dali.haohaochexian.top/Article/details/gtjbqmxbko.html

std::sort(v.begin(), v.end());
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmxamivsr.html

[S39] C++：自定义比较器排序
来源：http://dali.zhongyouzk.top/Article/details/gtnuoswrrv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yangfankeji.com/Article/details/gtxiblfvye.html

[S40] C++：查找元素
来源：http://dali.zhiwuduotai.top/Article/details/gtmfkdblah.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.vqdsnc.cn/Article/details/gtxlegsaks.html

[S41] C++：类与构造函数
来源：http://dali.xuanzx.com/Article/details/gtzufbsnaj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.smart0.xyz/Article/details/gtfqzppctr.html

[S42] C++：继承与虚函数
来源：http://dali.nanxuanxn.top/Article/details/gtihrbjsbc.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhoulong.xyz/Article/details/gtabdcgert.html

[S43] C++：智能指针
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdkbbboap.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gtsygbbzei.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gtzrsmfhaq.html

void inc(int &x) { ++x; }
来源：http://dali.hfpthk.cn/Article/details/gtzhglyoyl.html

[S45] C++：lambda
来源：http://dali.yongpay.top/Article/details/gtnpvygaxe.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zdqjudy.top/Article/details/gtpagvhkud.html

[S46] C++：函数模板
来源：http://dali.andypj.xyz/Article/details/gtkbhimbpp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yueranfly.top/Article/details/gtvoxbrsup.html

[S47] C++：结构化绑定遍历
来源：http://dali.sysykeji.top/Article/details/gtqrxjgmfb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.vqdsnc.cn/Article/details/gtklhomigc.html

[S48] C++：逐行读文件
来源：http://dali.wangdashe.top/Article/details/gtsaupjcdp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.0kj1m.cn/Article/details/gtzswwmgqe.html

while (std::getline(in, line)) { }
来源：http://dali.gaohongyu789.top/Article/details/gtjuhyxhwd.html

[S49] C++：写文件
来源：http://dali.wangdashe.top/Article/details/gttkrwghkp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.svipenyu.cn/Article/details/gtzfhfyngy.html

[S50] C++：格式化数字
来源：http://dali.smart0.xyz/Article/details/gtwcrtssdm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yanxiufei.cn/Article/details/gtoxfdrtqt.html

[S51] C++：显式类型转换
来源：http://dali.hnxiangtu.top/Article/details/gtdpilukoh.html

static_cast<double>(a) / b
来源：http://dali.yangfankeji.com/Article/details/gtggqujxvc.html

[S52] C++：const 与 noexcept
来源：http://dali.xinyue.icu/Article/details/gteugjczal.html

int size() const noexcept { return n_; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlmqtjrvm.html

[S53] C++：移动语义
来源：http://dali.jinghuilouyu.cn/Article/details/gthvglmkxy.html

std::vector<int> w = std::move(v);
来源：http://dali.zycfv.cn/Article/details/gtwcagesgl.html

[S54] C++：异常处理
来源：http://dali.shanyushiyangtech.top/Article/details/gtejmbbwhr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.smart0.xyz/Article/details/gtghlaoidh.html

[S55] C++：结构化绑定
来源：http://dali.hfpthk.cn/Article/details/gthiretyjo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.aizwys.cn/Article/details/gtfvzrgxiq.html

[S56] C++：optional
来源：http://dali.sweek.top/Article/details/gtprwenfeu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.pycfn.com/Article/details/gtwcbdkoem.html

[S57] C++：编译期常量
来源：http://dali.yj20258.top/Article/details/gtnuscwnnc.html

constexpr int N = 10;
来源：http://dali.dashuyun.cn/Article/details/gtachokeyf.html

[S58] C++：命名空间
来源：http://dali.iojbl.cn/Article/details/gtwlplnqpu.html

namespace ns { int f() { return 1; } }
来源：http://dali.gaohongyu789.top/Article/details/gtjscstlcw.html

[S59] C++：静态断言
来源：http://dali.tianlin.xyz/Article/details/gtwwegpsgu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhengqikj.top/Article/details/gtmdmgmtzr.html

[S60] C++：遍历并删除元素
来源：http://dali.hammf.cn/Article/details/gtcojhdxoj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sxryk.cn/Article/details/gtgspyxpbk.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtjcvolijz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cheryme.top/Article/details/gtrdjmsoli.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtpxsmqynq.html

[T01] Kotlin：Hello World
来源：http://dali.meibo888.top/Article/details/gtiopaxoqr.html

println("Hello")
来源：http://dali.xziqi.cn/Article/details/gtvtfoetal.html

[T02] Kotlin：变量
来源：http://dali.yuanzhike.top/Article/details/gtjlricbqx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yuxming.cn/Article/details/gtjjpjsbfw.html

[T03] Kotlin：字符串模板
来源：http://dali.vqdsnc.cn/Article/details/gtpybpwpwp.html

"值: $b"
来源：http://dali.jianghu66.top/Article/details/gtugepoisy.html

[T04] Kotlin：空安全
来源：http://dali.shangyingyoupin.top/Article/details/gtetonapov.html

val n: String? = null;  n?.length
来源：http://dali.hywenlv.cn/Article/details/gtmqduujyw.html

[T05] Kotlin：when 表达式
来源：http://dali.bjfxy.top/Article/details/gtmblyakdr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.chenlongwang.top/Article/details/gtbqpumode.html

[T06] Kotlin：集合映射
来源：http://dali.wangdashe.top/Article/details/gtleyfzyib.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hnqzz.top/Article/details/gtrytsbzyn.html

[T07] Kotlin：集合过滤
来源：http://dali.hfpthk.cn/Article/details/gtdcocatrx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.tian-w.cn/Article/details/gtluxfzrvs.html

[T08] Kotlin：数据类
来源：http://dali.zycfv.cn/Article/details/gtxxwkauar.html

data class User(val name: String, val age: Int)
来源：http://dali.yj20258888.top/Article/details/gtufwnuxfe.html

[T09] Kotlin：扩展函数
来源：http://dali.pycfn.com/Article/details/gtpwjpgjsb.html

fun String.exclaim() = this + "!"
来源：http://dali.dashuyun.cn/Article/details/gtuordyrbt.html

[T10] Kotlin：默认参数
来源：http://dali.sufxvd.cn/Article/details/gtixntreey.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cheryme.top/Article/details/gtcqcmvcfd.html

[T11] Kotlin：协程
来源：http://dali.yvedp.cn/Article/details/gtapjsylrp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yj202588.top/Article/details/gtbcgapwwm.html

[T12] Kotlin：解构声明
来源：http://dali.ivvv.top/Article/details/gtsxsicfbj.html

val (a, b) = Pair(1, 2)
来源：http://dali.jianghu66.top/Article/details/gttowvmaky.html

[T13] Kotlin：只读 Map
来源：http://dali.haohaochexian.top/Article/details/gtosnzjvcs.html

val m = mapOf("a" to 1)
来源：http://dali.haohaochexian.top/Article/details/gtucbuszfg.html

[T14] Kotlin：循环
来源：http://dali.ehwqpu.com/Article/details/gtvgydpvwl.html

for (i in 1..10) println(i)
来源：http://dali.gotoacloud.top/Article/details/gtuvkbprph.html

[T15] Kotlin：接口
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaswfubtp.html

interface Shape { fun area(): Double }
来源：http://dali.andypj.xyz/Article/details/gtcmehafqy.html

[T16] Swift：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gtbobobbnh.html

print("Hello")
来源：http://dali.jiagoushi.top/Article/details/gtmtgpnmsp.html

[T17] Swift：变量与常量
来源：http://dali.nanxinkj.top/Article/details/gtxtujcnif.html

var a = 1;  let b = 2
来源：http://dali.zycfv.cn/Article/details/gtdyqnfjyw.html

[T18] Swift：字符串插值
来源：http://dali.pengpengdd.cyou/Article/details/gtlinurvvh.html

"值: \(b)"
来源：http://dali.xuanzx.com/Article/details/gtmvghblcw.html

[T19] Swift：可选绑定
来源：http://dali.feifeiyinyue.top/Article/details/gtnprwfhvg.html

if let n = opt { print(n) }
来源：http://dali.hnqzz.top/Article/details/gtukcsrorl.html

[T20] Swift：数组操作
来源：http://dali.shangyingyoupin.top/Article/details/gtimvouyfm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.wangdashe.top/Article/details/gtujtvdakj.html

[T21] Swift：遍历
来源：http://dali.zycfv.cn/Article/details/gtkuuqpflo.html

for x in a { print(x) }
来源：http://dali.dashuyun.cn/Article/details/gtchykfeew.html

[T22] Swift：字典
来源：http://dali.yueranfly.top/Article/details/gtcaiohgug.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cdnleiting.top/Article/details/gtobdqkvud.html

[T23] Swift：函数
来源：http://dali.guannengcc.top/Article/details/gtfpqvbjte.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.birdmap.top/Article/details/gtigkhkiky.html

[T24] Swift：闭包
来源：http://dali.sufxvd.cn/Article/details/gtkfkwheyn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xinyue.icu/Article/details/gtphrfwszk.html

[T25] Swift：结构体
来源：http://dali.9152youxi.cn/Article/details/gtuaszwxih.html

struct P { var x: Int }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmpbomqcv.html

[T26] Swift：类与重写
来源：http://dali.ppjwa.cn/Article/details/gtilgmnvet.html

class A: Base { override func f() {} }
来源：http://dali.svipenyu.cn/Article/details/gtwtxqsxqc.html

[T27] Swift：错误处理
来源：http://dali.zycfv.cn/Article/details/gtdvmgpjyh.html

do { try f() } catch { print(error) }
来源：http://dali.svipenyu.cn/Article/details/gttcdizyps.html

[T28] Swift：枚举
来源：http://dali.sxryk.cn/Article/details/gtpxwhznwp.html

enum Color { case red, green }
来源：http://dali.bjfxy.top/Article/details/gtomfqmdzr.html

[T29] Swift：guard 提前返回
来源：http://dali.quarkkingdee.top/Article/details/gteciaczqq.html

guard let x = opt else { return }
来源：http://dali.cqqwz.cn/Article/details/gtnktwyfma.html

[T30] Swift：协议
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqboujikk.html

protocol Shape { func area() -> Double }
来源：http://dali.tanke756.top/Article/details/gtfobeslkh.html

[T31] Lua：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtxtkzrfvu.html

print("Hello")
来源：http://dali.jianghu66.top/Article/details/gtneijyexm.html

[T32] Lua：局部变量
来源：http://dali.kuanghao11.cn/Article/details/gtjxjunqfu.html

local a = 1
来源：http://dali.zhongyouzk.top/Article/details/gtejmtayeq.html

[T33] Lua：表（数组）
来源：http://dali.fzhhl.top/Article/details/gthxegtiqb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.haohaochexian.top/Article/details/gtlyhpschb.html

[T34] Lua：遍历表
来源：http://dali.haohaochexian.top/Article/details/gtjvbqsfsi.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhongyouzk.top/Article/details/gtmlohxqpb.html

[T35] Lua：字典表
来源：http://dali.dianchejie.cn/Article/details/gtcayjilfe.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shangyingyoupin.top/Article/details/gtertejdbu.html

[T36] Lua：函数
来源：http://dali.jinqigufen.top/Article/details/gtawoebbwn.html

function add(a, b) return a + b end
来源：http://dali.ppjwa.cn/Article/details/gtdhjarepm.html

[T37] Lua：字符串拼接
来源：http://dali.hammf.cn/Article/details/gtunhwmhag.html

"a" .. "b"
来源：http://dali.zhoulong.xyz/Article/details/gtddovtarr.html

[T38] Lua：条件
来源：http://dali.ybcxt.top/Article/details/gtpnhjugiq.html

if x > 0 then print("正") end
来源：http://dali.meibo888.top/Article/details/gthfklgnjf.html

[T39] Lua：模式匹配
来源：http://dali.xziqi.cn/Article/details/gtzyxzoexn.html

string.find(s, "%d+")
来源：http://dali.aibaodan.cn/Article/details/gtnmfhopfw.html

[T40] Lua：元表
来源：http://dali.quarkkingdee.top/Article/details/gtljtnfawh.html

setmetatable({}, { __index = base })
来源：http://dali.ppjwa.cn/Article/details/gtychaymdu.html

[T41] Perl：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtcpvdriud.html

print "Hello\n";
来源：http://dali.xylfe.cn/Article/details/gtpgausjml.html

[T42] Perl：变量类型
来源：http://dali.ehwqpu.com/Article/details/gthbxxaenf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.gogol.net.cn/Article/details/gtmfvnjtha.html

[T43] Perl：字符串插值
来源：http://dali.jyoumei.cn/Article/details/gtwmeziwen.html

"值: $a"
来源：http://dali.jinqigufen.top/Article/details/gtmzbuyleb.html

[T44] Perl：条件
来源：http://dali.iojbl.cn/Article/details/gtrxynhjdi.html

if ($a > 0) { print "正"; }
来源：http://dali.yj20258.top/Article/details/gtvkvhotkt.html

[T45] Perl：数组遍历
来源：http://dali.aizwys.cn/Article/details/gtajvipiss.html

for my $x (@arr) { print $x; }
来源：http://dali.svipenyu.cn/Article/details/gtinyuefpj.html

[T46] Perl：哈希操作
来源：http://dali.tian-w.cn/Article/details/gtbotnnsja.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.snrcjt.cn/Article/details/gtwjjfsbtg.html

[T47] Perl：正则捕获
来源：http://dali.vqdsnc.cn/Article/details/gtytpqtusi.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yuanzhike.top/Article/details/gtsaesafoh.html

[T48] Perl：正则替换
来源：http://dali.shangyingyoupin.top/Article/details/gtbpcxqimc.html

$s =~ s/old/new/g;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtybdtiqse.html

[T49] Perl：函数
来源：http://dali.ehwqpu.com/Article/details/gtpakaazjf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.wangdashe.top/Article/details/gtyawwcijm.html

[T50] Perl：逐行读文件
来源：http://dali.pycfn.com/Article/details/gtacmfjkmt.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gtlrdcobvx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.cashguo.top/Article/details/gtaxjcjfea.html

[T51] Scala：Hello World
来源：http://dali.ivvv.top/Article/details/gtybvyhzzk.html

println("Hello")
来源：http://dali.gogol.net.cn/Article/details/gthrhpghnl.html

[T52] Scala：变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gteajejaol.html


<!-- 参考信息 -->