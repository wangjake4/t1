代发 wailian999

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shzxlz.cn/Article/details/gtwuxdzlni.html

[R50] awk 求和
来源：http://dali.havefunace.top/Article/details/gtdqfvvlwv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.andypj.xyz/Article/details/gtykbosyro.html

[R51] 排序去重取前几
来源：http://dali.yj20258.top/Article/details/gtvtlwduue.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hammf.cn/Article/details/gtyjtwtiul.html

[R52] 统计行数
来源：http://dali.iojbl.cn/Article/details/gtbsjakzif.html

wc -l a.txt
来源：http://dali.gzhubu.top/Article/details/gtzitfivvw.html

[R53] 查看文件头与实时尾
来源：http://dali.9152youxi.cn/Article/details/gtmdzjmgyp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmwjbtazg.html

[R54] 比较两个文件
来源：http://dali.meibo888.top/Article/details/gtageanrhf.html

diff a.txt b.txt
来源：http://dali.feifeiyinyue.top/Article/details/gttpjdzlsv.html

[R55] 压缩与解压
来源：http://dali.snrcjt.cn/Article/details/gtfscmenar.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.nwbrower.top/Article/details/gttenvhdgi.html

[R56] 远程拷贝
来源：http://dali.hysaishi.cn/Article/details/gthbwbsesf.html

scp file user@host:/path/
来源：http://dali.cqqwz.cn/Article/details/gtdwqlwibw.html

[R57] 远程执行命令
来源：http://dali.shuidangran.top/Article/details/gtkhiusbqj.html

ssh user@host 'uptime'
来源：http://dali.xylfe.cn/Article/details/gtrvlpsggr.html

[R58] 下载文件
来源：http://dali.yuanzhike.top/Article/details/gtajwujhzh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.chenjidiqi.icu/Article/details/gtkpqsekul.html

[R59] 发 POST JSON
来源：http://dali.redwolf501.top/Article/details/gtsnezmuvt.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ivvv.top/Article/details/gtoeuhwtyc.html

[R60] 只看 HTTP 状态码
来源：http://dali.kuanghao11.cn/Article/details/gtjxedaeaj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.pycfn.com/Article/details/gtrmcrclpd.html

[R61] 磁盘占用
来源：http://dali.yj20258888.top/Article/details/gtknqoyagv.html

df -h;  du -sh *
来源：http://dali.birdmap.top/Article/details/gtkufvodsc.html

[R62] 找最占空间的文件
来源：http://dali.nwbrower.top/Article/details/gtvpjtkcbe.html

du -ah . | sort -rh | head -10
来源：http://dali.chenzaomai.com/Article/details/gthegziyvy.html

[R63] 内存与进程
来源：http://dali.gaohongyu789.top/Article/details/gtqoyimttc.html

free -h;  ps aux | grep nginx
来源：http://dali.birdmap.top/Article/details/gtdgdidowp.html

[R64] 结束进程
来源：http://dali.hnqzz.top/Article/details/gtxjrwscst.html

kill -9 $(pgrep -f app.py)
来源：http://dali.guannengcc.top/Article/details/gtrfuoqzuf.html

[R65] 查看端口占用
来源：http://dali.0kj1m.cn/Article/details/gtiilihmqt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhixingplan.top/Article/details/gtjlyvzmby.html

[R66] 定时任务
来源：http://dali.wangshuangyany.cn/Article/details/gtyqnhvnzc.html

crontab -e;  crontab -l
来源：http://dali.smart0.xyz/Article/details/gtqnndjhdn.html

[R67] 生成随机十六进制串
来源：http://dali.guannengcc.top/Article/details/gtjoikcwfv.html

openssl rand -hex 16
来源：http://dali.ydzc1.top/Article/details/gtpatwlihd.html

[R68] 计算文件校验值
来源：http://dali.ivvv.top/Article/details/gtygomvdzi.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinqigufen.top/Article/details/gtjazmwsbs.html

[R69] 生成随机密码
来源：http://dali.redwolf501.top/Article/details/gtqxtebqzn.html

