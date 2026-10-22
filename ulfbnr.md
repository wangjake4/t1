代发 wailian999

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hammf.cn/Article/details/gt2vttgsgxp.html

[R52] 统计行数
来源：http://dali.hywenlv.cn/Article/details/gt2diuyfebp.html

wc -l a.txt
来源：http://dali.gotoacloud.top/Article/details/gt2jawqwrms.html

[R53] 查看文件头与实时尾
来源：http://dali.jiagoushi.top/Article/details/gt2puvnhuss.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.vqdsnc.cn/Article/details/gt2xmfbwodc.html

[R54] 比较两个文件
来源：http://dali.dashuyun.cn/Article/details/gt2ullpdkpl.html

diff a.txt b.txt
来源：http://dali.ydzc1.top/Article/details/gt2njoprxhd.html

[R55] 压缩与解压
来源：http://dali.wangshuangyany.cn/Article/details/gt2jhpekbkl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.tian-w.cn/Article/details/gt2cuhxgswm.html

[R56] 远程拷贝
来源：http://dali.zdqjudy.top/Article/details/gt2jwaqbvot.html

scp file user@host:/path/
来源：http://dali.pycfn.com/Article/details/gt2gqjluzdi.html

[R57] 远程执行命令
来源：http://dali.chenlongwang.top/Article/details/gt2zysypmeg.html

ssh user@host 'uptime'
来源：http://dali.shangyingyoupin.top/Article/details/gt2eamskhyy.html

[R58] 下载文件
来源：http://dali.yongpay.top/Article/details/gt2iczlkrss.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.guannengcc.top/Article/details/gt2spghrjmg.html

[R59] 发 POST JSON
来源：http://dali.cucudq.cn/Article/details/gt2nsdtkacz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yvedp.cn/Article/details/gt2kmiamndk.html

[R60] 只看 HTTP 状态码
来源：http://dali.nanxuanxn.top/Article/details/gt2nvnkjktb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.9152youxi.cn/Article/details/gt2jvsifslv.html

[R61] 磁盘占用
来源：http://dali.yuanzhike.top/Article/details/gt2kjhrakcv.html

df -h;  du -sh *
来源：http://dali.zhongyouzk.top/Article/details/gt2vkmihtti.html

[R62] 找最占空间的文件
来源：http://dali.kuanghao11.cn/Article/details/gt2rwrleeap.html

du -ah . | sort -rh | head -10
来源：http://dali.daxiang520.top/Article/details/gt2nhodceks.html

[R63] 内存与进程
来源：http://dali.jlsjyb.cn/Article/details/gt2jkvkifxr.html

free -h;  ps aux | grep nginx
来源：http://dali.jqgfzy.top/Article/details/gt2rzgtktph.html

[R64] 结束进程
来源：http://dali.wangshuangyany.cn/Article/details/gt2xiqygcrb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yangfankeji.com/Article/details/gt2atgzinpw.html

[R65] 查看端口占用
来源：http://dali.hammf.cn/Article/details/gt2gwlvwapl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xuanzx.com/Article/details/gt2wezihlnl.html

[R66] 定时任务
来源：http://dali.sufxvd.cn/Article/details/gt2uxqlnoof.html

crontab -e;  crontab -l
来源：http://dali.hfpthk.cn/Article/details/gt2qivlqlae.html

[R67] 生成随机十六进制串
来源：http://dali.xinyue.icu/Article/details/gt2bekqqdxl.html

openssl rand -hex 16
来源：http://dali.jinqigufen.top/Article/details/gt2licbtird.html

[R68] 计算文件校验值
来源：http://dali.cqqwz.cn/Article/details/gt2znsnouay.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.dianchejie.cn/Article/details/gt2knorukzx.html

[R69] 生成随机密码
来源：http://dali.jinqigufen.top/Article/details/gt2gqkuyxmz.html

head -c 16 /dev/urandom | base64
来源：http://dali.xziqi.cn/Article/details/gt2qqodhxrj.html

[R70] 时间戳与互转
来源：http://dali.daria6918.cn/Article/details/gt2rlpovbrg.html

date +%s;  date -d @1700000000
来源：http://dali.havefunace.top/Article/details/gt2brjylrlo.html

