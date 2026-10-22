代发 wailian999

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gzhubu.top/Article/details/gt2grrbtked.html

[R52] 统计行数
来源：http://dali.cdnleiting.top/Article/details/gt2bduwnzvx.html

wc -l a.txt
来源：http://dali.daxiang520.top/Article/details/gt2ygecwiny.html

[R53] 查看文件头与实时尾
来源：http://dali.birdmap.top/Article/details/gt2pkxbnhbj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.sufxvd.cn/Article/details/gt2fvxkkomz.html

[R54] 比较两个文件
来源：http://dali.jlsjyb.cn/Article/details/gt2vthnwfae.html

diff a.txt b.txt
来源：http://dali.guowangkeji.top/Article/details/gt2ejectqvw.html

[R55] 压缩与解压
来源：http://dali.ehwqpu.com/Article/details/gt2ydxzwkhl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jyoumei.cn/Article/details/gt2mcpoalgx.html

[R56] 远程拷贝
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iodgegbc.html

scp file user@host:/path/
来源：http://dali.hongshengwenyu.top/Article/details/gt2errxplyd.html

[R57] 远程执行命令
来源：http://dali.cashguo.top/Article/details/gt2npzuiacw.html

ssh user@host 'uptime'
来源：http://dali.tianlin.xyz/Article/details/gt2puxmbcxy.html

[R58] 下载文件
来源：http://dali.gaohongyu789.top/Article/details/gt2iuxxbsdi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hongshengwenyu.top/Article/details/gt2foolwhjb.html

[R59] 发 POST JSON
来源：http://dali.zycfv.cn/Article/details/gt2uypvejfu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhiwuduotai.top/Article/details/gt2tnnxghuh.html

[R60] 只看 HTTP 状态码
来源：http://dali.meibo888.top/Article/details/gt2oaqrwgdy.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shangyingyoupin.top/Article/details/gt2yaocmaag.html

[R61] 磁盘占用
来源：http://dali.tanke756.top/Article/details/gt2jvtthxpv.html

df -h;  du -sh *
来源：http://dali.gogol.net.cn/Article/details/gt2kcmkwioe.html

[R62] 找最占空间的文件
来源：http://dali.jyoumei.cn/Article/details/gt2ckjietah.html

du -ah . | sort -rh | head -10
来源：http://dali.cheryme.top/Article/details/gt2rbjupwwt.html

[R63] 内存与进程
来源：http://dali.guannengcc.top/Article/details/gt2ueeqciky.html

free -h;  ps aux | grep nginx
来源：http://dali.yuanzhike.top/Article/details/gt2ighfcwsp.html

[R64] 结束进程
来源：http://dali.mhx1999.top/Article/details/gt2iaxsoqyk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jinqigfzy.top/Article/details/gt2jrwgrdcy.html

[R65] 查看端口占用
来源：http://dali.jinqigfzy.top/Article/details/gt2kxlbqlbk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yvedp.cn/Article/details/gt2rpjjteqb.html

[R66] 定时任务
来源：http://dali.dashuyun.cn/Article/details/gt2mwtphjfr.html

crontab -e;  crontab -l
来源：http://dali.jlsjyb.cn/Article/details/gt2ktibzfoh.html

[R67] 生成随机十六进制串
来源：http://dali.jqgfzy.top/Article/details/gt2hnmahdlv.html

openssl rand -hex 16
来源：http://dali.snrcjt.cn/Article/details/gt2olewbcyh.html

[R68] 计算文件校验值
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zljazses.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhixingplan.top/Article/details/gt2bwhfcdpu.html

[R69] 生成随机密码
来源：http://dali.hywenlv.cn/Article/details/gt2kjbblzhl.html

head -c 16 /dev/urandom | base64
来源：http://dali.tianlin.xyz/Article/details/gt2goqnzsxm.html

[R70] 时间戳与互转
来源：http://dali.kuanghao11.cn/Article/details/gt2dxwxssmq.html

date +%s;  date -d @1700000000
来源：http://dali.shzxlz.cn/Article/details/gt2jocwnoll.html

[R71] 日期格式化
来源：http://dali.jlsjyb.cn/Article/details/gt2jgbpyjgm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cheryme.top/Article/details/gt2jlfejupn.html

