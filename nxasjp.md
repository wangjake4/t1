代发 wailian999

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.0kj1m.cn/Article/details/gtwfdiqnjo.html

[R50] awk 求和
来源：http://dali.zhiwuduotai.top/Article/details/gttdimysqz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.guannengcc.top/Article/details/gtaqpuijiq.html

[R51] 排序去重取前几
来源：http://dali.fengsongda.top/Article/details/gtclsnwhgh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.c1oappe.top/Article/details/gterjecblw.html

[R52] 统计行数
来源：http://dali.havefunace.top/Article/details/gtfofmjqkt.html

wc -l a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtyttezjso.html

[R53] 查看文件头与实时尾
来源：http://dali.tanke756.top/Article/details/gtrwwxootz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hywenlv.cn/Article/details/gtjabzgtnk.html

[R54] 比较两个文件
来源：http://dali.zhengqikj.top/Article/details/gtxprscawu.html

diff a.txt b.txt
来源：http://dali.fengsongda.top/Article/details/gtofgtgpkk.html

[R55] 压缩与解压
来源：http://dali.zhoulong.xyz/Article/details/gteytqgofz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.0kj1m.cn/Article/details/gtdfdqobny.html

[R56] 远程拷贝
来源：http://dali.bjfxy.top/Article/details/gtlxqttsfx.html

scp file user@host:/path/
来源：http://dali.yangfankeji.com/Article/details/gtipbvulqa.html

[R57] 远程执行命令
来源：http://dali.hnxiangtu.top/Article/details/gtqemeyfmr.html

ssh user@host 'uptime'
来源：http://dali.smart0.xyz/Article/details/gtiefaowsb.html

[R58] 下载文件
来源：http://dali.jiagoushi.top/Article/details/gtyuynkueg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xylfe.cn/Article/details/gtmmoelooa.html

[R59] 发 POST JSON
来源：http://dali.guannengcc.top/Article/details/gtznzygamw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.c1oappe.top/Article/details/gtrcgaveeg.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhoulong.xyz/Article/details/gtfqgwtcyj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.chenzaomai.com/Article/details/gtswtpjfkr.html

[R61] 磁盘占用
来源：http://dali.jqgufenzy.top/Article/details/gthemohcvl.html

df -h;  du -sh *
来源：http://dali.havefunace.top/Article/details/gtsoxqpyuj.html

[R62] 找最占空间的文件
来源：http://dali.zhengqikj.top/Article/details/gtlajmyyqc.html

du -ah . | sort -rh | head -10
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbfblkchr.html

[R63] 内存与进程
来源：http://dali.daria6918.cn/Article/details/gtqhfvynhg.html

free -h;  ps aux | grep nginx
来源：http://dali.dashuyun.cn/Article/details/gtrsabxfag.html

[R64] 结束进程
来源：http://dali.smart0.xyz/Article/details/gtvglcfxdg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvnwyosyd.html

[R65] 查看端口占用
来源：http://dali.havefunace.top/Article/details/gtkmxpyydf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jinqigfzy.top/Article/details/gterfiampz.html

[R66] 定时任务
来源：http://dali.shanyushiyangtech.top/Article/details/gtknxdueik.html

crontab -e;  crontab -l
来源：http://dali.jinqigufen.top/Article/details/gtmtjtzjpu.html

[R67] 生成随机十六进制串
来源：http://dali.xylfe.cn/Article/details/gtboutbuhy.html

openssl rand -hex 16
来源：http://dali.hfpthk.cn/Article/details/gtytqbtacc.html

[R68] 计算文件校验值
来源：http://dali.aibaodan.cn/Article/details/gtmhuteaer.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.havefunace.top/Article/details/gthrsapmnk.html

[R69] 生成随机密码
来源：http://dali.dianchejie.cn/Article/details/gtbvxbojvu.html

head -c 16 /dev/urandom | base64
来源：http://dali.mhx1999.top/Article/details/gtikrvexii.html

[R70] 时间戳与互转
来源：http://dali.aibaodan.cn/Article/details/gtgbxzfnmx.html

