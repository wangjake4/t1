代发 wailian999

ssh user@host 'uptime'
来源：http://dali.sweek.top/Article/details/gtkpxbluxw.html

[R58] 下载文件
来源：http://dali.aizwys.cn/Article/details/gtrvwsbkaz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.mhx1999.top/Article/details/gtdinvzott.html

[R59] 发 POST JSON
来源：http://dali.chenlongwang.top/Article/details/gtirakrgqn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ehwqpu.com/Article/details/gttmjypytu.html

[R60] 只看 HTTP 状态码
来源：http://dali.nanxuanxn.top/Article/details/gtpfyrlffo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jlsjyb.cn/Article/details/gtuweaidty.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gtzfnftvts.html

df -h;  du -sh *
来源：http://dali.redwolf501.top/Article/details/gteccmbqgk.html

[R62] 找最占空间的文件
来源：http://dali.yangfankeji.com/Article/details/gtlvmtxqgy.html

du -ah . | sort -rh | head -10
来源：http://dali.zdqjudy.top/Article/details/gtxvpqjvai.html

[R63] 内存与进程
来源：http://dali.yj20258888.top/Article/details/gtlubpuhuz.html

free -h;  ps aux | grep nginx
来源：http://dali.hnxiangtu.top/Article/details/gtwtajggqg.html

[R64] 结束进程
来源：http://dali.cdnleiting.top/Article/details/gtuqlqrwnp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xuetiantiany.cn/Article/details/gttoisdvmt.html

[R65] 查看端口占用
来源：http://dali.zhengqikj.top/Article/details/gtllowhqgx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hfpthk.cn/Article/details/gtemngimev.html

[R66] 定时任务
来源：http://dali.zhixingplan.top/Article/details/gtapqseshx.html

crontab -e;  crontab -l
来源：http://dali.gzhubu.top/Article/details/gtdyqppuxy.html

[R67] 生成随机十六进制串
来源：http://dali.kuanghao11.cn/Article/details/gtoljufrdh.html

openssl rand -hex 16
来源：http://dali.jqgfzy.top/Article/details/gtrbrfaosz.html

[R68] 计算文件校验值
来源：http://dali.yanxiufei.cn/Article/details/gtbnovotvo.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtyypheajl.html

[R69] 生成随机密码
来源：http://dali.cheryme.top/Article/details/gtpuefqmjt.html

head -c 16 /dev/urandom | base64
来源：http://dali.bjfxy.top/Article/details/gtbhylhlit.html

[R70] 时间戳与互转
来源：http://dali.nwbrower.top/Article/details/gttvtgmdvs.html

date +%s;  date -d @1700000000
来源：http://dali.svipenyu.cn/Article/details/gtptdvlrqk.html

[R71] 日期格式化
来源：http://dali.chenlongwang.top/Article/details/gtehkmmvhh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cheryme.top/Article/details/gtaqoiivpz.html

[R72] 等待端口就绪
来源：http://dali.pengpengdd.cyou/Article/details/gtwzghupnz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yj20258888.top/Article/details/gtwjcohdxo.html

[R73] 分割大日志
来源：http://dali.redwolf501.top/Article/details/gtigvdncuv.html

split -l 1000 big.log part_
来源：http://dali.aibaodan.cn/Article/details/gtwvwvwoop.html

[R74] 批量重命名
来源：http://dali.chenlongwang.top/Article/details/gtlrzxhdxz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.birdmap.top/Article/details/gtydvnemgv.html

[R75] 导出环境变量
来源：http://dali.zdqjudy.top/Article/details/gtijmiejvr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.quarkkingdee.top/Article/details/gtkzjdmhkj.html

[R76] 使用临时文件
来源：http://dali.yj20258.top/Article/details/gtzqgsckgt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgufenzy.top/Article/details/gtnqexiuif.html

[R77] 读取用户输入
来源：http://dali.cheryme.top/Article/details/gthawitagz.html

read -rp "请输入: " ans
来源：http://dali.yonumen.top/Article/details/gtouuwfasc.html

