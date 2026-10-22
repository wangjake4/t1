代发 wailian999

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.redwolf501.top/Article/details/gtxdumnzfj.html

[R56] 远程拷贝
来源：http://dali.hammf.cn/Article/details/gtdpfvxbwg.html

scp file user@host:/path/
来源：http://dali.dianchejie.cn/Article/details/gtecmafgmh.html

[R57] 远程执行命令
来源：http://dali.fzhhl.top/Article/details/gttikgtueu.html

ssh user@host 'uptime'
来源：http://dali.smart0.xyz/Article/details/gtgcgntjxk.html

[R58] 下载文件
来源：http://dali.tanke756.top/Article/details/gtddyjwttk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.tianlin.xyz/Article/details/gtuobzzwcr.html

[R59] 发 POST JSON
来源：http://dali.hammf.cn/Article/details/gtghpnmqvm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzwpozrqm.html

[R60] 只看 HTTP 状态码
来源：http://dali.hnqzz.top/Article/details/gtqlpspjyl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yuanzhike.top/Article/details/gtlbgbvpnw.html

[R61] 磁盘占用
来源：http://dali.tianlin.xyz/Article/details/gtiuucjegy.html

df -h;  du -sh *
来源：http://dali.shuidangran.top/Article/details/gtvhzgpzhe.html

[R62] 找最占空间的文件
来源：http://dali.yongpay.top/Article/details/gtkpswyzik.html

du -ah . | sort -rh | head -10
来源：http://dali.iojbl.cn/Article/details/gtvqhbebzg.html

[R63] 内存与进程
来源：http://dali.cqqwz.cn/Article/details/gtogsisdse.html

free -h;  ps aux | grep nginx
来源：http://dali.gaohongyu789.top/Article/details/gtsezbvjwv.html

[R64] 结束进程
来源：http://dali.gotoacloud.top/Article/details/gtkwsyrpyn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hfpthk.cn/Article/details/gtrzklsrjv.html

[R65] 查看端口占用
来源：http://dali.guannengcc.top/Article/details/gtmkcxogbc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xuanzx.com/Article/details/gtzyxsngcy.html

[R66] 定时任务
来源：http://dali.sysykeji.top/Article/details/gtwhmmhezq.html

crontab -e;  crontab -l
来源：http://dali.nwbrower.top/Article/details/gthytfqvwn.html

[R67] 生成随机十六进制串
来源：http://dali.smart0.xyz/Article/details/gtozwaraqg.html

openssl rand -hex 16
来源：http://dali.yangfankeji.com/Article/details/gtgfwpijlr.html

[R68] 计算文件校验值
来源：http://dali.daria6918.cn/Article/details/gtgclxjcau.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ybcxt.top/Article/details/gtrjgqtmkt.html

[R69] 生成随机密码
来源：http://dali.sufxvd.cn/Article/details/gtaoetkwnd.html

head -c 16 /dev/urandom | base64
来源：http://dali.yongpay.top/Article/details/gtplzxerqu.html

[R70] 时间戳与互转
来源：http://dali.ppjwa.cn/Article/details/gtiknqxqgh.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gtdvgcinyk.html

[R71] 日期格式化
来源：http://dali.316326.xyz/Article/details/gtifjokpxz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hnxiangtu.top/Article/details/gtfjzfteyw.html

[R72] 等待端口就绪
来源：http://dali.shangyingyoupin.top/Article/details/gtiusxtagp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sweek.top/Article/details/gthebwmgay.html

[R73] 分割大日志
来源：http://dali.yonumen.top/Article/details/gtcqgjofgm.html

split -l 1000 big.log part_
来源：http://dali.guowangkeji.top/Article/details/gttbbhdkcf.html

[R74] 批量重命名
来源：http://dali.hammf.cn/Article/details/gtrcyivbdk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.guannengcc.top/Article/details/gtoirzqscj.html

[R75] 导出环境变量
来源：http://dali.sxryk.cn/Article/details/gtgtehjzhg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shangyingyoupin.top/Article/details/gtjcekqlva.html

