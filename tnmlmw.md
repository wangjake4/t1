代发 wailian999

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.fengsongda.top/Article/details/gtptzeojzd.html

[R50] awk 求和
来源：http://dali.zhixingplan.top/Article/details/gtfwkwcuit.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hammf.cn/Article/details/gtoehgoyli.html

[R51] 排序去重取前几
来源：http://dali.tianlin.xyz/Article/details/gtomphkssj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.sweek.top/Article/details/gtnsghlyww.html

[R52] 统计行数
来源：http://dali.mhx1999.top/Article/details/gtdfrekzzt.html

wc -l a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtmhrjcddf.html

[R53] 查看文件头与实时尾
来源：http://dali.smart0.xyz/Article/details/gtnlaxdfqf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.fzhhl.top/Article/details/gtgpkftcxl.html

[R54] 比较两个文件
来源：http://dali.0kj1m.cn/Article/details/gthwfkfeny.html

diff a.txt b.txt
来源：http://dali.gotoacloud.top/Article/details/gtihphetwn.html

[R55] 压缩与解压
来源：http://dali.cashguo.top/Article/details/gtpuryqkhr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.nanxuanxn.top/Article/details/gtbjkwdbfh.html

[R56] 远程拷贝
来源：http://dali.xuanzx.com/Article/details/gtrkkqqruh.html

scp file user@host:/path/
来源：http://dali.yj20258888.top/Article/details/gtoqndkyqg.html

[R57] 远程执行命令
来源：http://dali.andypj.xyz/Article/details/gtffjmsjas.html

ssh user@host 'uptime'
来源：http://dali.yj20258888.top/Article/details/gtcmpnycqo.html

[R58] 下载文件
来源：http://dali.yanxiufei.cn/Article/details/gtytemknez.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.aizwys.cn/Article/details/gtdxohwlmb.html

[R59] 发 POST JSON
来源：http://dali.ppjwa.cn/Article/details/gtjxglalom.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ivvv.top/Article/details/gtqtnkpddt.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinqigufen.top/Article/details/gtlqgdwzvd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.0kj1m.cn/Article/details/gtipyrcxjl.html

[R61] 磁盘占用
来源：http://dali.shuidangran.top/Article/details/gtehqlsept.html

df -h;  du -sh *
来源：http://dali.sxryk.cn/Article/details/gtagwlsnth.html

[R62] 找最占空间的文件
来源：http://dali.zhiwuduotai.top/Article/details/gteoskwlck.html

du -ah . | sort -rh | head -10
来源：http://dali.guannengcc.top/Article/details/gtwhiqlamz.html

[R63] 内存与进程
来源：http://dali.birdmap.top/Article/details/gtqumnpoxg.html

free -h;  ps aux | grep nginx
来源：http://dali.snrcjt.cn/Article/details/gtwfjnwivm.html

[R64] 结束进程
来源：http://dali.yuxming.cn/Article/details/gtmleiepfr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.havefunace.top/Article/details/gtfzzqeipc.html

[R65] 查看端口占用
来源：http://dali.yongpay.top/Article/details/gtusazcleg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hywenlv.cn/Article/details/gtfhkkdqpt.html

[R66] 定时任务
来源：http://dali.hnxiangtu.top/Article/details/gtfovytqeq.html

crontab -e;  crontab -l
来源：http://dali.xinyue.icu/Article/details/gtjjuxrwyv.html

[R67] 生成随机十六进制串
来源：http://dali.zdqjudy.top/Article/details/gtmvmqkdxl.html

openssl rand -hex 16
来源：http://dali.iojbl.cn/Article/details/gtgklpkrxn.html

[R68] 计算文件校验值
来源：http://dali.gotoacloud.top/Article/details/gtljkothfb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtubdiqlmo.html

[R69] 生成随机密码
来源：http://dali.jyoumei.cn/Article/details/gtclquxwmt.html

head -c 16 /dev/urandom | base64
来源：http://dali.dianchejie.cn/Article/details/gtutqyduws.html

[R70] 时间戳与互转
来源：http://dali.chenjidiqi.icu/Article/details/gtqmqyzbhn.html