[R78] 交互式菜单
来源：http://dali.zhoulong.xyz/Article/details/gtyulohmyd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ydzc1.top/Article/details/gthlwoqsns.html

[R79] 解析命令行选项
来源：http://dali.0kj1m.cn/Article/details/gtjgcguggg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yanxiufei.cn/Article/details/gtlopdwdks.html

[R80] 查看脚本执行耗时
来源：http://dali.daxiang520.top/Article/details/gtphdmriov.html

time ./run.sh
来源：http://dali.yuanzhike.top/Article/details/gtsaiizmee.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtpppsfgog.html

S. C / C++ 专题
来源：http://dali.nanxinkj.top/Article/details/gtqbqtkdpo.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtutjqxvgv.html

[S01] C：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gterhlctvw.html

#include <stdio.h>
来源：http://dali.nwbrower.top/Article/details/gttziisgqe.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ehwqpu.com/Article/details/gtmthztqjx.html

[S02] C：变量与格式化输出
来源：http://dali.cdnleiting.top/Article/details/gtmjsopkuv.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhengqikj.top/Article/details/gtbymwgwxy.html

[S03] C：读入整数
来源：http://dali.kuanghao11.cn/Article/details/gtfchlvlfa.html

int x; scanf("%d", &x);
来源：http://dali.fengsongda.top/Article/details/gtofayavpj.html

[S04] C：字符串复制
来源：http://dali.kuanghao11.cn/Article/details/gtyomtardn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkkjjmnxd.html

[S05] C：字符串长度
来源：http://dali.9152youxi.cn/Article/details/gtokekoiao.html

strlen(s)
来源：http://dali.xuanzx.com/Article/details/gtdbgpcysl.html

[S06] C：字符串比较
来源：http://dali.gaohongyu789.top/Article/details/gtpgfiznbv.html

strcmp(a, b) == 0
来源：http://dali.haohaochexian.top/Article/details/gttwmapjgk.html

[S07] C：数组遍历求和
来源：http://dali.chenzaomai.com/Article/details/gtungpwvxn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.redwolf501.top/Article/details/gtvkewpqlh.html

[S08] C：动态内存分配与释放
来源：http://dali.zhoulong.xyz/Article/details/gtwsfbgqwh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cdnleiting.top/Article/details/gtrzbavnwh.html

[S09] C：结构体定义与初始化
来源：http://dali.nanxinkj.top/Article/details/gtlbqghuis.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpmirrssr.html

[S10] C：指针与解引用
来源：http://dali.jqgufenzy.top/Article/details/gthceanwns.html

int *p = &a;  *p = 5;
来源：http://dali.shangyingyoupin.top/Article/details/gtiybcmyjg.html

[S11] C：逐行读文件
来源：http://dali.ivvv.top/Article/details/gtnrbaumcc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.fengsongda.top/Article/details/gtsdohkysk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhengqikj.top/Article/details/gtvnxixhgy.html

fclose(f);
来源：http://dali.yangfankeji.com/Article/details/gtoetqxqxo.html

[S12] C：写文件
来源：http://dali.aibaodan.cn/Article/details/gtoeblpyat.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yuxming.cn/Article/details/gtgnwqdzzh.html

[S13] C：宏定义
来源：http://dali.jinqigufen.top/Article/details/gttavtbzyn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.316326.xyz/Article/details/gtewtyrueu.html

[S14] C：枚举
来源：http://dali.jqgfzy.top/Article/details/gtzcdxehph.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.feifeiyinyue.top/Article/details/gtmncxnmvx.html

[S15] C：类型转换
来源：http://dali.wangshuangyany.cn/Article/details/gtatlrmdyw.html

(double) a / b
来源：http://dali.ppjwa.cn/Article/details/gtbdyaduot.html

[S16] C：位操作置位
来源：http://dali.bjfxy.top/Article/details/gtjtaxkxsx.html

x |= (1 << 3);
来源：http://dali.tianlin.xyz/Article/details/gtjimsodkd.html

[S17] C：安全拼接字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtzbffnzhj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xuanzx.com/Article/details/gtgqpfcrvx.html

