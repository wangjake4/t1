代发 wailian999

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.c1oappe.top/Article/details/gt2tbjdnasv.html

[R50] awk 求和
来源：http://dali.sufxvd.cn/Article/details/gt2tozfthsp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.guowangkeji.top/Article/details/gt2pjsmzeow.html

[R51] 排序去重取前几
来源：http://dali.daria6918.cn/Article/details/gt2qrksflig.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jiagoushi.top/Article/details/gt2vvnpimhu.html

[R52] 统计行数
来源：http://dali.jyoumei.cn/Article/details/gt2pnlrpzvo.html

wc -l a.txt
来源：http://dali.jinqigfzy.top/Article/details/gt2msbivxrk.html

[R53] 查看文件头与实时尾
来源：http://dali.iojbl.cn/Article/details/gt2aoxcjpcw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jianghu66.top/Article/details/gt2cresamjx.html

[R54] 比较两个文件
来源：http://dali.hnxiangtu.top/Article/details/gt2grhcopzw.html

diff a.txt b.txt
来源：http://dali.shangyingyoupin.top/Article/details/gt2pinqnngg.html

[R55] 压缩与解压
来源：http://dali.nanxuanxn.top/Article/details/gt2svmtfrnu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.vqdsnc.cn/Article/details/gt2blodkevv.html

[R56] 远程拷贝
来源：http://dali.chenlongwang.top/Article/details/gt2vfftauhu.html

scp file user@host:/path/
来源：http://dali.hongshengwenyu.top/Article/details/gt2oqnigjzt.html

[R57] 远程执行命令
来源：http://dali.fengsongda.top/Article/details/gt2lpxnbcgx.html

ssh user@host 'uptime'
来源：http://dali.xuetiantiany.cn/Article/details/gt2qgzgkgwh.html

[R58] 下载文件
来源：http://dali.chenlongwang.top/Article/details/gt2sbxozxii.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.316326.xyz/Article/details/gt2jfqxihro.html

[R59] 发 POST JSON
来源：http://dali.kuanghao11.cn/Article/details/gt2zpiofvvl.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.wangdashe.top/Article/details/gt2oacsohyq.html

[R60] 只看 HTTP 状态码
来源：http://dali.hywenlv.cn/Article/details/gt2wivkecln.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.wangdashe.top/Article/details/gt2qujgwgzc.html

[R61] 磁盘占用
来源：http://dali.chenjidiqi.icu/Article/details/gt2udqgospd.html

df -h;  du -sh *
来源：http://dali.xylfe.cn/Article/details/gt2ugjuzohl.html

[R62] 找最占空间的文件
来源：http://dali.smart0.xyz/Article/details/gt2aezexfwb.html

du -ah . | sort -rh | head -10
来源：http://dali.sweek.top/Article/details/gt2mjrcogzs.html

[R63] 内存与进程
来源：http://dali.redwolf501.top/Article/details/gt2mxisvwjw.html

free -h;  ps aux | grep nginx
来源：http://dali.chenjidiqi.icu/Article/details/gt2yhfgmfqb.html

[R64] 结束进程
来源：http://dali.wangshuangyany.cn/Article/details/gt2nzujzdkt.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shuidangran.top/Article/details/gt2hjuyiqni.html

[R65] 查看端口占用
来源：http://dali.hammf.cn/Article/details/gt2kgqfhhaq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gotoacloud.top/Article/details/gt2cssylpcb.html

[R66] 定时任务
来源：http://dali.yuanzhike.top/Article/details/gt2oaukaziu.html

crontab -e;  crontab -l
来源：http://dali.gogol.net.cn/Article/details/gt2lbniwjwy.html

[R67] 生成随机十六进制串
来源：http://dali.hongshengwenyu.top/Article/details/gt2rmqdwzjd.html

openssl rand -hex 16
来源：http://dali.fengsongda.top/Article/details/gt2qyoujuct.html

[R68] 计算文件校验值
来源：http://dali.yj20258888.top/Article/details/gt2uzvnoqli.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.birdmap.top/Article/details/gt2cpskbufc.html

[R69] 生成随机密码
来源：http://dali.jqgfzy.top/Article/details/gt2yavwrklu.html

