代发 wailian999

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hfpthk.cn/Article/details/gtmkjmaqyc.html

[R52] 统计行数
来源：http://dali.hongshengwenyu.top/Article/details/gtsxuaitrm.html

wc -l a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gteodrdowi.html

[R53] 查看文件头与实时尾
来源：http://dali.cashguo.top/Article/details/gtgkjqnsmr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hongshengwenyu.top/Article/details/gtnnixgqwh.html

[R54] 比较两个文件
来源：http://dali.pengpengdd.cyou/Article/details/gtjqazliwd.html

diff a.txt b.txt
来源：http://dali.9152youxi.cn/Article/details/gtfrzdjqzn.html

[R55] 压缩与解压
来源：http://dali.guannengcc.top/Article/details/gtlussglrj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.dashuyun.cn/Article/details/gtqlepemqr.html

[R56] 远程拷贝
来源：http://dali.sysykeji.top/Article/details/gtdvhfjtwx.html

scp file user@host:/path/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjpszzzla.html

[R57] 远程执行命令
来源：http://dali.hongshengwenyu.top/Article/details/gtfnuwsjzr.html

ssh user@host 'uptime'
来源：http://dali.jinqigufen.top/Article/details/gtptxhlbkc.html

[R58] 下载文件
来源：http://dali.jyoumei.cn/Article/details/gtmgcssksi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xziqi.cn/Article/details/gttsmbouyo.html

[R59] 发 POST JSON
来源：http://dali.jiagoushi.top/Article/details/gtnmkyfylk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cheryme.top/Article/details/gtmfirnqtq.html

[R60] 只看 HTTP 状态码
来源：http://dali.fzhhl.top/Article/details/gthhzzqbeq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.haohaochexian.top/Article/details/gtuodbvxvs.html

[R61] 磁盘占用
来源：http://dali.hammf.cn/Article/details/gtmozorhab.html

df -h;  du -sh *
来源：http://dali.gogol.net.cn/Article/details/gtjwugbdzv.html

[R62] 找最占空间的文件
来源：http://dali.havefunace.top/Article/details/gtoscwkudq.html

du -ah . | sort -rh | head -10
来源：http://dali.yanxiufei.cn/Article/details/gtfaixdqmz.html

[R63] 内存与进程
来源：http://dali.cucudq.cn/Article/details/gtosjhdqps.html

free -h;  ps aux | grep nginx
来源：http://dali.tianlin.xyz/Article/details/gtaffbrjin.html

[R64] 结束进程
来源：http://dali.zhoulong.xyz/Article/details/gttyzgccbh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.wangdashe.top/Article/details/gtshrxzter.html

[R65] 查看端口占用
来源：http://dali.cheryme.top/Article/details/gtbzlrcnqa.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.feifeiyinyue.top/Article/details/gttpuadoqu.html

[R66] 定时任务
来源：http://dali.yj20258888.top/Article/details/gtrjnaatvn.html

crontab -e;  crontab -l
来源：http://dali.cashguo.top/Article/details/gtmwxpjezi.html

[R67] 生成随机十六进制串
来源：http://dali.gzhubu.top/Article/details/gtwixghxos.html

openssl rand -hex 16
来源：http://dali.pycfn.com/Article/details/gtjmbjevsl.html

[R68] 计算文件校验值
来源：http://dali.yonumen.top/Article/details/gtpepulgsb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ppjwa.cn/Article/details/gtfazwjhzm.html

[R69] 生成随机密码
来源：http://dali.dianchejie.cn/Article/details/gtnwvvenay.html

head -c 16 /dev/urandom | base64
来源：http://dali.hysaishi.cn/Article/details/gtdkifuoyr.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gtuechpktc.html

date +%s;  date -d @1700000000
来源：http://dali.kuanghao11.cn/Article/details/gtzmdodmna.html

[R71] 日期格式化
来源：http://dali.wangdashe.top/Article/details/gtnfnlkrly.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.meibo888.top/Article/details/gteaycgdky.html

[R72] 等待端口就绪
来源：http://dali.yj20258888.top/Article/details/gtewisfhgx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.nwbrower.top/Article/details/gtwjvvpqrg.html

