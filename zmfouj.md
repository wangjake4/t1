代发 wailian999

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hysaishi.cn/Article/details/gtnlbvjzyh.html

[R48] awk 取指定列
来源：http://dali.dianchejie.cn/Article/details/gtunoloarr.html

awk '{print $1, $3}' a.txt
来源：http://dali.yuxming.cn/Article/details/gtudiwzcxa.html

[R49] awk 带条件
来源：http://dali.yanxiufei.cn/Article/details/gtsvblbzbv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.guannengcc.top/Article/details/gtswoeazjj.html

[R50] awk 求和
来源：http://dali.hysaishi.cn/Article/details/gtbejyfklv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.wangdashe.top/Article/details/gthpvfvskp.html

[R51] 排序去重取前几
来源：http://dali.hnxiangtu.top/Article/details/gtgvdnpbpx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.aibaodan.cn/Article/details/gtfegntplb.html

[R52] 统计行数
来源：http://dali.tanke756.top/Article/details/gtpbbcawta.html

wc -l a.txt
来源：http://dali.cdnleiting.top/Article/details/gtzerbsoeq.html

[R53] 查看文件头与实时尾
来源：http://dali.yueranfly.top/Article/details/gtkgmmcotx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.meibo888.top/Article/details/gtzlezuelu.html

[R54] 比较两个文件
来源：http://dali.guannengcc.top/Article/details/gtuwebkpmu.html

diff a.txt b.txt
来源：http://dali.chenzaomai.com/Article/details/gtwvlzigqc.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gtozwtwcrr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hnqzz.top/Article/details/gthktzdjkf.html

[R56] 远程拷贝
来源：http://dali.aibaodan.cn/Article/details/gtqfdroylq.html

scp file user@host:/path/
来源：http://dali.chenjidiqi.icu/Article/details/gtedcsuslu.html

[R57] 远程执行命令
来源：http://dali.kuanghao11.cn/Article/details/gtvqaxryjf.html

ssh user@host 'uptime'
来源：http://dali.svipenyu.cn/Article/details/gtgetuchdw.html

[R58] 下载文件
来源：http://dali.iojbl.cn/Article/details/gtxmqtmvig.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jinyuanbaomall.cn/Article/details/gtitqapbrz.html

[R59] 发 POST JSON
来源：http://dali.shuidangran.top/Article/details/gtwtyiyybp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.tianlin.xyz/Article/details/gtwxwrnzic.html

[R60] 只看 HTTP 状态码
来源：http://dali.hongshengwenyu.top/Article/details/gtfidozmjm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hysaishi.cn/Article/details/gtqmvpgoeb.html

[R61] 磁盘占用
来源：http://dali.sxryk.cn/Article/details/gtthanxlwj.html

df -h;  du -sh *
来源：http://dali.ivvv.top/Article/details/gtlzqmgayx.html

[R62] 找最占空间的文件
来源：http://dali.jianghu66.top/Article/details/gtjnaewvaq.html

du -ah . | sort -rh | head -10
来源：http://dali.yangfankeji.com/Article/details/gtfsjdkugo.html

[R63] 内存与进程
来源：http://dali.daxiang520.top/Article/details/gttvotzgxi.html

free -h;  ps aux | grep nginx
来源：http://dali.yj20258.top/Article/details/gtqkyuebrz.html

[R64] 结束进程
来源：http://dali.yonumen.top/Article/details/gtfjvqcvem.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jqgfzy.top/Article/details/gtmlftoxvn.html

[R65] 查看端口占用
来源：http://dali.quarkkingdee.top/Article/details/gtthkkgmtv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zdqjudy.top/Article/details/gtigfagzei.html

[R66] 定时任务
来源：http://dali.mhx1999.top/Article/details/gtoghpgznq.html

crontab -e;  crontab -l
来源：http://dali.9152youxi.cn/Article/details/gtypdzanmb.html

[R67] 生成随机十六进制串
来源：http://dali.yangfankeji.com/Article/details/gtrnllcdfj.html

openssl rand -hex 16
来源：http://dali.jinyuanbaomall.cn/Article/details/gtslmnvbqx.html

