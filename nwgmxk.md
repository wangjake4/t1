代发 wailian999

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jqgfzy.top/Article/details/gtqqlrdebq.html

[R56] 远程拷贝
来源：http://dali.ppjwa.cn/Article/details/gthlwroduz.html

scp file user@host:/path/
来源：http://dali.ybcxt.top/Article/details/gtihwiuscl.html

[R57] 远程执行命令
来源：http://dali.jiagoushi.top/Article/details/gtdwmnsdkb.html

ssh user@host 'uptime'
来源：http://dali.chenzaomai.com/Article/details/gtmuicoilb.html

[R58] 下载文件
来源：http://dali.wangdashe.top/Article/details/gtzvwnbrtc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.daria6918.cn/Article/details/gtrcmqfwwp.html

[R59] 发 POST JSON
来源：http://dali.sxryk.cn/Article/details/gtdbqgpzbd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.chenlongwang.top/Article/details/gtnbvnlmhk.html

[R60] 只看 HTTP 状态码
来源：http://dali.meibo888.top/Article/details/gtgjwanrol.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yongpay.top/Article/details/gtahzenfnz.html

[R61] 磁盘占用
来源：http://dali.yuxming.cn/Article/details/gtnbcuqsjo.html

df -h;  du -sh *
来源：http://dali.havefunace.top/Article/details/gtfwhehlfm.html

[R62] 找最占空间的文件
来源：http://dali.jqgfzy.top/Article/details/gtsziolims.html

du -ah . | sort -rh | head -10
来源：http://dali.zhoulong.xyz/Article/details/gtmobtwubi.html

[R63] 内存与进程
来源：http://dali.kuanghao11.cn/Article/details/gtxbztmzom.html

free -h;  ps aux | grep nginx
来源：http://dali.shzxlz.cn/Article/details/gtjnyqanxg.html

[R64] 结束进程
来源：http://dali.tanke756.top/Article/details/gtamxlcedd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.0kj1m.cn/Article/details/gtwfirqrqh.html

[R65] 查看端口占用
来源：http://dali.cheryme.top/Article/details/gtiomdtfsf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.fzhhl.top/Article/details/gtllrdycec.html

[R66] 定时任务
来源：http://dali.shangyingyoupin.top/Article/details/gtzegjjemy.html

crontab -e;  crontab -l
来源：http://dali.mhx1999.top/Article/details/gtvldcbjib.html

[R67] 生成随机十六进制串
来源：http://dali.dashuyun.cn/Article/details/gtmikysqit.html

openssl rand -hex 16
来源：http://dali.sweek.top/Article/details/gtvcjduhrr.html

[R68] 计算文件校验值
来源：http://dali.birdmap.top/Article/details/gtzfxbhfzk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.birdmap.top/Article/details/gtpnetkaro.html

[R69] 生成随机密码
来源：http://dali.tian-w.cn/Article/details/gtzexwcruk.html

head -c 16 /dev/urandom | base64
来源：http://dali.jqgfzy.top/Article/details/gtwtfygdkn.html

[R70] 时间戳与互转
来源：http://dali.zhongyouzk.top/Article/details/gtdtsfczmj.html

date +%s;  date -d @1700000000
来源：http://dali.yongpay.top/Article/details/gthpcqbcay.html

[R71] 日期格式化
来源：http://dali.ivvv.top/Article/details/gtydulausu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jiagoushi.top/Article/details/gtsefgvmsw.html

[R72] 等待端口就绪
来源：http://dali.nwbrower.top/Article/details/gttwomuubg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shangyingyoupin.top/Article/details/gtbpejlmcf.html

[R73] 分割大日志
来源：http://dali.jinghuilouyu.cn/Article/details/gtbsxkpdcf.html

split -l 1000 big.log part_
来源：http://dali.yuxming.cn/Article/details/gtrujixpss.html

[R74] 批量重命名
来源：http://dali.yongpay.top/Article/details/gtxvdyjgnn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtvcobjlyh.html

[R75] 导出环境变量
来源：http://dali.nanxinkj.top/Article/details/gtjluqzsbf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.mhx1999.top/Article/details/gtcukqzhzj.html

