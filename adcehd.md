代发 wailian999

find . -name "*.tmp" -delete
来源：http://dali.cheryme.top/Article/details/gtjowfprgc.html

[R46] 递归替换文件内容
来源：http://dali.zycfv.cn/Article/details/gterxowtfp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hfpthk.cn/Article/details/gtwntwikfl.html

[R47] sed 单行替换
来源：http://dali.jiagoushi.top/Article/details/gtaladyqot.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.c1oappe.top/Article/details/gteqruelby.html

[R48] awk 取指定列
来源：http://dali.jinghuilouyu.cn/Article/details/gtulrqduxp.html

awk '{print $1, $3}' a.txt
来源：http://dali.ehwqpu.com/Article/details/gtsejmrstm.html

[R49] awk 带条件
来源：http://dali.shuidangran.top/Article/details/gttdkpaxee.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sxryk.cn/Article/details/gtxejplrrr.html

[R50] awk 求和
来源：http://dali.nanxinkj.top/Article/details/gthdyifynj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hysaishi.cn/Article/details/gtqztwyobk.html

[R51] 排序去重取前几
来源：http://dali.svipenyu.cn/Article/details/gtsdwhuhwq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xinyue.icu/Article/details/gtsgumnorw.html

[R52] 统计行数
来源：http://dali.guowangkeji.top/Article/details/gthszyrccy.html

wc -l a.txt
来源：http://dali.tian-w.cn/Article/details/gtwtvkxmke.html

[R53] 查看文件头与实时尾
来源：http://dali.gotoacloud.top/Article/details/gtjlheqcss.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ehwqpu.com/Article/details/gtmptvxltc.html

[R54] 比较两个文件
来源：http://dali.gotoacloud.top/Article/details/gtseqsijdk.html

diff a.txt b.txt
来源：http://dali.hnqzz.top/Article/details/gtitqylzfk.html

[R55] 压缩与解压
来源：http://dali.feifeiyinyue.top/Article/details/gtbeqxykaf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jqgfzy.top/Article/details/gtyjfupsgq.html

[R56] 远程拷贝
来源：http://dali.zhixingplan.top/Article/details/gtacnwoelx.html

scp file user@host:/path/
来源：http://dali.hongshengwenyu.top/Article/details/gtgerrmlrf.html

[R57] 远程执行命令
来源：http://dali.gotoacloud.top/Article/details/gterwgzohb.html

ssh user@host 'uptime'
来源：http://dali.jinqigufen.top/Article/details/gthqqpoeib.html

[R58] 下载文件
来源：http://dali.guannengcc.top/Article/details/gtmdavxnst.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.aibaodan.cn/Article/details/gtnpicsqcc.html

[R59] 发 POST JSON
来源：http://dali.chenjidiqi.icu/Article/details/gtgexjtchn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.pycfn.com/Article/details/gtfxewnbza.html

[R60] 只看 HTTP 状态码
来源：http://dali.vqdsnc.cn/Article/details/gtoqjpjxsi.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jianghu66.top/Article/details/gtkfclhcca.html

[R61] 磁盘占用
来源：http://dali.9152youxi.cn/Article/details/gtobaoxeui.html

df -h;  du -sh *
来源：http://dali.gzhubu.top/Article/details/gtrasvopbn.html

[R62] 找最占空间的文件
来源：http://dali.smart0.xyz/Article/details/gtpnednryj.html

du -ah . | sort -rh | head -10
来源：http://dali.yongpay.top/Article/details/gthluuynja.html

[R63] 内存与进程
来源：http://dali.shanyushiyangtech.top/Article/details/gtvlodesni.html

free -h;  ps aux | grep nginx
来源：http://dali.tanke756.top/Article/details/gttivobalq.html

[R64] 结束进程
来源：http://dali.aizwys.cn/Article/details/gtyujoumor.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yongpay.top/Article/details/gtpmdubzzd.html

[R65] 查看端口占用
来源：http://dali.daria6918.cn/Article/details/gteylkvlhh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.0kj1m.cn/Article/details/gtxwulclpi.html

[R66] 定时任务
来源：http://dali.cqqwz.cn/Article/details/gtvwxrlhjs.html

