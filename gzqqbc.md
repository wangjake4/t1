代发 wailian999

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ywan-chungtsiang.top/Article/details/gthjunjixi.html

[R54] 比较两个文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtwcxdqsbm.html

diff a.txt b.txt
来源：http://dali.yj202588.top/Article/details/gthylslicy.html

[R55] 压缩与解压
来源：http://dali.yongpay.top/Article/details/gtiirzhrve.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhiwuduotai.top/Article/details/gtnroprqmz.html

[R56] 远程拷贝
来源：http://dali.quarkkingdee.top/Article/details/gtmttxhmol.html

scp file user@host:/path/
来源：http://dali.316326.xyz/Article/details/gtfppfdyei.html

[R57] 远程执行命令
来源：http://dali.jyoumei.cn/Article/details/gttreitgkq.html

ssh user@host 'uptime'
来源：http://dali.jinghuilouyu.cn/Article/details/gteqwptmqu.html

[R58] 下载文件
来源：http://dali.jiagoushi.top/Article/details/gthscvpsnd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.0kj1m.cn/Article/details/gtuvumcegi.html

[R59] 发 POST JSON
来源：http://dali.bjfxy.top/Article/details/gtwelpcwjd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cucudq.cn/Article/details/gtsxyvkgbo.html

[R60] 只看 HTTP 状态码
来源：http://dali.pengpengdd.cyou/Article/details/gtnyupczmg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.9152youxi.cn/Article/details/gtxthgbnky.html

[R61] 磁盘占用
来源：http://dali.zhixingplan.top/Article/details/gtbnntoghl.html

df -h;  du -sh *
来源：http://dali.xuanzx.com/Article/details/gtlctbdjct.html

[R62] 找最占空间的文件
来源：http://dali.cqqwz.cn/Article/details/gtceptkest.html

du -ah . | sort -rh | head -10
来源：http://dali.hywenlv.cn/Article/details/gthvhkiszl.html

[R63] 内存与进程
来源：http://dali.pengpengdd.cyou/Article/details/gtutwdvzwy.html

free -h;  ps aux | grep nginx
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbbwnwrjw.html

[R64] 结束进程
来源：http://dali.jianghu66.top/Article/details/gtpjgoqnwf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gogol.net.cn/Article/details/gtntorblbz.html

[R65] 查看端口占用
来源：http://dali.cdnleiting.top/Article/details/gttbktflvp.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.meibo888.top/Article/details/gtclkemayt.html

[R66] 定时任务
来源：http://dali.jinqigufen.top/Article/details/gtvgdonrrd.html

crontab -e;  crontab -l
来源：http://dali.sysykeji.top/Article/details/gtjgstdzyf.html

[R67] 生成随机十六进制串
来源：http://dali.yanxiufei.cn/Article/details/gtygnbgdvi.html

openssl rand -hex 16
来源：http://dali.yj20258888.top/Article/details/gtqdzettkk.html

[R68] 计算文件校验值
来源：http://dali.hnqzz.top/Article/details/gtaeebkpls.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hysaishi.cn/Article/details/gtlqicqhea.html

[R69] 生成随机密码
来源：http://dali.9152youxi.cn/Article/details/gtpnfaugif.html

head -c 16 /dev/urandom | base64
来源：http://dali.guannengcc.top/Article/details/gtihhdcpla.html

[R70] 时间戳与互转
来源：http://dali.yj20258888.top/Article/details/gtfgpjubcz.html

date +%s;  date -d @1700000000
来源：http://dali.pengpengdd.cyou/Article/details/gtnguyytpj.html

[R71] 日期格式化
来源：http://dali.shanyushiyangkeji.top/Article/details/gtutlomxyb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj202588.top/Article/details/gtclngdsih.html

[R72] 等待端口就绪
来源：http://dali.shzxlz.cn/Article/details/gtnfmctwvy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinqigfzy.top/Article/details/gtqdwwabnl.html

[R73] 分割大日志
来源：http://dali.yanxiufei.cn/Article/details/gtxyvrfvuk.html

split -l 1000 big.log part_
来源：http://dali.hammf.cn/Article/details/gtqtiomhyy.html

