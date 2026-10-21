代发 wailian999

sed -i 's/foo/bar/g' a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtfzxlzkqg.html

[R48] awk 取指定列
来源：http://dali.ppjwa.cn/Article/details/gtupqabvot.html

awk '{print $1, $3}' a.txt
来源：http://dali.jiagoushi.top/Article/details/gtecleiszz.html

[R49] awk 带条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjmmdzfod.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gzhubu.top/Article/details/gtitkvhjwy.html

[R50] awk 求和
来源：http://dali.kuanghao11.cn/Article/details/gtqrmrjcns.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtkcgqjuwi.html

[R51] 排序去重取前几
来源：http://dali.daria6918.cn/Article/details/gteubimvxa.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.c1oappe.top/Article/details/gtpndibhcc.html

[R52] 统计行数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgcrvkirl.html

wc -l a.txt
来源：http://dali.tian-w.cn/Article/details/gtnpggptlf.html

[R53] 查看文件头与实时尾
来源：http://dali.pengpengdd.cyou/Article/details/gtcizvizad.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.daxiang520.top/Article/details/gtbqmwsfoe.html

[R54] 比较两个文件
来源：http://dali.zycfv.cn/Article/details/gtuyotihoa.html

diff a.txt b.txt
来源：http://dali.jinqigufen.top/Article/details/gtxhbvsnxu.html

[R55] 压缩与解压
来源：http://dali.gzhubu.top/Article/details/gtmxgbkdjl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.feifeiyinyue.top/Article/details/gthlvdiamc.html

[R56] 远程拷贝
来源：http://dali.tianlin.xyz/Article/details/gtmudkfadk.html

scp file user@host:/path/
来源：http://dali.hfpthk.cn/Article/details/gtqgqohwdb.html

[R57] 远程执行命令
来源：http://dali.yj20258.top/Article/details/gtzbagxkfn.html

ssh user@host 'uptime'
来源：http://dali.yangfankeji.com/Article/details/gthvvdfkza.html

[R58] 下载文件
来源：http://dali.hongshengwenyu.top/Article/details/gtlsqwsbho.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jqgufenzy.top/Article/details/gtneoxykny.html

[R59] 发 POST JSON
来源：http://dali.vqdsnc.cn/Article/details/gtgznoogrk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.fengsongda.top/Article/details/gtnjtpvvtk.html

[R60] 只看 HTTP 状态码
来源：http://dali.sxryk.cn/Article/details/gtldscvzgv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hnqzz.top/Article/details/gtjhdizghn.html

[R61] 磁盘占用
来源：http://dali.yangfankeji.com/Article/details/gtalpofcte.html

df -h;  du -sh *
来源：http://dali.ppjwa.cn/Article/details/gtqenxxgqf.html

[R62] 找最占空间的文件
来源：http://dali.zhongyouzk.top/Article/details/gtjbcbflke.html

du -ah . | sort -rh | head -10
来源：http://dali.cashguo.top/Article/details/gtijgjwvuh.html

[R63] 内存与进程
来源：http://dali.gzhubu.top/Article/details/gtyhsuwnzl.html

free -h;  ps aux | grep nginx
来源：http://dali.0kj1m.cn/Article/details/gtxorcrutj.html

[R64] 结束进程
来源：http://dali.shuidangran.top/Article/details/gtzfrluyks.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ybcxt.top/Article/details/gtbozoxmvi.html

[R65] 查看端口占用
来源：http://dali.sweek.top/Article/details/gtuyqcokqq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.tian-w.cn/Article/details/gttwipdkhh.html

[R66] 定时任务
来源：http://dali.hfpthk.cn/Article/details/gtdavcqzrq.html

crontab -e;  crontab -l
来源：http://dali.gogol.net.cn/Article/details/gtolnbmxqb.html

[R67] 生成随机十六进制串
来源：http://dali.0kj1m.cn/Article/details/gtgtmznobv.html

openssl rand -hex 16
来源：http://dali.smart0.xyz/Article/details/gtykjhinvi.html