[R72] 等待端口就绪
来源：http://dali.zhixingplan.top/Article/details/gt2mlviveok.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cqqwz.cn/Article/details/gt2ytdbbzyc.html

[R73] 分割大日志
来源：http://dali.fengsongda.top/Article/details/gt2hntohzlz.html

split -l 1000 big.log part_
来源：http://dali.iojbl.cn/Article/details/gt2wzuthmxb.html

[R74] 批量重命名
来源：http://dali.dianchejie.cn/Article/details/gt2fdpcvgyy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hysaishi.cn/Article/details/gt2tabsltlt.html

[R75] 导出环境变量
来源：http://dali.xuanzx.com/Article/details/gt2ufggstpx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jqgufenzy.top/Article/details/gt2qcfmknbf.html

[R76] 使用临时文件
来源：http://dali.sweek.top/Article/details/gt2jgvqkzsh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.tian-w.cn/Article/details/gt2rzdxtnfy.html

[R77] 读取用户输入
来源：http://dali.ehwqpu.com/Article/details/gt2illsjaux.html

read -rp "请输入: " ans
来源：http://dali.cashguo.top/Article/details/gt2arawqzft.html

[R78] 交互式菜单
来源：http://dali.feifeiyinyue.top/Article/details/gt2lhojweug.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xuanzx.com/Article/details/gt2upijfmkf.html

[R79] 解析命令行选项
来源：http://dali.gzhubu.top/Article/details/gt2zlsgujhf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yangfankeji.com/Article/details/gt2teruplju.html

[R80] 查看脚本执行耗时
来源：http://dali.dianchejie.cn/Article/details/gt2tpiguboq.html

time ./run.sh
来源：http://dali.yuanzhike.top/Article/details/gt2woosjiuw.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2vdfbgnah.html

S. C / C++ 专题
来源：http://dali.316326.xyz/Article/details/gt2xkdpczba.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2hwcaglvh.html

[S01] C：Hello World
来源：http://dali.c1oappe.top/Article/details/gt2usojdjtx.html

#include <stdio.h>
来源：http://dali.shangyingyoupin.top/Article/details/gt2slhdaihp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hfpthk.cn/Article/details/gt2vydatbek.html

[S02] C：变量与格式化输出
来源：http://dali.kuanghao11.cn/Article/details/gt2ulsdkkfk.html

int a = 10; printf("%d\n", a);
来源：http://dali.shzxlz.cn/Article/details/gt2qgmburjz.html

[S03] C：读入整数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vvmcghdj.html

int x; scanf("%d", &x);
来源：http://dali.jlsjyb.cn/Article/details/gt2svbqunoi.html

[S04] C：字符串复制
来源：http://dali.sysykeji.top/Article/details/gt2acjzvszf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yanxiufei.cn/Article/details/gt2wwdcoiov.html

[S05] C：字符串长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2herrdlpj.html

strlen(s)
来源：http://dali.yonumen.top/Article/details/gt2ounrkftc.html

[S06] C：字符串比较
来源：http://dali.cashguo.top/Article/details/gt2aceqywle.html

strcmp(a, b) == 0
来源：http://dali.xziqi.cn/Article/details/gt2orxeouyt.html

[S07] C：数组遍历求和
来源：http://dali.cashguo.top/Article/details/gt2ucprbona.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.smart0.xyz/Article/details/gt2bgmscods.html

[S08] C：动态内存分配与释放
来源：http://dali.meibo888.top/Article/details/gt2vebkdhvs.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cdnleiting.top/Article/details/gt2pwlrfkml.html

[S09] C：结构体定义与初始化
来源：http://dali.gotoacloud.top/Article/details/gt2ujwwcxee.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yueranfly.top/Article/details/gt2tvotrjqq.html

[S10] C：指针与解引用
来源：http://dali.yueranfly.top/Article/details/gt2qbsjzckx.html

int *p = &a;  *p = 5;
来源：http://dali.gotoacloud.top/Article/details/gt2bpnzqyie.html

[S11] C：逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gt2qmxswdiv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.birdmap.top/Article/details/gt2uehslbqc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hsdohhww.html

