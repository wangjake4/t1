代发 wailian999

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.chenjidiqi.icu/Article/details/gt2cyddqtao.html

[R52] 统计行数
来源：http://dali.gogol.net.cn/Article/details/gt2gehqreeg.html

wc -l a.txt
来源：http://dali.gotoacloud.top/Article/details/gt2wrjvvial.html

[R53] 查看文件头与实时尾
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gdmfgdem.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xylfe.cn/Article/details/gt2pjblfhwj.html

[R54] 比较两个文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hpueeyjc.html

diff a.txt b.txt
来源：http://dali.andypj.xyz/Article/details/gt2hivzbnaw.html

[R55] 压缩与解压
来源：http://dali.wangdashe.top/Article/details/gt2bybntyzl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.haohaochexian.top/Article/details/gt2uywgrgpm.html

[R56] 远程拷贝
来源：http://dali.shangyingyoupin.top/Article/details/gt2rlyqpdnb.html

scp file user@host:/path/
来源：http://dali.gaohongyu789.top/Article/details/gt2kdvmqmnj.html

[R57] 远程执行命令
来源：http://dali.redwolf501.top/Article/details/gt2kpprypui.html

ssh user@host 'uptime'
来源：http://dali.jianghu66.top/Article/details/gt2fmqbblec.html

[R58] 下载文件
来源：http://dali.cashguo.top/Article/details/gt2bmvnqdai.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.snrcjt.cn/Article/details/gt2hhhglsuw.html

[R59] 发 POST JSON
来源：http://dali.haohaochexian.top/Article/details/gt2ipqbaqls.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aqwpliha.html

[R60] 只看 HTTP 状态码
来源：http://dali.haohaochexian.top/Article/details/gt2ibkxsjqq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.dashuyun.cn/Article/details/gt2qstkcltn.html

[R61] 磁盘占用
来源：http://dali.yangfankeji.com/Article/details/gt2iqturqkb.html

df -h;  du -sh *
来源：http://dali.yuanzhike.top/Article/details/gt2tygzwfwr.html

[R62] 找最占空间的文件
来源：http://dali.sxryk.cn/Article/details/gt2yzuyhcxl.html

du -ah . | sort -rh | head -10
来源：http://dali.dashuyun.cn/Article/details/gt2ntkawzrl.html

[R63] 内存与进程
来源：http://dali.kuanghao11.cn/Article/details/gt2uiyejyvy.html

free -h;  ps aux | grep nginx
来源：http://dali.cqqwz.cn/Article/details/gt2uczprgha.html

[R64] 结束进程
来源：http://dali.nanxuanxn.top/Article/details/gt2uxohgihl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sweek.top/Article/details/gt2nnykdual.html

[R65] 查看端口占用
来源：http://dali.hnxiangtu.top/Article/details/gt2sggzcxqt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.birdmap.top/Article/details/gt2naaqotfq.html

[R66] 定时任务
来源：http://dali.chenlongwang.top/Article/details/gt2krmklcga.html

crontab -e;  crontab -l
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fdwmqswy.html

[R67] 生成随机十六进制串
来源：http://dali.shuidangran.top/Article/details/gt2qhlqyyei.html

openssl rand -hex 16
来源：http://dali.yuanzhike.top/Article/details/gt2tjyyoakg.html

[R68] 计算文件校验值
来源：http://dali.9152youxi.cn/Article/details/gt2pchrfklv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jianghu66.top/Article/details/gt2llkgrztt.html

[R69] 生成随机密码
来源：http://dali.gotoacloud.top/Article/details/gt2jexffmtp.html

head -c 16 /dev/urandom | base64
来源：http://dali.birdmap.top/Article/details/gt2xzdaijpi.html

[R70] 时间戳与互转
来源：http://dali.hammf.cn/Article/details/gt2qmzrmhaz.html

date +%s;  date -d @1700000000
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gmmuclct.html

[R71] 日期格式化
来源：http://dali.yvedp.cn/Article/details/gt2eddqfqus.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jqgfzy.top/Article/details/gt2anrgyysq.html

[R72] 等待端口就绪
来源：http://dali.ehwqpu.com/Article/details/gt2focnqktw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.c1oappe.top/Article/details/gt2hgzaewuk.html

