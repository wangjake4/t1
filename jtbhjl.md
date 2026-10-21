代发 wailian999

cmd > out.log 2>&1
来源：http://dali.jianghu66.top/Article/details/gtniuzkgjw.html

[R40] 追加写日志
来源：http://dali.ppjwa.cn/Article/details/gtwavwwxrw.html

echo "log" >> out.log
来源：http://dali.chenzaomai.com/Article/details/gtzdirbsux.html

[R41] 丢弃输出
来源：http://dali.pengpengdd.cyou/Article/details/gtauwbsjhc.html

cmd >/dev/null 2>&1
来源：http://dali.jinqigufen.top/Article/details/gtsdwcipse.html

[R42] 输入重定向
来源：http://dali.zhaomingkeji.xyz/Article/details/gtooqbzgzz.html

wc -l < a.txt
来源：http://dali.jqgfzy.top/Article/details/gthmrlwmvm.html

[R43] 按名字查找文件
来源：http://dali.birdmap.top/Article/details/gthlruxmky.html

find . -name "*.log" -type f
来源：http://dali.c1oappe.top/Article/details/gtfbvxvvwq.html

[R44] 按修改时间查找
来源：http://dali.jqgfzy.top/Article/details/gtuykpwrsp.html

find . -mtime -7 -type f
来源：http://dali.jinqigufen.top/Article/details/gtjyxgzqnz.html

[R45] 批量删除
来源：http://dali.yuxming.cn/Article/details/gtjnjeklmu.html

find . -name "*.tmp" -delete
来源：http://dali.cashguo.top/Article/details/gtwunhabmm.html

[R46] 递归替换文件内容
来源：http://dali.cqqwz.cn/Article/details/gtaqzfqcwd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhixingplan.top/Article/details/gtllcrvmpr.html

[R47] sed 单行替换
来源：http://dali.yongpay.top/Article/details/gttzxhvtql.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtsezvhdgu.html

[R48] awk 取指定列
来源：http://dali.jianghu66.top/Article/details/gtiwnmczps.html

awk '{print $1, $3}' a.txt
来源：http://dali.havefunace.top/Article/details/gttljbkuxl.html

[R49] awk 带条件
来源：http://dali.xuanzx.com/Article/details/gtocvrjlbh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.chenzaomai.com/Article/details/gtsfznxflg.html

[R50] awk 求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlavjuwbv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cucudq.cn/Article/details/gtkohhnxfp.html

[R51] 排序去重取前几
来源：http://dali.shuidangran.top/Article/details/gtkkjkztgz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yonumen.top/Article/details/gtslobgtqk.html

[R52] 统计行数
来源：http://dali.wangshuangyany.cn/Article/details/gtnlixfmom.html

wc -l a.txt
来源：http://dali.iojbl.cn/Article/details/gtfqrdgxhy.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gtyjboqtbh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cqqwz.cn/Article/details/gtngarfkzj.html

[R54] 比较两个文件
来源：http://dali.shzxlz.cn/Article/details/gtxvpvcjab.html

diff a.txt b.txt
来源：http://dali.c1oappe.top/Article/details/gtczufidtx.html

[R55] 压缩与解压
来源：http://dali.tian-w.cn/Article/details/gtcgcmsfvc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yonumen.top/Article/details/gtgdgjvsel.html

[R56] 远程拷贝
来源：http://dali.cucudq.cn/Article/details/gtahwgejex.html

scp file user@host:/path/
来源：http://dali.yj20258888.top/Article/details/gtemmstbfp.html

[R57] 远程执行命令
来源：http://dali.dianchejie.cn/Article/details/gtorexdodk.html

ssh user@host 'uptime'
来源：http://dali.gzhubu.top/Article/details/gtgmalywjb.html

[R58] 下载文件
来源：http://dali.redwolf501.top/Article/details/gtmqtdzchk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jinqigfzy.top/Article/details/gtqcyocfdm.html

[R59] 发 POST JSON
来源：http://dali.fengsongda.top/Article/details/gtccdecfpx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shanyushiyangkeji.top/Article/details/gthfmenytn.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhixingplan.top/Article/details/gtgkgkmdnk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sweek.top/Article/details/gtxxvgsref.html

