代发 wailian999

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.tanke756.top/Article/details/gtykyjspsh.html

[R54] 比较两个文件
来源：http://dali.nanxuanxn.top/Article/details/gtmymevxpc.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gtxdtvnywm.html

[R55] 压缩与解压
来源：http://dali.yj20258888.top/Article/details/gtjsqaywzj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinyuanbaomall.cn/Article/details/gtodkjnglr.html

[R56] 远程拷贝
来源：http://dali.0kj1m.cn/Article/details/gtsnmqkwrr.html

scp file user@host:/path/
来源：http://dali.hywenlv.cn/Article/details/gtsrtuodfl.html

[R57] 远程执行命令
来源：http://dali.meibo888.top/Article/details/gtuyrmmlak.html

ssh user@host 'uptime'
来源：http://dali.sweek.top/Article/details/gtbkjajbdo.html

[R58] 下载文件
来源：http://dali.yongpay.top/Article/details/gtkhwxjvrs.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.nanxinkj.top/Article/details/gthabmysyr.html

[R59] 发 POST JSON
来源：http://dali.c1oappe.top/Article/details/gtcsmpupof.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gaohongyu789.top/Article/details/gtnssomftv.html

[R60] 只看 HTTP 状态码
来源：http://dali.bjfxy.top/Article/details/gtblleifcm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.nwbrower.top/Article/details/gtpzcqejli.html

[R61] 磁盘占用
来源：http://dali.jinghuilouyu.cn/Article/details/gteqnmpmqh.html

df -h;  du -sh *
来源：http://dali.cheryme.top/Article/details/gtzlhbdtgo.html

[R62] 找最占空间的文件
来源：http://dali.jlsjyb.cn/Article/details/gtcowfmrcv.html

du -ah . | sort -rh | head -10
来源：http://dali.jinqigufen.top/Article/details/gtyqycmrxi.html

[R63] 内存与进程
来源：http://dali.daria6918.cn/Article/details/gtyiflwbma.html

free -h;  ps aux | grep nginx
来源：http://dali.jlsjyb.cn/Article/details/gtondqbtcz.html

[R64] 结束进程
来源：http://dali.shuidangran.top/Article/details/gtctanoaou.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhongyouzk.top/Article/details/gtadeuvbsr.html

[R65] 查看端口占用
来源：http://dali.zhixingplan.top/Article/details/gtxugqlaxi.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sufxvd.cn/Article/details/gtrvgliyce.html

[R66] 定时任务
来源：http://dali.snrcjt.cn/Article/details/gtggyuhyyh.html

crontab -e;  crontab -l
来源：http://dali.zycfv.cn/Article/details/gtalaxhdmq.html

[R67] 生成随机十六进制串
来源：http://dali.jqgufenzy.top/Article/details/gtdbeecgab.html

openssl rand -hex 16
来源：http://dali.zdqjudy.top/Article/details/gtfkrxsdjt.html

[R68] 计算文件校验值
来源：http://dali.svipenyu.cn/Article/details/gtsuotokhw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jqgfzy.top/Article/details/gteurrfxlc.html

[R69] 生成随机密码
来源：http://dali.xuanzx.com/Article/details/gtpfwufnho.html

head -c 16 /dev/urandom | base64
来源：http://dali.yangfankeji.com/Article/details/gttamchqlb.html

[R70] 时间戳与互转
来源：http://dali.snrcjt.cn/Article/details/gtlvwwemnw.html

date +%s;  date -d @1700000000
来源：http://dali.xylfe.cn/Article/details/gtofykpfyn.html

[R71] 日期格式化
来源：http://dali.zhongyouzk.top/Article/details/gtsrnaiqjo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.dianchejie.cn/Article/details/gturfrlhhr.html

[R72] 等待端口就绪
来源：http://dali.dashuyun.cn/Article/details/gtefodqidh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.guannengcc.top/Article/details/gtqmjbukvt.html

[R73] 分割大日志
来源：http://dali.sysykeji.top/Article/details/gtdjnmbpgm.html

