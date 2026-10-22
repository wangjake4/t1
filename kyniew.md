代发 wailian999

cmd >/dev/null 2>&1
来源：http://dali.hywenlv.cn/Article/details/gtdfwcfjth.html

[R42] 输入重定向
来源：http://dali.jinghuilouyu.cn/Article/details/gtrczasydt.html

wc -l < a.txt
来源：http://dali.zycfv.cn/Article/details/gtxsiwifvj.html

[R43] 按名字查找文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmavjeugc.html

find . -name "*.log" -type f
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmwheingu.html

[R44] 按修改时间查找
来源：http://dali.zdqjudy.top/Article/details/gtdpugapyv.html

find . -mtime -7 -type f
来源：http://dali.cdnleiting.top/Article/details/gtgxtmhqsf.html

[R45] 批量删除
来源：http://dali.316326.xyz/Article/details/gttfqtkrme.html

find . -name "*.tmp" -delete
来源：http://dali.yj202588.top/Article/details/gtewouksbn.html

[R46] 递归替换文件内容
来源：http://dali.hfpthk.cn/Article/details/gtjfqcisip.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.chenjidiqi.icu/Article/details/gtamyptubz.html

[R47] sed 单行替换
来源：http://dali.yongpay.top/Article/details/gttliavvsl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xylfe.cn/Article/details/gtupsjflvq.html

[R48] awk 取指定列
来源：http://dali.jqgufenzy.top/Article/details/gtsrweehaw.html

awk '{print $1, $3}' a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtrcmvyxxx.html

[R49] awk 带条件
来源：http://dali.chenjidiqi.icu/Article/details/gttlnbrpvd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gtujufpegd.html

[R50] awk 求和
来源：http://dali.zycfv.cn/Article/details/gtsvsdqlnj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtweksrjfr.html

[R51] 排序去重取前几
来源：http://dali.yongpay.top/Article/details/gtrmhvdflu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ppjwa.cn/Article/details/gtdopguuxb.html

[R52] 统计行数
来源：http://dali.jlsjyb.cn/Article/details/gtqzqxuvza.html

wc -l a.txt
来源：http://dali.redwolf501.top/Article/details/gtrujdjrnx.html

[R53] 查看文件头与实时尾
来源：http://dali.xylfe.cn/Article/details/gtvqtchufj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xziqi.cn/Article/details/gtyzzrpnax.html

[R54] 比较两个文件
来源：http://dali.daxiang520.top/Article/details/gttbxtlgan.html

diff a.txt b.txt
来源：http://dali.ivvv.top/Article/details/gtczsmtgvq.html

[R55] 压缩与解压
来源：http://dali.jinqigufen.top/Article/details/gtirygswfi.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cheryme.top/Article/details/gtkndbscel.html

[R56] 远程拷贝
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgcnmulvf.html

scp file user@host:/path/
来源：http://dali.nwbrower.top/Article/details/gtaabepofv.html

[R57] 远程执行命令
来源：http://dali.nanxinkj.top/Article/details/gtfzcvrdzn.html

ssh user@host 'uptime'
来源：http://dali.smart0.xyz/Article/details/gtxinounaf.html

[R58] 下载文件
来源：http://dali.yuxming.cn/Article/details/gtlaasncem.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.nanxuanxn.top/Article/details/gtlpnkqrfn.html

[R59] 发 POST JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gtdevgpiad.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdpxagmcb.html

[R60] 只看 HTTP 状态码
来源：http://dali.hfpthk.cn/Article/details/gtlzqmcbbi.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhixingplan.top/Article/details/gtcesjlcog.html

[R61] 磁盘占用
来源：http://dali.gogol.net.cn/Article/details/gtebmrqxbj.html

df -h;  du -sh *
来源：http://dali.yongpay.top/Article/details/gtrausxsjp.html

[R62] 找最占空间的文件
来源：http://dali.chenlongwang.top/Article/details/gtqydmslyl.html

du -ah . | sort -rh | head -10
来源：http://dali.dianchejie.cn/Article/details/gtmhuldgwj.html