[R76] 使用临时文件
来源：http://dali.zhongyouzk.top/Article/details/gtysqhobmj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhoulong.xyz/Article/details/gtxsvfrhuy.html

[R77] 读取用户输入
来源：http://dali.ybcxt.top/Article/details/gttztazppz.html

read -rp "请输入: " ans
来源：http://dali.jyoumei.cn/Article/details/gtuziutwrr.html

[R78] 交互式菜单
来源：http://dali.wangshuangyany.cn/Article/details/gtpyxzbacd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinqigfzy.top/Article/details/gtrwxggpbw.html

[R79] 解析命令行选项
来源：http://dali.iojbl.cn/Article/details/gthnqdsbkq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.nwbrower.top/Article/details/gttrieyomz.html

[R80] 查看脚本执行耗时
来源：http://dali.chenjidiqi.icu/Article/details/gttwlqtcxj.html

time ./run.sh
来源：http://dali.hnqzz.top/Article/details/gtmnppxtmd.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtxnuqsmsk.html

S. C / C++ 专题
来源：http://dali.yanxiufei.cn/Article/details/gtziejsems.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtzxmgemtq.html

[S01] C：Hello World
来源：http://dali.nanxinkj.top/Article/details/gtlvpejhac.html

#include <stdio.h>
来源：http://dali.aibaodan.cn/Article/details/gtkkenqftx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yj20258888.top/Article/details/gtmyrzkrag.html

[S02] C：变量与格式化输出
来源：http://dali.meibo888.top/Article/details/gtnxwrztqv.html

int a = 10; printf("%d\n", a);
来源：http://dali.pycfn.com/Article/details/gtatxeimdw.html

[S03] C：读入整数
来源：http://dali.yvedp.cn/Article/details/gthrrhuwuk.html

int x; scanf("%d", &x);
来源：http://dali.gogol.net.cn/Article/details/gtjzrjjwiu.html

[S04] C：字符串复制
来源：http://dali.gogol.net.cn/Article/details/gtjlfflspx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmmyyiqda.html

[S05] C：字符串长度
来源：http://dali.yuxming.cn/Article/details/gtuoryqtdw.html

strlen(s)
来源：http://dali.xziqi.cn/Article/details/gtovkfiqku.html

[S06] C：字符串比较
来源：http://dali.aizwys.cn/Article/details/gtrsvrxodu.html

strcmp(a, b) == 0
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuppahuth.html

[S07] C：数组遍历求和
来源：http://dali.jinghuilouyu.cn/Article/details/gtsngoitut.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtimwzkzza.html

[S08] C：动态内存分配与释放
来源：http://dali.tianlin.xyz/Article/details/gtavmxvysx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ppjwa.cn/Article/details/gtpkygwtxx.html

[S09] C：结构体定义与初始化
来源：http://dali.guowangkeji.top/Article/details/gtrqhfxxja.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.vqdsnc.cn/Article/details/gttxhwrxnj.html

[S10] C：指针与解引用
来源：http://dali.cheryme.top/Article/details/gtczbccmps.html

int *p = &a;  *p = 5;
来源：http://dali.yangfankeji.com/Article/details/gtguhergya.html

[S11] C：逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gtlktialcq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xuetiantiany.cn/Article/details/gtwwobsrir.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jyoumei.cn/Article/details/gtiaggpqkk.html

fclose(f);
来源：http://dali.pycfn.com/Article/details/gtchkjqmbe.html

[S12] C：写文件
来源：http://dali.snrcjt.cn/Article/details/gtdxxhurqh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.mhx1999.top/Article/details/gtrmrqyiss.html

[S13] C：宏定义
来源：http://dali.zhixingplan.top/Article/details/gtltqoscrl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yj20258888.top/Article/details/gtspmqqizr.html

[S14] C：枚举
来源：http://dali.andypj.xyz/Article/details/gtxeihbbxv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.meibo888.top/Article/details/gtloivemzy.html

[S15] C：类型转换
来源：http://dali.xuetiantiany.cn/Article/details/gtctlkaqzc.html

