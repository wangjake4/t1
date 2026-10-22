代发 wailian999

ssh user@host 'uptime'
来源：http://dali.jianghu66.top/Article/details/gt2wvwewfzt.html

[R58] 下载文件
来源：http://dali.gzhubu.top/Article/details/gt2esdbyhnu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.kuanghao11.cn/Article/details/gt2nveixyay.html

[R59] 发 POST JSON
来源：http://dali.guowangkeji.top/Article/details/gt2xvzgwqfj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.nanxinkj.top/Article/details/gt2zpdczpwp.html

[R60] 只看 HTTP 状态码
来源：http://dali.c1oappe.top/Article/details/gt2ytffwvpf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sufxvd.cn/Article/details/gt2hklufxhz.html

[R61] 磁盘占用
来源：http://dali.yangfankeji.com/Article/details/gt2iicuhcks.html

df -h;  du -sh *
来源：http://dali.havefunace.top/Article/details/gt2nusebovi.html

[R62] 找最占空间的文件
来源：http://dali.sxryk.cn/Article/details/gt2hwbbnbmy.html

du -ah . | sort -rh | head -10
来源：http://dali.ybcxt.top/Article/details/gt2qqjoncxm.html

[R63] 内存与进程
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gjjqhvmg.html

free -h;  ps aux | grep nginx
来源：http://dali.ydzc1.top/Article/details/gt2qreialcy.html

[R64] 结束进程
来源：http://dali.gaohongyu789.top/Article/details/gt2xdfabeaj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.tianlin.xyz/Article/details/gt2lixaxvqx.html

[R65] 查看端口占用
来源：http://dali.vqdsnc.cn/Article/details/gt2wwgemgct.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.pengpengdd.cyou/Article/details/gt2matlmmrj.html

[R66] 定时任务
来源：http://dali.jinqigufen.top/Article/details/gt2ffqbwlmv.html

crontab -e;  crontab -l
来源：http://dali.ppjwa.cn/Article/details/gt2uplpuzpr.html

[R67] 生成随机十六进制串
来源：http://dali.hongshengwenyu.top/Article/details/gt2pgfknyri.html

openssl rand -hex 16
来源：http://dali.feifeiyinyue.top/Article/details/gt2xqhyrkkz.html

[R68] 计算文件校验值
来源：http://dali.yj20258.top/Article/details/gt2stjvqmpp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jyoumei.cn/Article/details/gt2zqjjurtu.html

[R69] 生成随机密码
来源：http://dali.aizwys.cn/Article/details/gt2gxbyxqku.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinqigfzy.top/Article/details/gt2tcoegfbp.html

[R70] 时间戳与互转
来源：http://dali.chenjidiqi.icu/Article/details/gt2cdmmscva.html

date +%s;  date -d @1700000000
来源：http://dali.jqgufenzy.top/Article/details/gt2bnwrbmkz.html

[R71] 日期格式化
来源：http://dali.shzxlz.cn/Article/details/gt2qybkxhgq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.feifeiyinyue.top/Article/details/gt2ucvxowoz.html

[R72] 等待端口就绪
来源：http://dali.bjfxy.top/Article/details/gt2vtqswxmw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hfpthk.cn/Article/details/gt2gxrkmtvl.html

[R73] 分割大日志
来源：http://dali.jlsjyb.cn/Article/details/gt2wuuatylv.html

split -l 1000 big.log part_
来源：http://dali.316326.xyz/Article/details/gt2txeremag.html

[R74] 批量重命名
来源：http://dali.316326.xyz/Article/details/gt2nlkvwvup.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ycashwlx.html

[R75] 导出环境变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kghdozjj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sysykeji.top/Article/details/gt2avbzqmet.html

[R76] 使用临时文件
来源：http://dali.shuidangran.top/Article/details/gt2otenbjmv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuxming.cn/Article/details/gt2ygqswuxu.html

[R77] 读取用户输入
来源：http://dali.fzhhl.top/Article/details/gt2iwtduhbb.html

read -rp "请输入: " ans
来源：http://dali.gogol.net.cn/Article/details/gt2lpxuwcqf.html