[R68] 计算文件校验值
来源：http://dali.quarkkingdee.top/Article/details/gtflbcfwym.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cheryme.top/Article/details/gthbixrwyw.html

[R69] 生成随机密码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpkimqnbo.html

head -c 16 /dev/urandom | base64
来源：http://dali.tanke756.top/Article/details/gtdbijsqki.html

[R70] 时间戳与互转
来源：http://dali.yangfankeji.com/Article/details/gtwvvqvjkm.html

date +%s;  date -d @1700000000
来源：http://dali.pycfn.com/Article/details/gtatfjukxs.html

[R71] 日期格式化
来源：http://dali.zhixingplan.top/Article/details/gtvylagjht.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.fengsongda.top/Article/details/gtoicabwmf.html

[R72] 等待端口就绪
来源：http://dali.iojbl.cn/Article/details/gtuaxgarpe.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.havefunace.top/Article/details/gtkwjvjans.html

[R73] 分割大日志
来源：http://dali.xuetiantiany.cn/Article/details/gtpohbnpbd.html

split -l 1000 big.log part_
来源：http://dali.svipenyu.cn/Article/details/gtroloxosx.html

[R74] 批量重命名
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyiavlgwn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.smart0.xyz/Article/details/gtgyxjnoea.html

[R75] 导出环境变量
来源：http://dali.redwolf501.top/Article/details/gtexrzilvc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.vqdsnc.cn/Article/details/gtgymddoje.html

[R76] 使用临时文件
来源：http://dali.hammf.cn/Article/details/gtezcjiiqg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zycfv.cn/Article/details/gtznntxhwe.html

[R77] 读取用户输入
来源：http://dali.jinghuilouyu.cn/Article/details/gtxleslsss.html

read -rp "请输入: " ans
来源：http://dali.nanxuanxn.top/Article/details/gtpggsciyy.html

[R78] 交互式菜单
来源：http://dali.wangshuangyany.cn/Article/details/gtoufnboxl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.meibo888.top/Article/details/gtjkoexwsm.html

[R79] 解析命令行选项
来源：http://dali.iojbl.cn/Article/details/gtwubbrizk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.kuanghao11.cn/Article/details/gtbvdqzfxj.html

[R80] 查看脚本执行耗时
来源：http://dali.yueranfly.top/Article/details/gtkbrrxrfy.html

time ./run.sh
来源：http://dali.c1oappe.top/Article/details/gtmpytzjsp.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gthgqwlsxh.html

S. C / C++ 专题
来源：http://dali.jlsjyb.cn/Article/details/gtbctuaeiz.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtrhwqaykp.html

[S01] C：Hello World
来源：http://dali.ybcxt.top/Article/details/gtwxytctob.html

#include <stdio.h>
来源：http://dali.dashuyun.cn/Article/details/gtaqktasmp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xinyue.icu/Article/details/gtlbjfzwha.html

[S02] C：变量与格式化输出
来源：http://dali.andypj.xyz/Article/details/gtdkknenkw.html

int a = 10; printf("%d\n", a);
来源：http://dali.9152youxi.cn/Article/details/gtwscqipya.html

[S03] C：读入整数
来源：http://dali.hfpthk.cn/Article/details/gtreagpqmo.html

int x; scanf("%d", &x);
来源：http://dali.ppjwa.cn/Article/details/gtufiohlos.html

[S04] C：字符串复制
来源：http://dali.aibaodan.cn/Article/details/gtesjblbpm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhengqikj.top/Article/details/gteyamaowr.html

[S05] C：字符串长度
来源：http://dali.ppjwa.cn/Article/details/gtbyclhpnj.html

strlen(s)
来源：http://dali.xinyue.icu/Article/details/gtggeklxub.html

[S06] C：字符串比较
来源：http://dali.redwolf501.top/Article/details/gturzvfybm.html

strcmp(a, b) == 0
来源：http://dali.daria6918.cn/Article/details/gtibvwftkl.html