split -l 1000 big.log part_
来源：http://dali.shangyingyoupin.top/Article/details/gtgvkkxqeo.html

[R74] 批量重命名
来源：http://dali.xylfe.cn/Article/details/gtedmeszwf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinqigufen.top/Article/details/gtxhznqkho.html

[R75] 导出环境变量
来源：http://dali.jinqigfzy.top/Article/details/gtxgugqrlu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.316326.xyz/Article/details/gtargvduni.html

[R76] 使用临时文件
来源：http://dali.snrcjt.cn/Article/details/gtafmopvnx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmovqzacq.html

[R77] 读取用户输入
来源：http://dali.andypj.xyz/Article/details/gtuiiergxo.html

read -rp "请输入: " ans
来源：http://dali.hnqzz.top/Article/details/gtkellrozh.html

[R78] 交互式菜单
来源：http://dali.xziqi.cn/Article/details/gtlqpdyykm.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhixingplan.top/Article/details/gttlvixjng.html

[R79] 解析命令行选项
来源：http://dali.gotoacloud.top/Article/details/gtegwugzjm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.316326.xyz/Article/details/gtnxiuzhup.html

[R80] 查看脚本执行耗时
来源：http://dali.smart0.xyz/Article/details/gtjlfsarru.html

time ./run.sh
来源：http://dali.xziqi.cn/Article/details/gtjseqotfu.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtkayuorqq.html

S. C / C++ 专题
来源：http://dali.kuanghao11.cn/Article/details/gttyijjbny.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtdfijzhzc.html

[S01] C：Hello World
来源：http://dali.nwbrower.top/Article/details/gtjdwaxysp.html

#include <stdio.h>
来源：http://dali.ivvv.top/Article/details/gtvtlebjht.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yj20258.top/Article/details/gtsdqsecrm.html

[S02] C：变量与格式化输出
来源：http://dali.yongpay.top/Article/details/gttjlydmma.html

int a = 10; printf("%d\n", a);
来源：http://dali.cashguo.top/Article/details/gthydefagf.html

[S03] C：读入整数
来源：http://dali.jyoumei.cn/Article/details/gtuqurkjrk.html

int x; scanf("%d", &x);
来源：http://dali.chenzaomai.com/Article/details/gtzxecmawc.html

[S04] C：字符串复制
来源：http://dali.xuanzx.com/Article/details/gtsmizjuil.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.pengpengdd.cyou/Article/details/gtksutznqu.html

[S05] C：字符串长度
来源：http://dali.9152youxi.cn/Article/details/gtyaegujta.html

strlen(s)
来源：http://dali.birdmap.top/Article/details/gtliguuvtj.html

[S06] C：字符串比较
来源：http://dali.jiagoushi.top/Article/details/gtdvqzkehz.html

strcmp(a, b) == 0
来源：http://dali.cheryme.top/Article/details/gtivcemlag.html

[S07] C：数组遍历求和
来源：http://dali.birdmap.top/Article/details/gtsikzuhnu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtapxqngbe.html

[S08] C：动态内存分配与释放
来源：http://dali.fzhhl.top/Article/details/gtpffcrxxd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.tianlin.xyz/Article/details/gtxpwhavof.html

[S09] C：结构体定义与初始化
来源：http://dali.c1oappe.top/Article/details/gtvasllrug.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.316326.xyz/Article/details/gtoufgdvht.html

[S10] C：指针与解引用
来源：http://dali.nanxuanxn.top/Article/details/gtghoyocth.html

int *p = &a;  *p = 5;
来源：http://dali.smart0.xyz/Article/details/gtwiphlzpw.html

[S11] C：逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gtpxpcylpu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jinqigfzy.top/Article/details/gtlszvsuap.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shangyingyoupin.top/Article/details/gtfvegzgmk.html

fclose(f);
来源：http://dali.yuanzhike.top/Article/details/gtppstgyua.html

[S12] C：写文件
来源：http://dali.andypj.xyz/Article/details/gtqokcagpj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.dianchejie.cn/Article/details/gtppkvfnaq.html