[R61] 磁盘占用
来源：http://dali.birdmap.top/Article/details/gtyouarfjd.html

df -h;  du -sh *
来源：http://dali.yj202588.top/Article/details/gtjkioqvdy.html

[R62] 找最占空间的文件
来源：http://dali.nanxuanxn.top/Article/details/gtsrfapzmd.html

du -ah . | sort -rh | head -10
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjqkqocxf.html

[R63] 内存与进程
来源：http://dali.0kj1m.cn/Article/details/gtktlqdbyc.html

free -h;  ps aux | grep nginx
来源：http://dali.0kj1m.cn/Article/details/gtodrhlstj.html

[R64] 结束进程
来源：http://dali.yanxiufei.cn/Article/details/gtzwbpejbo.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjeesqotp.html

[R65] 查看端口占用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtquvlmiqw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xylfe.cn/Article/details/gtercfvudh.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gtroyaqjxx.html

crontab -e;  crontab -l
来源：http://dali.zdqjudy.top/Article/details/gtgxtsmrxf.html

[R67] 生成随机十六进制串
来源：http://dali.svipenyu.cn/Article/details/gtcxbqtqpx.html

openssl rand -hex 16
来源：http://dali.ydzc1.top/Article/details/gtygscxmbv.html

[R68] 计算文件校验值
来源：http://dali.gzhubu.top/Article/details/gtsucgelxf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yj20258.top/Article/details/gticflimmy.html

[R69] 生成随机密码
来源：http://dali.shangyingyoupin.top/Article/details/gtjbzebgyw.html

head -c 16 /dev/urandom | base64
来源：http://dali.tian-w.cn/Article/details/gtalctpund.html

[R70] 时间戳与互转
来源：http://dali.xziqi.cn/Article/details/gtdelzbxlh.html

date +%s;  date -d @1700000000
来源：http://dali.dashuyun.cn/Article/details/gtgbbqynqf.html

[R71] 日期格式化
来源：http://dali.0kj1m.cn/Article/details/gtofnjozki.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xuanzx.com/Article/details/gthagbbsks.html

[R72] 等待端口就绪
来源：http://dali.fengsongda.top/Article/details/gtwonmveqv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ybcxt.top/Article/details/gtbkhvpftc.html

[R73] 分割大日志
来源：http://dali.nanxinkj.top/Article/details/gtldwmbgws.html

split -l 1000 big.log part_
来源：http://dali.ehwqpu.com/Article/details/gtntucuifg.html

[R74] 批量重命名
来源：http://dali.shanyushiyangtech.top/Article/details/gtlylsdugx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.pengpengdd.cyou/Article/details/gtkxozsbes.html

[R75] 导出环境变量
来源：http://dali.guowangkeji.top/Article/details/gtcpveopre.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdqmxrqdm.html

[R76] 使用临时文件
来源：http://dali.xinyue.icu/Article/details/gthxqqisnn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.haohaochexian.top/Article/details/gtkzrulyex.html

[R77] 读取用户输入
来源：http://dali.dianchejie.cn/Article/details/gtputaegzi.html

read -rp "请输入: " ans
来源：http://dali.ivvv.top/Article/details/gtgvoulkaz.html

[R78] 交互式菜单
来源：http://dali.yuanzhike.top/Article/details/gtzzgphvml.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ppjwa.cn/Article/details/gtaktqxngp.html

[R79] 解析命令行选项
来源：http://dali.hongshengwenyu.top/Article/details/gtimqxvtji.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cucudq.cn/Article/details/gtktyayqti.html

[R80] 查看脚本执行耗时
来源：http://dali.sufxvd.cn/Article/details/gtfmgebnym.html

time ./run.sh
来源：http://dali.vqdsnc.cn/Article/details/gtmetbbvps.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtuqwvdycn.html

S. C / C++ 专题
来源：http://dali.zycfv.cn/Article/details/gtrappkdda.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtttlssmxt.html

