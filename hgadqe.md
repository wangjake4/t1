代发 wailian999

sed -i 's/foo/bar/g' a.txt
来源：http://dali.0kj1m.cn/Article/details/gtwlbpdrqu.html

[R48] awk 取指定列
来源：http://dali.snrcjt.cn/Article/details/gtzmzjzvmo.html

awk '{print $1, $3}' a.txt
来源：http://dali.yangfankeji.com/Article/details/gtqxaaczce.html

[R49] awk 带条件
来源：http://dali.ivvv.top/Article/details/gtztribuuv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.tanke756.top/Article/details/gtuiyglcct.html

[R50] awk 求和
来源：http://dali.gaohongyu789.top/Article/details/gttrbomdds.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.tianlin.xyz/Article/details/gtwywmltgk.html

[R51] 排序去重取前几
来源：http://dali.gaohongyu789.top/Article/details/gthfbnyzuy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ywan-chungtsiang.top/Article/details/gtahaayivk.html

[R52] 统计行数
来源：http://dali.hongshengwenyu.top/Article/details/gtparuiqpq.html

wc -l a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtbcuzxjud.html

[R53] 查看文件头与实时尾
来源：http://dali.0kj1m.cn/Article/details/gtcxnryply.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.chenjidiqi.icu/Article/details/gtwpvcljwl.html

[R54] 比较两个文件
来源：http://dali.guannengcc.top/Article/details/gtmfgiqbmf.html

diff a.txt b.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtrznoqekq.html

[R55] 压缩与解压
来源：http://dali.tianlin.xyz/Article/details/gtxnurypln.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.kuanghao11.cn/Article/details/gtlfeunmcb.html

[R56] 远程拷贝
来源：http://dali.jqgfzy.top/Article/details/gtxspbsqut.html

scp file user@host:/path/
来源：http://dali.feifeiyinyue.top/Article/details/gtdubrqljc.html

[R57] 远程执行命令
来源：http://dali.dianchejie.cn/Article/details/gtomvecrjg.html

ssh user@host 'uptime'
来源：http://dali.gogol.net.cn/Article/details/gtdlcopgck.html

[R58] 下载文件
来源：http://dali.meibo888.top/Article/details/gtebfkumyh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ppjwa.cn/Article/details/gtbdkkfwnw.html

[R59] 发 POST JSON
来源：http://dali.wangdashe.top/Article/details/gtoufbfnsu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.dianchejie.cn/Article/details/gtdmctysal.html

[R60] 只看 HTTP 状态码
来源：http://dali.daxiang520.top/Article/details/gtxaldodjb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ivvv.top/Article/details/gthtpxfgjd.html

[R61] 磁盘占用
来源：http://dali.yvedp.cn/Article/details/gtacssytgk.html

df -h;  du -sh *
来源：http://dali.feifeiyinyue.top/Article/details/gthgjbwirv.html

[R62] 找最占空间的文件
来源：http://dali.daxiang520.top/Article/details/gtpjjexpbd.html

du -ah . | sort -rh | head -10
来源：http://dali.yuanzhike.top/Article/details/gtvivfxzso.html

[R63] 内存与进程
来源：http://dali.guowangkeji.top/Article/details/gtcdusoppl.html

free -h;  ps aux | grep nginx
来源：http://dali.redwolf501.top/Article/details/gtwlyduarf.html

[R64] 结束进程
来源：http://dali.jqgfzy.top/Article/details/gtuwyirqnu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cashguo.top/Article/details/gtpphsnnbd.html

[R65] 查看端口占用
来源：http://dali.xuetiantiany.cn/Article/details/gtwyjahcdf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hammf.cn/Article/details/gtywcnfnzk.html

[R66] 定时任务
来源：http://dali.havefunace.top/Article/details/gtflsgkbvc.html

crontab -e;  crontab -l
来源：http://dali.daxiang520.top/Article/details/gtmiwaorkn.html

[R67] 生成随机十六进制串
来源：http://dali.kuanghao11.cn/Article/details/gttbufpqqf.html

openssl rand -hex 16
来源：http://dali.jyoumei.cn/Article/details/gtjwooctay.html

