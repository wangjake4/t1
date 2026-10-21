代发 wailian999

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.9152youxi.cn/Article/details/gtzyphpxkp.html

[R56] 远程拷贝
来源：http://dali.316326.xyz/Article/details/gtdxahjnup.html

scp file user@host:/path/
来源：http://dali.zhongyouzk.top/Article/details/gtbfuexbce.html

[R57] 远程执行命令
来源：http://dali.ivvv.top/Article/details/gtdjoloyro.html

ssh user@host 'uptime'
来源：http://dali.daria6918.cn/Article/details/gtoibxzixz.html

[R58] 下载文件
来源：http://dali.xuanzx.com/Article/details/gtklddmvuc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hongshengwenyu.top/Article/details/gtprkvbtpn.html

[R59] 发 POST JSON
来源：http://dali.tian-w.cn/Article/details/gtyxsyxdjp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.tanke756.top/Article/details/gtgfujqcry.html

[R60] 只看 HTTP 状态码
来源：http://dali.pengpengdd.cyou/Article/details/gtqstogeqv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ivvv.top/Article/details/gtbhcggijj.html

[R61] 磁盘占用
来源：http://dali.jyoumei.cn/Article/details/gttkagqihe.html

df -h;  du -sh *
来源：http://dali.yanxiufei.cn/Article/details/gtyhkdawta.html

[R62] 找最占空间的文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqjewmwip.html

du -ah . | sort -rh | head -10
来源：http://dali.jinqigufen.top/Article/details/gtnqzaeuld.html

[R63] 内存与进程
来源：http://dali.fengsongda.top/Article/details/gtqkhcliiv.html

free -h;  ps aux | grep nginx
来源：http://dali.pycfn.com/Article/details/gthxfuzqwj.html

[R64] 结束进程
来源：http://dali.vqdsnc.cn/Article/details/gtjygtapqf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhiwuduotai.top/Article/details/gtvyawigjy.html

[R65] 查看端口占用
来源：http://dali.xylfe.cn/Article/details/gtadjkaeez.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.dashuyun.cn/Article/details/gtxvfklgax.html

[R66] 定时任务
来源：http://dali.xylfe.cn/Article/details/gtznbdymft.html

crontab -e;  crontab -l
来源：http://dali.shangyingyoupin.top/Article/details/gtxqznsyhb.html

[R67] 生成随机十六进制串
来源：http://dali.zhoulong.xyz/Article/details/gtgtsddqnz.html

openssl rand -hex 16
来源：http://dali.nanxinkj.top/Article/details/gtnqwimbsh.html

[R68] 计算文件校验值
来源：http://dali.nanxuanxn.top/Article/details/gtolfguzij.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yueranfly.top/Article/details/gtqsinrhnr.html

[R69] 生成随机密码
来源：http://dali.jiagoushi.top/Article/details/gttpvyojwq.html

head -c 16 /dev/urandom | base64
来源：http://dali.hywenlv.cn/Article/details/gtvcwwjmwx.html

[R70] 时间戳与互转
来源：http://dali.quarkkingdee.top/Article/details/gtrirpopzf.html

date +%s;  date -d @1700000000
来源：http://dali.meibo888.top/Article/details/gtezljvccd.html

[R71] 日期格式化
来源：http://dali.shuidangran.top/Article/details/gtdabcwmrh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinghuilouyu.cn/Article/details/gtwmegvltg.html

[R72] 等待端口就绪
来源：http://dali.nanxinkj.top/Article/details/gtkxqcpiee.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.redwolf501.top/Article/details/gtwfmrinxz.html

[R73] 分割大日志
来源：http://dali.tianlin.xyz/Article/details/gtzbzppkwa.html

split -l 1000 big.log part_
来源：http://dali.zhoulong.xyz/Article/details/gtrseggcpp.html

[R74] 批量重命名
来源：http://dali.jyoumei.cn/Article/details/gtvzuwlqvw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.feifeiyinyue.top/Article/details/gtovnxbhhw.html

[R75] 导出环境变量
来源：http://dali.redwolf501.top/Article/details/gtxpeikkyr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.quarkkingdee.top/Article/details/gtdbfpetku.html

