代发 wailian999

ssh user@host 'uptime'
来源：http://dali.gotoacloud.top/Article/details/gt2hpbamgww.html

[R58] 下载文件
来源：http://dali.sysykeji.top/Article/details/gt2bofpjxbq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.mhx1999.top/Article/details/gt2xowrpvcv.html

[R59] 发 POST JSON
来源：http://dali.shangyingyoupin.top/Article/details/gt2cckrldgv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ofyxlbgi.html

[R60] 只看 HTTP 状态码
来源：http://dali.dashuyun.cn/Article/details/gt2muhxfdmj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gogol.net.cn/Article/details/gt2cmipvmcu.html

[R61] 磁盘占用
来源：http://dali.hywenlv.cn/Article/details/gt2ffkideas.html

df -h;  du -sh *
来源：http://dali.chenzaomai.com/Article/details/gt2fojqqoid.html

[R62] 找最占空间的文件
来源：http://dali.pycfn.com/Article/details/gt2zsxdndcl.html

du -ah . | sort -rh | head -10
来源：http://dali.zhongyouzk.top/Article/details/gt2bmguiohv.html

[R63] 内存与进程
来源：http://dali.316326.xyz/Article/details/gt2fbkxqqwn.html

free -h;  ps aux | grep nginx
来源：http://dali.havefunace.top/Article/details/gt2dxrpplns.html

[R64] 结束进程
来源：http://dali.jlsjyb.cn/Article/details/gt2vpymxnvb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uctemukz.html

[R65] 查看端口占用
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2whbyslwj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.316326.xyz/Article/details/gt2hmfjwnka.html

[R66] 定时任务
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ojdhftgp.html

crontab -e;  crontab -l
来源：http://dali.yangfankeji.com/Article/details/gt2ofkqclss.html

[R67] 生成随机十六进制串
来源：http://dali.jiagoushi.top/Article/details/gt2kvzlmawo.html

openssl rand -hex 16
来源：http://dali.yuxming.cn/Article/details/gt2pwxrqkcy.html

[R68] 计算文件校验值
来源：http://dali.xziqi.cn/Article/details/gt2imkpnohl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xziqi.cn/Article/details/gt2lbczqqis.html

[R69] 生成随机密码
来源：http://dali.jinqigfzy.top/Article/details/gt2wrshwkpw.html

head -c 16 /dev/urandom | base64
来源：http://dali.yj20258888.top/Article/details/gt2wcznzqir.html

[R70] 时间戳与互转
来源：http://dali.xuanzx.com/Article/details/gt2ixeowfsq.html

date +%s;  date -d @1700000000
来源：http://dali.ivvv.top/Article/details/gt2jxfdmfvd.html

[R71] 日期格式化
来源：http://dali.yuxming.cn/Article/details/gt2wugopdwn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xylfe.cn/Article/details/gt2wdcbpkxd.html

[R72] 等待端口就绪
来源：http://dali.andypj.xyz/Article/details/gt2rwdfosjq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.c1oappe.top/Article/details/gt2dnvoejce.html

[R73] 分割大日志
来源：http://dali.vqdsnc.cn/Article/details/gt2fvhagbsi.html

split -l 1000 big.log part_
来源：http://dali.tianlin.xyz/Article/details/gt2qhcgvvcm.html

[R74] 批量重命名
来源：http://dali.yuanzhike.top/Article/details/gt2jbcrskaf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yuanzhike.top/Article/details/gt2lgobvcsa.html

[R75] 导出环境变量
来源：http://dali.chenzaomai.com/Article/details/gt2qnwjekgf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.fengsongda.top/Article/details/gt2lgnumijx.html

[R76] 使用临时文件
来源：http://dali.xinyue.icu/Article/details/gt2rjdvmdfu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.birdmap.top/Article/details/gt2gbruzbjq.html

[R77] 读取用户输入
来源：http://dali.ppjwa.cn/Article/details/gt2zjorajub.html

read -rp "请输入: " ans
来源：http://dali.chenzaomai.com/Article/details/gt2ichbvcuu.html

