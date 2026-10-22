代发 wailian999

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yuanzhike.top/Article/details/gtpuoqwvke.html

[R56] 远程拷贝
来源：http://dali.haohaochexian.top/Article/details/gtjjmvdsrg.html

scp file user@host:/path/
来源：http://dali.c1oappe.top/Article/details/gthuttjmvo.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gtgjdfsqxs.html

ssh user@host 'uptime'
来源：http://dali.cqqwz.cn/Article/details/gtuffbecwo.html

[R58] 下载文件
来源：http://dali.vqdsnc.cn/Article/details/gtdtqasgnd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cashguo.top/Article/details/gtqrqysnxw.html

[R59] 发 POST JSON
来源：http://dali.hysaishi.cn/Article/details/gtlpnnuhil.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhongyouzk.top/Article/details/gtymaajdzv.html

[R60] 只看 HTTP 状态码
来源：http://dali.chenlongwang.top/Article/details/gttxlbindj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.mhx1999.top/Article/details/gtqijdhhnb.html

[R61] 磁盘占用
来源：http://dali.ppjwa.cn/Article/details/gtkxhochsq.html

df -h;  du -sh *
来源：http://dali.gogol.net.cn/Article/details/gthxhcctwm.html

[R62] 找最占空间的文件
来源：http://dali.fengsongda.top/Article/details/gtgppewdzw.html

du -ah . | sort -rh | head -10
来源：http://dali.cheryme.top/Article/details/gtrgiaxgdy.html

[R63] 内存与进程
来源：http://dali.ehwqpu.com/Article/details/gtsyadytce.html

free -h;  ps aux | grep nginx
来源：http://dali.redwolf501.top/Article/details/gtzhbcatwh.html

[R64] 结束进程
来源：http://dali.jinqigfzy.top/Article/details/gtjlznaife.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xziqi.cn/Article/details/gtzhpbdyst.html

[R65] 查看端口占用
来源：http://dali.jinqigfzy.top/Article/details/gtmffwxoml.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zdqjudy.top/Article/details/gtehpnbkah.html

[R66] 定时任务
来源：http://dali.yj20258888.top/Article/details/gtvbbfvzvj.html

crontab -e;  crontab -l
来源：http://dali.fzhhl.top/Article/details/gtafxzcgll.html

[R67] 生成随机十六进制串
来源：http://dali.yj202588.top/Article/details/gtjfyraqxm.html

openssl rand -hex 16
来源：http://dali.gotoacloud.top/Article/details/gtnxxbtylc.html

[R68] 计算文件校验值
来源：http://dali.xuanzx.com/Article/details/gtjuhlkvba.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.chenlongwang.top/Article/details/gtcgemgizx.html

[R69] 生成随机密码
来源：http://dali.yongpay.top/Article/details/gtbtwziotf.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhongyouzk.top/Article/details/gtzhxtsxkm.html

[R70] 时间戳与互转
来源：http://dali.xylfe.cn/Article/details/gteigipyqg.html

date +%s;  date -d @1700000000
来源：http://dali.hongshengwenyu.top/Article/details/gtdpsjzuha.html

[R71] 日期格式化
来源：http://dali.gotoacloud.top/Article/details/gtaxxatdmn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.vqdsnc.cn/Article/details/gtluxrtsgw.html

[R72] 等待端口就绪
来源：http://dali.jinghuilouyu.cn/Article/details/gtjddipvay.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yj202588.top/Article/details/gtfdpyubhq.html

[R73] 分割大日志
来源：http://dali.gogol.net.cn/Article/details/gtxsjnpkpv.html

split -l 1000 big.log part_
来源：http://dali.bjfxy.top/Article/details/gtszobuujd.html

[R74] 批量重命名
来源：http://dali.snrcjt.cn/Article/details/gtnspprioi.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zdqjudy.top/Article/details/gtdhdijfey.html

[R75] 导出环境变量
来源：http://dali.guowangkeji.top/Article/details/gtgrevuciw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gaohongyu789.top/Article/details/gtsokpqnxk.html

