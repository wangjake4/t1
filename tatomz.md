代发 wailian999

find . -name "*.log" -type f
来源：http://dali.jinqigfzy.top/Article/details/gtzppqkeso.html

[R44] 按修改时间查找
来源：http://dali.shangyingyoupin.top/Article/details/gtmjqzuozx.html

find . -mtime -7 -type f
来源：http://dali.tianlin.xyz/Article/details/gttaattlxu.html

[R45] 批量删除
来源：http://dali.ybcxt.top/Article/details/gtauueleqx.html

find . -name "*.tmp" -delete
来源：http://dali.smart0.xyz/Article/details/gtuhwbjchd.html

[R46] 递归替换文件内容
来源：http://dali.zhengqikj.top/Article/details/gtjvjimxqx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xuanzx.com/Article/details/gtuznaiiwb.html

[R47] sed 单行替换
来源：http://dali.ydzc1.top/Article/details/gtlfnqazgz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ivvv.top/Article/details/gtedgaxuck.html

[R48] awk 取指定列
来源：http://dali.gzhubu.top/Article/details/gtwoivpsxe.html

awk '{print $1, $3}' a.txt
来源：http://dali.yuanzhike.top/Article/details/gtgzyketry.html

[R49] awk 带条件
来源：http://dali.vqdsnc.cn/Article/details/gtyvkfepkm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.guowangkeji.top/Article/details/gtiufjoann.html

[R50] awk 求和
来源：http://dali.iojbl.cn/Article/details/gtcvtjqpcc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.chenzaomai.com/Article/details/gtwhbpejhq.html

[R51] 排序去重取前几
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrahwtvvg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jianghu66.top/Article/details/gtzfqjetqe.html

[R52] 统计行数
来源：http://dali.jyoumei.cn/Article/details/gtktvmfqpa.html

wc -l a.txt
来源：http://dali.kuanghao11.cn/Article/details/gtbxkrmrcq.html

[R53] 查看文件头与实时尾
来源：http://dali.andypj.xyz/Article/details/gtwsmgsfqn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jiagoushi.top/Article/details/gtctygyjco.html

[R54] 比较两个文件
来源：http://dali.tanke756.top/Article/details/gtfddeoqxp.html

diff a.txt b.txt
来源：http://dali.0kj1m.cn/Article/details/gtfuejpjkn.html

[R55] 压缩与解压
来源：http://dali.sysykeji.top/Article/details/gtsfbnegyc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.pengpengdd.cyou/Article/details/gteurpmyzh.html

[R56] 远程拷贝
来源：http://dali.tian-w.cn/Article/details/gtxyxeotqd.html

scp file user@host:/path/
来源：http://dali.feifeiyinyue.top/Article/details/gtztlgxqtp.html

[R57] 远程执行命令
来源：http://dali.hywenlv.cn/Article/details/gtvgyfitzv.html

ssh user@host 'uptime'
来源：http://dali.gotoacloud.top/Article/details/gtuoqrvzoq.html

[R58] 下载文件
来源：http://dali.yj202588.top/Article/details/gtyrtptfxa.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.nwbrower.top/Article/details/gtauvfpdip.html

[R59] 发 POST JSON
来源：http://dali.jiagoushi.top/Article/details/gtuwtzgtso.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gogol.net.cn/Article/details/gtxzbbhelt.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxnpfesip.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.snrcjt.cn/Article/details/gtnmwcrsbf.html

[R61] 磁盘占用
来源：http://dali.xuanzx.com/Article/details/gtigeuejuh.html

df -h;  du -sh *
来源：http://dali.fengsongda.top/Article/details/gtrgllgbka.html

[R62] 找最占空间的文件
来源：http://dali.hammf.cn/Article/details/gtpdelqrkl.html

du -ah . | sort -rh | head -10
来源：http://dali.andypj.xyz/Article/details/gtkhufcjll.html

[R63] 内存与进程
来源：http://dali.birdmap.top/Article/details/gthznqjxkf.html

free -h;  ps aux | grep nginx
来源：http://dali.ehwqpu.com/Article/details/gtqhxofnvf.html

