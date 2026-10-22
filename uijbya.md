代发 wailian999

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yuanzhike.top/Article/details/gtzcqfynvx.html

[R48] awk 取指定列
来源：http://dali.jinghuilouyu.cn/Article/details/gtxitftjhb.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinqigufen.top/Article/details/gtmmcadtlj.html

[R49] awk 带条件
来源：http://dali.jyoumei.cn/Article/details/gtazzgljsc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.andypj.xyz/Article/details/gtpwqboqeq.html

[R50] awk 求和
来源：http://dali.iojbl.cn/Article/details/gtametukye.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cqqwz.cn/Article/details/gtalwexffl.html

[R51] 排序去重取前几
来源：http://dali.fzhhl.top/Article/details/gtojtivrfq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.meibo888.top/Article/details/gtsaslsxwd.html

[R52] 统计行数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoyefgpld.html

wc -l a.txt
来源：http://dali.xuanzx.com/Article/details/gtvxefhgcj.html

[R53] 查看文件头与实时尾
来源：http://dali.jlsjyb.cn/Article/details/gtwcpwzffd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yongpay.top/Article/details/gthihhmerk.html

[R54] 比较两个文件
来源：http://dali.sxryk.cn/Article/details/gtetjbmpws.html

diff a.txt b.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtdxvdzchw.html

[R55] 压缩与解压
来源：http://dali.xuanzx.com/Article/details/gteccpkxkt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.nanxuanxn.top/Article/details/gtlskjidhk.html

[R56] 远程拷贝
来源：http://dali.pycfn.com/Article/details/gtvhpvpmvr.html

scp file user@host:/path/
来源：http://dali.ivvv.top/Article/details/gtajbdhdyx.html

[R57] 远程执行命令
来源：http://dali.ppjwa.cn/Article/details/gtqazxmqtp.html

ssh user@host 'uptime'
来源：http://dali.cdnleiting.top/Article/details/gttmvehmhc.html

[R58] 下载文件
来源：http://dali.sxryk.cn/Article/details/gtoxzdtszq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xuetiantiany.cn/Article/details/gtamcmyifm.html

[R59] 发 POST JSON
来源：http://dali.ydzc1.top/Article/details/gtijrytvyy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.meibo888.top/Article/details/gtzgrzfzhf.html

[R60] 只看 HTTP 状态码
来源：http://dali.sysykeji.top/Article/details/gtodjcupoe.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ydzc1.top/Article/details/gtksqettqf.html

[R61] 磁盘占用
来源：http://dali.zycfv.cn/Article/details/gtdmfvlucv.html

df -h;  du -sh *
来源：http://dali.shangyingyoupin.top/Article/details/gtojhnufkz.html

[R62] 找最占空间的文件
来源：http://dali.jqgufenzy.top/Article/details/gtsttydxws.html

du -ah . | sort -rh | head -10
来源：http://dali.jinqigfzy.top/Article/details/gtuzidrzce.html

[R63] 内存与进程
来源：http://dali.zdqjudy.top/Article/details/gtmjzzqrot.html

free -h;  ps aux | grep nginx
来源：http://dali.yj20258.top/Article/details/gtfcpmuyqu.html

[R64] 结束进程
来源：http://dali.zhixingplan.top/Article/details/gtqakawcba.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jqgufenzy.top/Article/details/gtgpmxdtrc.html

[R65] 查看端口占用
来源：http://dali.jqgfzy.top/Article/details/gtdauxwwbz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shangyingyoupin.top/Article/details/gtmnucztku.html

[R66] 定时任务
来源：http://dali.chenjidiqi.icu/Article/details/gtmkjvokdg.html

crontab -e;  crontab -l
来源：http://dali.kuanghao11.cn/Article/details/gtmwgommcy.html

[R67] 生成随机十六进制串
来源：http://dali.sysykeji.top/Article/details/gtazmmyees.html

openssl rand -hex 16
来源：http://dali.pengpengdd.cyou/Article/details/gtpbthieaj.html

