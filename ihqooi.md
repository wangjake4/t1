代发 wailian999

sed -i 's/foo/bar/g' a.txt
来源：http://dali.pycfn.com/Article/details/gtumplcxax.html

[R48] awk 取指定列
来源：http://dali.birdmap.top/Article/details/gtisvrwtqj.html

awk '{print $1, $3}' a.txt
来源：http://dali.sysykeji.top/Article/details/gtmcljudlm.html

[R49] awk 带条件
来源：http://dali.nwbrower.top/Article/details/gttahlvgmh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.fengsongda.top/Article/details/gtueiqlrbe.html

[R50] awk 求和
来源：http://dali.gaohongyu789.top/Article/details/gtxusaxsxj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.svipenyu.cn/Article/details/gtqcgclxom.html

[R51] 排序去重取前几
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrzzimgla.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.quarkkingdee.top/Article/details/gtxhooyhlz.html

[R52] 统计行数
来源：http://dali.hysaishi.cn/Article/details/gtlpacjbif.html

wc -l a.txt
来源：http://dali.haohaochexian.top/Article/details/gtbgtwvktq.html

[R53] 查看文件头与实时尾
来源：http://dali.birdmap.top/Article/details/gtkqlmuewf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.wangdashe.top/Article/details/gtankhrvfk.html

[R54] 比较两个文件
来源：http://dali.xziqi.cn/Article/details/gthousblxk.html

diff a.txt b.txt
来源：http://dali.0kj1m.cn/Article/details/gtbqhthfzz.html

[R55] 压缩与解压
来源：http://dali.xylfe.cn/Article/details/gtfqqnrvmg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhixingplan.top/Article/details/gthrwurqag.html

[R56] 远程拷贝
来源：http://dali.shangyingyoupin.top/Article/details/gtlzikvtkb.html

scp file user@host:/path/
来源：http://dali.nwbrower.top/Article/details/gtlmivdovo.html

[R57] 远程执行命令
来源：http://dali.smart0.xyz/Article/details/gtqeyakazr.html

ssh user@host 'uptime'
来源：http://dali.sysykeji.top/Article/details/gtmhvveqxq.html

[R58] 下载文件
来源：http://dali.cqqwz.cn/Article/details/gtacdrthnw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.bjfxy.top/Article/details/gtolrnflfc.html

[R59] 发 POST JSON
来源：http://dali.yongpay.top/Article/details/gtjjixzoav.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.tanke756.top/Article/details/gtqabuipxi.html

[R60] 只看 HTTP 状态码
来源：http://dali.sxryk.cn/Article/details/gtkdabfozo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.tian-w.cn/Article/details/gtkdeaplip.html

[R61] 磁盘占用
来源：http://dali.yonumen.top/Article/details/gtblaltzdd.html

df -h;  du -sh *
来源：http://dali.nanxinkj.top/Article/details/gtyywobabz.html

[R62] 找最占空间的文件
来源：http://dali.zhoulong.xyz/Article/details/gtrszgpqnw.html

du -ah . | sort -rh | head -10
来源：http://dali.cqqwz.cn/Article/details/gthcdvevxb.html

[R63] 内存与进程
来源：http://dali.jiagoushi.top/Article/details/gtjgwycgpa.html

free -h;  ps aux | grep nginx
来源：http://dali.haohaochexian.top/Article/details/gtofbehszv.html

[R64] 结束进程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbpryguon.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hnqzz.top/Article/details/gtpxassnmf.html

[R65] 查看端口占用
来源：http://dali.pengpengdd.cyou/Article/details/gtcjlwllmf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ybcxt.top/Article/details/gtooawfoks.html

[R66] 定时任务
来源：http://dali.cqqwz.cn/Article/details/gtccmuabzz.html

crontab -e;  crontab -l
来源：http://dali.yongpay.top/Article/details/gtwhmzaewo.html

[R67] 生成随机十六进制串
来源：http://dali.guowangkeji.top/Article/details/gtieaqnzsb.html

openssl rand -hex 16
来源：http://dali.shzxlz.cn/Article/details/gttqejubrs.html

