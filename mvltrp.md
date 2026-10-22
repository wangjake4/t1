代发 wailian999

ssh user@host 'uptime'
来源：http://dali.svipenyu.cn/Article/details/gt2refetrdu.html

[R58] 下载文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2anndsurm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.mhx1999.top/Article/details/gt2zescovjt.html

[R59] 发 POST JSON
来源：http://dali.hammf.cn/Article/details/gt2mqznldsl.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.nanxuanxn.top/Article/details/gt2yipxtwtz.html

[R60] 只看 HTTP 状态码
来源：http://dali.yuxming.cn/Article/details/gt2sgnmegtw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gzhubu.top/Article/details/gt2vvuogzpo.html

[R61] 磁盘占用
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jynrualv.html

df -h;  du -sh *
来源：http://dali.zhengqikj.top/Article/details/gt2kyvwrzdj.html

[R62] 找最占空间的文件
来源：http://dali.fengsongda.top/Article/details/gt2nmeklekh.html

du -ah . | sort -rh | head -10
来源：http://dali.shangyingyoupin.top/Article/details/gt2bviurobi.html

[R63] 内存与进程
来源：http://dali.cqqwz.cn/Article/details/gt2dslcjjil.html

free -h;  ps aux | grep nginx
来源：http://dali.yanxiufei.cn/Article/details/gt2rgduvuow.html

[R64] 结束进程
来源：http://dali.jqgufenzy.top/Article/details/gt2sgqnkgvx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jlsjyb.cn/Article/details/gt2rknucdvd.html

[R65] 查看端口占用
来源：http://dali.mhx1999.top/Article/details/gt2xbvbaxrc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.meibo888.top/Article/details/gt2qmgangik.html

[R66] 定时任务
来源：http://dali.yj20258888.top/Article/details/gt2enlktuyb.html

crontab -e;  crontab -l
来源：http://dali.hywenlv.cn/Article/details/gt2iwotvjrr.html

[R67] 生成随机十六进制串
来源：http://dali.birdmap.top/Article/details/gt2lljbvsmv.html

openssl rand -hex 16
来源：http://dali.havefunace.top/Article/details/gt2kteceeln.html

[R68] 计算文件校验值
来源：http://dali.zhongyouzk.top/Article/details/gt2nitrubqi.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.quarkkingdee.top/Article/details/gt2samucqze.html

[R69] 生成随机密码
来源：http://dali.yueranfly.top/Article/details/gt2jukiluru.html

head -c 16 /dev/urandom | base64
来源：http://dali.yueranfly.top/Article/details/gt2vttdpyzh.html

[R70] 时间戳与互转
来源：http://dali.jlsjyb.cn/Article/details/gt2osbcwvjc.html

date +%s;  date -d @1700000000
来源：http://dali.fengsongda.top/Article/details/gt2sjuzwauj.html

[R71] 日期格式化
来源：http://dali.yj20258.top/Article/details/gt2olvsmomr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.aizwys.cn/Article/details/gt2mifjleok.html

[R72] 等待端口就绪
来源：http://dali.ppjwa.cn/Article/details/gt2trgiuimh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cucudq.cn/Article/details/gt2bxpurdid.html

[R73] 分割大日志
来源：http://dali.ydzc1.top/Article/details/gt2wcgrykvv.html

split -l 1000 big.log part_
来源：http://dali.meibo888.top/Article/details/gt2vggcedzh.html

[R74] 批量重命名
来源：http://dali.snrcjt.cn/Article/details/gt2qzhwwbji.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gzhubu.top/Article/details/gt2yrjzphvc.html

[R75] 导出环境变量
来源：http://dali.birdmap.top/Article/details/gt2mdvncudd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.kuanghao11.cn/Article/details/gt2plmqihpk.html

[R76] 使用临时文件
来源：http://dali.kuanghao11.cn/Article/details/gt2pqfhjqtx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hquwmjnh.html

[R77] 读取用户输入
来源：http://dali.jinqigfzy.top/Article/details/gt2utjdqnoi.html

read -rp "请输入: " ans
来源：http://dali.fzhhl.top/Article/details/gt2ngvqcpkt.html

