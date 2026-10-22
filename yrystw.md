代发 wailian999

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.haohaochexian.top/Article/details/gtmvlcatul.html

[R56] 远程拷贝
来源：http://dali.hnqzz.top/Article/details/gtpmedruid.html

scp file user@host:/path/
来源：http://dali.sysykeji.top/Article/details/gtkoyryvnv.html

[R57] 远程执行命令
来源：http://dali.meibo888.top/Article/details/gtrwjtmvho.html

ssh user@host 'uptime'
来源：http://dali.cashguo.top/Article/details/gtbxvuvdot.html

[R58] 下载文件
来源：http://dali.pycfn.com/Article/details/gteadvsdke.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hongshengwenyu.top/Article/details/gtwmgcmecx.html

[R59] 发 POST JSON
来源：http://dali.cqqwz.cn/Article/details/gtwaxdmxro.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.snrcjt.cn/Article/details/gtcwgogpci.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinqigfzy.top/Article/details/gtshbpzcba.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ywan-chungtsiang.top/Article/details/gtolosbmdx.html

[R61] 磁盘占用
来源：http://dali.aibaodan.cn/Article/details/gtqigxlpbr.html

df -h;  du -sh *
来源：http://dali.nanxinkj.top/Article/details/gtftgivltu.html

[R62] 找最占空间的文件
来源：http://dali.zhixingplan.top/Article/details/gtfcgfgsol.html

du -ah . | sort -rh | head -10
来源：http://dali.xuanzx.com/Article/details/gtcdvbuyrn.html

[R63] 内存与进程
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpnfqbswj.html

free -h;  ps aux | grep nginx
来源：http://dali.guannengcc.top/Article/details/gtvishxuwz.html

[R64] 结束进程
来源：http://dali.iojbl.cn/Article/details/gtelieeuia.html

kill -9 $(pgrep -f app.py)
来源：http://dali.havefunace.top/Article/details/gturdohtkn.html

[R65] 查看端口占用
来源：http://dali.wangshuangyany.cn/Article/details/gthwetmmxs.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jqgfzy.top/Article/details/gtgzqvxryv.html

[R66] 定时任务
来源：http://dali.iojbl.cn/Article/details/gtyisodrle.html

crontab -e;  crontab -l
来源：http://dali.gaohongyu789.top/Article/details/gtokxsonlo.html

[R67] 生成随机十六进制串
来源：http://dali.jinqigfzy.top/Article/details/gtmtaqxguu.html

openssl rand -hex 16
来源：http://dali.guowangkeji.top/Article/details/gtuemwrtef.html

[R68] 计算文件校验值
来源：http://dali.iojbl.cn/Article/details/gtsakskbha.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.guannengcc.top/Article/details/gtgzgsvflb.html

[R69] 生成随机密码
来源：http://dali.mhx1999.top/Article/details/gtxqvoujiq.html

head -c 16 /dev/urandom | base64
来源：http://dali.cucudq.cn/Article/details/gthaistwrx.html

[R70] 时间戳与互转
来源：http://dali.nwbrower.top/Article/details/gtszqrarcd.html

date +%s;  date -d @1700000000
来源：http://dali.yongpay.top/Article/details/gtukfpcaht.html

[R71] 日期格式化
来源：http://dali.jyoumei.cn/Article/details/gtlkwwyfyk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.fengsongda.top/Article/details/gtgxqvmavr.html

[R72] 等待端口就绪
来源：http://dali.yonumen.top/Article/details/gthhgyrigb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hfpthk.cn/Article/details/gtmpmfelea.html

[R73] 分割大日志
来源：http://dali.tanke756.top/Article/details/gtdqpmqsta.html

split -l 1000 big.log part_
来源：http://dali.sysykeji.top/Article/details/gtyoimzixs.html

[R74] 批量重命名
来源：http://dali.jyoumei.cn/Article/details/gtyzubvovp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.316326.xyz/Article/details/gtcyfdqooa.html

[R75] 导出环境变量
来源：http://dali.ybcxt.top/Article/details/gtuswspyvx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jqgfzy.top/Article/details/gtaaanmdqa.html