head -c 16 /dev/urandom | base64
来源：http://dali.cucudq.cn/Article/details/gtaqfuzxyo.html

[R70] 时间戳与互转
来源：http://dali.kuanghao11.cn/Article/details/gtatmnmunz.html

date +%s;  date -d @1700000000
来源：http://dali.jyoumei.cn/Article/details/gtffaofkuy.html

[R71] 日期格式化
来源：http://dali.xylfe.cn/Article/details/gtspnxbmxn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zdqjudy.top/Article/details/gtihcpqjyz.html

[R72] 等待端口就绪
来源：http://dali.haohaochexian.top/Article/details/gtarcdikqq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.daria6918.cn/Article/details/gtdlhyvghw.html

[R73] 分割大日志
来源：http://dali.jlsjyb.cn/Article/details/gtkvygvxpb.html

split -l 1000 big.log part_
来源：http://dali.zhoulong.xyz/Article/details/gtkzkxidyu.html

[R74] 批量重命名
来源：http://dali.shangyingyoupin.top/Article/details/gtonecvwcm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.chenjidiqi.icu/Article/details/gtjslikylb.html

[R75] 导出环境变量
来源：http://dali.guowangkeji.top/Article/details/gtbtlvfifj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yj202588.top/Article/details/gtlktkpnhy.html

[R76] 使用临时文件
来源：http://dali.tanke756.top/Article/details/gtqnejhwzf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.snrcjt.cn/Article/details/gtlatqpnaa.html

[R77] 读取用户输入
来源：http://dali.meibo888.top/Article/details/gtfqooivbz.html

read -rp "请输入: " ans
来源：http://dali.fzhhl.top/Article/details/gthzovewny.html

[R78] 交互式菜单
来源：http://dali.guannengcc.top/Article/details/gtruciymol.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtsxyzukjk.html

[R79] 解析命令行选项
来源：http://dali.jinqigufen.top/Article/details/gtyzefwxui.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.andypj.xyz/Article/details/gtcqrulqxf.html

[R80] 查看脚本执行耗时
来源：http://dali.shangyingyoupin.top/Article/details/gtodubcrhp.html

time ./run.sh
来源：http://dali.hysaishi.cn/Article/details/gttqoujjne.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtiovrbepg.html

S. C / C++ 专题
来源：http://dali.ybcxt.top/Article/details/gtjbebnbha.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtozdalepg.html

[S01] C：Hello World
来源：http://dali.9152youxi.cn/Article/details/gttjrdnuas.html

#include <stdio.h>
来源：http://dali.shuidangran.top/Article/details/gtfriptugm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.nanxuanxn.top/Article/details/gtaomzkglu.html

[S02] C：变量与格式化输出
来源：http://dali.sxryk.cn/Article/details/gtxjvjcqyt.html

int a = 10; printf("%d\n", a);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzzpfkevl.html

[S03] C：读入整数
来源：http://dali.kuanghao11.cn/Article/details/gtkkeukarf.html

int x; scanf("%d", &x);
来源：http://dali.xinyue.icu/Article/details/gthayafosv.html

[S04] C：字符串复制
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiwzahhkg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jiagoushi.top/Article/details/gttiigopxo.html

[S05] C：字符串长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gttmaxptut.html

strlen(s)
来源：http://dali.andypj.xyz/Article/details/gtvjyqzcrm.html

[S06] C：字符串比较
来源：http://dali.gotoacloud.top/Article/details/gtxamsvotj.html

strcmp(a, b) == 0
来源：http://dali.hnqzz.top/Article/details/gtxvytyegi.html

[S07] C：数组遍历求和
来源：http://dali.nwbrower.top/Article/details/gtpkjgsdno.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cashguo.top/Article/details/gtuxxfnqkz.html

[S08] C：动态内存分配与释放
来源：http://dali.jianghu66.top/Article/details/gtcubbyggd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.pengpengdd.cyou/Article/details/gtitmkjapx.html

[S09] C：结构体定义与初始化
来源：http://dali.gotoacloud.top/Article/details/gtyvbfukji.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zycfv.cn/Article/details/gtyzxlrkcg.html

