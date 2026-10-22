代发 wailian999

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.pengpengdd.cyou/Article/details/gt2cpzucqbq.html

[R54] 比较两个文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2tolhiyih.html

diff a.txt b.txt
来源：http://dali.yj202588.top/Article/details/gt2fpwrlldt.html

[R55] 压缩与解压
来源：http://dali.gzhubu.top/Article/details/gt2xrykxdjt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yanxiufei.cn/Article/details/gt2xgafgmay.html

[R56] 远程拷贝
来源：http://dali.pycfn.com/Article/details/gt2bzbdgssm.html

scp file user@host:/path/
来源：http://dali.c1oappe.top/Article/details/gt2ahduafwc.html

[R57] 远程执行命令
来源：http://dali.jianghu66.top/Article/details/gt2lagklwxz.html

ssh user@host 'uptime'
来源：http://dali.xuanzx.com/Article/details/gt2wevozcki.html

[R58] 下载文件
来源：http://dali.hywenlv.cn/Article/details/gt2rtdapbta.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.9152youxi.cn/Article/details/gt2qsoqsvld.html

[R59] 发 POST JSON
来源：http://dali.dashuyun.cn/Article/details/gt2cvviaipv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.c1oappe.top/Article/details/gt2feeijnjx.html

[R60] 只看 HTTP 状态码
来源：http://dali.shuidangran.top/Article/details/gt2lcrpwgyt.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.316326.xyz/Article/details/gt2jegywpkg.html

[R61] 磁盘占用
来源：http://dali.jiagoushi.top/Article/details/gt2kwhsrbmf.html

df -h;  du -sh *
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cvimjbpr.html

[R62] 找最占空间的文件
来源：http://dali.yuxming.cn/Article/details/gt2wjedszmq.html

du -ah . | sort -rh | head -10
来源：http://dali.chenzaomai.com/Article/details/gt2bnxblgfu.html

[R63] 内存与进程
来源：http://dali.zhongyouzk.top/Article/details/gt2nvifawvq.html

free -h;  ps aux | grep nginx
来源：http://dali.pengpengdd.cyou/Article/details/gt2zmtwuvwo.html

[R64] 结束进程
来源：http://dali.haohaochexian.top/Article/details/gt2zrwhdmfp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.guowangkeji.top/Article/details/gt2nbuopuan.html

[R65] 查看端口占用
来源：http://dali.c1oappe.top/Article/details/gt2hbevsdzs.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cashguo.top/Article/details/gt2qdbbxrcs.html

[R66] 定时任务
来源：http://dali.yueranfly.top/Article/details/gt2madxwmks.html

crontab -e;  crontab -l
来源：http://dali.aibaodan.cn/Article/details/gt2bsawnjvu.html

[R67] 生成随机十六进制串
来源：http://dali.fengsongda.top/Article/details/gt2xloxbyve.html

openssl rand -hex 16
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rmgizjuf.html

[R68] 计算文件校验值
来源：http://dali.yueranfly.top/Article/details/gt2txfzqfzl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sysykeji.top/Article/details/gt2ejyptgtn.html

[R69] 生成随机密码
来源：http://dali.hnqzz.top/Article/details/gt2chgxpdxt.html

head -c 16 /dev/urandom | base64
来源：http://dali.316326.xyz/Article/details/gt2tokjtsau.html

[R70] 时间戳与互转
来源：http://dali.ybcxt.top/Article/details/gt2tkmspdys.html

date +%s;  date -d @1700000000
来源：http://dali.bjfxy.top/Article/details/gt2xjuivcro.html

[R71] 日期格式化
来源：http://dali.quarkkingdee.top/Article/details/gt2ypwsevde.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.nwbrower.top/Article/details/gt2dynoqgsb.html

[R72] 等待端口就绪
来源：http://dali.jyoumei.cn/Article/details/gt2imwubegc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.quarkkingdee.top/Article/details/gt2kzgikchu.html

[R73] 分割大日志
来源：http://dali.zhengqikj.top/Article/details/gt2eqsnksms.html

split -l 1000 big.log part_
来源：http://dali.jqgufenzy.top/Article/details/gt2dvcdmwtw.html