[R78] 交互式菜单
来源：http://dali.yonumen.top/Article/details/gt2uaqdtlxa.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iretsjez.html

[R79] 解析命令行选项
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lyrrezxs.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.dashuyun.cn/Article/details/gt2xkyfybbn.html

[R80] 查看脚本执行耗时
来源：http://dali.havefunace.top/Article/details/gt2tekemkin.html

time ./run.sh
来源：http://dali.yanxiufei.cn/Article/details/gt2kloojuxj.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2idnerllk.html

S. C / C++ 专题
来源：http://dali.yj20258.top/Article/details/gt2xxplbvqz.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2nadrkegi.html

[S01] C：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gt2duvijmgm.html

#include <stdio.h>
来源：http://dali.hywenlv.cn/Article/details/gt2uumkjmyy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.mhx1999.top/Article/details/gt2oecgmmnw.html

[S02] C：变量与格式化输出
来源：http://dali.wangshuangyany.cn/Article/details/gt2oscbdrxj.html

int a = 10; printf("%d\n", a);
来源：http://dali.chenlongwang.top/Article/details/gt2vrghsvjn.html

[S03] C：读入整数
来源：http://dali.hammf.cn/Article/details/gt2frwnadjy.html

int x; scanf("%d", &x);
来源：http://dali.gotoacloud.top/Article/details/gt2enmqjhvv.html

[S04] C：字符串复制
来源：http://dali.jinqigufen.top/Article/details/gt2rhkvuojr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.aibaodan.cn/Article/details/gt2nwmvqasc.html

[S05] C：字符串长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2utimyyzw.html

strlen(s)
来源：http://dali.hfpthk.cn/Article/details/gt2owxmzklc.html

[S06] C：字符串比较
来源：http://dali.xinyue.icu/Article/details/gt2qsfjpjll.html

strcmp(a, b) == 0
来源：http://dali.shangyingyoupin.top/Article/details/gt2dvjeygwj.html

[S07] C：数组遍历求和
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2caihfgfu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhoulong.xyz/Article/details/gt2vupxgufw.html

[S08] C：动态内存分配与释放
来源：http://dali.jinqigfzy.top/Article/details/gt2svbccjlt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cashguo.top/Article/details/gt2tanzfoao.html

[S09] C：结构体定义与初始化
来源：http://dali.smart0.xyz/Article/details/gt2zcaecooj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.wangshuangyany.cn/Article/details/gt2gcebziai.html

[S10] C：指针与解引用
来源：http://dali.hfpthk.cn/Article/details/gt2lbuzjqnv.html

int *p = &a;  *p = 5;
来源：http://dali.andypj.xyz/Article/details/gt2zldvfvmo.html

[S11] C：逐行读文件
来源：http://dali.cucudq.cn/Article/details/gt2ewpjzjhk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xylfe.cn/Article/details/gt2qxwatudx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.aizwys.cn/Article/details/gt2iekybwua.html

fclose(f);
来源：http://dali.sufxvd.cn/Article/details/gt2isisysct.html

[S12] C：写文件
来源：http://dali.iojbl.cn/Article/details/gt2uuygdnly.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.pengpengdd.cyou/Article/details/gt2fjunwhbf.html

[S13] C：宏定义
来源：http://dali.xylfe.cn/Article/details/gt2ovedrcvl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xinyue.icu/Article/details/gt2xicsuzfp.html

[S14] C：枚举
来源：http://dali.wangshuangyany.cn/Article/details/gt2etrwzbbp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.gogol.net.cn/Article/details/gt2anjshoik.html

[S15] C：类型转换
来源：http://dali.ehwqpu.com/Article/details/gt2yjlyczub.html

(double) a / b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ujoeahve.html

[S16] C：位操作置位
来源：http://dali.hfpthk.cn/Article/details/gt2buppsvco.html

x |= (1 << 3);
来源：http://dali.yueranfly.top/Article/details/gt2juaxnzxx.html

[S17] C：安全拼接字符串
来源：http://dali.tian-w.cn/Article/details/gt2mpwjhefr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yuanzhike.top/Article/details/gt2ufiixoya.html