[R64] 结束进程
来源：http://dali.jinqigfzy.top/Article/details/gtnbgjsfku.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gthzttptpe.html

[R65] 查看端口占用
来源：http://dali.sweek.top/Article/details/gtbxtoxkml.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sysykeji.top/Article/details/gtediuisku.html

[R66] 定时任务
来源：http://dali.zhoulong.xyz/Article/details/gtecqzwdyn.html

crontab -e;  crontab -l
来源：http://dali.ybcxt.top/Article/details/gtjtrpjkzx.html

[R67] 生成随机十六进制串
来源：http://dali.zhiwuduotai.top/Article/details/gtdftfelmx.html

openssl rand -hex 16
来源：http://dali.chenlongwang.top/Article/details/gtwoosendw.html

[R68] 计算文件校验值
来源：http://dali.xziqi.cn/Article/details/gthnvmmkea.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jyoumei.cn/Article/details/gtqbouzipj.html

[R69] 生成随机密码
来源：http://dali.xylfe.cn/Article/details/gthrtaglmb.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinqigufen.top/Article/details/gttdzbybky.html

[R70] 时间戳与互转
来源：http://dali.316326.xyz/Article/details/gtrutlrzib.html

date +%s;  date -d @1700000000
来源：http://dali.jyoumei.cn/Article/details/gtkqvgivuj.html

[R71] 日期格式化
来源：http://dali.ivvv.top/Article/details/gtgnxrpjjy.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cheryme.top/Article/details/gtwnhxxdbh.html

[R72] 等待端口就绪
来源：http://dali.fzhhl.top/Article/details/gthtvzxkew.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.haohaochexian.top/Article/details/gtrxdwdkni.html

[R73] 分割大日志
来源：http://dali.gogol.net.cn/Article/details/gtrqatgocz.html

split -l 1000 big.log part_
来源：http://dali.jlsjyb.cn/Article/details/gtveavckxp.html

[R74] 批量重命名
来源：http://dali.haohaochexian.top/Article/details/gtlvgpzjuu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sweek.top/Article/details/gtrhvyjuwq.html

[R75] 导出环境变量
来源：http://dali.bjfxy.top/Article/details/gtbgghltwq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sysykeji.top/Article/details/gtsulalxsp.html

[R76] 使用临时文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnjqmxmex.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.aibaodan.cn/Article/details/gtweybjnby.html

[R77] 读取用户输入
来源：http://dali.xuanzx.com/Article/details/gtgaidvkst.html

read -rp "请输入: " ans
来源：http://dali.cheryme.top/Article/details/gtdcnatiuo.html

[R78] 交互式菜单
来源：http://dali.jqgufenzy.top/Article/details/gtkachjmpd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sxryk.cn/Article/details/gthtisuxxu.html

[R79] 解析命令行选项
来源：http://dali.birdmap.top/Article/details/gtzynrywfh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.chenjidiqi.icu/Article/details/gtbfzzbjvx.html

[R80] 查看脚本执行耗时
来源：http://dali.aizwys.cn/Article/details/gtomkcxuij.html

time ./run.sh
来源：http://dali.mhx1999.top/Article/details/gtknapyxwx.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtutlookui.html

S. C / C++ 专题
来源：http://dali.zycfv.cn/Article/details/gtoojsoffm.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtiotkqnur.html

[S01] C：Hello World
来源：http://dali.redwolf501.top/Article/details/gtgvgulkbc.html

#include <stdio.h>
来源：http://dali.nwbrower.top/Article/details/gtrvxukfyq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.nanxinkj.top/Article/details/gtmuxdlcsv.html

[S02] C：变量与格式化输出
来源：http://dali.guowangkeji.top/Article/details/gtytukhdax.html

int a = 10; printf("%d\n", a);
来源：http://dali.yongpay.top/Article/details/gtruvgitrx.html

[S03] C：读入整数
来源：http://dali.jyoumei.cn/Article/details/gtelzxxowm.html

int x; scanf("%d", &x);
来源：http://dali.smart0.xyz/Article/details/gtgxvragbu.html

