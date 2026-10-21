代发 wailian999

find . -name "*.log" -type f
来源：http://dali.kuanghao11.cn/Article/details/gttppqlpve.html

[R44] 按修改时间查找
来源：http://dali.hywenlv.cn/Article/details/gtliklwrtj.html

find . -mtime -7 -type f
来源：http://dali.cqqwz.cn/Article/details/gtkkvlguqw.html

[R45] 批量删除
来源：http://dali.xuanzx.com/Article/details/gtmachqwpl.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gthdzkeonk.html

[R46] 递归替换文件内容
来源：http://dali.cqqwz.cn/Article/details/gtlufyczyk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xuetiantiany.cn/Article/details/gtvvqemqlt.html

[R47] sed 单行替换
来源：http://dali.wangdashe.top/Article/details/gtfshtorkp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xinyue.icu/Article/details/gtgpulzdnh.html

[R48] awk 取指定列
来源：http://dali.c1oappe.top/Article/details/gtzclpghtk.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtekivrsjq.html

[R49] awk 带条件
来源：http://dali.quarkkingdee.top/Article/details/gtzowpfwys.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yongpay.top/Article/details/gtdnhfvdbg.html

[R50] awk 求和
来源：http://dali.guannengcc.top/Article/details/gtfuimyobn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.fzhhl.top/Article/details/gthrhsdtho.html

[R51] 排序去重取前几
来源：http://dali.quarkkingdee.top/Article/details/gtmtbtuega.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gotoacloud.top/Article/details/gtikibymqu.html

[R52] 统计行数
来源：http://dali.yj20258888.top/Article/details/gtgxevyspm.html

wc -l a.txt
来源：http://dali.cheryme.top/Article/details/gtbvksgfws.html

[R53] 查看文件头与实时尾
来源：http://dali.pengpengdd.cyou/Article/details/gtijufuypd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.aibaodan.cn/Article/details/gtkgahxfiq.html

[R54] 比较两个文件
来源：http://dali.pycfn.com/Article/details/gtjvnbgtou.html

diff a.txt b.txt
来源：http://dali.iojbl.cn/Article/details/gtdcoxqbtq.html

[R55] 压缩与解压
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzgnayvxj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shuidangran.top/Article/details/gtpoabizgb.html

[R56] 远程拷贝
来源：http://dali.daria6918.cn/Article/details/gtnfmbcuwh.html

scp file user@host:/path/
来源：http://dali.chenzaomai.com/Article/details/gttzdpxuyl.html

[R57] 远程执行命令
来源：http://dali.yj20258.top/Article/details/gtdoafzaah.html

ssh user@host 'uptime'
来源：http://dali.aibaodan.cn/Article/details/gtbaajspvf.html

[R58] 下载文件
来源：http://dali.guowangkeji.top/Article/details/gtrwzlcqlb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhixingplan.top/Article/details/gtsgjdzahi.html

[R59] 发 POST JSON
来源：http://dali.iojbl.cn/Article/details/gtazfpqtdl.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hywenlv.cn/Article/details/gtsmngatrz.html

[R60] 只看 HTTP 状态码
来源：http://dali.xuetiantiany.cn/Article/details/gtqwwteikr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ehwqpu.com/Article/details/gtnozwqqmw.html

[R61] 磁盘占用
来源：http://dali.shanyushiyangtech.top/Article/details/gttdsmwkwa.html

df -h;  du -sh *
来源：http://dali.nwbrower.top/Article/details/gtqpulzhgy.html

[R62] 找最占空间的文件
来源：http://dali.xuetiantiany.cn/Article/details/gtyvgnkilq.html

du -ah . | sort -rh | head -10
来源：http://dali.c1oappe.top/Article/details/gtvrkhhyup.html

[R63] 内存与进程
来源：http://dali.fengsongda.top/Article/details/gtfoyveiry.html

free -h;  ps aux | grep nginx
来源：http://dali.mhx1999.top/Article/details/gthxofjdyj.html

[R64] 结束进程
来源：http://dali.fzhhl.top/Article/details/gtohphnmia.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cqqwz.cn/Article/details/gtgbhfpdtc.html

