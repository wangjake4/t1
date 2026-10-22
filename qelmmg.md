代发 wailian999

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zdqjudy.top/Article/details/gt2rdltnthv.html

[R56] 远程拷贝
来源：http://dali.yj20258.top/Article/details/gt2bmdayoxl.html

scp file user@host:/path/
来源：http://dali.hnqzz.top/Article/details/gt2dqsjevdj.html

[R57] 远程执行命令
来源：http://dali.jlsjyb.cn/Article/details/gt2mstijokr.html

ssh user@host 'uptime'
来源：http://dali.nwbrower.top/Article/details/gt2otdyytvq.html

[R58] 下载文件
来源：http://dali.smart0.xyz/Article/details/gt2qekshfmo.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.haohaochexian.top/Article/details/gt2jjygxpnc.html

[R59] 发 POST JSON
来源：http://dali.zdqjudy.top/Article/details/gt2wjdmokhc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cheryme.top/Article/details/gt2yengvqfp.html

[R60] 只看 HTTP 状态码
来源：http://dali.jqgfzy.top/Article/details/gt2kolnmxqy.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.aibaodan.cn/Article/details/gt2druhdogk.html

[R61] 磁盘占用
来源：http://dali.zdqjudy.top/Article/details/gt2dmwvdmjq.html

df -h;  du -sh *
来源：http://dali.iojbl.cn/Article/details/gt2byqyksib.html

[R62] 找最占空间的文件
来源：http://dali.yj202588.top/Article/details/gt2tqsdypcm.html

du -ah . | sort -rh | head -10
来源：http://dali.sysykeji.top/Article/details/gt2wpjiozcl.html

[R63] 内存与进程
来源：http://dali.svipenyu.cn/Article/details/gt2vtpfwafn.html

free -h;  ps aux | grep nginx
来源：http://dali.fengsongda.top/Article/details/gt2ewjfrudm.html

[R64] 结束进程
来源：http://dali.chenlongwang.top/Article/details/gt2fqyfvbqe.html

kill -9 $(pgrep -f app.py)
来源：http://dali.fengsongda.top/Article/details/gt2abehbzrs.html

[R65] 查看端口占用
来源：http://dali.yueranfly.top/Article/details/gt2tqoskmrb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jinqigufen.top/Article/details/gt2vvnlxyxq.html

[R66] 定时任务
来源：http://dali.hywenlv.cn/Article/details/gt2davlrbsf.html

crontab -e;  crontab -l
来源：http://dali.jqgufenzy.top/Article/details/gt2srdasorw.html

[R67] 生成随机十六进制串
来源：http://dali.chenzaomai.com/Article/details/gt2gcahqvur.html

openssl rand -hex 16
来源：http://dali.zycfv.cn/Article/details/gt2csyqhelx.html

[R68] 计算文件校验值
来源：http://dali.yvedp.cn/Article/details/gt2bvzhtakq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.chenzaomai.com/Article/details/gt2vjwdekwo.html

[R69] 生成随机密码
来源：http://dali.xuanzx.com/Article/details/gt2wwuxmeax.html

head -c 16 /dev/urandom | base64
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sugautrl.html

[R70] 时间戳与互转
来源：http://dali.yvedp.cn/Article/details/gt2qgawhepe.html

date +%s;  date -d @1700000000
来源：http://dali.nanxuanxn.top/Article/details/gt2dxwxdbze.html

[R71] 日期格式化
来源：http://dali.yj20258888.top/Article/details/gt2sktyqhuq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.nanxuanxn.top/Article/details/gt2gmixuqyh.html

[R72] 等待端口就绪
来源：http://dali.nanxinkj.top/Article/details/gt2wyjgtauf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.mhx1999.top/Article/details/gt2dtyuywls.html

[R73] 分割大日志
来源：http://dali.nanxinkj.top/Article/details/gt2essbppkv.html

split -l 1000 big.log part_
来源：http://dali.gotoacloud.top/Article/details/gt2zcqalbet.html

[R74] 批量重命名
来源：http://dali.zhoulong.xyz/Article/details/gt2dtmqtbcs.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hnqzz.top/Article/details/gt2efxyhefe.html