[S18] C：命令行参数
来源：http://dali.gaohongyu789.top/Article/details/gt2zlrfnozc.html

int main(int argc, char **argv)
来源：http://dali.jianghu66.top/Article/details/gt2vqfguyqf.html

[S19] C：快速排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wnpntnau.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hnxiangtu.top/Article/details/gt2sbmdhmxh.html

[S20] C：二分查找
来源：http://dali.fengsongda.top/Article/details/gt2xnbbtbdh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.iojbl.cn/Article/details/gt2rdqlhndx.html

[S21] C：字符类别判断
来源：http://dali.wangshuangyany.cn/Article/details/gt2gpawbcsk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sweek.top/Article/details/gt2ljsmqhfk.html

[S22] C：字符串转数字
来源：http://dali.jlsjyb.cn/Article/details/gt2vzvgelnv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yj20258888.top/Article/details/gt2majnxynq.html

[S23] C：随机数
来源：http://dali.aibaodan.cn/Article/details/gt2tjqucegr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.feifeiyinyue.top/Article/details/gt2sbritvog.html

[S24] C：获取本地时间
来源：http://dali.pycfn.com/Article/details/gt2guxqkzko.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.aibaodan.cn/Article/details/gt2nziqtzbu.html

[S25] C：内存拷贝
来源：http://dali.xuanzx.com/Article/details/gt2urcphrrh.html

memcpy(dst, src, n);
来源：http://dali.bjfxy.top/Article/details/gt2trmznlov.html

[S26] C：内存清零
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2komogqgy.html

memset(a, 0, sizeof a);
来源：http://dali.ydzc1.top/Article/details/gt2rkxnruko.html

[S27] C：定义常量
来源：http://dali.tianlin.xyz/Article/details/gt2ulhdfwjz.html

const double PI = 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gt2hjmgnwoq.html

[S28] C：静态变量
来源：http://dali.gzhubu.top/Article/details/gt2evmrmlsx.html

static int counter = 0;
来源：http://dali.cdnleiting.top/Article/details/gt2ceteqday.html

[S29] C：变参函数
来源：http://dali.ydzc1.top/Article/details/gt2saexguxx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jiagoushi.top/Article/details/gt2toafgpwt.html

[S30] C：头文件保护
来源：http://dali.nwbrower.top/Article/details/gt2ilvqspoc.html

#ifndef X_H
来源：http://dali.zhengqikj.top/Article/details/gt2ummwpfya.html

#define X_H
来源：http://dali.ehwqpu.com/Article/details/gt2imotqryh.html

#endif
来源：http://dali.guannengcc.top/Article/details/gt2syqpcimz.html

[S31] C++：Hello World
来源：http://dali.tian-w.cn/Article/details/gt2kflnourv.html

#include <iostream>
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jgsrezhe.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.daria6918.cn/Article/details/gt2nwpgschc.html

[S32] C++：字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2ofbbxhqh.html

std::string s = "hi";  s += "!";
来源：http://dali.sufxvd.cn/Article/details/gt2phznhqjw.html

[S33] C++：vector 增删
来源：http://dali.jianghu66.top/Article/details/gt2dzevimhv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yuanzhike.top/Article/details/gt2uaqkyqar.html

[S34] C++：遍历 vector
来源：http://dali.jinqigufen.top/Article/details/gt2xzmcrsxn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.smart0.xyz/Article/details/gt2tihnefnw.html

[S35] C++：map
来源：http://dali.yonumen.top/Article/details/gt2sepfdcmm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.smart0.xyz/Article/details/gt2uycdygkl.html

[S36] C++：unordered_map
来源：http://dali.tianlin.xyz/Article/details/gt2symtzgyn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gt2gwxmymas.html

[S37] C++：set
来源：http://dali.vqdsnc.cn/Article/details/gt2jvyambqn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yuanzhike.top/Article/details/gt2agveuqwz.html

[S38] C++：排序
来源：http://dali.shangyingyoupin.top/Article/details/gt2jxwbkssi.html

std::sort(v.begin(), v.end());
来源：http://dali.sysykeji.top/Article/details/gt2utbrbrqt.html

