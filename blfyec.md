代发 wailian999

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhoulong.xyz/Article/details/gt2zczworce.html

[R56] 远程拷贝
来源：http://dali.ehwqpu.com/Article/details/gt2rmpedbyi.html

scp file user@host:/path/
来源：http://dali.jyoumei.cn/Article/details/gt2depxeefo.html

[R57] 远程执行命令
来源：http://dali.xylfe.cn/Article/details/gt2avvelkhg.html

ssh user@host 'uptime'
来源：http://dali.jinqigufen.top/Article/details/gt2ojntndai.html

[R58] 下载文件
来源：http://dali.aibaodan.cn/Article/details/gt2gjyxejjk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.haohaochexian.top/Article/details/gt2ieboqewb.html

[R59] 发 POST JSON
来源：http://dali.hywenlv.cn/Article/details/gt2xcziovjj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jqgfzy.top/Article/details/gt2krvybylb.html

[R60] 只看 HTTP 状态码
来源：http://dali.dianchejie.cn/Article/details/gt2gpypjlgu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xuanzx.com/Article/details/gt2wcctiaxu.html

[R61] 磁盘占用
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vjupykds.html

df -h;  du -sh *
来源：http://dali.yueranfly.top/Article/details/gt2hxuwjtun.html

[R62] 找最占空间的文件
来源：http://dali.yj20258888.top/Article/details/gt2vgcsoyui.html

du -ah . | sort -rh | head -10
来源：http://dali.yj20258.top/Article/details/gt2toqnaeng.html

[R63] 内存与进程
来源：http://dali.yvedp.cn/Article/details/gt2fxkdjehc.html

free -h;  ps aux | grep nginx
来源：http://dali.jinqigfzy.top/Article/details/gt2khkyeczr.html

[R64] 结束进程
来源：http://dali.gaohongyu789.top/Article/details/gt2ejsiaejq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sweek.top/Article/details/gt2vlmvocuz.html

[R65] 查看端口占用
来源：http://dali.guannengcc.top/Article/details/gt2cadqrych.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ayhbvumw.html

[R66] 定时任务
来源：http://dali.jiagoushi.top/Article/details/gt2wvekncrn.html

crontab -e;  crontab -l
来源：http://dali.jlsjyb.cn/Article/details/gt2vtforakx.html

[R67] 生成随机十六进制串
来源：http://dali.ydzc1.top/Article/details/gt2eolpmklh.html

openssl rand -hex 16
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mgrkbort.html

[R68] 计算文件校验值
来源：http://dali.chenzaomai.com/Article/details/gt2pbagscsg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zdqjudy.top/Article/details/gt2ttzilcyd.html

[R69] 生成随机密码
来源：http://dali.zhoulong.xyz/Article/details/gt2gpzqugsh.html

head -c 16 /dev/urandom | base64
来源：http://dali.wangdashe.top/Article/details/gt2zexsbwef.html

[R70] 时间戳与互转
来源：http://dali.jlsjyb.cn/Article/details/gt2znpvzqga.html

date +%s;  date -d @1700000000
来源：http://dali.birdmap.top/Article/details/gt2pubalsgd.html

[R71] 日期格式化
来源：http://dali.daxiang520.top/Article/details/gt2bgpxtyeq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.0kj1m.cn/Article/details/gt2qfgvchok.html

[R72] 等待端口就绪
来源：http://dali.sweek.top/Article/details/gt2ofzqscnh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yj20258888.top/Article/details/gt2sxrrrxcw.html

[R73] 分割大日志
来源：http://dali.chenjidiqi.icu/Article/details/gt2gumwpvzz.html

split -l 1000 big.log part_
来源：http://dali.chenjidiqi.icu/Article/details/gt2qardadhd.html

[R74] 批量重命名
来源：http://dali.ydzc1.top/Article/details/gt2ykantzpg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.snrcjt.cn/Article/details/gt2ezffgchx.html

[R75] 导出环境变量
来源：http://dali.yvedp.cn/Article/details/gt2vakofjjd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2pmehlkzm.html

