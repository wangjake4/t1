代发 wailian999

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinqigfzy.top/Article/details/gteapblrtu.html

[R48] awk 取指定列
来源：http://dali.yuxming.cn/Article/details/gttrjmcvcq.html

awk '{print $1, $3}' a.txt
来源：http://dali.fzhhl.top/Article/details/gtltmouegx.html

[R49] awk 带条件
来源：http://dali.fzhhl.top/Article/details/gtsrdgojwj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinghuilouyu.cn/Article/details/gttkaoqncn.html

[R50] awk 求和
来源：http://dali.zhiwuduotai.top/Article/details/gtxulqcbva.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfzgxtjdv.html

[R51] 排序去重取前几
来源：http://dali.redwolf501.top/Article/details/gtanvjhajr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shzxlz.cn/Article/details/gtuftrdauy.html

[R52] 统计行数
来源：http://dali.yj20258.top/Article/details/gtfpbqovrx.html

wc -l a.txt
来源：http://dali.dianchejie.cn/Article/details/gtmadgdnwq.html

[R53] 查看文件头与实时尾
来源：http://dali.jianghu66.top/Article/details/gtzihydpot.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.vqdsnc.cn/Article/details/gtdilhcyaj.html

[R54] 比较两个文件
来源：http://dali.sweek.top/Article/details/gtfbxmqoag.html

diff a.txt b.txt
来源：http://dali.xinyue.icu/Article/details/gtcocdkkpj.html

[R55] 压缩与解压
来源：http://dali.zhiwuduotai.top/Article/details/gtenfgnlgi.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yuanzhike.top/Article/details/gtfjahlzmf.html

[R56] 远程拷贝
来源：http://dali.hongshengwenyu.top/Article/details/gtgtngzdww.html

scp file user@host:/path/
来源：http://dali.hongshengwenyu.top/Article/details/gttfanxuki.html

[R57] 远程执行命令
来源：http://dali.quarkkingdee.top/Article/details/gttwgzmafb.html

ssh user@host 'uptime'
来源：http://dali.ppjwa.cn/Article/details/gtdvhcscwp.html

[R58] 下载文件
来源：http://dali.sweek.top/Article/details/gtjaxkxddd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.nwbrower.top/Article/details/gtyctmgfbf.html

[R59] 发 POST JSON
来源：http://dali.shangyingyoupin.top/Article/details/gtmaeptehw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.tianlin.xyz/Article/details/gtrgdltvom.html

[R60] 只看 HTTP 状态码
来源：http://dali.hnqzz.top/Article/details/gtxdzvnygy.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gotoacloud.top/Article/details/gtzrrcghsa.html

[R61] 磁盘占用
来源：http://dali.gzhubu.top/Article/details/gttxxdwaaj.html

df -h;  du -sh *
来源：http://dali.yvedp.cn/Article/details/gtsryvagio.html

[R62] 找最占空间的文件
来源：http://dali.nwbrower.top/Article/details/gtufybbwli.html

du -ah . | sort -rh | head -10
来源：http://dali.yongpay.top/Article/details/gttkyxflwk.html

[R63] 内存与进程
来源：http://dali.yuanzhike.top/Article/details/gtfpvgrrnv.html

free -h;  ps aux | grep nginx
来源：http://dali.dianchejie.cn/Article/details/gtykjdzkge.html

[R64] 结束进程
来源：http://dali.guannengcc.top/Article/details/gtypozooee.html

kill -9 $(pgrep -f app.py)
来源：http://dali.pengpengdd.cyou/Article/details/gtmykcyxtu.html

[R65] 查看端口占用
来源：http://dali.jqgfzy.top/Article/details/gtqerrvorn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cheryme.top/Article/details/gteaceulmy.html

[R66] 定时任务
来源：http://dali.zdqjudy.top/Article/details/gtnbpiizoe.html

crontab -e;  crontab -l
来源：http://dali.pengpengdd.cyou/Article/details/gtlyrnhqmo.html

[R67] 生成随机十六进制串
来源：http://dali.gzhubu.top/Article/details/gtzhrjttez.html

openssl rand -hex 16
来源：http://dali.aizwys.cn/Article/details/gtwrspjtaq.html