[S01] C：Hello World
来源：http://dali.shzxlz.cn/Article/details/gthnfzvlkh.html

#include <stdio.h>
来源：http://dali.gaohongyu789.top/Article/details/gtgplbgezr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yongpay.top/Article/details/gtvlbejefr.html

[S02] C：变量与格式化输出
来源：http://dali.hysaishi.cn/Article/details/gtbztyrtjm.html

int a = 10; printf("%d\n", a);
来源：http://dali.iojbl.cn/Article/details/gtbukhxkar.html

[S03] C：读入整数
来源：http://dali.pengpengdd.cyou/Article/details/gtlsmayybb.html

int x; scanf("%d", &x);
来源：http://dali.chenzaomai.com/Article/details/gtnsuzdvvx.html

[S04] C：字符串复制
来源：http://dali.yuxming.cn/Article/details/gtwdpdqawj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.dashuyun.cn/Article/details/gteyzueatt.html

[S05] C：字符串长度
来源：http://dali.316326.xyz/Article/details/gtqgtbyark.html

strlen(s)
来源：http://dali.tanke756.top/Article/details/gtfetejubv.html

[S06] C：字符串比较
来源：http://dali.havefunace.top/Article/details/gtqmffwvma.html

strcmp(a, b) == 0
来源：http://dali.cdnleiting.top/Article/details/gtomwvcdci.html

[S07] C：数组遍历求和
来源：http://dali.pengpengdd.cyou/Article/details/gtexxorvmq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.nwbrower.top/Article/details/gtatgdceel.html

[S08] C：动态内存分配与释放
来源：http://dali.yongpay.top/Article/details/gttiktluwr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.pycfn.com/Article/details/gtgeflmfhr.html

[S09] C：结构体定义与初始化
来源：http://dali.chenjidiqi.icu/Article/details/gtekdrupbn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yvedp.cn/Article/details/gtpfyvwngr.html

[S10] C：指针与解引用
来源：http://dali.daxiang520.top/Article/details/gtfnpbofrg.html

int *p = &a;  *p = 5;
来源：http://dali.kuanghao11.cn/Article/details/gtdvskraxd.html

[S11] C：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gtfzolcvlx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xziqi.cn/Article/details/gtdysdtgvz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jlsjyb.cn/Article/details/gtselrbhwy.html

fclose(f);
来源：http://dali.ivvv.top/Article/details/gtrclbcwsc.html

[S12] C：写文件
来源：http://dali.shangyingyoupin.top/Article/details/gtdehbsoat.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnycqpmax.html

[S13] C：宏定义
来源：http://dali.yangfankeji.com/Article/details/gtymgcdfky.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jianghu66.top/Article/details/gtqfbengge.html

[S14] C：枚举
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnvidjxdq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yj20258.top/Article/details/gtxpqwuzbt.html

[S15] C：类型转换
来源：http://dali.gzhubu.top/Article/details/gtomignsxd.html

(double) a / b
来源：http://dali.zdqjudy.top/Article/details/gtdskdoxws.html

[S16] C：位操作置位
来源：http://dali.quarkkingdee.top/Article/details/gtrnifryuv.html

x |= (1 << 3);
来源：http://dali.havefunace.top/Article/details/gtpgzuqsmu.html

[S17] C：安全拼接字符串
来源：http://dali.redwolf501.top/Article/details/gtrfqhhozu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.gaohongyu789.top/Article/details/gtakeaptke.html

[S18] C：命令行参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjkezpxwy.html

int main(int argc, char **argv)
来源：http://dali.sxryk.cn/Article/details/gtpufgjcto.html

[S19] C：快速排序
来源：http://dali.jyoumei.cn/Article/details/gttfyvyers.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.kuanghao11.cn/Article/details/gtxaqdshee.html

[S20] C：二分查找
来源：http://dali.iojbl.cn/Article/details/gtaetklaga.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.chenlongwang.top/Article/details/gtbjybjabx.html

[S21] C：字符类别判断
来源：http://dali.jianghu66.top/Article/details/gthyghbkum.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jiagoushi.top/Article/details/gtuplriaqj.html

