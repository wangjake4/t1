代发 wailian999

cmd >/dev/null 2>&1
来源：http://dali.iojbl.cn/Article/details/gtmsnxwocn.html

[R42] 输入重定向
来源：http://dali.316326.xyz/Article/details/gtpbxjsymf.html

wc -l < a.txt
来源：http://dali.aizwys.cn/Article/details/gtcdtqgiod.html

[R43] 按名字查找文件
来源：http://dali.chenjidiqi.icu/Article/details/gtdnynetwg.html

find . -name "*.log" -type f
来源：http://dali.hnxiangtu.top/Article/details/gtxhekjbgf.html

[R44] 按修改时间查找
来源：http://dali.ybcxt.top/Article/details/gtysnamvwr.html

find . -mtime -7 -type f
来源：http://dali.yvedp.cn/Article/details/gtxwpcfbrj.html

[R45] 批量删除
来源：http://dali.ybcxt.top/Article/details/gtmutkhwha.html

find . -name "*.tmp" -delete
来源：http://dali.0kj1m.cn/Article/details/gttmarwovd.html

[R46] 递归替换文件内容
来源：http://dali.iojbl.cn/Article/details/gtbbttvndy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.daxiang520.top/Article/details/gtbibizxfc.html

[R47] sed 单行替换
来源：http://dali.yuanzhike.top/Article/details/gtoefktoyv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.guowangkeji.top/Article/details/gtlyyvxgrj.html

[R48] awk 取指定列
来源：http://dali.hammf.cn/Article/details/gtlijeziyp.html

awk '{print $1, $3}' a.txt
来源：http://dali.meibo888.top/Article/details/gtrektudea.html

[R49] awk 带条件
来源：http://dali.c1oappe.top/Article/details/gtjhwjjuxj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.daxiang520.top/Article/details/gtgzuynggl.html

[R50] awk 求和
来源：http://dali.gzhubu.top/Article/details/gtwycyfoxe.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.svipenyu.cn/Article/details/gtpnimnotx.html

[R51] 排序去重取前几
来源：http://dali.snrcjt.cn/Article/details/gtqanqdeoa.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yuanzhike.top/Article/details/gtqtjcyjtb.html

[R52] 统计行数
来源：http://dali.tanke756.top/Article/details/gtglnemmyk.html

wc -l a.txt
来源：http://dali.jyoumei.cn/Article/details/gtgvsmqwuj.html

[R53] 查看文件头与实时尾
来源：http://dali.vqdsnc.cn/Article/details/gtcpfqkhby.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.tian-w.cn/Article/details/gtwhfvtpxu.html

[R54] 比较两个文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtscyppqna.html

diff a.txt b.txt
来源：http://dali.haohaochexian.top/Article/details/gtdgbyfvew.html

[R55] 压缩与解压
来源：http://dali.sweek.top/Article/details/gtynphfbas.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlmuckvss.html

[R56] 远程拷贝
来源：http://dali.quarkkingdee.top/Article/details/gtstvycdxb.html

scp file user@host:/path/
来源：http://dali.fzhhl.top/Article/details/gtthpmfpge.html

[R57] 远程执行命令
来源：http://dali.vqdsnc.cn/Article/details/gtcuiciejx.html

ssh user@host 'uptime'
来源：http://dali.snrcjt.cn/Article/details/gtldwxinhq.html

[R58] 下载文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrkdpmnlr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hammf.cn/Article/details/gtpxisubvl.html

[R59] 发 POST JSON
来源：http://dali.quarkkingdee.top/Article/details/gtriwjwbfi.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.guowangkeji.top/Article/details/gtntxbqksp.html

[R60] 只看 HTTP 状态码
来源：http://dali.zycfv.cn/Article/details/gtwfbubkgr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hywenlv.cn/Article/details/gtunuzcmmj.html

[R61] 磁盘占用
来源：http://dali.haohaochexian.top/Article/details/gtlvueuoxk.html

df -h;  du -sh *
来源：http://dali.ydzc1.top/Article/details/gtugnqjtxw.html

[R62] 找最占空间的文件
来源：http://dali.daria6918.cn/Article/details/gtfqzszkyc.html

