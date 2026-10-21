代发 wailian999

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.9152youxi.cn/Article/details/gtykqvzoud.html

[R52] 统计行数
来源：http://dali.quarkkingdee.top/Article/details/gtjtvkkeuf.html

wc -l a.txt
来源：http://dali.ybcxt.top/Article/details/gtxncfoizt.html

[R53] 查看文件头与实时尾
来源：http://dali.xuanzx.com/Article/details/gtxlywcugm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhengqikj.top/Article/details/gtusqrigzj.html

[R54] 比较两个文件
来源：http://dali.hammf.cn/Article/details/gttlqdpqnk.html

diff a.txt b.txt
来源：http://dali.zhongyouzk.top/Article/details/gtijkmbhsi.html

[R55] 压缩与解压
来源：http://dali.ydzc1.top/Article/details/gtjxrqrjfy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.tian-w.cn/Article/details/gtedtbhizg.html

[R56] 远程拷贝
来源：http://dali.xuetiantiany.cn/Article/details/gtedyjfozy.html

scp file user@host:/path/
来源：http://dali.shuidangran.top/Article/details/gtscekjtvl.html

[R57] 远程执行命令
来源：http://dali.nanxinkj.top/Article/details/gtdajnsmsc.html

ssh user@host 'uptime'
来源：http://dali.chenlongwang.top/Article/details/gtwxjqvtft.html

[R58] 下载文件
来源：http://dali.chenzaomai.com/Article/details/gtxiitlvzv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gaohongyu789.top/Article/details/gtsiyyxxel.html

[R59] 发 POST JSON
来源：http://dali.shuidangran.top/Article/details/gtuchuncfs.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hfpthk.cn/Article/details/gtsqoyqqfm.html

[R60] 只看 HTTP 状态码
来源：http://dali.snrcjt.cn/Article/details/gtminbubys.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gzhubu.top/Article/details/gtxonkrzkq.html

[R61] 磁盘占用
来源：http://dali.gzhubu.top/Article/details/gtofqdpsqd.html

df -h;  du -sh *
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdwnobkcp.html

[R62] 找最占空间的文件
来源：http://dali.jinqigufen.top/Article/details/gtdqdjgvfx.html

du -ah . | sort -rh | head -10
来源：http://dali.zhoulong.xyz/Article/details/gtavoeeqmw.html

[R63] 内存与进程
来源：http://dali.gotoacloud.top/Article/details/gtdjbnpegc.html

free -h;  ps aux | grep nginx
来源：http://dali.zycfv.cn/Article/details/gtjsxcrlmo.html

[R64] 结束进程
来源：http://dali.tianlin.xyz/Article/details/gtigyaazxc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yvedp.cn/Article/details/gtqdiqxaxr.html

[R65] 查看端口占用
来源：http://dali.ehwqpu.com/Article/details/gtgkffffna.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jinqigfzy.top/Article/details/gtxrhjjzzc.html

[R66] 定时任务
来源：http://dali.zdqjudy.top/Article/details/gtelysounh.html

crontab -e;  crontab -l
来源：http://dali.smart0.xyz/Article/details/gtnrwiwxht.html

[R67] 生成随机十六进制串
来源：http://dali.yj20258.top/Article/details/gtzkeddnea.html

openssl rand -hex 16
来源：http://dali.cashguo.top/Article/details/gtituoayai.html

[R68] 计算文件校验值
来源：http://dali.meibo888.top/Article/details/gtdclhlrxq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yongpay.top/Article/details/gtgzmbttju.html

[R69] 生成随机密码
来源：http://dali.zhoulong.xyz/Article/details/gtgxvqvkle.html

head -c 16 /dev/urandom | base64
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthlbmaquy.html

[R70] 时间戳与互转
来源：http://dali.ybcxt.top/Article/details/gtpowcxoce.html

date +%s;  date -d @1700000000
来源：http://dali.jinghuilouyu.cn/Article/details/gtvdspyrgt.html

[R71] 日期格式化
来源：http://dali.hongshengwenyu.top/Article/details/gtuzkymejf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xuetiantiany.cn/Article/details/gttqyubpbw.html