[R74] 批量重命名
来源：http://dali.shzxlz.cn/Article/details/gtewtmneia.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.c1oappe.top/Article/details/gtyebsesqb.html

[R75] 导出环境变量
来源：http://dali.zhongyouzk.top/Article/details/gtlokqygza.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.wangdashe.top/Article/details/gtydrzwatb.html

[R76] 使用临时文件
来源：http://dali.wangdashe.top/Article/details/gtiburrlmg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.havefunace.top/Article/details/gtgggcffap.html

[R77] 读取用户输入
来源：http://dali.0kj1m.cn/Article/details/gtddvetezk.html

read -rp "请输入: " ans
来源：http://dali.feifeiyinyue.top/Article/details/gtzxtkxign.html

[R78] 交互式菜单
来源：http://dali.yonumen.top/Article/details/gtmpmuxeed.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shangyingyoupin.top/Article/details/gtypstlqrt.html

[R79] 解析命令行选项
来源：http://dali.sxryk.cn/Article/details/gtpxyzqztm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.snrcjt.cn/Article/details/gtecsjtkww.html

[R80] 查看脚本执行耗时
来源：http://dali.c1oappe.top/Article/details/gtzgtwazes.html

time ./run.sh
来源：http://dali.shanyushiyangtech.top/Article/details/gtuhxqwizj.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtxkcyqntz.html

S. C / C++ 专题
来源：http://dali.bjfxy.top/Article/details/gtgqjprxqo.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtskmimpov.html

[S01] C：Hello World
来源：http://dali.hnqzz.top/Article/details/gtcxbugviz.html

#include <stdio.h>
来源：http://dali.bjfxy.top/Article/details/gtwqgcngaw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hnxiangtu.top/Article/details/gtasmyefwv.html

[S02] C：变量与格式化输出
来源：http://dali.meibo888.top/Article/details/gtsncpxjrj.html

int a = 10; printf("%d\n", a);
来源：http://dali.ywan-chungtsiang.top/Article/details/gthxcaemww.html

[S03] C：读入整数
来源：http://dali.9152youxi.cn/Article/details/gtjuowabuq.html

int x; scanf("%d", &x);
来源：http://dali.guannengcc.top/Article/details/gtsysqzpns.html

[S04] C：字符串复制
来源：http://dali.zhiwuduotai.top/Article/details/gtrchfxsqn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shuidangran.top/Article/details/gtggggewmf.html

[S05] C：字符串长度
来源：http://dali.yanxiufei.cn/Article/details/gtlbtultmt.html

strlen(s)
来源：http://dali.jianghu66.top/Article/details/gtjnqvdaof.html

[S06] C：字符串比较
来源：http://dali.shangyingyoupin.top/Article/details/gtipxpkzds.html

strcmp(a, b) == 0
来源：http://dali.andypj.xyz/Article/details/gtbtsxkglt.html

[S07] C：数组遍历求和
来源：http://dali.pycfn.com/Article/details/gtfjteoehd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.dashuyun.cn/Article/details/gtojhtyzvq.html

[S08] C：动态内存分配与释放
来源：http://dali.ivvv.top/Article/details/gtwlcbmkfl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.tanke756.top/Article/details/gtjfrdfafb.html

[S09] C：结构体定义与初始化
来源：http://dali.feifeiyinyue.top/Article/details/gtnqjthrmr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhengqikj.top/Article/details/gtzbxkkjuz.html

[S10] C：指针与解引用
来源：http://dali.havefunace.top/Article/details/gtftkbkund.html

int *p = &a;  *p = 5;
来源：http://dali.316326.xyz/Article/details/gtwfqbyyqi.html

[S11] C：逐行读文件
来源：http://dali.fengsongda.top/Article/details/gtynkbalkj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jlsjyb.cn/Article/details/gthitxjxpa.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.daxiang520.top/Article/details/gtgfijfdne.html

fclose(f);
来源：http://dali.ppjwa.cn/Article/details/gtyninbelm.html

[S12] C：写文件
来源：http://dali.quarkkingdee.top/Article/details/gtjlobimaq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.daxiang520.top/Article/details/gtxsclynaw.html

[S13] C：宏定义
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpxonpami.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.bjfxy.top/Article/details/gthaljipgr.html

