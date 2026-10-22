代发 wailian999

ssh user@host 'uptime'
来源：http://dali.jiagoushi.top/Article/details/gt2fdhhpkvp.html

[R58] 下载文件
来源：http://dali.sweek.top/Article/details/gt2ehrpyhcv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.redwolf501.top/Article/details/gt2jambsldm.html

[R59] 发 POST JSON
来源：http://dali.nanxinkj.top/Article/details/gt2lmjnlkhf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shangyingyoupin.top/Article/details/gt2gmihlyky.html

[R60] 只看 HTTP 状态码
来源：http://dali.gogol.net.cn/Article/details/gt2pmjhfpee.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yj20258.top/Article/details/gt2nysckpqh.html

[R61] 磁盘占用
来源：http://dali.andypj.xyz/Article/details/gt2twfscrzk.html

df -h;  du -sh *
来源：http://dali.aizwys.cn/Article/details/gt2omaupjir.html

[R62] 找最占空间的文件
来源：http://dali.zdqjudy.top/Article/details/gt2gdkrrzkd.html

du -ah . | sort -rh | head -10
来源：http://dali.zhoulong.xyz/Article/details/gt2vyddsyam.html

[R63] 内存与进程
来源：http://dali.c1oappe.top/Article/details/gt2ygpiyfag.html

free -h;  ps aux | grep nginx
来源：http://dali.gotoacloud.top/Article/details/gt2foktddzn.html

[R64] 结束进程
来源：http://dali.gotoacloud.top/Article/details/gt2xwxjapbl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.svipenyu.cn/Article/details/gt2nawhnsnd.html

[R65] 查看端口占用
来源：http://dali.pycfn.com/Article/details/gt2oxrwbnfl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cqqwz.cn/Article/details/gt2hbqsqtua.html

[R66] 定时任务
来源：http://dali.jlsjyb.cn/Article/details/gt2zadbjdvj.html

crontab -e;  crontab -l
来源：http://dali.kuanghao11.cn/Article/details/gt2pflvynif.html

[R67] 生成随机十六进制串
来源：http://dali.cucudq.cn/Article/details/gt2nnzbzdam.html

openssl rand -hex 16
来源：http://dali.guowangkeji.top/Article/details/gt2mcrljsby.html

[R68] 计算文件校验值
来源：http://dali.gogol.net.cn/Article/details/gt2yzdkkucd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yvedp.cn/Article/details/gt2fbjavmrr.html

[R69] 生成随机密码
来源：http://dali.vqdsnc.cn/Article/details/gt2vdjakxby.html

head -c 16 /dev/urandom | base64
来源：http://dali.cdnleiting.top/Article/details/gt2taomqneu.html

[R70] 时间戳与互转
来源：http://dali.guannengcc.top/Article/details/gt2sbavacxv.html

date +%s;  date -d @1700000000
来源：http://dali.cqqwz.cn/Article/details/gt2gimbjzzw.html

[R71] 日期格式化
来源：http://dali.shzxlz.cn/Article/details/gt2mdltcaaq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.fengsongda.top/Article/details/gt2gyjzwfui.html

[R72] 等待端口就绪
来源：http://dali.zhongyouzk.top/Article/details/gt2kgnsnpde.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yangfankeji.com/Article/details/gt2ruvggmof.html

[R73] 分割大日志
来源：http://dali.daxiang520.top/Article/details/gt2arzatemm.html

split -l 1000 big.log part_
来源：http://dali.snrcjt.cn/Article/details/gt2xbzjcugd.html

[R74] 批量重命名
来源：http://dali.andypj.xyz/Article/details/gt2jmqusfdy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hysaishi.cn/Article/details/gt2qbfdaiui.html

[R75] 导出环境变量
来源：http://dali.sysykeji.top/Article/details/gt2oeaesnnk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shzxlz.cn/Article/details/gt2puzcauyy.html

[R76] 使用临时文件
来源：http://dali.wangdashe.top/Article/details/gt2geycymhx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.sysykeji.top/Article/details/gt2wstdvjir.html

[R77] 读取用户输入
来源：http://dali.xylfe.cn/Article/details/gt2nzlrznzr.html