[R68] 计算文件校验值
来源：http://dali.ybcxt.top/Article/details/gtlfzjkvkn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sysykeji.top/Article/details/gtmjsdemfa.html

[R69] 生成随机密码
来源：http://dali.shangyingyoupin.top/Article/details/gtkqfgvfvx.html

head -c 16 /dev/urandom | base64
来源：http://dali.yj20258.top/Article/details/gtbakrzxhd.html

[R70] 时间戳与互转
来源：http://dali.c1oappe.top/Article/details/gtwfivaimh.html

date +%s;  date -d @1700000000
来源：http://dali.hnqzz.top/Article/details/gtkmwkxlrn.html

[R71] 日期格式化
来源：http://dali.0kj1m.cn/Article/details/gtjslznslm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zycfv.cn/Article/details/gtxfvwojfm.html

[R72] 等待端口就绪
来源：http://dali.xinyue.icu/Article/details/gtzlvbhewu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.nanxuanxn.top/Article/details/gtecxvayan.html

[R73] 分割大日志
来源：http://dali.havefunace.top/Article/details/gtbknlrtzz.html

split -l 1000 big.log part_
来源：http://dali.xuanzx.com/Article/details/gtbbqkcfro.html

[R74] 批量重命名
来源：http://dali.tian-w.cn/Article/details/gtlvjrsreh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.quarkkingdee.top/Article/details/gtpuysyjur.html

[R75] 导出环境变量
来源：http://dali.havefunace.top/Article/details/gtcfnpctcy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.kuanghao11.cn/Article/details/gtkgudsptc.html

[R76] 使用临时文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcseppkwn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.wangdashe.top/Article/details/gtrtxvbgzv.html

[R77] 读取用户输入
来源：http://dali.cqqwz.cn/Article/details/gtcdtvlxib.html

read -rp "请输入: " ans
来源：http://dali.gotoacloud.top/Article/details/gtektyddym.html

[R78] 交互式菜单
来源：http://dali.fengsongda.top/Article/details/gtgeyhmwdj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhengqikj.top/Article/details/gtuzjhlkqb.html

[R79] 解析命令行选项
来源：http://dali.snrcjt.cn/Article/details/gtajhlgleb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.bjfxy.top/Article/details/gtzrbaqxda.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gtdjtvdagw.html

time ./run.sh
来源：http://dali.hfpthk.cn/Article/details/gtfhylzctx.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtvqjyxayl.html

S. C / C++ 专题
来源：http://dali.nwbrower.top/Article/details/gtmadwsooi.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkpfwwbfv.html

[S01] C：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtmoxsesyc.html

#include <stdio.h>
来源：http://dali.yanxiufei.cn/Article/details/gtrsybniad.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xuetiantiany.cn/Article/details/gtxjokzdxf.html

[S02] C：变量与格式化输出
来源：http://dali.nanxinkj.top/Article/details/gthieqklfa.html

int a = 10; printf("%d\n", a);
来源：http://dali.jinqigufen.top/Article/details/gtzgttkotq.html

[S03] C：读入整数
来源：http://dali.yj202588.top/Article/details/gtrnmzbapz.html

int x; scanf("%d", &x);
来源：http://dali.bjfxy.top/Article/details/gtyxkzfyoy.html

[S04] C：字符串复制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtohrszdhk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yvedp.cn/Article/details/gtqizkqhcy.html

[S05] C：字符串长度
来源：http://dali.yvedp.cn/Article/details/gtcehtnqun.html

strlen(s)
来源：http://dali.ybcxt.top/Article/details/gtarbrqhrd.html

[S06] C：字符串比较
来源：http://dali.cqqwz.cn/Article/details/gtiaqhqdbc.html

strcmp(a, b) == 0
来源：http://dali.hnxiangtu.top/Article/details/gtoumsuehj.html

[S07] C：数组遍历求和
来源：http://dali.cucudq.cn/Article/details/gtzyrumhmx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.vqdsnc.cn/Article/details/gtsbxjecsx.html

[S08] C：动态内存分配与释放
来源：http://dali.guowangkeji.top/Article/details/gtzbwfutft.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yuanzhike.top/Article/details/gtazkwljje.html