[S07] C：数组遍历求和
来源：http://dali.zhoulong.xyz/Article/details/gtvlmecjfr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhoulong.xyz/Article/details/gttencsvdc.html

[S08] C：动态内存分配与释放
来源：http://dali.nanxinkj.top/Article/details/gtelzctotp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.aibaodan.cn/Article/details/gtazdlmsne.html

[S09] C：结构体定义与初始化
来源：http://dali.fzhhl.top/Article/details/gtdfemtlsw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hammf.cn/Article/details/gtvmyqlujr.html

[S10] C：指针与解引用
来源：http://dali.snrcjt.cn/Article/details/gtfchexthe.html

int *p = &a;  *p = 5;
来源：http://dali.daria6918.cn/Article/details/gturhzeigi.html

[S11] C：逐行读文件
来源：http://dali.daria6918.cn/Article/details/gtzwpkzbca.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shangyingyoupin.top/Article/details/gtuxtxymra.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cheryme.top/Article/details/gtmrhmywyu.html

fclose(f);
来源：http://dali.316326.xyz/Article/details/gtsoczgher.html

[S12] C：写文件
来源：http://dali.yj20258.top/Article/details/gtzxgzbpim.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sufxvd.cn/Article/details/gtymyeoitl.html

[S13] C：宏定义
来源：http://dali.jqgfzy.top/Article/details/gtweecgojg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfpnrjnwk.html

[S14] C：枚举
来源：http://dali.nwbrower.top/Article/details/gtvdzengka.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ivvv.top/Article/details/gtbqjvxwff.html

[S15] C：类型转换
来源：http://dali.cashguo.top/Article/details/gtkgbkqelo.html

(double) a / b
来源：http://dali.sweek.top/Article/details/gtpmuundzd.html

[S16] C：位操作置位
来源：http://dali.zhongyouzk.top/Article/details/gtpyraffcu.html

x |= (1 << 3);
来源：http://dali.daxiang520.top/Article/details/gtedxbzcij.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gtscqjhpuo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cdnleiting.top/Article/details/gtxqejsggp.html

[S18] C：命令行参数
来源：http://dali.vqdsnc.cn/Article/details/gtcebqpivd.html

int main(int argc, char **argv)
来源：http://dali.gaohongyu789.top/Article/details/gtyxhlgsyt.html

[S19] C：快速排序
来源：http://dali.kuanghao11.cn/Article/details/gtgvtmlwgu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ehwqpu.com/Article/details/gtmxwjajqs.html

[S20] C：二分查找
来源：http://dali.pycfn.com/Article/details/gtzfqwechj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ivvv.top/Article/details/gthalrwqch.html

[S21] C：字符类别判断
来源：http://dali.kuanghao11.cn/Article/details/gtvlvmdbfb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.tian-w.cn/Article/details/gtulqdcuap.html

[S22] C：字符串转数字
来源：http://dali.hfpthk.cn/Article/details/gtpmnvznre.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinqigfzy.top/Article/details/gtltttimpx.html

[S23] C：随机数
来源：http://dali.yvedp.cn/Article/details/gtmpevrdft.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shuidangran.top/Article/details/gtxevobcdz.html

[S24] C：获取本地时间
来源：http://dali.jqgufenzy.top/Article/details/gtbwhzkicv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ehwqpu.com/Article/details/gtfgbjojak.html

[S25] C：内存拷贝
来源：http://dali.sufxvd.cn/Article/details/gtccjtsoly.html

memcpy(dst, src, n);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjjcsscez.html

[S26] C：内存清零
来源：http://dali.yongpay.top/Article/details/gtzlstgwcw.html

memset(a, 0, sizeof a);
来源：http://dali.fzhhl.top/Article/details/gtbjymjeuz.html

[S27] C：定义常量
来源：http://dali.aibaodan.cn/Article/details/gteqtoculy.html

const double PI = 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gtoavckmrm.html

[S28] C：静态变量
来源：http://dali.tian-w.cn/Article/details/gtwncvmblz.html

static int counter = 0;
来源：http://dali.wangdashe.top/Article/details/gtfsectwwr.html