[R68] 计算文件校验值
来源：http://dali.jyoumei.cn/Article/details/gtmihslxak.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cucudq.cn/Article/details/gtbhppiwip.html

[R69] 生成随机密码
来源：http://dali.chenzaomai.com/Article/details/gtrvqigxpw.html

head -c 16 /dev/urandom | base64
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpcevmjbp.html

[R70] 时间戳与互转
来源：http://dali.hnxiangtu.top/Article/details/gtqusfscyd.html

date +%s;  date -d @1700000000
来源：http://dali.nwbrower.top/Article/details/gtmhybzqlu.html

[R71] 日期格式化
来源：http://dali.ydzc1.top/Article/details/gtgzzceucl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinqigufen.top/Article/details/gtqvpipibk.html

[R72] 等待端口就绪
来源：http://dali.birdmap.top/Article/details/gtheglvxmo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.aibaodan.cn/Article/details/gtmgyhogzl.html

[R73] 分割大日志
来源：http://dali.shanyushiyangtech.top/Article/details/gtswuqiemw.html

split -l 1000 big.log part_
来源：http://dali.jyoumei.cn/Article/details/gtbasaplxn.html

[R74] 批量重命名
来源：http://dali.yuanzhike.top/Article/details/gtjdkgilur.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.daria6918.cn/Article/details/gtzmyatssf.html

[R75] 导出环境变量
来源：http://dali.xuanzx.com/Article/details/gtesvoiuou.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xuetiantiany.cn/Article/details/gtgrytkgvp.html

[R76] 使用临时文件
来源：http://dali.yonumen.top/Article/details/gtengcwfgb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yongpay.top/Article/details/gtugovvsny.html

[R77] 读取用户输入
来源：http://dali.yuxming.cn/Article/details/gtnemgqwms.html

read -rp "请输入: " ans
来源：http://dali.chenjidiqi.icu/Article/details/gtidjjeagy.html

[R78] 交互式菜单
来源：http://dali.guannengcc.top/Article/details/gtnjopdxbb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sysykeji.top/Article/details/gtjwbpzaxn.html

[R79] 解析命令行选项
来源：http://dali.tian-w.cn/Article/details/gtqauvrsvi.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yonumen.top/Article/details/gtfijlhzzg.html

[R80] 查看脚本执行耗时
来源：http://dali.zhiwuduotai.top/Article/details/gtvynpdsxr.html

time ./run.sh
来源：http://dali.xuanzx.com/Article/details/gtncxsthlp.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gttghljdxl.html

S. C / C++ 专题
来源：http://dali.guowangkeji.top/Article/details/gtukymbwlh.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gteuydizyu.html

[S01] C：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtxbpuhygh.html

#include <stdio.h>
来源：http://dali.dashuyun.cn/Article/details/gtexewpoec.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sysykeji.top/Article/details/gtidtmonzp.html

[S02] C：变量与格式化输出
来源：http://dali.yueranfly.top/Article/details/gttvkqdils.html

int a = 10; printf("%d\n", a);
来源：http://dali.nanxuanxn.top/Article/details/gtiysrnoyl.html

[S03] C：读入整数
来源：http://dali.iojbl.cn/Article/details/gtmxijipgk.html

int x; scanf("%d", &x);
来源：http://dali.havefunace.top/Article/details/gtstaqdgyu.html

[S04] C：字符串复制
来源：http://dali.smart0.xyz/Article/details/gttkjdgkde.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ivvv.top/Article/details/gteizhzuee.html

[S05] C：字符串长度
来源：http://dali.pengpengdd.cyou/Article/details/gtkqosruev.html

strlen(s)
来源：http://dali.jianghu66.top/Article/details/gtwjjejevk.html

[S06] C：字符串比较
来源：http://dali.zycfv.cn/Article/details/gtoohpwoan.html

strcmp(a, b) == 0
来源：http://dali.xuanzx.com/Article/details/gtwjsltzqo.html

[S07] C：数组遍历求和
来源：http://dali.feifeiyinyue.top/Article/details/gtclljmdra.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinghuilouyu.cn/Article/details/gtihzmalmc.html