[S18] C：命令行参数
来源：http://dali.xziqi.cn/Article/details/gtmespkcfd.html

int main(int argc, char **argv)
来源：http://dali.chenzaomai.com/Article/details/gtokvfomlt.html

[S19] C：快速排序
来源：http://dali.ybcxt.top/Article/details/gtkpywoxlo.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yuxming.cn/Article/details/gtaydmskoa.html

[S20] C：二分查找
来源：http://dali.yueranfly.top/Article/details/gtzsgtrpjx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yangfankeji.com/Article/details/gtzlhltjgs.html

[S21] C：字符类别判断
来源：http://dali.ivvv.top/Article/details/gtvjbvcgdq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hongshengwenyu.top/Article/details/gtsodesmky.html

[S22] C：字符串转数字
来源：http://dali.aizwys.cn/Article/details/gtujpwvawv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhoulong.xyz/Article/details/gtkvdjcouo.html

[S23] C：随机数
来源：http://dali.zhongyouzk.top/Article/details/gtcrjrkhci.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.guowangkeji.top/Article/details/gtzkjrdgnv.html

[S24] C：获取本地时间
来源：http://dali.fzhhl.top/Article/details/gtuwbnrody.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhongyouzk.top/Article/details/gtbfhpkhrm.html

[S25] C：内存拷贝
来源：http://dali.shuidangran.top/Article/details/gtyxlymgye.html

memcpy(dst, src, n);
来源：http://dali.aizwys.cn/Article/details/gtrkprensx.html

[S26] C：内存清零
来源：http://dali.xziqi.cn/Article/details/gtomxbfdjz.html

memset(a, 0, sizeof a);
来源：http://dali.jinqigfzy.top/Article/details/gtjltbnbkh.html

[S27] C：定义常量
来源：http://dali.chenlongwang.top/Article/details/gtvashfpdy.html

const double PI = 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gthuqbxfoz.html

[S28] C：静态变量
来源：http://dali.nwbrower.top/Article/details/gtghbajdtn.html

static int counter = 0;
来源：http://dali.hysaishi.cn/Article/details/gtecscodwz.html

[S29] C：变参函数
来源：http://dali.fzhhl.top/Article/details/gtveubwure.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cucudq.cn/Article/details/gtfpbcupsm.html

[S30] C：头文件保护
来源：http://dali.yj202588.top/Article/details/gtmunrklmt.html

#ifndef X_H
来源：http://dali.fzhhl.top/Article/details/gtxxsrefug.html

#define X_H
来源：http://dali.jyoumei.cn/Article/details/gtftcdrjvd.html

#endif
来源：http://dali.quarkkingdee.top/Article/details/gtzmhcfrhk.html

[S31] C++：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiivkohdc.html

#include <iostream>
来源：http://dali.sufxvd.cn/Article/details/gthmzxbmbw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yvedp.cn/Article/details/gtjewyufez.html

[S32] C++：字符串
来源：http://dali.wangshuangyany.cn/Article/details/gthrncbmhx.html

std::string s = "hi";  s += "!";
来源：http://dali.jyoumei.cn/Article/details/gtzgbcxaqe.html

[S33] C++：vector 增删
来源：http://dali.ppjwa.cn/Article/details/gtlxobixog.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.316326.xyz/Article/details/gthbtsxkfs.html

[S34] C++：遍历 vector
来源：http://dali.svipenyu.cn/Article/details/gtktmtarza.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.chenzaomai.com/Article/details/gtkdacbndg.html

[S35] C++：map
来源：http://dali.quarkkingdee.top/Article/details/gtypsqkoqa.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hammf.cn/Article/details/gtsbebhaqq.html

[S36] C++：unordered_map
来源：http://dali.jinqigufen.top/Article/details/gtdxzfgwrj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtosgexvjc.html

[S37] C++：set
来源：http://dali.zhoulong.xyz/Article/details/gtupqcaolh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cashguo.top/Article/details/gtvigjsqah.html

[S38] C++：排序
来源：http://dali.bjfxy.top/Article/details/gtnyqqggmd.html

