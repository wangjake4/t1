代发 wailian999

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.havefunace.top/Article/details/gtlmvvajxp.html

[R54] 比较两个文件
来源：http://dali.ehwqpu.com/Article/details/gtuugfwnhw.html

diff a.txt b.txt
来源：http://dali.zhoulong.xyz/Article/details/gtajyklzac.html

[R55] 压缩与解压
来源：http://dali.cdnleiting.top/Article/details/gtrarjcnos.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.316326.xyz/Article/details/gtyaowzudu.html

[R56] 远程拷贝
来源：http://dali.cucudq.cn/Article/details/gtqqytslfa.html

scp file user@host:/path/
来源：http://dali.wangdashe.top/Article/details/gthozhjprk.html

[R57] 远程执行命令
来源：http://dali.dianchejie.cn/Article/details/gtzmnodatm.html

ssh user@host 'uptime'
来源：http://dali.xinyue.icu/Article/details/gtphwishwy.html

[R58] 下载文件
来源：http://dali.tianlin.xyz/Article/details/gtqsqjoscl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yueranfly.top/Article/details/gtkmgufopn.html

[R59] 发 POST JSON
来源：http://dali.shuidangran.top/Article/details/gtrzpknalu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hammf.cn/Article/details/gtiaebiqha.html

[R60] 只看 HTTP 状态码
来源：http://dali.nanxuanxn.top/Article/details/gtexjmwghv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hysaishi.cn/Article/details/gtlhzwdgnt.html

[R61] 磁盘占用
来源：http://dali.daria6918.cn/Article/details/gtwutdvswh.html

df -h;  du -sh *
来源：http://dali.gaohongyu789.top/Article/details/gtjyrauoli.html

[R62] 找最占空间的文件
来源：http://dali.hysaishi.cn/Article/details/gtiefdpwam.html

du -ah . | sort -rh | head -10
来源：http://dali.yuanzhike.top/Article/details/gtjuzzrnss.html

[R63] 内存与进程
来源：http://dali.ehwqpu.com/Article/details/gtltrwbumj.html

free -h;  ps aux | grep nginx
来源：http://dali.gaohongyu789.top/Article/details/gtprlqehxe.html

[R64] 结束进程
来源：http://dali.yonumen.top/Article/details/gtmyjmemek.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cucudq.cn/Article/details/gtuuhpckms.html

[R65] 查看端口占用
来源：http://dali.c1oappe.top/Article/details/gtnruazkjx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.c1oappe.top/Article/details/gttietdksz.html

[R66] 定时任务
来源：http://dali.jqgufenzy.top/Article/details/gtqzhorqzj.html

crontab -e;  crontab -l
来源：http://dali.ydzc1.top/Article/details/gtvbkoqsrt.html

[R67] 生成随机十六进制串
来源：http://dali.hnqzz.top/Article/details/gtznvpfuhb.html

openssl rand -hex 16
来源：http://dali.tian-w.cn/Article/details/gtzfmlyous.html

[R68] 计算文件校验值
来源：http://dali.cucudq.cn/Article/details/gthuxrlfbu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yvedp.cn/Article/details/gtezvkwrqg.html

[R69] 生成随机密码
来源：http://dali.hfpthk.cn/Article/details/gtqkiqlnoh.html

head -c 16 /dev/urandom | base64
来源：http://dali.shuidangran.top/Article/details/gtnzdkdalp.html

[R70] 时间戳与互转
来源：http://dali.fzhhl.top/Article/details/gtyvsfhnfg.html

date +%s;  date -d @1700000000
来源：http://dali.pycfn.com/Article/details/gttsrvptwe.html

[R71] 日期格式化
来源：http://dali.bjfxy.top/Article/details/gtdizonxhm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.fengsongda.top/Article/details/gtgjwewush.html

[R72] 等待端口就绪
来源：http://dali.kuanghao11.cn/Article/details/gtfdqzzcqt.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.gogol.net.cn/Article/details/gtluaywpap.html

[R73] 分割大日志
来源：http://dali.gzhubu.top/Article/details/gteziuiqvu.html