[R73] 分割大日志
来源：http://dali.sufxvd.cn/Article/details/gtjhxvclkz.html

split -l 1000 big.log part_
来源：http://dali.yanxiufei.cn/Article/details/gtxrmdcymf.html

[R74] 批量重命名
来源：http://dali.yanxiufei.cn/Article/details/gteegtrzfh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.tian-w.cn/Article/details/gthimqnegn.html

[R75] 导出环境变量
来源：http://dali.jianghu66.top/Article/details/gtzqqkdfgl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.dianchejie.cn/Article/details/gtegstxvzh.html

[R76] 使用临时文件
来源：http://dali.chenlongwang.top/Article/details/gtwhaklxdn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.sweek.top/Article/details/gtmgnefkve.html

[R77] 读取用户输入
来源：http://dali.ppjwa.cn/Article/details/gtnlzzdpfa.html

read -rp "请输入: " ans
来源：http://dali.yuxming.cn/Article/details/gttqkoqmgj.html

[R78] 交互式菜单
来源：http://dali.yangfankeji.com/Article/details/gtgcapzskm.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.nanxinkj.top/Article/details/gttlzrpjxh.html

[R79] 解析命令行选项
来源：http://dali.sysykeji.top/Article/details/gtuaisehpz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.guannengcc.top/Article/details/gtgzztyogu.html

[R80] 查看脚本执行耗时
来源：http://dali.mhx1999.top/Article/details/gttdhhkvxt.html

time ./run.sh
来源：http://dali.svipenyu.cn/Article/details/gtjirkituk.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtrifscdnn.html

S. C / C++ 专题
来源：http://dali.gaohongyu789.top/Article/details/gtaroyoonj.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtemocvacr.html

[S01] C：Hello World
来源：http://dali.xziqi.cn/Article/details/gtfvilgiua.html

#include <stdio.h>
来源：http://dali.andypj.xyz/Article/details/gtaudsibdf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sweek.top/Article/details/gtiqttxoph.html

[S02] C：变量与格式化输出
来源：http://dali.yueranfly.top/Article/details/gtemwudjqm.html

int a = 10; printf("%d\n", a);
来源：http://dali.ehwqpu.com/Article/details/gtdglxziee.html

[S03] C：读入整数
来源：http://dali.tanke756.top/Article/details/gtrpfbozwg.html

int x; scanf("%d", &x);
来源：http://dali.quarkkingdee.top/Article/details/gtkgeydzfx.html

[S04] C：字符串复制
来源：http://dali.shanyushiyangkeji.top/Article/details/gthgjjoslz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgshwcwyl.html

[S05] C：字符串长度
来源：http://dali.shangyingyoupin.top/Article/details/gtyeuqzobq.html

strlen(s)
来源：http://dali.c1oappe.top/Article/details/gtlannrkva.html

[S06] C：字符串比较
来源：http://dali.feifeiyinyue.top/Article/details/gtcgktdxxp.html

strcmp(a, b) == 0
来源：http://dali.dashuyun.cn/Article/details/gtikidjygv.html

[S07] C：数组遍历求和
来源：http://dali.jinqigufen.top/Article/details/gtyrtnlhlw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.redwolf501.top/Article/details/gtpxgwdnxb.html

[S08] C：动态内存分配与释放
来源：http://dali.pengpengdd.cyou/Article/details/gthigglegx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sxryk.cn/Article/details/gtrzbqryxb.html

[S09] C：结构体定义与初始化
来源：http://dali.aizwys.cn/Article/details/gtcgdbocpz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.dianchejie.cn/Article/details/gtkaasrwbw.html

[S10] C：指针与解引用
来源：http://dali.yuanzhike.top/Article/details/gtwvzougbo.html

int *p = &a;  *p = 5;
来源：http://dali.xinyue.icu/Article/details/gtezjtxqik.html

[S11] C：逐行读文件
来源：http://dali.ivvv.top/Article/details/gtsizkhqzr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmzfvqvct.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.tianlin.xyz/Article/details/gtzyteutpj.html

fclose(f);
来源：http://dali.jianghu66.top/Article/details/gtofainspw.html