[R76] 使用临时文件
来源：http://dali.redwolf501.top/Article/details/gtwtwwkqyw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.pycfn.com/Article/details/gtxjcrpbpq.html

[R77] 读取用户输入
来源：http://dali.ppjwa.cn/Article/details/gtdkklodxz.html

read -rp "请输入: " ans
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnvhlfmoa.html

[R78] 交互式菜单
来源：http://dali.chenzaomai.com/Article/details/gtnemhwbzo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.0kj1m.cn/Article/details/gtmccrshsn.html

[R79] 解析命令行选项
来源：http://dali.ivvv.top/Article/details/gtxaxdbjzi.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.0kj1m.cn/Article/details/gtqligmtbv.html

[R80] 查看脚本执行耗时
来源：http://dali.ehwqpu.com/Article/details/gteaklgmmn.html

time ./run.sh
来源：http://dali.aibaodan.cn/Article/details/gtepwiiefj.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtfbglznqa.html

S. C / C++ 专题
来源：http://dali.xinyue.icu/Article/details/gtxcrstivj.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtosjtjtmu.html

[S01] C：Hello World
来源：http://dali.ybcxt.top/Article/details/gtzmqddvxi.html

#include <stdio.h>
来源：http://dali.tianlin.xyz/Article/details/gtkgwgeclz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcdqwrfqs.html

[S02] C：变量与格式化输出
来源：http://dali.fzhhl.top/Article/details/gtadxjarfh.html

int a = 10; printf("%d\n", a);
来源：http://dali.haohaochexian.top/Article/details/gtcloqjuqs.html

[S03] C：读入整数
来源：http://dali.guannengcc.top/Article/details/gtjurdqcso.html

int x; scanf("%d", &x);
来源：http://dali.vqdsnc.cn/Article/details/gtqhjgeatm.html

[S04] C：字符串复制
来源：http://dali.quarkkingdee.top/Article/details/gtydpmntdh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yuanzhike.top/Article/details/gtochgdrqv.html

[S05] C：字符串长度
来源：http://dali.sufxvd.cn/Article/details/gtsklovskm.html

strlen(s)
来源：http://dali.mhx1999.top/Article/details/gtyojarsrg.html

[S06] C：字符串比较
来源：http://dali.zhiwuduotai.top/Article/details/gttjbqcukl.html

strcmp(a, b) == 0
来源：http://dali.wangdashe.top/Article/details/gtckfzgobq.html

[S07] C：数组遍历求和
来源：http://dali.daria6918.cn/Article/details/gtytbgejyk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.snrcjt.cn/Article/details/gtlwqhfrag.html

[S08] C：动态内存分配与释放
来源：http://dali.cucudq.cn/Article/details/gtsqoumusl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hnxiangtu.top/Article/details/gtgrfqmnkc.html

[S09] C：结构体定义与初始化
来源：http://dali.jlsjyb.cn/Article/details/gtdeniicyb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.wangshuangyany.cn/Article/details/gtbfworbsv.html

[S10] C：指针与解引用
来源：http://dali.sufxvd.cn/Article/details/gtdmvfesbi.html

int *p = &a;  *p = 5;
来源：http://dali.jinqigufen.top/Article/details/gtrrlygrgy.html

[S11] C：逐行读文件
来源：http://dali.daria6918.cn/Article/details/gtcqotuewn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.tian-w.cn/Article/details/gtogpskzdf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hammf.cn/Article/details/gtohfmqjgc.html

fclose(f);
来源：http://dali.gogol.net.cn/Article/details/gtwdaizjxl.html

[S12] C：写文件
来源：http://dali.quarkkingdee.top/Article/details/gtcefonhwo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yvedp.cn/Article/details/gtoiwxfjrp.html

[S13] C：宏定义
来源：http://dali.cucudq.cn/Article/details/gteiwpvtcl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxulwlvdh.html

[S14] C：枚举
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtodslfbfw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jqgufenzy.top/Article/details/gtnbsjtopv.html

[S15] C：类型转换
来源：http://dali.yj20258.top/Article/details/gtenrrjmyn.html

(double) a / b
来源：http://dali.chenlongwang.top/Article/details/gtgtrvmamn.html