[S39] C++：自定义比较器排序
来源：http://dali.gotoacloud.top/Article/details/gt2fviihftb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yuanzhike.top/Article/details/gt2syplekqt.html

[S40] C++：查找元素
来源：http://dali.yvedp.cn/Article/details/gt2ocniuqrh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.chenzaomai.com/Article/details/gt2gkbdwwgu.html

[S41] C++：类与构造函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2xqhaxkqh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.guowangkeji.top/Article/details/gt2uailgamf.html

[S42] C++：继承与虚函数
来源：http://dali.fzhhl.top/Article/details/gt2linmvgkm.html

class B : public Base { public: void f() override {} };
来源：http://dali.shzxlz.cn/Article/details/gt2tlpdmopw.html

[S43] C++：智能指针
来源：http://dali.haohaochexian.top/Article/details/gt2ltwswtlf.html

auto p = std::make_unique<int>(5);
来源：http://dali.shuidangran.top/Article/details/gt2guykarvt.html

[S44] C++：引用传参
来源：http://dali.cdnleiting.top/Article/details/gt2yetlzpkb.html

void inc(int &x) { ++x; }
来源：http://dali.daria6918.cn/Article/details/gt2ypvfdrqz.html

[S45] C++：lambda
来源：http://dali.meibo888.top/Article/details/gt2thoroxre.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ehwqpu.com/Article/details/gt2pbhbveue.html

[S46] C++：函数模板
来源：http://dali.vqdsnc.cn/Article/details/gt2zipbuicm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wuzfthmt.html

[S47] C++：结构化绑定遍历
来源：http://dali.xuanzx.com/Article/details/gt2kjezrutk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhongyouzk.top/Article/details/gt2pxwvghth.html

[S48] C++：逐行读文件
来源：http://dali.ivvv.top/Article/details/gt2prgbrkwm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cihqdlcd.html

while (std::getline(in, line)) { }
来源：http://dali.yangfankeji.com/Article/details/gt2yqtynhai.html

[S49] C++：写文件
来源：http://dali.smart0.xyz/Article/details/gt2wfpimzie.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.chenlongwang.top/Article/details/gt2spzbqnyb.html

[S50] C++：格式化数字
来源：http://dali.guowangkeji.top/Article/details/gt2lkvqpqql.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.daria6918.cn/Article/details/gt2hkhsmhih.html

[S51] C++：显式类型转换
来源：http://dali.yuxming.cn/Article/details/gt2zpbknvuz.html

static_cast<double>(a) / b
来源：http://dali.sxryk.cn/Article/details/gt2slrmkpdn.html

[S52] C++：const 与 noexcept
来源：http://dali.gogol.net.cn/Article/details/gt2kubjucgw.html

int size() const noexcept { return n_; }
来源：http://dali.xziqi.cn/Article/details/gt2tcbosxbk.html

[S53] C++：移动语义
来源：http://dali.bjfxy.top/Article/details/gt2opiphssz.html

std::vector<int> w = std::move(v);
来源：http://dali.nanxinkj.top/Article/details/gt2kgmtoqkz.html

[S54] C++：异常处理
来源：http://dali.jqgfzy.top/Article/details/gt2zcgavtys.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2idelzsjp.html

[S55] C++：结构化绑定
来源：http://dali.gotoacloud.top/Article/details/gt2ebqxmjeq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhoulong.xyz/Article/details/gt2fsehwkkt.html

[S56] C++：optional
来源：http://dali.gogol.net.cn/Article/details/gt2osksbecm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.aizwys.cn/Article/details/gt2olltngqx.html

[S57] C++：编译期常量
来源：http://dali.gaohongyu789.top/Article/details/gt2rjvcnatv.html

constexpr int N = 10;
来源：http://dali.zhengqikj.top/Article/details/gt2pmbwtibz.html

[S58] C++：命名空间
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ezflcabw.html

namespace ns { int f() { return 1; } }
来源：http://dali.c1oappe.top/Article/details/gt2gkcmcjol.html

[S59] C++：静态断言
来源：http://dali.chenjidiqi.icu/Article/details/gt2bgsbvbcb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shangyingyoupin.top/Article/details/gt2zcmthrvp.html

