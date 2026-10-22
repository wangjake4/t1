代发 wailian999

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ybcxt.top/Article/details/gt2vlsncojy.html

[R50] awk 求和
来源：http://dali.chenlongwang.top/Article/details/gt2ecjljbbk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.daxiang520.top/Article/details/gt2wrebvupk.html

[R51] 排序去重取前几
来源：http://dali.cucudq.cn/Article/details/gt2twxkoxyj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhiwuduotai.top/Article/details/gt2ejmwuvbj.html

[R52] 统计行数
来源：http://dali.daria6918.cn/Article/details/gt2iqooccxf.html

wc -l a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rhrgnkpo.html

[R53] 查看文件头与实时尾
来源：http://dali.tanke756.top/Article/details/gt2mxazsusi.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yongpay.top/Article/details/gt2ebqwtova.html

[R54] 比较两个文件
来源：http://dali.cqqwz.cn/Article/details/gt2skvfiles.html

diff a.txt b.txt
来源：http://dali.yvedp.cn/Article/details/gt2bcydazsm.html

[R55] 压缩与解压
来源：http://dali.smart0.xyz/Article/details/gt2gvrcshcq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jianghu66.top/Article/details/gt2nnphcgut.html

[R56] 远程拷贝
来源：http://dali.yuanzhike.top/Article/details/gt2qlolgmby.html

scp file user@host:/path/
来源：http://dali.jiagoushi.top/Article/details/gt2fxmjcwrt.html

[R57] 远程执行命令
来源：http://dali.hnxiangtu.top/Article/details/gt2jpaqgfpa.html

ssh user@host 'uptime'
来源：http://dali.jinghuilouyu.cn/Article/details/gt2smcpekpe.html

[R58] 下载文件
来源：http://dali.andypj.xyz/Article/details/gt2kskyifml.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jnfigbkg.html

[R59] 发 POST JSON
来源：http://dali.cdnleiting.top/Article/details/gt2wupejzpd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.snrcjt.cn/Article/details/gt2piarlfrr.html

[R60] 只看 HTTP 状态码
来源：http://dali.havefunace.top/Article/details/gt2lcvdjelf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yongpay.top/Article/details/gt2uylulblo.html

[R61] 磁盘占用
来源：http://dali.yj20258888.top/Article/details/gt2ecwatkfd.html

df -h;  du -sh *
来源：http://dali.zdqjudy.top/Article/details/gt2okfjqfcu.html

[R62] 找最占空间的文件
来源：http://dali.ybcxt.top/Article/details/gt2vstxskmd.html

du -ah . | sort -rh | head -10
来源：http://dali.ppjwa.cn/Article/details/gt2fgsymmlj.html

[R63] 内存与进程
来源：http://dali.zhengqikj.top/Article/details/gt2yzkzxjll.html

free -h;  ps aux | grep nginx
来源：http://dali.vqdsnc.cn/Article/details/gt2pojtpbdg.html

[R64] 结束进程
来源：http://dali.fengsongda.top/Article/details/gt2gstijgnc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yongpay.top/Article/details/gt2ighhzpdg.html

[R65] 查看端口占用
来源：http://dali.gaohongyu789.top/Article/details/gt2aljyyljk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shanyushiyangtech.top/Article/details/gt2decgrvpk.html

[R66] 定时任务
来源：http://dali.xuetiantiany.cn/Article/details/gt2aliefztq.html

crontab -e;  crontab -l
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tjybsxmk.html

[R67] 生成随机十六进制串
来源：http://dali.jqgfzy.top/Article/details/gt2gfyxbmpp.html

openssl rand -hex 16
来源：http://dali.hnqzz.top/Article/details/gt2ymbervsk.html

[R68] 计算文件校验值
来源：http://dali.hammf.cn/Article/details/gt2grsofdno.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yongpay.top/Article/details/gt2tsbrvfrt.html

[R69] 生成随机密码
来源：http://dali.pengpengdd.cyou/Article/details/gt2rtktlvfr.html

head -c 16 /dev/urandom | base64
来源：http://dali.zycfv.cn/Article/details/gt2zxtbwtsf.html

