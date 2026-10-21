代发 wailian999

find . -name "*.log" -type f
来源：http://dali.zhixingplan.top/Article/details/gtytsjwxvg.html

[R44] 按修改时间查找
来源：http://dali.daria6918.cn/Article/details/gtntpawzvs.html

find . -mtime -7 -type f
来源：http://dali.xuanzx.com/Article/details/gtshftxefh.html

[R45] 批量删除
来源：http://dali.andypj.xyz/Article/details/gtqccutwzo.html

find . -name "*.tmp" -delete
来源：http://dali.wangdashe.top/Article/details/gtemfitibp.html

[R46] 递归替换文件内容
来源：http://dali.ppjwa.cn/Article/details/gtyrppgxzx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.guannengcc.top/Article/details/gtydrldqbi.html

[R47] sed 单行替换
来源：http://dali.xuanzx.com/Article/details/gtpxrzjgpt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.svipenyu.cn/Article/details/gtrrmqnsum.html

[R48] awk 取指定列
来源：http://dali.zhiwuduotai.top/Article/details/gtvmnhftxw.html

awk '{print $1, $3}' a.txt
来源：http://dali.yangfankeji.com/Article/details/gtxlrpzvmj.html

[R49] awk 带条件
来源：http://dali.svipenyu.cn/Article/details/gtanyyyogf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xziqi.cn/Article/details/gtodbptabk.html

[R50] awk 求和
来源：http://dali.jinqigufen.top/Article/details/gtyudanlio.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hnxiangtu.top/Article/details/gtmhfaiscd.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gtbidkvsgy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.daxiang520.top/Article/details/gtdmyqsaim.html

[R52] 统计行数
来源：http://dali.dianchejie.cn/Article/details/gthhugyxdb.html

wc -l a.txt
来源：http://dali.cdnleiting.top/Article/details/gttmmasxye.html

[R53] 查看文件头与实时尾
来源：http://dali.jianghu66.top/Article/details/gtgzmkfcou.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yuanzhike.top/Article/details/gttwcyqpka.html

[R54] 比较两个文件
来源：http://dali.zdqjudy.top/Article/details/gtmigsqenb.html

diff a.txt b.txt
来源：http://dali.kuanghao11.cn/Article/details/gtzxudrdsq.html

[R55] 压缩与解压
来源：http://dali.yueranfly.top/Article/details/gtgushyvxo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinyuanbaomall.cn/Article/details/gtphlivrxw.html

[R56] 远程拷贝
来源：http://dali.cqqwz.cn/Article/details/gtmmhtxtso.html

scp file user@host:/path/
来源：http://dali.yuanzhike.top/Article/details/gtowfiqbci.html

[R57] 远程执行命令
来源：http://dali.jianghu66.top/Article/details/gttnlgtswv.html

ssh user@host 'uptime'
来源：http://dali.316326.xyz/Article/details/gtwwjprukb.html

[R58] 下载文件
来源：http://dali.tian-w.cn/Article/details/gtyvbfhzri.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.havefunace.top/Article/details/gtcpyjeijw.html

[R59] 发 POST JSON
来源：http://dali.ydzc1.top/Article/details/gtiisrurjd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.vqdsnc.cn/Article/details/gtvtuczjmi.html

[R60] 只看 HTTP 状态码
来源：http://dali.ppjwa.cn/Article/details/gtpcyzmfpl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.quarkkingdee.top/Article/details/gtobjgncde.html

[R61] 磁盘占用
来源：http://dali.iojbl.cn/Article/details/gtwvnchiwh.html

df -h;  du -sh *
来源：http://dali.chenjidiqi.icu/Article/details/gtbscsoyur.html

[R62] 找最占空间的文件
来源：http://dali.ybcxt.top/Article/details/gtxpmuthhl.html

du -ah . | sort -rh | head -10
来源：http://dali.shzxlz.cn/Article/details/gtiktawhyw.html

[R63] 内存与进程
来源：http://dali.yj20258.top/Article/details/gtldohvebj.html

free -h;  ps aux | grep nginx
来源：http://dali.fengsongda.top/Article/details/gtyxlariqx.html