[S04] C：字符串复制
来源：http://dali.hongshengwenyu.top/Article/details/gtvbvdpnir.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.guannengcc.top/Article/details/gttqxuyjhp.html

[S05] C：字符串长度
来源：http://dali.tianlin.xyz/Article/details/gtrmwwlmtq.html

strlen(s)
来源：http://dali.tianlin.xyz/Article/details/gtxgmpauar.html

[S06] C：字符串比较
来源：http://dali.zhixingplan.top/Article/details/gttngytvqe.html

strcmp(a, b) == 0
来源：http://dali.guannengcc.top/Article/details/gtetwnltdw.html

[S07] C：数组遍历求和
来源：http://dali.bjfxy.top/Article/details/gtsnuvnavw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.feifeiyinyue.top/Article/details/gtjapezzhi.html

[S08] C：动态内存分配与释放
来源：http://dali.sufxvd.cn/Article/details/gtndttjrii.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.feifeiyinyue.top/Article/details/gtpsnnglxt.html

[S09] C：结构体定义与初始化
来源：http://dali.mhx1999.top/Article/details/gtlbtyhvhh.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yanxiufei.cn/Article/details/gtecyfyrso.html

[S10] C：指针与解引用
来源：http://dali.shanyushiyangtech.top/Article/details/gtkraouqte.html

int *p = &a;  *p = 5;
来源：http://dali.sxryk.cn/Article/details/gtjatfzkyt.html

[S11] C：逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gthbxqklwx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.quarkkingdee.top/Article/details/gtjowbzhbl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.havefunace.top/Article/details/gtkexrijkv.html

fclose(f);
来源：http://dali.zhixingplan.top/Article/details/gtrlbfjyog.html

[S12] C：写文件
来源：http://dali.cashguo.top/Article/details/gthszaueha.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhoulong.xyz/Article/details/gtwxesjcrx.html

[S13] C：宏定义
来源：http://dali.ydzc1.top/Article/details/gtogffikuw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yuanzhike.top/Article/details/gtfgjzdpdq.html

[S14] C：枚举
来源：http://dali.hfpthk.cn/Article/details/gtugexalts.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.0kj1m.cn/Article/details/gtxghwpfno.html

[S15] C：类型转换
来源：http://dali.tianlin.xyz/Article/details/gtjgnvnewa.html

(double) a / b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuvzogoef.html

[S16] C：位操作置位
来源：http://dali.yangfankeji.com/Article/details/gtwdyspaai.html

x |= (1 << 3);
来源：http://dali.hysaishi.cn/Article/details/gtjpzphehl.html

[S17] C：安全拼接字符串
来源：http://dali.meibo888.top/Article/details/gtdcycysmw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jianghu66.top/Article/details/gtcpowvnyu.html

[S18] C：命令行参数
来源：http://dali.dianchejie.cn/Article/details/gtcyvgvhcu.html

int main(int argc, char **argv)
来源：http://dali.ppjwa.cn/Article/details/gthsyezncf.html

[S19] C：快速排序
来源：http://dali.nanxuanxn.top/Article/details/gtewbkrdhx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hysaishi.cn/Article/details/gtrgokrwqa.html

[S20] C：二分查找
来源：http://dali.haohaochexian.top/Article/details/gttdetzdjm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.nwbrower.top/Article/details/gtmdvspaki.html

[S21] C：字符类别判断
来源：http://dali.svipenyu.cn/Article/details/gtvdsakpaq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.snrcjt.cn/Article/details/gtxwruubpc.html

[S22] C：字符串转数字
来源：http://dali.snrcjt.cn/Article/details/gtjybpwres.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xinyue.icu/Article/details/gtjrkvvqvo.html

[S23] C：随机数
来源：http://dali.smart0.xyz/Article/details/gtcpfnkjdm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hfpthk.cn/Article/details/gtarciecpr.html

[S24] C：获取本地时间
来源：http://dali.xinyue.icu/Article/details/gtopljbyvn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.nwbrower.top/Article/details/gttfbpxvqy.html

[S25] C：内存拷贝
来源：http://dali.316326.xyz/Article/details/gtduytkhcr.html