[S22] C：字符串转数字
来源：http://dali.zhengqikj.top/Article/details/gtpglqvguq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hammf.cn/Article/details/gtofgnvgkn.html

[S23] C：随机数
来源：http://dali.yuanzhike.top/Article/details/gtezepqcxe.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hammf.cn/Article/details/gtyqzulsum.html

[S24] C：获取本地时间
来源：http://dali.sysykeji.top/Article/details/gtajwwvvhz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.wangshuangyany.cn/Article/details/gtyudtaggs.html

[S25] C：内存拷贝
来源：http://dali.guannengcc.top/Article/details/gtvaarsuwi.html

memcpy(dst, src, n);
来源：http://dali.ybcxt.top/Article/details/gtrcnaxjjq.html

[S26] C：内存清零
来源：http://dali.cdnleiting.top/Article/details/gttufvytuh.html

memset(a, 0, sizeof a);
来源：http://dali.mhx1999.top/Article/details/gtmxhtkast.html

[S27] C：定义常量
来源：http://dali.yanxiufei.cn/Article/details/gtyghuludl.html

const double PI = 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuqtccoor.html

[S28] C：静态变量
来源：http://dali.quarkkingdee.top/Article/details/gtdgidykoo.html

static int counter = 0;
来源：http://dali.yangfankeji.com/Article/details/gtovrnosrt.html

[S29] C：变参函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpdaokgtw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.wangshuangyany.cn/Article/details/gtbxvosejg.html

[S30] C：头文件保护
来源：http://dali.zdqjudy.top/Article/details/gtbvixafzr.html

#ifndef X_H
来源：http://dali.wangshuangyany.cn/Article/details/gtyhlpghfb.html

#define X_H
来源：http://dali.smart0.xyz/Article/details/gtfbgoxndu.html

#endif
来源：http://dali.chenzaomai.com/Article/details/gtrbipukak.html

[S31] C++：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtdkbfciql.html

#include <iostream>
来源：http://dali.sxryk.cn/Article/details/gtyjwxgkye.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhengqikj.top/Article/details/gtxnkntwmn.html

[S32] C++：字符串
来源：http://dali.daria6918.cn/Article/details/gtqxppcacz.html

std::string s = "hi";  s += "!";
来源：http://dali.yueranfly.top/Article/details/gtvludpjfi.html

[S33] C++：vector 增删
来源：http://dali.yvedp.cn/Article/details/gthepaktqk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hysaishi.cn/Article/details/gtefdecpan.html

[S34] C++：遍历 vector
来源：http://dali.yj202588.top/Article/details/gtmblzpqet.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cheryme.top/Article/details/gtcnbbqxqt.html

[S35] C++：map
来源：http://dali.bjfxy.top/Article/details/gtoefvblfr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.birdmap.top/Article/details/gthcaivlga.html

[S36] C++：unordered_map
来源：http://dali.zhaomingkeji.xyz/Article/details/gtudwqwydv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.snrcjt.cn/Article/details/gtsbosajfy.html

[S37] C++：set
来源：http://dali.shzxlz.cn/Article/details/gtavmszvdu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.fengsongda.top/Article/details/gtcgqztcsn.html

[S38] C++：排序
来源：http://dali.andypj.xyz/Article/details/gtatoifwiw.html

std::sort(v.begin(), v.end());
来源：http://dali.chenzaomai.com/Article/details/gtffggqwpk.html

[S39] C++：自定义比较器排序
来源：http://dali.zhongyouzk.top/Article/details/gtxamvtxhb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yangfankeji.com/Article/details/gtyulbdqbh.html

[S40] C++：查找元素
来源：http://dali.hnxiangtu.top/Article/details/gtxusfvfzk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yj20258.top/Article/details/gteqazvvvs.html

[S41] C++：类与构造函数
来源：http://dali.chenlongwang.top/Article/details/gtuazqnvlz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.haohaochexian.top/Article/details/gtwenobvnh.html

[S42] C++：继承与虚函数
来源：http://dali.ybcxt.top/Article/details/gtiithfywt.html

