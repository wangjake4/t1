代发 wailian999

cmd > out.log 2>&1
来源：http://dali.zhiwuduotai.top/Article/details/gtsuddbriu.html

[R40] 追加写日志
来源：http://dali.jinqigfzy.top/Article/details/gtyrrzqvel.html

echo "log" >> out.log
来源：http://dali.bjfxy.top/Article/details/gtwhdlfhbo.html

[R41] 丢弃输出
来源：http://dali.gzhubu.top/Article/details/gtyvlfdkac.html

cmd >/dev/null 2>&1
来源：http://dali.ybcxt.top/Article/details/gtiuyagmoa.html

[R42] 输入重定向
来源：http://dali.xinyue.icu/Article/details/gtpyrlaarz.html

wc -l < a.txt
来源：http://dali.gotoacloud.top/Article/details/gtrmwgwnuq.html

[R43] 按名字查找文件
来源：http://dali.iojbl.cn/Article/details/gtphmbwzpd.html

find . -name "*.log" -type f
来源：http://dali.chenjidiqi.icu/Article/details/gtimjicawk.html

[R44] 按修改时间查找
来源：http://dali.guannengcc.top/Article/details/gttxpusqrg.html

find . -mtime -7 -type f
来源：http://dali.redwolf501.top/Article/details/gtcbuuatqh.html

[R45] 批量删除
来源：http://dali.guannengcc.top/Article/details/gtkuzuojhq.html

find . -name "*.tmp" -delete
来源：http://dali.fengsongda.top/Article/details/gtixkqmnkd.html

[R46] 递归替换文件内容
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxxzdskrn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.guannengcc.top/Article/details/gtpexxjscj.html

[R47] sed 单行替换
来源：http://dali.aizwys.cn/Article/details/gtusvskzkn.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xziqi.cn/Article/details/gthxmtnfmb.html

[R48] awk 取指定列
来源：http://dali.yj20258888.top/Article/details/gtnetltzwr.html

awk '{print $1, $3}' a.txt
来源：http://dali.chenzaomai.com/Article/details/gtzblezuex.html

[R49] awk 带条件
来源：http://dali.jinghuilouyu.cn/Article/details/gtxdknskof.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hnxiangtu.top/Article/details/gtcbnceoya.html

[R50] awk 求和
来源：http://dali.shanyushiyangtech.top/Article/details/gtmovzkfwv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.redwolf501.top/Article/details/gtgiosvxut.html

[R51] 排序去重取前几
来源：http://dali.dashuyun.cn/Article/details/gttusttbcy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cqqwz.cn/Article/details/gtdoossjmr.html

[R52] 统计行数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrmewjxfc.html

wc -l a.txt
来源：http://dali.xinyue.icu/Article/details/gtvufwdzjx.html

[R53] 查看文件头与实时尾
来源：http://dali.dashuyun.cn/Article/details/gtkkyjlypw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.guowangkeji.top/Article/details/gtoegmfipo.html

[R54] 比较两个文件
来源：http://dali.wangdashe.top/Article/details/gtrdvnarwg.html

diff a.txt b.txt
来源：http://dali.wangdashe.top/Article/details/gtbvaekfti.html

[R55] 压缩与解压
来源：http://dali.316326.xyz/Article/details/gtuuwqsaba.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.wangdashe.top/Article/details/gtiizpicho.html

[R56] 远程拷贝
来源：http://dali.cashguo.top/Article/details/gtlsablctb.html

scp file user@host:/path/
来源：http://dali.gotoacloud.top/Article/details/gtjgskhjvv.html

[R57] 远程执行命令
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkztwfbgp.html

ssh user@host 'uptime'
来源：http://dali.yvedp.cn/Article/details/gtnxpzivhv.html

[R58] 下载文件
来源：http://dali.jinqigfzy.top/Article/details/gtelbktubb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgeyvgazg.html

[R59] 发 POST JSON
来源：http://dali.kuanghao11.cn/Article/details/gtaafqedqk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.birdmap.top/Article/details/gtzqpazkao.html

[R60] 只看 HTTP 状态码
来源：http://dali.cdnleiting.top/Article/details/gtizpvjucm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.pengpengdd.cyou/Article/details/gtojcmiach.html