crontab -e;  crontab -l
来源：http://dali.aizwys.cn/Article/details/gtxqcyqxss.html

[R67] 生成随机十六进制串
来源：http://dali.guannengcc.top/Article/details/gtxgfxqaqi.html

openssl rand -hex 16
来源：http://dali.sufxvd.cn/Article/details/gtvwcplowc.html

[R68] 计算文件校验值
来源：http://dali.yanxiufei.cn/Article/details/gtbwhrulxu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hywenlv.cn/Article/details/gtdgdelojk.html

[R69] 生成随机密码
来源：http://dali.aibaodan.cn/Article/details/gttxwlaqpm.html

head -c 16 /dev/urandom | base64
来源：http://dali.zycfv.cn/Article/details/gtvsoijlmg.html

[R70] 时间戳与互转
来源：http://dali.zhongyouzk.top/Article/details/gtkmqtxftx.html

date +%s;  date -d @1700000000
来源：http://dali.cucudq.cn/Article/details/gtobpvseis.html

[R71] 日期格式化
来源：http://dali.guannengcc.top/Article/details/gtdptfpmno.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cheryme.top/Article/details/gtqjewmhuz.html

[R72] 等待端口就绪
来源：http://dali.tian-w.cn/Article/details/gtdkzkiofz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.aizwys.cn/Article/details/gtfzgrazxd.html

[R73] 分割大日志
来源：http://dali.zhoulong.xyz/Article/details/gtkiwpqhcz.html

split -l 1000 big.log part_
来源：http://dali.aibaodan.cn/Article/details/gtukqvmsyr.html

[R74] 批量重命名
来源：http://dali.hywenlv.cn/Article/details/gtyscozlnx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.smart0.xyz/Article/details/gthigqzmfz.html

[R75] 导出环境变量
来源：http://dali.yonumen.top/Article/details/gtqbkwdnyb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.wangdashe.top/Article/details/gtkgwcggmt.html

[R76] 使用临时文件
来源：http://dali.yangfankeji.com/Article/details/gtbykztglf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gogol.net.cn/Article/details/gtemdpkcwy.html

[R77] 读取用户输入
来源：http://dali.yvedp.cn/Article/details/gtqcwmeioa.html

read -rp "请输入: " ans
来源：http://dali.shzxlz.cn/Article/details/gtuxmuttaw.html

[R78] 交互式菜单
来源：http://dali.xinyue.icu/Article/details/gtjoxsrhoh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hnqzz.top/Article/details/gtfhnvuilj.html

[R79] 解析命令行选项
来源：http://dali.meibo888.top/Article/details/gtwzzgqidf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xuetiantiany.cn/Article/details/gtkdxrmupu.html

[R80] 查看脚本执行耗时
来源：http://dali.sysykeji.top/Article/details/gtdcyuzotk.html

time ./run.sh
来源：http://dali.ppjwa.cn/Article/details/gtxqewjbay.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtsmyfkruz.html

S. C / C++ 专题
来源：http://dali.sysykeji.top/Article/details/gtofpcdjxv.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtdeoepjvx.html

[S01] C：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtoverjgzk.html

#include <stdio.h>
来源：http://dali.zhoulong.xyz/Article/details/gtptwcaytd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jiagoushi.top/Article/details/gtjpwcaiwq.html

[S02] C：变量与格式化输出
来源：http://dali.zycfv.cn/Article/details/gtivcreama.html

int a = 10; printf("%d\n", a);
来源：http://dali.dashuyun.cn/Article/details/gtcbrjwwls.html

[S03] C：读入整数
来源：http://dali.zdqjudy.top/Article/details/gtfhzbdwqr.html

int x; scanf("%d", &x);
来源：http://dali.shzxlz.cn/Article/details/gtzfimjtnk.html

[S04] C：字符串复制
来源：http://dali.jlsjyb.cn/Article/details/gtvaycbjgl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yangfankeji.com/Article/details/gtuzkzdyux.html

[S05] C：字符串长度
来源：http://dali.0kj1m.cn/Article/details/gtjmkraavl.html

strlen(s)
来源：http://dali.havefunace.top/Article/details/gtqdfqwatn.html