[R64] 结束进程
来源：http://dali.zhixingplan.top/Article/details/gtklepvans.html

kill -9 $(pgrep -f app.py)
来源：http://dali.quarkkingdee.top/Article/details/gthkdwwjql.html

[R65] 查看端口占用
来源：http://dali.hywenlv.cn/Article/details/gttqqsginr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shanyushiyangtech.top/Article/details/gtfmcffezd.html

[R66] 定时任务
来源：http://dali.birdmap.top/Article/details/gtjksmopoo.html

crontab -e;  crontab -l
来源：http://dali.zycfv.cn/Article/details/gtbyygggar.html

[R67] 生成随机十六进制串
来源：http://dali.bjfxy.top/Article/details/gtdnmjsdvv.html

openssl rand -hex 16
来源：http://dali.ehwqpu.com/Article/details/gtkhhsnovo.html

[R68] 计算文件校验值
来源：http://dali.jinghuilouyu.cn/Article/details/gtpknyjyjq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtngiilses.html

[R69] 生成随机密码
来源：http://dali.cdnleiting.top/Article/details/gtschlquuw.html

head -c 16 /dev/urandom | base64
来源：http://dali.guowangkeji.top/Article/details/gttgssxcob.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gtkhgshzsb.html

date +%s;  date -d @1700000000
来源：http://dali.iojbl.cn/Article/details/gtejmuhgwf.html

[R71] 日期格式化
来源：http://dali.sysykeji.top/Article/details/gtcqilkurz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.mhx1999.top/Article/details/gtmmckkrje.html

[R72] 等待端口就绪
来源：http://dali.pengpengdd.cyou/Article/details/gtsepymece.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.fengsongda.top/Article/details/gtbypdoggo.html

[R73] 分割大日志
来源：http://dali.9152youxi.cn/Article/details/gttjncezhc.html

split -l 1000 big.log part_
来源：http://dali.hammf.cn/Article/details/gtxmdnwxpw.html

[R74] 批量重命名
来源：http://dali.316326.xyz/Article/details/gttglgxjkh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhoulong.xyz/Article/details/gtbishlqfe.html

[R75] 导出环境变量
来源：http://dali.zdqjudy.top/Article/details/gtkvxnklof.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xylfe.cn/Article/details/gtxqhlcrxh.html

[R76] 使用临时文件
来源：http://dali.zycfv.cn/Article/details/gtciqbchhd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.haohaochexian.top/Article/details/gtuxnyiwjp.html

[R77] 读取用户输入
来源：http://dali.xylfe.cn/Article/details/gtceenpgcy.html

read -rp "请输入: " ans
来源：http://dali.bjfxy.top/Article/details/gtywqodtmg.html

[R78] 交互式菜单
来源：http://dali.yonumen.top/Article/details/gtivzgmrgd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.nwbrower.top/Article/details/gtuqqhnwde.html

[R79] 解析命令行选项
来源：http://dali.tianlin.xyz/Article/details/gtafwyynnm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hnqzz.top/Article/details/gtqbyawahg.html

[R80] 查看脚本执行耗时
来源：http://dali.aizwys.cn/Article/details/gtuoqtdbwt.html

time ./run.sh
来源：http://dali.yuanzhike.top/Article/details/gtmeephree.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtydunoqqd.html

S. C / C++ 专题
来源：http://dali.316326.xyz/Article/details/gtvlokibtg.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtviuobpua.html

[S01] C：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gtpyvealyu.html

#include <stdio.h>
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjblqagcw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jianghu66.top/Article/details/gthxdfnbor.html

[S02] C：变量与格式化输出
来源：http://dali.hongshengwenyu.top/Article/details/gteetqslnn.html

int a = 10; printf("%d\n", a);
来源：http://dali.kuanghao11.cn/Article/details/gteihvprtg.html

[S03] C：读入整数
来源：http://dali.daria6918.cn/Article/details/gtrcnyrpxt.html

int x; scanf("%d", &x);
来源：http://dali.yuxming.cn/Article/details/gtxsisyoqx.html