[S60] C++：遍历并删除元素
来源：http://dali.tianlin.xyz/Article/details/gt2gksqolzl.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.daria6918.cn/Article/details/gt2vrhaxlss.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2iwhbzihp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ydzc1.top/Article/details/gt2rpycdzra.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uwetcmjn.html

[T01] Kotlin：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gt2fmyzmcte.html

println("Hello")
来源：http://dali.ydzc1.top/Article/details/gt2zuancims.html

[T02] Kotlin：变量
来源：http://dali.gaohongyu789.top/Article/details/gt2pvunltlq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cheryme.top/Article/details/gt2rpciwyiq.html

[T03] Kotlin：字符串模板
来源：http://dali.shanyushiyangtech.top/Article/details/gt2guyugfqk.html

"值: $b"
来源：http://dali.cashguo.top/Article/details/gt2gjvqvhzs.html

[T04] Kotlin：空安全
来源：http://dali.cashguo.top/Article/details/gt2agdmhird.html

val n: String? = null;  n?.length
来源：http://dali.yueranfly.top/Article/details/gt2licknvdj.html

[T05] Kotlin：when 表达式
来源：http://dali.chenlongwang.top/Article/details/gt2pzattzds.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.tian-w.cn/Article/details/gt2phppyvub.html

[T06] Kotlin：集合映射
来源：http://dali.tian-w.cn/Article/details/gt2gocitkyf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.316326.xyz/Article/details/gt2mubsurao.html

[T07] Kotlin：集合过滤
来源：http://dali.smart0.xyz/Article/details/gt2zjsuogao.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cheryme.top/Article/details/gt2rhwmztrb.html

[T08] Kotlin：数据类
来源：http://dali.hnqzz.top/Article/details/gt2nnqwsvaq.html

data class User(val name: String, val age: Int)
来源：http://dali.zdqjudy.top/Article/details/gt2ywhpcyyg.html

[T09] Kotlin：扩展函数
来源：http://dali.jinqigufen.top/Article/details/gt2aezwqwit.html

fun String.exclaim() = this + "!"
来源：http://dali.316326.xyz/Article/details/gt2pigplndc.html

[T10] Kotlin：默认参数
来源：http://dali.jinqigufen.top/Article/details/gt2yopdojzq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dxjfseln.html

[T11] Kotlin：协程
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fzzxyyxq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.nanxuanxn.top/Article/details/gt2fmrqfdxx.html

[T12] Kotlin：解构声明
来源：http://dali.daria6918.cn/Article/details/gt2chmwhebc.html

val (a, b) = Pair(1, 2)
来源：http://dali.yj20258888.top/Article/details/gt2vielclqr.html

[T13] Kotlin：只读 Map
来源：http://dali.yanxiufei.cn/Article/details/gt2ytjltndc.html

val m = mapOf("a" to 1)
来源：http://dali.cqqwz.cn/Article/details/gt2zblolqrj.html

[T14] Kotlin：循环
来源：http://dali.jinghuilouyu.cn/Article/details/gt2htyuyxta.html

for (i in 1..10) println(i)
来源：http://dali.nwbrower.top/Article/details/gt2qtxapsiz.html

[T15] Kotlin：接口
来源：http://dali.hammf.cn/Article/details/gt2tvudsniw.html

interface Shape { fun area(): Double }
来源：http://dali.aibaodan.cn/Article/details/gt2bapwlhbc.html

[T16] Swift：Hello World
来源：http://dali.tanke756.top/Article/details/gt2gzqlgidp.html

print("Hello")
来源：http://dali.smart0.xyz/Article/details/gt2uizpoohi.html

[T17] Swift：变量与常量
来源：http://dali.jinqigfzy.top/Article/details/gt2fodzhnpb.html

var a = 1;  let b = 2
来源：http://dali.jinqigufen.top/Article/details/gt2klvmutlu.html

[T18] Swift：字符串插值
来源：http://dali.guannengcc.top/Article/details/gt2xjotprjk.html

"值: \(b)"
来源：http://dali.wangdashe.top/Article/details/gt2xmhxgrox.html

[T19] Swift：可选绑定
来源：http://dali.xziqi.cn/Article/details/gt2lfcsontg.html