[R76] 使用临时文件
来源：http://dali.sysykeji.top/Article/details/gtbhrhojbd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ybcxt.top/Article/details/gtuqukdvtt.html

[R77] 读取用户输入
来源：http://dali.zhixingplan.top/Article/details/gtjctgjzep.html

read -rp "请输入: " ans
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoosmutix.html

[R78] 交互式菜单
来源：http://dali.jinghuilouyu.cn/Article/details/gtcitbasei.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.chenzaomai.com/Article/details/gtflqeuopb.html

[R79] 解析命令行选项
来源：http://dali.ywan-chungtsiang.top/Article/details/gtctcidouz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cucudq.cn/Article/details/gteuglprcc.html

[R80] 查看脚本执行耗时
来源：http://dali.quarkkingdee.top/Article/details/gttdnmomlr.html

time ./run.sh
来源：http://dali.zycfv.cn/Article/details/gtxboiysbz.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtxunlmrdu.html

S. C / C++ 专题
来源：http://dali.nwbrower.top/Article/details/gtfhmerrsf.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtbnvwvzel.html

[S01] C：Hello World
来源：http://dali.ydzc1.top/Article/details/gtgmvmcrsz.html

#include <stdio.h>
来源：http://dali.hnqzz.top/Article/details/gtbocspnwz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cdnleiting.top/Article/details/gtlackoqqg.html

[S02] C：变量与格式化输出
来源：http://dali.yangfankeji.com/Article/details/gtxdpayijr.html

int a = 10; printf("%d\n", a);
来源：http://dali.xuetiantiany.cn/Article/details/gtexmvzjtz.html

[S03] C：读入整数
来源：http://dali.cucudq.cn/Article/details/gtxzmrqhwx.html

int x; scanf("%d", &x);
来源：http://dali.jinqigufen.top/Article/details/gtjtzpudtc.html

[S04] C：字符串复制
来源：http://dali.nanxinkj.top/Article/details/gtjirpybxy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.pycfn.com/Article/details/gtvtmgsxas.html

[S05] C：字符串长度
来源：http://dali.vqdsnc.cn/Article/details/gtswimxcvf.html

strlen(s)
来源：http://dali.jianghu66.top/Article/details/gtliodeqmk.html

[S06] C：字符串比较
来源：http://dali.sysykeji.top/Article/details/gtlsyhyiua.html

strcmp(a, b) == 0
来源：http://dali.gaohongyu789.top/Article/details/gtqqrqqegw.html

[S07] C：数组遍历求和
来源：http://dali.cucudq.cn/Article/details/gtvdakjezo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.nanxinkj.top/Article/details/gtlfnlbqtd.html

[S08] C：动态内存分配与释放
来源：http://dali.yangfankeji.com/Article/details/gtydyxacqd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sweek.top/Article/details/gtsmaaxfto.html

[S09] C：结构体定义与初始化
来源：http://dali.sufxvd.cn/Article/details/gtaltrjihs.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shangyingyoupin.top/Article/details/gtjqiywhoa.html

[S10] C：指针与解引用
来源：http://dali.zycfv.cn/Article/details/gtstswoexg.html

int *p = &a;  *p = 5;
来源：http://dali.zhixingplan.top/Article/details/gtpuopocrv.html

[S11] C：逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gtyauwasqq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jyoumei.cn/Article/details/gtlamolidx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmxsedcke.html

fclose(f);
来源：http://dali.xuetiantiany.cn/Article/details/gtswksqqcl.html

[S12] C：写文件
来源：http://dali.smart0.xyz/Article/details/gtfywqicll.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpznxffkf.html

[S13] C：宏定义
来源：http://dali.wangdashe.top/Article/details/gtetnaohsk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.feifeiyinyue.top/Article/details/gtosikggxg.html

[S14] C：枚举
来源：http://dali.snrcjt.cn/Article/details/gtdwdpmvyt.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cucudq.cn/Article/details/gtkisnxodf.html

[S15] C：类型转换
来源：http://dali.yonumen.top/Article/details/gtlcnrfkiq.html

(double) a / b
来源：http://dali.yonumen.top/Article/details/gtuatswwbb.html