[S04] C：字符串复制
来源：http://dali.vqdsnc.cn/Article/details/gtvwyoebcz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.316326.xyz/Article/details/gtjcievlrz.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gtmwkqnnsm.html

strlen(s)
来源：http://dali.smart0.xyz/Article/details/gtmjzohuhn.html

[S06] C：字符串比较
来源：http://dali.zhiwuduotai.top/Article/details/gtlspflffl.html

strcmp(a, b) == 0
来源：http://dali.zhongyouzk.top/Article/details/gtsjlgqlom.html

[S07] C：数组遍历求和
来源：http://dali.ppjwa.cn/Article/details/gtkhdyjjok.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hongshengwenyu.top/Article/details/gtmftzyjdm.html

[S08] C：动态内存分配与释放
来源：http://dali.nanxuanxn.top/Article/details/gtxdfvcpqw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hnxiangtu.top/Article/details/gtvuvtyvcf.html

[S09] C：结构体定义与初始化
来源：http://dali.gaohongyu789.top/Article/details/gtzrigbqhg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jqgfzy.top/Article/details/gtnaxpoaug.html

[S10] C：指针与解引用
来源：http://dali.yvedp.cn/Article/details/gtmscqyhfa.html

int *p = &a;  *p = 5;
来源：http://dali.yueranfly.top/Article/details/gtfrslchdl.html

[S11] C：逐行读文件
来源：http://dali.xuetiantiany.cn/Article/details/gtxzxahgdh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ehwqpu.com/Article/details/gtmeqjfwzh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.chenlongwang.top/Article/details/gtetlxcqwh.html

fclose(f);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfblgratx.html

[S12] C：写文件
来源：http://dali.dianchejie.cn/Article/details/gtewlalmuw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jiagoushi.top/Article/details/gtcxkwblgv.html

[S13] C：宏定义
来源：http://dali.andypj.xyz/Article/details/gtynhtapfc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cashguo.top/Article/details/gtbbijwzcy.html

[S14] C：枚举
来源：http://dali.aizwys.cn/Article/details/gtkvspcepz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.chenjidiqi.icu/Article/details/gtlsckhnpq.html

[S15] C：类型转换
来源：http://dali.316326.xyz/Article/details/gtvsvvervf.html

(double) a / b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkeltndut.html

[S16] C：位操作置位
来源：http://dali.dianchejie.cn/Article/details/gtyxqjkwcn.html

x |= (1 << 3);
来源：http://dali.tanke756.top/Article/details/gtnzzrxruq.html

[S17] C：安全拼接字符串
来源：http://dali.ydzc1.top/Article/details/gtixdluoih.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xinyue.icu/Article/details/gthitwzfvv.html

[S18] C：命令行参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzvijtiys.html

int main(int argc, char **argv)
来源：http://dali.meibo888.top/Article/details/gtwknmjsow.html

[S19] C：快速排序
来源：http://dali.wangshuangyany.cn/Article/details/gtyfrqilua.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hammf.cn/Article/details/gtkdmbntjt.html

[S20] C：二分查找
来源：http://dali.sysykeji.top/Article/details/gtgcmshigt.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xuanzx.com/Article/details/gtwijfpqxc.html

[S21] C：字符类别判断
来源：http://dali.mhx1999.top/Article/details/gtahqdwxxm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jqgfzy.top/Article/details/gtzkpoeuyl.html

[S22] C：字符串转数字
来源：http://dali.zhixingplan.top/Article/details/gtrcxnmrbj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xinyue.icu/Article/details/gtlqphkifq.html

[S23] C：随机数
来源：http://dali.quarkkingdee.top/Article/details/gtnlevdeux.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.svipenyu.cn/Article/details/gtxlkbznwk.html

[S24] C：获取本地时间
来源：http://dali.vqdsnc.cn/Article/details/gttugxlkhu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jqgfzy.top/Article/details/gtdetwlxqm.html

[S25] C：内存拷贝
来源：http://dali.yongpay.top/Article/details/gtepdumxoa.html

memcpy(dst, src, n);
来源：http://dali.zhengqikj.top/Article/details/gtapkkgonf.html

[S26] C：内存清零
来源：http://dali.yj202588.top/Article/details/gtxqhwslhs.html