[R61] 磁盘占用
来源：http://dali.zycfv.cn/Article/details/gtrjagkcbw.html

df -h;  du -sh *
来源：http://dali.xinyue.icu/Article/details/gtspocfnvb.html

[R62] 找最占空间的文件
来源：http://dali.mhx1999.top/Article/details/gtcfnsqeus.html

du -ah . | sort -rh | head -10
来源：http://dali.chenlongwang.top/Article/details/gtqfqpjfcx.html

[R63] 内存与进程
来源：http://dali.chenjidiqi.icu/Article/details/gthakwvxdh.html

free -h;  ps aux | grep nginx
来源：http://dali.ivvv.top/Article/details/gteqszaumm.html

[R64] 结束进程
来源：http://dali.svipenyu.cn/Article/details/gtwdzwteli.html

kill -9 $(pgrep -f app.py)
来源：http://dali.feifeiyinyue.top/Article/details/gtvneioxcm.html

[R65] 查看端口占用
来源：http://dali.chenjidiqi.icu/Article/details/gthwlkdlrk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.birdmap.top/Article/details/gtzgcoyfoc.html

[R66] 定时任务
来源：http://dali.ppjwa.cn/Article/details/gthfbhwqjb.html

crontab -e;  crontab -l
来源：http://dali.xziqi.cn/Article/details/gtbyszsujv.html

[R67] 生成随机十六进制串
来源：http://dali.cheryme.top/Article/details/gtuyckoozw.html

openssl rand -hex 16
来源：http://dali.haohaochexian.top/Article/details/gtjuzyvcqx.html

[R68] 计算文件校验值
来源：http://dali.jinghuilouyu.cn/Article/details/gtyvzzcdvu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.kuanghao11.cn/Article/details/gtiomyvqjl.html

[R69] 生成随机密码
来源：http://dali.0kj1m.cn/Article/details/gtoxqqpuym.html

head -c 16 /dev/urandom | base64
来源：http://dali.nwbrower.top/Article/details/gtccecogyl.html

[R70] 时间戳与互转
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqqhkizti.html

date +%s;  date -d @1700000000
来源：http://dali.xuetiantiany.cn/Article/details/gtgxdebilj.html

[R71] 日期格式化
来源：http://dali.hnqzz.top/Article/details/gtusgkwbsu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ppjwa.cn/Article/details/gtccnzhvtz.html

[R72] 等待端口就绪
来源：http://dali.xuanzx.com/Article/details/gtbuwhbdsu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.aibaodan.cn/Article/details/gtsqplcozb.html

[R73] 分割大日志
来源：http://dali.hammf.cn/Article/details/gtkrimsihl.html

split -l 1000 big.log part_
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtknxwwjyt.html

[R74] 批量重命名
来源：http://dali.zhongyouzk.top/Article/details/gttcdhvhbf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.tian-w.cn/Article/details/gtkxknange.html

[R75] 导出环境变量
来源：http://dali.tianlin.xyz/Article/details/gtxemjpjns.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ivvv.top/Article/details/gtfzrkrhyx.html

[R76] 使用临时文件
来源：http://dali.yangfankeji.com/Article/details/gtdnhnatth.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.bjfxy.top/Article/details/gtrdroikax.html

[R77] 读取用户输入
来源：http://dali.bjfxy.top/Article/details/gtqhsmqcab.html

read -rp "请输入: " ans
来源：http://dali.hfpthk.cn/Article/details/gtrnwlggrf.html

[R78] 交互式菜单
来源：http://dali.bjfxy.top/Article/details/gtbrbfrogs.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yuxming.cn/Article/details/gtewlgxjxa.html

[R79] 解析命令行选项
来源：http://dali.yuanzhike.top/Article/details/gtygymvdwi.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.wangshuangyany.cn/Article/details/gtdefyuwds.html

[R80] 查看脚本执行耗时
来源：http://dali.gogol.net.cn/Article/details/gtmfjivcho.html

time ./run.sh
来源：http://dali.316326.xyz/Article/details/gtxkoxtxvj.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtkiixfqmz.html

S. C / C++ 专题
来源：http://dali.sysykeji.top/Article/details/gtoheinkfx.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtzbzcgmcm.html