head -c 16 /dev/urandom | base64
来源：http://dali.nanxinkj.top/Article/details/gt2clwdpley.html

[R70] 时间戳与互转
来源：http://dali.fzhhl.top/Article/details/gt2hincfpam.html

date +%s;  date -d @1700000000
来源：http://dali.aizwys.cn/Article/details/gt2lhjphjls.html

[R71] 日期格式化
来源：http://dali.fengsongda.top/Article/details/gt2auhcszzs.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ybcxt.top/Article/details/gt2wrqrvewk.html

[R72] 等待端口就绪
来源：http://dali.jqgfzy.top/Article/details/gt2tdgmhddf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yuanzhike.top/Article/details/gt2xlnkchkb.html

[R73] 分割大日志
来源：http://dali.xylfe.cn/Article/details/gt2eayprxbc.html

split -l 1000 big.log part_
来源：http://dali.quarkkingdee.top/Article/details/gt2arqykqcl.html

[R74] 批量重命名
来源：http://dali.pengpengdd.cyou/Article/details/gt2ybfgmglm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.tianlin.xyz/Article/details/gt2monjgilu.html

[R75] 导出环境变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2usjwgwse.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hnqzz.top/Article/details/gt2mmgrpsqj.html

[R76] 使用临时文件
来源：http://dali.gzhubu.top/Article/details/gt2gmycuowq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.iojbl.cn/Article/details/gt2qkmbweuw.html

[R77] 读取用户输入
来源：http://dali.jqgufenzy.top/Article/details/gt2giburazd.html

read -rp "请输入: " ans
来源：http://dali.pengpengdd.cyou/Article/details/gt2opkkxmrd.html

[R78] 交互式菜单
来源：http://dali.yuanzhike.top/Article/details/gt2exgalthf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cucudq.cn/Article/details/gt2yutsriou.html

[R79] 解析命令行选项
来源：http://dali.jinqigfzy.top/Article/details/gt2dpalolhg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xuetiantiany.cn/Article/details/gt2fvccqtfz.html

[R80] 查看脚本执行耗时
来源：http://dali.meibo888.top/Article/details/gt2pnldcjpw.html

time ./run.sh
来源：http://dali.sweek.top/Article/details/gt2thhbizka.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jijnmqsc.html

S. C / C++ 专题
来源：http://dali.havefunace.top/Article/details/gt2kyzrejxe.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2fvxsewmz.html

[S01] C：Hello World
来源：http://dali.yvedp.cn/Article/details/gt2srlnwkrz.html

#include <stdio.h>
来源：http://dali.9152youxi.cn/Article/details/gt2fjhxjizr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sweek.top/Article/details/gt2wpclkizn.html

[S02] C：变量与格式化输出
来源：http://dali.hammf.cn/Article/details/gt2cjmbgjvi.html

int a = 10; printf("%d\n", a);
来源：http://dali.dashuyun.cn/Article/details/gt2vivplwbm.html

[S03] C：读入整数
来源：http://dali.fengsongda.top/Article/details/gt2skfchshj.html

int x; scanf("%d", &x);
来源：http://dali.xuetiantiany.cn/Article/details/gt2nivgcywy.html

[S04] C：字符串复制
来源：http://dali.svipenyu.cn/Article/details/gt2rwigzidl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.nwbrower.top/Article/details/gt2nlessmky.html

[S05] C：字符串长度
来源：http://dali.316326.xyz/Article/details/gt2chgkixcq.html

strlen(s)
来源：http://dali.c1oappe.top/Article/details/gt2zrkhjxzp.html

[S06] C：字符串比较
来源：http://dali.smart0.xyz/Article/details/gt2bhkpxnny.html

strcmp(a, b) == 0
来源：http://dali.zdqjudy.top/Article/details/gt2wyztmxdn.html

[S07] C：数组遍历求和
来源：http://dali.zhiwuduotai.top/Article/details/gt2lyxcnsid.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.guannengcc.top/Article/details/gt2mbxtfjqu.html

[S08] C：动态内存分配与释放
来源：http://dali.shangyingyoupin.top/Article/details/gt2yajsxukr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xinyue.icu/Article/details/gt2tpwtkbgp.html

