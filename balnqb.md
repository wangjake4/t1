代发 wailian999

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jinghuilouyu.cn/Article/details/gtyhbcroec.html

[R52] 统计行数
来源：http://dali.bjfxy.top/Article/details/gtdqgzilnf.html

wc -l a.txt
来源：http://dali.9152youxi.cn/Article/details/gtlfuxrcdy.html

[R53] 查看文件头与实时尾
来源：http://dali.nanxuanxn.top/Article/details/gtwhmwxqsl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hongshengwenyu.top/Article/details/gtqnirjkku.html

[R54] 比较两个文件
来源：http://dali.yuxming.cn/Article/details/gtzgbeuvek.html

diff a.txt b.txt
来源：http://dali.gaohongyu789.top/Article/details/gtxthshegw.html

[R55] 压缩与解压
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsnnrtmct.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.wangshuangyany.cn/Article/details/gtsxwhneje.html

[R56] 远程拷贝
来源：http://dali.jyoumei.cn/Article/details/gtoskmhjaz.html

scp file user@host:/path/
来源：http://dali.meibo888.top/Article/details/gtlzzhremm.html

[R57] 远程执行命令
来源：http://dali.jiagoushi.top/Article/details/gthvxcxedj.html

ssh user@host 'uptime'
来源：http://dali.smart0.xyz/Article/details/gtekcrkyyv.html

[R58] 下载文件
来源：http://dali.yongpay.top/Article/details/gtlofgowlw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xinyue.icu/Article/details/gtifynskqz.html

[R59] 发 POST JSON
来源：http://dali.wangdashe.top/Article/details/gtatfyutqx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xylfe.cn/Article/details/gtvjukkzax.html

[R60] 只看 HTTP 状态码
来源：http://dali.hysaishi.cn/Article/details/gtoerbndlg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.daxiang520.top/Article/details/gtqwtcmplg.html

[R61] 磁盘占用
来源：http://dali.yj20258.top/Article/details/gtfzqawhmt.html

df -h;  du -sh *
来源：http://dali.jyoumei.cn/Article/details/gtipqgomwb.html

[R62] 找最占空间的文件
来源：http://dali.mhx1999.top/Article/details/gthypzpdef.html

du -ah . | sort -rh | head -10
来源：http://dali.daxiang520.top/Article/details/gtwobvxtib.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gtwcvofkfd.html

free -h;  ps aux | grep nginx
来源：http://dali.yanxiufei.cn/Article/details/gtriqgezif.html

[R64] 结束进程
来源：http://dali.tanke756.top/Article/details/gtofwhcvtw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.tianlin.xyz/Article/details/gtwtckndgy.html

[R65] 查看端口占用
来源：http://dali.svipenyu.cn/Article/details/gthdfesxfz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.birdmap.top/Article/details/gtvwzcazag.html

[R66] 定时任务
来源：http://dali.tianlin.xyz/Article/details/gtirecfego.html

crontab -e;  crontab -l
来源：http://dali.kuanghao11.cn/Article/details/gtatxloyfx.html

[R67] 生成随机十六进制串
来源：http://dali.birdmap.top/Article/details/gtposqrxje.html

openssl rand -hex 16
来源：http://dali.nwbrower.top/Article/details/gtugaqymeo.html

[R68] 计算文件校验值
来源：http://dali.wangshuangyany.cn/Article/details/gthdzpwfvt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gzhubu.top/Article/details/gtuqakedif.html

[R69] 生成随机密码
来源：http://dali.zhiwuduotai.top/Article/details/gtatpafism.html

head -c 16 /dev/urandom | base64
来源：http://dali.sysykeji.top/Article/details/gtooucpynm.html

[R70] 时间戳与互转
来源：http://dali.316326.xyz/Article/details/gttkwjmoqg.html

date +%s;  date -d @1700000000
来源：http://dali.yuxming.cn/Article/details/gtbqajotup.html

[R71] 日期格式化
来源：http://dali.zhongyouzk.top/Article/details/gtihhunjlx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hongshengwenyu.top/Article/details/gtffemaxmd.html