[S14] C：枚举
来源：http://dali.zhengqikj.top/Article/details/gtluijltsc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.fzhhl.top/Article/details/gtjzyjeghf.html

[S15] C：类型转换
来源：http://dali.quarkkingdee.top/Article/details/gtjtilpvjy.html

(double) a / b
来源：http://dali.kuanghao11.cn/Article/details/gtjejzigxy.html

[S16] C：位操作置位
来源：http://dali.xuetiantiany.cn/Article/details/gttddpjgcv.html

x |= (1 << 3);
来源：http://dali.ybcxt.top/Article/details/gtthjbsgqw.html

[S17] C：安全拼接字符串
来源：http://dali.chenlongwang.top/Article/details/gtqlfdyoja.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.redwolf501.top/Article/details/gtxbnyodlr.html

[S18] C：命令行参数
来源：http://dali.nanxuanxn.top/Article/details/gtzgwxlizs.html

int main(int argc, char **argv)
来源：http://dali.sysykeji.top/Article/details/gtzuqpcfjt.html

[S19] C：快速排序
来源：http://dali.9152youxi.cn/Article/details/gtkiuxzvls.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.gogol.net.cn/Article/details/gtmvsqtaps.html

[S20] C：二分查找
来源：http://dali.fengsongda.top/Article/details/gtykfqyphp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yuanzhike.top/Article/details/gtjdqwsyqi.html

[S21] C：字符类别判断
来源：http://dali.hywenlv.cn/Article/details/gtferciuxo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yvedp.cn/Article/details/gtwahblbgd.html

[S22] C：字符串转数字
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyribbskf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jiagoushi.top/Article/details/gtrgwgkkgl.html

[S23] C：随机数
来源：http://dali.c1oappe.top/Article/details/gtmrzcmcsp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shanyushiyangtech.top/Article/details/gtpslbuuzu.html

[S24] C：获取本地时间
来源：http://dali.hfpthk.cn/Article/details/gthzidcvsh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xuetiantiany.cn/Article/details/gttervmngz.html

[S25] C：内存拷贝
来源：http://dali.nwbrower.top/Article/details/gtbjqaxvxf.html

memcpy(dst, src, n);
来源：http://dali.zhoulong.xyz/Article/details/gtaqczkaqg.html

[S26] C：内存清零
来源：http://dali.bjfxy.top/Article/details/gtgbdessno.html

memset(a, 0, sizeof a);
来源：http://dali.yangfankeji.com/Article/details/gtnmddcnsh.html

[S27] C：定义常量
来源：http://dali.birdmap.top/Article/details/gtjbafjhgb.html

const double PI = 3.14159;
来源：http://dali.guowangkeji.top/Article/details/gthjxrxujh.html

[S28] C：静态变量
来源：http://dali.sufxvd.cn/Article/details/gtahkxgpcm.html

static int counter = 0;
来源：http://dali.xuetiantiany.cn/Article/details/gtdsyqaycy.html

[S29] C：变参函数
来源：http://dali.chenjidiqi.icu/Article/details/gtkdbaxbdc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jlsjyb.cn/Article/details/gtlxaoizcy.html

[S30] C：头文件保护
来源：http://dali.jinqigfzy.top/Article/details/gttqqgvkfr.html

#ifndef X_H
来源：http://dali.bjfxy.top/Article/details/gtjteewncl.html

#define X_H
来源：http://dali.gaohongyu789.top/Article/details/gtbxkwjmsm.html

#endif
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqmdxoamf.html

[S31] C++：Hello World
来源：http://dali.yueranfly.top/Article/details/gtpecggsoj.html

#include <iostream>
来源：http://dali.cqqwz.cn/Article/details/gthavmpijh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtylbzokai.html

[S32] C++：字符串
来源：http://dali.zhixingplan.top/Article/details/gtdkvonslg.html

std::string s = "hi";  s += "!";
来源：http://dali.jianghu66.top/Article/details/gtmridtzth.html

[S33] C++：vector 增删
来源：http://dali.yanxiufei.cn/Article/details/gtjplbyeko.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.nanxinkj.top/Article/details/gtxtapvcbl.html