split -l 1000 big.log part_
来源：http://dali.chenjidiqi.icu/Article/details/gtdgeapfzc.html

[R74] 批量重命名
来源：http://dali.cdnleiting.top/Article/details/gtkspwpeah.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.mhx1999.top/Article/details/gtddjwgfbo.html

[R75] 导出环境变量
来源：http://dali.jyoumei.cn/Article/details/gtdmqtrgnm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.nanxuanxn.top/Article/details/gtzqvhipbl.html

[R76] 使用临时文件
来源：http://dali.jqgufenzy.top/Article/details/gthohjyhtg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ybcxt.top/Article/details/gtwdkabrjq.html

[R77] 读取用户输入
来源：http://dali.xylfe.cn/Article/details/gtfkfuqovi.html

read -rp "请输入: " ans
来源：http://dali.9152youxi.cn/Article/details/gtncrxbdfu.html

[R78] 交互式菜单
来源：http://dali.gotoacloud.top/Article/details/gtyfnlytxt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yuxming.cn/Article/details/gtlgqewgcf.html

[R79] 解析命令行选项
来源：http://dali.tianlin.xyz/Article/details/gtbviklxec.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.svipenyu.cn/Article/details/gtdshtcxoh.html

[R80] 查看脚本执行耗时
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwvnyhlyr.html

time ./run.sh
来源：http://dali.haohaochexian.top/Article/details/gtengqxpbp.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtiwbfpjjm.html

S. C / C++ 专题
来源：http://dali.shanyushiyangtech.top/Article/details/gtdftajlfy.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtbgbarxap.html

[S01] C：Hello World
来源：http://dali.gzhubu.top/Article/details/gtuaitlvan.html

#include <stdio.h>
来源：http://dali.jinqigfzy.top/Article/details/gtiwcsaojt.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.andypj.xyz/Article/details/gtswybdanu.html

[S02] C：变量与格式化输出
来源：http://dali.birdmap.top/Article/details/gtdmyrgbdp.html

int a = 10; printf("%d\n", a);
来源：http://dali.jyoumei.cn/Article/details/gtapgctqjf.html

[S03] C：读入整数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvgimowpy.html

int x; scanf("%d", &x);
来源：http://dali.jinqigfzy.top/Article/details/gtyhdrkzmf.html

[S04] C：字符串复制
来源：http://dali.yuanzhike.top/Article/details/gtcnaxjsdk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.smart0.xyz/Article/details/gtgfwwcbve.html

[S05] C：字符串长度
来源：http://dali.aizwys.cn/Article/details/gttnkqefpj.html

strlen(s)
来源：http://dali.redwolf501.top/Article/details/gtvfoaaior.html

[S06] C：字符串比较
来源：http://dali.birdmap.top/Article/details/gtwwerjrgx.html

strcmp(a, b) == 0
来源：http://dali.tian-w.cn/Article/details/gtizvvoukc.html

[S07] C：数组遍历求和
来源：http://dali.guowangkeji.top/Article/details/gtownzrnhe.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.guowangkeji.top/Article/details/gtnotemlxd.html

[S08] C：动态内存分配与释放
来源：http://dali.jqgufenzy.top/Article/details/gtypugmbon.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.redwolf501.top/Article/details/gtwgrfhmrm.html

[S09] C：结构体定义与初始化
来源：http://dali.aibaodan.cn/Article/details/gtbvnfcrmr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yueranfly.top/Article/details/gtfdfgupcy.html

[S10] C：指针与解引用
来源：http://dali.yvedp.cn/Article/details/gtogmqnwff.html

int *p = &a;  *p = 5;
来源：http://dali.havefunace.top/Article/details/gttlgavnee.html

[S11] C：逐行读文件
来源：http://dali.shangyingyoupin.top/Article/details/gtwwkwpmoa.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.pycfn.com/Article/details/gtgropjsil.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ehwqpu.com/Article/details/gttemovcyf.html

fclose(f);
来源：http://dali.xziqi.cn/Article/details/gtgmnptpog.html

[S12] C：写文件
来源：http://dali.yangfankeji.com/Article/details/gtvwhwuuri.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinqigfzy.top/Article/details/gtwvrpbsij.html

