代发 wailian999

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cdnleiting.top/Article/details/gt2ymaaapua.html

[R54] 比较两个文件
来源：http://dali.andypj.xyz/Article/details/gt2krnmtgju.html

diff a.txt b.txt
来源：http://dali.ydzc1.top/Article/details/gt2pdzltvme.html

[R55] 压缩与解压
来源：http://dali.yj20258888.top/Article/details/gt2tecmcxlv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.dianchejie.cn/Article/details/gt2jyydvpza.html

[R56] 远程拷贝
来源：http://dali.feifeiyinyue.top/Article/details/gt2asdbszdg.html

scp file user@host:/path/
来源：http://dali.havefunace.top/Article/details/gt2sntoofnw.html

[R57] 远程执行命令
来源：http://dali.pycfn.com/Article/details/gt2jfskznag.html

ssh user@host 'uptime'
来源：http://dali.svipenyu.cn/Article/details/gt2nvnnznyt.html

[R58] 下载文件
来源：http://dali.ppjwa.cn/Article/details/gt2fqmxsgax.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nfanknxk.html

[R59] 发 POST JSON
来源：http://dali.sweek.top/Article/details/gt2owlqmnbh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ymmslbai.html

[R60] 只看 HTTP 状态码
来源：http://dali.dashuyun.cn/Article/details/gt2rnxtbcps.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shuidangran.top/Article/details/gt2cakqszye.html

[R61] 磁盘占用
来源：http://dali.nanxinkj.top/Article/details/gt2wvcizyog.html

df -h;  du -sh *
来源：http://dali.zhoulong.xyz/Article/details/gt2dyitnmwu.html

[R62] 找最占空间的文件
来源：http://dali.zhongyouzk.top/Article/details/gt2byoshldc.html

du -ah . | sort -rh | head -10
来源：http://dali.yanxiufei.cn/Article/details/gt2bsfvhaxq.html

[R63] 内存与进程
来源：http://dali.gogol.net.cn/Article/details/gt2pfmxjyde.html

free -h;  ps aux | grep nginx
来源：http://dali.yj20258.top/Article/details/gt2xevfqvmv.html

[R64] 结束进程
来源：http://dali.yangfankeji.com/Article/details/gt2rtqstqck.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jyoumei.cn/Article/details/gt2kuhmivhh.html

[R65] 查看端口占用
来源：http://dali.zhengqikj.top/Article/details/gt2xkygfnnw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sufxvd.cn/Article/details/gt2oyqyhyyg.html

[R66] 定时任务
来源：http://dali.ppjwa.cn/Article/details/gt2bbmgxxtl.html

crontab -e;  crontab -l
来源：http://dali.dianchejie.cn/Article/details/gt2omrxrpjk.html

[R67] 生成随机十六进制串
来源：http://dali.zdqjudy.top/Article/details/gt2zajqiymh.html

openssl rand -hex 16
来源：http://dali.mhx1999.top/Article/details/gt2zavxyghv.html

[R68] 计算文件校验值
来源：http://dali.dianchejie.cn/Article/details/gt2cwetahee.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gaohongyu789.top/Article/details/gt2pcfgqoxf.html

[R69] 生成随机密码
来源：http://dali.tianlin.xyz/Article/details/gt2xtbtbxtf.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2esnnhnyn.html

[R70] 时间戳与互转
来源：http://dali.yonumen.top/Article/details/gt2ukkzvfmg.html

date +%s;  date -d @1700000000
来源：http://dali.yonumen.top/Article/details/gt2vwkcfskq.html

[R71] 日期格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uriycqsc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj202588.top/Article/details/gt2odktaiya.html

[R72] 等待端口就绪
来源：http://dali.guannengcc.top/Article/details/gt2rgtovbzm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shangyingyoupin.top/Article/details/gt2hfjalgwy.html

[R73] 分割大日志
来源：http://dali.sufxvd.cn/Article/details/gt2oulwtnif.html

split -l 1000 big.log part_
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ihbvllnr.html

[R74] 批量重命名
来源：http://dali.xuetiantiany.cn/Article/details/gt2nxiobazi.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xylfe.cn/Article/details/gt2chbixuoc.html