[S08] C：动态内存分配与释放
来源：http://dali.ppjwa.cn/Article/details/gthbnijnoq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cucudq.cn/Article/details/gtwznhgxay.html

[S09] C：结构体定义与初始化
来源：http://dali.daria6918.cn/Article/details/gtopcnwvlm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ybcxt.top/Article/details/gthvulorxs.html

[S10] C：指针与解引用
来源：http://dali.mhx1999.top/Article/details/gtpszdgahv.html

int *p = &a;  *p = 5;
来源：http://dali.chenjidiqi.icu/Article/details/gtpgrpxdiu.html

[S11] C：逐行读文件
来源：http://dali.daxiang520.top/Article/details/gtuzdpqhfk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xuanzx.com/Article/details/gtxyanlrtt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xuetiantiany.cn/Article/details/gtlfbvsmny.html

fclose(f);
来源：http://dali.hywenlv.cn/Article/details/gtevgjvdya.html

[S12] C：写文件
来源：http://dali.yongpay.top/Article/details/gtxafdwnhk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hammf.cn/Article/details/gtdmprxtht.html

[S13] C：宏定义
来源：http://dali.shanyushiyangtech.top/Article/details/gtbypslqdk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.birdmap.top/Article/details/gtlfdshhqh.html

[S14] C：枚举
来源：http://dali.gzhubu.top/Article/details/gtyynvotaq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yj20258888.top/Article/details/gtbgodkhrj.html

[S15] C：类型转换
来源：http://dali.daxiang520.top/Article/details/gtlvndugyx.html

(double) a / b
来源：http://dali.tian-w.cn/Article/details/gtzmntxxzu.html

[S16] C：位操作置位
来源：http://dali.iojbl.cn/Article/details/gtlpqxbngs.html

x |= (1 << 3);
来源：http://dali.fzhhl.top/Article/details/gtuiualbze.html

[S17] C：安全拼接字符串
来源：http://dali.sxryk.cn/Article/details/gtihyansox.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.tanke756.top/Article/details/gthqfpegju.html

[S18] C：命令行参数
来源：http://dali.fengsongda.top/Article/details/gtolfpbrid.html

int main(int argc, char **argv)
来源：http://dali.ivvv.top/Article/details/gtqjntdewe.html

[S19] C：快速排序
来源：http://dali.wangdashe.top/Article/details/gtxtrepqnh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xylfe.cn/Article/details/gtrznvvlsq.html

[S20] C：二分查找
来源：http://dali.zhoulong.xyz/Article/details/gtqhytjcxl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hnxiangtu.top/Article/details/gtywgdiims.html

[S21] C：字符类别判断
来源：http://dali.nwbrower.top/Article/details/gtcccgmumg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yj20258888.top/Article/details/gtsvcxnmjy.html

[S22] C：字符串转数字
来源：http://dali.sxryk.cn/Article/details/gttxoltefb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cucudq.cn/Article/details/gtflhahvja.html

[S23] C：随机数
来源：http://dali.gotoacloud.top/Article/details/gtwqwxkogh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.9152youxi.cn/Article/details/gtoggkywfi.html

[S24] C：获取本地时间
来源：http://dali.shanyushiyangtech.top/Article/details/gtecatapnb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinqigfzy.top/Article/details/gtxzhpiotk.html

[S25] C：内存拷贝
来源：http://dali.zdqjudy.top/Article/details/gtgtrilejy.html

memcpy(dst, src, n);
来源：http://dali.chenzaomai.com/Article/details/gtakfwizkr.html

[S26] C：内存清零
来源：http://dali.cucudq.cn/Article/details/gtnsswdxit.html

memset(a, 0, sizeof a);
来源：http://dali.tian-w.cn/Article/details/gtqforxjvq.html

[S27] C：定义常量
来源：http://dali.snrcjt.cn/Article/details/gtiaswjexa.html

const double PI = 3.14159;
来源：http://dali.zhengqikj.top/Article/details/gtnkafqvjv.html

[S28] C：静态变量
来源：http://dali.mhx1999.top/Article/details/gtlemogphk.html

static int counter = 0;
来源：http://dali.tanke756.top/Article/details/gtecoefgwz.html