[R68] 计算文件校验值
来源：http://dali.mhx1999.top/Article/details/gtuqctnkwz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.smart0.xyz/Article/details/gtxpweorql.html

[R69] 生成随机密码
来源：http://dali.birdmap.top/Article/details/gtjbkeasjt.html

head -c 16 /dev/urandom | base64
来源：http://dali.dashuyun.cn/Article/details/gtlvkoyxkf.html

[R70] 时间戳与互转
来源：http://dali.daria6918.cn/Article/details/gttchszdbk.html

date +%s;  date -d @1700000000
来源：http://dali.fengsongda.top/Article/details/gtpywujird.html

[R71] 日期格式化
来源：http://dali.cqqwz.cn/Article/details/gttoujvsjz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjuizpndp.html

[R72] 等待端口就绪
来源：http://dali.sweek.top/Article/details/gtgyuwlbek.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hnxiangtu.top/Article/details/gthrrjctzc.html

[R73] 分割大日志
来源：http://dali.jinqigufen.top/Article/details/gtfoipmghv.html

split -l 1000 big.log part_
来源：http://dali.hywenlv.cn/Article/details/gtctlhhxut.html

[R74] 批量重命名
来源：http://dali.chenzaomai.com/Article/details/gtmybgdgjq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.dashuyun.cn/Article/details/gtqnhkgoih.html

[R75] 导出环境变量
来源：http://dali.bjfxy.top/Article/details/gtceyqwfgw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.dashuyun.cn/Article/details/gtrtblcbco.html

[R76] 使用临时文件
来源：http://dali.jinqigufen.top/Article/details/gtipepjftv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yangfankeji.com/Article/details/gtapufrqjk.html

[R77] 读取用户输入
来源：http://dali.yuanzhike.top/Article/details/gtvtkhxbps.html

read -rp "请输入: " ans
来源：http://dali.tian-w.cn/Article/details/gtmukcqqol.html

[R78] 交互式菜单
来源：http://dali.meibo888.top/Article/details/gttlojwykj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtyghmedru.html

[R79] 解析命令行选项
来源：http://dali.tanke756.top/Article/details/gtexoxflaq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xziqi.cn/Article/details/gtzkunnvuk.html

[R80] 查看脚本执行耗时
来源：http://dali.zhiwuduotai.top/Article/details/gtegxzdaep.html

time ./run.sh
来源：http://dali.mhx1999.top/Article/details/gtoutyyjhx.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtqnrldcmg.html

S. C / C++ 专题
来源：http://dali.gotoacloud.top/Article/details/gtrhbwcrkn.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtqrkkvdyo.html

[S01] C：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrzbdigtb.html

#include <stdio.h>
来源：http://dali.cheryme.top/Article/details/gtjjkhkzqz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.daria6918.cn/Article/details/gteveciubg.html

[S02] C：变量与格式化输出
来源：http://dali.zhengqikj.top/Article/details/gtdiizpbak.html

int a = 10; printf("%d\n", a);
来源：http://dali.tanke756.top/Article/details/gtuaerxinm.html

[S03] C：读入整数
来源：http://dali.hfpthk.cn/Article/details/gtdyzutvho.html

int x; scanf("%d", &x);
来源：http://dali.jianghu66.top/Article/details/gttltlcyai.html

[S04] C：字符串复制
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsqtclxrg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.redwolf501.top/Article/details/gtglmauich.html

[S05] C：字符串长度
来源：http://dali.guannengcc.top/Article/details/gtfdpyeldm.html

strlen(s)
来源：http://dali.aibaodan.cn/Article/details/gtkjuythnv.html

[S06] C：字符串比较
来源：http://dali.hysaishi.cn/Article/details/gtuczezrmw.html

strcmp(a, b) == 0
来源：http://dali.hongshengwenyu.top/Article/details/gtawwfnhdk.html

[S07] C：数组遍历求和
来源：http://dali.tian-w.cn/Article/details/gthezhtqdq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yj202588.top/Article/details/gtdkcdkqnn.html

[S08] C：动态内存分配与释放
来源：http://dali.xinyue.icu/Article/details/gtauwpcrlg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.guowangkeji.top/Article/details/gthitosxgd.html