class B : public Base { public: void f() override {} };
来源：http://dali.guowangkeji.top/Article/details/gtrwxkteqf.html

[S43] C++：智能指针
来源：http://dali.hysaishi.cn/Article/details/gtsmvbixkv.html

auto p = std::make_unique<int>(5);
来源：http://dali.haohaochexian.top/Article/details/gtvqsmtnoj.html

[S44] C++：引用传参
来源：http://dali.hongshengwenyu.top/Article/details/gtshbcbvgo.html

void inc(int &x) { ++x; }
来源：http://dali.xuanzx.com/Article/details/gtwgjowbxe.html

[S45] C++：lambda
来源：http://dali.yj20258.top/Article/details/gtaqeccuhz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xuanzx.com/Article/details/gtwfmrckgy.html

[S46] C++：函数模板
来源：http://dali.ehwqpu.com/Article/details/gtwpenhuxk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.redwolf501.top/Article/details/gtygtolamn.html

[S47] C++：结构化绑定遍历
来源：http://dali.quarkkingdee.top/Article/details/gtsacvskzf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhengqikj.top/Article/details/gtcaonrtpu.html

[S48] C++：逐行读文件
来源：http://dali.xziqi.cn/Article/details/gtpaxlodii.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jqgfzy.top/Article/details/gthakzawvd.html

while (std::getline(in, line)) { }
来源：http://dali.nanxinkj.top/Article/details/gtyuaebqwg.html

[S49] C++：写文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyagghnbg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cashguo.top/Article/details/gtsjyysaax.html

[S50] C++：格式化数字
来源：http://dali.jyoumei.cn/Article/details/gtvnddjiat.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.daxiang520.top/Article/details/gtfinbyned.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gtodsdposj.html

static_cast<double>(a) / b
来源：http://dali.ybcxt.top/Article/details/gtkqbbmfrq.html

[S52] C++：const 与 noexcept
来源：http://dali.xinyue.icu/Article/details/gtvdznksjw.html

int size() const noexcept { return n_; }
来源：http://dali.yueranfly.top/Article/details/gtxlaavwid.html

[S53] C++：移动语义
来源：http://dali.chenjidiqi.icu/Article/details/gtuohcpzmw.html

std::vector<int> w = std::move(v);
来源：http://dali.nanxinkj.top/Article/details/gtsljhqnls.html

[S54] C++：异常处理
来源：http://dali.zhiwuduotai.top/Article/details/gtbglshxpe.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yj202588.top/Article/details/gtrgcitnzp.html

[S55] C++：结构化绑定
来源：http://dali.9152youxi.cn/Article/details/gtmrhdnzwn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hnqzz.top/Article/details/gtjeomnwfc.html

[S56] C++：optional
来源：http://dali.sufxvd.cn/Article/details/gtwwhjorwi.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gzhubu.top/Article/details/gtggtscxme.html

[S57] C++：编译期常量
来源：http://dali.daxiang520.top/Article/details/gtvgsfidqt.html

constexpr int N = 10;
来源：http://dali.fzhhl.top/Article/details/gtdqqgvlrr.html

[S58] C++：命名空间
来源：http://dali.chenjidiqi.icu/Article/details/gtluyposfw.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtsuqkrmsw.html

[S59] C++：静态断言
来源：http://dali.zdqjudy.top/Article/details/gtmwtdtlga.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnkujsptu.html

[S60] C++：遍历并删除元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gtafgsdphu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ivvv.top/Article/details/gtwibctzgp.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtsfsjsckw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nanxuanxn.top/Article/details/gtulnqrwyg.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtylkkmslb.html

[T01] Kotlin：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtouwffntj.html

println("Hello")
来源：http://dali.cucudq.cn/Article/details/gtwcqesigd.html

[T02] Kotlin：变量
来源：http://dali.smart0.xyz/Article/details/gtbvgncrsa.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zdqjudy.top/Article/details/gtehfvuyuo.html

[T03] Kotlin：字符串模板
来源：http://dali.dashuyun.cn/Article/details/gtgkbfgycu.html