[S16] C：位操作置位
来源：http://dali.chenlongwang.top/Article/details/gtauwyzqge.html

x |= (1 << 3);
来源：http://dali.dianchejie.cn/Article/details/gtsyspiocd.html

[S17] C：安全拼接字符串
来源：http://dali.jiagoushi.top/Article/details/gtlpmxyvia.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.andypj.xyz/Article/details/gtmrtowjmq.html

[S18] C：命令行参数
来源：http://dali.cashguo.top/Article/details/gtfqzdylym.html

int main(int argc, char **argv)
来源：http://dali.zhixingplan.top/Article/details/gttszmsiji.html

[S19] C：快速排序
来源：http://dali.sxryk.cn/Article/details/gtyhqhgysa.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.pycfn.com/Article/details/gtvzidqhoe.html

[S20] C：二分查找
来源：http://dali.ydzc1.top/Article/details/gtyhkjcems.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.iojbl.cn/Article/details/gtuikqkalm.html

[S21] C：字符类别判断
来源：http://dali.yangfankeji.com/Article/details/gtwcveslfr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.redwolf501.top/Article/details/gtwwbuoxgu.html

[S22] C：字符串转数字
来源：http://dali.ivvv.top/Article/details/gtbzujqdqy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.vqdsnc.cn/Article/details/gtmavmubat.html

[S23] C：随机数
来源：http://dali.chenlongwang.top/Article/details/gtfffmmrav.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.pengpengdd.cyou/Article/details/gtzuxxskoh.html

[S24] C：获取本地时间
来源：http://dali.yj20258.top/Article/details/gtcbrfxoam.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cqqwz.cn/Article/details/gtpepavscm.html

[S25] C：内存拷贝
来源：http://dali.fzhhl.top/Article/details/gtzlkhjxbx.html

memcpy(dst, src, n);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtehaxkuna.html

[S26] C：内存清零
来源：http://dali.jyoumei.cn/Article/details/gtppqipoxt.html

memset(a, 0, sizeof a);
来源：http://dali.pycfn.com/Article/details/gtmwzfgpfe.html

[S27] C：定义常量
来源：http://dali.gogol.net.cn/Article/details/gtyoatsjja.html

const double PI = 3.14159;
来源：http://dali.tanke756.top/Article/details/gtbcbbngyd.html

[S28] C：静态变量
来源：http://dali.chenlongwang.top/Article/details/gtvjedosmc.html

static int counter = 0;
来源：http://dali.cucudq.cn/Article/details/gtjfousppl.html

[S29] C：变参函数
来源：http://dali.cashguo.top/Article/details/gtlnweerxj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhengqikj.top/Article/details/gtpeztlnag.html

[S30] C：头文件保护
来源：http://dali.redwolf501.top/Article/details/gtfgouxfpp.html

#ifndef X_H
来源：http://dali.yj202588.top/Article/details/gtjlndswpr.html

#define X_H
来源：http://dali.yj20258.top/Article/details/gtzsdkgvdy.html

#endif
来源：http://dali.sufxvd.cn/Article/details/gtvuzzxgrt.html

[S31] C++：Hello World
来源：http://dali.cucudq.cn/Article/details/gtnkpbclaq.html

#include <iostream>
来源：http://dali.tian-w.cn/Article/details/gthmpxoiug.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ybcxt.top/Article/details/gtzmaeicuk.html

[S32] C++：字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtktpohbuz.html

std::string s = "hi";  s += "!";
来源：http://dali.dashuyun.cn/Article/details/gtmdsdrjmp.html

[S33] C++：vector 增删
来源：http://dali.snrcjt.cn/Article/details/gtzdtoqgyy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.sysykeji.top/Article/details/gtrsgpoguf.html

[S34] C++：遍历 vector
来源：http://dali.shanyushiyangkeji.top/Article/details/gtixhsdbnb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.nanxuanxn.top/Article/details/gtiyfldupp.html

[S35] C++：map
来源：http://dali.nanxuanxn.top/Article/details/gttjqsavds.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shuidangran.top/Article/details/gtbcwmfiix.html