if let n = opt { print(n) }
来源：http://dali.chenjidiqi.icu/Article/details/gt2gcerhxeq.html

[T20] Swift：数组操作
来源：http://dali.yuxming.cn/Article/details/gt2beyouwdp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.sufxvd.cn/Article/details/gt2xnqteqqb.html

[T21] Swift：遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xcqekctz.html

for x in a { print(x) }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lmqfvcgm.html

[T22] Swift：字典
来源：http://dali.chenzaomai.com/Article/details/gt2hstwngyp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xylfe.cn/Article/details/gt2rnlyuwdv.html

[T23] Swift：函数
来源：http://dali.9152youxi.cn/Article/details/gt2hkvhcjlu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.daxiang520.top/Article/details/gt2hwtppyik.html

[T24] Swift：闭包
来源：http://dali.nanxinkj.top/Article/details/gt2knekbzbn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.wangdashe.top/Article/details/gt2eymapikf.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2jqgvffih.html

struct P { var x: Int }
来源：http://dali.chenzaomai.com/Article/details/gt2ukttnqsl.html

[T26] Swift：类与重写
来源：http://dali.jinqigufen.top/Article/details/gt2ylprjsui.html

class A: Base { override func f() {} }
来源：http://dali.daxiang520.top/Article/details/gt2ojjsfgwk.html

[T27] Swift：错误处理
来源：http://dali.chenjidiqi.icu/Article/details/gt2slwgffsp.html

do { try f() } catch { print(error) }
来源：http://dali.zycfv.cn/Article/details/gt2pmdiwzsy.html

[T28] Swift：枚举
来源：http://dali.hfpthk.cn/Article/details/gt2epwqjyng.html

enum Color { case red, green }
来源：http://dali.shangyingyoupin.top/Article/details/gt2jjiojjgh.html

[T29] Swift：guard 提前返回
来源：http://dali.svipenyu.cn/Article/details/gt2kneatduu.html

guard let x = opt else { return }
来源：http://dali.yj202588.top/Article/details/gt2uoulilvy.html

[T30] Swift：协议
来源：http://dali.jinqigfzy.top/Article/details/gt2thmkbilc.html

protocol Shape { func area() -> Double }
来源：http://dali.daria6918.cn/Article/details/gt2bwtprjpm.html

[T31] Lua：Hello World
来源：http://dali.fengsongda.top/Article/details/gt2goouodnl.html

print("Hello")
来源：http://dali.xziqi.cn/Article/details/gt2kmnhvvrr.html

[T32] Lua：局部变量
来源：http://dali.pycfn.com/Article/details/gt2buigrgnk.html

local a = 1
来源：http://dali.ivvv.top/Article/details/gt2goehwpis.html

[T33] Lua：表（数组）
来源：http://dali.feifeiyinyue.top/Article/details/gt2awjjfzmw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jianghu66.top/Article/details/gt2akfeoepm.html

[T34] Lua：遍历表
来源：http://dali.quarkkingdee.top/Article/details/gt2rvzaxefi.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shangyingyoupin.top/Article/details/gt2wjynerpn.html

[T35] Lua：字典表
来源：http://dali.guowangkeji.top/Article/details/gt2dxjagfit.html

local d = { a = 1 };  d.b = 2
来源：http://dali.redwolf501.top/Article/details/gt2rjayuuqp.html

[T36] Lua：函数
来源：http://dali.jiagoushi.top/Article/details/gt2ylagryyd.html

function add(a, b) return a + b end
来源：http://dali.ivvv.top/Article/details/gt2szvrcabl.html

[T37] Lua：字符串拼接
来源：http://dali.chenzaomai.com/Article/details/gt2edxvadop.html

"a" .. "b"
来源：http://dali.quarkkingdee.top/Article/details/gt2ycbydgnq.html

[T38] Lua：条件
来源：http://dali.wangshuangyany.cn/Article/details/gt2gulisoyp.html

if x > 0 then print("正") end
来源：http://dali.vqdsnc.cn/Article/details/gt2fboylzbu.html

[T39] Lua：模式匹配
来源：http://dali.nwbrower.top/Article/details/gt2ablzqtji.html