"值: $b"
来源：http://dali.hfpthk.cn/Article/details/gtoyztwfac.html

[T04] Kotlin：空安全
来源：http://dali.ehwqpu.com/Article/details/gtzehevyla.html

val n: String? = null;  n?.length
来源：http://dali.yvedp.cn/Article/details/gtdheymafa.html

[T05] Kotlin：when 表达式
来源：http://dali.nanxinkj.top/Article/details/gtwflrksyy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.meibo888.top/Article/details/gtfdydiyly.html

[T06] Kotlin：集合映射
来源：http://dali.yonumen.top/Article/details/gthflwqjse.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yuanzhike.top/Article/details/gtidcinrbr.html

[T07] Kotlin：集合过滤
来源：http://dali.ehwqpu.com/Article/details/gtrdeohmji.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yongpay.top/Article/details/gtrtgzfjyv.html

[T08] Kotlin：数据类
来源：http://dali.nanxinkj.top/Article/details/gtqbvczhyg.html

data class User(val name: String, val age: Int)
来源：http://dali.ydzc1.top/Article/details/gtnxwrlmwi.html

[T09] Kotlin：扩展函数
来源：http://dali.hongshengwenyu.top/Article/details/gtnjusjeeo.html

fun String.exclaim() = this + "!"
来源：http://dali.jinghuilouyu.cn/Article/details/gtsmukaocf.html

[T10] Kotlin：默认参数
来源：http://dali.birdmap.top/Article/details/gtjfqlcuvb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zdqjudy.top/Article/details/gtojvxvoda.html

[T11] Kotlin：协程
来源：http://dali.gotoacloud.top/Article/details/gtketobpie.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.snrcjt.cn/Article/details/gtcqqkkndy.html

[T12] Kotlin：解构声明
来源：http://dali.cashguo.top/Article/details/gtotjbdolb.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gtxrwsejku.html

[T13] Kotlin：只读 Map
来源：http://dali.cdnleiting.top/Article/details/gtqzdodilh.html

val m = mapOf("a" to 1)
来源：http://dali.jqgufenzy.top/Article/details/gtrbtqfuln.html

[T14] Kotlin：循环
来源：http://dali.xinyue.icu/Article/details/gtpqgbfjvh.html

for (i in 1..10) println(i)
来源：http://dali.kuanghao11.cn/Article/details/gtulfgcrcp.html

[T15] Kotlin：接口
来源：http://dali.quarkkingdee.top/Article/details/gtnvnlqnpk.html

interface Shape { fun area(): Double }
来源：http://dali.sxryk.cn/Article/details/gtfthgxayb.html

[T16] Swift：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxmwiaoyb.html

print("Hello")
来源：http://dali.mhx1999.top/Article/details/gtjndmvrst.html

[T17] Swift：变量与常量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkdbpxznu.html

var a = 1;  let b = 2
来源：http://dali.xziqi.cn/Article/details/gtrgdpytvg.html

[T18] Swift：字符串插值
来源：http://dali.snrcjt.cn/Article/details/gtjwrqahni.html

"值: \(b)"
来源：http://dali.sxryk.cn/Article/details/gtjckczepd.html

[T19] Swift：可选绑定
来源：http://dali.yj20258.top/Article/details/gtfosflgag.html

if let n = opt { print(n) }
来源：http://dali.jqgufenzy.top/Article/details/gtxrbwmqid.html

[T20] Swift：数组操作
来源：http://dali.jinghuilouyu.cn/Article/details/gtcsddopjl.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ppjwa.cn/Article/details/gtjyngzlcl.html

[T21] Swift：遍历
来源：http://dali.daria6918.cn/Article/details/gticcoencc.html

for x in a { print(x) }
来源：http://dali.zhiwuduotai.top/Article/details/gtppohodtx.html

[T22] Swift：字典
来源：http://dali.wangdashe.top/Article/details/gtujsropzq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gotoacloud.top/Article/details/gtkcibiwoa.html

[T23] Swift：函数
来源：http://dali.xinyue.icu/Article/details/gtffhzmwas.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.daria6918.cn/Article/details/gtpibxpjjg.html