[R68] 计算文件校验值
来源：http://dali.yueranfly.top/Article/details/gtgvltprpq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtyexwrufw.html

[R69] 生成随机密码
来源：http://dali.0kj1m.cn/Article/details/gtlnteswxf.html

head -c 16 /dev/urandom | base64
来源：http://dali.mhx1999.top/Article/details/gtvrkqbbmy.html

[R70] 时间戳与互转
来源：http://dali.zhixingplan.top/Article/details/gtfvodzmtv.html

date +%s;  date -d @1700000000
来源：http://dali.hysaishi.cn/Article/details/gttiwaxvvy.html

[R71] 日期格式化
来源：http://dali.xuanzx.com/Article/details/gtmdyyxtbq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xziqi.cn/Article/details/gtttoqoxjx.html

[R72] 等待端口就绪
来源：http://dali.zdqjudy.top/Article/details/gtqiudecmx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.c1oappe.top/Article/details/gtngtuahvq.html

[R73] 分割大日志
来源：http://dali.daxiang520.top/Article/details/gttnlfvfjj.html

split -l 1000 big.log part_
来源：http://dali.dashuyun.cn/Article/details/gtvdzwjxff.html

[R74] 批量重命名
来源：http://dali.yj20258888.top/Article/details/gtgizrohvh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuycjxeqv.html

[R75] 导出环境变量
来源：http://dali.yonumen.top/Article/details/gtnkmlaqke.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jqgufenzy.top/Article/details/gtuhvkmnav.html

[R76] 使用临时文件
来源：http://dali.jianghu66.top/Article/details/gtjokalzaf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xylfe.cn/Article/details/gtlmxmwqtw.html

[R77] 读取用户输入
来源：http://dali.fengsongda.top/Article/details/gtlhmjxcpu.html

read -rp "请输入: " ans
来源：http://dali.wangshuangyany.cn/Article/details/gtgrchadzf.html

[R78] 交互式菜单
来源：http://dali.cdnleiting.top/Article/details/gtrwkthksi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinqigfzy.top/Article/details/gtpfwjoclh.html

[R79] 解析命令行选项
来源：http://dali.zycfv.cn/Article/details/gtmaykkbio.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hammf.cn/Article/details/gtophuduun.html

[R80] 查看脚本执行耗时
来源：http://dali.sufxvd.cn/Article/details/gtmdkiisyq.html

time ./run.sh
来源：http://dali.nanxinkj.top/Article/details/gtxstqhebo.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtfnovxhwh.html

S. C / C++ 专题
来源：http://dali.yj20258888.top/Article/details/gtvxzwaesz.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtalwahntn.html

[S01] C：Hello World
来源：http://dali.xziqi.cn/Article/details/gtetwwfkvt.html

#include <stdio.h>
来源：http://dali.snrcjt.cn/Article/details/gthkzcjuln.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.tianlin.xyz/Article/details/gtzebyjhyq.html

[S02] C：变量与格式化输出
来源：http://dali.hfpthk.cn/Article/details/gtpthabkui.html

int a = 10; printf("%d\n", a);
来源：http://dali.gotoacloud.top/Article/details/gtnjdppxgw.html

[S03] C：读入整数
来源：http://dali.nwbrower.top/Article/details/gtcgvpcply.html

int x; scanf("%d", &x);
来源：http://dali.316326.xyz/Article/details/gtdsbmbmin.html

[S04] C：字符串复制
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwfpuxsny.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gotoacloud.top/Article/details/gtzgmupplk.html

[S05] C：字符串长度
来源：http://dali.jqgufenzy.top/Article/details/gtsluwxprm.html

strlen(s)
来源：http://dali.zhixingplan.top/Article/details/gtkluviezc.html

[S06] C：字符串比较
来源：http://dali.nanxuanxn.top/Article/details/gtvejdahbo.html

strcmp(a, b) == 0
来源：http://dali.yj202588.top/Article/details/gtzbtqmwdu.html

[S07] C：数组遍历求和
来源：http://dali.ybcxt.top/Article/details/gtgxmlfrrf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gzhubu.top/Article/details/gtbxlpqkhr.html