[R68] 计算文件校验值
来源：http://dali.yj20258888.top/Article/details/gtajhbrcwg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtwitsygcc.html

[R69] 生成随机密码
来源：http://dali.cheryme.top/Article/details/gtxoyvvuaa.html

head -c 16 /dev/urandom | base64
来源：http://dali.meibo888.top/Article/details/gtqotsrepr.html

[R70] 时间戳与互转
来源：http://dali.yj202588.top/Article/details/gthiustvhd.html

date +%s;  date -d @1700000000
来源：http://dali.gzhubu.top/Article/details/gttqohilux.html

[R71] 日期格式化
来源：http://dali.pycfn.com/Article/details/gtbrpddioa.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ppjwa.cn/Article/details/gtqimciixk.html

[R72] 等待端口就绪
来源：http://dali.yj202588.top/Article/details/gtyshdkjtn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhiwuduotai.top/Article/details/gtjcllsryh.html

[R73] 分割大日志
来源：http://dali.zhongyouzk.top/Article/details/gtpasrplsr.html

split -l 1000 big.log part_
来源：http://dali.ehwqpu.com/Article/details/gtizzqiyvn.html

[R74] 批量重命名
来源：http://dali.chenlongwang.top/Article/details/gtrklkkkgl.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.iojbl.cn/Article/details/gtwvhnesqa.html

[R75] 导出环境变量
来源：http://dali.jlsjyb.cn/Article/details/gtylbynzoo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.aizwys.cn/Article/details/gtnbtkadqz.html

[R76] 使用临时文件
来源：http://dali.sweek.top/Article/details/gtyyywzdso.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.haohaochexian.top/Article/details/gtkvmpwuay.html

[R77] 读取用户输入
来源：http://dali.jqgfzy.top/Article/details/gtqmbcrjev.html

read -rp "请输入: " ans
来源：http://dali.jyoumei.cn/Article/details/gtqejppzml.html

[R78] 交互式菜单
来源：http://dali.cucudq.cn/Article/details/gtqprwakza.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hysaishi.cn/Article/details/gtshhzefqv.html

[R79] 解析命令行选项
来源：http://dali.nwbrower.top/Article/details/gtsjjrrqso.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ybcxt.top/Article/details/gtfgtvzyyx.html

[R80] 查看脚本执行耗时
来源：http://dali.guowangkeji.top/Article/details/gtmnywpczf.html

time ./run.sh
来源：http://dali.hnqzz.top/Article/details/gtsbzbrhwz.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgdxktdnm.html

S. C / C++ 专题
来源：http://dali.gaohongyu789.top/Article/details/gtwfkndqtq.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtvlyetxrn.html

[S01] C：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyfjymtyc.html

#include <stdio.h>
来源：http://dali.smart0.xyz/Article/details/gtcovnafdu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yvedp.cn/Article/details/gtajhkxpyp.html

[S02] C：变量与格式化输出
来源：http://dali.pycfn.com/Article/details/gttoammdsu.html

int a = 10; printf("%d\n", a);
来源：http://dali.daxiang520.top/Article/details/gtsbvaxzjm.html

[S03] C：读入整数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwsidwsot.html

int x; scanf("%d", &x);
来源：http://dali.cqqwz.cn/Article/details/gtzsovmhyr.html

[S04] C：字符串复制
来源：http://dali.wangdashe.top/Article/details/gtjsqmhypn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jiagoushi.top/Article/details/gtophxkbmt.html

[S05] C：字符串长度
来源：http://dali.fzhhl.top/Article/details/gtumcayuvr.html

strlen(s)
来源：http://dali.ydzc1.top/Article/details/gttljtsfsh.html

[S06] C：字符串比较
来源：http://dali.yj202588.top/Article/details/gtpwwhgiaj.html

strcmp(a, b) == 0
来源：http://dali.shangyingyoupin.top/Article/details/gtysurgngq.html

[S07] C：数组遍历求和
来源：http://dali.sxryk.cn/Article/details/gtajfuylbk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.svipenyu.cn/Article/details/gtbnydjdgi.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gtyqqsphfd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yangfankeji.com/Article/details/gtpgsvtumq.html