[R63] 内存与进程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjayshoar.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gtlpgfhvdy.html

[R64] 结束进程
来源：http://dali.ehwqpu.com/Article/details/gtctzrudnm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jinghuilouyu.cn/Article/details/gtoqudhicy.html

[R65] 查看端口占用
来源：http://dali.zycfv.cn/Article/details/gtgjoorvkk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.tian-w.cn/Article/details/gtytsozxku.html

[R66] 定时任务
来源：http://dali.cdnleiting.top/Article/details/gtsznisbjx.html

crontab -e;  crontab -l
来源：http://dali.hysaishi.cn/Article/details/gtjbgchjpw.html

[R67] 生成随机十六进制串
来源：http://dali.jyoumei.cn/Article/details/gtmthojisf.html

openssl rand -hex 16
来源：http://dali.havefunace.top/Article/details/gteojisvey.html

[R68] 计算文件校验值
来源：http://dali.tianlin.xyz/Article/details/gtmylvdeif.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yj20258888.top/Article/details/gtitmpqtyw.html

[R69] 生成随机密码
来源：http://dali.cucudq.cn/Article/details/gtsvphwljq.html

head -c 16 /dev/urandom | base64
来源：http://dali.xylfe.cn/Article/details/gtckhavovs.html

[R70] 时间戳与互转
来源：http://dali.yuanzhike.top/Article/details/gtbbxoamnu.html

date +%s;  date -d @1700000000
来源：http://dali.yueranfly.top/Article/details/gtbypdldda.html

[R71] 日期格式化
来源：http://dali.xuanzx.com/Article/details/gtqljoxisp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.smart0.xyz/Article/details/gtabydmsrz.html

[R72] 等待端口就绪
来源：http://dali.zhixingplan.top/Article/details/gtxqmuwque.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjmghjthw.html

[R73] 分割大日志
来源：http://dali.zdqjudy.top/Article/details/gtscejhffa.html

split -l 1000 big.log part_
来源：http://dali.sweek.top/Article/details/gtnahzawyn.html

[R74] 批量重命名
来源：http://dali.gzhubu.top/Article/details/gtuyrpbizx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.haohaochexian.top/Article/details/gtnbxxcngn.html

[R75] 导出环境变量
来源：http://dali.jyoumei.cn/Article/details/gtnszkfrjz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.daria6918.cn/Article/details/gtnisoskqm.html

[R76] 使用临时文件
来源：http://dali.meibo888.top/Article/details/gtolosvigc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj20258888.top/Article/details/gtxpeujoub.html

[R77] 读取用户输入
来源：http://dali.jqgufenzy.top/Article/details/gtwscawywz.html

read -rp "请输入: " ans
来源：http://dali.sxryk.cn/Article/details/gttzjeghdu.html

[R78] 交互式菜单
来源：http://dali.gzhubu.top/Article/details/gtdikfnajk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.kuanghao11.cn/Article/details/gtpaiycvfx.html

[R79] 解析命令行选项
来源：http://dali.xuanzx.com/Article/details/gthblrhkic.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yangfankeji.com/Article/details/gtmoubpffn.html

[R80] 查看脚本执行耗时
来源：http://dali.yj202588.top/Article/details/gttwmubzje.html

time ./run.sh
来源：http://dali.jianghu66.top/Article/details/gtcyvflbvq.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtiszmlfmp.html

S. C / C++ 专题
来源：http://dali.316326.xyz/Article/details/gtummyuwqe.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiuzmlpct.html

[S01] C：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtdpsrjupf.html

#include <stdio.h>
来源：http://dali.cheryme.top/Article/details/gtsofauqwy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gogol.net.cn/Article/details/gtzvguiwdi.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gtykktslgj.html

int a = 10; printf("%d\n", a);
来源：http://dali.xziqi.cn/Article/details/gtfxatnhor.html

[S03] C：读入整数
来源：http://dali.jlsjyb.cn/Article/details/gtvwbfzggb.html

int x; scanf("%d", &x);
来源：http://dali.sufxvd.cn/Article/details/gthvlveeza.html