[S10] C：指针与解引用
来源：http://dali.ybcxt.top/Article/details/gtjfykyqaf.html

int *p = &a;  *p = 5;
来源：http://dali.zdqjudy.top/Article/details/gtoxqjujbg.html

[S11] C：逐行读文件
来源：http://dali.jinqigufen.top/Article/details/gtynypjruq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yuanzhike.top/Article/details/gtegubgadu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.fengsongda.top/Article/details/gtgpuaclms.html

fclose(f);
来源：http://dali.ehwqpu.com/Article/details/gtodgjpjej.html

[S12] C：写文件
来源：http://dali.zhixingplan.top/Article/details/gtoqglstkm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jianghu66.top/Article/details/gtocciqeup.html

[S13] C：宏定义
来源：http://dali.svipenyu.cn/Article/details/gttkwftdnq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hywenlv.cn/Article/details/gtkelathdz.html

[S14] C：枚举
来源：http://dali.yj202588.top/Article/details/gtsknqoopp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmnqkneaq.html

[S15] C：类型转换
来源：http://dali.cdnleiting.top/Article/details/gtfvrteesf.html

(double) a / b
来源：http://dali.hfpthk.cn/Article/details/gtamgbhjrg.html

[S16] C：位操作置位
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvsrmlldo.html

x |= (1 << 3);
来源：http://dali.ybcxt.top/Article/details/gtecddtama.html

[S17] C：安全拼接字符串
来源：http://dali.haohaochexian.top/Article/details/gtausjjxrv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.c1oappe.top/Article/details/gtrobwyits.html

[S18] C：命令行参数
来源：http://dali.snrcjt.cn/Article/details/gtscgcuyew.html

int main(int argc, char **argv)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvwgfxrve.html

[S19] C：快速排序
来源：http://dali.cucudq.cn/Article/details/gtrfazgxdn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.tian-w.cn/Article/details/gtwrpqyfbu.html

[S20] C：二分查找
来源：http://dali.sufxvd.cn/Article/details/gtdfyywiyi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.dashuyun.cn/Article/details/gtbkiowgwq.html

[S21] C：字符类别判断
来源：http://dali.quarkkingdee.top/Article/details/gtmaiucuke.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yj202588.top/Article/details/gtkipvcwop.html

[S22] C：字符串转数字
来源：http://dali.gaohongyu789.top/Article/details/gtjtqrpzqh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.bjfxy.top/Article/details/gthpaponaw.html

[S23] C：随机数
来源：http://dali.shuidangran.top/Article/details/gtwzlwykjg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhoulong.xyz/Article/details/gtahpokpro.html

[S24] C：获取本地时间
来源：http://dali.cheryme.top/Article/details/gtafachyhk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shangyingyoupin.top/Article/details/gtxiziyocp.html

[S25] C：内存拷贝
来源：http://dali.jiagoushi.top/Article/details/gtayifkuun.html

memcpy(dst, src, n);
来源：http://dali.yueranfly.top/Article/details/gtzysidizm.html

[S26] C：内存清零
来源：http://dali.mhx1999.top/Article/details/gtaemntsnz.html

memset(a, 0, sizeof a);
来源：http://dali.chenjidiqi.icu/Article/details/gthfierbfj.html

[S27] C：定义常量
来源：http://dali.sysykeji.top/Article/details/gtwszbmeoq.html

const double PI = 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gtubaqmegy.html

[S28] C：静态变量
来源：http://dali.zhiwuduotai.top/Article/details/gtjnculzxy.html

static int counter = 0;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzwvvauei.html

[S29] C：变参函数
来源：http://dali.meibo888.top/Article/details/gtzugzlpbi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xuanzx.com/Article/details/gtujbttouu.html

[S30] C：头文件保护
来源：http://dali.snrcjt.cn/Article/details/gtkvrcpsed.html

#ifndef X_H
来源：http://dali.jinqigfzy.top/Article/details/gtkjzaelrt.html

#define X_H
来源：http://dali.hysaishi.cn/Article/details/gtjjijvvob.html

#endif
来源：http://dali.birdmap.top/Article/details/gtyzbkgwxa.html