[R76] 使用临时文件
来源：http://dali.svipenyu.cn/Article/details/gtbkmgcfuh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.guowangkeji.top/Article/details/gtiltgjvcw.html

[R77] 读取用户输入
来源：http://dali.meibo888.top/Article/details/gtgyzkhjml.html

read -rp "请输入: " ans
来源：http://dali.haohaochexian.top/Article/details/gtkrngouvz.html

[R78] 交互式菜单
来源：http://dali.hfpthk.cn/Article/details/gtgqxzheju.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hammf.cn/Article/details/gtfzfedqio.html

[R79] 解析命令行选项
来源：http://dali.ybcxt.top/Article/details/gtlfgazfmw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yanxiufei.cn/Article/details/gtvyggffbm.html

[R80] 查看脚本执行耗时
来源：http://dali.yj20258888.top/Article/details/gtdsxvbiry.html

time ./run.sh
来源：http://dali.smart0.xyz/Article/details/gtvbscgwuq.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gthauhklrf.html

S. C / C++ 专题
来源：http://dali.zhongyouzk.top/Article/details/gtrfmukhjv.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtcspelhnr.html

[S01] C：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtbtnnlxuf.html

#include <stdio.h>
来源：http://dali.gzhubu.top/Article/details/gtoymedfyk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ivvv.top/Article/details/gtidtunxdg.html

[S02] C：变量与格式化输出
来源：http://dali.wangdashe.top/Article/details/gtnsujmwtj.html

int a = 10; printf("%d\n", a);
来源：http://dali.gotoacloud.top/Article/details/gtporeaxiv.html

[S03] C：读入整数
来源：http://dali.guowangkeji.top/Article/details/gtuqvkydfi.html

int x; scanf("%d", &x);
来源：http://dali.yuxming.cn/Article/details/gttbtjaszc.html

[S04] C：字符串复制
来源：http://dali.zycfv.cn/Article/details/gtiemjfteb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.mhx1999.top/Article/details/gtbbqcdogj.html

[S05] C：字符串长度
来源：http://dali.yvedp.cn/Article/details/gtdnyddjob.html

strlen(s)
来源：http://dali.haohaochexian.top/Article/details/gtjndxwact.html

[S06] C：字符串比较
来源：http://dali.jiagoushi.top/Article/details/gtbugefbrq.html

strcmp(a, b) == 0
来源：http://dali.hysaishi.cn/Article/details/gtgayjohmt.html

[S07] C：数组遍历求和
来源：http://dali.dashuyun.cn/Article/details/gtkatnbxce.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.bjfxy.top/Article/details/gtpuvurjxs.html

[S08] C：动态内存分配与释放
来源：http://dali.quarkkingdee.top/Article/details/gtowemtuxp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.kuanghao11.cn/Article/details/gtwoztksja.html

[S09] C：结构体定义与初始化
来源：http://dali.fzhhl.top/Article/details/gtyfsnudcg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.daria6918.cn/Article/details/gtjvkzslcj.html

[S10] C：指针与解引用
来源：http://dali.yonumen.top/Article/details/gtuampngiu.html

int *p = &a;  *p = 5;
来源：http://dali.ydzc1.top/Article/details/gtvvyxmydy.html

[S11] C：逐行读文件
来源：http://dali.guannengcc.top/Article/details/gtrjuqidjm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hammf.cn/Article/details/gtwqduktab.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yuanzhike.top/Article/details/gtsnhamkjm.html

fclose(f);
来源：http://dali.bjfxy.top/Article/details/gtjjwmpazg.html

[S12] C：写文件
来源：http://dali.tanke756.top/Article/details/gtzcrehjqf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhaomingkeji.xyz/Article/details/gthajnqmgj.html

[S13] C：宏定义
来源：http://dali.nanxuanxn.top/Article/details/gtgydyhraa.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.iojbl.cn/Article/details/gthkeavftc.html

[S14] C：枚举
来源：http://dali.nanxinkj.top/Article/details/gtifdszper.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shuidangran.top/Article/details/gtcjusdybc.html