[R78] 交互式菜单
来源：http://dali.zhiwuduotai.top/Article/details/gt2rzkxyifw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.snrcjt.cn/Article/details/gt2fbuudgdj.html

[R79] 解析命令行选项
来源：http://dali.kuanghao11.cn/Article/details/gt2pmovhzgp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kpdjppow.html

[R80] 查看脚本执行耗时
来源：http://dali.chenzaomai.com/Article/details/gt2zlrpwscj.html

time ./run.sh
来源：http://dali.svipenyu.cn/Article/details/gt2cixutdyk.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2auwwsssq.html

S. C / C++ 专题
来源：http://dali.gogol.net.cn/Article/details/gt2bhgslxqf.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2iqahblfn.html

[S01] C：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gt2jeruzfkp.html

#include <stdio.h>
来源：http://dali.pengpengdd.cyou/Article/details/gt2psfypwpi.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2hncynpij.html

[S02] C：变量与格式化输出
来源：http://dali.daria6918.cn/Article/details/gt2mkdiesuq.html

int a = 10; printf("%d\n", a);
来源：http://dali.xinyue.icu/Article/details/gt2trrmfrwu.html

[S03] C：读入整数
来源：http://dali.0kj1m.cn/Article/details/gt2vluudmhi.html

int x; scanf("%d", &x);
来源：http://dali.fzhhl.top/Article/details/gt2ycqfxfme.html

[S04] C：字符串复制
来源：http://dali.feifeiyinyue.top/Article/details/gt2qhnahwdv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cqqwz.cn/Article/details/gt2fcjhlwph.html

[S05] C：字符串长度
来源：http://dali.guowangkeji.top/Article/details/gt2umesulze.html

strlen(s)
来源：http://dali.havefunace.top/Article/details/gt2zaqtbhql.html

[S06] C：字符串比较
来源：http://dali.jqgfzy.top/Article/details/gt2khtqkoup.html

strcmp(a, b) == 0
来源：http://dali.ybcxt.top/Article/details/gt2roosvbku.html

[S07] C：数组遍历求和
来源：http://dali.gotoacloud.top/Article/details/gt2siijfjrg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cdnleiting.top/Article/details/gt2izerlvml.html

[S08] C：动态内存分配与释放
来源：http://dali.snrcjt.cn/Article/details/gt2hfcpiocf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gotoacloud.top/Article/details/gt2qfkfznyh.html

[S09] C：结构体定义与初始化
来源：http://dali.fzhhl.top/Article/details/gt2iokhugzx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cashguo.top/Article/details/gt2vmofbaip.html

[S10] C：指针与解引用
来源：http://dali.xylfe.cn/Article/details/gt2bsskqqdw.html

int *p = &a;  *p = 5;
来源：http://dali.gaohongyu789.top/Article/details/gt2dmvzenxr.html

[S11] C：逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2rhqamiel.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.tianlin.xyz/Article/details/gt2aiopyobd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hysaishi.cn/Article/details/gt2rzfglwgm.html

fclose(f);
来源：http://dali.dianchejie.cn/Article/details/gt2moigsmmo.html

[S12] C：写文件
来源：http://dali.smart0.xyz/Article/details/gt2ggkehvpi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.316326.xyz/Article/details/gt2zmbrdrum.html

[S13] C：宏定义
来源：http://dali.hfpthk.cn/Article/details/gt2jrojwtml.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.dianchejie.cn/Article/details/gt2jlpnxqly.html

[S14] C：枚举
来源：http://dali.cqqwz.cn/Article/details/gt2wixufthi.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.chenlongwang.top/Article/details/gt2yrtpuslk.html

[S15] C：类型转换
来源：http://dali.chenlongwang.top/Article/details/gt2jnpzjuxk.html

(double) a / b
来源：http://dali.svipenyu.cn/Article/details/gt2dhsmxipu.html

[S16] C：位操作置位
来源：http://dali.quarkkingdee.top/Article/details/gt2mvgwimug.html

x |= (1 << 3);
来源：http://dali.zhixingplan.top/Article/details/gt2nwufegjt.html

[S17] C：安全拼接字符串
来源：http://dali.yj20258888.top/Article/details/gt2ajjbongs.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.daria6918.cn/Article/details/gt2ijoqltwa.html

