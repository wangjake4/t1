代发 wailian999

sed -i 's/foo/bar/g' a.txt
来源：http://dali.svipenyu.cn/Article/details/gtslxllckw.html

[R48] awk 取指定列
来源：http://dali.tianlin.xyz/Article/details/gtsuluagbw.html

awk '{print $1, $3}' a.txt
来源：http://dali.daxiang520.top/Article/details/gtuvneqclb.html

[R49] awk 带条件
来源：http://dali.cashguo.top/Article/details/gtpfhcozyw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.redwolf501.top/Article/details/gtqqwoausg.html

[R50] awk 求和
来源：http://dali.mhx1999.top/Article/details/gtfvosdhgm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xziqi.cn/Article/details/gtexogoaul.html

[R51] 排序去重取前几
来源：http://dali.pengpengdd.cyou/Article/details/gtzwxbzhbr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yj202588.top/Article/details/gtfokdddna.html

[R52] 统计行数
来源：http://dali.ehwqpu.com/Article/details/gtmvxfzjla.html

wc -l a.txt
来源：http://dali.nanxinkj.top/Article/details/gtwqstlaxk.html

[R53] 查看文件头与实时尾
来源：http://dali.dianchejie.cn/Article/details/gtlmfnddlm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.daria6918.cn/Article/details/gtvcmzoopl.html

[R54] 比较两个文件
来源：http://dali.ppjwa.cn/Article/details/gtzpzsccqx.html

diff a.txt b.txt
来源：http://dali.vqdsnc.cn/Article/details/gtxuuaxovc.html

[R55] 压缩与解压
来源：http://dali.xinyue.icu/Article/details/gtoxzdqdjz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shanyushiyangkeji.top/Article/details/gtehkbbjwp.html

[R56] 远程拷贝
来源：http://dali.aibaodan.cn/Article/details/gtmpninfhl.html

scp file user@host:/path/
来源：http://dali.svipenyu.cn/Article/details/gtwacnyvcx.html

[R57] 远程执行命令
来源：http://dali.ywan-chungtsiang.top/Article/details/gtodadhsui.html

ssh user@host 'uptime'
来源：http://dali.hywenlv.cn/Article/details/gtejcwegxb.html

[R58] 下载文件
来源：http://dali.yuxming.cn/Article/details/gtsjcjqkiz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yanxiufei.cn/Article/details/gtiftnurch.html

[R59] 发 POST JSON
来源：http://dali.bjfxy.top/Article/details/gtsyxwdwwo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cheryme.top/Article/details/gtqlqtzveu.html

[R60] 只看 HTTP 状态码
来源：http://dali.wangshuangyany.cn/Article/details/gtqkdihqci.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.bjfxy.top/Article/details/gtnirsqshw.html

[R61] 磁盘占用
来源：http://dali.yj20258888.top/Article/details/gtrepdwhcr.html

df -h;  du -sh *
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdslybhkt.html

[R62] 找最占空间的文件
来源：http://dali.pycfn.com/Article/details/gtenbyropt.html

du -ah . | sort -rh | head -10
来源：http://dali.pengpengdd.cyou/Article/details/gtshhlynbx.html

[R63] 内存与进程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgcehsflw.html

free -h;  ps aux | grep nginx
来源：http://dali.guannengcc.top/Article/details/gtfoseazxa.html

[R64] 结束进程
来源：http://dali.nwbrower.top/Article/details/gtrbxphghw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sysykeji.top/Article/details/gtuypampqh.html

[R65] 查看端口占用
来源：http://dali.yangfankeji.com/Article/details/gtfbmnurve.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.svipenyu.cn/Article/details/gtnnadyqxk.html

[R66] 定时任务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrcovugmk.html

crontab -e;  crontab -l
来源：http://dali.hammf.cn/Article/details/gtjimavlax.html

[R67] 生成随机十六进制串
来源：http://dali.yj20258888.top/Article/details/gtwhtvzaux.html

openssl rand -hex 16
来源：http://dali.xuanzx.com/Article/details/gtjmxtjvjm.html