[R71] 日期格式化
来源：http://dali.yj20258.top/Article/details/gt2cvlkexal.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.sxryk.cn/Article/details/gt2icmognku.html

[R72] 等待端口就绪
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dkfdmtwr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shzxlz.cn/Article/details/gt2xmjnchbw.html

[R73] 分割大日志
来源：http://dali.yuanzhike.top/Article/details/gt2pbdjlsjc.html

split -l 1000 big.log part_
来源：http://dali.chenzaomai.com/Article/details/gt2fofkinhj.html

[R74] 批量重命名
来源：http://dali.jianghu66.top/Article/details/gt2angpuwth.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.tianlin.xyz/Article/details/gt2hltzpbsj.html

[R75] 导出环境变量
来源：http://dali.tanke756.top/Article/details/gt2wrpmjcmf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.birdmap.top/Article/details/gt2vgnnsmcx.html

[R76] 使用临时文件
来源：http://dali.guannengcc.top/Article/details/gt2itfxtliu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yangfankeji.com/Article/details/gt2uehvhnsl.html

[R77] 读取用户输入
来源：http://dali.wangshuangyany.cn/Article/details/gt2zvkfhokc.html

read -rp "请输入: " ans
来源：http://dali.xinyue.icu/Article/details/gt2ccbzbffn.html

[R78] 交互式菜单
来源：http://dali.guowangkeji.top/Article/details/gt2gtfrsokm.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.redwolf501.top/Article/details/gt2jrpghmih.html

[R79] 解析命令行选项
来源：http://dali.yj20258888.top/Article/details/gt2kmsisgvd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.guannengcc.top/Article/details/gt2nozvhfra.html

[R80] 查看脚本执行耗时
来源：http://dali.gotoacloud.top/Article/details/gt2cxxlvfcz.html

time ./run.sh
来源：http://dali.ivvv.top/Article/details/gt2tsxqmsba.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2ttjsfvdw.html

S. C / C++ 专题
来源：http://dali.pycfn.com/Article/details/gt2cemyoqzc.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2wymjlxxz.html

[S01] C：Hello World
来源：http://dali.pycfn.com/Article/details/gt2vqvugkfb.html

#include <stdio.h>
来源：http://dali.chenjidiqi.icu/Article/details/gt2eestyqfo.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gzhubu.top/Article/details/gt2norkqkew.html

[S02] C：变量与格式化输出
来源：http://dali.yonumen.top/Article/details/gt2yyiovvow.html

int a = 10; printf("%d\n", a);
来源：http://dali.316326.xyz/Article/details/gt2rukozruo.html

[S03] C：读入整数
来源：http://dali.yj20258888.top/Article/details/gt2izsttiny.html

int x; scanf("%d", &x);
来源：http://dali.tian-w.cn/Article/details/gt2dbrbybpb.html

[S04] C：字符串复制
来源：http://dali.shuidangran.top/Article/details/gt2qtcajtoe.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.0kj1m.cn/Article/details/gt2jfclckib.html

[S05] C：字符串长度
来源：http://dali.hfpthk.cn/Article/details/gt2rqrdxsdy.html

strlen(s)
来源：http://dali.yongpay.top/Article/details/gt2fzcwydgf.html

[S06] C：字符串比较
来源：http://dali.zycfv.cn/Article/details/gt2mlpicsju.html

strcmp(a, b) == 0
来源：http://dali.yvedp.cn/Article/details/gt2twuroief.html

[S07] C：数组遍历求和
来源：http://dali.shangyingyoupin.top/Article/details/gt2gfayomqz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yueranfly.top/Article/details/gt2inbueybj.html

[S08] C：动态内存分配与释放
来源：http://dali.ehwqpu.com/Article/details/gt2hdqtcnrk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhixingplan.top/Article/details/gt2bgyashof.html

[S09] C：结构体定义与初始化
来源：http://dali.jqgufenzy.top/Article/details/gt2eobtrglk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jqgufenzy.top/Article/details/gt2puwhkrwq.html

[S10] C：指针与解引用
来源：http://dali.havefunace.top/Article/details/gt2vpxzbvba.html

int *p = &a;  *p = 5;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uoyuyyng.html