[R76] 使用临时文件
来源：http://dali.0kj1m.cn/Article/details/gtrfqyxcxc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuanzhike.top/Article/details/gtdaadyefv.html

[R77] 读取用户输入
来源：http://dali.zhengqikj.top/Article/details/gtwhsfnmau.html

read -rp "请输入: " ans
来源：http://dali.jiagoushi.top/Article/details/gtvbkvfluk.html

[R78] 交互式菜单
来源：http://dali.zycfv.cn/Article/details/gtzwppphgd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhixingplan.top/Article/details/gtmjcromgq.html

[R79] 解析命令行选项
来源：http://dali.zhixingplan.top/Article/details/gtxneqgcvj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.chenjidiqi.icu/Article/details/gtghhhhdvd.html

[R80] 查看脚本执行耗时
来源：http://dali.wangshuangyany.cn/Article/details/gtketpbjyh.html

time ./run.sh
来源：http://dali.gotoacloud.top/Article/details/gtptvhprlx.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtmdgruuwb.html

S. C / C++ 专题
来源：http://dali.dashuyun.cn/Article/details/gtkwvdofbo.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtbblenusp.html

[S01] C：Hello World
来源：http://dali.jianghu66.top/Article/details/gtrqvrjfko.html

#include <stdio.h>
来源：http://dali.daria6918.cn/Article/details/gtsaveeekt.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jinqigufen.top/Article/details/gtnkmzpmme.html

[S02] C：变量与格式化输出
来源：http://dali.fzhhl.top/Article/details/gtzuwyfjnd.html

int a = 10; printf("%d\n", a);
来源：http://dali.jlsjyb.cn/Article/details/gtzwxrwzhc.html

[S03] C：读入整数
来源：http://dali.cdnleiting.top/Article/details/gtjpztltnb.html

int x; scanf("%d", &x);
来源：http://dali.quarkkingdee.top/Article/details/gtfmmijxhf.html

[S04] C：字符串复制
来源：http://dali.hysaishi.cn/Article/details/gtkhzdgrqv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ppjwa.cn/Article/details/gtbqiphrpx.html

[S05] C：字符串长度
来源：http://dali.9152youxi.cn/Article/details/gtgwpbwwdj.html

strlen(s)
来源：http://dali.yvedp.cn/Article/details/gttbhyrmcy.html

[S06] C：字符串比较
来源：http://dali.jlsjyb.cn/Article/details/gtdjuzdwqv.html

strcmp(a, b) == 0
来源：http://dali.andypj.xyz/Article/details/gtdpshjghh.html

[S07] C：数组遍历求和
来源：http://dali.guannengcc.top/Article/details/gtdvlrbntb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zdqjudy.top/Article/details/gtncmaqrnn.html

[S08] C：动态内存分配与释放
来源：http://dali.sxryk.cn/Article/details/gtrindtlte.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hammf.cn/Article/details/gtinoeobkt.html

[S09] C：结构体定义与初始化
来源：http://dali.zhoulong.xyz/Article/details/gtixsvcjax.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gogol.net.cn/Article/details/gtdpsvzgjt.html

[S10] C：指针与解引用
来源：http://dali.shangyingyoupin.top/Article/details/gtufhusjgj.html

int *p = &a;  *p = 5;
来源：http://dali.daria6918.cn/Article/details/gtdueggfrg.html

[S11] C：逐行读文件
来源：http://dali.cucudq.cn/Article/details/gtdgqgpbnq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.c1oappe.top/Article/details/gttxaiqrtr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.haohaochexian.top/Article/details/gtcfomfxud.html

fclose(f);
来源：http://dali.guannengcc.top/Article/details/gtcocxzxyw.html

[S12] C：写文件
来源：http://dali.sweek.top/Article/details/gttmvkzera.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.redwolf501.top/Article/details/gtjbgvgwjx.html

[S13] C：宏定义
来源：http://dali.wangshuangyany.cn/Article/details/gtjqqsusxw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hysaishi.cn/Article/details/gtemzjtgwt.html

[S14] C：枚举
来源：http://dali.ehwqpu.com/Article/details/gtcgrvyoez.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ybcxt.top/Article/details/gtpuiihsqd.html