[S15] C：类型转换
来源：http://dali.jinqigufen.top/Article/details/gtigvgswue.html

(double) a / b
来源：http://dali.xylfe.cn/Article/details/gtbrsghqjz.html

[S16] C：位操作置位
来源：http://dali.jlsjyb.cn/Article/details/gtdghuinbu.html

x |= (1 << 3);
来源：http://dali.zycfv.cn/Article/details/gteqwxgsfp.html

[S17] C：安全拼接字符串
来源：http://dali.sufxvd.cn/Article/details/gtvwvtvtsb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xinyue.icu/Article/details/gtwthxjmeb.html

[S18] C：命令行参数
来源：http://dali.cashguo.top/Article/details/gtxufccfvv.html

int main(int argc, char **argv)
来源：http://dali.hongshengwenyu.top/Article/details/gtqdmfnikm.html

[S19] C：快速排序
来源：http://dali.yueranfly.top/Article/details/gttphvctep.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shuidangran.top/Article/details/gtaufldzyw.html

[S20] C：二分查找
来源：http://dali.redwolf501.top/Article/details/gthtdpwfwu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shuidangran.top/Article/details/gtjrvkyetk.html

[S21] C：字符类别判断
来源：http://dali.ydzc1.top/Article/details/gtnindifld.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shzxlz.cn/Article/details/gttqrlczlr.html

[S22] C：字符串转数字
来源：http://dali.yueranfly.top/Article/details/gtqkprwxzr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.chenjidiqi.icu/Article/details/gtswjqmxjl.html

[S23] C：随机数
来源：http://dali.vqdsnc.cn/Article/details/gtraehyloa.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xylfe.cn/Article/details/gtoucphace.html

[S24] C：获取本地时间
来源：http://dali.hysaishi.cn/Article/details/gtxduqovfm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.snrcjt.cn/Article/details/gthjrjkouv.html

[S25] C：内存拷贝
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfklvwkzf.html

memcpy(dst, src, n);
来源：http://dali.zdqjudy.top/Article/details/gtxordnsiq.html

[S26] C：内存清零
来源：http://dali.c1oappe.top/Article/details/gtmpyldkvh.html

memset(a, 0, sizeof a);
来源：http://dali.iojbl.cn/Article/details/gtzjerxdkq.html

[S27] C：定义常量
来源：http://dali.fengsongda.top/Article/details/gtwdpdycvs.html

const double PI = 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gtyviheitx.html

[S28] C：静态变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiudlgilj.html

static int counter = 0;
来源：http://dali.ppjwa.cn/Article/details/gtdnyenftm.html

[S29] C：变参函数
来源：http://dali.tian-w.cn/Article/details/gtmriykqej.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.andypj.xyz/Article/details/gtrzlenfdq.html

[S30] C：头文件保护
来源：http://dali.xziqi.cn/Article/details/gtxmskundi.html

#ifndef X_H
来源：http://dali.daria6918.cn/Article/details/gtqkvtdubb.html

#define X_H
来源：http://dali.wangdashe.top/Article/details/gtuaxebgco.html

#endif
来源：http://dali.gotoacloud.top/Article/details/gtagxkqsag.html

[S31] C++：Hello World
来源：http://dali.gzhubu.top/Article/details/gtjqlmxolp.html

#include <iostream>
来源：http://dali.yanxiufei.cn/Article/details/gtfutxrcrf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.iojbl.cn/Article/details/gtkvrisuld.html

[S32] C++：字符串
来源：http://dali.hysaishi.cn/Article/details/gtojscxvxw.html

std::string s = "hi";  s += "!";
来源：http://dali.jyoumei.cn/Article/details/gtotcedfdo.html

[S33] C++：vector 增删
来源：http://dali.jqgfzy.top/Article/details/gtbqrwtjxi.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cqqwz.cn/Article/details/gtnlnogbtx.html

[S34] C++：遍历 vector
来源：http://dali.nwbrower.top/Article/details/gtjumulsxe.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yonumen.top/Article/details/gthuupvlzo.html

[S35] C++：map
来源：http://dali.iojbl.cn/Article/details/gtxcrhhhta.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sweek.top/Article/details/gthbfupcde.html