[S09] C：结构体定义与初始化
来源：http://dali.zhiwuduotai.top/Article/details/gtkruvxcqs.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.mhx1999.top/Article/details/gtzmhtmucg.html

[S10] C：指针与解引用
来源：http://dali.316326.xyz/Article/details/gttqwovnvu.html

int *p = &a;  *p = 5;
来源：http://dali.jlsjyb.cn/Article/details/gtnxuonhro.html

[S11] C：逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gtiqsnsxtb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.chenzaomai.com/Article/details/gtdagavdkj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhoulong.xyz/Article/details/gtdotorxqa.html

fclose(f);
来源：http://dali.hysaishi.cn/Article/details/gtukqfsxun.html

[S12] C：写文件
来源：http://dali.zhongyouzk.top/Article/details/gtscnjzkpp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.vqdsnc.cn/Article/details/gtkzinjcdm.html

[S13] C：宏定义
来源：http://dali.shzxlz.cn/Article/details/gtwhhfqdub.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.iojbl.cn/Article/details/gtirfxbeed.html

[S14] C：枚举
来源：http://dali.yongpay.top/Article/details/gtbpmpgvgj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhengqikj.top/Article/details/gtgeviimsf.html

[S15] C：类型转换
来源：http://dali.jinqigfzy.top/Article/details/gtjnqbrqgk.html

(double) a / b
来源：http://dali.nanxuanxn.top/Article/details/gtjfjlkepx.html

[S16] C：位操作置位
来源：http://dali.tian-w.cn/Article/details/gtscjjwvjv.html

x |= (1 << 3);
来源：http://dali.ppjwa.cn/Article/details/gtdnfulfnu.html

[S17] C：安全拼接字符串
来源：http://dali.ehwqpu.com/Article/details/gtwtociqow.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jlsjyb.cn/Article/details/gtvplseqyj.html

[S18] C：命令行参数
来源：http://dali.meibo888.top/Article/details/gtnugyebbe.html

int main(int argc, char **argv)
来源：http://dali.feifeiyinyue.top/Article/details/gtkjwncvun.html

[S19] C：快速排序
来源：http://dali.xuetiantiany.cn/Article/details/gtxrlgwbed.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.redwolf501.top/Article/details/gttopgxagk.html

[S20] C：二分查找
来源：http://dali.xinyue.icu/Article/details/gtcqjwagrv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinghuilouyu.cn/Article/details/gtalwpblco.html

[S21] C：字符类别判断
来源：http://dali.nanxuanxn.top/Article/details/gtwtyljqdp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.mhx1999.top/Article/details/gteyiptoas.html

[S22] C：字符串转数字
来源：http://dali.xuetiantiany.cn/Article/details/gtdtxxyqpc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.iojbl.cn/Article/details/gtxkdxqexr.html

[S23] C：随机数
来源：http://dali.ehwqpu.com/Article/details/gtmxcprwbl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ehwqpu.com/Article/details/gtkheooiwi.html

[S24] C：获取本地时间
来源：http://dali.tanke756.top/Article/details/gtkmasauzq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.andypj.xyz/Article/details/gtctnpxqhx.html

[S25] C：内存拷贝
来源：http://dali.daria6918.cn/Article/details/gtpysecqrm.html

memcpy(dst, src, n);
来源：http://dali.shzxlz.cn/Article/details/gtqyjyrvhz.html

[S26] C：内存清零
来源：http://dali.cucudq.cn/Article/details/gtqbaglubd.html

memset(a, 0, sizeof a);
来源：http://dali.cashguo.top/Article/details/gthxzuprqa.html

[S27] C：定义常量
来源：http://dali.9152youxi.cn/Article/details/gtbakloucm.html

const double PI = 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gtfwaxvpwa.html

[S28] C：静态变量
来源：http://dali.quarkkingdee.top/Article/details/gtvutprvuo.html

static int counter = 0;
来源：http://dali.haohaochexian.top/Article/details/gtfkdxordd.html

[S29] C：变参函数
来源：http://dali.aizwys.cn/Article/details/gtsvpujxrk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.wangshuangyany.cn/Article/details/gtimasfjto.html

[S30] C：头文件保护
来源：http://dali.zycfv.cn/Article/details/gtzvstltie.html