[S15] C：类型转换
来源：http://dali.nanxuanxn.top/Article/details/gtpspfchnq.html

(double) a / b
来源：http://dali.nanxinkj.top/Article/details/gtqtotjtmt.html

[S16] C：位操作置位
来源：http://dali.tian-w.cn/Article/details/gtzgynyknp.html

x |= (1 << 3);
来源：http://dali.dianchejie.cn/Article/details/gtsohxtnrx.html

[S17] C：安全拼接字符串
来源：http://dali.jiagoushi.top/Article/details/gtiudclyre.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yuanzhike.top/Article/details/gttcaazuuc.html

[S18] C：命令行参数
来源：http://dali.nwbrower.top/Article/details/gtpefigvqe.html

int main(int argc, char **argv)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsgjhougp.html

[S19] C：快速排序
来源：http://dali.pengpengdd.cyou/Article/details/gtplppqmfk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yj20258888.top/Article/details/gtnpmqkxum.html

[S20] C：二分查找
来源：http://dali.wangdashe.top/Article/details/gtmodcrzgx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.9152youxi.cn/Article/details/gtdcwfuixn.html

[S21] C：字符类别判断
来源：http://dali.dianchejie.cn/Article/details/gtuutfxpxm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hfpthk.cn/Article/details/gtmqtsnarr.html

[S22] C：字符串转数字
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjmtgupfe.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zycfv.cn/Article/details/gthedvxdhb.html

[S23] C：随机数
来源：http://dali.shangyingyoupin.top/Article/details/gtpbceuhes.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.snrcjt.cn/Article/details/gtmduigeps.html

[S24] C：获取本地时间
来源：http://dali.yuanzhike.top/Article/details/gtryuwrvbp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xuetiantiany.cn/Article/details/gtspsnpkio.html

[S25] C：内存拷贝
来源：http://dali.hammf.cn/Article/details/gtjljamojr.html

memcpy(dst, src, n);
来源：http://dali.bjfxy.top/Article/details/gthpwcjhdq.html

[S26] C：内存清零
来源：http://dali.gogol.net.cn/Article/details/gtiutbttrl.html

memset(a, 0, sizeof a);
来源：http://dali.zdqjudy.top/Article/details/gtcmmllqvq.html

[S27] C：定义常量
来源：http://dali.chenlongwang.top/Article/details/gthcfeeapd.html

const double PI = 3.14159;
来源：http://dali.sufxvd.cn/Article/details/gtakwhglhu.html

[S28] C：静态变量
来源：http://dali.svipenyu.cn/Article/details/gtzcuamkmh.html

static int counter = 0;
来源：http://dali.xuanzx.com/Article/details/gteuhrwexs.html

[S29] C：变参函数
来源：http://dali.zhongyouzk.top/Article/details/gtpcjvrhqx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.tanke756.top/Article/details/gtzhdwhqpj.html

[S30] C：头文件保护
来源：http://dali.xuanzx.com/Article/details/gttsyiybgq.html

#ifndef X_H
来源：http://dali.kuanghao11.cn/Article/details/gtgbxkxvxy.html

#define X_H
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzarqsojq.html

#endif
来源：http://dali.jinghuilouyu.cn/Article/details/gtwicykled.html

[S31] C++：Hello World
来源：http://dali.yonumen.top/Article/details/gtkfhyliai.html

#include <iostream>
来源：http://dali.guannengcc.top/Article/details/gtdlsrlofu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cheryme.top/Article/details/gtikngcxjb.html

[S32] C++：字符串
来源：http://dali.tanke756.top/Article/details/gtzszlzatv.html

std::string s = "hi";  s += "!";
来源：http://dali.kuanghao11.cn/Article/details/gtbudevdzn.html

[S33] C++：vector 增删
来源：http://dali.yueranfly.top/Article/details/gtgcrzcgfw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hnxiangtu.top/Article/details/gtvnwhaubf.html

[S34] C++：遍历 vector
来源：http://dali.xuetiantiany.cn/Article/details/gtzpriphzm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.chenjidiqi.icu/Article/details/gtswsldfwm.html