[S29] C：变参函数
来源：http://dali.hnxiangtu.top/Article/details/gtxvydwiei.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yonumen.top/Article/details/gtqxplhrdy.html

[S30] C：头文件保护
来源：http://dali.xylfe.cn/Article/details/gtgnffxcpd.html

#ifndef X_H
来源：http://dali.cqqwz.cn/Article/details/gtjfdtkeqc.html

#define X_H
来源：http://dali.jinyuanbaomall.cn/Article/details/gthnignzrh.html

#endif
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwljeilis.html

[S31] C++：Hello World
来源：http://dali.bjfxy.top/Article/details/gtlupgirbn.html

#include <iostream>
来源：http://dali.xuanzx.com/Article/details/gtvjxxfnyf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.dianchejie.cn/Article/details/gtoxzxgkmh.html

[S32] C++：字符串
来源：http://dali.tian-w.cn/Article/details/gtyehkzlhs.html

std::string s = "hi";  s += "!";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuxkevgpj.html

[S33] C++：vector 增删
来源：http://dali.yonumen.top/Article/details/gtwwydtxwn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hongshengwenyu.top/Article/details/gtczzicniq.html

[S34] C++：遍历 vector
来源：http://dali.cqqwz.cn/Article/details/gtavkynsku.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yueranfly.top/Article/details/gtemfmsjal.html

[S35] C++：map
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdjkgkuca.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhongyouzk.top/Article/details/gtffyovopa.html

[S36] C++：unordered_map
来源：http://dali.ehwqpu.com/Article/details/gtkecjisic.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgufenzy.top/Article/details/gtgbozwzie.html

[S37] C++：set
来源：http://dali.pengpengdd.cyou/Article/details/gtedkhakcr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cheryme.top/Article/details/gtmudwckmr.html

[S38] C++：排序
来源：http://dali.cdnleiting.top/Article/details/gthjppozir.html

std::sort(v.begin(), v.end());
来源：http://dali.jyoumei.cn/Article/details/gtxtmdmhot.html

[S39] C++：自定义比较器排序
来源：http://dali.cqqwz.cn/Article/details/gtfeybojea.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.havefunace.top/Article/details/gthesizlly.html

[S40] C++：查找元素
来源：http://dali.chenlongwang.top/Article/details/gtjnuabbkr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.c1oappe.top/Article/details/gtnrciplmv.html

[S41] C++：类与构造函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtuwwgazgq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.snrcjt.cn/Article/details/gttwbdbfsp.html

[S42] C++：继承与虚函数
来源：http://dali.redwolf501.top/Article/details/gtniszfdri.html

class B : public Base { public: void f() override {} };
来源：http://dali.fzhhl.top/Article/details/gtifcwowyu.html

[S43] C++：智能指针
来源：http://dali.xziqi.cn/Article/details/gtftbknwmd.html

auto p = std::make_unique<int>(5);
来源：http://dali.cashguo.top/Article/details/gtkyxxqwtz.html

[S44] C++：引用传参
来源：http://dali.hammf.cn/Article/details/gtssldczdo.html

void inc(int &x) { ++x; }
来源：http://dali.jiagoushi.top/Article/details/gtybynlrya.html

[S45] C++：lambda
来源：http://dali.xuetiantiany.cn/Article/details/gtkdfrfnta.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sysykeji.top/Article/details/gtkaygqsru.html

[S46] C++：函数模板
来源：http://dali.havefunace.top/Article/details/gtcgzzefyc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gogol.net.cn/Article/details/gtrojfvmdq.html

[S47] C++：结构化绑定遍历
来源：http://dali.yvedp.cn/Article/details/gthplpactv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.quarkkingdee.top/Article/details/gtmvtrnqeb.html

[S48] C++：逐行读文件
来源：http://dali.bjfxy.top/Article/details/gtpbbrjons.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gotoacloud.top/Article/details/gthzydurde.html

while (std::getline(in, line)) { }
来源：http://dali.quarkkingdee.top/Article/details/gtjapxnxuq.html