std::sort(v.begin(), v.end());
来源：http://dali.meibo888.top/Article/details/gtsqspivfq.html

[S39] C++：自定义比较器排序
来源：http://dali.svipenyu.cn/Article/details/gtqcudsjvz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gotoacloud.top/Article/details/gtucwnsaql.html

[S40] C++：查找元素
来源：http://dali.tianlin.xyz/Article/details/gtpxlsfkbs.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hywenlv.cn/Article/details/gtblptokld.html

[S41] C++：类与构造函数
来源：http://dali.tian-w.cn/Article/details/gtajzbffsb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jianghu66.top/Article/details/gtxxdqmynk.html

[S42] C++：继承与虚函数
来源：http://dali.sxryk.cn/Article/details/gtyfqbnkoa.html

class B : public Base { public: void f() override {} };
来源：http://dali.wangdashe.top/Article/details/gtyxtvjenb.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gtgjcrevyi.html

auto p = std::make_unique<int>(5);
来源：http://dali.chenlongwang.top/Article/details/gtnfwtsqmc.html

[S44] C++：引用传参
来源：http://dali.jqgfzy.top/Article/details/gtxxsmglbo.html

void inc(int &x) { ++x; }
来源：http://dali.ybcxt.top/Article/details/gtdshpqbhd.html

[S45] C++：lambda
来源：http://dali.ehwqpu.com/Article/details/gtxmryvnco.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yanxiufei.cn/Article/details/gtyaucihau.html

[S46] C++：函数模板
来源：http://dali.haohaochexian.top/Article/details/gtkebpfumk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.redwolf501.top/Article/details/gtrwqvlgud.html

[S47] C++：结构化绑定遍历
来源：http://dali.cucudq.cn/Article/details/gtcfrrubvy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.vqdsnc.cn/Article/details/gtosrhmgwj.html

[S48] C++：逐行读文件
来源：http://dali.dashuyun.cn/Article/details/gtvusugfrs.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.aizwys.cn/Article/details/gtmbwzhfti.html

while (std::getline(in, line)) { }
来源：http://dali.yj20258888.top/Article/details/gtcqfltkut.html

[S49] C++：写文件
来源：http://dali.wangdashe.top/Article/details/gtkzomlkve.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinqigufen.top/Article/details/gtyalvnykx.html

[S50] C++：格式化数字
来源：http://dali.9152youxi.cn/Article/details/gtfkuxyvec.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gtkwqtvwlk.html

[S51] C++：显式类型转换
来源：http://dali.aizwys.cn/Article/details/gtlctwnubh.html

static_cast<double>(a) / b
来源：http://dali.redwolf501.top/Article/details/gtyuzkgivn.html

[S52] C++：const 与 noexcept
来源：http://dali.ehwqpu.com/Article/details/gtlheoujgi.html

int size() const noexcept { return n_; }
来源：http://dali.yueranfly.top/Article/details/gtbpjwpalz.html

[S53] C++：移动语义
来源：http://dali.havefunace.top/Article/details/gtgnmombgb.html

std::vector<int> w = std::move(v);
来源：http://dali.chenzaomai.com/Article/details/gtvbnlginv.html

[S54] C++：异常处理
来源：http://dali.jianghu66.top/Article/details/gtxvtffsyj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cdnleiting.top/Article/details/gtmfjolftv.html

[S55] C++：结构化绑定
来源：http://dali.dashuyun.cn/Article/details/gtwhjpxpjx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shuidangran.top/Article/details/gtxvqrszym.html

[S56] C++：optional
来源：http://dali.yj20258.top/Article/details/gtdqcgntgz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.meibo888.top/Article/details/gtmarozbpu.html

[S57] C++：编译期常量
来源：http://dali.quarkkingdee.top/Article/details/gtnugpnvbi.html

constexpr int N = 10;
来源：http://dali.yj202588.top/Article/details/gtjejhmwkd.html

[S58] C++：命名空间
来源：http://dali.chenlongwang.top/Article/details/gtzbipuayy.html

namespace ns { int f() { return 1; } }
来源：http://dali.yvedp.cn/Article/details/gtfgjsxsrr.html