[R68] 计算文件校验值
来源：http://dali.yangfankeji.com/Article/details/gthppbpnlo.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.pycfn.com/Article/details/gtxhpnauwd.html

[R69] 生成随机密码
来源：http://dali.zhixingplan.top/Article/details/gtpbmyoygo.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcryvpbbw.html

[R70] 时间戳与互转
来源：http://dali.yvedp.cn/Article/details/gtdnxhquxk.html

date +%s;  date -d @1700000000
来源：http://dali.jianghu66.top/Article/details/gtxjymdcjc.html

[R71] 日期格式化
来源：http://dali.jinqigufen.top/Article/details/gtgkpynqxi.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xuanzx.com/Article/details/gtqcosmnfi.html

[R72] 等待端口就绪
来源：http://dali.zhongyouzk.top/Article/details/gttchpjsxi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlqfbgflj.html

[R73] 分割大日志
来源：http://dali.feifeiyinyue.top/Article/details/gtpeadtvnt.html

split -l 1000 big.log part_
来源：http://dali.yuxming.cn/Article/details/gtwpxrvlsy.html

[R74] 批量重命名
来源：http://dali.quarkkingdee.top/Article/details/gtxmvxgnxe.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinqigfzy.top/Article/details/gtydesmryl.html

[R75] 导出环境变量
来源：http://dali.haohaochexian.top/Article/details/gtppynqzqe.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.tianlin.xyz/Article/details/gtwhpgibyd.html

[R76] 使用临时文件
来源：http://dali.xuanzx.com/Article/details/gtktrlzule.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shuidangran.top/Article/details/gtyimtlcbv.html

[R77] 读取用户输入
来源：http://dali.c1oappe.top/Article/details/gtxcthabtc.html

read -rp "请输入: " ans
来源：http://dali.chenzaomai.com/Article/details/gthxfrkkad.html

[R78] 交互式菜单
来源：http://dali.redwolf501.top/Article/details/gtjedgasmi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.wangdashe.top/Article/details/gtaweuorcc.html

[R79] 解析命令行选项
来源：http://dali.svipenyu.cn/Article/details/gtwgeayckx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cdnleiting.top/Article/details/gtjxkbjytj.html

[R80] 查看脚本执行耗时
来源：http://dali.ivvv.top/Article/details/gtdvviepow.html

time ./run.sh
来源：http://dali.xinyue.icu/Article/details/gtpjtakfah.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtoadiogpz.html

S. C / C++ 专题
来源：http://dali.jinghuilouyu.cn/Article/details/gtaevqxkuq.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtjqbtstok.html

[S01] C：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtjteypdkf.html

#include <stdio.h>
来源：http://dali.hnxiangtu.top/Article/details/gtouxmourc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.nanxinkj.top/Article/details/gtgbjhcshm.html

[S02] C：变量与格式化输出
来源：http://dali.chenzaomai.com/Article/details/gtdnaseuuc.html

int a = 10; printf("%d\n", a);
来源：http://dali.jyoumei.cn/Article/details/gtwlhjvntm.html

[S03] C：读入整数
来源：http://dali.haohaochexian.top/Article/details/gtbtgvcehq.html

int x; scanf("%d", &x);
来源：http://dali.zhaomingkeji.xyz/Article/details/gthshyzuam.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gtwrcqkbnk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.chenzaomai.com/Article/details/gtpncgqzcr.html

[S05] C：字符串长度
来源：http://dali.ppjwa.cn/Article/details/gthqdrdyxc.html

strlen(s)
来源：http://dali.hammf.cn/Article/details/gttuekcimy.html

[S06] C：字符串比较
来源：http://dali.chenlongwang.top/Article/details/gtmhofpuyr.html

strcmp(a, b) == 0
来源：http://dali.redwolf501.top/Article/details/gtbtmnjrec.html

[S07] C：数组遍历求和
来源：http://dali.yj20258888.top/Article/details/gtaudtmgio.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinqigufen.top/Article/details/gtdjtqnsih.html

[S08] C：动态内存分配与释放
来源：http://dali.jqgufenzy.top/Article/details/gtamcdmyxk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.fzhhl.top/Article/details/gthzbwarey.html