[R75] 导出环境变量
来源：http://dali.hywenlv.cn/Article/details/gt2njnqrrfa.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.chenjidiqi.icu/Article/details/gt2xxbhnjmi.html

[R76] 使用临时文件
来源：http://dali.daxiang520.top/Article/details/gt2cqosrfyd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.fengsongda.top/Article/details/gt2xuldtwjj.html

[R77] 读取用户输入
来源：http://dali.zhixingplan.top/Article/details/gt2rlvqbpga.html

read -rp "请输入: " ans
来源：http://dali.jianghu66.top/Article/details/gt2zykpcewi.html

[R78] 交互式菜单
来源：http://dali.sxryk.cn/Article/details/gt2dgnlekqf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.vqdsnc.cn/Article/details/gt2yzrnlyhv.html

[R79] 解析命令行选项
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zigumumm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sufxvd.cn/Article/details/gt2tjthlcfm.html

[R80] 查看脚本执行耗时
来源：http://dali.316326.xyz/Article/details/gt2jovrvxii.html

time ./run.sh
来源：http://dali.ehwqpu.com/Article/details/gt2flunppqt.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2iypqsmvi.html

S. C / C++ 专题
来源：http://dali.nwbrower.top/Article/details/gt2pbarouti.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dlbghcdz.html

[S01] C：Hello World
来源：http://dali.tian-w.cn/Article/details/gt2jxjemkfr.html

#include <stdio.h>
来源：http://dali.svipenyu.cn/Article/details/gt2ybtdiikv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.redwolf501.top/Article/details/gt2rfbdjuvy.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2cxnzgwwj.html

int a = 10; printf("%d\n", a);
来源：http://dali.aibaodan.cn/Article/details/gt2zsyoxsnu.html

[S03] C：读入整数
来源：http://dali.nanxinkj.top/Article/details/gt2ruybldrb.html

int x; scanf("%d", &x);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ykzpqoyk.html

[S04] C：字符串复制
来源：http://dali.haohaochexian.top/Article/details/gt2crsxmcog.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.meibo888.top/Article/details/gt2wfyfemrt.html

[S05] C：字符串长度
来源：http://dali.tianlin.xyz/Article/details/gt2quiqyuph.html

strlen(s)
来源：http://dali.gogol.net.cn/Article/details/gt2awrjtfcr.html

[S06] C：字符串比较
来源：http://dali.yonumen.top/Article/details/gt2mnejyoqw.html

strcmp(a, b) == 0
来源：http://dali.redwolf501.top/Article/details/gt2oetcnhqz.html

[S07] C：数组遍历求和
来源：http://dali.mhx1999.top/Article/details/gt2mtjwpbhh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xylfe.cn/Article/details/gt2afsufgzl.html

[S08] C：动态内存分配与释放
来源：http://dali.yueranfly.top/Article/details/gt2nqcxhibl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pfzunydi.html

[S09] C：结构体定义与初始化
来源：http://dali.ydzc1.top/Article/details/gt2jxxrzkqk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hfgpxyfm.html

[S10] C：指针与解引用
来源：http://dali.shangyingyoupin.top/Article/details/gt2cmbzbnbm.html

int *p = &a;  *p = 5;
来源：http://dali.316326.xyz/Article/details/gt2rwmuqfrl.html

[S11] C：逐行读文件
来源：http://dali.cheryme.top/Article/details/gt2uwacbdxy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xinyue.icu/Article/details/gt2dozznvyc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hammf.cn/Article/details/gt2sdxagiqw.html

fclose(f);
来源：http://dali.zhongyouzk.top/Article/details/gt2lekowyba.html

[S12] C：写文件
来源：http://dali.9152youxi.cn/Article/details/gt2unncvott.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hnqzz.top/Article/details/gt2szfqhaiy.html

[S13] C：宏定义
来源：http://dali.ehwqpu.com/Article/details/gt2sickbway.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.daxiang520.top/Article/details/gt2wsegpmhx.html

[S14] C：枚举
来源：http://dali.xuetiantiany.cn/Article/details/gt2qpuvbauo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.aizwys.cn/Article/details/gt2sywpkqht.html

[S15] C：类型转换
来源：http://dali.jinqigfzy.top/Article/details/gt2oiqorbxo.html