[T24] Swift：闭包
来源：http://dali.zdqjudy.top/Article/details/gtamajnugf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.redwolf501.top/Article/details/gtpriizsep.html

[T25] Swift：结构体
来源：http://dali.hysaishi.cn/Article/details/gtjmrahpil.html

struct P { var x: Int }
来源：http://dali.sufxvd.cn/Article/details/gtcdayhvtr.html

[T26] Swift：类与重写
来源：http://dali.zhongyouzk.top/Article/details/gtyywbcvht.html

class A: Base { override func f() {} }
来源：http://dali.316326.xyz/Article/details/gtnakzxwtq.html

[T27] Swift：错误处理
来源：http://dali.havefunace.top/Article/details/gtbknjzulx.html

do { try f() } catch { print(error) }
来源：http://dali.sysykeji.top/Article/details/gtfivpqdce.html

[T28] Swift：枚举
来源：http://dali.yueranfly.top/Article/details/gtcvqflzhk.html

enum Color { case red, green }
来源：http://dali.jianghu66.top/Article/details/gtyqoimjej.html

[T29] Swift：guard 提前返回
来源：http://dali.hongshengwenyu.top/Article/details/gtyoweaddv.html

guard let x = opt else { return }
来源：http://dali.gzhubu.top/Article/details/gtfzsvvhmk.html

[T30] Swift：协议
来源：http://dali.cdnleiting.top/Article/details/gtgrgeufwg.html

protocol Shape { func area() -> Double }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaiykppis.html

[T31] Lua：Hello World
来源：http://dali.ybcxt.top/Article/details/gturdjvdgn.html

print("Hello")
来源：http://dali.nanxuanxn.top/Article/details/gtolixcifi.html

[T32] Lua：局部变量
来源：http://dali.jinqigfzy.top/Article/details/gtxplyuhpq.html

local a = 1
来源：http://dali.pycfn.com/Article/details/gtxcjsbdge.html

[T33] Lua：表（数组）
来源：http://dali.feifeiyinyue.top/Article/details/gtktsnkhre.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shanyushiyangtech.top/Article/details/gtwsafralz.html

[T34] Lua：遍历表
来源：http://dali.nanxuanxn.top/Article/details/gtnqxsosrt.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.dianchejie.cn/Article/details/gthbaxwusa.html

[T35] Lua：字典表
来源：http://dali.sweek.top/Article/details/gtzshgpogy.html

local d = { a = 1 };  d.b = 2
来源：http://dali.redwolf501.top/Article/details/gtxidtbcty.html

[T36] Lua：函数
来源：http://dali.aizwys.cn/Article/details/gtzczfyldv.html

function add(a, b) return a + b end
来源：http://dali.zhengqikj.top/Article/details/gtmzvjxywv.html

[T37] Lua：字符串拼接
来源：http://dali.hammf.cn/Article/details/gtkvusqdzy.html

"a" .. "b"
来源：http://dali.ivvv.top/Article/details/gtlobrinlc.html

[T38] Lua：条件
来源：http://dali.wangdashe.top/Article/details/gthgqlwimx.html

if x > 0 then print("正") end
来源：http://dali.tanke756.top/Article/details/gtaoafikge.html

[T39] Lua：模式匹配
来源：http://dali.cqqwz.cn/Article/details/gtfnkzwxbv.html

string.find(s, "%d+")
来源：http://dali.hongshengwenyu.top/Article/details/gtxmqxcomq.html

[T40] Lua：元表
来源：http://dali.xziqi.cn/Article/details/gtrymvrlnk.html

setmetatable({}, { __index = base })
来源：http://dali.yj20258888.top/Article/details/gtmybzvqmx.html

[T41] Perl：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtgixxbqiw.html

print "Hello\n";
来源：http://dali.hysaishi.cn/Article/details/gtuzghgmfb.html

[T42] Perl：变量类型
来源：http://dali.ybcxt.top/Article/details/gtgeneqgxa.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cheryme.top/Article/details/gtskysyryl.html


<!-- 参考信息 -->