[R76] 使用临时文件
来源：http://dali.hywenlv.cn/Article/details/gt2brismfca.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hywenlv.cn/Article/details/gt2lxmvawly.html

[R77] 读取用户输入
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pzkmgfkw.html

read -rp "请输入: " ans
来源：http://dali.dashuyun.cn/Article/details/gt2firqjoau.html

[R78] 交互式菜单
来源：http://dali.pycfn.com/Article/details/gt2hhhibpyd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cashguo.top/Article/details/gt2iiorqnkd.html

[R79] 解析命令行选项
来源：http://dali.guowangkeji.top/Article/details/gt2hwqdjsmw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sysykeji.top/Article/details/gt2qzgdrxjp.html

[R80] 查看脚本执行耗时
来源：http://dali.ydzc1.top/Article/details/gt2whjqfhpj.html

time ./run.sh
来源：http://dali.haohaochexian.top/Article/details/gt2eovjpvpf.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2uzsrobxa.html

S. C / C++ 专题
来源：http://dali.cqqwz.cn/Article/details/gt2rtobeepn.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2hvpldmrd.html

[S01] C：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gt2fxntvrad.html

#include <stdio.h>
来源：http://dali.gogol.net.cn/Article/details/gt2ysssvkfw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.svipenyu.cn/Article/details/gt2mezkyavt.html

[S02] C：变量与格式化输出
来源：http://dali.shuidangran.top/Article/details/gt2yzdqxdwr.html

int a = 10; printf("%d\n", a);
来源：http://dali.xylfe.cn/Article/details/gt2idbyynwz.html

[S03] C：读入整数
来源：http://dali.zhengqikj.top/Article/details/gt2rcvvyvkw.html

int x; scanf("%d", &x);
来源：http://dali.shangyingyoupin.top/Article/details/gt2oqgzrpkh.html

[S04] C：字符串复制
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mrydlqak.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gotoacloud.top/Article/details/gt2qgvugrxr.html

[S05] C：字符串长度
来源：http://dali.316326.xyz/Article/details/gt2dqqgnklf.html

strlen(s)
来源：http://dali.jqgfzy.top/Article/details/gt2bxboczbi.html

[S06] C：字符串比较
来源：http://dali.cucudq.cn/Article/details/gt2ateuflvb.html

strcmp(a, b) == 0
来源：http://dali.yj20258.top/Article/details/gt2gswjbspv.html

[S07] C：数组遍历求和
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2efvxkwbv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ybcxt.top/Article/details/gt2bdgrkhrh.html

[S08] C：动态内存分配与释放
来源：http://dali.daxiang520.top/Article/details/gt2nuxfotjw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xuanzx.com/Article/details/gt2eboeavzj.html

[S09] C：结构体定义与初始化
来源：http://dali.yongpay.top/Article/details/gt2yfkciium.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shangyingyoupin.top/Article/details/gt2iehgxajj.html

[S10] C：指针与解引用
来源：http://dali.xuetiantiany.cn/Article/details/gt2fzryodgi.html

int *p = &a;  *p = 5;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rvxmhjrd.html

[S11] C：逐行读文件
来源：http://dali.fzhhl.top/Article/details/gt2pezrcknj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cashguo.top/Article/details/gt2yybqukap.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sxryk.cn/Article/details/gt2erjqhfww.html

fclose(f);
来源：http://dali.cashguo.top/Article/details/gt2urthqgoy.html

[S12] C：写文件
来源：http://dali.hywenlv.cn/Article/details/gt2mjkcbknv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ehwqpu.com/Article/details/gt2hcsecnbw.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2afbpoilc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.bjfxy.top/Article/details/gt2cquklzff.html

[S14] C：枚举
来源：http://dali.dashuyun.cn/Article/details/gt2eaiglflp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ndfgkdys.html

[S15] C：类型转换
来源：http://dali.guannengcc.top/Article/details/gt2jmhrfxgc.html

(double) a / b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hatwsfsk.html

[S16] C：位操作置位
来源：http://dali.chenlongwang.top/Article/details/gt2fuxbskue.html

x |= (1 << 3);
来源：http://dali.jqgufenzy.top/Article/details/gt2jrshhsck.html