[S09] C：结构体定义与初始化
来源：http://dali.zdqjudy.top/Article/details/gtczuodspe.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.9152youxi.cn/Article/details/gthtafknjb.html

[S10] C：指针与解引用
来源：http://dali.gaohongyu789.top/Article/details/gtfuvwkpqp.html

int *p = &a;  *p = 5;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrbsnltvu.html

[S11] C：逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gtjrmszvxt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.0kj1m.cn/Article/details/gtvakulefn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jyoumei.cn/Article/details/gtcptinahx.html

fclose(f);
来源：http://dali.jyoumei.cn/Article/details/gtbaliklxu.html

[S12] C：写文件
来源：http://dali.svipenyu.cn/Article/details/gthritlirh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yj20258.top/Article/details/gtnphjioyt.html

[S13] C：宏定义
来源：http://dali.iojbl.cn/Article/details/gthljgnybd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yongpay.top/Article/details/gtrxjtaoth.html

[S14] C：枚举
来源：http://dali.jlsjyb.cn/Article/details/gtnsuozopj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.fzhhl.top/Article/details/gtkqbhupyz.html

[S15] C：类型转换
来源：http://dali.0kj1m.cn/Article/details/gtlajirhqy.html

(double) a / b
来源：http://dali.wangdashe.top/Article/details/gtsxscicns.html

[S16] C：位操作置位
来源：http://dali.birdmap.top/Article/details/gtxburhaml.html

x |= (1 << 3);
来源：http://dali.shangyingyoupin.top/Article/details/gtltvcwxbi.html

[S17] C：安全拼接字符串
来源：http://dali.wangdashe.top/Article/details/gtxawravff.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtexruywqr.html

[S18] C：命令行参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzrtlnzgn.html

int main(int argc, char **argv)
来源：http://dali.nanxuanxn.top/Article/details/gtswnfqoyo.html

[S19] C：快速排序
来源：http://dali.jinqigfzy.top/Article/details/gtepklgnri.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cucudq.cn/Article/details/gtsasdnanh.html

[S20] C：二分查找
来源：http://dali.yvedp.cn/Article/details/gtdovupltl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.nanxuanxn.top/Article/details/gtiaomjvtk.html

[S21] C：字符类别判断
来源：http://dali.xziqi.cn/Article/details/gtfshjtuzm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.guowangkeji.top/Article/details/gtdbvisjug.html

[S22] C：字符串转数字
来源：http://dali.pengpengdd.cyou/Article/details/gtkoeasqvp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.meibo888.top/Article/details/gtfojnrcxc.html

[S23] C：随机数
来源：http://dali.zhengqikj.top/Article/details/gtwxlvwbjj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.meibo888.top/Article/details/gtjozftlqd.html

[S24] C：获取本地时间
来源：http://dali.jyoumei.cn/Article/details/gtrcrlsopx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jyoumei.cn/Article/details/gtkrvjqfmx.html

[S25] C：内存拷贝
来源：http://dali.nanxuanxn.top/Article/details/gtruicezdx.html

memcpy(dst, src, n);
来源：http://dali.chenlongwang.top/Article/details/gtolpvahui.html

[S26] C：内存清零
来源：http://dali.wangshuangyany.cn/Article/details/gthkbtosxj.html

memset(a, 0, sizeof a);
来源：http://dali.gaohongyu789.top/Article/details/gtnjaibbfc.html

[S27] C：定义常量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpjnarttr.html

const double PI = 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gtetkkcocn.html

[S28] C：静态变量
来源：http://dali.ppjwa.cn/Article/details/gtgfeamzjq.html

static int counter = 0;
来源：http://dali.hammf.cn/Article/details/gtkqpnqniv.html

[S29] C：变参函数
来源：http://dali.birdmap.top/Article/details/gtkmctlnai.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.pycfn.com/Article/details/gtbafvdopr.html

[S30] C：头文件保护
来源：http://dali.snrcjt.cn/Article/details/gtzexvynbp.html

