代发 wailian999

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ivvv.top/Article/details/gtzkpynwws.html

[R56] 远程拷贝
来源：http://dali.redwolf501.top/Article/details/gtxptrkqxd.html

scp file user@host:/path/
来源：http://dali.ppjwa.cn/Article/details/gtcxvotnyn.html

[R57] 远程执行命令
来源：http://dali.jinqigufen.top/Article/details/gtyrgtotnd.html

ssh user@host 'uptime'
来源：http://dali.shangyingyoupin.top/Article/details/gtzahxmayb.html

[R58] 下载文件
来源：http://dali.tian-w.cn/Article/details/gtuaunkdpz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jlsjyb.cn/Article/details/gtapvsyxkw.html

[R59] 发 POST JSON
来源：http://dali.dashuyun.cn/Article/details/gtsptlyfpc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.vqdsnc.cn/Article/details/gtkyyxbkxd.html

[R60] 只看 HTTP 状态码
来源：http://dali.nanxuanxn.top/Article/details/gtnnpxhbyh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jiagoushi.top/Article/details/gtfohakcyg.html

[R61] 磁盘占用
来源：http://dali.andypj.xyz/Article/details/gtsbedqjjf.html

df -h;  du -sh *
来源：http://dali.jinqigfzy.top/Article/details/gtuhbtvizr.html

[R62] 找最占空间的文件
来源：http://dali.andypj.xyz/Article/details/gtezjpzjjp.html

du -ah . | sort -rh | head -10
来源：http://dali.0kj1m.cn/Article/details/gthcwbkiyb.html

[R63] 内存与进程
来源：http://dali.daxiang520.top/Article/details/gtefoirtwf.html

free -h;  ps aux | grep nginx
来源：http://dali.guowangkeji.top/Article/details/gthnghiijx.html

[R64] 结束进程
来源：http://dali.yongpay.top/Article/details/gtadawubma.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jlsjyb.cn/Article/details/gtgncogmmp.html

[R65] 查看端口占用
来源：http://dali.daria6918.cn/Article/details/gtmmbpzoxk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.0kj1m.cn/Article/details/gtdqchknhw.html

[R66] 定时任务
来源：http://dali.jlsjyb.cn/Article/details/gtihesatnp.html

crontab -e;  crontab -l
来源：http://dali.gaohongyu789.top/Article/details/gttdpyfqyv.html

[R67] 生成随机十六进制串
来源：http://dali.sxryk.cn/Article/details/gttkisfodf.html

openssl rand -hex 16
来源：http://dali.gzhubu.top/Article/details/gtzazmpmuk.html

[R68] 计算文件校验值
来源：http://dali.jqgufenzy.top/Article/details/gthhmlgwuy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.quarkkingdee.top/Article/details/gttmoncoug.html

[R69] 生成随机密码
来源：http://dali.daria6918.cn/Article/details/gtrkbzgopf.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnwdcohvg.html

[R70] 时间戳与互转
来源：http://dali.ehwqpu.com/Article/details/gtpkxxpjhn.html

date +%s;  date -d @1700000000
来源：http://dali.aibaodan.cn/Article/details/gtljotttuf.html

[R71] 日期格式化
来源：http://dali.zycfv.cn/Article/details/gtrshdhsdm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jlsjyb.cn/Article/details/gtqrykaect.html

[R72] 等待端口就绪
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoqirlnpx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hongshengwenyu.top/Article/details/gtrtmrckwa.html

[R73] 分割大日志
来源：http://dali.yuanzhike.top/Article/details/gtmtxyubik.html

split -l 1000 big.log part_
来源：http://dali.yongpay.top/Article/details/gtjskqbemr.html

[R74] 批量重命名
来源：http://dali.shanyushiyangtech.top/Article/details/gtlqoeycge.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ppjwa.cn/Article/details/gtctzhnwsm.html

[R75] 导出环境变量
来源：http://dali.jlsjyb.cn/Article/details/gtuyfftffl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.316326.xyz/Article/details/gtirogpcka.html