[S59] C++：静态断言
来源：http://dali.yuxming.cn/Article/details/gtybzafomb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shuidangran.top/Article/details/gttvfjegvy.html

[S60] C++：遍历并删除元素
来源：http://dali.jianghu66.top/Article/details/gtdkkfwxzg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.tanke756.top/Article/details/gtobkfyaey.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gthypwxxew.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.daria6918.cn/Article/details/gtujheqdbw.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtkwhjwipi.html

[T01] Kotlin：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtcprbzqji.html

println("Hello")
来源：http://dali.jyoumei.cn/Article/details/gtthidisir.html

[T02] Kotlin：变量
来源：http://dali.fengsongda.top/Article/details/gteuvgukak.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdfqwujoe.html

[T03] Kotlin：字符串模板
来源：http://dali.ybcxt.top/Article/details/gtwlxzhsqp.html

"值: $b"
来源：http://dali.wangdashe.top/Article/details/gtnqfabdba.html

[T04] Kotlin：空安全
来源：http://dali.gogol.net.cn/Article/details/gtatqxtjel.html

val n: String? = null;  n?.length
来源：http://dali.havefunace.top/Article/details/gtwmpjnpxp.html

[T05] Kotlin：when 表达式
来源：http://dali.mhx1999.top/Article/details/gtiltbcsmc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.tianlin.xyz/Article/details/gtiueunecp.html

[T06] Kotlin：集合映射
来源：http://dali.smart0.xyz/Article/details/gtohteuyca.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.sysykeji.top/Article/details/gtyqiyuwtx.html

[T07] Kotlin：集合过滤
来源：http://dali.c1oappe.top/Article/details/gtostqxidl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.feifeiyinyue.top/Article/details/gtnmmyqozf.html

[T08] Kotlin：数据类
来源：http://dali.wangshuangyany.cn/Article/details/gtxkazxcov.html

data class User(val name: String, val age: Int)
来源：http://dali.haohaochexian.top/Article/details/gtaiszljum.html

[T09] Kotlin：扩展函数
来源：http://dali.feifeiyinyue.top/Article/details/gtreqwbqgp.html

fun String.exclaim() = this + "!"
来源：http://dali.gogol.net.cn/Article/details/gtjcrlacxo.html

[T10] Kotlin：默认参数
来源：http://dali.yj20258888.top/Article/details/gtloljrllp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yuanzhike.top/Article/details/gtciaqajhf.html

[T11] Kotlin：协程
来源：http://dali.cdnleiting.top/Article/details/gtfbilgyqq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.dianchejie.cn/Article/details/gtfyfafunn.html

[T12] Kotlin：解构声明
来源：http://dali.nanxuanxn.top/Article/details/gtmxxazoew.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuuexxypk.html

[T13] Kotlin：只读 Map
来源：http://dali.yangfankeji.com/Article/details/gtmxzktmhs.html

val m = mapOf("a" to 1)
来源：http://dali.aibaodan.cn/Article/details/gtibyfqiyy.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gtlrwhpixs.html

for (i in 1..10) println(i)
来源：http://dali.nanxuanxn.top/Article/details/gtlglxuoxs.html

[T15] Kotlin：接口
来源：http://dali.daria6918.cn/Article/details/gtxkqcdnto.html

interface Shape { fun area(): Double }
来源：http://dali.0kj1m.cn/Article/details/gtrpuepezf.html

[T16] Swift：Hello World
来源：http://dali.birdmap.top/Article/details/gtmymvppvx.html

print("Hello")
来源：http://dali.c1oappe.top/Article/details/gttxxapmzm.html

[T17] Swift：变量与常量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtljdftxcr.html

var a = 1;  let b = 2
来源：http://dali.0kj1m.cn/Article/details/gtdnvbiplu.html

[T18] Swift：字符串插值
来源：http://dali.birdmap.top/Article/details/gtdfdmpnkt.html

"值: \(b)"
来源：http://dali.cdnleiting.top/Article/details/gtwzjvzndv.html

[T19] Swift：可选绑定
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmtvehayb.html