[R73] 分割大日志
来源：http://dali.jinqigufen.top/Article/details/gt2rxrcewjl.html

split -l 1000 big.log part_
来源：http://dali.ehwqpu.com/Article/details/gt2atopeaou.html

[R74] 批量重命名
来源：http://dali.cdnleiting.top/Article/details/gt2lylmauwf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yueranfly.top/Article/details/gt2joodtezy.html

[R75] 导出环境变量
来源：http://dali.jinqigufen.top/Article/details/gt2syxerrll.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zdqjudy.top/Article/details/gt2qsqripwb.html

[R76] 使用临时文件
来源：http://dali.xziqi.cn/Article/details/gt2xxousupf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gaohongyu789.top/Article/details/gt2uzsxzuaf.html

[R77] 读取用户输入
来源：http://dali.chenjidiqi.icu/Article/details/gt2mugmyvvl.html

read -rp "请输入: " ans
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fnpwsnoa.html

[R78] 交互式菜单
来源：http://dali.shzxlz.cn/Article/details/gt2mflhvvno.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jyoumei.cn/Article/details/gt2tsrxzitj.html

[R79] 解析命令行选项
来源：http://dali.zhixingplan.top/Article/details/gt2ahhtleix.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jinqigufen.top/Article/details/gt2pmgdwydy.html

[R80] 查看脚本执行耗时
来源：http://dali.jinqigufen.top/Article/details/gt2afdvgeyo.html

time ./run.sh
来源：http://dali.nwbrower.top/Article/details/gt2ngzwdhnc.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2qpzsgqwx.html

S. C / C++ 专题
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qauzhrku.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2vfqowzjd.html

[S01] C：Hello World
来源：http://dali.chenzaomai.com/Article/details/gt2hqsovcgh.html

#include <stdio.h>
来源：http://dali.sweek.top/Article/details/gt2frhrhswd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shzxlz.cn/Article/details/gt2obqtpwiy.html

[S02] C：变量与格式化输出
来源：http://dali.svipenyu.cn/Article/details/gt2fnqpihql.html

int a = 10; printf("%d\n", a);
来源：http://dali.guannengcc.top/Article/details/gt2prguxclk.html

[S03] C：读入整数
来源：http://dali.sufxvd.cn/Article/details/gt2dwuxgebc.html

int x; scanf("%d", &x);
来源：http://dali.fengsongda.top/Article/details/gt2ugenyfnc.html

[S04] C：字符串复制
来源：http://dali.zhiwuduotai.top/Article/details/gt2wbyvdanh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.kuanghao11.cn/Article/details/gt2zptnzbct.html

[S05] C：字符串长度
来源：http://dali.yongpay.top/Article/details/gt2oyhakzxf.html

strlen(s)
来源：http://dali.hfpthk.cn/Article/details/gt2wvmciyod.html

[S06] C：字符串比较
来源：http://dali.shzxlz.cn/Article/details/gt2izubjbsm.html

strcmp(a, b) == 0
来源：http://dali.tian-w.cn/Article/details/gt2vzltnqlb.html

[S07] C：数组遍历求和
来源：http://dali.nanxuanxn.top/Article/details/gt2yfqblidt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ehwqpu.com/Article/details/gt2dxlkjwbw.html

[S08] C：动态内存分配与释放
来源：http://dali.zhixingplan.top/Article/details/gt2exwsfdre.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hywenlv.cn/Article/details/gt2vljcvcua.html

[S09] C：结构体定义与初始化
来源：http://dali.fzhhl.top/Article/details/gt2wsykabsu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jlsjyb.cn/Article/details/gt2mfcxajos.html

[S10] C：指针与解引用
来源：http://dali.feifeiyinyue.top/Article/details/gt2onbgmmbf.html

int *p = &a;  *p = 5;
来源：http://dali.yvedp.cn/Article/details/gt2cinmhnau.html

[S11] C：逐行读文件
来源：http://dali.smart0.xyz/Article/details/gt2drznfrqf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hongshengwenyu.top/Article/details/gt2buwdyvzi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.fengsongda.top/Article/details/gt2unekxslq.html

fclose(f);
来源：http://dali.ehwqpu.com/Article/details/gt2luihgkig.html