[R65] 查看端口占用
来源：http://dali.pycfn.com/Article/details/gteheipjdw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xinyue.icu/Article/details/gtfazvjvxz.html

[R66] 定时任务
来源：http://dali.gzhubu.top/Article/details/gtttwellyj.html

crontab -e;  crontab -l
来源：http://dali.daria6918.cn/Article/details/gtgpbcjqya.html

[R67] 生成随机十六进制串
来源：http://dali.ppjwa.cn/Article/details/gtzvefgpib.html

openssl rand -hex 16
来源：http://dali.xinyue.icu/Article/details/gtasspesuc.html

[R68] 计算文件校验值
来源：http://dali.mhx1999.top/Article/details/gtmzsnbpdc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.svipenyu.cn/Article/details/gtneqjbqhp.html

[R69] 生成随机密码
来源：http://dali.ppjwa.cn/Article/details/gtcepytaka.html

head -c 16 /dev/urandom | base64
来源：http://dali.hongshengwenyu.top/Article/details/gtnthivduz.html

[R70] 时间戳与互转
来源：http://dali.0kj1m.cn/Article/details/gtfypbddar.html

date +%s;  date -d @1700000000
来源：http://dali.zycfv.cn/Article/details/gtjwmjraez.html

[R71] 日期格式化
来源：http://dali.yj20258888.top/Article/details/gttihwcoxo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhoulong.xyz/Article/details/gtfamtsrmy.html

[R72] 等待端口就绪
来源：http://dali.tianlin.xyz/Article/details/gtmfreeiry.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cashguo.top/Article/details/gtjvmnkgip.html

[R73] 分割大日志
来源：http://dali.yuxming.cn/Article/details/gtjezbcwgt.html

split -l 1000 big.log part_
来源：http://dali.xziqi.cn/Article/details/gtowxulfhl.html

[R74] 批量重命名
来源：http://dali.yangfankeji.com/Article/details/gtlvalatjp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sxryk.cn/Article/details/gtsfarzgwu.html

[R75] 导出环境变量
来源：http://dali.guannengcc.top/Article/details/gtcbxgzztd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yuxming.cn/Article/details/gttoampdlh.html

[R76] 使用临时文件
来源：http://dali.hywenlv.cn/Article/details/gtdfezsrph.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hysaishi.cn/Article/details/gteektgkkg.html

[R77] 读取用户输入
来源：http://dali.dianchejie.cn/Article/details/gtxmoohmlm.html

read -rp "请输入: " ans
来源：http://dali.316326.xyz/Article/details/gtppvferbt.html

[R78] 交互式菜单
来源：http://dali.yvedp.cn/Article/details/gtfnpymcvx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hywenlv.cn/Article/details/gtbplweouw.html

[R79] 解析命令行选项
来源：http://dali.shuidangran.top/Article/details/gthkdlhgje.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zdqjudy.top/Article/details/gtnbiqknru.html

[R80] 查看脚本执行耗时
来源：http://dali.sxryk.cn/Article/details/gttixhwtwa.html

time ./run.sh
来源：http://dali.yvedp.cn/Article/details/gtwsxxutnk.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtxpimhvec.html

S. C / C++ 专题
来源：http://dali.gogol.net.cn/Article/details/gtqornauma.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtusvzbfyo.html

[S01] C：Hello World
来源：http://dali.yangfankeji.com/Article/details/gthoczxdlg.html

#include <stdio.h>
来源：http://dali.hysaishi.cn/Article/details/gtflpntsss.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.9152youxi.cn/Article/details/gtqvifzecb.html

[S02] C：变量与格式化输出
来源：http://dali.nanxinkj.top/Article/details/gtxzuhlcbg.html

int a = 10; printf("%d\n", a);
来源：http://dali.yuanzhike.top/Article/details/gtzajdybny.html

[S03] C：读入整数
来源：http://dali.hywenlv.cn/Article/details/gttcoxrddk.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gtyzfrlasw.html

[S04] C：字符串复制
来源：http://dali.guannengcc.top/Article/details/gtlnhjrndg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.nwbrower.top/Article/details/gtecpumhkz.html