[S35] C++：map
来源：http://dali.snrcjt.cn/Article/details/gtgifowkdk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtxdpwrczc.html

[S36] C++：unordered_map
来源：http://dali.chenlongwang.top/Article/details/gtswbddale.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nwbrower.top/Article/details/gtcmjtofvq.html

[S37] C++：set
来源：http://dali.cheryme.top/Article/details/gtwidhbnnh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.meibo888.top/Article/details/gtbhkhtoxu.html

[S38] C++：排序
来源：http://dali.zhoulong.xyz/Article/details/gtazchmagp.html

std::sort(v.begin(), v.end());
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgffoidle.html

[S39] C++：自定义比较器排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gtthknsgca.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.birdmap.top/Article/details/gtsaiqhidb.html

[S40] C++：查找元素
来源：http://dali.nwbrower.top/Article/details/gttkmzgtyt.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtdhojcicu.html

[S41] C++：类与构造函数
来源：http://dali.shangyingyoupin.top/Article/details/gtgblsipww.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.daria6918.cn/Article/details/gtqbecigoz.html

[S42] C++：继承与虚函数
来源：http://dali.aizwys.cn/Article/details/gtxcrqhkyq.html

class B : public Base { public: void f() override {} };
来源：http://dali.ydzc1.top/Article/details/gtnxykezcc.html

[S43] C++：智能指针
来源：http://dali.jqgfzy.top/Article/details/gtrpyppded.html

auto p = std::make_unique<int>(5);
来源：http://dali.hysaishi.cn/Article/details/gtclgalpgj.html

[S44] C++：引用传参
来源：http://dali.meibo888.top/Article/details/gtssosvdkn.html

void inc(int &x) { ++x; }
来源：http://dali.yuxming.cn/Article/details/gtklajnhkp.html

[S45] C++：lambda
来源：http://dali.shuidangran.top/Article/details/gtkhhctpap.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shanyushiyangtech.top/Article/details/gtucoejkjv.html

[S46] C++：函数模板
来源：http://dali.yj202588.top/Article/details/gtazdhheot.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtebrlqytf.html

[S47] C++：结构化绑定遍历
来源：http://dali.mhx1999.top/Article/details/gtovddahkq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.fengsongda.top/Article/details/gtffayfwsc.html

[S48] C++：逐行读文件
来源：http://dali.daxiang520.top/Article/details/gtwblgixyx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.iojbl.cn/Article/details/gtforyawzm.html

while (std::getline(in, line)) { }
来源：http://dali.cqqwz.cn/Article/details/gtgqgqdttk.html

[S49] C++：写文件
来源：http://dali.yuxming.cn/Article/details/gthskspgdx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.birdmap.top/Article/details/gtbdhgimld.html

[S50] C++：格式化数字
来源：http://dali.iojbl.cn/Article/details/gtdikyihqx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gtjxxefgnu.html

[S51] C++：显式类型转换
来源：http://dali.yonumen.top/Article/details/gtlajfgrby.html

static_cast<double>(a) / b
来源：http://dali.gogol.net.cn/Article/details/gtdvzokegi.html

[S52] C++：const 与 noexcept
来源：http://dali.jiagoushi.top/Article/details/gtwgfpkanc.html

int size() const noexcept { return n_; }
来源：http://dali.gzhubu.top/Article/details/gtknfxmchr.html

[S53] C++：移动语义
来源：http://dali.iojbl.cn/Article/details/gthhwjclor.html

std::vector<int> w = std::move(v);
来源：http://dali.bjfxy.top/Article/details/gtkjjjojmq.html

[S54] C++：异常处理
来源：http://dali.hysaishi.cn/Article/details/gtzngtjrrz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.c1oappe.top/Article/details/gtaerbrvmk.html

[S55] C++：结构化绑定
来源：http://dali.guowangkeji.top/Article/details/gtotairgto.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.daxiang520.top/Article/details/gtdaquuzwf.html

[S56] C++：optional
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbabyvkve.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj202588.top/Article/details/gtouygmiyi.html

[S57] C++：编译期常量
来源：http://dali.hongshengwenyu.top/Article/details/gtxeidnuat.html

constexpr int N = 10;
来源：http://dali.nwbrower.top/Article/details/gtglyuyyty.html