[S12] C：写文件
来源：http://dali.havefunace.top/Article/details/gt2viusumtt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.316326.xyz/Article/details/gt2wyqvrfaf.html

[S13] C：宏定义
来源：http://dali.chenzaomai.com/Article/details/gt2ozwwktwk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.wangshuangyany.cn/Article/details/gt2wadzdvbo.html

[S14] C：枚举
来源：http://dali.zdqjudy.top/Article/details/gt2xbqqxfke.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.316326.xyz/Article/details/gt2etuwvtgs.html

[S15] C：类型转换
来源：http://dali.andypj.xyz/Article/details/gt2vwtembua.html

(double) a / b
来源：http://dali.sufxvd.cn/Article/details/gt2bhgtkcub.html

[S16] C：位操作置位
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ytmibszv.html

x |= (1 << 3);
来源：http://dali.tian-w.cn/Article/details/gt2exmuyqmt.html

[S17] C：安全拼接字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2avklkvft.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.nanxuanxn.top/Article/details/gt2ylqhodns.html

[S18] C：命令行参数
来源：http://dali.cashguo.top/Article/details/gt2dnagxxhk.html

int main(int argc, char **argv)
来源：http://dali.tianlin.xyz/Article/details/gt2vzevtlbt.html

[S19] C：快速排序
来源：http://dali.yj20258.top/Article/details/gt2kyfalohx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xuanzx.com/Article/details/gt2cyccmtrq.html

[S20] C：二分查找
来源：http://dali.tianlin.xyz/Article/details/gt2fgevdugn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.birdmap.top/Article/details/gt2pedddiqi.html

[S21] C：字符类别判断
来源：http://dali.hongshengwenyu.top/Article/details/gt2vjihhbvc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.pycfn.com/Article/details/gt2apbdyusj.html

[S22] C：字符串转数字
来源：http://dali.zhoulong.xyz/Article/details/gt2qttzrrgw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.quarkkingdee.top/Article/details/gt2vgoxjpic.html

[S23] C：随机数
来源：http://dali.jianghu66.top/Article/details/gt2hdxodqtd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yueranfly.top/Article/details/gt2hztugivg.html

[S24] C：获取本地时间
来源：http://dali.vqdsnc.cn/Article/details/gt2udjgqdlt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sykhgprc.html

[S25] C：内存拷贝
来源：http://dali.xinyue.icu/Article/details/gt2lhfyovuk.html

memcpy(dst, src, n);
来源：http://dali.ppjwa.cn/Article/details/gt2pbcmhqmd.html

[S26] C：内存清零
来源：http://dali.tianlin.xyz/Article/details/gt2cwwedgju.html

memset(a, 0, sizeof a);
来源：http://dali.hammf.cn/Article/details/gt2ywxjbcby.html

[S27] C：定义常量
来源：http://dali.hywenlv.cn/Article/details/gt2vtvviweb.html

const double PI = 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gt2atlbwkwd.html

[S28] C：静态变量
来源：http://dali.zhixingplan.top/Article/details/gt2vebtpztu.html

static int counter = 0;
来源：http://dali.havefunace.top/Article/details/gt2gnqiuolk.html

[S29] C：变参函数
来源：http://dali.ehwqpu.com/Article/details/gt2wizoptvn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.iojbl.cn/Article/details/gt2nzvxctev.html

[S30] C：头文件保护
来源：http://dali.c1oappe.top/Article/details/gt2zqwrwcbb.html

#ifndef X_H
来源：http://dali.0kj1m.cn/Article/details/gt2targjmau.html

#define X_H
来源：http://dali.hnxiangtu.top/Article/details/gt2pxfxzsrg.html

#endif
来源：http://dali.fzhhl.top/Article/details/gt2qomnyqvb.html

[S31] C++：Hello World
来源：http://dali.dianchejie.cn/Article/details/gt2buigbshw.html

#include <iostream>
来源：http://dali.daria6918.cn/Article/details/gt2rhlrgwiu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yvedp.cn/Article/details/gt2dandadgh.html

[S32] C++：字符串
来源：http://dali.havefunace.top/Article/details/gt2sjomhkju.html

