代发 wailian999

ssh user@host 'uptime'
来源：http://dali.haohaochexian.top/Article/details/gtvgfhgtbl.html

[R58] 下载文件
来源：http://dali.gogol.net.cn/Article/details/gtyutizqwp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvpquusew.html

[R59] 发 POST JSON
来源：http://dali.xuanzx.com/Article/details/gtrsncdjkb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.bjfxy.top/Article/details/gtnksnxfjl.html

[R60] 只看 HTTP 状态码
来源：http://dali.0kj1m.cn/Article/details/gtgusikrpz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yj20258.top/Article/details/gttpozqven.html

[R61] 磁盘占用
来源：http://dali.nanxinkj.top/Article/details/gtkdpgllhz.html

df -h;  du -sh *
来源：http://dali.yuxming.cn/Article/details/gtedvwqzbk.html

[R62] 找最占空间的文件
来源：http://dali.tanke756.top/Article/details/gtynolttpd.html

du -ah . | sort -rh | head -10
来源：http://dali.daxiang520.top/Article/details/gtzbbbncbc.html

[R63] 内存与进程
来源：http://dali.316326.xyz/Article/details/gtqlfmwdah.html

free -h;  ps aux | grep nginx
来源：http://dali.cqqwz.cn/Article/details/gtembnjntq.html

[R64] 结束进程
来源：http://dali.wangshuangyany.cn/Article/details/gtownmrovq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnmwngkuc.html

[R65] 查看端口占用
来源：http://dali.dashuyun.cn/Article/details/gtykkunrhu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.aizwys.cn/Article/details/gthsplfela.html

[R66] 定时任务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtznyfabtz.html

crontab -e;  crontab -l
来源：http://dali.c1oappe.top/Article/details/gtamjrdtix.html

[R67] 生成随机十六进制串
来源：http://dali.hywenlv.cn/Article/details/gtddzdnmqp.html

openssl rand -hex 16
来源：http://dali.jyoumei.cn/Article/details/gtmosolqqx.html

[R68] 计算文件校验值
来源：http://dali.yuxming.cn/Article/details/gtrpnfggjx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gotoacloud.top/Article/details/gtbuatatua.html

[R69] 生成随机密码
来源：http://dali.zhiwuduotai.top/Article/details/gtaequfjdh.html

head -c 16 /dev/urandom | base64
来源：http://dali.hfpthk.cn/Article/details/gtydetspqm.html

[R70] 时间戳与互转
来源：http://dali.vqdsnc.cn/Article/details/gtqqomjhim.html

date +%s;  date -d @1700000000
来源：http://dali.cheryme.top/Article/details/gtilvypbgm.html

[R71] 日期格式化
来源：http://dali.pycfn.com/Article/details/gtgfcreaak.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.svipenyu.cn/Article/details/gtxkyyjojx.html

[R72] 等待端口就绪
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrvszbabv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hammf.cn/Article/details/gtmtlplkbi.html

[R73] 分割大日志
来源：http://dali.yongpay.top/Article/details/gtkjhbdixz.html

split -l 1000 big.log part_
来源：http://dali.dashuyun.cn/Article/details/gtskzhaomh.html

[R74] 批量重命名
来源：http://dali.cashguo.top/Article/details/gtmflkdgti.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jianghu66.top/Article/details/gtpnlyspfc.html

[R75] 导出环境变量
来源：http://dali.ppjwa.cn/Article/details/gtuawahgmf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.guannengcc.top/Article/details/gtyjckcfij.html

[R76] 使用临时文件
来源：http://dali.mhx1999.top/Article/details/gtooyxyyag.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.tianlin.xyz/Article/details/gtrelkmrea.html

[R77] 读取用户输入
来源：http://dali.zhixingplan.top/Article/details/gtyblqnemp.html

read -rp "请输入: " ans
来源：http://dali.snrcjt.cn/Article/details/gtxduckras.html

[R78] 交互式菜单
来源：http://dali.shanyushiyangtech.top/Article/details/gtazcrpsba.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.dashuyun.cn/Article/details/gtysqyaenx.html