fclose(f);
来源：http://dali.dashuyun.cn/Article/details/gt2khqqqjvy.html

[S12] C：写文件
来源：http://dali.meibo888.top/Article/details/gt2htsrxikr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hysaishi.cn/Article/details/gt2miffsfij.html

[S13] C：宏定义
来源：http://dali.chenlongwang.top/Article/details/gt2kpurilaj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yanxiufei.cn/Article/details/gt2buriryyl.html

[S14] C：枚举
来源：http://dali.ehwqpu.com/Article/details/gt2rgctlwek.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.meibo888.top/Article/details/gt2wepmyfwj.html

[S15] C：类型转换
来源：http://dali.ehwqpu.com/Article/details/gt2hwlwzyrk.html

(double) a / b
来源：http://dali.zhiwuduotai.top/Article/details/gt2tcuavtob.html

[S16] C：位操作置位
来源：http://dali.nanxinkj.top/Article/details/gt2nlqskame.html

x |= (1 << 3);
来源：http://dali.yanxiufei.cn/Article/details/gt2mewajwpq.html

[S17] C：安全拼接字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2asyjmnsw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yiyyechf.html

[S18] C：命令行参数
来源：http://dali.quarkkingdee.top/Article/details/gt2golxergx.html

int main(int argc, char **argv)
来源：http://dali.haohaochexian.top/Article/details/gt2iyutdmnu.html

[S19] C：快速排序
来源：http://dali.ehwqpu.com/Article/details/gt2nemrieep.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.fzhhl.top/Article/details/gt2dyybxmuk.html

[S20] C：二分查找
来源：http://dali.chenzaomai.com/Article/details/gt2moairywm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.nwbrower.top/Article/details/gt2kcropjdo.html

[S21] C：字符类别判断
来源：http://dali.mhx1999.top/Article/details/gt2srrmupzu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yueranfly.top/Article/details/gt2tsspbosl.html

[S22] C：字符串转数字
来源：http://dali.sufxvd.cn/Article/details/gt2xvkitdrl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ockcwjci.html

[S23] C：随机数
来源：http://dali.zhoulong.xyz/Article/details/gt2uyzllbnl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.guowangkeji.top/Article/details/gt2vytjodty.html

[S24] C：获取本地时间
来源：http://dali.sufxvd.cn/Article/details/gt2dzptozus.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhoulong.xyz/Article/details/gt2jmzdtoxs.html

[S25] C：内存拷贝
来源：http://dali.sufxvd.cn/Article/details/gt2wwvqnipi.html

memcpy(dst, src, n);
来源：http://dali.jqgufenzy.top/Article/details/gt2wrvbvcjv.html

[S26] C：内存清零
来源：http://dali.nwbrower.top/Article/details/gt2fwhcdksi.html

memset(a, 0, sizeof a);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iinorcsv.html

[S27] C：定义常量
来源：http://dali.cucudq.cn/Article/details/gt2fivschst.html

const double PI = 3.14159;
来源：http://dali.316326.xyz/Article/details/gt2kkgnrbpf.html

[S28] C：静态变量
来源：http://dali.ivvv.top/Article/details/gt2gewtuhtm.html

static int counter = 0;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wrtkdyxi.html

[S29] C：变参函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2gjetierw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.dashuyun.cn/Article/details/gt2pkgemvyy.html

[S30] C：头文件保护
来源：http://dali.nwbrower.top/Article/details/gt2erhlgctl.html

#ifndef X_H
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yzrtncci.html

#define X_H
来源：http://dali.mhx1999.top/Article/details/gt2iosjcaqu.html

#endif
来源：http://dali.tian-w.cn/Article/details/gt2kibufqwy.html

[S31] C++：Hello World
来源：http://dali.hysaishi.cn/Article/details/gt2pfbwswgr.html

#include <iostream>
来源：http://dali.xinyue.icu/Article/details/gt2wxtialjd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yangfankeji.com/Article/details/gt2otlidshf.html

[S32] C++：字符串
来源：http://dali.zycfv.cn/Article/details/gt2mlnbavfz.html

std::string s = "hi";  s += "!";
来源：http://dali.zhixingplan.top/Article/details/gt2rygiitid.html