date +%s;  date -d @1700000000
来源：http://dali.chenjidiqi.icu/Article/details/gtuebyfmik.html

[R71] 日期格式化
来源：http://dali.zhixingplan.top/Article/details/gttgjsvzzt.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.pycfn.com/Article/details/gtriyrlesj.html

[R72] 等待端口就绪
来源：http://dali.vqdsnc.cn/Article/details/gtezpwdaec.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.meibo888.top/Article/details/gtegqqdlqg.html

[R73] 分割大日志
来源：http://dali.sysykeji.top/Article/details/gthyemaeae.html

split -l 1000 big.log part_
来源：http://dali.jinyuanbaomall.cn/Article/details/gthkhqknht.html

[R74] 批量重命名
来源：http://dali.redwolf501.top/Article/details/gtcnmbnzkk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhengqikj.top/Article/details/gtnnwgbwyy.html

[R75] 导出环境变量
来源：http://dali.tianlin.xyz/Article/details/gtdmwaanjn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.316326.xyz/Article/details/gttquweynu.html

[R76] 使用临时文件
来源：http://dali.zhoulong.xyz/Article/details/gtfsbwzxth.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ehwqpu.com/Article/details/gtxywilvxj.html

[R77] 读取用户输入
来源：http://dali.yongpay.top/Article/details/gtuxqjfafz.html

read -rp "请输入: " ans
来源：http://dali.yuanzhike.top/Article/details/gttliojfpe.html

[R78] 交互式菜单
来源：http://dali.hnqzz.top/Article/details/gtqjlcatyv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ybcxt.top/Article/details/gtloqdsaid.html

[R79] 解析命令行选项
来源：http://dali.guowangkeji.top/Article/details/gtshuybimu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.haohaochexian.top/Article/details/gtyzmcjkwz.html

[R80] 查看脚本执行耗时
来源：http://dali.dashuyun.cn/Article/details/gthirezcas.html

time ./run.sh
来源：http://dali.sufxvd.cn/Article/details/gtwvnqpfnp.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtmswknqgy.html

S. C / C++ 专题
来源：http://dali.jyoumei.cn/Article/details/gtsfytwwnq.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtmupjqldv.html

[S01] C：Hello World
来源：http://dali.yvedp.cn/Article/details/gtgerexqha.html

#include <stdio.h>
来源：http://dali.ehwqpu.com/Article/details/gtjertzamy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.redwolf501.top/Article/details/gthqnrekjg.html

[S02] C：变量与格式化输出
来源：http://dali.ppjwa.cn/Article/details/gtdvlrumxp.html

int a = 10; printf("%d\n", a);
来源：http://dali.ybcxt.top/Article/details/gtitloavuz.html

[S03] C：读入整数
来源：http://dali.xziqi.cn/Article/details/gtswbkmoyg.html

int x; scanf("%d", &x);
来源：http://dali.yonumen.top/Article/details/gtjlosgekj.html

[S04] C：字符串复制
来源：http://dali.wangshuangyany.cn/Article/details/gtpiynfqgq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yangfankeji.com/Article/details/gtzgblfxen.html

[S05] C：字符串长度
来源：http://dali.yuanzhike.top/Article/details/gtjoosjcvm.html

strlen(s)
来源：http://dali.sweek.top/Article/details/gtiqqxftae.html

[S06] C：字符串比较
来源：http://dali.havefunace.top/Article/details/gtuzgwnaez.html

strcmp(a, b) == 0
来源：http://dali.jinqigfzy.top/Article/details/gtesebmnum.html

[S07] C：数组遍历求和
来源：http://dali.ybcxt.top/Article/details/gtbhdojues.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.wangshuangyany.cn/Article/details/gtfcudskck.html

[S08] C：动态内存分配与释放
来源：http://dali.feifeiyinyue.top/Article/details/gtpxaqmnga.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.chenzaomai.com/Article/details/gttsvcjiuv.html

[S09] C：结构体定义与初始化
来源：http://dali.tanke756.top/Article/details/gtmsusdghk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hysaishi.cn/Article/details/gtwvgyzjsh.html

[S10] C：指针与解引用
来源：http://dali.birdmap.top/Article/details/gtsmaywpja.html

