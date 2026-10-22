代发 wailian999

ssh user@host 'uptime'
来源：http://dali.pengpengdd.cyou/Article/details/gt2ulnvvnvf.html

[R58] 下载文件
来源：http://dali.gzhubu.top/Article/details/gt2cmnrctte.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jinqigufen.top/Article/details/gt2guwqtglv.html

[R59] 发 POST JSON
来源：http://dali.bjfxy.top/Article/details/gt2zbaldgnt.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ppjwa.cn/Article/details/gt2dpgteldw.html

[R60] 只看 HTTP 状态码
来源：http://dali.cdnleiting.top/Article/details/gt2pypcggaq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jqgufenzy.top/Article/details/gt2qrwybmqz.html

[R61] 磁盘占用
来源：http://dali.birdmap.top/Article/details/gt2ncmmcngb.html

df -h;  du -sh *
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tktkjiof.html

[R62] 找最占空间的文件
来源：http://dali.birdmap.top/Article/details/gt2iqoqsjbc.html

du -ah . | sort -rh | head -10
来源：http://dali.guowangkeji.top/Article/details/gt2eqfemlns.html

[R63] 内存与进程
来源：http://dali.wangdashe.top/Article/details/gt2wfufjkqt.html

free -h;  ps aux | grep nginx
来源：http://dali.snrcjt.cn/Article/details/gt2jzrkzcbg.html

[R64] 结束进程
来源：http://dali.cheryme.top/Article/details/gt2npkrfvyl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhengqikj.top/Article/details/gt2inpswaio.html

[R65] 查看端口占用
来源：http://dali.bjfxy.top/Article/details/gt2dddnmkpp.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jqgfzy.top/Article/details/gt2asubrgtl.html

[R66] 定时任务
来源：http://dali.xuanzx.com/Article/details/gt2uopzjtci.html

crontab -e;  crontab -l
来源：http://dali.bjfxy.top/Article/details/gt2qecoudqv.html

[R67] 生成随机十六进制串
来源：http://dali.zhoulong.xyz/Article/details/gt2pmbuenho.html

openssl rand -hex 16
来源：http://dali.andypj.xyz/Article/details/gt2xcrkejcm.html

[R68] 计算文件校验值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dkvhigkr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jqgfzy.top/Article/details/gt2gpdlebkv.html

[R69] 生成随机密码
来源：http://dali.yongpay.top/Article/details/gt2tjudxdmm.html

head -c 16 /dev/urandom | base64
来源：http://dali.havefunace.top/Article/details/gt2qdnfuert.html

[R70] 时间戳与互转
来源：http://dali.yonumen.top/Article/details/gt2nmrtbwbz.html

date +%s;  date -d @1700000000
来源：http://dali.svipenyu.cn/Article/details/gt2prngbmrj.html

[R71] 日期格式化
来源：http://dali.jyoumei.cn/Article/details/gt2bwlhpyuk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.feifeiyinyue.top/Article/details/gt2ucbrswvo.html

[R72] 等待端口就绪
来源：http://dali.cdnleiting.top/Article/details/gt2ffzagmsn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.kuanghao11.cn/Article/details/gt2smqtmuzr.html

[R73] 分割大日志
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iubcxrdq.html

split -l 1000 big.log part_
来源：http://dali.9152youxi.cn/Article/details/gt2lbdyxpdk.html

[R74] 批量重命名
来源：http://dali.316326.xyz/Article/details/gt2hebcckap.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ttvawfgf.html

[R75] 导出环境变量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pscoqkyu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.mhx1999.top/Article/details/gt2aybqwimz.html

[R76] 使用临时文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2jyognjox.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cucudq.cn/Article/details/gt2asmuunai.html

[R77] 读取用户输入
来源：http://dali.kuanghao11.cn/Article/details/gt2fahgazid.html

read -rp "请输入: " ans
来源：http://dali.sweek.top/Article/details/gt2bkamsxgg.html

[R78] 交互式菜单
来源：http://dali.pengpengdd.cyou/Article/details/gt2aruohpck.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sysykeji.top/Article/details/gt2yskhnfsh.html