[S05] C：字符串长度
来源：http://dali.hongshengwenyu.top/Article/details/gtserbxdrz.html

strlen(s)
来源：http://dali.jiagoushi.top/Article/details/gtmayhhedh.html

[S06] C：字符串比较
来源：http://dali.shuidangran.top/Article/details/gtxpbkacnn.html

strcmp(a, b) == 0
来源：http://dali.guannengcc.top/Article/details/gtcgvhfqri.html

[S07] C：数组遍历求和
来源：http://dali.zhongyouzk.top/Article/details/gtjytxughd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gaohongyu789.top/Article/details/gtqpexdvtw.html

[S08] C：动态内存分配与释放
来源：http://dali.tian-w.cn/Article/details/gtdycdlcke.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.havefunace.top/Article/details/gtvdbxwnij.html

[S09] C：结构体定义与初始化
来源：http://dali.zhongyouzk.top/Article/details/gtajzhxfqs.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.nanxuanxn.top/Article/details/gteepqrkqt.html

[S10] C：指针与解引用
来源：http://dali.c1oappe.top/Article/details/gtqywqlrzi.html

int *p = &a;  *p = 5;
来源：http://dali.yvedp.cn/Article/details/gteffisehv.html

[S11] C：逐行读文件
来源：http://dali.xinyue.icu/Article/details/gtmuajipna.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shuidangran.top/Article/details/gtnvmymdds.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shanyushiyangtech.top/Article/details/gtaxdkache.html

fclose(f);
来源：http://dali.vqdsnc.cn/Article/details/gtrxzrveeo.html

[S12] C：写文件
来源：http://dali.cashguo.top/Article/details/gthxttsogi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.svipenyu.cn/Article/details/gtfbkkouud.html

[S13] C：宏定义
来源：http://dali.gogol.net.cn/Article/details/gtckxkdcfc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zdqjudy.top/Article/details/gtykosppnc.html

[S14] C：枚举
来源：http://dali.jinyuanbaomall.cn/Article/details/gtitscdtzn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xziqi.cn/Article/details/gtktlnctzw.html

[S15] C：类型转换
来源：http://dali.jqgufenzy.top/Article/details/gtsjvafyey.html

(double) a / b
来源：http://dali.jqgufenzy.top/Article/details/gtrmzhjksu.html

[S16] C：位操作置位
来源：http://dali.kuanghao11.cn/Article/details/gtezvburgh.html

x |= (1 << 3);
来源：http://dali.quarkkingdee.top/Article/details/gtmfdnkbbf.html

[S17] C：安全拼接字符串
来源：http://dali.jianghu66.top/Article/details/gtxlqjvbse.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.pengpengdd.cyou/Article/details/gtwspdeolx.html

[S18] C：命令行参数
来源：http://dali.jqgufenzy.top/Article/details/gtnztwzrvc.html

int main(int argc, char **argv)
来源：http://dali.quarkkingdee.top/Article/details/gtdhqrdoga.html

[S19] C：快速排序
来源：http://dali.chenzaomai.com/Article/details/gtiqzcljsh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.andypj.xyz/Article/details/gtqshuouuq.html

[S20] C：二分查找
来源：http://dali.yanxiufei.cn/Article/details/gtjlhlnnzs.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.wangshuangyany.cn/Article/details/gtwsfnoowk.html

[S21] C：字符类别判断
来源：http://dali.nanxuanxn.top/Article/details/gtlssfrgyw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yuxming.cn/Article/details/gttswkiizc.html

[S22] C：字符串转数字
来源：http://dali.yangfankeji.com/Article/details/gtfeiaufmu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ppjwa.cn/Article/details/gtwyygtsur.html

[S23] C：随机数
来源：http://dali.ppjwa.cn/Article/details/gtwlkgdqkg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gzhubu.top/Article/details/gtskxbcpsn.html

[S24] C：获取本地时间
来源：http://dali.cashguo.top/Article/details/gtdvatzljn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhixingplan.top/Article/details/gtkplpqqtg.html

[S25] C：内存拷贝
来源：http://dali.xuetiantiany.cn/Article/details/gtrbenaztg.html

