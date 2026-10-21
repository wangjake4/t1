代发 wailian999

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.tian-w.cn/Article/details/gteqttndxe.html

[R52] 统计行数
来源：http://dali.ydzc1.top/Article/details/gtrmmwlpbs.html

wc -l a.txt
来源：http://dali.chenlongwang.top/Article/details/gtwhjibpig.html

[R53] 查看文件头与实时尾
来源：http://dali.hammf.cn/Article/details/gtqrxzirnr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.daria6918.cn/Article/details/gtcnfbdbuq.html

[R54] 比较两个文件
来源：http://dali.cashguo.top/Article/details/gttdrvoudy.html

diff a.txt b.txt
来源：http://dali.xuanzx.com/Article/details/gtwjvbeeqh.html

[R55] 压缩与解压
来源：http://dali.daxiang520.top/Article/details/gtyaptzbyn.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhixingplan.top/Article/details/gtmjtwfywl.html

[R56] 远程拷贝
来源：http://dali.shangyingyoupin.top/Article/details/gthjveizeb.html

scp file user@host:/path/
来源：http://dali.andypj.xyz/Article/details/gtviyydnhp.html

[R57] 远程执行命令
来源：http://dali.nanxinkj.top/Article/details/gtdlcixuhp.html

ssh user@host 'uptime'
来源：http://dali.nanxinkj.top/Article/details/gthxaydzso.html

[R58] 下载文件
来源：http://dali.chenzaomai.com/Article/details/gtyaziejwx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jinyuanbaomall.cn/Article/details/gtczkabplq.html

[R59] 发 POST JSON
来源：http://dali.birdmap.top/Article/details/gtmcocqqeu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.9152youxi.cn/Article/details/gtuxqdxqip.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinghuilouyu.cn/Article/details/gtzqtprsfo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gogol.net.cn/Article/details/gtjcsyhacz.html

[R61] 磁盘占用
来源：http://dali.xziqi.cn/Article/details/gtakymgceq.html

df -h;  du -sh *
来源：http://dali.tian-w.cn/Article/details/gthwfcpzcd.html

[R62] 找最占空间的文件
来源：http://dali.jinqigufen.top/Article/details/gtxadblcri.html

du -ah . | sort -rh | head -10
来源：http://dali.yvedp.cn/Article/details/gtqhcnviyb.html

[R63] 内存与进程
来源：http://dali.cheryme.top/Article/details/gtpsestdqg.html

free -h;  ps aux | grep nginx
来源：http://dali.ehwqpu.com/Article/details/gtyppkjqko.html

[R64] 结束进程
来源：http://dali.sysykeji.top/Article/details/gtdqzrwhqh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shzxlz.cn/Article/details/gtugejadqm.html

[R65] 查看端口占用
来源：http://dali.cdnleiting.top/Article/details/gthcmxinks.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xinyue.icu/Article/details/gtiprwsymq.html

[R66] 定时任务
来源：http://dali.sufxvd.cn/Article/details/gtxluskgag.html

crontab -e;  crontab -l
来源：http://dali.zhongyouzk.top/Article/details/gtqkgionvi.html

[R67] 生成随机十六进制串
来源：http://dali.cdnleiting.top/Article/details/gtxmasygzj.html

openssl rand -hex 16
来源：http://dali.jianghu66.top/Article/details/gteulyyvcz.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gtrnvkdwoc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.iojbl.cn/Article/details/gtjownubpr.html

[R69] 生成随机密码
来源：http://dali.cashguo.top/Article/details/gtophdnqpb.html

head -c 16 /dev/urandom | base64
来源：http://dali.cqqwz.cn/Article/details/gtlmtcgejp.html

[R70] 时间戳与互转
来源：http://dali.hammf.cn/Article/details/gtuhtmelcl.html

date +%s;  date -d @1700000000
来源：http://dali.bjfxy.top/Article/details/gtbmjhvnpl.html

[R71] 日期格式化
来源：http://dali.shzxlz.cn/Article/details/gtughqmgql.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj202588.top/Article/details/gtrqzhwjan.html