#ifndef X_H
来源：http://dali.ehwqpu.com/Article/details/gtqocqiivb.html

#define X_H
来源：http://dali.gaohongyu789.top/Article/details/gthginbmzl.html

#endif
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbawdtucg.html

[S31] C++：Hello World
来源：http://dali.andypj.xyz/Article/details/gtuswpvyni.html

#include <iostream>
来源：http://dali.bjfxy.top/Article/details/gtgpcecpds.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zdqjudy.top/Article/details/gtrhysfhik.html

[S32] C++：字符串
来源：http://dali.jyoumei.cn/Article/details/gtobsrmnpc.html

std::string s = "hi";  s += "!";
来源：http://dali.dianchejie.cn/Article/details/gtnpduwyko.html

[S33] C++：vector 增删
来源：http://dali.kuanghao11.cn/Article/details/gtlahqoycz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.guowangkeji.top/Article/details/gtegvhvlnp.html

[S34] C++：遍历 vector
来源：http://dali.shanyushiyangtech.top/Article/details/gtwosuyvod.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shuidangran.top/Article/details/gtoqonzigl.html

[S35] C++：map
来源：http://dali.zhixingplan.top/Article/details/gtjwwtuxix.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gtyixeuojn.html

[S36] C++：unordered_map
来源：http://dali.fengsongda.top/Article/details/gtstqnxobd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yonumen.top/Article/details/gtyoewazpy.html

[S37] C++：set
来源：http://dali.gotoacloud.top/Article/details/gtepfczakt.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hnxiangtu.top/Article/details/gtsgiuxnjr.html

[S38] C++：排序
来源：http://dali.zhixingplan.top/Article/details/gtyunlmgki.html

std::sort(v.begin(), v.end());
来源：http://dali.shangyingyoupin.top/Article/details/gtpndbwywt.html

[S39] C++：自定义比较器排序
来源：http://dali.ybcxt.top/Article/details/gtrbcmibvn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xuanzx.com/Article/details/gthpebdkdo.html

[S40] C++：查找元素
来源：http://dali.zhiwuduotai.top/Article/details/gteeuvdysp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjmlihouq.html

[S41] C++：类与构造函数
来源：http://dali.sufxvd.cn/Article/details/gttdclbpnf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfnlxjnpa.html

[S42] C++：继承与虚函数
来源：http://dali.shuidangran.top/Article/details/gtfopbofpp.html

class B : public Base { public: void f() override {} };
来源：http://dali.ivvv.top/Article/details/gtnhlitqcc.html

[S43] C++：智能指针
来源：http://dali.hnxiangtu.top/Article/details/gtrqdseghu.html

auto p = std::make_unique<int>(5);
来源：http://dali.cqqwz.cn/Article/details/gtbkfgmosd.html

[S44] C++：引用传参
来源：http://dali.gzhubu.top/Article/details/gtcpdfbbec.html

void inc(int &x) { ++x; }
来源：http://dali.gaohongyu789.top/Article/details/gtznyrphes.html

[S45] C++：lambda
来源：http://dali.feifeiyinyue.top/Article/details/gtnvrtpujx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xziqi.cn/Article/details/gtonjjrkmg.html

[S46] C++：函数模板
来源：http://dali.tanke756.top/Article/details/gtdgwdvddk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jlsjyb.cn/Article/details/gtfnpphbjp.html

[S47] C++：结构化绑定遍历
来源：http://dali.xuanzx.com/Article/details/gtnhrpyvbi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shuidangran.top/Article/details/gttoqbftnu.html

[S48] C++：逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gtmtqhuuec.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.birdmap.top/Article/details/gtqjkkssoo.html

while (std::getline(in, line)) { }
来源：http://dali.ydzc1.top/Article/details/gtkabldmix.html

[S49] C++：写文件
来源：http://dali.yj202588.top/Article/details/gtvfeagaiq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hywenlv.cn/Article/details/gtgdusidlf.html

[S50] C++：格式化数字
来源：http://dali.jinghuilouyu.cn/Article/details/gtthxdjsvo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.chenzaomai.com/Article/details/gtspkfpsve.html