(double) a / b
来源：http://dali.shzxlz.cn/Article/details/gtvwuqgemo.html

[S16] C：位操作置位
来源：http://dali.c1oappe.top/Article/details/gtlxfwvouz.html

x |= (1 << 3);
来源：http://dali.9152youxi.cn/Article/details/gtzkavvngp.html

[S17] C：安全拼接字符串
来源：http://dali.guowangkeji.top/Article/details/gtgdykyhim.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.aibaodan.cn/Article/details/gttedojpfn.html

[S18] C：命令行参数
来源：http://dali.kuanghao11.cn/Article/details/gtlgdthehr.html

int main(int argc, char **argv)
来源：http://dali.kuanghao11.cn/Article/details/gtnnqvjnyp.html

[S19] C：快速排序
来源：http://dali.tianlin.xyz/Article/details/gthrgasreh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.gzhubu.top/Article/details/gtydsksoka.html

[S20] C：二分查找
来源：http://dali.cdnleiting.top/Article/details/gtyojnjfqq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinghuilouyu.cn/Article/details/gtfciviepz.html

[S21] C：字符类别判断
来源：http://dali.wangdashe.top/Article/details/gtyfqsjdlz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.haohaochexian.top/Article/details/gtznvbownt.html

[S22] C：字符串转数字
来源：http://dali.yj20258888.top/Article/details/gthrwyrbaq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.dashuyun.cn/Article/details/gtdbeolpwq.html

[S23] C：随机数
来源：http://dali.zhixingplan.top/Article/details/gtgygtxrgt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zycfv.cn/Article/details/gtyptusudv.html

[S24] C：获取本地时间
来源：http://dali.yj20258.top/Article/details/gtdennfane.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xuetiantiany.cn/Article/details/gtcyyqyeri.html

[S25] C：内存拷贝
来源：http://dali.meibo888.top/Article/details/gtxtrwzmjr.html

memcpy(dst, src, n);
来源：http://dali.chenlongwang.top/Article/details/gtptrtgodq.html

[S26] C：内存清零
来源：http://dali.jinqigfzy.top/Article/details/gtzuvkmial.html

memset(a, 0, sizeof a);
来源：http://dali.shzxlz.cn/Article/details/gthlelbrlh.html

[S27] C：定义常量
来源：http://dali.chenzaomai.com/Article/details/gtlgepxkbt.html

const double PI = 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiembnrej.html

[S28] C：静态变量
来源：http://dali.kuanghao11.cn/Article/details/gtsugblgzb.html

static int counter = 0;
来源：http://dali.jinqigufen.top/Article/details/gtscttlcpk.html

[S29] C：变参函数
来源：http://dali.shuidangran.top/Article/details/gtdbskfply.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hysaishi.cn/Article/details/gtsqtcnozb.html

[S30] C：头文件保护
来源：http://dali.pycfn.com/Article/details/gtyqwfjtzk.html

#ifndef X_H
来源：http://dali.guannengcc.top/Article/details/gtwjhqvlat.html

#define X_H
来源：http://dali.bjfxy.top/Article/details/gtjzzihujm.html

#endif
来源：http://dali.yonumen.top/Article/details/gtxxfxfzss.html

[S31] C++：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gterxavhbw.html

#include <iostream>
来源：http://dali.xuanzx.com/Article/details/gtnujjwsrg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.mhx1999.top/Article/details/gtiqerxrlp.html

[S32] C++：字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvjbbsike.html

std::string s = "hi";  s += "!";
来源：http://dali.yangfankeji.com/Article/details/gtsrrzzwry.html

[S33] C++：vector 增删
来源：http://dali.zdqjudy.top/Article/details/gtrzllzcwz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yonumen.top/Article/details/gtfmitnzaa.html

[S34] C++：遍历 vector
来源：http://dali.hnqzz.top/Article/details/gtbrjedkxa.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yuanzhike.top/Article/details/gtpmuuksda.html

[S35] C++：map
来源：http://dali.guowangkeji.top/Article/details/gtqfnockvi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hysaishi.cn/Article/details/gtzzkfecma.html