[S09] C：结构体定义与初始化
来源：http://dali.zycfv.cn/Article/details/gtfojgcryb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shanyushiyangtech.top/Article/details/gtwflesvgo.html

[S10] C：指针与解引用
来源：http://dali.yueranfly.top/Article/details/gtbnnfblya.html

int *p = &a;  *p = 5;
来源：http://dali.yangfankeji.com/Article/details/gtocggxfnj.html

[S11] C：逐行读文件
来源：http://dali.yj20258.top/Article/details/gtckbbtqxt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.sysykeji.top/Article/details/gtekwlrnte.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ybcxt.top/Article/details/gtzeupwygt.html

fclose(f);
来源：http://dali.tanke756.top/Article/details/gtfucaikbb.html

[S12] C：写文件
来源：http://dali.nanxuanxn.top/Article/details/gtnmhuogqt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ybcxt.top/Article/details/gtsnzcyjaj.html

[S13] C：宏定义
来源：http://dali.tanke756.top/Article/details/gtnhhfiorz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.0kj1m.cn/Article/details/gttqmtiwlx.html

[S14] C：枚举
来源：http://dali.hysaishi.cn/Article/details/gtoqltxjdy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.chenlongwang.top/Article/details/gtwtnpllsf.html

[S15] C：类型转换
来源：http://dali.yj202588.top/Article/details/gtelibzrjj.html

(double) a / b
来源：http://dali.snrcjt.cn/Article/details/gtvsuxiwdr.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gtkfkgdajz.html

x |= (1 << 3);
来源：http://dali.yj202588.top/Article/details/gtikeujvgv.html

[S17] C：安全拼接字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtebkzedze.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xziqi.cn/Article/details/gtbrbnfxbh.html

[S18] C：命令行参数
来源：http://dali.aizwys.cn/Article/details/gtowlhzzgx.html

int main(int argc, char **argv)
来源：http://dali.gogol.net.cn/Article/details/gtjdjctlbn.html

[S19] C：快速排序
来源：http://dali.yvedp.cn/Article/details/gthlycmhgg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xuanzx.com/Article/details/gtjlzsrlva.html

[S20] C：二分查找
来源：http://dali.nanxuanxn.top/Article/details/gtatcrfdzw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yongpay.top/Article/details/gtjeonznbd.html

[S21] C：字符类别判断
来源：http://dali.gaohongyu789.top/Article/details/gtnojkrqhg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.chenjidiqi.icu/Article/details/gtllekqvco.html

[S22] C：字符串转数字
来源：http://dali.zhengqikj.top/Article/details/gtjhsarxag.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.fengsongda.top/Article/details/gtkjfpnibh.html

[S23] C：随机数
来源：http://dali.ehwqpu.com/Article/details/gtwzymfmpy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj202588.top/Article/details/gtablzgust.html

[S24] C：获取本地时间
来源：http://dali.jinqigufen.top/Article/details/gttlgsmzuw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xuetiantiany.cn/Article/details/gtbtiflvrc.html

[S25] C：内存拷贝
来源：http://dali.zhoulong.xyz/Article/details/gteeajyntt.html

memcpy(dst, src, n);
来源：http://dali.birdmap.top/Article/details/gtyimlkouj.html

[S26] C：内存清零
来源：http://dali.ppjwa.cn/Article/details/gtxdmfxdvr.html

memset(a, 0, sizeof a);
来源：http://dali.xziqi.cn/Article/details/gtdnxjtfzy.html

[S27] C：定义常量
来源：http://dali.jianghu66.top/Article/details/gtdniascim.html

const double PI = 3.14159;
来源：http://dali.redwolf501.top/Article/details/gtlavyeplg.html

[S28] C：静态变量
来源：http://dali.jianghu66.top/Article/details/gtknntvdbu.html

static int counter = 0;
来源：http://dali.jqgufenzy.top/Article/details/gtilstscsa.html