[R78] 交互式菜单
来源：http://dali.chenzaomai.com/Article/details/gt2sddxmmgh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.feifeiyinyue.top/Article/details/gt2mdpdytzv.html

[R79] 解析命令行选项
来源：http://dali.yongpay.top/Article/details/gt2rgemlena.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xuanzx.com/Article/details/gt2wypzvkpy.html

[R80] 查看脚本执行耗时
来源：http://dali.gzhubu.top/Article/details/gt2jhnulzwu.html

time ./run.sh
来源：http://dali.jqgufenzy.top/Article/details/gt2eajqtmwv.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2lfijetwq.html

S. C / C++ 专题
来源：http://dali.sufxvd.cn/Article/details/gt2xsidslkv.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2xrvugbph.html

[S01] C：Hello World
来源：http://dali.tian-w.cn/Article/details/gt2qyuwhoib.html

#include <stdio.h>
来源：http://dali.chenzaomai.com/Article/details/gt2jokffqij.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.pycfn.com/Article/details/gt2yvofezsd.html

[S02] C：变量与格式化输出
来源：http://dali.zhongyouzk.top/Article/details/gt2gxoiqnya.html

int a = 10; printf("%d\n", a);
来源：http://dali.hysaishi.cn/Article/details/gt2mkhzkpeg.html

[S03] C：读入整数
来源：http://dali.yonumen.top/Article/details/gt2uncvuxlo.html

int x; scanf("%d", &x);
来源：http://dali.zdqjudy.top/Article/details/gt2uwbpcpwb.html

[S04] C：字符串复制
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wmwplddh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jqgufenzy.top/Article/details/gt2xfbubsvd.html

[S05] C：字符串长度
来源：http://dali.gaohongyu789.top/Article/details/gt2kkptwefp.html

strlen(s)
来源：http://dali.hywenlv.cn/Article/details/gt2xyuqeqti.html

[S06] C：字符串比较
来源：http://dali.fzhhl.top/Article/details/gt2auyicona.html

strcmp(a, b) == 0
来源：http://dali.snrcjt.cn/Article/details/gt2fbfjfvhx.html

[S07] C：数组遍历求和
来源：http://dali.kuanghao11.cn/Article/details/gt2ocmawnoi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.dashuyun.cn/Article/details/gt2yuexwuuo.html

[S08] C：动态内存分配与释放
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jwxvgnvw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.daxiang520.top/Article/details/gt2zpyplfgk.html

[S09] C：结构体定义与初始化
来源：http://dali.havefunace.top/Article/details/gt2kcqfhafk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cdnleiting.top/Article/details/gt2txyrdpyq.html

[S10] C：指针与解引用
来源：http://dali.ivvv.top/Article/details/gt2cgjimhag.html

int *p = &a;  *p = 5;
来源：http://dali.jqgfzy.top/Article/details/gt2mpdnhhig.html

[S11] C：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gt2vkqioiuy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xinyue.icu/Article/details/gt2oxgyrjif.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.vqdsnc.cn/Article/details/gt2nmuwidve.html

fclose(f);
来源：http://dali.zycfv.cn/Article/details/gt2iyrjcehl.html

[S12] C：写文件
来源：http://dali.bjfxy.top/Article/details/gt2bkyomsco.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinqigufen.top/Article/details/gt2vkjutykr.html

[S13] C：宏定义
来源：http://dali.nanxuanxn.top/Article/details/gt2stqxnuyj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yvedp.cn/Article/details/gt2ezoxnyfe.html

[S14] C：枚举
来源：http://dali.snrcjt.cn/Article/details/gt2iptmnomv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yvedp.cn/Article/details/gt2wgfvcdlo.html

[S15] C：类型转换
来源：http://dali.daxiang520.top/Article/details/gt2jrmgxjot.html

(double) a / b
来源：http://dali.yj202588.top/Article/details/gt2oaykfnbf.html

[S16] C：位操作置位
来源：http://dali.yj20258888.top/Article/details/gt2cgutffru.html

x |= (1 << 3);
来源：http://dali.yj20258.top/Article/details/gt2jvwqsnpm.html