[S04] C：字符串复制
来源：http://dali.redwolf501.top/Article/details/gtfgefgfyy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.tanke756.top/Article/details/gtueiouecq.html

[S05] C：字符串长度
来源：http://dali.aibaodan.cn/Article/details/gttgbeinss.html

strlen(s)
来源：http://dali.vqdsnc.cn/Article/details/gtsolixdyp.html

[S06] C：字符串比较
来源：http://dali.chenlongwang.top/Article/details/gtqqnpcbjt.html

strcmp(a, b) == 0
来源：http://dali.hywenlv.cn/Article/details/gtkvrcykba.html

[S07] C：数组遍历求和
来源：http://dali.xuanzx.com/Article/details/gtiihvfwmy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hfpthk.cn/Article/details/gtninhrjkz.html

[S08] C：动态内存分配与释放
来源：http://dali.bjfxy.top/Article/details/gtyyszmoot.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ydzc1.top/Article/details/gtupzrgjuz.html

[S09] C：结构体定义与初始化
来源：http://dali.yj20258888.top/Article/details/gtmtozrere.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ehwqpu.com/Article/details/gtxwixsunt.html

[S10] C：指针与解引用
来源：http://dali.hnxiangtu.top/Article/details/gtbyqlpyjx.html

int *p = &a;  *p = 5;
来源：http://dali.quarkkingdee.top/Article/details/gtsydkazaf.html

[S11] C：逐行读文件
来源：http://dali.c1oappe.top/Article/details/gtisqnolox.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.pengpengdd.cyou/Article/details/gtnfaiurle.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.wangdashe.top/Article/details/gtzevghilc.html

fclose(f);
来源：http://dali.316326.xyz/Article/details/gtjvrywlwg.html

[S12] C：写文件
来源：http://dali.daria6918.cn/Article/details/gtetnzvxcu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.nanxuanxn.top/Article/details/gtxrbmzyzb.html

[S13] C：宏定义
来源：http://dali.yongpay.top/Article/details/gtwsbgzpfc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yvedp.cn/Article/details/gtoembcpdk.html

[S14] C：枚举
来源：http://dali.cqqwz.cn/Article/details/gthezxsvay.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.tianlin.xyz/Article/details/gtyxzccbtd.html

[S15] C：类型转换
来源：http://dali.jqgufenzy.top/Article/details/gtihtucqfv.html

(double) a / b
来源：http://dali.chenlongwang.top/Article/details/gtwgjqiiyv.html

[S16] C：位操作置位
来源：http://dali.ehwqpu.com/Article/details/gtarfnnwlk.html

x |= (1 << 3);
来源：http://dali.bjfxy.top/Article/details/gtqnkauvrt.html

[S17] C：安全拼接字符串
来源：http://dali.dianchejie.cn/Article/details/gtaxpkdjyk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hammf.cn/Article/details/gtsrjgkzhd.html

[S18] C：命令行参数
来源：http://dali.gzhubu.top/Article/details/gtockhzfnv.html

int main(int argc, char **argv)
来源：http://dali.9152youxi.cn/Article/details/gtrbprvhae.html

[S19] C：快速排序
来源：http://dali.nanxinkj.top/Article/details/gtjoyukhwq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.gotoacloud.top/Article/details/gttiytyync.html

[S20] C：二分查找
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgeicfgmv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ehwqpu.com/Article/details/gttghcrpxj.html

[S21] C：字符类别判断
来源：http://dali.meibo888.top/Article/details/gtflmxkjbh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.fengsongda.top/Article/details/gtfcemhtfx.html

[S22] C：字符串转数字
来源：http://dali.chenlongwang.top/Article/details/gtrjtdfqmt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zdqjudy.top/Article/details/gtrvuibnvl.html

[S23] C：随机数
来源：http://dali.tian-w.cn/Article/details/gtwhpmjvxu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xinyue.icu/Article/details/gtrksesnhq.html

[S24] C：获取本地时间
来源：http://dali.hywenlv.cn/Article/details/gtrivicwoe.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xuanzx.com/Article/details/gtnbqdpdfd.html

[S25] C：内存拷贝
来源：http://dali.316326.xyz/Article/details/gtiaomwaom.html