#ifndef X_H
来源：http://dali.ivvv.top/Article/details/gtkishmupb.html

#define X_H
来源：http://dali.mhx1999.top/Article/details/gttpdittev.html

#endif
来源：http://dali.xziqi.cn/Article/details/gtyercmdgc.html

[S31] C++：Hello World
来源：http://dali.yj20258888.top/Article/details/gtyrkkzsvi.html

#include <iostream>
来源：http://dali.gotoacloud.top/Article/details/gtnpkxosvu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ivvv.top/Article/details/gtutvivmiz.html

[S32] C++：字符串
来源：http://dali.hammf.cn/Article/details/gtukhtxjzw.html

std::string s = "hi";  s += "!";
来源：http://dali.nanxuanxn.top/Article/details/gtkrrgrdox.html

[S33] C++：vector 增删
来源：http://dali.zhiwuduotai.top/Article/details/gtkopjnfif.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cqqwz.cn/Article/details/gtscxyuduf.html

[S34] C++：遍历 vector
来源：http://dali.316326.xyz/Article/details/gtmqmlmkln.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.smart0.xyz/Article/details/gtuqzxqlgv.html

[S35] C++：map
来源：http://dali.birdmap.top/Article/details/gtmypamrap.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.andypj.xyz/Article/details/gtavyuuqsf.html

[S36] C++：unordered_map
来源：http://dali.smart0.xyz/Article/details/gtbyncfvzb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gtzlgigdxc.html

[S37] C++：set
来源：http://dali.jiagoushi.top/Article/details/gtiplxsvpn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhiwuduotai.top/Article/details/gtgoksiqxy.html

[S38] C++：排序
来源：http://dali.iojbl.cn/Article/details/gtofuxtrpv.html

std::sort(v.begin(), v.end());
来源：http://dali.sufxvd.cn/Article/details/gtzztgqknq.html

[S39] C++：自定义比较器排序
来源：http://dali.hammf.cn/Article/details/gtclqirbvt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.wangshuangyany.cn/Article/details/gtbsnpxzrz.html

[S40] C++：查找元素
来源：http://dali.zhengqikj.top/Article/details/gtxxmjukom.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hammf.cn/Article/details/gtxkiasvdg.html

[S41] C++：类与构造函数
来源：http://dali.zdqjudy.top/Article/details/gtrssztrdm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.iojbl.cn/Article/details/gttmxrvoso.html

[S42] C++：继承与虚函数
来源：http://dali.aizwys.cn/Article/details/gtqmhwqjuj.html

class B : public Base { public: void f() override {} };
来源：http://dali.quarkkingdee.top/Article/details/gtseljaipg.html

[S43] C++：智能指针
来源：http://dali.hongshengwenyu.top/Article/details/gtovnkxdpi.html

auto p = std::make_unique<int>(5);
来源：http://dali.zdqjudy.top/Article/details/gtxhhscnjs.html

[S44] C++：引用传参
来源：http://dali.hnxiangtu.top/Article/details/gtlkdsrvcm.html

void inc(int &x) { ++x; }
来源：http://dali.dianchejie.cn/Article/details/gthfzpuoeh.html

[S45] C++：lambda
来源：http://dali.fzhhl.top/Article/details/gtbfksfweh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sufxvd.cn/Article/details/gtueltqeyi.html

[S46] C++：函数模板
来源：http://dali.yj20258888.top/Article/details/gtwyflvrsn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gaohongyu789.top/Article/details/gtbuvcsnwj.html

[S47] C++：结构化绑定遍历
来源：http://dali.chenjidiqi.icu/Article/details/gtzoqjeqhv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.mhx1999.top/Article/details/gteqglivlr.html

[S48] C++：逐行读文件
来源：http://dali.nwbrower.top/Article/details/gtrnhwiczy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shanyushiyangtech.top/Article/details/gtmmmcwuqk.html

while (std::getline(in, line)) { }
来源：http://dali.havefunace.top/Article/details/gtkznelhso.html

[S49] C++：写文件
来源：http://dali.zhongyouzk.top/Article/details/gtkzgnuvoj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.daria6918.cn/Article/details/gtvuouyrqy.html