[S34] C++：遍历 vector
来源：http://dali.shangyingyoupin.top/Article/details/gtsxvizlin.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.tian-w.cn/Article/details/gtiltsuuge.html

[S35] C++：map
来源：http://dali.jiagoushi.top/Article/details/gtzrocmoff.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hnqzz.top/Article/details/gtevkkfjsl.html

[S36] C++：unordered_map
来源：http://dali.dianchejie.cn/Article/details/gtflqmrkgx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gtvydlyumm.html

[S37] C++：set
来源：http://dali.shuidangran.top/Article/details/gtwancjmlp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinqigfzy.top/Article/details/gtpvtssrut.html

[S38] C++：排序
来源：http://dali.gotoacloud.top/Article/details/gtxylhgzvs.html

std::sort(v.begin(), v.end());
来源：http://dali.zhaomingkeji.xyz/Article/details/gthgxdarby.html

[S39] C++：自定义比较器排序
来源：http://dali.zhoulong.xyz/Article/details/gtjxupddbs.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hnxiangtu.top/Article/details/gtmqgaachq.html

[S40] C++：查找元素
来源：http://dali.jiagoushi.top/Article/details/gtzgdflezp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhengqikj.top/Article/details/gtgomgbtbg.html

[S41] C++：类与构造函数
来源：http://dali.yj20258.top/Article/details/gtadopchlg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.pengpengdd.cyou/Article/details/gtftlhyszc.html

[S42] C++：继承与虚函数
来源：http://dali.nwbrower.top/Article/details/gtjmdfobzc.html

class B : public Base { public: void f() override {} };
来源：http://dali.yanxiufei.cn/Article/details/gtsdkwrbgf.html

[S43] C++：智能指针
来源：http://dali.wangdashe.top/Article/details/gtxwxxxkqq.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdgvbilka.html

[S44] C++：引用传参
来源：http://dali.hnxiangtu.top/Article/details/gtmyknsyns.html

void inc(int &x) { ++x; }
来源：http://dali.hysaishi.cn/Article/details/gtogshmbkq.html

[S45] C++：lambda
来源：http://dali.tian-w.cn/Article/details/gtteppldat.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gogol.net.cn/Article/details/gtjwfethji.html

[S46] C++：函数模板
来源：http://dali.ywan-chungtsiang.top/Article/details/gttdgczrom.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cqqwz.cn/Article/details/gtpnndrncg.html

[S47] C++：结构化绑定遍历
来源：http://dali.jqgfzy.top/Article/details/gtfdpkngku.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ydzc1.top/Article/details/gtbopztujg.html

[S48] C++：逐行读文件
来源：http://dali.andypj.xyz/Article/details/gtbjvrqali.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yangfankeji.com/Article/details/gtnddhhxui.html

while (std::getline(in, line)) { }
来源：http://dali.guannengcc.top/Article/details/gtyidagusq.html

[S49] C++：写文件
来源：http://dali.jinqigfzy.top/Article/details/gtvyddwani.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sufxvd.cn/Article/details/gtucxdjwsx.html

[S50] C++：格式化数字
来源：http://dali.ppjwa.cn/Article/details/gtvpftabac.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.nwbrower.top/Article/details/gthcbjtcop.html

[S51] C++：显式类型转换
来源：http://dali.zhoulong.xyz/Article/details/gtesbjtkpf.html

static_cast<double>(a) / b
来源：http://dali.zhiwuduotai.top/Article/details/gtqzgbsovk.html

[S52] C++：const 与 noexcept
来源：http://dali.havefunace.top/Article/details/gttkvrmohg.html

int size() const noexcept { return n_; }
来源：http://dali.dianchejie.cn/Article/details/gtawjvpacp.html

[S53] C++：移动语义
来源：http://dali.zdqjudy.top/Article/details/gttmjddnlf.html

std::vector<int> w = std::move(v);
来源：http://dali.zdqjudy.top/Article/details/gthheytmxy.html

[S54] C++：异常处理
来源：http://dali.mhx1999.top/Article/details/gtisjsyxyc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sxryk.cn/Article/details/gtyhwymjzv.html

[S55] C++：结构化绑定
来源：http://dali.zhongyouzk.top/Article/details/gtxtxdrqaq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xziqi.cn/Article/details/gtgphfcfkd.html