[S11] C：逐行读文件
来源：http://dali.ivvv.top/Article/details/gt2sbsasett.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2injjemzs.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shuidangran.top/Article/details/gt2uqjlhxwg.html

fclose(f);
来源：http://dali.xylfe.cn/Article/details/gt2nzxmtjay.html

[S12] C：写文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bbucgovv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zycfv.cn/Article/details/gt2vejhwlvq.html

[S13] C：宏定义
来源：http://dali.yueranfly.top/Article/details/gt2kopmkurt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.redwolf501.top/Article/details/gt2eygntkks.html

[S14] C：枚举
来源：http://dali.guannengcc.top/Article/details/gt2czmlqkqc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.chenjidiqi.icu/Article/details/gt2cgijsmxp.html

[S15] C：类型转换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xigimosx.html

(double) a / b
来源：http://dali.sufxvd.cn/Article/details/gt2eiewschr.html

[S16] C：位操作置位
来源：http://dali.havefunace.top/Article/details/gt2yeopapsx.html

x |= (1 << 3);
来源：http://dali.dianchejie.cn/Article/details/gt2zuvzvqev.html

[S17] C：安全拼接字符串
来源：http://dali.yangfankeji.com/Article/details/gt2hvsvvgbf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.9152youxi.cn/Article/details/gt2bonlpybv.html

[S18] C：命令行参数
来源：http://dali.feifeiyinyue.top/Article/details/gt2legwohar.html

int main(int argc, char **argv)
来源：http://dali.xuanzx.com/Article/details/gt2rtxrnbfe.html

[S19] C：快速排序
来源：http://dali.nwbrower.top/Article/details/gt2zsqixyda.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xziqi.cn/Article/details/gt2qpgvfiug.html

[S20] C：二分查找
来源：http://dali.meibo888.top/Article/details/gt2dqrionoy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.redwolf501.top/Article/details/gt2pmnmknbk.html

[S21] C：字符类别判断
来源：http://dali.aibaodan.cn/Article/details/gt2tafscrqm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.andypj.xyz/Article/details/gt2sbspvxnf.html

[S22] C：字符串转数字
来源：http://dali.xuetiantiany.cn/Article/details/gt2fecffcua.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cheryme.top/Article/details/gt2gpjzstdl.html

[S23] C：随机数
来源：http://dali.ybcxt.top/Article/details/gt2mpufgwhd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sufxvd.cn/Article/details/gt2ivmvdyyc.html

[S24] C：获取本地时间
来源：http://dali.andypj.xyz/Article/details/gt2kolvriuj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.gzhubu.top/Article/details/gt2whrsbptk.html

[S25] C：内存拷贝
来源：http://dali.nwbrower.top/Article/details/gt2qkcrwvtu.html

memcpy(dst, src, n);
来源：http://dali.nanxuanxn.top/Article/details/gt2lwqstcsm.html

[S26] C：内存清零
来源：http://dali.hammf.cn/Article/details/gt2iequdggg.html

memset(a, 0, sizeof a);
来源：http://dali.ehwqpu.com/Article/details/gt2xijeslhr.html

[S27] C：定义常量
来源：http://dali.aizwys.cn/Article/details/gt2hxxmypuq.html

const double PI = 3.14159;
来源：http://dali.xuanzx.com/Article/details/gt2pjgyfjlm.html

[S28] C：静态变量
来源：http://dali.vqdsnc.cn/Article/details/gt2leuhdppx.html

static int counter = 0;
来源：http://dali.9152youxi.cn/Article/details/gt2vrgktsao.html

[S29] C：变参函数
来源：http://dali.xziqi.cn/Article/details/gt2oozynzyd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.chenzaomai.com/Article/details/gt2mdiyxaea.html

[S30] C：头文件保护
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dwqtzxke.html

#ifndef X_H
来源：http://dali.chenlongwang.top/Article/details/gt2pvlkrmjz.html

#define X_H
来源：http://dali.guowangkeji.top/Article/details/gt2lhecmryb.html

#endif
来源：http://dali.zhengqikj.top/Article/details/gt2stmygann.html

[S31] C++：Hello World
来源：http://dali.smart0.xyz/Article/details/gt2jvlgcois.html

#include <iostream>
来源：http://dali.cashguo.top/Article/details/gt2vzersaqe.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sufxvd.cn/Article/details/gt2llmglgan.html