[S33] C++：vector 增删
来源：http://dali.dianchejie.cn/Article/details/gt2tbptjijn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhengqikj.top/Article/details/gt2kskapbrv.html

[S34] C++：遍历 vector
来源：http://dali.daxiang520.top/Article/details/gt2rxuwbgrn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ehwqpu.com/Article/details/gt2erswjbor.html

[S35] C++：map
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xucuekrl.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhoulong.xyz/Article/details/gt2vttdklzb.html

[S36] C++：unordered_map
来源：http://dali.316326.xyz/Article/details/gt2nwwdjmwu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ppjwa.cn/Article/details/gt2mqsyvuzl.html

[S37] C++：set
来源：http://dali.xziqi.cn/Article/details/gt2aotaywzu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hnqzz.top/Article/details/gt2zdeuvyui.html

[S38] C++：排序
来源：http://dali.9152youxi.cn/Article/details/gt2oujwkked.html

std::sort(v.begin(), v.end());
来源：http://dali.cdnleiting.top/Article/details/gt2mvdvmsdd.html

[S39] C++：自定义比较器排序
来源：http://dali.xinyue.icu/Article/details/gt2uykwljxb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hnxiangtu.top/Article/details/gt2nrzcuccf.html

[S40] C++：查找元素
来源：http://dali.svipenyu.cn/Article/details/gt2dewdfqsx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hammf.cn/Article/details/gt2vxnkgdod.html

[S41] C++：类与构造函数
来源：http://dali.zhengqikj.top/Article/details/gt2qtybrlmt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.vqdsnc.cn/Article/details/gt2ttynowld.html

[S42] C++：继承与虚函数
来源：http://dali.gzhubu.top/Article/details/gt2ltqjqwtp.html

class B : public Base { public: void f() override {} };
来源：http://dali.redwolf501.top/Article/details/gt2mpnbjexx.html

[S43] C++：智能指针
来源：http://dali.yonumen.top/Article/details/gt2kwwihkew.html

auto p = std::make_unique<int>(5);
来源：http://dali.mhx1999.top/Article/details/gt2oeehhmdd.html

[S44] C++：引用传参
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xlslyilk.html

void inc(int &x) { ++x; }
来源：http://dali.snrcjt.cn/Article/details/gt2puianvxr.html

[S45] C++：lambda
来源：http://dali.hysaishi.cn/Article/details/gt2qubtrgzq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gaohongyu789.top/Article/details/gt2mhksfhuj.html

[S46] C++：函数模板
来源：http://dali.bjfxy.top/Article/details/gt2jndiqixn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sufxvd.cn/Article/details/gt2lnvqrtnc.html

[S47] C++：结构化绑定遍历
来源：http://dali.vqdsnc.cn/Article/details/gt2sqvlixzp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.vqdsnc.cn/Article/details/gt2zaguqcay.html

[S48] C++：逐行读文件
来源：http://dali.nwbrower.top/Article/details/gt2nlfpygep.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gotoacloud.top/Article/details/gt2lkykjxez.html

while (std::getline(in, line)) { }
来源：http://dali.meibo888.top/Article/details/gt2eimjksbn.html

[S49] C++：写文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hlrnflcp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.tian-w.cn/Article/details/gt2nitjgppg.html

[S50] C++：格式化数字
来源：http://dali.yueranfly.top/Article/details/gt2ymlmhbob.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cucudq.cn/Article/details/gt2fgolmetu.html

[S51] C++：显式类型转换
来源：http://dali.tian-w.cn/Article/details/gt2ghlpkolx.html

static_cast<double>(a) / b
来源：http://dali.yueranfly.top/Article/details/gt2zhbgpbqn.html

[S52] C++：const 与 noexcept
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uvjlggmd.html

int size() const noexcept { return n_; }
来源：http://dali.hywenlv.cn/Article/details/gt2ikusoscx.html

[S53] C++：移动语义
来源：http://dali.sysykeji.top/Article/details/gt2jfdtigvq.html

std::vector<int> w = std::move(v);
来源：http://dali.yangfankeji.com/Article/details/gt2xudubohi.html