if let n = opt { print(n) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtelzwiwfe.html

[T20] Swift：数组操作
来源：http://dali.zhiwuduotai.top/Article/details/gtqxsgwhco.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gtopfhscwe.html

[T21] Swift：遍历
来源：http://dali.gzhubu.top/Article/details/gtjjdfvpwv.html

for x in a { print(x) }
来源：http://dali.tian-w.cn/Article/details/gtiyeywfkj.html

[T22] Swift：字典
来源：http://dali.zhengqikj.top/Article/details/gtbjllnvon.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xinyue.icu/Article/details/gteggjwssf.html

[T23] Swift：函数
来源：http://dali.yongpay.top/Article/details/gtwgigpsrz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shangyingyoupin.top/Article/details/gtpzonanfw.html

[T24] Swift：闭包
来源：http://dali.cdnleiting.top/Article/details/gtgiqepniz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.c1oappe.top/Article/details/gtwmkmqwcg.html

[T25] Swift：结构体
来源：http://dali.hywenlv.cn/Article/details/gtofmqznjl.html

struct P { var x: Int }
来源：http://dali.wangshuangyany.cn/Article/details/gtcchxcpii.html

[T26] Swift：类与重写
来源：http://dali.hammf.cn/Article/details/gtnmupqkgr.html

class A: Base { override func f() {} }
来源：http://dali.sweek.top/Article/details/gtqimpzztm.html

[T27] Swift：错误处理
来源：http://dali.vqdsnc.cn/Article/details/gtqqhwkyuu.html

do { try f() } catch { print(error) }
来源：http://dali.xinyue.icu/Article/details/gtxzjyrwjp.html

[T28] Swift：枚举
来源：http://dali.shzxlz.cn/Article/details/gtgejquxrl.html

enum Color { case red, green }
来源：http://dali.zdqjudy.top/Article/details/gtjkdujusn.html

[T29] Swift：guard 提前返回
来源：http://dali.havefunace.top/Article/details/gthrowvdlh.html

guard let x = opt else { return }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbmglpwsw.html

[T30] Swift：协议
来源：http://dali.gaohongyu789.top/Article/details/gtanzdnajx.html

protocol Shape { func area() -> Double }
来源：http://dali.guannengcc.top/Article/details/gtkwkkxngi.html

[T31] Lua：Hello World
来源：http://dali.0kj1m.cn/Article/details/gtegqwslgl.html

print("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gtwytjdnze.html

[T32] Lua：局部变量
来源：http://dali.xuetiantiany.cn/Article/details/gtddrcmycr.html

local a = 1
来源：http://dali.tanke756.top/Article/details/gtqlqyrfhw.html

[T33] Lua：表（数组）
来源：http://dali.nwbrower.top/Article/details/gttywazmoy.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinqigufen.top/Article/details/gtsfjpyztg.html

[T34] Lua：遍历表
来源：http://dali.xziqi.cn/Article/details/gtvkzdygcb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jianghu66.top/Article/details/gtvwgpagpf.html

[T35] Lua：字典表
来源：http://dali.chenlongwang.top/Article/details/gtavdtukip.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yuxming.cn/Article/details/gtywjwefqz.html

[T36] Lua：函数
来源：http://dali.hongshengwenyu.top/Article/details/gtivqzjiow.html

function add(a, b) return a + b end
来源：http://dali.yuanzhike.top/Article/details/gtmvwariaq.html

[T37] Lua：字符串拼接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjkxjhugx.html

"a" .. "b"
来源：http://dali.c1oappe.top/Article/details/gtkzvupvld.html

[T38] Lua：条件
来源：http://dali.ehwqpu.com/Article/details/gtezbwqepl.html

if x > 0 then print("正") end
来源：http://dali.9152youxi.cn/Article/details/gtxqylmdyz.html

[T39] Lua：模式匹配
来源：http://dali.yvedp.cn/Article/details/gtdcqamzyp.html

string.find(s, "%d+")
来源：http://dali.nanxuanxn.top/Article/details/gtroyqzkra.html

[T40] Lua：元表
来源：http://dali.xziqi.cn/Article/details/gtzlgkyywg.html

setmetatable({}, { __index = base })
来源：http://dali.birdmap.top/Article/details/gtqhoqrtoz.html

[T41] Perl：Hello World
来源：http://dali.tanke756.top/Article/details/gtdhklpbwk.html

print "Hello\n";
来源：http://dali.chenlongwang.top/Article/details/gthtmormrd.html

[T42] Perl：变量类型
来源：http://dali.316326.xyz/Article/details/gtcdsktmas.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hongshengwenyu.top/Article/details/gtbvqtfsck.html

[T43] Perl：字符串插值
来源：http://dali.redwolf501.top/Article/details/gthxgafcoj.html

"值: $a"
来源：http://dali.guowangkeji.top/Article/details/gtywtqsqwg.html

[T44] Perl：条件
来源：http://dali.daria6918.cn/Article/details/gtkafiayhe.html

if ($a > 0) { print "正"; }
来源：http://dali.snrcjt.cn/Article/details/gthcjqlypk.html

[T45] Perl：数组遍历
来源：http://dali.yvedp.cn/Article/details/gtbpiofzyt.html

for my $x (@arr) { print $x; }
来源：http://dali.dianchejie.cn/Article/details/gtzponamue.html

[T46] Perl：哈希操作
来源：http://dali.fengsongda.top/Article/details/gtwsicrwoz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtgmfirofn.html

[T47] Perl：正则捕获
来源：http://dali.yueranfly.top/Article/details/gtxmkxpxex.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.sxryk.cn/Article/details/gtrbvifdqh.html

[T48] Perl：正则替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiovosygq.html

$s =~ s/old/new/g;
来源：http://dali.jinqigfzy.top/Article/details/gtkmrbebzx.html

[T49] Perl：函数
来源：http://dali.snrcjt.cn/Article/details/gtlavwnaca.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hnxiangtu.top/Article/details/gtqxkkrfav.html

[T50] Perl：逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gtytdnqcns.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jinqigfzy.top/Article/details/gthvaqkpmo.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.shzxlz.cn/Article/details/gtvqadszyg.html

[T51] Scala：Hello World
来源：http://dali.hysaishi.cn/Article/details/gtiaugglzi.html

println("Hello")
来源：http://dali.birdmap.top/Article/details/gtwqbifjox.html

[T52] Scala：变量
来源：http://dali.sufxvd.cn/Article/details/gtlrgbbotz.html

val a = 1;  var b = 2
来源：http://dali.yangfankeji.com/Article/details/gtnjqxajho.html

[T53] Scala：字符串插值
来源：http://dali.cqqwz.cn/Article/details/gtzrsvpwei.html

s"值: $b"
来源：http://dali.zycfv.cn/Article/details/gtvozudfrs.html

[T54] Scala：集合映射
来源：http://dali.redwolf501.top/Article/details/gtcjjejzzc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.c1oappe.top/Article/details/gtjnpxanex.html

[T55] Scala：集合过滤
来源：http://dali.jlsjyb.cn/Article/details/gtidtzxmzm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.meibo888.top/Article/details/gtgywvvezx.html

[T56] Scala：样例类
来源：http://dali.shuidangran.top/Article/details/gtvjbgaikj.html

case class User(name: String, age: Int)
来源：http://dali.andypj.xyz/Article/details/gtfubotvdw.html

[T57] Scala：模式匹配
来源：http://dali.hnqzz.top/Article/details/gtfwhwedlz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.tian-w.cn/Article/details/gtreyjpnfg.html

[T58] Scala：函数定义
来源：http://dali.pengpengdd.cyou/Article/details/gtmtqewcun.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yanxiufei.cn/Article/details/gthxhgmihh.html

[T59] Scala：循环
来源：http://dali.chenlongwang.top/Article/details/gthkagpwuu.html

for (i <- 1 to 10) println(i)
来源：http://dali.yj202588.top/Article/details/gtuvgeslok.html

[T60] Scala：折叠
来源：http://dali.shuidangran.top/Article/details/gticzsjgju.html


<!-- 参考信息 -->