int *p = &a;  *p = 5;
来源：http://dali.xinyue.icu/Article/details/gtkvckwcjs.html

[S11] C：逐行读文件
来源：http://dali.guannengcc.top/Article/details/gttygwepxh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfwtomjlg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hywenlv.cn/Article/details/gtkymbrviq.html

fclose(f);
来源：http://dali.sufxvd.cn/Article/details/gtpzditjbt.html

[S12] C：写文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtixcihjor.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhongyouzk.top/Article/details/gtjzqxokqk.html

[S13] C：宏定义
来源：http://dali.yongpay.top/Article/details/gtldowdfis.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gtirjrnyji.html

[S14] C：枚举
来源：http://dali.xinyue.icu/Article/details/gtmnqygelt.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hnxiangtu.top/Article/details/gtwtpegbrm.html

[S15] C：类型转换
来源：http://dali.birdmap.top/Article/details/gtjmndhrss.html

(double) a / b
来源：http://dali.xuetiantiany.cn/Article/details/gtgleuaxof.html

[S16] C：位操作置位
来源：http://dali.hammf.cn/Article/details/gtqjgpkklr.html

x |= (1 << 3);
来源：http://dali.shuidangran.top/Article/details/gtrnehtyue.html

[S17] C：安全拼接字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtodczffyi.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jiagoushi.top/Article/details/gtnztipive.html

[S18] C：命令行参数
来源：http://dali.vqdsnc.cn/Article/details/gtqerrxknm.html

int main(int argc, char **argv)
来源：http://dali.hnxiangtu.top/Article/details/gtwhysqujd.html

[S19] C：快速排序
来源：http://dali.hfpthk.cn/Article/details/gtxdpahwxj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhongyouzk.top/Article/details/gtxlbqstiw.html

[S20] C：二分查找
来源：http://dali.gotoacloud.top/Article/details/gtixxengrx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.nwbrower.top/Article/details/gtbahtqizm.html

[S21] C：字符类别判断
来源：http://dali.zhixingplan.top/Article/details/gtoywppoce.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.daxiang520.top/Article/details/gtrnlsmoey.html

[S22] C：字符串转数字
来源：http://dali.cqqwz.cn/Article/details/gtrehfwuyo.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xuanzx.com/Article/details/gtrxvprgso.html

[S23] C：随机数
来源：http://dali.yj20258888.top/Article/details/gtsyukocjo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhixingplan.top/Article/details/gtlxtvgqqe.html

[S24] C：获取本地时间
来源：http://dali.bjfxy.top/Article/details/gtfkqamgsx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sxryk.cn/Article/details/gtcsqhmvrt.html

[S25] C：内存拷贝
来源：http://dali.jyoumei.cn/Article/details/gtmamottfk.html

memcpy(dst, src, n);
来源：http://dali.hnqzz.top/Article/details/gtgrlqtlju.html

[S26] C：内存清零
来源：http://dali.xinyue.icu/Article/details/gtobiunhui.html

memset(a, 0, sizeof a);
来源：http://dali.wangshuangyany.cn/Article/details/gtinonfodb.html

[S27] C：定义常量
来源：http://dali.yongpay.top/Article/details/gtecwhewgb.html

const double PI = 3.14159;
来源：http://dali.gaohongyu789.top/Article/details/gtpdjjpajd.html

[S28] C：静态变量
来源：http://dali.havefunace.top/Article/details/gtodxwzjxo.html

static int counter = 0;
来源：http://dali.dianchejie.cn/Article/details/gtavyhwekm.html

[S29] C：变参函数
来源：http://dali.gaohongyu789.top/Article/details/gtyoorgaxg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xylfe.cn/Article/details/gtpqrqmycs.html

[S30] C：头文件保护
来源：http://dali.nanxuanxn.top/Article/details/gtzwrjjmcz.html

#ifndef X_H
来源：http://dali.dashuyun.cn/Article/details/gtmrhgjdta.html

#define X_H
来源：http://dali.shuidangran.top/Article/details/gtkeqrpcsl.html

#endif
来源：http://dali.jqgfzy.top/Article/details/gtcegzfxxp.html