[S08] C：动态内存分配与释放
来源：http://dali.hfpthk.cn/Article/details/gtneybrksk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jyoumei.cn/Article/details/gtbhmillqy.html

[S09] C：结构体定义与初始化
来源：http://dali.sufxvd.cn/Article/details/gtfvebfazq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jqgfzy.top/Article/details/gtzxjtiyzq.html

[S10] C：指针与解引用
来源：http://dali.vqdsnc.cn/Article/details/gtijsyjixp.html

int *p = &a;  *p = 5;
来源：http://dali.vqdsnc.cn/Article/details/gtcjjyzwyk.html

[S11] C：逐行读文件
来源：http://dali.yj20258888.top/Article/details/gttzezteqc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhixingplan.top/Article/details/gtbzhgojde.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xuanzx.com/Article/details/gtamyjnpgt.html

fclose(f);
来源：http://dali.nwbrower.top/Article/details/gtwhoxznlp.html

[S12] C：写文件
来源：http://dali.jinqigufen.top/Article/details/gtkzblklma.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.guannengcc.top/Article/details/gthjgbbrib.html

[S13] C：宏定义
来源：http://dali.zhengqikj.top/Article/details/gtvnvvpezn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.316326.xyz/Article/details/gtvrqqlqhi.html

[S14] C：枚举
来源：http://dali.haohaochexian.top/Article/details/gtdyggdgne.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.dianchejie.cn/Article/details/gturlwtpzx.html

[S15] C：类型转换
来源：http://dali.tianlin.xyz/Article/details/gtqhhuxydm.html

(double) a / b
来源：http://dali.xinyue.icu/Article/details/gtbxliztwe.html

[S16] C：位操作置位
来源：http://dali.xuetiantiany.cn/Article/details/gtjbnctldt.html

x |= (1 << 3);
来源：http://dali.quarkkingdee.top/Article/details/gtezlsvdki.html

[S17] C：安全拼接字符串
来源：http://dali.tianlin.xyz/Article/details/gtmaprwisa.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.dianchejie.cn/Article/details/gtjusumnrq.html

[S18] C：命令行参数
来源：http://dali.jyoumei.cn/Article/details/gtvmeqzuzy.html

int main(int argc, char **argv)
来源：http://dali.hnxiangtu.top/Article/details/gtxavlhoqc.html

[S19] C：快速排序
来源：http://dali.cqqwz.cn/Article/details/gtqmclxzom.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.snrcjt.cn/Article/details/gtpmxhjgdi.html

[S20] C：二分查找
来源：http://dali.nanxuanxn.top/Article/details/gtaznbmyjp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yuanzhike.top/Article/details/gtxgbnqdjk.html

[S21] C：字符类别判断
来源：http://dali.hnqzz.top/Article/details/gtdpgcacyi.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jianghu66.top/Article/details/gthyjsqpmd.html

[S22] C：字符串转数字
来源：http://dali.yongpay.top/Article/details/gtqqoyyelu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.snrcjt.cn/Article/details/gtyinfuysu.html

[S23] C：随机数
来源：http://dali.yj20258.top/Article/details/gttuyjerlo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.tianlin.xyz/Article/details/gtugtrvpek.html

[S24] C：获取本地时间
来源：http://dali.nanxinkj.top/Article/details/gtzitcfxsf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hnqzz.top/Article/details/gtodvpfzbg.html

[S25] C：内存拷贝
来源：http://dali.zhoulong.xyz/Article/details/gtmerjbohr.html

memcpy(dst, src, n);
来源：http://dali.aizwys.cn/Article/details/gtnndmtmpe.html

[S26] C：内存清零
来源：http://dali.xziqi.cn/Article/details/gtwgreuyia.html

memset(a, 0, sizeof a);
来源：http://dali.jiagoushi.top/Article/details/gtkjnssajd.html

[S27] C：定义常量
来源：http://dali.xylfe.cn/Article/details/gtbvgjixcl.html

const double PI = 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gtsjlryaog.html

[S28] C：静态变量
来源：http://dali.kuanghao11.cn/Article/details/gtqabgbuss.html

static int counter = 0;
来源：http://dali.zhaomingkeji.xyz/Article/details/gteyixyekc.html