[S54] C++：异常处理
来源：http://dali.hnxiangtu.top/Article/details/gt2tqkuizce.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.andypj.xyz/Article/details/gt2jixvhmaw.html

[S55] C++：结构化绑定
来源：http://dali.hammf.cn/Article/details/gt2nnlmbljb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.tian-w.cn/Article/details/gt2serootqi.html

[S56] C++：optional
来源：http://dali.jianghu66.top/Article/details/gt2nlfzgqkv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hnqzz.top/Article/details/gt2ucgrqagh.html

[S57] C++：编译期常量
来源：http://dali.quarkkingdee.top/Article/details/gt2trfiruxq.html

constexpr int N = 10;
来源：http://dali.nwbrower.top/Article/details/gt2tseypvgg.html

[S58] C++：命名空间
来源：http://dali.hysaishi.cn/Article/details/gt2ztdgfwef.html

namespace ns { int f() { return 1; } }
来源：http://dali.yj202588.top/Article/details/gt2ykaepgjv.html

[S59] C++：静态断言
来源：http://dali.daxiang520.top/Article/details/gt2udmxfafi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cdnleiting.top/Article/details/gt2gojfnqrf.html

[S60] C++：遍历并删除元素
来源：http://dali.cdnleiting.top/Article/details/gt2garzpchw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.pengpengdd.cyou/Article/details/gt2lpseflqj.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2ndezenpy.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.kuanghao11.cn/Article/details/gt2kmqlanba.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2bkywvtff.html

[T01] Kotlin：Hello World
来源：http://dali.xuanzx.com/Article/details/gt2joqpgqqw.html

println("Hello")
来源：http://dali.jqgfzy.top/Article/details/gt2nzxtcmdw.html

[T02] Kotlin：变量
来源：http://dali.cheryme.top/Article/details/gt2hdueyjkg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jyoumei.cn/Article/details/gt2yrbggjts.html

[T03] Kotlin：字符串模板
来源：http://dali.zhixingplan.top/Article/details/gt2ololeizm.html

"值: $b"
来源：http://dali.quarkkingdee.top/Article/details/gt2psixyidk.html

[T04] Kotlin：空安全
来源：http://dali.meibo888.top/Article/details/gt2ftblxrgj.html

val n: String? = null;  n?.length
来源：http://dali.yongpay.top/Article/details/gt2xsnhkucs.html

[T05] Kotlin：when 表达式
来源：http://dali.jyoumei.cn/Article/details/gt2itsswjgf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.wangdashe.top/Article/details/gt2onophmxi.html

[T06] Kotlin：集合映射
来源：http://dali.feifeiyinyue.top/Article/details/gt2nrsuoeoj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gt2tdtdtwbn.html

[T07] Kotlin：集合过滤
来源：http://dali.sufxvd.cn/Article/details/gt2ddrsdfbn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ybcxt.top/Article/details/gt2dwaophiw.html

[T08] Kotlin：数据类
来源：http://dali.hywenlv.cn/Article/details/gt2iqjtizml.html

data class User(val name: String, val age: Int)
来源：http://dali.gaohongyu789.top/Article/details/gt2tlqkcjpo.html

[T09] Kotlin：扩展函数
来源：http://dali.guowangkeji.top/Article/details/gt2jlohztjk.html

fun String.exclaim() = this + "!"
来源：http://dali.cheryme.top/Article/details/gt2diezqlpg.html

[T10] Kotlin：默认参数
来源：http://dali.sufxvd.cn/Article/details/gt2omfylifk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qvzjvejt.html

[T11] Kotlin：协程
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nzjvfmpc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.kuanghao11.cn/Article/details/gt2qlqkgejw.html

[T12] Kotlin：解构声明
来源：http://dali.9152youxi.cn/Article/details/gt2mxtyfevq.html

val (a, b) = Pair(1, 2)
来源：http://dali.birdmap.top/Article/details/gt2dkkuakao.html

[T13] Kotlin：只读 Map
来源：http://dali.shangyingyoupin.top/Article/details/gt2hjpjofwa.html

val m = mapOf("a" to 1)
来源：http://dali.ppjwa.cn/Article/details/gt2hirvccot.html

[T14] Kotlin：循环
来源：http://dali.gogol.net.cn/Article/details/gt2oqxamtlq.html