[S06] C：字符串比较
来源：http://dali.dashuyun.cn/Article/details/gtuviezavg.html

strcmp(a, b) == 0
来源：http://dali.zhoulong.xyz/Article/details/gtngdvepzu.html

[S07] C：数组遍历求和
来源：http://dali.dianchejie.cn/Article/details/gteinsiqlu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.birdmap.top/Article/details/gtuunivedd.html

[S08] C：动态内存分配与释放
来源：http://dali.chenzaomai.com/Article/details/gtwlrhzhij.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yj20258.top/Article/details/gtmiyynrrs.html

[S09] C：结构体定义与初始化
来源：http://dali.yonumen.top/Article/details/gtzkzuiwog.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinqigufen.top/Article/details/gtonzpqdck.html

[S10] C：指针与解引用
来源：http://dali.aizwys.cn/Article/details/gtbghsomzr.html

int *p = &a;  *p = 5;
来源：http://dali.aibaodan.cn/Article/details/gtsovsgsbx.html

[S11] C：逐行读文件
来源：http://dali.cqqwz.cn/Article/details/gtrbykfieu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yvedp.cn/Article/details/gtsuysepuh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.nanxuanxn.top/Article/details/gtvncrmoll.html

fclose(f);
来源：http://dali.zycfv.cn/Article/details/gtqujmzojp.html

[S12] C：写文件
来源：http://dali.jinqigufen.top/Article/details/gtqowpobts.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gtxvrmgyju.html

[S13] C：宏定义
来源：http://dali.aizwys.cn/Article/details/gtheqngsxf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhoulong.xyz/Article/details/gtpfijgjgd.html

[S14] C：枚举
来源：http://dali.andypj.xyz/Article/details/gtjbsgexzn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.fzhhl.top/Article/details/gtkztwgpzc.html

[S15] C：类型转换
来源：http://dali.yuanzhike.top/Article/details/gtmimlpgal.html

(double) a / b
来源：http://dali.gzhubu.top/Article/details/gtrozzlwmf.html

[S16] C：位操作置位
来源：http://dali.nwbrower.top/Article/details/gtetcfqnsa.html

x |= (1 << 3);
来源：http://dali.yangfankeji.com/Article/details/gtxxdpkevr.html

[S17] C：安全拼接字符串
来源：http://dali.hnqzz.top/Article/details/gtobjvjmcr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yuanzhike.top/Article/details/gtltdyhcaz.html

[S18] C：命令行参数
来源：http://dali.gogol.net.cn/Article/details/gtenxbujmf.html

int main(int argc, char **argv)
来源：http://dali.jinqigufen.top/Article/details/gtkkauawsq.html

[S19] C：快速排序
来源：http://dali.sufxvd.cn/Article/details/gtvhzblilq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yj202588.top/Article/details/gtzjnzqjsa.html

[S20] C：二分查找
来源：http://dali.pycfn.com/Article/details/gtobeyvhgx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tanke756.top/Article/details/gtjrevklkf.html

[S21] C：字符类别判断
来源：http://dali.dianchejie.cn/Article/details/gtxeizwwnl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.fengsongda.top/Article/details/gtxulaozxq.html

[S22] C：字符串转数字
来源：http://dali.yanxiufei.cn/Article/details/gthtzeasau.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xinyue.icu/Article/details/gtatmlmtwh.html

[S23] C：随机数
来源：http://dali.pycfn.com/Article/details/gttkqukzdl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yonumen.top/Article/details/gtwnmannyb.html

[S24] C：获取本地时间
来源：http://dali.cashguo.top/Article/details/gtrzahakux.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhixingplan.top/Article/details/gtxhqdgfng.html

[S25] C：内存拷贝
来源：http://dali.cheryme.top/Article/details/gtntrxmbkt.html

memcpy(dst, src, n);
来源：http://dali.fengsongda.top/Article/details/gtblzgufeb.html

[S26] C：内存清零
来源：http://dali.shuidangran.top/Article/details/gtwxaylzhj.html

memset(a, 0, sizeof a);
来源：http://dali.zhongyouzk.top/Article/details/gtkazebhvk.html