[R75] 导出环境变量
来源：http://dali.sweek.top/Article/details/gt2kohnnkkq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ehwqpu.com/Article/details/gt2mqpcbfyo.html

[R76] 使用临时文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wiqfrdgp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cxxhobew.html

[R77] 读取用户输入
来源：http://dali.daria6918.cn/Article/details/gt2mfhqgoez.html

read -rp "请输入: " ans
来源：http://dali.jlsjyb.cn/Article/details/gt2ciavrbbr.html

[R78] 交互式菜单
来源：http://dali.yuanzhike.top/Article/details/gt2fxqcnisu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yj20258.top/Article/details/gt2vuvjpcaz.html

[R79] 解析命令行选项
来源：http://dali.redwolf501.top/Article/details/gt2acbzviti.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.daxiang520.top/Article/details/gt2yptpwxlg.html

[R80] 查看脚本执行耗时
来源：http://dali.sweek.top/Article/details/gt2qrfmaggz.html

time ./run.sh
来源：http://dali.aizwys.cn/Article/details/gt2peuebfpb.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2ihcmdfzj.html

S. C / C++ 专题
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hmtoefja.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2yvsokybv.html

[S01] C：Hello World
来源：http://dali.yvedp.cn/Article/details/gt2jykptule.html

#include <stdio.h>
来源：http://dali.zycfv.cn/Article/details/gt2nfdiigfd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.bjfxy.top/Article/details/gt2vushseke.html

[S02] C：变量与格式化输出
来源：http://dali.zycfv.cn/Article/details/gt2irkfvopi.html

int a = 10; printf("%d\n", a);
来源：http://dali.zdqjudy.top/Article/details/gt2lxddfdva.html

[S03] C：读入整数
来源：http://dali.snrcjt.cn/Article/details/gt2yldznqrx.html

int x; scanf("%d", &x);
来源：http://dali.jianghu66.top/Article/details/gt2foirxxce.html

[S04] C：字符串复制
来源：http://dali.hysaishi.cn/Article/details/gt2mffivmmf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jlsjyb.cn/Article/details/gt2ckorycrn.html

[S05] C：字符串长度
来源：http://dali.cqqwz.cn/Article/details/gt2xgrskpof.html

strlen(s)
来源：http://dali.c1oappe.top/Article/details/gt2hljqpjoq.html

[S06] C：字符串比较
来源：http://dali.smart0.xyz/Article/details/gt2xvfuwwee.html

strcmp(a, b) == 0
来源：http://dali.ppjwa.cn/Article/details/gt2gwndxfpa.html

[S07] C：数组遍历求和
来源：http://dali.cqqwz.cn/Article/details/gt2ntwaxznd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.fzhhl.top/Article/details/gt2tuwlfowm.html

[S08] C：动态内存分配与释放
来源：http://dali.hongshengwenyu.top/Article/details/gt2ruppsmvw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.dianchejie.cn/Article/details/gt2sswywjya.html

[S09] C：结构体定义与初始化
来源：http://dali.yueranfly.top/Article/details/gt2lnwshrxv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.havefunace.top/Article/details/gt2ahseimdx.html

[S10] C：指针与解引用
来源：http://dali.jyoumei.cn/Article/details/gt2zgsjbbci.html

int *p = &a;  *p = 5;
来源：http://dali.xylfe.cn/Article/details/gt2vhogjrbf.html

[S11] C：逐行读文件
来源：http://dali.hfpthk.cn/Article/details/gt2ptiffdvw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.aizwys.cn/Article/details/gt2lapwkjpw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2twgcxhlg.html

fclose(f);
来源：http://dali.fzhhl.top/Article/details/gt2xejkqrtt.html

[S12] C：写文件
来源：http://dali.pycfn.com/Article/details/gt2vgvtrdcm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hywenlv.cn/Article/details/gt2qrdywchh.html

[S13] C：宏定义
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2misrhwmc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.daxiang520.top/Article/details/gt2flizftnn.html

[S14] C：枚举
来源：http://dali.hammf.cn/Article/details/gt2pcztvwqs.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ybcxt.top/Article/details/gt2dhzpjcxb.html