[S12] C：写文件
来源：http://dali.nwbrower.top/Article/details/gtbdttxczv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.316326.xyz/Article/details/gtxbznvxya.html

[S13] C：宏定义
来源：http://dali.jinqigfzy.top/Article/details/gtxsaolalx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.andypj.xyz/Article/details/gtlqlaxymo.html

[S14] C：枚举
来源：http://dali.yvedp.cn/Article/details/gtltqzoiyc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yonumen.top/Article/details/gtlylymbuh.html

[S15] C：类型转换
来源：http://dali.jqgfzy.top/Article/details/gtpjwaflcs.html

(double) a / b
来源：http://dali.zhoulong.xyz/Article/details/gttwzerxey.html

[S16] C：位操作置位
来源：http://dali.aibaodan.cn/Article/details/gtannwlqte.html

x |= (1 << 3);
来源：http://dali.kuanghao11.cn/Article/details/gtirhbrxzh.html

[S17] C：安全拼接字符串
来源：http://dali.pycfn.com/Article/details/gtmozucugt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.pycfn.com/Article/details/gtbfxhalgl.html

[S18] C：命令行参数
来源：http://dali.nanxuanxn.top/Article/details/gtrbitjgdr.html

int main(int argc, char **argv)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtowixoyfl.html

[S19] C：快速排序
来源：http://dali.tianlin.xyz/Article/details/gtkxlramwm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xuanzx.com/Article/details/gttyauwjnm.html

[S20] C：二分查找
来源：http://dali.jinqigufen.top/Article/details/gtwgmfhthd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.dashuyun.cn/Article/details/gtboctcfpx.html

[S21] C：字符类别判断
来源：http://dali.xuanzx.com/Article/details/gtvwerkygi.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.birdmap.top/Article/details/gtcnxtinfu.html

[S22] C：字符串转数字
来源：http://dali.chenlongwang.top/Article/details/gtrbrspcyi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.meibo888.top/Article/details/gtmvjrhrmj.html

[S23] C：随机数
来源：http://dali.feifeiyinyue.top/Article/details/gtodehambf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfvcieowm.html

[S24] C：获取本地时间
来源：http://dali.hysaishi.cn/Article/details/gtjttmycvd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.svipenyu.cn/Article/details/gtcocjtesg.html

[S25] C：内存拷贝
来源：http://dali.redwolf501.top/Article/details/gtmzejmvjv.html

memcpy(dst, src, n);
来源：http://dali.cashguo.top/Article/details/gtghkewmzi.html

[S26] C：内存清零
来源：http://dali.ppjwa.cn/Article/details/gtmfvvollc.html

memset(a, 0, sizeof a);
来源：http://dali.xuanzx.com/Article/details/gtliokzoky.html

[S27] C：定义常量
来源：http://dali.yonumen.top/Article/details/gtksyvshnz.html

const double PI = 3.14159;
来源：http://dali.zycfv.cn/Article/details/gtlfhcvieu.html

[S28] C：静态变量
来源：http://dali.hfpthk.cn/Article/details/gtkhtjuyfn.html

static int counter = 0;
来源：http://dali.nwbrower.top/Article/details/gtfltlkpuu.html

[S29] C：变参函数
来源：http://dali.hysaishi.cn/Article/details/gtcxbjylph.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hysaishi.cn/Article/details/gtxfqvjwms.html

[S30] C：头文件保护
来源：http://dali.jinyuanbaomall.cn/Article/details/gthvzddsov.html

#ifndef X_H
来源：http://dali.shanyushiyangtech.top/Article/details/gtcgfxagdy.html

#define X_H
来源：http://dali.redwolf501.top/Article/details/gtvdxsbcbw.html

#endif
来源：http://dali.gaohongyu789.top/Article/details/gthuvrotvq.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtmqqvkmco.html

#include <iostream>
来源：http://dali.sxryk.cn/Article/details/gtbguhmtau.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.dashuyun.cn/Article/details/gtunfmokcb.html

[S32] C++：字符串
来源：http://dali.zhengqikj.top/Article/details/gtrvvzfehy.html