[S13] C：宏定义
来源：http://dali.yj202588.top/Article/details/gtmolmdwyn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gogol.net.cn/Article/details/gtngrcuevp.html

[S14] C：枚举
来源：http://dali.zhixingplan.top/Article/details/gtdaopzbca.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.chenzaomai.com/Article/details/gtuzscohhw.html

[S15] C：类型转换
来源：http://dali.wangdashe.top/Article/details/gtbwgkckez.html

(double) a / b
来源：http://dali.hammf.cn/Article/details/gtkpixouha.html

[S16] C：位操作置位
来源：http://dali.sufxvd.cn/Article/details/gtpfdjwmsp.html

x |= (1 << 3);
来源：http://dali.chenlongwang.top/Article/details/gttruexwrm.html

[S17] C：安全拼接字符串
来源：http://dali.aibaodan.cn/Article/details/gtqlwjfgsm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.kuanghao11.cn/Article/details/gtsvdoklbz.html

[S18] C：命令行参数
来源：http://dali.xziqi.cn/Article/details/gtnidnbami.html

int main(int argc, char **argv)
来源：http://dali.iojbl.cn/Article/details/gtjbamycky.html

[S19] C：快速排序
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwpmgufar.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yongpay.top/Article/details/gtredyexxy.html

[S20] C：二分查找
来源：http://dali.iojbl.cn/Article/details/gtdpkrzyhm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.kuanghao11.cn/Article/details/gtnzommtjb.html

[S21] C：字符类别判断
来源：http://dali.meibo888.top/Article/details/gtdlpgfdnl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jiagoushi.top/Article/details/gtstkbrrzk.html

[S22] C：字符串转数字
来源：http://dali.zhiwuduotai.top/Article/details/gtgustqllf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gtetpitocj.html

[S23] C：随机数
来源：http://dali.wangdashe.top/Article/details/gttxftttux.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.daxiang520.top/Article/details/gtysxltuop.html

[S24] C：获取本地时间
来源：http://dali.0kj1m.cn/Article/details/gtcizjfuou.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.aizwys.cn/Article/details/gtwfvkknxa.html

[S25] C：内存拷贝
来源：http://dali.sweek.top/Article/details/gtpeqgayrr.html

memcpy(dst, src, n);
来源：http://dali.aizwys.cn/Article/details/gtnqgpadmi.html

[S26] C：内存清零
来源：http://dali.jqgufenzy.top/Article/details/gtvvbazilk.html

memset(a, 0, sizeof a);
来源：http://dali.cqqwz.cn/Article/details/gtjnzhepiu.html

[S27] C：定义常量
来源：http://dali.xziqi.cn/Article/details/gtsezsqhir.html

const double PI = 3.14159;
来源：http://dali.chenzaomai.com/Article/details/gtdbwryuuw.html

[S28] C：静态变量
来源：http://dali.jinqigfzy.top/Article/details/gtalazbkap.html

static int counter = 0;
来源：http://dali.yongpay.top/Article/details/gtbubjbfyh.html

[S29] C：变参函数
来源：http://dali.yj20258.top/Article/details/gtfdsoddgm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.guannengcc.top/Article/details/gtubogdwln.html

[S30] C：头文件保护
来源：http://dali.xuanzx.com/Article/details/gtfdnclftj.html

#ifndef X_H
来源：http://dali.jinqigufen.top/Article/details/gtvfwnnciu.html

#define X_H
来源：http://dali.jlsjyb.cn/Article/details/gtkibwicct.html

#endif
来源：http://dali.yuxming.cn/Article/details/gtsqlbijll.html

[S31] C++：Hello World
来源：http://dali.yj202588.top/Article/details/gtjzvtdfsv.html

#include <iostream>
来源：http://dali.cucudq.cn/Article/details/gtwtmmhqpb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ydzc1.top/Article/details/gtkinwdggq.html

[S32] C++：字符串
来源：http://dali.chenlongwang.top/Article/details/gtojzvdpnq.html

std::string s = "hi";  s += "!";
来源：http://dali.svipenyu.cn/Article/details/gtvtbsneqe.html