[S18] C：命令行参数
来源：http://dali.yangfankeji.com/Article/details/gt2rdeejqle.html

int main(int argc, char **argv)
来源：http://dali.tian-w.cn/Article/details/gt2rjhmdpfo.html

[S19] C：快速排序
来源：http://dali.xziqi.cn/Article/details/gt2tsdddbra.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2guqwvqao.html

[S20] C：二分查找
来源：http://dali.yj202588.top/Article/details/gt2uukpenpc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.kuanghao11.cn/Article/details/gt2mcjrcpzv.html

[S21] C：字符类别判断
来源：http://dali.yongpay.top/Article/details/gt2vhyqymkb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.birdmap.top/Article/details/gt2pbssgfml.html

[S22] C：字符串转数字
来源：http://dali.jiagoushi.top/Article/details/gt2udxkwdtg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cdnleiting.top/Article/details/gt2uorsuvrb.html

[S23] C：随机数
来源：http://dali.wangdashe.top/Article/details/gt2xnyvkwnc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cqqwz.cn/Article/details/gt2kxqxyllx.html

[S24] C：获取本地时间
来源：http://dali.yj20258888.top/Article/details/gt2zushrbvb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ngojbdjd.html

[S25] C：内存拷贝
来源：http://dali.chenzaomai.com/Article/details/gt2lwjkrzfh.html

memcpy(dst, src, n);
来源：http://dali.nanxinkj.top/Article/details/gt2rjnixscg.html

[S26] C：内存清零
来源：http://dali.vqdsnc.cn/Article/details/gt2qnhqfcup.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlfgvpcc.html

[S27] C：定义常量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2inwvnqbv.html

const double PI = 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gt2iotbftrq.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mvtilbby.html

static int counter = 0;
来源：http://dali.aibaodan.cn/Article/details/gt2wtuueick.html

[S29] C：变参函数
来源：http://dali.ivvv.top/Article/details/gt2szqfwmws.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.guannengcc.top/Article/details/gt2srytajrf.html

[S30] C：头文件保护
来源：http://dali.zhixingplan.top/Article/details/gt2dmuijcat.html

#ifndef X_H
来源：http://dali.chenzaomai.com/Article/details/gt2gtmrafna.html

#define X_H
来源：http://dali.birdmap.top/Article/details/gt2rehgfwnf.html

#endif
来源：http://dali.chenzaomai.com/Article/details/gt2dkmytgls.html

[S31] C++：Hello World
来源：http://dali.guowangkeji.top/Article/details/gt2vvbzgaqe.html

#include <iostream>
来源：http://dali.sufxvd.cn/Article/details/gt2sctfljmd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zycfv.cn/Article/details/gt2gjfsfsec.html

[S32] C++：字符串
来源：http://dali.jlsjyb.cn/Article/details/gt2vxshsuyr.html

std::string s = "hi";  s += "!";
来源：http://dali.xziqi.cn/Article/details/gt2kxdnrdtc.html

[S33] C++：vector 增删
来源：http://dali.yvedp.cn/Article/details/gt2kdkiuujs.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.nwbrower.top/Article/details/gt2gwmkkoiz.html

[S34] C++：遍历 vector
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qpoaoqvz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.meibo888.top/Article/details/gt2kxmfwuko.html

[S35] C++：map
来源：http://dali.ehwqpu.com/Article/details/gt2evprxmgl.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gt2ihhuoxpu.html

[S36] C++：unordered_map
来源：http://dali.jianghu66.top/Article/details/gt2usbmvhks.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gt2skaabsts.html

[S37] C++：set
来源：http://dali.wangdashe.top/Article/details/gt2mzpgofkw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.tianlin.xyz/Article/details/gt2kargcnrv.html

[S38] C++：排序
来源：http://dali.fzhhl.top/Article/details/gt2reopqmcs.html

std::sort(v.begin(), v.end());
来源：http://dali.iojbl.cn/Article/details/gt2bgmowecc.html

[S39] C++：自定义比较器排序
来源：http://dali.yangfankeji.com/Article/details/gt2upsryhpn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hammf.cn/Article/details/gt2widfmokg.html