[R79] 解析命令行选项
来源：http://dali.gaohongyu789.top/Article/details/gt2iwjdeqan.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zdqjudy.top/Article/details/gt2jwlgvfaq.html

[R80] 查看脚本执行耗时
来源：http://dali.shangyingyoupin.top/Article/details/gt2voxiuhla.html

time ./run.sh
来源：http://dali.cqqwz.cn/Article/details/gt2pmrjtbeg.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2gmtmxvod.html

S. C / C++ 专题
来源：http://dali.jyoumei.cn/Article/details/gt2sbibebgt.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2fqwucaiu.html

[S01] C：Hello World
来源：http://dali.mhx1999.top/Article/details/gt2aorzaeic.html

#include <stdio.h>
来源：http://dali.shuidangran.top/Article/details/gt2erpdfkwe.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.daria6918.cn/Article/details/gt2gmwswnxz.html

[S02] C：变量与格式化输出
来源：http://dali.yongpay.top/Article/details/gt2ikhljtzv.html

int a = 10; printf("%d\n", a);
来源：http://dali.snrcjt.cn/Article/details/gt2ftvetdqy.html

[S03] C：读入整数
来源：http://dali.wangdashe.top/Article/details/gt2hsgerlep.html

int x; scanf("%d", &x);
来源：http://dali.fzhhl.top/Article/details/gt2nslmbtwr.html

[S04] C：字符串复制
来源：http://dali.guowangkeji.top/Article/details/gt2oyvxznvc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gotoacloud.top/Article/details/gt2fquhzzot.html

[S05] C：字符串长度
来源：http://dali.shzxlz.cn/Article/details/gt2wcgrvuxr.html

strlen(s)
来源：http://dali.gzhubu.top/Article/details/gt2zfrqxjjx.html

[S06] C：字符串比较
来源：http://dali.tianlin.xyz/Article/details/gt2kvfjdyxf.html

strcmp(a, b) == 0
来源：http://dali.sysykeji.top/Article/details/gt2ktlcqbza.html

[S07] C：数组遍历求和
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vfydwinr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.wangshuangyany.cn/Article/details/gt2yuzrnqtj.html

[S08] C：动态内存分配与释放
来源：http://dali.mhx1999.top/Article/details/gt2lxcqewhw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.c1oappe.top/Article/details/gt2tphqiytv.html

[S09] C：结构体定义与初始化
来源：http://dali.zycfv.cn/Article/details/gt2wilxekia.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.daria6918.cn/Article/details/gt2bxgpqtei.html

[S10] C：指针与解引用
来源：http://dali.feifeiyinyue.top/Article/details/gt2hpsqnbfp.html

int *p = &a;  *p = 5;
来源：http://dali.hnxiangtu.top/Article/details/gt2ypmjwsvx.html

[S11] C：逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mhslrfeb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.pengpengdd.cyou/Article/details/gt2trivgktu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jianghu66.top/Article/details/gt2ltyindjk.html

fclose(f);
来源：http://dali.yuanzhike.top/Article/details/gt2dolakqxb.html

[S12] C：写文件
来源：http://dali.daria6918.cn/Article/details/gt2cnqyqqcz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.pycfn.com/Article/details/gt2ilzhcuez.html

[S13] C：宏定义
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dmjxgegf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.birdmap.top/Article/details/gt2bpndakph.html

[S14] C：枚举
来源：http://dali.yueranfly.top/Article/details/gt2ldzrqwdv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xziqi.cn/Article/details/gt2pfdaftqb.html

[S15] C：类型转换
来源：http://dali.316326.xyz/Article/details/gt2czhrhhrf.html

(double) a / b
来源：http://dali.daria6918.cn/Article/details/gt2gptpqdwk.html

[S16] C：位操作置位
来源：http://dali.jianghu66.top/Article/details/gt2irneykdd.html

x |= (1 << 3);
来源：http://dali.gotoacloud.top/Article/details/gt2ljsyzhvt.html

[S17] C：安全拼接字符串
来源：http://dali.xinyue.icu/Article/details/gt2jpqvmtms.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ivvv.top/Article/details/gt2jdqxgkxg.html

[S18] C：命令行参数
来源：http://dali.guowangkeji.top/Article/details/gt2ymeedfif.html