std::string s = "hi";  s += "!";
来源：http://dali.sysykeji.top/Article/details/gt2ffbgiggj.html

[S33] C++：vector 增删
来源：http://dali.meibo888.top/Article/details/gt2lgvswsgx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhiwuduotai.top/Article/details/gt2prhxjxki.html

[S34] C++：遍历 vector
来源：http://dali.hfpthk.cn/Article/details/gt2xjinaqig.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yj202588.top/Article/details/gt2jznmdqla.html

[S35] C++：map
来源：http://dali.aizwys.cn/Article/details/gt2tujxgefc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.redwolf501.top/Article/details/gt2mzeegtzt.html

[S36] C++：unordered_map
来源：http://dali.sufxvd.cn/Article/details/gt2hdvxdbeb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuxming.cn/Article/details/gt2lzzxoodl.html

[S37] C++：set
来源：http://dali.ppjwa.cn/Article/details/gt2gkhochhu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yvedp.cn/Article/details/gt2rntuntlv.html

[S38] C++：排序
来源：http://dali.9152youxi.cn/Article/details/gt2gfklxbee.html

std::sort(v.begin(), v.end());
来源：http://dali.redwolf501.top/Article/details/gt2abmqwinh.html

[S39] C++：自定义比较器排序
来源：http://dali.zhiwuduotai.top/Article/details/gt2vsgmzfif.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pdggvgcf.html

[S40] C++：查找元素
来源：http://dali.xuetiantiany.cn/Article/details/gt2vyxxcbgw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.redwolf501.top/Article/details/gt2ixhsjwzh.html

[S41] C++：类与构造函数
来源：http://dali.meibo888.top/Article/details/gt2fkbxbjbd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zdqjudy.top/Article/details/gt2mqfifdqz.html

[S42] C++：继承与虚函数
来源：http://dali.yanxiufei.cn/Article/details/gt2shuerdmz.html

class B : public Base { public: void f() override {} };
来源：http://dali.gogol.net.cn/Article/details/gt2byednaet.html

[S43] C++：智能指针
来源：http://dali.dashuyun.cn/Article/details/gt2twfdmdwl.html

auto p = std::make_unique<int>(5);
来源：http://dali.meibo888.top/Article/details/gt2rvgdoget.html

[S44] C++：引用传参
来源：http://dali.jinqigufen.top/Article/details/gt2cideskge.html

void inc(int &x) { ++x; }
来源：http://dali.sweek.top/Article/details/gt2vplvrypz.html

[S45] C++：lambda
来源：http://dali.yonumen.top/Article/details/gt2dzbjdulg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cheryme.top/Article/details/gt2ouqcxzrr.html

[S46] C++：函数模板
来源：http://dali.feifeiyinyue.top/Article/details/gt2wjyhimir.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yonumen.top/Article/details/gt2nuxjyktf.html

[S47] C++：结构化绑定遍历
来源：http://dali.yuxming.cn/Article/details/gt2njapnvfk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.316326.xyz/Article/details/gt2qwqhbavx.html

[S48] C++：逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2fygxedpt.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yonumen.top/Article/details/gt2ydybmcrt.html

while (std::getline(in, line)) { }
来源：http://dali.tanke756.top/Article/details/gt2fvfwaavf.html

[S49] C++：写文件
来源：http://dali.zhengqikj.top/Article/details/gt2jxhkfwmp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zycfv.cn/Article/details/gt2sonaskdt.html

[S50] C++：格式化数字
来源：http://dali.wangshuangyany.cn/Article/details/gt2rlahxbct.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.smart0.xyz/Article/details/gt2nitvrdsc.html

[S51] C++：显式类型转换
来源：http://dali.ivvv.top/Article/details/gt2qaqxfyft.html

static_cast<double>(a) / b
来源：http://dali.svipenyu.cn/Article/details/gt2txhffzvk.html

[S52] C++：const 与 noexcept
来源：http://dali.tian-w.cn/Article/details/gt2iuasxxfh.html

int size() const noexcept { return n_; }
来源：http://dali.yangfankeji.com/Article/details/gt2bmmkodrm.html

[S53] C++：移动语义
来源：http://dali.hnxiangtu.top/Article/details/gt2dqaqdfpm.html