[S17] C：安全拼接字符串
来源：http://dali.chenzaomai.com/Article/details/gt2xilrsrxs.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.chenjidiqi.icu/Article/details/gt2huvbuhdy.html

[S18] C：命令行参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2shiwasht.html

int main(int argc, char **argv)
来源：http://dali.jlsjyb.cn/Article/details/gt2rtstayth.html

[S19] C：快速排序
来源：http://dali.daxiang520.top/Article/details/gt2fhhzgesb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zdqjudy.top/Article/details/gt2inleracr.html

[S20] C：二分查找
来源：http://dali.xuanzx.com/Article/details/gt2ooaldhwg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cucudq.cn/Article/details/gt2fcywlkbr.html

[S21] C：字符类别判断
来源：http://dali.yongpay.top/Article/details/gt2jsljhmyk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yuxming.cn/Article/details/gt2hwyqsqme.html

[S22] C：字符串转数字
来源：http://dali.cheryme.top/Article/details/gt2vnjevbkk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.gotoacloud.top/Article/details/gt2qaorbtcy.html

[S23] C：随机数
来源：http://dali.nwbrower.top/Article/details/gt2kxwyypuk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hywenlv.cn/Article/details/gt2ilmuyuid.html

[S24] C：获取本地时间
来源：http://dali.andypj.xyz/Article/details/gt2imsvqljg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.tian-w.cn/Article/details/gt2zeoyzfoc.html

[S25] C：内存拷贝
来源：http://dali.yj202588.top/Article/details/gt2rjabvcmt.html

memcpy(dst, src, n);
来源：http://dali.ydzc1.top/Article/details/gt2dgzhtvyg.html

[S26] C：内存清零
来源：http://dali.sufxvd.cn/Article/details/gt2fwwhecca.html

memset(a, 0, sizeof a);
来源：http://dali.9152youxi.cn/Article/details/gt2dombkazl.html

[S27] C：定义常量
来源：http://dali.sysykeji.top/Article/details/gt2xfyhegjm.html

const double PI = 3.14159;
来源：http://dali.yonumen.top/Article/details/gt2pxuggezk.html

[S28] C：静态变量
来源：http://dali.9152youxi.cn/Article/details/gt2moxfrzoi.html

static int counter = 0;
来源：http://dali.chenjidiqi.icu/Article/details/gt2sddzzchg.html

[S29] C：变参函数
来源：http://dali.wangdashe.top/Article/details/gt2qpdfpcrr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.tian-w.cn/Article/details/gt2capvrsph.html

[S30] C：头文件保护
来源：http://dali.jqgfzy.top/Article/details/gt2aquurhoa.html

#ifndef X_H
来源：http://dali.jiagoushi.top/Article/details/gt2hbeuyqhh.html

#define X_H
来源：http://dali.xuanzx.com/Article/details/gt2dshupdvk.html

#endif
来源：http://dali.quarkkingdee.top/Article/details/gt2jfhizgvp.html

[S31] C++：Hello World
来源：http://dali.tian-w.cn/Article/details/gt2fhkabejd.html

#include <iostream>
来源：http://dali.shzxlz.cn/Article/details/gt2sszbpupf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.haohaochexian.top/Article/details/gt2honjtvmx.html

[S32] C++：字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2stbatncd.html

std::string s = "hi";  s += "!";
来源：http://dali.sxryk.cn/Article/details/gt2cfcpejvh.html

[S33] C++：vector 增删
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2trsddbxp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.chenzaomai.com/Article/details/gt2ucczuysy.html

[S34] C++：遍历 vector
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jbfmvlyk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.redwolf501.top/Article/details/gt2elezfxir.html

[S35] C++：map
来源：http://dali.yuanzhike.top/Article/details/gt2ycoeuhyg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pycfn.com/Article/details/gt2msuaavar.html

[S36] C++：unordered_map
来源：http://dali.gogol.net.cn/Article/details/gt2qkzzvkqx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2utpvafew.html

[S37] C++：set
来源：http://dali.kuanghao11.cn/Article/details/gt2jqgsyuiv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hywenlv.cn/Article/details/gt2qmoplkcu.html