[S49] C++：写文件
来源：http://dali.nanxuanxn.top/Article/details/gtaqguwdat.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ppjwa.cn/Article/details/gtnibwfkda.html

[S50] C++：格式化数字
来源：http://dali.yj202588.top/Article/details/gtsjfwwqbf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gtpwwsfyin.html

[S51] C++：显式类型转换
来源：http://dali.xinyue.icu/Article/details/gtgtobijma.html

static_cast<double>(a) / b
来源：http://dali.hnxiangtu.top/Article/details/gtzxyzhyds.html

[S52] C++：const 与 noexcept
来源：http://dali.tian-w.cn/Article/details/gtdvlnczpu.html

int size() const noexcept { return n_; }
来源：http://dali.jinqigufen.top/Article/details/gtvdihpkse.html

[S53] C++：移动语义
来源：http://dali.zhongyouzk.top/Article/details/gtxopjhiud.html

std::vector<int> w = std::move(v);
来源：http://dali.cheryme.top/Article/details/gtpemdkcim.html

[S54] C++：异常处理
来源：http://dali.yj20258.top/Article/details/gtuuohvzdj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.kuanghao11.cn/Article/details/gthypoattf.html

[S55] C++：结构化绑定
来源：http://dali.zycfv.cn/Article/details/gtvapxtwod.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yuanzhike.top/Article/details/gttcgxfhci.html

[S56] C++：optional
来源：http://dali.gaohongyu789.top/Article/details/gtqcsimrna.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yvedp.cn/Article/details/gtaaggsbha.html

[S57] C++：编译期常量
来源：http://dali.cashguo.top/Article/details/gtwukzfdiu.html

constexpr int N = 10;
来源：http://dali.hywenlv.cn/Article/details/gtkqqjpdmm.html

[S58] C++：命名空间
来源：http://dali.cqqwz.cn/Article/details/gtgjovmxtr.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbyribast.html

[S59] C++：静态断言
来源：http://dali.daria6918.cn/Article/details/gtgdwxxbky.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhixingplan.top/Article/details/gtldfqqbxc.html

[S60] C++：遍历并删除元素
来源：http://dali.nwbrower.top/Article/details/gtaottsqcd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.nanxuanxn.top/Article/details/gtazumywad.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtklunpigc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hnxiangtu.top/Article/details/gtupynzdba.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtkjcuqtrr.html

[T01] Kotlin：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtlqhalrpg.html

println("Hello")
来源：http://dali.guannengcc.top/Article/details/gtjnkqgrkm.html

[T02] Kotlin：变量
来源：http://dali.aibaodan.cn/Article/details/gtedghtjga.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shanyushiyangtech.top/Article/details/gtekcgptbb.html

[T03] Kotlin：字符串模板
来源：http://dali.aibaodan.cn/Article/details/gtfokzqiap.html

"值: $b"
来源：http://dali.hysaishi.cn/Article/details/gtwmfxrwtw.html

[T04] Kotlin：空安全
来源：http://dali.yuxming.cn/Article/details/gtesutwcsg.html

val n: String? = null;  n?.length
来源：http://dali.c1oappe.top/Article/details/gtorgafmki.html

[T05] Kotlin：when 表达式
来源：http://dali.yj20258.top/Article/details/gtwyltzelb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yongpay.top/Article/details/gtszpjmxky.html

[T06] Kotlin：集合映射
来源：http://dali.yuanzhike.top/Article/details/gtoiqllsvr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ehwqpu.com/Article/details/gtrsbivntv.html

[T07] Kotlin：集合过滤
来源：http://dali.fzhhl.top/Article/details/gtrwvtrgeu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.9152youxi.cn/Article/details/gtcyjujdmz.html

[T08] Kotlin：数据类
来源：http://dali.tianlin.xyz/Article/details/gtaoslocqn.html

data class User(val name: String, val age: Int)
来源：http://dali.feifeiyinyue.top/Article/details/gtouqxblce.html

[T09] Kotlin：扩展函数
来源：http://dali.hammf.cn/Article/details/gtouixvkzv.html

fun String.exclaim() = this + "!"
来源：http://dali.c1oappe.top/Article/details/gtphflvxpo.html