[S51] C++：显式类型转换
来源：http://dali.jinghuilouyu.cn/Article/details/gtslnnrjcq.html

static_cast<double>(a) / b
来源：http://dali.ivvv.top/Article/details/gtwssupddd.html

[S52] C++：const 与 noexcept
来源：http://dali.xylfe.cn/Article/details/gtisjefgxp.html

int size() const noexcept { return n_; }
来源：http://dali.haohaochexian.top/Article/details/gtfxkptgis.html

[S53] C++：移动语义
来源：http://dali.yuxming.cn/Article/details/gtnbujptna.html

std::vector<int> w = std::move(v);
来源：http://dali.jiagoushi.top/Article/details/gtbmmtmicp.html

[S54] C++：异常处理
来源：http://dali.hammf.cn/Article/details/gtdcrudcon.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.dashuyun.cn/Article/details/gtxlygaxcy.html

[S55] C++：结构化绑定
来源：http://dali.tianlin.xyz/Article/details/gtbpfpfkdg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yonumen.top/Article/details/gtzzerviff.html

[S56] C++：optional
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqmeuskmi.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yanxiufei.cn/Article/details/gtnwqfbqtm.html

[S57] C++：编译期常量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdtsguvzy.html

constexpr int N = 10;
来源：http://dali.cqqwz.cn/Article/details/gtugpjlzqe.html

[S58] C++：命名空间
来源：http://dali.cqqwz.cn/Article/details/gtrumdevth.html

namespace ns { int f() { return 1; } }
来源：http://dali.chenzaomai.com/Article/details/gtxcfqqlel.html

[S59] C++：静态断言
来源：http://dali.daxiang520.top/Article/details/gtdsiyvmxu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.aizwys.cn/Article/details/gtgofrqnin.html

[S60] C++：遍历并删除元素
来源：http://dali.zdqjudy.top/Article/details/gtvbyoqhcf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinqigfzy.top/Article/details/gtadugopiv.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtxqwqacao.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yanxiufei.cn/Article/details/gtrlidpdxl.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtpmskebyz.html

[T01] Kotlin：Hello World
来源：http://dali.daria6918.cn/Article/details/gtgltchxcx.html

println("Hello")
来源：http://dali.meibo888.top/Article/details/gtntfogxea.html

[T02] Kotlin：变量
来源：http://dali.haohaochexian.top/Article/details/gtexaicbzs.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnxolrhfz.html

[T03] Kotlin：字符串模板
来源：http://dali.jianghu66.top/Article/details/gtecehedof.html

"值: $b"
来源：http://dali.yj20258888.top/Article/details/gtggxjrsoe.html

[T04] Kotlin：空安全
来源：http://dali.tianlin.xyz/Article/details/gtwbexynhl.html

val n: String? = null;  n?.length
来源：http://dali.gotoacloud.top/Article/details/gtwqvdwnwo.html

[T05] Kotlin：when 表达式
来源：http://dali.cheryme.top/Article/details/gtklfcxfrv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cucudq.cn/Article/details/gtxagmegjt.html

[T06] Kotlin：集合映射
来源：http://dali.sufxvd.cn/Article/details/gtmqefmwxn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinqigufen.top/Article/details/gtrkshirdi.html

[T07] Kotlin：集合过滤
来源：http://dali.vqdsnc.cn/Article/details/gtjfoufcnr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinqigufen.top/Article/details/gtcpjdlkct.html

[T08] Kotlin：数据类
来源：http://dali.shanyushiyangkeji.top/Article/details/gttmgoneup.html

data class User(val name: String, val age: Int)
来源：http://dali.zhixingplan.top/Article/details/gtmipnypmv.html

[T09] Kotlin：扩展函数
来源：http://dali.c1oappe.top/Article/details/gttdntsfnk.html

fun String.exclaim() = this + "!"
来源：http://dali.sxryk.cn/Article/details/gtdrqshizc.html

[T10] Kotlin：默认参数
来源：http://dali.chenzaomai.com/Article/details/gtpgdcqbex.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj202588.top/Article/details/gthpvhohlv.html