string.find(s, "%d+")
来源：http://dali.iojbl.cn/Article/details/gt2ueffrikw.html

[T40] Lua：元表
来源：http://dali.aibaodan.cn/Article/details/gt2mycqjrgx.html

setmetatable({}, { __index = base })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2trcnzgjm.html

[T41] Perl：Hello World
来源：http://dali.yuxming.cn/Article/details/gt2wczpxgjt.html

print "Hello\n";
来源：http://dali.c1oappe.top/Article/details/gt2cqmulpcx.html

[T42] Perl：变量类型
来源：http://dali.zycfv.cn/Article/details/gt2htagmbik.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xylfe.cn/Article/details/gt2bichynyv.html

[T43] Perl：字符串插值
来源：http://dali.mhx1999.top/Article/details/gt2cmtkjckg.html

"值: $a"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nthrusjf.html

[T44] Perl：条件
来源：http://dali.c1oappe.top/Article/details/gt2myjzimcm.html

if ($a > 0) { print "正"; }
来源：http://dali.xziqi.cn/Article/details/gt2tcftidph.html

[T45] Perl：数组遍历
来源：http://dali.cqqwz.cn/Article/details/gt2jxnwlzmq.html

for my $x (@arr) { print $x; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2mlraddxc.html

[T46] Perl：哈希操作
来源：http://dali.aibaodan.cn/Article/details/gt2sumkndoa.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jiagoushi.top/Article/details/gt2eebvmdex.html

[T47] Perl：正则捕获
来源：http://dali.pycfn.com/Article/details/gt2xylrogjw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.9152youxi.cn/Article/details/gt2rqypohnc.html

[T48] Perl：正则替换
来源：http://dali.hywenlv.cn/Article/details/gt2esbocdzy.html

$s =~ s/old/new/g;
来源：http://dali.hfpthk.cn/Article/details/gt2eofutyxp.html

[T49] Perl：函数
来源：http://dali.yj202588.top/Article/details/gt2wtofluey.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gt2fmkqdyhk.html

[T50] Perl：逐行读文件
来源：http://dali.cashguo.top/Article/details/gt2hmzycypy.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.pycfn.com/Article/details/gt2zngetekq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntswenjd.html

[T51] Scala：Hello World
来源：http://dali.chenlongwang.top/Article/details/gt2vstuwrfy.html

println("Hello")
来源：http://dali.gzhubu.top/Article/details/gt2adyarmtm.html

[T52] Scala：变量
来源：http://dali.ehwqpu.com/Article/details/gt2rqgodrfb.html

val a = 1;  var b = 2
来源：http://dali.hongshengwenyu.top/Article/details/gt2zwvtqggg.html

[T53] Scala：字符串插值
来源：http://dali.jianghu66.top/Article/details/gt2ewhehxat.html

s"值: $b"
来源：http://dali.yonumen.top/Article/details/gt2qbsenzyn.html

[T54] Scala：集合映射
来源：http://dali.yj20258888.top/Article/details/gt2ijntudtm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ebgydtxl.html

[T55] Scala：集合过滤
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mveutpmb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hnqzz.top/Article/details/gt2dqrktlxn.html

[T56] Scala：样例类
来源：http://dali.nwbrower.top/Article/details/gt2rypexrha.html

case class User(name: String, age: Int)
来源：http://dali.zycfv.cn/Article/details/gt2aoisrtwv.html

[T57] Scala：模式匹配
来源：http://dali.zhongyouzk.top/Article/details/gt2wtdhbpnj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.guowangkeji.top/Article/details/gt2nqpvxnlp.html

[T58] Scala：函数定义
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sxdhxbto.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yongpay.top/Article/details/gt2zdooyuxd.html

[T59] Scala：循环
来源：http://dali.vqdsnc.cn/Article/details/gt2cjmwtxzc.html

for (i <- 1 to 10) println(i)
来源：http://dali.316326.xyz/Article/details/gt2yyozdeob.html

[T60] Scala：折叠
来源：http://dali.tianlin.xyz/Article/details/gt2orahnusz.html


<!-- 参考信息 -->