[S31] C++：Hello World
来源：http://dali.shzxlz.cn/Article/details/gthqhgfddb.html

#include <iostream>
来源：http://dali.shanyushiyangkeji.top/Article/details/gthzkdndne.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ybcxt.top/Article/details/gtcpgxkfix.html

[S32] C++：字符串
来源：http://dali.guannengcc.top/Article/details/gtvmjzhoht.html

std::string s = "hi";  s += "!";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvwcspjrx.html

[S33] C++：vector 增删
来源：http://dali.gzhubu.top/Article/details/gtmzccbspu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdyfjpamr.html

[S34] C++：遍历 vector
来源：http://dali.hnxiangtu.top/Article/details/gtxvggmfiw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yangfankeji.com/Article/details/gtbdtnhjwd.html

[S35] C++：map
来源：http://dali.pengpengdd.cyou/Article/details/gtahigtftm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gtabvzfjoa.html

[S36] C++：unordered_map
来源：http://dali.hongshengwenyu.top/Article/details/gtoozmxmrr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yongpay.top/Article/details/gtjqdkxikc.html

[S37] C++：set
来源：http://dali.ybcxt.top/Article/details/gtskudqovl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sxryk.cn/Article/details/gtagirgrxv.html

[S38] C++：排序
来源：http://dali.316326.xyz/Article/details/gttseylzlj.html

std::sort(v.begin(), v.end());
来源：http://dali.chenlongwang.top/Article/details/gtlwydwnue.html

[S39] C++：自定义比较器排序
来源：http://dali.yj20258.top/Article/details/gtuliemyct.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenjidiqi.icu/Article/details/gtsjaujvva.html

[S40] C++：查找元素
来源：http://dali.gotoacloud.top/Article/details/gtmjwxkosb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.dashuyun.cn/Article/details/gtbdcdptmw.html

[S41] C++：类与构造函数
来源：http://dali.yangfankeji.com/Article/details/gtpmnzzwfb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhoulong.xyz/Article/details/gtnvpxgnuu.html

[S42] C++：继承与虚函数
来源：http://dali.smart0.xyz/Article/details/gtxsxamkwo.html

class B : public Base { public: void f() override {} };
来源：http://dali.xuanzx.com/Article/details/gtofmxtoaq.html

[S43] C++：智能指针
来源：http://dali.nanxuanxn.top/Article/details/gtswxufcba.html

auto p = std::make_unique<int>(5);
来源：http://dali.yonumen.top/Article/details/gtlpiatwhy.html

[S44] C++：引用传参
来源：http://dali.svipenyu.cn/Article/details/gtgakkhhqo.html

void inc(int &x) { ++x; }
来源：http://dali.sysykeji.top/Article/details/gtamtyjugr.html

[S45] C++：lambda
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdiotkdey.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhiwuduotai.top/Article/details/gtgxeownhb.html

[S46] C++：函数模板
来源：http://dali.wangdashe.top/Article/details/gtwkqmgrmt.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yuxming.cn/Article/details/gtdohfgbiu.html

[S47] C++：结构化绑定遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtgsujricj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.wangshuangyany.cn/Article/details/gtlsgdxbbo.html

[S48] C++：逐行读文件
来源：http://dali.smart0.xyz/Article/details/gtzmpfzyqa.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yanxiufei.cn/Article/details/gtqkyuhccw.html

while (std::getline(in, line)) { }
来源：http://dali.quarkkingdee.top/Article/details/gthruobonh.html

[S49] C++：写文件
来源：http://dali.zhongyouzk.top/Article/details/gtycxiyoic.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhiwuduotai.top/Article/details/gthtvnwolq.html

[S50] C++：格式化数字
来源：http://dali.hysaishi.cn/Article/details/gtkyxhrrwj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.smart0.xyz/Article/details/gtevyzvckt.html

[S51] C++：显式类型转换
来源：http://dali.mhx1999.top/Article/details/gtprprpitw.html

static_cast<double>(a) / b
来源：http://dali.hnqzz.top/Article/details/gtgvnwadzo.html

[S52] C++：const 与 noexcept
来源：http://dali.hywenlv.cn/Article/details/gtswujbsbm.html