memcpy(dst, src, n);
来源：http://dali.shzxlz.cn/Article/details/gtekcgpqss.html

[S26] C：内存清零
来源：http://dali.snrcjt.cn/Article/details/gtpkxxzaie.html

memset(a, 0, sizeof a);
来源：http://dali.sysykeji.top/Article/details/gthpxaedvi.html

[S27] C：定义常量
来源：http://dali.hongshengwenyu.top/Article/details/gtxaiachse.html

const double PI = 3.14159;
来源：http://dali.smart0.xyz/Article/details/gtobwvrjfy.html

[S28] C：静态变量
来源：http://dali.guowangkeji.top/Article/details/gtxjaragdj.html

static int counter = 0;
来源：http://dali.tianlin.xyz/Article/details/gtauoxulwo.html

[S29] C：变参函数
来源：http://dali.redwolf501.top/Article/details/gtvvulwkbk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.sweek.top/Article/details/gtdhbbdkgx.html

[S30] C：头文件保护
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwrvzlgii.html

#ifndef X_H
来源：http://dali.jqgfzy.top/Article/details/gteluzbjdb.html

#define X_H
来源：http://dali.yangfankeji.com/Article/details/gtyydfacea.html

#endif
来源：http://dali.jinqigufen.top/Article/details/gtdbnhozod.html

[S31] C++：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtoyoqrxyo.html

#include <iostream>
来源：http://dali.yj20258.top/Article/details/gtoqfwwhit.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.nanxuanxn.top/Article/details/gtggouuxbg.html

[S32] C++：字符串
来源：http://dali.gzhubu.top/Article/details/gtsvucmjyu.html

std::string s = "hi";  s += "!";
来源：http://dali.guannengcc.top/Article/details/gtqfsgfips.html

[S33] C++：vector 增删
来源：http://dali.cashguo.top/Article/details/gtnkejdbnu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.svipenyu.cn/Article/details/gtkxleclne.html

[S34] C++：遍历 vector
来源：http://dali.0kj1m.cn/Article/details/gtfuoiaige.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.guannengcc.top/Article/details/gtrnmxzfgm.html

[S35] C++：map
来源：http://dali.daria6918.cn/Article/details/gtovdwuyor.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gtonkmyczu.html

[S36] C++：unordered_map
来源：http://dali.yangfankeji.com/Article/details/gtwtzpnwmi.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.316326.xyz/Article/details/gtksvctewh.html

[S37] C++：set
来源：http://dali.316326.xyz/Article/details/gtmevdhmhp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hywenlv.cn/Article/details/gtnjdcjuqr.html

[S38] C++：排序
来源：http://dali.yj20258.top/Article/details/gtyxwwsxeh.html

std::sort(v.begin(), v.end());
来源：http://dali.haohaochexian.top/Article/details/gtqsdixjdg.html

[S39] C++：自定义比较器排序
来源：http://dali.jyoumei.cn/Article/details/gtjhzxjbby.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jqgufenzy.top/Article/details/gtevvhdfrw.html

[S40] C++：查找元素
来源：http://dali.sysykeji.top/Article/details/gtjusohtiy.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinqigfzy.top/Article/details/gtbbcfyznq.html

[S41] C++：类与构造函数
来源：http://dali.jyoumei.cn/Article/details/gtkmwysfea.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jqgfzy.top/Article/details/gtwloljgqp.html

[S42] C++：继承与虚函数
来源：http://dali.ydzc1.top/Article/details/gtzzoufkvi.html

class B : public Base { public: void f() override {} };
来源：http://dali.svipenyu.cn/Article/details/gteupjrfoj.html

[S43] C++：智能指针
来源：http://dali.shuidangran.top/Article/details/gtezztbxir.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhiwuduotai.top/Article/details/gtdnmhyaxa.html

[S44] C++：引用传参
来源：http://dali.zycfv.cn/Article/details/gtayubacao.html

void inc(int &x) { ++x; }
来源：http://dali.kuanghao11.cn/Article/details/gthqdbcsku.html