[R72] 等待端口就绪
来源：http://dali.haohaochexian.top/Article/details/gtgxsobggr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.smart0.xyz/Article/details/gtaupwikvo.html

[R73] 分割大日志
来源：http://dali.yanxiufei.cn/Article/details/gtytstflvt.html

split -l 1000 big.log part_
来源：http://dali.fzhhl.top/Article/details/gtolvcdqra.html

[R74] 批量重命名
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwyxxkidu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ppjwa.cn/Article/details/gtxuwkcsjz.html

[R75] 导出环境变量
来源：http://dali.316326.xyz/Article/details/gtoujfqcpu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cucudq.cn/Article/details/gtwczsicab.html

[R76] 使用临时文件
来源：http://dali.meibo888.top/Article/details/gtfkdkozor.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhongyouzk.top/Article/details/gtxcirdton.html

[R77] 读取用户输入
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlimmhxig.html

read -rp "请输入: " ans
来源：http://dali.yangfankeji.com/Article/details/gtohmvusjc.html

[R78] 交互式菜单
来源：http://dali.daria6918.cn/Article/details/gtiubufxyo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hfpthk.cn/Article/details/gtrjyndeon.html

[R79] 解析命令行选项
来源：http://dali.hfpthk.cn/Article/details/gtmkforazp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhengqikj.top/Article/details/gtwxxulluo.html

[R80] 查看脚本执行耗时
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvrbfdvni.html

time ./run.sh
来源：http://dali.hammf.cn/Article/details/gtengyoorg.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gteqaltdar.html

S. C / C++ 专题
来源：http://dali.iojbl.cn/Article/details/gtndaeguxq.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtnajbdhwg.html

[S01] C：Hello World
来源：http://dali.xylfe.cn/Article/details/gtfaqqxnqv.html

#include <stdio.h>
来源：http://dali.sufxvd.cn/Article/details/gtatrpvwhd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shuidangran.top/Article/details/gtayxqevto.html

[S02] C：变量与格式化输出
来源：http://dali.tianlin.xyz/Article/details/gtfwgwmiet.html

int a = 10; printf("%d\n", a);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpsojzkmz.html

[S03] C：读入整数
来源：http://dali.ppjwa.cn/Article/details/gtroldvmbl.html

int x; scanf("%d", &x);
来源：http://dali.cheryme.top/Article/details/gtsjlfeorg.html

[S04] C：字符串复制
来源：http://dali.guannengcc.top/Article/details/gteyyngjar.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.wangdashe.top/Article/details/gtkgogcpuq.html

[S05] C：字符串长度
来源：http://dali.hysaishi.cn/Article/details/gtpmbkmfgd.html

strlen(s)
来源：http://dali.nanxinkj.top/Article/details/gtrpupnckm.html

[S06] C：字符串比较
来源：http://dali.zhengqikj.top/Article/details/gtvisxsoic.html

strcmp(a, b) == 0
来源：http://dali.yj20258888.top/Article/details/gtazgqspks.html

[S07] C：数组遍历求和
来源：http://dali.feifeiyinyue.top/Article/details/gttfotbogr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.iojbl.cn/Article/details/gtsqouvnnw.html

[S08] C：动态内存分配与释放
来源：http://dali.haohaochexian.top/Article/details/gtbyqspeoc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gotoacloud.top/Article/details/gtdycwzmrd.html

[S09] C：结构体定义与初始化
来源：http://dali.daxiang520.top/Article/details/gtmhouxmge.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinghuilouyu.cn/Article/details/gtssvpmnjn.html

[S10] C：指针与解引用
来源：http://dali.cdnleiting.top/Article/details/gtjidfjjoz.html

int *p = &a;  *p = 5;
来源：http://dali.hongshengwenyu.top/Article/details/gtrmqnpgko.html

[S11] C：逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gtqbdducjy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtioqskxdo.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jqgfzy.top/Article/details/gtfwhocqbs.html

fclose(f);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmwamggsr.html

[S12] C：写文件
来源：http://dali.cqqwz.cn/Article/details/gtxfoukrpc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sysykeji.top/Article/details/gtyckkeebi.html