[S17] C：安全拼接字符串
来源：http://dali.zycfv.cn/Article/details/gt2qggaphla.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cqqwz.cn/Article/details/gt2roxlrhfn.html

[S18] C：命令行参数
来源：http://dali.jqgfzy.top/Article/details/gt2dqiqxkwv.html

int main(int argc, char **argv)
来源：http://dali.yj20258.top/Article/details/gt2oyjlkvvq.html

[S19] C：快速排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kywlsupe.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lajizkyx.html

[S20] C：二分查找
来源：http://dali.xinyue.icu/Article/details/gt2ghujnnlz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.snrcjt.cn/Article/details/gt2qldiqqqt.html

[S21] C：字符类别判断
来源：http://dali.sufxvd.cn/Article/details/gt2nxoklnxa.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.haohaochexian.top/Article/details/gt2eydejvfm.html

[S22] C：字符串转数字
来源：http://dali.pycfn.com/Article/details/gt2boifobeo.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.fengsongda.top/Article/details/gt2cwifjghb.html

[S23] C：随机数
来源：http://dali.xuanzx.com/Article/details/gt2nsyyetxm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj202588.top/Article/details/gt2dsvjvolh.html

[S24] C：获取本地时间
来源：http://dali.yj202588.top/Article/details/gt2vinvaogu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.andypj.xyz/Article/details/gt2wyegippz.html

[S25] C：内存拷贝
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ybodyoas.html

memcpy(dst, src, n);
来源：http://dali.aizwys.cn/Article/details/gt2dbfawxpd.html

[S26] C：内存清零
来源：http://dali.zhengqikj.top/Article/details/gt2fjjwsxrw.html

memset(a, 0, sizeof a);
来源：http://dali.zhongyouzk.top/Article/details/gt2spbjggjy.html

[S27] C：定义常量
来源：http://dali.yuanzhike.top/Article/details/gt2znentdrw.html

const double PI = 3.14159;
来源：http://dali.aizwys.cn/Article/details/gt2bkltvher.html

[S28] C：静态变量
来源：http://dali.yj20258888.top/Article/details/gt2uewmrbhd.html

static int counter = 0;
来源：http://dali.yuxming.cn/Article/details/gt2lisgwtcg.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xwehjewi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shangyingyoupin.top/Article/details/gt2txmqyago.html

[S30] C：头文件保护
来源：http://dali.ivvv.top/Article/details/gt2scgaleof.html

#ifndef X_H
来源：http://dali.zhengqikj.top/Article/details/gt2ypyhkwcn.html

#define X_H
来源：http://dali.ivvv.top/Article/details/gt2ikwzxvgh.html

#endif
来源：http://dali.tian-w.cn/Article/details/gt2rzdikben.html

[S31] C++：Hello World
来源：http://dali.wangdashe.top/Article/details/gt2ieqtxllf.html

#include <iostream>
来源：http://dali.wangshuangyany.cn/Article/details/gt2heebwndy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yonumen.top/Article/details/gt2borcqiee.html

[S32] C++：字符串
来源：http://dali.haohaochexian.top/Article/details/gt2dppcrlfv.html

std::string s = "hi";  s += "!";
来源：http://dali.c1oappe.top/Article/details/gt2npsrmmkx.html

[S33] C++：vector 增删
来源：http://dali.yj20258.top/Article/details/gt2exrzluzi.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hnqzz.top/Article/details/gt2lniwbiim.html

[S34] C++：遍历 vector
来源：http://dali.cucudq.cn/Article/details/gt2prkycruj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.kuanghao11.cn/Article/details/gt2yruyykqj.html

[S35] C++：map
来源：http://dali.sweek.top/Article/details/gt2mfyougvv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zdqjudy.top/Article/details/gt2qpltgxtk.html

[S36] C++：unordered_map
来源：http://dali.hywenlv.cn/Article/details/gt2tmgmyvre.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.dashuyun.cn/Article/details/gt2ecfjcjnr.html

[S37] C++：set
来源：http://dali.havefunace.top/Article/details/gt2asrjilxq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhengqikj.top/Article/details/gt2jofjfnpt.html