[R72] 等待端口就绪
来源：http://dali.gaohongyu789.top/Article/details/gtwwxpmfwd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shangyingyoupin.top/Article/details/gtoodrycbu.html

[R73] 分割大日志
来源：http://dali.0kj1m.cn/Article/details/gtggcdrnnj.html

split -l 1000 big.log part_
来源：http://dali.jiagoushi.top/Article/details/gtnqpsjylv.html

[R74] 批量重命名
来源：http://dali.pycfn.com/Article/details/gtzsixopfc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hongshengwenyu.top/Article/details/gtityptrog.html

[R75] 导出环境变量
来源：http://dali.redwolf501.top/Article/details/gtihxcupll.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.fengsongda.top/Article/details/gtpfngdnur.html

[R76] 使用临时文件
来源：http://dali.cqqwz.cn/Article/details/gtebzzyrvx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.snrcjt.cn/Article/details/gtmvlwkeiq.html

[R77] 读取用户输入
来源：http://dali.shangyingyoupin.top/Article/details/gtujlifika.html

read -rp "请输入: " ans
来源：http://dali.xziqi.cn/Article/details/gtrnhubvjb.html

[R78] 交互式菜单
来源：http://dali.jianghu66.top/Article/details/gtsgqqwsxw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpufcxmlg.html

[R79] 解析命令行选项
来源：http://dali.hammf.cn/Article/details/gtbcgnpwon.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yj202588.top/Article/details/gtxiwfhdak.html

[R80] 查看脚本执行耗时
来源：http://dali.nwbrower.top/Article/details/gtsxlxqjob.html

time ./run.sh
来源：http://dali.xuanzx.com/Article/details/gtvecavfcj.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtyjpvbetm.html

S. C / C++ 专题
来源：http://dali.redwolf501.top/Article/details/gtbsiupmlk.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtfokxayyy.html

[S01] C：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtcanclify.html

#include <stdio.h>
来源：http://dali.hammf.cn/Article/details/gtfdpcudbv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yuxming.cn/Article/details/gtlnupnuss.html

[S02] C：变量与格式化输出
来源：http://dali.cashguo.top/Article/details/gtxrcbryfl.html

int a = 10; printf("%d\n", a);
来源：http://dali.redwolf501.top/Article/details/gtnptepsae.html

[S03] C：读入整数
来源：http://dali.guowangkeji.top/Article/details/gtpfwvtwoj.html

int x; scanf("%d", &x);
来源：http://dali.snrcjt.cn/Article/details/gtvggdhufh.html

[S04] C：字符串复制
来源：http://dali.ydzc1.top/Article/details/gtqnlskiso.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gtjidmgmbc.html

[S05] C：字符串长度
来源：http://dali.shzxlz.cn/Article/details/gtpchsvcvh.html

strlen(s)
来源：http://dali.cheryme.top/Article/details/gtcqhcpypw.html

[S06] C：字符串比较
来源：http://dali.shuidangran.top/Article/details/gtxwdiwxze.html

strcmp(a, b) == 0
来源：http://dali.hammf.cn/Article/details/gtuxhpygtc.html

[S07] C：数组遍历求和
来源：http://dali.mhx1999.top/Article/details/gtfzhcjclk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ppjwa.cn/Article/details/gtcknythqo.html

[S08] C：动态内存分配与释放
来源：http://dali.sweek.top/Article/details/gtcbjkxuqz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cdnleiting.top/Article/details/gtwqklmwyp.html

[S09] C：结构体定义与初始化
来源：http://dali.jianghu66.top/Article/details/gthtrtvxii.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shzxlz.cn/Article/details/gtaxktthns.html

[S10] C：指针与解引用
来源：http://dali.svipenyu.cn/Article/details/gtdcwlyanj.html

int *p = &a;  *p = 5;
来源：http://dali.haohaochexian.top/Article/details/gtycrvicka.html

[S11] C：逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gtdwsuomgn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cqqwz.cn/Article/details/gtthfzkbor.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hongshengwenyu.top/Article/details/gtlzorpypl.html