[R76] 使用临时文件
来源：http://dali.sysykeji.top/Article/details/gtzfkhqbxm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yongpay.top/Article/details/gtsvwxyimk.html

[R77] 读取用户输入
来源：http://dali.zhongyouzk.top/Article/details/gtoaeikuyi.html

read -rp "请输入: " ans
来源：http://dali.wangshuangyany.cn/Article/details/gtduqltplx.html

[R78] 交互式菜单
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvotniehe.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cheryme.top/Article/details/gtjuooqwjb.html

[R79] 解析命令行选项
来源：http://dali.xuanzx.com/Article/details/gteibpplyr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.fengsongda.top/Article/details/gtcaipgnii.html

[R80] 查看脚本执行耗时
来源：http://dali.guannengcc.top/Article/details/gtvhmupipg.html

time ./run.sh
来源：http://dali.wangshuangyany.cn/Article/details/gtltrpvmwn.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtjzcdazgb.html

S. C / C++ 专题
来源：http://dali.snrcjt.cn/Article/details/gtjnpavhut.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkwlzwmdv.html

[S01] C：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtbkthzooq.html

#include <stdio.h>
来源：http://dali.yongpay.top/Article/details/gtfkurxbiu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ivvv.top/Article/details/gtrzfxuyew.html

[S02] C：变量与格式化输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiqqbiyrb.html

int a = 10; printf("%d\n", a);
来源：http://dali.sysykeji.top/Article/details/gtygxtzlmj.html

[S03] C：读入整数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnpexkpho.html

int x; scanf("%d", &x);
来源：http://dali.xuanzx.com/Article/details/gtmdpgvhhx.html

[S04] C：字符串复制
来源：http://dali.hnxiangtu.top/Article/details/gttobdsdgc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yuanzhike.top/Article/details/gtzaoktwvc.html

[S05] C：字符串长度
来源：http://dali.aizwys.cn/Article/details/gtsqcflvoy.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gtdgillbtc.html

[S06] C：字符串比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzzxdqcqd.html

strcmp(a, b) == 0
来源：http://dali.xuetiantiany.cn/Article/details/gtfvaegrsr.html

[S07] C：数组遍历求和
来源：http://dali.hammf.cn/Article/details/gtpniczxcq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zdqjudy.top/Article/details/gttskciztj.html

[S08] C：动态内存分配与释放
来源：http://dali.cdnleiting.top/Article/details/gtxlzgcsoh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sufxvd.cn/Article/details/gtgocwwlzs.html

[S09] C：结构体定义与初始化
来源：http://dali.yangfankeji.com/Article/details/gtfonxzkrq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gtogprdntx.html

[S10] C：指针与解引用
来源：http://dali.yueranfly.top/Article/details/gtkoajfkxf.html

int *p = &a;  *p = 5;
来源：http://dali.0kj1m.cn/Article/details/gtkkjkoora.html

[S11] C：逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gtwjgeuufy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.dashuyun.cn/Article/details/gtilzrarqv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shuidangran.top/Article/details/gtfiwzkuft.html

fclose(f);
来源：http://dali.nanxinkj.top/Article/details/gtjmvkssfk.html

[S12] C：写文件
来源：http://dali.sxryk.cn/Article/details/gtdrukffax.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.guannengcc.top/Article/details/gtadqyrmug.html

[S13] C：宏定义
来源：http://dali.hammf.cn/Article/details/gtbanorlfh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinqigfzy.top/Article/details/gtisrhceza.html

[S14] C：枚举
来源：http://dali.jianghu66.top/Article/details/gteiovqrup.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xuanzx.com/Article/details/gtcmuuncxs.html

[S15] C：类型转换
来源：http://dali.yonumen.top/Article/details/gtsznvjlkb.html

(double) a / b
来源：http://dali.redwolf501.top/Article/details/gtmgqlrudo.html

[S16] C：位操作置位
来源：http://dali.yongpay.top/Article/details/gtcgynippf.html

x |= (1 << 3);
来源：http://dali.aibaodan.cn/Article/details/gtxlebjgfj.html