[S36] C++：unordered_map
来源：http://dali.zdqjudy.top/Article/details/gtczembcfq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtapchyiyb.html

[S37] C++：set
来源：http://dali.chenlongwang.top/Article/details/gtphiqswrg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfwrpkjht.html

[S38] C++：排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gtocvmccfu.html

std::sort(v.begin(), v.end());
来源：http://dali.jyoumei.cn/Article/details/gtmeybyevw.html

[S39] C++：自定义比较器排序
来源：http://dali.jiagoushi.top/Article/details/gtfhqigbbr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hammf.cn/Article/details/gtelsizmii.html

[S40] C++：查找元素
来源：http://dali.dashuyun.cn/Article/details/gtwboyqabr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yvedp.cn/Article/details/gtqlroczpt.html

[S41] C++：类与构造函数
来源：http://dali.chenzaomai.com/Article/details/gtjsynpwkq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.andypj.xyz/Article/details/gtzwgrkhfn.html

[S42] C++：继承与虚函数
来源：http://dali.wangshuangyany.cn/Article/details/gturhpilwp.html

class B : public Base { public: void f() override {} };
来源：http://dali.ehwqpu.com/Article/details/gtgmnvnztr.html

[S43] C++：智能指针
来源：http://dali.yonumen.top/Article/details/gtfepvlipt.html

auto p = std::make_unique<int>(5);
来源：http://dali.xuetiantiany.cn/Article/details/gthouhouyo.html

[S44] C++：引用传参
来源：http://dali.yvedp.cn/Article/details/gtbqadiszp.html

void inc(int &x) { ++x; }
来源：http://dali.daria6918.cn/Article/details/gttyqmzwzp.html

[S45] C++：lambda
来源：http://dali.bjfxy.top/Article/details/gtkphhvyll.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hammf.cn/Article/details/gtxqyovino.html

[S46] C++：函数模板
来源：http://dali.jqgfzy.top/Article/details/gtchywwvvk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yanxiufei.cn/Article/details/gtbnvxxwwe.html

[S47] C++：结构化绑定遍历
来源：http://dali.yuanzhike.top/Article/details/gtgmzxjjpr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shangyingyoupin.top/Article/details/gtgnpqvwjh.html

[S48] C++：逐行读文件
来源：http://dali.hnxiangtu.top/Article/details/gtzpiuazkd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jqgfzy.top/Article/details/gthyvfvbjn.html

while (std::getline(in, line)) { }
来源：http://dali.meibo888.top/Article/details/gtsgbqkbil.html

[S49] C++：写文件
来源：http://dali.jinqigufen.top/Article/details/gtzysvjqza.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.havefunace.top/Article/details/gtmcpbegqz.html

[S50] C++：格式化数字
来源：http://dali.jinqigfzy.top/Article/details/gtwaaphtzt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yvedp.cn/Article/details/gtuavukxjv.html

[S51] C++：显式类型转换
来源：http://dali.chenzaomai.com/Article/details/gtjrlwmrqz.html

static_cast<double>(a) / b
来源：http://dali.sxryk.cn/Article/details/gtzjilhomy.html

[S52] C++：const 与 noexcept
来源：http://dali.hnqzz.top/Article/details/gtfeagwavd.html

int size() const noexcept { return n_; }
来源：http://dali.yj202588.top/Article/details/gtdpqtvyln.html

[S53] C++：移动语义
来源：http://dali.wangdashe.top/Article/details/gtzryhkqpn.html

std::vector<int> w = std::move(v);
来源：http://dali.guowangkeji.top/Article/details/gtgyimtgbu.html

[S54] C++：异常处理
来源：http://dali.havefunace.top/Article/details/gtriapkwzp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.tanke756.top/Article/details/gthkqgjlqv.html

[S55] C++：结构化绑定
来源：http://dali.shzxlz.cn/Article/details/gtwwrpccwx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.fengsongda.top/Article/details/gtjrymixhv.html

[S56] C++：optional
来源：http://dali.hysaishi.cn/Article/details/gtxjwgpfya.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.wangshuangyany.cn/Article/details/gtptdfguqo.html