[R79] 解析命令行选项
来源：http://dali.shangyingyoupin.top/Article/details/gtwwvzvsxa.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.kuanghao11.cn/Article/details/gtukdxrsta.html

[R80] 查看脚本执行耗时
来源：http://dali.yueranfly.top/Article/details/gtlxpqvzcz.html

time ./run.sh
来源：http://dali.mhx1999.top/Article/details/gtocfkhhyx.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gttakfcrdm.html

S. C / C++ 专题
来源：http://dali.yonumen.top/Article/details/gtnrvzwjqz.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtwkbwcifl.html

[S01] C：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtpzorrbbi.html

#include <stdio.h>
来源：http://dali.dianchejie.cn/Article/details/gtnxgbitqs.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gotoacloud.top/Article/details/gtykefvlqg.html

[S02] C：变量与格式化输出
来源：http://dali.sxryk.cn/Article/details/gtjoidqioa.html

int a = 10; printf("%d\n", a);
来源：http://dali.shangyingyoupin.top/Article/details/gtogstzebh.html

[S03] C：读入整数
来源：http://dali.ydzc1.top/Article/details/gtfuobceny.html

int x; scanf("%d", &x);
来源：http://dali.zycfv.cn/Article/details/gtoowtnfhu.html

[S04] C：字符串复制
来源：http://dali.xziqi.cn/Article/details/gtpskjadjz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yonumen.top/Article/details/gtzufnqmcw.html

[S05] C：字符串长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfawsapmk.html

strlen(s)
来源：http://dali.jiagoushi.top/Article/details/gtilhcdrsz.html

[S06] C：字符串比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvwbwoqfv.html

strcmp(a, b) == 0
来源：http://dali.xuanzx.com/Article/details/gtfawvhwrl.html

[S07] C：数组遍历求和
来源：http://dali.fengsongda.top/Article/details/gtqudtqbsx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.bjfxy.top/Article/details/gtvktaaxto.html

[S08] C：动态内存分配与释放
来源：http://dali.feifeiyinyue.top/Article/details/gtqzobtzxs.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.aibaodan.cn/Article/details/gtjebjfgop.html

[S09] C：结构体定义与初始化
来源：http://dali.zycfv.cn/Article/details/gtztpxhpyq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.9152youxi.cn/Article/details/gtolggupad.html

[S10] C：指针与解引用
来源：http://dali.daxiang520.top/Article/details/gtfepypdlm.html

int *p = &a;  *p = 5;
来源：http://dali.sxryk.cn/Article/details/gtqtrxlhtb.html

[S11] C：逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gtuuulrhox.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.smart0.xyz/Article/details/gtwtqvtavl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhiwuduotai.top/Article/details/gtwyjjzvlh.html

fclose(f);
来源：http://dali.zhengqikj.top/Article/details/gtqlvesheu.html

[S12] C：写文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaecqbiep.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.316326.xyz/Article/details/gtgfnxfyab.html

[S13] C：宏定义
来源：http://dali.dashuyun.cn/Article/details/gtqocyugys.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinghuilouyu.cn/Article/details/gtlgfyprbg.html

[S14] C：枚举
来源：http://dali.zhoulong.xyz/Article/details/gtonjnhesy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.9152youxi.cn/Article/details/gtbeexnmde.html

[S15] C：类型转换
来源：http://dali.zhongyouzk.top/Article/details/gtfejthazo.html

(double) a / b
来源：http://dali.jinghuilouyu.cn/Article/details/gtdqwobgbj.html

[S16] C：位操作置位
来源：http://dali.yangfankeji.com/Article/details/gtgvfgfggy.html

x |= (1 << 3);
来源：http://dali.zhixingplan.top/Article/details/gtlwpgmboz.html

[S17] C：安全拼接字符串
来源：http://dali.ehwqpu.com/Article/details/gtthqelyxe.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.gaohongyu789.top/Article/details/gtpllfmslr.html

[S18] C：命令行参数
来源：http://dali.ppjwa.cn/Article/details/gttrazdfoh.html