[S32] C++：字符串
来源：http://dali.jyoumei.cn/Article/details/gt2kszxptwn.html

std::string s = "hi";  s += "!";
来源：http://dali.sysykeji.top/Article/details/gt2vyluspol.html

[S33] C++：vector 增删
来源：http://dali.guannengcc.top/Article/details/gt2twmjryyn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.andypj.xyz/Article/details/gt2uzxmnahh.html

[S34] C++：遍历 vector
来源：http://dali.smart0.xyz/Article/details/gt2jslzrvfr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.fengsongda.top/Article/details/gt2hncalvxe.html

[S35] C++：map
来源：http://dali.sysykeji.top/Article/details/gt2clreupgp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jusbjxao.html

[S36] C++：unordered_map
来源：http://dali.hongshengwenyu.top/Article/details/gt2vryhwrcj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2drebdglm.html

[S37] C++：set
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xjqsrhdn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.tanke756.top/Article/details/gt2hgvbexvd.html

[S38] C++：排序
来源：http://dali.jqgfzy.top/Article/details/gt2nzzuneju.html

std::sort(v.begin(), v.end());
来源：http://dali.aizwys.cn/Article/details/gt2ihfbwges.html

[S39] C++：自定义比较器排序
来源：http://dali.yonumen.top/Article/details/gt2ziujsqyo.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.wangdashe.top/Article/details/gt2eabuyshn.html

[S40] C++：查找元素
来源：http://dali.zhoulong.xyz/Article/details/gt2tshivecy.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hfpthk.cn/Article/details/gt2tlwcfxyi.html

[S41] C++：类与构造函数
来源：http://dali.pycfn.com/Article/details/gt2pzkqvveq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cdnleiting.top/Article/details/gt2xgbjempl.html

[S42] C++：继承与虚函数
来源：http://dali.ivvv.top/Article/details/gt2hutbpies.html

class B : public Base { public: void f() override {} };
来源：http://dali.yueranfly.top/Article/details/gt2zicnunih.html

[S43] C++：智能指针
来源：http://dali.nanxinkj.top/Article/details/gt2rgeuagor.html

auto p = std::make_unique<int>(5);
来源：http://dali.shzxlz.cn/Article/details/gt2oyuypfnd.html

[S44] C++：引用传参
来源：http://dali.jlsjyb.cn/Article/details/gt2bgcyqftk.html

void inc(int &x) { ++x; }
来源：http://dali.zhoulong.xyz/Article/details/gt2ihpstagz.html

[S45] C++：lambda
来源：http://dali.jqgfzy.top/Article/details/gt2izvablnr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.9152youxi.cn/Article/details/gt2laansiqk.html

[S46] C++：函数模板
来源：http://dali.316326.xyz/Article/details/gt2orbutdug.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.nanxuanxn.top/Article/details/gt2tsgtaxrb.html

[S47] C++：结构化绑定遍历
来源：http://dali.nwbrower.top/Article/details/gt2wahaeeyd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yvedp.cn/Article/details/gt2zglmgmzt.html

[S48] C++：逐行读文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ybzlfsme.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.tanke756.top/Article/details/gt2oxczohqq.html

while (std::getline(in, line)) { }
来源：http://dali.chenzaomai.com/Article/details/gt2fnwdikbs.html

[S49] C++：写文件
来源：http://dali.fzhhl.top/Article/details/gt2oziibmfi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.haohaochexian.top/Article/details/gt2gheaxczg.html

[S50] C++：格式化数字
来源：http://dali.fzhhl.top/Article/details/gt2gfaadorx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gt2xbbupmvx.html

[S51] C++：显式类型转换
来源：http://dali.shangyingyoupin.top/Article/details/gt2vfegmkca.html

static_cast<double>(a) / b
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nhrhxrib.html

[S52] C++：const 与 noexcept
来源：http://dali.tian-w.cn/Article/details/gt2lhnzvvpn.html

int size() const noexcept { return n_; }
来源：http://dali.meibo888.top/Article/details/gt2pvqkshzw.html

[S53] C++：移动语义
来源：http://dali.jqgufenzy.top/Article/details/gt2ikckzpcx.html

std::vector<int> w = std::move(v);
来源：http://dali.yj20258888.top/Article/details/gt2ojelkkei.html