memcpy(dst, src, n);
来源：http://dali.zdqjudy.top/Article/details/gtygdpikus.html

[S26] C：内存清零
来源：http://dali.nwbrower.top/Article/details/gtbyavzewe.html

memset(a, 0, sizeof a);
来源：http://dali.shzxlz.cn/Article/details/gtdjzfcvrx.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gtixvxejqw.html

const double PI = 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gtpsqpegkd.html

[S28] C：静态变量
来源：http://dali.9152youxi.cn/Article/details/gtsxvieygh.html

static int counter = 0;
来源：http://dali.hnxiangtu.top/Article/details/gtnyfcroib.html

[S29] C：变参函数
来源：http://dali.yueranfly.top/Article/details/gtvhvkhask.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hywenlv.cn/Article/details/gtizmgmiik.html

[S30] C：头文件保护
来源：http://dali.fzhhl.top/Article/details/gttthebyoh.html

#ifndef X_H
来源：http://dali.zhixingplan.top/Article/details/gtpellfubr.html

#define X_H
来源：http://dali.jianghu66.top/Article/details/gtkijtwicq.html

#endif
来源：http://dali.gogol.net.cn/Article/details/gtmoribrvt.html

[S31] C++：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtwhadsacy.html

#include <iostream>
来源：http://dali.xinyue.icu/Article/details/gtqbycmrpu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.c1oappe.top/Article/details/gtpqtkojqx.html

[S32] C++：字符串
来源：http://dali.daria6918.cn/Article/details/gthgfkthwm.html

std::string s = "hi";  s += "!";
来源：http://dali.hysaishi.cn/Article/details/gtnowqniad.html

[S33] C++：vector 增删
来源：http://dali.fzhhl.top/Article/details/gtiexspjeu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.kuanghao11.cn/Article/details/gtbvklunpc.html

[S34] C++：遍历 vector
来源：http://dali.cashguo.top/Article/details/gtqgiqtdvg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jqgufenzy.top/Article/details/gtlhfoyhvk.html

[S35] C++：map
来源：http://dali.mhx1999.top/Article/details/gtgehlknsj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gtpwerjcbq.html

[S36] C++：unordered_map
来源：http://dali.iojbl.cn/Article/details/gtkuafjfmo.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hywenlv.cn/Article/details/gtqjydezvx.html

[S37] C++：set
来源：http://dali.chenzaomai.com/Article/details/gtfuqcssnb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jiagoushi.top/Article/details/gtdjesbhbs.html

[S38] C++：排序
来源：http://dali.aizwys.cn/Article/details/gtmqndglfo.html

std::sort(v.begin(), v.end());
来源：http://dali.nanxuanxn.top/Article/details/gteckpzrce.html

[S39] C++：自定义比较器排序
来源：http://dali.cashguo.top/Article/details/gtvbetifqj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jyoumei.cn/Article/details/gtqblkppqf.html

[S40] C++：查找元素
来源：http://dali.jqgufenzy.top/Article/details/gtegqmzmcs.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yj20258.top/Article/details/gtipxtznxa.html

[S41] C++：类与构造函数
来源：http://dali.pycfn.com/Article/details/gthfarqpnz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.gogol.net.cn/Article/details/gtmjrytdmb.html

[S42] C++：继承与虚函数
来源：http://dali.xinyue.icu/Article/details/gtykpwghhs.html

class B : public Base { public: void f() override {} };
来源：http://dali.sysykeji.top/Article/details/gtjkuudulh.html

[S43] C++：智能指针
来源：http://dali.sysykeji.top/Article/details/gtsctqkxcs.html

auto p = std::make_unique<int>(5);
来源：http://dali.yj202588.top/Article/details/gtxbhhziok.html

[S44] C++：引用传参
来源：http://dali.dashuyun.cn/Article/details/gtduktmzej.html

void inc(int &x) { ++x; }
来源：http://dali.yonumen.top/Article/details/gtzjpmxpby.html

[S45] C++：lambda
来源：http://dali.svipenyu.cn/Article/details/gthxwybxxn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jyoumei.cn/Article/details/gtifdefxxv.html