[S29] C：变参函数
来源：http://dali.iojbl.cn/Article/details/gtzascumpi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shzxlz.cn/Article/details/gtjktmbeeu.html

[S30] C：头文件保护
来源：http://dali.redwolf501.top/Article/details/gtyrvwjgzn.html

#ifndef X_H
来源：http://dali.xuetiantiany.cn/Article/details/gtkqvqrgmb.html

#define X_H
来源：http://dali.jianghu66.top/Article/details/gtqcncxavy.html

#endif
来源：http://dali.cheryme.top/Article/details/gtxkrlkrhn.html

[S31] C++：Hello World
来源：http://dali.cucudq.cn/Article/details/gtmifmagvr.html

#include <iostream>
来源：http://dali.jqgufenzy.top/Article/details/gtzuoynlqy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.nwbrower.top/Article/details/gtneiyrahj.html

[S32] C++：字符串
来源：http://dali.yongpay.top/Article/details/gtlrciooux.html

std::string s = "hi";  s += "!";
来源：http://dali.xziqi.cn/Article/details/gtncvfavul.html

[S33] C++：vector 增删
来源：http://dali.hammf.cn/Article/details/gtcjzzwdaz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.bjfxy.top/Article/details/gtpzfxmiwn.html

[S34] C++：遍历 vector
来源：http://dali.shangyingyoupin.top/Article/details/gthguahcmr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ydzc1.top/Article/details/gtndfsedky.html

[S35] C++：map
来源：http://dali.hongshengwenyu.top/Article/details/gtevckyzgi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pycfn.com/Article/details/gtdlcmufxc.html

[S36] C++：unordered_map
来源：http://dali.tian-w.cn/Article/details/gtqrnkxwpi.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pycfn.com/Article/details/gtyktclxyp.html

[S37] C++：set
来源：http://dali.jqgfzy.top/Article/details/gtdtodmarx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.bjfxy.top/Article/details/gtzpithtob.html

[S38] C++：排序
来源：http://dali.zycfv.cn/Article/details/gtuktnoexk.html

std::sort(v.begin(), v.end());
来源：http://dali.wangshuangyany.cn/Article/details/gtqhajlopa.html

[S39] C++：自定义比较器排序
来源：http://dali.yonumen.top/Article/details/gtajexuodi.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsojjuqpo.html

[S40] C++：查找元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtotfoypkq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nanxinkj.top/Article/details/gtxontamra.html

[S41] C++：类与构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gtwduhuawp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.vqdsnc.cn/Article/details/gtmgohhuym.html

[S42] C++：继承与虚函数
来源：http://dali.guowangkeji.top/Article/details/gtyyyltyqx.html

class B : public Base { public: void f() override {} };
来源：http://dali.jqgfzy.top/Article/details/gttlgayxjs.html

[S43] C++：智能指针
来源：http://dali.cucudq.cn/Article/details/gtsklqhimy.html

auto p = std::make_unique<int>(5);
来源：http://dali.hfpthk.cn/Article/details/gtijoxbtaw.html

[S44] C++：引用传参
来源：http://dali.jinqigufen.top/Article/details/gtkijtaiat.html

void inc(int &x) { ++x; }
来源：http://dali.birdmap.top/Article/details/gtlnngzxmq.html

[S45] C++：lambda
来源：http://dali.gogol.net.cn/Article/details/gtgqzfsvuf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hywenlv.cn/Article/details/gthijxkdak.html

[S46] C++：函数模板
来源：http://dali.zhongyouzk.top/Article/details/gtcwmdwgpu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hammf.cn/Article/details/gtoqzxokpq.html

[S47] C++：结构化绑定遍历
来源：http://dali.ehwqpu.com/Article/details/gtccjddsay.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.bjfxy.top/Article/details/gtszpbbxvs.html

[S48] C++：逐行读文件
来源：http://dali.jiagoushi.top/Article/details/gtfhzrrgnm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.nanxuanxn.top/Article/details/gtyucgtzcb.html

while (std::getline(in, line)) { }
来源：http://dali.iojbl.cn/Article/details/gtembrjufw.html