std::vector<int> w = std::move(v);
来源：http://dali.ivvv.top/Article/details/gt2vaepvtbs.html

[S54] C++：异常处理
来源：http://dali.jyoumei.cn/Article/details/gt2vnuiwjhd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hysaishi.cn/Article/details/gt2bybbqhbb.html

[S55] C++：结构化绑定
来源：http://dali.tian-w.cn/Article/details/gt2mgivcwax.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jianghu66.top/Article/details/gt2prmedkms.html

[S56] C++：optional
来源：http://dali.yj20258.top/Article/details/gt2ffmdndnx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.0kj1m.cn/Article/details/gt2rfbqqmnk.html

[S57] C++：编译期常量
来源：http://dali.hnxiangtu.top/Article/details/gt2qgnhhbzz.html

constexpr int N = 10;
来源：http://dali.aizwys.cn/Article/details/gt2mjapzvvw.html

[S58] C++：命名空间
来源：http://dali.hywenlv.cn/Article/details/gt2whnlnadi.html

namespace ns { int f() { return 1; } }
来源：http://dali.xylfe.cn/Article/details/gt2bkohflye.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxhvmcp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.birdmap.top/Article/details/gt2zzuzepur.html

[S60] C++：遍历并删除元素
来源：http://dali.wangshuangyany.cn/Article/details/gt2tipejomn.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.fengsongda.top/Article/details/gt2bwjnqhmn.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2oqkhxkjj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yongpay.top/Article/details/gt2fghtpjjf.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2cluethkv.html

[T01] Kotlin：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gt2xcutqqqh.html

println("Hello")
来源：http://dali.aizwys.cn/Article/details/gt2floghqtg.html

[T02] Kotlin：变量
来源：http://dali.wangdashe.top/Article/details/gt2bnshfjbe.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhoulong.xyz/Article/details/gt2qkjcvqno.html

[T03] Kotlin：字符串模板
来源：http://dali.shangyingyoupin.top/Article/details/gt2eerfdssu.html

"值: $b"
来源：http://dali.aizwys.cn/Article/details/gt2xobbfypi.html

[T04] Kotlin：空安全
来源：http://dali.yangfankeji.com/Article/details/gt2ccpaybls.html

val n: String? = null;  n?.length
来源：http://dali.xinyue.icu/Article/details/gt2qbgfhovu.html

[T05] Kotlin：when 表达式
来源：http://dali.ybcxt.top/Article/details/gt2bozetimi.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.havefunace.top/Article/details/gt2pztgaaok.html

[T06] Kotlin：集合映射
来源：http://dali.hywenlv.cn/Article/details/gt2njicttlc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yangfankeji.com/Article/details/gt2feckghdz.html

[T07] Kotlin：集合过滤
来源：http://dali.mhx1999.top/Article/details/gt2acywmxyw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cqqwz.cn/Article/details/gt2inbziwxz.html

[T08] Kotlin：数据类
来源：http://dali.fzhhl.top/Article/details/gt2tcejhqyx.html

data class User(val name: String, val age: Int)
来源：http://dali.sysykeji.top/Article/details/gt2llksjpzo.html

[T09] Kotlin：扩展函数
来源：http://dali.c1oappe.top/Article/details/gt2sracalrj.html

fun String.exclaim() = this + "!"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lumccadx.html

[T10] Kotlin：默认参数
来源：http://dali.zhixingplan.top/Article/details/gt2rjlpkwat.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.pengpengdd.cyou/Article/details/gt2njazwxrk.html

[T11] Kotlin：协程
来源：http://dali.tanke756.top/Article/details/gt2xiapsvsy.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xuanzx.com/Article/details/gt2rntuyoqu.html

[T12] Kotlin：解构声明
来源：http://dali.hammf.cn/Article/details/gt2udzxlgku.html

val (a, b) = Pair(1, 2)
来源：http://dali.jiagoushi.top/Article/details/gt2atgxypee.html

[T13] Kotlin：只读 Map
来源：http://dali.zhiwuduotai.top/Article/details/gt2nokpwrza.html

val m = mapOf("a" to 1)
来源：http://dali.cheryme.top/Article/details/gt2puehdlyy.html