[S29] C：变参函数
来源：http://dali.jianghu66.top/Article/details/gtwoqmvnpk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cqqwz.cn/Article/details/gtkscnwoya.html

[S30] C：头文件保护
来源：http://dali.cucudq.cn/Article/details/gtgsuxupaz.html

#ifndef X_H
来源：http://dali.dianchejie.cn/Article/details/gtvndlsmay.html

#define X_H
来源：http://dali.bjfxy.top/Article/details/gtfcbfcaeq.html

#endif
来源：http://dali.cdnleiting.top/Article/details/gtavnqdhcf.html

[S31] C++：Hello World
来源：http://dali.ydzc1.top/Article/details/gtknwbjrds.html

#include <iostream>
来源：http://dali.wangdashe.top/Article/details/gtiwyhvzlo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.aizwys.cn/Article/details/gtvcwywsid.html

[S32] C++：字符串
来源：http://dali.sufxvd.cn/Article/details/gtkzbxlmdt.html

std::string s = "hi";  s += "!";
来源：http://dali.shanyushiyangtech.top/Article/details/gtrurxodyy.html

[S33] C++：vector 增删
来源：http://dali.shzxlz.cn/Article/details/gtvrjrxftp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.vqdsnc.cn/Article/details/gtvgodlgbb.html

[S34] C++：遍历 vector
来源：http://dali.ivvv.top/Article/details/gthfohwovg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jianghu66.top/Article/details/gtuvtomrxp.html

[S35] C++：map
来源：http://dali.shanyushiyangtech.top/Article/details/gtqjlpxmlc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jiagoushi.top/Article/details/gtlgiezsnt.html

[S36] C++：unordered_map
来源：http://dali.snrcjt.cn/Article/details/gtkdrpxuap.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtfpshmpbf.html

[S37] C++：set
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyxdfljio.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.redwolf501.top/Article/details/gtikublxki.html

[S38] C++：排序
来源：http://dali.wangshuangyany.cn/Article/details/gtsnoukncd.html

std::sort(v.begin(), v.end());
来源：http://dali.ehwqpu.com/Article/details/gtgclqnklo.html

[S39] C++：自定义比较器排序
来源：http://dali.jinghuilouyu.cn/Article/details/gtvcogecws.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jianghu66.top/Article/details/gtjggypaoz.html

[S40] C++：查找元素
来源：http://dali.cdnleiting.top/Article/details/gtsjtjxmau.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinqigfzy.top/Article/details/gtrjydnfeu.html

[S41] C++：类与构造函数
来源：http://dali.zhoulong.xyz/Article/details/gtuepllmnb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.guowangkeji.top/Article/details/gtfxgpkuji.html

[S42] C++：继承与虚函数
来源：http://dali.mhx1999.top/Article/details/gtupcxfofk.html

class B : public Base { public: void f() override {} };
来源：http://dali.zycfv.cn/Article/details/gtmvlpurhe.html

[S43] C++：智能指针
来源：http://dali.jqgfzy.top/Article/details/gtfjqkeexq.html

auto p = std::make_unique<int>(5);
来源：http://dali.xuanzx.com/Article/details/gtexizvnza.html

[S44] C++：引用传参
来源：http://dali.dianchejie.cn/Article/details/gtbgkjxcph.html

void inc(int &x) { ++x; }
来源：http://dali.hongshengwenyu.top/Article/details/gtmvupcqhx.html

[S45] C++：lambda
来源：http://dali.daria6918.cn/Article/details/gtibqhmwvl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.fzhhl.top/Article/details/gtsugmrhtb.html

[S46] C++：函数模板
来源：http://dali.jiagoushi.top/Article/details/gtvpvtnepq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xuanzx.com/Article/details/gtktslcmco.html

[S47] C++：结构化绑定遍历
来源：http://dali.xinyue.icu/Article/details/gtwggkyuti.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shuidangran.top/Article/details/gtmnvaebbs.html

[S48] C++：逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gtztqhfzde.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yj20258.top/Article/details/gtihoshccs.html

while (std::getline(in, line)) { }
来源：http://dali.sufxvd.cn/Article/details/gtalivdntq.html