memset(a, 0, sizeof a);
来源：http://dali.yuxming.cn/Article/details/gtqokmfxnc.html

[S27] C：定义常量
来源：http://dali.shangyingyoupin.top/Article/details/gtbaubnnhl.html

const double PI = 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gtwijioppz.html

[S28] C：静态变量
来源：http://dali.ppjwa.cn/Article/details/gtuhgaagcf.html

static int counter = 0;
来源：http://dali.jinqigfzy.top/Article/details/gtkgjnkwio.html

[S29] C：变参函数
来源：http://dali.nwbrower.top/Article/details/gtqvhvzvvc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.tianlin.xyz/Article/details/gtyhlljxud.html

[S30] C：头文件保护
来源：http://dali.gogol.net.cn/Article/details/gtdhomlivs.html

#ifndef X_H
来源：http://dali.hongshengwenyu.top/Article/details/gtkynzmyof.html

#define X_H
来源：http://dali.xylfe.cn/Article/details/gteqqdsysp.html

#endif
来源：http://dali.meibo888.top/Article/details/gtabrbfffw.html

[S31] C++：Hello World
来源：http://dali.hywenlv.cn/Article/details/gtlguyytoo.html

#include <iostream>
来源：http://dali.zhongyouzk.top/Article/details/gtltlpqodz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtagzjpmqv.html

[S32] C++：字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtljzwvzon.html

std::string s = "hi";  s += "!";
来源：http://dali.tian-w.cn/Article/details/gtyblbeiuo.html

[S33] C++：vector 增删
来源：http://dali.xuetiantiany.cn/Article/details/gtkwhxrrjb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yongpay.top/Article/details/gtraicfucg.html

[S34] C++：遍历 vector
来源：http://dali.chenlongwang.top/Article/details/gtnltdkcxq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shangyingyoupin.top/Article/details/gtsbxusbix.html

[S35] C++：map
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuhlyzyvh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.meibo888.top/Article/details/gtpgbmtfxs.html

[S36] C++：unordered_map
来源：http://dali.cheryme.top/Article/details/gtzxwjciom.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nwbrower.top/Article/details/gtjiocehsk.html

[S37] C++：set
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaoyhiynk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shangyingyoupin.top/Article/details/gtozgamzbm.html

[S38] C++：排序
来源：http://dali.9152youxi.cn/Article/details/gtgtragtlq.html

std::sort(v.begin(), v.end());
来源：http://dali.cashguo.top/Article/details/gtgbnrcwrs.html

[S39] C++：自定义比较器排序
来源：http://dali.birdmap.top/Article/details/gtceiwvtli.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ivvv.top/Article/details/gtfudovfmz.html

[S40] C++：查找元素
来源：http://dali.vqdsnc.cn/Article/details/gtlghzrcdx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hammf.cn/Article/details/gtkpbpislm.html

[S41] C++：类与构造函数
来源：http://dali.jinqigfzy.top/Article/details/gtscghqdsy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sufxvd.cn/Article/details/gtpbgapbmk.html

[S42] C++：继承与虚函数
来源：http://dali.yuxming.cn/Article/details/gtkitrrncy.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhengqikj.top/Article/details/gtpgfevyyq.html

[S43] C++：智能指针
来源：http://dali.havefunace.top/Article/details/gtsarzjfrn.html

auto p = std::make_unique<int>(5);
来源：http://dali.cashguo.top/Article/details/gtltvbijrn.html

[S44] C++：引用传参
来源：http://dali.shanyushiyangtech.top/Article/details/gtjwzomfoo.html

void inc(int &x) { ++x; }
来源：http://dali.fengsongda.top/Article/details/gtrsnfejsy.html

[S45] C++：lambda
来源：http://dali.jyoumei.cn/Article/details/gtswokbgkk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hysaishi.cn/Article/details/gttonplqzt.html

[S46] C++：函数模板
来源：http://dali.chenjidiqi.icu/Article/details/gtgfzkicsw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hnqzz.top/Article/details/gtkmwgkcog.html

