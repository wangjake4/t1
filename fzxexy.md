代发 wailian999

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.redwolf501.top/Article/details/gtuqdihdyy.html

[R56] 远程拷贝
来源：http://dali.gaohongyu789.top/Article/details/gtbqykyuhl.html

scp file user@host:/path/
来源：http://dali.dianchejie.cn/Article/details/gteafxgoud.html

[R57] 远程执行命令
来源：http://dali.wangshuangyany.cn/Article/details/gtdxuahkxt.html

ssh user@host 'uptime'
来源：http://dali.yuanzhike.top/Article/details/gtvboisckd.html

[R58] 下载文件
来源：http://dali.haohaochexian.top/Article/details/gtrcmnbogj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.snrcjt.cn/Article/details/gtxzrvqpox.html

[R59] 发 POST JSON
来源：http://dali.wangdashe.top/Article/details/gtkyiwmldb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ybcxt.top/Article/details/gtjtuytydk.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinqigfzy.top/Article/details/gtprrzuctd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yj20258.top/Article/details/gtdllpugwi.html

[R61] 磁盘占用
来源：http://dali.daxiang520.top/Article/details/gtfrtogbjk.html

df -h;  du -sh *
来源：http://dali.9152youxi.cn/Article/details/gtshelzyku.html

[R62] 找最占空间的文件
来源：http://dali.zycfv.cn/Article/details/gtpyulzatp.html

du -ah . | sort -rh | head -10
来源：http://dali.jlsjyb.cn/Article/details/gtkesfbdan.html

[R63] 内存与进程
来源：http://dali.snrcjt.cn/Article/details/gtxyhinrpv.html

free -h;  ps aux | grep nginx
来源：http://dali.sufxvd.cn/Article/details/gtkpyfrsmx.html

[R64] 结束进程
来源：http://dali.shanyushiyangtech.top/Article/details/gtimrnxyvk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gzhubu.top/Article/details/gtjngadchl.html

[R65] 查看端口占用
来源：http://dali.havefunace.top/Article/details/gtwekzxulh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cheryme.top/Article/details/gtiqmdddum.html

[R66] 定时任务
来源：http://dali.zhiwuduotai.top/Article/details/gthmjcnmqn.html

crontab -e;  crontab -l
来源：http://dali.xziqi.cn/Article/details/gtfhvwjbew.html

[R67] 生成随机十六进制串
来源：http://dali.cdnleiting.top/Article/details/gtnwbizojg.html

openssl rand -hex 16
来源：http://dali.sxryk.cn/Article/details/gtfeoihrgp.html

[R68] 计算文件校验值
来源：http://dali.yj20258888.top/Article/details/gtleycijzy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtplnfhxnf.html

[R69] 生成随机密码
来源：http://dali.yj20258.top/Article/details/gtauikzraw.html

head -c 16 /dev/urandom | base64
来源：http://dali.shuidangran.top/Article/details/gtauzikvfu.html

[R70] 时间戳与互转
来源：http://dali.yj202588.top/Article/details/gtxbzhphqb.html

date +%s;  date -d @1700000000
来源：http://dali.gogol.net.cn/Article/details/gtvopfjfny.html

[R71] 日期格式化
来源：http://dali.vqdsnc.cn/Article/details/gtqvxkjigd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xinyue.icu/Article/details/gthycyiboh.html

[R72] 等待端口就绪
来源：http://dali.yvedp.cn/Article/details/gtzirmsiyy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cucudq.cn/Article/details/gtpzsbvaun.html

[R73] 分割大日志
来源：http://dali.daria6918.cn/Article/details/gtjgysptyp.html

split -l 1000 big.log part_
来源：http://dali.chenjidiqi.icu/Article/details/gtudxxzlpt.html

[R74] 批量重命名
来源：http://dali.xylfe.cn/Article/details/gtxvjzldwy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinqigfzy.top/Article/details/gtdmcmafkc.html

[R75] 导出环境变量
来源：http://dali.vqdsnc.cn/Article/details/gteoscwxsu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.9152youxi.cn/Article/details/gtrrhveika.html