int main(int argc, char **argv)
来源：http://dali.fengsongda.top/Article/details/gt2ceqqwagc.html

[S19] C：快速排序
来源：http://dali.xuetiantiany.cn/Article/details/gt2ylxhwmxn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yangfankeji.com/Article/details/gt2hwgyntwk.html

[S20] C：二分查找
来源：http://dali.xinyue.icu/Article/details/gt2hchhfhrg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uhjcepge.html

[S21] C：字符类别判断
来源：http://dali.sysykeji.top/Article/details/gt2hwnqjibi.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.andypj.xyz/Article/details/gt2wxjylaxx.html

[S22] C：字符串转数字
来源：http://dali.zhoulong.xyz/Article/details/gt2szvfdrqi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cashguo.top/Article/details/gt2mockozii.html

[S23] C：随机数
来源：http://dali.iojbl.cn/Article/details/gt2voeyikwp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sxryk.cn/Article/details/gt2aubeuehk.html

[S24] C：获取本地时间
来源：http://dali.sysykeji.top/Article/details/gt2czctqlzw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hfpthk.cn/Article/details/gt2hkgyokan.html

[S25] C：内存拷贝
来源：http://dali.jqgufenzy.top/Article/details/gt2utikevtk.html

memcpy(dst, src, n);
来源：http://dali.daria6918.cn/Article/details/gt2wvztzjxs.html

[S26] C：内存清零
来源：http://dali.yj20258.top/Article/details/gt2xrdyzpoa.html

memset(a, 0, sizeof a);
来源：http://dali.chenlongwang.top/Article/details/gt2trqpxegr.html

[S27] C：定义常量
来源：http://dali.jinqigfzy.top/Article/details/gt2ygxfozqe.html

const double PI = 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gt2kzdsrldm.html

[S28] C：静态变量
来源：http://dali.jqgfzy.top/Article/details/gt2mlfqtwby.html

static int counter = 0;
来源：http://dali.zdqjudy.top/Article/details/gt2bmzxfxxr.html

[S29] C：变参函数
来源：http://dali.hnxiangtu.top/Article/details/gt2ioowuwzn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yuxming.cn/Article/details/gt2doechtoi.html

[S30] C：头文件保护
来源：http://dali.aizwys.cn/Article/details/gt2wvcalxgd.html

#ifndef X_H
来源：http://dali.jianghu66.top/Article/details/gt2whdhyfqc.html

#define X_H
来源：http://dali.ydzc1.top/Article/details/gt2dreyprud.html

#endif
来源：http://dali.sxryk.cn/Article/details/gt2vfhuiqel.html

[S31] C++：Hello World
来源：http://dali.9152youxi.cn/Article/details/gt2sqcxqyll.html

#include <iostream>
来源：http://dali.zhongyouzk.top/Article/details/gt2uujnydtr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.9152youxi.cn/Article/details/gt2xwvbubru.html

[S32] C++：字符串
来源：http://dali.sxryk.cn/Article/details/gt2dzsqcdyz.html

std::string s = "hi";  s += "!";
来源：http://dali.nanxuanxn.top/Article/details/gt2fnmcprwd.html

[S33] C++：vector 增删
来源：http://dali.gaohongyu789.top/Article/details/gt2jmgrbpxq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shzxlz.cn/Article/details/gt2ovawcuxo.html

[S34] C++：遍历 vector
来源：http://dali.jqgufenzy.top/Article/details/gt2qnrvaojm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hgdwwhxo.html

[S35] C++：map
来源：http://dali.sufxvd.cn/Article/details/gt2wuzbetgs.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gt2jibuildt.html

[S36] C++：unordered_map
来源：http://dali.wangshuangyany.cn/Article/details/gt2tagrmqjg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.bjfxy.top/Article/details/gt2yzsqsuxj.html

[S37] C++：set
来源：http://dali.shuidangran.top/Article/details/gt2ggsphppb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wrseewlo.html

[S38] C++：排序
来源：http://dali.xinyue.icu/Article/details/gt2ggjpxete.html

std::sort(v.begin(), v.end());
来源：http://dali.dashuyun.cn/Article/details/gt2ewwonxzw.html

