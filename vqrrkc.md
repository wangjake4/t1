代发 wailian999

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yongpay.top/Article/details/gt2cupsntdc.html

[R52] 统计行数
来源：http://dali.sxryk.cn/Article/details/gt2hmiepakl.html

wc -l a.txt
来源：http://dali.yongpay.top/Article/details/gt2dozfjbsb.html

[R53] 查看文件头与实时尾
来源：http://dali.yueranfly.top/Article/details/gt2xgcvhpni.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jyoumei.cn/Article/details/gt2iomeakdv.html

[R54] 比较两个文件
来源：http://dali.cheryme.top/Article/details/gt2fzavylys.html

diff a.txt b.txt
来源：http://dali.shzxlz.cn/Article/details/gt2ulaxspkw.html

[R55] 压缩与解压
来源：http://dali.snrcjt.cn/Article/details/gt2bawhhpny.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.guannengcc.top/Article/details/gt2jvxveten.html

[R56] 远程拷贝
来源：http://dali.guannengcc.top/Article/details/gt2tnbmpiyl.html

scp file user@host:/path/
来源：http://dali.zhixingplan.top/Article/details/gt2xkdzigwp.html

[R57] 远程执行命令
来源：http://dali.jqgufenzy.top/Article/details/gt2srrkwyfl.html

ssh user@host 'uptime'
来源：http://dali.gaohongyu789.top/Article/details/gt2sescjjld.html

[R58] 下载文件
来源：http://dali.9152youxi.cn/Article/details/gt2gmnwevkt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.vqdsnc.cn/Article/details/gt2ijuaohbc.html

[R59] 发 POST JSON
来源：http://dali.hysaishi.cn/Article/details/gt2gclfiidx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.haohaochexian.top/Article/details/gt2mjuksode.html

[R60] 只看 HTTP 状态码
来源：http://dali.yuxming.cn/Article/details/gt2ciastbxe.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cdnleiting.top/Article/details/gt2saiognbf.html

[R61] 磁盘占用
来源：http://dali.pengpengdd.cyou/Article/details/gt2vclxhzzx.html

df -h;  du -sh *
来源：http://dali.jiagoushi.top/Article/details/gt2hppugcyj.html

[R62] 找最占空间的文件
来源：http://dali.daxiang520.top/Article/details/gt2osaypzqn.html

du -ah . | sort -rh | head -10
来源：http://dali.ivvv.top/Article/details/gt2zxwevhgt.html

[R63] 内存与进程
来源：http://dali.redwolf501.top/Article/details/gt2yryrfgaq.html

free -h;  ps aux | grep nginx
来源：http://dali.nanxinkj.top/Article/details/gt2afioaecz.html

[R64] 结束进程
来源：http://dali.ydzc1.top/Article/details/gt2kqgsjkjf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.dashuyun.cn/Article/details/gt2bpuukqnb.html

[R65] 查看端口占用
来源：http://dali.yuxming.cn/Article/details/gt2pchqpdjd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2smdnyxxl.html

[R66] 定时任务
来源：http://dali.zhengqikj.top/Article/details/gt2clynplzs.html

crontab -e;  crontab -l
来源：http://dali.mhx1999.top/Article/details/gt2vzkksrpe.html

[R67] 生成随机十六进制串
来源：http://dali.jqgfzy.top/Article/details/gt2bjlkapym.html

openssl rand -hex 16
来源：http://dali.haohaochexian.top/Article/details/gt2dyujguts.html

[R68] 计算文件校验值
来源：http://dali.smart0.xyz/Article/details/gt2jwmspkra.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.kuanghao11.cn/Article/details/gt2crmhrgwv.html

[R69] 生成随机密码
来源：http://dali.haohaochexian.top/Article/details/gt2kinbnzlm.html

head -c 16 /dev/urandom | base64
来源：http://dali.chenjidiqi.icu/Article/details/gt2shvnbqwg.html

[R70] 时间戳与互转
来源：http://dali.yuxming.cn/Article/details/gt2ywdufpgx.html

date +%s;  date -d @1700000000
来源：http://dali.daxiang520.top/Article/details/gt2djqzlsrf.html