[S49] C++：写文件
来源：http://dali.meibo888.top/Article/details/gtrzogslat.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zdqjudy.top/Article/details/gtnmzwuewo.html

[S50] C++：格式化数字
来源：http://dali.yongpay.top/Article/details/gtllyihzte.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gtnkamwmkr.html

[S51] C++：显式类型转换
来源：http://dali.cashguo.top/Article/details/gtnailrrsa.html

static_cast<double>(a) / b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlawlydhh.html

[S52] C++：const 与 noexcept
来源：http://dali.cucudq.cn/Article/details/gtxrkblvvs.html

int size() const noexcept { return n_; }
来源：http://dali.hnxiangtu.top/Article/details/gtmyrdxezy.html

[S53] C++：移动语义
来源：http://dali.yj202588.top/Article/details/gtmefcnrhb.html

std::vector<int> w = std::move(v);
来源：http://dali.ivvv.top/Article/details/gthpxwsfjj.html

[S54] C++：异常处理
来源：http://dali.hammf.cn/Article/details/gtsyfssfjp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.pycfn.com/Article/details/gttyzfuypo.html

[S55] C++：结构化绑定
来源：http://dali.hysaishi.cn/Article/details/gtiowtdrhw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.quarkkingdee.top/Article/details/gteruijcuz.html

[S56] C++：optional
来源：http://dali.yangfankeji.com/Article/details/gtqmiftkwr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.0kj1m.cn/Article/details/gtpyifpzcl.html

[S57] C++：编译期常量
来源：http://dali.meibo888.top/Article/details/gtrtlfbkbt.html

constexpr int N = 10;
来源：http://dali.guannengcc.top/Article/details/gtyzslfbco.html

[S58] C++：命名空间
来源：http://dali.quarkkingdee.top/Article/details/gtkzvzkhax.html

namespace ns { int f() { return 1; } }
来源：http://dali.xziqi.cn/Article/details/gttcomahyu.html

[S59] C++：静态断言
来源：http://dali.jianghu66.top/Article/details/gtaxcntixo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhengqikj.top/Article/details/gtoyckonqw.html

[S60] C++：遍历并删除元素
来源：http://dali.hnxiangtu.top/Article/details/gtdncddvil.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xylfe.cn/Article/details/gtpxaohucz.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtkxbzhrcj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinqigufen.top/Article/details/gtnngugnco.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtwyiqpreu.html

[T01] Kotlin：Hello World
来源：http://dali.nwbrower.top/Article/details/gtvsywsald.html

println("Hello")
来源：http://dali.yvedp.cn/Article/details/gtukjjmkmc.html

[T02] Kotlin：变量
来源：http://dali.ydzc1.top/Article/details/gtemvfvxew.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cdnleiting.top/Article/details/gtjlnbrfhl.html

[T03] Kotlin：字符串模板
来源：http://dali.kuanghao11.cn/Article/details/gtxwqkmraj.html

"值: $b"
来源：http://dali.chenlongwang.top/Article/details/gtybzwkgwm.html

[T04] Kotlin：空安全
来源：http://dali.haohaochexian.top/Article/details/gtkvnppaeg.html

val n: String? = null;  n?.length
来源：http://dali.yongpay.top/Article/details/gtwhblqyse.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gtlzpsphup.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shanyushiyangtech.top/Article/details/gttscitzgt.html

[T06] Kotlin：集合映射
来源：http://dali.316326.xyz/Article/details/gtipehqnub.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmhuizhtz.html

[T07] Kotlin：集合过滤
来源：http://dali.tanke756.top/Article/details/gtnqjwleuq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jqgufenzy.top/Article/details/gtzazisooa.html

[T08] Kotlin：数据类
来源：http://dali.hnqzz.top/Article/details/gtzxlawvtl.html

data class User(val name: String, val age: Int)
来源：http://dali.svipenyu.cn/Article/details/gtbvybpahh.html

[T09] Kotlin：扩展函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtarxrxooy.html

fun String.exclaim() = this + "!"
来源：http://dali.hysaishi.cn/Article/details/gtfbxlgltl.html

[T10] Kotlin：默认参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtttrrkhzq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.snrcjt.cn/Article/details/gtndyptqht.html