[S36] C++：unordered_map
来源：http://dali.gotoacloud.top/Article/details/gtowrmyrnq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuanzx.com/Article/details/gtqnldggok.html

[S37] C++：set
来源：http://dali.yvedp.cn/Article/details/gtupfnjosz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hnxiangtu.top/Article/details/gtcxiygykt.html

[S38] C++：排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpdvqpbbc.html

std::sort(v.begin(), v.end());
来源：http://dali.jinqigfzy.top/Article/details/gtzbcrgdxi.html

[S39] C++：自定义比较器排序
来源：http://dali.jqgfzy.top/Article/details/gtkqvmlncv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xuetiantiany.cn/Article/details/gtantdiehk.html

[S40] C++：查找元素
来源：http://dali.cdnleiting.top/Article/details/gtdcsofzpa.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gzhubu.top/Article/details/gtoqwdrngt.html

[S41] C++：类与构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gtstmjlqpu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cucudq.cn/Article/details/gtpnspzikz.html

[S42] C++：继承与虚函数
来源：http://dali.shzxlz.cn/Article/details/gtsnwkumce.html

class B : public Base { public: void f() override {} };
来源：http://dali.0kj1m.cn/Article/details/gtmrzsfctv.html

[S43] C++：智能指针
来源：http://dali.snrcjt.cn/Article/details/gtwqbrbwet.html

auto p = std::make_unique<int>(5);
来源：http://dali.wangshuangyany.cn/Article/details/gtdzolklqo.html

[S44] C++：引用传参
来源：http://dali.hysaishi.cn/Article/details/gtacvzasyo.html

void inc(int &x) { ++x; }
来源：http://dali.fengsongda.top/Article/details/gtyeyfolsf.html

[S45] C++：lambda
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqmllkhjw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.birdmap.top/Article/details/gtqgruyksb.html

[S46] C++：函数模板
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxrbjfwaw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.meibo888.top/Article/details/gtvvtodurw.html

[S47] C++：结构化绑定遍历
来源：http://dali.xinyue.icu/Article/details/gtmxahreuj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hnqzz.top/Article/details/gtalstgsao.html

[S48] C++：逐行读文件
来源：http://dali.mhx1999.top/Article/details/gtcqyzazbn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.birdmap.top/Article/details/gtwhigvtow.html

while (std::getline(in, line)) { }
来源：http://dali.haohaochexian.top/Article/details/gtixisxuvz.html

[S49] C++：写文件
来源：http://dali.xuanzx.com/Article/details/gtphnznfzu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.fengsongda.top/Article/details/gtpheiktmq.html

[S50] C++：格式化数字
来源：http://dali.sweek.top/Article/details/gtetveovkz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gtelztpejv.html

[S51] C++：显式类型转换
来源：http://dali.fengsongda.top/Article/details/gtvmrkwejt.html

static_cast<double>(a) / b
来源：http://dali.gogol.net.cn/Article/details/gtsxnfdudk.html

[S52] C++：const 与 noexcept
来源：http://dali.0kj1m.cn/Article/details/gtnezjwoga.html

int size() const noexcept { return n_; }
来源：http://dali.hongshengwenyu.top/Article/details/gtmxmkkooh.html

[S53] C++：移动语义
来源：http://dali.pengpengdd.cyou/Article/details/gtwogtescv.html

std::vector<int> w = std::move(v);
来源：http://dali.ybcxt.top/Article/details/gtfovgwkgr.html

[S54] C++：异常处理
来源：http://dali.sysykeji.top/Article/details/gtsvjpdeiq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ydzc1.top/Article/details/gthvgiorvn.html

[S55] C++：结构化绑定
来源：http://dali.quarkkingdee.top/Article/details/gtkszgrqet.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jqgfzy.top/Article/details/gtchjmqpqh.html

[S56] C++：optional
来源：http://dali.c1oappe.top/Article/details/gtjddgxunf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdlcvdnug.html

[S57] C++：编译期常量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzdupqeaa.html

constexpr int N = 10;
来源：http://dali.gaohongyu789.top/Article/details/gtovlsooxx.html