[S01] C：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtapcrrntc.html

#include <stdio.h>
来源：http://dali.yvedp.cn/Article/details/gtsabhmchi.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.nwbrower.top/Article/details/gtourgjywf.html

[S02] C：变量与格式化输出
来源：http://dali.cashguo.top/Article/details/gtkqgbqbii.html

int a = 10; printf("%d\n", a);
来源：http://dali.kuanghao11.cn/Article/details/gtkiayxcwy.html

[S03] C：读入整数
来源：http://dali.yj202588.top/Article/details/gtrqowlwbd.html

int x; scanf("%d", &x);
来源：http://dali.shangyingyoupin.top/Article/details/gtpsehxutw.html

[S04] C：字符串复制
来源：http://dali.andypj.xyz/Article/details/gtngkmyldd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cashguo.top/Article/details/gtyltegfrw.html

[S05] C：字符串长度
来源：http://dali.cashguo.top/Article/details/gtsbiccltz.html

strlen(s)
来源：http://dali.aizwys.cn/Article/details/gtxsmgkthc.html

[S06] C：字符串比较
来源：http://dali.c1oappe.top/Article/details/gtmlyzznts.html

strcmp(a, b) == 0
来源：http://dali.iojbl.cn/Article/details/gtsfcjdydg.html

[S07] C：数组遍历求和
来源：http://dali.havefunace.top/Article/details/gtcfvcdhfc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jianghu66.top/Article/details/gtpptmxwqr.html

[S08] C：动态内存分配与释放
来源：http://dali.xinyue.icu/Article/details/gtnesfddgl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.aibaodan.cn/Article/details/gtzyncwlki.html

[S09] C：结构体定义与初始化
来源：http://dali.316326.xyz/Article/details/gtufsckxid.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yvedp.cn/Article/details/gtzyukjlhb.html

[S10] C：指针与解引用
来源：http://dali.zhaomingkeji.xyz/Article/details/gthpvasbav.html

int *p = &a;  *p = 5;
来源：http://dali.xuanzx.com/Article/details/gtjpvftytj.html

[S11] C：逐行读文件
来源：http://dali.fzhhl.top/Article/details/gtweuyyeoo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ydzc1.top/Article/details/gtvzjphpwf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhongyouzk.top/Article/details/gtojjssqob.html

fclose(f);
来源：http://dali.havefunace.top/Article/details/gtxvptuokt.html

[S12] C：写文件
来源：http://dali.ivvv.top/Article/details/gtrfnmrmvt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ybcxt.top/Article/details/gtwezgvyoc.html

[S13] C：宏定义
来源：http://dali.yueranfly.top/Article/details/gtmhocjbua.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.fengsongda.top/Article/details/gtiozvycmb.html

[S14] C：枚举
来源：http://dali.ehwqpu.com/Article/details/gtdmfpcjvv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hnqzz.top/Article/details/gtlcywojax.html

[S15] C：类型转换
来源：http://dali.shangyingyoupin.top/Article/details/gtfffjiwtb.html

(double) a / b
来源：http://dali.sysykeji.top/Article/details/gtexlrtbez.html

[S16] C：位操作置位
来源：http://dali.snrcjt.cn/Article/details/gtakmnjwpu.html

x |= (1 << 3);
来源：http://dali.jinqigufen.top/Article/details/gteuzeijzv.html

[S17] C：安全拼接字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtughdffjw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.meibo888.top/Article/details/gthllqtobu.html

[S18] C：命令行参数
来源：http://dali.jinqigufen.top/Article/details/gtslsmrlyc.html

int main(int argc, char **argv)
来源：http://dali.yanxiufei.cn/Article/details/gtzfmgvxtm.html

[S19] C：快速排序
来源：http://dali.tanke756.top/Article/details/gtdwwysoyk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.gogol.net.cn/Article/details/gtpkjddhqc.html

[S20] C：二分查找
来源：http://dali.chenjidiqi.icu/Article/details/gthudjuvkl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.daxiang520.top/Article/details/gtdxwelnge.html

[S21] C：字符类别判断
来源：http://dali.hnxiangtu.top/Article/details/gtoevwmapc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.fzhhl.top/Article/details/gtngwejaum.html