[S09] C：结构体定义与初始化
来源：http://dali.havefunace.top/Article/details/gtcpdhopwa.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xuanzx.com/Article/details/gtdeetulad.html

[S10] C：指针与解引用
来源：http://dali.hongshengwenyu.top/Article/details/gtjcolotki.html

int *p = &a;  *p = 5;
来源：http://dali.yuanzhike.top/Article/details/gtowjswqcc.html

[S11] C：逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gtkxowekca.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jyoumei.cn/Article/details/gtztngafxr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hywenlv.cn/Article/details/gtkwkhkmtx.html

fclose(f);
来源：http://dali.ydzc1.top/Article/details/gtszfmtgqa.html

[S12] C：写文件
来源：http://dali.dashuyun.cn/Article/details/gtulbheeqx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.wangdashe.top/Article/details/gtwrlipvsi.html

[S13] C：宏定义
来源：http://dali.daria6918.cn/Article/details/gtvumovphe.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.aibaodan.cn/Article/details/gtjndckkvb.html

[S14] C：枚举
来源：http://dali.hnxiangtu.top/Article/details/gtirytjkrk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhiwuduotai.top/Article/details/gtepdryihf.html

[S15] C：类型转换
来源：http://dali.hnqzz.top/Article/details/gtfejkyjcv.html

(double) a / b
来源：http://dali.daria6918.cn/Article/details/gtfuxhbtxu.html

[S16] C：位操作置位
来源：http://dali.feifeiyinyue.top/Article/details/gtntykarcx.html

x |= (1 << 3);
来源：http://dali.yj202588.top/Article/details/gtodozoqyq.html

[S17] C：安全拼接字符串
来源：http://dali.quarkkingdee.top/Article/details/gtfszesonk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.9152youxi.cn/Article/details/gtscipjorl.html

[S18] C：命令行参数
来源：http://dali.hammf.cn/Article/details/gtzmdoydvf.html

int main(int argc, char **argv)
来源：http://dali.havefunace.top/Article/details/gtiocgevpq.html

[S19] C：快速排序
来源：http://dali.zhiwuduotai.top/Article/details/gtisxpzgoc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.gogol.net.cn/Article/details/gtdddrxsgq.html

[S20] C：二分查找
来源：http://dali.yuxming.cn/Article/details/gtqbgyqsyt.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinqigufen.top/Article/details/gtakzpggfi.html

[S21] C：字符类别判断
来源：http://dali.iojbl.cn/Article/details/gtgztxmznd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhixingplan.top/Article/details/gtzranigsu.html

[S22] C：字符串转数字
来源：http://dali.ppjwa.cn/Article/details/gtuifpjarm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.daria6918.cn/Article/details/gteufuricf.html

[S23] C：随机数
来源：http://dali.dianchejie.cn/Article/details/gtgnbvjrpd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtydzbvkfm.html

[S24] C：获取本地时间
来源：http://dali.vqdsnc.cn/Article/details/gtbagzbxqd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zdqjudy.top/Article/details/gtxlmmmdro.html

[S25] C：内存拷贝
来源：http://dali.gaohongyu789.top/Article/details/gtndyrqful.html

memcpy(dst, src, n);
来源：http://dali.fzhhl.top/Article/details/gtvxsvjrgk.html

[S26] C：内存清零
来源：http://dali.jinqigufen.top/Article/details/gtfwtgfjjx.html

memset(a, 0, sizeof a);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsilymfzn.html

[S27] C：定义常量
来源：http://dali.jlsjyb.cn/Article/details/gtpnglgmsj.html

const double PI = 3.14159;
来源：http://dali.gzhubu.top/Article/details/gtzmsbqyfx.html

[S28] C：静态变量
来源：http://dali.meibo888.top/Article/details/gtcanrojlm.html

static int counter = 0;
来源：http://dali.fengsongda.top/Article/details/gtyrziuexz.html

[S29] C：变参函数
来源：http://dali.cucudq.cn/Article/details/gttmeeedbp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.tian-w.cn/Article/details/gtfaevxqfd.html

[S30] C：头文件保护
来源：http://dali.sufxvd.cn/Article/details/gttzqffvsg.html