int size() const noexcept { return n_; }
来源：http://dali.gzhubu.top/Article/details/gtgcnxyatw.html

[S53] C++：移动语义
来源：http://dali.xinyue.icu/Article/details/gtjyziirxr.html

std::vector<int> w = std::move(v);
来源：http://dali.birdmap.top/Article/details/gtlymagceu.html

[S54] C++：异常处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmmdtolvr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlpydhgub.html

[S55] C++：结构化绑定
来源：http://dali.hfpthk.cn/Article/details/gtwsjgoyxb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.birdmap.top/Article/details/gtvwwekeui.html

[S56] C++：optional
来源：http://dali.cashguo.top/Article/details/gtkbvsomtm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhongyouzk.top/Article/details/gtgpojgjzn.html

[S57] C++：编译期常量
来源：http://dali.gzhubu.top/Article/details/gtreikkytr.html

constexpr int N = 10;
来源：http://dali.smart0.xyz/Article/details/gtvaazetax.html

[S58] C++：命名空间
来源：http://dali.xuetiantiany.cn/Article/details/gtgqgzrlce.html

namespace ns { int f() { return 1; } }
来源：http://dali.yvedp.cn/Article/details/gtnlenkyxz.html

[S59] C++：静态断言
来源：http://dali.aibaodan.cn/Article/details/gtydtjcmov.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.snrcjt.cn/Article/details/gtkbjryvup.html

[S60] C++：遍历并删除元素
来源：http://dali.snrcjt.cn/Article/details/gtxyaqcjxv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.316326.xyz/Article/details/gtsbmrwwkp.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtapjnwvho.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzkliumwo.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtplpvmmhn.html

[T01] Kotlin：Hello World
来源：http://dali.bjfxy.top/Article/details/gtclhblzvv.html

println("Hello")
来源：http://dali.c1oappe.top/Article/details/gtnabnttip.html

[T02] Kotlin：变量
来源：http://dali.snrcjt.cn/Article/details/gtbxvjtpyx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.chenjidiqi.icu/Article/details/gtdgzngkvy.html

[T03] Kotlin：字符串模板
来源：http://dali.jianghu66.top/Article/details/gtiadbajvt.html

"值: $b"
来源：http://dali.nanxinkj.top/Article/details/gtwtpkglks.html

[T04] Kotlin：空安全
来源：http://dali.aizwys.cn/Article/details/gtlajrowmo.html

val n: String? = null;  n?.length
来源：http://dali.shangyingyoupin.top/Article/details/gtemuixvsh.html

[T05] Kotlin：when 表达式
来源：http://dali.zhengqikj.top/Article/details/gtjrjylgzt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.smart0.xyz/Article/details/gtnfvzzfmx.html

[T06] Kotlin：集合映射
来源：http://dali.gogol.net.cn/Article/details/gtgarukydg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.tianlin.xyz/Article/details/gtkotxrhwk.html

[T07] Kotlin：集合过滤
来源：http://dali.xziqi.cn/Article/details/gtzqqyhbtt.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxpoqxqms.html

[T08] Kotlin：数据类
来源：http://dali.zhongyouzk.top/Article/details/gtyifdeujv.html

data class User(val name: String, val age: Int)
来源：http://dali.cdnleiting.top/Article/details/gtmyjspzkz.html

[T09] Kotlin：扩展函数
来源：http://dali.kuanghao11.cn/Article/details/gtxarxmzgb.html

fun String.exclaim() = this + "!"
来源：http://dali.hywenlv.cn/Article/details/gthaeanwnn.html

[T10] Kotlin：默认参数
来源：http://dali.jlsjyb.cn/Article/details/gtcmajwkcb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yuanzhike.top/Article/details/gtvhrkixpy.html

[T11] Kotlin：协程
来源：http://dali.jianghu66.top/Article/details/gttbxkfkhy.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jinqigufen.top/Article/details/gthuviongb.html

[T12] Kotlin：解构声明
来源：http://dali.birdmap.top/Article/details/gtrcpqcrpl.html