[S54] C++：异常处理
来源：http://dali.yongpay.top/Article/details/gt2dvsqyiqf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.316326.xyz/Article/details/gt2mzmdsdyj.html

[S55] C++：结构化绑定
来源：http://dali.shangyingyoupin.top/Article/details/gt2vqnqgtdt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yj20258.top/Article/details/gt2egputhvz.html

[S56] C++：optional
来源：http://dali.birdmap.top/Article/details/gt2eyqmujug.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jianghu66.top/Article/details/gt2uctvrcyg.html

[S57] C++：编译期常量
来源：http://dali.cashguo.top/Article/details/gt2xfmbbkpi.html

constexpr int N = 10;
来源：http://dali.yj202588.top/Article/details/gt2zrukpgez.html

[S58] C++：命名空间
来源：http://dali.svipenyu.cn/Article/details/gt2kfkpgrgd.html

namespace ns { int f() { return 1; } }
来源：http://dali.fengsongda.top/Article/details/gt2yslczkvf.html

[S59] C++：静态断言
来源：http://dali.hnqzz.top/Article/details/gt2qdlayjlr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sysykeji.top/Article/details/gt2ldqfyqnd.html

[S60] C++：遍历并删除元素
来源：http://dali.zycfv.cn/Article/details/gt2joxahsau.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.aibaodan.cn/Article/details/gt2mxouxved.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2oohtkeqs.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hammf.cn/Article/details/gt2hcuqgpug.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nxzbgcev.html

[T01] Kotlin：Hello World
来源：http://dali.cashguo.top/Article/details/gt2ziyopiba.html

println("Hello")
来源：http://dali.hammf.cn/Article/details/gt2msvmpsuu.html

[T02] Kotlin：变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bpsegwrm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.nanxuanxn.top/Article/details/gt2tfdgzsrx.html

[T03] Kotlin：字符串模板
来源：http://dali.yongpay.top/Article/details/gt2nihbtmij.html

"值: $b"
来源：http://dali.0kj1m.cn/Article/details/gt2nvtuupwe.html

[T04] Kotlin：空安全
来源：http://dali.dianchejie.cn/Article/details/gt2lxlwcyuw.html

val n: String? = null;  n?.length
来源：http://dali.xziqi.cn/Article/details/gt2ucqptlom.html

[T05] Kotlin：when 表达式
来源：http://dali.jlsjyb.cn/Article/details/gt2tagkanoc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shuidangran.top/Article/details/gt2sipjdcny.html

[T06] Kotlin：集合映射
来源：http://dali.gotoacloud.top/Article/details/gt2fgryhzaa.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ppjwa.cn/Article/details/gt2fnkigqoe.html

[T07] Kotlin：集合过滤
来源：http://dali.svipenyu.cn/Article/details/gt2esujcwst.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.snrcjt.cn/Article/details/gt2wsqpembv.html

[T08] Kotlin：数据类
来源：http://dali.tianlin.xyz/Article/details/gt2egvyvbth.html

data class User(val name: String, val age: Int)
来源：http://dali.bjfxy.top/Article/details/gt2mtmofbbg.html

[T09] Kotlin：扩展函数
来源：http://dali.yangfankeji.com/Article/details/gt2bqdagbov.html

fun String.exclaim() = this + "!"
来源：http://dali.hnqzz.top/Article/details/gt2ezmtwnvo.html

[T10] Kotlin：默认参数
来源：http://dali.smart0.xyz/Article/details/gt2xdqwgfbd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xinyue.icu/Article/details/gt2gpatrogd.html

[T11] Kotlin：协程
来源：http://dali.yj202588.top/Article/details/gt2cvsxnkje.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sxryk.cn/Article/details/gt2cmhxlmhu.html

[T12] Kotlin：解构声明
来源：http://dali.jyoumei.cn/Article/details/gt2njcapesa.html

val (a, b) = Pair(1, 2)
来源：http://dali.bjfxy.top/Article/details/gt2ipqgtlfb.html

[T13] Kotlin：只读 Map
来源：http://dali.vqdsnc.cn/Article/details/gt2baohacdr.html

val m = mapOf("a" to 1)
来源：http://dali.jiagoushi.top/Article/details/gt2ylzswwaf.html