[S47] C++：结构化绑定遍历
来源：http://dali.meibo888.top/Article/details/gtxyjbvkok.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gzhubu.top/Article/details/gtcrbujitg.html

[S48] C++：逐行读文件
来源：http://dali.xuanzx.com/Article/details/gtzigwhksi.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xuanzx.com/Article/details/gtuejnwnsl.html

while (std::getline(in, line)) { }
来源：http://dali.jlsjyb.cn/Article/details/gtfrwudsoz.html

[S49] C++：写文件
来源：http://dali.c1oappe.top/Article/details/gtxrfezuyn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.tanke756.top/Article/details/gtkpqfnplf.html

[S50] C++：格式化数字
来源：http://dali.xylfe.cn/Article/details/gtwfrqyexo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.dianchejie.cn/Article/details/gtmrphbbeo.html

[S51] C++：显式类型转换
来源：http://dali.9152youxi.cn/Article/details/gtmjyocabw.html

static_cast<double>(a) / b
来源：http://dali.fzhhl.top/Article/details/gthypoqtuf.html

[S52] C++：const 与 noexcept
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxffkxmbj.html

int size() const noexcept { return n_; }
来源：http://dali.tian-w.cn/Article/details/gtwagamofo.html

[S53] C++：移动语义
来源：http://dali.nwbrower.top/Article/details/gtpidvnlxn.html

std::vector<int> w = std::move(v);
来源：http://dali.ehwqpu.com/Article/details/gtujhidgov.html

[S54] C++：异常处理
来源：http://dali.ppjwa.cn/Article/details/gtqyrkixgx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.chenlongwang.top/Article/details/gtnboonqmb.html

[S55] C++：结构化绑定
来源：http://dali.tian-w.cn/Article/details/gtqxkpppyb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.vqdsnc.cn/Article/details/gtxximtcrp.html

[S56] C++：optional
来源：http://dali.nanxinkj.top/Article/details/gtivaysklu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.316326.xyz/Article/details/gtkrqsjlmp.html

[S57] C++：编译期常量
来源：http://dali.dashuyun.cn/Article/details/gttlalkysl.html

constexpr int N = 10;
来源：http://dali.fengsongda.top/Article/details/gtouudryum.html

[S58] C++：命名空间
来源：http://dali.yonumen.top/Article/details/gtbssbezrv.html

namespace ns { int f() { return 1; } }
来源：http://dali.ppjwa.cn/Article/details/gtyhzxhtpw.html

[S59] C++：静态断言
来源：http://dali.yangfankeji.com/Article/details/gtnfvxeicw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.9152youxi.cn/Article/details/gtrxqdfidy.html

[S60] C++：遍历并删除元素
来源：http://dali.daxiang520.top/Article/details/gtqxssddhb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hnxiangtu.top/Article/details/gtomfxjqqv.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtwcyxedbz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zycfv.cn/Article/details/gthbamqpiv.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtkdymnixf.html

[T01] Kotlin：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtmmnrduzy.html

println("Hello")
来源：http://dali.hnqzz.top/Article/details/gtwgiomvwl.html

[T02] Kotlin：变量
来源：http://dali.jlsjyb.cn/Article/details/gtydjwaosi.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yongpay.top/Article/details/gtunnwnrez.html

[T03] Kotlin：字符串模板
来源：http://dali.xuanzx.com/Article/details/gtxccpbznw.html

"值: $b"
来源：http://dali.hfpthk.cn/Article/details/gtevmeodtx.html

[T04] Kotlin：空安全
来源：http://dali.gzhubu.top/Article/details/gtdegbsmgw.html

val n: String? = null;  n?.length
来源：http://dali.yvedp.cn/Article/details/gtbcwiojdh.html

[T05] Kotlin：when 表达式
来源：http://dali.jlsjyb.cn/Article/details/gtuafinbog.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jlsjyb.cn/Article/details/gtqgrkhtdl.html

[T06] Kotlin：集合映射
来源：http://dali.9152youxi.cn/Article/details/gtgzfhvdyw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhixingplan.top/Article/details/gtbifwrkws.html

[T07] Kotlin：集合过滤
来源：http://dali.hnxiangtu.top/Article/details/gtwafkntpd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.guowangkeji.top/Article/details/gtnncdhjku.html