[T14] Kotlin：循环
来源：http://dali.svipenyu.cn/Article/details/gt2ppwavuym.html

for (i in 1..10) println(i)
来源：http://dali.cashguo.top/Article/details/gt2nnomjvzf.html

[T15] Kotlin：接口
来源：http://dali.yonumen.top/Article/details/gt2xvonbftx.html

interface Shape { fun area(): Double }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lzhjcebi.html

[T16] Swift：Hello World
来源：http://dali.gzhubu.top/Article/details/gt2mdwazaoz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqmtyjs.html

[T17] Swift：变量与常量
来源：http://dali.shangyingyoupin.top/Article/details/gt2bpkfhwtg.html

var a = 1;  let b = 2
来源：http://dali.ydzc1.top/Article/details/gt2ajypdomr.html

[T18] Swift：字符串插值
来源：http://dali.hywenlv.cn/Article/details/gt2galmfhcl.html

"值: \(b)"
来源：http://dali.hongshengwenyu.top/Article/details/gt2efrqkhsz.html

[T19] Swift：可选绑定
来源：http://dali.zhengqikj.top/Article/details/gt2rwcnonen.html

if let n = opt { print(n) }
来源：http://dali.svipenyu.cn/Article/details/gt2ughjczba.html

[T20] Swift：数组操作
来源：http://dali.vqdsnc.cn/Article/details/gt2brnteoos.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yueranfly.top/Article/details/gt2ymofmrwm.html

[T21] Swift：遍历
来源：http://dali.316326.xyz/Article/details/gt2xlibrimo.html

for x in a { print(x) }
来源：http://dali.nanxinkj.top/Article/details/gt2boimcjtj.html

[T22] Swift：字典
来源：http://dali.hnxiangtu.top/Article/details/gt2entggarm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cqqwz.cn/Article/details/gt2wviylfca.html

[T23] Swift：函数
来源：http://dali.ydzc1.top/Article/details/gt2wdaxhash.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.tanke756.top/Article/details/gt2iuexwjuu.html

[T24] Swift：闭包
来源：http://dali.guowangkeji.top/Article/details/gt2xwttmyno.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yj202588.top/Article/details/gt2pblaloyy.html

[T25] Swift：结构体
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xkriablj.html

struct P { var x: Int }
来源：http://dali.xuetiantiany.cn/Article/details/gt2eztnhocb.html

[T26] Swift：类与重写
来源：http://dali.ydzc1.top/Article/details/gt2ivousbxd.html

class A: Base { override func f() {} }
来源：http://dali.chenlongwang.top/Article/details/gt2injqauub.html

[T27] Swift：错误处理
来源：http://dali.chenlongwang.top/Article/details/gt2bobuptut.html

do { try f() } catch { print(error) }
来源：http://dali.cqqwz.cn/Article/details/gt2umgveyne.html

[T28] Swift：枚举
来源：http://dali.cdnleiting.top/Article/details/gt2frewasgy.html

enum Color { case red, green }
来源：http://dali.snrcjt.cn/Article/details/gt2ykzvyyls.html

[T29] Swift：guard 提前返回
来源：http://dali.hysaishi.cn/Article/details/gt2qxcnkpfw.html

guard let x = opt else { return }
来源：http://dali.hnxiangtu.top/Article/details/gt2lmvqxvvd.html

[T30] Swift：协议
来源：http://dali.shangyingyoupin.top/Article/details/gt2weutnfbu.html

protocol Shape { func area() -> Double }
来源：http://dali.jinqigfzy.top/Article/details/gt2boasblxn.html

[T31] Lua：Hello World
来源：http://dali.chenzaomai.com/Article/details/gt2tjnnkzga.html

print("Hello")
来源：http://dali.zhoulong.xyz/Article/details/gt2kkfznzjb.html

[T32] Lua：局部变量
来源：http://dali.daxiang520.top/Article/details/gt2mlxiepli.html

local a = 1
来源：http://dali.gaohongyu789.top/Article/details/gt2xhzwhbpa.html

[T33] Lua：表（数组）
来源：http://dali.xuanzx.com/Article/details/gt2eyklptms.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xziqi.cn/Article/details/gt2ceqjyqnp.html