[S27] C：定义常量
来源：http://dali.wangshuangyany.cn/Article/details/gtukejljfu.html

const double PI = 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gtxncldecn.html

[S28] C：静态变量
来源：http://dali.chenjidiqi.icu/Article/details/gtraaegbqj.html

static int counter = 0;
来源：http://dali.wangshuangyany.cn/Article/details/gtvplzqftw.html

[S29] C：变参函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtzfxsmbjj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gzhubu.top/Article/details/gtmyklznun.html

[S30] C：头文件保护
来源：http://dali.zhixingplan.top/Article/details/gtrxnyxake.html

#ifndef X_H
来源：http://dali.ybcxt.top/Article/details/gtvtdigmsg.html

#define X_H
来源：http://dali.nanxinkj.top/Article/details/gtwnpgmplc.html

#endif
来源：http://dali.yongpay.top/Article/details/gtimxnlpkg.html

[S31] C++：Hello World
来源：http://dali.yangfankeji.com/Article/details/gtppbrlkju.html

#include <iostream>
来源：http://dali.ybcxt.top/Article/details/gtwnnehyre.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cqqwz.cn/Article/details/gtusaqiohc.html

[S32] C++：字符串
来源：http://dali.yangfankeji.com/Article/details/gtjlvjszut.html

std::string s = "hi";  s += "!";
来源：http://dali.aizwys.cn/Article/details/gtxovyiolf.html

[S33] C++：vector 增删
来源：http://dali.jiagoushi.top/Article/details/gthmuszyxb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhixingplan.top/Article/details/gtpaprizxw.html

[S34] C++：遍历 vector
来源：http://dali.hnqzz.top/Article/details/gtdbfccqsi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.bjfxy.top/Article/details/gtaxcsgdgx.html

[S35] C++：map
来源：http://dali.kuanghao11.cn/Article/details/gtqteuyzvi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fengsongda.top/Article/details/gteddsfdax.html

[S36] C++：unordered_map
来源：http://dali.havefunace.top/Article/details/gtssjtnbtb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nwbrower.top/Article/details/gtqgerdfpq.html

[S37] C++：set
来源：http://dali.feifeiyinyue.top/Article/details/gtumruyeln.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yj20258888.top/Article/details/gtbpwhuzyw.html

[S38] C++：排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gtelaxtgzs.html

std::sort(v.begin(), v.end());
来源：http://dali.sxryk.cn/Article/details/gtksnuhbly.html

[S39] C++：自定义比较器排序
来源：http://dali.birdmap.top/Article/details/gtwfryoljl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yanxiufei.cn/Article/details/gtndbhhaqh.html

[S40] C++：查找元素
来源：http://dali.chenlongwang.top/Article/details/gtsbmhkcuj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.c1oappe.top/Article/details/gtjeeleejh.html

[S41] C++：类与构造函数
来源：http://dali.gaohongyu789.top/Article/details/gtifdgydgz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.daria6918.cn/Article/details/gtoxxrnowd.html

[S42] C++：继承与虚函数
来源：http://dali.sysykeji.top/Article/details/gtgrkgqqvu.html

class B : public Base { public: void f() override {} };
来源：http://dali.jianghu66.top/Article/details/gtqoitvavs.html

[S43] C++：智能指针
来源：http://dali.ivvv.top/Article/details/gtwzatburl.html

auto p = std::make_unique<int>(5);
来源：http://dali.haohaochexian.top/Article/details/gtzldxquwp.html

[S44] C++：引用传参
来源：http://dali.daria6918.cn/Article/details/gthnwtxawe.html

void inc(int &x) { ++x; }
来源：http://dali.guowangkeji.top/Article/details/gtidmkryjz.html

[S45] C++：lambda
来源：http://dali.nwbrower.top/Article/details/gtwxrgkour.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jiagoushi.top/Article/details/gtznpuygjb.html

[S46] C++：函数模板
来源：http://dali.gotoacloud.top/Article/details/gththkjkfe.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zdqjudy.top/Article/details/gtibfcpkgd.html

[S47] C++：结构化绑定遍历
来源：http://dali.yj202588.top/Article/details/gtxtqaidcg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhiwuduotai.top/Article/details/gtbwzolwdd.html