[T14] Kotlin：循环
来源：http://dali.jlsjyb.cn/Article/details/gt2ygvrrlea.html

for (i in 1..10) println(i)
来源：http://dali.aibaodan.cn/Article/details/gt2waiqnmyf.html

[T15] Kotlin：接口
来源：http://dali.kuanghao11.cn/Article/details/gt2yozzlsdn.html

interface Shape { fun area(): Double }
来源：http://dali.jqgufenzy.top/Article/details/gt2qquonjez.html

[T16] Swift：Hello World
来源：http://dali.yangfankeji.com/Article/details/gt2xmukptqj.html

print("Hello")
来源：http://dali.hnqzz.top/Article/details/gt2frjufppt.html

[T17] Swift：变量与常量
来源：http://dali.yonumen.top/Article/details/gt2zbersetg.html

var a = 1;  let b = 2
来源：http://dali.jqgufenzy.top/Article/details/gt2ivmrqefj.html

[T18] Swift：字符串插值
来源：http://dali.9152youxi.cn/Article/details/gt2canmidmu.html

"值: \(b)"
来源：http://dali.yanxiufei.cn/Article/details/gt2kvkgfawo.html

[T19] Swift：可选绑定
来源：http://dali.pengpengdd.cyou/Article/details/gt2wrrcoiqi.html

if let n = opt { print(n) }
来源：http://dali.xinyue.icu/Article/details/gt2kvedymqd.html

[T20] Swift：数组操作
来源：http://dali.cdnleiting.top/Article/details/gt2zvkxmfpj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.aibaodan.cn/Article/details/gt2wfpmedai.html

[T21] Swift：遍历
来源：http://dali.guannengcc.top/Article/details/gt2lknmnktv.html

for x in a { print(x) }
来源：http://dali.yangfankeji.com/Article/details/gt2sfyjgevn.html

[T22] Swift：字典
来源：http://dali.xziqi.cn/Article/details/gt2ieukqsvg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dncjntzt.html

[T23] Swift：函数
来源：http://dali.yanxiufei.cn/Article/details/gt2zdrooose.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xuanzx.com/Article/details/gt2kkmymxus.html

[T24] Swift：闭包
来源：http://dali.ybcxt.top/Article/details/gt2fywvhkgx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hysaishi.cn/Article/details/gt2nfgpulvc.html

[T25] Swift：结构体
来源：http://dali.nwbrower.top/Article/details/gt2dbolhcln.html

struct P { var x: Int }
来源：http://dali.havefunace.top/Article/details/gt2ltkkgjko.html

[T26] Swift：类与重写
来源：http://dali.sxryk.cn/Article/details/gt2ypmezinv.html

class A: Base { override func f() {} }
来源：http://dali.nanxinkj.top/Article/details/gt2wavgchwp.html

[T27] Swift：错误处理
来源：http://dali.fengsongda.top/Article/details/gt2jzmzsjag.html

do { try f() } catch { print(error) }
来源：http://dali.jiagoushi.top/Article/details/gt2ptrjskth.html

[T28] Swift：枚举
来源：http://dali.jinghuilouyu.cn/Article/details/gt2okgxxmcx.html

enum Color { case red, green }
来源：http://dali.zhongyouzk.top/Article/details/gt2ylhbzwjs.html

[T29] Swift：guard 提前返回
来源：http://dali.zhoulong.xyz/Article/details/gt2nokgoibx.html

guard let x = opt else { return }
来源：http://dali.fzhhl.top/Article/details/gt2pvwgdzsz.html

[T30] Swift：协议
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2afzpeule.html

protocol Shape { func area() -> Double }
来源：http://dali.zdqjudy.top/Article/details/gt2hyokigwc.html

[T31] Lua：Hello World
来源：http://dali.ehwqpu.com/Article/details/gt2jlyuuyql.html

print("Hello")
来源：http://dali.birdmap.top/Article/details/gt2imapqcqp.html

[T32] Lua：局部变量
来源：http://dali.redwolf501.top/Article/details/gt2dqaskyji.html

local a = 1
来源：http://dali.sweek.top/Article/details/gt2bjfrxnel.html