[S49] C++：写文件
来源：http://dali.fzhhl.top/Article/details/gthprifvlh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.daria6918.cn/Article/details/gtcajmazdm.html

[S50] C++：格式化数字
来源：http://dali.sufxvd.cn/Article/details/gtkrnnhfeq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gtiylerdmy.html

[S51] C++：显式类型转换
来源：http://dali.aizwys.cn/Article/details/gtkbqypdxe.html

static_cast<double>(a) / b
来源：http://dali.sweek.top/Article/details/gtjkvqphih.html

[S52] C++：const 与 noexcept
来源：http://dali.havefunace.top/Article/details/gtsdunusqo.html

int size() const noexcept { return n_; }
来源：http://dali.ppjwa.cn/Article/details/gtydddadsm.html

[S53] C++：移动语义
来源：http://dali.shuidangran.top/Article/details/gtduaydxcd.html

std::vector<int> w = std::move(v);
来源：http://dali.redwolf501.top/Article/details/gtfilxwklq.html

[S54] C++：异常处理
来源：http://dali.iojbl.cn/Article/details/gtbcmawqmv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqkjbgzsw.html

[S55] C++：结构化绑定
来源：http://dali.jiagoushi.top/Article/details/gtuyrulyjm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.birdmap.top/Article/details/gtdvalzyfs.html

[S56] C++：optional
来源：http://dali.andypj.xyz/Article/details/gtsljmnzof.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gotoacloud.top/Article/details/gtmxzwphbq.html

[S57] C++：编译期常量
来源：http://dali.zhongyouzk.top/Article/details/gtmnntyzkn.html

constexpr int N = 10;
来源：http://dali.zhengqikj.top/Article/details/gthjdospza.html

[S58] C++：命名空间
来源：http://dali.tian-w.cn/Article/details/gtskbjvjtr.html

namespace ns { int f() { return 1; } }
来源：http://dali.nanxinkj.top/Article/details/gtkgfyyxar.html

[S59] C++：静态断言
来源：http://dali.hnxiangtu.top/Article/details/gtbhygasgr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hysaishi.cn/Article/details/gtmccfxzpm.html

[S60] C++：遍历并删除元素
来源：http://dali.ehwqpu.com/Article/details/gtwzkuyesa.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.dianchejie.cn/Article/details/gthcnojzgg.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtlqwpbmey.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.snrcjt.cn/Article/details/gtkbbbkyih.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtaegvqzit.html

[T01] Kotlin：Hello World
来源：http://dali.0kj1m.cn/Article/details/gtvsogfxyu.html

println("Hello")
来源：http://dali.cqqwz.cn/Article/details/gtkrzqbiym.html

[T02] Kotlin：变量
来源：http://dali.svipenyu.cn/Article/details/gtywfoghub.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gtflzxguzc.html

[T03] Kotlin：字符串模板
来源：http://dali.0kj1m.cn/Article/details/gtkakyjsjl.html

"值: $b"
来源：http://dali.nanxinkj.top/Article/details/gtuieqsyzt.html

[T04] Kotlin：空安全
来源：http://dali.pengpengdd.cyou/Article/details/gttlrqxurm.html

val n: String? = null;  n?.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpipkkfbm.html

[T05] Kotlin：when 表达式
来源：http://dali.gzhubu.top/Article/details/gtpoyedume.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.fzhhl.top/Article/details/gtyrxijinv.html

[T06] Kotlin：集合映射
来源：http://dali.svipenyu.cn/Article/details/gtmjlcjszl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.pycfn.com/Article/details/gtauaogtte.html

[T07] Kotlin：集合过滤
来源：http://dali.jqgufenzy.top/Article/details/gtzuxnouou.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yj20258888.top/Article/details/gtcvpfdyho.html

[T08] Kotlin：数据类
来源：http://dali.mhx1999.top/Article/details/gtgkmwuzpe.html

data class User(val name: String, val age: Int)
来源：http://dali.hnxiangtu.top/Article/details/gtpheepxhb.html

[T09] Kotlin：扩展函数
来源：http://dali.ydzc1.top/Article/details/gtoqicllro.html