[S48] C++：逐行读文件
来源：http://dali.hongshengwenyu.top/Article/details/gtdecidmmx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkhspibyt.html

while (std::getline(in, line)) { }
来源：http://dali.hnqzz.top/Article/details/gtpgzqridk.html

[S49] C++：写文件
来源：http://dali.ehwqpu.com/Article/details/gtsdhmmive.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.haohaochexian.top/Article/details/gtqlsbtwqw.html

[S50] C++：格式化数字
来源：http://dali.jinyuanbaomall.cn/Article/details/gtndogbzio.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhengqikj.top/Article/details/gtiplgujcg.html

[S51] C++：显式类型转换
来源：http://dali.dashuyun.cn/Article/details/gtseopixwl.html

static_cast<double>(a) / b
来源：http://dali.jinghuilouyu.cn/Article/details/gtmscysbxv.html

[S52] C++：const 与 noexcept
来源：http://dali.kuanghao11.cn/Article/details/gtadlntzfj.html

int size() const noexcept { return n_; }
来源：http://dali.yangfankeji.com/Article/details/gtcsmfules.html

[S53] C++：移动语义
来源：http://dali.yanxiufei.cn/Article/details/gtmztkhfgn.html

std::vector<int> w = std::move(v);
来源：http://dali.ivvv.top/Article/details/gtzugndxff.html

[S54] C++：异常处理
来源：http://dali.yj20258888.top/Article/details/gtprphgeul.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqeoonptp.html

[S55] C++：结构化绑定
来源：http://dali.xinyue.icu/Article/details/gtbzcbagqm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gogol.net.cn/Article/details/gthqxqaols.html

[S56] C++：optional
来源：http://dali.yongpay.top/Article/details/gtpnedwopd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.nwbrower.top/Article/details/gtrgamcbnt.html

[S57] C++：编译期常量
来源：http://dali.xylfe.cn/Article/details/gtrjmqbsbz.html

constexpr int N = 10;
来源：http://dali.tianlin.xyz/Article/details/gtlrvcolzr.html

[S58] C++：命名空间
来源：http://dali.hammf.cn/Article/details/gtxoiwkcjr.html

namespace ns { int f() { return 1; } }
来源：http://dali.wangdashe.top/Article/details/gtkzrvkghl.html

[S59] C++：静态断言
来源：http://dali.daxiang520.top/Article/details/gtzitfdbho.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.c1oappe.top/Article/details/gtnzhutboe.html

[S60] C++：遍历并删除元素
来源：http://dali.c1oappe.top/Article/details/gtsctfaigl.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.fengsongda.top/Article/details/gtzjnckhlf.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtsysmdepz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ehwqpu.com/Article/details/gtjvusinqe.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gttmirhruc.html

[T01] Kotlin：Hello World
来源：http://dali.yj20258888.top/Article/details/gtwqqokukj.html

println("Hello")
来源：http://dali.nanxuanxn.top/Article/details/gtkbzqxjog.html

[T02] Kotlin：变量
来源：http://dali.zhengqikj.top/Article/details/gtyjufysef.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.sufxvd.cn/Article/details/gtjcljnaec.html

[T03] Kotlin：字符串模板
来源：http://dali.shzxlz.cn/Article/details/gtpifdvbac.html

"值: $b"
来源：http://dali.xinyue.icu/Article/details/gtkmprycjo.html

[T04] Kotlin：空安全
来源：http://dali.nanxinkj.top/Article/details/gtpcinudup.html

val n: String? = null;  n?.length
来源：http://dali.ppjwa.cn/Article/details/gtnfbhlnpm.html

[T05] Kotlin：when 表达式
来源：http://dali.xuanzx.com/Article/details/gtgbyihxmx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.haohaochexian.top/Article/details/gtwczriiqj.html

[T06] Kotlin：集合映射
来源：http://dali.jinqigfzy.top/Article/details/gtzzzkzmux.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.nanxuanxn.top/Article/details/gteirwwhat.html

[T07] Kotlin：集合过滤
来源：http://dali.guannengcc.top/Article/details/gtdicvsoyp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinqigufen.top/Article/details/gtupnkmmsf.html