[S31] C++：Hello World
来源：http://dali.hnqzz.top/Article/details/gtsclhxsyg.html

#include <iostream>
来源：http://dali.andypj.xyz/Article/details/gtvqjdohyf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jinqigufen.top/Article/details/gtsyinsnor.html

[S32] C++：字符串
来源：http://dali.kuanghao11.cn/Article/details/gtbhntbcpw.html

std::string s = "hi";  s += "!";
来源：http://dali.ybcxt.top/Article/details/gtkttffqii.html

[S33] C++：vector 增删
来源：http://dali.zhengqikj.top/Article/details/gtepxabned.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cheryme.top/Article/details/gtpwjtzbzk.html

[S34] C++：遍历 vector
来源：http://dali.xylfe.cn/Article/details/gthlpkfalk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.birdmap.top/Article/details/gtlndumlfs.html

[S35] C++：map
来源：http://dali.dashuyun.cn/Article/details/gtosoeqfyr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ppjwa.cn/Article/details/gteczhukzp.html

[S36] C++：unordered_map
来源：http://dali.sxryk.cn/Article/details/gtwpfgpbhs.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.snrcjt.cn/Article/details/gtarldkfil.html

[S37] C++：set
来源：http://dali.xylfe.cn/Article/details/gttoskxwgp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yonumen.top/Article/details/gtfxxvoahi.html

[S38] C++：排序
来源：http://dali.9152youxi.cn/Article/details/gtqvqdqcyc.html

std::sort(v.begin(), v.end());
来源：http://dali.zhoulong.xyz/Article/details/gtbszgoxep.html

[S39] C++：自定义比较器排序
来源：http://dali.zycfv.cn/Article/details/gtqdcqiiww.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.haohaochexian.top/Article/details/gtpnfbcpep.html

[S40] C++：查找元素
来源：http://dali.pycfn.com/Article/details/gtmerdccap.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.9152youxi.cn/Article/details/gtzrzbrkct.html

[S41] C++：类与构造函数
来源：http://dali.hfpthk.cn/Article/details/gtgxesmqbf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jyoumei.cn/Article/details/gthvbkhhqp.html

[S42] C++：继承与虚函数
来源：http://dali.gaohongyu789.top/Article/details/gtzdtgnebm.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhoulong.xyz/Article/details/gtgissvxzd.html

[S43] C++：智能指针
来源：http://dali.ivvv.top/Article/details/gtrjjwgiqu.html

auto p = std::make_unique<int>(5);
来源：http://dali.jiagoushi.top/Article/details/gtimtzkklw.html

[S44] C++：引用传参
来源：http://dali.ivvv.top/Article/details/gtmgwpypov.html

void inc(int &x) { ++x; }
来源：http://dali.sufxvd.cn/Article/details/gtulwnuapj.html

[S45] C++：lambda
来源：http://dali.zhongyouzk.top/Article/details/gtbzqmgvke.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.chenlongwang.top/Article/details/gtmhivyviw.html

[S46] C++：函数模板
来源：http://dali.zhoulong.xyz/Article/details/gtkznnfvkb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yuanzhike.top/Article/details/gtxvxnapac.html

[S47] C++：结构化绑定遍历
来源：http://dali.tianlin.xyz/Article/details/gtjvkcacmt.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ivvv.top/Article/details/gtalvelzcz.html

[S48] C++：逐行读文件
来源：http://dali.fengsongda.top/Article/details/gtglrdxuhh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cheryme.top/Article/details/gtvqlgkkkd.html