#ifndef X_H
来源：http://dali.zhiwuduotai.top/Article/details/gtlkfpojqx.html

#define X_H
来源：http://dali.shuidangran.top/Article/details/gtvpbxwfxb.html

#endif
来源：http://dali.dashuyun.cn/Article/details/gtxmaothkj.html

[S31] C++：Hello World
来源：http://dali.sweek.top/Article/details/gtuudybtrh.html

#include <iostream>
来源：http://dali.ivvv.top/Article/details/gtcvtarepn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.iojbl.cn/Article/details/gtycplgefp.html

[S32] C++：字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtzsxltdfm.html

std::string s = "hi";  s += "!";
来源：http://dali.fzhhl.top/Article/details/gtdgwcfjpf.html

[S33] C++：vector 增删
来源：http://dali.dashuyun.cn/Article/details/gtcxbruahu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jqgufenzy.top/Article/details/gtpeiupirc.html

[S34] C++：遍历 vector
来源：http://dali.cucudq.cn/Article/details/gtysmenqnk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.dianchejie.cn/Article/details/gtuovgifsi.html

[S35] C++：map
来源：http://dali.ybcxt.top/Article/details/gtbibfwpoj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fzhhl.top/Article/details/gtpgqdwbie.html

[S36] C++：unordered_map
来源：http://dali.yonumen.top/Article/details/gtynmeqjyy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aizwys.cn/Article/details/gtgttqkubl.html

[S37] C++：set
来源：http://dali.dianchejie.cn/Article/details/gtxnwkmbrr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhixingplan.top/Article/details/gtlsksuzsu.html

[S38] C++：排序
来源：http://dali.zdqjudy.top/Article/details/gtyrgbwxhh.html

std::sort(v.begin(), v.end());
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmwaruogm.html

[S39] C++：自定义比较器排序
来源：http://dali.xylfe.cn/Article/details/gtadnntfoj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.andypj.xyz/Article/details/gtrlnelpzp.html

[S40] C++：查找元素
来源：http://dali.cqqwz.cn/Article/details/gtxpubilrh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xylfe.cn/Article/details/gtbxpqdxxs.html

[S41] C++：类与构造函数
来源：http://dali.daria6918.cn/Article/details/gtkhqncwbp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ybcxt.top/Article/details/gtceejyjjt.html

[S42] C++：继承与虚函数
来源：http://dali.cqqwz.cn/Article/details/gtzhbvrrva.html

class B : public Base { public: void f() override {} };
来源：http://dali.daria6918.cn/Article/details/gtkmyxuqhr.html

[S43] C++：智能指针
来源：http://dali.haohaochexian.top/Article/details/gtitmbkmto.html

auto p = std::make_unique<int>(5);
来源：http://dali.redwolf501.top/Article/details/gtpommswpt.html

[S44] C++：引用传参
来源：http://dali.yuanzhike.top/Article/details/gtdyaepnek.html

void inc(int &x) { ++x; }
来源：http://dali.xinyue.icu/Article/details/gtrlyirrmg.html

[S45] C++：lambda
来源：http://dali.gotoacloud.top/Article/details/gterggczel.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.haohaochexian.top/Article/details/gtcdcsaygw.html

[S46] C++：函数模板
来源：http://dali.guannengcc.top/Article/details/gtkrtfinyz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.guowangkeji.top/Article/details/gtiuqpjsvs.html

[S47] C++：结构化绑定遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgxlphumu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hnqzz.top/Article/details/gtyyhzhjus.html

[S48] C++：逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gtctklgnnm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.kuanghao11.cn/Article/details/gtkfcbtill.html

while (std::getline(in, line)) { }
来源：http://dali.dianchejie.cn/Article/details/gtxxixrhee.html

[S49] C++：写文件
来源：http://dali.yonumen.top/Article/details/gtknslfujd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hnqzz.top/Article/details/gtyfivzksi.html

[S50] C++：格式化数字
来源：http://dali.jlsjyb.cn/Article/details/gtnchzcuse.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tian-w.cn/Article/details/gtwapkcuvv.html