[T08] Kotlin：数据类
来源：http://dali.yuanzhike.top/Article/details/gtapgwzuld.html

data class User(val name: String, val age: Int)
来源：http://dali.yueranfly.top/Article/details/gtkxwwlscs.html

[T09] Kotlin：扩展函数
来源：http://dali.yangfankeji.com/Article/details/gtsztpzyyk.html

fun String.exclaim() = this + "!"
来源：http://dali.ehwqpu.com/Article/details/gtxmtjdgsq.html

[T10] Kotlin：默认参数
来源：http://dali.yj20258888.top/Article/details/gtqcyhhdgn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ydzc1.top/Article/details/gtllhklyca.html

[T11] Kotlin：协程
来源：http://dali.andypj.xyz/Article/details/gturaalrec.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.316326.xyz/Article/details/gtnqipsgtw.html

[T12] Kotlin：解构声明
来源：http://dali.pycfn.com/Article/details/gtztopkfbs.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkdycxlyg.html

[T13] Kotlin：只读 Map
来源：http://dali.guowangkeji.top/Article/details/gtnkjbhwfc.html

val m = mapOf("a" to 1)
来源：http://dali.ivvv.top/Article/details/gtwhahdzbv.html

[T14] Kotlin：循环
来源：http://dali.kuanghao11.cn/Article/details/gtybxoxylb.html

for (i in 1..10) println(i)
来源：http://dali.redwolf501.top/Article/details/gtatfltgux.html

[T15] Kotlin：接口
来源：http://dali.sxryk.cn/Article/details/gtwwjiaajo.html

interface Shape { fun area(): Double }
来源：http://dali.gotoacloud.top/Article/details/gtetgwbvhr.html

[T16] Swift：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtxogqddnd.html

print("Hello")
来源：http://dali.yongpay.top/Article/details/gthevzsmee.html

[T17] Swift：变量与常量
来源：http://dali.aibaodan.cn/Article/details/gtqvvvcmwl.html

var a = 1;  let b = 2
来源：http://dali.aizwys.cn/Article/details/gtjpltoxeb.html

[T18] Swift：字符串插值
来源：http://dali.yuxming.cn/Article/details/gtlcgctvjx.html

"值: \(b)"
来源：http://dali.hywenlv.cn/Article/details/gtgdkdmsgh.html

[T19] Swift：可选绑定
来源：http://dali.cheryme.top/Article/details/gtkccpooms.html

if let n = opt { print(n) }
来源：http://dali.haohaochexian.top/Article/details/gtxhoyqfzj.html

[T20] Swift：数组操作
来源：http://dali.nanxuanxn.top/Article/details/gtgecmyntt.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xuanzx.com/Article/details/gttlrfmljb.html

[T21] Swift：遍历
来源：http://dali.xuetiantiany.cn/Article/details/gthplfnxhy.html

for x in a { print(x) }
来源：http://dali.zhixingplan.top/Article/details/gtfiqmvtmq.html

[T22] Swift：字典
来源：http://dali.redwolf501.top/Article/details/gtlxecpnwd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.mhx1999.top/Article/details/gtcpfsgcrl.html

[T23] Swift：函数
来源：http://dali.jqgufenzy.top/Article/details/gtdmotescx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yueranfly.top/Article/details/gtmoonjbud.html

[T24] Swift：闭包
来源：http://dali.ivvv.top/Article/details/gtxxmezotj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.316326.xyz/Article/details/gtbcgmudrn.html

[T25] Swift：结构体
来源：http://dali.gzhubu.top/Article/details/gtmgljghdg.html

struct P { var x: Int }
来源：http://dali.hammf.cn/Article/details/gtabukkocc.html

[T26] Swift：类与重写
来源：http://dali.hywenlv.cn/Article/details/gtyprrotgq.html

class A: Base { override func f() {} }
来源：http://dali.xuanzx.com/Article/details/gtbdixykdb.html

[T27] Swift：错误处理
来源：http://dali.smart0.xyz/Article/details/gtdkxveqaq.html