du -ah . | sort -rh | head -10
来源：http://dali.cheryme.top/Article/details/gtvdpjbmkx.html

[R63] 内存与进程
来源：http://dali.ehwqpu.com/Article/details/gtqqvrhkqz.html

free -h;  ps aux | grep nginx
来源：http://dali.yonumen.top/Article/details/gtybcajccy.html

[R64] 结束进程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfojltoqj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.daria6918.cn/Article/details/gtomxavafd.html

[R65] 查看端口占用
来源：http://dali.zhengqikj.top/Article/details/gtucehiwut.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shanyushiyangtech.top/Article/details/gtkppvqmyq.html

[R66] 定时任务
来源：http://dali.zhixingplan.top/Article/details/gtupwtjxob.html

crontab -e;  crontab -l
来源：http://dali.dashuyun.cn/Article/details/gtxlrcrzyl.html

[R67] 生成随机十六进制串
来源：http://dali.cashguo.top/Article/details/gtfxheurgt.html

openssl rand -hex 16
来源：http://dali.hywenlv.cn/Article/details/gtccayjdse.html

[R68] 计算文件校验值
来源：http://dali.jiagoushi.top/Article/details/gtzbzfbmsi.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.guowangkeji.top/Article/details/gtwgxzysaq.html

[R69] 生成随机密码
来源：http://dali.yuanzhike.top/Article/details/gtfjduyfyg.html

head -c 16 /dev/urandom | base64
来源：http://dali.hnqzz.top/Article/details/gtedxzjnzv.html

[R70] 时间戳与互转
来源：http://dali.zhengqikj.top/Article/details/gtpccapnrz.html

date +%s;  date -d @1700000000
来源：http://dali.bjfxy.top/Article/details/gtvslneadi.html

[R71] 日期格式化
来源：http://dali.hnqzz.top/Article/details/gtrafurhta.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.0kj1m.cn/Article/details/gtoudjexma.html

[R72] 等待端口就绪
来源：http://dali.tian-w.cn/Article/details/gthvyvjbqv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtwatugqlb.html

[R73] 分割大日志
来源：http://dali.zhiwuduotai.top/Article/details/gtboekhktq.html

split -l 1000 big.log part_
来源：http://dali.ivvv.top/Article/details/gtzjnesliu.html

[R74] 批量重命名
来源：http://dali.jianghu66.top/Article/details/gtgotoywka.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.0kj1m.cn/Article/details/gtnctrfdew.html

[R75] 导出环境变量
来源：http://dali.cdnleiting.top/Article/details/gtfcvcuadz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yj20258888.top/Article/details/gtarfzymda.html

[R76] 使用临时文件
来源：http://dali.guannengcc.top/Article/details/gtsfxjqaok.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.316326.xyz/Article/details/gtwijcsurb.html

[R77] 读取用户输入
来源：http://dali.yonumen.top/Article/details/gtwjyyizaw.html

read -rp "请输入: " ans
来源：http://dali.cdnleiting.top/Article/details/gtzftpryju.html

[R78] 交互式菜单
来源：http://dali.aizwys.cn/Article/details/gtdqfgurew.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinqigfzy.top/Article/details/gthbnsymgu.html

[R79] 解析命令行选项
来源：http://dali.yongpay.top/Article/details/gtbpmdpivw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhiwuduotai.top/Article/details/gthdsctbkb.html

[R80] 查看脚本执行耗时
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvstmudei.html

time ./run.sh
来源：http://dali.jlsjyb.cn/Article/details/gtjyoarcox.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtsbgenwhc.html

S. C / C++ 专题
来源：http://dali.gotoacloud.top/Article/details/gtbfpcvmkv.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gthkhhpwdx.html

[S01] C：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtlvuyzmax.html

#include <stdio.h>
来源：http://dali.guowangkeji.top/Article/details/gttbnhjsoa.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.redwolf501.top/Article/details/gtkadifinx.html

[S02] C：变量与格式化输出
来源：http://dali.zhengqikj.top/Article/details/gtrcsyqafp.html