[S39] C++：自定义比较器排序
来源：http://dali.svipenyu.cn/Article/details/gt2qringypm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.9152youxi.cn/Article/details/gt2eqkzwzbj.html

[S40] C++：查找元素
来源：http://dali.yvedp.cn/Article/details/gt2afdxitqu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.iojbl.cn/Article/details/gt2jqaqgfex.html

[S41] C++：类与构造函数
来源：http://dali.yongpay.top/Article/details/gt2cobpguul.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cheryme.top/Article/details/gt2xarrpxfx.html

[S42] C++：继承与虚函数
来源：http://dali.pycfn.com/Article/details/gt2hgzqykhn.html

class B : public Base { public: void f() override {} };
来源：http://dali.cashguo.top/Article/details/gt2iwpjazlq.html

[S43] C++：智能指针
来源：http://dali.jinqigufen.top/Article/details/gt2vlppncuc.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2xytthbjc.html

[S44] C++：引用传参
来源：http://dali.jqgfzy.top/Article/details/gt2fwbtjomt.html

void inc(int &x) { ++x; }
来源：http://dali.fengsongda.top/Article/details/gt2sewiybve.html

[S45] C++：lambda
来源：http://dali.hnxiangtu.top/Article/details/gt2pakzqccx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ybcxt.top/Article/details/gt2wmkxxkgx.html

[S46] C++：函数模板
来源：http://dali.yueranfly.top/Article/details/gt2rbpnkaec.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qzwmhpup.html

[S47] C++：结构化绑定遍历
来源：http://dali.hfpthk.cn/Article/details/gt2eiwbixnn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2jhneustk.html

[S48] C++：逐行读文件
来源：http://dali.yonumen.top/Article/details/gt2umpkainm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bayepyez.html

while (std::getline(in, line)) { }
来源：http://dali.hammf.cn/Article/details/gt2mdeemfid.html

[S49] C++：写文件
来源：http://dali.hnqzz.top/Article/details/gt2kepevsya.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.9152youxi.cn/Article/details/gt2lourwfjr.html

[S50] C++：格式化数字
来源：http://dali.hywenlv.cn/Article/details/gt2eafuymzl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gt2crzgecce.html

[S51] C++：显式类型转换
来源：http://dali.gaohongyu789.top/Article/details/gt2nvvbbhzc.html

static_cast<double>(a) / b
来源：http://dali.tanke756.top/Article/details/gt2hsucgyup.html

[S52] C++：const 与 noexcept
来源：http://dali.ppjwa.cn/Article/details/gt2jwlnxkjn.html

int size() const noexcept { return n_; }
来源：http://dali.jinqigufen.top/Article/details/gt2yugqdgpx.html

[S53] C++：移动语义
来源：http://dali.guowangkeji.top/Article/details/gt2dgdvcrqa.html

std::vector<int> w = std::move(v);
来源：http://dali.snrcjt.cn/Article/details/gt2tecgnqbh.html

[S54] C++：异常处理
来源：http://dali.shzxlz.cn/Article/details/gt2jqfqnura.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ehwqpu.com/Article/details/gt2xjtapzfw.html

[S55] C++：结构化绑定
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cejlraiq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yongpay.top/Article/details/gt2kzmovnzd.html

[S56] C++：optional
来源：http://dali.shangyingyoupin.top/Article/details/gt2iyudkduk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.svipenyu.cn/Article/details/gt2sowxkqbj.html

[S57] C++：编译期常量
来源：http://dali.sysykeji.top/Article/details/gt2kwpxlchw.html

constexpr int N = 10;
来源：http://dali.sufxvd.cn/Article/details/gt2ppwnheri.html

[S58] C++：命名空间
来源：http://dali.pengpengdd.cyou/Article/details/gt2ashdkewb.html

namespace ns { int f() { return 1; } }
来源：http://dali.daria6918.cn/Article/details/gt2luhzakwy.html

[S59] C++：静态断言
来源：http://dali.redwolf501.top/Article/details/gt2ukfbsxet.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jianghu66.top/Article/details/gt2yebqgwzf.html