[T08] Kotlin：数据类
来源：http://dali.fzhhl.top/Article/details/gthucxhukw.html

data class User(val name: String, val age: Int)
来源：http://dali.bjfxy.top/Article/details/gtpmsjtprc.html

[T09] Kotlin：扩展函数
来源：http://dali.jinqigfzy.top/Article/details/gtwudymzxk.html

fun String.exclaim() = this + "!"
来源：http://dali.guannengcc.top/Article/details/gtlgmnagio.html

[T10] Kotlin：默认参数
来源：http://dali.hnqzz.top/Article/details/gtxdddtozm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.tian-w.cn/Article/details/gtoiekyjmz.html

[T11] Kotlin：协程
来源：http://dali.jyoumei.cn/Article/details/gtoudhwlso.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hywenlv.cn/Article/details/gtcrzfurof.html

[T12] Kotlin：解构声明
来源：http://dali.bjfxy.top/Article/details/gtixwvrphg.html

val (a, b) = Pair(1, 2)
来源：http://dali.fengsongda.top/Article/details/gtehwyxfmf.html

[T13] Kotlin：只读 Map
来源：http://dali.daria6918.cn/Article/details/gttlgtwgrr.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gtpgeouvfb.html

[T14] Kotlin：循环
来源：http://dali.gogol.net.cn/Article/details/gtmxlqjtjw.html

for (i in 1..10) println(i)
来源：http://dali.tanke756.top/Article/details/gtzatfwvqb.html

[T15] Kotlin：接口
来源：http://dali.aizwys.cn/Article/details/gtabfdwpsw.html

interface Shape { fun area(): Double }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcdflyjjh.html

[T16] Swift：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtodyacxlg.html

print("Hello")
来源：http://dali.wangdashe.top/Article/details/gtuvvxncug.html

[T17] Swift：变量与常量
来源：http://dali.zhengqikj.top/Article/details/gtpltsuvei.html

var a = 1;  let b = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gthpuzmuga.html

[T18] Swift：字符串插值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuirgtooi.html

"值: \(b)"
来源：http://dali.jyoumei.cn/Article/details/gtwmhraozi.html

[T19] Swift：可选绑定
来源：http://dali.yvedp.cn/Article/details/gtbnjeehxe.html

if let n = opt { print(n) }
来源：http://dali.9152youxi.cn/Article/details/gtodpsqkay.html

[T20] Swift：数组操作
来源：http://dali.shangyingyoupin.top/Article/details/gtiyoomajb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.guannengcc.top/Article/details/gttivwqxtm.html

[T21] Swift：遍历
来源：http://dali.guannengcc.top/Article/details/gtupfcychv.html

for x in a { print(x) }
来源：http://dali.sysykeji.top/Article/details/gtrzgjbxfq.html

[T22] Swift：字典
来源：http://dali.yonumen.top/Article/details/gticwfigiz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jqgfzy.top/Article/details/gtzfsmlobu.html

[T23] Swift：函数
来源：http://dali.iojbl.cn/Article/details/gtodfjlsgo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.andypj.xyz/Article/details/gtfddapnii.html

[T24] Swift：闭包
来源：http://dali.xziqi.cn/Article/details/gtdsfovkdt.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shzxlz.cn/Article/details/gtakztzoxl.html

[T25] Swift：结构体
来源：http://dali.daria6918.cn/Article/details/gtugbcbqik.html

struct P { var x: Int }
来源：http://dali.mhx1999.top/Article/details/gtajntnmrg.html

[T26] Swift：类与重写
来源：http://dali.sysykeji.top/Article/details/gtuhdqhjnu.html

class A: Base { override func f() {} }
来源：http://dali.havefunace.top/Article/details/gtfvbqbqiq.html

[T27] Swift：错误处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfzpnmjlb.html

do { try f() } catch { print(error) }
来源：http://dali.guannengcc.top/Article/details/gtwsmcqcfz.html

[T28] Swift：枚举
来源：http://dali.jiagoushi.top/Article/details/gtxyvronkv.html

enum Color { case red, green }
来源：http://dali.cqqwz.cn/Article/details/gtqjbapkqx.html