[R74] 批量重命名
来源：http://dali.cheryme.top/Article/details/gt2rygrualv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hsutdkwm.html

[R75] 导出环境变量
来源：http://dali.yuanzhike.top/Article/details/gt2fzxjdkxz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xylfe.cn/Article/details/gt2osahrrcy.html

[R76] 使用临时文件
来源：http://dali.svipenyu.cn/Article/details/gt2wpjmjpkk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.316326.xyz/Article/details/gt2asplxxiv.html

[R77] 读取用户输入
来源：http://dali.daria6918.cn/Article/details/gt2yoftqril.html

read -rp "请输入: " ans
来源：http://dali.zhongyouzk.top/Article/details/gt2cmndnmbu.html

[R78] 交互式菜单
来源：http://dali.hammf.cn/Article/details/gt2rjsxfvem.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jlsjyb.cn/Article/details/gt2lneukwuc.html

[R79] 解析命令行选项
来源：http://dali.dianchejie.cn/Article/details/gt2msucjgmo.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kmttvvun.html

[R80] 查看脚本执行耗时
来源：http://dali.zhiwuduotai.top/Article/details/gt2aurhrvis.html

time ./run.sh
来源：http://dali.yongpay.top/Article/details/gt2bbvgvecv.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2xuidxltn.html

S. C / C++ 专题
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2celorjhg.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2bwhncvwp.html

[S01] C：Hello World
来源：http://dali.ehwqpu.com/Article/details/gt2xtaxgnzo.html

#include <stdio.h>
来源：http://dali.kuanghao11.cn/Article/details/gt2mixnzxsf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2evkgeopa.html

[S02] C：变量与格式化输出
来源：http://dali.c1oappe.top/Article/details/gt2fqxevkdw.html

int a = 10; printf("%d\n", a);
来源：http://dali.pycfn.com/Article/details/gt2bjgrnpjr.html

[S03] C：读入整数
来源：http://dali.cheryme.top/Article/details/gt2fobidcxr.html

int x; scanf("%d", &x);
来源：http://dali.hammf.cn/Article/details/gt2wdpddhge.html

[S04] C：字符串复制
来源：http://dali.jianghu66.top/Article/details/gt2ibbjibmo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.fzhhl.top/Article/details/gt2lrsqbykj.html

[S05] C：字符串长度
来源：http://dali.pycfn.com/Article/details/gt2pqaoqbcn.html