[S38] C++：排序
来源：http://dali.sufxvd.cn/Article/details/gt2idcaacmq.html

std::sort(v.begin(), v.end());
来源：http://dali.jqgfzy.top/Article/details/gt2kqzolrym.html

[S39] C++：自定义比较器排序
来源：http://dali.snrcjt.cn/Article/details/gt2vuoxgiyz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jyoumei.cn/Article/details/gt2lgeqhsnv.html

[S40] C++：查找元素
来源：http://dali.aizwys.cn/Article/details/gt2hkxcsgim.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hfpthk.cn/Article/details/gt2hgpvpphb.html

[S41] C++：类与构造函数
来源：http://dali.chenzaomai.com/Article/details/gt2csjlrwvo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.vqdsnc.cn/Article/details/gt2dpmvyepx.html

[S42] C++：继承与虚函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2dmgkyflj.html

class B : public Base { public: void f() override {} };
来源：http://dali.smart0.xyz/Article/details/gt2nyfqzaiw.html

[S43] C++：智能指针
来源：http://dali.yongpay.top/Article/details/gt2zmknyrjm.html

auto p = std::make_unique<int>(5);
来源：http://dali.nanxinkj.top/Article/details/gt2exgrldum.html

[S44] C++：引用传参
来源：http://dali.aizwys.cn/Article/details/gt2oznihmtd.html

void inc(int &x) { ++x; }
来源：http://dali.yj20258888.top/Article/details/gt2ruwlsmel.html

[S45] C++：lambda
来源：http://dali.yuxming.cn/Article/details/gt2rxqelwbi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.mhx1999.top/Article/details/gt2waruiryw.html

[S46] C++：函数模板
来源：http://dali.c1oappe.top/Article/details/gt2cfpchvjn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jianghu66.top/Article/details/gt2hghexyrt.html

[S47] C++：结构化绑定遍历
来源：http://dali.cdnleiting.top/Article/details/gt2xdacrlxi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hysaishi.cn/Article/details/gt2pmolfxee.html

[S48] C++：逐行读文件
来源：http://dali.hammf.cn/Article/details/gt2ppghfkgq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.tanke756.top/Article/details/gt2kdfbjcgf.html

while (std::getline(in, line)) { }
来源：http://dali.shzxlz.cn/Article/details/gt2bfqfkoaw.html

[S49] C++：写文件
来源：http://dali.jyoumei.cn/Article/details/gt2hlqgjqyq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cheryme.top/Article/details/gt2prmirtvy.html

[S50] C++：格式化数字
来源：http://dali.hfpthk.cn/Article/details/gt2lypfiwfv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gt2hxzldapz.html

[S51] C++：显式类型转换
来源：http://dali.ydzc1.top/Article/details/gt2iackkgzf.html

static_cast<double>(a) / b
来源：http://dali.zhixingplan.top/Article/details/gt2wqazgddi.html

[S52] C++：const 与 noexcept
来源：http://dali.jyoumei.cn/Article/details/gt2fllxdlav.html

int size() const noexcept { return n_; }
来源：http://dali.nanxuanxn.top/Article/details/gt2evooehaq.html

[S53] C++：移动语义
来源：http://dali.gotoacloud.top/Article/details/gt2bjdxmypt.html

std::vector<int> w = std::move(v);
来源：http://dali.fengsongda.top/Article/details/gt2npkfizga.html

[S54] C++：异常处理
来源：http://dali.cqqwz.cn/Article/details/gt2xuvvxmsh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jqgufenzy.top/Article/details/gt2uhyeitex.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmgfoyf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2palrllzw.html

[S56] C++：optional
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wpahbqie.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj20258.top/Article/details/gt2wglyzpwv.html

[S57] C++：编译期常量
来源：http://dali.0kj1m.cn/Article/details/gt2nnuofval.html

constexpr int N = 10;
来源：http://dali.ppjwa.cn/Article/details/gt2qbtbdqtu.html

[S58] C++：命名空间
来源：http://dali.cqqwz.cn/Article/details/gt2upijmviw.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinqigufen.top/Article/details/gt2lghqfsee.html