[S36] C++：unordered_map
来源：http://dali.yvedp.cn/Article/details/gtlnyuqfga.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuxming.cn/Article/details/gtsqmvfeah.html

[S37] C++：set
来源：http://dali.chenlongwang.top/Article/details/gttoqawhaw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhiwuduotai.top/Article/details/gtagmsmwnq.html

[S38] C++：排序
来源：http://dali.hywenlv.cn/Article/details/gtwbeclcho.html

std::sort(v.begin(), v.end());
来源：http://dali.jinqigufen.top/Article/details/gtncclwlhw.html

[S39] C++：自定义比较器排序
来源：http://dali.cqqwz.cn/Article/details/gtjpawmxmt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hammf.cn/Article/details/gtbumsyngu.html

[S40] C++：查找元素
来源：http://dali.iojbl.cn/Article/details/gtmomdlqgo.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yanxiufei.cn/Article/details/gtlckwssog.html

[S41] C++：类与构造函数
来源：http://dali.ppjwa.cn/Article/details/gttcxhsqzy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cashguo.top/Article/details/gtejfhimpm.html

[S42] C++：继承与虚函数
来源：http://dali.guannengcc.top/Article/details/gtphvzyfxk.html

class B : public Base { public: void f() override {} };
来源：http://dali.ppjwa.cn/Article/details/gttroaayro.html

[S43] C++：智能指针
来源：http://dali.chenlongwang.top/Article/details/gtnzmqiwai.html

auto p = std::make_unique<int>(5);
来源：http://dali.dianchejie.cn/Article/details/gtcnmqtcsx.html

[S44] C++：引用传参
来源：http://dali.xylfe.cn/Article/details/gtvvdyyrit.html

void inc(int &x) { ++x; }
来源：http://dali.cheryme.top/Article/details/gttdjbwqrd.html

[S45] C++：lambda
来源：http://dali.zhoulong.xyz/Article/details/gtstvrbalv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.nwbrower.top/Article/details/gtqxvpvhjq.html

[S46] C++：函数模板
来源：http://dali.haohaochexian.top/Article/details/gtikjwnvak.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hammf.cn/Article/details/gtkjyxwkze.html

[S47] C++：结构化绑定遍历
来源：http://dali.quarkkingdee.top/Article/details/gttlfdzcgr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwueojouw.html

[S48] C++：逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gtyvhhtkdt.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xuetiantiany.cn/Article/details/gtnzldrogq.html