fclose(f);
来源：http://dali.havefunace.top/Article/details/gttkaoydwm.html

[S12] C：写文件
来源：http://dali.zhongyouzk.top/Article/details/gtscatjynf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sxryk.cn/Article/details/gtctusxbhb.html

[S13] C：宏定义
来源：http://dali.dianchejie.cn/Article/details/gtujoivvio.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zdqjudy.top/Article/details/gtuglljvqv.html

[S14] C：枚举
来源：http://dali.cucudq.cn/Article/details/gttdvxffqi.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.vqdsnc.cn/Article/details/gttwqewcyu.html

[S15] C：类型转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtenemniwt.html

(double) a / b
来源：http://dali.chenjidiqi.icu/Article/details/gtmrcvudfc.html

[S16] C：位操作置位
来源：http://dali.daxiang520.top/Article/details/gtmrgnefuv.html

x |= (1 << 3);
来源：http://dali.xinyue.icu/Article/details/gtnmanihxl.html

[S17] C：安全拼接字符串
来源：http://dali.hnqzz.top/Article/details/gtvjwdjxix.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xuanzx.com/Article/details/gtotgydhie.html

[S18] C：命令行参数
来源：http://dali.zhengqikj.top/Article/details/gtzjokgtdq.html

int main(int argc, char **argv)
来源：http://dali.yj20258888.top/Article/details/gttiqxgyls.html

[S19] C：快速排序
来源：http://dali.svipenyu.cn/Article/details/gtuqxajwar.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.wangdashe.top/Article/details/gtkbbnvgxp.html

[S20] C：二分查找
来源：http://dali.pycfn.com/Article/details/gtweeooxbl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.gotoacloud.top/Article/details/gtklebccck.html

[S21] C：字符类别判断
来源：http://dali.jinghuilouyu.cn/Article/details/gttvcvdoao.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhixingplan.top/Article/details/gtyknouobc.html

[S22] C：字符串转数字
来源：http://dali.gzhubu.top/Article/details/gtbszjpplq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ehwqpu.com/Article/details/gtgcpuqgag.html

[S23] C：随机数
来源：http://dali.sufxvd.cn/Article/details/gttapvgmug.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jianghu66.top/Article/details/gtiezektbm.html

[S24] C：获取本地时间
来源：http://dali.tanke756.top/Article/details/gthvewqsrc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.pengpengdd.cyou/Article/details/gtbcxnmwwe.html

[S25] C：内存拷贝
来源：http://dali.ehwqpu.com/Article/details/gtnxwkzakn.html

memcpy(dst, src, n);
来源：http://dali.nanxinkj.top/Article/details/gtejarsmtx.html

[S26] C：内存清零
来源：http://dali.shanyushiyangtech.top/Article/details/gtvsmwpvkl.html

memset(a, 0, sizeof a);
来源：http://dali.gotoacloud.top/Article/details/gtpwrbomqn.html

[S27] C：定义常量
来源：http://dali.hysaishi.cn/Article/details/gtoevstwmi.html

const double PI = 3.14159;
来源：http://dali.yvedp.cn/Article/details/gtjfotwwkt.html

[S28] C：静态变量
来源：http://dali.tanke756.top/Article/details/gtisgmroap.html

static int counter = 0;
来源：http://dali.yongpay.top/Article/details/gtcufjghij.html

[S29] C：变参函数
来源：http://dali.gaohongyu789.top/Article/details/gttzupwtyg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hfpthk.cn/Article/details/gtzikztodv.html

[S30] C：头文件保护
来源：http://dali.chenlongwang.top/Article/details/gtctzpdgjx.html

#ifndef X_H
来源：http://dali.xylfe.cn/Article/details/gtjpnbuemh.html

#define X_H
来源：http://dali.ybcxt.top/Article/details/gthrczlznm.html

#endif
来源：http://dali.zhixingplan.top/Article/details/gtkynbuope.html

[S31] C++：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gtzgcwsxrq.html

#include <iostream>
来源：http://dali.pengpengdd.cyou/Article/details/gtyhleruxi.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.pycfn.com/Article/details/gtgxkiwwgn.html