int a = 10; printf("%d\n", a);
来源：http://dali.guannengcc.top/Article/details/gtoijkgvyw.html

[S03] C：读入整数
来源：http://dali.tanke756.top/Article/details/gtnqpigrwz.html

int x; scanf("%d", &x);
来源：http://dali.zhengqikj.top/Article/details/gtuqmghqbb.html

[S04] C：字符串复制
来源：http://dali.jqgfzy.top/Article/details/gtewtzgmds.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.quarkkingdee.top/Article/details/gtlrjtzveb.html

[S05] C：字符串长度
来源：http://dali.yvedp.cn/Article/details/gtfgremwjk.html

strlen(s)
来源：http://dali.iojbl.cn/Article/details/gtxswpulrv.html

[S06] C：字符串比较
来源：http://dali.cheryme.top/Article/details/gtxmsmappl.html

strcmp(a, b) == 0
来源：http://dali.kuanghao11.cn/Article/details/gtghykutxw.html

[S07] C：数组遍历求和
来源：http://dali.jqgufenzy.top/Article/details/gtxlsghowb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.0kj1m.cn/Article/details/gtzkplivdc.html

[S08] C：动态内存分配与释放
来源：http://dali.hammf.cn/Article/details/gtbeuevnlq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zycfv.cn/Article/details/gteogbjpne.html

[S09] C：结构体定义与初始化
来源：http://dali.haohaochexian.top/Article/details/gtzdkmhbsm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ivvv.top/Article/details/gtnkqhnrun.html

[S10] C：指针与解引用
来源：http://dali.jinqigfzy.top/Article/details/gtcloggaqj.html

int *p = &a;  *p = 5;
来源：http://dali.gaohongyu789.top/Article/details/gtbjybyoqy.html

[S11] C：逐行读文件
来源：http://dali.yj20258.top/Article/details/gtdbkpujfu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nwbrower.top/Article/details/gtjdthptkf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jinghuilouyu.cn/Article/details/gtppwcldow.html

fclose(f);
来源：http://dali.yj202588.top/Article/details/gtqauavoan.html

[S12] C：写文件
来源：http://dali.hammf.cn/Article/details/gtryvqzhgh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gzhubu.top/Article/details/gtnedrwzzd.html

[S13] C：宏定义
来源：http://dali.9152youxi.cn/Article/details/gtfeesiqqz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhixingplan.top/Article/details/gtpljinwal.html

[S14] C：枚举
来源：http://dali.shanyushiyangtech.top/Article/details/gteeixffkk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xuanzx.com/Article/details/gtgtdmrisg.html

[S15] C：类型转换
来源：http://dali.jqgufenzy.top/Article/details/gtpfvcmort.html

(double) a / b
来源：http://dali.yongpay.top/Article/details/gtdrtubbma.html

[S16] C：位操作置位
来源：http://dali.wangshuangyany.cn/Article/details/gtilwxpzif.html

x |= (1 << 3);
来源：http://dali.ivvv.top/Article/details/gtjwjxvhrv.html

[S17] C：安全拼接字符串
来源：http://dali.sysykeji.top/Article/details/gtfqfxrgtx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hysaishi.cn/Article/details/gtaylwptyx.html

[S18] C：命令行参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvvldlmyc.html

int main(int argc, char **argv)
来源：http://dali.zycfv.cn/Article/details/gtnabhgmev.html

[S19] C：快速排序
来源：http://dali.c1oappe.top/Article/details/gtubvdumbf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.havefunace.top/Article/details/gtvbmvbhrm.html

[S20] C：二分查找
来源：http://dali.jiagoushi.top/Article/details/gtdhrrukks.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmbrchxdm.html

[S21] C：字符类别判断
来源：http://dali.zhiwuduotai.top/Article/details/gthvmiqpou.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.nanxinkj.top/Article/details/gtphzhzqwh.html

[S22] C：字符串转数字
来源：http://dali.gaohongyu789.top/Article/details/gtdteguvod.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.fengsongda.top/Article/details/gtxgnxetgp.html

[S23] C：随机数
来源：http://dali.birdmap.top/Article/details/gtopqzuhft.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.meibo888.top/Article/details/gtvheiiwej.html