[S60] C++：遍历并删除元素
来源：http://dali.guannengcc.top/Article/details/gt2xbuqsanp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shzxlz.cn/Article/details/gt2cfiqgelw.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2bvuivsly.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.fzhhl.top/Article/details/gt2pirafcrn.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2lepahift.html

[T01] Kotlin：Hello World
来源：http://dali.yuanzhike.top/Article/details/gt2qxrerybn.html

println("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gt2apciwuvi.html

[T02] Kotlin：变量
来源：http://dali.meibo888.top/Article/details/gt2izhflhbd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xuanzx.com/Article/details/gt2acrjdfwk.html

[T03] Kotlin：字符串模板
来源：http://dali.yonumen.top/Article/details/gt2ttqyteba.html

"值: $b"
来源：http://dali.redwolf501.top/Article/details/gt2bnsagbku.html

[T04] Kotlin：空安全
来源：http://dali.316326.xyz/Article/details/gt2gcqndtgs.html

val n: String? = null;  n?.length
来源：http://dali.chenzaomai.com/Article/details/gt2bsmflnef.html

[T05] Kotlin：when 表达式
来源：http://dali.yueranfly.top/Article/details/gt2dlnxzohu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.316326.xyz/Article/details/gt2npmcjvpx.html

[T06] Kotlin：集合映射
来源：http://dali.andypj.xyz/Article/details/gt2hohzlvct.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.haohaochexian.top/Article/details/gt2ijcetwqk.html

[T07] Kotlin：集合过滤
来源：http://dali.hammf.cn/Article/details/gt2scjeiiye.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.c1oappe.top/Article/details/gt2aawtfsoe.html

[T08] Kotlin：数据类
来源：http://dali.cheryme.top/Article/details/gt2blxqunyw.html

data class User(val name: String, val age: Int)
来源：http://dali.sweek.top/Article/details/gt2glrxpdxm.html

[T09] Kotlin：扩展函数
来源：http://dali.gotoacloud.top/Article/details/gt2etmsluww.html

fun String.exclaim() = this + "!"
来源：http://dali.gotoacloud.top/Article/details/gt2lcdjzuzc.html

[T10] Kotlin：默认参数
来源：http://dali.aibaodan.cn/Article/details/gt2eatyezug.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xylfe.cn/Article/details/gt2tnxtptey.html

[T11] Kotlin：协程
来源：http://dali.aizwys.cn/Article/details/gt2zgdnxxbe.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhixingplan.top/Article/details/gt2yfvtxvhg.html

[T12] Kotlin：解构声明
来源：http://dali.tanke756.top/Article/details/gt2feewuxpp.html

val (a, b) = Pair(1, 2)
来源：http://dali.cheryme.top/Article/details/gt2vharfpiy.html

[T13] Kotlin：只读 Map
来源：http://dali.svipenyu.cn/Article/details/gt2lhhdiqnn.html

val m = mapOf("a" to 1)
来源：http://dali.nanxinkj.top/Article/details/gt2csxinlyp.html

[T14] Kotlin：循环
来源：http://dali.zhiwuduotai.top/Article/details/gt2zuhmaknn.html

for (i in 1..10) println(i)
来源：http://dali.c1oappe.top/Article/details/gt2glylgiah.html

[T15] Kotlin：接口
来源：http://dali.yj202588.top/Article/details/gt2yqdabvvk.html

interface Shape { fun area(): Double }
来源：http://dali.havefunace.top/Article/details/gt2bhnmvhpj.html

[T16] Swift：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gt2krganhun.html

print("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gt2wtttwvvc.html

[T17] Swift：变量与常量
来源：http://dali.dianchejie.cn/Article/details/gt2zamkryky.html

var a = 1;  let b = 2
来源：http://dali.fzhhl.top/Article/details/gt2qssyursb.html

[T18] Swift：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rgpgpikq.html

"值: \(b)"
来源：http://dali.gogol.net.cn/Article/details/gt2nljhgpog.html

[T19] Swift：可选绑定
来源：http://dali.yuxming.cn/Article/details/gt2ubyfxpcm.html

if let n = opt { print(n) }
来源：http://dali.havefunace.top/Article/details/gt2xxlltpdo.html

[T20] Swift：数组操作
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fyhgomtu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jqgfzy.top/Article/details/gt2blsjzfjt.html

[T21] Swift：遍历
来源：http://dali.pycfn.com/Article/details/gt2jwzxpkxo.html

for x in a { print(x) }
来源：http://dali.jiagoushi.top/Article/details/gt2ghafldyt.html

[T22] Swift：字典
来源：http://dali.hammf.cn/Article/details/gt2winrdgcr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gzhubu.top/Article/details/gt2qcesasnx.html

[T23] Swift：函数
来源：http://dali.cheryme.top/Article/details/gt2xtxtiacs.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.nanxinkj.top/Article/details/gt2mkrvclxn.html

[T24] Swift：闭包
来源：http://dali.haohaochexian.top/Article/details/gt2byxsfnme.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ydzc1.top/Article/details/gt2ksvxgdbe.html

[T25] Swift：结构体
来源：http://dali.wangshuangyany.cn/Article/details/gt2ozwxqhbi.html

struct P { var x: Int }
来源：http://dali.cashguo.top/Article/details/gt2qnhmompz.html

[T26] Swift：类与重写
来源：http://dali.zycfv.cn/Article/details/gt2glnxypwz.html

class A: Base { override func f() {} }
来源：http://dali.havefunace.top/Article/details/gt2jolavdlh.html

[T27] Swift：错误处理
来源：http://dali.svipenyu.cn/Article/details/gt2znwdlyqg.html

do { try f() } catch { print(error) }
来源：http://dali.cashguo.top/Article/details/gt2svrgmrow.html

[T28] Swift：枚举
来源：http://dali.birdmap.top/Article/details/gt2svmbmpjy.html

enum Color { case red, green }
来源：http://dali.ppjwa.cn/Article/details/gt2kziakpbd.html

[T29] Swift：guard 提前返回
来源：http://dali.gaohongyu789.top/Article/details/gt2rwqhjnxj.html

guard let x = opt else { return }
来源：http://dali.hnxiangtu.top/Article/details/gt2mfkahfcn.html

[T30] Swift：协议
来源：http://dali.cdnleiting.top/Article/details/gt2ycdvmvym.html

protocol Shape { func area() -> Double }
来源：http://dali.meibo888.top/Article/details/gt2olexzdzw.html

[T31] Lua：Hello World
来源：http://dali.hnqzz.top/Article/details/gt2rhtieqyj.html

print("Hello")
来源：http://dali.hfpthk.cn/Article/details/gt2shunbcvh.html

[T32] Lua：局部变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2afdrecdp.html

local a = 1
来源：http://dali.xuanzx.com/Article/details/gt2cbohsgdp.html

[T33] Lua：表（数组）
来源：http://dali.yonumen.top/Article/details/gt2fyrfsdsa.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.0kj1m.cn/Article/details/gt2sfwiepgd.html

[T34] Lua：遍历表
来源：http://dali.zhoulong.xyz/Article/details/gt2vyvipizx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.gaohongyu789.top/Article/details/gt2dkclkdzj.html

[T35] Lua：字典表
来源：http://dali.gaohongyu789.top/Article/details/gt2xzlkqlce.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yj20258888.top/Article/details/gt2weifumrc.html

[T36] Lua：函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2skbaqaaf.html

function add(a, b) return a + b end
来源：http://dali.yuxming.cn/Article/details/gt2joufqbbz.html

[T37] Lua：字符串拼接
来源：http://dali.andypj.xyz/Article/details/gt2fmftecyb.html

"a" .. "b"
来源：http://dali.jinqigufen.top/Article/details/gt2uhzkzmol.html

[T38] Lua：条件
来源：http://dali.gzhubu.top/Article/details/gt2gllodrky.html

if x > 0 then print("正") end
来源：http://dali.nanxinkj.top/Article/details/gt2nsykhxqb.html

[T39] Lua：模式匹配
来源：http://dali.daria6918.cn/Article/details/gt2dolpdswv.html

string.find(s, "%d+")
来源：http://dali.dashuyun.cn/Article/details/gt2cpxhcdaj.html

[T40] Lua：元表
来源：http://dali.dashuyun.cn/Article/details/gt2ehmgoglp.html

setmetatable({}, { __index = base })
来源：http://dali.hongshengwenyu.top/Article/details/gt2elzpsses.html

[T41] Perl：Hello World
来源：http://dali.yj20258.top/Article/details/gt2wfoqadcn.html

print "Hello\n";
来源：http://dali.chenzaomai.com/Article/details/gt2jyzqppqm.html

[T42] Perl：变量类型
来源：http://dali.fzhhl.top/Article/details/gt2xbkmheqm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.smart0.xyz/Article/details/gt2qhribvcc.html

[T43] Perl：字符串插值
来源：http://dali.hnxiangtu.top/Article/details/gt2mxpyucoq.html

"值: $a"
来源：http://dali.shangyingyoupin.top/Article/details/gt2cdjphwni.html

[T44] Perl：条件
来源：http://dali.0kj1m.cn/Article/details/gt2xjrokghu.html

if ($a > 0) { print "正"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kuwzmkmu.html

[T45] Perl：数组遍历
来源：http://dali.c1oappe.top/Article/details/gt2akghfyvl.html

for my $x (@arr) { print $x; }
来源：http://dali.kuanghao11.cn/Article/details/gt2gzpwcroc.html

[T46] Perl：哈希操作
来源：http://dali.haohaochexian.top/Article/details/gt2buihufkt.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.fengsongda.top/Article/details/gt2fxegezdg.html

[T47] Perl：正则捕获
来源：http://dali.cucudq.cn/Article/details/gt2rusmghwi.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhixingplan.top/Article/details/gt2gbvglfgf.html

[T48] Perl：正则替换
来源：http://dali.birdmap.top/Article/details/gt2yztgwpmf.html

$s =~ s/old/new/g;
来源：http://dali.xinyue.icu/Article/details/gt2xfljosll.html

[T49] Perl：函数
来源：http://dali.daxiang520.top/Article/details/gt2gaxmhvfr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yuanzhike.top/Article/details/gt2ebleqxqm.html

[T50] Perl：逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gt2xrbpqaop.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xylfe.cn/Article/details/gt2szswrrml.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.nanxinkj.top/Article/details/gt2ospoqnhe.html

[T51] Scala：Hello World
来源：http://dali.sweek.top/Article/details/gt2auanwtqw.html

println("Hello")
来源：http://dali.9152youxi.cn/Article/details/gt2mkmalohv.html

[T52] Scala：变量
来源：http://dali.zycfv.cn/Article/details/gt2qdhkirur.html

val a = 1;  var b = 2
来源：http://dali.meibo888.top/Article/details/gt2adtnlfpa.html

[T53] Scala：字符串插值
来源：http://dali.tianlin.xyz/Article/details/gt2ljtqjujw.html

s"值: $b"
来源：http://dali.gotoacloud.top/Article/details/gt2gnkgplkk.html

[T54] Scala：集合映射
来源：http://dali.pycfn.com/Article/details/gt2sirijlcl.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jinqigfzy.top/Article/details/gt2tsvpkdmj.html

[T55] Scala：集合过滤
来源：http://dali.yuxming.cn/Article/details/gt2bsdlllox.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jqgfzy.top/Article/details/gt2brdbbgep.html

[T56] Scala：样例类
来源：http://dali.cucudq.cn/Article/details/gt2ogrjygmt.html

case class User(name: String, age: Int)
来源：http://dali.0kj1m.cn/Article/details/gt2mgvjkmyf.html

[T57] Scala：模式匹配
来源：http://dali.tian-w.cn/Article/details/gt2dnpjfndw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xziqi.cn/Article/details/gt2vxoypuce.html

[T58] Scala：函数定义
来源：http://dali.gotoacloud.top/Article/details/gt2ybymzuad.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.dianchejie.cn/Article/details/gt2zfejbgye.html

[T59] Scala：循环
来源：http://dali.tianlin.xyz/Article/details/gt2iaccrygt.html

for (i <- 1 to 10) println(i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sgegcsoq.html

[T60] Scala：折叠
来源：http://dali.yueranfly.top/Article/details/gt2ukskojbp.html


<!-- 参考信息 -->