[S15] C：类型转换
来源：http://dali.yonumen.top/Article/details/gt2ofkalscb.html

(double) a / b
来源：http://dali.shzxlz.cn/Article/details/gt2twzvvxgq.html

[S16] C：位操作置位
来源：http://dali.zycfv.cn/Article/details/gt2qhgbgknk.html

x |= (1 << 3);
来源：http://dali.nanxinkj.top/Article/details/gt2omhjyzdd.html

[S17] C：安全拼接字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2uskwvlti.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.redwolf501.top/Article/details/gt2tvtauqyo.html

[S18] C：命令行参数
来源：http://dali.xziqi.cn/Article/details/gt2cnseolzq.html

int main(int argc, char **argv)
来源：http://dali.jinqigfzy.top/Article/details/gt2bbkpjupd.html

[S19] C：快速排序
来源：http://dali.hysaishi.cn/Article/details/gt2qmzvxofn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvudidgo.html

[S20] C：二分查找
来源：http://dali.sufxvd.cn/Article/details/gt2qqedufam.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sysykeji.top/Article/details/gt2amlnjlvv.html

[S21] C：字符类别判断
来源：http://dali.zhixingplan.top/Article/details/gt2ltjcxxct.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.pengpengdd.cyou/Article/details/gt2yndhooah.html

[S22] C：字符串转数字
来源：http://dali.hysaishi.cn/Article/details/gt2rlxqaysu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.pycfn.com/Article/details/gt2yiiycyix.html

[S23] C：随机数
来源：http://dali.zhoulong.xyz/Article/details/gt2grwizvtc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.iojbl.cn/Article/details/gt2opplolnw.html

[S24] C：获取本地时间
来源：http://dali.jyoumei.cn/Article/details/gt2pguxnnud.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2lulaxxse.html

[S25] C：内存拷贝
来源：http://dali.sxryk.cn/Article/details/gt2vlmlvcfb.html

memcpy(dst, src, n);
来源：http://dali.shuidangran.top/Article/details/gt2shhpbauu.html

[S26] C：内存清零
来源：http://dali.0kj1m.cn/Article/details/gt2jgblldub.html

memset(a, 0, sizeof a);
来源：http://dali.316326.xyz/Article/details/gt2bzyiwjui.html

[S27] C：定义常量
来源：http://dali.andypj.xyz/Article/details/gt2gsvkxyot.html

const double PI = 3.14159;
来源：http://dali.cheryme.top/Article/details/gt2xhkxofjr.html

[S28] C：静态变量
来源：http://dali.ydzc1.top/Article/details/gt2kzfaxzif.html

static int counter = 0;
来源：http://dali.zhengqikj.top/Article/details/gt2ilmcwtak.html

[S29] C：变参函数
来源：http://dali.svipenyu.cn/Article/details/gt2cjuvszsa.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jlsjyb.cn/Article/details/gt2qjuhxsxh.html

[S30] C：头文件保护
来源：http://dali.redwolf501.top/Article/details/gt2cegpwltq.html

#ifndef X_H
来源：http://dali.redwolf501.top/Article/details/gt2miiknzli.html

#define X_H
来源：http://dali.yj20258.top/Article/details/gt2ivjbngch.html

#endif
来源：http://dali.xuetiantiany.cn/Article/details/gt2ioiwrnvt.html

[S31] C++：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gt2ozaslymn.html

#include <iostream>
来源：http://dali.guowangkeji.top/Article/details/gt2fkjoupoi.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.tianlin.xyz/Article/details/gt2jtofjhkp.html

[S32] C++：字符串
来源：http://dali.smart0.xyz/Article/details/gt2vbigyekf.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2yahirguo.html

[S33] C++：vector 增删
来源：http://dali.tian-w.cn/Article/details/gt2viextlcn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.sysykeji.top/Article/details/gt2bavyrtsy.html

[S34] C++：遍历 vector
来源：http://dali.aizwys.cn/Article/details/gt2djvauojk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhoulong.xyz/Article/details/gt2zqhqfxgp.html