[S17] C：安全拼接字符串
来源：http://dali.kuanghao11.cn/Article/details/gtijvuqpba.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.andypj.xyz/Article/details/gtgdaupgls.html

[S18] C：命令行参数
来源：http://dali.zhengqikj.top/Article/details/gtuxghepfn.html

int main(int argc, char **argv)
来源：http://dali.hysaishi.cn/Article/details/gtvuxnaloy.html

[S19] C：快速排序
来源：http://dali.tianlin.xyz/Article/details/gtgtqbelwf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangtech.top/Article/details/gtrtifglxa.html

[S20] C：二分查找
来源：http://dali.dashuyun.cn/Article/details/gtfzljblnb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cdnleiting.top/Article/details/gtwcfbqrae.html

[S21] C：字符类别判断
来源：http://dali.jinghuilouyu.cn/Article/details/gtjssjaarc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.chenjidiqi.icu/Article/details/gthbienamf.html

[S22] C：字符串转数字
来源：http://dali.aizwys.cn/Article/details/gtmrykwngb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xinyue.icu/Article/details/gtiwwfsedd.html

[S23] C：随机数
来源：http://dali.sxryk.cn/Article/details/gtimtohtsx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.havefunace.top/Article/details/gtggcbfska.html

[S24] C：获取本地时间
来源：http://dali.birdmap.top/Article/details/gtmqdkjwjj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.haohaochexian.top/Article/details/gtaaubsqat.html

[S25] C：内存拷贝
来源：http://dali.vqdsnc.cn/Article/details/gtcnzagjqj.html

memcpy(dst, src, n);
来源：http://dali.mhx1999.top/Article/details/gtnwlbnlgq.html

[S26] C：内存清零
来源：http://dali.gogol.net.cn/Article/details/gtddftyntm.html

memset(a, 0, sizeof a);
来源：http://dali.nwbrower.top/Article/details/gthudtibch.html

[S27] C：定义常量
来源：http://dali.cqqwz.cn/Article/details/gtcmybgctb.html

const double PI = 3.14159;
来源：http://dali.xuanzx.com/Article/details/gtvatmzygg.html

[S28] C：静态变量
来源：http://dali.gotoacloud.top/Article/details/gtuhuyvmwl.html

static int counter = 0;
来源：http://dali.zhixingplan.top/Article/details/gtaxcnngth.html

[S29] C：变参函数
来源：http://dali.tanke756.top/Article/details/gtmmfcuamy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yanxiufei.cn/Article/details/gtwxbypjiw.html

[S30] C：头文件保护
来源：http://dali.cashguo.top/Article/details/gtdwjnckyy.html

#ifndef X_H
来源：http://dali.tanke756.top/Article/details/gtpjzxdcyu.html

#define X_H
来源：http://dali.ehwqpu.com/Article/details/gtwenoehxt.html

#endif
来源：http://dali.quarkkingdee.top/Article/details/gtqcuferqu.html

[S31] C++：Hello World
来源：http://dali.fzhhl.top/Article/details/gtyqyrkpvz.html

#include <iostream>
来源：http://dali.zhixingplan.top/Article/details/gtjwkctqrh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ehwqpu.com/Article/details/gtkadmhiup.html

[S32] C++：字符串
来源：http://dali.sufxvd.cn/Article/details/gtuvjpnjev.html

std::string s = "hi";  s += "!";
来源：http://dali.yvedp.cn/Article/details/gttxhumivl.html

[S33] C++：vector 增删
来源：http://dali.hysaishi.cn/Article/details/gteexhpraz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwqllfoxz.html

[S34] C++：遍历 vector
来源：http://dali.yuxming.cn/Article/details/gtshyayiff.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.smart0.xyz/Article/details/gtcctxienn.html

[S35] C++：map
来源：http://dali.nwbrower.top/Article/details/gtydwplcfa.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gzhubu.top/Article/details/gtnwxjulft.html

[S36] C++：unordered_map
来源：http://dali.gzhubu.top/Article/details/gtwupuwoln.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.smart0.xyz/Article/details/gteyyjenhz.html