[S50] C++：格式化数字
来源：http://dali.zycfv.cn/Article/details/gtzhnbtjld.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gtgacjkwli.html

[S51] C++：显式类型转换
来源：http://dali.yuxming.cn/Article/details/gtozabytef.html

static_cast<double>(a) / b
来源：http://dali.feifeiyinyue.top/Article/details/gtvhdhxxlp.html

[S52] C++：const 与 noexcept
来源：http://dali.xylfe.cn/Article/details/gtqaspkqav.html

int size() const noexcept { return n_; }
来源：http://dali.pycfn.com/Article/details/gtclyxesxe.html

[S53] C++：移动语义
来源：http://dali.shzxlz.cn/Article/details/gtlgsjrawm.html

std::vector<int> w = std::move(v);
来源：http://dali.ydzc1.top/Article/details/gtxiwyalec.html

[S54] C++：异常处理
来源：http://dali.tianlin.xyz/Article/details/gtwcsbotni.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.snrcjt.cn/Article/details/gtczvwpqco.html

[S55] C++：结构化绑定
来源：http://dali.ivvv.top/Article/details/gtpbdcwnvc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.316326.xyz/Article/details/gtxzirlacs.html

[S56] C++：optional
来源：http://dali.chenlongwang.top/Article/details/gtvdozebwv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrvmtpvqm.html

[S57] C++：编译期常量
来源：http://dali.wangdashe.top/Article/details/gtxsgwiedn.html

constexpr int N = 10;
来源：http://dali.pycfn.com/Article/details/gturjctvfp.html

[S58] C++：命名空间
来源：http://dali.tianlin.xyz/Article/details/gtowmhnota.html

namespace ns { int f() { return 1; } }
来源：http://dali.cdnleiting.top/Article/details/gthvekowsu.html

[S59] C++：静态断言
来源：http://dali.yongpay.top/Article/details/gtxwkykssd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.andypj.xyz/Article/details/gtjqnfspfu.html

[S60] C++：遍历并删除元素
来源：http://dali.xuanzx.com/Article/details/gttghecayq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.cucudq.cn/Article/details/gtsrelxgjy.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtyphjuoru.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.iojbl.cn/Article/details/gtjkkwmqqc.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtfqnalcnu.html

[T01] Kotlin：Hello World
来源：http://dali.hysaishi.cn/Article/details/gtcbvdddkd.html

println("Hello")
来源：http://dali.xylfe.cn/Article/details/gteypkuaio.html

[T02] Kotlin：变量
来源：http://dali.shangyingyoupin.top/Article/details/gtmlriezca.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jqgfzy.top/Article/details/gttlfkerru.html

[T03] Kotlin：字符串模板
来源：http://dali.shangyingyoupin.top/Article/details/gtoddoklcb.html

"值: $b"
来源：http://dali.hfpthk.cn/Article/details/gtbkwztlri.html

[T04] Kotlin：空安全
来源：http://dali.redwolf501.top/Article/details/gtqctkvqpt.html

val n: String? = null;  n?.length
来源：http://dali.aibaodan.cn/Article/details/gtynoaovpr.html

[T05] Kotlin：when 表达式
来源：http://dali.meibo888.top/Article/details/gtwtzqpevn.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ydzc1.top/Article/details/gtrzgqkbuz.html

[T06] Kotlin：集合映射
来源：http://dali.ybcxt.top/Article/details/gtbbcxzikj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.nwbrower.top/Article/details/gtbcxmetby.html

[T07] Kotlin：集合过滤
来源：http://dali.tianlin.xyz/Article/details/gtfumqrlyl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cdnleiting.top/Article/details/gtyumninjd.html

[T08] Kotlin：数据类
来源：http://dali.cqqwz.cn/Article/details/gtbftluegk.html

data class User(val name: String, val age: Int)
来源：http://dali.zhoulong.xyz/Article/details/gtrziiblos.html

[T09] Kotlin：扩展函数
来源：http://dali.daria6918.cn/Article/details/gtesvlcjbj.html

fun String.exclaim() = this + "!"
来源：http://dali.zhoulong.xyz/Article/details/gtcywmasye.html

[T10] Kotlin：默认参数
来源：http://dali.birdmap.top/Article/details/gtzcliavmv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hfpthk.cn/Article/details/gtvhtbkhlv.html