[S57] C++：编译期常量
来源：http://dali.xuanzx.com/Article/details/gtxwdfuanv.html

constexpr int N = 10;
来源：http://dali.cashguo.top/Article/details/gtpbdspplq.html

[S58] C++：命名空间
来源：http://dali.zycfv.cn/Article/details/gthkcarfag.html

namespace ns { int f() { return 1; } }
来源：http://dali.jiagoushi.top/Article/details/gtbjxename.html

[S59] C++：静态断言
来源：http://dali.yangfankeji.com/Article/details/gtlbvgxjtw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hywenlv.cn/Article/details/gtxszdezqa.html

[S60] C++：遍历并删除元素
来源：http://dali.shzxlz.cn/Article/details/gtqngveuvk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyejylcwx.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtzagxauxs.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jqgufenzy.top/Article/details/gtzxjcyhye.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtmzvajvya.html

[T01] Kotlin：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtgdqhvgcj.html

println("Hello")
来源：http://dali.kuanghao11.cn/Article/details/gtewprbgzh.html

[T02] Kotlin：变量
来源：http://dali.wangdashe.top/Article/details/gthblntwaf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhongyouzk.top/Article/details/gtkbhjngah.html

[T03] Kotlin：字符串模板
来源：http://dali.tanke756.top/Article/details/gtoignqmjh.html

"值: $b"
来源：http://dali.yj20258.top/Article/details/gtudssbbga.html

[T04] Kotlin：空安全
来源：http://dali.sxryk.cn/Article/details/gtfkumwjfn.html

val n: String? = null;  n?.length
来源：http://dali.jqgufenzy.top/Article/details/gtgritjkwx.html

[T05] Kotlin：when 表达式
来源：http://dali.316326.xyz/Article/details/gtzydeuicd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhoulong.xyz/Article/details/gthoumejls.html

[T06] Kotlin：集合映射
来源：http://dali.mhx1999.top/Article/details/gtpsxswgdy.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjoscqeee.html

[T07] Kotlin：集合过滤
来源：http://dali.cqqwz.cn/Article/details/gttzxwxgom.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xylfe.cn/Article/details/gtzxpoudxj.html

[T08] Kotlin：数据类
来源：http://dali.birdmap.top/Article/details/gtxkjnwswt.html

data class User(val name: String, val age: Int)
来源：http://dali.pycfn.com/Article/details/gtlducwdvy.html

[T09] Kotlin：扩展函数
来源：http://dali.zhengqikj.top/Article/details/gtdpwwkici.html

fun String.exclaim() = this + "!"
来源：http://dali.jinqigfzy.top/Article/details/gtgtcpnvmv.html

[T10] Kotlin：默认参数
来源：http://dali.xinyue.icu/Article/details/gtathjaygz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.sufxvd.cn/Article/details/gtoywgkpkc.html

[T11] Kotlin：协程
来源：http://dali.cheryme.top/Article/details/gthpifgvdc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.kuanghao11.cn/Article/details/gtpnravhtp.html

[T12] Kotlin：解构声明
来源：http://dali.quarkkingdee.top/Article/details/gtfmfwfiei.html

val (a, b) = Pair(1, 2)
来源：http://dali.birdmap.top/Article/details/gtiqvywudm.html

[T13] Kotlin：只读 Map
来源：http://dali.pengpengdd.cyou/Article/details/gthbaflxmp.html

val m = mapOf("a" to 1)
来源：http://dali.cashguo.top/Article/details/gtlapxqqfe.html

[T14] Kotlin：循环
来源：http://dali.nanxuanxn.top/Article/details/gtepycdtrk.html

for (i in 1..10) println(i)
来源：http://dali.chenjidiqi.icu/Article/details/gtfpvrvqjp.html

[T15] Kotlin：接口
来源：http://dali.daxiang520.top/Article/details/gtwskakjyu.html

interface Shape { fun area(): Double }
来源：http://dali.cheryme.top/Article/details/gtpupfqnyf.html

[T16] Swift：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtsaqaypid.html

print("Hello")
来源：http://dali.ivvv.top/Article/details/gtednwtory.html