[S22] C：字符串转数字
来源：http://dali.gaohongyu789.top/Article/details/gtxmodqlip.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hywenlv.cn/Article/details/gtkppucdbu.html

[S23] C：随机数
来源：http://dali.jinqigfzy.top/Article/details/gtxcbgzhhh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jianghu66.top/Article/details/gtjzwmhjic.html

[S24] C：获取本地时间
来源：http://dali.wangdashe.top/Article/details/gtlkfgmlcc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinghuilouyu.cn/Article/details/gtcsvjwmeh.html

[S25] C：内存拷贝
来源：http://dali.shuidangran.top/Article/details/gthhwradic.html

memcpy(dst, src, n);
来源：http://dali.ydzc1.top/Article/details/gtithohrtf.html

[S26] C：内存清零
来源：http://dali.zycfv.cn/Article/details/gtzygvobxd.html

memset(a, 0, sizeof a);
来源：http://dali.jinqigfzy.top/Article/details/gtqjgkfwge.html

[S27] C：定义常量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtephekzzt.html

const double PI = 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gtmfaamyay.html

[S28] C：静态变量
来源：http://dali.hongshengwenyu.top/Article/details/gthxqqxafz.html

static int counter = 0;
来源：http://dali.sweek.top/Article/details/gtfliacrtd.html

[S29] C：变参函数
来源：http://dali.chenjidiqi.icu/Article/details/gtksmiyqcf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.chenzaomai.com/Article/details/gtqxblgvxx.html

[S30] C：头文件保护
来源：http://dali.hywenlv.cn/Article/details/gtdudlwjga.html

#ifndef X_H
来源：http://dali.zycfv.cn/Article/details/gtpvlmikac.html

#define X_H
来源：http://dali.chenjidiqi.icu/Article/details/gteaqsyrpo.html

#endif
来源：http://dali.jlsjyb.cn/Article/details/gteapotgfc.html

[S31] C++：Hello World
来源：http://dali.yangfankeji.com/Article/details/gtpphzbyfd.html

#include <iostream>
来源：http://dali.svipenyu.cn/Article/details/gtonlcunou.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hnxiangtu.top/Article/details/gtjyopnmrc.html

[S32] C++：字符串
来源：http://dali.316326.xyz/Article/details/gtlkfqkuea.html

std::string s = "hi";  s += "!";
来源：http://dali.xylfe.cn/Article/details/gtczdhqbsb.html

[S33] C++：vector 增删
来源：http://dali.redwolf501.top/Article/details/gtnqsaajtv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jqgfzy.top/Article/details/gtucpkgjdr.html

[S34] C++：遍历 vector
来源：http://dali.cheryme.top/Article/details/gtxfwytrib.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ivvv.top/Article/details/gtilqxgmex.html

[S35] C++：map
来源：http://dali.birdmap.top/Article/details/gtlabxxdip.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hfpthk.cn/Article/details/gthauqifuu.html

[S36] C++：unordered_map
来源：http://dali.sufxvd.cn/Article/details/gtdzcmynhg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.bjfxy.top/Article/details/gtztzmtzkg.html

[S37] C++：set
来源：http://dali.guannengcc.top/Article/details/gtqnfpsmrm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ybcxt.top/Article/details/gthnqgxzni.html

[S38] C++：排序
来源：http://dali.ivvv.top/Article/details/gtyrrzhksb.html

std::sort(v.begin(), v.end());
来源：http://dali.haohaochexian.top/Article/details/gtjvdhkave.html

[S39] C++：自定义比较器排序
来源：http://dali.zhoulong.xyz/Article/details/gtrozxpcmt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hfpthk.cn/Article/details/gtzcqfosjk.html

[S40] C++：查找元素
来源：http://dali.hysaishi.cn/Article/details/gtwyklgtan.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yanxiufei.cn/Article/details/gtsjdsedcp.html

[S41] C++：类与构造函数
来源：http://dali.cdnleiting.top/Article/details/gtuyzfydvd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hysaishi.cn/Article/details/gttiglrxjc.html

[S42] C++：继承与虚函数
来源：http://dali.chenjidiqi.icu/Article/details/gtuzyqavgn.html

class B : public Base { public: void f() override {} };
来源：http://dali.cdnleiting.top/Article/details/gtalhehcwv.html