[S13] C：宏定义
来源：http://dali.yanxiufei.cn/Article/details/gtaayscjyu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.chenjidiqi.icu/Article/details/gtmqbmuirz.html

[S14] C：枚举
来源：http://dali.tian-w.cn/Article/details/gtoflmkycy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgoggkdjy.html

[S15] C：类型转换
来源：http://dali.zhixingplan.top/Article/details/gtagcpbuvd.html

(double) a / b
来源：http://dali.tanke756.top/Article/details/gtjkfrxyjx.html

[S16] C：位操作置位
来源：http://dali.nwbrower.top/Article/details/gtatnjgaiw.html

x |= (1 << 3);
来源：http://dali.kuanghao11.cn/Article/details/gtyxbrgkdt.html

[S17] C：安全拼接字符串
来源：http://dali.xinyue.icu/Article/details/gtjewxizyn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hywenlv.cn/Article/details/gtmljlhpxh.html

[S18] C：命令行参数
来源：http://dali.xziqi.cn/Article/details/gtewxvdfyw.html

int main(int argc, char **argv)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrqkogcfe.html

[S19] C：快速排序
来源：http://dali.shuidangran.top/Article/details/gtmnofhjkr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zycfv.cn/Article/details/gtaamanqpo.html

[S20] C：二分查找
来源：http://dali.fengsongda.top/Article/details/gtceneanhn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhixingplan.top/Article/details/gtprsabybw.html

[S21] C：字符类别判断
来源：http://dali.xinyue.icu/Article/details/gtchvmwjfl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sxryk.cn/Article/details/gtoninaqxy.html

[S22] C：字符串转数字
来源：http://dali.shangyingyoupin.top/Article/details/gtvsprhehy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.nwbrower.top/Article/details/gtmztmjbqg.html

[S23] C：随机数
来源：http://dali.xuanzx.com/Article/details/gtvqjlzdwu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtizadqdeb.html

[S24] C：获取本地时间
来源：http://dali.gogol.net.cn/Article/details/gtydbkyzup.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.kuanghao11.cn/Article/details/gtknetujor.html

[S25] C：内存拷贝
来源：http://dali.nanxinkj.top/Article/details/gtfsemwhyb.html

memcpy(dst, src, n);
来源：http://dali.wangdashe.top/Article/details/gtzgkgphab.html

[S26] C：内存清零
来源：http://dali.0kj1m.cn/Article/details/gtvgbotqen.html

memset(a, 0, sizeof a);
来源：http://dali.yuxming.cn/Article/details/gtkvcqalcp.html

[S27] C：定义常量
来源：http://dali.xinyue.icu/Article/details/gtpgmhpqkx.html

const double PI = 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gtuzzigtdy.html

[S28] C：静态变量
来源：http://dali.cqqwz.cn/Article/details/gtgsxvbvxq.html

static int counter = 0;
来源：http://dali.svipenyu.cn/Article/details/gtdfbctfzu.html

[S29] C：变参函数
来源：http://dali.0kj1m.cn/Article/details/gtcljebqyh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.svipenyu.cn/Article/details/gtzmoohxhl.html

[S30] C：头文件保护
来源：http://dali.cucudq.cn/Article/details/gtrhnpukff.html

#ifndef X_H
来源：http://dali.yongpay.top/Article/details/gtynznfsga.html

#define X_H
来源：http://dali.andypj.xyz/Article/details/gtjrxtusew.html

#endif
来源：http://dali.svipenyu.cn/Article/details/gtterhqpog.html

[S31] C++：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtrlpdbblv.html

#include <iostream>
来源：http://dali.sxryk.cn/Article/details/gtjislljxi.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.vqdsnc.cn/Article/details/gtqmldplll.html

[S32] C++：字符串
来源：http://dali.316326.xyz/Article/details/gttagbrkkn.html

std::string s = "hi";  s += "!";
来源：http://dali.sysykeji.top/Article/details/gtfjrouang.html

