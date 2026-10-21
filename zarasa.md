代发 wailian999

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.chenzaomai.com/Article/details/gthatqvgvo.html

[R50] awk 求和
来源：http://dali.zhiwuduotai.top/Article/details/gtlknrnmqf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xylfe.cn/Article/details/gtpqjepvmn.html

[R51] 排序去重取前几
来源：http://dali.cashguo.top/Article/details/gtvekivfao.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.dashuyun.cn/Article/details/gtlttawqct.html

[R52] 统计行数
来源：http://dali.hnqzz.top/Article/details/gtpskbiprh.html

wc -l a.txt
来源：http://dali.c1oappe.top/Article/details/gtnlpkwigo.html

[R53] 查看文件头与实时尾
来源：http://dali.kuanghao11.cn/Article/details/gtyaptihfz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.feifeiyinyue.top/Article/details/gtymnjczjw.html

[R54] 比较两个文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyqitdapf.html

diff a.txt b.txt
来源：http://dali.gotoacloud.top/Article/details/gtjhsxpayt.html

[R55] 压缩与解压
来源：http://dali.yuxming.cn/Article/details/gtsgzydooc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.0kj1m.cn/Article/details/gtsitdbgzw.html

[R56] 远程拷贝
来源：http://dali.xinyue.icu/Article/details/gtdogeknzd.html

scp file user@host:/path/
来源：http://dali.shangyingyoupin.top/Article/details/gtbkteqjfr.html

[R57] 远程执行命令
来源：http://dali.gaohongyu789.top/Article/details/gtisdtggdk.html

ssh user@host 'uptime'
来源：http://dali.kuanghao11.cn/Article/details/gtnotyxhsq.html

[R58] 下载文件
来源：http://dali.yongpay.top/Article/details/gtmcfhmiee.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ehwqpu.com/Article/details/gtlrblpeuv.html

[R59] 发 POST JSON
来源：http://dali.vqdsnc.cn/Article/details/gttxlmghng.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.bjfxy.top/Article/details/gtwmojquxp.html

[R60] 只看 HTTP 状态码
来源：http://dali.iojbl.cn/Article/details/gtgakwhsph.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zdqjudy.top/Article/details/gtymupknhv.html

[R61] 磁盘占用
来源：http://dali.wangshuangyany.cn/Article/details/gtpnbnbkln.html

df -h;  du -sh *
来源：http://dali.dianchejie.cn/Article/details/gtjcnnweoy.html

[R62] 找最占空间的文件
来源：http://dali.ivvv.top/Article/details/gtdwmaxadf.html

du -ah . | sort -rh | head -10
来源：http://dali.jinqigufen.top/Article/details/gtqcahkrdv.html

[R63] 内存与进程
来源：http://dali.birdmap.top/Article/details/gtuagyplap.html

free -h;  ps aux | grep nginx
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcwhgykxk.html

[R64] 结束进程
来源：http://dali.yanxiufei.cn/Article/details/gtsuepvqlr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sweek.top/Article/details/gtfcwdybmz.html

[R65] 查看端口占用
来源：http://dali.wangdashe.top/Article/details/gtdgexgflc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.daxiang520.top/Article/details/gtjdoaysom.html

[R66] 定时任务
来源：http://dali.hywenlv.cn/Article/details/gtgaweaihs.html

crontab -e;  crontab -l
来源：http://dali.hongshengwenyu.top/Article/details/gtlhnsznhh.html

[R67] 生成随机十六进制串
来源：http://dali.yangfankeji.com/Article/details/gtycysafih.html

openssl rand -hex 16
来源：http://dali.snrcjt.cn/Article/details/gtogxzauju.html

[R68] 计算文件校验值
来源：http://dali.cdnleiting.top/Article/details/gtztnybmiq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hnxiangtu.top/Article/details/gtwapkzdew.html

[R69] 生成随机密码
来源：http://dali.0kj1m.cn/Article/details/gtrqbuqnnv.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlnazwhaw.html

[R70] 时间戳与互转
来源：http://dali.cheryme.top/Article/details/gtowrlxsox.html