[S45] C++：lambda
来源：http://dali.sufxvd.cn/Article/details/gtevlzghmz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yj20258.top/Article/details/gtlnlcsgig.html

[S46] C++：函数模板
来源：http://dali.sufxvd.cn/Article/details/gtjfkrelow.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hnqzz.top/Article/details/gtqrjdnyzc.html

[S47] C++：结构化绑定遍历
来源：http://dali.guannengcc.top/Article/details/gttgybftoh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yj20258.top/Article/details/gtnppccwww.html

[S48] C++：逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gtpeakinbr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yonumen.top/Article/details/gtmyrvigdh.html

while (std::getline(in, line)) { }
来源：http://dali.xuanzx.com/Article/details/gtrspqotqn.html

[S49] C++：写文件
来源：http://dali.xziqi.cn/Article/details/gtnbtnzuli.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.havefunace.top/Article/details/gtarkxeyjc.html

[S50] C++：格式化数字
来源：http://dali.bjfxy.top/Article/details/gtaqxxhohs.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gtvuorkyol.html

[S51] C++：显式类型转换
来源：http://dali.jinqigufen.top/Article/details/gtdliqfgaw.html

static_cast<double>(a) / b
来源：http://dali.nwbrower.top/Article/details/gtdigjhlfi.html

[S52] C++：const 与 noexcept
来源：http://dali.nwbrower.top/Article/details/gtbglmgzfy.html

int size() const noexcept { return n_; }
来源：http://dali.ppjwa.cn/Article/details/gtuievekvd.html

[S53] C++：移动语义
来源：http://dali.mhx1999.top/Article/details/gtefzmtcoz.html

std::vector<int> w = std::move(v);
来源：http://dali.hongshengwenyu.top/Article/details/gtbarfgeyn.html

[S54] C++：异常处理
来源：http://dali.meibo888.top/Article/details/gtkbjgvjdq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.guannengcc.top/Article/details/gtyxhoupzr.html

[S55] C++：结构化绑定
来源：http://dali.chenzaomai.com/Article/details/gtdvxthyey.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.vqdsnc.cn/Article/details/gtfqiccewg.html

[S56] C++：optional
来源：http://dali.jinqigufen.top/Article/details/gtkpcvwhie.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jianghu66.top/Article/details/gtbssxwibp.html

[S57] C++：编译期常量
来源：http://dali.pycfn.com/Article/details/gtgwznyobp.html

constexpr int N = 10;
来源：http://dali.quarkkingdee.top/Article/details/gtnxyjrors.html

[S58] C++：命名空间
来源：http://dali.nwbrower.top/Article/details/gthyaodkjl.html

namespace ns { int f() { return 1; } }
来源：http://dali.andypj.xyz/Article/details/gtxipemhpu.html

[S59] C++：静态断言
来源：http://dali.fengsongda.top/Article/details/gtylyxcahn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.snrcjt.cn/Article/details/gtjovdpyum.html

[S60] C++：遍历并删除元素
来源：http://dali.guowangkeji.top/Article/details/gtpxvmcbyu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.cashguo.top/Article/details/gtyhlrpsma.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtpzgsqwdp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shuidangran.top/Article/details/gtcxxtblvh.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtmevwovwp.html

[T01] Kotlin：Hello World
来源：http://dali.hammf.cn/Article/details/gtrehkgphk.html

println("Hello")
来源：http://dali.nwbrower.top/Article/details/gtzcwxosxt.html

[T02] Kotlin：变量
来源：http://dali.ybcxt.top/Article/details/gtafbxwvug.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ydzc1.top/Article/details/gtsdyylyta.html

[T03] Kotlin：字符串模板
来源：http://dali.zhixingplan.top/Article/details/gtmnyzudha.html

"值: $b"
来源：http://dali.dashuyun.cn/Article/details/gtyhchqjst.html

[T04] Kotlin：空安全
来源：http://dali.shanyushiyangtech.top/Article/details/gtkkiwtexo.html

val n: String? = null;  n?.length
来源：http://dali.nwbrower.top/Article/details/gttkwlzxtc.html