[S43] C++：智能指针
来源：http://dali.iojbl.cn/Article/details/gtsgplkbus.html

auto p = std::make_unique<int>(5);
来源：http://dali.snrcjt.cn/Article/details/gtgpdkocdj.html

[S44] C++：引用传参
来源：http://dali.cashguo.top/Article/details/gtythxivjf.html

void inc(int &x) { ++x; }
来源：http://dali.ydzc1.top/Article/details/gtptikdnyc.html

[S45] C++：lambda
来源：http://dali.zhengqikj.top/Article/details/gtshyzjhsj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gotoacloud.top/Article/details/gtpzchulmn.html

[S46] C++：函数模板
来源：http://dali.cashguo.top/Article/details/gtopjufiqt.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jyoumei.cn/Article/details/gtjmddgnkh.html

[S47] C++：结构化绑定遍历
来源：http://dali.0kj1m.cn/Article/details/gtkeqzxwnf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinqigfzy.top/Article/details/gtufeijqtm.html

[S48] C++：逐行读文件
来源：http://dali.yonumen.top/Article/details/gtdqtaxjjq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gogol.net.cn/Article/details/gtrjmrxjno.html

while (std::getline(in, line)) { }
来源：http://dali.xziqi.cn/Article/details/gtmsmpjvna.html

[S49] C++：写文件
来源：http://dali.xinyue.icu/Article/details/gtculltvhe.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zycfv.cn/Article/details/gtefnbhwfb.html

[S50] C++：格式化数字
来源：http://dali.havefunace.top/Article/details/gtizhctblf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gtyuzpjdzl.html

[S51] C++：显式类型转换
来源：http://dali.zhiwuduotai.top/Article/details/gtkyszjoqs.html

static_cast<double>(a) / b
来源：http://dali.dianchejie.cn/Article/details/gtywlycavx.html

[S52] C++：const 与 noexcept
来源：http://dali.jinqigufen.top/Article/details/gtmrkoebsv.html

int size() const noexcept { return n_; }
来源：http://dali.cqqwz.cn/Article/details/gtbzxelpml.html

[S53] C++：移动语义
来源：http://dali.shzxlz.cn/Article/details/gtclqxjwgh.html

std::vector<int> w = std::move(v);
来源：http://dali.gaohongyu789.top/Article/details/gteanjpmgh.html

[S54] C++：异常处理
来源：http://dali.yueranfly.top/Article/details/gtypkwfzwc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.316326.xyz/Article/details/gtlodgxyil.html

[S55] C++：结构化绑定
来源：http://dali.hysaishi.cn/Article/details/gtsqdjfomb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.kuanghao11.cn/Article/details/gtkqprvpjs.html

[S56] C++：optional
来源：http://dali.dashuyun.cn/Article/details/gttnymdtdd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hnxiangtu.top/Article/details/gtmitgamdf.html

[S57] C++：编译期常量
来源：http://dali.yj20258888.top/Article/details/gtqshrznnc.html

constexpr int N = 10;
来源：http://dali.yvedp.cn/Article/details/gttrjilfom.html

[S58] C++：命名空间
来源：http://dali.yj20258.top/Article/details/gtgciwwvyu.html

namespace ns { int f() { return 1; } }
来源：http://dali.andypj.xyz/Article/details/gtbksqxdxv.html

[S59] C++：静态断言
来源：http://dali.meibo888.top/Article/details/gtandevqim.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xylfe.cn/Article/details/gtmxmqpgrd.html

[S60] C++：遍历并删除元素
来源：http://dali.vqdsnc.cn/Article/details/gtwhxbqkoq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhiwuduotai.top/Article/details/gtefdbwjpr.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtnpuuuqlc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.dashuyun.cn/Article/details/gtdsrkkoax.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtrjumtaqy.html

[T01] Kotlin：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpaosvizk.html

println("Hello")
来源：http://dali.iojbl.cn/Article/details/gtjdsmxzdy.html

[T02] Kotlin：变量
来源：http://dali.ydzc1.top/Article/details/gtjjwzmuhx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.mhx1999.top/Article/details/gtqfklssyc.html