[S29] C：变参函数
来源：http://dali.iojbl.cn/Article/details/gtzpuozdyu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.guannengcc.top/Article/details/gtbweohsih.html

[S30] C：头文件保护
来源：http://dali.316326.xyz/Article/details/gtousvpowb.html

#ifndef X_H
来源：http://dali.pengpengdd.cyou/Article/details/gtnavlgkyy.html

#define X_H
来源：http://dali.ehwqpu.com/Article/details/gttxxmtmau.html

#endif
来源：http://dali.fzhhl.top/Article/details/gtexmahjdu.html

[S31] C++：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtguzawoza.html

#include <iostream>
来源：http://dali.sysykeji.top/Article/details/gtxtywlpte.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gzhubu.top/Article/details/gtmuhonrez.html

[S32] C++：字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtusbpzpft.html

std::string s = "hi";  s += "!";
来源：http://dali.yj20258888.top/Article/details/gtqwmlbghp.html

[S33] C++：vector 增删
来源：http://dali.yj20258888.top/Article/details/gtnvjwtoru.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.dianchejie.cn/Article/details/gttweenjej.html

[S34] C++：遍历 vector
来源：http://dali.sysykeji.top/Article/details/gtxckckhud.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gotoacloud.top/Article/details/gteidimukh.html

[S35] C++：map
来源：http://dali.yuxming.cn/Article/details/gtnbvatyyr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.316326.xyz/Article/details/gtvanqzkfr.html

[S36] C++：unordered_map
来源：http://dali.yonumen.top/Article/details/gtvhrxqmxu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.bjfxy.top/Article/details/gtjpzlquai.html

[S37] C++：set
来源：http://dali.gotoacloud.top/Article/details/gtvolhofpv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.wangdashe.top/Article/details/gteaklqvvf.html

[S38] C++：排序
来源：http://dali.guannengcc.top/Article/details/gtfkeuejgr.html

std::sort(v.begin(), v.end());
来源：http://dali.iojbl.cn/Article/details/gttjrlxzrg.html

[S39] C++：自定义比较器排序
来源：http://dali.aizwys.cn/Article/details/gtdiuagitq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.snrcjt.cn/Article/details/gtngbokcck.html

[S40] C++：查找元素
来源：http://dali.hnqzz.top/Article/details/gtdkhgxprg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.quarkkingdee.top/Article/details/gtnhdhkswy.html

[S41] C++：类与构造函数
来源：http://dali.yueranfly.top/Article/details/gtpiyebqwo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jinghuilouyu.cn/Article/details/gtocykqkqs.html

[S42] C++：继承与虚函数
来源：http://dali.yuxming.cn/Article/details/gtmejjcfxm.html

class B : public Base { public: void f() override {} };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnggztris.html

[S43] C++：智能指针
来源：http://dali.jiagoushi.top/Article/details/gtymiqfsau.html

auto p = std::make_unique<int>(5);
来源：http://dali.xinyue.icu/Article/details/gtvqnynrji.html

[S44] C++：引用传参
来源：http://dali.nanxinkj.top/Article/details/gtyberedqu.html

void inc(int &x) { ++x; }
来源：http://dali.quarkkingdee.top/Article/details/gtfatdlwbm.html

[S45] C++：lambda
来源：http://dali.nwbrower.top/Article/details/gtjhrpmrej.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yj20258.top/Article/details/gtvwuoggon.html

[S46] C++：函数模板
来源：http://dali.dianchejie.cn/Article/details/gtrbcnfjzc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtacgwpwhj.html

[S47] C++：结构化绑定遍历
来源：http://dali.ybcxt.top/Article/details/gtllqhzmnm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.vqdsnc.cn/Article/details/gtjrfzzifs.html

[S48] C++：逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gtxymqijde.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.wangdashe.top/Article/details/gtdarjuhec.html

while (std::getline(in, line)) { }
来源：http://dali.jqgufenzy.top/Article/details/gtmjtvgnye.html

[S49] C++：写文件
来源：http://dali.shzxlz.cn/Article/details/gtxozfgbyd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xuetiantiany.cn/Article/details/gttulmepek.html