[T10] Kotlin：默认参数
来源：http://dali.ivvv.top/Article/details/gtcdfhatzs.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhoulong.xyz/Article/details/gtzqonlkmj.html

[T11] Kotlin：协程
来源：http://dali.yuxming.cn/Article/details/gtykujmibm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yvedp.cn/Article/details/gtczmsapzf.html

[T12] Kotlin：解构声明
来源：http://dali.guowangkeji.top/Article/details/gtsynibfqs.html

val (a, b) = Pair(1, 2)
来源：http://dali.xziqi.cn/Article/details/gttmiiuyph.html

[T13] Kotlin：只读 Map
来源：http://dali.nanxinkj.top/Article/details/gtcylntjbi.html

val m = mapOf("a" to 1)
来源：http://dali.316326.xyz/Article/details/gtdhznbiud.html

[T14] Kotlin：循环
来源：http://dali.nwbrower.top/Article/details/gtvfqoxctr.html

for (i in 1..10) println(i)
来源：http://dali.iojbl.cn/Article/details/gtutzjmgeb.html

[T15] Kotlin：接口
来源：http://dali.chenlongwang.top/Article/details/gthaorcqtq.html

interface Shape { fun area(): Double }
来源：http://dali.hfpthk.cn/Article/details/gtyostkvrh.html

[T16] Swift：Hello World
来源：http://dali.iojbl.cn/Article/details/gttpgjmxcy.html