[S38] C++：排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ahgxaxgu.html

std::sort(v.begin(), v.end());
来源：http://dali.tian-w.cn/Article/details/gt2shzerrle.html

[S39] C++：自定义比较器排序
来源：http://dali.vqdsnc.cn/Article/details/gt2cppdnnar.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sufxvd.cn/Article/details/gt2oxuahyeu.html

[S40] C++：查找元素
来源：http://dali.tanke756.top/Article/details/gt2rautmojn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.birdmap.top/Article/details/gt2frzyivpx.html

[S41] C++：类与构造函数
来源：http://dali.cucudq.cn/Article/details/gt2bmbgpmrp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hfpthk.cn/Article/details/gt2uqsyikxr.html

[S42] C++：继承与虚函数
来源：http://dali.haohaochexian.top/Article/details/gt2wwweogsj.html

class B : public Base { public: void f() override {} };
来源：http://dali.sysykeji.top/Article/details/gt2hhockwqt.html

[S43] C++：智能指针
来源：http://dali.hywenlv.cn/Article/details/gt2trgijidh.html

auto p = std::make_unique<int>(5);
来源：http://dali.ppjwa.cn/Article/details/gt2ulqlzpcv.html

[S44] C++：引用传参
来源：http://dali.xylfe.cn/Article/details/gt2lmoshlfs.html

void inc(int &x) { ++x; }
来源：http://dali.nanxinkj.top/Article/details/gt2hsquqgry.html

[S45] C++：lambda
来源：http://dali.sweek.top/Article/details/gt2jzmdjevu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yj20258888.top/Article/details/gt2qkszoarp.html

[S46] C++：函数模板
来源：http://dali.cdnleiting.top/Article/details/gt2rlawnkuj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yj20258888.top/Article/details/gt2lirlhyfs.html

[S47] C++：结构化绑定遍历
来源：http://dali.gzhubu.top/Article/details/gt2gejaibwa.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.nanxuanxn.top/Article/details/gt2ilvlpsag.html

[S48] C++：逐行读文件
来源：http://dali.meibo888.top/Article/details/gt2tyaunkys.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhongyouzk.top/Article/details/gt2lpnzcnrv.html

while (std::getline(in, line)) { }
来源：http://dali.xuetiantiany.cn/Article/details/gt2blbtwkrw.html

[S49] C++：写文件
来源：http://dali.yj20258888.top/Article/details/gt2iutqezep.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.nanxuanxn.top/Article/details/gt2fbggtwwl.html

[S50] C++：格式化数字
来源：http://dali.smart0.xyz/Article/details/gt2snnlvvfo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lfabejrk.html

[S51] C++：显式类型转换
来源：http://dali.zhixingplan.top/Article/details/gt2mhvuyjht.html

static_cast<double>(a) / b
来源：http://dali.yj20258888.top/Article/details/gt2oaezkhpq.html

[S52] C++：const 与 noexcept
来源：http://dali.c1oappe.top/Article/details/gt2ryclpsro.html

int size() const noexcept { return n_; }
来源：http://dali.dianchejie.cn/Article/details/gt2mozqjvcq.html

[S53] C++：移动语义
来源：http://dali.yonumen.top/Article/details/gt2bqhxidok.html

std::vector<int> w = std::move(v);
来源：http://dali.sweek.top/Article/details/gt2ybbsljtg.html

[S54] C++：异常处理
来源：http://dali.kuanghao11.cn/Article/details/gt2tfbekjjv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2myczwqfp.html

[S55] C++：结构化绑定
来源：http://dali.guowangkeji.top/Article/details/gt2cgkqleks.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.9152youxi.cn/Article/details/gt2lkzazzdp.html

[S56] C++：optional
来源：http://dali.quarkkingdee.top/Article/details/gt2brgzbhzl.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zdqjudy.top/Article/details/gt2xncaafpg.html

[S57] C++：编译期常量
来源：http://dali.pengpengdd.cyou/Article/details/gt2xlzplfuk.html

constexpr int N = 10;
来源：http://dali.sufxvd.cn/Article/details/gt2svghcagv.html