[T17] Swift：变量与常量
来源：http://dali.zhixingplan.top/Article/details/gtrbsgpsml.html

var a = 1;  let b = 2
来源：http://dali.zhiwuduotai.top/Article/details/gtwvamwaaq.html

[T18] Swift：字符串插值
来源：http://dali.shzxlz.cn/Article/details/gtuzbrurau.html

"值: \(b)"
来源：http://dali.yvedp.cn/Article/details/gtiwpywhum.html

[T19] Swift：可选绑定
来源：http://dali.gotoacloud.top/Article/details/gtkppggjlk.html

if let n = opt { print(n) }
来源：http://dali.feifeiyinyue.top/Article/details/gtvkdxecgu.html

[T20] Swift：数组操作
来源：http://dali.yuxming.cn/Article/details/gtlwvqekmw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jlsjyb.cn/Article/details/gtzdpmqxvc.html

[T21] Swift：遍历
来源：http://dali.cdnleiting.top/Article/details/gthpupzuow.html

for x in a { print(x) }
来源：http://dali.iojbl.cn/Article/details/gtosvwkvsa.html

[T22] Swift：字典
来源：http://dali.dianchejie.cn/Article/details/gtxntqakbo.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.9152youxi.cn/Article/details/gtupjrixmg.html

[T23] Swift：函数
来源：http://dali.hnqzz.top/Article/details/gtrtypojyu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.316326.xyz/Article/details/gtkbsbsuxr.html

[T24] Swift：闭包
来源：http://dali.nanxinkj.top/Article/details/gtdokaubkv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.gotoacloud.top/Article/details/gtohrcpuhh.html

[T25] Swift：结构体
来源：http://dali.xziqi.cn/Article/details/gtpxtuhfih.html

struct P { var x: Int }
来源：http://dali.zhiwuduotai.top/Article/details/gtbogtbwbp.html

[T26] Swift：类与重写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtufmxjbho.html

class A: Base { override func f() {} }
来源：http://dali.wangdashe.top/Article/details/gtqfjkzhjn.html

[T27] Swift：错误处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtulthelrk.html

do { try f() } catch { print(error) }
来源：http://dali.jinqigfzy.top/Article/details/gtdouvlese.html

[T28] Swift：枚举
来源：http://dali.aizwys.cn/Article/details/gtpoobfkzr.html

enum Color { case red, green }
来源：http://dali.yueranfly.top/Article/details/gtmvuihufu.html

[T29] Swift：guard 提前返回
来源：http://dali.redwolf501.top/Article/details/gteukrrgrt.html

guard let x = opt else { return }
来源：http://dali.cqqwz.cn/Article/details/gtfghmqcpr.html

[T30] Swift：协议
来源：http://dali.iojbl.cn/Article/details/gtvvocxwzk.html

protocol Shape { func area() -> Double }
来源：http://dali.0kj1m.cn/Article/details/gtivkcjtuj.html

[T31] Lua：Hello World
来源：http://dali.cheryme.top/Article/details/gtxcfbizwj.html

print("Hello")
来源：http://dali.svipenyu.cn/Article/details/gtrmomxctk.html

[T32] Lua：局部变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsnjqgoya.html

local a = 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gthzxiomgi.html

[T33] Lua：表（数组）
来源：http://dali.hysaishi.cn/Article/details/gtgyplfnom.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.sufxvd.cn/Article/details/gtblcqcasm.html

[T34] Lua：遍历表
来源：http://dali.yueranfly.top/Article/details/gtnmpnoauf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.cheryme.top/Article/details/gtkcbluudr.html

[T35] Lua：字典表
来源：http://dali.havefunace.top/Article/details/gtfmatnzeo.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gtfxainiva.html

[T36] Lua：函数
来源：http://dali.iojbl.cn/Article/details/gtpwtjckcm.html

function add(a, b) return a + b end
来源：http://dali.sufxvd.cn/Article/details/gtxtyqviad.html

[T37] Lua：字符串拼接
来源：http://dali.shzxlz.cn/Article/details/gttatxidio.html

"a" .. "b"
来源：http://dali.yueranfly.top/Article/details/gtpmnebnco.html