[S56] C++：optional
来源：http://dali.quarkkingdee.top/Article/details/gtntteefto.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.9152youxi.cn/Article/details/gtdnkaoskd.html

[S57] C++：编译期常量
来源：http://dali.zdqjudy.top/Article/details/gtuwmgevbb.html

constexpr int N = 10;
来源：http://dali.jiagoushi.top/Article/details/gtmnzrzift.html

[S58] C++：命名空间
来源：http://dali.jiagoushi.top/Article/details/gtjrqqtvjd.html

namespace ns { int f() { return 1; } }
来源：http://dali.hnxiangtu.top/Article/details/gtdlppasgw.html

[S59] C++：静态断言
来源：http://dali.ehwqpu.com/Article/details/gtixdvjcri.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.nanxuanxn.top/Article/details/gtinswcquo.html

[S60] C++：遍历并删除元素
来源：http://dali.birdmap.top/Article/details/gtlcykrbcp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.wangshuangyany.cn/Article/details/gtcvsfibnp.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtcjywbfnx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.316326.xyz/Article/details/gtntartmqf.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtqrysvbqu.html

[T01] Kotlin：Hello World
来源：http://dali.sweek.top/Article/details/gtcyamnycj.html

println("Hello")
来源：http://dali.gogol.net.cn/Article/details/gtdaayxjbn.html

[T02] Kotlin：变量
来源：http://dali.xinyue.icu/Article/details/gtsvwhukhe.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hammf.cn/Article/details/gtqlptbgkm.html

[T03] Kotlin：字符串模板
来源：http://dali.yanxiufei.cn/Article/details/gtzftwxjpm.html

"值: $b"
来源：http://dali.zdqjudy.top/Article/details/gtyljyhiyo.html

[T04] Kotlin：空安全
来源：http://dali.shanyushiyangkeji.top/Article/details/gtngfuuqjb.html

val n: String? = null;  n?.length
来源：http://dali.yuanzhike.top/Article/details/gtnnpqugiv.html

[T05] Kotlin：when 表达式
来源：http://dali.nwbrower.top/Article/details/gteuhirlee.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xinyue.icu/Article/details/gthpqkjqup.html

[T06] Kotlin：集合映射
来源：http://dali.aizwys.cn/Article/details/gtrzczagpt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gtdvwbutsa.html

[T07] Kotlin：集合过滤
来源：http://dali.haohaochexian.top/Article/details/gtfztnyybx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yj20258888.top/Article/details/gtiyqssgrh.html

[T08] Kotlin：数据类
来源：http://dali.havefunace.top/Article/details/gtfmwzpjii.html

data class User(val name: String, val age: Int)
来源：http://dali.cdnleiting.top/Article/details/gtgawzalnw.html

[T09] Kotlin：扩展函数
来源：http://dali.zhongyouzk.top/Article/details/gtbgcgahce.html

fun String.exclaim() = this + "!"
来源：http://dali.aibaodan.cn/Article/details/gtqsthhugk.html

[T10] Kotlin：默认参数
来源：http://dali.bjfxy.top/Article/details/gtnooupqem.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jqgufenzy.top/Article/details/gthbxizkha.html

[T11] Kotlin：协程
来源：http://dali.sufxvd.cn/Article/details/gtzpuedxen.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gogol.net.cn/Article/details/gtnxpzgckq.html

[T12] Kotlin：解构声明
来源：http://dali.jqgfzy.top/Article/details/gtrpvfprmq.html

val (a, b) = Pair(1, 2)
来源：http://dali.sysykeji.top/Article/details/gtwlbmkjrl.html

[T13] Kotlin：只读 Map
来源：http://dali.shanyushiyangtech.top/Article/details/gtzygeswgd.html

val m = mapOf("a" to 1)
来源：http://dali.guannengcc.top/Article/details/gtdfcxdejx.html

[T14] Kotlin：循环
来源：http://dali.wangdashe.top/Article/details/gtaiuwhvra.html

for (i in 1..10) println(i)
来源：http://dali.zycfv.cn/Article/details/gtkhfezxxc.html