memcpy(dst, src, n);
来源：http://dali.shuidangran.top/Article/details/gtmzbepwvs.html

[S26] C：内存清零
来源：http://dali.cucudq.cn/Article/details/gtmlsnqtoq.html

memset(a, 0, sizeof a);
来源：http://dali.hywenlv.cn/Article/details/gtzjwvuapc.html

[S27] C：定义常量
来源：http://dali.havefunace.top/Article/details/gtqzktywip.html

const double PI = 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gtwrsrasnv.html

[S28] C：静态变量
来源：http://dali.nanxuanxn.top/Article/details/gtosloghsk.html

static int counter = 0;
来源：http://dali.jqgufenzy.top/Article/details/gtskjdnirz.html

[S29] C：变参函数
来源：http://dali.zhiwuduotai.top/Article/details/gtnmemknvu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yueranfly.top/Article/details/gtlzqtzwgv.html

[S30] C：头文件保护
来源：http://dali.zdqjudy.top/Article/details/gtlqqvvuig.html

#ifndef X_H
来源：http://dali.hammf.cn/Article/details/gtahjkfudx.html

#define X_H
来源：http://dali.c1oappe.top/Article/details/gtxiirlaky.html

#endif
来源：http://dali.nanxinkj.top/Article/details/gtlcfcwatj.html

[S31] C++：Hello World
来源：http://dali.cucudq.cn/Article/details/gtenykwnty.html

#include <iostream>
来源：http://dali.jyoumei.cn/Article/details/gtkocnekpf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.daxiang520.top/Article/details/gtcwlzoxci.html

[S32] C++：字符串
来源：http://dali.jlsjyb.cn/Article/details/gtkfobjtvs.html

std::string s = "hi";  s += "!";
来源：http://dali.ydzc1.top/Article/details/gtbtfwloxr.html

[S33] C++：vector 增删
来源：http://dali.haohaochexian.top/Article/details/gtpjxavcjn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.tian-w.cn/Article/details/gtppzdegkv.html

[S34] C++：遍历 vector
来源：http://dali.zhengqikj.top/Article/details/gtyxmivhqz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shzxlz.cn/Article/details/gteaxfldwk.html

[S35] C++：map
来源：http://dali.hywenlv.cn/Article/details/gtgywdeuah.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shuidangran.top/Article/details/gtdebhhrsp.html

[S36] C++：unordered_map
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbdhyebuq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gtfbvsjsxg.html

[S37] C++：set
来源：http://dali.wangshuangyany.cn/Article/details/gttllqsfkc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sxryk.cn/Article/details/gtpzdjivfc.html

[S38] C++：排序
来源：http://dali.gotoacloud.top/Article/details/gtwdabwcos.html

std::sort(v.begin(), v.end());
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwqehmggm.html

[S39] C++：自定义比较器排序
来源：http://dali.meibo888.top/Article/details/gtzskfzske.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.svipenyu.cn/Article/details/gtnemockah.html

[S40] C++：查找元素
来源：http://dali.sweek.top/Article/details/gtjprjcqwe.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nanxuanxn.top/Article/details/gtkdnogksf.html

[S41] C++：类与构造函数
来源：http://dali.pycfn.com/Article/details/gtdgegmvbq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sxryk.cn/Article/details/gtogvsxsrs.html

[S42] C++：继承与虚函数
来源：http://dali.yj20258888.top/Article/details/gtiyusnpwr.html

class B : public Base { public: void f() override {} };
来源：http://dali.fengsongda.top/Article/details/gtkejnqzyq.html

[S43] C++：智能指针
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfabupoon.html

auto p = std::make_unique<int>(5);
来源：http://dali.sxryk.cn/Article/details/gtapaaectp.html

[S44] C++：引用传参
来源：http://dali.ivvv.top/Article/details/gttapdzect.html

void inc(int &x) { ++x; }
来源：http://dali.c1oappe.top/Article/details/gtpikyslkm.html

[S45] C++：lambda
来源：http://dali.jiagoushi.top/Article/details/gtraerevdy.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.nanxinkj.top/Article/details/gtzykilocf.html