[S09] C：结构体定义与初始化
来源：http://dali.chenjidiqi.icu/Article/details/gt2fbbifhic.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xziqi.cn/Article/details/gt2rqlyafrc.html

[S10] C：指针与解引用
来源：http://dali.aizwys.cn/Article/details/gt2ldontgta.html

int *p = &a;  *p = 5;
来源：http://dali.gaohongyu789.top/Article/details/gt2kaiamqpo.html

[S11] C：逐行读文件
来源：http://dali.andypj.xyz/Article/details/gt2seqzjwvg.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yueranfly.top/Article/details/gt2kzggyecc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cucudq.cn/Article/details/gt2eloucuoy.html

fclose(f);
来源：http://dali.yuxming.cn/Article/details/gt2zzjcwifu.html

[S12] C：写文件
来源：http://dali.jinqigufen.top/Article/details/gt2gchmpeyt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.kuanghao11.cn/Article/details/gt2iwyrmpyp.html

[S13] C：宏定义
来源：http://dali.zhiwuduotai.top/Article/details/gt2sptnxjte.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cqqwz.cn/Article/details/gt2rpcxurfi.html

[S14] C：枚举
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rriflcbo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xziqi.cn/Article/details/gt2sllpfeiv.html

[S15] C：类型转换
来源：http://dali.yuanzhike.top/Article/details/gt2attonpsu.html

(double) a / b
来源：http://dali.xylfe.cn/Article/details/gt2ryfjprzg.html

[S16] C：位操作置位
来源：http://dali.hfpthk.cn/Article/details/gt2rzpryerj.html

x |= (1 << 3);
来源：http://dali.haohaochexian.top/Article/details/gt2lpvcugpn.html

[S17] C：安全拼接字符串
来源：http://dali.haohaochexian.top/Article/details/gt2hxbilmkq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yueranfly.top/Article/details/gt2zuzapaxx.html

[S18] C：命令行参数
来源：http://dali.yvedp.cn/Article/details/gt2easrvdhr.html

int main(int argc, char **argv)
来源：http://dali.pycfn.com/Article/details/gt2vpigzntr.html

[S19] C：快速排序
来源：http://dali.tanke756.top/Article/details/gt2vuwbnxvt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.nwbrower.top/Article/details/gt2sxfmiclm.html

[S20] C：二分查找
来源：http://dali.sweek.top/Article/details/gt2qanfvqmb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xylfe.cn/Article/details/gt2cakbnihz.html

[S21] C：字符类别判断
来源：http://dali.mhx1999.top/Article/details/gt2eksicfrl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zycfv.cn/Article/details/gt2oxjcejlx.html

[S22] C：字符串转数字
来源：http://dali.9152youxi.cn/Article/details/gt2bjnalrdw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.daria6918.cn/Article/details/gt2koicwine.html

[S23] C：随机数
来源：http://dali.hnxiangtu.top/Article/details/gt2lolgsgmw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yueranfly.top/Article/details/gt2fyghrand.html

[S24] C：获取本地时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uuudqjtc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yuanzhike.top/Article/details/gt2whjbmnfm.html

[S25] C：内存拷贝
来源：http://dali.yongpay.top/Article/details/gt2ebviykdw.html

memcpy(dst, src, n);
来源：http://dali.zhiwuduotai.top/Article/details/gt2bevmocfw.html

[S26] C：内存清零
来源：http://dali.nwbrower.top/Article/details/gt2szfwefwy.html

memset(a, 0, sizeof a);
来源：http://dali.yangfankeji.com/Article/details/gt2uekqlxtl.html

[S27] C：定义常量
来源：http://dali.vqdsnc.cn/Article/details/gt2ahqchexw.html

const double PI = 3.14159;
来源：http://dali.iojbl.cn/Article/details/gt2wzkgzoct.html

[S28] C：静态变量
来源：http://dali.birdmap.top/Article/details/gt2noaslknt.html

static int counter = 0;
来源：http://dali.ivvv.top/Article/details/gt2cuwlwjik.html

[S29] C：变参函数
来源：http://dali.tanke756.top/Article/details/gt2zjeoxrla.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.tianlin.xyz/Article/details/gt2eadwxaco.html