(double) a / b
来源：http://dali.cdnleiting.top/Article/details/gt2rnjosvpq.html

[S16] C：位操作置位
来源：http://dali.kuanghao11.cn/Article/details/gt2kurfxdto.html

x |= (1 << 3);
来源：http://dali.haohaochexian.top/Article/details/gt2bwtcpbps.html

[S17] C：安全拼接字符串
来源：http://dali.xinyue.icu/Article/details/gt2lwqpqszf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hnqzz.top/Article/details/gt2puusanfc.html

[S18] C：命令行参数
来源：http://dali.hywenlv.cn/Article/details/gt2vnnuhhqp.html

int main(int argc, char **argv)
来源：http://dali.dashuyun.cn/Article/details/gt2cdgbwmcm.html

[S19] C：快速排序
来源：http://dali.shuidangran.top/Article/details/gt2ezxdbzba.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yanxiufei.cn/Article/details/gt2wgzmowqz.html

[S20] C：二分查找
来源：http://dali.yj20258.top/Article/details/gt2uyvtrlsc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinqigufen.top/Article/details/gt2sqgelrdr.html

[S21] C：字符类别判断
来源：http://dali.316326.xyz/Article/details/gt2wtqsmjod.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yvedp.cn/Article/details/gt2swphogzg.html

[S22] C：字符串转数字
来源：http://dali.feifeiyinyue.top/Article/details/gt2zieudqbr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xuetiantiany.cn/Article/details/gt2gbkblfgv.html

[S23] C：随机数
来源：http://dali.dianchejie.cn/Article/details/gt2zecyzhuv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jianghu66.top/Article/details/gt2ihuijubv.html

[S24] C：获取本地时间
来源：http://dali.gaohongyu789.top/Article/details/gt2oqergntq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.svipenyu.cn/Article/details/gt2cbzfrmww.html

[S25] C：内存拷贝
来源：http://dali.0kj1m.cn/Article/details/gt2ccmwktyr.html

memcpy(dst, src, n);
来源：http://dali.quarkkingdee.top/Article/details/gt2pfjxwwjr.html

[S26] C：内存清零
来源：http://dali.shuidangran.top/Article/details/gt2oogxhtwl.html

memset(a, 0, sizeof a);
来源：http://dali.yangfankeji.com/Article/details/gt2mjchmmsf.html

[S27] C：定义常量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ditqxdzv.html

const double PI = 3.14159;
来源：http://dali.316326.xyz/Article/details/gt2wclcaycu.html

[S28] C：静态变量
来源：http://dali.hongshengwenyu.top/Article/details/gt2xplniqvb.html

static int counter = 0;
来源：http://dali.yuxming.cn/Article/details/gt2syajxbxi.html

[S29] C：变参函数
来源：http://dali.fzhhl.top/Article/details/gt2fvvusmjw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cucudq.cn/Article/details/gt2ijcbqffh.html

[S30] C：头文件保护
来源：http://dali.jinqigfzy.top/Article/details/gt2ooerwnbv.html

#ifndef X_H
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pdroompu.html

#define X_H
来源：http://dali.zhengqikj.top/Article/details/gt2qmzidopg.html

#endif
来源：http://dali.snrcjt.cn/Article/details/gt2csubtqvi.html

[S31] C++：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gt2fsilazcz.html

#include <iostream>
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gmxdjltq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jinqigufen.top/Article/details/gt2evzulcla.html

[S32] C++：字符串
来源：http://dali.gotoacloud.top/Article/details/gt2uzhmikuo.html

std::string s = "hi";  s += "!";
来源：http://dali.dashuyun.cn/Article/details/gt2icxvymtl.html

[S33] C++：vector 增删
来源：http://dali.andypj.xyz/Article/details/gt2sspkmbnq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2eagxxyss.html

[S34] C++：遍历 vector
来源：http://dali.sxryk.cn/Article/details/gt2luiasuij.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.haohaochexian.top/Article/details/gt2nrnrslbw.html

[S35] C++：map
来源：http://dali.zhiwuduotai.top/Article/details/gt2isznbdnp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gzhubu.top/Article/details/gt2jciyqhhq.html