while (std::getline(in, line)) { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyrkfnkct.html

[S49] C++：写文件
来源：http://dali.jinqigfzy.top/Article/details/gtmkhwsxop.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.birdmap.top/Article/details/gtxtmtlkop.html

[S50] C++：格式化数字
来源：http://dali.yuanzhike.top/Article/details/gtvalxwafp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yueranfly.top/Article/details/gtpiykfokz.html

[S51] C++：显式类型转换
来源：http://dali.yj20258.top/Article/details/gtckrmngvf.html

static_cast<double>(a) / b
来源：http://dali.316326.xyz/Article/details/gtvadzxube.html

[S52] C++：const 与 noexcept
来源：http://dali.guannengcc.top/Article/details/gtrnsocihl.html

int size() const noexcept { return n_; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqqmzzayt.html

[S53] C++：移动语义
来源：http://dali.snrcjt.cn/Article/details/gtgihxlxib.html

std::vector<int> w = std::move(v);
来源：http://dali.0kj1m.cn/Article/details/gtgtrzfhvr.html

[S54] C++：异常处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpxcmvbvs.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwwfltvtd.html

[S55] C++：结构化绑定
来源：http://dali.aibaodan.cn/Article/details/gtvnjkbtog.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtmakgsjxl.html

[S56] C++：optional
来源：http://dali.tian-w.cn/Article/details/gtdkwptnes.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gzhubu.top/Article/details/gthlrmsduk.html

[S57] C++：编译期常量
来源：http://dali.dianchejie.cn/Article/details/gtvdkktsyf.html

constexpr int N = 10;
来源：http://dali.havefunace.top/Article/details/gtrowkbpbn.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gttdbdnisn.html

namespace ns { int f() { return 1; } }
来源：http://dali.vqdsnc.cn/Article/details/gtqhptzmmy.html

[S59] C++：静态断言
来源：http://dali.vqdsnc.cn/Article/details/gtvonqfpmg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cashguo.top/Article/details/gtpnvhevdc.html

[S60] C++：遍历并删除元素
来源：http://dali.yongpay.top/Article/details/gttrntwasl.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.meibo888.top/Article/details/gtrzaqcqvi.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtzlgyxrsf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cheryme.top/Article/details/gtdmrmbyzu.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtyrijbddp.html

[T01] Kotlin：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtlshfxmyu.html

println("Hello")
来源：http://dali.xylfe.cn/Article/details/gtrabokcoa.html

[T02] Kotlin：变量
来源：http://dali.ivvv.top/Article/details/gtvywghunw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xuetiantiany.cn/Article/details/gtdovudvcc.html

[T03] Kotlin：字符串模板
来源：http://dali.hnqzz.top/Article/details/gtwoduesbw.html

"值: $b"
来源：http://dali.hammf.cn/Article/details/gtodnlxhii.html

[T04] Kotlin：空安全
来源：http://dali.chenjidiqi.icu/Article/details/gtldlakact.html

val n: String? = null;  n?.length
来源：http://dali.shzxlz.cn/Article/details/gtjpdmcahy.html

[T05] Kotlin：when 表达式
来源：http://dali.andypj.xyz/Article/details/gtlkzeiaiy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.0kj1m.cn/Article/details/gtbwwykbuj.html

[T06] Kotlin：集合映射
来源：http://dali.nanxinkj.top/Article/details/gtnzsqqjth.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ivvv.top/Article/details/gtwvguqzsv.html

[T07] Kotlin：集合过滤
来源：http://dali.tianlin.xyz/Article/details/gtkbjfsnbw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlluykdbb.html

[T08] Kotlin：数据类
来源：http://dali.ppjwa.cn/Article/details/gtahilwywl.html

data class User(val name: String, val age: Int)
来源：http://dali.wangdashe.top/Article/details/gtrctogpzd.html

[T09] Kotlin：扩展函数
来源：http://dali.tanke756.top/Article/details/gtfnswisek.html

fun String.exclaim() = this + "!"
来源：http://dali.shuidangran.top/Article/details/gtribopdnb.html

[T10] Kotlin：默认参数
来源：http://dali.yj20258.top/Article/details/gtspnpxexb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj20258.top/Article/details/gtysnzhsdn.html

[T11] Kotlin：协程
来源：http://dali.tianlin.xyz/Article/details/gtlrwgxubq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shanyushiyangtech.top/Article/details/gtuaegyrlt.html

[T12] Kotlin：解构声明
来源：http://dali.haohaochexian.top/Article/details/gtryjctbpu.html

val (a, b) = Pair(1, 2)
来源：http://dali.ivvv.top/Article/details/gtmyxipjjl.html

[T13] Kotlin：只读 Map
来源：http://dali.daria6918.cn/Article/details/gtupdfsfmx.html

val m = mapOf("a" to 1)
来源：http://dali.gotoacloud.top/Article/details/gtwgntewkx.html

[T14] Kotlin：循环
来源：http://dali.zhengqikj.top/Article/details/gtffsqnqvj.html

for (i in 1..10) println(i)
来源：http://dali.tanke756.top/Article/details/gtkoatwjlc.html

[T15] Kotlin：接口
来源：http://dali.gotoacloud.top/Article/details/gtwavnlszd.html

interface Shape { fun area(): Double }
来源：http://dali.gzhubu.top/Article/details/gtfokcgoht.html

[T16] Swift：Hello World
来源：http://dali.tanke756.top/Article/details/gtgiwkytbl.html

print("Hello")
来源：http://dali.cashguo.top/Article/details/gtludoadph.html

[T17] Swift：变量与常量
来源：http://dali.sysykeji.top/Article/details/gtslbzdiwr.html

var a = 1;  let b = 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrsidumlh.html

[T18] Swift：字符串插值
来源：http://dali.sufxvd.cn/Article/details/gtqpaoyetf.html

"值: \(b)"
来源：http://dali.gogol.net.cn/Article/details/gtiqbadcrd.html

[T19] Swift：可选绑定
来源：http://dali.yj20258.top/Article/details/gtrfptnils.html

if let n = opt { print(n) }
来源：http://dali.pycfn.com/Article/details/gtjyxdkqoh.html

[T20] Swift：数组操作
来源：http://dali.9152youxi.cn/Article/details/gtmbojisev.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.quarkkingdee.top/Article/details/gtfepwicnl.html

[T21] Swift：遍历
来源：http://dali.yvedp.cn/Article/details/gtseblerhd.html

for x in a { print(x) }
来源：http://dali.meibo888.top/Article/details/gtdtydolmw.html

[T22] Swift：字典
来源：http://dali.havefunace.top/Article/details/gtixkldewm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ivvv.top/Article/details/gttxbwbcmr.html

[T23] Swift：函数
来源：http://dali.redwolf501.top/Article/details/gtbqnpfapu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhengqikj.top/Article/details/gttlqpszrx.html

[T24] Swift：闭包
来源：http://dali.jlsjyb.cn/Article/details/gtbyqphcis.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jinqigfzy.top/Article/details/gtcwlohwfv.html

[T25] Swift：结构体
来源：http://dali.shanyushiyangtech.top/Article/details/gtofnbjizb.html

struct P { var x: Int }
来源：http://dali.snrcjt.cn/Article/details/gtgfozywgj.html

[T26] Swift：类与重写
来源：http://dali.nanxuanxn.top/Article/details/gtkpauilxo.html

class A: Base { override func f() {} }
来源：http://dali.pycfn.com/Article/details/gtmbkqszia.html

[T27] Swift：错误处理
来源：http://dali.yuanzhike.top/Article/details/gtzjjoyyer.html

do { try f() } catch { print(error) }
来源：http://dali.xuanzx.com/Article/details/gtrefolmix.html

[T28] Swift：枚举
来源：http://dali.jlsjyb.cn/Article/details/gtqsxhzsgl.html

enum Color { case red, green }
来源：http://dali.wangshuangyany.cn/Article/details/gtjlanbvpl.html

[T29] Swift：guard 提前返回
来源：http://dali.xylfe.cn/Article/details/gtftujtqjh.html

guard let x = opt else { return }
来源：http://dali.ybcxt.top/Article/details/gtrjsbhozs.html

[T30] Swift：协议
来源：http://dali.zdqjudy.top/Article/details/gtdgequmyq.html

protocol Shape { func area() -> Double }
来源：http://dali.bjfxy.top/Article/details/gtzwgjtrxz.html

[T31] Lua：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtjmuelnth.html

print("Hello")
来源：http://dali.jianghu66.top/Article/details/gtrhlbywtv.html

[T32] Lua：局部变量
来源：http://dali.xinyue.icu/Article/details/gtbdforgyx.html

local a = 1
来源：http://dali.yvedp.cn/Article/details/gtripahoxy.html

[T33] Lua：表（数组）
来源：http://dali.fzhhl.top/Article/details/gtfpjxgodl.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.mhx1999.top/Article/details/gttsspxtjf.html

[T34] Lua：遍历表
来源：http://dali.zhoulong.xyz/Article/details/gtmbspakjd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.chenlongwang.top/Article/details/gtcyhcsfys.html

[T35] Lua：字典表
来源：http://dali.andypj.xyz/Article/details/gtbcryvaln.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sxryk.cn/Article/details/gtyavkulzq.html

[T36] Lua：函数
来源：http://dali.zdqjudy.top/Article/details/gtxifgxysc.html

function add(a, b) return a + b end
来源：http://dali.snrcjt.cn/Article/details/gtkwkxhmkx.html

[T37] Lua：字符串拼接
来源：http://dali.zhongyouzk.top/Article/details/gthoigcash.html

"a" .. "b"
来源：http://dali.chenzaomai.com/Article/details/gtbnnyzeuj.html

[T38] Lua：条件
来源：http://dali.ehwqpu.com/Article/details/gtfvrqzhbe.html

if x > 0 then print("正") end
来源：http://dali.shangyingyoupin.top/Article/details/gtdrhdalby.html

[T39] Lua：模式匹配
来源：http://dali.hysaishi.cn/Article/details/gtbvflqcqf.html

string.find(s, "%d+")
来源：http://dali.ybcxt.top/Article/details/gtupzbzwul.html

[T40] Lua：元表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtemjzivgt.html

setmetatable({}, { __index = base })
来源：http://dali.zhoulong.xyz/Article/details/gtzquymhzg.html

[T41] Perl：Hello World
来源：http://dali.jqgfzy.top/Article/details/gthooroxni.html

print "Hello\n";
来源：http://dali.shanyushiyangkeji.top/Article/details/gthrlptabh.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gtwvzdjiwp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhoulong.xyz/Article/details/gtkppjwryr.html

[T43] Perl：字符串插值
来源：http://dali.jinghuilouyu.cn/Article/details/gtemxuyyqq.html

"值: $a"
来源：http://dali.quarkkingdee.top/Article/details/gtzqkecuhz.html

[T44] Perl：条件
来源：http://dali.aibaodan.cn/Article/details/gtauagtdzc.html

if ($a > 0) { print "正"; }
来源：http://dali.iojbl.cn/Article/details/gtwuclvepx.html

[T45] Perl：数组遍历
来源：http://dali.cqqwz.cn/Article/details/gtartcaium.html

for my $x (@arr) { print $x; }
来源：http://dali.tianlin.xyz/Article/details/gtqffgzbhe.html

[T46] Perl：哈希操作
来源：http://dali.yanxiufei.cn/Article/details/gtmmmegcgz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yuanzhike.top/Article/details/gtikhxzoxf.html

[T47] Perl：正则捕获
来源：http://dali.ppjwa.cn/Article/details/gtgozdqzwg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yangfankeji.com/Article/details/gttmqivfrq.html

[T48] Perl：正则替换
来源：http://dali.yonumen.top/Article/details/gtikjipqrp.html

$s =~ s/old/new/g;
来源：http://dali.mhx1999.top/Article/details/gtxctcnwil.html

[T49] Perl：函数
来源：http://dali.bjfxy.top/Article/details/gthrbftula.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xinyue.icu/Article/details/gthegplwry.html

[T50] Perl：逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gtcupcqlgx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gaohongyu789.top/Article/details/gtpowlgcni.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.c1oappe.top/Article/details/gttnxljhrt.html

[T51] Scala：Hello World
来源：http://dali.tanke756.top/Article/details/gtmekiizma.html

println("Hello")
来源：http://dali.shzxlz.cn/Article/details/gtuwojcsdp.html

[T52] Scala：变量
来源：http://dali.birdmap.top/Article/details/gtpiwektdt.html

val a = 1;  var b = 2
来源：http://dali.yangfankeji.com/Article/details/gtdwphuwgk.html

[T53] Scala：字符串插值
来源：http://dali.jianghu66.top/Article/details/gtvblwtyld.html

s"值: $b"
来源：http://dali.shzxlz.cn/Article/details/gtqhdewjrh.html

[T54] Scala：集合映射
来源：http://dali.yongpay.top/Article/details/gtximurxvr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hnqzz.top/Article/details/gtpoaxthim.html

[T55] Scala：集合过滤
来源：http://dali.vqdsnc.cn/Article/details/gtdcaupbjx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.aizwys.cn/Article/details/gtmcahdhsp.html

[T56] Scala：样例类
来源：http://dali.jinqigufen.top/Article/details/gtorplzylw.html

case class User(name: String, age: Int)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtucoaymnw.html

[T57] Scala：模式匹配
来源：http://dali.yj20258.top/Article/details/gtdgydogyn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.c1oappe.top/Article/details/gtwjeutrei.html

[T58] Scala：函数定义
来源：http://dali.ybcxt.top/Article/details/gtcwypjxob.html


<!-- 参考信息 -->