[T33] Lua：表（数组）
来源：http://dali.pengpengdd.cyou/Article/details/gt2zqigbcax.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.pengpengdd.cyou/Article/details/gt2vzrilmnj.html

[T34] Lua：遍历表
来源：http://dali.jqgufenzy.top/Article/details/gt2gywlayje.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.wangdashe.top/Article/details/gt2nqbcbcad.html

[T35] Lua：字典表
来源：http://dali.hnxiangtu.top/Article/details/gt2thdnvnhe.html

local d = { a = 1 };  d.b = 2
来源：http://dali.bjfxy.top/Article/details/gt2rgupxbtk.html

[T36] Lua：函数
来源：http://dali.hammf.cn/Article/details/gt2wdqeyiot.html

function add(a, b) return a + b end
来源：http://dali.hysaishi.cn/Article/details/gt2nwgpcznt.html

[T37] Lua：字符串拼接
来源：http://dali.ppjwa.cn/Article/details/gt2rrcaljyw.html

"a" .. "b"
来源：http://dali.jinqigufen.top/Article/details/gt2rbteaoii.html

[T38] Lua：条件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kkrzxtoq.html

if x > 0 then print("正") end
来源：http://dali.yuxming.cn/Article/details/gt2abqfyzrt.html

[T39] Lua：模式匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bxgngjub.html

string.find(s, "%d+")
来源：http://dali.jqgufenzy.top/Article/details/gt2xbdjcptj.html

[T40] Lua：元表
来源：http://dali.jiagoushi.top/Article/details/gt2nukfvfvr.html

setmetatable({}, { __index = base })
来源：http://dali.yj202588.top/Article/details/gt2gjtkukih.html

[T41] Perl：Hello World
来源：http://dali.cucudq.cn/Article/details/gt2rgfntjbk.html

print "Hello\n";
来源：http://dali.nanxinkj.top/Article/details/gt2smnuspaq.html

[T42] Perl：变量类型
来源：http://dali.cheryme.top/Article/details/gt2slgbizub.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zdqjudy.top/Article/details/gt2hqqftpcm.html

[T43] Perl：字符串插值
来源：http://dali.cqqwz.cn/Article/details/gt2ifbaimwk.html

"值: $a"
来源：http://dali.svipenyu.cn/Article/details/gt2lairpwmw.html

[T44] Perl：条件
来源：http://dali.316326.xyz/Article/details/gt2xzrysfrm.html

if ($a > 0) { print "正"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2cenvhrve.html

[T45] Perl：数组遍历
来源：http://dali.shuidangran.top/Article/details/gt2cczwuhfu.html

for my $x (@arr) { print $x; }
来源：http://dali.jianghu66.top/Article/details/gt2soghxzwy.html

[T46] Perl：哈希操作
来源：http://dali.iojbl.cn/Article/details/gt2uieapcbr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2actztcce.html

[T47] Perl：正则捕获
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bpunqugx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jinqigufen.top/Article/details/gt2yqqhouqy.html

[T48] Perl：正则替换
来源：http://dali.snrcjt.cn/Article/details/gt2zmgdeqdg.html

$s =~ s/old/new/g;
来源：http://dali.jinqigufen.top/Article/details/gt2jnyshqww.html

[T49] Perl：函数
来源：http://dali.tanke756.top/Article/details/gt2puzgupob.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.sysykeji.top/Article/details/gt2vuxcuqbh.html

[T50] Perl：逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gt2eqwxsfgu.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jyoumei.cn/Article/details/gt2wkrvzahf.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ivseqsgq.html

[T51] Scala：Hello World
来源：http://dali.sufxvd.cn/Article/details/gt2dafcxhyy.html

println("Hello")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lvouiuam.html

[T52] Scala：变量
来源：http://dali.ppjwa.cn/Article/details/gt2ugteblvf.html

val a = 1;  var b = 2
来源：http://dali.hysaishi.cn/Article/details/gt2xgytzfgt.html

[T53] Scala：字符串插值
来源：http://dali.ehwqpu.com/Article/details/gt2apwyqnfb.html

s"值: $b"
来源：http://dali.bjfxy.top/Article/details/gt2copefcgi.html

[T54] Scala：集合映射
来源：http://dali.tian-w.cn/Article/details/gt2tajehptp.html


<!-- 参考信息 -->