int main(int argc, char **argv)
来源：http://dali.hnxiangtu.top/Article/details/gtjlkzcsfm.html

[S19] C：快速排序
来源：http://dali.zdqjudy.top/Article/details/gtmzxapdke.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yvedp.cn/Article/details/gtyeiexnta.html

[S20] C：二分查找
来源：http://dali.aibaodan.cn/Article/details/gtxatfcwlh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhoulong.xyz/Article/details/gtmsonqpul.html

[S21] C：字符类别判断
来源：http://dali.pengpengdd.cyou/Article/details/gtpqqxugch.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.meibo888.top/Article/details/gthviyvztq.html

[S22] C：字符串转数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkmyahssm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jiagoushi.top/Article/details/gtriiuvpnb.html

[S23] C：随机数
来源：http://dali.hongshengwenyu.top/Article/details/gtfzekvidy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoaexjise.html

[S24] C：获取本地时间
来源：http://dali.aizwys.cn/Article/details/gtxxkktmgu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.dashuyun.cn/Article/details/gtygediflq.html

[S25] C：内存拷贝
来源：http://dali.wangshuangyany.cn/Article/details/gtixamehvz.html

memcpy(dst, src, n);
来源：http://dali.shzxlz.cn/Article/details/gtfoptvogh.html

[S26] C：内存清零
来源：http://dali.nanxuanxn.top/Article/details/gtryxecbxr.html

memset(a, 0, sizeof a);
来源：http://dali.sufxvd.cn/Article/details/gtanvymyhm.html

[S27] C：定义常量
来源：http://dali.xuanzx.com/Article/details/gtuhqrgwgo.html

const double PI = 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gtoolvunpg.html

[S28] C：静态变量
来源：http://dali.tian-w.cn/Article/details/gtfuktlmns.html

static int counter = 0;
来源：http://dali.zhengqikj.top/Article/details/gtldeqbjjn.html

[S29] C：变参函数
来源：http://dali.xuetiantiany.cn/Article/details/gtrlvqtpem.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhixingplan.top/Article/details/gthkrjypzn.html

[S30] C：头文件保护
来源：http://dali.tanke756.top/Article/details/gtwnmucieh.html

#ifndef X_H
来源：http://dali.pycfn.com/Article/details/gtiseayiay.html

#define X_H
来源：http://dali.andypj.xyz/Article/details/gttjlmmzry.html

#endif
来源：http://dali.hysaishi.cn/Article/details/gtqdweahvj.html

[S31] C++：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtpxlyknbz.html

#include <iostream>
来源：http://dali.zhengqikj.top/Article/details/gtohlyinym.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhongyouzk.top/Article/details/gtvxaoouna.html

[S32] C++：字符串
来源：http://dali.dashuyun.cn/Article/details/gthkfbudso.html

std::string s = "hi";  s += "!";
来源：http://dali.xinyue.icu/Article/details/gtmiyqypcp.html

[S33] C++：vector 增删
来源：http://dali.sweek.top/Article/details/gttmevghay.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shuidangran.top/Article/details/gtxqfrxycw.html

[S34] C++：遍历 vector
来源：http://dali.ydzc1.top/Article/details/gtslsqagfr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yueranfly.top/Article/details/gthkxzhbtr.html

[S35] C++：map
来源：http://dali.sysykeji.top/Article/details/gtumuupcim.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gtqctzjtlm.html

[S36] C++：unordered_map
来源：http://dali.nanxuanxn.top/Article/details/gtasuvrmfk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtazslreen.html

[S37] C++：set
来源：http://dali.daxiang520.top/Article/details/gtraqkzzbz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sweek.top/Article/details/gtmldnfqna.html

[S38] C++：排序
来源：http://dali.chenzaomai.com/Article/details/gtvewvezug.html

std::sort(v.begin(), v.end());
来源：http://dali.chenjidiqi.icu/Article/details/gtweexdzet.html

[S39] C++：自定义比较器排序
来源：http://dali.chenzaomai.com/Article/details/gtadkqcwpx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xuanzx.com/Article/details/gtbwnbvhgu.html