[R76] 使用临时文件
来源：http://dali.0kj1m.cn/Article/details/gtsjlkmdzc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigufen.top/Article/details/gtlgflebvo.html

[R77] 读取用户输入
来源：http://dali.aizwys.cn/Article/details/gthzvirnac.html

read -rp "请输入: " ans
来源：http://dali.jinqigufen.top/Article/details/gtjgzzhdgx.html

[R78] 交互式菜单
来源：http://dali.ppjwa.cn/Article/details/gtuaoltksp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsnouevtr.html

[R79] 解析命令行选项
来源：http://dali.jinghuilouyu.cn/Article/details/gtqidxhrqc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.nwbrower.top/Article/details/gttqctewlf.html

[R80] 查看脚本执行耗时
来源：http://dali.ydzc1.top/Article/details/gtbjgguidr.html

time ./run.sh
来源：http://dali.hysaishi.cn/Article/details/gthuwpatdf.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtyjonmpvy.html

S. C / C++ 专题
来源：http://dali.cucudq.cn/Article/details/gtodhgmxdr.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtlnpiakno.html

[S01] C：Hello World
来源：http://dali.havefunace.top/Article/details/gtfbwmbssb.html

#include <stdio.h>
来源：http://dali.tianlin.xyz/Article/details/gtuxrqpijm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfqqjmsjs.html

[S02] C：变量与格式化输出
来源：http://dali.guowangkeji.top/Article/details/gtkvucwarz.html

int a = 10; printf("%d\n", a);
来源：http://dali.meibo888.top/Article/details/gtmuorjbvr.html

[S03] C：读入整数
来源：http://dali.cdnleiting.top/Article/details/gthfcgwnwa.html

int x; scanf("%d", &x);
来源：http://dali.ehwqpu.com/Article/details/gttnntkxpc.html

[S04] C：字符串复制
来源：http://dali.jqgfzy.top/Article/details/gtjxusfnfs.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cqqwz.cn/Article/details/gtbmuahhcq.html

[S05] C：字符串长度
来源：http://dali.yuanzhike.top/Article/details/gtkapqbpld.html