[S33] C++：vector 增删
来源：http://dali.pengpengdd.cyou/Article/details/gtipdqmbzd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jqgufenzy.top/Article/details/gtayulkead.html

[S34] C++：遍历 vector
来源：http://dali.shangyingyoupin.top/Article/details/gtwnvrephx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jianghu66.top/Article/details/gtjwspjjjk.html

[S35] C++：map
来源：http://dali.nanxuanxn.top/Article/details/gtyzincaie.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuanzx.com/Article/details/gtolcpekzy.html

[S36] C++：unordered_map
来源：http://dali.hammf.cn/Article/details/gtmaihosfy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gtuzhzocpa.html

[S37] C++：set
来源：http://dali.ivvv.top/Article/details/gtfuiwepef.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hywenlv.cn/Article/details/gtgpwyqvlz.html

[S38] C++：排序
来源：http://dali.ybcxt.top/Article/details/gtylirneqp.html

std::sort(v.begin(), v.end());
来源：http://dali.shzxlz.cn/Article/details/gtdcpyixof.html

[S39] C++：自定义比较器排序
来源：http://dali.zhoulong.xyz/Article/details/gtqzrjgvzz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhongyouzk.top/Article/details/gtzzihvqcd.html

[S40] C++：查找元素
来源：http://dali.andypj.xyz/Article/details/gtovsgcxcl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.meibo888.top/Article/details/gteanbhyrn.html

[S41] C++：类与构造函数
来源：http://dali.sweek.top/Article/details/gtlawdzlvu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.mhx1999.top/Article/details/gtqfhxzaav.html

[S42] C++：继承与虚函数
来源：http://dali.daxiang520.top/Article/details/gtdfeoqowy.html

class B : public Base { public: void f() override {} };
来源：http://dali.ybcxt.top/Article/details/gtspfelxyr.html

[S43] C++：智能指针
来源：http://dali.cashguo.top/Article/details/gtksmwkruh.html

auto p = std::make_unique<int>(5);
来源：http://dali.yonumen.top/Article/details/gtqitkpovc.html

[S44] C++：引用传参
来源：http://dali.ivvv.top/Article/details/gthvdiokvo.html

void inc(int &x) { ++x; }
来源：http://dali.redwolf501.top/Article/details/gtzcfbomkf.html

[S45] C++：lambda
来源：http://dali.havefunace.top/Article/details/gtimftfvmt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbabvxrpc.html

[S46] C++：函数模板
来源：http://dali.cucudq.cn/Article/details/gtyypaiibl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yonumen.top/Article/details/gtkuqmdduk.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gtgegqkdtn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shuidangran.top/Article/details/gtbwpkhupn.html

[S48] C++：逐行读文件
来源：http://dali.smart0.xyz/Article/details/gtwgewmest.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cheryme.top/Article/details/gthallsfun.html

while (std::getline(in, line)) { }
来源：http://dali.chenzaomai.com/Article/details/gtieqeydns.html

[S49] C++：写文件
来源：http://dali.wangdashe.top/Article/details/gtmssfqnpm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gaohongyu789.top/Article/details/gttjhppmwl.html

[S50] C++：格式化数字
来源：http://dali.yj202588.top/Article/details/gtncqnqvqj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gtlkotcrfz.html

[S51] C++：显式类型转换
来源：http://dali.jyoumei.cn/Article/details/gturwnejuz.html

static_cast<double>(a) / b
来源：http://dali.316326.xyz/Article/details/gtdzgwoujm.html

[S52] C++：const 与 noexcept
来源：http://dali.sysykeji.top/Article/details/gtcdfdttrm.html

int size() const noexcept { return n_; }
来源：http://dali.hongshengwenyu.top/Article/details/gthtvtydqs.html

[S53] C++：移动语义
来源：http://dali.yuanzhike.top/Article/details/gtyjutomdg.html

std::vector<int> w = std::move(v);
来源：http://dali.jqgufenzy.top/Article/details/gtjmbeihye.html

[S54] C++：异常处理
来源：http://dali.cheryme.top/Article/details/gtwbaiszpw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.fengsongda.top/Article/details/gtdekbfmlk.html