std::string s = "hi";  s += "!";
来源：http://dali.hnxiangtu.top/Article/details/gtbqopobpc.html

[S33] C++：vector 增删
来源：http://dali.pengpengdd.cyou/Article/details/gtgllhunue.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shzxlz.cn/Article/details/gtqatutfzk.html

[S34] C++：遍历 vector
来源：http://dali.snrcjt.cn/Article/details/gtumbbbelv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.mhx1999.top/Article/details/gtuhdqitlf.html

[S35] C++：map
来源：http://dali.birdmap.top/Article/details/gtrjdutnpb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhengqikj.top/Article/details/gtgkxdzrik.html

[S36] C++：unordered_map
来源：http://dali.jinqigfzy.top/Article/details/gtpcimfium.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hnxiangtu.top/Article/details/gtkepgddvd.html

[S37] C++：set
来源：http://dali.yueranfly.top/Article/details/gtyudevzoj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.meibo888.top/Article/details/gttxdlcfbd.html

[S38] C++：排序
来源：http://dali.ehwqpu.com/Article/details/gtsdctqgyg.html

std::sort(v.begin(), v.end());
来源：http://dali.snrcjt.cn/Article/details/gtzetrzqtr.html

[S39] C++：自定义比较器排序
来源：http://dali.yongpay.top/Article/details/gtikdmxdox.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hysaishi.cn/Article/details/gteulvxxrl.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gtuydcdnvj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.pengpengdd.cyou/Article/details/gtyzquzgfu.html

[S41] C++：类与构造函数
来源：http://dali.xziqi.cn/Article/details/gtgymoqpos.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.0kj1m.cn/Article/details/gtqnkzvsyj.html

[S42] C++：继承与虚函数
来源：http://dali.zhoulong.xyz/Article/details/gtrctfnwfg.html

class B : public Base { public: void f() override {} };
来源：http://dali.meibo888.top/Article/details/gtsagyztkv.html

[S43] C++：智能指针
来源：http://dali.fzhhl.top/Article/details/gtaqheltov.html

auto p = std::make_unique<int>(5);
来源：http://dali.haohaochexian.top/Article/details/gtbgtuvikz.html

[S44] C++：引用传参
来源：http://dali.chenlongwang.top/Article/details/gtupzhpzfu.html

void inc(int &x) { ++x; }
来源：http://dali.svipenyu.cn/Article/details/gtjvpvljrb.html

[S45] C++：lambda
来源：http://dali.jinghuilouyu.cn/Article/details/gtpoysirpk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.tanke756.top/Article/details/gtnlwjaesr.html

[S46] C++：函数模板
来源：http://dali.yangfankeji.com/Article/details/gtaozqlyqg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zycfv.cn/Article/details/gtyrsetfxa.html

[S47] C++：结构化绑定遍历
来源：http://dali.daria6918.cn/Article/details/gtqwehfjkf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sysykeji.top/Article/details/gtcfahvcic.html

[S48] C++：逐行读文件
来源：http://dali.meibo888.top/Article/details/gtcvjawzkj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhiwuduotai.top/Article/details/gtmvxxxulp.html

while (std::getline(in, line)) { }
来源：http://dali.cashguo.top/Article/details/gtrlvpejza.html

[S49] C++：写文件
来源：http://dali.mhx1999.top/Article/details/gtfkyssdeg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtakfzghqg.html

[S50] C++：格式化数字
来源：http://dali.ehwqpu.com/Article/details/gtewacyjgx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.smart0.xyz/Article/details/gtdncxbnxj.html

[S51] C++：显式类型转换
来源：http://dali.pengpengdd.cyou/Article/details/gtukbpwkya.html

static_cast<double>(a) / b
来源：http://dali.cheryme.top/Article/details/gtvvbmgixd.html

[S52] C++：const 与 noexcept
来源：http://dali.haohaochexian.top/Article/details/gtwdgplhoj.html

int size() const noexcept { return n_; }
来源：http://dali.xinyue.icu/Article/details/gtfjwjqlyt.html

[S53] C++：移动语义
来源：http://dali.smart0.xyz/Article/details/gtlksbjjpf.html