[R70] 时间戳与互转
来源：http://dali.316326.xyz/Article/details/gt2xmqwegmg.html

date +%s;  date -d @1700000000
来源：http://dali.0kj1m.cn/Article/details/gt2yqvrdjhg.html

[R71] 日期格式化
来源：http://dali.jianghu66.top/Article/details/gt2oxguymuu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tppjcevy.html

[R72] 等待端口就绪
来源：http://dali.aibaodan.cn/Article/details/gt2umhamqbw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.pycfn.com/Article/details/gt2mouqogoy.html

[R73] 分割大日志
来源：http://dali.yonumen.top/Article/details/gt2rtorsvzb.html

split -l 1000 big.log part_
来源：http://dali.xylfe.cn/Article/details/gt2qtipihuf.html

[R74] 批量重命名
来源：http://dali.xuetiantiany.cn/Article/details/gt2xawvyngs.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sweek.top/Article/details/gt2fowjrbot.html

[R75] 导出环境变量
来源：http://dali.hnxiangtu.top/Article/details/gt2tzlyqqaz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.havefunace.top/Article/details/gt2ixwvgbdh.html

[R76] 使用临时文件
来源：http://dali.daxiang520.top/Article/details/gt2kzszqkcj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.nwbrower.top/Article/details/gt2gxcoevka.html

[R77] 读取用户输入
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tlpjdfxf.html

read -rp "请输入: " ans
来源：http://dali.smart0.xyz/Article/details/gt2uynrcqet.html

[R78] 交互式菜单
来源：http://dali.pengpengdd.cyou/Article/details/gt2dlaytbsw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.tian-w.cn/Article/details/gt2fgpwihen.html

[R79] 解析命令行选项
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bfcnknqe.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.dianchejie.cn/Article/details/gt2rpnlahyd.html

[R80] 查看脚本执行耗时
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dyajfigg.html

time ./run.sh
来源：http://dali.feifeiyinyue.top/Article/details/gt2bgkhkybd.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2nqlcgbtg.html

S. C / C++ 专题
来源：http://dali.birdmap.top/Article/details/gt2digolnqr.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vusqaycy.html

[S01] C：Hello World
来源：http://dali.yangfankeji.com/Article/details/gt2unoyglhb.html

#include <stdio.h>
来源：http://dali.shuidangran.top/Article/details/gt2atdjsnsn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.c1oappe.top/Article/details/gt2yhlwafpc.html

[S02] C：变量与格式化输出
来源：http://dali.cqqwz.cn/Article/details/gt2ycksmnyt.html

int a = 10; printf("%d\n", a);
来源：http://dali.cashguo.top/Article/details/gt2gutpspaw.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2enzfigiw.html

int x; scanf("%d", &x);
来源：http://dali.zhixingplan.top/Article/details/gt2lkejcxmc.html

[S04] C：字符串复制
来源：http://dali.jinqigfzy.top/Article/details/gt2nwejjufq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cqqwz.cn/Article/details/gt2loyqrtae.html

[S05] C：字符串长度
来源：http://dali.zhiwuduotai.top/Article/details/gt2dcobiarq.html