[T11] Kotlin：协程
来源：http://dali.zhongyouzk.top/Article/details/gtmbkqgncs.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sweek.top/Article/details/gtvzbeplrj.html

[T12] Kotlin：解构声明
来源：http://dali.dashuyun.cn/Article/details/gtvpmlbbbm.html

val (a, b) = Pair(1, 2)
来源：http://dali.shzxlz.cn/Article/details/gtcgtyeuqo.html

[T13] Kotlin：只读 Map
来源：http://dali.chenzaomai.com/Article/details/gtuptwtjom.html

val m = mapOf("a" to 1)
来源：http://dali.aibaodan.cn/Article/details/gtojihlblg.html

[T14] Kotlin：循环
来源：http://dali.jqgfzy.top/Article/details/gtxmamumsy.html

for (i in 1..10) println(i)
来源：http://dali.jinqigfzy.top/Article/details/gtsrvoaadn.html

[T15] Kotlin：接口
来源：http://dali.guowangkeji.top/Article/details/gtrqlptzis.html

interface Shape { fun area(): Double }
来源：http://dali.shuidangran.top/Article/details/gtrsnbtnmg.html

[T16] Swift：Hello World
来源：http://dali.hysaishi.cn/Article/details/gtllllpdjy.html

print("Hello")
来源：http://dali.0kj1m.cn/Article/details/gtcksctxja.html

[T17] Swift：变量与常量
来源：http://dali.jinqigfzy.top/Article/details/gtvxrbabbu.html

var a = 1;  let b = 2
来源：http://dali.mhx1999.top/Article/details/gtdtytfeha.html

[T18] Swift：字符串插值
来源：http://dali.aibaodan.cn/Article/details/gthgmnjscr.html

"值: \(b)"
来源：http://dali.ivvv.top/Article/details/gtktciqjfj.html

[T19] Swift：可选绑定
来源：http://dali.ybcxt.top/Article/details/gtfsveqqqq.html

if let n = opt { print(n) }
来源：http://dali.andypj.xyz/Article/details/gtsblyvvnx.html

[T20] Swift：数组操作
来源：http://dali.smart0.xyz/Article/details/gtwilsuvwc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkyuvamwy.html

[T21] Swift：遍历
来源：http://dali.zhongyouzk.top/Article/details/gtywolwrnu.html

for x in a { print(x) }
来源：http://dali.redwolf501.top/Article/details/gtjlyjfkov.html

[T22] Swift：字典
来源：http://dali.fengsongda.top/Article/details/gtjbemvrit.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yanxiufei.cn/Article/details/gtjjprcapi.html

[T23] Swift：函数
来源：http://dali.feifeiyinyue.top/Article/details/gtzilpianz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jinqigufen.top/Article/details/gtludnovnp.html

[T24] Swift：闭包
来源：http://dali.birdmap.top/Article/details/gteshgcbub.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdynzeshm.html

[T25] Swift：结构体
来源：http://dali.daria6918.cn/Article/details/gtgjcdgwvs.html

struct P { var x: Int }
来源：http://dali.yuxming.cn/Article/details/gtckvjufab.html

[T26] Swift：类与重写
来源：http://dali.dianchejie.cn/Article/details/gtlbrtxfvb.html

class A: Base { override func f() {} }
来源：http://dali.guannengcc.top/Article/details/gtzqugzasw.html

[T27] Swift：错误处理
来源：http://dali.cheryme.top/Article/details/gtkvpmqxcx.html

do { try f() } catch { print(error) }
来源：http://dali.shuidangran.top/Article/details/gtzyubieup.html

[T28] Swift：枚举
来源：http://dali.cheryme.top/Article/details/gtzpsjudsx.html

enum Color { case red, green }
来源：http://dali.gaohongyu789.top/Article/details/gtuaoewvwf.html

[T29] Swift：guard 提前返回
来源：http://dali.shzxlz.cn/Article/details/gtisbrjncx.html

guard let x = opt else { return }
来源：http://dali.sweek.top/Article/details/gtxzqkypmv.html

[T30] Swift：协议
来源：http://dali.wangshuangyany.cn/Article/details/gtjnxztvuz.html