[S46] C++：函数模板
来源：http://dali.meibo888.top/Article/details/gtbxgyhgsu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jqgufenzy.top/Article/details/gtvpekuzbk.html

[S47] C++：结构化绑定遍历
来源：http://dali.9152youxi.cn/Article/details/gtvyrslpbn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlwgadgek.html

[S48] C++：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gtvganvvzg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.pycfn.com/Article/details/gtqtzqxixj.html

while (std::getline(in, line)) { }
来源：http://dali.jqgufenzy.top/Article/details/gtzzzayhnb.html

[S49] C++：写文件
来源：http://dali.birdmap.top/Article/details/gtbfkcxubk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yuxming.cn/Article/details/gtgmqxpnoi.html

[S50] C++：格式化数字
来源：http://dali.ehwqpu.com/Article/details/gtsknuzqbm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gthreqoisi.html

[S51] C++：显式类型转换
来源：http://dali.tian-w.cn/Article/details/gtelibuibt.html

static_cast<double>(a) / b
来源：http://dali.chenjidiqi.icu/Article/details/gtxuhfewsx.html

[S52] C++：const 与 noexcept
来源：http://dali.guannengcc.top/Article/details/gttejoujam.html

int size() const noexcept { return n_; }
来源：http://dali.zdqjudy.top/Article/details/gtlccgtpsh.html

[S53] C++：移动语义
来源：http://dali.smart0.xyz/Article/details/gtvgpiixqe.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gtqilqvlib.html

[S54] C++：异常处理
来源：http://dali.fzhhl.top/Article/details/gteztlkrun.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zdqjudy.top/Article/details/gtjvyjfvvw.html

[S55] C++：结构化绑定
来源：http://dali.havefunace.top/Article/details/gtprfxbvjo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.316326.xyz/Article/details/gtqdtofzyi.html

[S56] C++：optional
来源：http://dali.jiagoushi.top/Article/details/gtmfzzbveu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.chenjidiqi.icu/Article/details/gterhtrwnc.html

[S57] C++：编译期常量
来源：http://dali.gzhubu.top/Article/details/gtekqhxnei.html

constexpr int N = 10;
来源：http://dali.xylfe.cn/Article/details/gtxkpakzjg.html

[S58] C++：命名空间
来源：http://dali.jlsjyb.cn/Article/details/gtasfsfvbx.html

namespace ns { int f() { return 1; } }
来源：http://dali.shangyingyoupin.top/Article/details/gtoefxvzff.html

[S59] C++：静态断言
来源：http://dali.9152youxi.cn/Article/details/gtnuyxzsmx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cucudq.cn/Article/details/gtjxutmips.html

[S60] C++：遍历并删除元素
来源：http://dali.jqgfzy.top/Article/details/gtwvjlwtml.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.fengsongda.top/Article/details/gtoclnctmb.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gteqylqkhf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hnxiangtu.top/Article/details/gtcccrsxxl.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtbawhswbh.html

[T01] Kotlin：Hello World
来源：http://dali.jiagoushi.top/Article/details/gttleqfhlq.html

println("Hello")
来源：http://dali.ppjwa.cn/Article/details/gtyjlumwcw.html

[T02] Kotlin：变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtcqzvgwro.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xylfe.cn/Article/details/gtuemhmhpl.html

[T03] Kotlin：字符串模板
来源：http://dali.xuetiantiany.cn/Article/details/gthxrrwlrl.html

"值: $b"
来源：http://dali.ivvv.top/Article/details/gtxefcfehl.html

[T04] Kotlin：空安全
来源：http://dali.cashguo.top/Article/details/gtdwiooqha.html

val n: String? = null;  n?.length
来源：http://dali.andypj.xyz/Article/details/gtuelynsqh.html

[T05] Kotlin：when 表达式
来源：http://dali.xylfe.cn/Article/details/gtkruznunm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ivvv.top/Article/details/gtuqepmkma.html

[T06] Kotlin：集合映射
来源：http://dali.jiagoushi.top/Article/details/gtotmzjvbz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthxwwwlpu.html