for (i in 1..10) println(i)
来源：http://dali.wangshuangyany.cn/Article/details/gt2swjovkmv.html

[T15] Kotlin：接口
来源：http://dali.dashuyun.cn/Article/details/gt2mdzwcmao.html

interface Shape { fun area(): Double }
来源：http://dali.yvedp.cn/Article/details/gt2yvmkgjyr.html

[T16] Swift：Hello World
来源：http://dali.yj20258.top/Article/details/gt2znikdnmy.html

print("Hello")
来源：http://dali.c1oappe.top/Article/details/gt2iqilcvtc.html

[T17] Swift：变量与常量
来源：http://dali.jinqigfzy.top/Article/details/gt2ioxibcqv.html

var a = 1;  let b = 2
来源：http://dali.9152youxi.cn/Article/details/gt2sugbbqqx.html

[T18] Swift：字符串插值
来源：http://dali.iojbl.cn/Article/details/gt2xtuyukzq.html

"值: \(b)"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xjwuvlat.html

[T19] Swift：可选绑定
来源：http://dali.316326.xyz/Article/details/gt2tphmzecu.html

if let n = opt { print(n) }
来源：http://dali.jqgfzy.top/Article/details/gt2mnvpnqwn.html

[T20] Swift：数组操作
来源：http://dali.hnqzz.top/Article/details/gt2lbpkyiab.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cdnleiting.top/Article/details/gt2cgzitmyv.html

[T21] Swift：遍历
来源：http://dali.hywenlv.cn/Article/details/gt2tflxpmxw.html

for x in a { print(x) }
来源：http://dali.chenzaomai.com/Article/details/gt2jjhuurvj.html

[T22] Swift：字典
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jhxrcjyi.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jinqigfzy.top/Article/details/gt2dwgavaft.html

[T23] Swift：函数
来源：http://dali.zdqjudy.top/Article/details/gt2phgmuysy.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yj202588.top/Article/details/gt2qmxqhwxb.html

[T24] Swift：闭包
来源：http://dali.yangfankeji.com/Article/details/gt2nvksmvdq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jiagoushi.top/Article/details/gt2bnfcjrbr.html

[T25] Swift：结构体
来源：http://dali.tian-w.cn/Article/details/gt2vfxrlcpg.html

struct P { var x: Int }
来源：http://dali.hysaishi.cn/Article/details/gt2thkbqgiy.html

[T26] Swift：类与重写
来源：http://dali.jlsjyb.cn/Article/details/gt2vbgmumlx.html

class A: Base { override func f() {} }
来源：http://dali.cqqwz.cn/Article/details/gt2jnpjblfc.html

[T27] Swift：错误处理
来源：http://dali.gogol.net.cn/Article/details/gt2tfggkwpe.html

do { try f() } catch { print(error) }
来源：http://dali.shangyingyoupin.top/Article/details/gt2mwlrzlkj.html

[T28] Swift：枚举
来源：http://dali.hongshengwenyu.top/Article/details/gt2eyoxfghz.html

enum Color { case red, green }
来源：http://dali.sxryk.cn/Article/details/gt2tkdachwy.html

[T29] Swift：guard 提前返回
来源：http://dali.yangfankeji.com/Article/details/gt2aslmjtbt.html

guard let x = opt else { return }
来源：http://dali.zdqjudy.top/Article/details/gt2kabyxtor.html

[T30] Swift：协议
来源：http://dali.xylfe.cn/Article/details/gt2zfjasxyg.html

protocol Shape { func area() -> Double }
来源：http://dali.hywenlv.cn/Article/details/gt2mbetmfze.html

[T31] Lua：Hello World
来源：http://dali.havefunace.top/Article/details/gt2xniaurpi.html

print("Hello")
来源：http://dali.yangfankeji.com/Article/details/gt2wkyikxiq.html

[T32] Lua：局部变量
来源：http://dali.dianchejie.cn/Article/details/gt2apdihlpe.html

local a = 1
来源：http://dali.yangfankeji.com/Article/details/gt2pvurxyhx.html

[T33] Lua：表（数组）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ctfwvwni.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.bjfxy.top/Article/details/gt2jovsapsb.html