protocol Shape { func area() -> Double }
来源：http://dali.fzhhl.top/Article/details/gtoqmxqlfa.html

[T31] Lua：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtutoklyel.html

print("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtncfdzfuy.html

[T32] Lua：局部变量
来源：http://dali.andypj.xyz/Article/details/gtdyxgmukw.html

local a = 1
来源：http://dali.snrcjt.cn/Article/details/gtftdombzf.html

[T33] Lua：表（数组）
来源：http://dali.shangyingyoupin.top/Article/details/gtcbncspdn.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.nanxuanxn.top/Article/details/gtvxejrpke.html

[T34] Lua：遍历表
来源：http://dali.yj20258888.top/Article/details/gteebpxndd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yuxming.cn/Article/details/gthlcvmoqn.html

[T35] Lua：字典表
来源：http://dali.aizwys.cn/Article/details/gtzhckpcsk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.guowangkeji.top/Article/details/gtnonzvvbw.html

[T36] Lua：函数
来源：http://dali.tianlin.xyz/Article/details/gtneybbfmh.html

function add(a, b) return a + b end
来源：http://dali.kuanghao11.cn/Article/details/gtcebzxrbg.html

[T37] Lua：字符串拼接
来源：http://dali.sysykeji.top/Article/details/gtsdvasxxf.html

"a" .. "b"
来源：http://dali.kuanghao11.cn/Article/details/gtqdbvvtin.html

[T38] Lua：条件
来源：http://dali.shuidangran.top/Article/details/gttypvoxub.html

if x > 0 then print("正") end
来源：http://dali.cdnleiting.top/Article/details/gtwsiqgyrq.html

[T39] Lua：模式匹配
来源：http://dali.cdnleiting.top/Article/details/gtzfnmciro.html

string.find(s, "%d+")
来源：http://dali.yangfankeji.com/Article/details/gtashkwncw.html

[T40] Lua：元表
来源：http://dali.ehwqpu.com/Article/details/gtskuhgvbm.html

setmetatable({}, { __index = base })
来源：http://dali.pengpengdd.cyou/Article/details/gtuvqcxjmi.html

[T41] Perl：Hello World
来源：http://dali.tanke756.top/Article/details/gtxweeosvp.html

print "Hello\n";
来源：http://dali.daria6918.cn/Article/details/gttxpyhpsh.html

[T42] Perl：变量类型
来源：http://dali.zhoulong.xyz/Article/details/gtwzhptugo.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.9152youxi.cn/Article/details/gtljmocyli.html

[T43] Perl：字符串插值
来源：http://dali.fzhhl.top/Article/details/gtlkjltomw.html

"值: $a"
来源：http://dali.xuanzx.com/Article/details/gtqulfyygr.html

[T44] Perl：条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtewjfwsnj.html

if ($a > 0) { print "正"; }
来源：http://dali.daxiang520.top/Article/details/gtcathfejf.html

[T45] Perl：数组遍历
来源：http://dali.xuetiantiany.cn/Article/details/gtlxngrshf.html

for my $x (@arr) { print $x; }
来源：http://dali.gzhubu.top/Article/details/gtgmjhnvsk.html

[T46] Perl：哈希操作
来源：http://dali.yangfankeji.com/Article/details/gtiuztppeu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jiagoushi.top/Article/details/gtgfrqrzbx.html

[T47] Perl：正则捕获
来源：http://dali.ybcxt.top/Article/details/gtnxrozezu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.pengpengdd.cyou/Article/details/gtjxzontsb.html

[T48] Perl：正则替换
来源：http://dali.bjfxy.top/Article/details/gtcqhsopyo.html

$s =~ s/old/new/g;
来源：http://dali.tianlin.xyz/Article/details/gtdwqesnix.html

[T49] Perl：函数
来源：http://dali.chenzaomai.com/Article/details/gtsdivcamg.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.nwbrower.top/Article/details/gtkrlvomql.html

[T50] Perl：逐行读文件
来源：http://dali.gzhubu.top/Article/details/gtiotsgjdp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hnqzz.top/Article/details/gtebeejhyg.html


<!-- 参考信息 -->