read -rp "请输入: " ans
来源：http://dali.tanke756.top/Article/details/gt2wfkueszn.html

[R78] 交互式菜单
来源：http://dali.nwbrower.top/Article/details/gt2cvdoakhp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yuxming.cn/Article/details/gt2bpfwgtly.html

[R79] 解析命令行选项
来源：http://dali.redwolf501.top/Article/details/gt2yglczcoa.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.smart0.xyz/Article/details/gt2gktfadfc.html

[R80] 查看脚本执行耗时
来源：http://dali.cucudq.cn/Article/details/gt2sylfndck.html

time ./run.sh
来源：http://dali.yj202588.top/Article/details/gt2chtfhwjd.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2ibivofzm.html

S. C / C++ 专题
来源：http://dali.quarkkingdee.top/Article/details/gt2bkavpujr.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2sfqxdghq.html

[S01] C：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gt2qifpnxfn.html

#include <stdio.h>
来源：http://dali.quarkkingdee.top/Article/details/gt2rggmuwhx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gaohongyu789.top/Article/details/gt2lbdllssl.html

[S02] C：变量与格式化输出
来源：http://dali.xinyue.icu/Article/details/gt2lqzpizjo.html

int a = 10; printf("%d\n", a);
来源：http://dali.yangfankeji.com/Article/details/gt2vsxwtpen.html

[S03] C：读入整数
来源：http://dali.jyoumei.cn/Article/details/gt2qtongalh.html

int x; scanf("%d", &x);
来源：http://dali.nanxinkj.top/Article/details/gt2uvrjvpmf.html

[S04] C：字符串复制
来源：http://dali.yongpay.top/Article/details/gt2ypnqndlz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.316326.xyz/Article/details/gt2zflhxeyi.html

[S05] C：字符串长度
来源：http://dali.yj20258.top/Article/details/gt2lpqwtkkr.html