[T38] Lua：条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdypqtbzh.html

if x > 0 then print("正") end
来源：http://dali.guannengcc.top/Article/details/gtafbwkluy.html

[T39] Lua：模式匹配
来源：http://dali.ybcxt.top/Article/details/gtglfrjauq.html

string.find(s, "%d+")
来源：http://dali.hysaishi.cn/Article/details/gtxpoykppy.html

[T40] Lua：元表
来源：http://dali.jqgufenzy.top/Article/details/gtkalzuejh.html

setmetatable({}, { __index = base })
来源：http://dali.jqgufenzy.top/Article/details/gtyfqfchsq.html

[T41] Perl：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtlpvyxwgh.html

print "Hello\n";
来源：http://dali.vqdsnc.cn/Article/details/gtpqquejvn.html

[T42] Perl：变量类型
来源：http://dali.jinqigufen.top/Article/details/gtwsndqxha.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.feifeiyinyue.top/Article/details/gtullgstak.html

[T43] Perl：字符串插值
来源：http://dali.daxiang520.top/Article/details/gtqnjafcuy.html

"值: $a"
来源：http://dali.jlsjyb.cn/Article/details/gtgeuwernr.html

[T44] Perl：条件
来源：http://dali.guannengcc.top/Article/details/gtyxmjngcs.html

if ($a > 0) { print "正"; }
来源：http://dali.ydzc1.top/Article/details/gtruerywmr.html

[T45] Perl：数组遍历
来源：http://dali.hywenlv.cn/Article/details/gtgssgnspw.html

for my $x (@arr) { print $x; }
来源：http://dali.0kj1m.cn/Article/details/gtjetijqyp.html

[T46] Perl：哈希操作
来源：http://dali.svipenyu.cn/Article/details/gtqvkfjasp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtuqqbtnco.html

[T47] Perl：正则捕获
来源：http://dali.jinqigufen.top/Article/details/gtmitqblbr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhoulong.xyz/Article/details/gthelzntnk.html

[T48] Perl：正则替换
来源：http://dali.zhoulong.xyz/Article/details/gtwhuhelmw.html

$s =~ s/old/new/g;
来源：http://dali.yvedp.cn/Article/details/gtvjgmreon.html

[T49] Perl：函数
来源：http://dali.chenzaomai.com/Article/details/gttontgrbq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.tianlin.xyz/Article/details/gtcuynccct.html

[T50] Perl：逐行读文件
来源：http://dali.shangyingyoupin.top/Article/details/gtowhmetbl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.pengpengdd.cyou/Article/details/gtwmlpviur.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtndbxkdth.html

[T51] Scala：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gtroydqlwb.html

println("Hello")
来源：http://dali.meibo888.top/Article/details/gtpfrngpwt.html

[T52] Scala：变量
来源：http://dali.zdqjudy.top/Article/details/gtlzasfhlf.html

val a = 1;  var b = 2
来源：http://dali.ehwqpu.com/Article/details/gtzhuebsoo.html

[T53] Scala：字符串插值
来源：http://dali.pycfn.com/Article/details/gtzkxxwkgx.html

s"值: $b"
来源：http://dali.havefunace.top/Article/details/gtmjemrcgc.html

[T54] Scala：集合映射
来源：http://dali.dianchejie.cn/Article/details/gturkwhynv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.gotoacloud.top/Article/details/gtsratsbly.html

[T55] Scala：集合过滤
来源：http://dali.sufxvd.cn/Article/details/gtqxoihuro.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yangfankeji.com/Article/details/gtylslxrci.html

[T56] Scala：样例类
来源：http://dali.yvedp.cn/Article/details/gtngbsbidx.html

case class User(name: String, age: Int)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtejktgjmo.html

[T57] Scala：模式匹配
来源：http://dali.smart0.xyz/Article/details/gtkgzuobmb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xylfe.cn/Article/details/gtbgwsgeyd.html

[T58] Scala：函数定义
来源：http://dali.zhoulong.xyz/Article/details/gtuzzxbtcz.html


<!-- 参考信息 -->