[S30] C：头文件保护
来源：http://dali.xinyue.icu/Article/details/gt2osenhhmz.html

#ifndef X_H
来源：http://dali.hnxiangtu.top/Article/details/gt2pwfnxfhe.html

#define X_H
来源：http://dali.tanke756.top/Article/details/gt2qwslfvyj.html

#endif
来源：http://dali.jinqigfzy.top/Article/details/gt2mlokutgo.html

[S31] C++：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gt2sfcsjego.html

#include <iostream>
来源：http://dali.hongshengwenyu.top/Article/details/gt2zvtbgtos.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jyoumei.cn/Article/details/gt2gsbtrehh.html

[S32] C++：字符串
来源：http://dali.aibaodan.cn/Article/details/gt2jnguvkuk.html

std::string s = "hi";  s += "!";
来源：http://dali.gzhubu.top/Article/details/gt2ecgniigi.html

[S33] C++：vector 增删
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uazcrdud.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uvpjquao.html

[S34] C++：遍历 vector
来源：http://dali.yj20258.top/Article/details/gt2qmrxmvon.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.316326.xyz/Article/details/gt2qzuzkloj.html

[S35] C++：map
来源：http://dali.shuidangran.top/Article/details/gt2jjuhfjta.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gt2nlthdzxx.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2vvnivclj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gt2lbnarogb.html

[S37] C++：set
来源：http://dali.guannengcc.top/Article/details/gt2emigssba.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yueranfly.top/Article/details/gt2bgpswkmr.html

[S38] C++：排序
来源：http://dali.nanxinkj.top/Article/details/gt2bhkgsbpw.html

std::sort(v.begin(), v.end());
来源：http://dali.zhengqikj.top/Article/details/gt2zmztcxpg.html

[S39] C++：自定义比较器排序
来源：http://dali.smart0.xyz/Article/details/gt2dsibfhks.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.aibaodan.cn/Article/details/gt2zyrrmcai.html

[S40] C++：查找元素
来源：http://dali.sweek.top/Article/details/gt2jyxdtifn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cheryme.top/Article/details/gt2bmounrhv.html

[S41] C++：类与构造函数
来源：http://dali.cashguo.top/Article/details/gt2yymxyjgc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hammf.cn/Article/details/gt2cirkhhwf.html

[S42] C++：继承与虚函数
来源：http://dali.hysaishi.cn/Article/details/gt2yzpgwffr.html

class B : public Base { public: void f() override {} };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sfsowhxd.html

[S43] C++：智能指针
来源：http://dali.feifeiyinyue.top/Article/details/gt2jjgezejj.html