[S40] C++：查找元素
来源：http://dali.gzhubu.top/Article/details/gt2vnjxoerf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.guowangkeji.top/Article/details/gt2xjgyblkz.html

[S41] C++：类与构造函数
来源：http://dali.xinyue.icu/Article/details/gt2rqzqauzn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hnqzz.top/Article/details/gt2pymvdlzn.html

[S42] C++：继承与虚函数
来源：http://dali.yongpay.top/Article/details/gt2nqvdpwlg.html

class B : public Base { public: void f() override {} };
来源：http://dali.guannengcc.top/Article/details/gt2eejrdhjg.html

[S43] C++：智能指针
来源：http://dali.mhx1999.top/Article/details/gt2hsuljaum.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhongyouzk.top/Article/details/gt2neuezvyw.html

[S44] C++：引用传参
来源：http://dali.xylfe.cn/Article/details/gt2hsthcxdz.html

void inc(int &x) { ++x; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bfizkorh.html

[S45] C++：lambda
来源：http://dali.yj20258888.top/Article/details/gt2rkyfmchg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.nanxinkj.top/Article/details/gt2cnznfuni.html

[S46] C++：函数模板
来源：http://dali.cdnleiting.top/Article/details/gt2wstptcjl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.quarkkingdee.top/Article/details/gt2yivpbapw.html

[S47] C++：结构化绑定遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mwcleqxr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gotoacloud.top/Article/details/gt2nuhnhzqi.html

[S48] C++：逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rwsvbzks.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cucudq.cn/Article/details/gt2nuskwmds.html

while (std::getline(in, line)) { }
来源：http://dali.jiagoushi.top/Article/details/gt2svzrsznz.html

[S49] C++：写文件
来源：http://dali.hfpthk.cn/Article/details/gt2pkhaknim.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.iojbl.cn/Article/details/gt2uvhlsmso.html

[S50] C++：格式化数字
来源：http://dali.zhiwuduotai.top/Article/details/gt2wjfwoeol.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gt2qyxnmvml.html

[S51] C++：显式类型转换
来源：http://dali.birdmap.top/Article/details/gt2mozvbhvr.html

static_cast<double>(a) / b
来源：http://dali.xuanzx.com/Article/details/gt2zmbhvvbu.html

[S52] C++：const 与 noexcept
来源：http://dali.snrcjt.cn/Article/details/gt2vpeaajwo.html

int size() const noexcept { return n_; }
来源：http://dali.hysaishi.cn/Article/details/gt2yqnaoikj.html

[S53] C++：移动语义
来源：http://dali.sxryk.cn/Article/details/gt2ffrxrogc.html

std::vector<int> w = std::move(v);
来源：http://dali.xinyue.icu/Article/details/gt2ehyezatl.html

[S54] C++：异常处理
来源：http://dali.yuanzhike.top/Article/details/gt2lteogawb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhongyouzk.top/Article/details/gt2rxlvmqug.html

[S55] C++：结构化绑定
来源：http://dali.haohaochexian.top/Article/details/gt2hodfydqo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yueranfly.top/Article/details/gt2ylpdcmro.html

[S56] C++：optional
来源：http://dali.feifeiyinyue.top/Article/details/gt2blneesir.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hammf.cn/Article/details/gt2bklsecnu.html

[S57] C++：编译期常量
来源：http://dali.yuanzhike.top/Article/details/gt2nqtffxjy.html

constexpr int N = 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2utnisgpw.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2glkemybj.html

namespace ns { int f() { return 1; } }
来源：http://dali.jqgufenzy.top/Article/details/gt2woaouowm.html

[S59] C++：静态断言
来源：http://dali.birdmap.top/Article/details/gt2tgagqfql.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.pengpengdd.cyou/Article/details/gt2dkfdznhu.html

[S60] C++：遍历并删除元素
来源：http://dali.kuanghao11.cn/Article/details/gt2agouliuz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.nanxinkj.top/Article/details/gt2ewtvnmyt.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fcuyjdsm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.dianchejie.cn/Article/details/gt2fvbvhkps.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2xoaxurxz.html

[T01] Kotlin：Hello World
来源：http://dali.aibaodan.cn/Article/details/gt2mftjsxcl.html

println("Hello")
来源：http://dali.chenlongwang.top/Article/details/gt2hjqyvfsj.html

[T02] Kotlin：变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2snhxkfcm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.snrcjt.cn/Article/details/gt2eypslmmj.html

[T03] Kotlin：字符串模板
来源：http://dali.bjfxy.top/Article/details/gt2wuwpdpcb.html

"值: $b"
来源：http://dali.jyoumei.cn/Article/details/gt2cxhucfgz.html

[T04] Kotlin：空安全
来源：http://dali.chenlongwang.top/Article/details/gt2kepfhspb.html

val n: String? = null;  n?.length
来源：http://dali.c1oappe.top/Article/details/gt2frtuqkwj.html

[T05] Kotlin：when 表达式
来源：http://dali.hnxiangtu.top/Article/details/gt2evhwxcik.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sufxvd.cn/Article/details/gt2xiuefkud.html

[T06] Kotlin：集合映射
来源：http://dali.sysykeji.top/Article/details/gt2ddnhylxo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.meibo888.top/Article/details/gt2udecmdzj.html

[T07] Kotlin：集合过滤
来源：http://dali.zhiwuduotai.top/Article/details/gt2brljroes.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shangyingyoupin.top/Article/details/gt2nwzeglcv.html

[T08] Kotlin：数据类
来源：http://dali.yvedp.cn/Article/details/gt2xsubyino.html

data class User(val name: String, val age: Int)
来源：http://dali.andypj.xyz/Article/details/gt2spuljkke.html

[T09] Kotlin：扩展函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2cdbnsthw.html

fun String.exclaim() = this + "!"
来源：http://dali.feifeiyinyue.top/Article/details/gt2hkjdcmlw.html

[T10] Kotlin：默认参数
来源：http://dali.316326.xyz/Article/details/gt2fybzhohj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.aizwys.cn/Article/details/gt2uacynjek.html

[T11] Kotlin：协程
来源：http://dali.nanxinkj.top/Article/details/gt2jhyrdqfy.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yanxiufei.cn/Article/details/gt2enuhdeuv.html

[T12] Kotlin：解构声明
来源：http://dali.snrcjt.cn/Article/details/gt2aultqgsp.html

val (a, b) = Pair(1, 2)
来源：http://dali.yuanzhike.top/Article/details/gt2lhseecld.html

[T13] Kotlin：只读 Map
来源：http://dali.xuanzx.com/Article/details/gt2fdddixkw.html

val m = mapOf("a" to 1)
来源：http://dali.jlsjyb.cn/Article/details/gt2kbpuqkis.html

[T14] Kotlin：循环
来源：http://dali.jinqigufen.top/Article/details/gt2lmotqgsb.html

for (i in 1..10) println(i)
来源：http://dali.jyoumei.cn/Article/details/gt2smgsxoqw.html

[T15] Kotlin：接口
来源：http://dali.jqgufenzy.top/Article/details/gt2loubywah.html

interface Shape { fun area(): Double }
来源：http://dali.andypj.xyz/Article/details/gt2hmimsbzf.html

[T16] Swift：Hello World
来源：http://dali.gzhubu.top/Article/details/gt2jwzqglru.html

print("Hello")
来源：http://dali.bjfxy.top/Article/details/gt2ejysfeka.html

[T17] Swift：变量与常量
来源：http://dali.aizwys.cn/Article/details/gt2jtwgtijd.html

var a = 1;  let b = 2
来源：http://dali.shangyingyoupin.top/Article/details/gt2hcwdhgbl.html

[T18] Swift：字符串插值
来源：http://dali.gaohongyu789.top/Article/details/gt2kdgoysmr.html

"值: \(b)"
来源：http://dali.wangshuangyany.cn/Article/details/gt2unlsvswu.html

[T19] Swift：可选绑定
来源：http://dali.aibaodan.cn/Article/details/gt2ablyrrxj.html

if let n = opt { print(n) }
来源：http://dali.zhoulong.xyz/Article/details/gt2ahmscpwn.html

[T20] Swift：数组操作
来源：http://dali.zhiwuduotai.top/Article/details/gt2tctgtdjf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.fzhhl.top/Article/details/gt2ppauhqjc.html

[T21] Swift：遍历
来源：http://dali.shzxlz.cn/Article/details/gt2dhdxgyuw.html

for x in a { print(x) }
来源：http://dali.jlsjyb.cn/Article/details/gt2uxpfrixc.html

[T22] Swift：字典
来源：http://dali.xuetiantiany.cn/Article/details/gt2jlbgoopm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.pengpengdd.cyou/Article/details/gt2dollemvx.html

[T23] Swift：函数
来源：http://dali.quarkkingdee.top/Article/details/gt2elatlbax.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cqqwz.cn/Article/details/gt2iodjihjk.html

[T24] Swift：闭包
来源：http://dali.9152youxi.cn/Article/details/gt2ryymxnnq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.sysykeji.top/Article/details/gt2neuyhcmv.html

[T25] Swift：结构体
来源：http://dali.kuanghao11.cn/Article/details/gt2lrjujtyn.html

struct P { var x: Int }
来源：http://dali.yvedp.cn/Article/details/gt2oqhmpaia.html

[T26] Swift：类与重写
来源：http://dali.9152youxi.cn/Article/details/gt2qflabykc.html

class A: Base { override func f() {} }
来源：http://dali.iojbl.cn/Article/details/gt2qnqraqwx.html

[T27] Swift：错误处理
来源：http://dali.xylfe.cn/Article/details/gt2tfugpwae.html

do { try f() } catch { print(error) }
来源：http://dali.sufxvd.cn/Article/details/gt2sguoyzyn.html

[T28] Swift：枚举
来源：http://dali.redwolf501.top/Article/details/gt2uoiivemr.html

enum Color { case red, green }
来源：http://dali.fengsongda.top/Article/details/gt2xifplikf.html

[T29] Swift：guard 提前返回
来源：http://dali.cqqwz.cn/Article/details/gt2vsofnkhf.html

guard let x = opt else { return }
来源：http://dali.ppjwa.cn/Article/details/gt2qniplhhn.html

[T30] Swift：协议
来源：http://dali.andypj.xyz/Article/details/gt2tfepfqus.html

protocol Shape { func area() -> Double }
来源：http://dali.wangdashe.top/Article/details/gt2fekzvosc.html

[T31] Lua：Hello World
来源：http://dali.wangdashe.top/Article/details/gt2zmljrwqx.html

print("Hello")
来源：http://dali.yvedp.cn/Article/details/gt2wfrstvld.html

[T32] Lua：局部变量
来源：http://dali.jqgufenzy.top/Article/details/gt2dnmapjwi.html

local a = 1
来源：http://dali.yueranfly.top/Article/details/gt2ccnpffvs.html

[T33] Lua：表（数组）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xblftnnz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.chenzaomai.com/Article/details/gt2qlnylvbh.html

[T34] Lua：遍历表
来源：http://dali.pycfn.com/Article/details/gt2bwbxcmkg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xinyue.icu/Article/details/gt2uxkxxmvf.html

[T35] Lua：字典表
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vcsxacgp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hongshengwenyu.top/Article/details/gt2pxygilzx.html

[T36] Lua：函数
来源：http://dali.cashguo.top/Article/details/gt2hcvgtwsx.html

function add(a, b) return a + b end
来源：http://dali.cdnleiting.top/Article/details/gt2vjvssrhg.html

[T37] Lua：字符串拼接
来源：http://dali.fengsongda.top/Article/details/gt2wixxacvy.html

"a" .. "b"
来源：http://dali.chenjidiqi.icu/Article/details/gt2jizbbxsr.html

[T38] Lua：条件
来源：http://dali.jinqigfzy.top/Article/details/gt2otogpdie.html

if x > 0 then print("正") end
来源：http://dali.yangfankeji.com/Article/details/gt2jwsauthx.html

[T39] Lua：模式匹配
来源：http://dali.pengpengdd.cyou/Article/details/gt2gutmyybe.html

string.find(s, "%d+")
来源：http://dali.nwbrower.top/Article/details/gt2jjhwvujz.html

[T40] Lua：元表
来源：http://dali.316326.xyz/Article/details/gt2xuxecfas.html

setmetatable({}, { __index = base })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hijskvnb.html

[T41] Perl：Hello World
来源：http://dali.316326.xyz/Article/details/gt2mgvxfzxs.html

print "Hello\n";
来源：http://dali.ivvv.top/Article/details/gt2iikyzind.html

[T42] Perl：变量类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yfgjaxzc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.redwolf501.top/Article/details/gt2zodcoajb.html

[T43] Perl：字符串插值
来源：http://dali.tanke756.top/Article/details/gt2rpoybdmv.html

"值: $a"
来源：http://dali.316326.xyz/Article/details/gt2liimvzuj.html

[T44] Perl：条件
来源：http://dali.jlsjyb.cn/Article/details/gt2rkfjaiha.html

if ($a > 0) { print "正"; }
来源：http://dali.cucudq.cn/Article/details/gt2fkhdgyvf.html

[T45] Perl：数组遍历
来源：http://dali.jlsjyb.cn/Article/details/gt2vqyzscwd.html

for my $x (@arr) { print $x; }
来源：http://dali.yj20258888.top/Article/details/gt2qyzuecmb.html

[T46] Perl：哈希操作
来源：http://dali.smart0.xyz/Article/details/gt2znqpisyt.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2iopajjld.html

[T47] Perl：正则捕获
来源：http://dali.xinyue.icu/Article/details/gt2azyyglac.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhongyouzk.top/Article/details/gt2nlpdjpae.html

[T48] Perl：正则替换
来源：http://dali.nanxinkj.top/Article/details/gt2npixejal.html

$s =~ s/old/new/g;
来源：http://dali.nanxinkj.top/Article/details/gt2aoexsdkf.html

[T49] Perl：函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2mneizkle.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2kfynjftn.html

[T50] Perl：逐行读文件
来源：http://dali.yongpay.top/Article/details/gt2qzsuavie.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yuanzhike.top/Article/details/gt2wgreddsw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wutfhvtq.html

[T51] Scala：Hello World
来源：http://dali.aibaodan.cn/Article/details/gt2ixmhykax.html

println("Hello")
来源：http://dali.guannengcc.top/Article/details/gt2mxupmlte.html

[T52] Scala：变量
来源：http://dali.tianlin.xyz/Article/details/gt2fhemgary.html

val a = 1;  var b = 2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wirnxmks.html

[T53] Scala：字符串插值
来源：http://dali.gotoacloud.top/Article/details/gt2zyvmugjn.html

s"值: $b"
来源：http://dali.pengpengdd.cyou/Article/details/gt2ctyjwgdj.html

[T54] Scala：集合映射
来源：http://dali.xziqi.cn/Article/details/gt2xjdconev.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.sufxvd.cn/Article/details/gt2ekpbhycb.html

[T55] Scala：集合过滤
来源：http://dali.andypj.xyz/Article/details/gt2akckkped.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.pycfn.com/Article/details/gt2sylscvrd.html

[T56] Scala：样例类
来源：http://dali.zhixingplan.top/Article/details/gt2ytnhepuw.html

case class User(name: String, age: Int)
来源：http://dali.yueranfly.top/Article/details/gt2xgrdhtyq.html

[T57] Scala：模式匹配
来源：http://dali.yangfankeji.com/Article/details/gt2inspaujb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hongshengwenyu.top/Article/details/gt2fpzxgtle.html

[T58] Scala：函数定义
来源：http://dali.fengsongda.top/Article/details/gt2bevadxkq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xlalafcm.html

[T59] Scala：循环
来源：http://dali.ydzc1.top/Article/details/gt2qhvxhiop.html

for (i <- 1 to 10) println(i)
来源：http://dali.gaohongyu789.top/Article/details/gt2xigrybwg.html

[T60] Scala：折叠
来源：http://dali.yuanzhike.top/Article/details/gt2czrlyxrn.html


<!-- 参考信息 -->