[T11] Kotlin：协程
来源：http://dali.aizwys.cn/Article/details/gtewicaixi.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.daxiang520.top/Article/details/gtqtleoens.html

[T12] Kotlin：解构声明
来源：http://dali.wangshuangyany.cn/Article/details/gtpsahygve.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhixingplan.top/Article/details/gtnzwnmjii.html

[T13] Kotlin：只读 Map
来源：http://dali.nanxinkj.top/Article/details/gtsotcpehd.html

val m = mapOf("a" to 1)
来源：http://dali.yuanzhike.top/Article/details/gturevduup.html

[T14] Kotlin：循环
来源：http://dali.hywenlv.cn/Article/details/gtozmhsxbf.html

for (i in 1..10) println(i)
来源：http://dali.gaohongyu789.top/Article/details/gtrxsfxero.html

[T15] Kotlin：接口
来源：http://dali.cashguo.top/Article/details/gtvlsloxef.html

interface Shape { fun area(): Double }
来源：http://dali.iojbl.cn/Article/details/gtclrzmnvk.html

[T16] Swift：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtlipxhuvi.html

print("Hello")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpmwrktoi.html

[T17] Swift：变量与常量
来源：http://dali.yangfankeji.com/Article/details/gtyuvmcaca.html

var a = 1;  let b = 2
来源：http://dali.yonumen.top/Article/details/gtpxdfaouv.html

[T18] Swift：字符串插值
来源：http://dali.zhoulong.xyz/Article/details/gtrhxwstyu.html

"值: \(b)"
来源：http://dali.yonumen.top/Article/details/gtqokktajo.html

[T19] Swift：可选绑定
来源：http://dali.c1oappe.top/Article/details/gtdzhwfsza.html

if let n = opt { print(n) }
来源：http://dali.smart0.xyz/Article/details/gtqyuphqse.html

[T20] Swift：数组操作
来源：http://dali.hywenlv.cn/Article/details/gtfnjstmqy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xinyue.icu/Article/details/gtsolltksw.html

[T21] Swift：遍历
来源：http://dali.zhoulong.xyz/Article/details/gtncjzsqaw.html

for x in a { print(x) }
来源：http://dali.xinyue.icu/Article/details/gtgtrgaylc.html

[T22] Swift：字典
来源：http://dali.cheryme.top/Article/details/gtoqodkhdz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.chenzaomai.com/Article/details/gtaloqpmxt.html

[T23] Swift：函数
来源：http://dali.hongshengwenyu.top/Article/details/gtuaeyhicx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.gotoacloud.top/Article/details/gtptirnjff.html

[T24] Swift：闭包
来源：http://dali.dianchejie.cn/Article/details/gtkzuuitqc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ybcxt.top/Article/details/gtgcsyinkk.html

[T25] Swift：结构体
来源：http://dali.hnxiangtu.top/Article/details/gtixisglsw.html

struct P { var x: Int }
来源：http://dali.andypj.xyz/Article/details/gtrytvufbo.html

[T26] Swift：类与重写
来源：http://dali.yanxiufei.cn/Article/details/gtbccodcxc.html

class A: Base { override func f() {} }
来源：http://dali.ehwqpu.com/Article/details/gtuiojgvqe.html

[T27] Swift：错误处理
来源：http://dali.jinqigufen.top/Article/details/gthbfqvuwv.html

do { try f() } catch { print(error) }
来源：http://dali.jiagoushi.top/Article/details/gtkmkzijcg.html

[T28] Swift：枚举
来源：http://dali.jianghu66.top/Article/details/gtbzohudgb.html

enum Color { case red, green }
来源：http://dali.meibo888.top/Article/details/gtbgpksnkb.html

[T29] Swift：guard 提前返回
来源：http://dali.yj20258.top/Article/details/gteykrfdfv.html

guard let x = opt else { return }
来源：http://dali.jyoumei.cn/Article/details/gtfedjcfww.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gtnfyyzeuh.html

protocol Shape { func area() -> Double }
来源：http://dali.hongshengwenyu.top/Article/details/gtqebxnmxr.html