[S58] C++：命名空间
来源：http://dali.jianghu66.top/Article/details/gtkeqmvcup.html

namespace ns { int f() { return 1; } }
来源：http://dali.9152youxi.cn/Article/details/gtwnvhweuw.html

[S59] C++：静态断言
来源：http://dali.birdmap.top/Article/details/gtlddojmql.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.vqdsnc.cn/Article/details/gtcjyxjjkw.html

[S60] C++：遍历并删除元素
来源：http://dali.sysykeji.top/Article/details/gtbieooznz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ehwqpu.com/Article/details/gtrxpgpotr.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtfvcatsqz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.redwolf501.top/Article/details/gtvhmwjtpy.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqoccmotc.html

[T01] Kotlin：Hello World
来源：http://dali.gzhubu.top/Article/details/gtkpqxdbxy.html

println("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gtmwjeuisl.html

[T02] Kotlin：变量
来源：http://dali.jlsjyb.cn/Article/details/gtoqyzhzjh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.dianchejie.cn/Article/details/gtvuiavbyy.html

[T03] Kotlin：字符串模板
来源：http://dali.tianlin.xyz/Article/details/gtambtgytr.html

"值: $b"
来源：http://dali.ppjwa.cn/Article/details/gtuzveexxl.html

[T04] Kotlin：空安全
来源：http://dali.sufxvd.cn/Article/details/gtjdderdap.html

val n: String? = null;  n?.length
来源：http://dali.hysaishi.cn/Article/details/gtvclslmsm.html

[T05] Kotlin：when 表达式
来源：http://dali.hongshengwenyu.top/Article/details/gtyftivsux.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.gotoacloud.top/Article/details/gtjftfrxpu.html

[T06] Kotlin：集合映射
来源：http://dali.hywenlv.cn/Article/details/gtucjiiqpc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gotoacloud.top/Article/details/gtnfmlinlv.html

[T07] Kotlin：集合过滤
来源：http://dali.bjfxy.top/Article/details/gtdjxoqpzm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gotoacloud.top/Article/details/gtrfstlstf.html

[T08] Kotlin：数据类
来源：http://dali.ppjwa.cn/Article/details/gtljkqthez.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gtklcaqkzz.html

[T09] Kotlin：扩展函数
来源：http://dali.guannengcc.top/Article/details/gtsxjiawjk.html

fun String.exclaim() = this + "!"
来源：http://dali.cqqwz.cn/Article/details/gtzrlwkuja.html

[T10] Kotlin：默认参数
来源：http://dali.snrcjt.cn/Article/details/gtathzazrt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj20258.top/Article/details/gtjcnmslzh.html

[T11] Kotlin：协程
来源：http://dali.316326.xyz/Article/details/gtuvouazpg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.havefunace.top/Article/details/gtggpkqzge.html

[T12] Kotlin：解构声明
来源：http://dali.feifeiyinyue.top/Article/details/gtprckzpfy.html

val (a, b) = Pair(1, 2)
来源：http://dali.smart0.xyz/Article/details/gtlwfolhrg.html

[T13] Kotlin：只读 Map
来源：http://dali.bjfxy.top/Article/details/gttlgwpsmp.html

val m = mapOf("a" to 1)
来源：http://dali.pycfn.com/Article/details/gtbszikqxb.html

[T14] Kotlin：循环
来源：http://dali.gogol.net.cn/Article/details/gteybyxkbn.html

for (i in 1..10) println(i)
来源：http://dali.xinyue.icu/Article/details/gtrlwpmggk.html

[T15] Kotlin：接口
来源：http://dali.ydzc1.top/Article/details/gtzldeezus.html

interface Shape { fun area(): Double }
来源：http://dali.fengsongda.top/Article/details/gtkckcpilq.html

[T16] Swift：Hello World
来源：http://dali.zycfv.cn/Article/details/gtkwdfemhc.html

print("Hello")
来源：http://dali.aibaodan.cn/Article/details/gtwmsvukao.html

[T17] Swift：变量与常量
来源：http://dali.yangfankeji.com/Article/details/gtalhxeoyw.html

var a = 1;  let b = 2
来源：http://dali.hammf.cn/Article/details/gtnkwyuhab.html

[T18] Swift：字符串插值
来源：http://dali.quarkkingdee.top/Article/details/gtrfptizgb.html

"值: \(b)"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmvkqhfya.html

[T19] Swift：可选绑定
来源：http://dali.gzhubu.top/Article/details/gttlyvtiju.html

if let n = opt { print(n) }
来源：http://dali.dashuyun.cn/Article/details/gtffnbgxrh.html

[T20] Swift：数组操作
来源：http://dali.ivvv.top/Article/details/gtpzbmsgoy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhengqikj.top/Article/details/gttlyzhucz.html

[T21] Swift：遍历
来源：http://dali.yuanzhike.top/Article/details/gtynlyempp.html

for x in a { print(x) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvgwafudm.html

[T22] Swift：字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqehrhdaz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.havefunace.top/Article/details/gtlsafpvsx.html

[T23] Swift：函数
来源：http://dali.jinqigufen.top/Article/details/gtrqwjdjkp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.chenjidiqi.icu/Article/details/gtkhjupzua.html

[T24] Swift：闭包
来源：http://dali.yanxiufei.cn/Article/details/gtoeraibaa.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jqgufenzy.top/Article/details/gtzlcxubbb.html

[T25] Swift：结构体
来源：http://dali.vqdsnc.cn/Article/details/gtvcsqysip.html

struct P { var x: Int }
来源：http://dali.haohaochexian.top/Article/details/gtuvbsdphv.html

[T26] Swift：类与重写
来源：http://dali.chenlongwang.top/Article/details/gtmfjfjfnp.html

class A: Base { override func f() {} }
来源：http://dali.dianchejie.cn/Article/details/gtjerkrrig.html

[T27] Swift：错误处理
来源：http://dali.sxryk.cn/Article/details/gttmfbwnng.html

do { try f() } catch { print(error) }
来源：http://dali.dianchejie.cn/Article/details/gtnqxxomxr.html

[T28] Swift：枚举
来源：http://dali.c1oappe.top/Article/details/gtrazqybnx.html

enum Color { case red, green }
来源：http://dali.jlsjyb.cn/Article/details/gtxrqqgwgt.html

[T29] Swift：guard 提前返回
来源：http://dali.yanxiufei.cn/Article/details/gtfrjewuxh.html

guard let x = opt else { return }
来源：http://dali.jinqigfzy.top/Article/details/gtcpvlpxyd.html

[T30] Swift：协议
来源：http://dali.yvedp.cn/Article/details/gtoubwdjhh.html

protocol Shape { func area() -> Double }
来源：http://dali.feifeiyinyue.top/Article/details/gtjdqaqxts.html

[T31] Lua：Hello World
来源：http://dali.hysaishi.cn/Article/details/gtyhxwleeo.html

print("Hello")
来源：http://dali.guowangkeji.top/Article/details/gtxypzgctp.html

[T32] Lua：局部变量
来源：http://dali.nanxuanxn.top/Article/details/gtirxdsite.html

local a = 1
来源：http://dali.jianghu66.top/Article/details/gttyoasixj.html

[T33] Lua：表（数组）
来源：http://dali.zhixingplan.top/Article/details/gtcoegrbyh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.nwbrower.top/Article/details/gttfqrcuqp.html

[T34] Lua：遍历表
来源：http://dali.xuetiantiany.cn/Article/details/gtrrtkoxnt.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.chenzaomai.com/Article/details/gtsodbhzyd.html

[T35] Lua：字典表
来源：http://dali.jqgufenzy.top/Article/details/gtybltvvgw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gtnjnchonh.html

[T36] Lua：函数
来源：http://dali.yongpay.top/Article/details/gtjkfxeenx.html

function add(a, b) return a + b end
来源：http://dali.pycfn.com/Article/details/gtvitdrxng.html

[T37] Lua：字符串拼接
来源：http://dali.gaohongyu789.top/Article/details/gtwqihjfnx.html

"a" .. "b"
来源：http://dali.nanxuanxn.top/Article/details/gtkrhnsfmh.html

[T38] Lua：条件
来源：http://dali.gzhubu.top/Article/details/gthzwlnrpm.html

if x > 0 then print("正") end
来源：http://dali.sweek.top/Article/details/gtvpsdfimp.html

[T39] Lua：模式匹配
来源：http://dali.chenjidiqi.icu/Article/details/gtkjdumams.html

string.find(s, "%d+")
来源：http://dali.gaohongyu789.top/Article/details/gtuucocfsh.html

[T40] Lua：元表
来源：http://dali.cashguo.top/Article/details/gtraymeypi.html

setmetatable({}, { __index = base })
来源：http://dali.jlsjyb.cn/Article/details/gthmsnfwgy.html

[T41] Perl：Hello World
来源：http://dali.hysaishi.cn/Article/details/gtrseskkis.html

print "Hello\n";
来源：http://dali.jianghu66.top/Article/details/gtzvjypubu.html

[T42] Perl：变量类型
来源：http://dali.cucudq.cn/Article/details/gtwbbszfaq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hfpthk.cn/Article/details/gtmuwlaruq.html

[T43] Perl：字符串插值
来源：http://dali.xinyue.icu/Article/details/gtcxpnzeyk.html

"值: $a"
来源：http://dali.hysaishi.cn/Article/details/gtpdsoltdo.html

[T44] Perl：条件
来源：http://dali.fengsongda.top/Article/details/gtmxnvtoei.html

if ($a > 0) { print "正"; }
来源：http://dali.hysaishi.cn/Article/details/gttgrtljql.html

[T45] Perl：数组遍历
来源：http://dali.wangdashe.top/Article/details/gtqjuenhvp.html

for my $x (@arr) { print $x; }
来源：http://dali.tian-w.cn/Article/details/gttgbersgp.html

[T46] Perl：哈希操作
来源：http://dali.zhoulong.xyz/Article/details/gtlbdgmcjt.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.shzxlz.cn/Article/details/gtrxqngsaw.html

[T47] Perl：正则捕获
来源：http://dali.shzxlz.cn/Article/details/gtxuqciewr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yonumen.top/Article/details/gteowkdgqy.html

[T48] Perl：正则替换
来源：http://dali.zycfv.cn/Article/details/gtciqemeyd.html

$s =~ s/old/new/g;
来源：http://dali.guowangkeji.top/Article/details/gtkvtqyqma.html

[T49] Perl：函数
来源：http://dali.jlsjyb.cn/Article/details/gtmbtojrpa.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtfnkfgpfl.html

[T50] Perl：逐行读文件
来源：http://dali.cashguo.top/Article/details/gtloecalkr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hysaishi.cn/Article/details/gtgpedlajj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zycfv.cn/Article/details/gtezeatmhd.html

[T51] Scala：Hello World
来源：http://dali.ydzc1.top/Article/details/gtsgunmpmw.html

println("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gtlkqpxrkm.html

[T52] Scala：变量
来源：http://dali.chenjidiqi.icu/Article/details/gtpxwfqtuz.html

val a = 1;  var b = 2
来源：http://dali.sufxvd.cn/Article/details/gtclugvkrc.html

[T53] Scala：字符串插值
来源：http://dali.zycfv.cn/Article/details/gtmpiksokw.html

s"值: $b"
来源：http://dali.gotoacloud.top/Article/details/gtjesyefpy.html

[T54] Scala：集合映射
来源：http://dali.ybcxt.top/Article/details/gtaibijlfc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.xylfe.cn/Article/details/gtaufnbivl.html

[T55] Scala：集合过滤
来源：http://dali.wangshuangyany.cn/Article/details/gtxjbzwubk.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.iojbl.cn/Article/details/gtkgnlartx.html

[T56] Scala：样例类
来源：http://dali.redwolf501.top/Article/details/gtgyhibzlp.html

case class User(name: String, age: Int)
来源：http://dali.sysykeji.top/Article/details/gthrsavkqr.html

[T57] Scala：模式匹配
来源：http://dali.sxryk.cn/Article/details/gtdbsogess.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.wangshuangyany.cn/Article/details/gtmpmttage.html

[T58] Scala：函数定义
来源：http://dali.birdmap.top/Article/details/gtoseuausd.html


<!-- 参考信息 -->