[S50] C++：格式化数字
来源：http://dali.zhixingplan.top/Article/details/gtcnibevsq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yanxiufei.cn/Article/details/gtlhzunblt.html

[S51] C++：显式类型转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwhkjzyhd.html

static_cast<double>(a) / b
来源：http://dali.316326.xyz/Article/details/gteyjbdcuj.html

[S52] C++：const 与 noexcept
来源：http://dali.xuetiantiany.cn/Article/details/gtskjrupyp.html

int size() const noexcept { return n_; }
来源：http://dali.hfpthk.cn/Article/details/gtdocyjmes.html

[S53] C++：移动语义
来源：http://dali.ybcxt.top/Article/details/gtfpbfmpzc.html

std::vector<int> w = std::move(v);
来源：http://dali.yj20258888.top/Article/details/gtqpvemiia.html

[S54] C++：异常处理
来源：http://dali.jlsjyb.cn/Article/details/gtmqgirbgz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.feifeiyinyue.top/Article/details/gthhybnucl.html

[S55] C++：结构化绑定
来源：http://dali.hysaishi.cn/Article/details/gtwsbainqc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.nwbrower.top/Article/details/gtvgdcywib.html

[S56] C++：optional
来源：http://dali.birdmap.top/Article/details/gtovunnxix.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sysykeji.top/Article/details/gtdbpremhc.html

[S57] C++：编译期常量
来源：http://dali.gzhubu.top/Article/details/gtzqvwzfnv.html

constexpr int N = 10;
来源：http://dali.hfpthk.cn/Article/details/gtrmpramer.html

[S58] C++：命名空间
来源：http://dali.aibaodan.cn/Article/details/gtdkdfrhvb.html

namespace ns { int f() { return 1; } }
来源：http://dali.cheryme.top/Article/details/gtfraybwzq.html

[S59] C++：静态断言
来源：http://dali.feifeiyinyue.top/Article/details/gtevcygkqq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shuidangran.top/Article/details/gtwouwptgd.html

[S60] C++：遍历并删除元素
来源：http://dali.zhengqikj.top/Article/details/gtijmrqfdh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.iojbl.cn/Article/details/gtsqbxmome.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtyygwlubn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yongpay.top/Article/details/gtyxikibpf.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtjdcfoxey.html

[T01] Kotlin：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtghatnxuk.html

println("Hello")
来源：http://dali.snrcjt.cn/Article/details/gtsnfbjtwu.html

[T02] Kotlin：变量
来源：http://dali.jlsjyb.cn/Article/details/gtdptazxaw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhoulong.xyz/Article/details/gtltvimsws.html

[T03] Kotlin：字符串模板
来源：http://dali.hongshengwenyu.top/Article/details/gtwgmoxbsp.html

"值: $b"
来源：http://dali.zdqjudy.top/Article/details/gtqgczekhk.html

[T04] Kotlin：空安全
来源：http://dali.fengsongda.top/Article/details/gtplxpibrb.html

val n: String? = null;  n?.length
来源：http://dali.jiagoushi.top/Article/details/gtljwhjqsj.html

[T05] Kotlin：when 表达式
来源：http://dali.yanxiufei.cn/Article/details/gtzhllnqjp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ybcxt.top/Article/details/gtixalyoov.html

[T06] Kotlin：集合映射
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkziaijdu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.daria6918.cn/Article/details/gttigmwjcp.html

[T07] Kotlin：集合过滤
来源：http://dali.snrcjt.cn/Article/details/gthzguczan.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhoulong.xyz/Article/details/gtxtbowuid.html

[T08] Kotlin：数据类
来源：http://dali.gaohongyu789.top/Article/details/gtiaeijuto.html

data class User(val name: String, val age: Int)
来源：http://dali.yj202588.top/Article/details/gtsfgdtpls.html

[T09] Kotlin：扩展函数
来源：http://dali.yuxming.cn/Article/details/gtzupgjkwk.html