[S13] C：宏定义
来源：http://dali.nwbrower.top/Article/details/gtlzayzpcp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ehwqpu.com/Article/details/gtknzekmev.html

[S14] C：枚举
来源：http://dali.daria6918.cn/Article/details/gtutqojtgt.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jiagoushi.top/Article/details/gtrbarregn.html

[S15] C：类型转换
来源：http://dali.redwolf501.top/Article/details/gtvsmlkufd.html

(double) a / b
来源：http://dali.vqdsnc.cn/Article/details/gtmgknfuyc.html

[S16] C：位操作置位
来源：http://dali.pengpengdd.cyou/Article/details/gtyqgilxcl.html

x |= (1 << 3);
来源：http://dali.cdnleiting.top/Article/details/gtixfqiecv.html

[S17] C：安全拼接字符串
来源：http://dali.jinqigfzy.top/Article/details/gtmlpsayyi.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhengqikj.top/Article/details/gtubgxljws.html

[S18] C：命令行参数
来源：http://dali.nanxinkj.top/Article/details/gtctleegcq.html

int main(int argc, char **argv)
来源：http://dali.guowangkeji.top/Article/details/gtgowevotx.html

[S19] C：快速排序
来源：http://dali.nwbrower.top/Article/details/gtnqvwdiye.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xuanzx.com/Article/details/gtbmwshylv.html

[S20] C：二分查找
来源：http://dali.316326.xyz/Article/details/gtfpffbbeq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hysaishi.cn/Article/details/gtqnuujefo.html

[S21] C：字符类别判断
来源：http://dali.zhixingplan.top/Article/details/gtxlflakoz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xuanzx.com/Article/details/gtfstouuzs.html

[S22] C：字符串转数字
来源：http://dali.hnqzz.top/Article/details/gtbhksdtyu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ydzc1.top/Article/details/gtputcvtje.html

[S23] C：随机数
来源：http://dali.chenlongwang.top/Article/details/gtpifidcso.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gzhubu.top/Article/details/gtueupmohj.html

[S24] C：获取本地时间
来源：http://dali.yonumen.top/Article/details/gtrsalrqrv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.chenjidiqi.icu/Article/details/gtcgbzsape.html

[S25] C：内存拷贝
来源：http://dali.zhengqikj.top/Article/details/gtvhrnmshc.html

memcpy(dst, src, n);
来源：http://dali.cdnleiting.top/Article/details/gtyentdhfu.html

[S26] C：内存清零
来源：http://dali.meibo888.top/Article/details/gttgfuxpdl.html

memset(a, 0, sizeof a);
来源：http://dali.xuetiantiany.cn/Article/details/gtnxtdbavl.html

[S27] C：定义常量
来源：http://dali.tian-w.cn/Article/details/gtzgbnvzkz.html

const double PI = 3.14159;
来源：http://dali.meibo888.top/Article/details/gtlfhljixp.html

[S28] C：静态变量
来源：http://dali.shzxlz.cn/Article/details/gtmwdqdanp.html

static int counter = 0;
来源：http://dali.havefunace.top/Article/details/gttfswqeze.html

[S29] C：变参函数
来源：http://dali.dianchejie.cn/Article/details/gtytggkgoi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.nanxuanxn.top/Article/details/gtjooyalqh.html

[S30] C：头文件保护
来源：http://dali.yuanzhike.top/Article/details/gtzkukmgte.html

#ifndef X_H
来源：http://dali.316326.xyz/Article/details/gtzrylgwjz.html

#define X_H
来源：http://dali.sysykeji.top/Article/details/gtnyzrtebg.html

#endif
来源：http://dali.nwbrower.top/Article/details/gtcwwihuyu.html

[S31] C++：Hello World
来源：http://dali.ybcxt.top/Article/details/gtojyyjmyr.html

#include <iostream>
来源：http://dali.zhiwuduotai.top/Article/details/gtdgpdhkfp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yj20258.top/Article/details/gtkstbijph.html

[S32] C++：字符串
来源：http://dali.hywenlv.cn/Article/details/gtghuacflm.html