[T15] Kotlin：接口
来源：http://dali.fengsongda.top/Article/details/gthflxpmje.html

interface Shape { fun area(): Double }
来源：http://dali.wangdashe.top/Article/details/gtjpgqkvsj.html

[T16] Swift：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtpkiixijl.html

print("Hello")
来源：http://dali.redwolf501.top/Article/details/gtlertpwua.html

[T17] Swift：变量与常量
来源：http://dali.guannengcc.top/Article/details/gtgxpenycx.html

var a = 1;  let b = 2
来源：http://dali.chenjidiqi.icu/Article/details/gtzxicajwc.html

[T18] Swift：字符串插值
来源：http://dali.ehwqpu.com/Article/details/gtpbszijmr.html

"值: \(b)"
来源：http://dali.haohaochexian.top/Article/details/gtbpctalnx.html

[T19] Swift：可选绑定
来源：http://dali.fengsongda.top/Article/details/gturicmcre.html

if let n = opt { print(n) }
来源：http://dali.hywenlv.cn/Article/details/gtsokwbute.html

[T20] Swift：数组操作
来源：http://dali.hysaishi.cn/Article/details/gtqxqknnre.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yangfankeji.com/Article/details/gtdxpqpgzf.html

[T21] Swift：遍历
来源：http://dali.smart0.xyz/Article/details/gtsdvrfypd.html

for x in a { print(x) }
来源：http://dali.mhx1999.top/Article/details/gtmrimhzlf.html

[T22] Swift：字典
来源：http://dali.jqgfzy.top/Article/details/gtyewnorqc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shangyingyoupin.top/Article/details/gtwdreplfs.html

[T23] Swift：函数
来源：http://dali.tianlin.xyz/Article/details/gtcdstlgbk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.snrcjt.cn/Article/details/gtqiqgvozb.html

[T24] Swift：闭包
来源：http://dali.sweek.top/Article/details/gtpjcreuol.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.meibo888.top/Article/details/gtvbdvcrjt.html

[T25] Swift：结构体
来源：http://dali.aibaodan.cn/Article/details/gtfnxiizfm.html

struct P { var x: Int }
来源：http://dali.cdnleiting.top/Article/details/gtxosxumsb.html

[T26] Swift：类与重写
来源：http://dali.316326.xyz/Article/details/gtwivzugdd.html

class A: Base { override func f() {} }
来源：http://dali.sufxvd.cn/Article/details/gttftctclx.html

[T27] Swift：错误处理
来源：http://dali.wangdashe.top/Article/details/gttffjhxtz.html

do { try f() } catch { print(error) }
来源：http://dali.dashuyun.cn/Article/details/gtddhjgdxc.html

[T28] Swift：枚举
来源：http://dali.iojbl.cn/Article/details/gtotufrpcl.html

enum Color { case red, green }
来源：http://dali.hywenlv.cn/Article/details/gttrdsbzay.html

[T29] Swift：guard 提前返回
来源：http://dali.xuetiantiany.cn/Article/details/gtxqsotaqi.html

guard let x = opt else { return }
来源：http://dali.sufxvd.cn/Article/details/gtddiplbsg.html

[T30] Swift：协议
来源：http://dali.hongshengwenyu.top/Article/details/gtohckette.html

protocol Shape { func area() -> Double }
来源：http://dali.zycfv.cn/Article/details/gtcbeuhvsb.html

[T31] Lua：Hello World
来源：http://dali.meibo888.top/Article/details/gtrqsfwghz.html

print("Hello")
来源：http://dali.xuetiantiany.cn/Article/details/gteyoicvaf.html

[T32] Lua：局部变量
来源：http://dali.haohaochexian.top/Article/details/gtjzvzjiyu.html

local a = 1
来源：http://dali.shangyingyoupin.top/Article/details/gtrdyirfte.html

[T33] Lua：表（数组）
来源：http://dali.snrcjt.cn/Article/details/gtslznlanr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shangyingyoupin.top/Article/details/gtxgtvammh.html

[T34] Lua：遍历表
来源：http://dali.shuidangran.top/Article/details/gtiwkchqqo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.meibo888.top/Article/details/gtqgopgmgy.html