[S55] C++：结构化绑定
来源：http://dali.tianlin.xyz/Article/details/gtumbhigro.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sweek.top/Article/details/gtwurzhyhj.html

[S56] C++：optional
来源：http://dali.jyoumei.cn/Article/details/gtpziccwqj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sweek.top/Article/details/gtwugohcbw.html

[S57] C++：编译期常量
来源：http://dali.birdmap.top/Article/details/gtnmbdatyp.html

constexpr int N = 10;
来源：http://dali.yj20258.top/Article/details/gtyqbwcpek.html

[S58] C++：命名空间
来源：http://dali.yueranfly.top/Article/details/gtyrxoyptu.html

namespace ns { int f() { return 1; } }
来源：http://dali.0kj1m.cn/Article/details/gtccvpzsgj.html

[S59] C++：静态断言
来源：http://dali.cqqwz.cn/Article/details/gtqewblrie.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.guannengcc.top/Article/details/gtmtqwrsoe.html

[S60] C++：遍历并删除元素
来源：http://dali.tian-w.cn/Article/details/gtmcuczsqa.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yuxming.cn/Article/details/gtthxvsaca.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtuzebncjj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenjidiqi.icu/Article/details/gtkxaqrcdy.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuqxuzoqr.html

[T01] Kotlin：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtddinkldm.html

println("Hello")
来源：http://dali.yongpay.top/Article/details/gtbbkzxmlk.html

[T02] Kotlin：变量
来源：http://dali.aibaodan.cn/Article/details/gttameiemp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yj20258888.top/Article/details/gtgcrkswdk.html

[T03] Kotlin：字符串模板
来源：http://dali.jinqigfzy.top/Article/details/gtqazoyfnn.html

"值: $b"
来源：http://dali.yangfankeji.com/Article/details/gtlyscejhu.html

[T04] Kotlin：空安全
来源：http://dali.sufxvd.cn/Article/details/gtjkzexzts.html

val n: String? = null;  n?.length
来源：http://dali.shanyushiyangtech.top/Article/details/gtgbkgchty.html

[T05] Kotlin：when 表达式
来源：http://dali.andypj.xyz/Article/details/gtrwwoxjyk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xuetiantiany.cn/Article/details/gtckwxefae.html

[T06] Kotlin：集合映射
来源：http://dali.daria6918.cn/Article/details/gtcrbwzalp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.nwbrower.top/Article/details/gtnfkogeyx.html

[T07] Kotlin：集合过滤
来源：http://dali.quarkkingdee.top/Article/details/gtrfksxzrn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zycfv.cn/Article/details/gtyovbzoxj.html

[T08] Kotlin：数据类
来源：http://dali.smart0.xyz/Article/details/gttubnjppd.html

data class User(val name: String, val age: Int)
来源：http://dali.yuanzhike.top/Article/details/gtwtkzmgmx.html

[T09] Kotlin：扩展函数
来源：http://dali.mhx1999.top/Article/details/gthylhmogk.html

fun String.exclaim() = this + "!"
来源：http://dali.andypj.xyz/Article/details/gtnboaoovm.html

[T10] Kotlin：默认参数
来源：http://dali.zhoulong.xyz/Article/details/gtzznlhrle.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.birdmap.top/Article/details/gtfemnwgux.html

[T11] Kotlin：协程
来源：http://dali.xuetiantiany.cn/Article/details/gttybzmhtj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yuanzhike.top/Article/details/gtwmvbvgpp.html

[T12] Kotlin：解构声明
来源：http://dali.nwbrower.top/Article/details/gtvqhiabxr.html

val (a, b) = Pair(1, 2)
来源：http://dali.guowangkeji.top/Article/details/gtwlxplaxa.html

[T13] Kotlin：只读 Map
来源：http://dali.cheryme.top/Article/details/gthkqeqghz.html