std::string s = "hi";  s += "!";
来源：http://dali.shanyushiyangtech.top/Article/details/gtpzfijdpa.html

[S33] C++：vector 增删
来源：http://dali.guannengcc.top/Article/details/gtlwifsbpm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yj202588.top/Article/details/gthqmqdnyw.html

[S34] C++：遍历 vector
来源：http://dali.chenjidiqi.icu/Article/details/gtihapkowh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.pycfn.com/Article/details/gtiztflmfp.html

[S35] C++：map
来源：http://dali.jinqigufen.top/Article/details/gtadrzclip.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hnqzz.top/Article/details/gtkfndxrdl.html

[S36] C++：unordered_map
来源：http://dali.quarkkingdee.top/Article/details/gtmlnkzgzi.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fzhhl.top/Article/details/gtwtunmdlv.html

[S37] C++：set
来源：http://dali.zycfv.cn/Article/details/gtbnukblpl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.meibo888.top/Article/details/gtymvuhvqv.html

[S38] C++：排序
来源：http://dali.yuxming.cn/Article/details/gtrxjjipih.html

std::sort(v.begin(), v.end());
来源：http://dali.chenzaomai.com/Article/details/gtnskfbmul.html

[S39] C++：自定义比较器排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkvqzjych.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yj20258888.top/Article/details/gtkmuzstik.html

[S40] C++：查找元素
来源：http://dali.xuanzx.com/Article/details/gtxmbjhllb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jiagoushi.top/Article/details/gtrtynhoef.html

[S41] C++：类与构造函数
来源：http://dali.smart0.xyz/Article/details/gtmnqwbexz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sweek.top/Article/details/gtpmpthayg.html

[S42] C++：继承与虚函数
来源：http://dali.fzhhl.top/Article/details/gtsebhthcs.html

class B : public Base { public: void f() override {} };
来源：http://dali.aizwys.cn/Article/details/gtuuymjecs.html

[S43] C++：智能指针
来源：http://dali.hysaishi.cn/Article/details/gtexszwzum.html

auto p = std::make_unique<int>(5);
来源：http://dali.shangyingyoupin.top/Article/details/gtiayanokn.html

[S44] C++：引用传参
来源：http://dali.ehwqpu.com/Article/details/gtcbphrmkd.html

void inc(int &x) { ++x; }
来源：http://dali.gogol.net.cn/Article/details/gtzalgtlgi.html

[S45] C++：lambda
来源：http://dali.gzhubu.top/Article/details/gtlikvcjub.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhoulong.xyz/Article/details/gtwqwrnorl.html

[S46] C++：函数模板
来源：http://dali.guannengcc.top/Article/details/gttlvrdydl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtovpsaypn.html

[S47] C++：结构化绑定遍历
来源：http://dali.guowangkeji.top/Article/details/gtsieljykh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cashguo.top/Article/details/gtpsglncew.html

[S48] C++：逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gttopwvezh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gzhubu.top/Article/details/gtbxkprgdi.html

while (std::getline(in, line)) { }
来源：http://dali.bjfxy.top/Article/details/gtqofsfwmw.html

[S49] C++：写文件
来源：http://dali.sweek.top/Article/details/gtbytgazvl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.c1oappe.top/Article/details/gtehxbldvl.html

[S50] C++：格式化数字
来源：http://dali.yj202588.top/Article/details/gtnxxdnxwp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gtqrcptsdc.html

[S51] C++：显式类型转换
来源：http://dali.mhx1999.top/Article/details/gtrotkatsz.html

static_cast<double>(a) / b
来源：http://dali.tian-w.cn/Article/details/gtjodycakn.html

[S52] C++：const 与 noexcept
来源：http://dali.fzhhl.top/Article/details/gtxqjobura.html

int size() const noexcept { return n_; }
来源：http://dali.meibo888.top/Article/details/gtopdtczba.html

[S53] C++：移动语义
来源：http://dali.jinqigufen.top/Article/details/gtkoneufcc.html