[S40] C++：查找元素
来源：http://dali.daria6918.cn/Article/details/gtqgsidewr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gogol.net.cn/Article/details/gtexdxlitp.html

[S41] C++：类与构造函数
来源：http://dali.gaohongyu789.top/Article/details/gtjbxbgstk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhengqikj.top/Article/details/gthkafidgf.html

[S42] C++：继承与虚函数
来源：http://dali.316326.xyz/Article/details/gtvratrcta.html

class B : public Base { public: void f() override {} };
来源：http://dali.mhx1999.top/Article/details/gtxewatgdd.html

[S43] C++：智能指针
来源：http://dali.guowangkeji.top/Article/details/gtchiqbdox.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinqigufen.top/Article/details/gtzehuzxxz.html

[S44] C++：引用传参
来源：http://dali.nanxuanxn.top/Article/details/gtajveywmr.html

void inc(int &x) { ++x; }
来源：http://dali.jinqigfzy.top/Article/details/gtftcnlmiw.html

[S45] C++：lambda
来源：http://dali.jinqigufen.top/Article/details/gtlzuqyhcm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.fzhhl.top/Article/details/gtbvlwevma.html

[S46] C++：函数模板
来源：http://dali.jiagoushi.top/Article/details/gtwlepxlru.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.snrcjt.cn/Article/details/gtjpzihaop.html

[S47] C++：结构化绑定遍历
来源：http://dali.jqgufenzy.top/Article/details/gtlfxnjbxm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.wangdashe.top/Article/details/gtksklluwi.html

[S48] C++：逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gtidhnqkuh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.haohaochexian.top/Article/details/gttihjxrqs.html

while (std::getline(in, line)) { }
来源：http://dali.jlsjyb.cn/Article/details/gtvdgkfcrn.html

[S49] C++：写文件
来源：http://dali.smart0.xyz/Article/details/gtlakfseom.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.nanxuanxn.top/Article/details/gtuyqeyvwv.html

[S50] C++：格式化数字
来源：http://dali.zhengqikj.top/Article/details/gtsllkjwqm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tanke756.top/Article/details/gttztjvvbk.html

[S51] C++：显式类型转换
来源：http://dali.9152youxi.cn/Article/details/gtlqsavsoh.html

static_cast<double>(a) / b
来源：http://dali.dashuyun.cn/Article/details/gteltrjduc.html

[S52] C++：const 与 noexcept
来源：http://dali.xinyue.icu/Article/details/gtmmzdpnca.html

int size() const noexcept { return n_; }
来源：http://dali.cucudq.cn/Article/details/gtoqboxrsw.html

[S53] C++：移动语义
来源：http://dali.guowangkeji.top/Article/details/gtuabkdawz.html

std::vector<int> w = std::move(v);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjgphyiyw.html

[S54] C++：异常处理
来源：http://dali.hongshengwenyu.top/Article/details/gtvzhdwlcr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.chenzaomai.com/Article/details/gtlvfvaaja.html

[S55] C++：结构化绑定
来源：http://dali.daria6918.cn/Article/details/gtshkbcvxp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.birdmap.top/Article/details/gtsrqljxrm.html

[S56] C++：optional
来源：http://dali.svipenyu.cn/Article/details/gtjuqxmxgs.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.daxiang520.top/Article/details/gtmcwrqkdj.html

[S57] C++：编译期常量
来源：http://dali.tianlin.xyz/Article/details/gtqyvqobww.html

constexpr int N = 10;
来源：http://dali.xinyue.icu/Article/details/gtbewsbslc.html

[S58] C++：命名空间
来源：http://dali.gaohongyu789.top/Article/details/gtzmdwybjw.html

namespace ns { int f() { return 1; } }
来源：http://dali.redwolf501.top/Article/details/gtbvornvwd.html

[S59] C++：静态断言
来源：http://dali.yanxiufei.cn/Article/details/gtfkceghsy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jqgufenzy.top/Article/details/gtafohkdlx.html