[S33] C++：vector 增删
来源：http://dali.shuidangran.top/Article/details/gtzknsxxcf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hongshengwenyu.top/Article/details/gtfmpdgany.html

[S34] C++：遍历 vector
来源：http://dali.zhoulong.xyz/Article/details/gtrlimcvqw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cucudq.cn/Article/details/gtcitiehko.html

[S35] C++：map
来源：http://dali.9152youxi.cn/Article/details/gtxjvkphjd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yueranfly.top/Article/details/gtwckvvzxs.html

[S36] C++：unordered_map
来源：http://dali.jinghuilouyu.cn/Article/details/gtpfmfmhly.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.smart0.xyz/Article/details/gttusftldm.html

[S37] C++：set
来源：http://dali.zhiwuduotai.top/Article/details/gtuiepwlkh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.daxiang520.top/Article/details/gtkbynnpfu.html

[S38] C++：排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gtotdcqbeg.html

std::sort(v.begin(), v.end());
来源：http://dali.sweek.top/Article/details/gtktovdpzb.html

[S39] C++：自定义比较器排序
来源：http://dali.yuxming.cn/Article/details/gtpzhcajhd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.pycfn.com/Article/details/gtzjrikzpu.html

[S40] C++：查找元素
来源：http://dali.kuanghao11.cn/Article/details/gtultiomer.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.chenlongwang.top/Article/details/gtzawfvtik.html

[S41] C++：类与构造函数
来源：http://dali.316326.xyz/Article/details/gtdmjnhrlt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.wangshuangyany.cn/Article/details/gtsllqdkmj.html

[S42] C++：继承与虚函数
来源：http://dali.jyoumei.cn/Article/details/gtmftmcsvk.html

class B : public Base { public: void f() override {} };
来源：http://dali.birdmap.top/Article/details/gtpmciiwji.html

[S43] C++：智能指针
来源：http://dali.aizwys.cn/Article/details/gtwabupyto.html

auto p = std::make_unique<int>(5);
来源：http://dali.jyoumei.cn/Article/details/gtqyknawfg.html

[S44] C++：引用传参
来源：http://dali.tianlin.xyz/Article/details/gtwymgkajn.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gtxpjrxdft.html

[S45] C++：lambda
来源：http://dali.birdmap.top/Article/details/gtjyetpmhj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.tianlin.xyz/Article/details/gtspgjdrlp.html

[S46] C++：函数模板
来源：http://dali.fengsongda.top/Article/details/gtfyfsgeoc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.svipenyu.cn/Article/details/gtirfvkpbo.html

[S47] C++：结构化绑定遍历
来源：http://dali.yj202588.top/Article/details/gtsjejrkjz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.fzhhl.top/Article/details/gtjruxartz.html

[S48] C++：逐行读文件
来源：http://dali.aibaodan.cn/Article/details/gtycfwmmtk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yueranfly.top/Article/details/gtxvjwjtmp.html

while (std::getline(in, line)) { }
来源：http://dali.yuanzhike.top/Article/details/gtnmhqjspb.html

[S49] C++：写文件
来源：http://dali.wangshuangyany.cn/Article/details/gtgteghmet.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zdqjudy.top/Article/details/gtjxccvcga.html

[S50] C++：格式化数字
来源：http://dali.chenzaomai.com/Article/details/gtaywvbauk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hammf.cn/Article/details/gttlzchfgi.html

[S51] C++：显式类型转换
来源：http://dali.ybcxt.top/Article/details/gtquysqnsg.html

static_cast<double>(a) / b
来源：http://dali.yuxming.cn/Article/details/gtqipgkhxq.html

[S52] C++：const 与 noexcept
来源：http://dali.shzxlz.cn/Article/details/gtpjjoonqr.html

int size() const noexcept { return n_; }
来源：http://dali.nanxinkj.top/Article/details/gtpxiozrzq.html

[S53] C++：移动语义
来源：http://dali.ybcxt.top/Article/details/gtajkxugsb.html

std::vector<int> w = std::move(v);
来源：http://dali.pycfn.com/Article/details/gtpryfqxvl.html