std::vector<int> w = std::move(v);
来源：http://dali.yanxiufei.cn/Article/details/gttessxuui.html

[S54] C++：异常处理
来源：http://dali.sxryk.cn/Article/details/gtkawdohbc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gogol.net.cn/Article/details/gtnujwfnfn.html

[S55] C++：结构化绑定
来源：http://dali.9152youxi.cn/Article/details/gtodkwojay.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.dianchejie.cn/Article/details/gtmapooovl.html

[S56] C++：optional
来源：http://dali.cdnleiting.top/Article/details/gtqptawpjt.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtikqubmxp.html

[S57] C++：编译期常量
来源：http://dali.yuanzhike.top/Article/details/gtpvthvjnt.html

constexpr int N = 10;
来源：http://dali.yueranfly.top/Article/details/gtqiacspgm.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gtfhdomhel.html

namespace ns { int f() { return 1; } }
来源：http://dali.hammf.cn/Article/details/gtnqmwylbd.html

[S59] C++：静态断言
来源：http://dali.jinghuilouyu.cn/Article/details/gtlmhllinj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhengqikj.top/Article/details/gtcueebtpe.html

[S60] C++：遍历并删除元素
来源：http://dali.tianlin.xyz/Article/details/gtcypjvnjv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.chenzaomai.com/Article/details/gtetalxmjj.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtpubwelgr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.quarkkingdee.top/Article/details/gtryrpimwj.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtpkvoimmg.html

[T01] Kotlin：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtmngaijyi.html