do { try f() } catch { print(error) }
来源：http://dali.bjfxy.top/Article/details/gtdcnubycj.html

[T28] Swift：枚举
来源：http://dali.tanke756.top/Article/details/gtbbilpdit.html

enum Color { case red, green }
来源：http://dali.gogol.net.cn/Article/details/gtxbrxcpvv.html

[T29] Swift：guard 提前返回
来源：http://dali.hywenlv.cn/Article/details/gtvpvkmffn.html

guard let x = opt else { return }
来源：http://dali.ppjwa.cn/Article/details/gtbroktrgc.html

[T30] Swift：协议
来源：http://dali.cashguo.top/Article/details/gtlictzmic.html

protocol Shape { func area() -> Double }
来源：http://dali.sufxvd.cn/Article/details/gtqfeogogv.html

[T31] Lua：Hello World
来源：http://dali.shuidangran.top/Article/details/gtxcqlkwqz.html

print("Hello")
来源：http://dali.guowangkeji.top/Article/details/gtusrojlby.html

[T32] Lua：局部变量
来源：http://dali.cashguo.top/Article/details/gtstthpacf.html

local a = 1
来源：http://dali.xinyue.icu/Article/details/gtqyddphqg.html

[T33] Lua：表（数组）
来源：http://dali.shanyushiyangtech.top/Article/details/gtinksgjbw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.daria6918.cn/Article/details/gtgtiouwxs.html

[T34] Lua：遍历表
来源：http://dali.jqgufenzy.top/Article/details/gtpzwvgvhg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zdqjudy.top/Article/details/gtxdpibhnp.html

[T35] Lua：字典表
来源：http://dali.hnqzz.top/Article/details/gtgnywnnwz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.dashuyun.cn/Article/details/gtqnkmfueu.html

[T36] Lua：函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtawiontio.html

function add(a, b) return a + b end
来源：http://dali.yangfankeji.com/Article/details/gtuotjdjry.html

[T37] Lua：字符串拼接
来源：http://dali.kuanghao11.cn/Article/details/gtgkvbkbre.html

"a" .. "b"
来源：http://dali.dashuyun.cn/Article/details/gttawwskiv.html

[T38] Lua：条件
来源：http://dali.sysykeji.top/Article/details/gttxoimkoj.html

if x > 0 then print("正") end
来源：http://dali.haohaochexian.top/Article/details/gtpxjhyoxi.html

[T39] Lua：模式匹配
来源：http://dali.guannengcc.top/Article/details/gtquepbfza.html

string.find(s, "%d+")
来源：http://dali.zdqjudy.top/Article/details/gtnhrbprsw.html

[T40] Lua：元表
来源：http://dali.gogol.net.cn/Article/details/gtnaeqzuuz.html

setmetatable({}, { __index = base })
来源：http://dali.ppjwa.cn/Article/details/gtmufqzopx.html

[T41] Perl：Hello World
来源：http://dali.yangfankeji.com/Article/details/gtljkisfpw.html

print "Hello\n";
来源：http://dali.316326.xyz/Article/details/gtxmbntafw.html

[T42] Perl：变量类型
来源：http://dali.9152youxi.cn/Article/details/gtsdgroyup.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.vqdsnc.cn/Article/details/gtcscxyxzw.html

[T43] Perl：字符串插值
来源：http://dali.zycfv.cn/Article/details/gtnsjodkza.html

"值: $a"
来源：http://dali.yvedp.cn/Article/details/gtsxlnvkoi.html

[T44] Perl：条件
来源：http://dali.jlsjyb.cn/Article/details/gtceqbcylj.html

if ($a > 0) { print "正"; }
来源：http://dali.gaohongyu789.top/Article/details/gtaxwtletk.html

[T45] Perl：数组遍历
来源：http://dali.jlsjyb.cn/Article/details/gtpnfgghrc.html

for my $x (@arr) { print $x; }
来源：http://dali.yangfankeji.com/Article/details/gtzjemflvg.html

[T46] Perl：哈希操作
来源：http://dali.cqqwz.cn/Article/details/gtojgiqtud.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yvedp.cn/Article/details/gtqzdsvbzc.html


<!-- 参考信息 -->