std::vector<int> w = std::move(v);
来源：http://dali.haohaochexian.top/Article/details/gtkhpunphy.html

[S54] C++：异常处理
来源：http://dali.yanxiufei.cn/Article/details/gtnqziceol.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yonumen.top/Article/details/gtlthhzual.html

[S55] C++：结构化绑定
来源：http://dali.guannengcc.top/Article/details/gtxxtaqhij.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yueranfly.top/Article/details/gtqzqseudi.html

[S56] C++：optional
来源：http://dali.tian-w.cn/Article/details/gtdwqsytgv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqdyrdiow.html

[S57] C++：编译期常量
来源：http://dali.xuetiantiany.cn/Article/details/gtfbnsiuvp.html

constexpr int N = 10;
来源：http://dali.kuanghao11.cn/Article/details/gtjcgehgye.html

[S58] C++：命名空间
来源：http://dali.pycfn.com/Article/details/gtljfrpulg.html

namespace ns { int f() { return 1; } }
来源：http://dali.gaohongyu789.top/Article/details/gteglvaruf.html

[S59] C++：静态断言
来源：http://dali.zhoulong.xyz/Article/details/gtaqkidrjt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.quarkkingdee.top/Article/details/gtgbqxfoog.html

[S60] C++：遍历并删除元素
来源：http://dali.yuanzhike.top/Article/details/gtcylfghwp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.wangshuangyany.cn/Article/details/gtcitdrkwj.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtzuajggoi.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cashguo.top/Article/details/gtcdoncvoe.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtgiipengo.html

[T01] Kotlin：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtntlmignn.html

println("Hello")
来源：http://dali.tanke756.top/Article/details/gtwcoxwiul.html

[T02] Kotlin：变量
来源：http://dali.zdqjudy.top/Article/details/gtqmrueegx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yuxming.cn/Article/details/gtaevrwqub.html

[T03] Kotlin：字符串模板
来源：http://dali.fengsongda.top/Article/details/gtarlwqgfj.html

"值: $b"
来源：http://dali.yj202588.top/Article/details/gtsjecnucx.html

[T04] Kotlin：空安全
来源：http://dali.cashguo.top/Article/details/gtyhwacbfx.html

val n: String? = null;  n?.length
来源：http://dali.quarkkingdee.top/Article/details/gtjerxbame.html

[T05] Kotlin：when 表达式
来源：http://dali.xuetiantiany.cn/Article/details/gtmoffpthc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yonumen.top/Article/details/gtjqgaqxil.html

[T06] Kotlin：集合映射
来源：http://dali.shangyingyoupin.top/Article/details/gtojlgqsjk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hfpthk.cn/Article/details/gtxewdiwna.html

[T07] Kotlin：集合过滤
来源：http://dali.jqgfzy.top/Article/details/gtfpooednb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yj202588.top/Article/details/gtypzwchdm.html

[T08] Kotlin：数据类
来源：http://dali.jiagoushi.top/Article/details/gtcqszeior.html

data class User(val name: String, val age: Int)
来源：http://dali.0kj1m.cn/Article/details/gtvcgfmrjv.html

[T09] Kotlin：扩展函数
来源：http://dali.zhoulong.xyz/Article/details/gtgogvhxdp.html

fun String.exclaim() = this + "!"
来源：http://dali.jqgfzy.top/Article/details/gtesgjzgwp.html

[T10] Kotlin：默认参数
来源：http://dali.smart0.xyz/Article/details/gttuwztfix.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.bjfxy.top/Article/details/gtfckbqpfp.html

[T11] Kotlin：协程
来源：http://dali.0kj1m.cn/Article/details/gtxnhblxvs.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.daria6918.cn/Article/details/gticfnvich.html

[T12] Kotlin：解构声明
来源：http://dali.smart0.xyz/Article/details/gtbowlafcd.html

val (a, b) = Pair(1, 2)
来源：http://dali.aibaodan.cn/Article/details/gtnocxehme.html

[T13] Kotlin：只读 Map
来源：http://dali.jlsjyb.cn/Article/details/gteugdjskq.html

val m = mapOf("a" to 1)
来源：http://dali.daxiang520.top/Article/details/gtnorjpfpl.html