[R72] 等待端口就绪
来源：http://dali.hnxiangtu.top/Article/details/gthiukyqpy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.dianchejie.cn/Article/details/gtceagshti.html

[R73] 分割大日志
来源：http://dali.andypj.xyz/Article/details/gtoqynnfst.html

split -l 1000 big.log part_
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaabxvwqu.html

[R74] 批量重命名
来源：http://dali.tian-w.cn/Article/details/gtwevnvvpi.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.chenlongwang.top/Article/details/gtzkdrlhtw.html

[R75] 导出环境变量
来源：http://dali.jinqigfzy.top/Article/details/gteapgvldh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shuidangran.top/Article/details/gtoktzautj.html

[R76] 使用临时文件
来源：http://dali.hammf.cn/Article/details/gtwenkgrly.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hywenlv.cn/Article/details/gtyspzmubx.html

[R77] 读取用户输入
来源：http://dali.nanxinkj.top/Article/details/gtbiznlykm.html

read -rp "请输入: " ans
来源：http://dali.haohaochexian.top/Article/details/gtzwvfqzug.html

[R78] 交互式菜单
来源：http://dali.yongpay.top/Article/details/gtnhxxsvmn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.tanke756.top/Article/details/gtnzauvllp.html

[R79] 解析命令行选项
来源：http://dali.9152youxi.cn/Article/details/gtabknxqts.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yj20258888.top/Article/details/gtceceodza.html

[R80] 查看脚本执行耗时
来源：http://dali.yvedp.cn/Article/details/gtqomlyhsn.html

time ./run.sh
来源：http://dali.svipenyu.cn/Article/details/gthkpvxtmk.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtxqrhqcnz.html

S. C / C++ 专题
来源：http://dali.nwbrower.top/Article/details/gtjaomstup.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtjklhohwi.html

[S01] C：Hello World
来源：http://dali.fengsongda.top/Article/details/gtuqzizbot.html

#include <stdio.h>
来源：http://dali.yuxming.cn/Article/details/gtlxmviwop.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cqqwz.cn/Article/details/gtobfqpdcw.html

[S02] C：变量与格式化输出
来源：http://dali.daxiang520.top/Article/details/gtgxnqzxjg.html

int a = 10; printf("%d\n", a);
来源：http://dali.smart0.xyz/Article/details/gtlszlxxtt.html

[S03] C：读入整数
来源：http://dali.pengpengdd.cyou/Article/details/gtckkpmtrj.html

int x; scanf("%d", &x);
来源：http://dali.cucudq.cn/Article/details/gtkcypdivk.html

[S04] C：字符串复制
来源：http://dali.yangfankeji.com/Article/details/gtjxxxuzln.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.svipenyu.cn/Article/details/gtpowjqmgz.html

[S05] C：字符串长度
来源：http://dali.pengpengdd.cyou/Article/details/gtjefiwpvt.html

strlen(s)
来源：http://dali.fengsongda.top/Article/details/gtyvjmijdt.html

[S06] C：字符串比较
来源：http://dali.gogol.net.cn/Article/details/gtnoiwhqot.html

strcmp(a, b) == 0
来源：http://dali.sweek.top/Article/details/gtqtttajrz.html

[S07] C：数组遍历求和
来源：http://dali.fengsongda.top/Article/details/gtncqsuxpb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jianghu66.top/Article/details/gtfqnibhpb.html

[S08] C：动态内存分配与释放
来源：http://dali.ydzc1.top/Article/details/gtrhblxevt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jianghu66.top/Article/details/gtwicidfys.html

[S09] C：结构体定义与初始化
来源：http://dali.dashuyun.cn/Article/details/gtohrmtrkr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ybcxt.top/Article/details/gtpvqawjfa.html

[S10] C：指针与解引用
来源：http://dali.mhx1999.top/Article/details/gtqsmfjmsk.html

int *p = &a;  *p = 5;
来源：http://dali.cashguo.top/Article/details/gtdruswylv.html

[S11] C：逐行读文件
来源：http://dali.yongpay.top/Article/details/gtjhavbbpc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xziqi.cn/Article/details/gtnprkyiri.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gaohongyu789.top/Article/details/gthjbqcqms.html