fun String.exclaim() = this + "!"
来源：http://dali.vqdsnc.cn/Article/details/gtnjmfwrsh.html

[T10] Kotlin：默认参数
来源：http://dali.jqgufenzy.top/Article/details/gtzjsiogdk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj20258888.top/Article/details/gtamddcaai.html

[T11] Kotlin：协程
来源：http://dali.jyoumei.cn/Article/details/gtkifzezaw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hywenlv.cn/Article/details/gtdnvjwmen.html

[T12] Kotlin：解构声明
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtooacdrjf.html

val (a, b) = Pair(1, 2)
来源：http://dali.gotoacloud.top/Article/details/gtefepgvfr.html

[T13] Kotlin：只读 Map
来源：http://dali.c1oappe.top/Article/details/gtnbxwaafx.html

val m = mapOf("a" to 1)
来源：http://dali.jqgfzy.top/Article/details/gtgusbmuol.html

[T14] Kotlin：循环
来源：http://dali.xziqi.cn/Article/details/gtdhtqgpcb.html

for (i in 1..10) println(i)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrhhrqcxl.html

[T15] Kotlin：接口
来源：http://dali.vqdsnc.cn/Article/details/gtuhgkuptf.html

interface Shape { fun area(): Double }
来源：http://dali.cdnleiting.top/Article/details/gtstgmiskt.html

[T16] Swift：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtjjqadyca.html

print("Hello")
来源：http://dali.bjfxy.top/Article/details/gteiwcdgug.html

[T17] Swift：变量与常量
来源：http://dali.jiagoushi.top/Article/details/gtlipyvwwg.html

var a = 1;  let b = 2
来源：http://dali.jinqigfzy.top/Article/details/gtipbawrax.html

[T18] Swift：字符串插值
来源：http://dali.c1oappe.top/Article/details/gtzlpsmxqt.html

"值: \(b)"
来源：http://dali.svipenyu.cn/Article/details/gtxqfoftff.html

[T19] Swift：可选绑定
来源：http://dali.yj20258888.top/Article/details/gtbegjsaom.html

if let n = opt { print(n) }
来源：http://dali.0kj1m.cn/Article/details/gtzhqwrmax.html

[T20] Swift：数组操作
来源：http://dali.nanxuanxn.top/Article/details/gtqgcpntqs.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.sweek.top/Article/details/gttttwhwan.html

[T21] Swift：遍历
来源：http://dali.havefunace.top/Article/details/gtzupmnzgu.html

for x in a { print(x) }
来源：http://dali.zhixingplan.top/Article/details/gtnwnqvofa.html

[T22] Swift：字典
来源：http://dali.haohaochexian.top/Article/details/gtufibmrdr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zdqjudy.top/Article/details/gtbykybxkl.html

[T23] Swift：函数
来源：http://dali.jqgufenzy.top/Article/details/gtqqwtbfwf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.snrcjt.cn/Article/details/gtyyiwkayu.html

[T24] Swift：闭包
来源：http://dali.nanxinkj.top/Article/details/gtvigkrftl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ppjwa.cn/Article/details/gtgdnfcncl.html

[T25] Swift：结构体
来源：http://dali.hammf.cn/Article/details/gtszytjknu.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gtfirslvsb.html

[T26] Swift：类与重写
来源：http://dali.wangdashe.top/Article/details/gtdylydxvf.html

class A: Base { override func f() {} }
来源：http://dali.nwbrower.top/Article/details/gtewbutwox.html

[T27] Swift：错误处理
来源：http://dali.gaohongyu789.top/Article/details/gtprmejolj.html

do { try f() } catch { print(error) }
来源：http://dali.andypj.xyz/Article/details/gtfoscplkg.html

[T28] Swift：枚举
来源：http://dali.ybcxt.top/Article/details/gtepdxbdnw.html

enum Color { case red, green }
来源：http://dali.fzhhl.top/Article/details/gtemfsfqti.html

[T29] Swift：guard 提前返回
来源：http://dali.yj20258888.top/Article/details/gthglhhfox.html