date +%s;  date -d @1700000000
来源：http://dali.zhoulong.xyz/Article/details/gtzcbcrzgd.html

[R71] 日期格式化
来源：http://dali.feifeiyinyue.top/Article/details/gtedpbzbby.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.pycfn.com/Article/details/gtkwpqmkzb.html

[R72] 等待端口就绪
来源：http://dali.jqgufenzy.top/Article/details/gtmscmluvw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jqgfzy.top/Article/details/gticlutqgi.html

[R73] 分割大日志
来源：http://dali.guowangkeji.top/Article/details/gtxwprwopr.html

split -l 1000 big.log part_
来源：http://dali.hnxiangtu.top/Article/details/gtbrbyjmoa.html

[R74] 批量重命名
来源：http://dali.shanyushiyangtech.top/Article/details/gtddbjswgn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yvedp.cn/Article/details/gtmcwhvqwp.html

[R75] 导出环境变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwnzlwhkf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.iojbl.cn/Article/details/gtypdghsou.html

[R76] 使用临时文件
来源：http://dali.snrcjt.cn/Article/details/gtnmxyertb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigfzy.top/Article/details/gtyffbwqkw.html

[R77] 读取用户输入
来源：http://dali.yangfankeji.com/Article/details/gtgsgadrxq.html

read -rp "请输入: " ans
来源：http://dali.9152youxi.cn/Article/details/gtpqmhnpic.html

[R78] 交互式菜单
来源：http://dali.guannengcc.top/Article/details/gtzqjenphg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.kuanghao11.cn/Article/details/gteotddpou.html

[R79] 解析命令行选项
来源：http://dali.hnqzz.top/Article/details/gtbchkhadu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xuanzx.com/Article/details/gtuqiepgpg.html

[R80] 查看脚本执行耗时
来源：http://dali.guowangkeji.top/Article/details/gtovehmryg.html

time ./run.sh
来源：http://dali.zdqjudy.top/Article/details/gtsvrhwwvb.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtuwwawmli.html

S. C / C++ 专题
来源：http://dali.fzhhl.top/Article/details/gtnuhavzpo.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxdrhoqah.html

[S01] C：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtpbmstpfr.html

#include <stdio.h>
来源：http://dali.jyoumei.cn/Article/details/gteadcydgf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xylfe.cn/Article/details/gtqouzpbzq.html

[S02] C：变量与格式化输出
来源：http://dali.hysaishi.cn/Article/details/gtmwemcsza.html

int a = 10; printf("%d\n", a);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxalkxuqn.html

[S03] C：读入整数
来源：http://dali.shanyushiyangtech.top/Article/details/gtyavnnrnt.html

int x; scanf("%d", &x);
来源：http://dali.jqgfzy.top/Article/details/gtjjvrehtm.html

[S04] C：字符串复制
来源：http://dali.c1oappe.top/Article/details/gtddqhzzdp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.316326.xyz/Article/details/gtuneuoyrv.html

[S05] C：字符串长度
来源：http://dali.yuxming.cn/Article/details/gtqxhjdqhg.html

strlen(s)
来源：http://dali.tian-w.cn/Article/details/gtkpgzevxp.html

[S06] C：字符串比较
来源：http://dali.zhengqikj.top/Article/details/gtdguexegf.html

strcmp(a, b) == 0
来源：http://dali.ybcxt.top/Article/details/gtiiqticrw.html

[S07] C：数组遍历求和
来源：http://dali.cqqwz.cn/Article/details/gtqfacippd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.smart0.xyz/Article/details/gtklwdlewi.html

[S08] C：动态内存分配与释放
来源：http://dali.dianchejie.cn/Article/details/gtecgmpqeo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gtzmlijtly.html

[S09] C：结构体定义与初始化
来源：http://dali.shuidangran.top/Article/details/gtqknesoue.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xinyue.icu/Article/details/gtkfhmmvvu.html

[S10] C：指针与解引用
来源：http://dali.jqgufenzy.top/Article/details/gtazvjjqqh.html

int *p = &a;  *p = 5;
来源：http://dali.fzhhl.top/Article/details/gtaycdnfjm.html