[S35] C++：map
来源：http://dali.pengpengdd.cyou/Article/details/gt2sibflfwf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gt2keppfqkc.html

[S36] C++：unordered_map
来源：http://dali.sweek.top/Article/details/gt2uaxcbqgr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xziqi.cn/Article/details/gt2saspyorv.html

[S37] C++：set
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wappfwhw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yuanzhike.top/Article/details/gt2yjmrhorl.html

[S38] C++：排序
来源：http://dali.c1oappe.top/Article/details/gt2tyxgmrwn.html

std::sort(v.begin(), v.end());
来源：http://dali.aizwys.cn/Article/details/gt2plmtmrqm.html

[S39] C++：自定义比较器排序
来源：http://dali.jinqigufen.top/Article/details/gt2mvsufcyj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hysaishi.cn/Article/details/gt2nraarekh.html

[S40] C++：查找元素
来源：http://dali.fengsongda.top/Article/details/gt2crsiisxq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nanxuanxn.top/Article/details/gt2ferudmcf.html

[S41] C++：类与构造函数
来源：http://dali.yvedp.cn/Article/details/gt2zkdvwmbq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yuxming.cn/Article/details/gt2fyhjyaeq.html

[S42] C++：继承与虚函数
来源：http://dali.yongpay.top/Article/details/gt2bybbuvwl.html

class B : public Base { public: void f() override {} };
来源：http://dali.meibo888.top/Article/details/gt2beomlfps.html

[S43] C++：智能指针
来源：http://dali.xinyue.icu/Article/details/gt2gwmzprnk.html

auto p = std::make_unique<int>(5);
来源：http://dali.tanke756.top/Article/details/gt2azzhkzbk.html

[S44] C++：引用传参
来源：http://dali.hammf.cn/Article/details/gt2aufxcpnq.html

void inc(int &x) { ++x; }
来源：http://dali.dashuyun.cn/Article/details/gt2cdbnxymr.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2fuksxwzh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.dashuyun.cn/Article/details/gt2vrbbdobt.html

[S46] C++：函数模板
来源：http://dali.yj202588.top/Article/details/gt2fxxcardt.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yvedp.cn/Article/details/gt2odubpfct.html

[S47] C++：结构化绑定遍历
来源：http://dali.yuxming.cn/Article/details/gt2cchzqjya.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zycfv.cn/Article/details/gt2gtthsytz.html

[S48] C++：逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gt2gjcwffsl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.wangshuangyany.cn/Article/details/gt2hhlavqvc.html

while (std::getline(in, line)) { }
来源：http://dali.xuanzx.com/Article/details/gt2mdfvylgc.html

[S49] C++：写文件
来源：http://dali.yongpay.top/Article/details/gt2ahzgtqdk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.wangdashe.top/Article/details/gt2ytkxkxng.html

[S50] C++：格式化数字
来源：http://dali.pycfn.com/Article/details/gt2ctzpnzii.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2klgdslgv.html

[S51] C++：显式类型转换
来源：http://dali.meibo888.top/Article/details/gt2rqrdygnx.html

static_cast<double>(a) / b
来源：http://dali.cashguo.top/Article/details/gt2yafgbdpe.html

[S52] C++：const 与 noexcept
来源：http://dali.chenlongwang.top/Article/details/gt2legjdqco.html

int size() const noexcept { return n_; }
来源：http://dali.zycfv.cn/Article/details/gt2lmhlcitb.html

[S53] C++：移动语义
来源：http://dali.hywenlv.cn/Article/details/gt2bfznkafy.html

std::vector<int> w = std::move(v);
来源：http://dali.c1oappe.top/Article/details/gt2xjgktilh.html

[S54] C++：异常处理
来源：http://dali.jiagoushi.top/Article/details/gt2attktzyr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ppjwa.cn/Article/details/gt2wngqejse.html

[S55] C++：结构化绑定
来源：http://dali.snrcjt.cn/Article/details/gt2mgqwmlwd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.mhx1999.top/Article/details/gt2mutiipno.html

[S56] C++：optional
来源：http://dali.ppjwa.cn/Article/details/gt2hsxdrzor.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.svipenyu.cn/Article/details/gt2eqxeqkfj.html