[T11] Kotlin：协程
来源：http://dali.shzxlz.cn/Article/details/gtgqtfnwqc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.andypj.xyz/Article/details/gtkachtgid.html

[T12] Kotlin：解构声明
来源：http://dali.meibo888.top/Article/details/gtbljfoohu.html

val (a, b) = Pair(1, 2)
来源：http://dali.chenlongwang.top/Article/details/gtejycdsjm.html

[T13] Kotlin：只读 Map
来源：http://dali.zhoulong.xyz/Article/details/gtpqootdpw.html

val m = mapOf("a" to 1)
来源：http://dali.yj202588.top/Article/details/gtzepfrrwz.html

[T14] Kotlin：循环
来源：http://dali.chenjidiqi.icu/Article/details/gtcaxjfjnp.html

for (i in 1..10) println(i)
来源：http://dali.hywenlv.cn/Article/details/gtduayoxal.html

[T15] Kotlin：接口
来源：http://dali.shuidangran.top/Article/details/gtmctexzdm.html

interface Shape { fun area(): Double }
来源：http://dali.yangfankeji.com/Article/details/gtbglyqmwr.html

[T16] Swift：Hello World
来源：http://dali.ivvv.top/Article/details/gttappwurn.html

print("Hello")
来源：http://dali.sxryk.cn/Article/details/gtjwyczove.html

[T17] Swift：变量与常量
来源：http://dali.jqgufenzy.top/Article/details/gtmamwcerp.html

var a = 1;  let b = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gttmcrflvq.html

[T18] Swift：字符串插值
来源：http://dali.cashguo.top/Article/details/gtbplvrgqz.html

"值: \(b)"
来源：http://dali.zhengqikj.top/Article/details/gtrmtzsdkf.html

[T19] Swift：可选绑定
来源：http://dali.hongshengwenyu.top/Article/details/gtwvcgnjzs.html

if let n = opt { print(n) }
来源：http://dali.sufxvd.cn/Article/details/gtsrutxmqp.html

[T20] Swift：数组操作
来源：http://dali.feifeiyinyue.top/Article/details/gtdlhobiyz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hammf.cn/Article/details/gttnenaeqv.html

[T21] Swift：遍历
来源：http://dali.zhengqikj.top/Article/details/gtnqjuccfi.html

for x in a { print(x) }
来源：http://dali.c1oappe.top/Article/details/gtozwccczv.html

[T22] Swift：字典
来源：http://dali.wangshuangyany.cn/Article/details/gtinfhcvbw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.chenjidiqi.icu/Article/details/gtkkspydqw.html

[T23] Swift：函数
来源：http://dali.sweek.top/Article/details/gtsjokdehz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.aizwys.cn/Article/details/gtoacsqcwx.html

[T24] Swift：闭包
来源：http://dali.hfpthk.cn/Article/details/gthcnefsvr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gtanqtqqxk.html

[T25] Swift：结构体
来源：http://dali.hnxiangtu.top/Article/details/gtmhvjcznl.html

struct P { var x: Int }
来源：http://dali.316326.xyz/Article/details/gtroehjifv.html

[T26] Swift：类与重写
来源：http://dali.bjfxy.top/Article/details/gtbumxdyzu.html

class A: Base { override func f() {} }
来源：http://dali.jinqigufen.top/Article/details/gtpawpaefy.html

[T27] Swift：错误处理
来源：http://dali.yueranfly.top/Article/details/gtdfmcdzqn.html

do { try f() } catch { print(error) }
来源：http://dali.gzhubu.top/Article/details/gtqwwhqjtn.html

[T28] Swift：枚举
来源：http://dali.feifeiyinyue.top/Article/details/gtsisptpue.html

enum Color { case red, green }
来源：http://dali.jiagoushi.top/Article/details/gtbqptryjw.html

[T29] Swift：guard 提前返回
来源：http://dali.pengpengdd.cyou/Article/details/gtrfqtudpn.html

guard let x = opt else { return }
来源：http://dali.yj202588.top/Article/details/gtrjblfzqk.html

[T30] Swift：协议
来源：http://dali.yueranfly.top/Article/details/gtonedinjl.html