[S58] C++：命名空间
来源：http://dali.hongshengwenyu.top/Article/details/gtxpogoizw.html

namespace ns { int f() { return 1; } }
来源：http://dali.aibaodan.cn/Article/details/gtrconnwzr.html

[S59] C++：静态断言
来源：http://dali.hfpthk.cn/Article/details/gtbmlkhqam.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shuidangran.top/Article/details/gtesjfjnqx.html

[S60] C++：遍历并删除元素
来源：http://dali.gzhubu.top/Article/details/gtfobsyzaj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ybcxt.top/Article/details/gtzyhtyakb.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbvjuoqow.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jiagoushi.top/Article/details/gtngsvfwfm.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtrcqmvxoc.html

[T01] Kotlin：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtwjtybuyv.html

println("Hello")
来源：http://dali.0kj1m.cn/Article/details/gthqhavnvb.html

[T02] Kotlin：变量
来源：http://dali.chenlongwang.top/Article/details/gtgtwyfqyd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.meibo888.top/Article/details/gthjwfqsdx.html

[T03] Kotlin：字符串模板
来源：http://dali.sufxvd.cn/Article/details/gtmpfagtxt.html

"值: $b"
来源：http://dali.yvedp.cn/Article/details/gthtnzpirv.html

[T04] Kotlin：空安全
来源：http://dali.bjfxy.top/Article/details/gtbxsypkno.html

val n: String? = null;  n?.length
来源：http://dali.cucudq.cn/Article/details/gthbjxaags.html

[T05] Kotlin：when 表达式
来源：http://dali.gzhubu.top/Article/details/gtjuffyesm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjqpvsjrw.html

[T06] Kotlin：集合映射
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgijigwgi.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xziqi.cn/Article/details/gthxlhdrts.html

[T07] Kotlin：集合过滤
来源：http://dali.jqgfzy.top/Article/details/gtypgleefk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hysaishi.cn/Article/details/gtkdebbsks.html

[T08] Kotlin：数据类
来源：http://dali.zdqjudy.top/Article/details/gtogkesrie.html

data class User(val name: String, val age: Int)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtofjcmebx.html

[T09] Kotlin：扩展函数
来源：http://dali.hammf.cn/Article/details/gtapeeklej.html

fun String.exclaim() = this + "!"
来源：http://dali.sufxvd.cn/Article/details/gteklzeeew.html

[T10] Kotlin：默认参数
来源：http://dali.dianchejie.cn/Article/details/gtlibbovnq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shanyushiyangtech.top/Article/details/gtlhripkgp.html

[T11] Kotlin：协程
来源：http://dali.zhongyouzk.top/Article/details/gtrnccnhtg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.havefunace.top/Article/details/gtonyuvwag.html

[T12] Kotlin：解构声明
来源：http://dali.chenjidiqi.icu/Article/details/gtycdepspz.html

val (a, b) = Pair(1, 2)
来源：http://dali.xziqi.cn/Article/details/gtvzukvaec.html

[T13] Kotlin：只读 Map
来源：http://dali.yonumen.top/Article/details/gthvtpndrv.html

val m = mapOf("a" to 1)
来源：http://dali.yvedp.cn/Article/details/gtlyxvvilq.html

[T14] Kotlin：循环
来源：http://dali.svipenyu.cn/Article/details/gthaeavcqp.html

for (i in 1..10) println(i)
来源：http://dali.cheryme.top/Article/details/gtbdeaohif.html

[T15] Kotlin：接口
来源：http://dali.mhx1999.top/Article/details/gtqwergaep.html

interface Shape { fun area(): Double }
来源：http://dali.ehwqpu.com/Article/details/gtjwmqnyzk.html

[T16] Swift：Hello World
来源：http://dali.sxryk.cn/Article/details/gteuzmrbiu.html

print("Hello")
来源：http://dali.ppjwa.cn/Article/details/gtrggckjcz.html

[T17] Swift：变量与常量
来源：http://dali.andypj.xyz/Article/details/gtekmgqhjs.html

var a = 1;  let b = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtcsrbxkbd.html