fun String.exclaim() = this + "!"
来源：http://dali.meibo888.top/Article/details/gtbhokeiun.html

[T10] Kotlin：默认参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdqsgidcd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhixingplan.top/Article/details/gtoecphhyu.html

[T11] Kotlin：协程
来源：http://dali.dashuyun.cn/Article/details/gttvywgifj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.meibo888.top/Article/details/gtjophyapl.html

[T12] Kotlin：解构声明
来源：http://dali.jiagoushi.top/Article/details/gtruqqbixt.html

val (a, b) = Pair(1, 2)
来源：http://dali.ivvv.top/Article/details/gtxfizueel.html

[T13] Kotlin：只读 Map
来源：http://dali.dianchejie.cn/Article/details/gtypljxhtt.html

val m = mapOf("a" to 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gttpwtarvz.html

[T14] Kotlin：循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtlaolvdbe.html

for (i in 1..10) println(i)
来源：http://dali.gotoacloud.top/Article/details/gthtdvadvt.html

[T15] Kotlin：接口
来源：http://dali.fengsongda.top/Article/details/gtwrglwswt.html

interface Shape { fun area(): Double }
来源：http://dali.gogol.net.cn/Article/details/gtumbfuuok.html

[T16] Swift：Hello World
来源：http://dali.pycfn.com/Article/details/gthotfnzgz.html

print("Hello")
来源：http://dali.xylfe.cn/Article/details/gtorxeaank.html

[T17] Swift：变量与常量
来源：http://dali.yj202588.top/Article/details/gtwhqxtvco.html

var a = 1;  let b = 2
来源：http://dali.hysaishi.cn/Article/details/gtxyqausqq.html

[T18] Swift：字符串插值
来源：http://dali.gzhubu.top/Article/details/gtgaciuocp.html

"值: \(b)"
来源：http://dali.gogol.net.cn/Article/details/gtukclnbpe.html

[T19] Swift：可选绑定
来源：http://dali.9152youxi.cn/Article/details/gtqihxbnrw.html

if let n = opt { print(n) }
来源：http://dali.xylfe.cn/Article/details/gtatumywku.html

[T20] Swift：数组操作
来源：http://dali.xuetiantiany.cn/Article/details/gtqkegmvre.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.dianchejie.cn/Article/details/gtucxfoddx.html

[T21] Swift：遍历
来源：http://dali.jyoumei.cn/Article/details/gtwbhczaav.html

for x in a { print(x) }
来源：http://dali.zdqjudy.top/Article/details/gtnqegwqmb.html

[T22] Swift：字典
来源：http://dali.yongpay.top/Article/details/gtepdguoui.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.havefunace.top/Article/details/gtmzlrwbtm.html

[T23] Swift：函数
来源：http://dali.yuxming.cn/Article/details/gtwlzsbeun.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtucqqjjzn.html

[T24] Swift：闭包
来源：http://dali.cdnleiting.top/Article/details/gthfkkbrgw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gtgohlrlhl.html

[T25] Swift：结构体
来源：http://dali.aibaodan.cn/Article/details/gtqjhcqkxb.html

struct P { var x: Int }
来源：http://dali.redwolf501.top/Article/details/gtdctbgery.html

[T26] Swift：类与重写
来源：http://dali.sysykeji.top/Article/details/gtxhftezmz.html

class A: Base { override func f() {} }
来源：http://dali.zycfv.cn/Article/details/gtgfnsxuav.html

[T27] Swift：错误处理
来源：http://dali.zhongyouzk.top/Article/details/gtahgnrcbm.html

do { try f() } catch { print(error) }
来源：http://dali.nanxinkj.top/Article/details/gtfvrggeaa.html

[T28] Swift：枚举
来源：http://dali.jlsjyb.cn/Article/details/gthxtnuqjb.html

enum Color { case red, green }
来源：http://dali.nwbrower.top/Article/details/gtqhqnabsr.html

[T29] Swift：guard 提前返回
来源：http://dali.yangfankeji.com/Article/details/gtrphcrprm.html

guard let x = opt else { return }
来源：http://dali.yuanzhike.top/Article/details/gtzfzouhlw.html

[T30] Swift：协议
来源：http://dali.hfpthk.cn/Article/details/gtdujrjtne.html

protocol Shape { func area() -> Double }
来源：http://dali.zhengqikj.top/Article/details/gtaiybnirs.html

[T31] Lua：Hello World
来源：http://dali.yj20258888.top/Article/details/gtisphxnze.html

print("Hello")
来源：http://dali.guowangkeji.top/Article/details/gtnncoywzp.html

[T32] Lua：局部变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaacawdbz.html

local a = 1
来源：http://dali.snrcjt.cn/Article/details/gtougqzxcw.html

[T33] Lua：表（数组）
来源：http://dali.jlsjyb.cn/Article/details/gtzqjcbugb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.daria6918.cn/Article/details/gtuvbvcitf.html

[T34] Lua：遍历表
来源：http://dali.tian-w.cn/Article/details/gtdrbawjiu.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jinghuilouyu.cn/Article/details/gtibnjagiw.html

[T35] Lua：字典表
来源：http://dali.gotoacloud.top/Article/details/gthnvxgaqg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ehwqpu.com/Article/details/gtzosrowyk.html

[T36] Lua：函数
来源：http://dali.hammf.cn/Article/details/gtrlhkeazb.html

function add(a, b) return a + b end
来源：http://dali.nanxinkj.top/Article/details/gtygjitmpq.html

[T37] Lua：字符串拼接
来源：http://dali.9152youxi.cn/Article/details/gtqvfftmqw.html

"a" .. "b"
来源：http://dali.dianchejie.cn/Article/details/gtffexktkh.html

[T38] Lua：条件
来源：http://dali.hongshengwenyu.top/Article/details/gtepztohwt.html

if x > 0 then print("正") end
来源：http://dali.xuanzx.com/Article/details/gtgftmtlrv.html

[T39] Lua：模式匹配
来源：http://dali.zdqjudy.top/Article/details/gtzmbrqnjy.html

string.find(s, "%d+")
来源：http://dali.yanxiufei.cn/Article/details/gtexpvtfxv.html

[T40] Lua：元表
来源：http://dali.hnxiangtu.top/Article/details/gtnhubfwsm.html

setmetatable({}, { __index = base })
来源：http://dali.pengpengdd.cyou/Article/details/gtjnqyvqko.html

[T41] Perl：Hello World
来源：http://dali.pycfn.com/Article/details/gthycimcha.html

print "Hello\n";
来源：http://dali.sweek.top/Article/details/gtalacmavr.html

[T42] Perl：变量类型
来源：http://dali.jinqigufen.top/Article/details/gtcdxptjer.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.haohaochexian.top/Article/details/gtuoqriziu.html

[T43] Perl：字符串插值
来源：http://dali.shangyingyoupin.top/Article/details/gtymcdgztx.html

"值: $a"
来源：http://dali.guowangkeji.top/Article/details/gtzndecqmc.html

[T44] Perl：条件
来源：http://dali.zhixingplan.top/Article/details/gtoyetihdq.html

if ($a > 0) { print "正"; }
来源：http://dali.jinqigufen.top/Article/details/gtsloxyqfv.html

[T45] Perl：数组遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtteycqboi.html

for my $x (@arr) { print $x; }
来源：http://dali.yvedp.cn/Article/details/gtjmrchvqy.html

[T46] Perl：哈希操作
来源：http://dali.nwbrower.top/Article/details/gtvvqfbrev.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.nwbrower.top/Article/details/gtrkdjeykf.html

[T47] Perl：正则捕获
来源：http://dali.ywan-chungtsiang.top/Article/details/gtydyaawja.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.fengsongda.top/Article/details/gtwudgyplv.html

[T48] Perl：正则替换
来源：http://dali.fzhhl.top/Article/details/gtipdxwhrk.html

$s =~ s/old/new/g;
来源：http://dali.zhoulong.xyz/Article/details/gtgubqgwmi.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gtzmaydpty.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gtrxjexmvl.html

[T50] Perl：逐行读文件
来源：http://dali.yj20258.top/Article/details/gtfybuykdd.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.svipenyu.cn/Article/details/gtokqwczdb.html


<!-- 参考信息 -->