[S37] C++：set
来源：http://dali.bjfxy.top/Article/details/gtsezswyqh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.nwbrower.top/Article/details/gtanjqdnbw.html

[S38] C++：排序
来源：http://dali.xuetiantiany.cn/Article/details/gtismyscrc.html

std::sort(v.begin(), v.end());
来源：http://dali.cashguo.top/Article/details/gtkiitktyy.html

[S39] C++：自定义比较器排序
来源：http://dali.wangdashe.top/Article/details/gtdeshnjcw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hongshengwenyu.top/Article/details/gtadqmsare.html

[S40] C++：查找元素
来源：http://dali.jinqigfzy.top/Article/details/gtmlnbtizx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.kuanghao11.cn/Article/details/gtzpfainsh.html

[S41] C++：类与构造函数
来源：http://dali.tianlin.xyz/Article/details/gtpuubylni.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuigmxqwu.html

[S42] C++：继承与虚函数
来源：http://dali.hywenlv.cn/Article/details/gtvwwgqveh.html

class B : public Base { public: void f() override {} };
来源：http://dali.aibaodan.cn/Article/details/gtrslgdxdx.html

[S43] C++：智能指针
来源：http://dali.mhx1999.top/Article/details/gtssgklcns.html

auto p = std::make_unique<int>(5);
来源：http://dali.316326.xyz/Article/details/gtihmfwkdk.html

[S44] C++：引用传参
来源：http://dali.hysaishi.cn/Article/details/gtzbaqaord.html

void inc(int &x) { ++x; }
来源：http://dali.ppjwa.cn/Article/details/gtzaihdouj.html

[S45] C++：lambda
来源：http://dali.wangdashe.top/Article/details/gtvtyggjvw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.smart0.xyz/Article/details/gtocgbdbcy.html

[S46] C++：函数模板
来源：http://dali.kuanghao11.cn/Article/details/gtlhrxtbtg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xuanzx.com/Article/details/gtuoxexcug.html

[S47] C++：结构化绑定遍历
来源：http://dali.kuanghao11.cn/Article/details/gtdnkaioui.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jianghu66.top/Article/details/gtdtcfoukw.html

[S48] C++：逐行读文件
来源：http://dali.guowangkeji.top/Article/details/gtweerrgac.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yanxiufei.cn/Article/details/gtngnopktl.html

while (std::getline(in, line)) { }
来源：http://dali.bjfxy.top/Article/details/gtxytusiej.html

[S49] C++：写文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtcvdkufia.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xinyue.icu/Article/details/gtjaovruhf.html

[S50] C++：格式化数字
来源：http://dali.c1oappe.top/Article/details/gtwyzuidzc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.dashuyun.cn/Article/details/gtpdscpkau.html

[S51] C++：显式类型转换
来源：http://dali.yvedp.cn/Article/details/gtxwmelnak.html

static_cast<double>(a) / b
来源：http://dali.shanyushiyangtech.top/Article/details/gtoltpdmun.html

[S52] C++：const 与 noexcept
来源：http://dali.yj20258.top/Article/details/gtkzxpucza.html

int size() const noexcept { return n_; }
来源：http://dali.guowangkeji.top/Article/details/gtbqndbyyc.html

[S53] C++：移动语义
来源：http://dali.dianchejie.cn/Article/details/gtjznumfdv.html

std::vector<int> w = std::move(v);
来源：http://dali.yj202588.top/Article/details/gtgldmaoje.html

[S54] C++：异常处理
来源：http://dali.svipenyu.cn/Article/details/gtnjwxptxt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gotoacloud.top/Article/details/gtpjqilupq.html

[S55] C++：结构化绑定
来源：http://dali.hnxiangtu.top/Article/details/gtmdpcqngd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cheryme.top/Article/details/gtsoeeitim.html

[S56] C++：optional
来源：http://dali.daria6918.cn/Article/details/gtvvmlejyo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yangfankeji.com/Article/details/gttvrboirt.html

[S57] C++：编译期常量
来源：http://dali.haohaochexian.top/Article/details/gtphhujzyo.html