[R71] 日期格式化
来源：http://dali.meibo888.top/Article/details/gt2vokrhygz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ehwqpu.com/Article/details/gt2enejssls.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2skteigxk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.gzhubu.top/Article/details/gt2svlzhjui.html

[R73] 分割大日志
来源：http://dali.quarkkingdee.top/Article/details/gt2chcbvsli.html

split -l 1000 big.log part_
来源：http://dali.pycfn.com/Article/details/gt2sqgbmchn.html

[R74] 批量重命名
来源：http://dali.yongpay.top/Article/details/gt2rabdfqct.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.haohaochexian.top/Article/details/gt2dqfiampj.html

[R75] 导出环境变量
来源：http://dali.pycfn.com/Article/details/gt2fmjzahap.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xinyue.icu/Article/details/gt2dqtjvmqx.html

[R76] 使用临时文件
来源：http://dali.xinyue.icu/Article/details/gt2gstcuxrz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shanyushiyangtech.top/Article/details/gt2loiyikes.html

[R77] 读取用户输入
来源：http://dali.tianlin.xyz/Article/details/gt2wciklxpt.html

read -rp "请输入: " ans
来源：http://dali.guannengcc.top/Article/details/gt2rhcpjeej.html

[R78] 交互式菜单
来源：http://dali.hfpthk.cn/Article/details/gt2essagpil.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinqigufen.top/Article/details/gt2lgqzbcyo.html

[R79] 解析命令行选项
来源：http://dali.gzhubu.top/Article/details/gt2jcbthtlf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.havefunace.top/Article/details/gt2xrhlefcy.html

[R80] 查看脚本执行耗时
来源：http://dali.jinqigfzy.top/Article/details/gt2gjtuzupk.html

time ./run.sh
来源：http://dali.guannengcc.top/Article/details/gt2onfrlhmb.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2yrulofos.html

S. C / C++ 专题
来源：http://dali.cqqwz.cn/Article/details/gt2beomzqlo.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2oitqtmdv.html

[S01] C：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gt2fmquprjd.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwotrdw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cashguo.top/Article/details/gt2tenghjza.html

[S02] C：变量与格式化输出
来源：http://dali.zhoulong.xyz/Article/details/gt2apftfjdb.html

int a = 10; printf("%d\n", a);
来源：http://dali.sweek.top/Article/details/gt2nrdxkaku.html

[S03] C：读入整数
来源：http://dali.nwbrower.top/Article/details/gt2pzqiiutf.html

int x; scanf("%d", &x);
来源：http://dali.nanxuanxn.top/Article/details/gt2lnbjcwbe.html

[S04] C：字符串复制
来源：http://dali.gzhubu.top/Article/details/gt2kzbkmzhs.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.vqdsnc.cn/Article/details/gt2awhlallo.html

[S05] C：字符串长度
来源：http://dali.jqgufenzy.top/Article/details/gt2tqxsivkw.html

strlen(s)
来源：http://dali.bjfxy.top/Article/details/gt2doximizv.html

[S06] C：字符串比较
来源：http://dali.jqgfzy.top/Article/details/gt2xythgmrt.html

strcmp(a, b) == 0
来源：http://dali.9152youxi.cn/Article/details/gt2ojtueipi.html

[S07] C：数组遍历求和
来源：http://dali.cashguo.top/Article/details/gt2hexqsoxn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jyoumei.cn/Article/details/gt2qvanfprj.html

[S08] C：动态内存分配与释放
来源：http://dali.hysaishi.cn/Article/details/gt2dhfcrich.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.mhx1999.top/Article/details/gt2djdzyecs.html

[S09] C：结构体定义与初始化
来源：http://dali.meibo888.top/Article/details/gt2dcukzjrn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yj20258888.top/Article/details/gt2ejwmeypn.html

[S10] C：指针与解引用
来源：http://dali.yangfankeji.com/Article/details/gt2owlzutuo.html

int *p = &a;  *p = 5;
来源：http://dali.daxiang520.top/Article/details/gt2kupjqpwa.html

[S11] C：逐行读文件
来源：http://dali.9152youxi.cn/Article/details/gt2qwynbxul.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ztrgqsdf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.wangdashe.top/Article/details/gt2plxhttob.html

fclose(f);
来源：http://dali.chenzaomai.com/Article/details/gt2vlftqwje.html