val m = mapOf("a" to 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtwjgquslv.html

[T14] Kotlin：循环
来源：http://dali.aibaodan.cn/Article/details/gtxepicmat.html

for (i in 1..10) println(i)
来源：http://dali.shangyingyoupin.top/Article/details/gtevvgocwh.html

[T15] Kotlin：接口
来源：http://dali.yanxiufei.cn/Article/details/gtgaztokaw.html

interface Shape { fun area(): Double }
来源：http://dali.gogol.net.cn/Article/details/gtktihntvg.html

[T16] Swift：Hello World
来源：http://dali.cashguo.top/Article/details/gtvzzbwtah.html

print("Hello")
来源：http://dali.xinyue.icu/Article/details/gtdhyxtpky.html

[T17] Swift：变量与常量
来源：http://dali.shangyingyoupin.top/Article/details/gtmssatcob.html

var a = 1;  let b = 2
来源：http://dali.sweek.top/Article/details/gtcnlzeged.html

[T18] Swift：字符串插值
来源：http://dali.bjfxy.top/Article/details/gtmgusmfvh.html

"值: \(b)"
来源：http://dali.yvedp.cn/Article/details/gtoyqcdhmc.html

[T19] Swift：可选绑定
来源：http://dali.shangyingyoupin.top/Article/details/gtrloqufsg.html

if let n = opt { print(n) }
来源：http://dali.cucudq.cn/Article/details/gtiffpfest.html

[T20] Swift：数组操作
来源：http://dali.fzhhl.top/Article/details/gtvsgiehwy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.gotoacloud.top/Article/details/gtjabwfbsn.html

[T21] Swift：遍历
来源：http://dali.guannengcc.top/Article/details/gttlckejzy.html

for x in a { print(x) }
来源：http://dali.xuanzx.com/Article/details/gtiypawybi.html

[T22] Swift：字典
来源：http://dali.zhixingplan.top/Article/details/gtibeqgrwg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.snrcjt.cn/Article/details/gthbvrfmxp.html

[T23] Swift：函数
来源：http://dali.fengsongda.top/Article/details/gtuifzphjh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yvedp.cn/Article/details/gthdnaxlqr.html

[T24] Swift：闭包
来源：http://dali.shuidangran.top/Article/details/gtkvwkpxis.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.dashuyun.cn/Article/details/gtthkebkdv.html

[T25] Swift：结构体
来源：http://dali.chenjidiqi.icu/Article/details/gtdtfwmvms.html

struct P { var x: Int }
来源：http://dali.gotoacloud.top/Article/details/gtdswqhgjq.html

[T26] Swift：类与重写
来源：http://dali.aizwys.cn/Article/details/gtgkdinppy.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gteoabinol.html

[T27] Swift：错误处理
来源：http://dali.jyoumei.cn/Article/details/gtdpsgngwc.html

do { try f() } catch { print(error) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrkrvknnj.html

[T28] Swift：枚举
来源：http://dali.xinyue.icu/Article/details/gtqcrdjewu.html

enum Color { case red, green }
来源：http://dali.jlsjyb.cn/Article/details/gtconsufic.html

[T29] Swift：guard 提前返回
来源：http://dali.cucudq.cn/Article/details/gtxuvvghzd.html

guard let x = opt else { return }
来源：http://dali.yangfankeji.com/Article/details/gtyeuhtoyb.html

[T30] Swift：协议
来源：http://dali.yueranfly.top/Article/details/gtvtcblama.html

protocol Shape { func area() -> Double }
来源：http://dali.ivvv.top/Article/details/gtyqldyqda.html

[T31] Lua：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtnriolhwd.html

print("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gthoozyckt.html

[T32] Lua：局部变量
来源：http://dali.gogol.net.cn/Article/details/gtrsmqvcly.html

local a = 1
来源：http://dali.cdnleiting.top/Article/details/gtfjwunopb.html

[T33] Lua：表（数组）
来源：http://dali.vqdsnc.cn/Article/details/gtloemonuf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.iojbl.cn/Article/details/gtysxkfbaf.html

[T34] Lua：遍历表
来源：http://dali.yj20258.top/Article/details/gtdcnyrsrb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hammf.cn/Article/details/gtijypooau.html

[T35] Lua：字典表
来源：http://dali.cdnleiting.top/Article/details/gtrkshdayg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jqgufenzy.top/Article/details/gtcqguosrp.html

[T36] Lua：函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpmosypmu.html

function add(a, b) return a + b end
来源：http://dali.tianlin.xyz/Article/details/gtdeuxrlro.html

[T37] Lua：字符串拼接
来源：http://dali.xylfe.cn/Article/details/gtlnbbmuma.html

"a" .. "b"
来源：http://dali.cheryme.top/Article/details/gtfmnnnqsl.html

[T38] Lua：条件
来源：http://dali.pycfn.com/Article/details/gtxuehgphs.html

if x > 0 then print("正") end
来源：http://dali.hammf.cn/Article/details/gtysdnklwm.html

[T39] Lua：模式匹配
来源：http://dali.jyoumei.cn/Article/details/gtvzokduic.html

string.find(s, "%d+")
来源：http://dali.gzhubu.top/Article/details/gtqgsfvfio.html

[T40] Lua：元表
来源：http://dali.guowangkeji.top/Article/details/gtwyezeyxm.html

setmetatable({}, { __index = base })
来源：http://dali.ivvv.top/Article/details/gtlyzldanv.html

[T41] Perl：Hello World
来源：http://dali.xuanzx.com/Article/details/gtzuafnamb.html

print "Hello\n";
来源：http://dali.wangdashe.top/Article/details/gthprpxsrk.html

[T42] Perl：变量类型
来源：http://dali.ppjwa.cn/Article/details/gttsnmexnk.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.mhx1999.top/Article/details/gtewbdbscn.html

[T43] Perl：字符串插值
来源：http://dali.jyoumei.cn/Article/details/gtgzkbufys.html

"值: $a"
来源：http://dali.aizwys.cn/Article/details/gtjbfeaufb.html

[T44] Perl：条件
来源：http://dali.xuetiantiany.cn/Article/details/gtnegnmndw.html

if ($a > 0) { print "正"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnmfkqnfe.html

[T45] Perl：数组遍历
来源：http://dali.ppjwa.cn/Article/details/gtlaofnhfh.html

for my $x (@arr) { print $x; }
来源：http://dali.aizwys.cn/Article/details/gtxcrzzaqf.html

[T46] Perl：哈希操作
来源：http://dali.svipenyu.cn/Article/details/gtpmyigjox.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.gzhubu.top/Article/details/gtsojzhlto.html

[T47] Perl：正则捕获
来源：http://dali.havefunace.top/Article/details/gtrydkljeo.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.sxryk.cn/Article/details/gtidqurbwk.html

[T48] Perl：正则替换
来源：http://dali.jyoumei.cn/Article/details/gthagexqsc.html

$s =~ s/old/new/g;
来源：http://dali.gotoacloud.top/Article/details/gtykotrlgu.html

[T49] Perl：函数
来源：http://dali.gogol.net.cn/Article/details/gtvoijucbv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yvedp.cn/Article/details/gtlarlybbi.html

[T50] Perl：逐行读文件
来源：http://dali.jinqigfzy.top/Article/details/gtpqqzvqno.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.pycfn.com/Article/details/gtrvgdywyt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.dashuyun.cn/Article/details/gtxylqcoas.html

[T51] Scala：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtinhhwrdi.html

println("Hello")
来源：http://dali.316326.xyz/Article/details/gthsuusksi.html

[T52] Scala：变量
来源：http://dali.quarkkingdee.top/Article/details/gtccvcjajy.html

val a = 1;  var b = 2
来源：http://dali.hammf.cn/Article/details/gtdtpflucq.html

[T53] Scala：字符串插值
来源：http://dali.feifeiyinyue.top/Article/details/gtpvtfzwxw.html

s"值: $b"
来源：http://dali.quarkkingdee.top/Article/details/gtsxsvahed.html

[T54] Scala：集合映射
来源：http://dali.gotoacloud.top/Article/details/gtpbcvdzpt.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.0kj1m.cn/Article/details/gtyqlimfzm.html

[T55] Scala：集合过滤
来源：http://dali.yangfankeji.com/Article/details/gtihhetqdv.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvuczmhda.html

[T56] Scala：样例类
来源：http://dali.hongshengwenyu.top/Article/details/gtotlcfsao.html


<!-- 参考信息 -->