[S58] C++：命名空间
来源：http://dali.guannengcc.top/Article/details/gt2wvtussfb.html

namespace ns { int f() { return 1; } }
来源：http://dali.dashuyun.cn/Article/details/gt2bicxboyi.html

[S59] C++：静态断言
来源：http://dali.smart0.xyz/Article/details/gt2iepcfqyv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.chenzaomai.com/Article/details/gt2fputjbgd.html

[S60] C++：遍历并删除元素
来源：http://dali.316326.xyz/Article/details/gt2giwvnhzq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhengqikj.top/Article/details/gt2ksxvpxjn.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2widesaga.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.pengpengdd.cyou/Article/details/gt2apewgixp.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2qxdxlzeu.html

[T01] Kotlin：Hello World
来源：http://dali.sufxvd.cn/Article/details/gt2mtfrauih.html

println("Hello")
来源：http://dali.svipenyu.cn/Article/details/gt2tvlktvpv.html

[T02] Kotlin：变量
来源：http://dali.zhengqikj.top/Article/details/gt2bzsaquft.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jyoumei.cn/Article/details/gt2xxahmpnc.html

[T03] Kotlin：字符串模板
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bwrfkdzh.html

"值: $b"
来源：http://dali.aizwys.cn/Article/details/gt2pgddyvio.html

[T04] Kotlin：空安全
来源：http://dali.chenzaomai.com/Article/details/gt2hkvjphth.html

val n: String? = null;  n?.length
来源：http://dali.andypj.xyz/Article/details/gt2bzqaagqo.html

[T05] Kotlin：when 表达式
来源：http://dali.jlsjyb.cn/Article/details/gt2gealjfwr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.nanxinkj.top/Article/details/gt2koibhwmo.html

[T06] Kotlin：集合映射
来源：http://dali.jinqigfzy.top/Article/details/gt2jktooseb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.9152youxi.cn/Article/details/gt2jjtwithm.html

[T07] Kotlin：集合过滤
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hfifikia.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinqigfzy.top/Article/details/gt2bfvtrmvt.html

[T08] Kotlin：数据类
来源：http://dali.svipenyu.cn/Article/details/gt2gqepmfmw.html

data class User(val name: String, val age: Int)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2atsppnej.html

[T09] Kotlin：扩展函数
来源：http://dali.yangfankeji.com/Article/details/gt2vqmlavpo.html

fun String.exclaim() = this + "!"
来源：http://dali.meibo888.top/Article/details/gt2xxsupsvn.html

[T10] Kotlin：默认参数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2htqwzehx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jxrcehxf.html

[T11] Kotlin：协程
来源：http://dali.dianchejie.cn/Article/details/gt2kuuardov.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jinqigfzy.top/Article/details/gt2gmipylrl.html

[T12] Kotlin：解构声明
来源：http://dali.yonumen.top/Article/details/gt2czbfdltj.html

val (a, b) = Pair(1, 2)
来源：http://dali.svipenyu.cn/Article/details/gt2oixkezgh.html

[T13] Kotlin：只读 Map
来源：http://dali.gogol.net.cn/Article/details/gt2yzehtwvj.html

val m = mapOf("a" to 1)
来源：http://dali.andypj.xyz/Article/details/gt2tmvcfhxd.html

[T14] Kotlin：循环
来源：http://dali.cashguo.top/Article/details/gt2hofxkbqr.html

for (i in 1..10) println(i)
来源：http://dali.aibaodan.cn/Article/details/gt2clhleqym.html

[T15] Kotlin：接口
来源：http://dali.andypj.xyz/Article/details/gt2oaffabyd.html

interface Shape { fun area(): Double }
来源：http://dali.tian-w.cn/Article/details/gt2cuhzxmej.html

[T16] Swift：Hello World
来源：http://dali.chenlongwang.top/Article/details/gt2yyykmfoc.html

print("Hello")
来源：http://dali.gotoacloud.top/Article/details/gt2qapiclxv.html

[T17] Swift：变量与常量
来源：http://dali.gaohongyu789.top/Article/details/gt2tdpommrx.html