[S57] C++：编译期常量
来源：http://dali.ehwqpu.com/Article/details/gt2gcbkffbm.html

constexpr int N = 10;
来源：http://dali.xuanzx.com/Article/details/gt2fcgugsjw.html

[S58] C++：命名空间
来源：http://dali.shzxlz.cn/Article/details/gt2gfphlnyy.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhengqikj.top/Article/details/gt2tfedjexy.html

[S59] C++：静态断言
来源：http://dali.smart0.xyz/Article/details/gt2tnodfkkx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.tianlin.xyz/Article/details/gt2nofgugcb.html

[S60] C++：遍历并删除元素
来源：http://dali.yj20258888.top/Article/details/gt2ewhfrggy.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zycfv.cn/Article/details/gt2mzxxtsbk.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2mtmgbqjb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yuanzhike.top/Article/details/gt2cphpcqbb.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2etodwrws.html

[T01] Kotlin：Hello World
来源：http://dali.chenzaomai.com/Article/details/gt2rxufadaw.html

println("Hello")
来源：http://dali.tianlin.xyz/Article/details/gt2pqtkjgpx.html

[T02] Kotlin：变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2howlqssn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zsxmlemd.html

[T03] Kotlin：字符串模板
来源：http://dali.cashguo.top/Article/details/gt2seordxob.html

"值: $b"
来源：http://dali.c1oappe.top/Article/details/gt2mqpcyzqx.html

[T04] Kotlin：空安全
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vwavtrio.html

val n: String? = null;  n?.length
来源：http://dali.hongshengwenyu.top/Article/details/gt2yrdzoyhy.html

[T05] Kotlin：when 表达式
来源：http://dali.sufxvd.cn/Article/details/gt2cnqfujhg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shangyingyoupin.top/Article/details/gt2fyspqgbb.html

[T06] Kotlin：集合映射
来源：http://dali.yongpay.top/Article/details/gt2cicbygsj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xuanzx.com/Article/details/gt2mxtbbpbs.html

[T07] Kotlin：集合过滤
来源：http://dali.daria6918.cn/Article/details/gt2eyspfwra.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2snvimver.html

[T08] Kotlin：数据类
来源：http://dali.yuanzhike.top/Article/details/gt2slqovhzy.html

data class User(val name: String, val age: Int)
来源：http://dali.snrcjt.cn/Article/details/gt2iywwrzvk.html

[T09] Kotlin：扩展函数
来源：http://dali.quarkkingdee.top/Article/details/gt2njlssfuh.html

fun String.exclaim() = this + "!"
来源：http://dali.wangdashe.top/Article/details/gt2dalckxvw.html

[T10] Kotlin：默认参数
来源：http://dali.ehwqpu.com/Article/details/gt2ybyjlejn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ppjwa.cn/Article/details/gt2hexdohwz.html

[T11] Kotlin：协程
来源：http://dali.svipenyu.cn/Article/details/gt2zxxtslaz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yuanzhike.top/Article/details/gt2tgmxonrz.html

[T12] Kotlin：解构声明
来源：http://dali.yongpay.top/Article/details/gt2kgxlttyw.html

val (a, b) = Pair(1, 2)
来源：http://dali.andypj.xyz/Article/details/gt2gycrrszz.html

[T13] Kotlin：只读 Map
来源：http://dali.yuanzhike.top/Article/details/gt2aatfkfen.html

val m = mapOf("a" to 1)
来源：http://dali.kuanghao11.cn/Article/details/gt2wuexjnot.html

[T14] Kotlin：循环
来源：http://dali.cashguo.top/Article/details/gt2behodoqd.html

for (i in 1..10) println(i)
来源：http://dali.yongpay.top/Article/details/gt2tsydlprg.html

[T15] Kotlin：接口
来源：http://dali.shzxlz.cn/Article/details/gt2smpwqrcn.html

interface Shape { fun area(): Double }
来源：http://dali.vqdsnc.cn/Article/details/gt2qcieuprh.html

[T16] Swift：Hello World
来源：http://dali.jyoumei.cn/Article/details/gt2jlsdcfhi.html