[T05] Kotlin：when 表达式
来源：http://dali.chenlongwang.top/Article/details/gtfbvqpoek.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhixingplan.top/Article/details/gtfpacwqgm.html

[T06] Kotlin：集合映射
来源：http://dali.wangshuangyany.cn/Article/details/gtydegwgah.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ppjwa.cn/Article/details/gtlbfhpnjo.html

[T07] Kotlin：集合过滤
来源：http://dali.tian-w.cn/Article/details/gtfrwxlnwh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.haohaochexian.top/Article/details/gtqapwaszg.html

[T08] Kotlin：数据类
来源：http://dali.xuetiantiany.cn/Article/details/gtwsbjvccv.html

data class User(val name: String, val age: Int)
来源：http://dali.aibaodan.cn/Article/details/gtfoadlajc.html

[T09] Kotlin：扩展函数
来源：http://dali.chenzaomai.com/Article/details/gtyoprwcpi.html

fun String.exclaim() = this + "!"
来源：http://dali.fengsongda.top/Article/details/gtjhjasiwz.html

[T10] Kotlin：默认参数
来源：http://dali.yanxiufei.cn/Article/details/gtwebdfasl.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shzxlz.cn/Article/details/gtqmussfvj.html

[T11] Kotlin：协程
来源：http://dali.ybcxt.top/Article/details/gtpascteoy.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.guannengcc.top/Article/details/gtljxncgdl.html

[T12] Kotlin：解构声明
来源：http://dali.yangfankeji.com/Article/details/gtttklsgfz.html