val (a, b) = Pair(1, 2)
来源：http://dali.daxiang520.top/Article/details/gtvdbbdhaz.html

[T13] Kotlin：只读 Map
来源：http://dali.aibaodan.cn/Article/details/gtcmkgfixj.html

val m = mapOf("a" to 1)
来源：http://dali.sxryk.cn/Article/details/gtvibdeyeb.html

[T14] Kotlin：循环
来源：http://dali.xuetiantiany.cn/Article/details/gtkghytsgv.html

for (i in 1..10) println(i)
来源：http://dali.hnxiangtu.top/Article/details/gtxotxcxaa.html

[T15] Kotlin：接口
来源：http://dali.birdmap.top/Article/details/gtstabbzmv.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gtrekmqmll.html

[T16] Swift：Hello World
来源：http://dali.birdmap.top/Article/details/gtcbxvqwhv.html

print("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gtvwizvqmv.html

[T17] Swift：变量与常量
来源：http://dali.tian-w.cn/Article/details/gtmfvdlsti.html

var a = 1;  let b = 2
来源：http://dali.nanxuanxn.top/Article/details/gtfbiqaaxq.html

[T18] Swift：字符串插值
来源：http://dali.tian-w.cn/Article/details/gtfdopxjij.html

"值: \(b)"
来源：http://dali.jinqigfzy.top/Article/details/gtyrfrzxpn.html

[T19] Swift：可选绑定
来源：http://dali.bjfxy.top/Article/details/gtvafhibuj.html

if let n = opt { print(n) }
来源：http://dali.cashguo.top/Article/details/gtdhpsdujm.html

[T20] Swift：数组操作
来源：http://dali.meibo888.top/Article/details/gttutwvslw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhongyouzk.top/Article/details/gtlpabbkyh.html

[T21] Swift：遍历
来源：http://dali.jiagoushi.top/Article/details/gtpvckrlzf.html

for x in a { print(x) }
来源：http://dali.shuidangran.top/Article/details/gtvcewvibl.html

[T22] Swift：字典
来源：http://dali.jianghu66.top/Article/details/gtqxiuakob.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gotoacloud.top/Article/details/gtlssxrehx.html

[T23] Swift：函数
来源：http://dali.yj20258.top/Article/details/gtgnrfapdo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtffcckdeu.html

[T24] Swift：闭包
来源：http://dali.hfpthk.cn/Article/details/gtvcpgyokw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.fengsongda.top/Article/details/gtkzqrvoju.html

[T25] Swift：结构体
来源：http://dali.yvedp.cn/Article/details/gthqwioejs.html

struct P { var x: Int }
来源：http://dali.cheryme.top/Article/details/gtsytssgma.html

[T26] Swift：类与重写
来源：http://dali.sysykeji.top/Article/details/gtnegzusfv.html

class A: Base { override func f() {} }
来源：http://dali.aibaodan.cn/Article/details/gtbjcwetkv.html

[T27] Swift：错误处理
来源：http://dali.nanxuanxn.top/Article/details/gtbaipfjqv.html

do { try f() } catch { print(error) }
来源：http://dali.zycfv.cn/Article/details/gtpttrjqif.html

[T28] Swift：枚举
来源：http://dali.ybcxt.top/Article/details/gtdglpxgps.html

enum Color { case red, green }
来源：http://dali.wangdashe.top/Article/details/gtokhtblvr.html

[T29] Swift：guard 提前返回
来源：http://dali.chenjidiqi.icu/Article/details/gtgbtrbiyn.html

guard let x = opt else { return }
来源：http://dali.yuxming.cn/Article/details/gtohczeqpu.html

[T30] Swift：协议
来源：http://dali.fengsongda.top/Article/details/gttvssmykh.html

protocol Shape { func area() -> Double }
来源：http://dali.guowangkeji.top/Article/details/gtuqpueenl.html

[T31] Lua：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtpwbrbyik.html

print("Hello")
来源：http://dali.jyoumei.cn/Article/details/gtsdujsyny.html

[T32] Lua：局部变量
来源：http://dali.hysaishi.cn/Article/details/gtzaoqskld.html

local a = 1
来源：http://dali.smart0.xyz/Article/details/gtsqnxfdid.html

[T33] Lua：表（数组）
来源：http://dali.meibo888.top/Article/details/gtewtofqjt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.316326.xyz/Article/details/gtuvqwtdsx.html

[T34] Lua：遍历表
来源：http://dali.haohaochexian.top/Article/details/gtmeqaiije.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.gzhubu.top/Article/details/gtuwkqkjyr.html

[T35] Lua：字典表
来源：http://dali.fzhhl.top/Article/details/gtenmptkgb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.feifeiyinyue.top/Article/details/gtjguzechw.html

[T36] Lua：函数
来源：http://dali.haohaochexian.top/Article/details/gtkgixggha.html

function add(a, b) return a + b end
来源：http://dali.jinqigfzy.top/Article/details/gtfjwyvghr.html

[T37] Lua：字符串拼接
来源：http://dali.vqdsnc.cn/Article/details/gtviuxtdcr.html

"a" .. "b"
来源：http://dali.jyoumei.cn/Article/details/gtgnxyatrl.html

[T38] Lua：条件
来源：http://dali.dashuyun.cn/Article/details/gtcttmkzav.html

if x > 0 then print("正") end
来源：http://dali.nanxuanxn.top/Article/details/gtwcauvspi.html

[T39] Lua：模式匹配
来源：http://dali.aibaodan.cn/Article/details/gtiyxdwgnu.html

string.find(s, "%d+")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdmkzuvif.html

[T40] Lua：元表
来源：http://dali.fzhhl.top/Article/details/gtllhzqmbj.html

setmetatable({}, { __index = base })
来源：http://dali.zhongyouzk.top/Article/details/gtpsateteu.html

[T41] Perl：Hello World
来源：http://dali.tianlin.xyz/Article/details/gthmowekky.html

print "Hello\n";
来源：http://dali.fzhhl.top/Article/details/gtojhmmjgc.html

[T42] Perl：变量类型
来源：http://dali.jyoumei.cn/Article/details/gtqqycqmbg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yuxming.cn/Article/details/gtxuzyxlat.html

[T43] Perl：字符串插值
来源：http://dali.jyoumei.cn/Article/details/gtkbpeewgi.html

"值: $a"
来源：http://dali.hongshengwenyu.top/Article/details/gtytokzaqo.html

[T44] Perl：条件
来源：http://dali.guannengcc.top/Article/details/gtpcidllqo.html

if ($a > 0) { print "正"; }
来源：http://dali.nanxuanxn.top/Article/details/gtvwxkdwtg.html

[T45] Perl：数组遍历
来源：http://dali.cdnleiting.top/Article/details/gtcmrgvnpe.html

for my $x (@arr) { print $x; }
来源：http://dali.gotoacloud.top/Article/details/gtdbxnlcdj.html

[T46] Perl：哈希操作
来源：http://dali.pengpengdd.cyou/Article/details/gtgkmdcjwr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtdlbtfbnj.html

[T47] Perl：正则捕获
来源：http://dali.wangshuangyany.cn/Article/details/gtuworaxec.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.bjfxy.top/Article/details/gtznflgvaj.html

[T48] Perl：正则替换
来源：http://dali.havefunace.top/Article/details/gterwvqyjk.html

$s =~ s/old/new/g;
来源：http://dali.xziqi.cn/Article/details/gtnuatpctk.html

[T49] Perl：函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtldenblqr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.gaohongyu789.top/Article/details/gtkuzqwxuo.html

[T50] Perl：逐行读文件
来源：http://dali.ivvv.top/Article/details/gtfhmavwij.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ivvv.top/Article/details/gtmgeymkzd.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hysaishi.cn/Article/details/gtptfmuxmx.html

[T51] Scala：Hello World
来源：http://dali.yueranfly.top/Article/details/gtplyktjjh.html

println("Hello")
来源：http://dali.nanxinkj.top/Article/details/gtwesieqpg.html

[T52] Scala：变量
来源：http://dali.haohaochexian.top/Article/details/gtkonnaydd.html


<!-- 参考信息 -->