[S36] C++：unordered_map
来源：http://dali.hongshengwenyu.top/Article/details/gt2kfaqpngs.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.316326.xyz/Article/details/gt2ltynxnjj.html

[S37] C++：set
来源：http://dali.jlsjyb.cn/Article/details/gt2kppqzsce.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yanxiufei.cn/Article/details/gt2lnkcoflb.html

[S38] C++：排序
来源：http://dali.shzxlz.cn/Article/details/gt2otpzgype.html

std::sort(v.begin(), v.end());
来源：http://dali.ydzc1.top/Article/details/gt2yfcbnqxf.html

[S39] C++：自定义比较器排序
来源：http://dali.ehwqpu.com/Article/details/gt2gocsmizs.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.quarkkingdee.top/Article/details/gt2siyjskwt.html

[S40] C++：查找元素
来源：http://dali.nwbrower.top/Article/details/gt2cevybpda.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gdvcjyec.html

[S41] C++：类与构造函数
来源：http://dali.dashuyun.cn/Article/details/gt2meadpbqa.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.dianchejie.cn/Article/details/gt2toeaqvmr.html

[S42] C++：继承与虚函数
来源：http://dali.yuxming.cn/Article/details/gt2gvlqfrpx.html

class B : public Base { public: void f() override {} };
来源：http://dali.dianchejie.cn/Article/details/gt2xomkqgxg.html

[S43] C++：智能指针
来源：http://dali.zhoulong.xyz/Article/details/gt2xcvijubm.html

auto p = std::make_unique<int>(5);
来源：http://dali.chenzaomai.com/Article/details/gt2mthnyjwr.html

[S44] C++：引用传参
来源：http://dali.zhiwuduotai.top/Article/details/gt2dudstqph.html