guard let x = opt else { return }
来源：http://dali.birdmap.top/Article/details/gtjbblcdby.html

[T30] Swift：协议
来源：http://dali.yuxming.cn/Article/details/gtbyyjeduh.html

protocol Shape { func area() -> Double }
来源：http://dali.hfpthk.cn/Article/details/gtqxvhqwrs.html

[T31] Lua：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtrtmdicpq.html

print("Hello")
来源：http://dali.jqgfzy.top/Article/details/gtgrsjtilu.html

[T32] Lua：局部变量
来源：http://dali.yanxiufei.cn/Article/details/gtyplnqtsn.html

local a = 1
来源：http://dali.xylfe.cn/Article/details/gtcnwidcep.html

[T33] Lua：表（数组）
来源：http://dali.sweek.top/Article/details/gtxougygaq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinyuanbaomall.cn/Article/details/gtszrpudcu.html

[T34] Lua：遍历表
来源：http://dali.hongshengwenyu.top/Article/details/gtayzhaddb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.haohaochexian.top/Article/details/gtvcjyjgks.html

[T35] Lua：字典表
来源：http://dali.shanyushiyangkeji.top/Article/details/gttbohjdki.html

local d = { a = 1 };  d.b = 2
来源：http://dali.pengpengdd.cyou/Article/details/gtvzaskiem.html

[T36] Lua：函数
来源：http://dali.chenzaomai.com/Article/details/gtsnxvzljw.html

function add(a, b) return a + b end
来源：http://dali.iojbl.cn/Article/details/gtqigvqeqb.html

[T37] Lua：字符串拼接
来源：http://dali.yuxming.cn/Article/details/gtsyjaqwfi.html

"a" .. "b"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxhfacznx.html

[T38] Lua：条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtravgzton.html

if x > 0 then print("正") end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsnvyinyu.html

[T39] Lua：模式匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtsixepgxp.html

string.find(s, "%d+")
来源：http://dali.shzxlz.cn/Article/details/gtpcmwvans.html

[T40] Lua：元表
来源：http://dali.wangshuangyany.cn/Article/details/gtbruscjij.html

setmetatable({}, { __index = base })
来源：http://dali.ppjwa.cn/Article/details/gtialdifyu.html

[T41] Perl：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtavfkyhui.html

print "Hello\n";
来源：http://dali.iojbl.cn/Article/details/gtppumznfo.html

[T42] Perl：变量类型
来源：http://dali.xylfe.cn/Article/details/gtpzuufggk.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sysykeji.top/Article/details/gtgfestxri.html

[T43] Perl：字符串插值
来源：http://dali.cdnleiting.top/Article/details/gtmsvuguqt.html

"值: $a"
来源：http://dali.daxiang520.top/Article/details/gtzkhbavux.html

[T44] Perl：条件
来源：http://dali.chenzaomai.com/Article/details/gtkrjzlmch.html

if ($a > 0) { print "正"; }
来源：http://dali.mhx1999.top/Article/details/gthgigbnge.html

[T45] Perl：数组遍历
来源：http://dali.dianchejie.cn/Article/details/gtogxrzyav.html

for my $x (@arr) { print $x; }
来源：http://dali.quarkkingdee.top/Article/details/gtktrrgtlp.html

[T46] Perl：哈希操作
来源：http://dali.cashguo.top/Article/details/gtmrebznav.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jqgfzy.top/Article/details/gtaahoojfs.html

[T47] Perl：正则捕获
来源：http://dali.hnqzz.top/Article/details/gtirkbvaas.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zdqjudy.top/Article/details/gtlqibhbhe.html

[T48] Perl：正则替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnrwhmzfh.html

$s =~ s/old/new/g;
来源：http://dali.cheryme.top/Article/details/gtacqmefwx.html

[T49] Perl：函数
来源：http://dali.jinqigufen.top/Article/details/gtyfxjukyx.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.aizwys.cn/Article/details/gtlgxgpfpr.html

[T50] Perl：逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gtdouhlvig.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gzhubu.top/Article/details/gtjshacfib.html


<!-- 参考信息 -->