fclose(f);
来源：http://dali.shangyingyoupin.top/Article/details/gtaecwrpyc.html

[S12] C：写文件
来源：http://dali.jlsjyb.cn/Article/details/gtjkfpijwr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.daria6918.cn/Article/details/gttikcfzkx.html

[S13] C：宏定义
来源：http://dali.jlsjyb.cn/Article/details/gtjlcnweor.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.birdmap.top/Article/details/gtqolejtet.html

[S14] C：枚举
来源：http://dali.ppjwa.cn/Article/details/gtblvelbgp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hfpthk.cn/Article/details/gtqobeniuw.html

[S15] C：类型转换
来源：http://dali.zhongyouzk.top/Article/details/gtppzbqinh.html

(double) a / b
来源：http://dali.tanke756.top/Article/details/gtbpdjwfzy.html

[S16] C：位操作置位
来源：http://dali.yanxiufei.cn/Article/details/gtibhjyqaq.html

x |= (1 << 3);
来源：http://dali.nanxuanxn.top/Article/details/gttgwiqgdk.html

[S17] C：安全拼接字符串
来源：http://dali.9152youxi.cn/Article/details/gtztatvolb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.gotoacloud.top/Article/details/gtoqsdlrbd.html

[S18] C：命令行参数
来源：http://dali.9152youxi.cn/Article/details/gtepbwxdqp.html

int main(int argc, char **argv)
来源：http://dali.hysaishi.cn/Article/details/gtnynjemhp.html

[S19] C：快速排序
来源：http://dali.iojbl.cn/Article/details/gtjjfqrbfr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xinyue.icu/Article/details/gtiixpskwy.html

[S20] C：二分查找
来源：http://dali.jqgfzy.top/Article/details/gtaoaxsnyz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hywenlv.cn/Article/details/gtxtkseooi.html

[S21] C：字符类别判断
来源：http://dali.svipenyu.cn/Article/details/gtafzdszjc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xuetiantiany.cn/Article/details/gtgpqiejet.html

[S22] C：字符串转数字
来源：http://dali.hongshengwenyu.top/Article/details/gtxnrhtqzt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jlsjyb.cn/Article/details/gtpqxrkddg.html

[S23] C：随机数
来源：http://dali.chenjidiqi.icu/Article/details/gtdhxxlfkn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sxryk.cn/Article/details/gtdgrhvhzc.html

[S24] C：获取本地时间
来源：http://dali.wangshuangyany.cn/Article/details/gtxziboiza.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hnqzz.top/Article/details/gtuuxwpsii.html

[S25] C：内存拷贝
来源：http://dali.andypj.xyz/Article/details/gtyidoyixx.html

memcpy(dst, src, n);
来源：http://dali.yuxming.cn/Article/details/gtuamlukik.html

[S26] C：内存清零
来源：http://dali.cheryme.top/Article/details/gtsosoihbu.html

memset(a, 0, sizeof a);
来源：http://dali.nanxuanxn.top/Article/details/gtjjkgbdbp.html

[S27] C：定义常量
来源：http://dali.cucudq.cn/Article/details/gtbwwyents.html

const double PI = 3.14159;
来源：http://dali.daxiang520.top/Article/details/gtgwdyuefh.html

[S28] C：静态变量
来源：http://dali.jinqigfzy.top/Article/details/gtngflatlp.html

static int counter = 0;
来源：http://dali.sweek.top/Article/details/gtjfobjsji.html

[S29] C：变参函数
来源：http://dali.xylfe.cn/Article/details/gtvzhkizpi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.haohaochexian.top/Article/details/gtzhvdkzkk.html

[S30] C：头文件保护
来源：http://dali.guannengcc.top/Article/details/gtpbowapid.html

#ifndef X_H
来源：http://dali.gotoacloud.top/Article/details/gthzylfsit.html

#define X_H
来源：http://dali.guowangkeji.top/Article/details/gtpydqitdx.html

#endif
来源：http://dali.cdnleiting.top/Article/details/gtumumbnqh.html

[S31] C++：Hello World
来源：http://dali.xziqi.cn/Article/details/gtjzwoyonf.html