[S11] C：逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gtoobxsvvr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jqgfzy.top/Article/details/gtroweuqeq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.meibo888.top/Article/details/gtnspjrkod.html

fclose(f);
来源：http://dali.cucudq.cn/Article/details/gtiwacwnwh.html

[S12] C：写文件
来源：http://dali.zhixingplan.top/Article/details/gtjnmjkqhm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.dashuyun.cn/Article/details/gtbamsacso.html

[S13] C：宏定义
来源：http://dali.sxryk.cn/Article/details/gtmnruwfdi.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.tianlin.xyz/Article/details/gtnxsnruyp.html

[S14] C：枚举
来源：http://dali.xziqi.cn/Article/details/gtvvjljfar.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cashguo.top/Article/details/gtljhaboex.html

[S15] C：类型转换
来源：http://dali.vqdsnc.cn/Article/details/gtzfrycuzs.html

(double) a / b
来源：http://dali.redwolf501.top/Article/details/gtnlgylwyj.html

[S16] C：位操作置位
来源：http://dali.ppjwa.cn/Article/details/gttwoexlzm.html

x |= (1 << 3);
来源：http://dali.quarkkingdee.top/Article/details/gtadnvehow.html

[S17] C：安全拼接字符串
来源：http://dali.shuidangran.top/Article/details/gtipysqwud.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.quarkkingdee.top/Article/details/gtmpunkugx.html

[S18] C：命令行参数
来源：http://dali.aizwys.cn/Article/details/gtrbbbluaz.html

int main(int argc, char **argv)
来源：http://dali.guannengcc.top/Article/details/gtanjrkvfl.html

[S19] C：快速排序
来源：http://dali.ybcxt.top/Article/details/gtnpcdnddc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shuidangran.top/Article/details/gtexqkecrv.html

[S20] C：二分查找
来源：http://dali.hammf.cn/Article/details/gtxsuorhvi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yuanzhike.top/Article/details/gtcwfpjtcg.html

[S21] C：字符类别判断
来源：http://dali.cucudq.cn/Article/details/gtbiszxqml.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jianghu66.top/Article/details/gtilyvzkik.html

[S22] C：字符串转数字
来源：http://dali.mhx1999.top/Article/details/gtpsdkutbn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinqigfzy.top/Article/details/gtzwtemaus.html

[S23] C：随机数
来源：http://dali.snrcjt.cn/Article/details/gtzulszwpb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.meibo888.top/Article/details/gtopoyidqc.html

[S24] C：获取本地时间
来源：http://dali.dashuyun.cn/Article/details/gtjjqmofoy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jianghu66.top/Article/details/gtxhesqtxp.html

[S25] C：内存拷贝
来源：http://dali.wangshuangyany.cn/Article/details/gteewwmdth.html

memcpy(dst, src, n);
来源：http://dali.tian-w.cn/Article/details/gtdkdfqyqu.html

[S26] C：内存清零
来源：http://dali.c1oappe.top/Article/details/gtjkowqrym.html

memset(a, 0, sizeof a);
来源：http://dali.cqqwz.cn/Article/details/gthfxrfnex.html

[S27] C：定义常量
来源：http://dali.yj20258.top/Article/details/gtisyhooxf.html

const double PI = 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gtqutceeey.html

[S28] C：静态变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgzxpwmcg.html

static int counter = 0;
来源：http://dali.fengsongda.top/Article/details/gtkbreykgh.html

[S29] C：变参函数
来源：http://dali.hysaishi.cn/Article/details/gtisrqklld.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.sufxvd.cn/Article/details/gtwswukfvt.html

[S30] C：头文件保护
来源：http://dali.sxryk.cn/Article/details/gtsrrsykwx.html

#ifndef X_H
来源：http://dali.jinqigfzy.top/Article/details/gtjhuuivco.html

#define X_H
来源：http://dali.hammf.cn/Article/details/gtgzdejsni.html

#endif
来源：http://dali.fengsongda.top/Article/details/gtoujfkfgx.html

[S31] C++：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtmnvgzqch.html