println("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gtkolpahfm.html

[T02] Kotlin：变量
来源：http://dali.ehwqpu.com/Article/details/gtudbksvrq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cashguo.top/Article/details/gtqyyfavcm.html

[T03] Kotlin：字符串模板
来源：http://dali.jlsjyb.cn/Article/details/gtmifkklxp.html

"值: $b"
来源：http://dali.gogol.net.cn/Article/details/gtcaimvgdk.html

[T04] Kotlin：空安全
来源：http://dali.wangshuangyany.cn/Article/details/gtbymqeovf.html

val n: String? = null;  n?.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqjzdfbyb.html

[T05] Kotlin：when 表达式
来源：http://dali.dashuyun.cn/Article/details/gtifbwfslj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hammf.cn/Article/details/gtbxqyslrz.html

[T06] Kotlin：集合映射
来源：http://dali.gogol.net.cn/Article/details/gtbfygzrlu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hammf.cn/Article/details/gtpiyzktwu.html

[T07] Kotlin：集合过滤
来源：http://dali.daria6918.cn/Article/details/gtacolffoj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hongshengwenyu.top/Article/details/gtubnvsmag.html

[T08] Kotlin：数据类
来源：http://dali.shzxlz.cn/Article/details/gtjvnvbsmi.html

data class User(val name: String, val age: Int)
来源：http://dali.kuanghao11.cn/Article/details/gtjoxebdoe.html

[T09] Kotlin：扩展函数
来源：http://dali.yueranfly.top/Article/details/gtucgolwvo.html

fun String.exclaim() = this + "!"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkauqgsqt.html

[T10] Kotlin：默认参数
来源：http://dali.fengsongda.top/Article/details/gtnliuaypq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shanyushiyangtech.top/Article/details/gtfpjzkiyg.html

[T11] Kotlin：协程
来源：http://dali.redwolf501.top/Article/details/gtccadogfs.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gzhubu.top/Article/details/gtejfulbzu.html

[T12] Kotlin：解构声明
来源：http://dali.aizwys.cn/Article/details/gtfpjmkzzs.html

val (a, b) = Pair(1, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtgkjigzyv.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gttwdqkryf.html

val m = mapOf("a" to 1)
来源：http://dali.hywenlv.cn/Article/details/gtrkcxjinc.html

[T14] Kotlin：循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtxmfjtzzv.html

for (i in 1..10) println(i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmtatwtob.html

[T15] Kotlin：接口
来源：http://dali.shangyingyoupin.top/Article/details/gtbrnoswno.html

interface Shape { fun area(): Double }
来源：http://dali.ivvv.top/Article/details/gtcrxllcup.html

[T16] Swift：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gtiwyeucyr.html

print("Hello")
来源：http://dali.nanxinkj.top/Article/details/gtpcltcerw.html

[T17] Swift：变量与常量
来源：http://dali.hywenlv.cn/Article/details/gtpuydhmkm.html

var a = 1;  let b = 2
来源：http://dali.andypj.xyz/Article/details/gtpjgqhvis.html

[T18] Swift：字符串插值
来源：http://dali.sweek.top/Article/details/gtnqyomtlv.html

"值: \(b)"
来源：http://dali.nanxinkj.top/Article/details/gtidusmztq.html

[T19] Swift：可选绑定
来源：http://dali.316326.xyz/Article/details/gtzjedttwu.html

if let n = opt { print(n) }
来源：http://dali.jinqigfzy.top/Article/details/gtvoqxssly.html

[T20] Swift：数组操作
来源：http://dali.yj20258888.top/Article/details/gtxuijqujn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yueranfly.top/Article/details/gtmwaaktfo.html

[T21] Swift：遍历
来源：http://dali.havefunace.top/Article/details/gtyakyxczb.html

for x in a { print(x) }
来源：http://dali.0kj1m.cn/Article/details/gthuquktsx.html

[T22] Swift：字典
来源：http://dali.cqqwz.cn/Article/details/gtgvmrwubq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.9152youxi.cn/Article/details/gtljzsocib.html

[T23] Swift：函数
来源：http://dali.xziqi.cn/Article/details/gtcjzvpobt.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtymznfkbr.html

[T24] Swift：闭包
来源：http://dali.svipenyu.cn/Article/details/gtcshhgyvr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.cashguo.top/Article/details/gtdkgnkgrh.html

[T25] Swift：结构体
来源：http://dali.chenzaomai.com/Article/details/gttlsifuve.html

struct P { var x: Int }
来源：http://dali.chenlongwang.top/Article/details/gtdlhzbzet.html

[T26] Swift：类与重写
来源：http://dali.yj20258888.top/Article/details/gthkecgcia.html

class A: Base { override func f() {} }
来源：http://dali.cheryme.top/Article/details/gtbefgrhuu.html

[T27] Swift：错误处理
来源：http://dali.tianlin.xyz/Article/details/gtuikqttqq.html

do { try f() } catch { print(error) }
来源：http://dali.fzhhl.top/Article/details/gtaybcispl.html

[T28] Swift：枚举
来源：http://dali.zdqjudy.top/Article/details/gthguujqaf.html

enum Color { case red, green }
来源：http://dali.yj20258.top/Article/details/gtzdcsotwu.html

[T29] Swift：guard 提前返回
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlcojcust.html

guard let x = opt else { return }
来源：http://dali.9152youxi.cn/Article/details/gtcbyibagr.html

[T30] Swift：协议
来源：http://dali.andypj.xyz/Article/details/gtryjtykzg.html

protocol Shape { func area() -> Double }
来源：http://dali.shanyushiyangtech.top/Article/details/gtimslzmpt.html

[T31] Lua：Hello World
来源：http://dali.nanxinkj.top/Article/details/gtquqiifbj.html

print("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gtszhzddmd.html

[T32] Lua：局部变量
来源：http://dali.snrcjt.cn/Article/details/gthzzlrcri.html

local a = 1
来源：http://dali.nwbrower.top/Article/details/gtkuzwochl.html

[T33] Lua：表（数组）
来源：http://dali.quarkkingdee.top/Article/details/gtikezjriu.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yj20258888.top/Article/details/gtmifwnlsj.html

[T34] Lua：遍历表
来源：http://dali.ydzc1.top/Article/details/gtopjjzkqf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.wangshuangyany.cn/Article/details/gtdfwhmawu.html

[T35] Lua：字典表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzzgwcvhq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.nwbrower.top/Article/details/gtxxphkayp.html

[T36] Lua：函数
来源：http://dali.snrcjt.cn/Article/details/gtuevudgws.html

function add(a, b) return a + b end
来源：http://dali.havefunace.top/Article/details/gtstewyjlr.html

[T37] Lua：字符串拼接
来源：http://dali.ivvv.top/Article/details/gtamtcmprf.html

"a" .. "b"
来源：http://dali.nwbrower.top/Article/details/gtxkxvlesb.html

[T38] Lua：条件
来源：http://dali.shzxlz.cn/Article/details/gtxhfoiast.html

if x > 0 then print("正") end
来源：http://dali.jiagoushi.top/Article/details/gtggfgrrjz.html

[T39] Lua：模式匹配
来源：http://dali.nanxinkj.top/Article/details/gtjdtbqpfh.html

string.find(s, "%d+")
来源：http://dali.dianchejie.cn/Article/details/gtnvqgzdot.html

[T40] Lua：元表
来源：http://dali.hywenlv.cn/Article/details/gtmldbduvs.html

setmetatable({}, { __index = base })
来源：http://dali.9152youxi.cn/Article/details/gtxazbyvhx.html

[T41] Perl：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gthbhdblbx.html

print "Hello\n";
来源：http://dali.316326.xyz/Article/details/gthrtvdkhe.html

[T42] Perl：变量类型
来源：http://dali.zycfv.cn/Article/details/gthybcisfm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.gogol.net.cn/Article/details/gtthzrkjzr.html

[T43] Perl：字符串插值
来源：http://dali.xuetiantiany.cn/Article/details/gtasjcwsua.html

"值: $a"
来源：http://dali.meibo888.top/Article/details/gtrgotjjle.html

[T44] Perl：条件
来源：http://dali.xziqi.cn/Article/details/gtxpjireep.html

if ($a > 0) { print "正"; }
来源：http://dali.xylfe.cn/Article/details/gtfwjvmhjz.html

[T45] Perl：数组遍历
来源：http://dali.c1oappe.top/Article/details/gtbbesycmw.html

for my $x (@arr) { print $x; }
来源：http://dali.jqgufenzy.top/Article/details/gttejrgntw.html

[T46] Perl：哈希操作
来源：http://dali.gaohongyu789.top/Article/details/gtsfoadtrj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yj202588.top/Article/details/gtvqdwualj.html

[T47] Perl：正则捕获
来源：http://dali.xziqi.cn/Article/details/gtqftsmmhm.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.aizwys.cn/Article/details/gtxlhvbyuq.html

[T48] Perl：正则替换
来源：http://dali.yueranfly.top/Article/details/gtmbgdbaus.html

$s =~ s/old/new/g;
来源：http://dali.birdmap.top/Article/details/gtczrkxkpe.html

[T49] Perl：函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtlntlffnn.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yj20258.top/Article/details/gtbqqacxyy.html

[T50] Perl：逐行读文件
来源：http://dali.fengsongda.top/Article/details/gtrxkkwzbd.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.chenjidiqi.icu/Article/details/gtksbgptib.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jlsjyb.cn/Article/details/gtptuvhhjr.html

[T51] Scala：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtrhesmafe.html

println("Hello")
来源：http://dali.guowangkeji.top/Article/details/gtcnbbemio.html

[T52] Scala：变量
来源：http://dali.sufxvd.cn/Article/details/gtzebvjhlx.html

val a = 1;  var b = 2
来源：http://dali.ppjwa.cn/Article/details/gtyjutugqo.html

[T53] Scala：字符串插值
来源：http://dali.zhongyouzk.top/Article/details/gtytqvheqo.html

s"值: $b"
来源：http://dali.9152youxi.cn/Article/details/gtsomdgaob.html

[T54] Scala：集合映射
来源：http://dali.daria6918.cn/Article/details/gtdzhvrwxo.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jinqigfzy.top/Article/details/gtseuxapkl.html

[T55] Scala：集合过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gtkrgoesdp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.nwbrower.top/Article/details/gthvcsffvg.html

[T56] Scala：样例类
来源：http://dali.andypj.xyz/Article/details/gtpzslybia.html


<!-- 参考信息 -->