auto p = std::make_unique<int>(5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2npzlvzqj.html

[S44] C++：引用传参
来源：http://dali.jqgufenzy.top/Article/details/gt2buqxqrhu.html

void inc(int &x) { ++x; }
来源：http://dali.cqqwz.cn/Article/details/gt2kicwilyi.html

[S45] C++：lambda
来源：http://dali.yangfankeji.com/Article/details/gt2kegfvbhi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hnqzz.top/Article/details/gt2dvrolyyv.html

[S46] C++：函数模板
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fawxyhgn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jyoumei.cn/Article/details/gt2rlemionz.html

[S47] C++：结构化绑定遍历
来源：http://dali.xylfe.cn/Article/details/gt2pzfnhhmn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jyoumei.cn/Article/details/gt2vczytcvy.html

[S48] C++：逐行读文件
来源：http://dali.ydzc1.top/Article/details/gt2nlbqfqdh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cashguo.top/Article/details/gt2ynnirrzz.html

while (std::getline(in, line)) { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hdxpwhrm.html

[S49] C++：写文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sjxhgscv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gogol.net.cn/Article/details/gt2xaefuqjk.html

[S50] C++：格式化数字
来源：http://dali.cashguo.top/Article/details/gt2kyrzpvat.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gt2xnckslvl.html

[S51] C++：显式类型转换
来源：http://dali.wangshuangyany.cn/Article/details/gt2aegrcrni.html

static_cast<double>(a) / b
来源：http://dali.ivvv.top/Article/details/gt2iyfhioqk.html

[S52] C++：const 与 noexcept
来源：http://dali.guowangkeji.top/Article/details/gt2jncbpvnb.html

int size() const noexcept { return n_; }
来源：http://dali.hysaishi.cn/Article/details/gt2msaozucy.html

[S53] C++：移动语义
来源：http://dali.jyoumei.cn/Article/details/gt2abyipeau.html

std::vector<int> w = std::move(v);
来源：http://dali.tanke756.top/Article/details/gt2rhfffofd.html

[S54] C++：异常处理
来源：http://dali.zhongyouzk.top/Article/details/gt2fejdzulv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hnqzz.top/Article/details/gt2rbyanhwv.html

[S55] C++：结构化绑定
来源：http://dali.meibo888.top/Article/details/gt2bofswbii.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hfpthk.cn/Article/details/gt2lcspxopx.html

[S56] C++：optional
来源：http://dali.hnqzz.top/Article/details/gt2jftrankw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sweek.top/Article/details/gt2qpanqzar.html

[S57] C++：编译期常量
来源：http://dali.kuanghao11.cn/Article/details/gt2udrhacjp.html

constexpr int N = 10;
来源：http://dali.yonumen.top/Article/details/gt2yqvwoyui.html

[S58] C++：命名空间
来源：http://dali.cashguo.top/Article/details/gt2hcjqcgmu.html

namespace ns { int f() { return 1; } }
来源：http://dali.yonumen.top/Article/details/gt2ztvmkhff.html

[S59] C++：静态断言
来源：http://dali.gaohongyu789.top/Article/details/gt2grigdmux.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.kuanghao11.cn/Article/details/gt2rbvspixs.html

[S60] C++：遍历并删除元素
来源：http://dali.jqgufenzy.top/Article/details/gt2ytkwsaao.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yuzwwqwo.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2ptnywdzc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zdqjudy.top/Article/details/gt2lmxparyj.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2kyhxsrfx.html

[T01] Kotlin：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gt2uvtjioru.html

println("Hello")
来源：http://dali.xziqi.cn/Article/details/gt2dkokbrgx.html

[T02] Kotlin：变量
来源：http://dali.ivvv.top/Article/details/gt2tpjlyivm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gaohongyu789.top/Article/details/gt2vvnuphmg.html

[T03] Kotlin：字符串模板
来源：http://dali.nanxinkj.top/Article/details/gt2vmqopyud.html

"值: $b"
来源：http://dali.yj20258.top/Article/details/gt2fzacoiuc.html

[T04] Kotlin：空安全
来源：http://dali.iojbl.cn/Article/details/gt2dtsbwcif.html

val n: String? = null;  n?.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sbswmght.html

[T05] Kotlin：when 表达式
来源：http://dali.hnxiangtu.top/Article/details/gt2ooyldybs.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhongyouzk.top/Article/details/gt2amrndich.html

[T06] Kotlin：集合映射
来源：http://dali.dashuyun.cn/Article/details/gt2kiixufba.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gaohongyu789.top/Article/details/gt2icpjjifh.html

[T07] Kotlin：集合过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kszmkxud.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gzhubu.top/Article/details/gt2hlabzklm.html

[T08] Kotlin：数据类
来源：http://dali.jqgufenzy.top/Article/details/gt2rgiusdau.html

data class User(val name: String, val age: Int)
来源：http://dali.gzhubu.top/Article/details/gt2dopdrzxa.html

[T09] Kotlin：扩展函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2dtxblvhi.html

fun String.exclaim() = this + "!"
来源：http://dali.feifeiyinyue.top/Article/details/gt2vcftbbri.html

[T10] Kotlin：默认参数
来源：http://dali.haohaochexian.top/Article/details/gt2hziwmlmk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.mhx1999.top/Article/details/gt2egwbvqal.html

[T11] Kotlin：协程
来源：http://dali.yuxming.cn/Article/details/gt2qwnqmfim.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zdqjudy.top/Article/details/gt2abarvyxl.html

[T12] Kotlin：解构声明
来源：http://dali.andypj.xyz/Article/details/gt2noauzuwu.html

val (a, b) = Pair(1, 2)
来源：http://dali.xinyue.icu/Article/details/gt2rjpxfjpp.html

[T13] Kotlin：只读 Map
来源：http://dali.xylfe.cn/Article/details/gt2dqjlscmm.html

val m = mapOf("a" to 1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hzyntnlf.html

[T14] Kotlin：循环
来源：http://dali.cheryme.top/Article/details/gt2iwgeggby.html

for (i in 1..10) println(i)
来源：http://dali.haohaochexian.top/Article/details/gt2wqefmevw.html

[T15] Kotlin：接口
来源：http://dali.nanxinkj.top/Article/details/gt2lvhmvsgp.html

interface Shape { fun area(): Double }
来源：http://dali.ydzc1.top/Article/details/gt2jakilqkl.html

[T16] Swift：Hello World
来源：http://dali.mhx1999.top/Article/details/gt2hccdkfdp.html

print("Hello")
来源：http://dali.sufxvd.cn/Article/details/gt2basixhdd.html

[T17] Swift：变量与常量
来源：http://dali.zdqjudy.top/Article/details/gt2ssxyllhi.html

var a = 1;  let b = 2
来源：http://dali.aibaodan.cn/Article/details/gt2nrxgoajz.html

[T18] Swift：字符串插值
来源：http://dali.fengsongda.top/Article/details/gt2ipllnvlw.html

"值: \(b)"
来源：http://dali.tanke756.top/Article/details/gt2pnhmswwv.html

[T19] Swift：可选绑定
来源：http://dali.gzhubu.top/Article/details/gt2axofyksc.html

if let n = opt { print(n) }
来源：http://dali.cheryme.top/Article/details/gt2ussjmame.html

[T20] Swift：数组操作
来源：http://dali.yuxming.cn/Article/details/gt2aifyusqn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.daria6918.cn/Article/details/gt2awzdghxp.html

[T21] Swift：遍历
来源：http://dali.jiagoushi.top/Article/details/gt2sptfpsty.html

for x in a { print(x) }
来源：http://dali.xylfe.cn/Article/details/gt2yhcdrnqk.html

[T22] Swift：字典
来源：http://dali.quarkkingdee.top/Article/details/gt2dldcesdd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cashguo.top/Article/details/gt2myhmyhgm.html

[T23] Swift：函数
来源：http://dali.yonumen.top/Article/details/gt2lvacwjob.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sufxvd.cn/Article/details/gt2azdippzi.html

[T24] Swift：闭包
来源：http://dali.jqgfzy.top/Article/details/gt2vgbpswko.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.birdmap.top/Article/details/gt2jideuvis.html

[T25] Swift：结构体
来源：http://dali.aizwys.cn/Article/details/gt2pyezkckk.html

struct P { var x: Int }
来源：http://dali.kuanghao11.cn/Article/details/gt2flsxswtg.html

[T26] Swift：类与重写
来源：http://dali.0kj1m.cn/Article/details/gt2dkirkssg.html

class A: Base { override func f() {} }
来源：http://dali.tian-w.cn/Article/details/gt2shkqgqzi.html

[T27] Swift：错误处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bbgqubaw.html

do { try f() } catch { print(error) }
来源：http://dali.havefunace.top/Article/details/gt2hfhyaoay.html

[T28] Swift：枚举
来源：http://dali.bjfxy.top/Article/details/gt2nxsccioz.html

enum Color { case red, green }
来源：http://dali.yanxiufei.cn/Article/details/gt2eebcndvd.html

[T29] Swift：guard 提前返回
来源：http://dali.jqgfzy.top/Article/details/gt2vufcjjzs.html

guard let x = opt else { return }
来源：http://dali.zhengqikj.top/Article/details/gt2ngbsbfiv.html

[T30] Swift：协议
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gescekvz.html

protocol Shape { func area() -> Double }
来源：http://dali.meibo888.top/Article/details/gt2qwqqtbjj.html

[T31] Lua：Hello World
来源：http://dali.fzhhl.top/Article/details/gt2ewcxeueq.html

print("Hello")
来源：http://dali.zhiwuduotai.top/Article/details/gt2fulgrerw.html

[T32] Lua：局部变量
来源：http://dali.yueranfly.top/Article/details/gt2ntqcwlft.html

local a = 1
来源：http://dali.jlsjyb.cn/Article/details/gt2tjilqupw.html

[T33] Lua：表（数组）
来源：http://dali.svipenyu.cn/Article/details/gt2wdoezgdy.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.c1oappe.top/Article/details/gt2ulqiuxpf.html

[T34] Lua：遍历表
来源：http://dali.yuxming.cn/Article/details/gt2jbmoasfl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.cdnleiting.top/Article/details/gt2kqpcmjxw.html

[T35] Lua：字典表
来源：http://dali.sufxvd.cn/Article/details/gt2tnbfrlpu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yangfankeji.com/Article/details/gt2pcvlyjww.html

[T36] Lua：函数
来源：http://dali.zhengqikj.top/Article/details/gt2ykgvbqtw.html

function add(a, b) return a + b end
来源：http://dali.tanke756.top/Article/details/gt2ugeyypir.html

[T37] Lua：字符串拼接
来源：http://dali.hongshengwenyu.top/Article/details/gt2iculmnpg.html

"a" .. "b"
来源：http://dali.chenjidiqi.icu/Article/details/gt2wfaggjjc.html

[T38] Lua：条件
来源：http://dali.xziqi.cn/Article/details/gt2gqmuxsue.html

if x > 0 then print("正") end
来源：http://dali.sufxvd.cn/Article/details/gt2jukibraf.html

[T39] Lua：模式匹配
来源：http://dali.guannengcc.top/Article/details/gt2qzwagxrg.html

string.find(s, "%d+")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ngrkjrlc.html

[T40] Lua：元表
来源：http://dali.tian-w.cn/Article/details/gt2nfowzprc.html

setmetatable({}, { __index = base })
来源：http://dali.haohaochexian.top/Article/details/gt2xgcoxdtp.html

[T41] Perl：Hello World
来源：http://dali.0kj1m.cn/Article/details/gt2zysxizma.html

print "Hello\n";
来源：http://dali.meibo888.top/Article/details/gt2uhlbnbse.html

[T42] Perl：变量类型
来源：http://dali.ivvv.top/Article/details/gt2fycpghyu.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hfpthk.cn/Article/details/gt2ucpmybzp.html

[T43] Perl：字符串插值
来源：http://dali.jinqigufen.top/Article/details/gt2ehrhfbab.html

"值: $a"
来源：http://dali.9152youxi.cn/Article/details/gt2kpdkbmml.html

[T44] Perl：条件
来源：http://dali.xuanzx.com/Article/details/gt2svaqkffi.html

if ($a > 0) { print "正"; }
来源：http://dali.cucudq.cn/Article/details/gt2izehjodj.html

[T45] Perl：数组遍历
来源：http://dali.snrcjt.cn/Article/details/gt2zflifdag.html

for my $x (@arr) { print $x; }
来源：http://dali.yongpay.top/Article/details/gt2pcndlywi.html

[T46] Perl：哈希操作
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uchumnwc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xziqi.cn/Article/details/gt2vkmjsrky.html

[T47] Perl：正则捕获
来源：http://dali.dianchejie.cn/Article/details/gt2aknirerk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.iojbl.cn/Article/details/gt2wkhbnkzn.html

[T48] Perl：正则替换
来源：http://dali.cucudq.cn/Article/details/gt2nxrgluab.html

$s =~ s/old/new/g;
来源：http://dali.dashuyun.cn/Article/details/gt2tmhuclwm.html

[T49] Perl：函数
来源：http://dali.sweek.top/Article/details/gt2opiwqhfu.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jlsjyb.cn/Article/details/gt2bjmsjjhe.html

[T50] Perl：逐行读文件
来源：http://dali.daxiang520.top/Article/details/gt2cgyocmdb.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xuetiantiany.cn/Article/details/gt2lkjdscqk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jianghu66.top/Article/details/gt2qviteqbi.html

[T51] Scala：Hello World
来源：http://dali.ivvv.top/Article/details/gt2mcltbhtm.html

println("Hello")
来源：http://dali.shuidangran.top/Article/details/gt2kvymgkrz.html

[T52] Scala：变量
来源：http://dali.hammf.cn/Article/details/gt2yhicbpbb.html


<!-- 参考信息 -->