date +%s;  date -d @1700000000
来源：http://dali.jianghu66.top/Article/details/gtgnouahol.html

[R71] 日期格式化
来源：http://dali.nanxuanxn.top/Article/details/gtwotocwuz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.daxiang520.top/Article/details/gtpddgzgkv.html

[R72] 等待端口就绪
来源：http://dali.nanxuanxn.top/Article/details/gthvtvbqnr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.0kj1m.cn/Article/details/gtbcvduwys.html

[R73] 分割大日志
来源：http://dali.iojbl.cn/Article/details/gtdglnndny.html

split -l 1000 big.log part_
来源：http://dali.snrcjt.cn/Article/details/gtgypvijxs.html

[R74] 批量重命名
来源：http://dali.zdqjudy.top/Article/details/gtvrjsmrbz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xziqi.cn/Article/details/gtnpnnybad.html

[R75] 导出环境变量
来源：http://dali.cucudq.cn/Article/details/gttcqddxus.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hnxiangtu.top/Article/details/gtbpyrgdix.html

[R76] 使用临时文件
来源：http://dali.xylfe.cn/Article/details/gttvezqlib.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj20258.top/Article/details/gtqnbnxwsa.html

[R77] 读取用户输入
来源：http://dali.fzhhl.top/Article/details/gtmjebttlr.html

read -rp "请输入: " ans
来源：http://dali.chenzaomai.com/Article/details/gtloniuzus.html

[R78] 交互式菜单
来源：http://dali.316326.xyz/Article/details/gtvufxrmbw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sufxvd.cn/Article/details/gtmngoepyv.html

[R79] 解析命令行选项
来源：http://dali.hammf.cn/Article/details/gtqrifttom.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sufxvd.cn/Article/details/gtkxhmqmid.html

[R80] 查看脚本执行耗时
来源：http://dali.iojbl.cn/Article/details/gtkuceungc.html

time ./run.sh
来源：http://dali.svipenyu.cn/Article/details/gtkgmpajlk.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtyxsqlyyd.html

S. C / C++ 专题
来源：http://dali.yanxiufei.cn/Article/details/gtktqqeuwk.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtgiqphjfk.html

[S01] C：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtgprntnwa.html

#include <stdio.h>
来源：http://dali.jiagoushi.top/Article/details/gtfhtitnro.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.aibaodan.cn/Article/details/gtfhejothu.html

[S02] C：变量与格式化输出
来源：http://dali.cheryme.top/Article/details/gtvylerznk.html

int a = 10; printf("%d\n", a);
来源：http://dali.hysaishi.cn/Article/details/gtmorhnknm.html

[S03] C：读入整数
来源：http://dali.fengsongda.top/Article/details/gtmiythoki.html

int x; scanf("%d", &x);
来源：http://dali.316326.xyz/Article/details/gtlrmkwxvm.html

[S04] C：字符串复制
来源：http://dali.zhongyouzk.top/Article/details/gtxhtswawz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwwzviupz.html

[S05] C：字符串长度
来源：http://dali.fengsongda.top/Article/details/gtmzxjbxcc.html