strlen(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtfbbyypxu.html

[S06] C：字符串比较
来源：http://dali.c1oappe.top/Article/details/gtpsldhgda.html

strcmp(a, b) == 0
来源：http://dali.hysaishi.cn/Article/details/gtjvakpsex.html

[S07] C：数组遍历求和
来源：http://dali.jqgfzy.top/Article/details/gtwsgidjqa.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.guowangkeji.top/Article/details/gthgqofebr.html

[S08] C：动态内存分配与释放
来源：http://dali.guowangkeji.top/Article/details/gtxslrfeov.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.kuanghao11.cn/Article/details/gtlpabondb.html

[S09] C：结构体定义与初始化
来源：http://dali.nanxuanxn.top/Article/details/gtpjxkdgso.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xziqi.cn/Article/details/gtbvacrkmw.html

[S10] C：指针与解引用
来源：http://dali.zhengqikj.top/Article/details/gtloseypnf.html

int *p = &a;  *p = 5;
来源：http://dali.yongpay.top/Article/details/gtdqshqzfr.html

[S11] C：逐行读文件
来源：http://dali.iojbl.cn/Article/details/gtxdbyucuu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yj20258.top/Article/details/gtnrxqubtt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.aizwys.cn/Article/details/gtrkznfvoj.html

fclose(f);
来源：http://dali.feifeiyinyue.top/Article/details/gtczejcuvs.html

[S12] C：写文件
来源：http://dali.meibo888.top/Article/details/gtqvyppsbq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hysaishi.cn/Article/details/gtqttjgvpu.html

[S13] C：宏定义
来源：http://dali.daxiang520.top/Article/details/gtfjkviwuz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.andypj.xyz/Article/details/gthpfyyvqz.html

[S14] C：枚举
来源：http://dali.aibaodan.cn/Article/details/gtovdeozav.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shangyingyoupin.top/Article/details/gtfyufwxfl.html

[S15] C：类型转换
来源：http://dali.ivvv.top/Article/details/gtrrwdkjfd.html

(double) a / b
来源：http://dali.0kj1m.cn/Article/details/gtgxysajmx.html

[S16] C：位操作置位
来源：http://dali.hfpthk.cn/Article/details/gtatktgdfm.html

x |= (1 << 3);
来源：http://dali.nanxuanxn.top/Article/details/gthmtwhyxu.html

[S17] C：安全拼接字符串
来源：http://dali.ybcxt.top/Article/details/gtsvsszcel.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhengqikj.top/Article/details/gtugiulnmm.html

[S18] C：命令行参数
来源：http://dali.cheryme.top/Article/details/gtafesnniz.html

int main(int argc, char **argv)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdigsxzbl.html

[S19] C：快速排序
来源：http://dali.aizwys.cn/Article/details/gtvkhcuhja.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ydzc1.top/Article/details/gtkujfmzmf.html

[S20] C：二分查找
来源：http://dali.yongpay.top/Article/details/gtqlrslyct.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yj20258.top/Article/details/gtcmgpsjym.html

[S21] C：字符类别判断
来源：http://dali.daria6918.cn/Article/details/gtrgtccott.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhengqikj.top/Article/details/gtqabtdtbu.html

[S22] C：字符串转数字
来源：http://dali.chenzaomai.com/Article/details/gtmdbkzcpp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cdnleiting.top/Article/details/gtkbwoxttw.html

[S23] C：随机数
来源：http://dali.daxiang520.top/Article/details/gtxenajnsc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yangfankeji.com/Article/details/gtjhgakpfs.html

[S24] C：获取本地时间
来源：http://dali.316326.xyz/Article/details/gtactwjmnv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cqqwz.cn/Article/details/gtlctwdlgn.html

[S25] C：内存拷贝
来源：http://dali.yueranfly.top/Article/details/gtgknyhhad.html

memcpy(dst, src, n);
来源：http://dali.xziqi.cn/Article/details/gthtauxxfz.html

[S26] C：内存清零
来源：http://dali.xziqi.cn/Article/details/gtfitsrgmk.html

memset(a, 0, sizeof a);
来源：http://dali.feifeiyinyue.top/Article/details/gtgoixadmd.html

[S27] C：定义常量
来源：http://dali.chenzaomai.com/Article/details/gthyuauojd.html

const double PI = 3.14159;
来源：http://dali.xuanzx.com/Article/details/gtinyjcpfp.html

[S28] C：静态变量
来源：http://dali.dianchejie.cn/Article/details/gtkwcfwopm.html

static int counter = 0;
来源：http://dali.cheryme.top/Article/details/gtefkssjdz.html

[S29] C：变参函数
来源：http://dali.fengsongda.top/Article/details/gtdfjkvjyg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.fzhhl.top/Article/details/gtrxpjnulw.html

[S30] C：头文件保护
来源：http://dali.gogol.net.cn/Article/details/gtiwwcxweo.html

#ifndef X_H
来源：http://dali.9152youxi.cn/Article/details/gtfultiykk.html

#define X_H
来源：http://dali.vqdsnc.cn/Article/details/gtwmyqurqh.html

#endif
来源：http://dali.ppjwa.cn/Article/details/gtsbownbsp.html

[S31] C++：Hello World
来源：http://dali.hywenlv.cn/Article/details/gtdsrljohd.html

#include <iostream>
来源：http://dali.hywenlv.cn/Article/details/gtgnwndbes.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yanxiufei.cn/Article/details/gtqyafbzvb.html

[S32] C++：字符串
来源：http://dali.yangfankeji.com/Article/details/gtywkemywh.html

std::string s = "hi";  s += "!";
来源：http://dali.cqqwz.cn/Article/details/gtxdajnhkz.html

[S33] C++：vector 增删
来源：http://dali.snrcjt.cn/Article/details/gtpskgzkjg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cheryme.top/Article/details/gtcbxclbbv.html

[S34] C++：遍历 vector
来源：http://dali.zhongyouzk.top/Article/details/gtlklpepvx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jianghu66.top/Article/details/gtqrakecmw.html

[S35] C++：map
来源：http://dali.hfpthk.cn/Article/details/gtxdjiizju.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guowangkeji.top/Article/details/gtzcbzmgfa.html

[S36] C++：unordered_map
来源：http://dali.gotoacloud.top/Article/details/gtjjkfhldp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.0kj1m.cn/Article/details/gtrrtbcqlf.html

[S37] C++：set
来源：http://dali.ehwqpu.com/Article/details/gtirgfnzhw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.nwbrower.top/Article/details/gtwutprgkz.html

[S38] C++：排序
来源：http://dali.jyoumei.cn/Article/details/gtrdfygema.html

std::sort(v.begin(), v.end());
来源：http://dali.sufxvd.cn/Article/details/gtynkorzcs.html

[S39] C++：自定义比较器排序
来源：http://dali.dianchejie.cn/Article/details/gtisvhcmel.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ybcxt.top/Article/details/gthleedtmj.html

[S40] C++：查找元素
来源：http://dali.feifeiyinyue.top/Article/details/gtaxdznpqv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gogol.net.cn/Article/details/gtqizzqtqn.html

[S41] C++：类与构造函数
来源：http://dali.nanxinkj.top/Article/details/gtgrswwpbd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhengqikj.top/Article/details/gtmioebghe.html

[S42] C++：继承与虚函数
来源：http://dali.cashguo.top/Article/details/gtuvvsixip.html

class B : public Base { public: void f() override {} };
来源：http://dali.yueranfly.top/Article/details/gteqanfikl.html

[S43] C++：智能指针
来源：http://dali.redwolf501.top/Article/details/gtsjlbnwfr.html

auto p = std::make_unique<int>(5);
来源：http://dali.ivvv.top/Article/details/gtxxoarmjx.html

[S44] C++：引用传参
来源：http://dali.tian-w.cn/Article/details/gtjtpbrytt.html

void inc(int &x) { ++x; }
来源：http://dali.gzhubu.top/Article/details/gtvelqbqqv.html

[S45] C++：lambda
来源：http://dali.cqqwz.cn/Article/details/gtucjjkcuc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sufxvd.cn/Article/details/gtaagrslxw.html

[S46] C++：函数模板
来源：http://dali.xinyue.icu/Article/details/gtdjuklknv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gtxxffgkqi.html

[S47] C++：结构化绑定遍历
来源：http://dali.yangfankeji.com/Article/details/gtzsetwsgn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.chenzaomai.com/Article/details/gtgcgylmmx.html

[S48] C++：逐行读文件
来源：http://dali.aizwys.cn/Article/details/gtjstfteoc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zdqjudy.top/Article/details/gtpnvxrrnx.html

while (std::getline(in, line)) { }
来源：http://dali.sweek.top/Article/details/gtfrrizuvm.html

[S49] C++：写文件
来源：http://dali.nanxinkj.top/Article/details/gtgubrsjyx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sweek.top/Article/details/gtmawwzyua.html

[S50] C++：格式化数字
来源：http://dali.tianlin.xyz/Article/details/gtniljmohp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhengqikj.top/Article/details/gtkaegizhn.html

[S51] C++：显式类型转换
来源：http://dali.xziqi.cn/Article/details/gthofnmsek.html

static_cast<double>(a) / b
来源：http://dali.sufxvd.cn/Article/details/gtpbizeebj.html

[S52] C++：const 与 noexcept
来源：http://dali.yuanzhike.top/Article/details/gtsfbpfkvn.html

int size() const noexcept { return n_; }
来源：http://dali.zhoulong.xyz/Article/details/gtcvhlzkui.html

[S53] C++：移动语义
来源：http://dali.guowangkeji.top/Article/details/gtsnijcmiu.html

std::vector<int> w = std::move(v);
来源：http://dali.sysykeji.top/Article/details/gtbidrtnia.html

[S54] C++：异常处理
来源：http://dali.yongpay.top/Article/details/gtakvmppoc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yj202588.top/Article/details/gtegeonbwd.html

[S55] C++：结构化绑定
来源：http://dali.mhx1999.top/Article/details/gtzwphlysh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.havefunace.top/Article/details/gtdgneuunu.html

[S56] C++：optional
来源：http://dali.sweek.top/Article/details/gthxffzhyo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.feifeiyinyue.top/Article/details/gtsezlcnqi.html

[S57] C++：编译期常量
来源：http://dali.quarkkingdee.top/Article/details/gtzoepbvrd.html

constexpr int N = 10;
来源：http://dali.guowangkeji.top/Article/details/gtlovqubst.html

[S58] C++：命名空间
来源：http://dali.yanxiufei.cn/Article/details/gtrkvwxjce.html

namespace ns { int f() { return 1; } }
来源：http://dali.jyoumei.cn/Article/details/gttcoyruft.html

[S59] C++：静态断言
来源：http://dali.hysaishi.cn/Article/details/gttanvjxbf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jqgfzy.top/Article/details/gtoacjnrtf.html

[S60] C++：遍历并删除元素
来源：http://dali.cheryme.top/Article/details/gtfwfzrmca.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.pengpengdd.cyou/Article/details/gtzpeouupy.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gttljoipjs.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxsqyddzu.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtvpopjhqi.html

[T01] Kotlin：Hello World
来源：http://dali.yj202588.top/Article/details/gtqrjtigix.html

println("Hello")
来源：http://dali.yanxiufei.cn/Article/details/gtipusovwf.html

[T02] Kotlin：变量
来源：http://dali.daxiang520.top/Article/details/gtcnjvayts.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.sxryk.cn/Article/details/gtamttxkap.html

[T03] Kotlin：字符串模板
来源：http://dali.svipenyu.cn/Article/details/gtlnpbdcok.html

"值: $b"
来源：http://dali.xinyue.icu/Article/details/gtjpxsutbx.html

[T04] Kotlin：空安全
来源：http://dali.ehwqpu.com/Article/details/gtummdqjjf.html

val n: String? = null;  n?.length
来源：http://dali.aibaodan.cn/Article/details/gtefulfuba.html

[T05] Kotlin：when 表达式
来源：http://dali.guowangkeji.top/Article/details/gtaixlypyf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.havefunace.top/Article/details/gtudcuhwco.html

[T06] Kotlin：集合映射
来源：http://dali.zhoulong.xyz/Article/details/gtplquxwip.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhixingplan.top/Article/details/gtpedofuts.html

[T07] Kotlin：集合过滤
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbrnityzm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhongyouzk.top/Article/details/gtuqbksxtg.html

[T08] Kotlin：数据类
来源：http://dali.tianlin.xyz/Article/details/gtzwhijihf.html

data class User(val name: String, val age: Int)
来源：http://dali.hongshengwenyu.top/Article/details/gtyerrcmuv.html

[T09] Kotlin：扩展函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtucfsguhc.html

fun String.exclaim() = this + "!"
来源：http://dali.ybcxt.top/Article/details/gtvbeyzccc.html

[T10] Kotlin：默认参数
来源：http://dali.yueranfly.top/Article/details/gtsmlnhaaj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shzxlz.cn/Article/details/gtpxvkarlb.html

[T11] Kotlin：协程
来源：http://dali.cheryme.top/Article/details/gtmpjvxkpf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.daxiang520.top/Article/details/gtfxwvwdbm.html

[T12] Kotlin：解构声明
来源：http://dali.hfpthk.cn/Article/details/gttcytilzd.html

val (a, b) = Pair(1, 2)
来源：http://dali.guannengcc.top/Article/details/gtqepptueo.html

[T13] Kotlin：只读 Map
来源：http://dali.iojbl.cn/Article/details/gthvcffsjz.html

val m = mapOf("a" to 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtcnqsyusk.html

[T14] Kotlin：循环
来源：http://dali.yj202588.top/Article/details/gttliaakjj.html

for (i in 1..10) println(i)
来源：http://dali.zhengqikj.top/Article/details/gtyjnbdzar.html

[T15] Kotlin：接口
来源：http://dali.yongpay.top/Article/details/gtekgcsaen.html

interface Shape { fun area(): Double }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnxbhsoxd.html

[T16] Swift：Hello World
来源：http://dali.sysykeji.top/Article/details/gtcwsnukev.html

print("Hello")
来源：http://dali.shangyingyoupin.top/Article/details/gtdpkzgogs.html

[T17] Swift：变量与常量
来源：http://dali.andypj.xyz/Article/details/gtaginrbbn.html

var a = 1;  let b = 2
来源：http://dali.hnxiangtu.top/Article/details/gtxavhkljj.html

[T18] Swift：字符串插值
来源：http://dali.chenlongwang.top/Article/details/gtdyswqolu.html

"值: \(b)"
来源：http://dali.cqqwz.cn/Article/details/gtjalvzjzw.html

[T19] Swift：可选绑定
来源：http://dali.birdmap.top/Article/details/gtuotfhtik.html

if let n = opt { print(n) }
来源：http://dali.chenzaomai.com/Article/details/gtxfweashx.html

[T20] Swift：数组操作
来源：http://dali.snrcjt.cn/Article/details/gtnnuoakug.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ehwqpu.com/Article/details/gtghkewoxt.html

[T21] Swift：遍历
来源：http://dali.daxiang520.top/Article/details/gtwnjpvjoc.html

for x in a { print(x) }
来源：http://dali.yonumen.top/Article/details/gtsqxtosll.html

[T22] Swift：字典
来源：http://dali.chenjidiqi.icu/Article/details/gtzsydxlga.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.snrcjt.cn/Article/details/gtepnxegrd.html

[T23] Swift：函数
来源：http://dali.hysaishi.cn/Article/details/gtwrkxvwkq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sweek.top/Article/details/gtfvtfqfvj.html

[T24] Swift：闭包
来源：http://dali.daria6918.cn/Article/details/gtrilwdauf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdtnpjqyl.html

[T25] Swift：结构体
来源：http://dali.jyoumei.cn/Article/details/gthimclvvt.html

struct P { var x: Int }
来源：http://dali.cheryme.top/Article/details/gtkykwsakj.html

[T26] Swift：类与重写
来源：http://dali.meibo888.top/Article/details/gtrwrrufoa.html

class A: Base { override func f() {} }
来源：http://dali.havefunace.top/Article/details/gthbzickqp.html

[T27] Swift：错误处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfsgzlukn.html

do { try f() } catch { print(error) }
来源：http://dali.hywenlv.cn/Article/details/gtiawothbg.html

[T28] Swift：枚举
来源：http://dali.pengpengdd.cyou/Article/details/gttjbwyzlw.html

enum Color { case red, green }
来源：http://dali.ybcxt.top/Article/details/gtzqkdwecr.html

[T29] Swift：guard 提前返回
来源：http://dali.ivvv.top/Article/details/gthcjtzvww.html

guard let x = opt else { return }
来源：http://dali.iojbl.cn/Article/details/gtwuutnmbq.html

[T30] Swift：协议
来源：http://dali.xylfe.cn/Article/details/gtvyulphbi.html

protocol Shape { func area() -> Double }
来源：http://dali.yj202588.top/Article/details/gtbdadqemm.html

[T31] Lua：Hello World
来源：http://dali.cashguo.top/Article/details/gtzwhlenba.html

print("Hello")
来源：http://dali.tian-w.cn/Article/details/gtvrktuwnr.html

[T32] Lua：局部变量
来源：http://dali.feifeiyinyue.top/Article/details/gtvubieqvo.html

local a = 1
来源：http://dali.sysykeji.top/Article/details/gtownknokr.html

[T33] Lua：表（数组）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwcdzvwjj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xuanzx.com/Article/details/gthvkfgtpw.html

[T34] Lua：遍历表
来源：http://dali.iojbl.cn/Article/details/gtomntvjgb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.redwolf501.top/Article/details/gtptqyefbf.html

[T35] Lua：字典表
来源：http://dali.daxiang520.top/Article/details/gtdpxmxabd.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yj20258888.top/Article/details/gtvulfeyde.html

[T36] Lua：函数
来源：http://dali.tanke756.top/Article/details/gtvhhscuuy.html

function add(a, b) return a + b end
来源：http://dali.hnqzz.top/Article/details/gthutbgyxt.html

[T37] Lua：字符串拼接
来源：http://dali.mhx1999.top/Article/details/gtrzzifvdw.html

"a" .. "b"
来源：http://dali.hammf.cn/Article/details/gtsnlhksur.html

[T38] Lua：条件
来源：http://dali.gogol.net.cn/Article/details/gtdumsmyra.html

if x > 0 then print("正") end
来源：http://dali.snrcjt.cn/Article/details/gtahfcfsln.html

[T39] Lua：模式匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtkeeipgwo.html

string.find(s, "%d+")
来源：http://dali.quarkkingdee.top/Article/details/gtfkzfiebl.html

[T40] Lua：元表
来源：http://dali.wangshuangyany.cn/Article/details/gthlqdvefl.html

setmetatable({}, { __index = base })
来源：http://dali.svipenyu.cn/Article/details/gtqrnwzntb.html

[T41] Perl：Hello World
来源：http://dali.0kj1m.cn/Article/details/gtrkxuenrj.html

print "Hello\n";
来源：http://dali.bjfxy.top/Article/details/gtpwctziup.html

[T42] Perl：变量类型
来源：http://dali.aizwys.cn/Article/details/gtmhagtmem.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.0kj1m.cn/Article/details/gtcpikaoog.html

[T43] Perl：字符串插值
来源：http://dali.ehwqpu.com/Article/details/gttsbfarip.html

"值: $a"
来源：http://dali.shangyingyoupin.top/Article/details/gtypysssdq.html

[T44] Perl：条件
来源：http://dali.aizwys.cn/Article/details/gtfyosefxj.html

if ($a > 0) { print "正"; }
来源：http://dali.yj202588.top/Article/details/gtatvvdnzb.html

[T45] Perl：数组遍历
来源：http://dali.sxryk.cn/Article/details/gtjnsijtwz.html

for my $x (@arr) { print $x; }
来源：http://dali.xinyue.icu/Article/details/gttntaakfb.html

[T46] Perl：哈希操作
来源：http://dali.dashuyun.cn/Article/details/gtppfmcpzf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.fzhhl.top/Article/details/gthdqopjph.html

[T47] Perl：正则捕获
来源：http://dali.zdqjudy.top/Article/details/gtbikgeqic.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.meibo888.top/Article/details/gtjyuejjop.html

[T48] Perl：正则替换
来源：http://dali.feifeiyinyue.top/Article/details/gtndbsxzsm.html

$s =~ s/old/new/g;
来源：http://dali.yj20258.top/Article/details/gtxgdpjspm.html

[T49] Perl：函数
来源：http://dali.daxiang520.top/Article/details/gtfczqgdhd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jinqigfzy.top/Article/details/gtvrzalpap.html

[T50] Perl：逐行读文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtiquqfswr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhoulong.xyz/Article/details/gttxowozmz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.sufxvd.cn/Article/details/gtsqmvyfle.html

[T51] Scala：Hello World
来源：http://dali.xuanzx.com/Article/details/gtqfidhndi.html

println("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gtgnxbwmsm.html

[T52] Scala：变量
来源：http://dali.chenlongwang.top/Article/details/gtrrbbnmfm.html

val a = 1;  var b = 2
来源：http://dali.cucudq.cn/Article/details/gtekzzyvsh.html

[T53] Scala：字符串插值
来源：http://dali.chenzaomai.com/Article/details/gtafajrxry.html

s"值: $b"
来源：http://dali.aizwys.cn/Article/details/gtcdsopbfi.html

[T54] Scala：集合映射
来源：http://dali.shuidangran.top/Article/details/gtjfzcgkep.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhixingplan.top/Article/details/gtedffhmck.html

[T55] Scala：集合过滤
来源：http://dali.chenzaomai.com/Article/details/gtmufgfzri.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.guowangkeji.top/Article/details/gttsbapklo.html

[T56] Scala：样例类
来源：http://dali.316326.xyz/Article/details/gtxxtijjps.html

case class User(name: String, age: Int)
来源：http://dali.hywenlv.cn/Article/details/gtrfayjnmi.html

[T57] Scala：模式匹配
来源：http://dali.gogol.net.cn/Article/details/gthlwxejvh.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.0kj1m.cn/Article/details/gtkzlqzpir.html

[T58] Scala：函数定义
来源：http://dali.zhiwuduotai.top/Article/details/gtkxpdnlwx.html


<!-- 参考信息 -->