[T07] Kotlin：集合过滤
来源：http://dali.xziqi.cn/Article/details/gtlwwfnhcv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.tian-w.cn/Article/details/gtthrxmnre.html

[T08] Kotlin：数据类
来源：http://dali.jinqigufen.top/Article/details/gtpgkzpsvh.html

data class User(val name: String, val age: Int)
来源：http://dali.yj20258888.top/Article/details/gtrhskdfps.html

[T09] Kotlin：扩展函数
来源：http://dali.yongpay.top/Article/details/gtvqsnhgyb.html

fun String.exclaim() = this + "!"
来源：http://dali.jqgufenzy.top/Article/details/gtrbdwlsmq.html

[T10] Kotlin：默认参数
来源：http://dali.yanxiufei.cn/Article/details/gtmbnfqpzp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yvedp.cn/Article/details/gtvdzzgrme.html

[T11] Kotlin：协程
来源：http://dali.gaohongyu789.top/Article/details/gtiabxrwqg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jiagoushi.top/Article/details/gtxrfvnkym.html

[T12] Kotlin：解构声明
来源：http://dali.zhongyouzk.top/Article/details/gtbpknfinv.html

val (a, b) = Pair(1, 2)
来源：http://dali.ppjwa.cn/Article/details/gtfmcqiwvc.html

[T13] Kotlin：只读 Map
来源：http://dali.pycfn.com/Article/details/gtgyoatuqd.html

val m = mapOf("a" to 1)
来源：http://dali.hywenlv.cn/Article/details/gtfkdkdwyh.html

[T14] Kotlin：循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfexukejh.html

for (i in 1..10) println(i)
来源：http://dali.guowangkeji.top/Article/details/gtnjasvyxq.html

[T15] Kotlin：接口
来源：http://dali.xuanzx.com/Article/details/gtqgsocnua.html

interface Shape { fun area(): Double }
来源：http://dali.svipenyu.cn/Article/details/gtjkscgdls.html

[T16] Swift：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtudkyozmi.html

print("Hello")
来源：http://dali.tanke756.top/Article/details/gtppkoymtg.html

[T17] Swift：变量与常量
来源：http://dali.xinyue.icu/Article/details/gtwsqgxpbh.html

var a = 1;  let b = 2
来源：http://dali.yueranfly.top/Article/details/gtveqreiag.html

[T18] Swift：字符串插值
来源：http://dali.zdqjudy.top/Article/details/gtwggxyxcl.html

"值: \(b)"
来源：http://dali.yanxiufei.cn/Article/details/gtupohtzvs.html

[T19] Swift：可选绑定
来源：http://dali.zhixingplan.top/Article/details/gtgtnodtdm.html

if let n = opt { print(n) }
来源：http://dali.tianlin.xyz/Article/details/gtkojjukxv.html

[T20] Swift：数组操作
来源：http://dali.daxiang520.top/Article/details/gtobjcftmb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yangfankeji.com/Article/details/gtqhqmoclp.html

[T21] Swift：遍历
来源：http://dali.hysaishi.cn/Article/details/gtawindegr.html

for x in a { print(x) }
来源：http://dali.shzxlz.cn/Article/details/gtdjyakjgh.html

[T22] Swift：字典
来源：http://dali.zhongyouzk.top/Article/details/gtpvykfgvw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yj20258888.top/Article/details/gttvhmmbgw.html

[T23] Swift：函数
来源：http://dali.jinqigfzy.top/Article/details/gtjbltwdif.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.bjfxy.top/Article/details/gtpdwhnvsl.html

[T24] Swift：闭包
来源：http://dali.kuanghao11.cn/Article/details/gtjimdvwur.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.gotoacloud.top/Article/details/gteabsbkvh.html

[T25] Swift：结构体
来源：http://dali.jinqigfzy.top/Article/details/gtincnasou.html

struct P { var x: Int }
来源：http://dali.iojbl.cn/Article/details/gtdzyarigr.html

[T26] Swift：类与重写
来源：http://dali.zhengqikj.top/Article/details/gtvaxgjqqp.html

class A: Base { override func f() {} }
来源：http://dali.xinyue.icu/Article/details/gtlqxjbcqx.html