[T14] Kotlin：循环
来源：http://dali.cheryme.top/Article/details/gtunsgckmd.html

for (i in 1..10) println(i)
来源：http://dali.dianchejie.cn/Article/details/gtcuuugglb.html

[T15] Kotlin：接口
来源：http://dali.chenjidiqi.icu/Article/details/gtaohxxoip.html

interface Shape { fun area(): Double }
来源：http://dali.gotoacloud.top/Article/details/gtzsyfhiyr.html

[T16] Swift：Hello World
来源：http://dali.mhx1999.top/Article/details/gtinledhbu.html

print("Hello")
来源：http://dali.bjfxy.top/Article/details/gtrpqakpro.html

[T17] Swift：变量与常量
来源：http://dali.yj20258.top/Article/details/gtoemwuzgx.html

var a = 1;  let b = 2
来源：http://dali.dashuyun.cn/Article/details/gtaartshej.html

[T18] Swift：字符串插值
来源：http://dali.pengpengdd.cyou/Article/details/gtdnwmwqje.html

"值: \(b)"
来源：http://dali.meibo888.top/Article/details/gtpzmdltde.html

[T19] Swift：可选绑定
来源：http://dali.zhiwuduotai.top/Article/details/gtcevkyjbm.html

if let n = opt { print(n) }
来源：http://dali.snrcjt.cn/Article/details/gtipbprhhg.html

[T20] Swift：数组操作
来源：http://dali.guannengcc.top/Article/details/gtatwnrqxq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ppjwa.cn/Article/details/gttrhyziul.html

[T21] Swift：遍历
来源：http://dali.cdnleiting.top/Article/details/gtvpsbzrrh.html

for x in a { print(x) }
来源：http://dali.andypj.xyz/Article/details/gtnvbaespr.html

[T22] Swift：字典
来源：http://dali.gzhubu.top/Article/details/gtpvftlbno.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.dianchejie.cn/Article/details/gtydwctjqu.html

[T23] Swift：函数
来源：http://dali.sxryk.cn/Article/details/gthxasdqeg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.daria6918.cn/Article/details/gtioodyamu.html

[T24] Swift：闭包
来源：http://dali.smart0.xyz/Article/details/gtqlnkofzs.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.sweek.top/Article/details/gtcurejfkv.html

[T25] Swift：结构体
来源：http://dali.shzxlz.cn/Article/details/gtncoxhspu.html

struct P { var x: Int }
来源：http://dali.kuanghao11.cn/Article/details/gtrauqkmpp.html

[T26] Swift：类与重写
来源：http://dali.bjfxy.top/Article/details/gtgcedkbpy.html

class A: Base { override func f() {} }
来源：http://dali.pengpengdd.cyou/Article/details/gtrjrnotah.html

[T27] Swift：错误处理
来源：http://dali.wangshuangyany.cn/Article/details/gtdktnnsix.html

do { try f() } catch { print(error) }
来源：http://dali.yuanzhike.top/Article/details/gtnhmoyhco.html

[T28] Swift：枚举
来源：http://dali.yj202588.top/Article/details/gtlakbrjqa.html

enum Color { case red, green }
来源：http://dali.zycfv.cn/Article/details/gtjgzvqmsz.html

[T29] Swift：guard 提前返回
来源：http://dali.fzhhl.top/Article/details/gtcdnpltqi.html

guard let x = opt else { return }
来源：http://dali.jiagoushi.top/Article/details/gtsmmxdjsj.html

[T30] Swift：协议
来源：http://dali.hysaishi.cn/Article/details/gtiklmrjgz.html

protocol Shape { func area() -> Double }
来源：http://dali.zhixingplan.top/Article/details/gttaxdvtqa.html

[T31] Lua：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfqreaafs.html

print("Hello")
来源：http://dali.xziqi.cn/Article/details/gtefpwgvkq.html

[T32] Lua：局部变量
来源：http://dali.gzhubu.top/Article/details/gtgiggqrqr.html

local a = 1
来源：http://dali.hfpthk.cn/Article/details/gtptmaowzd.html