print("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrdzqofgn.html

[T17] Swift：变量与常量
来源：http://dali.yongpay.top/Article/details/gtxnoecjup.html

var a = 1;  let b = 2
来源：http://dali.hnxiangtu.top/Article/details/gtgfuqpqav.html

[T18] Swift：字符串插值
来源：http://dali.yongpay.top/Article/details/gtbkfmythu.html

"值: \(b)"
来源：http://dali.zhiwuduotai.top/Article/details/gtqcdcmrod.html

[T19] Swift：可选绑定
来源：http://dali.yangfankeji.com/Article/details/gtpqvsgdqn.html

if let n = opt { print(n) }
来源：http://dali.yanxiufei.cn/Article/details/gthiuqhkls.html

[T20] Swift：数组操作
来源：http://dali.pycfn.com/Article/details/gtdzuenjqd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xylfe.cn/Article/details/gtrmpaveci.html

[T21] Swift：遍历
来源：http://dali.fzhhl.top/Article/details/gtqjdyefvg.html

for x in a { print(x) }
来源：http://dali.wangdashe.top/Article/details/gtlnduuxap.html

[T22] Swift：字典
来源：http://dali.316326.xyz/Article/details/gtksfennrj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gaohongyu789.top/Article/details/gtxciovfrp.html

[T23] Swift：函数
来源：http://dali.pengpengdd.cyou/Article/details/gtfhiskibv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.svipenyu.cn/Article/details/gthqanixzp.html

[T24] Swift：闭包
来源：http://dali.fengsongda.top/Article/details/gtrwinsggv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gtvtgdyrfi.html

[T25] Swift：结构体
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyszbtzrc.html

struct P { var x: Int }
来源：http://dali.yj20258.top/Article/details/gtfimfykuc.html

[T26] Swift：类与重写
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbjijshyb.html

class A: Base { override func f() {} }
来源：http://dali.daria6918.cn/Article/details/gtxorzppfn.html

[T27] Swift：错误处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbysiwkve.html

do { try f() } catch { print(error) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpimayhdw.html

[T28] Swift：枚举
来源：http://dali.jianghu66.top/Article/details/gtqvazsvmo.html

enum Color { case red, green }
来源：http://dali.guowangkeji.top/Article/details/gtkrszaraz.html

[T29] Swift：guard 提前返回
来源：http://dali.yj20258888.top/Article/details/gthvskzeiv.html

guard let x = opt else { return }
来源：http://dali.shzxlz.cn/Article/details/gtidkmlmdz.html

[T30] Swift：协议
来源：http://dali.yj20258888.top/Article/details/gtjlvcvcos.html

protocol Shape { func area() -> Double }
来源：http://dali.redwolf501.top/Article/details/gtspgsyvuu.html

[T31] Lua：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtnvliixuu.html

print("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gtajffcgnc.html

[T32] Lua：局部变量
来源：http://dali.nanxuanxn.top/Article/details/gtflkvrdev.html

local a = 1
来源：http://dali.yangfankeji.com/Article/details/gtwmnqyevx.html

[T33] Lua：表（数组）
来源：http://dali.zhixingplan.top/Article/details/gtaliwvnle.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.chenlongwang.top/Article/details/gtranykkeu.html

[T34] Lua：遍历表
来源：http://dali.pycfn.com/Article/details/gtzgubyxww.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ydzc1.top/Article/details/gtyfstjefo.html

[T35] Lua：字典表
来源：http://dali.316326.xyz/Article/details/gtxplausfv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.bjfxy.top/Article/details/gtbscfkguh.html

[T36] Lua：函数
来源：http://dali.9152youxi.cn/Article/details/gtfloxfulx.html

function add(a, b) return a + b end
来源：http://dali.fzhhl.top/Article/details/gtoryzgyne.html

[T37] Lua：字符串拼接
来源：http://dali.zhoulong.xyz/Article/details/gtevqfcnil.html

"a" .. "b"
来源：http://dali.xziqi.cn/Article/details/gtkxzlkkud.html

[T38] Lua：条件
来源：http://dali.yueranfly.top/Article/details/gtdlygwacs.html

if x > 0 then print("正") end
来源：http://dali.shanyushiyangtech.top/Article/details/gtqqckrelh.html

[T39] Lua：模式匹配
来源：http://dali.yvedp.cn/Article/details/gtucbymxob.html

string.find(s, "%d+")
来源：http://dali.jiagoushi.top/Article/details/gtmcexjxpk.html

[T40] Lua：元表
来源：http://dali.yanxiufei.cn/Article/details/gtzzpgcovq.html

setmetatable({}, { __index = base })
来源：http://dali.cqqwz.cn/Article/details/gtyrpedvll.html

[T41] Perl：Hello World
来源：http://dali.cdnleiting.top/Article/details/gtavprorhz.html

print "Hello\n";
来源：http://dali.zdqjudy.top/Article/details/gtgmvzifnc.html

[T42] Perl：变量类型
来源：http://dali.tian-w.cn/Article/details/gtjwgacvsv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jianghu66.top/Article/details/gtpelspkom.html

[T43] Perl：字符串插值
来源：http://dali.yueranfly.top/Article/details/gtwojlcfvh.html

"值: $a"
来源：http://dali.tianlin.xyz/Article/details/gtyvorbdmd.html

[T44] Perl：条件
来源：http://dali.bjfxy.top/Article/details/gtbmyzgyhv.html

if ($a > 0) { print "正"; }
来源：http://dali.zhongyouzk.top/Article/details/gtblnrpzzd.html

[T45] Perl：数组遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmggkpzwd.html

for my $x (@arr) { print $x; }
来源：http://dali.yj20258.top/Article/details/gtpwnpmaej.html

[T46] Perl：哈希操作
来源：http://dali.hysaishi.cn/Article/details/gtnyqgnljw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cdnleiting.top/Article/details/gtihdhltso.html

[T47] Perl：正则捕获
来源：http://dali.xuanzx.com/Article/details/gtrunnrvvw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.birdmap.top/Article/details/gttpygfawz.html

[T48] Perl：正则替换
来源：http://dali.chenlongwang.top/Article/details/gtemezuxjx.html

$s =~ s/old/new/g;
来源：http://dali.pycfn.com/Article/details/gtrkrtincz.html

[T49] Perl：函数
来源：http://dali.havefunace.top/Article/details/gtmahauijw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ybcxt.top/Article/details/gtxemdknhx.html

[T50] Perl：逐行读文件
来源：http://dali.xinyue.icu/Article/details/gtolrghmih.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yanxiufei.cn/Article/details/gtmarsgfem.html


<!-- 参考信息 -->