val (a, b) = Pair(1, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtcrdzmuvm.html

[T13] Kotlin：只读 Map
来源：http://dali.dashuyun.cn/Article/details/gtcexrmtsx.html

val m = mapOf("a" to 1)
来源：http://dali.andypj.xyz/Article/details/gtpkqroiyx.html

[T14] Kotlin：循环
来源：http://dali.yangfankeji.com/Article/details/gtzmtdcbgg.html

for (i in 1..10) println(i)
来源：http://dali.xuetiantiany.cn/Article/details/gtcrkfspdm.html

[T15] Kotlin：接口
来源：http://dali.9152youxi.cn/Article/details/gtxgkbapxl.html

interface Shape { fun area(): Double }
来源：http://dali.jiagoushi.top/Article/details/gtiwxlyfri.html

[T16] Swift：Hello World
来源：http://dali.cqqwz.cn/Article/details/gthiqrtnsz.html

print("Hello")
来源：http://dali.hnqzz.top/Article/details/gtfbxygogf.html

[T17] Swift：变量与常量
来源：http://dali.cdnleiting.top/Article/details/gtcjgdtxmx.html

var a = 1;  let b = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtmjrfzgkv.html

[T18] Swift：字符串插值
来源：http://dali.ivvv.top/Article/details/gtvkwuhqpw.html

"值: \(b)"
来源：http://dali.jinghuilouyu.cn/Article/details/gtefsfosvk.html

[T19] Swift：可选绑定
来源：http://dali.gogol.net.cn/Article/details/gtjprjyrck.html

if let n = opt { print(n) }
来源：http://dali.andypj.xyz/Article/details/gtftglfmmt.html

[T20] Swift：数组操作
来源：http://dali.c1oappe.top/Article/details/gtcuaaddhu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj20258888.top/Article/details/gtkugjoqyk.html

[T21] Swift：遍历
来源：http://dali.dianchejie.cn/Article/details/gtzormgdtq.html

for x in a { print(x) }
来源：http://dali.yvedp.cn/Article/details/gtjtsjgbqw.html

[T22] Swift：字典
来源：http://dali.guowangkeji.top/Article/details/gtvykxzlyb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ehwqpu.com/Article/details/gtnchgwckf.html

[T23] Swift：函数
来源：http://dali.yuxming.cn/Article/details/gtsfppyxri.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cheryme.top/Article/details/gtzxsgakco.html

[T24] Swift：闭包
来源：http://dali.tanke756.top/Article/details/gtssimutqv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.redwolf501.top/Article/details/gtmhpiywlt.html

[T25] Swift：结构体
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwkldheao.html

struct P { var x: Int }
来源：http://dali.tanke756.top/Article/details/gtqqipnbmp.html

[T26] Swift：类与重写
来源：http://dali.ybcxt.top/Article/details/gteyedalzp.html

class A: Base { override func f() {} }
来源：http://dali.zhongyouzk.top/Article/details/gtzflywcbv.html

[T27] Swift：错误处理
来源：http://dali.yangfankeji.com/Article/details/gtxwezsdsg.html

do { try f() } catch { print(error) }
来源：http://dali.wangdashe.top/Article/details/gtrczcwwpk.html

[T28] Swift：枚举
来源：http://dali.nanxuanxn.top/Article/details/gtatlbydcy.html

enum Color { case red, green }
来源：http://dali.shangyingyoupin.top/Article/details/gtofaiufcv.html

[T29] Swift：guard 提前返回
来源：http://dali.aizwys.cn/Article/details/gtvswrzpqa.html

guard let x = opt else { return }
来源：http://dali.aibaodan.cn/Article/details/gtietzlknv.html

[T30] Swift：协议
来源：http://dali.nanxinkj.top/Article/details/gtzzvwalqy.html

protocol Shape { func area() -> Double }
来源：http://dali.nanxuanxn.top/Article/details/gtsbtnmukt.html

[T31] Lua：Hello World
来源：http://dali.0kj1m.cn/Article/details/gtdgtabxpp.html

print("Hello")
来源：http://dali.pycfn.com/Article/details/gtrdefxnlo.html

[T32] Lua：局部变量
来源：http://dali.mhx1999.top/Article/details/gtuyccdxyx.html

local a = 1
来源：http://dali.jqgufenzy.top/Article/details/gtqknfiilt.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gtjqhnnbcw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yj20258888.top/Article/details/gtxgwyeehy.html

[T34] Lua：遍历表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwhhjlakj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ehwqpu.com/Article/details/gtqccqacqy.html

[T35] Lua：字典表
来源：http://dali.jianghu66.top/Article/details/gtxdksvlue.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jlsjyb.cn/Article/details/gtfqppcqgo.html

[T36] Lua：函数
来源：http://dali.birdmap.top/Article/details/gtpcvujesy.html

function add(a, b) return a + b end
来源：http://dali.tian-w.cn/Article/details/gtjslroavx.html

[T37] Lua：字符串拼接
来源：http://dali.zhongyouzk.top/Article/details/gtkcbhxnei.html

"a" .. "b"
来源：http://dali.9152youxi.cn/Article/details/gtiswpgnph.html

[T38] Lua：条件
来源：http://dali.cashguo.top/Article/details/gtxnfximpw.html

if x > 0 then print("正") end
来源：http://dali.ehwqpu.com/Article/details/gtrmomwbfr.html

[T39] Lua：模式匹配
来源：http://dali.pycfn.com/Article/details/gtxmcpoydg.html

string.find(s, "%d+")
来源：http://dali.zhixingplan.top/Article/details/gtwrdaekep.html

[T40] Lua：元表
来源：http://dali.andypj.xyz/Article/details/gtbuisqtux.html

setmetatable({}, { __index = base })
来源：http://dali.jyoumei.cn/Article/details/gtuvhojpcs.html

[T41] Perl：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtkvqyagcu.html

print "Hello\n";
来源：http://dali.yuanzhike.top/Article/details/gtjvvdoxzq.html

[T42] Perl：变量类型
来源：http://dali.sxryk.cn/Article/details/gtsfxikrey.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.gogol.net.cn/Article/details/gttsbiushu.html

[T43] Perl：字符串插值
来源：http://dali.birdmap.top/Article/details/gtqaoseiwx.html

"值: $a"
来源：http://dali.vqdsnc.cn/Article/details/gtefyepggd.html

[T44] Perl：条件
来源：http://dali.ivvv.top/Article/details/gtgbxyckkt.html

if ($a > 0) { print "正"; }
来源：http://dali.jlsjyb.cn/Article/details/gtajbzfhpo.html


<!-- 参考信息 -->