strlen(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ycdqknpr.html

[S06] C：字符串比较
来源：http://dali.daxiang520.top/Article/details/gt2mwpxdqri.html

strcmp(a, b) == 0
来源：http://dali.xziqi.cn/Article/details/gt2gsmwihlz.html

[S07] C：数组遍历求和
来源：http://dali.ivvv.top/Article/details/gt2skoxdgmq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2osckxbcj.html

[S08] C：动态内存分配与释放
来源：http://dali.dashuyun.cn/Article/details/gt2oppdnynb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinqigufen.top/Article/details/gt2dwkqnvar.html

[S09] C：结构体定义与初始化
来源：http://dali.wangshuangyany.cn/Article/details/gt2yfwsnkmc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gotoacloud.top/Article/details/gt2vlfnvhlp.html

[S10] C：指针与解引用
来源：http://dali.nanxinkj.top/Article/details/gt2efnysrhl.html

int *p = &a;  *p = 5;
来源：http://dali.zycfv.cn/Article/details/gt2qtdujvkm.html

[S11] C：逐行读文件
来源：http://dali.shuidangran.top/Article/details/gt2qsrbgdml.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.redwolf501.top/Article/details/gt2jdzzslih.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xuetiantiany.cn/Article/details/gt2zojqfcyc.html

fclose(f);
来源：http://dali.chenjidiqi.icu/Article/details/gt2fwsmwkno.html

[S12] C：写文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2hwciyhpq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyrtjmnf.html

[S13] C：宏定义
来源：http://dali.hnxiangtu.top/Article/details/gt2xnfeebjy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jyoumei.cn/Article/details/gt2hktarkeb.html

[S14] C：枚举
来源：http://dali.feifeiyinyue.top/Article/details/gt2rxhmsfmt.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2byizrkwy.html

[S15] C：类型转换
来源：http://dali.xziqi.cn/Article/details/gt2hhpvcvtw.html

(double) a / b
来源：http://dali.ivvv.top/Article/details/gt2tnhqxicw.html

[S16] C：位操作置位
来源：http://dali.xylfe.cn/Article/details/gt2lgtmyioe.html

x |= (1 << 3);
来源：http://dali.jianghu66.top/Article/details/gt2vkomwmul.html

[S17] C：安全拼接字符串
来源：http://dali.yonumen.top/Article/details/gt2xtjjmcxz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.dianchejie.cn/Article/details/gt2hsvzvfgy.html

[S18] C：命令行参数
来源：http://dali.zdqjudy.top/Article/details/gt2mxuhjtmm.html

int main(int argc, char **argv)
来源：http://dali.vqdsnc.cn/Article/details/gt2nzhlcjkl.html

[S19] C：快速排序
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xwfexnhh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shzxlz.cn/Article/details/gt2dovchtyk.html

[S20] C：二分查找
来源：http://dali.shuidangran.top/Article/details/gt2nbveunkr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tanke756.top/Article/details/gt2ysbzpszu.html

[S21] C：字符类别判断
来源：http://dali.ydzc1.top/Article/details/gt2wkekbwgk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.meibo888.top/Article/details/gt2mrxumkre.html

[S22] C：字符串转数字
来源：http://dali.fzhhl.top/Article/details/gt2zqbiaktz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yj20258888.top/Article/details/gt2yxsckmec.html

[S23] C：随机数
来源：http://dali.feifeiyinyue.top/Article/details/gt2qrujuabd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wumosyra.html

[S24] C：获取本地时间
来源：http://dali.9152youxi.cn/Article/details/gt2ukkwzsmq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.tian-w.cn/Article/details/gt2fleriuci.html

[S25] C：内存拷贝
来源：http://dali.yj202588.top/Article/details/gt2cbbstgsh.html

memcpy(dst, src, n);
来源：http://dali.9152youxi.cn/Article/details/gt2oiqmnxhk.html

[S26] C：内存清零
来源：http://dali.c1oappe.top/Article/details/gt2pkpufnko.html

memset(a, 0, sizeof a);
来源：http://dali.sweek.top/Article/details/gt2adzilvrb.html

[S27] C：定义常量
来源：http://dali.jlsjyb.cn/Article/details/gt2sxysiysv.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmutscvg.html

[S28] C：静态变量
来源：http://dali.yj20258888.top/Article/details/gt2coqzrjpt.html

static int counter = 0;
来源：http://dali.havefunace.top/Article/details/gt2fzmfuwct.html

[S29] C：变参函数
来源：http://dali.iojbl.cn/Article/details/gt2sttczobu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.wangshuangyany.cn/Article/details/gt2xezuwuhj.html

[S30] C：头文件保护
来源：http://dali.nanxinkj.top/Article/details/gt2gahnzhmq.html

#ifndef X_H
来源：http://dali.guowangkeji.top/Article/details/gt2gkvkpxjq.html

#define X_H
来源：http://dali.yvedp.cn/Article/details/gt2nsroqeqv.html

#endif
来源：http://dali.andypj.xyz/Article/details/gt2avjxtdxy.html

[S31] C++：Hello World
来源：http://dali.yongpay.top/Article/details/gt2jkrwrfrw.html

#include <iostream>
来源：http://dali.hnxiangtu.top/Article/details/gt2lqymeawl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ehwqpu.com/Article/details/gt2oprxzbzw.html

[S32] C++：字符串
来源：http://dali.pycfn.com/Article/details/gt2lkmeyzls.html

std::string s = "hi";  s += "!";
来源：http://dali.jianghu66.top/Article/details/gt2rftiwjeb.html

[S33] C++：vector 增删
来源：http://dali.yuanzhike.top/Article/details/gt2yilnlxuw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xcmpquts.html

[S34] C++：遍历 vector
来源：http://dali.haohaochexian.top/Article/details/gt2ekafnssm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhengqikj.top/Article/details/gt2rmqkffmk.html

[S35] C++：map
来源：http://dali.jqgufenzy.top/Article/details/gt2uuhhqeqd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.daria6918.cn/Article/details/gt2luwynyuc.html

[S36] C++：unordered_map
来源：http://dali.guowangkeji.top/Article/details/gt2bjzchlbn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gt2gyxxctgs.html

[S37] C++：set
来源：http://dali.xinyue.icu/Article/details/gt2mjekqszd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jyoumei.cn/Article/details/gt2bkaenagu.html

[S38] C++：排序
来源：http://dali.birdmap.top/Article/details/gt2qdtqijwf.html

std::sort(v.begin(), v.end());
来源：http://dali.jlsjyb.cn/Article/details/gt2pibiuuqq.html

[S39] C++：自定义比较器排序
来源：http://dali.yj20258.top/Article/details/gt2zvtliovq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.pengpengdd.cyou/Article/details/gt2dubkeltg.html

[S40] C++：查找元素
来源：http://dali.gaohongyu789.top/Article/details/gt2tzzoceei.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinqigfzy.top/Article/details/gt2lcmszxhb.html

[S41] C++：类与构造函数
来源：http://dali.yuxming.cn/Article/details/gt2fgldggdd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sufxvd.cn/Article/details/gt2bztmseym.html

[S42] C++：继承与虚函数
来源：http://dali.yanxiufei.cn/Article/details/gt2cpbesvwr.html

class B : public Base { public: void f() override {} };
来源：http://dali.cqqwz.cn/Article/details/gt2tgysufnk.html

[S43] C++：智能指针
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rntrdwrc.html

auto p = std::make_unique<int>(5);
来源：http://dali.pengpengdd.cyou/Article/details/gt2xlvmamfs.html

[S44] C++：引用传参
来源：http://dali.cucudq.cn/Article/details/gt2qvpnabvv.html

void inc(int &x) { ++x; }
来源：http://dali.gzhubu.top/Article/details/gt2kqmlseqi.html

[S45] C++：lambda
来源：http://dali.yanxiufei.cn/Article/details/gt2xojmnfpy.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jlsjyb.cn/Article/details/gt2fkopwlcp.html

[S46] C++：函数模板
来源：http://dali.0kj1m.cn/Article/details/gt2cqemqeto.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.tianlin.xyz/Article/details/gt2nvqntdlv.html

[S47] C++：结构化绑定遍历
来源：http://dali.ehwqpu.com/Article/details/gt2akalisxv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.dianchejie.cn/Article/details/gt2xitobuow.html

[S48] C++：逐行读文件
来源：http://dali.havefunace.top/Article/details/gt2qhhrjxnq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hywenlv.cn/Article/details/gt2etqaymhz.html

while (std::getline(in, line)) { }
来源：http://dali.xziqi.cn/Article/details/gt2hemtnuvi.html

[S49] C++：写文件
来源：http://dali.vqdsnc.cn/Article/details/gt2dulndazg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.guannengcc.top/Article/details/gt2feeftrqk.html

[S50] C++：格式化数字
来源：http://dali.c1oappe.top/Article/details/gt2xjkwntdn.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hskogvjn.html

[S51] C++：显式类型转换
来源：http://dali.jiagoushi.top/Article/details/gt2ijjsxzke.html

static_cast<double>(a) / b
来源：http://dali.yuxming.cn/Article/details/gt2cthsrdln.html

[S52] C++：const 与 noexcept
来源：http://dali.tianlin.xyz/Article/details/gt2fbdognco.html

int size() const noexcept { return n_; }
来源：http://dali.yj20258.top/Article/details/gt2vytniiox.html

[S53] C++：移动语义
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fiidmwho.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjavhxcz.html

[S54] C++：异常处理
来源：http://dali.xuetiantiany.cn/Article/details/gt2wzkjxqpl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.316326.xyz/Article/details/gt2yypewwia.html

[S55] C++：结构化绑定
来源：http://dali.aizwys.cn/Article/details/gt2pltclqze.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2owccjnjc.html

[S56] C++：optional
来源：http://dali.birdmap.top/Article/details/gt2wepotuoq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2rdmhoufy.html

[S57] C++：编译期常量
来源：http://dali.andypj.xyz/Article/details/gt2utcqxttk.html

constexpr int N = 10;
来源：http://dali.ydzc1.top/Article/details/gt2ikugkmtx.html

[S58] C++：命名空间
来源：http://dali.jiagoushi.top/Article/details/gt2wgkzgphq.html

namespace ns { int f() { return 1; } }
来源：http://dali.havefunace.top/Article/details/gt2hgipibab.html

[S59] C++：静态断言
来源：http://dali.cqqwz.cn/Article/details/gt2fdzmmebw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xylfe.cn/Article/details/gt2qkbsbrko.html

[S60] C++：遍历并删除元素
来源：http://dali.jinqigufen.top/Article/details/gt2trmewlms.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.guowangkeji.top/Article/details/gt2qfiajduy.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2xxiznvyl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xylfe.cn/Article/details/gt2glaxbirt.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2lfbdmwcr.html

[T01] Kotlin：Hello World
来源：http://dali.hfpthk.cn/Article/details/gt2lvplnufn.html

println("Hello")
来源：http://dali.sysykeji.top/Article/details/gt2kwnjraap.html

[T02] Kotlin：变量
来源：http://dali.gzhubu.top/Article/details/gt2cvjhctxh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.quarkkingdee.top/Article/details/gt2exgshesg.html

[T03] Kotlin：字符串模板
来源：http://dali.zhengqikj.top/Article/details/gt2enyndjtp.html

"值: $b"
来源：http://dali.ydzc1.top/Article/details/gt2kyttuivx.html

[T04] Kotlin：空安全
来源：http://dali.tianlin.xyz/Article/details/gt2ghvfrnpe.html

val n: String? = null;  n?.length
来源：http://dali.yj20258.top/Article/details/gt2wblrxoba.html

[T05] Kotlin：when 表达式
来源：http://dali.fengsongda.top/Article/details/gt2tiwzqxod.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hnqzz.top/Article/details/gt2gfmorzvc.html

[T06] Kotlin：集合映射
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2skophssz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.smart0.xyz/Article/details/gt2dzckobfb.html

[T07] Kotlin：集合过滤
来源：http://dali.shzxlz.cn/Article/details/gt2hyijfzkl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xinyue.icu/Article/details/gt2siidltvo.html

[T08] Kotlin：数据类
来源：http://dali.0kj1m.cn/Article/details/gt2cdroyrae.html

data class User(val name: String, val age: Int)
来源：http://dali.tanke756.top/Article/details/gt2uslcwqrb.html

[T09] Kotlin：扩展函数
来源：http://dali.yj202588.top/Article/details/gt2dcsxqnts.html

fun String.exclaim() = this + "!"
来源：http://dali.daria6918.cn/Article/details/gt2kndtrghg.html

[T10] Kotlin：默认参数
来源：http://dali.ybcxt.top/Article/details/gt2uwcjanbh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.wangshuangyany.cn/Article/details/gt2yevurpga.html

[T11] Kotlin：协程
来源：http://dali.hammf.cn/Article/details/gt2ucyxfqmh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.snrcjt.cn/Article/details/gt2wrwlyomd.html

[T12] Kotlin：解构声明
来源：http://dali.yongpay.top/Article/details/gt2uftdaeqk.html

val (a, b) = Pair(1, 2)
来源：http://dali.ivvv.top/Article/details/gt2iuziavol.html

[T13] Kotlin：只读 Map
来源：http://dali.jqgufenzy.top/Article/details/gt2zomrsrqf.html

val m = mapOf("a" to 1)
来源：http://dali.zdqjudy.top/Article/details/gt2ecavmfyn.html

[T14] Kotlin：循环
来源：http://dali.hammf.cn/Article/details/gt2yymffuyd.html

for (i in 1..10) println(i)
来源：http://dali.jinqigfzy.top/Article/details/gt2plxomitz.html

[T15] Kotlin：接口
来源：http://dali.yueranfly.top/Article/details/gt2hlckewcf.html

interface Shape { fun area(): Double }
来源：http://dali.ybcxt.top/Article/details/gt2ttqtmxox.html

[T16] Swift：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gt2chkvqvxn.html

print("Hello")
来源：http://dali.shzxlz.cn/Article/details/gt2pugvlwch.html

[T17] Swift：变量与常量
来源：http://dali.yanxiufei.cn/Article/details/gt2sjbvbnyz.html

var a = 1;  let b = 2
来源：http://dali.jianghu66.top/Article/details/gt2mvnkdesp.html

[T18] Swift：字符串插值
来源：http://dali.hnqzz.top/Article/details/gt2goapmxuu.html

"值: \(b)"
来源：http://dali.kuanghao11.cn/Article/details/gt2gdgmxcky.html

[T19] Swift：可选绑定
来源：http://dali.sufxvd.cn/Article/details/gt2ejkfyfrl.html

if let n = opt { print(n) }
来源：http://dali.hammf.cn/Article/details/gt2uzzvinzt.html

[T20] Swift：数组操作
来源：http://dali.jyoumei.cn/Article/details/gt2szlszbma.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xziqi.cn/Article/details/gt2dxozznar.html

[T21] Swift：遍历
来源：http://dali.nanxuanxn.top/Article/details/gt2lsgviobc.html

for x in a { print(x) }
来源：http://dali.dashuyun.cn/Article/details/gt2naujlpep.html

[T22] Swift：字典
来源：http://dali.tianlin.xyz/Article/details/gt2gbwrfhlt.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhixingplan.top/Article/details/gt2hedwcgdy.html

[T23] Swift：函数
来源：http://dali.jianghu66.top/Article/details/gt2fwtwucfx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.tianlin.xyz/Article/details/gt2mteknppv.html

[T24] Swift：闭包
来源：http://dali.hammf.cn/Article/details/gt2uubzmpoj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.gaohongyu789.top/Article/details/gt2htwoxmtt.html

[T25] Swift：结构体
来源：http://dali.tianlin.xyz/Article/details/gt2cstiwgmo.html

struct P { var x: Int }
来源：http://dali.aizwys.cn/Article/details/gt2telcadkr.html

[T26] Swift：类与重写
来源：http://dali.hongshengwenyu.top/Article/details/gt2jzalzzft.html

class A: Base { override func f() {} }
来源：http://dali.hywenlv.cn/Article/details/gt2hwzbzdxf.html

[T27] Swift：错误处理
来源：http://dali.zhongyouzk.top/Article/details/gt2vxfyckui.html

do { try f() } catch { print(error) }
来源：http://dali.nanxinkj.top/Article/details/gt2yvlbllex.html

[T28] Swift：枚举
来源：http://dali.mhx1999.top/Article/details/gt2wfplrtmt.html

enum Color { case red, green }
来源：http://dali.hongshengwenyu.top/Article/details/gt2bonzapfw.html

[T29] Swift：guard 提前返回
来源：http://dali.jinqigfzy.top/Article/details/gt2coiqvgrr.html

guard let x = opt else { return }
来源：http://dali.sweek.top/Article/details/gt2imbugfgf.html

[T30] Swift：协议
来源：http://dali.yueranfly.top/Article/details/gt2iofttaan.html

protocol Shape { func area() -> Double }
来源：http://dali.kuanghao11.cn/Article/details/gt2sjnnryjc.html

[T31] Lua：Hello World
来源：http://dali.redwolf501.top/Article/details/gt2zialqjoq.html

print("Hello")
来源：http://dali.mhx1999.top/Article/details/gt2iywtgzpv.html

[T32] Lua：局部变量
来源：http://dali.yj20258888.top/Article/details/gt2mrivuoxq.html

local a = 1
来源：http://dali.daxiang520.top/Article/details/gt2zwjyfwye.html

[T33] Lua：表（数组）
来源：http://dali.meibo888.top/Article/details/gt2hgzovxvm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yj202588.top/Article/details/gt2eihihjqe.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2dkcgziwc.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yanxiufei.cn/Article/details/gt2nvdiztkr.html

[T35] Lua：字典表
来源：http://dali.jinqigfzy.top/Article/details/gt2snecgaed.html

local d = { a = 1 };  d.b = 2
来源：http://dali.birdmap.top/Article/details/gt2synrkbxa.html

[T36] Lua：函数
来源：http://dali.sweek.top/Article/details/gt2msfacrvp.html

function add(a, b) return a + b end
来源：http://dali.birdmap.top/Article/details/gt2pubpsdfw.html

[T37] Lua：字符串拼接
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mnwntjdl.html

"a" .. "b"
来源：http://dali.quarkkingdee.top/Article/details/gt2mdrrlypv.html

[T38] Lua：条件
来源：http://dali.jiagoushi.top/Article/details/gt2tjsdwrkm.html

if x > 0 then print("正") end
来源：http://dali.xylfe.cn/Article/details/gt2ibtvcrfx.html

[T39] Lua：模式匹配
来源：http://dali.hnxiangtu.top/Article/details/gt2ouiuwxmz.html

string.find(s, "%d+")
来源：http://dali.daxiang520.top/Article/details/gt2iwdpwdqq.html

[T40] Lua：元表
来源：http://dali.snrcjt.cn/Article/details/gt2gkicpjwt.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2eovsqqvf.html

[T41] Perl：Hello World
来源：http://dali.c1oappe.top/Article/details/gt2ajeqxyhr.html

print "Hello\n";
来源：http://dali.chenzaomai.com/Article/details/gt2hyrporuo.html

[T42] Perl：变量类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2jiwglfhs.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hywenlv.cn/Article/details/gt2nnuptftk.html

[T43] Perl：字符串插值
来源：http://dali.shangyingyoupin.top/Article/details/gt2zlowmvuc.html

"值: $a"
来源：http://dali.zhoulong.xyz/Article/details/gt2mtcswijk.html

[T44] Perl：条件
来源：http://dali.tian-w.cn/Article/details/gt2gguihrmm.html

if ($a > 0) { print "正"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2vcdudfam.html

[T45] Perl：数组遍历
来源：http://dali.yonumen.top/Article/details/gt2agpgekff.html

for my $x (@arr) { print $x; }
来源：http://dali.aizwys.cn/Article/details/gt2wzchfyko.html

[T46] Perl：哈希操作
来源：http://dali.cucudq.cn/Article/details/gt2onicwigy.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2tukihfpz.html

[T47] Perl：正则捕获
来源：http://dali.tanke756.top/Article/details/gt2jinvskhl.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.sweek.top/Article/details/gt2wskgcixn.html

[T48] Perl：正则替换
来源：http://dali.hfpthk.cn/Article/details/gt2zmovpmwd.html

$s =~ s/old/new/g;
来源：http://dali.ydzc1.top/Article/details/gt2grseudfm.html

[T49] Perl：函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hcdlhyjg.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2alrmmdeg.html

[T50] Perl：逐行读文件
来源：http://dali.yuxming.cn/Article/details/gt2mfnejqdc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.dianchejie.cn/Article/details/gt2pcpzgmtd.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yj20258888.top/Article/details/gt2acprjkuo.html

[T51] Scala：Hello World
来源：http://dali.xziqi.cn/Article/details/gt2pedwdfey.html

println("Hello")
来源：http://dali.hammf.cn/Article/details/gt2sbvyjsaq.html

[T52] Scala：变量
来源：http://dali.yj20258.top/Article/details/gt2pydgrikq.html


<!-- 参考信息 -->