#include <iostream>
来源：http://dali.guannengcc.top/Article/details/gtagyrrhbo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.snrcjt.cn/Article/details/gterbnrsjg.html

[S32] C++：字符串
来源：http://dali.ppjwa.cn/Article/details/gtzccwwesg.html

std::string s = "hi";  s += "!";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcufnpgxj.html

[S33] C++：vector 增删
来源：http://dali.hammf.cn/Article/details/gtbjhpgfvo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.svipenyu.cn/Article/details/gtggcipbvp.html

[S34] C++：遍历 vector
来源：http://dali.316326.xyz/Article/details/gttsvansng.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cheryme.top/Article/details/gtgpbrreih.html

[S35] C++：map
来源：http://dali.hfpthk.cn/Article/details/gtpdvrhivn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yongpay.top/Article/details/gtlurxntbp.html

[S36] C++：unordered_map
来源：http://dali.c1oappe.top/Article/details/gtqqfwrshy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpowqgrey.html

[S37] C++：set
来源：http://dali.xuetiantiany.cn/Article/details/gtzstrobug.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yuxming.cn/Article/details/gtvifccswc.html

[S38] C++：排序
来源：http://dali.316326.xyz/Article/details/gtqurupzed.html

std::sort(v.begin(), v.end());
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwpoykatq.html

[S39] C++：自定义比较器排序
来源：http://dali.kuanghao11.cn/Article/details/gteiwfmkah.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hysaishi.cn/Article/details/gtowdkobwk.html

[S40] C++：查找元素
来源：http://dali.wangdashe.top/Article/details/gtcocqihgb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nanxuanxn.top/Article/details/gtpmfoxziu.html

[S41] C++：类与构造函数
来源：http://dali.yj202588.top/Article/details/gtoqmkhxdb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.gaohongyu789.top/Article/details/gtnhnmiwjr.html

[S42] C++：继承与虚函数
来源：http://dali.iojbl.cn/Article/details/gtwhegwzpl.html

class B : public Base { public: void f() override {} };
来源：http://dali.vqdsnc.cn/Article/details/gtbuhgpkka.html

[S43] C++：智能指针
来源：http://dali.kuanghao11.cn/Article/details/gtmbijdclc.html

auto p = std::make_unique<int>(5);
来源：http://dali.fengsongda.top/Article/details/gtceuapxpz.html

[S44] C++：引用传参
来源：http://dali.gzhubu.top/Article/details/gtdxndfnyf.html

void inc(int &x) { ++x; }
来源：http://dali.hysaishi.cn/Article/details/gttriteabv.html

[S45] C++：lambda
来源：http://dali.cashguo.top/Article/details/gtsucmuoql.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gogol.net.cn/Article/details/gtxjjoswhk.html

[S46] C++：函数模板
来源：http://dali.jlsjyb.cn/Article/details/gtcysvybqg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtzfslumvn.html

[S47] C++：结构化绑定遍历
来源：http://dali.aibaodan.cn/Article/details/gtmfbgwxpx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sysykeji.top/Article/details/gtgcmajhve.html

[S48] C++：逐行读文件
来源：http://dali.yj20258888.top/Article/details/gtpdzzyajm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sweek.top/Article/details/gtiibolbdz.html

while (std::getline(in, line)) { }
来源：http://dali.kuanghao11.cn/Article/details/gtvrmsppef.html

[S49] C++：写文件
来源：http://dali.jqgfzy.top/Article/details/gtawramtrh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.tanke756.top/Article/details/gtsaoioccc.html

[S50] C++：格式化数字
来源：http://dali.quarkkingdee.top/Article/details/gtetstxfcd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhengqikj.top/Article/details/gtdrumofan.html

[S51] C++：显式类型转换
来源：http://dali.cucudq.cn/Article/details/gtnxdlqxec.html

static_cast<double>(a) / b
来源：http://dali.jqgufenzy.top/Article/details/gtgdlesenk.html

[S52] C++：const 与 noexcept
来源：http://dali.meibo888.top/Article/details/gtmquvdscy.html

int size() const noexcept { return n_; }
来源：http://dali.dashuyun.cn/Article/details/gtrhlirsbm.html

[S53] C++：移动语义
来源：http://dali.hnqzz.top/Article/details/gtofpmkgna.html