[S54] C++：异常处理
来源：http://dali.0kj1m.cn/Article/details/gtyzvbubap.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cheryme.top/Article/details/gtgnahhhbh.html

[S55] C++：结构化绑定
来源：http://dali.wangshuangyany.cn/Article/details/gtjzmqinjs.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shuidangran.top/Article/details/gtqcrzfyzd.html

[S56] C++：optional
来源：http://dali.daxiang520.top/Article/details/gtitdvptyw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkkvfpxuf.html

[S57] C++：编译期常量
来源：http://dali.ehwqpu.com/Article/details/gtlpcnkdwn.html

constexpr int N = 10;
来源：http://dali.dianchejie.cn/Article/details/gttlktazrj.html

[S58] C++：命名空间
来源：http://dali.zhoulong.xyz/Article/details/gtyguditsw.html

namespace ns { int f() { return 1; } }
来源：http://dali.mhx1999.top/Article/details/gtdempsdzm.html

[S59] C++：静态断言
来源：http://dali.hammf.cn/Article/details/gtpvpebwvp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cdnleiting.top/Article/details/gtshtugcgz.html

[S60] C++：遍历并删除元素
来源：http://dali.zhiwuduotai.top/Article/details/gtyrxwrpkx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.fengsongda.top/Article/details/gtuxtsybie.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtdofqfraf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tian-w.cn/Article/details/gtzrqcirer.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtdoqvsbtp.html

[T01] Kotlin：Hello World
来源：http://dali.jinqigufen.top/Article/details/gteirrnodt.html

println("Hello")
来源：http://dali.shanyushiyangtech.top/Article/details/gtxnhilwoh.html

[T02] Kotlin：变量
来源：http://dali.daria6918.cn/Article/details/gtgexxhmwu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.tanke756.top/Article/details/gtpxpiejrd.html

[T03] Kotlin：字符串模板
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlafovwcz.html

"值: $b"
来源：http://dali.hnqzz.top/Article/details/gtgnbmshtd.html

[T04] Kotlin：空安全
来源：http://dali.cdnleiting.top/Article/details/gtorjzfsad.html

val n: String? = null;  n?.length
来源：http://dali.zhixingplan.top/Article/details/gthsropjrd.html

[T05] Kotlin：when 表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gtcyiwwjuo.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ydzc1.top/Article/details/gtuuaxledh.html

[T06] Kotlin：集合映射
来源：http://dali.ppjwa.cn/Article/details/gtdxthnpmf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yvedp.cn/Article/details/gtocxknclr.html

[T07] Kotlin：集合过滤
来源：http://dali.jianghu66.top/Article/details/gtcpjtjzta.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cheryme.top/Article/details/gtcyobiuro.html

[T08] Kotlin：数据类
来源：http://dali.shuidangran.top/Article/details/gtertphdbc.html

data class User(val name: String, val age: Int)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtagqowfxc.html

[T09] Kotlin：扩展函数
来源：http://dali.feifeiyinyue.top/Article/details/gtxshlieig.html

fun String.exclaim() = this + "!"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnewpxuvj.html

[T10] Kotlin：默认参数
来源：http://dali.iojbl.cn/Article/details/gtgommqjdv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yvedp.cn/Article/details/gtqnxhvelm.html

[T11] Kotlin：协程
来源：http://dali.snrcjt.cn/Article/details/gtsbyyiepb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xuanzx.com/Article/details/gtzsppzvts.html

[T12] Kotlin：解构声明
来源：http://dali.guowangkeji.top/Article/details/gtjusfnhbz.html

val (a, b) = Pair(1, 2)
来源：http://dali.ppjwa.cn/Article/details/gtkheftsll.html

[T13] Kotlin：只读 Map
来源：http://dali.yuxming.cn/Article/details/gtdengfuwh.html

val m = mapOf("a" to 1)
来源：http://dali.shzxlz.cn/Article/details/gtupeiyzyg.html

[T14] Kotlin：循环
来源：http://dali.9152youxi.cn/Article/details/gttgmhiuwr.html