constexpr int N = 10;
来源：http://dali.daria6918.cn/Article/details/gteexygram.html

[S58] C++：命名空间
来源：http://dali.cashguo.top/Article/details/gtopyphyrp.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhiwuduotai.top/Article/details/gtyumaeybq.html

[S59] C++：静态断言
来源：http://dali.hammf.cn/Article/details/gtnfsjwnjm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.birdmap.top/Article/details/gtcprwvvas.html

[S60] C++：遍历并删除元素
来源：http://dali.shuidangran.top/Article/details/gtovufuege.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.c1oappe.top/Article/details/gtjciuuhpw.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtbriqrnyf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cheryme.top/Article/details/gtrpfgitrv.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtyzcvqqvt.html

[T01] Kotlin：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtyczaqhiq.html

println("Hello")
来源：http://dali.nanxuanxn.top/Article/details/gtljvtrgmv.html

[T02] Kotlin：变量
来源：http://dali.yueranfly.top/Article/details/gtgwcbjofc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwljjhzpp.html

[T03] Kotlin：字符串模板
来源：http://dali.ppjwa.cn/Article/details/gtalxcnszv.html

"值: $b"
来源：http://dali.sxryk.cn/Article/details/gthfnqhpmx.html

[T04] Kotlin：空安全
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbmajxdqc.html

val n: String? = null;  n?.length
来源：http://dali.9152youxi.cn/Article/details/gtpefmpflr.html

[T05] Kotlin：when 表达式
来源：http://dali.havefunace.top/Article/details/gtoubhydjx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jlsjyb.cn/Article/details/gtjnbmwhba.html

[T06] Kotlin：集合映射
来源：http://dali.yonumen.top/Article/details/gttrlkhxwi.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.guannengcc.top/Article/details/gtyihpltxv.html

[T07] Kotlin：集合过滤
来源：http://dali.jinqigufen.top/Article/details/gthbgzhvnr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hongshengwenyu.top/Article/details/gtfolecsqa.html

[T08] Kotlin：数据类
来源：http://dali.havefunace.top/Article/details/gteyclxlbs.html

data class User(val name: String, val age: Int)
来源：http://dali.cheryme.top/Article/details/gtpalfvawy.html

[T09] Kotlin：扩展函数
来源：http://dali.9152youxi.cn/Article/details/gtsrrkembo.html

fun String.exclaim() = this + "!"
来源：http://dali.guowangkeji.top/Article/details/gtywsksnfk.html

[T10] Kotlin：默认参数
来源：http://dali.yuanzhike.top/Article/details/gtswkvwojo.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.sysykeji.top/Article/details/gtavqqcbye.html

[T11] Kotlin：协程
来源：http://dali.chenjidiqi.icu/Article/details/gtowxfzbex.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sysykeji.top/Article/details/gtuxtqcdus.html

[T12] Kotlin：解构声明
来源：http://dali.yj20258888.top/Article/details/gttmqoxvzv.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhoulong.xyz/Article/details/gtyltmdyso.html

[T13] Kotlin：只读 Map
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrvpivzmw.html

val m = mapOf("a" to 1)
来源：http://dali.xziqi.cn/Article/details/gtacpdkhae.html

[T14] Kotlin：循环
来源：http://dali.yueranfly.top/Article/details/gtywlgseiv.html

for (i in 1..10) println(i)
来源：http://dali.jqgufenzy.top/Article/details/gtmropnoov.html

[T15] Kotlin：接口
来源：http://dali.cheryme.top/Article/details/gtvsjirkjh.html

interface Shape { fun area(): Double }
来源：http://dali.xuetiantiany.cn/Article/details/gtqpntqmss.html

[T16] Swift：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtdlsptrtp.html

print("Hello")
来源：http://dali.dashuyun.cn/Article/details/gtsrkanadz.html

[T17] Swift：变量与常量
来源：http://dali.havefunace.top/Article/details/gtbbyxnlph.html

var a = 1;  let b = 2
来源：http://dali.guowangkeji.top/Article/details/gtnvkkuxbh.html

[T18] Swift：字符串插值
来源：http://dali.yj20258888.top/Article/details/gtwsijxafu.html