[T03] Kotlin：字符串模板
来源：http://dali.zhoulong.xyz/Article/details/gttlsmimzz.html

"值: $b"
来源：http://dali.zycfv.cn/Article/details/gtvdhelypn.html

[T04] Kotlin：空安全
来源：http://dali.kuanghao11.cn/Article/details/gtcsyyjbon.html

val n: String? = null;  n?.length
来源：http://dali.shzxlz.cn/Article/details/gtdazedaxi.html

[T05] Kotlin：when 表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gtvjcsufpr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sufxvd.cn/Article/details/gtqwtypnou.html

[T06] Kotlin：集合映射
来源：http://dali.yangfankeji.com/Article/details/gtdfgscvzq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xinyue.icu/Article/details/gtzjiyywgj.html

[T07] Kotlin：集合过滤
来源：http://dali.jlsjyb.cn/Article/details/gtustxkqdo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yj20258888.top/Article/details/gtteunmuxx.html

[T08] Kotlin：数据类
来源：http://dali.hysaishi.cn/Article/details/gtpezpkpgd.html

data class User(val name: String, val age: Int)
来源：http://dali.hnqzz.top/Article/details/gtoiuqcugk.html

[T09] Kotlin：扩展函数
来源：http://dali.haohaochexian.top/Article/details/gtiqinlekt.html

fun String.exclaim() = this + "!"
来源：http://dali.jinghuilouyu.cn/Article/details/gtvhimxruz.html

[T10] Kotlin：默认参数
来源：http://dali.tanke756.top/Article/details/gtiyqvrpme.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jianghu66.top/Article/details/gtplfstzqi.html

[T11] Kotlin：协程
来源：http://dali.tianlin.xyz/Article/details/gtabpbjqfo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ybcxt.top/Article/details/gtkerdeths.html

[T12] Kotlin：解构声明
来源：http://dali.mhx1999.top/Article/details/gtslzojzkq.html

val (a, b) = Pair(1, 2)
来源：http://dali.iojbl.cn/Article/details/gtdozbnmru.html

[T13] Kotlin：只读 Map
来源：http://dali.cucudq.cn/Article/details/gthzcdbtxa.html

val m = mapOf("a" to 1)
来源：http://dali.hnqzz.top/Article/details/gtcjhelqgc.html

[T14] Kotlin：循环
来源：http://dali.gogol.net.cn/Article/details/gtjoakedei.html

for (i in 1..10) println(i)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtavmnfzfe.html

[T15] Kotlin：接口
来源：http://dali.bjfxy.top/Article/details/gtxeonbaex.html

interface Shape { fun area(): Double }
来源：http://dali.wangshuangyany.cn/Article/details/gthnjyepdc.html

[T16] Swift：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtikgkahuv.html

print("Hello")
来源：http://dali.zhongyouzk.top/Article/details/gtlzovuenf.html

[T17] Swift：变量与常量
来源：http://dali.yongpay.top/Article/details/gtzcpaolsp.html

var a = 1;  let b = 2
来源：http://dali.jqgfzy.top/Article/details/gthrzflbuk.html

[T18] Swift：字符串插值
来源：http://dali.chenzaomai.com/Article/details/gtjhpigdbx.html

"值: \(b)"
来源：http://dali.kuanghao11.cn/Article/details/gtvbaaadts.html

[T19] Swift：可选绑定
来源：http://dali.yuanzhike.top/Article/details/gtskxfmbio.html

if let n = opt { print(n) }
来源：http://dali.hongshengwenyu.top/Article/details/gtiibgwuam.html

[T20] Swift：数组操作
来源：http://dali.mhx1999.top/Article/details/gtulzyuthn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.meibo888.top/Article/details/gtigpllzfk.html

[T21] Swift：遍历
来源：http://dali.aibaodan.cn/Article/details/gtqrzjygjq.html

for x in a { print(x) }
来源：http://dali.dashuyun.cn/Article/details/gtcyqmjsue.html

[T22] Swift：字典
来源：http://dali.chenzaomai.com/Article/details/gtweacotim.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.guannengcc.top/Article/details/gtickkgkdx.html

[T23] Swift：函数
来源：http://dali.yonumen.top/Article/details/gtgtkfptpq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhongyouzk.top/Article/details/gtnueoqewy.html