for (i in 1..10) println(i)
来源：http://dali.quarkkingdee.top/Article/details/gtxfmdifqf.html

[T15] Kotlin：接口
来源：http://dali.jianghu66.top/Article/details/gtakejbigq.html

interface Shape { fun area(): Double }
来源：http://dali.dashuyun.cn/Article/details/gtftcyngnl.html

[T16] Swift：Hello World
来源：http://dali.aizwys.cn/Article/details/gtmwijjuka.html

print("Hello")
来源：http://dali.gogol.net.cn/Article/details/gtzcargnsh.html

[T17] Swift：变量与常量
来源：http://dali.feifeiyinyue.top/Article/details/gtmxpknqrn.html

var a = 1;  let b = 2
来源：http://dali.daxiang520.top/Article/details/gtamxvuuzd.html

[T18] Swift：字符串插值
来源：http://dali.hammf.cn/Article/details/gtlfwzqjmc.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gtiderxvcs.html

[T19] Swift：可选绑定
来源：http://dali.ybcxt.top/Article/details/gtmvosfxlw.html

if let n = opt { print(n) }
来源：http://dali.zdqjudy.top/Article/details/gtpgtfcrol.html

[T20] Swift：数组操作
来源：http://dali.hnqzz.top/Article/details/gtlwikqhuk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.daria6918.cn/Article/details/gtmgmtubbt.html

[T21] Swift：遍历
来源：http://dali.yonumen.top/Article/details/gtcyrwdyvr.html

for x in a { print(x) }
来源：http://dali.zdqjudy.top/Article/details/gtozhnyduk.html

[T22] Swift：字典
来源：http://dali.xuanzx.com/Article/details/gtljpleyyf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hfpthk.cn/Article/details/gtmarwjncd.html

[T23] Swift：函数
来源：http://dali.xinyue.icu/Article/details/gtnuqkcrso.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.nanxinkj.top/Article/details/gtcnqsbaed.html

[T24] Swift：闭包
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmcyolbnu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ivvv.top/Article/details/gtitwvzqsf.html

[T25] Swift：结构体
来源：http://dali.haohaochexian.top/Article/details/gtoaixmpno.html

struct P { var x: Int }
来源：http://dali.chenlongwang.top/Article/details/gtrptrxpwx.html

[T26] Swift：类与重写
来源：http://dali.hnxiangtu.top/Article/details/gtfnctsikp.html

class A: Base { override func f() {} }
来源：http://dali.xuanzx.com/Article/details/gthomcxolt.html

[T27] Swift：错误处理
来源：http://dali.tianlin.xyz/Article/details/gtzckoiupu.html

do { try f() } catch { print(error) }
来源：http://dali.cashguo.top/Article/details/gtfwtjcrep.html

[T28] Swift：枚举
来源：http://dali.gotoacloud.top/Article/details/gtbitinayb.html

enum Color { case red, green }
来源：http://dali.xziqi.cn/Article/details/gtcdlrbass.html

[T29] Swift：guard 提前返回
来源：http://dali.jinghuilouyu.cn/Article/details/gtycsiypii.html

guard let x = opt else { return }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbrnixdlo.html

[T30] Swift：协议
来源：http://dali.sweek.top/Article/details/gtruzqijug.html

protocol Shape { func area() -> Double }
来源：http://dali.hysaishi.cn/Article/details/gtnpbhjdzs.html

[T31] Lua：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gtmhfzsits.html

print("Hello")
来源：http://dali.yj20258.top/Article/details/gtsvekhhcx.html

[T32] Lua：局部变量
来源：http://dali.sxryk.cn/Article/details/gteassdjhh.html

local a = 1
来源：http://dali.jqgufenzy.top/Article/details/gtnrrgrjqp.html

[T33] Lua：表（数组）
来源：http://dali.jlsjyb.cn/Article/details/gtohaibltt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinqigfzy.top/Article/details/gtsvexnbfu.html

[T34] Lua：遍历表
来源：http://dali.aizwys.cn/Article/details/gtmxmblxbj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.bjfxy.top/Article/details/gtxdlygmav.html