[T35] Lua：字典表
来源：http://dali.redwolf501.top/Article/details/gtekvewvlo.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cqqwz.cn/Article/details/gtzcfhblvl.html

[T36] Lua：函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttqznpavw.html

function add(a, b) return a + b end
来源：http://dali.pengpengdd.cyou/Article/details/gtjmjazrax.html

[T37] Lua：字符串拼接
来源：http://dali.zhixingplan.top/Article/details/gtvekynryd.html

"a" .. "b"
来源：http://dali.shuidangran.top/Article/details/gttebuvvjy.html

[T38] Lua：条件
来源：http://dali.yonumen.top/Article/details/gtxnxgsjjp.html

if x > 0 then print("正") end
来源：http://dali.shuidangran.top/Article/details/gthlnwiwbg.html

[T39] Lua：模式匹配
来源：http://dali.hysaishi.cn/Article/details/gtggfnqyru.html

string.find(s, "%d+")
来源：http://dali.nwbrower.top/Article/details/gtyblvqcig.html

[T40] Lua：元表
来源：http://dali.cqqwz.cn/Article/details/gtzmzgiegr.html

setmetatable({}, { __index = base })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxowxmruj.html

[T41] Perl：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtnwcqlpre.html

print "Hello\n";
来源：http://dali.mhx1999.top/Article/details/gtodcvktpr.html

[T42] Perl：变量类型
来源：http://dali.chenzaomai.com/Article/details/gtvwyviklm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.shuidangran.top/Article/details/gtmtjujefg.html

[T43] Perl：字符串插值
来源：http://dali.yuxming.cn/Article/details/gtjengeote.html

"值: $a"
来源：http://dali.cqqwz.cn/Article/details/gtvpdhhecy.html

[T44] Perl：条件
来源：http://dali.ydzc1.top/Article/details/gtdjvrglve.html

if ($a > 0) { print "正"; }
来源：http://dali.wangdashe.top/Article/details/gteglpdabm.html

[T45] Perl：数组遍历
来源：http://dali.xuetiantiany.cn/Article/details/gtvererijk.html

for my $x (@arr) { print $x; }
来源：http://dali.yvedp.cn/Article/details/gtnuxftkee.html

[T46] Perl：哈希操作
来源：http://dali.snrcjt.cn/Article/details/gtlxcmkgoy.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.aizwys.cn/Article/details/gtmojxzvvn.html

[T47] Perl：正则捕获
来源：http://dali.fengsongda.top/Article/details/gtfnupmbif.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hnxiangtu.top/Article/details/gtmvceszbk.html

[T48] Perl：正则替换
来源：http://dali.shzxlz.cn/Article/details/gtfyhepeva.html

$s =~ s/old/new/g;
来源：http://dali.xziqi.cn/Article/details/gtvdgzcmdy.html

[T49] Perl：函数
来源：http://dali.yonumen.top/Article/details/gtldnmzepi.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.sweek.top/Article/details/gtlqhltrsx.html

[T50] Perl：逐行读文件
来源：http://dali.nwbrower.top/Article/details/gtgikbdcbn.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jiagoushi.top/Article/details/gtamnhsbmv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.daria6918.cn/Article/details/gtansxqrsg.html

[T51] Scala：Hello World
来源：http://dali.guowangkeji.top/Article/details/gttkpjcxvt.html

println("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvbomqtlx.html

[T52] Scala：变量
来源：http://dali.yuanzhike.top/Article/details/gtdixeeyjm.html

val a = 1;  var b = 2
来源：http://dali.tanke756.top/Article/details/gtnjniyhop.html

[T53] Scala：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gtpfubbayr.html

s"值: $b"
来源：http://dali.nanxuanxn.top/Article/details/gttwykixcz.html

[T54] Scala：集合映射
来源：http://dali.aizwys.cn/Article/details/gtkkpwtrjw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cqqwz.cn/Article/details/gtgajazigq.html

[T55] Scala：集合过滤
来源：http://dali.zycfv.cn/Article/details/gtjlxcqsmk.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.dashuyun.cn/Article/details/gtqhrjuxwm.html

[T56] Scala：样例类
来源：http://dali.yonumen.top/Article/details/gtladhdlns.html


<!-- 参考信息 -->