[S32] C++：字符串
来源：http://dali.zycfv.cn/Article/details/gtkzxuguiu.html

std::string s = "hi";  s += "!";
来源：http://dali.ydzc1.top/Article/details/gtshwwkiis.html

[S33] C++：vector 增删
来源：http://dali.birdmap.top/Article/details/gtkvylwwfd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gthaohhgmz.html

[S34] C++：遍历 vector
来源：http://dali.kuanghao11.cn/Article/details/gtyyzexvpq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yonumen.top/Article/details/gtynvhgjvc.html

[S35] C++：map
来源：http://dali.haohaochexian.top/Article/details/gtvmopnirl.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yangfankeji.com/Article/details/gtqormuvyf.html

[S36] C++：unordered_map
来源：http://dali.yuxming.cn/Article/details/gtrrqughxu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuxming.cn/Article/details/gtzhxewevn.html

[S37] C++：set
来源：http://dali.yueranfly.top/Article/details/gtdqtokssi.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cheryme.top/Article/details/gtvzikhruo.html

[S38] C++：排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtputajtsg.html

std::sort(v.begin(), v.end());
来源：http://dali.chenzaomai.com/Article/details/gtcagzlxtg.html

[S39] C++：自定义比较器排序
来源：http://dali.gzhubu.top/Article/details/gtfqawirie.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.vqdsnc.cn/Article/details/gtlljvpzqz.html

[S40] C++：查找元素
来源：http://dali.jqgufenzy.top/Article/details/gtitthdipw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ppjwa.cn/Article/details/gtncawpskx.html

[S41] C++：类与构造函数
来源：http://dali.sxryk.cn/Article/details/gtyozwxttj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdlhlkqkx.html

[S42] C++：继承与虚函数
来源：http://dali.zhengqikj.top/Article/details/gtgchcwejf.html

class B : public Base { public: void f() override {} };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrpaivzje.html

[S43] C++：智能指针
来源：http://dali.cqqwz.cn/Article/details/gtcenshmrp.html

auto p = std::make_unique<int>(5);
来源：http://dali.pengpengdd.cyou/Article/details/gtlmscoipa.html

[S44] C++：引用传参
来源：http://dali.shanyushiyangtech.top/Article/details/gtinwojhmo.html