[S12] C：写文件
来源：http://dali.nanxinkj.top/Article/details/gt2kgryovqm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.chenlongwang.top/Article/details/gt2wwlsxdwg.html

[S13] C：宏定义
来源：http://dali.hammf.cn/Article/details/gt2mnvvwebi.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.aizwys.cn/Article/details/gt2xirspxww.html

[S14] C：枚举
来源：http://dali.jinqigfzy.top/Article/details/gt2cmtilzyk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sysykeji.top/Article/details/gt2eyjpmwxm.html

[S15] C：类型转换
来源：http://dali.tianlin.xyz/Article/details/gt2tdngdnsq.html

(double) a / b
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ouifpucm.html

[S16] C：位操作置位
来源：http://dali.sweek.top/Article/details/gt2srbylvip.html

x |= (1 << 3);
来源：http://dali.gaohongyu789.top/Article/details/gt2nvafkjfr.html

[S17] C：安全拼接字符串
来源：http://dali.316326.xyz/Article/details/gt2rxekkfom.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cucudq.cn/Article/details/gt2vqvmjytm.html

[S18] C：命令行参数
来源：http://dali.svipenyu.cn/Article/details/gt2sraoauie.html

int main(int argc, char **argv)
来源：http://dali.jinqigufen.top/Article/details/gt2iqwmfssx.html

[S19] C：快速排序
来源：http://dali.yuxming.cn/Article/details/gt2qdlkwexz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yvedp.cn/Article/details/gt2qagfmqbj.html

[S20] C：二分查找
来源：http://dali.mhx1999.top/Article/details/gt2tulhnekm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cucudq.cn/Article/details/gt2odzkdutt.html

[S21] C：字符类别判断
来源：http://dali.sweek.top/Article/details/gt2rnerzxpj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yj202588.top/Article/details/gt2zhrivwhk.html

[S22] C：字符串转数字
来源：http://dali.316326.xyz/Article/details/gt2tdijtxgq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.haohaochexian.top/Article/details/gt2ljaeiquy.html

[S23] C：随机数
来源：http://dali.jqgufenzy.top/Article/details/gt2cxpbwstc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jlsjyb.cn/Article/details/gt2kdpugeje.html

[S24] C：获取本地时间
来源：http://dali.fzhhl.top/Article/details/gt2tuuppixs.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sxryk.cn/Article/details/gt2lwbrhlka.html

[S25] C：内存拷贝
来源：http://dali.hammf.cn/Article/details/gt2lchgwrma.html

memcpy(dst, src, n);
来源：http://dali.gogol.net.cn/Article/details/gt2rxskurcb.html

[S26] C：内存清零
来源：http://dali.nanxinkj.top/Article/details/gt2cjbymjsr.html

memset(a, 0, sizeof a);
来源：http://dali.andypj.xyz/Article/details/gt2jwcxjxpq.html

[S27] C：定义常量
来源：http://dali.snrcjt.cn/Article/details/gt2jrqdjpza.html

const double PI = 3.14159;
来源：http://dali.tian-w.cn/Article/details/gt2wcjpphel.html

[S28] C：静态变量
来源：http://dali.ehwqpu.com/Article/details/gt2indetrtt.html

static int counter = 0;
来源：http://dali.hammf.cn/Article/details/gt2ufcnemyk.html

[S29] C：变参函数
来源：http://dali.meibo888.top/Article/details/gt2qghhweay.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cdnleiting.top/Article/details/gt2wkerxchn.html

[S30] C：头文件保护
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pfcbrtkq.html

#ifndef X_H
来源：http://dali.c1oappe.top/Article/details/gt2pjwemytd.html

#define X_H
来源：http://dali.cdnleiting.top/Article/details/gt2ambwxwdq.html

#endif
来源：http://dali.xuanzx.com/Article/details/gt2fpyciyyy.html

[S31] C++：Hello World
来源：http://dali.xziqi.cn/Article/details/gt2xafvcqcc.html

#include <iostream>
来源：http://dali.sweek.top/Article/details/gt2oqbbiryq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.nwbrower.top/Article/details/gt2bflngjyh.html

[S32] C++：字符串
来源：http://dali.tianlin.xyz/Article/details/gt2eoqishgc.html