[T34] Lua：遍历表
来源：http://dali.cashguo.top/Article/details/gt2pvstpyez.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.cqqwz.cn/Article/details/gt2ypziubzk.html

[T35] Lua：字典表
来源：http://dali.hywenlv.cn/Article/details/gt2lhveftpa.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhengqikj.top/Article/details/gt2vdddgeny.html

[T36] Lua：函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ffrgkogq.html

function add(a, b) return a + b end
来源：http://dali.fzhhl.top/Article/details/gt2rhtwufjd.html

[T37] Lua：字符串拼接
来源：http://dali.yongpay.top/Article/details/gt2sewipkdo.html

"a" .. "b"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uzhrpgxh.html

[T38] Lua：条件
来源：http://dali.yueranfly.top/Article/details/gt2yzfpzvhd.html

if x > 0 then print("正") end
来源：http://dali.xinyue.icu/Article/details/gt2mtjracuw.html

[T39] Lua：模式匹配
来源：http://dali.cheryme.top/Article/details/gt2xargyluf.html

string.find(s, "%d+")
来源：http://dali.havefunace.top/Article/details/gt2pdfbbalp.html

[T40] Lua：元表
来源：http://dali.nanxinkj.top/Article/details/gt2flaoubch.html

setmetatable({}, { __index = base })
来源：http://dali.dianchejie.cn/Article/details/gt2zycgoxao.html

[T41] Perl：Hello World
来源：http://dali.wangdashe.top/Article/details/gt2ieztryot.html

print "Hello\n";
来源：http://dali.nanxinkj.top/Article/details/gt2jedulgsi.html

[T42] Perl：变量类型
来源：http://dali.jqgfzy.top/Article/details/gt2sdgqytxh.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.daxiang520.top/Article/details/gt2sulsblth.html

[T43] Perl：字符串插值
来源：http://dali.hammf.cn/Article/details/gt2kzowmohy.html

"值: $a"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mbsxflah.html

[T44] Perl：条件
来源：http://dali.nwbrower.top/Article/details/gt2tcgzvdng.html

if ($a > 0) { print "正"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2dpldxagd.html

[T45] Perl：数组遍历
来源：http://dali.yanxiufei.cn/Article/details/gt2aairoslc.html

for my $x (@arr) { print $x; }
来源：http://dali.haohaochexian.top/Article/details/gt2jslbcsjt.html

[T46] Perl：哈希操作
来源：http://dali.hysaishi.cn/Article/details/gt2rpepouyg.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jinqigufen.top/Article/details/gt2tkdqkuwm.html

[T47] Perl：正则捕获
来源：http://dali.zhiwuduotai.top/Article/details/gt2ezditjzy.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.wangdashe.top/Article/details/gt2etdlwblb.html

[T48] Perl：正则替换
来源：http://dali.xuetiantiany.cn/Article/details/gt2igwvutfq.html

$s =~ s/old/new/g;
来源：http://dali.daria6918.cn/Article/details/gt2eosodgep.html

[T49] Perl：函数
来源：http://dali.yj202588.top/Article/details/gt2nxcfvtyj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.nwbrower.top/Article/details/gt2honwhqgv.html

[T50] Perl：逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gt2ersdyauw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yongpay.top/Article/details/gt2xbqjtvxs.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hnxiangtu.top/Article/details/gt2zmaalnam.html

[T51] Scala：Hello World
来源：http://dali.sufxvd.cn/Article/details/gt2xerrtgvk.html

println("Hello")
来源：http://dali.yonumen.top/Article/details/gt2tsatbima.html

[T52] Scala：变量
来源：http://dali.smart0.xyz/Article/details/gt2bbdydzly.html

val a = 1;  var b = 2
来源：http://dali.tian-w.cn/Article/details/gt2nzdcztme.html

[T53] Scala：字符串插值
来源：http://dali.316326.xyz/Article/details/gt2cwbnpwjm.html

s"值: $b"
来源：http://dali.meibo888.top/Article/details/gt2asokukjl.html

[T54] Scala：集合映射
来源：http://dali.feifeiyinyue.top/Article/details/gt2ldppzayn.html


<!-- 参考信息 -->