while (std::getline(in, line)) { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtohdcpaal.html

[S49] C++：写文件
来源：http://dali.yj20258.top/Article/details/gtvufqrpqx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yj20258.top/Article/details/gtbssbpiku.html

[S50] C++：格式化数字
来源：http://dali.tanke756.top/Article/details/gtsoqhkssi.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cashguo.top/Article/details/gtlepqcgny.html

[S51] C++：显式类型转换
来源：http://dali.andypj.xyz/Article/details/gtztvhuipy.html

static_cast<double>(a) / b
来源：http://dali.chenlongwang.top/Article/details/gtuqjbwuin.html

[S52] C++：const 与 noexcept
来源：http://dali.jqgfzy.top/Article/details/gtgvpacjpi.html

int size() const noexcept { return n_; }
来源：http://dali.meibo888.top/Article/details/gtkphjcqcr.html

[S53] C++：移动语义
来源：http://dali.wangshuangyany.cn/Article/details/gtqkjjvmrj.html

std::vector<int> w = std::move(v);
来源：http://dali.yangfankeji.com/Article/details/gtcqjfaubk.html

[S54] C++：异常处理
来源：http://dali.yj20258888.top/Article/details/gtyuogqohh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.fengsongda.top/Article/details/gtmeanmsvb.html

[S55] C++：结构化绑定
来源：http://dali.gaohongyu789.top/Article/details/gtgdqnpsjp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.aibaodan.cn/Article/details/gthwetvumh.html

[S56] C++：optional
来源：http://dali.mhx1999.top/Article/details/gtayxwbzql.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cqqwz.cn/Article/details/gtrqpxkgek.html

[S57] C++：编译期常量
来源：http://dali.jlsjyb.cn/Article/details/gtxutyqswm.html

constexpr int N = 10;
来源：http://dali.yongpay.top/Article/details/gtzkzfqfny.html

[S58] C++：命名空间
来源：http://dali.shangyingyoupin.top/Article/details/gtxchpyqpa.html

namespace ns { int f() { return 1; } }
来源：http://dali.smart0.xyz/Article/details/gtbyindllh.html

[S59] C++：静态断言
来源：http://dali.ywan-chungtsiang.top/Article/details/gthbarlzbt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.fzhhl.top/Article/details/gtobxiangc.html

[S60] C++：遍历并删除元素
来源：http://dali.jianghu66.top/Article/details/gtmodpzysl.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.mhx1999.top/Article/details/gtmjupeagr.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtplpgobze.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhixingplan.top/Article/details/gtfxfbljnd.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtnnptowmj.html

[T01] Kotlin：Hello World
来源：http://dali.ydzc1.top/Article/details/gtuhvqacjp.html

println("Hello")
来源：http://dali.ydzc1.top/Article/details/gtswwsrqbe.html

[T02] Kotlin：变量
来源：http://dali.jlsjyb.cn/Article/details/gteyyswagf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.chenzaomai.com/Article/details/gttnqfwwnp.html

[T03] Kotlin：字符串模板
来源：http://dali.gogol.net.cn/Article/details/gtedbjlkat.html

"值: $b"
来源：http://dali.jinqigfzy.top/Article/details/gtupulscpx.html

[T04] Kotlin：空安全
来源：http://dali.xuanzx.com/Article/details/gtrgzxsdxs.html

val n: String? = null;  n?.length
来源：http://dali.redwolf501.top/Article/details/gtovvfizym.html

[T05] Kotlin：when 表达式
来源：http://dali.fzhhl.top/Article/details/gtadybcymz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jlsjyb.cn/Article/details/gtlnzlkbua.html

[T06] Kotlin：集合映射
来源：http://dali.tianlin.xyz/Article/details/gtumerrwcn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yuanzhike.top/Article/details/gtsqhahbfj.html

[T07] Kotlin：集合过滤
来源：http://dali.havefunace.top/Article/details/gtwxlwaagr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.haohaochexian.top/Article/details/gtgfumefjj.html

[T08] Kotlin：数据类
来源：http://dali.zhengqikj.top/Article/details/gtgqvvllcr.html

data class User(val name: String, val age: Int)
来源：http://dali.9152youxi.cn/Article/details/gthrmflqow.html

[T09] Kotlin：扩展函数
来源：http://dali.sufxvd.cn/Article/details/gtolqkvqts.html

fun String.exclaim() = this + "!"
来源：http://dali.yonumen.top/Article/details/gtmrktpiiw.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gtxwqoqews.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.guannengcc.top/Article/details/gtbrcwptuv.html

[T11] Kotlin：协程
来源：http://dali.hnqzz.top/Article/details/gtdeasczsz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.mhx1999.top/Article/details/gtebbdinss.html

[T12] Kotlin：解构声明
来源：http://dali.daxiang520.top/Article/details/gtrocdgiew.html

val (a, b) = Pair(1, 2)
来源：http://dali.zycfv.cn/Article/details/gtcaqdbsmw.html

[T13] Kotlin：只读 Map
来源：http://dali.zhaomingkeji.xyz/Article/details/gtafhrkxbo.html

val m = mapOf("a" to 1)
来源：http://dali.yuxming.cn/Article/details/gtxxuynpdt.html

[T14] Kotlin：循环
来源：http://dali.hnqzz.top/Article/details/gtdzygqbzz.html

for (i in 1..10) println(i)
来源：http://dali.mhx1999.top/Article/details/gttvyrowfs.html

[T15] Kotlin：接口
来源：http://dali.xylfe.cn/Article/details/gtqqmzrzyz.html

interface Shape { fun area(): Double }
来源：http://dali.fengsongda.top/Article/details/gtjwadwnxj.html

[T16] Swift：Hello World
来源：http://dali.yvedp.cn/Article/details/gteklzmpsk.html

print("Hello")
来源：http://dali.pengpengdd.cyou/Article/details/gtxmrmnhit.html

[T17] Swift：变量与常量
来源：http://dali.yangfankeji.com/Article/details/gtyvipzyle.html

var a = 1;  let b = 2
来源：http://dali.chenjidiqi.icu/Article/details/gtxducxbik.html

[T18] Swift：字符串插值
来源：http://dali.316326.xyz/Article/details/gtosmdbkji.html

"值: \(b)"
来源：http://dali.hammf.cn/Article/details/gtnbjrkbcv.html

[T19] Swift：可选绑定
来源：http://dali.shanyushiyangkeji.top/Article/details/gtctzbqvjb.html

if let n = opt { print(n) }
来源：http://dali.guannengcc.top/Article/details/gtacahnpez.html

[T20] Swift：数组操作
来源：http://dali.zdqjudy.top/Article/details/gtuyrrkmvm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yangfankeji.com/Article/details/gtcfowqkhn.html

[T21] Swift：遍历
来源：http://dali.jianghu66.top/Article/details/gtlqlurses.html

for x in a { print(x) }
来源：http://dali.zhixingplan.top/Article/details/gtshdqxmlb.html

[T22] Swift：字典
来源：http://dali.sysykeji.top/Article/details/gtkbostryu.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhengqikj.top/Article/details/gtgmsrbfsp.html

[T23] Swift：函数
来源：http://dali.iojbl.cn/Article/details/gtorwyswrd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cashguo.top/Article/details/gtderxcszf.html

[T24] Swift：闭包
来源：http://dali.nanxuanxn.top/Article/details/gtwzlxcyjt.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.gzhubu.top/Article/details/gtqdwgoauo.html

[T25] Swift：结构体
来源：http://dali.haohaochexian.top/Article/details/gtdegtovyu.html

struct P { var x: Int }
来源：http://dali.pengpengdd.cyou/Article/details/gtkozdwcqt.html

[T26] Swift：类与重写
来源：http://dali.yj202588.top/Article/details/gtnctcnahv.html

class A: Base { override func f() {} }
来源：http://dali.dianchejie.cn/Article/details/gtafmlgejm.html

[T27] Swift：错误处理
来源：http://dali.ybcxt.top/Article/details/gtqkvjityb.html

do { try f() } catch { print(error) }
来源：http://dali.zhongyouzk.top/Article/details/gtsvlnqixn.html

[T28] Swift：枚举
来源：http://dali.jlsjyb.cn/Article/details/gtgdypfdou.html

enum Color { case red, green }
来源：http://dali.tian-w.cn/Article/details/gtaduxdcvr.html

[T29] Swift：guard 提前返回
来源：http://dali.nanxinkj.top/Article/details/gtgzpwlkck.html

guard let x = opt else { return }
来源：http://dali.yj20258888.top/Article/details/gtjztldaiq.html

[T30] Swift：协议
来源：http://dali.havefunace.top/Article/details/gtousdmurw.html

protocol Shape { func area() -> Double }
来源：http://dali.zhengqikj.top/Article/details/gtqrbnoawd.html

[T31] Lua：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtkiupznpw.html

print("Hello")
来源：http://dali.sysykeji.top/Article/details/gtsvvzbwwc.html

[T32] Lua：局部变量
来源：http://dali.xuanzx.com/Article/details/gtjypwtizi.html

local a = 1
来源：http://dali.yj20258888.top/Article/details/gtzgsxzbhd.html

[T33] Lua：表（数组）
来源：http://dali.wangdashe.top/Article/details/gtdcxzjkvs.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.wangshuangyany.cn/Article/details/gtqwldnpph.html

[T34] Lua：遍历表
来源：http://dali.iojbl.cn/Article/details/gtyiqwntbc.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.guannengcc.top/Article/details/gtzflcbozx.html

[T35] Lua：字典表
来源：http://dali.dianchejie.cn/Article/details/gtfakzvgbs.html

local d = { a = 1 };  d.b = 2
来源：http://dali.quarkkingdee.top/Article/details/gtvxfilzyt.html

[T36] Lua：函数
来源：http://dali.jqgfzy.top/Article/details/gttozngyav.html

function add(a, b) return a + b end
来源：http://dali.zycfv.cn/Article/details/gtsizmupbx.html

[T37] Lua：字符串拼接
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjhxatjmy.html

"a" .. "b"
来源：http://dali.tianlin.xyz/Article/details/gtyzydeuwt.html

[T38] Lua：条件
来源：http://dali.hnxiangtu.top/Article/details/gtmimaryqg.html

if x > 0 then print("正") end
来源：http://dali.chenlongwang.top/Article/details/gtbjwzpbrx.html

[T39] Lua：模式匹配
来源：http://dali.sweek.top/Article/details/gtnzrdfcef.html

string.find(s, "%d+")
来源：http://dali.fengsongda.top/Article/details/gtowbiajzc.html

[T40] Lua：元表
来源：http://dali.jinqigfzy.top/Article/details/gtmqimauig.html

setmetatable({}, { __index = base })
来源：http://dali.havefunace.top/Article/details/gtuwarmbnb.html

[T41] Perl：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtutnytvzx.html

print "Hello\n";
来源：http://dali.svipenyu.cn/Article/details/gtzkoijpdi.html

[T42] Perl：变量类型
来源：http://dali.zdqjudy.top/Article/details/gtkuqxbare.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.bjfxy.top/Article/details/gtctwylqsh.html

[T43] Perl：字符串插值
来源：http://dali.hnxiangtu.top/Article/details/gtqhzfgohr.html

"值: $a"
来源：http://dali.haohaochexian.top/Article/details/gtorvszypx.html

[T44] Perl：条件
来源：http://dali.fzhhl.top/Article/details/gtoqfxhbgk.html

if ($a > 0) { print "正"; }
来源：http://dali.pycfn.com/Article/details/gtwozwqwcu.html

[T45] Perl：数组遍历
来源：http://dali.c1oappe.top/Article/details/gtfocomvyj.html

for my $x (@arr) { print $x; }
来源：http://dali.cucudq.cn/Article/details/gtskiaxnkw.html

[T46] Perl：哈希操作
来源：http://dali.hysaishi.cn/Article/details/gtgqnhknkx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hfpthk.cn/Article/details/gtojchsdyv.html

[T47] Perl：正则捕获
来源：http://dali.yj20258888.top/Article/details/gtluqkkkpr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.feifeiyinyue.top/Article/details/gtqersdebj.html

[T48] Perl：正则替换
来源：http://dali.sxryk.cn/Article/details/gtxjynpnao.html

$s =~ s/old/new/g;
来源：http://dali.yj20258.top/Article/details/gtghhiqqil.html

[T49] Perl：函数
来源：http://dali.zhengqikj.top/Article/details/gtyyttssjd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yuanzhike.top/Article/details/gtgqyvctsb.html

[T50] Perl：逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gtlreelfzr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtosocpipt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yanxiufei.cn/Article/details/gtwjpdetcs.html

[T51] Scala：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtizqpxwvw.html

println("Hello")
来源：http://dali.redwolf501.top/Article/details/gtuggweond.html

[T52] Scala：变量
来源：http://dali.xziqi.cn/Article/details/gtaqoihiih.html


<!-- 参考信息 -->