strlen(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ijxkevlz.html

[S06] C：字符串比较
来源：http://dali.ivvv.top/Article/details/gt2hexfgxol.html

strcmp(a, b) == 0
来源：http://dali.ydzc1.top/Article/details/gt2abfbhjos.html

[S07] C：数组遍历求和
来源：http://dali.yuxming.cn/Article/details/gt2wyglaatm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.andypj.xyz/Article/details/gt2qjdngjbo.html

[S08] C：动态内存分配与释放
来源：http://dali.hysaishi.cn/Article/details/gt2tpmhapvj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sweek.top/Article/details/gt2flnradet.html

[S09] C：结构体定义与初始化
来源：http://dali.yongpay.top/Article/details/gt2mzvnfkxg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xuetiantiany.cn/Article/details/gt2oaogcdax.html

[S10] C：指针与解引用
来源：http://dali.cdnleiting.top/Article/details/gt2ewbtjqyi.html

int *p = &a;  *p = 5;
来源：http://dali.tanke756.top/Article/details/gt2kgxetuwg.html

[S11] C：逐行读文件
来源：http://dali.birdmap.top/Article/details/gt2hzjedisn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yj20258888.top/Article/details/gt2intxkyft.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.tianlin.xyz/Article/details/gt2yohuypnb.html

fclose(f);
来源：http://dali.jqgfzy.top/Article/details/gt2pdsjvqlj.html

[S12] C：写文件
来源：http://dali.shzxlz.cn/Article/details/gt2dnglsiwk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.svipenyu.cn/Article/details/gt2rnwwypro.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bugvoydk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yj202588.top/Article/details/gt2hzqpytzr.html

[S14] C：枚举
来源：http://dali.guowangkeji.top/Article/details/gt2uwwkyorg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jyoumei.cn/Article/details/gt2kqjsgzji.html

[S15] C：类型转换
来源：http://dali.yj202588.top/Article/details/gt2dyjznlue.html

(double) a / b
来源：http://dali.hnxiangtu.top/Article/details/gt2wouksvhd.html

[S16] C：位操作置位
来源：http://dali.tian-w.cn/Article/details/gt2hotwqyll.html

x |= (1 << 3);
来源：http://dali.zhengqikj.top/Article/details/gt2vallqisj.html

[S17] C：安全拼接字符串
来源：http://dali.nwbrower.top/Article/details/gt2aqettyky.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.nwbrower.top/Article/details/gt2djotrnrz.html

[S18] C：命令行参数
来源：http://dali.zhengqikj.top/Article/details/gt2jcdsnrur.html

int main(int argc, char **argv)
来源：http://dali.fengsongda.top/Article/details/gt2diecbbup.html

[S19] C：快速排序
来源：http://dali.jianghu66.top/Article/details/gt2ztbvbegk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xuanzx.com/Article/details/gt2dpaptulh.html

[S20] C：二分查找
来源：http://dali.jyoumei.cn/Article/details/gt2hlgtiolh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xuanzx.com/Article/details/gt2ctihwwvi.html

[S21] C：字符类别判断
来源：http://dali.wangdashe.top/Article/details/gt2uonlnljy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xuetiantiany.cn/Article/details/gt2iwbuccqs.html

[S22] C：字符串转数字
来源：http://dali.zhongyouzk.top/Article/details/gt2lievlqsh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xziqi.cn/Article/details/gt2uefrhqto.html

[S23] C：随机数
来源：http://dali.tanke756.top/Article/details/gt2rsbqpmjt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.fengsongda.top/Article/details/gt2hlvyvhil.html

[S24] C：获取本地时间
来源：http://dali.jqgfzy.top/Article/details/gt2jiokqfse.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.chenlongwang.top/Article/details/gt2ahezbwmn.html

[S25] C：内存拷贝
来源：http://dali.zhixingplan.top/Article/details/gt2rxiwqvfp.html

memcpy(dst, src, n);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bujwdhht.html

[S26] C：内存清零
来源：http://dali.yongpay.top/Article/details/gt2iteofckf.html

memset(a, 0, sizeof a);
来源：http://dali.nanxinkj.top/Article/details/gt2zlttelao.html

[S27] C：定义常量
来源：http://dali.nanxuanxn.top/Article/details/gt2vysdwcvq.html

const double PI = 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gt2rsxmwfol.html

[S28] C：静态变量
来源：http://dali.cqqwz.cn/Article/details/gt2dfmqempg.html

static int counter = 0;
来源：http://dali.xinyue.icu/Article/details/gt2szobuooa.html

[S29] C：变参函数
来源：http://dali.yj202588.top/Article/details/gt2zymkliiy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ivvv.top/Article/details/gt2rbnjlwzp.html

[S30] C：头文件保护
来源：http://dali.cheryme.top/Article/details/gt2axrkrnmq.html

#ifndef X_H
来源：http://dali.tanke756.top/Article/details/gt2gdttygvv.html

#define X_H
来源：http://dali.gaohongyu789.top/Article/details/gt2jtfryaxm.html

#endif
来源：http://dali.gzhubu.top/Article/details/gt2hwnqtslv.html

[S31] C++：Hello World
来源：http://dali.aibaodan.cn/Article/details/gt2wfuycerv.html

#include <iostream>
来源：http://dali.sysykeji.top/Article/details/gt2tknmlzlk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.chenlongwang.top/Article/details/gt2ztwmeomb.html

[S32] C++：字符串
来源：http://dali.wangdashe.top/Article/details/gt2xmgvfhde.html

std::string s = "hi";  s += "!";
来源：http://dali.316326.xyz/Article/details/gt2rlypxdks.html

[S33] C++：vector 增删
来源：http://dali.jlsjyb.cn/Article/details/gt2owgmvueu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ppjwa.cn/Article/details/gt2cjqhfxnc.html

[S34] C++：遍历 vector
来源：http://dali.guowangkeji.top/Article/details/gt2bxqtrytc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2fcnmuzez.html

[S35] C++：map
来源：http://dali.wangshuangyany.cn/Article/details/gt2pzmgsitw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yonumen.top/Article/details/gt2blnehwaq.html

[S36] C++：unordered_map
来源：http://dali.yuanzhike.top/Article/details/gt2yrjlmvad.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guowangkeji.top/Article/details/gt2udrhtosd.html

[S37] C++：set
来源：http://dali.iojbl.cn/Article/details/gt2ivelpjpb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xuetiantiany.cn/Article/details/gt2xgccojtu.html

[S38] C++：排序
来源：http://dali.pycfn.com/Article/details/gt2qmvzqayq.html

std::sort(v.begin(), v.end());
来源：http://dali.yangfankeji.com/Article/details/gt2tkgwghjq.html

[S39] C++：自定义比较器排序
来源：http://dali.jiagoushi.top/Article/details/gt2ucwcoxuj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xuanzx.com/Article/details/gt2zjkoavxq.html

[S40] C++：查找元素
来源：http://dali.chenjidiqi.icu/Article/details/gt2esfuiuec.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbnhnoex.html

[S41] C++：类与构造函数
来源：http://dali.jianghu66.top/Article/details/gt2mjubcfes.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.meibo888.top/Article/details/gt2qdmdgvfp.html

[S42] C++：继承与虚函数
来源：http://dali.jqgfzy.top/Article/details/gt2qzmxxrcj.html

class B : public Base { public: void f() override {} };
来源：http://dali.cqqwz.cn/Article/details/gt2ekdhhyym.html

[S43] C++：智能指针
来源：http://dali.hnqzz.top/Article/details/gt2tdskvtib.html

auto p = std::make_unique<int>(5);
来源：http://dali.nwbrower.top/Article/details/gt2ifoenugp.html

[S44] C++：引用传参
来源：http://dali.hywenlv.cn/Article/details/gt2eqypaorq.html

void inc(int &x) { ++x; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2lgmglumi.html

[S45] C++：lambda
来源：http://dali.jinqigufen.top/Article/details/gt2ikohqqaq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.chenzaomai.com/Article/details/gt2hmifotku.html

[S46] C++：函数模板
来源：http://dali.wangshuangyany.cn/Article/details/gt2bvxemjhn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.nanxinkj.top/Article/details/gt2innvjudg.html

[S47] C++：结构化绑定遍历
来源：http://dali.guannengcc.top/Article/details/gt2aqdwsswu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.birdmap.top/Article/details/gt2twmfdoew.html

[S48] C++：逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gt2zpzqizwd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.bjfxy.top/Article/details/gt2uaakqevz.html

while (std::getline(in, line)) { }
来源：http://dali.shzxlz.cn/Article/details/gt2emfgtkaw.html

[S49] C++：写文件
来源：http://dali.iojbl.cn/Article/details/gt2fsvgqwst.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ppjwa.cn/Article/details/gt2wernxghw.html

[S50] C++：格式化数字
来源：http://dali.cdnleiting.top/Article/details/gt2zxxalggh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.chenzaomai.com/Article/details/gt2bcznhmgt.html

[S51] C++：显式类型转换
来源：http://dali.haohaochexian.top/Article/details/gt2nuuanpsu.html

static_cast<double>(a) / b
来源：http://dali.sufxvd.cn/Article/details/gt2fkvsretr.html

[S52] C++：const 与 noexcept
来源：http://dali.zdqjudy.top/Article/details/gt2tynobfix.html

int size() const noexcept { return n_; }
来源：http://dali.xinyue.icu/Article/details/gt2ldnqapde.html

[S53] C++：移动语义
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iqdezmcr.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2inukvvpy.html

[S54] C++：异常处理
来源：http://dali.yanxiufei.cn/Article/details/gt2iuwjnyaz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.nanxuanxn.top/Article/details/gt2ihpgcfqb.html

[S55] C++：结构化绑定
来源：http://dali.hammf.cn/Article/details/gt2prhpmxcv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shzxlz.cn/Article/details/gt2xrifceic.html

[S56] C++：optional
来源：http://dali.ehwqpu.com/Article/details/gt2cedezvhw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhoulong.xyz/Article/details/gt2mkkshyos.html

[S57] C++：编译期常量
来源：http://dali.hywenlv.cn/Article/details/gt2mmwozasz.html

constexpr int N = 10;
来源：http://dali.xinyue.icu/Article/details/gt2aehlnnis.html

[S58] C++：命名空间
来源：http://dali.iojbl.cn/Article/details/gt2zpxvrfwp.html

namespace ns { int f() { return 1; } }
来源：http://dali.havefunace.top/Article/details/gt2anwwtyeb.html

[S59] C++：静态断言
来源：http://dali.yonumen.top/Article/details/gt2youfgidt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yueranfly.top/Article/details/gt2roynvobs.html

[S60] C++：遍历并删除元素
来源：http://dali.zhongyouzk.top/Article/details/gt2icyjrztq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ybcxt.top/Article/details/gt2aefhckvp.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2hjyinixv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xinyue.icu/Article/details/gt2nahubcor.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2jkabrhln.html

[T01] Kotlin：Hello World
来源：http://dali.gogol.net.cn/Article/details/gt2rqflncls.html

println("Hello")
来源：http://dali.aibaodan.cn/Article/details/gt2obqqkkpt.html

[T02] Kotlin：变量
来源：http://dali.nwbrower.top/Article/details/gt2zhwmfuvg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.andypj.xyz/Article/details/gt2hivatjdz.html

[T03] Kotlin：字符串模板
来源：http://dali.ppjwa.cn/Article/details/gt2tzsohwju.html

"值: $b"
来源：http://dali.cucudq.cn/Article/details/gt2dpslsxga.html

[T04] Kotlin：空安全
来源：http://dali.smart0.xyz/Article/details/gt2djumdndv.html

val n: String? = null;  n?.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2egivrftl.html

[T05] Kotlin：when 表达式
来源：http://dali.mhx1999.top/Article/details/gt2mwcfnmvd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cheryme.top/Article/details/gt2ftviqjjs.html

[T06] Kotlin：集合映射
来源：http://dali.guowangkeji.top/Article/details/gt2ntmqvdwo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.birdmap.top/Article/details/gt2xojrvmxg.html

[T07] Kotlin：集合过滤
来源：http://dali.zdqjudy.top/Article/details/gt2iqjlqnoe.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ehwqpu.com/Article/details/gt2cmazoueg.html

[T08] Kotlin：数据类
来源：http://dali.tanke756.top/Article/details/gt2majmtfxi.html

data class User(val name: String, val age: Int)
来源：http://dali.havefunace.top/Article/details/gt2ectmlhlv.html

[T09] Kotlin：扩展函数
来源：http://dali.hysaishi.cn/Article/details/gt2facueint.html

fun String.exclaim() = this + "!"
来源：http://dali.chenzaomai.com/Article/details/gt2uieibezz.html

[T10] Kotlin：默认参数
来源：http://dali.zhoulong.xyz/Article/details/gt2soqazzia.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.pengpengdd.cyou/Article/details/gt2klvqqwoh.html

[T11] Kotlin：协程
来源：http://dali.zycfv.cn/Article/details/gt2rsgxsuek.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.quarkkingdee.top/Article/details/gt2kpbbkjdz.html

[T12] Kotlin：解构声明
来源：http://dali.jyoumei.cn/Article/details/gt2cdigohbz.html

val (a, b) = Pair(1, 2)
来源：http://dali.sysykeji.top/Article/details/gt2hvgmfkkh.html

[T13] Kotlin：只读 Map
来源：http://dali.bjfxy.top/Article/details/gt2vhcanlta.html

val m = mapOf("a" to 1)
来源：http://dali.0kj1m.cn/Article/details/gt2uktocamc.html

[T14] Kotlin：循环
来源：http://dali.xuetiantiany.cn/Article/details/gt2kwobttrq.html

for (i in 1..10) println(i)
来源：http://dali.fengsongda.top/Article/details/gt2ebiooxsn.html

[T15] Kotlin：接口
来源：http://dali.zhiwuduotai.top/Article/details/gt2cksetrwb.html

interface Shape { fun area(): Double }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eneepaox.html

[T16] Swift：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gt2vkduejcr.html

print("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wjkspfmt.html

[T17] Swift：变量与常量
来源：http://dali.nanxuanxn.top/Article/details/gt2atracejd.html

var a = 1;  let b = 2
来源：http://dali.hammf.cn/Article/details/gt2plilqujx.html

[T18] Swift：字符串插值
来源：http://dali.haohaochexian.top/Article/details/gt2gafeexbb.html

"值: \(b)"
来源：http://dali.dianchejie.cn/Article/details/gt2stdilknv.html

[T19] Swift：可选绑定
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sjojhmsu.html

if let n = opt { print(n) }
来源：http://dali.meibo888.top/Article/details/gt2ptexohax.html

[T20] Swift：数组操作
来源：http://dali.zdqjudy.top/Article/details/gt2prqxhjzi.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.9152youxi.cn/Article/details/gt2qafjzvdx.html

[T21] Swift：遍历
来源：http://dali.yangfankeji.com/Article/details/gt2sxdavnhm.html

for x in a { print(x) }
来源：http://dali.sysykeji.top/Article/details/gt2lphdrcvh.html

[T22] Swift：字典
来源：http://dali.gotoacloud.top/Article/details/gt2ekszztyv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yuxming.cn/Article/details/gt2ysxukwqn.html

[T23] Swift：函数
来源：http://dali.jlsjyb.cn/Article/details/gt2otufjmhb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.fzhhl.top/Article/details/gt2bwepxkhy.html

[T24] Swift：闭包
来源：http://dali.smart0.xyz/Article/details/gt2obstvsnf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yueranfly.top/Article/details/gt2bwpmrksi.html

[T25] Swift：结构体
来源：http://dali.daria6918.cn/Article/details/gt2ndnkcxpx.html

struct P { var x: Int }
来源：http://dali.yvedp.cn/Article/details/gt2swlgjlzf.html

[T26] Swift：类与重写
来源：http://dali.xinyue.icu/Article/details/gt2qfcijiex.html

class A: Base { override func f() {} }
来源：http://dali.aizwys.cn/Article/details/gt2jxwtiadw.html

[T27] Swift：错误处理
来源：http://dali.cashguo.top/Article/details/gt2yhekudmc.html

do { try f() } catch { print(error) }
来源：http://dali.0kj1m.cn/Article/details/gt2nokffgyp.html

[T28] Swift：枚举
来源：http://dali.nanxinkj.top/Article/details/gt2fqhgbnas.html

enum Color { case red, green }
来源：http://dali.hysaishi.cn/Article/details/gt2ewzuljrk.html

[T29] Swift：guard 提前返回
来源：http://dali.gzhubu.top/Article/details/gt2jqzvktpc.html

guard let x = opt else { return }
来源：http://dali.quarkkingdee.top/Article/details/gt2vclnkyyy.html

[T30] Swift：协议
来源：http://dali.0kj1m.cn/Article/details/gt2cpkqtjol.html

protocol Shape { func area() -> Double }
来源：http://dali.hysaishi.cn/Article/details/gt2xqgmmnnl.html

[T31] Lua：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gt2wjmqnnpu.html

print("Hello")
来源：http://dali.zhongyouzk.top/Article/details/gt2zssikrij.html

[T32] Lua：局部变量
来源：http://dali.hammf.cn/Article/details/gt2mkgetkhd.html

local a = 1
来源：http://dali.sysykeji.top/Article/details/gt2mdryvnuq.html

[T33] Lua：表（数组）
来源：http://dali.9152youxi.cn/Article/details/gt2vsuadlca.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.pycfn.com/Article/details/gt2ltcydfag.html

[T34] Lua：遍历表
来源：http://dali.xinyue.icu/Article/details/gt2zibylgny.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhiwuduotai.top/Article/details/gt2vofxwqek.html

[T35] Lua：字典表
来源：http://dali.316326.xyz/Article/details/gt2qzylsgzv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fliywjxv.html

[T36] Lua：函数
来源：http://dali.smart0.xyz/Article/details/gt2zuvdqjpr.html

function add(a, b) return a + b end
来源：http://dali.wangdashe.top/Article/details/gt2xgfrpgus.html

[T37] Lua：字符串拼接
来源：http://dali.tianlin.xyz/Article/details/gt2xznzgfwk.html

"a" .. "b"
来源：http://dali.guowangkeji.top/Article/details/gt2aqwillfj.html

[T38] Lua：条件
来源：http://dali.mhx1999.top/Article/details/gt2hkzzxexn.html

if x > 0 then print("正") end
来源：http://dali.jinqigufen.top/Article/details/gt2uyrzkiaz.html

[T39] Lua：模式匹配
来源：http://dali.yuanzhike.top/Article/details/gt2iaksclom.html

string.find(s, "%d+")
来源：http://dali.gaohongyu789.top/Article/details/gt2jupprcox.html

[T40] Lua：元表
来源：http://dali.zycfv.cn/Article/details/gt2pbydibib.html

setmetatable({}, { __index = base })
来源：http://dali.fengsongda.top/Article/details/gt2mugplnvr.html

[T41] Perl：Hello World
来源：http://dali.aizwys.cn/Article/details/gt2rrszdhly.html

print "Hello\n";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tygnpvom.html

[T42] Perl：变量类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2vxunyhjx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.andypj.xyz/Article/details/gt2igbdsxmt.html

[T43] Perl：字符串插值
来源：http://dali.jqgufenzy.top/Article/details/gt2dnohyfwc.html

"值: $a"
来源：http://dali.chenzaomai.com/Article/details/gt2gdkzsawf.html

[T44] Perl：条件
来源：http://dali.nanxuanxn.top/Article/details/gt2sfsjfuek.html

if ($a > 0) { print "正"; }
来源：http://dali.cdnleiting.top/Article/details/gt2ikkaolrs.html

[T45] Perl：数组遍历
来源：http://dali.nanxinkj.top/Article/details/gt2nrqhzamb.html

for my $x (@arr) { print $x; }
来源：http://dali.aibaodan.cn/Article/details/gt2janpkpyr.html

[T46] Perl：哈希操作
来源：http://dali.yj20258.top/Article/details/gt2ffqiqhsq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.iojbl.cn/Article/details/gt2ebelsbuc.html

[T47] Perl：正则捕获
来源：http://dali.chenzaomai.com/Article/details/gt2sgqzhcmd.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.mhx1999.top/Article/details/gt2naajkavd.html

[T48] Perl：正则替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qnoxrrwh.html

$s =~ s/old/new/g;
来源：http://dali.guowangkeji.top/Article/details/gt2swvqwwgx.html

[T49] Perl：函数
来源：http://dali.yongpay.top/Article/details/gt2zgyybbbf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.smart0.xyz/Article/details/gt2otaoxrbp.html

[T50] Perl：逐行读文件
来源：http://dali.snrcjt.cn/Article/details/gt2pevvhuug.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.c1oappe.top/Article/details/gt2juaeduim.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2yopkmuas.html

[T51] Scala：Hello World
来源：http://dali.bjfxy.top/Article/details/gt2ufeqmhdc.html

println("Hello")
来源：http://dali.zhongyouzk.top/Article/details/gt2nfgbxcnj.html

[T52] Scala：变量
来源：http://dali.guannengcc.top/Article/details/gt2hfvgbspm.html

val a = 1;  var b = 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mntaejno.html

[T53] Scala：字符串插值
来源：http://dali.xylfe.cn/Article/details/gt2sultmgzh.html

s"值: $b"
来源：http://dali.redwolf501.top/Article/details/gt2jatoando.html

[T54] Scala：集合映射
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kjmpmhyq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.redwolf501.top/Article/details/gt2nashnqsj.html

[T55] Scala：集合过滤
来源：http://dali.chenzaomai.com/Article/details/gt2wjhepxfp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhoulong.xyz/Article/details/gt2usfyqfyx.html

[T56] Scala：样例类
来源：http://dali.tian-w.cn/Article/details/gt2ajejbmcg.html


<!-- 参考信息 -->