[S24] C：获取本地时间
来源：http://dali.yj202588.top/Article/details/gtyxycimkb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.pengpengdd.cyou/Article/details/gtpfuljymq.html

[S25] C：内存拷贝
来源：http://dali.yongpay.top/Article/details/gtosqejnua.html

memcpy(dst, src, n);
来源：http://dali.kuanghao11.cn/Article/details/gtexybtqaw.html

[S26] C：内存清零
来源：http://dali.jqgfzy.top/Article/details/gtvswcpuae.html

memset(a, 0, sizeof a);
来源：http://dali.tianlin.xyz/Article/details/gtqizqrcvj.html

[S27] C：定义常量
来源：http://dali.dianchejie.cn/Article/details/gtbwxrqnpd.html

const double PI = 3.14159;
来源：http://dali.chenzaomai.com/Article/details/gtjdbonwsd.html

[S28] C：静态变量
来源：http://dali.yj202588.top/Article/details/gtngmmetpl.html

static int counter = 0;
来源：http://dali.gotoacloud.top/Article/details/gtlzwwyfba.html

[S29] C：变参函数
来源：http://dali.ehwqpu.com/Article/details/gticvdkgly.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ybcxt.top/Article/details/gtripuigas.html

[S30] C：头文件保护
来源：http://dali.fengsongda.top/Article/details/gtamswbqjt.html

#ifndef X_H
来源：http://dali.redwolf501.top/Article/details/gtavhqtfto.html

#define X_H
来源：http://dali.jyoumei.cn/Article/details/gtnhdiqdnk.html

#endif
来源：http://dali.nanxinkj.top/Article/details/gtuhchcuqv.html

[S31] C++：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyvfujxgx.html

#include <iostream>
来源：http://dali.xylfe.cn/Article/details/gtclylwash.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yongpay.top/Article/details/gtszskyzwd.html

[S32] C++：字符串
来源：http://dali.shzxlz.cn/Article/details/gtthuzzgxj.html

std::string s = "hi";  s += "!";
来源：http://dali.yanxiufei.cn/Article/details/gtzetvhnyo.html

[S33] C++：vector 增删
来源：http://dali.hywenlv.cn/Article/details/gtvlubsucl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.mhx1999.top/Article/details/gtrlisfxmh.html

[S34] C++：遍历 vector
来源：http://dali.316326.xyz/Article/details/gtzwfkmzin.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.dashuyun.cn/Article/details/gtupcupgfd.html

[S35] C++：map
来源：http://dali.ehwqpu.com/Article/details/gtasusnqqg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.smart0.xyz/Article/details/gtscbmmnli.html

[S36] C++：unordered_map
来源：http://dali.gzhubu.top/Article/details/gtgmxlawkq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfdbkaaed.html

[S37] C++：set
来源：http://dali.yanxiufei.cn/Article/details/gtcpitvtzf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.haohaochexian.top/Article/details/gtzvvitwpj.html

[S38] C++：排序
来源：http://dali.yj202588.top/Article/details/gtxytenkkj.html

std::sort(v.begin(), v.end());
来源：http://dali.tanke756.top/Article/details/gttcxsgqpv.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gtwgxaoqoa.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhongyouzk.top/Article/details/gtijxoazfq.html

[S40] C++：查找元素
来源：http://dali.jinqigufen.top/Article/details/gtouacmbiu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.svipenyu.cn/Article/details/gtvqkstxao.html

[S41] C++：类与构造函数
来源：http://dali.jianghu66.top/Article/details/gtjbxmzhft.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.haohaochexian.top/Article/details/gtdtruxrbk.html

[S42] C++：继承与虚函数
来源：http://dali.yuanzhike.top/Article/details/gtchrgbuan.html

class B : public Base { public: void f() override {} };
来源：http://dali.svipenyu.cn/Article/details/gtvkemcmet.html

[S43] C++：智能指针
来源：http://dali.fzhhl.top/Article/details/gtkxxafywg.html

auto p = std::make_unique<int>(5);
来源：http://dali.yongpay.top/Article/details/gtybitgmfi.html