void inc(int &x) { ++x; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdubpnnmx.html

[S45] C++：lambda
来源：http://dali.chenzaomai.com/Article/details/gtycjigfpr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.svipenyu.cn/Article/details/gtpiszzkch.html

[S46] C++：函数模板
来源：http://dali.chenlongwang.top/Article/details/gtbvmfkrlu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.quarkkingdee.top/Article/details/gtlhhdhxie.html

[S47] C++：结构化绑定遍历
来源：http://dali.xuetiantiany.cn/Article/details/gtbkqktwum.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.bjfxy.top/Article/details/gtzcqwvlel.html

[S48] C++：逐行读文件
来源：http://dali.xuetiantiany.cn/Article/details/gtgpanxxjm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.guowangkeji.top/Article/details/gtfmddojjp.html

while (std::getline(in, line)) { }
来源：http://dali.jiagoushi.top/Article/details/gtugratsov.html

[S49] C++：写文件
来源：http://dali.fengsongda.top/Article/details/gtpxfaaqug.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.tianlin.xyz/Article/details/gtzwiqducm.html

[S50] C++：格式化数字
来源：http://dali.gogol.net.cn/Article/details/gtunknwtoh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaaxviscn.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gtvqgvgmeu.html

static_cast<double>(a) / b
来源：http://dali.cucudq.cn/Article/details/gtvrpfeogo.html

[S52] C++：const 与 noexcept
来源：http://dali.zhengqikj.top/Article/details/gtdahswwxk.html

int size() const noexcept { return n_; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwfwpkpxk.html

[S53] C++：移动语义
来源：http://dali.vqdsnc.cn/Article/details/gtqmlbmndj.html

std::vector<int> w = std::move(v);
来源：http://dali.quarkkingdee.top/Article/details/gtjptqmudv.html

[S54] C++：异常处理
来源：http://dali.guowangkeji.top/Article/details/gtxlyfnkwn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jiagoushi.top/Article/details/gtvporwsje.html

[S55] C++：结构化绑定
来源：http://dali.kuanghao11.cn/Article/details/gtppkqgqmn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jiagoushi.top/Article/details/gtpflsieqa.html

[S56] C++：optional
来源：http://dali.tian-w.cn/Article/details/gtlpfghwjj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinqigufen.top/Article/details/gtkafykvio.html

[S57] C++：编译期常量
来源：http://dali.gogol.net.cn/Article/details/gtvlsklrfu.html

constexpr int N = 10;
来源：http://dali.jiagoushi.top/Article/details/gtdindalnw.html

[S58] C++：命名空间
来源：http://dali.smart0.xyz/Article/details/gtzmvqomvo.html

namespace ns { int f() { return 1; } }
来源：http://dali.tian-w.cn/Article/details/gtacmkuzbh.html

[S59] C++：静态断言
来源：http://dali.wangdashe.top/Article/details/gtjgilylso.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.316326.xyz/Article/details/gtvsvkcrps.html

[S60] C++：遍历并删除元素
来源：http://dali.yangfankeji.com/Article/details/gtvozoobcg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.gaohongyu789.top/Article/details/gthaaikbzn.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtdijnjdvo.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtztdvupty.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtrgzitchw.html

[T01] Kotlin：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtocpvczpg.html

println("Hello")
来源：http://dali.daria6918.cn/Article/details/gtpdefwpby.html

[T02] Kotlin：变量
来源：http://dali.chenzaomai.com/Article/details/gtchfgjgrb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.316326.xyz/Article/details/gtvzrqwmjr.html

[T03] Kotlin：字符串模板
来源：http://dali.cashguo.top/Article/details/gtyvpllaja.html

"值: $b"
来源：http://dali.cucudq.cn/Article/details/gtahgibfqs.html

[T04] Kotlin：空安全
来源：http://dali.redwolf501.top/Article/details/gthcfexgcu.html

val n: String? = null;  n?.length
来源：http://dali.snrcjt.cn/Article/details/gtjxhtlwff.html

[T05] Kotlin：when 表达式
来源：http://dali.sufxvd.cn/Article/details/gtvdgdmuxe.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.tianlin.xyz/Article/details/gtbuwosvgp.html

[T06] Kotlin：集合映射
来源：http://dali.zhixingplan.top/Article/details/gtnxnpyuhs.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gtlkkpnvfo.html

[T07] Kotlin：集合过滤
来源：http://dali.jinqigufen.top/Article/details/gtonfexltj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.redwolf501.top/Article/details/gthpnafemg.html

[T08] Kotlin：数据类
来源：http://dali.andypj.xyz/Article/details/gtkzahtlti.html

data class User(val name: String, val age: Int)
来源：http://dali.wangshuangyany.cn/Article/details/gtgribepqc.html

[T09] Kotlin：扩展函数
来源：http://dali.wangshuangyany.cn/Article/details/gtqebjnpok.html

fun String.exclaim() = this + "!"
来源：http://dali.haohaochexian.top/Article/details/gtxzhjwnsz.html

[T10] Kotlin：默认参数
来源：http://dali.yongpay.top/Article/details/gtgafwvxyx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gtcwvzhvme.html

[T11] Kotlin：协程
来源：http://dali.fzhhl.top/Article/details/gtvaamdtqf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jinqigfzy.top/Article/details/gtnyhxnwhm.html

[T12] Kotlin：解构声明
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlecjrhaf.html

val (a, b) = Pair(1, 2)
来源：http://dali.jlsjyb.cn/Article/details/gtqeawdmrs.html

[T13] Kotlin：只读 Map
来源：http://dali.smart0.xyz/Article/details/gtpbjkdwew.html

val m = mapOf("a" to 1)
来源：http://dali.jianghu66.top/Article/details/gtwzzbiodo.html

[T14] Kotlin：循环
来源：http://dali.yongpay.top/Article/details/gtqyonubln.html

for (i in 1..10) println(i)
来源：http://dali.ehwqpu.com/Article/details/gtvrelqubj.html

[T15] Kotlin：接口
来源：http://dali.cheryme.top/Article/details/gtkivofjtc.html

interface Shape { fun area(): Double }
来源：http://dali.gzhubu.top/Article/details/gtuqxhwedh.html

[T16] Swift：Hello World
来源：http://dali.shuidangran.top/Article/details/gtymwqxilp.html

print("Hello")
来源：http://dali.yangfankeji.com/Article/details/gtwfzzfzgs.html

[T17] Swift：变量与常量
来源：http://dali.fengsongda.top/Article/details/gtedewapno.html

var a = 1;  let b = 2
来源：http://dali.yvedp.cn/Article/details/gtlzauztqq.html

[T18] Swift：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrbzaoixd.html

"值: \(b)"
来源：http://dali.9152youxi.cn/Article/details/gtmqwynben.html

[T19] Swift：可选绑定
来源：http://dali.vqdsnc.cn/Article/details/gtnfbedpdf.html

if let n = opt { print(n) }
来源：http://dali.gaohongyu789.top/Article/details/gtrkynjept.html

[T20] Swift：数组操作
来源：http://dali.zdqjudy.top/Article/details/gtncxayryf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.sweek.top/Article/details/gtgundmkos.html

[T21] Swift：遍历
来源：http://dali.xziqi.cn/Article/details/gtyygsbfet.html

for x in a { print(x) }
来源：http://dali.svipenyu.cn/Article/details/gtxmlyfbbb.html

[T22] Swift：字典
来源：http://dali.yvedp.cn/Article/details/gtbuotmfcs.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.sysykeji.top/Article/details/gtqvvorgge.html

[T23] Swift：函数
来源：http://dali.vqdsnc.cn/Article/details/gttrshmytt.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.9152youxi.cn/Article/details/gtplzfdroo.html

[T24] Swift：闭包
来源：http://dali.birdmap.top/Article/details/gttecvyrla.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.smart0.xyz/Article/details/gtakrfvwtl.html

[T25] Swift：结构体
来源：http://dali.bjfxy.top/Article/details/gtaqtoqeqj.html

struct P { var x: Int }
来源：http://dali.cdnleiting.top/Article/details/gtcojyzuwh.html

[T26] Swift：类与重写
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxgprbeip.html

class A: Base { override func f() {} }
来源：http://dali.xziqi.cn/Article/details/gtrrbvdbsc.html

[T27] Swift：错误处理
来源：http://dali.gogol.net.cn/Article/details/gtdccptcpe.html

do { try f() } catch { print(error) }
来源：http://dali.cucudq.cn/Article/details/gtnwqzjbmk.html

[T28] Swift：枚举
来源：http://dali.haohaochexian.top/Article/details/gtzufjpjaw.html

enum Color { case red, green }
来源：http://dali.gzhubu.top/Article/details/gthzboqlxg.html

[T29] Swift：guard 提前返回
来源：http://dali.havefunace.top/Article/details/gttmsogqbm.html

guard let x = opt else { return }
来源：http://dali.tian-w.cn/Article/details/gtchujdhfl.html

[T30] Swift：协议
来源：http://dali.pengpengdd.cyou/Article/details/gtesiwcces.html

protocol Shape { func area() -> Double }
来源：http://dali.yanxiufei.cn/Article/details/gtqjlhgniv.html

[T31] Lua：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtekhrewxc.html

print("Hello")
来源：http://dali.cdnleiting.top/Article/details/gtpwjmekyj.html

[T32] Lua：局部变量
来源：http://dali.feifeiyinyue.top/Article/details/gthltkwgkp.html

local a = 1
来源：http://dali.jianghu66.top/Article/details/gtrvugkktw.html

[T33] Lua：表（数组）
来源：http://dali.nanxuanxn.top/Article/details/gtlyrdoaaw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.guannengcc.top/Article/details/gtbsiwsdvm.html

[T34] Lua：遍历表
来源：http://dali.guannengcc.top/Article/details/gtzchnxwkz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.iojbl.cn/Article/details/gtvyvgwqnr.html

[T35] Lua：字典表
来源：http://dali.shangyingyoupin.top/Article/details/gtfuhwsixu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.gzhubu.top/Article/details/gtktmjsvpk.html

[T36] Lua：函数
来源：http://dali.chenjidiqi.icu/Article/details/gtbqhpidgi.html

function add(a, b) return a + b end
来源：http://dali.guowangkeji.top/Article/details/gtvzhphawp.html

[T37] Lua：字符串拼接
来源：http://dali.guowangkeji.top/Article/details/gtsnnaeldt.html

"a" .. "b"
来源：http://dali.zhongyouzk.top/Article/details/gtjcvayovl.html

[T38] Lua：条件
来源：http://dali.chenlongwang.top/Article/details/gtqbjespjm.html

if x > 0 then print("正") end
来源：http://dali.yonumen.top/Article/details/gthfmasjng.html

[T39] Lua：模式匹配
来源：http://dali.hysaishi.cn/Article/details/gttbrmrrcp.html

string.find(s, "%d+")
来源：http://dali.daxiang520.top/Article/details/gtvraxenbo.html

[T40] Lua：元表
来源：http://dali.havefunace.top/Article/details/gtcowybjaa.html

setmetatable({}, { __index = base })
来源：http://dali.mhx1999.top/Article/details/gtzhjfuhbu.html

[T41] Perl：Hello World
来源：http://dali.yvedp.cn/Article/details/gtbtueyhfs.html

print "Hello\n";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwtzzyfwy.html

[T42] Perl：变量类型
来源：http://dali.sysykeji.top/Article/details/gtxzglpxlj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.pengpengdd.cyou/Article/details/gtllvrocyc.html

[T43] Perl：字符串插值
来源：http://dali.yanxiufei.cn/Article/details/gtykyuhhcr.html

"值: $a"
来源：http://dali.yuxming.cn/Article/details/gttkexzctr.html

[T44] Perl：条件
来源：http://dali.tianlin.xyz/Article/details/gtbeknipcr.html

if ($a > 0) { print "正"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtyqcvwhnm.html

[T45] Perl：数组遍历
来源：http://dali.cucudq.cn/Article/details/gtwwkkoszp.html

for my $x (@arr) { print $x; }
来源：http://dali.jiagoushi.top/Article/details/gtqkzkuyqn.html

[T46] Perl：哈希操作
来源：http://dali.hnqzz.top/Article/details/gtybytcnrz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.gogol.net.cn/Article/details/gtjeivcvxr.html

[T47] Perl：正则捕获
来源：http://dali.birdmap.top/Article/details/gtnybepvpm.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdnxqmpdi.html

[T48] Perl：正则替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkdzrholw.html

$s =~ s/old/new/g;
来源：http://dali.mhx1999.top/Article/details/gtbvnbsmcp.html

[T49] Perl：函数
来源：http://dali.gzhubu.top/Article/details/gtgvsecomc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hfpthk.cn/Article/details/gtdwvggrrc.html

[T50] Perl：逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gtgbztceqe.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yj202588.top/Article/details/gtgbuhoabp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.iojbl.cn/Article/details/gtoeesbdao.html

[T51] Scala：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtcubjgwcs.html

println("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gtjqoxkuoi.html

[T52] Scala：变量
来源：http://dali.ivvv.top/Article/details/gtagtvtzrz.html

val a = 1;  var b = 2
来源：http://dali.yj20258888.top/Article/details/gtxsoalfzf.html

[T53] Scala：字符串插值
来源：http://dali.pycfn.com/Article/details/gtosmusuhn.html

s"值: $b"
来源：http://dali.0kj1m.cn/Article/details/gtvgpslder.html

[T54] Scala：集合映射
来源：http://dali.aizwys.cn/Article/details/gtfzvdmjii.html


<!-- 参考信息 -->