std::vector<int> w = std::move(v);
来源：http://dali.shzxlz.cn/Article/details/gtwsitlsdl.html

[S54] C++：异常处理
来源：http://dali.sxryk.cn/Article/details/gtbywzxbav.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shzxlz.cn/Article/details/gtfinsuukc.html

[S55] C++：结构化绑定
来源：http://dali.zdqjudy.top/Article/details/gtwceavibn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ybcxt.top/Article/details/gtjlcampzq.html

[S56] C++：optional
来源：http://dali.c1oappe.top/Article/details/gtwnsshplt.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.fzhhl.top/Article/details/gtbnuanpzn.html

[S57] C++：编译期常量
来源：http://dali.pengpengdd.cyou/Article/details/gtnjlieefd.html

constexpr int N = 10;
来源：http://dali.cqqwz.cn/Article/details/gtqfawvxyx.html

[S58] C++：命名空间
来源：http://dali.xinyue.icu/Article/details/gtfarbrhae.html

namespace ns { int f() { return 1; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttceiogvi.html

[S59] C++：静态断言
来源：http://dali.xinyue.icu/Article/details/gtrpfqiczf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yanxiufei.cn/Article/details/gtbgxoxvya.html

[S60] C++：遍历并删除元素
来源：http://dali.hnqzz.top/Article/details/gtegvlhoxp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gtddsbrduq.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtlwyhlhuj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nanxinkj.top/Article/details/gtsoxrjbgs.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtmhapgyav.html

[T01] Kotlin：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtcudehduy.html

println("Hello")
来源：http://dali.yvedp.cn/Article/details/gteubnjwwc.html

[T02] Kotlin：变量
来源：http://dali.yvedp.cn/Article/details/gtfvzywkmr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.birdmap.top/Article/details/gtepttsjpp.html

[T03] Kotlin：字符串模板
来源：http://dali.dashuyun.cn/Article/details/gtdiwliahb.html

"值: $b"
来源：http://dali.sufxvd.cn/Article/details/gtnsbsfnsu.html

[T04] Kotlin：空安全
来源：http://dali.guowangkeji.top/Article/details/gtntfaghya.html

val n: String? = null;  n?.length
来源：http://dali.0kj1m.cn/Article/details/gtbouyforr.html

[T05] Kotlin：when 表达式
来源：http://dali.dianchejie.cn/Article/details/gtpricnbts.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.bjfxy.top/Article/details/gtzwiguuyx.html

[T06] Kotlin：集合映射
来源：http://dali.yangfankeji.com/Article/details/gtzxltnrlb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zdqjudy.top/Article/details/gtavdcvhhy.html

[T07] Kotlin：集合过滤
来源：http://dali.quarkkingdee.top/Article/details/gtiuafoazo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cheryme.top/Article/details/gtwvrrufza.html

[T08] Kotlin：数据类
来源：http://dali.daxiang520.top/Article/details/gtgbzqmfdc.html

data class User(val name: String, val age: Int)
来源：http://dali.yj202588.top/Article/details/gtamroafeb.html

[T09] Kotlin：扩展函数
来源：http://dali.tianlin.xyz/Article/details/gtrckhizjb.html

fun String.exclaim() = this + "!"
来源：http://dali.zhongyouzk.top/Article/details/gtjmugmjrt.html

[T10] Kotlin：默认参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtddbfupzi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.chenlongwang.top/Article/details/gtlrhkhafg.html

[T11] Kotlin：协程
来源：http://dali.yangfankeji.com/Article/details/gtdtakbgrw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ybcxt.top/Article/details/gtjigawgoj.html

[T12] Kotlin：解构声明
来源：http://dali.hammf.cn/Article/details/gttlypjvqz.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkrtjdbqb.html

[T13] Kotlin：只读 Map
来源：http://dali.yanxiufei.cn/Article/details/gtddeqwnvn.html

val m = mapOf("a" to 1)
来源：http://dali.gzhubu.top/Article/details/gtqwvqjaiw.html

[T14] Kotlin：循环
来源：http://dali.sweek.top/Article/details/gtqexavxfg.html

for (i in 1..10) println(i)
来源：http://dali.xuetiantiany.cn/Article/details/gtvwhidzvs.html

[T15] Kotlin：接口
来源：http://dali.zhiwuduotai.top/Article/details/gtzahrzayf.html

interface Shape { fun area(): Double }
来源：http://dali.iojbl.cn/Article/details/gtnvsoshzw.html

[T16] Swift：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtkhvuvzfy.html

print("Hello")
来源：http://dali.sufxvd.cn/Article/details/gtfjmuzywk.html

[T17] Swift：变量与常量
来源：http://dali.yvedp.cn/Article/details/gtocnxtrtz.html

var a = 1;  let b = 2
来源：http://dali.feifeiyinyue.top/Article/details/gtytyldhcg.html

[T18] Swift：字符串插值
来源：http://dali.zhongyouzk.top/Article/details/gtynxuclxe.html

"值: \(b)"
来源：http://dali.cheryme.top/Article/details/gtpipkekbp.html

[T19] Swift：可选绑定
来源：http://dali.jinqigfzy.top/Article/details/gtzikgensb.html

if let n = opt { print(n) }
来源：http://dali.jianghu66.top/Article/details/gtvmvlowrw.html

[T20] Swift：数组操作
来源：http://dali.vqdsnc.cn/Article/details/gtuvdudvuo.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zycfv.cn/Article/details/gtvdjrlynk.html

[T21] Swift：遍历
来源：http://dali.zhiwuduotai.top/Article/details/gtiwuutoqk.html

for x in a { print(x) }
来源：http://dali.daxiang520.top/Article/details/gtqswlftpo.html

[T22] Swift：字典
来源：http://dali.9152youxi.cn/Article/details/gtugzvrxpo.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.guannengcc.top/Article/details/gtspndmwyr.html

[T23] Swift：函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtpgepwpsx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.feifeiyinyue.top/Article/details/gtmavljbfz.html

[T24] Swift：闭包
来源：http://dali.jqgfzy.top/Article/details/gtpbdbluvb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.smart0.xyz/Article/details/gtaaiszznh.html

[T25] Swift：结构体
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdsdmqjpg.html

struct P { var x: Int }
来源：http://dali.9152youxi.cn/Article/details/gtvhzyhbfa.html

[T26] Swift：类与重写
来源：http://dali.wangshuangyany.cn/Article/details/gtzxwahmwk.html

class A: Base { override func f() {} }
来源：http://dali.tian-w.cn/Article/details/gtwfwedhiq.html

[T27] Swift：错误处理
来源：http://dali.jinqigfzy.top/Article/details/gtpvknuria.html

do { try f() } catch { print(error) }
来源：http://dali.shzxlz.cn/Article/details/gtvawvbpjm.html

[T28] Swift：枚举
来源：http://dali.jqgfzy.top/Article/details/gtcnikmcvk.html

enum Color { case red, green }
来源：http://dali.zhengqikj.top/Article/details/gtmcvgkbio.html

[T29] Swift：guard 提前返回
来源：http://dali.jiagoushi.top/Article/details/gtijlffhrb.html

guard let x = opt else { return }
来源：http://dali.aizwys.cn/Article/details/gtrknamnni.html

[T30] Swift：协议
来源：http://dali.xuetiantiany.cn/Article/details/gtyzndurfe.html

protocol Shape { func area() -> Double }
来源：http://dali.yonumen.top/Article/details/gtejxowsxy.html

[T31] Lua：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtvmkqsgjs.html

print("Hello")
来源：http://dali.dianchejie.cn/Article/details/gtkvdwceue.html

[T32] Lua：局部变量
来源：http://dali.ppjwa.cn/Article/details/gtcpjtmlec.html

local a = 1
来源：http://dali.ppjwa.cn/Article/details/gtimeqmnnw.html

[T33] Lua：表（数组）
来源：http://dali.wangshuangyany.cn/Article/details/gtrahmfgoj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhoulong.xyz/Article/details/gtjqnbrvto.html

[T34] Lua：遍历表
来源：http://dali.cheryme.top/Article/details/gtkiokmzbk.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ppjwa.cn/Article/details/gtflfsdxme.html

[T35] Lua：字典表
来源：http://dali.jinghuilouyu.cn/Article/details/gtahfspkdh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xuetiantiany.cn/Article/details/gthwhzgbgd.html

[T36] Lua：函数
来源：http://dali.dianchejie.cn/Article/details/gtiylcyker.html

function add(a, b) return a + b end
来源：http://dali.daxiang520.top/Article/details/gtyivegfsz.html

[T37] Lua：字符串拼接
来源：http://dali.yangfankeji.com/Article/details/gtexqxuifo.html

"a" .. "b"
来源：http://dali.xylfe.cn/Article/details/gtnlmpidvh.html

[T38] Lua：条件
来源：http://dali.yuxming.cn/Article/details/gtmcqjdbuw.html

if x > 0 then print("正") end
来源：http://dali.shanyushiyangtech.top/Article/details/gtyyrlates.html

[T39] Lua：模式匹配
来源：http://dali.jqgufenzy.top/Article/details/gtqukefhgd.html

string.find(s, "%d+")
来源：http://dali.svipenyu.cn/Article/details/gtafcwsucf.html

[T40] Lua：元表
来源：http://dali.redwolf501.top/Article/details/gtmcmtosyv.html

setmetatable({}, { __index = base })
来源：http://dali.kuanghao11.cn/Article/details/gtifiwnmxq.html

[T41] Perl：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtyzzhjstd.html

print "Hello\n";
来源：http://dali.daria6918.cn/Article/details/gtubehiumc.html

[T42] Perl：变量类型
来源：http://dali.dianchejie.cn/Article/details/gtdpkqybos.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhongyouzk.top/Article/details/gtfanlggap.html

[T43] Perl：字符串插值
来源：http://dali.pycfn.com/Article/details/gtyslfsdrk.html

"值: $a"
来源：http://dali.zhixingplan.top/Article/details/gtyhrxjfpb.html

[T44] Perl：条件
来源：http://dali.316326.xyz/Article/details/gtnvamawbg.html

if ($a > 0) { print "正"; }
来源：http://dali.hammf.cn/Article/details/gtuetwgipg.html

[T45] Perl：数组遍历
来源：http://dali.bjfxy.top/Article/details/gtmxqyxxnv.html

for my $x (@arr) { print $x; }
来源：http://dali.yanxiufei.cn/Article/details/gtpzqxpaht.html

[T46] Perl：哈希操作
来源：http://dali.gogol.net.cn/Article/details/gtuengoucm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.nanxinkj.top/Article/details/gtvqbpmtqi.html

[T47] Perl：正则捕获
来源：http://dali.dianchejie.cn/Article/details/gtltpvbccf.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.dashuyun.cn/Article/details/gtgiggrzvs.html

[T48] Perl：正则替换
来源：http://dali.pengpengdd.cyou/Article/details/gtstyyjcfx.html

$s =~ s/old/new/g;
来源：http://dali.zhengqikj.top/Article/details/gtkcwymvqi.html

[T49] Perl：函数
来源：http://dali.ydzc1.top/Article/details/gteijddkzk.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yj20258.top/Article/details/gtnvdvyvic.html

[T50] Perl：逐行读文件
来源：http://dali.hfpthk.cn/Article/details/gterrqfghm.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.smart0.xyz/Article/details/gtohqbknwt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hysaishi.cn/Article/details/gtpvgdwvkx.html

[T51] Scala：Hello World
来源：http://dali.0kj1m.cn/Article/details/gtesilmscb.html

println("Hello")
来源：http://dali.ivvv.top/Article/details/gtuxczpskn.html

[T52] Scala：变量
来源：http://dali.ydzc1.top/Article/details/gtppjissvu.html

val a = 1;  var b = 2
来源：http://dali.aizwys.cn/Article/details/gtxpisvavh.html

[T53] Scala：字符串插值
来源：http://dali.xuetiantiany.cn/Article/details/gtsqglptle.html

s"值: $b"
来源：http://dali.0kj1m.cn/Article/details/gtpjlfheid.html

[T54] Scala：集合映射
来源：http://dali.gaohongyu789.top/Article/details/gtycftmppr.html


<!-- 参考信息 -->