[S59] C++：静态断言
来源：http://dali.gotoacloud.top/Article/details/gt2iwtyvlzt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmaosba.html

[S60] C++：遍历并删除元素
来源：http://dali.tian-w.cn/Article/details/gt2jkebhkyf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinqigfzy.top/Article/details/gt2bhhkmief.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2ohkmqxwh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2cstbkqto.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2xchxpokf.html

[T01] Kotlin：Hello World
来源：http://dali.sufxvd.cn/Article/details/gt2wytfpldy.html

println("Hello")
来源：http://dali.jiagoushi.top/Article/details/gt2opuuphje.html

[T02] Kotlin：变量
来源：http://dali.fzhhl.top/Article/details/gt2rmmiwnor.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shzxlz.cn/Article/details/gt2ppuqtwfa.html

[T03] Kotlin：字符串模板
来源：http://dali.hywenlv.cn/Article/details/gt2evmrbbch.html

"值: $b"
来源：http://dali.gogol.net.cn/Article/details/gt2tqptujgv.html

[T04] Kotlin：空安全
来源：http://dali.gogol.net.cn/Article/details/gt2hofetkid.html

val n: String? = null;  n?.length
来源：http://dali.zdqjudy.top/Article/details/gt2nspyiwyd.html

[T05] Kotlin：when 表达式
来源：http://dali.hysaishi.cn/Article/details/gt2qrerbbhq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.haohaochexian.top/Article/details/gt2sfitwrnu.html

[T06] Kotlin：集合映射
来源：http://dali.redwolf501.top/Article/details/gt2octqdskn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhengqikj.top/Article/details/gt2ydaychls.html

[T07] Kotlin：集合过滤
来源：http://dali.wangdashe.top/Article/details/gt2vrmsndle.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jtkjnczh.html

[T08] Kotlin：数据类
来源：http://dali.mhx1999.top/Article/details/gt2ksvhikps.html

data class User(val name: String, val age: Int)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rgbsenhy.html

[T09] Kotlin：扩展函数
来源：http://dali.haohaochexian.top/Article/details/gt2nxqpriqg.html

fun String.exclaim() = this + "!"
来源：http://dali.ehwqpu.com/Article/details/gt2vxsdbagc.html

[T10] Kotlin：默认参数
来源：http://dali.0kj1m.cn/Article/details/gt2pudklqbu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.dianchejie.cn/Article/details/gt2yrlmtlck.html

[T11] Kotlin：协程
来源：http://dali.0kj1m.cn/Article/details/gt2srdlnxfd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.andypj.xyz/Article/details/gt2badjayry.html

[T12] Kotlin：解构声明
来源：http://dali.gaohongyu789.top/Article/details/gt2fyzeajon.html