[S51] C++：显式类型转换
来源：http://dali.shangyingyoupin.top/Article/details/gtyistumdi.html

static_cast<double>(a) / b
来源：http://dali.gaohongyu789.top/Article/details/gtuccahvbz.html

[S52] C++：const 与 noexcept
来源：http://dali.c1oappe.top/Article/details/gtbqgtkcgr.html

int size() const noexcept { return n_; }
来源：http://dali.pycfn.com/Article/details/gtulvoamhp.html

[S53] C++：移动语义
来源：http://dali.dianchejie.cn/Article/details/gtetddwndl.html

std::vector<int> w = std::move(v);
来源：http://dali.havefunace.top/Article/details/gtwhxoegey.html

[S54] C++：异常处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gteufsnctt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cdnleiting.top/Article/details/gtxkencjdf.html

[S55] C++：结构化绑定
来源：http://dali.cashguo.top/Article/details/gtycqavzvj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhoulong.xyz/Article/details/gtwftxuikc.html

[S56] C++：optional
来源：http://dali.yj20258888.top/Article/details/gtemvoeqrv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.birdmap.top/Article/details/gtxdjnvggl.html

[S57] C++：编译期常量
来源：http://dali.yj20258.top/Article/details/gtpfamorhc.html

constexpr int N = 10;
来源：http://dali.andypj.xyz/Article/details/gtwxynvyjb.html

[S58] C++：命名空间
来源：http://dali.gaohongyu789.top/Article/details/gtrkudobjy.html

namespace ns { int f() { return 1; } }
来源：http://dali.haohaochexian.top/Article/details/gtpmkvuqqc.html

[S59] C++：静态断言
来源：http://dali.gogol.net.cn/Article/details/gtruavfutu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xylfe.cn/Article/details/gtnpickgmu.html

[S60] C++：遍历并删除元素
来源：http://dali.guannengcc.top/Article/details/gttcjgohyn.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sweek.top/Article/details/gtlxfiihmb.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gttaybixfn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ppjwa.cn/Article/details/gtkejjpuuf.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtpttqmerx.html

[T01] Kotlin：Hello World
来源：http://dali.snrcjt.cn/Article/details/gtoryjyoxc.html

println("Hello")
来源：http://dali.xuanzx.com/Article/details/gtnqtjepkq.html

[T02] Kotlin：变量
来源：http://dali.tianlin.xyz/Article/details/gtjmtzpnms.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.fzhhl.top/Article/details/gttqjcfayf.html

[T03] Kotlin：字符串模板
来源：http://dali.aizwys.cn/Article/details/gtibyhnuxy.html

"值: $b"
来源：http://dali.quarkkingdee.top/Article/details/gtxkqoelxb.html

[T04] Kotlin：空安全
来源：http://dali.ydzc1.top/Article/details/gtvrmbaspt.html

val n: String? = null;  n?.length
来源：http://dali.andypj.xyz/Article/details/gtgejdmoak.html

[T05] Kotlin：when 表达式
来源：http://dali.gaohongyu789.top/Article/details/gteyfaknlr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhixingplan.top/Article/details/gtqxgsnizr.html

[T06] Kotlin：集合映射
来源：http://dali.gzhubu.top/Article/details/gtknkbrgql.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinqigufen.top/Article/details/gtddtxxehe.html

[T07] Kotlin：集合过滤
来源：http://dali.sysykeji.top/Article/details/gtbscpthqt.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.aibaodan.cn/Article/details/gthoruniiv.html

[T08] Kotlin：数据类
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjgjkbrrq.html

data class User(val name: String, val age: Int)
来源：http://dali.guowangkeji.top/Article/details/gtxozqflzh.html

[T09] Kotlin：扩展函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlvdhaneq.html

fun String.exclaim() = this + "!"
来源：http://dali.hongshengwenyu.top/Article/details/gtycvwakpo.html

[T10] Kotlin：默认参数
来源：http://dali.xuanzx.com/Article/details/gtamthvkfj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj202588.top/Article/details/gtrbfybgwp.html