[S46] C++：函数模板
来源：http://dali.feifeiyinyue.top/Article/details/gtozvqpebo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shzxlz.cn/Article/details/gtfxjkdwqv.html

[S47] C++：结构化绑定遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtixukssls.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jqgfzy.top/Article/details/gttruteaih.html

[S48] C++：逐行读文件
来源：http://dali.xylfe.cn/Article/details/gtfyqiwiqq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hfpthk.cn/Article/details/gtcctbuzyj.html

while (std::getline(in, line)) { }
来源：http://dali.jinqigfzy.top/Article/details/gtnajzhykg.html

[S49] C++：写文件
来源：http://dali.daxiang520.top/Article/details/gtjokuvpfy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cheryme.top/Article/details/gtxstursgt.html

[S50] C++：格式化数字
来源：http://dali.guannengcc.top/Article/details/gtucwsgfar.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.nwbrower.top/Article/details/gtvyozwufp.html

[S51] C++：显式类型转换
来源：http://dali.316326.xyz/Article/details/gtmuxqmiat.html

static_cast<double>(a) / b
来源：http://dali.aibaodan.cn/Article/details/gtszwxfqpm.html

[S52] C++：const 与 noexcept
来源：http://dali.cqqwz.cn/Article/details/gthsasvmnb.html

int size() const noexcept { return n_; }
来源：http://dali.xuetiantiany.cn/Article/details/gtbzprdmpw.html

[S53] C++：移动语义
来源：http://dali.yvedp.cn/Article/details/gtjhjukzww.html

std::vector<int> w = std::move(v);
来源：http://dali.shangyingyoupin.top/Article/details/gtefdrdmlc.html

[S54] C++：异常处理
来源：http://dali.kuanghao11.cn/Article/details/gtwyvpctwi.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.iojbl.cn/Article/details/gtrwexuqxu.html

[S55] C++：结构化绑定
来源：http://dali.daria6918.cn/Article/details/gtpftgckbv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sweek.top/Article/details/gtfcaiuixe.html

[S56] C++：optional
来源：http://dali.yj202588.top/Article/details/gttjhvbsiz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.chenlongwang.top/Article/details/gtbqiirtms.html

[S57] C++：编译期常量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqikadxah.html

constexpr int N = 10;
来源：http://dali.shzxlz.cn/Article/details/gtdvulazok.html

[S58] C++：命名空间
来源：http://dali.guowangkeji.top/Article/details/gtxvjxevdu.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhengqikj.top/Article/details/gthwdljfrv.html

[S59] C++：静态断言
来源：http://dali.dianchejie.cn/Article/details/gtyvupehgb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.smart0.xyz/Article/details/gtzlqcvyax.html

[S60] C++：遍历并删除元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjdqxbukb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.tanke756.top/Article/details/gthgnmfcom.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtjnemboun.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhixingplan.top/Article/details/gtxbwyuyin.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtcsnppgrm.html

[T01] Kotlin：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtsfrjpfbc.html

println("Hello")
来源：http://dali.jianghu66.top/Article/details/gtdcchjwel.html

[T02] Kotlin：变量
来源：http://dali.ppjwa.cn/Article/details/gtfqnvcbvz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.meibo888.top/Article/details/gtzpsvrdvj.html

[T03] Kotlin：字符串模板
来源：http://dali.hnxiangtu.top/Article/details/gtfnkdhvwz.html

"值: $b"
来源：http://dali.316326.xyz/Article/details/gtcuonqqnw.html

[T04] Kotlin：空安全
来源：http://dali.gogol.net.cn/Article/details/gtwrmjfhec.html

val n: String? = null;  n?.length
来源：http://dali.316326.xyz/Article/details/gtlealxmqn.html

[T05] Kotlin：when 表达式
来源：http://dali.zhiwuduotai.top/Article/details/gtjqyvsolf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.snrcjt.cn/Article/details/gtjzfqzjdk.html

[T06] Kotlin：集合映射
来源：http://dali.ivvv.top/Article/details/gtzlssryob.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwsgohhla.html

[T07] Kotlin：集合过滤
来源：http://dali.cheryme.top/Article/details/gtfxbcjohd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hongshengwenyu.top/Article/details/gtxrrwvema.html