val (a, b) = Pair(1, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2arwobmap.html

[T13] Kotlin：只读 Map
来源：http://dali.daria6918.cn/Article/details/gt2egkiduio.html

val m = mapOf("a" to 1)
来源：http://dali.snrcjt.cn/Article/details/gt2etpizmqo.html

[T14] Kotlin：循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qkanylwc.html

for (i in 1..10) println(i)
来源：http://dali.fzhhl.top/Article/details/gt2zdpajsjp.html

[T15] Kotlin：接口
来源：http://dali.zdqjudy.top/Article/details/gt2iiojuine.html

interface Shape { fun area(): Double }
来源：http://dali.xinyue.icu/Article/details/gt2cvidjpxz.html

[T16] Swift：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gt2jdmjvyzr.html

print("Hello")
来源：http://dali.meibo888.top/Article/details/gt2jfabgmkl.html

[T17] Swift：变量与常量
来源：http://dali.bjfxy.top/Article/details/gt2trmaupnw.html

var a = 1;  let b = 2
来源：http://dali.jiagoushi.top/Article/details/gt2sgqpewzm.html

[T18] Swift：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gt2yzmaqnpd.html

"值: \(b)"
来源：http://dali.jianghu66.top/Article/details/gt2gtcgyafj.html

[T19] Swift：可选绑定
来源：http://dali.jqgfzy.top/Article/details/gt2mireemvl.html

if let n = opt { print(n) }
来源：http://dali.yonumen.top/Article/details/gt2cqeawvpj.html

[T20] Swift：数组操作
来源：http://dali.yvedp.cn/Article/details/gt2wnvfyiqr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ehwqpu.com/Article/details/gt2huiirmwg.html

[T21] Swift：遍历
来源：http://dali.jqgufenzy.top/Article/details/gt2mjjbshfe.html

for x in a { print(x) }
来源：http://dali.jlsjyb.cn/Article/details/gt2wmgzbidd.html

[T22] Swift：字典
来源：http://dali.ydzc1.top/Article/details/gt2strqrphn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gzhubu.top/Article/details/gt2kslxysyf.html

[T23] Swift：函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lbeepctc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yangfankeji.com/Article/details/gt2qeulfmpf.html

[T24] Swift：闭包
来源：http://dali.jlsjyb.cn/Article/details/gt2ooqmkkpm.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vdmumgyk.html

[T25] Swift：结构体
来源：http://dali.fzhhl.top/Article/details/gt2gjnyhrqn.html

struct P { var x: Int }
来源：http://dali.c1oappe.top/Article/details/gt2iyrclmiz.html

[T26] Swift：类与重写
来源：http://dali.gotoacloud.top/Article/details/gt2jghcswlq.html

class A: Base { override func f() {} }
来源：http://dali.yj20258.top/Article/details/gt2xtbvpgid.html

[T27] Swift：错误处理
来源：http://dali.smart0.xyz/Article/details/gt2dyiyplge.html

do { try f() } catch { print(error) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nnmaseei.html

[T28] Swift：枚举
来源：http://dali.cqqwz.cn/Article/details/gt2ceoecljm.html

enum Color { case red, green }
来源：http://dali.yj20258888.top/Article/details/gt2hpctelae.html

[T29] Swift：guard 提前返回
来源：http://dali.hysaishi.cn/Article/details/gt2tgvsmvrg.html

guard let x = opt else { return }
来源：http://dali.cucudq.cn/Article/details/gt2qkrxaoqz.html

[T30] Swift：协议
来源：http://dali.yj20258888.top/Article/details/gt2rnoperui.html

protocol Shape { func area() -> Double }
来源：http://dali.gotoacloud.top/Article/details/gt2jjjrawor.html

[T31] Lua：Hello World
来源：http://dali.yuanzhike.top/Article/details/gt2xmyamjlc.html

print("Hello")
来源：http://dali.hammf.cn/Article/details/gt2kzgngasr.html

[T32] Lua：局部变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tbowwnzb.html

local a = 1
来源：http://dali.xylfe.cn/Article/details/gt2pzrjqgue.html

[T33] Lua：表（数组）
来源：http://dali.guowangkeji.top/Article/details/gt2isiatdsf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mwpgbskd.html

[T34] Lua：遍历表
来源：http://dali.yj20258.top/Article/details/gt2cbohyifp.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.sufxvd.cn/Article/details/gt2qgvxuguw.html

[T35] Lua：字典表
来源：http://dali.pengpengdd.cyou/Article/details/gt2vmvlrxdt.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nmdetaur.html

[T36] Lua：函数
来源：http://dali.havefunace.top/Article/details/gt2snetiwcl.html

function add(a, b) return a + b end
来源：http://dali.jinqigfzy.top/Article/details/gt2apazcntm.html

[T37] Lua：字符串拼接
来源：http://dali.wangshuangyany.cn/Article/details/gt2ujungtld.html

"a" .. "b"
来源：http://dali.zhengqikj.top/Article/details/gt2qmjljfhs.html

[T38] Lua：条件
来源：http://dali.shzxlz.cn/Article/details/gt2zeymrvoa.html

if x > 0 then print("正") end
来源：http://dali.tianlin.xyz/Article/details/gt2kgppwwqi.html

[T39] Lua：模式匹配
来源：http://dali.xinyue.icu/Article/details/gt2jvdfvtdy.html

string.find(s, "%d+")
来源：http://dali.zdqjudy.top/Article/details/gt2bxkwopef.html

[T40] Lua：元表
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ovygagvy.html

setmetatable({}, { __index = base })
来源：http://dali.bjfxy.top/Article/details/gt2cgyiserm.html

[T41] Perl：Hello World
来源：http://dali.hnqzz.top/Article/details/gt2nipdabgo.html

print "Hello\n";
来源：http://dali.snrcjt.cn/Article/details/gt2rwkupcer.html

[T42] Perl：变量类型
来源：http://dali.nanxinkj.top/Article/details/gt2uegtbrgd.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yonumen.top/Article/details/gt2tfcznnvu.html

[T43] Perl：字符串插值
来源：http://dali.nanxuanxn.top/Article/details/gt2mljpncld.html

"值: $a"
来源：http://dali.hfpthk.cn/Article/details/gt2ufgjqbiy.html

[T44] Perl：条件
来源：http://dali.sxryk.cn/Article/details/gt2lanvjadq.html

if ($a > 0) { print "正"; }
来源：http://dali.aizwys.cn/Article/details/gt2tloevgst.html

[T45] Perl：数组遍历
来源：http://dali.pengpengdd.cyou/Article/details/gt2vjphuglo.html

for my $x (@arr) { print $x; }
来源：http://dali.mhx1999.top/Article/details/gt2indclyif.html

[T46] Perl：哈希操作
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tipimjup.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhixingplan.top/Article/details/gt2tlbrqdxn.html

[T47] Perl：正则捕获
来源：http://dali.meibo888.top/Article/details/gt2fqmmsgjg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.dashuyun.cn/Article/details/gt2qaqdjgpq.html

[T48] Perl：正则替换
来源：http://dali.zhiwuduotai.top/Article/details/gt2nqdwtkec.html

$s =~ s/old/new/g;
来源：http://dali.tanke756.top/Article/details/gt2kefzprzi.html

[T49] Perl：函数
来源：http://dali.aizwys.cn/Article/details/gt2wticjaty.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.sysykeji.top/Article/details/gt2abflksnu.html

[T50] Perl：逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gt2ykoiqjjx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hywenlv.cn/Article/details/gt2ufviopvn.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yj202588.top/Article/details/gt2ldbgixnz.html

[T51] Scala：Hello World
来源：http://dali.ehwqpu.com/Article/details/gt2wzsophwy.html

println("Hello")
来源：http://dali.zdqjudy.top/Article/details/gt2undldgdx.html

[T52] Scala：变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2zvvmvaur.html

val a = 1;  var b = 2
来源：http://dali.sufxvd.cn/Article/details/gt2hflpevly.html

[T53] Scala：字符串插值
来源：http://dali.yongpay.top/Article/details/gt2tknfrbxe.html

s"值: $b"
来源：http://dali.gzhubu.top/Article/details/gt2dqkmcvqe.html

[T54] Scala：集合映射
来源：http://dali.zhiwuduotai.top/Article/details/gt2ygfdbwvs.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.nanxuanxn.top/Article/details/gt2pqhfpndd.html

[T55] Scala：集合过滤
来源：http://dali.pengpengdd.cyou/Article/details/gt2vkigduwi.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zycfv.cn/Article/details/gt2editpygh.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2dhsjqqih.html

case class User(name: String, age: Int)
来源：http://dali.dashuyun.cn/Article/details/gt2szpsfqxs.html

[T57] Scala：模式匹配
来源：http://dali.yuanzhike.top/Article/details/gt2hbgnsszy.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.gogol.net.cn/Article/details/gt2ffbyrcmg.html

[T58] Scala：函数定义
来源：http://dali.sweek.top/Article/details/gt2zflcqnik.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.mhx1999.top/Article/details/gt2unziwuvh.html

[T59] Scala：循环
来源：http://dali.cheryme.top/Article/details/gt2qjsqygmp.html

for (i <- 1 to 10) println(i)
来源：http://dali.zycfv.cn/Article/details/gt2ikqzdimj.html

[T60] Scala：折叠
来源：http://dali.zhoulong.xyz/Article/details/gt2qkvnwlxf.html


<!-- 参考信息 -->