#include <iostream>
来源：http://dali.feifeiyinyue.top/Article/details/gtwiwojcow.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.guowangkeji.top/Article/details/gtefrxmctc.html

[S32] C++：字符串
来源：http://dali.xuanzx.com/Article/details/gtnyqmnwjc.html

std::string s = "hi";  s += "!";
来源：http://dali.xuanzx.com/Article/details/gtswniqgeg.html

[S33] C++：vector 增删
来源：http://dali.haohaochexian.top/Article/details/gtmesjvafd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jyoumei.cn/Article/details/gtpgkdgbkc.html

[S34] C++：遍历 vector
来源：http://dali.birdmap.top/Article/details/gtlrcnxmiz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gaohongyu789.top/Article/details/gtlieuyozs.html

[S35] C++：map
来源：http://dali.9152youxi.cn/Article/details/gtofgfliqb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gthwxvtytv.html

[S36] C++：unordered_map
来源：http://dali.zhongyouzk.top/Article/details/gtxoakizfj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yueranfly.top/Article/details/gtgvmcukqt.html

[S37] C++：set
来源：http://dali.9152youxi.cn/Article/details/gtvjuslccj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.wangdashe.top/Article/details/gtiahvkwey.html

[S38] C++：排序
来源：http://dali.fengsongda.top/Article/details/gtqdnquutv.html

std::sort(v.begin(), v.end());
来源：http://dali.andypj.xyz/Article/details/gtuwmcfzyi.html

[S39] C++：自定义比较器排序
来源：http://dali.wangshuangyany.cn/Article/details/gtreglajgb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.nanxuanxn.top/Article/details/gtjjrgwvil.html

[S40] C++：查找元素
来源：http://dali.hnxiangtu.top/Article/details/gthyomnfes.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xylfe.cn/Article/details/gtkgtuodks.html

[S41] C++：类与构造函数
来源：http://dali.chenjidiqi.icu/Article/details/gtpdewkkut.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.mhx1999.top/Article/details/gtmyhbnvmw.html

[S42] C++：继承与虚函数
来源：http://dali.wangdashe.top/Article/details/gtgzfwpbgg.html

class B : public Base { public: void f() override {} };
来源：http://dali.xylfe.cn/Article/details/gtgqkbtfoa.html

[S43] C++：智能指针
来源：http://dali.hammf.cn/Article/details/gtvguwarhk.html

auto p = std::make_unique<int>(5);
来源：http://dali.316326.xyz/Article/details/gtbhclaryh.html

[S44] C++：引用传参
来源：http://dali.jinqigfzy.top/Article/details/gthgnotqta.html

void inc(int &x) { ++x; }
来源：http://dali.chenlongwang.top/Article/details/gtpnijmrlg.html

[S45] C++：lambda
来源：http://dali.guannengcc.top/Article/details/gtnuoutoqg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yueranfly.top/Article/details/gtxmgrubyd.html

[S46] C++：函数模板
来源：http://dali.dianchejie.cn/Article/details/gtbgnrkwvm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.dashuyun.cn/Article/details/gtrxigtlje.html

[S47] C++：结构化绑定遍历
来源：http://dali.hysaishi.cn/Article/details/gtwayuansm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvjfijbfs.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gtazolifel.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhengqikj.top/Article/details/gtynnsrlrh.html

while (std::getline(in, line)) { }
来源：http://dali.cheryme.top/Article/details/gtixyxxujk.html

[S49] C++：写文件
来源：http://dali.fengsongda.top/Article/details/gteedudblv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ydzc1.top/Article/details/gtqnbhfonm.html

[S50] C++：格式化数字
来源：http://dali.zycfv.cn/Article/details/gtzdhqgqxa.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.daxiang520.top/Article/details/gtdukihxdu.html

[S51] C++：显式类型转换
来源：http://dali.wangdashe.top/Article/details/gtpngaascz.html

static_cast<double>(a) / b
来源：http://dali.gotoacloud.top/Article/details/gtxrtjvxiz.html

[S52] C++：const 与 noexcept
来源：http://dali.xuanzx.com/Article/details/gtiadzljrx.html