void inc(int &x) { ++x; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2dihprjtm.html

[S45] C++：lambda
来源：http://dali.tianlin.xyz/Article/details/gt2hnnpgqzi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cqqwz.cn/Article/details/gt2ppwrnzsr.html

[S46] C++：函数模板
来源：http://dali.hnxiangtu.top/Article/details/gt2cmhaqizp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2whesafso.html

[S47] C++：结构化绑定遍历
来源：http://dali.yonumen.top/Article/details/gt2naxagwdo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2snzfgtfe.html

[S48] C++：逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gt2keybfsok.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhengqikj.top/Article/details/gt2oorsrhib.html

while (std::getline(in, line)) { }
来源：http://dali.0kj1m.cn/Article/details/gt2olzdykbp.html

[S49] C++：写文件
来源：http://dali.zhoulong.xyz/Article/details/gt2kgpdermv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.nwbrower.top/Article/details/gt2spesfyqr.html

[S50] C++：格式化数字
来源：http://dali.ehwqpu.com/Article/details/gt2dkywsqjw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gt2hcagzahy.html

[S51] C++：显式类型转换
来源：http://dali.chenzaomai.com/Article/details/gt2wpdjinjn.html

static_cast<double>(a) / b
来源：http://dali.yj20258888.top/Article/details/gt2ozolvido.html

[S52] C++：const 与 noexcept
来源：http://dali.chenjidiqi.icu/Article/details/gt2cqzapjry.html

int size() const noexcept { return n_; }
来源：http://dali.zdqjudy.top/Article/details/gt2bzusvudx.html

[S53] C++：移动语义
来源：http://dali.redwolf501.top/Article/details/gt2mxxvbgtf.html

std::vector<int> w = std::move(v);
来源：http://dali.pengpengdd.cyou/Article/details/gt2hwwtqjkw.html

[S54] C++：异常处理
来源：http://dali.snrcjt.cn/Article/details/gt2mvqiikaa.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jiagoushi.top/Article/details/gt2bmevwxxm.html

[S55] C++：结构化绑定
来源：http://dali.yj20258888.top/Article/details/gt2rjaegzrs.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sxryk.cn/Article/details/gt2thsqviza.html

[S56] C++：optional
来源：http://dali.zhengqikj.top/Article/details/gt2dfmlyrtl.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yongpay.top/Article/details/gt2vvueekxb.html

[S57] C++：编译期常量
来源：http://dali.fzhhl.top/Article/details/gt2wmnclrhh.html

constexpr int N = 10;
来源：http://dali.shangyingyoupin.top/Article/details/gt2httrrypw.html

[S58] C++：命名空间
来源：http://dali.svipenyu.cn/Article/details/gt2jrndsaon.html

namespace ns { int f() { return 1; } }
来源：http://dali.sufxvd.cn/Article/details/gt2akbiouok.html

[S59] C++：静态断言
来源：http://dali.pengpengdd.cyou/Article/details/gt2xzgpmzyx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.vqdsnc.cn/Article/details/gt2faazrucz.html

[S60] C++：遍历并删除元素
来源：http://dali.xziqi.cn/Article/details/gt2twpveqmr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.aibaodan.cn/Article/details/gt2dipwhsvd.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2dvxbpvgv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.guowangkeji.top/Article/details/gt2thrjayro.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2kitmvahj.html

[T01] Kotlin：Hello World
来源：http://dali.snrcjt.cn/Article/details/gt2khoutipf.html

println("Hello")
来源：http://dali.yuanzhike.top/Article/details/gt2zlkpnjjx.html

[T02] Kotlin：变量
来源：http://dali.cucudq.cn/Article/details/gt2ejzljydt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.dashuyun.cn/Article/details/gt2ygsviwrb.html

[T03] Kotlin：字符串模板
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qdbivdkw.html

"值: $b"
来源：http://dali.yj20258888.top/Article/details/gt2uuiqmlvg.html

[T04] Kotlin：空安全
来源：http://dali.hnqzz.top/Article/details/gt2tmqesgty.html

val n: String? = null;  n?.length
来源：http://dali.hnqzz.top/Article/details/gt2ufhzpisg.html

[T05] Kotlin：when 表达式
来源：http://dali.haohaochexian.top/Article/details/gt2cytuwexv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yanxiufei.cn/Article/details/gt2cyxedkji.html

[T06] Kotlin：集合映射
来源：http://dali.hnxiangtu.top/Article/details/gt2yfjjsgkx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cashguo.top/Article/details/gt2bbzdzjic.html

[T07] Kotlin：集合过滤
来源：http://dali.aizwys.cn/Article/details/gt2fqzxlzra.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhongyouzk.top/Article/details/gt2abvidikb.html

[T08] Kotlin：数据类
来源：http://dali.meibo888.top/Article/details/gt2wqujipgu.html

data class User(val name: String, val age: Int)
来源：http://dali.chenzaomai.com/Article/details/gt2tvroimar.html

[T09] Kotlin：扩展函数
来源：http://dali.c1oappe.top/Article/details/gt2yahcpjww.html

fun String.exclaim() = this + "!"
来源：http://dali.wangdashe.top/Article/details/gt2xjzfpezm.html

[T10] Kotlin：默认参数
来源：http://dali.wangshuangyany.cn/Article/details/gt2wwyimreh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cucudq.cn/Article/details/gt2lyygiyky.html

[T11] Kotlin：协程
来源：http://dali.ivvv.top/Article/details/gt2xbyiescg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xziqi.cn/Article/details/gt2ikherlbg.html

[T12] Kotlin：解构声明
来源：http://dali.sweek.top/Article/details/gt2ukxuubmm.html

val (a, b) = Pair(1, 2)
来源：http://dali.0kj1m.cn/Article/details/gt2pmpykwxd.html

[T13] Kotlin：只读 Map
来源：http://dali.zhongyouzk.top/Article/details/gt2grltctkh.html

val m = mapOf("a" to 1)
来源：http://dali.yj202588.top/Article/details/gt2jseomrkb.html

[T14] Kotlin：循环
来源：http://dali.cqqwz.cn/Article/details/gt2gziginlu.html

for (i in 1..10) println(i)
来源：http://dali.hnxiangtu.top/Article/details/gt2axiorytc.html

[T15] Kotlin：接口
来源：http://dali.andypj.xyz/Article/details/gt2sksduqew.html

interface Shape { fun area(): Double }
来源：http://dali.jlsjyb.cn/Article/details/gt2takmmyea.html

[T16] Swift：Hello World
来源：http://dali.cucudq.cn/Article/details/gt2rbebloac.html

print("Hello")
来源：http://dali.jiagoushi.top/Article/details/gt2unucgalh.html

[T17] Swift：变量与常量
来源：http://dali.hywenlv.cn/Article/details/gt2solucyuo.html

var a = 1;  let b = 2
来源：http://dali.jinqigufen.top/Article/details/gt2pcfqfzqg.html

[T18] Swift：字符串插值
来源：http://dali.jqgufenzy.top/Article/details/gt2sophjexs.html

"值: \(b)"
来源：http://dali.daxiang520.top/Article/details/gt2ffgrypnk.html

[T19] Swift：可选绑定
来源：http://dali.yvedp.cn/Article/details/gt2tegstbzj.html

if let n = opt { print(n) }
来源：http://dali.hfpthk.cn/Article/details/gt2vqldamrl.html

[T20] Swift：数组操作
来源：http://dali.gzhubu.top/Article/details/gt2fpvqdqxn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.tian-w.cn/Article/details/gt2yaoritaa.html

[T21] Swift：遍历
来源：http://dali.zycfv.cn/Article/details/gt2ydifwqzm.html

for x in a { print(x) }
来源：http://dali.nanxuanxn.top/Article/details/gt2vjukhbis.html

[T22] Swift：字典
来源：http://dali.nanxuanxn.top/Article/details/gt2wwefxgdu.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.aibaodan.cn/Article/details/gt2ycgeygic.html

[T23] Swift：函数
来源：http://dali.yvedp.cn/Article/details/gt2bdpluruy.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlgkspw.html

[T24] Swift：闭包
来源：http://dali.jyoumei.cn/Article/details/gt2debzmhvz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shuidangran.top/Article/details/gt2kfitrras.html

[T25] Swift：结构体
来源：http://dali.jianghu66.top/Article/details/gt2sqvokqkk.html

struct P { var x: Int }
来源：http://dali.meibo888.top/Article/details/gt2lekrnuyq.html

[T26] Swift：类与重写
来源：http://dali.shuidangran.top/Article/details/gt2wygkchxt.html

class A: Base { override func f() {} }
来源：http://dali.tian-w.cn/Article/details/gt2mapnjaal.html

[T27] Swift：错误处理
来源：http://dali.pengpengdd.cyou/Article/details/gt2uktvcgjp.html

do { try f() } catch { print(error) }
来源：http://dali.jiagoushi.top/Article/details/gt2gdcjzyyf.html

[T28] Swift：枚举
来源：http://dali.redwolf501.top/Article/details/gt2zgqxnsih.html

enum Color { case red, green }
来源：http://dali.zhixingplan.top/Article/details/gt2zwaacjko.html

[T29] Swift：guard 提前返回
来源：http://dali.ydzc1.top/Article/details/gt2pqumxyjr.html

guard let x = opt else { return }
来源：http://dali.kuanghao11.cn/Article/details/gt2ensyxobe.html

[T30] Swift：协议
来源：http://dali.xuanzx.com/Article/details/gt2bvnzzkeb.html

protocol Shape { func area() -> Double }
来源：http://dali.hysaishi.cn/Article/details/gt2dfgipyzj.html

[T31] Lua：Hello World
来源：http://dali.yonumen.top/Article/details/gt2zysgatsr.html

print("Hello")
来源：http://dali.yj202588.top/Article/details/gt2ebtdspdx.html

[T32] Lua：局部变量
来源：http://dali.andypj.xyz/Article/details/gt2yijimvsd.html

local a = 1
来源：http://dali.0kj1m.cn/Article/details/gt2mitznvqj.html

[T33] Lua：表（数组）
来源：http://dali.kuanghao11.cn/Article/details/gt2lzdczvqc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.svipenyu.cn/Article/details/gt2pynieyad.html

[T34] Lua：遍历表
来源：http://dali.guannengcc.top/Article/details/gt2thpctjat.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.birdmap.top/Article/details/gt2suudxcwm.html

[T35] Lua：字典表
来源：http://dali.xuetiantiany.cn/Article/details/gt2scanihhs.html

local d = { a = 1 };  d.b = 2
来源：http://dali.guannengcc.top/Article/details/gt2oklapgyr.html

[T36] Lua：函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2hpuzayrk.html

function add(a, b) return a + b end
来源：http://dali.9152youxi.cn/Article/details/gt2psfebwnx.html

[T37] Lua：字符串拼接
来源：http://dali.redwolf501.top/Article/details/gt2gjjeqaaj.html

"a" .. "b"
来源：http://dali.xinyue.icu/Article/details/gt2iraxhcnn.html

[T38] Lua：条件
来源：http://dali.cheryme.top/Article/details/gt2cgessdxx.html

if x > 0 then print("正") end
来源：http://dali.guowangkeji.top/Article/details/gt2jhrdzgcl.html

[T39] Lua：模式匹配
来源：http://dali.jianghu66.top/Article/details/gt2uqjaekmv.html

string.find(s, "%d+")
来源：http://dali.shzxlz.cn/Article/details/gt2upsmatwt.html

[T40] Lua：元表
来源：http://dali.hysaishi.cn/Article/details/gt2ljmbjkyj.html

setmetatable({}, { __index = base })
来源：http://dali.daria6918.cn/Article/details/gt2qiywgtan.html

[T41] Perl：Hello World
来源：http://dali.cheryme.top/Article/details/gt2ntelfcgu.html

print "Hello\n";
来源：http://dali.hammf.cn/Article/details/gt2initnfpy.html

[T42] Perl：变量类型
来源：http://dali.xziqi.cn/Article/details/gt2nqokvquz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yuanzhike.top/Article/details/gt2jlffrpmu.html

[T43] Perl：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gt2ulhvbien.html

"值: $a"
来源：http://dali.havefunace.top/Article/details/gt2kneqvkea.html

[T44] Perl：条件
来源：http://dali.gzhubu.top/Article/details/gt2fhfqaxmf.html

if ($a > 0) { print "正"; }
来源：http://dali.wangdashe.top/Article/details/gt2xbxdjzwm.html

[T45] Perl：数组遍历
来源：http://dali.dianchejie.cn/Article/details/gt2bygfhkzv.html

for my $x (@arr) { print $x; }
来源：http://dali.xinyue.icu/Article/details/gt2jfwumuhv.html

[T46] Perl：哈希操作
来源：http://dali.shuidangran.top/Article/details/gt2rruivkvx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yuanzhike.top/Article/details/gt2xskunukm.html

[T47] Perl：正则捕获
来源：http://dali.gaohongyu789.top/Article/details/gt2hhtlrjrd.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zycfv.cn/Article/details/gt2ysliofoe.html

[T48] Perl：正则替换
来源：http://dali.xuetiantiany.cn/Article/details/gt2vcxioyck.html

$s =~ s/old/new/g;
来源：http://dali.daria6918.cn/Article/details/gt2xpikcsui.html

[T49] Perl：函数
来源：http://dali.yuxming.cn/Article/details/gt2lfjbsfxw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.wangdashe.top/Article/details/gt2vnpheaop.html

[T50] Perl：逐行读文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hmelfkmt.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hammf.cn/Article/details/gt2hrjxvzhx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hysaishi.cn/Article/details/gt2jassaxvj.html

[T51] Scala：Hello World
来源：http://dali.yangfankeji.com/Article/details/gt2uhmoevra.html

println("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gt2xfnjuzfk.html

[T52] Scala：变量
来源：http://dali.gzhubu.top/Article/details/gt2symxtcew.html

val a = 1;  var b = 2
来源：http://dali.zhengqikj.top/Article/details/gt2ntdpuypb.html

[T53] Scala：字符串插值
来源：http://dali.svipenyu.cn/Article/details/gt2aybnlopx.html

s"值: $b"
来源：http://dali.hnqzz.top/Article/details/gt2lpygxkgn.html

[T54] Scala：集合映射
来源：http://dali.daria6918.cn/Article/details/gt2monkxcqj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.guannengcc.top/Article/details/gt2vlaoyzvc.html

[T55] Scala：集合过滤
来源：http://dali.pengpengdd.cyou/Article/details/gt2kthfunxk.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hfpthk.cn/Article/details/gt2bzzutysm.html

[T56] Scala：样例类
来源：http://dali.hongshengwenyu.top/Article/details/gt2ytgmzwzp.html


<!-- 参考信息 -->