[S44] C++：引用传参
来源：http://dali.andypj.xyz/Article/details/gtkwosisox.html

void inc(int &x) { ++x; }
来源：http://dali.xylfe.cn/Article/details/gtrbhnrieq.html

[S45] C++：lambda
来源：http://dali.zhiwuduotai.top/Article/details/gtmetvzdgm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.pycfn.com/Article/details/gtzmsactke.html

[S46] C++：函数模板
来源：http://dali.cheryme.top/Article/details/gtlsbuwhzw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yueranfly.top/Article/details/gtmtwgbjxr.html

[S47] C++：结构化绑定遍历
来源：http://dali.gogol.net.cn/Article/details/gtwrtsluad.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ppjwa.cn/Article/details/gttzktiklt.html

[S48] C++：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gtoehvibqr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.chenjidiqi.icu/Article/details/gtvibsdkbj.html

while (std::getline(in, line)) { }
来源：http://dali.tian-w.cn/Article/details/gtnganpcmc.html

[S49] C++：写文件
来源：http://dali.ppjwa.cn/Article/details/gtibkwpgqd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sweek.top/Article/details/gtjahcdndj.html

[S50] C++：格式化数字
来源：http://dali.yueranfly.top/Article/details/gtqndrrzlf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gttpmdhwix.html

[S51] C++：显式类型转换
来源：http://dali.quarkkingdee.top/Article/details/gtidnupvih.html

static_cast<double>(a) / b
来源：http://dali.hnqzz.top/Article/details/gtsruqqyws.html

[S52] C++：const 与 noexcept
来源：http://dali.hywenlv.cn/Article/details/gtsvinaxnl.html

int size() const noexcept { return n_; }
来源：http://dali.snrcjt.cn/Article/details/gtprfqzkty.html

[S53] C++：移动语义
来源：http://dali.meibo888.top/Article/details/gtwoadkscq.html

std::vector<int> w = std::move(v);
来源：http://dali.jiagoushi.top/Article/details/gtssxnyxri.html

[S54] C++：异常处理
来源：http://dali.zhoulong.xyz/Article/details/gtdtbymkzb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xziqi.cn/Article/details/gtqdqxkqgo.html

[S55] C++：结构化绑定
来源：http://dali.yangfankeji.com/Article/details/gtfvwjttya.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.nanxinkj.top/Article/details/gtbkrgcfdu.html

[S56] C++：optional
来源：http://dali.xuetiantiany.cn/Article/details/gthrrklmyl.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.redwolf501.top/Article/details/gtfqlirvvx.html

[S57] C++：编译期常量
来源：http://dali.hnxiangtu.top/Article/details/gtymezcbas.html

constexpr int N = 10;
来源：http://dali.yuanzhike.top/Article/details/gtjeivaofs.html

[S58] C++：命名空间
来源：http://dali.ehwqpu.com/Article/details/gtwpmxmgbc.html

namespace ns { int f() { return 1; } }
来源：http://dali.mhx1999.top/Article/details/gttekwlkki.html

[S59] C++：静态断言
来源：http://dali.gzhubu.top/Article/details/gtxidsawtu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cdnleiting.top/Article/details/gteoqseayd.html

[S60] C++：遍历并删除元素
来源：http://dali.aibaodan.cn/Article/details/gtojjznhcs.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.gogol.net.cn/Article/details/gtfdhxjugi.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtyqptpegt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.aizwys.cn/Article/details/gtiyirvjdm.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtdldymltw.html

[T01] Kotlin：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtwyrcgviz.html