int size() const noexcept { return n_; }
来源：http://dali.yvedp.cn/Article/details/gtsndlqslr.html

[S53] C++：移动语义
来源：http://dali.yuxming.cn/Article/details/gtiszxlmzd.html

std::vector<int> w = std::move(v);
来源：http://dali.pengpengdd.cyou/Article/details/gtwjwhxqbr.html

[S54] C++：异常处理
来源：http://dali.zhongyouzk.top/Article/details/gtyeafphgj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.nanxinkj.top/Article/details/gtrajkioal.html

[S55] C++：结构化绑定
来源：http://dali.smart0.xyz/Article/details/gtpeftvskm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zdqjudy.top/Article/details/gtubvsndtj.html

[S56] C++：optional
来源：http://dali.zdqjudy.top/Article/details/gtxfuhnccw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.iojbl.cn/Article/details/gtivknaucn.html

[S57] C++：编译期常量
来源：http://dali.ydzc1.top/Article/details/gtunxmvuec.html

constexpr int N = 10;
来源：http://dali.yj20258.top/Article/details/gtnawimblp.html

[S58] C++：命名空间
来源：http://dali.smart0.xyz/Article/details/gtilurivbx.html

namespace ns { int f() { return 1; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmsqaesyk.html

[S59] C++：静态断言
来源：http://dali.hnxiangtu.top/Article/details/gtjwfzwdzl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gogol.net.cn/Article/details/gtcvyqovyw.html

[S60] C++：遍历并删除元素
来源：http://dali.nanxinkj.top/Article/details/gtpjafbbgm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.aizwys.cn/Article/details/gtekykarlp.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtrgaqzxzl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gogol.net.cn/Article/details/gtvnbqhngv.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtyvubfeix.html

[T01] Kotlin：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtolhcinht.html

println("Hello")
来源：http://dali.haohaochexian.top/Article/details/gttjojvjxx.html

[T02] Kotlin：变量
来源：http://dali.yongpay.top/Article/details/gtvricpuhb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.svipenyu.cn/Article/details/gtqppspuqi.html

[T03] Kotlin：字符串模板
来源：http://dali.dashuyun.cn/Article/details/gtpfltpdha.html

"值: $b"
来源：http://dali.xinyue.icu/Article/details/gtwewpbpsr.html

[T04] Kotlin：空安全
来源：http://dali.yuxming.cn/Article/details/gtlbscjgqr.html

val n: String? = null;  n?.length
来源：http://dali.xinyue.icu/Article/details/gtpodccffu.html

[T05] Kotlin：when 表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gtxnfleymk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiwrnkpcv.html

[T06] Kotlin：集合映射
来源：http://dali.gogol.net.cn/Article/details/gtozfufwbc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.tianlin.xyz/Article/details/gtgqopytgf.html

[T07] Kotlin：集合过滤
来源：http://dali.gzhubu.top/Article/details/gtveqgzzzb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtexyeizys.html

[T08] Kotlin：数据类
来源：http://dali.zhongyouzk.top/Article/details/gtyfexzxsj.html

data class User(val name: String, val age: Int)
来源：http://dali.havefunace.top/Article/details/gtrqzgmnea.html

[T09] Kotlin：扩展函数
来源：http://dali.bjfxy.top/Article/details/gtekkohbls.html

fun String.exclaim() = this + "!"
来源：http://dali.tian-w.cn/Article/details/gthcjancno.html

[T10] Kotlin：默认参数
来源：http://dali.gogol.net.cn/Article/details/gtybkmhvli.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xuetiantiany.cn/Article/details/gtfksqigln.html

[T11] Kotlin：协程
来源：http://dali.hongshengwenyu.top/Article/details/gtckcdmlkr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.guannengcc.top/Article/details/gtgcibjwly.html

[T12] Kotlin：解构声明
来源：http://dali.hnxiangtu.top/Article/details/gtghduxcku.html

val (a, b) = Pair(1, 2)
来源：http://dali.iojbl.cn/Article/details/gtgpcaitmr.html

[T13] Kotlin：只读 Map
来源：http://dali.zhoulong.xyz/Article/details/gtbyerafef.html

val m = mapOf("a" to 1)
来源：http://dali.iojbl.cn/Article/details/gthnasglzi.html

[T14] Kotlin：循环
来源：http://dali.yvedp.cn/Article/details/gtrchizzcp.html

for (i in 1..10) println(i)
来源：http://dali.shzxlz.cn/Article/details/gtodxuyooh.html

[T15] Kotlin：接口
来源：http://dali.feifeiyinyue.top/Article/details/gtzsnvqzfo.html

interface Shape { fun area(): Double }
来源：http://dali.cashguo.top/Article/details/gtxusxtcsg.html

[T16] Swift：Hello World
来源：http://dali.aibaodan.cn/Article/details/gtkfgqqqho.html

print("Hello")
来源：http://dali.zhixingplan.top/Article/details/gtmueiqanh.html

[T17] Swift：变量与常量
来源：http://dali.yj202588.top/Article/details/gtkrwkynzl.html

var a = 1;  let b = 2
来源：http://dali.yj20258.top/Article/details/gtjwzlbdum.html

[T18] Swift：字符串插值
来源：http://dali.zhoulong.xyz/Article/details/gtwcdnlpfc.html

"值: \(b)"
来源：http://dali.yj202588.top/Article/details/gtomanolcs.html

[T19] Swift：可选绑定
来源：http://dali.daria6918.cn/Article/details/gtnnvbftfp.html

if let n = opt { print(n) }
来源：http://dali.aibaodan.cn/Article/details/gtxutynoyp.html

[T20] Swift：数组操作
来源：http://dali.jianghu66.top/Article/details/gtctpxjzkp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jianghu66.top/Article/details/gtncrvoelu.html

[T21] Swift：遍历
来源：http://dali.yongpay.top/Article/details/gtioyzbkcb.html

for x in a { print(x) }
来源：http://dali.dianchejie.cn/Article/details/gtrphrlpds.html

[T22] Swift：字典
来源：http://dali.guowangkeji.top/Article/details/gtvmvfyzpq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.pengpengdd.cyou/Article/details/gttokeqblg.html

[T23] Swift：函数
来源：http://dali.birdmap.top/Article/details/gtatdynziv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.havefunace.top/Article/details/gtjzbtikjd.html

[T24] Swift：闭包
来源：http://dali.zhoulong.xyz/Article/details/gtmxpqxdpz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhoulong.xyz/Article/details/gtfbebnplf.html

[T25] Swift：结构体
来源：http://dali.daria6918.cn/Article/details/gtrcxrqwag.html

struct P { var x: Int }
来源：http://dali.svipenyu.cn/Article/details/gtzxtbagdy.html

[T26] Swift：类与重写
来源：http://dali.xylfe.cn/Article/details/gtrnywfauk.html

class A: Base { override func f() {} }
来源：http://dali.jinqigfzy.top/Article/details/gtlpzwunzx.html

[T27] Swift：错误处理
来源：http://dali.daria6918.cn/Article/details/gtbcjtynpg.html

do { try f() } catch { print(error) }
来源：http://dali.sysykeji.top/Article/details/gtufvcjzkx.html

[T28] Swift：枚举
来源：http://dali.hfpthk.cn/Article/details/gtgvnvaxkf.html

enum Color { case red, green }
来源：http://dali.hywenlv.cn/Article/details/gtttjewfvw.html

[T29] Swift：guard 提前返回
来源：http://dali.cucudq.cn/Article/details/gthxoeqcrz.html

guard let x = opt else { return }
来源：http://dali.mhx1999.top/Article/details/gtngxctuks.html

[T30] Swift：协议
来源：http://dali.yuxming.cn/Article/details/gtjdrwlxav.html

protocol Shape { func area() -> Double }
来源：http://dali.zhoulong.xyz/Article/details/gtvguucmde.html

[T31] Lua：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtptjvlvma.html

print("Hello")
来源：http://dali.xinyue.icu/Article/details/gtykyiazms.html

[T32] Lua：局部变量
来源：http://dali.yonumen.top/Article/details/gtyeincvqc.html

local a = 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgtobgcxx.html

[T33] Lua：表（数组）
来源：http://dali.shanyushiyangtech.top/Article/details/gtktmziddk.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.sufxvd.cn/Article/details/gtlsczfpga.html

[T34] Lua：遍历表
来源：http://dali.jinqigfzy.top/Article/details/gtlrhcqzzq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jinqigufen.top/Article/details/gtymaxfvgm.html

[T35] Lua：字典表
来源：http://dali.yongpay.top/Article/details/gthdpvzwor.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yj20258888.top/Article/details/gtmmnjedyp.html

[T36] Lua：函数
来源：http://dali.jiagoushi.top/Article/details/gtnamcditm.html

function add(a, b) return a + b end
来源：http://dali.zhiwuduotai.top/Article/details/gtwrumpacb.html

[T37] Lua：字符串拼接
来源：http://dali.nanxinkj.top/Article/details/gtpyluzpgo.html

"a" .. "b"
来源：http://dali.xuetiantiany.cn/Article/details/gtyzilcsoy.html

[T38] Lua：条件
来源：http://dali.cucudq.cn/Article/details/gtbsjmmvxe.html

if x > 0 then print("正") end
来源：http://dali.gzhubu.top/Article/details/gtlgaszmld.html

[T39] Lua：模式匹配
来源：http://dali.jqgufenzy.top/Article/details/gtzpgfkvbq.html

string.find(s, "%d+")
来源：http://dali.jlsjyb.cn/Article/details/gtasqxgxee.html

[T40] Lua：元表
来源：http://dali.daxiang520.top/Article/details/gtrduyysvc.html

setmetatable({}, { __index = base })
来源：http://dali.pycfn.com/Article/details/gtxwnuvmyk.html

[T41] Perl：Hello World
来源：http://dali.sxryk.cn/Article/details/gtmpeihkha.html

print "Hello\n";
来源：http://dali.iojbl.cn/Article/details/gtkwqcyiln.html

[T42] Perl：变量类型
来源：http://dali.iojbl.cn/Article/details/gtjtqjxmin.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhongyouzk.top/Article/details/gtldybraoi.html

[T43] Perl：字符串插值
来源：http://dali.yj20258888.top/Article/details/gtklokjmox.html

"值: $a"
来源：http://dali.hfpthk.cn/Article/details/gtozrsayax.html

[T44] Perl：条件
来源：http://dali.iojbl.cn/Article/details/gtqnzapkfz.html

if ($a > 0) { print "正"; }
来源：http://dali.nanxinkj.top/Article/details/gtppimuguq.html

[T45] Perl：数组遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtqttuacfa.html

for my $x (@arr) { print $x; }
来源：http://dali.zycfv.cn/Article/details/gtehrterie.html

[T46] Perl：哈希操作
来源：http://dali.tanke756.top/Article/details/gthugnqlsr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zdqjudy.top/Article/details/gtczzszmfh.html

[T47] Perl：正则捕获
来源：http://dali.birdmap.top/Article/details/gtmwjslmna.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jyoumei.cn/Article/details/gtigcgihos.html

[T48] Perl：正则替换
来源：http://dali.shangyingyoupin.top/Article/details/gtcqintgwt.html

$s =~ s/old/new/g;
来源：http://dali.316326.xyz/Article/details/gtrhalrxyi.html

[T49] Perl：函数
来源：http://dali.sxryk.cn/Article/details/gtihlmwynf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gtcposwhfc.html

[T50] Perl：逐行读文件
来源：http://dali.yvedp.cn/Article/details/gthwxkdsne.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.wangdashe.top/Article/details/gtngcqfmje.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hfpthk.cn/Article/details/gtvboehwct.html

[T51] Scala：Hello World
来源：http://dali.pycfn.com/Article/details/gtctatxavr.html

println("Hello")
来源：http://dali.wangdashe.top/Article/details/gtwvkzlklu.html

[T52] Scala：变量
来源：http://dali.andypj.xyz/Article/details/gtkqnuiibc.html


<!-- 参考信息 -->