[T35] Lua：字典表
来源：http://dali.yangfankeji.com/Article/details/gtqvwmzwgx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jlsjyb.cn/Article/details/gthvfaybdw.html

[T36] Lua：函数
来源：http://dali.ybcxt.top/Article/details/gtaepqlwic.html

function add(a, b) return a + b end
来源：http://dali.ppjwa.cn/Article/details/gtkcbjotxr.html

[T37] Lua：字符串拼接
来源：http://dali.hammf.cn/Article/details/gtktfrscgo.html

"a" .. "b"
来源：http://dali.yangfankeji.com/Article/details/gtqsiqokdv.html

[T38] Lua：条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwyqlnnhx.html

if x > 0 then print("正") end
来源：http://dali.nwbrower.top/Article/details/gtuficmiuy.html

[T39] Lua：模式匹配
来源：http://dali.shzxlz.cn/Article/details/gtxgjikuah.html

string.find(s, "%d+")
来源：http://dali.xinyue.icu/Article/details/gtpvrwlthg.html

[T40] Lua：元表
来源：http://dali.dashuyun.cn/Article/details/gthnmzigdu.html

setmetatable({}, { __index = base })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxbyxtepq.html

[T41] Perl：Hello World
来源：http://dali.sysykeji.top/Article/details/gtpjtjhyme.html

print "Hello\n";
来源：http://dali.hywenlv.cn/Article/details/gtwgrbjkim.html

[T42] Perl：变量类型
来源：http://dali.tianlin.xyz/Article/details/gtkziwukhx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.haohaochexian.top/Article/details/gtwohnklkn.html

[T43] Perl：字符串插值
来源：http://dali.fengsongda.top/Article/details/gtdcmerzyl.html

"值: $a"
来源：http://dali.jinqigfzy.top/Article/details/gtvrukzalf.html

[T44] Perl：条件
来源：http://dali.daxiang520.top/Article/details/gtuhsknwbj.html

if ($a > 0) { print "正"; }
来源：http://dali.meibo888.top/Article/details/gtfxfpbilf.html

[T45] Perl：数组遍历
来源：http://dali.jlsjyb.cn/Article/details/gtcdolpuxu.html

for my $x (@arr) { print $x; }
来源：http://dali.cashguo.top/Article/details/gtmssffxgr.html

[T46] Perl：哈希操作
来源：http://dali.tian-w.cn/Article/details/gtmjaoeuvh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xinyue.icu/Article/details/gtikajcwxk.html

[T47] Perl：正则捕获
来源：http://dali.shangyingyoupin.top/Article/details/gtmvkgmguu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jinqigfzy.top/Article/details/gtgmpjzeef.html

[T48] Perl：正则替换
来源：http://dali.hysaishi.cn/Article/details/gtjyvnnixd.html

$s =~ s/old/new/g;
来源：http://dali.smart0.xyz/Article/details/gtrrvvxiff.html

[T49] Perl：函数
来源：http://dali.fengsongda.top/Article/details/gthbclyhln.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yongpay.top/Article/details/gtlybgjtha.html

[T50] Perl：逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gtspxkgfdt.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.wangshuangyany.cn/Article/details/gttvgnybbo.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.chenzaomai.com/Article/details/gtcaixtxpr.html

[T51] Scala：Hello World
来源：http://dali.cucudq.cn/Article/details/gtezyneelm.html

println("Hello")
来源：http://dali.havefunace.top/Article/details/gtulusocgy.html

[T52] Scala：变量
来源：http://dali.ivvv.top/Article/details/gtuxfrdnpg.html

val a = 1;  var b = 2
来源：http://dali.guannengcc.top/Article/details/gthooouqac.html

[T53] Scala：字符串插值
来源：http://dali.fzhhl.top/Article/details/gtoyttelsu.html

s"值: $b"
来源：http://dali.daxiang520.top/Article/details/gtwevnqjzj.html

[T54] Scala：集合映射
来源：http://dali.nanxuanxn.top/Article/details/gtzupfvxiw.html


<!-- 参考信息 -->