[T34] Lua：遍历表
来源：http://dali.yueranfly.top/Article/details/gt2feyxugnz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.tianlin.xyz/Article/details/gt2bhioqxxv.html

[T35] Lua：字典表
来源：http://dali.aizwys.cn/Article/details/gt2fnxcqzvl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yueranfly.top/Article/details/gt2hikcznde.html

[T36] Lua：函数
来源：http://dali.sysykeji.top/Article/details/gt2spinzkbp.html

function add(a, b) return a + b end
来源：http://dali.yj202588.top/Article/details/gt2lfgvlyly.html

[T37] Lua：字符串拼接
来源：http://dali.hysaishi.cn/Article/details/gt2vidboanp.html

"a" .. "b"
来源：http://dali.yongpay.top/Article/details/gt2bdlbpyum.html

[T38] Lua：条件
来源：http://dali.ppjwa.cn/Article/details/gt2ftndooll.html

if x > 0 then print("正") end
来源：http://dali.pycfn.com/Article/details/gt2qrjgjwfb.html

[T39] Lua：模式匹配
来源：http://dali.yueranfly.top/Article/details/gt2cvhtjzzg.html

string.find(s, "%d+")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aoqkrhip.html

[T40] Lua：元表
来源：http://dali.cqqwz.cn/Article/details/gt2ieqwzocm.html

setmetatable({}, { __index = base })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jmufatbn.html

[T41] Perl：Hello World
来源：http://dali.jqgfzy.top/Article/details/gt2bkaweqkf.html

print "Hello\n";
来源：http://dali.sysykeji.top/Article/details/gt2gxsgxbad.html

[T42] Perl：变量类型
来源：http://dali.jlsjyb.cn/Article/details/gt2ppkikhkl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.vqdsnc.cn/Article/details/gt2zqnzquvb.html

[T43] Perl：字符串插值
来源：http://dali.c1oappe.top/Article/details/gt2fooxbwnq.html

"值: $a"
来源：http://dali.cheryme.top/Article/details/gt2kbvvrbtl.html

[T44] Perl：条件
来源：http://dali.feifeiyinyue.top/Article/details/gt2waqvnwzc.html

if ($a > 0) { print "正"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2hjpyrqtb.html

[T45] Perl：数组遍历
来源：http://dali.cqqwz.cn/Article/details/gt2etvpjmdu.html

for my $x (@arr) { print $x; }
来源：http://dali.jinqigufen.top/Article/details/gt2bhmzwidg.html

[T46] Perl：哈希操作
来源：http://dali.zycfv.cn/Article/details/gt2qcajavtw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rvjhulhw.html

[T47] Perl：正则捕获
来源：http://dali.316326.xyz/Article/details/gt2iumelwtr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.dashuyun.cn/Article/details/gt2cbmoxvfd.html

[T48] Perl：正则替换
来源：http://dali.sxryk.cn/Article/details/gt2piopmphx.html

$s =~ s/old/new/g;
来源：http://dali.snrcjt.cn/Article/details/gt2zodxkncp.html

[T49] Perl：函数
来源：http://dali.zdqjudy.top/Article/details/gt2ieugabzy.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yvedp.cn/Article/details/gt2yekjsehk.html

[T50] Perl：逐行读文件
来源：http://dali.yj202588.top/Article/details/gt2eypygigl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gaohongyu789.top/Article/details/gt2wcuxodfx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2xqdlziki.html

[T51] Scala：Hello World
来源：http://dali.svipenyu.cn/Article/details/gt2awdzgwyi.html

println("Hello")
来源：http://dali.yvedp.cn/Article/details/gt2pvzzluls.html

[T52] Scala：变量
来源：http://dali.zdqjudy.top/Article/details/gt2nruugnaq.html

val a = 1;  var b = 2
来源：http://dali.yj202588.top/Article/details/gt2fcgirzxw.html

[T53] Scala：字符串插值
来源：http://dali.yuanzhike.top/Article/details/gt2pljawoun.html

s"值: $b"
来源：http://dali.mhx1999.top/Article/details/gt2hqpoawla.html

[T54] Scala：集合映射
来源：http://dali.hnxiangtu.top/Article/details/gt2bcqolouf.html


<!-- 参考信息 -->