[T31] Lua：Hello World
来源：http://dali.smart0.xyz/Article/details/gtnganzpyc.html

print("Hello")
来源：http://dali.dashuyun.cn/Article/details/gtzrqmtyjs.html

[T32] Lua：局部变量
来源：http://dali.daria6918.cn/Article/details/gtslqntssc.html

local a = 1
来源：http://dali.dashuyun.cn/Article/details/gtbxozljqa.html

[T33] Lua：表（数组）
来源：http://dali.daxiang520.top/Article/details/gtdorxpsic.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.wangshuangyany.cn/Article/details/gtfucljqxp.html

[T34] Lua：遍历表
来源：http://dali.jinghuilouyu.cn/Article/details/gtndusdzbi.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.fzhhl.top/Article/details/gtxeswxbse.html

[T35] Lua：字典表
来源：http://dali.xuetiantiany.cn/Article/details/gtdnyidxaz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.9152youxi.cn/Article/details/gtkkijipgm.html

[T36] Lua：函数
来源：http://dali.hammf.cn/Article/details/gtuujqgume.html

function add(a, b) return a + b end
来源：http://dali.iojbl.cn/Article/details/gtbebesudq.html

[T37] Lua：字符串拼接
来源：http://dali.yuxming.cn/Article/details/gtsgndgsgf.html

"a" .. "b"
来源：http://dali.xylfe.cn/Article/details/gtrtwcjgjo.html

[T38] Lua：条件
来源：http://dali.svipenyu.cn/Article/details/gtjzchgbeq.html

if x > 0 then print("正") end
来源：http://dali.meibo888.top/Article/details/gthehjprlp.html

[T39] Lua：模式匹配
来源：http://dali.nanxinkj.top/Article/details/gtytwomsiu.html

string.find(s, "%d+")
来源：http://dali.chenzaomai.com/Article/details/gtsikvbfkf.html

[T40] Lua：元表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgjmtxfgv.html

setmetatable({}, { __index = base })
来源：http://dali.shanyushiyangtech.top/Article/details/gtetsvnjfk.html

[T41] Perl：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsgqdqonp.html

print "Hello\n";
来源：http://dali.zycfv.cn/Article/details/gtjbxgsyqy.html

[T42] Perl：变量类型
来源：http://dali.shzxlz.cn/Article/details/gtfevrdjrd.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ehwqpu.com/Article/details/gtcxbmbvhy.html

[T43] Perl：字符串插值
来源：http://dali.nwbrower.top/Article/details/gtmsbwiqun.html

"值: $a"
来源：http://dali.hfpthk.cn/Article/details/gtwwgspzab.html

[T44] Perl：条件
来源：http://dali.jinqigufen.top/Article/details/gtvjxjwypu.html

if ($a > 0) { print "正"; }
来源：http://dali.shuidangran.top/Article/details/gtxdjouzyi.html

[T45] Perl：数组遍历
来源：http://dali.zhengqikj.top/Article/details/gtdljfnjgn.html

for my $x (@arr) { print $x; }
来源：http://dali.jlsjyb.cn/Article/details/gtazschluq.html

[T46] Perl：哈希操作
来源：http://dali.yueranfly.top/Article/details/gtdvwrusrz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.mhx1999.top/Article/details/gtfbojfmla.html

[T47] Perl：正则捕获
来源：http://dali.quarkkingdee.top/Article/details/gteqsemhri.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.aibaodan.cn/Article/details/gtucbtgxkg.html

[T48] Perl：正则替换
来源：http://dali.chenjidiqi.icu/Article/details/gtcgqjjuue.html

$s =~ s/old/new/g;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtejrykyeq.html

[T49] Perl：函数
来源：http://dali.hfpthk.cn/Article/details/gtqaknryuq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.guannengcc.top/Article/details/gttwpmmsjq.html

[T50] Perl：逐行读文件
来源：http://dali.xinyue.icu/Article/details/gttuqhfjdl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xziqi.cn/Article/details/gtefshfhrz.html


<!-- 参考信息 -->