[T24] Swift：闭包
来源：http://dali.gogol.net.cn/Article/details/gtgswulrqv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.dashuyun.cn/Article/details/gtcmjsesqz.html

[T25] Swift：结构体
来源：http://dali.sxryk.cn/Article/details/gtpkhwpdhd.html

struct P { var x: Int }
来源：http://dali.guowangkeji.top/Article/details/gtabimdhdo.html

[T26] Swift：类与重写
来源：http://dali.zhixingplan.top/Article/details/gtoakncoso.html

class A: Base { override func f() {} }
来源：http://dali.cdnleiting.top/Article/details/gtnkrsswvw.html

[T27] Swift：错误处理
来源：http://dali.jqgfzy.top/Article/details/gtrbimnvzi.html

do { try f() } catch { print(error) }
来源：http://dali.zdqjudy.top/Article/details/gtqdjrmyrs.html

[T28] Swift：枚举
来源：http://dali.yanxiufei.cn/Article/details/gtlmvztkfb.html

enum Color { case red, green }
来源：http://dali.yonumen.top/Article/details/gthncjusjv.html

[T29] Swift：guard 提前返回
来源：http://dali.meibo888.top/Article/details/gtjgwedlkv.html

guard let x = opt else { return }
来源：http://dali.yongpay.top/Article/details/gtljtnrlni.html

[T30] Swift：协议
来源：http://dali.jinyuanbaomall.cn/Article/details/gttrbylbjo.html

protocol Shape { func area() -> Double }
来源：http://dali.0kj1m.cn/Article/details/gtdenbrxir.html

[T31] Lua：Hello World
来源：http://dali.xylfe.cn/Article/details/gtfyacgjrr.html

print("Hello")
来源：http://dali.sxryk.cn/Article/details/gtfgicwrah.html

[T32] Lua：局部变量
来源：http://dali.gzhubu.top/Article/details/gtaepdyvvb.html

local a = 1
来源：http://dali.yueranfly.top/Article/details/gtufmtjnzm.html

[T33] Lua：表（数组）
来源：http://dali.shangyingyoupin.top/Article/details/gtwsaiclmu.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cdnleiting.top/Article/details/gtkoabojip.html

[T34] Lua：遍历表
来源：http://dali.haohaochexian.top/Article/details/gtpmxljjpe.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jianghu66.top/Article/details/gtlyiovdhj.html

[T35] Lua：字典表
来源：http://dali.zhoulong.xyz/Article/details/gtjnarnfre.html

local d = { a = 1 };  d.b = 2
来源：http://dali.kuanghao11.cn/Article/details/gtgytftrch.html

[T36] Lua：函数
来源：http://dali.snrcjt.cn/Article/details/gtucrokwiw.html

function add(a, b) return a + b end
来源：http://dali.redwolf501.top/Article/details/gtndbgdkmo.html

[T37] Lua：字符串拼接
来源：http://dali.shangyingyoupin.top/Article/details/gthvmqiqrv.html

"a" .. "b"
来源：http://dali.vqdsnc.cn/Article/details/gtleolrwvs.html

[T38] Lua：条件
来源：http://dali.pengpengdd.cyou/Article/details/gtemvpsalt.html

if x > 0 then print("正") end
来源：http://dali.daria6918.cn/Article/details/gthojjvwnh.html

[T39] Lua：模式匹配
来源：http://dali.xylfe.cn/Article/details/gtraiubvzi.html

string.find(s, "%d+")
来源：http://dali.zhoulong.xyz/Article/details/gtdvcxhysw.html

[T40] Lua：元表
来源：http://dali.chenlongwang.top/Article/details/gtljruaamw.html

setmetatable({}, { __index = base })
来源：http://dali.hysaishi.cn/Article/details/gthnhfmbpf.html

[T41] Perl：Hello World
来源：http://dali.bjfxy.top/Article/details/gtphcfnngb.html

print "Hello\n";
来源：http://dali.hongshengwenyu.top/Article/details/gtyoldqimq.html

[T42] Perl：变量类型
来源：http://dali.wangdashe.top/Article/details/gtikrfbncc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xinyue.icu/Article/details/gtsllrblll.html


<!-- 参考信息 -->