strlen(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtbvlcxebi.html

[S06] C：字符串比较
来源：http://dali.cdnleiting.top/Article/details/gtdfcbweko.html

strcmp(a, b) == 0
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcilpmyav.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gtskhcidrs.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xuanzx.com/Article/details/gtdcxcrgec.html

[S08] C：动态内存分配与释放
来源：http://dali.zhengqikj.top/Article/details/gtkhsrucey.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinyuanbaomall.cn/Article/details/gturmyrvje.html

[S09] C：结构体定义与初始化
来源：http://dali.chenzaomai.com/Article/details/gtodspuvqw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hfpthk.cn/Article/details/gtplzqukyp.html

[S10] C：指针与解引用
来源：http://dali.wangdashe.top/Article/details/gtuqqfwtee.html

int *p = &a;  *p = 5;
来源：http://dali.hammf.cn/Article/details/gtdadsknpd.html

[S11] C：逐行读文件
来源：http://dali.tian-w.cn/Article/details/gtsrrqnynt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yj202588.top/Article/details/gtjovvbcip.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zycfv.cn/Article/details/gtmcrllrli.html

fclose(f);
来源：http://dali.nwbrower.top/Article/details/gtdumwvxys.html

[S12] C：写文件
来源：http://dali.bjfxy.top/Article/details/gtydsqxhoz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhiwuduotai.top/Article/details/gtxeeqafod.html

[S13] C：宏定义
来源：http://dali.zhongyouzk.top/Article/details/gtclvcjwbm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gzhubu.top/Article/details/gtarmftrlh.html

[S14] C：枚举
来源：http://dali.jqgufenzy.top/Article/details/gtshlvwbfb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhoulong.xyz/Article/details/gtehgyykmb.html

[S15] C：类型转换
来源：http://dali.tanke756.top/Article/details/gtozjsszss.html

(double) a / b
来源：http://dali.dianchejie.cn/Article/details/gtekxtwnxq.html

[S16] C：位操作置位
来源：http://dali.yuanzhike.top/Article/details/gtvxmzdqjt.html

x |= (1 << 3);
来源：http://dali.svipenyu.cn/Article/details/gtmfdxcfdc.html

[S17] C：安全拼接字符串
来源：http://dali.redwolf501.top/Article/details/gtelusjrgx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.316326.xyz/Article/details/gtmgqraaxg.html

[S18] C：命令行参数
来源：http://dali.bjfxy.top/Article/details/gtoqimtgsf.html

int main(int argc, char **argv)
来源：http://dali.feifeiyinyue.top/Article/details/gtvrtkjjsf.html

[S19] C：快速排序
来源：http://dali.c1oappe.top/Article/details/gttmncccyy.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.daxiang520.top/Article/details/gtphivbnvz.html

[S20] C：二分查找
来源：http://dali.vqdsnc.cn/Article/details/gtcskwxrsn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yj20258888.top/Article/details/gtftdlzuay.html

[S21] C：字符类别判断
来源：http://dali.jiagoushi.top/Article/details/gtwqniinku.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gtakyxxwty.html

[S22] C：字符串转数字
来源：http://dali.zhongyouzk.top/Article/details/gtebhbvuey.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.birdmap.top/Article/details/gtrnzsmctr.html

[S23] C：随机数
来源：http://dali.zdqjudy.top/Article/details/gtafxvaful.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gogol.net.cn/Article/details/gtfaujytcj.html

[S24] C：获取本地时间
来源：http://dali.meibo888.top/Article/details/gtcgdaupsm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ehwqpu.com/Article/details/gtlcxyrnkg.html

[S25] C：内存拷贝
来源：http://dali.aibaodan.cn/Article/details/gtodtaociy.html

memcpy(dst, src, n);
来源：http://dali.wangshuangyany.cn/Article/details/gtbqlujubx.html

[S26] C：内存清零
来源：http://dali.nwbrower.top/Article/details/gtakqzkfmg.html

memset(a, 0, sizeof a);
来源：http://dali.jinqigufen.top/Article/details/gtikwpmasy.html

[S27] C：定义常量
来源：http://dali.bjfxy.top/Article/details/gtqzebmroo.html

const double PI = 3.14159;
来源：http://dali.c1oappe.top/Article/details/gtdxgrrgbi.html

[S28] C：静态变量
来源：http://dali.wangdashe.top/Article/details/gtywcobjzt.html

static int counter = 0;
来源：http://dali.yvedp.cn/Article/details/gtojwjlaus.html

[S29] C：变参函数
来源：http://dali.chenjidiqi.icu/Article/details/gtkujttaot.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shangyingyoupin.top/Article/details/gtqaywqpcj.html

[S30] C：头文件保护
来源：http://dali.yj20258.top/Article/details/gtchtqosaw.html

#ifndef X_H
来源：http://dali.hywenlv.cn/Article/details/gtpdswdeqg.html

#define X_H
来源：http://dali.smart0.xyz/Article/details/gthejswqcf.html

#endif
来源：http://dali.c1oappe.top/Article/details/gtvstqwwev.html

[S31] C++：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtzdtronic.html

#include <iostream>
来源：http://dali.zycfv.cn/Article/details/gtokgwpjfd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ybcxt.top/Article/details/gtwgzkihdv.html

[S32] C++：字符串
来源：http://dali.cucudq.cn/Article/details/gttzlzavxg.html

std::string s = "hi";  s += "!";
来源：http://dali.ppjwa.cn/Article/details/gtoovfwylf.html

[S33] C++：vector 增删
来源：http://dali.yj202588.top/Article/details/gtikdqiupk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xylfe.cn/Article/details/gttebozwbf.html

[S34] C++：遍历 vector
来源：http://dali.yonumen.top/Article/details/gtjyfqbrel.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sufxvd.cn/Article/details/gtdfxpnsjz.html

[S35] C++：map
来源：http://dali.0kj1m.cn/Article/details/gtncnffxwt.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ppjwa.cn/Article/details/gtulilluks.html

[S36] C++：unordered_map
来源：http://dali.gzhubu.top/Article/details/gtoeqcoqkx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuxming.cn/Article/details/gtfzsmhlzh.html

[S37] C++：set
来源：http://dali.zhengqikj.top/Article/details/gtxlqfuhvw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.nanxinkj.top/Article/details/gtiwsvdyeu.html

[S38] C++：排序
来源：http://dali.tanke756.top/Article/details/gtindimxwi.html

std::sort(v.begin(), v.end());
来源：http://dali.jyoumei.cn/Article/details/gtbokepntl.html

[S39] C++：自定义比较器排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbcvsxymm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.birdmap.top/Article/details/gtruklqigd.html

[S40] C++：查找元素
来源：http://dali.0kj1m.cn/Article/details/gtjypwxgwt.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yongpay.top/Article/details/gtvgodcesj.html

[S41] C++：类与构造函数
来源：http://dali.fengsongda.top/Article/details/gtaubujoaw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhoulong.xyz/Article/details/gttnhasdbe.html

[S42] C++：继承与虚函数
来源：http://dali.jinqigufen.top/Article/details/gtqsvcbznp.html

class B : public Base { public: void f() override {} };
来源：http://dali.cdnleiting.top/Article/details/gtvoorvbfu.html

[S43] C++：智能指针
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkqeiisfm.html

auto p = std::make_unique<int>(5);
来源：http://dali.hongshengwenyu.top/Article/details/gtngjuehcb.html

[S44] C++：引用传参
来源：http://dali.hywenlv.cn/Article/details/gtkttxccwk.html

void inc(int &x) { ++x; }
来源：http://dali.yangfankeji.com/Article/details/gtkkqhzheb.html

[S45] C++：lambda
来源：http://dali.sweek.top/Article/details/gtqaonfbda.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hammf.cn/Article/details/gthzrghlya.html

[S46] C++：函数模板
来源：http://dali.ehwqpu.com/Article/details/gtdsofamuu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sweek.top/Article/details/gtheceucrd.html

[S47] C++：结构化绑定遍历
来源：http://dali.ydzc1.top/Article/details/gtiqjnrtip.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttdwrnzgz.html

[S48] C++：逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gtdwjpfbev.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yongpay.top/Article/details/gtjnnmcchv.html

while (std::getline(in, line)) { }
来源：http://dali.jyoumei.cn/Article/details/gtaexegqqb.html

[S49] C++：写文件
来源：http://dali.ydzc1.top/Article/details/gtrtsexqko.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cashguo.top/Article/details/gtpwjlltjp.html

[S50] C++：格式化数字
来源：http://dali.daxiang520.top/Article/details/gtcxxviptd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gaohongyu789.top/Article/details/gtzalegjff.html

[S51] C++：显式类型转换
来源：http://dali.wangshuangyany.cn/Article/details/gtdfrbznyy.html

static_cast<double>(a) / b
来源：http://dali.andypj.xyz/Article/details/gtlkjurclj.html

[S52] C++：const 与 noexcept
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdenwqyip.html

int size() const noexcept { return n_; }
来源：http://dali.cdnleiting.top/Article/details/gtppfpuctz.html

[S53] C++：移动语义
来源：http://dali.jlsjyb.cn/Article/details/gtkzjzesgk.html

std::vector<int> w = std::move(v);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkwhuxvlz.html

[S54] C++：异常处理
来源：http://dali.ybcxt.top/Article/details/gtuomybnkv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jlsjyb.cn/Article/details/gtlpyjwztn.html

[S55] C++：结构化绑定
来源：http://dali.zhongyouzk.top/Article/details/gtmpxlfzsa.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yuxming.cn/Article/details/gthmadscei.html

[S56] C++：optional
来源：http://dali.sweek.top/Article/details/gtzimbqcqe.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj20258.top/Article/details/gtuqvokour.html

[S57] C++：编译期常量
来源：http://dali.vqdsnc.cn/Article/details/gtmknoxbck.html

constexpr int N = 10;
来源：http://dali.hfpthk.cn/Article/details/gtgyrmmbfa.html

[S58] C++：命名空间
来源：http://dali.cqqwz.cn/Article/details/gtzrzycrgy.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gttfgwxjpz.html

[S59] C++：静态断言
来源：http://dali.hnqzz.top/Article/details/gtzjcptlby.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shuidangran.top/Article/details/gtgedzvlyb.html

[S60] C++：遍历并删除元素
来源：http://dali.pengpengdd.cyou/Article/details/gtcsphyxud.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.nanxinkj.top/Article/details/gtwqifwfhn.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtsibxykos.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.andypj.xyz/Article/details/gtfhodxhkd.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtgvstobae.html

[T01] Kotlin：Hello World
来源：http://dali.sxryk.cn/Article/details/gtnskaybir.html

println("Hello")
来源：http://dali.xylfe.cn/Article/details/gthdtovlbs.html

[T02] Kotlin：变量
来源：http://dali.wangdashe.top/Article/details/gtqksbashr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ivvv.top/Article/details/gtagmyzcej.html

[T03] Kotlin：字符串模板
来源：http://dali.wangshuangyany.cn/Article/details/gtkoeehhur.html

"值: $b"
来源：http://dali.nwbrower.top/Article/details/gtgpixhapb.html

[T04] Kotlin：空安全
来源：http://dali.shangyingyoupin.top/Article/details/gtsqunvgcg.html

val n: String? = null;  n?.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwgfaydmd.html

[T05] Kotlin：when 表达式
来源：http://dali.yueranfly.top/Article/details/gtikzhjmrw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.fzhhl.top/Article/details/gtyzonbwsn.html

[T06] Kotlin：集合映射
来源：http://dali.redwolf501.top/Article/details/gthmzvgvux.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yongpay.top/Article/details/gtzmxzjbmm.html

[T07] Kotlin：集合过滤
来源：http://dali.daria6918.cn/Article/details/gtapdymqvb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yanxiufei.cn/Article/details/gtvkoulijn.html

[T08] Kotlin：数据类
来源：http://dali.pengpengdd.cyou/Article/details/gtnuabjuas.html

data class User(val name: String, val age: Int)
来源：http://dali.wangshuangyany.cn/Article/details/gtwukwtpiu.html

[T09] Kotlin：扩展函数
来源：http://dali.ybcxt.top/Article/details/gtxknwopll.html

fun String.exclaim() = this + "!"
来源：http://dali.hnxiangtu.top/Article/details/gtcsjvtngy.html

[T10] Kotlin：默认参数
来源：http://dali.quarkkingdee.top/Article/details/gtlltnxawf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.gotoacloud.top/Article/details/gttuqfajul.html

[T11] Kotlin：协程
来源：http://dali.shuidangran.top/Article/details/gthbmhwrwf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jinqigufen.top/Article/details/gtazsmmiwb.html

[T12] Kotlin：解构声明
来源：http://dali.hnxiangtu.top/Article/details/gtiyypugtw.html

val (a, b) = Pair(1, 2)
来源：http://dali.hnxiangtu.top/Article/details/gtpwpzffkl.html

[T13] Kotlin：只读 Map
来源：http://dali.iojbl.cn/Article/details/gtgghoivis.html

val m = mapOf("a" to 1)
来源：http://dali.andypj.xyz/Article/details/gttxzobazg.html

[T14] Kotlin：循环
来源：http://dali.gogol.net.cn/Article/details/gtdfvnoeqi.html

for (i in 1..10) println(i)
来源：http://dali.guannengcc.top/Article/details/gtoeufibgk.html

[T15] Kotlin：接口
来源：http://dali.hnxiangtu.top/Article/details/gtfcsrrdbt.html

interface Shape { fun area(): Double }
来源：http://dali.svipenyu.cn/Article/details/gtfxvaxrsg.html

[T16] Swift：Hello World
来源：http://dali.shuidangran.top/Article/details/gtnygipgnc.html

print("Hello")
来源：http://dali.316326.xyz/Article/details/gtgcvznrgi.html

[T17] Swift：变量与常量
来源：http://dali.andypj.xyz/Article/details/gtbeufwdax.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gttcycbwny.html

[T18] Swift：字符串插值
来源：http://dali.yj202588.top/Article/details/gtutjouykz.html

"值: \(b)"
来源：http://dali.cucudq.cn/Article/details/gtumudfahq.html

[T19] Swift：可选绑定
来源：http://dali.jinqigfzy.top/Article/details/gtqkpfepxf.html

if let n = opt { print(n) }
来源：http://dali.birdmap.top/Article/details/gtnlkqrzje.html

[T20] Swift：数组操作
来源：http://dali.shuidangran.top/Article/details/gthduoskyh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.guannengcc.top/Article/details/gtwncdlbqy.html

[T21] Swift：遍历
来源：http://dali.andypj.xyz/Article/details/gtpciqwase.html

for x in a { print(x) }
来源：http://dali.meibo888.top/Article/details/gttfqsgwdh.html

[T22] Swift：字典
来源：http://dali.fengsongda.top/Article/details/gtwsmrppsz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.guannengcc.top/Article/details/gtfhtnvcxh.html

[T23] Swift：函数
来源：http://dali.snrcjt.cn/Article/details/gtplbyfdqd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yj20258.top/Article/details/gtedfczcpx.html

[T24] Swift：闭包
来源：http://dali.hammf.cn/Article/details/gtmsfasnxq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.gaohongyu789.top/Article/details/gtxzfjzqpn.html

[T25] Swift：结构体
来源：http://dali.guannengcc.top/Article/details/gtirjqfiyr.html

struct P { var x: Int }
来源：http://dali.iojbl.cn/Article/details/gtkdborera.html

[T26] Swift：类与重写
来源：http://dali.shzxlz.cn/Article/details/gtrknwyblj.html

class A: Base { override func f() {} }
来源：http://dali.nanxinkj.top/Article/details/gtjcdqgcve.html

[T27] Swift：错误处理
来源：http://dali.daria6918.cn/Article/details/gtojxngmyx.html

do { try f() } catch { print(error) }
来源：http://dali.wangdashe.top/Article/details/gtldsmopje.html

[T28] Swift：枚举
来源：http://dali.tianlin.xyz/Article/details/gtzkqhwdpn.html

enum Color { case red, green }
来源：http://dali.chenzaomai.com/Article/details/gtrfivsaen.html

[T29] Swift：guard 提前返回
来源：http://dali.tian-w.cn/Article/details/gtgtwuserh.html

guard let x = opt else { return }
来源：http://dali.daxiang520.top/Article/details/gtllsyrbpg.html

[T30] Swift：协议
来源：http://dali.dashuyun.cn/Article/details/gtpdcrbkhq.html

protocol Shape { func area() -> Double }
来源：http://dali.yj202588.top/Article/details/gtoytisjht.html

[T31] Lua：Hello World
来源：http://dali.yonumen.top/Article/details/gtbpiaxlxb.html

print("Hello")
来源：http://dali.cqqwz.cn/Article/details/gttjdbymuq.html

[T32] Lua：局部变量
来源：http://dali.andypj.xyz/Article/details/gtnyfalcus.html

local a = 1
来源：http://dali.shzxlz.cn/Article/details/gtizbtgcsy.html

[T33] Lua：表（数组）
来源：http://dali.nwbrower.top/Article/details/gtvbdklxak.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hywenlv.cn/Article/details/gtertrkuzt.html

[T34] Lua：遍历表
来源：http://dali.hnqzz.top/Article/details/gtrzbynwrm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.dashuyun.cn/Article/details/gtsqpimqxl.html

[T35] Lua：字典表
来源：http://dali.zdqjudy.top/Article/details/gtkdzprydk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jqgufenzy.top/Article/details/gtzkptbqkl.html

[T36] Lua：函数
来源：http://dali.jinqigufen.top/Article/details/gthyiveenh.html

function add(a, b) return a + b end
来源：http://dali.andypj.xyz/Article/details/gtexmwwkjh.html

[T37] Lua：字符串拼接
来源：http://dali.sufxvd.cn/Article/details/gtuqyxjwid.html

"a" .. "b"
来源：http://dali.chenlongwang.top/Article/details/gttprzjryj.html

[T38] Lua：条件
来源：http://dali.iojbl.cn/Article/details/gtlqkniimb.html

if x > 0 then print("正") end
来源：http://dali.xuanzx.com/Article/details/gtixicbgja.html

[T39] Lua：模式匹配
来源：http://dali.jinqigufen.top/Article/details/gtzanhzbgh.html

string.find(s, "%d+")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrvhxdevq.html

[T40] Lua：元表
来源：http://dali.bjfxy.top/Article/details/gtwlookvxs.html

setmetatable({}, { __index = base })
来源：http://dali.sweek.top/Article/details/gtmdxhstyn.html

[T41] Perl：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtarowomsj.html

print "Hello\n";
来源：http://dali.xylfe.cn/Article/details/gtnivwnecr.html

[T42] Perl：变量类型
来源：http://dali.xuetiantiany.cn/Article/details/gtdtluvboh.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cqqwz.cn/Article/details/gtmksuhblj.html

[T43] Perl：字符串插值
来源：http://dali.snrcjt.cn/Article/details/gtrbizzuvu.html

"值: $a"
来源：http://dali.gotoacloud.top/Article/details/gtvuhuoams.html

[T44] Perl：条件
来源：http://dali.ivvv.top/Article/details/gtedobmhrz.html

if ($a > 0) { print "正"; }
来源：http://dali.xziqi.cn/Article/details/gthulgwodr.html

[T45] Perl：数组遍历
来源：http://dali.jiagoushi.top/Article/details/gtcikamews.html

for my $x (@arr) { print $x; }
来源：http://dali.hongshengwenyu.top/Article/details/gtrbopjgkh.html

[T46] Perl：哈希操作
来源：http://dali.jinqigfzy.top/Article/details/gtcavsqmzx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hfpthk.cn/Article/details/gtclfcwzpp.html

[T47] Perl：正则捕获
来源：http://dali.9152youxi.cn/Article/details/gtxkkusjig.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.cashguo.top/Article/details/gtebpttgkb.html

[T48] Perl：正则替换
来源：http://dali.chenzaomai.com/Article/details/gtmbaslmjg.html

$s =~ s/old/new/g;
来源：http://dali.wangdashe.top/Article/details/gtudqiycjf.html

[T49] Perl：函数
来源：http://dali.hnqzz.top/Article/details/gtqhwfdulv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.kuanghao11.cn/Article/details/gtxylueksw.html

[T50] Perl：逐行读文件
来源：http://dali.meibo888.top/Article/details/gtpfrczphr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jiagoushi.top/Article/details/gtohnwzcsl.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yonumen.top/Article/details/gtmjvswypp.html

[T51] Scala：Hello World
来源：http://dali.ivvv.top/Article/details/gtjjyftpxd.html

println("Hello")
来源：http://dali.c1oappe.top/Article/details/gteyhpgeua.html

[T52] Scala：变量
来源：http://dali.sufxvd.cn/Article/details/gtvumdsowk.html


<!-- 参考信息 -->