[T29] Swift：guard 提前返回
来源：http://dali.cdnleiting.top/Article/details/gttegaqhqu.html

guard let x = opt else { return }
来源：http://dali.wangshuangyany.cn/Article/details/gttslgzwae.html

[T30] Swift：协议
来源：http://dali.iojbl.cn/Article/details/gtgrjbsmzk.html

protocol Shape { func area() -> Double }
来源：http://dali.fzhhl.top/Article/details/gtddazbbtm.html

[T31] Lua：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtdyakufkc.html

print("Hello")
来源：http://dali.xuetiantiany.cn/Article/details/gtvilqjvpn.html

[T32] Lua：局部变量
来源：http://dali.xuetiantiany.cn/Article/details/gtcthznncv.html

local a = 1
来源：http://dali.yongpay.top/Article/details/gtlirahswk.html

[T33] Lua：表（数组）
来源：http://dali.cheryme.top/Article/details/gtnlqqhwdo.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.9152youxi.cn/Article/details/gtxzpvalhb.html

[T34] Lua：遍历表
来源：http://dali.yj202588.top/Article/details/gthjwocdnr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.dianchejie.cn/Article/details/gtjmfuclse.html

[T35] Lua：字典表
来源：http://dali.ehwqpu.com/Article/details/gtnpoupezc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.0kj1m.cn/Article/details/gteutmwtgm.html

[T36] Lua：函数
来源：http://dali.snrcjt.cn/Article/details/gtfdmqzckn.html

function add(a, b) return a + b end
来源：http://dali.yj202588.top/Article/details/gtfbcbiiqt.html

[T37] Lua：字符串拼接
来源：http://dali.iojbl.cn/Article/details/gthwktaemz.html

"a" .. "b"
来源：http://dali.fengsongda.top/Article/details/gtddkhpldu.html

[T38] Lua：条件
来源：http://dali.gotoacloud.top/Article/details/gtjjdfllys.html

if x > 0 then print("正") end
来源：http://dali.xziqi.cn/Article/details/gtnlxtchxr.html

[T39] Lua：模式匹配
来源：http://dali.316326.xyz/Article/details/gtsyyhxlaz.html

string.find(s, "%d+")
来源：http://dali.fzhhl.top/Article/details/gthnpsrgvr.html

[T40] Lua：元表
来源：http://dali.xuetiantiany.cn/Article/details/gtfurycrzu.html

setmetatable({}, { __index = base })
来源：http://dali.gotoacloud.top/Article/details/gtnettlzaf.html

[T41] Perl：Hello World
来源：http://dali.dashuyun.cn/Article/details/gtpzcogsfi.html

print "Hello\n";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkdgommtl.html

[T42] Perl：变量类型
来源：http://dali.chenlongwang.top/Article/details/gtfvqpaqms.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jinghuilouyu.cn/Article/details/gtkkwclocs.html

[T43] Perl：字符串插值
来源：http://dali.yvedp.cn/Article/details/gtxnpzlsqz.html

"值: $a"
来源：http://dali.jianghu66.top/Article/details/gtjntdetzt.html

[T44] Perl：条件
来源：http://dali.haohaochexian.top/Article/details/gtakgyyjvy.html

if ($a > 0) { print "正"; }
来源：http://dali.yj20258.top/Article/details/gttwlpbrck.html

[T45] Perl：数组遍历
来源：http://dali.yonumen.top/Article/details/gtwshpnqpk.html

for my $x (@arr) { print $x; }
来源：http://dali.yvedp.cn/Article/details/gtraoyfdqt.html

[T46] Perl：哈希操作
来源：http://dali.ydzc1.top/Article/details/gtjbgbhnoz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtkjrqprql.html

[T47] Perl：正则捕获
来源：http://dali.zhixingplan.top/Article/details/gtspfqzbts.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yongpay.top/Article/details/gtobitbmmi.html

[T48] Perl：正则替换
来源：http://dali.gogol.net.cn/Article/details/gtvnhlkxij.html

$s =~ s/old/new/g;
来源：http://dali.meibo888.top/Article/details/gtdixdsewy.html


<!-- 参考信息 -->