println("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtspownkvv.html

[T02] Kotlin：变量
来源：http://dali.hammf.cn/Article/details/gtvxzvratc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zdqjudy.top/Article/details/gtlkokfyev.html

[T03] Kotlin：字符串模板
来源：http://dali.ybcxt.top/Article/details/gtydncuwid.html

"值: $b"
来源：http://dali.hfpthk.cn/Article/details/gtlxvogdnv.html

[T04] Kotlin：空安全
来源：http://dali.yuxming.cn/Article/details/gtdaxharsz.html

val n: String? = null;  n?.length
来源：http://dali.cqqwz.cn/Article/details/gteghlagjg.html

[T05] Kotlin：when 表达式
来源：http://dali.ppjwa.cn/Article/details/gtaumhmxwo.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ivvv.top/Article/details/gtitokjffw.html

[T06] Kotlin：集合映射
来源：http://dali.yangfankeji.com/Article/details/gtlghynqpn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yj202588.top/Article/details/gtlmmwqfbx.html

[T07] Kotlin：集合过滤
来源：http://dali.gaohongyu789.top/Article/details/gteqkemrsk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinqigfzy.top/Article/details/gtechfjlxo.html

[T08] Kotlin：数据类
来源：http://dali.jqgufenzy.top/Article/details/gtsrhcmflf.html

data class User(val name: String, val age: Int)
来源：http://dali.yvedp.cn/Article/details/gtielxvcvx.html

[T09] Kotlin：扩展函数
来源：http://dali.iojbl.cn/Article/details/gtdofxhtss.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gtrbzxnbuw.html

[T10] Kotlin：默认参数
来源：http://dali.shuidangran.top/Article/details/gtyxpvahaz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.tian-w.cn/Article/details/gtpehnwvrv.html

[T11] Kotlin：协程
来源：http://dali.pycfn.com/Article/details/gtgbfxdjun.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.nanxuanxn.top/Article/details/gtixegbmhv.html

[T12] Kotlin：解构声明
来源：http://dali.dashuyun.cn/Article/details/gtmvsazpmj.html

val (a, b) = Pair(1, 2)
来源：http://dali.hammf.cn/Article/details/gtlvxemgnt.html

[T13] Kotlin：只读 Map
来源：http://dali.dianchejie.cn/Article/details/gtqutfpncu.html

val m = mapOf("a" to 1)
来源：http://dali.zycfv.cn/Article/details/gtjtkqohln.html

[T14] Kotlin：循环
来源：http://dali.andypj.xyz/Article/details/gtakordxne.html

for (i in 1..10) println(i)
来源：http://dali.birdmap.top/Article/details/gtscxpabmb.html

[T15] Kotlin：接口
来源：http://dali.shanyushiyangtech.top/Article/details/gtulnxwuck.html

interface Shape { fun area(): Double }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttvuvtyvk.html

[T16] Swift：Hello World
来源：http://dali.tianlin.xyz/Article/details/gtzrxahvhp.html

print("Hello")
来源：http://dali.zhengqikj.top/Article/details/gtuaqdbwkb.html

[T17] Swift：变量与常量
来源：http://dali.hongshengwenyu.top/Article/details/gtcbgcsnyk.html

var a = 1;  let b = 2
来源：http://dali.hongshengwenyu.top/Article/details/gtbawtkdck.html

[T18] Swift：字符串插值
来源：http://dali.fengsongda.top/Article/details/gtgvatknag.html

"值: \(b)"
来源：http://dali.nanxinkj.top/Article/details/gtergaiaal.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gttduijqub.html

if let n = opt { print(n) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gteytvofpv.html

[T20] Swift：数组操作
来源：http://dali.ybcxt.top/Article/details/gtmrrnflql.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.chenjidiqi.icu/Article/details/gtusvtppzq.html

[T21] Swift：遍历
来源：http://dali.hnxiangtu.top/Article/details/gtlbgjgbpw.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gtrkpphxeq.html

[T22] Swift：字典
来源：http://dali.nanxuanxn.top/Article/details/gtykyfwupe.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.iojbl.cn/Article/details/gtnnwcwacc.html

[T23] Swift：函数
来源：http://dali.iojbl.cn/Article/details/gtvmbjtxrj.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.kuanghao11.cn/Article/details/gtwfuxhrli.html

[T24] Swift：闭包
来源：http://dali.sufxvd.cn/Article/details/gtfdrdjxfg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwylwyaqk.html

[T25] Swift：结构体
来源：http://dali.gotoacloud.top/Article/details/gtumxzevyc.html

struct P { var x: Int }
来源：http://dali.smart0.xyz/Article/details/gthrafhnrb.html

[T26] Swift：类与重写
来源：http://dali.yj20258888.top/Article/details/gtgsvwenke.html

class A: Base { override func f() {} }
来源：http://dali.jinqigfzy.top/Article/details/gtwfbmojjt.html

[T27] Swift：错误处理
来源：http://dali.jqgfzy.top/Article/details/gtlxiyqmsr.html

do { try f() } catch { print(error) }
来源：http://dali.yanxiufei.cn/Article/details/gtwtlxoruz.html

[T28] Swift：枚举
来源：http://dali.redwolf501.top/Article/details/gtqetroblk.html

enum Color { case red, green }
来源：http://dali.shangyingyoupin.top/Article/details/gtoqzyzyzm.html

[T29] Swift：guard 提前返回
来源：http://dali.meibo888.top/Article/details/gtrlieozsc.html

guard let x = opt else { return }
来源：http://dali.zhiwuduotai.top/Article/details/gtnkctzbea.html

[T30] Swift：协议
来源：http://dali.aizwys.cn/Article/details/gtwljhnmyc.html

protocol Shape { func area() -> Double }
来源：http://dali.xinyue.icu/Article/details/gtvezlhjow.html

[T31] Lua：Hello World
来源：http://dali.guannengcc.top/Article/details/gtvlqgyleg.html

print("Hello")
来源：http://dali.jinqigfzy.top/Article/details/gtmeybyuxj.html

[T32] Lua：局部变量
来源：http://dali.gzhubu.top/Article/details/gtiwsbssge.html

local a = 1
来源：http://dali.yueranfly.top/Article/details/gtinjnclmy.html

[T33] Lua：表（数组）
来源：http://dali.ivvv.top/Article/details/gtjsxrnehe.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yueranfly.top/Article/details/gtyzjsdjao.html

[T34] Lua：遍历表
来源：http://dali.nanxuanxn.top/Article/details/gtlitfyozo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.gogol.net.cn/Article/details/gtahwxoytd.html

[T35] Lua：字典表
来源：http://dali.jinqigfzy.top/Article/details/gtijtpoikw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.smart0.xyz/Article/details/gtzfkihmsz.html

[T36] Lua：函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuurqiktj.html

function add(a, b) return a + b end
来源：http://dali.smart0.xyz/Article/details/gtyklelnqa.html

[T37] Lua：字符串拼接
来源：http://dali.dashuyun.cn/Article/details/gttuilhrxl.html

"a" .. "b"
来源：http://dali.0kj1m.cn/Article/details/gtowafmzvi.html

[T38] Lua：条件
来源：http://dali.cashguo.top/Article/details/gtcpkvrtdy.html

if x > 0 then print("正") end
来源：http://dali.hywenlv.cn/Article/details/gthtkwnaep.html

[T39] Lua：模式匹配
来源：http://dali.cqqwz.cn/Article/details/gtgilhbmvg.html

string.find(s, "%d+")
来源：http://dali.xinyue.icu/Article/details/gtzgrhinkc.html

[T40] Lua：元表
来源：http://dali.9152youxi.cn/Article/details/gtisilsbou.html

setmetatable({}, { __index = base })
来源：http://dali.guowangkeji.top/Article/details/gtexulsrhv.html

[T41] Perl：Hello World
来源：http://dali.ehwqpu.com/Article/details/gteafwefxd.html

print "Hello\n";
来源：http://dali.hammf.cn/Article/details/gtvoaawgap.html

[T42] Perl：变量类型
来源：http://dali.jinqigufen.top/Article/details/gtkhfasxgc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yj20258.top/Article/details/gtotieyhds.html

[T43] Perl：字符串插值
来源：http://dali.quarkkingdee.top/Article/details/gtxvdgbvai.html

"值: $a"
来源：http://dali.sysykeji.top/Article/details/gtjgglrlgx.html

[T44] Perl：条件
来源：http://dali.gotoacloud.top/Article/details/gtbmcotvzf.html

if ($a > 0) { print "正"; }
来源：http://dali.guowangkeji.top/Article/details/gtikcbyomk.html


<!-- 参考信息 -->