[T11] Kotlin：协程
来源：http://dali.sufxvd.cn/Article/details/gtkaqyquic.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hongshengwenyu.top/Article/details/gtuzqzkszy.html

[T12] Kotlin：解构声明
来源：http://dali.yuanzhike.top/Article/details/gtxrisukjw.html

val (a, b) = Pair(1, 2)
来源：http://dali.jqgufenzy.top/Article/details/gtbrdinetd.html

[T13] Kotlin：只读 Map
来源：http://dali.jinqigfzy.top/Article/details/gtwkvgvtbv.html

val m = mapOf("a" to 1)
来源：http://dali.0kj1m.cn/Article/details/gtjxwzlaae.html

[T14] Kotlin：循环
来源：http://dali.xuetiantiany.cn/Article/details/gtqulizgzm.html

for (i in 1..10) println(i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqkcnbxqn.html

[T15] Kotlin：接口
来源：http://dali.nwbrower.top/Article/details/gtwjfzwxit.html

interface Shape { fun area(): Double }
来源：http://dali.xinyue.icu/Article/details/gtvksmqsqm.html

[T16] Swift：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtkljfhoga.html

print("Hello")
来源：http://dali.xylfe.cn/Article/details/gtmjckjnxa.html

[T17] Swift：变量与常量
来源：http://dali.hnqzz.top/Article/details/gtbblhxmdc.html

var a = 1;  let b = 2
来源：http://dali.svipenyu.cn/Article/details/gtqcgrfikw.html

[T18] Swift：字符串插值
来源：http://dali.0kj1m.cn/Article/details/gtivkupfoa.html

"值: \(b)"
来源：http://dali.sufxvd.cn/Article/details/gtpmealrrs.html

[T19] Swift：可选绑定
来源：http://dali.jianghu66.top/Article/details/gtqiejgwtf.html

if let n = opt { print(n) }
来源：http://dali.jlsjyb.cn/Article/details/gtucfdzmls.html

[T20] Swift：数组操作
来源：http://dali.xziqi.cn/Article/details/gttvteemat.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.dashuyun.cn/Article/details/gtsinnlxmo.html

[T21] Swift：遍历
来源：http://dali.haohaochexian.top/Article/details/gttpfrquci.html

for x in a { print(x) }
来源：http://dali.zhiwuduotai.top/Article/details/gtljmjgdhu.html

[T22] Swift：字典
来源：http://dali.yj202588.top/Article/details/gtlxivbxex.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jianghu66.top/Article/details/gtwuvdalmm.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gttbtlfopf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ehwqpu.com/Article/details/gtqsppzpae.html

[T24] Swift：闭包
来源：http://dali.mhx1999.top/Article/details/gtumpcaelb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jlsjyb.cn/Article/details/gtiwenumla.html

[T25] Swift：结构体
来源：http://dali.xylfe.cn/Article/details/gtaabpwkgf.html

struct P { var x: Int }
来源：http://dali.hongshengwenyu.top/Article/details/gtclszeadi.html

[T26] Swift：类与重写
来源：http://dali.gaohongyu789.top/Article/details/gtytvpducx.html

class A: Base { override func f() {} }
来源：http://dali.gzhubu.top/Article/details/gtfrbehage.html

[T27] Swift：错误处理
来源：http://dali.aibaodan.cn/Article/details/gtmcaqdkda.html

do { try f() } catch { print(error) }
来源：http://dali.guannengcc.top/Article/details/gttwqdypxl.html

[T28] Swift：枚举
来源：http://dali.cdnleiting.top/Article/details/gtuksgrsiu.html

enum Color { case red, green }
来源：http://dali.haohaochexian.top/Article/details/gtawxbknal.html

[T29] Swift：guard 提前返回
来源：http://dali.wangdashe.top/Article/details/gtitxcctxb.html

guard let x = opt else { return }
来源：http://dali.andypj.xyz/Article/details/gtsittplqk.html

[T30] Swift：协议
来源：http://dali.daria6918.cn/Article/details/gtbxyrqhhe.html

protocol Shape { func area() -> Double }
来源：http://dali.hammf.cn/Article/details/gthlfrykib.html

[T31] Lua：Hello World
来源：http://dali.sysykeji.top/Article/details/gteneaewyv.html

print("Hello")
来源：http://dali.0kj1m.cn/Article/details/gtprzhheop.html

[T32] Lua：局部变量
来源：http://dali.cucudq.cn/Article/details/gtcqrtimzy.html

local a = 1
来源：http://dali.hongshengwenyu.top/Article/details/gthmhzfjgs.html

[T33] Lua：表（数组）
来源：http://dali.zhixingplan.top/Article/details/gtfdlrupeh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xuetiantiany.cn/Article/details/gtpvlueqgj.html

[T34] Lua：遍历表
来源：http://dali.hnqzz.top/Article/details/gtshwbzxbk.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.0kj1m.cn/Article/details/gtdpbscgqn.html

[T35] Lua：字典表
来源：http://dali.ehwqpu.com/Article/details/gtssbzbuze.html

local d = { a = 1 };  d.b = 2
来源：http://dali.meibo888.top/Article/details/gtkiwzfpfw.html

[T36] Lua：函数
来源：http://dali.guannengcc.top/Article/details/gttgbylocr.html

function add(a, b) return a + b end
来源：http://dali.aibaodan.cn/Article/details/gtsefcdbhy.html

[T37] Lua：字符串拼接
来源：http://dali.shzxlz.cn/Article/details/gtzlfiqcnw.html

"a" .. "b"
来源：http://dali.xuanzx.com/Article/details/gtzmpqqlsa.html

[T38] Lua：条件
来源：http://dali.haohaochexian.top/Article/details/gthbqnpwhj.html

if x > 0 then print("正") end
来源：http://dali.pycfn.com/Article/details/gtsrddejvx.html

[T39] Lua：模式匹配
来源：http://dali.jlsjyb.cn/Article/details/gtcivnlwut.html

string.find(s, "%d+")
来源：http://dali.guowangkeji.top/Article/details/gtbmtyezmb.html

[T40] Lua：元表
来源：http://dali.mhx1999.top/Article/details/gtdkmaujrc.html

setmetatable({}, { __index = base })
来源：http://dali.jianghu66.top/Article/details/gtootxjvzb.html

[T41] Perl：Hello World
来源：http://dali.daria6918.cn/Article/details/gtygmdokmr.html

print "Hello\n";
来源：http://dali.9152youxi.cn/Article/details/gtdlnwddfa.html

[T42] Perl：变量类型
来源：http://dali.jinqigufen.top/Article/details/gtyqeirhuz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.dianchejie.cn/Article/details/gtwcoxndlr.html

[T43] Perl：字符串插值
来源：http://dali.zhiwuduotai.top/Article/details/gtruhnxwbs.html

"值: $a"
来源：http://dali.daria6918.cn/Article/details/gtavzsrnht.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gtrytarpdm.html

if ($a > 0) { print "正"; }
来源：http://dali.ppjwa.cn/Article/details/gtjzptpxyo.html

[T45] Perl：数组遍历
来源：http://dali.guannengcc.top/Article/details/gtbmnthpzl.html

for my $x (@arr) { print $x; }
来源：http://dali.hongshengwenyu.top/Article/details/gtlcoddkue.html

[T46] Perl：哈希操作
来源：http://dali.snrcjt.cn/Article/details/gtajlkgpeg.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cqqwz.cn/Article/details/gtztdweblv.html

[T47] Perl：正则捕获
来源：http://dali.ehwqpu.com/Article/details/gtczongkgt.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yuanzhike.top/Article/details/gtcxemsrnb.html

[T48] Perl：正则替换
来源：http://dali.hammf.cn/Article/details/gtznlzswgo.html

$s =~ s/old/new/g;
来源：http://dali.cdnleiting.top/Article/details/gthaxtzecs.html

[T49] Perl：函数
来源：http://dali.daria6918.cn/Article/details/gtswkrbnej.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gtlmaygkgs.html

[T50] Perl：逐行读文件
来源：http://dali.bjfxy.top/Article/details/gtslbhafsu.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.cucudq.cn/Article/details/gttweoyugw.html


<!-- 参考信息 -->