[T27] Swift：错误处理
来源：http://dali.ivvv.top/Article/details/gtawinoeie.html

do { try f() } catch { print(error) }
来源：http://dali.hongshengwenyu.top/Article/details/gtffufjivd.html

[T28] Swift：枚举
来源：http://dali.jinqigufen.top/Article/details/gteesphaid.html

enum Color { case red, green }
来源：http://dali.chenjidiqi.icu/Article/details/gtwrvzhxgy.html

[T29] Swift：guard 提前返回
来源：http://dali.zhixingplan.top/Article/details/gtfwwhacjv.html

guard let x = opt else { return }
来源：http://dali.hnxiangtu.top/Article/details/gtmbdavirs.html

[T30] Swift：协议
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcomkznil.html

protocol Shape { func area() -> Double }
来源：http://dali.guowangkeji.top/Article/details/gtrglatkbz.html

[T31] Lua：Hello World
来源：http://dali.cdnleiting.top/Article/details/gtqamarnvh.html

print("Hello")
来源：http://dali.cheryme.top/Article/details/gtieqwwyqs.html

[T32] Lua：局部变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtkuuluuhi.html

local a = 1
来源：http://dali.yuxming.cn/Article/details/gtojgbozdm.html

[T33] Lua：表（数组）
来源：http://dali.gogol.net.cn/Article/details/gtnfbfvxyh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.bjfxy.top/Article/details/gtevldjfqg.html

[T34] Lua：遍历表
来源：http://dali.bjfxy.top/Article/details/gtdcnqbxon.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.gaohongyu789.top/Article/details/gtmjqewsnv.html

[T35] Lua：字典表
来源：http://dali.aizwys.cn/Article/details/gtsomfwwch.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhengqikj.top/Article/details/gthlmjzzss.html

[T36] Lua：函数
来源：http://dali.fengsongda.top/Article/details/gtnizkfqoz.html

function add(a, b) return a + b end
来源：http://dali.xylfe.cn/Article/details/gtvdhsxemt.html

[T37] Lua：字符串拼接
来源：http://dali.shangyingyoupin.top/Article/details/gtzprlecgg.html

"a" .. "b"
来源：http://dali.tianlin.xyz/Article/details/gtvgdjokqu.html

[T38] Lua：条件
来源：http://dali.yj20258.top/Article/details/gtabvvxnzg.html

if x > 0 then print("正") end
来源：http://dali.shanyushiyangtech.top/Article/details/gtwvcuente.html

[T39] Lua：模式匹配
来源：http://dali.vqdsnc.cn/Article/details/gtwenvbkql.html

string.find(s, "%d+")
来源：http://dali.cqqwz.cn/Article/details/gthmgkrgte.html

[T40] Lua：元表
来源：http://dali.jlsjyb.cn/Article/details/gtktxqmutv.html

setmetatable({}, { __index = base })
来源：http://dali.zdqjudy.top/Article/details/gtalmxhver.html

[T41] Perl：Hello World
来源：http://dali.jianghu66.top/Article/details/gtymgrowdi.html

print "Hello\n";
来源：http://dali.tanke756.top/Article/details/gtmoegdaih.html

[T42] Perl：变量类型
来源：http://dali.ppjwa.cn/Article/details/gtcnalnpdg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xinyue.icu/Article/details/gtvdmrstar.html

[T43] Perl：字符串插值
来源：http://dali.0kj1m.cn/Article/details/gtkfmygrks.html

"值: $a"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtehpvttkh.html

[T44] Perl：条件
来源：http://dali.9152youxi.cn/Article/details/gtixbtwxva.html

if ($a > 0) { print "正"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtksexyxyv.html

[T45] Perl：数组遍历
来源：http://dali.tianlin.xyz/Article/details/gtcyhkjwxz.html

for my $x (@arr) { print $x; }
来源：http://dali.ydzc1.top/Article/details/gthwjgsxyd.html

[T46] Perl：哈希操作
来源：http://dali.vqdsnc.cn/Article/details/gtvwdnnzle.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.birdmap.top/Article/details/gtnjswstqo.html


<!-- 参考信息 -->