strlen(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2qkuvrxmr.html

[S06] C：字符串比较
来源：http://dali.cheryme.top/Article/details/gt2nhdgfltc.html

strcmp(a, b) == 0
来源：http://dali.cdnleiting.top/Article/details/gt2xlfrduom.html

[S07] C：数组遍历求和
来源：http://dali.iojbl.cn/Article/details/gt2nokeajhn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhongyouzk.top/Article/details/gt2fjohuujy.html

[S08] C：动态内存分配与释放
来源：http://dali.tanke756.top/Article/details/gt2tmejnfdh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ydzc1.top/Article/details/gt2nocjayig.html

[S09] C：结构体定义与初始化
来源：http://dali.snrcjt.cn/Article/details/gt2qybyyffu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tvfnzqda.html

[S10] C：指针与解引用
来源：http://dali.birdmap.top/Article/details/gt2tmqrsoui.html

int *p = &a;  *p = 5;
来源：http://dali.ybcxt.top/Article/details/gt2vyhhjwje.html

[S11] C：逐行读文件
来源：http://dali.bjfxy.top/Article/details/gt2xblkvfxr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.0kj1m.cn/Article/details/gt2yuifguav.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yj20258.top/Article/details/gt2qkqagtkz.html

fclose(f);
来源：http://dali.yanxiufei.cn/Article/details/gt2jpcrpwfc.html

[S12] C：写文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2luayiyaj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.guannengcc.top/Article/details/gt2bptwdbpw.html

[S13] C：宏定义
来源：http://dali.wangshuangyany.cn/Article/details/gt2bomszqtf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cucudq.cn/Article/details/gt2ioneiimp.html

[S14] C：枚举
来源：http://dali.zhiwuduotai.top/Article/details/gt2jevkxqgd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hnqzz.top/Article/details/gt2wzihimlf.html

[S15] C：类型转换
来源：http://dali.shuidangran.top/Article/details/gt2xmpnvjrz.html

(double) a / b
来源：http://dali.tianlin.xyz/Article/details/gt2uvgjvchw.html

[S16] C：位操作置位
来源：http://dali.jqgufenzy.top/Article/details/gt2tltbyyfh.html

x |= (1 << 3);
来源：http://dali.gogol.net.cn/Article/details/gt2mfaulxud.html

[S17] C：安全拼接字符串
来源：http://dali.chenlongwang.top/Article/details/gt2vdvcyeje.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinqigufen.top/Article/details/gt2yhxtqvnn.html

[S18] C：命令行参数
来源：http://dali.tanke756.top/Article/details/gt2okyifoft.html

int main(int argc, char **argv)
来源：http://dali.zhoulong.xyz/Article/details/gt2nmyqxuga.html

[S19] C：快速排序
来源：http://dali.pengpengdd.cyou/Article/details/gt2kkncjdwl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.meibo888.top/Article/details/gt2qvqoubdf.html

[S20] C：二分查找
来源：http://dali.aizwys.cn/Article/details/gt2hcaienum.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.pycfn.com/Article/details/gt2ppiyjqat.html

[S21] C：字符类别判断
来源：http://dali.xziqi.cn/Article/details/gt2lxiowvgz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.smart0.xyz/Article/details/gt2lucqnjts.html

[S22] C：字符串转数字
来源：http://dali.zhengqikj.top/Article/details/gt2ffegxuen.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.fengsongda.top/Article/details/gt2wgnkuvks.html

[S23] C：随机数
来源：http://dali.hfpthk.cn/Article/details/gt2vsrtvraf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yangfankeji.com/Article/details/gt2vtepmodi.html

[S24] C：获取本地时间
来源：http://dali.nanxinkj.top/Article/details/gt2vxlbpdod.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.aizwys.cn/Article/details/gt2swqdedzb.html

[S25] C：内存拷贝
来源：http://dali.pycfn.com/Article/details/gt2uwftsgdf.html

memcpy(dst, src, n);
来源：http://dali.zhixingplan.top/Article/details/gt2gyjckram.html

[S26] C：内存清零
来源：http://dali.chenlongwang.top/Article/details/gt2pqidexye.html

memset(a, 0, sizeof a);
来源：http://dali.jqgufenzy.top/Article/details/gt2ubrqoxph.html

[S27] C：定义常量
来源：http://dali.cheryme.top/Article/details/gt2ipjmlnve.html

const double PI = 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gt2vvpwqrfn.html

[S28] C：静态变量
来源：http://dali.shuidangran.top/Article/details/gt2lxvhthit.html

static int counter = 0;
来源：http://dali.hnqzz.top/Article/details/gt2skvnnhtt.html

[S29] C：变参函数
来源：http://dali.ybcxt.top/Article/details/gt2ejsmdmpk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hywenlv.cn/Article/details/gt2tuhawhwq.html

[S30] C：头文件保护
来源：http://dali.yonumen.top/Article/details/gt2nngztker.html

#ifndef X_H
来源：http://dali.nwbrower.top/Article/details/gt2pvdkgrzi.html

#define X_H
来源：http://dali.xziqi.cn/Article/details/gt2fjhhrcyf.html

#endif
来源：http://dali.vqdsnc.cn/Article/details/gt2dupzxenz.html

[S31] C++：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gt2akgvxnfz.html

#include <iostream>
来源：http://dali.hammf.cn/Article/details/gt2wrxltxfl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hzzbisra.html

[S32] C++：字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2mfutmron.html

std::string s = "hi";  s += "!";
来源：http://dali.vqdsnc.cn/Article/details/gt2mbtnuqqc.html

[S33] C++：vector 增删
来源：http://dali.c1oappe.top/Article/details/gt2kzucyrad.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.feifeiyinyue.top/Article/details/gt2bbcaapql.html

[S34] C++：遍历 vector
来源：http://dali.cdnleiting.top/Article/details/gt2ngqeiquc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.aibaodan.cn/Article/details/gt2tmsfbgwa.html

[S35] C++：map
来源：http://dali.jlsjyb.cn/Article/details/gt2khshwnjf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.dashuyun.cn/Article/details/gt2sckfwwrm.html

[S36] C++：unordered_map
来源：http://dali.sxryk.cn/Article/details/gt2uthnsfjx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gt2nivaobie.html

[S37] C++：set
来源：http://dali.gogol.net.cn/Article/details/gt2vqqoyubz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhengqikj.top/Article/details/gt2hnjyzwgi.html

[S38] C++：排序
来源：http://dali.chenjidiqi.icu/Article/details/gt2spopdxeq.html

std::sort(v.begin(), v.end());
来源：http://dali.tian-w.cn/Article/details/gt2urjcnxew.html

[S39] C++：自定义比较器排序
来源：http://dali.jqgufenzy.top/Article/details/gt2xaftkmrl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2dlexdzre.html

[S40] C++：查找元素
来源：http://dali.yangfankeji.com/Article/details/gt2nntjfepu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hysaishi.cn/Article/details/gt2vxnhgngs.html

[S41] C++：类与构造函数
来源：http://dali.gogol.net.cn/Article/details/gt2exyhrzzj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.bjfxy.top/Article/details/gt2omwumfip.html

[S42] C++：继承与虚函数
来源：http://dali.gaohongyu789.top/Article/details/gt2crbjiafg.html

class B : public Base { public: void f() override {} };
来源：http://dali.guowangkeji.top/Article/details/gt2tjgrtscp.html

[S43] C++：智能指针
来源：http://dali.yueranfly.top/Article/details/gt2raxlcrlq.html

auto p = std::make_unique<int>(5);
来源：http://dali.chenjidiqi.icu/Article/details/gt2eplxdgnm.html

[S44] C++：引用传参
来源：http://dali.sysykeji.top/Article/details/gt2iivhirua.html

void inc(int &x) { ++x; }
来源：http://dali.sxryk.cn/Article/details/gt2jmfiytpp.html

[S45] C++：lambda
来源：http://dali.316326.xyz/Article/details/gt2zrqskrzb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.nanxuanxn.top/Article/details/gt2zedwwgvy.html

[S46] C++：函数模板
来源：http://dali.meibo888.top/Article/details/gt2nplxtnog.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yonumen.top/Article/details/gt2jpikflpq.html

[S47] C++：结构化绑定遍历
来源：http://dali.tanke756.top/Article/details/gt2dqahjhas.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ydzc1.top/Article/details/gt2vrxxedmk.html

[S48] C++：逐行读文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2zvampjcj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.nanxuanxn.top/Article/details/gt2otwzxbcb.html

while (std::getline(in, line)) { }
来源：http://dali.chenjidiqi.icu/Article/details/gt2uqecofid.html

[S49] C++：写文件
来源：http://dali.yj20258.top/Article/details/gt2snhxfzjt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.tian-w.cn/Article/details/gt2vefhwupf.html

[S50] C++：格式化数字
来源：http://dali.meibo888.top/Article/details/gt2cxzbrefu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gt2pzsjjlsa.html

[S51] C++：显式类型转换
来源：http://dali.nanxuanxn.top/Article/details/gt2dhzebtfr.html

static_cast<double>(a) / b
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ewmqgnlz.html

[S52] C++：const 与 noexcept
来源：http://dali.cqqwz.cn/Article/details/gt2zuganoft.html

int size() const noexcept { return n_; }
来源：http://dali.nanxinkj.top/Article/details/gt2bybhzplj.html

[S53] C++：移动语义
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ymqosfbu.html

std::vector<int> w = std::move(v);
来源：http://dali.jianghu66.top/Article/details/gt2zksuumde.html

[S54] C++：异常处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pwmrkqzo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jlsjyb.cn/Article/details/gt2qalprhaj.html

[S55] C++：结构化绑定
来源：http://dali.birdmap.top/Article/details/gt2rkhxdosb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.iojbl.cn/Article/details/gt2ngjbcixf.html

[S56] C++：optional
来源：http://dali.shuidangran.top/Article/details/gt2pqdqkxnj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.daxiang520.top/Article/details/gt2vwovzrfs.html

[S57] C++：编译期常量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aqxovfxa.html

constexpr int N = 10;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2duehkgjw.html

[S58] C++：命名空间
来源：http://dali.0kj1m.cn/Article/details/gt2hrcbbjfw.html

namespace ns { int f() { return 1; } }
来源：http://dali.vqdsnc.cn/Article/details/gt2sxfhfnia.html

[S59] C++：静态断言
来源：http://dali.smart0.xyz/Article/details/gt2kbelmxxc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jiagoushi.top/Article/details/gt2tnajiuyr.html

[S60] C++：遍历并删除元素
来源：http://dali.meibo888.top/Article/details/gt2urrkljnw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zycfv.cn/Article/details/gt2piizqoci.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2smjappry.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xinyue.icu/Article/details/gt2tyizqxfg.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2psruitme.html

[T01] Kotlin：Hello World
来源：http://dali.ppjwa.cn/Article/details/gt2eeujkers.html

println("Hello")
来源：http://dali.yj20258.top/Article/details/gt2fejgsrux.html

[T02] Kotlin：变量
来源：http://dali.yangfankeji.com/Article/details/gt2xvjzpfnz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hywenlv.cn/Article/details/gt2lwffnyls.html

[T03] Kotlin：字符串模板
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cxmngrzn.html

"值: $b"
来源：http://dali.zycfv.cn/Article/details/gt2qoyyufvc.html

[T04] Kotlin：空安全
来源：http://dali.zhoulong.xyz/Article/details/gt2alcqzclw.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ntkrmxyp.html

[T05] Kotlin：when 表达式
来源：http://dali.wangdashe.top/Article/details/gt2wdplozze.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.snrcjt.cn/Article/details/gt2ikakomzk.html

[T06] Kotlin：集合映射
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2phuvahxn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.nwbrower.top/Article/details/gt2sjtqwrhs.html

[T07] Kotlin：集合过滤
来源：http://dali.9152youxi.cn/Article/details/gt2ylrdgoda.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cucudq.cn/Article/details/gt2ijitisku.html

[T08] Kotlin：数据类
来源：http://dali.quarkkingdee.top/Article/details/gt2kgthqczt.html

data class User(val name: String, val age: Int)
来源：http://dali.sysykeji.top/Article/details/gt2fvghsygn.html

[T09] Kotlin：扩展函数
来源：http://dali.zycfv.cn/Article/details/gt2oiyqusvp.html

fun String.exclaim() = this + "!"
来源：http://dali.yj202588.top/Article/details/gt2teyptigk.html

[T10] Kotlin：默认参数
来源：http://dali.gzhubu.top/Article/details/gt2vxtswohz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jianghu66.top/Article/details/gt2xihixlwt.html

[T11] Kotlin：协程
来源：http://dali.mhx1999.top/Article/details/gt2gqjjinhw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cashguo.top/Article/details/gt2ccljdsgj.html

[T12] Kotlin：解构声明
来源：http://dali.dashuyun.cn/Article/details/gt2kthhnzom.html

val (a, b) = Pair(1, 2)
来源：http://dali.yvedp.cn/Article/details/gt2kgopnrng.html

[T13] Kotlin：只读 Map
来源：http://dali.gaohongyu789.top/Article/details/gt2bqlsjsiu.html

val m = mapOf("a" to 1)
来源：http://dali.cqqwz.cn/Article/details/gt2xnhoywox.html

[T14] Kotlin：循环
来源：http://dali.yanxiufei.cn/Article/details/gt2qpooqohm.html

for (i in 1..10) println(i)
来源：http://dali.xuetiantiany.cn/Article/details/gt2lthmvkzx.html

[T15] Kotlin：接口
来源：http://dali.hongshengwenyu.top/Article/details/gt2wvvckkhl.html

interface Shape { fun area(): Double }
来源：http://dali.ehwqpu.com/Article/details/gt2lpvgotug.html

[T16] Swift：Hello World
来源：http://dali.guowangkeji.top/Article/details/gt2bqdpyrwa.html

print("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xsujmigo.html

[T17] Swift：变量与常量
来源：http://dali.jinqigfzy.top/Article/details/gt2zsgnhlhm.html

var a = 1;  let b = 2
来源：http://dali.cashguo.top/Article/details/gt2ltgknndz.html

[T18] Swift：字符串插值
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ibmwqryp.html

"值: \(b)"
来源：http://dali.gaohongyu789.top/Article/details/gt2rrpsafwy.html

[T19] Swift：可选绑定
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2znqgylxn.html

if let n = opt { print(n) }
来源：http://dali.sufxvd.cn/Article/details/gt2xwesgnbc.html

[T20] Swift：数组操作
来源：http://dali.nanxuanxn.top/Article/details/gt2qsotownr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.andypj.xyz/Article/details/gt2nikvkzgo.html

[T21] Swift：遍历
来源：http://dali.nanxuanxn.top/Article/details/gt2elviyeef.html

for x in a { print(x) }
来源：http://dali.ppjwa.cn/Article/details/gt2twrmacmm.html

[T22] Swift：字典
来源：http://dali.tanke756.top/Article/details/gt2xinbrgbb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.birdmap.top/Article/details/gt2wwexhrcy.html

[T23] Swift：函数
来源：http://dali.snrcjt.cn/Article/details/gt2pvylyzqc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.nanxinkj.top/Article/details/gt2sjkqvzdw.html

[T24] Swift：闭包
来源：http://dali.zhiwuduotai.top/Article/details/gt2psirpblb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.iojbl.cn/Article/details/gt2okdmgshp.html

[T25] Swift：结构体
来源：http://dali.yongpay.top/Article/details/gt2unsomvop.html

struct P { var x: Int }
来源：http://dali.haohaochexian.top/Article/details/gt2ygdchyyl.html

[T26] Swift：类与重写
来源：http://dali.jinqigfzy.top/Article/details/gt2lvgxjsep.html

class A: Base { override func f() {} }
来源：http://dali.jyoumei.cn/Article/details/gt2buuzwssn.html

[T27] Swift：错误处理
来源：http://dali.snrcjt.cn/Article/details/gt2uyoviwpm.html

do { try f() } catch { print(error) }
来源：http://dali.hnqzz.top/Article/details/gt2pzdsnfwk.html

[T28] Swift：枚举
来源：http://dali.ehwqpu.com/Article/details/gt2ewpzutea.html

enum Color { case red, green }
来源：http://dali.aibaodan.cn/Article/details/gt2pyxwynbe.html

[T29] Swift：guard 提前返回
来源：http://dali.xuanzx.com/Article/details/gt2tjygtwnq.html

guard let x = opt else { return }
来源：http://dali.jqgfzy.top/Article/details/gt2lpcdwgnt.html

[T30] Swift：协议
来源：http://dali.yuanzhike.top/Article/details/gt2qctawljz.html

protocol Shape { func area() -> Double }
来源：http://dali.cdnleiting.top/Article/details/gt2yvvoawpr.html

[T31] Lua：Hello World
来源：http://dali.fzhhl.top/Article/details/gt2vgkczkmg.html

print("Hello")
来源：http://dali.yueranfly.top/Article/details/gt2llzotabz.html

[T32] Lua：局部变量
来源：http://dali.guannengcc.top/Article/details/gt2rqynhgsm.html

local a = 1
来源：http://dali.cdnleiting.top/Article/details/gt2lejqwfqy.html

[T33] Lua：表（数组）
来源：http://dali.316326.xyz/Article/details/gt2pagrxryr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinqigufen.top/Article/details/gt2ggeciabi.html

[T34] Lua：遍历表
来源：http://dali.hnxiangtu.top/Article/details/gt2xmroycwf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ybcxt.top/Article/details/gt2maophkrm.html

[T35] Lua：字典表
来源：http://dali.sysykeji.top/Article/details/gt2mghclnbi.html

local d = { a = 1 };  d.b = 2
来源：http://dali.0kj1m.cn/Article/details/gt2xxbitgdk.html

[T36] Lua：函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2gpbzevwg.html

function add(a, b) return a + b end
来源：http://dali.sufxvd.cn/Article/details/gt2cfuithkm.html

[T37] Lua：字符串拼接
来源：http://dali.hnxiangtu.top/Article/details/gt2nejupraw.html

"a" .. "b"
来源：http://dali.xuetiantiany.cn/Article/details/gt2lxsahcth.html

[T38] Lua：条件
来源：http://dali.tanke756.top/Article/details/gt2enzaiiyj.html

if x > 0 then print("正") end
来源：http://dali.yangfankeji.com/Article/details/gt2kvjoqtes.html

[T39] Lua：模式匹配
来源：http://dali.yueranfly.top/Article/details/gt2tjyvbkdb.html

string.find(s, "%d+")
来源：http://dali.xinyue.icu/Article/details/gt2fzhepyef.html

[T40] Lua：元表
来源：http://dali.hnxiangtu.top/Article/details/gt2icyxejvg.html

setmetatable({}, { __index = base })
来源：http://dali.jlsjyb.cn/Article/details/gt2ijdmcvjt.html

[T41] Perl：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nytiotgi.html

print "Hello\n";
来源：http://dali.hongshengwenyu.top/Article/details/gt2wsvdchvi.html

[T42] Perl：变量类型
来源：http://dali.dashuyun.cn/Article/details/gt2ovkzmzhx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ybcxt.top/Article/details/gt2jgtkukuh.html

[T43] Perl：字符串插值
来源：http://dali.wangdashe.top/Article/details/gt2kcmxmokm.html

"值: $a"
来源：http://dali.bjfxy.top/Article/details/gt2nljqsfzj.html

[T44] Perl：条件
来源：http://dali.xuanzx.com/Article/details/gt2bdcwfgdr.html

if ($a > 0) { print "正"; }
来源：http://dali.xziqi.cn/Article/details/gt2xwerxhoy.html

[T45] Perl：数组遍历
来源：http://dali.vqdsnc.cn/Article/details/gt2oodsxigz.html

for my $x (@arr) { print $x; }
来源：http://dali.ppjwa.cn/Article/details/gt2nrprlced.html

[T46] Perl：哈希操作
来源：http://dali.snrcjt.cn/Article/details/gt2tgkivhja.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.fzhhl.top/Article/details/gt2zoytcmle.html

[T47] Perl：正则捕获
来源：http://dali.hnxiangtu.top/Article/details/gt2dojcmxzq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.daxiang520.top/Article/details/gt2sxtqhxpa.html

[T48] Perl：正则替换
来源：http://dali.yanxiufei.cn/Article/details/gt2hcjbsjxv.html

$s =~ s/old/new/g;
来源：http://dali.sufxvd.cn/Article/details/gt2lfvcsyht.html

[T49] Perl：函数
来源：http://dali.zycfv.cn/Article/details/gt2apxedyjl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pdleyuca.html

[T50] Perl：逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gt2lkomasug.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.kuanghao11.cn/Article/details/gt2vcchbqvn.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2pyfxmosr.html

[T51] Scala：Hello World
来源：http://dali.xziqi.cn/Article/details/gt2zpoveheq.html

println("Hello")
来源：http://dali.jinqigfzy.top/Article/details/gt2qoardpwr.html

[T52] Scala：变量
来源：http://dali.havefunace.top/Article/details/gt2pthkdjxv.html

val a = 1;  var b = 2
来源：http://dali.guowangkeji.top/Article/details/gt2abscwulz.html

[T53] Scala：字符串插值
来源：http://dali.jiagoushi.top/Article/details/gt2mdfllife.html

s"值: $b"
来源：http://dali.jlsjyb.cn/Article/details/gt2jikvqjhe.html

[T54] Scala：集合映射
来源：http://dali.jinqigfzy.top/Article/details/gt2dysalmjq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yj20258888.top/Article/details/gt2iajkmsio.html

[T55] Scala：集合过滤
来源：http://dali.nanxinkj.top/Article/details/gt2cmxlzptn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yvedp.cn/Article/details/gt2upgtwxdx.html

[T56] Scala：样例类
来源：http://dali.hywenlv.cn/Article/details/gt2mxfjrrll.html

case class User(name: String, age: Int)
来源：http://dali.xylfe.cn/Article/details/gt2qptkhuac.html

[T57] Scala：模式匹配
来源：http://dali.jlsjyb.cn/Article/details/gt2bmxspovt.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jqgufenzy.top/Article/details/gt2wpzkixpf.html

[T58] Scala：函数定义
来源：http://dali.pengpengdd.cyou/Article/details/gt2xfjtgqle.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cdnleiting.top/Article/details/gt2iylrjeoc.html

[T59] Scala：循环
来源：http://dali.ehwqpu.com/Article/details/gt2txhknhws.html

for (i <- 1 to 10) println(i)
来源：http://dali.cucudq.cn/Article/details/gt2avyblptz.html

[T60] Scala：折叠
来源：http://dali.kuanghao11.cn/Article/details/gt2wxnykojm.html


<!-- 参考信息 -->