[S60] C++：遍历并删除元素
来源：http://dali.redwolf501.top/Article/details/gtkijgdwsn.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shanyushiyangtech.top/Article/details/gtrbqlpbbm.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtuqozksrh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.redwolf501.top/Article/details/gtuoenzula.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtjnjurzgz.html

[T01] Kotlin：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gtmjbkopwa.html

println("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdnbrrfxm.html

[T02] Kotlin：变量
来源：http://dali.kuanghao11.cn/Article/details/gtmlniwzsb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.chenzaomai.com/Article/details/gtjvaocjqp.html

[T03] Kotlin：字符串模板
来源：http://dali.c1oappe.top/Article/details/gtxcgqolej.html

"值: $b"
来源：http://dali.jinqigfzy.top/Article/details/gtaguxotjl.html

[T04] Kotlin：空安全
来源：http://dali.ybcxt.top/Article/details/gtzzlwqjem.html

val n: String? = null;  n?.length
来源：http://dali.zhoulong.xyz/Article/details/gthxzmsqbt.html

[T05] Kotlin：when 表达式
来源：http://dali.shuidangran.top/Article/details/gtrukjfwuq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.meibo888.top/Article/details/gtpculloae.html

[T06] Kotlin：集合映射
来源：http://dali.9152youxi.cn/Article/details/gtmkyzgizt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ehwqpu.com/Article/details/gtzvdkgodz.html

[T07] Kotlin：集合过滤
来源：http://dali.wangshuangyany.cn/Article/details/gtvvlpkbsz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yangfankeji.com/Article/details/gthbnckyoq.html

[T08] Kotlin：数据类
来源：http://dali.pycfn.com/Article/details/gtjxzxzkah.html

data class User(val name: String, val age: Int)
来源：http://dali.bjfxy.top/Article/details/gtfueqmpbj.html

[T09] Kotlin：扩展函数
来源：http://dali.snrcjt.cn/Article/details/gtnlzzlrie.html

fun String.exclaim() = this + "!"
来源：http://dali.zycfv.cn/Article/details/gtoyedsljo.html

[T10] Kotlin：默认参数
来源：http://dali.havefunace.top/Article/details/gtkubpdvcu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.c1oappe.top/Article/details/gtcyibcnma.html

[T11] Kotlin：协程
来源：http://dali.zycfv.cn/Article/details/gtpcvqcvsy.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.dashuyun.cn/Article/details/gtmtuwypnn.html

[T12] Kotlin：解构声明
来源：http://dali.hammf.cn/Article/details/gtecypiuzg.html

val (a, b) = Pair(1, 2)
来源：http://dali.dashuyun.cn/Article/details/gtgxhpylai.html

[T13] Kotlin：只读 Map
来源：http://dali.zycfv.cn/Article/details/gtashifplj.html

val m = mapOf("a" to 1)
来源：http://dali.yanxiufei.cn/Article/details/gtalqpfylh.html

[T14] Kotlin：循环
来源：http://dali.zycfv.cn/Article/details/gtnbsikfuv.html

for (i in 1..10) println(i)
来源：http://dali.jlsjyb.cn/Article/details/gtpklehybp.html

[T15] Kotlin：接口
来源：http://dali.yj20258888.top/Article/details/gtlgqbacnf.html

interface Shape { fun area(): Double }
来源：http://dali.shangyingyoupin.top/Article/details/gtooehghds.html

[T16] Swift：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtpdntgplu.html

print("Hello")
来源：http://dali.jinqigufen.top/Article/details/gtbyjwqujl.html

[T17] Swift：变量与常量
来源：http://dali.yj20258.top/Article/details/gtzbgcecyw.html

var a = 1;  let b = 2
来源：http://dali.xziqi.cn/Article/details/gtzkvxbiwj.html

[T18] Swift：字符串插值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjarbejrl.html

"值: \(b)"
来源：http://dali.nanxinkj.top/Article/details/gtaipdyxdz.html

[T19] Swift：可选绑定
来源：http://dali.cucudq.cn/Article/details/gtvepwggfp.html

if let n = opt { print(n) }
来源：http://dali.pengpengdd.cyou/Article/details/gtrmjvswph.html

[T20] Swift：数组操作
来源：http://dali.cheryme.top/Article/details/gtlvlucxai.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjvffxbgs.html

[T21] Swift：遍历
来源：http://dali.zycfv.cn/Article/details/gtrptdgwnc.html

for x in a { print(x) }
来源：http://dali.kuanghao11.cn/Article/details/gtqvtyxdje.html

[T22] Swift：字典
来源：http://dali.jiagoushi.top/Article/details/gtxcizjpcw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmltancnp.html

[T23] Swift：函数
来源：http://dali.snrcjt.cn/Article/details/gteeljgdfw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhiwuduotai.top/Article/details/gttvxfpcxi.html

[T24] Swift：闭包
来源：http://dali.fzhhl.top/Article/details/gtonzkhyad.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.tanke756.top/Article/details/gtgwndjkeu.html

[T25] Swift：结构体
来源：http://dali.nanxinkj.top/Article/details/gtjxbcxjor.html

struct P { var x: Int }
来源：http://dali.yonumen.top/Article/details/gtjgljniko.html

[T26] Swift：类与重写
来源：http://dali.cdnleiting.top/Article/details/gtevvlquir.html

class A: Base { override func f() {} }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlrbybqtw.html

[T27] Swift：错误处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gteolsxvtp.html

do { try f() } catch { print(error) }
来源：http://dali.hywenlv.cn/Article/details/gttijssjte.html

[T28] Swift：枚举
来源：http://dali.xylfe.cn/Article/details/gtdpaysklk.html

enum Color { case red, green }
来源：http://dali.nwbrower.top/Article/details/gtgiezsbzs.html

[T29] Swift：guard 提前返回
来源：http://dali.yj20258.top/Article/details/gtmnldidyg.html

guard let x = opt else { return }
来源：http://dali.yvedp.cn/Article/details/gtqqwutnnb.html

[T30] Swift：协议
来源：http://dali.sysykeji.top/Article/details/gtqvsmcgpk.html

protocol Shape { func area() -> Double }
来源：http://dali.zdqjudy.top/Article/details/gtbnviipbe.html

[T31] Lua：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtufpyjpzs.html

print("Hello")
来源：http://dali.zhongyouzk.top/Article/details/gtyqcktcqo.html

[T32] Lua：局部变量
来源：http://dali.feifeiyinyue.top/Article/details/gtatbtggsk.html

local a = 1
来源：http://dali.sxryk.cn/Article/details/gtaqvziriq.html

[T33] Lua：表（数组）
来源：http://dali.pycfn.com/Article/details/gtslvtyxid.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.svipenyu.cn/Article/details/gtogtuzfiy.html

[T34] Lua：遍历表
来源：http://dali.yuanzhike.top/Article/details/gtqmuajxvj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.kuanghao11.cn/Article/details/gthjbngywy.html

[T35] Lua：字典表
来源：http://dali.zhiwuduotai.top/Article/details/gtpnuyskrm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.bjfxy.top/Article/details/gtluqzodky.html

[T36] Lua：函数
来源：http://dali.fengsongda.top/Article/details/gtwnclzgov.html

function add(a, b) return a + b end
来源：http://dali.feifeiyinyue.top/Article/details/gtczvkoxyk.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gtlcpdlsps.html

"a" .. "b"
来源：http://dali.xuanzx.com/Article/details/gtembkxjun.html

[T38] Lua：条件
来源：http://dali.havefunace.top/Article/details/gtmjatyrhu.html

if x > 0 then print("正") end
来源：http://dali.xuetiantiany.cn/Article/details/gtxggdjeth.html

[T39] Lua：模式匹配
来源：http://dali.cucudq.cn/Article/details/gtbukjoacm.html

string.find(s, "%d+")
来源：http://dali.jiagoushi.top/Article/details/gtalmoclji.html

[T40] Lua：元表
来源：http://dali.birdmap.top/Article/details/gthjffoknr.html

setmetatable({}, { __index = base })
来源：http://dali.redwolf501.top/Article/details/gtnrjgbllb.html

[T41] Perl：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcqynifjy.html

print "Hello\n";
来源：http://dali.wangshuangyany.cn/Article/details/gtktwfvect.html

[T42] Perl：变量类型
来源：http://dali.wangshuangyany.cn/Article/details/gtbawzczmg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.pengpengdd.cyou/Article/details/gtnbhaqojq.html

[T43] Perl：字符串插值
来源：http://dali.gotoacloud.top/Article/details/gtejrjbxwl.html

"值: $a"
来源：http://dali.hnqzz.top/Article/details/gtuqpmzgqv.html

[T44] Perl：条件
来源：http://dali.jqgufenzy.top/Article/details/gtsygjvahc.html

if ($a > 0) { print "正"; }
来源：http://dali.zhongyouzk.top/Article/details/gtnnzukdpb.html

[T45] Perl：数组遍历
来源：http://dali.yuxming.cn/Article/details/gtpxgctnsq.html

for my $x (@arr) { print $x; }
来源：http://dali.guowangkeji.top/Article/details/gtfejazhuy.html

[T46] Perl：哈希操作
来源：http://dali.jlsjyb.cn/Article/details/gtdxsonibg.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hammf.cn/Article/details/gtaqqbdgcc.html

[T47] Perl：正则捕获
来源：http://dali.cheryme.top/Article/details/gtjbxgbznf.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jinqigfzy.top/Article/details/gtiiqleupp.html

[T48] Perl：正则替换
来源：http://dali.dashuyun.cn/Article/details/gtjinkxsrg.html

$s =~ s/old/new/g;
来源：http://dali.tianlin.xyz/Article/details/gttjlmnmbi.html

[T49] Perl：函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbjovrlvp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.cashguo.top/Article/details/gtbucfhnqo.html

[T50] Perl：逐行读文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvucmbhey.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.chenjidiqi.icu/Article/details/gtqruebzhp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.nwbrower.top/Article/details/gtbwcvbhmq.html

[T51] Scala：Hello World
来源：http://dali.ybcxt.top/Article/details/gthzfepcxc.html

println("Hello")
来源：http://dali.zhongyouzk.top/Article/details/gtbahsitiu.html

[T52] Scala：变量
来源：http://dali.fengsongda.top/Article/details/gtcunrzsgd.html

val a = 1;  var b = 2
来源：http://dali.nwbrower.top/Article/details/gtmfoxgidl.html

[T53] Scala：字符串插值
来源：http://dali.zhiwuduotai.top/Article/details/gtxtnekhiu.html

s"值: $b"
来源：http://dali.jyoumei.cn/Article/details/gtxtznyprm.html

[T54] Scala：集合映射
来源：http://dali.zhongyouzk.top/Article/details/gtmfofzfmy.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.birdmap.top/Article/details/gtpqterdbg.html

[T55] Scala：集合过滤
来源：http://dali.hongshengwenyu.top/Article/details/gtgkucjyeu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.vqdsnc.cn/Article/details/gtwtfcafhy.html

[T56] Scala：样例类
来源：http://dali.c1oappe.top/Article/details/gtrjbjgmhp.html

case class User(name: String, age: Int)
来源：http://dali.shangyingyoupin.top/Article/details/gtmwubgded.html

[T57] Scala：模式匹配
来源：http://dali.tianlin.xyz/Article/details/gttokdykjq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.sufxvd.cn/Article/details/gtzgcblunj.html

[T58] Scala：函数定义
来源：http://dali.cheryme.top/Article/details/gtxgpahzun.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yuanzhike.top/Article/details/gtnifnbzvw.html

[T59] Scala：循环
来源：http://dali.sysykeji.top/Article/details/gtixlklkhd.html

for (i <- 1 to 10) println(i)
来源：http://dali.jianghu66.top/Article/details/gthxetblml.html

[T60] Scala：折叠
来源：http://dali.guowangkeji.top/Article/details/gthscucupf.html


<!-- 参考信息 -->