std::string s = "hi";  s += "!";
来源：http://dali.ydzc1.top/Article/details/gt2jufusxgk.html

[S33] C++：vector 增删
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ekqkqtog.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hywenlv.cn/Article/details/gt2udwubhtn.html

[S34] C++：遍历 vector
来源：http://dali.guowangkeji.top/Article/details/gt2trfqmkzc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.chenlongwang.top/Article/details/gt2cmkpxayu.html

[S35] C++：map
来源：http://dali.yuxming.cn/Article/details/gt2sqhlplzi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.smart0.xyz/Article/details/gt2xqhkuabq.html

[S36] C++：unordered_map
来源：http://dali.redwolf501.top/Article/details/gt2zodqemwg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hfpthk.cn/Article/details/gt2embynrys.html

[S37] C++：set
来源：http://dali.xylfe.cn/Article/details/gt2ircbdarw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.wangshuangyany.cn/Article/details/gt2wschsseg.html

[S38] C++：排序
来源：http://dali.hammf.cn/Article/details/gt2vcnbluts.html

std::sort(v.begin(), v.end());
来源：http://dali.jinqigfzy.top/Article/details/gt2knkfjwfx.html

[S39] C++：自定义比较器排序
来源：http://dali.xylfe.cn/Article/details/gt2xpbaubyk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.tanke756.top/Article/details/gt2veafusfj.html

[S40] C++：查找元素
来源：http://dali.xinyue.icu/Article/details/gt2qexyints.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jyoumei.cn/Article/details/gt2alrzqinu.html

[S41] C++：类与构造函数
来源：http://dali.ppjwa.cn/Article/details/gt2omcuknfm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhengqikj.top/Article/details/gt2cqpjzzsk.html

[S42] C++：继承与虚函数
来源：http://dali.gaohongyu789.top/Article/details/gt2nsfttwqh.html

class B : public Base { public: void f() override {} };
来源：http://dali.nanxinkj.top/Article/details/gt2fbbuehrx.html

[S43] C++：智能指针
来源：http://dali.jyoumei.cn/Article/details/gt2qpeigaju.html

auto p = std::make_unique<int>(5);
来源：http://dali.yanxiufei.cn/Article/details/gt2gafbxxrv.html

[S44] C++：引用传参
来源：http://dali.nanxuanxn.top/Article/details/gt2ghamlhrh.html

void inc(int &x) { ++x; }
来源：http://dali.yangfankeji.com/Article/details/gt2koefdpwt.html

[S45] C++：lambda
来源：http://dali.ydzc1.top/Article/details/gt2dpnmrygn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yj20258.top/Article/details/gt2erohkulk.html

[S46] C++：函数模板
来源：http://dali.hammf.cn/Article/details/gt2yyzqfmxw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.birdmap.top/Article/details/gt2yrjjykck.html

[S47] C++：结构化绑定遍历
来源：http://dali.hfpthk.cn/Article/details/gt2tqzcvxyd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.haohaochexian.top/Article/details/gt2wboexsxq.html

[S48] C++：逐行读文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2ubbmysdo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhoulong.xyz/Article/details/gt2qeojwcwz.html

while (std::getline(in, line)) { }
来源：http://dali.ehwqpu.com/Article/details/gt2aqkhubnt.html

[S49] C++：写文件
来源：http://dali.wangdashe.top/Article/details/gt2jeguxnwd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.tian-w.cn/Article/details/gt2mumiupto.html

[S50] C++：格式化数字
来源：http://dali.ydzc1.top/Article/details/gt2xbizthgi.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gt2suiucnai.html

[S51] C++：显式类型转换
来源：http://dali.snrcjt.cn/Article/details/gt2tpfftspv.html

static_cast<double>(a) / b
来源：http://dali.jqgufenzy.top/Article/details/gt2trblbtkk.html

[S52] C++：const 与 noexcept
来源：http://dali.xinyue.icu/Article/details/gt2spjnkpds.html

int size() const noexcept { return n_; }
来源：http://dali.yongpay.top/Article/details/gt2otvgiuzp.html

[S53] C++：移动语义
来源：http://dali.jiagoushi.top/Article/details/gt2jacerted.html