print("Hello")
来源：http://dali.fzhhl.top/Article/details/gt2cuqxcboq.html

[T17] Swift：变量与常量
来源：http://dali.jqgfzy.top/Article/details/gt2qqghcnxb.html

var a = 1;  let b = 2
来源：http://dali.redwolf501.top/Article/details/gt2ygyygdnl.html

[T18] Swift：字符串插值
来源：http://dali.cdnleiting.top/Article/details/gt2lgxxmqsu.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2kcviqdyg.html

[T19] Swift：可选绑定
来源：http://dali.hfpthk.cn/Article/details/gt2ymqwvlyg.html

if let n = opt { print(n) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xjidizya.html

[T20] Swift：数组操作
来源：http://dali.wangshuangyany.cn/Article/details/gt2fzaybhic.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.guowangkeji.top/Article/details/gt2fjhpovaa.html

[T21] Swift：遍历
来源：http://dali.cheryme.top/Article/details/gt2hupgxzow.html

for x in a { print(x) }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vcwufjkw.html

[T22] Swift：字典
来源：http://dali.tianlin.xyz/Article/details/gt2uunbgkmp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yanxiufei.cn/Article/details/gt2vsrmydqk.html

[T23] Swift：函数
来源：http://dali.shzxlz.cn/Article/details/gt2ocpmxvkg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hnxiangtu.top/Article/details/gt2aovucsqp.html

[T24] Swift：闭包
来源：http://dali.cashguo.top/Article/details/gt2aitwjmjq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wkxssvvu.html

[T25] Swift：结构体
来源：http://dali.zhengqikj.top/Article/details/gt2gmhluzgx.html

struct P { var x: Int }
来源：http://dali.yvedp.cn/Article/details/gt2ebfyotky.html

[T26] Swift：类与重写
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mktoysrt.html

class A: Base { override func f() {} }
来源：http://dali.havefunace.top/Article/details/gt2zrorlpxp.html

[T27] Swift：错误处理
来源：http://dali.mhx1999.top/Article/details/gt2rzynptuu.html

do { try f() } catch { print(error) }
来源：http://dali.wangdashe.top/Article/details/gt2bnqqfero.html

[T28] Swift：枚举
来源：http://dali.xylfe.cn/Article/details/gt2cxkiruvo.html

enum Color { case red, green }
来源：http://dali.zhengqikj.top/Article/details/gt2sfsmrkbo.html

[T29] Swift：guard 提前返回
来源：http://dali.0kj1m.cn/Article/details/gt2eveqwupu.html

guard let x = opt else { return }
来源：http://dali.jyoumei.cn/Article/details/gt2xlhuznce.html

[T30] Swift：协议
来源：http://dali.svipenyu.cn/Article/details/gt2lomcccue.html

protocol Shape { func area() -> Double }
来源：http://dali.pycfn.com/Article/details/gt2onzcuous.html

[T31] Lua：Hello World
来源：http://dali.tianlin.xyz/Article/details/gt2ytvwmoue.html

print("Hello")
来源：http://dali.zhiwuduotai.top/Article/details/gt2uaemekmr.html

[T32] Lua：局部变量
来源：http://dali.aizwys.cn/Article/details/gt2zvddzqcy.html

local a = 1
来源：http://dali.tanke756.top/Article/details/gt2wxuudeut.html

[T33] Lua：表（数组）
来源：http://dali.ehwqpu.com/Article/details/gt2vddawzhz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xinyue.icu/Article/details/gt2zihitwqy.html

[T34] Lua：遍历表
来源：http://dali.0kj1m.cn/Article/details/gt2ibwkzapd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.tian-w.cn/Article/details/gt2misogrtl.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2xvetshvo.html

local d = { a = 1 };  d.b = 2
来源：http://dali.redwolf501.top/Article/details/gt2wosouutn.html

[T36] Lua：函数
来源：http://dali.pycfn.com/Article/details/gt2ljavnvra.html

function add(a, b) return a + b end
来源：http://dali.vqdsnc.cn/Article/details/gt2yquuwafy.html

[T37] Lua：字符串拼接
来源：http://dali.redwolf501.top/Article/details/gt2avegztke.html

"a" .. "b"
来源：http://dali.chenjidiqi.icu/Article/details/gt2qfywykpq.html

[T38] Lua：条件
来源：http://dali.quarkkingdee.top/Article/details/gt2mwbdyktf.html

if x > 0 then print("正") end
来源：http://dali.andypj.xyz/Article/details/gt2wkyofokq.html

[T39] Lua：模式匹配
来源：http://dali.yvedp.cn/Article/details/gt2gtizqgsi.html

string.find(s, "%d+")
来源：http://dali.smart0.xyz/Article/details/gt2bboltuig.html

[T40] Lua：元表
来源：http://dali.wangshuangyany.cn/Article/details/gt2uwnfprnk.html

setmetatable({}, { __index = base })
来源：http://dali.iojbl.cn/Article/details/gt2xbvzivmh.html

[T41] Perl：Hello World
来源：http://dali.ybcxt.top/Article/details/gt2noezgcio.html

print "Hello\n";
来源：http://dali.guowangkeji.top/Article/details/gt2wwxppjuo.html

[T42] Perl：变量类型
来源：http://dali.chenjidiqi.icu/Article/details/gt2jwycrdza.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.gaohongyu789.top/Article/details/gt2afsjcqjy.html

[T43] Perl：字符串插值
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nsjimqdo.html

"值: $a"
来源：http://dali.daria6918.cn/Article/details/gt2wvvtpvmm.html

[T44] Perl：条件
来源：http://dali.yongpay.top/Article/details/gt2elhhegqh.html

if ($a > 0) { print "正"; }
来源：http://dali.cqqwz.cn/Article/details/gt2tpuqwmkq.html

[T45] Perl：数组遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vrqhzxmx.html

for my $x (@arr) { print $x; }
来源：http://dali.bjfxy.top/Article/details/gt2nlpojdhl.html

[T46] Perl：哈希操作
来源：http://dali.fzhhl.top/Article/details/gt2hwdiwlxa.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.nanxinkj.top/Article/details/gt2eynxpurj.html

[T47] Perl：正则捕获
来源：http://dali.c1oappe.top/Article/details/gt2chmznvdq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yueranfly.top/Article/details/gt2tityzzkc.html

[T48] Perl：正则替换
来源：http://dali.hnqzz.top/Article/details/gt2nbfpaujj.html

$s =~ s/old/new/g;
来源：http://dali.jqgfzy.top/Article/details/gt2ngugigdc.html

[T49] Perl：函数
来源：http://dali.vqdsnc.cn/Article/details/gt2xftdafuy.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yonumen.top/Article/details/gt2iemjuwyn.html

[T50] Perl：逐行读文件
来源：http://dali.jinqigufen.top/Article/details/gt2lgpbgaws.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.nwbrower.top/Article/details/gt2crujncyc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2zgwaylsf.html

[T51] Scala：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gt2pdfhgodx.html

println("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xvgkrcja.html

[T52] Scala：变量
来源：http://dali.meibo888.top/Article/details/gt2mknhjury.html

val a = 1;  var b = 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pdxkpiwa.html

[T53] Scala：字符串插值
来源：http://dali.tian-w.cn/Article/details/gt2twbzxpqi.html

s"值: $b"
来源：http://dali.jqgufenzy.top/Article/details/gt2wwdcqols.html

[T54] Scala：集合映射
来源：http://dali.zhixingplan.top/Article/details/gt2romyjllz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shuidangran.top/Article/details/gt2bnacbvni.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2etwbmqgv.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.guowangkeji.top/Article/details/gt2oeazwzxg.html

[T56] Scala：样例类
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fugzwtnm.html

case class User(name: String, age: Int)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lezpcnqz.html

[T57] Scala：模式匹配
来源：http://dali.ehwqpu.com/Article/details/gt2drgoouyk.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.316326.xyz/Article/details/gt2npqyrbgu.html

[T58] Scala：函数定义
来源：http://dali.nanxinkj.top/Article/details/gt2zqfdafrx.html


<!-- 参考信息 -->