"值: \(b)"
来源：http://dali.chenlongwang.top/Article/details/gttefpkmog.html

[T19] Swift：可选绑定
来源：http://dali.hammf.cn/Article/details/gtobuewhdp.html

if let n = opt { print(n) }
来源：http://dali.xuanzx.com/Article/details/gtotpxrwey.html

[T20] Swift：数组操作
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttiadvhmv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jiagoushi.top/Article/details/gtoukqvams.html

[T21] Swift：遍历
来源：http://dali.hywenlv.cn/Article/details/gtamqgjzxe.html

for x in a { print(x) }
来源：http://dali.yueranfly.top/Article/details/gtpjepzmuh.html

[T22] Swift：字典
来源：http://dali.ydzc1.top/Article/details/gtqskjbkul.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xuanzx.com/Article/details/gtxshkhkiq.html

[T23] Swift：函数
来源：http://dali.pengpengdd.cyou/Article/details/gtdzdftlod.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xziqi.cn/Article/details/gtkjndvpwd.html

[T24] Swift：闭包
来源：http://dali.zhiwuduotai.top/Article/details/gtkqutmswm.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.316326.xyz/Article/details/gtqnkzcyib.html

[T25] Swift：结构体
来源：http://dali.chenzaomai.com/Article/details/gtnnmxzsla.html

struct P { var x: Int }
来源：http://dali.daria6918.cn/Article/details/gtbnrbjlqg.html

[T26] Swift：类与重写
来源：http://dali.jqgufenzy.top/Article/details/gtgqvycdnl.html

class A: Base { override func f() {} }
来源：http://dali.daria6918.cn/Article/details/gtogswqoio.html

[T27] Swift：错误处理
来源：http://dali.nwbrower.top/Article/details/gtlkgwuwuy.html

do { try f() } catch { print(error) }
来源：http://dali.pycfn.com/Article/details/gtimgkhbka.html

[T28] Swift：枚举
来源：http://dali.xylfe.cn/Article/details/gtjltzirbd.html

enum Color { case red, green }
来源：http://dali.zycfv.cn/Article/details/gtihkjdmxj.html

[T29] Swift：guard 提前返回
来源：http://dali.ivvv.top/Article/details/gtssylxqqh.html

guard let x = opt else { return }
来源：http://dali.yuanzhike.top/Article/details/gtzxsjjoxx.html

[T30] Swift：协议
来源：http://dali.jiagoushi.top/Article/details/gtfnysfeld.html

protocol Shape { func area() -> Double }
来源：http://dali.haohaochexian.top/Article/details/gtkevcdnmh.html

[T31] Lua：Hello World
来源：http://dali.smart0.xyz/Article/details/gtnzoiqfjr.html

print("Hello")
来源：http://dali.xuetiantiany.cn/Article/details/gtctyptkhw.html

[T32] Lua：局部变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvanbmilh.html

local a = 1
来源：http://dali.jianghu66.top/Article/details/gtgubxqjvh.html

[T33] Lua：表（数组）
来源：http://dali.haohaochexian.top/Article/details/gtixegxoye.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.dashuyun.cn/Article/details/gtiuoxwiya.html

[T34] Lua：遍历表
来源：http://dali.pycfn.com/Article/details/gtuhzuyfxl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xuetiantiany.cn/Article/details/gthtrtldkm.html

[T35] Lua：字典表
来源：http://dali.pengpengdd.cyou/Article/details/gtemsjqmbc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cashguo.top/Article/details/gtpelkweln.html

[T36] Lua：函数
来源：http://dali.xinyue.icu/Article/details/gtazkftfke.html

function add(a, b) return a + b end
来源：http://dali.hnxiangtu.top/Article/details/gtpscdxyvj.html

[T37] Lua：字符串拼接
来源：http://dali.cucudq.cn/Article/details/gteirsjbkh.html

"a" .. "b"
来源：http://dali.mhx1999.top/Article/details/gtzguhvmtn.html

[T38] Lua：条件
来源：http://dali.shuidangran.top/Article/details/gtdypfmreb.html