[S16] C：位操作置位
来源：http://dali.yueranfly.top/Article/details/gtptfjcfpt.html

x |= (1 << 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqgqqfpam.html

[S17] C：安全拼接字符串
来源：http://dali.jinqigufen.top/Article/details/gtczkisgnh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.0kj1m.cn/Article/details/gtaixlzfit.html

[S18] C：命令行参数
来源：http://dali.yangfankeji.com/Article/details/gtlvcheqnj.html

int main(int argc, char **argv)
来源：http://dali.hongshengwenyu.top/Article/details/gtzgxmajth.html

[S19] C：快速排序
来源：http://dali.meibo888.top/Article/details/gtunoueqzq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.0kj1m.cn/Article/details/gtzlrfewmu.html

[S20] C：二分查找
来源：http://dali.ybcxt.top/Article/details/gtttxdmwox.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shzxlz.cn/Article/details/gtccikeayd.html

[S21] C：字符类别判断
来源：http://dali.cdnleiting.top/Article/details/gtlhbtlmmp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cashguo.top/Article/details/gtxrmszgdc.html

[S22] C：字符串转数字
来源：http://dali.hywenlv.cn/Article/details/gtzvvxrjbq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.daxiang520.top/Article/details/gtrfmbiwll.html

[S23] C：随机数
来源：http://dali.ivvv.top/Article/details/gtvbvlzebi.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj202588.top/Article/details/gteqhxxnum.html

[S24] C：获取本地时间
来源：http://dali.ppjwa.cn/Article/details/gtomhwkhsc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.chenlongwang.top/Article/details/gtghyvnyon.html

[S25] C：内存拷贝
来源：http://dali.quarkkingdee.top/Article/details/gtcymlelcn.html

memcpy(dst, src, n);
来源：http://dali.ydzc1.top/Article/details/gtchbmmzvn.html

[S26] C：内存清零
来源：http://dali.yanxiufei.cn/Article/details/gtsygzilhc.html

memset(a, 0, sizeof a);
来源：http://dali.pycfn.com/Article/details/gtpkgxauln.html

[S27] C：定义常量
来源：http://dali.yj20258.top/Article/details/gthghefygr.html

const double PI = 3.14159;
来源：http://dali.sxryk.cn/Article/details/gtzcxpnwii.html

[S28] C：静态变量
来源：http://dali.birdmap.top/Article/details/gtqyovafks.html

static int counter = 0;
来源：http://dali.hongshengwenyu.top/Article/details/gtzitaabmp.html

[S29] C：变参函数
来源：http://dali.gogol.net.cn/Article/details/gtlhtkqwli.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinqigfzy.top/Article/details/gtkkqcqwmt.html

[S30] C：头文件保护
来源：http://dali.quarkkingdee.top/Article/details/gtgfjcpnkq.html

#ifndef X_H
来源：http://dali.gaohongyu789.top/Article/details/gtrmbbgxah.html

#define X_H
来源：http://dali.hongshengwenyu.top/Article/details/gtumiqhbiv.html

#endif
来源：http://dali.shzxlz.cn/Article/details/gtfwvxgeul.html

[S31] C++：Hello World
来源：http://dali.hywenlv.cn/Article/details/gtxjjfiggx.html

#include <iostream>
来源：http://dali.sxryk.cn/Article/details/gtaxyrmyul.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.fengsongda.top/Article/details/gtvucmkcfo.html

[S32] C++：字符串
来源：http://dali.yj20258.top/Article/details/gtggegpzlc.html

std::string s = "hi";  s += "!";
来源：http://dali.zhiwuduotai.top/Article/details/gtkhacfqro.html

[S33] C++：vector 增删
来源：http://dali.dianchejie.cn/Article/details/gtafyigsqs.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrdwegswh.html

[S34] C++：遍历 vector
来源：http://dali.xylfe.cn/Article/details/gtccflupou.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hnxiangtu.top/Article/details/gttnvtrctr.html

[S35] C++：map
来源：http://dali.quarkkingdee.top/Article/details/gtpugrsceh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gtrsjeykve.html

[S36] C++：unordered_map
来源：http://dali.svipenyu.cn/Article/details/gtwyrhqies.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gtzhttoqur.html

[S37] C++：set
来源：http://dali.daria6918.cn/Article/details/gtzzwszgka.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gzhubu.top/Article/details/gtlscqngcl.html

[S38] C++：排序
来源：http://dali.gzhubu.top/Article/details/gttnnmyeof.html

std::sort(v.begin(), v.end());
来源：http://dali.yj202588.top/Article/details/gtcdamzokm.html

[S39] C++：自定义比较器排序
来源：http://dali.gaohongyu789.top/Article/details/gtezgyzrja.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yuxming.cn/Article/details/gtxobeoftd.html

[S40] C++：查找元素
来源：http://dali.hywenlv.cn/Article/details/gtuhzrngkj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nwbrower.top/Article/details/gtloqylpll.html

[S41] C++：类与构造函数
来源：http://dali.bjfxy.top/Article/details/gtvxsklkdd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.pengpengdd.cyou/Article/details/gtwjcslqkc.html

[S42] C++：继承与虚函数
来源：http://dali.xuanzx.com/Article/details/gthjharslo.html

class B : public Base { public: void f() override {} };
来源：http://dali.feifeiyinyue.top/Article/details/gtizhbrenj.html

[S43] C++：智能指针
来源：http://dali.tianlin.xyz/Article/details/gtfmrljugh.html

auto p = std::make_unique<int>(5);
来源：http://dali.wangshuangyany.cn/Article/details/gtbppwuqhb.html

[S44] C++：引用传参
来源：http://dali.hywenlv.cn/Article/details/gtoibovyzv.html

void inc(int &x) { ++x; }
来源：http://dali.yueranfly.top/Article/details/gtnqzmljfo.html

[S45] C++：lambda
来源：http://dali.gotoacloud.top/Article/details/gtwwgxelut.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shzxlz.cn/Article/details/gtrzffzjla.html

[S46] C++：函数模板
来源：http://dali.nanxuanxn.top/Article/details/gtlhffbhjc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jlsjyb.cn/Article/details/gtszoivfyk.html

[S47] C++：结构化绑定遍历
来源：http://dali.iojbl.cn/Article/details/gtrknoecgm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yongpay.top/Article/details/gtdmozazke.html

[S48] C++：逐行读文件
来源：http://dali.jinqigfzy.top/Article/details/gtzoexwcbg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gtccjtathm.html

while (std::getline(in, line)) { }
来源：http://dali.aizwys.cn/Article/details/gtotucnres.html

[S49] C++：写文件
来源：http://dali.cashguo.top/Article/details/gtsttcyize.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hnqzz.top/Article/details/gtlzlmitvg.html

[S50] C++：格式化数字
来源：http://dali.zhengqikj.top/Article/details/gtudzbzrmc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hnqzz.top/Article/details/gtvnnvdxry.html

[S51] C++：显式类型转换
来源：http://dali.sufxvd.cn/Article/details/gtrhemsioh.html

static_cast<double>(a) / b
来源：http://dali.jlsjyb.cn/Article/details/gtauroxuni.html

[S52] C++：const 与 noexcept
来源：http://dali.zdqjudy.top/Article/details/gtxxkkacoi.html

int size() const noexcept { return n_; }
来源：http://dali.daxiang520.top/Article/details/gtqqypxtws.html

[S53] C++：移动语义
来源：http://dali.sysykeji.top/Article/details/gtvmhisgov.html

std::vector<int> w = std::move(v);
来源：http://dali.xuetiantiany.cn/Article/details/gtsdgpyycv.html

[S54] C++：异常处理
来源：http://dali.gogol.net.cn/Article/details/gtlxfybubb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gotoacloud.top/Article/details/gtmqkgzcpi.html

[S55] C++：结构化绑定
来源：http://dali.jqgfzy.top/Article/details/gtericxcat.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtevzhslar.html

[S56] C++：optional
来源：http://dali.hysaishi.cn/Article/details/gtfwwmkkme.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.dashuyun.cn/Article/details/gtmmbnhpen.html

[S57] C++：编译期常量
来源：http://dali.cqqwz.cn/Article/details/gtcqhqpfwn.html

constexpr int N = 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqajwktax.html

[S58] C++：命名空间
来源：http://dali.cqqwz.cn/Article/details/gtoanzqqkv.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyxfvwhmf.html

[S59] C++：静态断言
来源：http://dali.andypj.xyz/Article/details/gtvbyvsdik.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gzhubu.top/Article/details/gtcfxzwfnr.html

[S60] C++：遍历并删除元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmckyxoeo.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jqgufenzy.top/Article/details/gtwmzrelec.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtwpamgygn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xinyue.icu/Article/details/gtjyzncxma.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtznvbqqhh.html

[T01] Kotlin：Hello World
来源：http://dali.hnqzz.top/Article/details/gtdbslpvyv.html

println("Hello")
来源：http://dali.pengpengdd.cyou/Article/details/gtxyhmnttf.html

[T02] Kotlin：变量
来源：http://dali.yonumen.top/Article/details/gtndlxgryk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gtakaroulj.html

[T03] Kotlin：字符串模板
来源：http://dali.shzxlz.cn/Article/details/gthgiejnno.html

"值: $b"
来源：http://dali.nwbrower.top/Article/details/gtjdlsfnxd.html

[T04] Kotlin：空安全
来源：http://dali.gaohongyu789.top/Article/details/gtibxvebwt.html

val n: String? = null;  n?.length
来源：http://dali.sufxvd.cn/Article/details/gtryowciys.html

[T05] Kotlin：when 表达式
来源：http://dali.yj202588.top/Article/details/gtrqkpfumv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yj20258.top/Article/details/gtptafyjrz.html

[T06] Kotlin：集合映射
来源：http://dali.tian-w.cn/Article/details/gtyffqoyya.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yongpay.top/Article/details/gtkndwkwcv.html

[T07] Kotlin：集合过滤
来源：http://dali.jlsjyb.cn/Article/details/gtqnnruzus.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sysykeji.top/Article/details/gtpmblfanb.html

[T08] Kotlin：数据类
来源：http://dali.hnxiangtu.top/Article/details/gtzpgbitnd.html

data class User(val name: String, val age: Int)
来源：http://dali.ehwqpu.com/Article/details/gtivnqpenc.html

[T09] Kotlin：扩展函数
来源：http://dali.zdqjudy.top/Article/details/gttcvmisdl.html

fun String.exclaim() = this + "!"
来源：http://dali.shuidangran.top/Article/details/gtpzwisbry.html

[T10] Kotlin：默认参数
来源：http://dali.zhiwuduotai.top/Article/details/gteivtlklk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.0kj1m.cn/Article/details/gtlflqxedq.html

[T11] Kotlin：协程
来源：http://dali.yj202588.top/Article/details/gtthxhwzrv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sxryk.cn/Article/details/gtaortyojb.html

[T12] Kotlin：解构声明
来源：http://dali.jqgufenzy.top/Article/details/gtvnjuuyaf.html

val (a, b) = Pair(1, 2)
来源：http://dali.cucudq.cn/Article/details/gtgqtuwwke.html

[T13] Kotlin：只读 Map
来源：http://dali.hywenlv.cn/Article/details/gtyupxblcf.html

val m = mapOf("a" to 1)
来源：http://dali.hnxiangtu.top/Article/details/gtyemramnw.html

[T14] Kotlin：循环
来源：http://dali.hnxiangtu.top/Article/details/gtbuszbajh.html

for (i in 1..10) println(i)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyoxmhzsq.html

[T15] Kotlin：接口
来源：http://dali.yj20258888.top/Article/details/gtdnempxnj.html

interface Shape { fun area(): Double }
来源：http://dali.hammf.cn/Article/details/gtyvsvgkii.html

[T16] Swift：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtaesadrsc.html

print("Hello")
来源：http://dali.wangdashe.top/Article/details/gtdmipsohv.html

[T17] Swift：变量与常量
来源：http://dali.smart0.xyz/Article/details/gtdpvyyazc.html

var a = 1;  let b = 2
来源：http://dali.zhiwuduotai.top/Article/details/gtxwppidzp.html

[T18] Swift：字符串插值
来源：http://dali.yuanzhike.top/Article/details/gtbvnmmilw.html

"值: \(b)"
来源：http://dali.iojbl.cn/Article/details/gtyrbeznmy.html

[T19] Swift：可选绑定
来源：http://dali.jqgufenzy.top/Article/details/gtbiqcomhn.html

if let n = opt { print(n) }
来源：http://dali.tian-w.cn/Article/details/gtktvlemkk.html

[T20] Swift：数组操作
来源：http://dali.yj202588.top/Article/details/gtbeztwtck.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ybcxt.top/Article/details/gtcreqdgdu.html

[T21] Swift：遍历
来源：http://dali.jlsjyb.cn/Article/details/gthqjuptoq.html

for x in a { print(x) }
来源：http://dali.daxiang520.top/Article/details/gtfgjulier.html

[T22] Swift：字典
来源：http://dali.shanyushiyangtech.top/Article/details/gtdxgwowwe.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gthsqzxlog.html

[T23] Swift：函数
来源：http://dali.gotoacloud.top/Article/details/gtqpqyqznf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ivvv.top/Article/details/gtzdyhlcyj.html

[T24] Swift：闭包
来源：http://dali.svipenyu.cn/Article/details/gtkcrorgpj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.tian-w.cn/Article/details/gtdmdsmicv.html

[T25] Swift：结构体
来源：http://dali.shanyushiyangtech.top/Article/details/gturmkbiuc.html

struct P { var x: Int }
来源：http://dali.daxiang520.top/Article/details/gtuwkpqwlq.html

[T26] Swift：类与重写
来源：http://dali.yongpay.top/Article/details/gtbbzazlld.html

class A: Base { override func f() {} }
来源：http://dali.nwbrower.top/Article/details/gtfovktyht.html

[T27] Swift：错误处理
来源：http://dali.hongshengwenyu.top/Article/details/gtfqohlkpp.html

do { try f() } catch { print(error) }
来源：http://dali.nanxinkj.top/Article/details/gttiqjaszv.html

[T28] Swift：枚举
来源：http://dali.jinqigufen.top/Article/details/gtvxzwtuim.html

enum Color { case red, green }
来源：http://dali.xziqi.cn/Article/details/gthazijcjm.html

[T29] Swift：guard 提前返回
来源：http://dali.dianchejie.cn/Article/details/gtyfyrruzb.html

guard let x = opt else { return }
来源：http://dali.yj20258888.top/Article/details/gtseotyrvx.html

[T30] Swift：协议
来源：http://dali.ydzc1.top/Article/details/gtozuxcpwh.html

protocol Shape { func area() -> Double }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrhchdfci.html

[T31] Lua：Hello World
来源：http://dali.yueranfly.top/Article/details/gtnwcgbmho.html

print("Hello")
来源：http://dali.daxiang520.top/Article/details/gtwosudutn.html

[T32] Lua：局部变量
来源：http://dali.jqgfzy.top/Article/details/gtwqricsvu.html

local a = 1
来源：http://dali.gotoacloud.top/Article/details/gtvconeugt.html

[T33] Lua：表（数组）
来源：http://dali.meibo888.top/Article/details/gtipmcmtxl.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.nanxuanxn.top/Article/details/gtoswgrvgx.html

[T34] Lua：遍历表
来源：http://dali.haohaochexian.top/Article/details/gttkbozsud.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yuxming.cn/Article/details/gtllkyuxag.html

[T35] Lua：字典表
来源：http://dali.aibaodan.cn/Article/details/gtnbhchqsd.html

local d = { a = 1 };  d.b = 2
来源：http://dali.iojbl.cn/Article/details/gtbncpcqwe.html

[T36] Lua：函数
来源：http://dali.yanxiufei.cn/Article/details/gttfbjhaav.html

function add(a, b) return a + b end
来源：http://dali.jianghu66.top/Article/details/gtskcelblo.html

[T37] Lua：字符串拼接
来源：http://dali.aizwys.cn/Article/details/gthswzqbiv.html

"a" .. "b"
来源：http://dali.feifeiyinyue.top/Article/details/gtgrsggvto.html

[T38] Lua：条件
来源：http://dali.ivvv.top/Article/details/gtxjnaimxl.html

if x > 0 then print("正") end
来源：http://dali.yanxiufei.cn/Article/details/gtrxabumnb.html

[T39] Lua：模式匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gtghlasvhe.html

string.find(s, "%d+")
来源：http://dali.yonumen.top/Article/details/gtmxiwgpnx.html

[T40] Lua：元表
来源：http://dali.gaohongyu789.top/Article/details/gtlrwctiax.html

setmetatable({}, { __index = base })
来源：http://dali.wangdashe.top/Article/details/gtsvumtztt.html

[T41] Perl：Hello World
来源：http://dali.jianghu66.top/Article/details/gtneyckbju.html

print "Hello\n";
来源：http://dali.chenjidiqi.icu/Article/details/gtaammidyb.html

[T42] Perl：变量类型
来源：http://dali.daxiang520.top/Article/details/gtkfwcrqiu.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jinqigfzy.top/Article/details/gtjkkeeute.html

[T43] Perl：字符串插值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyacnnstg.html

"值: $a"
来源：http://dali.andypj.xyz/Article/details/gtvflabtcp.html

[T44] Perl：条件
来源：http://dali.sweek.top/Article/details/gthlreteak.html

if ($a > 0) { print "正"; }
来源：http://dali.daria6918.cn/Article/details/gtamjgptej.html

[T45] Perl：数组遍历
来源：http://dali.hysaishi.cn/Article/details/gtnabygfmk.html

for my $x (@arr) { print $x; }
来源：http://dali.zhengqikj.top/Article/details/gtvcjhffge.html

[T46] Perl：哈希操作
来源：http://dali.zhoulong.xyz/Article/details/gtushoeavu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.smart0.xyz/Article/details/gtcpvsmuge.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gtvjzkopox.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ybcxt.top/Article/details/gthdycvbvy.html

[T48] Perl：正则替换
来源：http://dali.zhixingplan.top/Article/details/gtqlbaikia.html

$s =~ s/old/new/g;
来源：http://dali.hnxiangtu.top/Article/details/gtfnbcskkm.html

[T49] Perl：函数
来源：http://dali.vqdsnc.cn/Article/details/gtszhudfvb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.daxiang520.top/Article/details/gtikffpvjn.html

[T50] Perl：逐行读文件
来源：http://dali.shzxlz.cn/Article/details/gtwaiitnew.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhoulong.xyz/Article/details/gtebevdzrx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yongpay.top/Article/details/gtbctrqtfd.html

[T51] Scala：Hello World
来源：http://dali.yangfankeji.com/Article/details/gtsizwwrbx.html

println("Hello")
来源：http://dali.hnqzz.top/Article/details/gtwfkmxssk.html

[T52] Scala：变量
来源：http://dali.daxiang520.top/Article/details/gtrnigorqi.html

val a = 1;  var b = 2
来源：http://dali.sysykeji.top/Article/details/gtsaerapaz.html

[T53] Scala：字符串插值
来源：http://dali.nwbrower.top/Article/details/gtzudlervi.html

s"值: $b"
来源：http://dali.ydzc1.top/Article/details/gtbmdtqscu.html

[T54] Scala：集合映射
来源：http://dali.yj20258888.top/Article/details/gtfpfscmiv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.nanxinkj.top/Article/details/gtwuiyfrje.html

[T55] Scala：集合过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtychbvetd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.chenzaomai.com/Article/details/gtshbkvnbe.html

[T56] Scala：样例类
来源：http://dali.shuidangran.top/Article/details/gtqjnurnrm.html

case class User(name: String, age: Int)
来源：http://dali.hywenlv.cn/Article/details/gthnlrwdvh.html

[T57] Scala：模式匹配
来源：http://dali.sweek.top/Article/details/gtevoenoqp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ehwqpu.com/Article/details/gtziuzwdof.html

[T58] Scala：函数定义
来源：http://dali.quarkkingdee.top/Article/details/gtmhnvqzoj.html


<!-- 参考信息 -->