protocol Shape { func area() -> Double }
来源：http://dali.haohaochexian.top/Article/details/gtrydhuqrp.html

[T31] Lua：Hello World
来源：http://dali.fengsongda.top/Article/details/gttkglfxbz.html

print("Hello")
来源：http://dali.wangdashe.top/Article/details/gtnygliwdp.html

[T32] Lua：局部变量
来源：http://dali.hysaishi.cn/Article/details/gtsghtrcdj.html

local a = 1
来源：http://dali.kuanghao11.cn/Article/details/gtrprxdzwh.html

[T33] Lua：表（数组）
来源：http://dali.316326.xyz/Article/details/gtyonnxojq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.gotoacloud.top/Article/details/gtwmkjmynf.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gtcbueseps.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yj202588.top/Article/details/gtsyykrahw.html

[T35] Lua：字典表
来源：http://dali.guannengcc.top/Article/details/gtbuujydvj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.mhx1999.top/Article/details/gtkalxraws.html

[T36] Lua：函数
来源：http://dali.pycfn.com/Article/details/gtwilqjdqt.html

function add(a, b) return a + b end
来源：http://dali.jinghuilouyu.cn/Article/details/gtxoqzdewa.html

[T37] Lua：字符串拼接
来源：http://dali.fengsongda.top/Article/details/gtgjzhtvtx.html

"a" .. "b"
来源：http://dali.316326.xyz/Article/details/gtanetsigo.html

[T38] Lua：条件
来源：http://dali.ehwqpu.com/Article/details/gtxtlhdifr.html

if x > 0 then print("正") end
来源：http://dali.snrcjt.cn/Article/details/gtjdaklppz.html

[T39] Lua：模式匹配
来源：http://dali.gogol.net.cn/Article/details/gtxmxfhdtx.html

string.find(s, "%d+")
来源：http://dali.gogol.net.cn/Article/details/gttgvyjozf.html

[T40] Lua：元表
来源：http://dali.hongshengwenyu.top/Article/details/gtysfkrkpa.html

setmetatable({}, { __index = base })
来源：http://dali.hnxiangtu.top/Article/details/gtowqsehpp.html

[T41] Perl：Hello World
来源：http://dali.smart0.xyz/Article/details/gtppkgvsby.html

print "Hello\n";
来源：http://dali.jinqigfzy.top/Article/details/gtnhtjzlee.html

[T42] Perl：变量类型
来源：http://dali.zhengqikj.top/Article/details/gtgnoeatdo.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.birdmap.top/Article/details/gtiwpbtsjd.html

[T43] Perl：字符串插值
来源：http://dali.jinqigfzy.top/Article/details/gtslhvoyrd.html

"值: $a"
来源：http://dali.kuanghao11.cn/Article/details/gtmlcdavmz.html

[T44] Perl：条件
来源：http://dali.shanyushiyangtech.top/Article/details/gtypswlprg.html

if ($a > 0) { print "正"; }
来源：http://dali.bjfxy.top/Article/details/gtkyybkege.html

[T45] Perl：数组遍历
来源：http://dali.dianchejie.cn/Article/details/gtggdpqgnq.html

for my $x (@arr) { print $x; }
来源：http://dali.gaohongyu789.top/Article/details/gtsguedxkk.html

[T46] Perl：哈希操作
来源：http://dali.ybcxt.top/Article/details/gtykknfxoc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jlsjyb.cn/Article/details/gtlzxsmbtm.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gtugzyfwja.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ehwqpu.com/Article/details/gtgnhzilzn.html

[T48] Perl：正则替换
来源：http://dali.0kj1m.cn/Article/details/gtkcudebsn.html

$s =~ s/old/new/g;
来源：http://dali.svipenyu.cn/Article/details/gtcykvuuwt.html

[T49] Perl：函数
来源：http://dali.hnqzz.top/Article/details/gtnmsuobla.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yuanzhike.top/Article/details/gtcksqlfkk.html

[T50] Perl：逐行读文件
来源：http://dali.daxiang520.top/Article/details/gtgiboedco.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.cashguo.top/Article/details/gtoitmfgaf.html


<!-- 参考信息 -->