[T33] Lua：表（数组）
来源：http://dali.cheryme.top/Article/details/gtfwynwufg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jqgfzy.top/Article/details/gtmfrfcpvq.html

[T34] Lua：遍历表
来源：http://dali.yj20258888.top/Article/details/gtiswgswxr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hongshengwenyu.top/Article/details/gtsshrbngg.html

[T35] Lua：字典表
来源：http://dali.ydzc1.top/Article/details/gtcnzhsnov.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtupqdhcpm.html

[T36] Lua：函数
来源：http://dali.guannengcc.top/Article/details/gtamkpqlbg.html

function add(a, b) return a + b end
来源：http://dali.cqqwz.cn/Article/details/gtnyfviajo.html

[T37] Lua：字符串拼接
来源：http://dali.zhoulong.xyz/Article/details/gtmuztmfxe.html

"a" .. "b"
来源：http://dali.sufxvd.cn/Article/details/gttvrarrhx.html

[T38] Lua：条件
来源：http://dali.yj202588.top/Article/details/gtnxssawfp.html

if x > 0 then print("正") end
来源：http://dali.tian-w.cn/Article/details/gtmrevlcqb.html

[T39] Lua：模式匹配
来源：http://dali.yvedp.cn/Article/details/gtvwwfnsqt.html

string.find(s, "%d+")
来源：http://dali.sweek.top/Article/details/gtdgpukrpd.html

[T40] Lua：元表
来源：http://dali.jyoumei.cn/Article/details/gtjsigplrx.html

setmetatable({}, { __index = base })
来源：http://dali.zdqjudy.top/Article/details/gtbggywest.html

[T41] Perl：Hello World
来源：http://dali.cdnleiting.top/Article/details/gtizzrjuqm.html

print "Hello\n";
来源：http://dali.fzhhl.top/Article/details/gtfvpgyseu.html

[T42] Perl：变量类型
来源：http://dali.yueranfly.top/Article/details/gtddrkyfty.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yueranfly.top/Article/details/gtpgipjrtm.html

[T43] Perl：字符串插值
来源：http://dali.hfpthk.cn/Article/details/gtmntfidus.html

"值: $a"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxvwpibbx.html

[T44] Perl：条件
来源：http://dali.ehwqpu.com/Article/details/gtyaaxstmd.html

if ($a > 0) { print "正"; }
来源：http://dali.hnxiangtu.top/Article/details/gtwcezncnq.html

[T45] Perl：数组遍历
来源：http://dali.sxryk.cn/Article/details/gtqavhcfjk.html

for my $x (@arr) { print $x; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvqnybtsn.html

[T46] Perl：哈希操作
来源：http://dali.jiagoushi.top/Article/details/gtpefmlcoa.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtxclsqxtq.html

[T47] Perl：正则捕获
来源：http://dali.svipenyu.cn/Article/details/gtcnqzqbtm.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.0kj1m.cn/Article/details/gtileeopes.html

[T48] Perl：正则替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtmsufmsqq.html

$s =~ s/old/new/g;
来源：http://dali.wangshuangyany.cn/Article/details/gtqgozszrc.html

[T49] Perl：函数
来源：http://dali.sweek.top/Article/details/gtszmeshoz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.chenlongwang.top/Article/details/gtymirahbu.html

[T50] Perl：逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gtdbhwqnhw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.meibo888.top/Article/details/gthpbwsloq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.daxiang520.top/Article/details/gtiggnavhi.html

[T51] Scala：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtancrtbgo.html

println("Hello")
来源：http://dali.ivvv.top/Article/details/gthffqvwfe.html

[T52] Scala：变量
来源：http://dali.xuetiantiany.cn/Article/details/gtrbhshykn.html

val a = 1;  var b = 2
来源：http://dali.andypj.xyz/Article/details/gtertidiya.html

[T53] Scala：字符串插值
来源：http://dali.cheryme.top/Article/details/gthcypjpyr.html

s"值: $b"
来源：http://dali.iojbl.cn/Article/details/gtedztfped.html

[T54] Scala：集合映射
来源：http://dali.316326.xyz/Article/details/gtsfjxfvgr.html


<!-- 参考信息 -->