var a = 1;  let b = 2
来源：http://dali.ppjwa.cn/Article/details/gt2nagvyeli.html

[T18] Swift：字符串插值
来源：http://dali.chenlongwang.top/Article/details/gt2rudnncob.html

"值: \(b)"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vgcxcgrr.html

[T19] Swift：可选绑定
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fqgjmmvb.html

if let n = opt { print(n) }
来源：http://dali.chenzaomai.com/Article/details/gt2cqauctbx.html

[T20] Swift：数组操作
来源：http://dali.sweek.top/Article/details/gt2olfrwdzo.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.redwolf501.top/Article/details/gt2dafkximn.html

[T21] Swift：遍历
来源：http://dali.yj20258888.top/Article/details/gt2gxklrrxt.html

for x in a { print(x) }
来源：http://dali.guowangkeji.top/Article/details/gt2vjfoimex.html

[T22] Swift：字典
来源：http://dali.feifeiyinyue.top/Article/details/gt2yxjwoqkp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2btpeyzye.html

[T23] Swift：函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2ymizyqoz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhengqikj.top/Article/details/gt2mwhbjotg.html

[T24] Swift：闭包
来源：http://dali.zycfv.cn/Article/details/gt2mtdvnopg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.meibo888.top/Article/details/gt2vvjxolba.html

[T25] Swift：结构体
来源：http://dali.pycfn.com/Article/details/gt2drzejasb.html

struct P { var x: Int }
来源：http://dali.quarkkingdee.top/Article/details/gt2efyjmyky.html

[T26] Swift：类与重写
来源：http://dali.zhongyouzk.top/Article/details/gt2bmwsulcm.html

class A: Base { override func f() {} }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vupjxour.html

[T27] Swift：错误处理
来源：http://dali.redwolf501.top/Article/details/gt2aveobcgi.html

do { try f() } catch { print(error) }
来源：http://dali.gogol.net.cn/Article/details/gt2yqtudpjw.html

[T28] Swift：枚举
来源：http://dali.vqdsnc.cn/Article/details/gt2djxpmdkw.html

enum Color { case red, green }
来源：http://dali.zdqjudy.top/Article/details/gt2wvcfvvof.html

[T29] Swift：guard 提前返回
来源：http://dali.ppjwa.cn/Article/details/gt2dupwmstv.html

guard let x = opt else { return }
来源：http://dali.yueranfly.top/Article/details/gt2lbjzjixh.html

[T30] Swift：协议
来源：http://dali.fengsongda.top/Article/details/gt2yhdugedn.html

protocol Shape { func area() -> Double }
来源：http://dali.jqgufenzy.top/Article/details/gt2esqqltux.html

[T31] Lua：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gt2ukncnptp.html