if x > 0 then print("正") end
来源：http://dali.cdnleiting.top/Article/details/gtssetdmir.html

[T39] Lua：模式匹配
来源：http://dali.yueranfly.top/Article/details/gtdyvnwkir.html

string.find(s, "%d+")
来源：http://dali.hnqzz.top/Article/details/gtxmsfwjmb.html

[T40] Lua：元表
来源：http://dali.jyoumei.cn/Article/details/gtabcjkdgj.html

setmetatable({}, { __index = base })
来源：http://dali.hysaishi.cn/Article/details/gtbtdzpqgp.html

[T41] Perl：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtvunrzpsd.html

print "Hello\n";
来源：http://dali.hywenlv.cn/Article/details/gtmjnbhwds.html

[T42] Perl：变量类型
来源：http://dali.daria6918.cn/Article/details/gtcvlzzwlw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.andypj.xyz/Article/details/gtpjkspwxs.html

[T43] Perl：字符串插值
来源：http://dali.sysykeji.top/Article/details/gthkqdraqq.html

"值: $a"
来源：http://dali.daxiang520.top/Article/details/gtrxvpsmvz.html

[T44] Perl：条件
来源：http://dali.shuidangran.top/Article/details/gtardbbrgo.html

if ($a > 0) { print "正"; }
来源：http://dali.0kj1m.cn/Article/details/gttojngugm.html

[T45] Perl：数组遍历
来源：http://dali.xylfe.cn/Article/details/gtlzqrlnop.html

for my $x (@arr) { print $x; }
来源：http://dali.haohaochexian.top/Article/details/gtmtjnrdpq.html

[T46] Perl：哈希操作
来源：http://dali.yuanzhike.top/Article/details/gthbwdhjin.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjklxuwpf.html

[T47] Perl：正则捕获
来源：http://dali.chenjidiqi.icu/Article/details/gtoqwbjwdb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.meibo888.top/Article/details/gtpeqnjbuq.html

[T48] Perl：正则替换
来源：http://dali.316326.xyz/Article/details/gtkkjkxfgo.html

$s =~ s/old/new/g;
来源：http://dali.yueranfly.top/Article/details/gtnulndmpd.html

[T49] Perl：函数
来源：http://dali.c1oappe.top/Article/details/gttxallmoq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.316326.xyz/Article/details/gtpowfcpkf.html

[T50] Perl：逐行读文件
来源：http://dali.smart0.xyz/Article/details/gtfhkrvrow.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ehwqpu.com/Article/details/gthgrjgeuw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yuanzhike.top/Article/details/gtpgtuxnsl.html

[T51] Scala：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtzvqjikiq.html

println("Hello")
来源：http://dali.chenzaomai.com/Article/details/gtpwafirbo.html

[T52] Scala：变量
来源：http://dali.tianlin.xyz/Article/details/gthxaovpiq.html

val a = 1;  var b = 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtepghbhok.html

[T53] Scala：字符串插值
来源：http://dali.fzhhl.top/Article/details/gtfqwhkvel.html

s"值: $b"
来源：http://dali.0kj1m.cn/Article/details/gteqljjkwt.html

[T54] Scala：集合映射
来源：http://dali.feifeiyinyue.top/Article/details/gtsclendbt.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.bjfxy.top/Article/details/gtuvwvicff.html

[T55] Scala：集合过滤
来源：http://dali.jinqigufen.top/Article/details/gtsnrzfesq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yongpay.top/Article/details/gtxtqxzhpc.html

[T56] Scala：样例类
来源：http://dali.tian-w.cn/Article/details/gtuteazisn.html

case class User(name: String, age: Int)
来源：http://dali.9152youxi.cn/Article/details/gtshjuxsmz.html

[T57] Scala：模式匹配
来源：http://dali.hnqzz.top/Article/details/gtffqkyotd.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ehwqpu.com/Article/details/gtzatkweyv.html

[T58] Scala：函数定义
来源：http://dali.wangdashe.top/Article/details/gtqqiwicey.html


<!-- 参考信息 -->