std::vector<int> w = std::move(v);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xmvmmpsa.html

[S54] C++：异常处理
来源：http://dali.hfpthk.cn/Article/details/gt2ucexkasy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lrkvnecr.html

[S55] C++：结构化绑定
来源：http://dali.pycfn.com/Article/details/gt2kkoxylkv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yangfankeji.com/Article/details/gt2dedmlejx.html

[S56] C++：optional
来源：http://dali.gzhubu.top/Article/details/gt2oueyxgag.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jruyavyj.html

[S57] C++：编译期常量
来源：http://dali.guannengcc.top/Article/details/gt2ecvpofct.html

constexpr int N = 10;
来源：http://dali.xinyue.icu/Article/details/gt2quolplhx.html

[S58] C++：命名空间
来源：http://dali.haohaochexian.top/Article/details/gt2lmjwccyv.html

namespace ns { int f() { return 1; } }
来源：http://dali.nwbrower.top/Article/details/gt2wqozvhuq.html

[S59] C++：静态断言
来源：http://dali.0kj1m.cn/Article/details/gt2jxfsltit.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zdqjudy.top/Article/details/gt2cqvyaopu.html

[S60] C++：遍历并删除元素
来源：http://dali.xziqi.cn/Article/details/gt2qhkttfvm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.9152youxi.cn/Article/details/gt2vkpnsuza.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2edqitmbd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.pycfn.com/Article/details/gt2zguttdas.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2tupchzva.html

[T01] Kotlin：Hello World
来源：http://dali.nanxinkj.top/Article/details/gt2gviwkzuu.html