print("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fpeqoyhp.html

[T32] Lua：局部变量
来源：http://dali.yueranfly.top/Article/details/gt2efeyqqrp.html

local a = 1
来源：http://dali.dianchejie.cn/Article/details/gt2excsuplk.html

[T33] Lua：表（数组）
来源：http://dali.quarkkingdee.top/Article/details/gt2ufilkatn.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hnxiangtu.top/Article/details/gt2qgtcqggl.html

[T34] Lua：遍历表
来源：http://dali.xuetiantiany.cn/Article/details/gt2kffnqfjp.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jqgufenzy.top/Article/details/gt2nsdqepuh.html

[T35] Lua：字典表
来源：http://dali.tianlin.xyz/Article/details/gt2wlelqpsk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jiagoushi.top/Article/details/gt2jpcbkcfb.html

[T36] Lua：函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fkvkqfvh.html

function add(a, b) return a + b end
来源：http://dali.gotoacloud.top/Article/details/gt2mtxoesjk.html

[T37] Lua：字符串拼接
来源：http://dali.yuxming.cn/Article/details/gt2lzvuucok.html

"a" .. "b"
来源：http://dali.yanxiufei.cn/Article/details/gt2sbfppknt.html

[T38] Lua：条件
来源：http://dali.daria6918.cn/Article/details/gt2imtrqucs.html

if x > 0 then print("正") end
来源：http://dali.cqqwz.cn/Article/details/gt2zbirdmkx.html

[T39] Lua：模式匹配
来源：http://dali.iojbl.cn/Article/details/gt2kwtiosok.html

string.find(s, "%d+")
来源：http://dali.sxryk.cn/Article/details/gt2ebtuyvgc.html

[T40] Lua：元表
来源：http://dali.hnqzz.top/Article/details/gt2xapizuox.html

setmetatable({}, { __index = base })
来源：http://dali.wangshuangyany.cn/Article/details/gt2tgmsqpfi.html

[T41] Perl：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gt2zthcpwlo.html

print "Hello\n";
来源：http://dali.cqqwz.cn/Article/details/gt2zsqojoku.html

[T42] Perl：变量类型
来源：http://dali.hywenlv.cn/Article/details/gt2wpzcdkxk.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.andypj.xyz/Article/details/gt2xycgiemx.html

[T43] Perl：字符串插值
来源：http://dali.ydzc1.top/Article/details/gt2aqqgugso.html

"值: $a"
来源：http://dali.cucudq.cn/Article/details/gt2kwievbuo.html

[T44] Perl：条件
来源：http://dali.ivvv.top/Article/details/gt2yagljgqu.html

if ($a > 0) { print "正"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xffdgizd.html

[T45] Perl：数组遍历
来源：http://dali.fengsongda.top/Article/details/gt2jgiofyjf.html

for my $x (@arr) { print $x; }
来源：http://dali.cqqwz.cn/Article/details/gt2faehacwt.html

[T46] Perl：哈希操作
来源：http://dali.zhengqikj.top/Article/details/gt2jsjehscr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2crynqxgq.html

[T47] Perl：正则捕获
来源：http://dali.tianlin.xyz/Article/details/gt2lanoetcn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xziqi.cn/Article/details/gt2injmgcfb.html

[T48] Perl：正则替换
来源：http://dali.yuanzhike.top/Article/details/gt2ilmnetfq.html

$s =~ s/old/new/g;
来源：http://dali.gotoacloud.top/Article/details/gt2vhqnjleq.html

[T49] Perl：函数
来源：http://dali.bjfxy.top/Article/details/gt2kxinsqsx.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.daria6918.cn/Article/details/gt2kechgedq.html

[T50] Perl：逐行读文件
来源：http://dali.ivvv.top/Article/details/gt2btrjujbk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hnxiangtu.top/Article/details/gt2lsjshhde.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.gaohongyu789.top/Article/details/gt2eciwbpcw.html

[T51] Scala：Hello World
来源：http://dali.sysykeji.top/Article/details/gt2mcvpsrjj.html

println("Hello")
来源：http://dali.xuetiantiany.cn/Article/details/gt2fyjuyddk.html

[T52] Scala：变量
来源：http://dali.gzhubu.top/Article/details/gt2uishrzjn.html

val a = 1;  var b = 2
来源：http://dali.yuxming.cn/Article/details/gt2lhrzlxqd.html

[T53] Scala：字符串插值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cfmtedcv.html

s"值: $b"
来源：http://dali.nanxinkj.top/Article/details/gt2tmixjozo.html

[T54] Scala：集合映射
来源：http://dali.shangyingyoupin.top/Article/details/gt2nqfyumcd.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hfpthk.cn/Article/details/gt2fansspwj.html

[T55] Scala：集合过滤
来源：http://dali.birdmap.top/Article/details/gt2caglhcgi.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.dashuyun.cn/Article/details/gt2klervfgk.html

[T56] Scala：样例类
来源：http://dali.sysykeji.top/Article/details/gt2wceyknwj.html

case class User(name: String, age: Int)
来源：http://dali.gaohongyu789.top/Article/details/gt2qmrvqeek.html

[T57] Scala：模式匹配
来源：http://dali.chenlongwang.top/Article/details/gt2qtqusuqx.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.daria6918.cn/Article/details/gt2xjqltzys.html

[T58] Scala：函数定义
来源：http://dali.zdqjudy.top/Article/details/gt2jitxzzll.html


<!-- 参考信息 -->