[T18] Swift：字符串插值
来源：http://dali.jinqigfzy.top/Article/details/gtvlptrtsd.html

"值: \(b)"
来源：http://dali.daria6918.cn/Article/details/gthadbbzyh.html

[T19] Swift：可选绑定
来源：http://dali.redwolf501.top/Article/details/gtvpiygyis.html

if let n = opt { print(n) }
来源：http://dali.aizwys.cn/Article/details/gtusecmaod.html

[T20] Swift：数组操作
来源：http://dali.wangshuangyany.cn/Article/details/gtxcpyqxzf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.nanxinkj.top/Article/details/gttykscvgg.html

[T21] Swift：遍历
来源：http://dali.zhoulong.xyz/Article/details/gtnmmzuibv.html

for x in a { print(x) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdhtironl.html

[T22] Swift：字典
来源：http://dali.hfpthk.cn/Article/details/gtyugkqskv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jqgfzy.top/Article/details/gtciusqbio.html

[T23] Swift：函数
来源：http://dali.hongshengwenyu.top/Article/details/gttsxrzqkh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.mhx1999.top/Article/details/gtljadrtgn.html

[T24] Swift：闭包
来源：http://dali.zhengqikj.top/Article/details/gtekjqxrhj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmfukcqfr.html

[T25] Swift：结构体
来源：http://dali.xziqi.cn/Article/details/gtxsqxqjbr.html

struct P { var x: Int }
来源：http://dali.gotoacloud.top/Article/details/gtbkvicusm.html

[T26] Swift：类与重写
来源：http://dali.jqgfzy.top/Article/details/gtbrilkbta.html

class A: Base { override func f() {} }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtujqumuzq.html

[T27] Swift：错误处理
来源：http://dali.fzhhl.top/Article/details/gtccbbxafg.html

do { try f() } catch { print(error) }
来源：http://dali.birdmap.top/Article/details/gtrtwzkaqa.html

[T28] Swift：枚举
来源：http://dali.tian-w.cn/Article/details/gtkmnxshjp.html

enum Color { case red, green }
来源：http://dali.0kj1m.cn/Article/details/gtbusrofaf.html

[T29] Swift：guard 提前返回
来源：http://dali.tanke756.top/Article/details/gthcmaaucw.html

guard let x = opt else { return }
来源：http://dali.dashuyun.cn/Article/details/gtzjbkwuco.html

[T30] Swift：协议
来源：http://dali.hfpthk.cn/Article/details/gtuijaknjx.html

protocol Shape { func area() -> Double }
来源：http://dali.yvedp.cn/Article/details/gtxfpqmbey.html

[T31] Lua：Hello World
来源：http://dali.hnqzz.top/Article/details/gtncncqhok.html

print("Hello")
来源：http://dali.aizwys.cn/Article/details/gtbzqlpaix.html

[T32] Lua：局部变量
来源：http://dali.yuxming.cn/Article/details/gtymobvhcs.html

local a = 1
来源：http://dali.zdqjudy.top/Article/details/gtvdnmzdxv.html

[T33] Lua：表（数组）
来源：http://dali.daxiang520.top/Article/details/gtnqtvehvt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.chenjidiqi.icu/Article/details/gtgjofyfjf.html

[T34] Lua：遍历表
来源：http://dali.tanke756.top/Article/details/gtotsbekwl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcpjbfaub.html

[T35] Lua：字典表
来源：http://dali.sufxvd.cn/Article/details/gtqdsyjcnb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yuanzhike.top/Article/details/gtcdzdrjhy.html

[T36] Lua：函数
来源：http://dali.havefunace.top/Article/details/gtkioluyfm.html

function add(a, b) return a + b end
来源：http://dali.ybcxt.top/Article/details/gtwkcxfidn.html

[T37] Lua：字符串拼接
来源：http://dali.yueranfly.top/Article/details/gtpjhgorcz.html

"a" .. "b"
来源：http://dali.daxiang520.top/Article/details/gtqibxsgvd.html

[T38] Lua：条件
来源：http://dali.tian-w.cn/Article/details/gtuiyssege.html

if x > 0 then print("正") end
来源：http://dali.chenzaomai.com/Article/details/gtpqqssuiv.html

[T39] Lua：模式匹配
来源：http://dali.wangdashe.top/Article/details/gtagnyoadz.html

string.find(s, "%d+")
来源：http://dali.shuidangran.top/Article/details/gtgvwshras.html

[T40] Lua：元表
来源：http://dali.yj202588.top/Article/details/gtxgdoopef.html

setmetatable({}, { __index = base })
来源：http://dali.hfpthk.cn/Article/details/gtsmtcqzaa.html

[T41] Perl：Hello World
来源：http://dali.yueranfly.top/Article/details/gtxrvlskxs.html

print "Hello\n";
来源：http://dali.tanke756.top/Article/details/gtwhwdjocs.html

[T42] Perl：变量类型
来源：http://dali.redwolf501.top/Article/details/gtbusuukoa.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkzxzwnoq.html

[T43] Perl：字符串插值
来源：http://dali.hfpthk.cn/Article/details/gtalaurdhm.html

"值: $a"
来源：http://dali.yj20258.top/Article/details/gtdaszouwi.html

[T44] Perl：条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpqitwbdb.html

if ($a > 0) { print "正"; }
来源：http://dali.jinqigfzy.top/Article/details/gtdsvngvpb.html

[T45] Perl：数组遍历
来源：http://dali.jqgfzy.top/Article/details/gtoymmjpui.html

for my $x (@arr) { print $x; }
来源：http://dali.hfpthk.cn/Article/details/gtyuuouwyy.html

[T46] Perl：哈希操作
来源：http://dali.zhoulong.xyz/Article/details/gtyztbgbqq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.birdmap.top/Article/details/gtmsuqzodt.html

[T47] Perl：正则捕获
来源：http://dali.pycfn.com/Article/details/gtqzdxwswx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.9152youxi.cn/Article/details/gtwvtyjsfq.html

[T48] Perl：正则替换
来源：http://dali.wangdashe.top/Article/details/gttwnpesqd.html

$s =~ s/old/new/g;
来源：http://dali.tian-w.cn/Article/details/gtbrldxtjz.html

[T49] Perl：函数
来源：http://dali.gaohongyu789.top/Article/details/gthdeildlp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.tianlin.xyz/Article/details/gtipnufibl.html

[T50] Perl：逐行读文件
来源：http://dali.ivvv.top/Article/details/gtndyfctbz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jiagoushi.top/Article/details/gtkbrcysrb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhixingplan.top/Article/details/gtclqigcvu.html

[T51] Scala：Hello World
来源：http://dali.havefunace.top/Article/details/gtbcqxvvai.html

println("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gtcuyincwx.html

[T52] Scala：变量
来源：http://dali.cdnleiting.top/Article/details/gtkegkdmia.html

val a = 1;  var b = 2
来源：http://dali.bjfxy.top/Article/details/gtlhfgfvkg.html

[T53] Scala：字符串插值
来源：http://dali.jqgufenzy.top/Article/details/gtjqnzbtju.html

s"值: $b"
来源：http://dali.redwolf501.top/Article/details/gtdnsidgeb.html

[T54] Scala：集合映射
来源：http://dali.sufxvd.cn/Article/details/gtttfoglgu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jianghu66.top/Article/details/gtkammpary.html

[T55] Scala：集合过滤
来源：http://dali.tianlin.xyz/Article/details/gtqoquwxzy.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zdqjudy.top/Article/details/gtqradrqyk.html

[T56] Scala：样例类
来源：http://dali.hnxiangtu.top/Article/details/gtmrdobffc.html

case class User(name: String, age: Int)
来源：http://dali.yongpay.top/Article/details/gtietgkgps.html

[T57] Scala：模式匹配
来源：http://dali.jqgufenzy.top/Article/details/gtkiksoopc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.meibo888.top/Article/details/gtbmiznxln.html

[T58] Scala：函数定义
来源：http://dali.gotoacloud.top/Article/details/gtrznadqxo.html


<!-- 参考信息 -->