println("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gt2dckscskh.html

[T02] Kotlin：变量
来源：http://dali.aibaodan.cn/Article/details/gt2rpbawzax.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hfpthk.cn/Article/details/gt2kmsfilaw.html

[T03] Kotlin：字符串模板
来源：http://dali.snrcjt.cn/Article/details/gt2yvlqusht.html

"值: $b"
来源：http://dali.smart0.xyz/Article/details/gt2ecvmwhbk.html

[T04] Kotlin：空安全
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fmagjojm.html

val n: String? = null;  n?.length
来源：http://dali.quarkkingdee.top/Article/details/gt2yeqxjfrx.html

[T05] Kotlin：when 表达式
来源：http://dali.yvedp.cn/Article/details/gt2bwwtvbwd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.nwbrower.top/Article/details/gt2mwahsijf.html

[T06] Kotlin：集合映射
来源：http://dali.hongshengwenyu.top/Article/details/gt2fgkyhfnc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xylfe.cn/Article/details/gt2ykkhrypz.html

[T07] Kotlin：集合过滤
来源：http://dali.gaohongyu789.top/Article/details/gt2gimaynqv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xinyue.icu/Article/details/gt2facdxjxc.html

[T08] Kotlin：数据类
来源：http://dali.yuxming.cn/Article/details/gt2eeqjeyui.html

data class User(val name: String, val age: Int)
来源：http://dali.sysykeji.top/Article/details/gt2poibsekx.html

[T09] Kotlin：扩展函数
来源：http://dali.jiagoushi.top/Article/details/gt2egijuhlb.html

fun String.exclaim() = this + "!"
来源：http://dali.gzhubu.top/Article/details/gt2nzinvvvl.html

[T10] Kotlin：默认参数
来源：http://dali.smart0.xyz/Article/details/gt2yawaqvmh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.vqdsnc.cn/Article/details/gt2ypfwelhu.html

[T11] Kotlin：协程
来源：http://dali.iojbl.cn/Article/details/gt2oklklyal.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yj20258888.top/Article/details/gt2uloemnji.html

[T12] Kotlin：解构声明
来源：http://dali.hnxiangtu.top/Article/details/gt2bsvcmrmt.html

val (a, b) = Pair(1, 2)
来源：http://dali.chenlongwang.top/Article/details/gt2uzzzpefr.html

[T13] Kotlin：只读 Map
来源：http://dali.chenjidiqi.icu/Article/details/gt2tdoqkuit.html

val m = mapOf("a" to 1)
来源：http://dali.cheryme.top/Article/details/gt2tugeaeyq.html

[T14] Kotlin：循环
来源：http://dali.yueranfly.top/Article/details/gt2wthpyvyc.html

for (i in 1..10) println(i)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rzevfwps.html

[T15] Kotlin：接口
来源：http://dali.zhiwuduotai.top/Article/details/gt2uszidyun.html

interface Shape { fun area(): Double }
来源：http://dali.zhengqikj.top/Article/details/gt2ksdkplrl.html

[T16] Swift：Hello World
来源：http://dali.dianchejie.cn/Article/details/gt2ahnfzodr.html

print("Hello")
来源：http://dali.chenzaomai.com/Article/details/gt2etbgftfc.html

[T17] Swift：变量与常量
来源：http://dali.hywenlv.cn/Article/details/gt2uhbegfib.html

var a = 1;  let b = 2
来源：http://dali.hnxiangtu.top/Article/details/gt2gemthhpr.html

[T18] Swift：字符串插值
来源：http://dali.hongshengwenyu.top/Article/details/gt2gvjheixs.html

"值: \(b)"
来源：http://dali.pengpengdd.cyou/Article/details/gt2lodktddk.html

[T19] Swift：可选绑定
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vljychhm.html

if let n = opt { print(n) }
来源：http://dali.jyoumei.cn/Article/details/gt2veoksscj.html

[T20] Swift：数组操作
来源：http://dali.hongshengwenyu.top/Article/details/gt2hvdhzsmx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.aibaodan.cn/Article/details/gt2pmirxwgp.html

[T21] Swift：遍历
来源：http://dali.xziqi.cn/Article/details/gt2hwhgjzrj.html

for x in a { print(x) }
来源：http://dali.jqgfzy.top/Article/details/gt2slvyzdmj.html

[T22] Swift：字典
来源：http://dali.hysaishi.cn/Article/details/gt2ymcmnhwr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zvmzcalb.html

[T23] Swift：函数
来源：http://dali.ppjwa.cn/Article/details/gt2xtzzyqpl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sufxvd.cn/Article/details/gt2mmerajuk.html

[T24] Swift：闭包
来源：http://dali.hammf.cn/Article/details/gt2gldowthx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yangfankeji.com/Article/details/gt2okxbuekr.html

[T25] Swift：结构体
来源：http://dali.havefunace.top/Article/details/gt2tnbgzetc.html

struct P { var x: Int }
来源：http://dali.yuxming.cn/Article/details/gt2lkwckspv.html

[T26] Swift：类与重写
来源：http://dali.smart0.xyz/Article/details/gt2rjzpiliw.html

class A: Base { override func f() {} }
来源：http://dali.xuetiantiany.cn/Article/details/gt2qxabolxx.html

[T27] Swift：错误处理
来源：http://dali.cdnleiting.top/Article/details/gt2ayittywg.html

do { try f() } catch { print(error) }
来源：http://dali.dianchejie.cn/Article/details/gt2iiwjepdt.html

[T28] Swift：枚举
来源：http://dali.ydzc1.top/Article/details/gt2emldorec.html

enum Color { case red, green }
来源：http://dali.sysykeji.top/Article/details/gt2rphlkigt.html

[T29] Swift：guard 提前返回
来源：http://dali.haohaochexian.top/Article/details/gt2fbtttpcn.html

guard let x = opt else { return }
来源：http://dali.shuidangran.top/Article/details/gt2iaxplmiu.html

[T30] Swift：协议
来源：http://dali.daxiang520.top/Article/details/gt2hdgzywbe.html

protocol Shape { func area() -> Double }
来源：http://dali.dianchejie.cn/Article/details/gt2eymgldfg.html

[T31] Lua：Hello World
来源：http://dali.mhx1999.top/Article/details/gt2bpcgbmje.html

print("Hello")
来源：http://dali.c1oappe.top/Article/details/gt2bxcqzyho.html

[T32] Lua：局部变量
来源：http://dali.gaohongyu789.top/Article/details/gt2hyvxmgai.html

local a = 1
来源：http://dali.tanke756.top/Article/details/gt2arwwundy.html

[T33] Lua：表（数组）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kuymmnet.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.nwbrower.top/Article/details/gt2sadnzvfg.html

[T34] Lua：遍历表
来源：http://dali.jqgufenzy.top/Article/details/gt2cnyxxeca.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xinyue.icu/Article/details/gt2nnzdmebd.html

[T35] Lua：字典表
来源：http://dali.shzxlz.cn/Article/details/gt2rsklgzmo.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jinqigfzy.top/Article/details/gt2fofrmpyb.html

[T36] Lua：函数
来源：http://dali.iojbl.cn/Article/details/gt2ecbojhwz.html

function add(a, b) return a + b end
来源：http://dali.snrcjt.cn/Article/details/gt2zpzkoeuu.html

[T37] Lua：字符串拼接
来源：http://dali.jqgufenzy.top/Article/details/gt2rqviqdxt.html

"a" .. "b"
来源：http://dali.yj20258888.top/Article/details/gt2zquysenn.html

[T38] Lua：条件
来源：http://dali.zycfv.cn/Article/details/gt2banyaktg.html

if x > 0 then print("正") end
来源：http://dali.jqgfzy.top/Article/details/gt2glvghucy.html

[T39] Lua：模式匹配
来源：http://dali.yueranfly.top/Article/details/gt2rcdyogee.html

string.find(s, "%d+")
来源：http://dali.sysykeji.top/Article/details/gt2udjpntfo.html

[T40] Lua：元表
来源：http://dali.cheryme.top/Article/details/gt2bsdpthul.html

setmetatable({}, { __index = base })
来源：http://dali.zycfv.cn/Article/details/gt2ncujjyon.html

[T41] Perl：Hello World
来源：http://dali.snrcjt.cn/Article/details/gt2efqaepll.html

print "Hello\n";
来源：http://dali.hnqzz.top/Article/details/gt2dktmgvwe.html

[T42] Perl：变量类型
来源：http://dali.birdmap.top/Article/details/gt2igxaedvq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.gaohongyu789.top/Article/details/gt2kkzerdlm.html

[T43] Perl：字符串插值
来源：http://dali.zhengqikj.top/Article/details/gt2kppvtdbj.html

"值: $a"
来源：http://dali.nwbrower.top/Article/details/gt2xkzirydd.html

[T44] Perl：条件
来源：http://dali.smart0.xyz/Article/details/gt2weyooycn.html

if ($a > 0) { print "正"; }
来源：http://dali.haohaochexian.top/Article/details/gt2mhikyxxa.html

[T45] Perl：数组遍历
来源：http://dali.yonumen.top/Article/details/gt2erxyykms.html

for my $x (@arr) { print $x; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2enwyeqnj.html

[T46] Perl：哈希操作
来源：http://dali.tianlin.xyz/Article/details/gt2bczkxzyc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.tian-w.cn/Article/details/gt2phcyfdcg.html

[T47] Perl：正则捕获
来源：http://dali.0kj1m.cn/Article/details/gt2wmjyqdir.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.guowangkeji.top/Article/details/gt2mrmpoubr.html

[T48] Perl：正则替换
来源：http://dali.jiagoushi.top/Article/details/gt2kgamxpsp.html

$s =~ s/old/new/g;
来源：http://dali.yj202588.top/Article/details/gt2xjyrutlv.html

[T49] Perl：函数
来源：http://dali.yongpay.top/Article/details/gt2lljajdeq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.iojbl.cn/Article/details/gt2hqllslnm.html

[T50] Perl：逐行读文件
来源：http://dali.xylfe.cn/Article/details/gt2umloylwh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.daria6918.cn/Article/details/gt2jfchgpan.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ybcxt.top/Article/details/gt2zfmitzqz.html

[T51] Scala：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2otaaxbux.html

println("Hello")
来源：http://dali.9152youxi.cn/Article/details/gt2huunreyr.html

[T52] Scala：变量
来源：http://dali.hywenlv.cn/Article/details/gt2cxovgozs.html

val a = 1;  var b = 2
来源：http://dali.svipenyu.cn/Article/details/gt2cldjvctn.html

[T53] Scala：字符串插值
来源：http://dali.yj20258888.top/Article/details/gt2totmhuah.html

s"值: $b"
来源：http://dali.yueranfly.top/Article/details/gt2spvitmsn.html

[T54] Scala：集合映射
来源：http://dali.fengsongda.top/Article/details/gt2smcryxpg.html


<!-- 参考信息 -->