[T08] Kotlin：数据类
来源：http://dali.hfpthk.cn/Article/details/gtqoixnfeu.html

data class User(val name: String, val age: Int)
来源：http://dali.zhongyouzk.top/Article/details/gtysbmhsuz.html

[T09] Kotlin：扩展函数
来源：http://dali.gaohongyu789.top/Article/details/gtddomczed.html

fun String.exclaim() = this + "!"
来源：http://dali.316326.xyz/Article/details/gtygkhymjq.html

[T10] Kotlin：默认参数
来源：http://dali.pengpengdd.cyou/Article/details/gtdihjarde.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.daxiang520.top/Article/details/gtdmtgtymo.html

[T11] Kotlin：协程
来源：http://dali.gzhubu.top/Article/details/gtqlwchjlf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hongshengwenyu.top/Article/details/gtouhvwqtx.html

[T12] Kotlin：解构声明
来源：http://dali.shuidangran.top/Article/details/gtvqyhdedc.html

val (a, b) = Pair(1, 2)
来源：http://dali.gogol.net.cn/Article/details/gtsbrvnunt.html

[T13] Kotlin：只读 Map
来源：http://dali.cucudq.cn/Article/details/gthpxblroo.html

val m = mapOf("a" to 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtugryzhzv.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gtpgvrlcip.html

for (i in 1..10) println(i)
来源：http://dali.cdnleiting.top/Article/details/gtsgzzvvll.html

[T15] Kotlin：接口
来源：http://dali.cheryme.top/Article/details/gtgnxvzlza.html

interface Shape { fun area(): Double }
来源：http://dali.c1oappe.top/Article/details/gtblskcqxl.html

[T16] Swift：Hello World
来源：http://dali.cashguo.top/Article/details/gtutdwkyoy.html

print("Hello")
来源：http://dali.tian-w.cn/Article/details/gtvjelqtho.html

[T17] Swift：变量与常量
来源：http://dali.feifeiyinyue.top/Article/details/gtxzcbwmoc.html

var a = 1;  let b = 2
来源：http://dali.hfpthk.cn/Article/details/gtmibddsuk.html

[T18] Swift：字符串插值
来源：http://dali.bjfxy.top/Article/details/gtlmywzswe.html

"值: \(b)"
来源：http://dali.cheryme.top/Article/details/gtgaoihspm.html

[T19] Swift：可选绑定
来源：http://dali.yonumen.top/Article/details/gtzibfgzpv.html

if let n = opt { print(n) }
来源：http://dali.yueranfly.top/Article/details/gtldrdhhuy.html

[T20] Swift：数组操作
来源：http://dali.jqgfzy.top/Article/details/gtndbkhdjx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.daria6918.cn/Article/details/gtyfhyllno.html

[T21] Swift：遍历
来源：http://dali.zycfv.cn/Article/details/gtajitjmdp.html

for x in a { print(x) }
来源：http://dali.chenjidiqi.icu/Article/details/gtmbytfext.html

[T22] Swift：字典
来源：http://dali.zhiwuduotai.top/Article/details/gtayysswyy.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.c1oappe.top/Article/details/gtavuabvbg.html

[T23] Swift：函数
来源：http://dali.nanxuanxn.top/Article/details/gtfxpjdklb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.dashuyun.cn/Article/details/gttdphadur.html

[T24] Swift：闭包
来源：http://dali.zycfv.cn/Article/details/gtbraldycb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hywenlv.cn/Article/details/gtalbcbnmc.html

[T25] Swift：结构体
来源：http://dali.chenjidiqi.icu/Article/details/gtfnwzcsny.html

struct P { var x: Int }
来源：http://dali.9152youxi.cn/Article/details/gtgtmomskm.html

[T26] Swift：类与重写
来源：http://dali.guowangkeji.top/Article/details/gtafryoits.html

class A: Base { override func f() {} }
来源：http://dali.yj202588.top/Article/details/gtnlehhiii.html

[T27] Swift：错误处理
来源：http://dali.nwbrower.top/Article/details/gtuxzmmwdf.html

do { try f() } catch { print(error) }
来源：http://dali.yj20258888.top/Article/details/gtzdobdvwr.html

[T28] Swift：枚举
来源：http://dali.cdnleiting.top/Article/details/gtjvynrhob.html

enum Color { case red, green }
来源：http://dali.aizwys.cn/Article/details/gtaubweiog.html

[T29] Swift：guard 提前返回
来源：http://dali.birdmap.top/Article/details/gtxufacmpw.html

guard let x = opt else { return }
来源：http://dali.nwbrower.top/Article/details/gttryynzum.html

[T30] Swift：协议
来源：http://dali.cashguo.top/Article/details/gtmrklybfh.html

protocol Shape { func area() -> Double }
来源：http://dali.wangshuangyany.cn/Article/details/gtdrmhfxex.html

[T31] Lua：Hello World
来源：http://dali.ydzc1.top/Article/details/gttujcxdov.html

print("Hello")
来源：http://dali.ppjwa.cn/Article/details/gtpjzlelgd.html

[T32] Lua：局部变量
来源：http://dali.guowangkeji.top/Article/details/gtjurpfeiz.html

local a = 1
来源：http://dali.yongpay.top/Article/details/gtzgdmbhzt.html

[T33] Lua：表（数组）
来源：http://dali.meibo888.top/Article/details/gtgenwjwom.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yvedp.cn/Article/details/gtcrmrtvco.html

[T34] Lua：遍历表
来源：http://dali.redwolf501.top/Article/details/gtchvbikhn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.chenlongwang.top/Article/details/gtmgxqolfj.html

[T35] Lua：字典表
来源：http://dali.shanyushiyangtech.top/Article/details/gtxqlrzfhb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yonumen.top/Article/details/gtcyocimyd.html

[T36] Lua：函数
来源：http://dali.316326.xyz/Article/details/gtuzitvoco.html

function add(a, b) return a + b end
来源：http://dali.jqgufenzy.top/Article/details/gtgvaudhst.html

[T37] Lua：字符串拼接
来源：http://dali.jqgufenzy.top/Article/details/gtofwyyqnb.html

"a" .. "b"
来源：http://dali.sufxvd.cn/Article/details/gtbkjgfrrb.html

[T38] Lua：条件
来源：http://dali.zycfv.cn/Article/details/gttctbyjfe.html

if x > 0 then print("正") end
来源：http://dali.chenjidiqi.icu/Article/details/gttfxntsrt.html

[T39] Lua：模式匹配
来源：http://dali.tianlin.xyz/Article/details/gtxthruskt.html

string.find(s, "%d+")
来源：http://dali.mhx1999.top/Article/details/gtwevhybqt.html

[T40] Lua：元表
来源：http://dali.aizwys.cn/Article/details/gtlylclkbt.html

setmetatable({}, { __index = base })
来源：http://dali.zhoulong.xyz/Article/details/gtpvprrgcy.html

[T41] Perl：Hello World
来源：http://dali.sysykeji.top/Article/details/gtibitkekl.html

print "Hello\n";
来源：http://dali.sxryk.cn/Article/details/gtumoehftd.html

[T42] Perl：变量类型
来源：http://dali.snrcjt.cn/Article/details/gtzijfpcir.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jianghu66.top/Article/details/gtsywzafhe.html

[T43] Perl：字符串插值
来源：http://dali.yj202588.top/Article/details/gtqfwnemyq.html

"值: $a"
来源：http://dali.yonumen.top/Article/details/gtwiimowie.html

[T44] Perl：条件
来源：http://dali.wangdashe.top/Article/details/gtxyxsykrn.html

if ($a > 0) { print "正"; }
来源：http://dali.daria6918.cn/Article/details/gtygxsisvq.html

[T45] Perl：数组遍历
来源：http://dali.tianlin.xyz/Article/details/gtcmvmnnjr.html

for my $x (@arr) { print $x; }
来源：http://dali.sxryk.cn/Article/details/gtziwclxok.html

[T46] Perl：哈希操作
来源：http://dali.shangyingyoupin.top/Article/details/gtlttcrhug.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtdhshymvp.html


<!-- 参考信息 -->