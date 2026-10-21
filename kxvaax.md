代发 wailian999

cmd > out.log 2>&1
来源：http://dali.zhengqikj.top/Article/details/gtheuyddwm.html

[R40] 追加写日志
来源：http://dali.sxryk.cn/Article/details/gtpecdllpg.html

echo "log" >> out.log
来源：http://dali.ybcxt.top/Article/details/gtzkkhvodf.html

[R41] 丢弃输出
来源：http://dali.cqqwz.cn/Article/details/gtdxajhlzd.html

cmd >/dev/null 2>&1
来源：http://dali.pycfn.com/Article/details/gtaiszqjep.html

[R42] 输入重定向
来源：http://dali.xinyue.icu/Article/details/gtwnsqmxdh.html

wc -l < a.txt
来源：http://dali.pycfn.com/Article/details/gtmnwiezap.html

[R43] 按名字查找文件
来源：http://dali.jinqigufen.top/Article/details/gtxuoeckvt.html

find . -name "*.log" -type f
来源：http://dali.yj20258.top/Article/details/gtatspgpoq.html

[R44] 按修改时间查找
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxysvaxjx.html

find . -mtime -7 -type f
来源：http://dali.yj20258888.top/Article/details/gtucykakhf.html

[R45] 批量删除
来源：http://dali.zhengqikj.top/Article/details/gtueojonzo.html

find . -name "*.tmp" -delete
来源：http://dali.haohaochexian.top/Article/details/gtiwsgbhju.html

[R46] 递归替换文件内容
来源：http://dali.quarkkingdee.top/Article/details/gtzlpdjyho.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.iojbl.cn/Article/details/gtrldwepau.html

[R47] sed 单行替换
来源：http://dali.xuanzx.com/Article/details/gtpviynwud.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ppjwa.cn/Article/details/gtgasmyqjx.html

[R48] awk 取指定列
来源：http://dali.dianchejie.cn/Article/details/gtunyshodm.html

awk '{print $1, $3}' a.txt
来源：http://dali.dashuyun.cn/Article/details/gtzooqxhyq.html

[R49] awk 带条件
来源：http://dali.yj20258888.top/Article/details/gttguclpaw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hongshengwenyu.top/Article/details/gtwmiysiyh.html

[R50] awk 求和
来源：http://dali.316326.xyz/Article/details/gtbqqxuwfd.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.nanxinkj.top/Article/details/gtuvmviwje.html

[R51] 排序去重取前几
来源：http://dali.jianghu66.top/Article/details/gtwepfcdgt.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shuidangran.top/Article/details/gtdjdkcbkr.html

[R52] 统计行数
来源：http://dali.chenzaomai.com/Article/details/gtkzbvssmm.html

wc -l a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtzfyibyqz.html

[R53] 查看文件头与实时尾
来源：http://dali.daxiang520.top/Article/details/gttpceqchg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinqigfzy.top/Article/details/gtdoalcjee.html

[R54] 比较两个文件
来源：http://dali.nanxuanxn.top/Article/details/gtesdacwjo.html

diff a.txt b.txt
来源：http://dali.andypj.xyz/Article/details/gtlourdtow.html

[R55] 压缩与解压
来源：http://dali.yongpay.top/Article/details/gtinimzuot.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ydzc1.top/Article/details/gtplixmjkz.html

[R56] 远程拷贝
来源：http://dali.snrcjt.cn/Article/details/gtwyohnflm.html

scp file user@host:/path/
来源：http://dali.xuetiantiany.cn/Article/details/gtxiboumqq.html

[R57] 远程执行命令
来源：http://dali.tianlin.xyz/Article/details/gtzzwpspai.html

ssh user@host 'uptime'
来源：http://dali.yvedp.cn/Article/details/gtsfxrqjve.html

[R58] 下载文件
来源：http://dali.xinyue.icu/Article/details/gtcdiunbwi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yanxiufei.cn/Article/details/gtjvnpmdzi.html

[R59] 发 POST JSON
来源：http://dali.yanxiufei.cn/Article/details/gtsahidmgg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hysaishi.cn/Article/details/gtzrxrsbxg.html

[R60] 只看 HTTP 状态码
来源：http://dali.cucudq.cn/Article/details/gtcdjnlptj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jqgufenzy.top/Article/details/gtxuuwcfwj.html

[R61] 磁盘占用
来源：http://dali.zdqjudy.top/Article/details/gtzgvewyva.html

df -h;  du -sh *
来源：http://dali.shuidangran.top/Article/details/gtepycvefl.html

[R62] 找最占空间的文件
来源：http://dali.hnqzz.top/Article/details/gttivzqnks.html

du -ah . | sort -rh | head -10
来源：http://dali.yongpay.top/Article/details/gtnpafkqkg.html

[R63] 内存与进程
来源：http://dali.hammf.cn/Article/details/gteawltwrj.html

free -h;  ps aux | grep nginx
来源：http://dali.c1oappe.top/Article/details/gtwfzbfsai.html

[R64] 结束进程
来源：http://dali.yj202588.top/Article/details/gtvabgzesu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhongyouzk.top/Article/details/gtiikilvds.html

[R65] 查看端口占用
来源：http://dali.hongshengwenyu.top/Article/details/gtaxvqcsdy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shuidangran.top/Article/details/gtdwbxibcs.html

[R66] 定时任务
来源：http://dali.cdnleiting.top/Article/details/gtfdtpimbs.html

crontab -e;  crontab -l
来源：http://dali.yonumen.top/Article/details/gtidnezdsg.html

[R67] 生成随机十六进制串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthjluvjdx.html

openssl rand -hex 16
来源：http://dali.zdqjudy.top/Article/details/gtpzxlivbq.html

[R68] 计算文件校验值
来源：http://dali.iojbl.cn/Article/details/gtuffbrrlg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jiagoushi.top/Article/details/gtrgizrpve.html

[R69] 生成随机密码
来源：http://dali.jiagoushi.top/Article/details/gtxbegxika.html

head -c 16 /dev/urandom | base64
来源：http://dali.jyoumei.cn/Article/details/gttilrgfvk.html

[R70] 时间戳与互转
来源：http://dali.jinghuilouyu.cn/Article/details/gtnxwoargn.html

date +%s;  date -d @1700000000
来源：http://dali.feifeiyinyue.top/Article/details/gtlpkgpspc.html

[R71] 日期格式化
来源：http://dali.ybcxt.top/Article/details/gtcnhqfgmh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.smart0.xyz/Article/details/gtympfcube.html

[R72] 等待端口就绪
来源：http://dali.shangyingyoupin.top/Article/details/gtpfplxsyt.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtwrudycti.html

[R73] 分割大日志
来源：http://dali.jiagoushi.top/Article/details/gtxnizmvau.html

split -l 1000 big.log part_
来源：http://dali.redwolf501.top/Article/details/gtfnveiugg.html

[R74] 批量重命名
来源：http://dali.zycfv.cn/Article/details/gtktknnpun.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gthtrsqrcb.html

[R75] 导出环境变量
来源：http://dali.hfpthk.cn/Article/details/gtlvqrwrcy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.316326.xyz/Article/details/gthqyckqve.html

[R76] 使用临时文件
来源：http://dali.sxryk.cn/Article/details/gtypxyyrrx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gaohongyu789.top/Article/details/gtelkupdeo.html

[R77] 读取用户输入
来源：http://dali.snrcjt.cn/Article/details/gtxoxcbiko.html

read -rp "请输入: " ans
来源：http://dali.ehwqpu.com/Article/details/gtozjdkvuo.html

[R78] 交互式菜单
来源：http://dali.cashguo.top/Article/details/gtgttbvdqf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xziqi.cn/Article/details/gteuxtqifl.html

[R79] 解析命令行选项
来源：http://dali.zycfv.cn/Article/details/gttpisbyof.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtigqrhvgi.html

[R80] 查看脚本执行耗时
来源：http://dali.havefunace.top/Article/details/gtohrlibzv.html

time ./run.sh
来源：http://dali.yuanzhike.top/Article/details/gthbzgchnh.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtvvuaqsxy.html

S. C / C++ 专题
来源：http://dali.zhoulong.xyz/Article/details/gtifaofgqy.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtnqtdtcvt.html

[S01] C：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtpyqdovsg.html

#include <stdio.h>
来源：http://dali.shanyushiyangkeji.top/Article/details/gtggshuadf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.guannengcc.top/Article/details/gtmvzwxjac.html

[S02] C：变量与格式化输出
来源：http://dali.aibaodan.cn/Article/details/gtqwtjjwnw.html

int a = 10; printf("%d\n", a);
来源：http://dali.daria6918.cn/Article/details/gtwwuqlqji.html

[S03] C：读入整数
来源：http://dali.svipenyu.cn/Article/details/gtdwsprrwm.html

int x; scanf("%d", &x);
来源：http://dali.shuidangran.top/Article/details/gtpqprkywq.html

[S04] C：字符串复制
来源：http://dali.daxiang520.top/Article/details/gtnjyzlmet.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.0kj1m.cn/Article/details/gtuipfsqis.html

[S05] C：字符串长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtntonolli.html

strlen(s)
来源：http://dali.9152youxi.cn/Article/details/gttdgmrdfr.html

[S06] C：字符串比较
来源：http://dali.aibaodan.cn/Article/details/gtyshscnsd.html

strcmp(a, b) == 0
来源：http://dali.snrcjt.cn/Article/details/gtfftepiqm.html

[S07] C：数组遍历求和
来源：http://dali.chenzaomai.com/Article/details/gtnhyzumij.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yj20258888.top/Article/details/gtqqufqynu.html

[S08] C：动态内存分配与释放
来源：http://dali.yongpay.top/Article/details/gtzdgftkks.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xziqi.cn/Article/details/gtszekxglp.html

[S09] C：结构体定义与初始化
来源：http://dali.shuidangran.top/Article/details/gtvgxlbyfw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.chenzaomai.com/Article/details/gtnjikodtq.html

[S10] C：指针与解引用
来源：http://dali.sweek.top/Article/details/gtlehkwhem.html

int *p = &a;  *p = 5;
来源：http://dali.quarkkingdee.top/Article/details/gtctvrndlb.html

[S11] C：逐行读文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtynwnbhqh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cheryme.top/Article/details/gtkzgfchoy.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sweek.top/Article/details/gtxvtjbtva.html

fclose(f);
来源：http://dali.yj20258888.top/Article/details/gtjuzuaueb.html

[S12] C：写文件
来源：http://dali.dashuyun.cn/Article/details/gtuzqgpzhc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xuetiantiany.cn/Article/details/gtkpkdjpfi.html

[S13] C：宏定义
来源：http://dali.c1oappe.top/Article/details/gtirmwuhbb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xuetiantiany.cn/Article/details/gtuydhwigw.html

[S14] C：枚举
来源：http://dali.cheryme.top/Article/details/gtqzfjhexw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.gogol.net.cn/Article/details/gtrwpbhbcy.html

[S15] C：类型转换
来源：http://dali.hysaishi.cn/Article/details/gtnxgqtudk.html

(double) a / b
来源：http://dali.xziqi.cn/Article/details/gtxjyichmc.html

[S16] C：位操作置位
来源：http://dali.kuanghao11.cn/Article/details/gtmvuheinj.html

x |= (1 << 3);
来源：http://dali.yuxming.cn/Article/details/gtbywbtigt.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gtxglzztkz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.daria6918.cn/Article/details/gtrrdvryga.html

[S18] C：命令行参数
来源：http://dali.jqgfzy.top/Article/details/gtxgtfbmxt.html

int main(int argc, char **argv)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgywaissb.html

[S19] C：快速排序
来源：http://dali.chenlongwang.top/Article/details/gtryznimsl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.aizwys.cn/Article/details/gtmsirddml.html

[S20] C：二分查找
来源：http://dali.iojbl.cn/Article/details/gtahtuyler.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.snrcjt.cn/Article/details/gttlelwric.html

[S21] C：字符类别判断
来源：http://dali.cheryme.top/Article/details/gtiatxhtpi.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.feifeiyinyue.top/Article/details/gtbbzaugbg.html

[S22] C：字符串转数字
来源：http://dali.yvedp.cn/Article/details/gtothhhzzm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdlqfmrxe.html

[S23] C：随机数
来源：http://dali.aizwys.cn/Article/details/gtzmaginbz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlxvyfqnz.html

[S24] C：获取本地时间
来源：http://dali.hammf.cn/Article/details/gtzrqzhalf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.c1oappe.top/Article/details/gtbgiosmnj.html

[S25] C：内存拷贝
来源：http://dali.guannengcc.top/Article/details/gtskamaokv.html

memcpy(dst, src, n);
来源：http://dali.jlsjyb.cn/Article/details/gtfdiqsbcg.html

[S26] C：内存清零
来源：http://dali.dashuyun.cn/Article/details/gtrhxrplae.html

memset(a, 0, sizeof a);
来源：http://dali.wangdashe.top/Article/details/gtolsrrask.html

[S27] C：定义常量
来源：http://dali.cqqwz.cn/Article/details/gtcmrpvbno.html

const double PI = 3.14159;
来源：http://dali.chenzaomai.com/Article/details/gtmtkidsaf.html

[S28] C：静态变量
来源：http://dali.guannengcc.top/Article/details/gtxwshydau.html

static int counter = 0;
来源：http://dali.chenjidiqi.icu/Article/details/gtczjtebzl.html

[S29] C：变参函数
来源：http://dali.wangdashe.top/Article/details/gtdirimaeg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xylfe.cn/Article/details/gtuymeqiql.html

[S30] C：头文件保护
来源：http://dali.hammf.cn/Article/details/gtnrturudg.html

#ifndef X_H
来源：http://dali.tanke756.top/Article/details/gttncakwgn.html

#define X_H
来源：http://dali.nanxinkj.top/Article/details/gtkptbkrwi.html

#endif
来源：http://dali.xuetiantiany.cn/Article/details/gthphiykii.html

[S31] C++：Hello World
来源：http://dali.meibo888.top/Article/details/gttiuwhewl.html

#include <iostream>
来源：http://dali.sufxvd.cn/Article/details/gtcyzfaohk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.dashuyun.cn/Article/details/gtwnpahrwa.html

[S32] C++：字符串
来源：http://dali.wangshuangyany.cn/Article/details/gthqdcuvsl.html

std::string s = "hi";  s += "!";
来源：http://dali.sufxvd.cn/Article/details/gtndvmgxel.html

[S33] C++：vector 增删
来源：http://dali.jinqigfzy.top/Article/details/gtodkbusmz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hfpthk.cn/Article/details/gttwvczdwv.html

[S34] C++：遍历 vector
来源：http://dali.jqgufenzy.top/Article/details/gtfbouicua.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.tanke756.top/Article/details/gtrissuxjy.html

[S35] C++：map
来源：http://dali.tian-w.cn/Article/details/gtjrborfio.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpniczilr.html

[S36] C++：unordered_map
来源：http://dali.nanxuanxn.top/Article/details/gtxxdwugmj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuxming.cn/Article/details/gtmajcwtkm.html

[S37] C++：set
来源：http://dali.guannengcc.top/Article/details/gtkpbydqgu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.0kj1m.cn/Article/details/gtfkfugcfd.html

[S38] C++：排序
来源：http://dali.xuetiantiany.cn/Article/details/gtqienzpll.html

std::sort(v.begin(), v.end());
来源：http://dali.chenjidiqi.icu/Article/details/gtzyhhwlgv.html

[S39] C++：自定义比较器排序
来源：http://dali.gzhubu.top/Article/details/gthtzagfmw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.guannengcc.top/Article/details/gtnkygvpmv.html

[S40] C++：查找元素
来源：http://dali.vqdsnc.cn/Article/details/gtdxeorfrn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yj202588.top/Article/details/gtlqpybnki.html

[S41] C++：类与构造函数
来源：http://dali.haohaochexian.top/Article/details/gtmrulsyuj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jqgufenzy.top/Article/details/gtvamyzouz.html

[S42] C++：继承与虚函数
来源：http://dali.ehwqpu.com/Article/details/gtfshmxrky.html

class B : public Base { public: void f() override {} };
来源：http://dali.hnqzz.top/Article/details/gtrjiduyki.html

[S43] C++：智能指针
来源：http://dali.tianlin.xyz/Article/details/gtcwpxooqh.html

auto p = std::make_unique<int>(5);
来源：http://dali.xylfe.cn/Article/details/gthrazgapu.html

[S44] C++：引用传参
来源：http://dali.sysykeji.top/Article/details/gtgblesgrw.html

void inc(int &x) { ++x; }
来源：http://dali.chenzaomai.com/Article/details/gtimplqstf.html

[S45] C++：lambda
来源：http://dali.zhongyouzk.top/Article/details/gtlkuqhuvv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shanyushiyangtech.top/Article/details/gtusarbdet.html

[S46] C++：函数模板
来源：http://dali.hongshengwenyu.top/Article/details/gtwwlztjhv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.guannengcc.top/Article/details/gtnptpuepg.html

[S47] C++：结构化绑定遍历
来源：http://dali.sysykeji.top/Article/details/gtzgagghwb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jqgufenzy.top/Article/details/gtdnfhldfi.html

[S48] C++：逐行读文件
来源：http://dali.ybcxt.top/Article/details/gthfknjrds.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpyxkzkhg.html

while (std::getline(in, line)) { }
来源：http://dali.hammf.cn/Article/details/gtlhnfzjsk.html

[S49] C++：写文件
来源：http://dali.pycfn.com/Article/details/gttcsfgnca.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cqqwz.cn/Article/details/gtsucbrxin.html

[S50] C++：格式化数字
来源：http://dali.kuanghao11.cn/Article/details/gtuocpevuy.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gtozzcknlh.html

[S51] C++：显式类型转换
来源：http://dali.ppjwa.cn/Article/details/gtuftibqpc.html

static_cast<double>(a) / b
来源：http://dali.ydzc1.top/Article/details/gteflpiggl.html

[S52] C++：const 与 noexcept
来源：http://dali.shzxlz.cn/Article/details/gtyxlvoevu.html

int size() const noexcept { return n_; }
来源：http://dali.yj20258.top/Article/details/gtwfdstguh.html

[S53] C++：移动语义
来源：http://dali.guowangkeji.top/Article/details/gtdfasphji.html

std::vector<int> w = std::move(v);
来源：http://dali.shangyingyoupin.top/Article/details/gtdjlqbejn.html

[S54] C++：异常处理
来源：http://dali.fengsongda.top/Article/details/gtjesqxntu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhongyouzk.top/Article/details/gtumautssb.html

[S55] C++：结构化绑定
来源：http://dali.hywenlv.cn/Article/details/gtvivhjydq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gtbtdrdlez.html

[S56] C++：optional
来源：http://dali.yueranfly.top/Article/details/gtqtzutfhf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cucudq.cn/Article/details/gttozjvjeg.html

[S57] C++：编译期常量
来源：http://dali.cheryme.top/Article/details/gtvnoghckk.html

constexpr int N = 10;
来源：http://dali.wangdashe.top/Article/details/gtbkgwoagu.html

[S58] C++：命名空间
来源：http://dali.daria6918.cn/Article/details/gtpwwlrwuy.html

namespace ns { int f() { return 1; } }
来源：http://dali.gzhubu.top/Article/details/gtfujhedfw.html

[S59] C++：静态断言
来源：http://dali.zhongyouzk.top/Article/details/gtvgqoqunn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.kuanghao11.cn/Article/details/gtjqbuicjq.html

[S60] C++：遍历并删除元素
来源：http://dali.hongshengwenyu.top/Article/details/gtxxdztlyj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.fengsongda.top/Article/details/gttajthbca.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtvzhcfoif.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.svipenyu.cn/Article/details/gtwbznraqh.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtkmflcplj.html

[T01] Kotlin：Hello World
来源：http://dali.daria6918.cn/Article/details/gtatwaxcin.html

println("Hello")
来源：http://dali.hfpthk.cn/Article/details/gtmgvhgvou.html

[T02] Kotlin：变量
来源：http://dali.cashguo.top/Article/details/gtyhjhwbnn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.meibo888.top/Article/details/gtsfgbhqak.html

[T03] Kotlin：字符串模板
来源：http://dali.cdnleiting.top/Article/details/gtxweznfuy.html

"值: $b"
来源：http://dali.bjfxy.top/Article/details/gtmbufswfn.html

[T04] Kotlin：空安全
来源：http://dali.jqgufenzy.top/Article/details/gtofbnhzyv.html

val n: String? = null;  n?.length
来源：http://dali.shzxlz.cn/Article/details/gtxuaizynw.html

[T05] Kotlin：when 表达式
来源：http://dali.andypj.xyz/Article/details/gtafgivrtb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.wangdashe.top/Article/details/gtbztmcncb.html

[T06] Kotlin：集合映射
来源：http://dali.chenzaomai.com/Article/details/gtsdtqspts.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.vqdsnc.cn/Article/details/gthmxobang.html

[T07] Kotlin：集合过滤
来源：http://dali.ivvv.top/Article/details/gtppcahdwj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhiwuduotai.top/Article/details/gtyfofmzac.html

[T08] Kotlin：数据类
来源：http://dali.dashuyun.cn/Article/details/gtvtdrhrmi.html

data class User(val name: String, val age: Int)
来源：http://dali.wangdashe.top/Article/details/gtryfanaqh.html

[T09] Kotlin：扩展函数
来源：http://dali.yongpay.top/Article/details/gtrwibjbqy.html

fun String.exclaim() = this + "!"
来源：http://dali.jianghu66.top/Article/details/gttfgcncey.html

[T10] Kotlin：默认参数
来源：http://dali.andypj.xyz/Article/details/gtplutffox.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.snrcjt.cn/Article/details/gtzptcxovj.html

[T11] Kotlin：协程
来源：http://dali.jlsjyb.cn/Article/details/gtqczarpbp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jianghu66.top/Article/details/gtfbrkcvju.html

[T12] Kotlin：解构声明
来源：http://dali.hammf.cn/Article/details/gtbonhdeya.html

val (a, b) = Pair(1, 2)
来源：http://dali.fzhhl.top/Article/details/gtpinngcsf.html

[T13] Kotlin：只读 Map
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmhbfxqbl.html

val m = mapOf("a" to 1)
来源：http://dali.hnqzz.top/Article/details/gttxgmsjyc.html

[T14] Kotlin：循环
来源：http://dali.hfpthk.cn/Article/details/gtsoxzvvti.html

for (i in 1..10) println(i)
来源：http://dali.hongshengwenyu.top/Article/details/gtvdekqqoz.html

[T15] Kotlin：接口
来源：http://dali.ivvv.top/Article/details/gtuyvsxzeq.html

interface Shape { fun area(): Double }
来源：http://dali.gaohongyu789.top/Article/details/gtzdxxunxu.html

[T16] Swift：Hello World
来源：http://dali.yuxming.cn/Article/details/gtfmbxeurw.html

print("Hello")
来源：http://dali.hysaishi.cn/Article/details/gtlbepwdxc.html

[T17] Swift：变量与常量
来源：http://dali.nanxuanxn.top/Article/details/gtooirjsxa.html

var a = 1;  let b = 2
来源：http://dali.pycfn.com/Article/details/gtfvxrcsur.html

[T18] Swift：字符串插值
来源：http://dali.gaohongyu789.top/Article/details/gtmtmxhlvu.html

"值: \(b)"
来源：http://dali.yueranfly.top/Article/details/gtafplyhum.html

[T19] Swift：可选绑定
来源：http://dali.hammf.cn/Article/details/gttbzkebin.html

if let n = opt { print(n) }
来源：http://dali.hfpthk.cn/Article/details/gtojbnkxap.html

[T20] Swift：数组操作
来源：http://dali.gzhubu.top/Article/details/gtskuuzdum.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.andypj.xyz/Article/details/gtwjhqtvkm.html

[T21] Swift：遍历
来源：http://dali.gotoacloud.top/Article/details/gtpgtasabv.html

for x in a { print(x) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtduguxiuj.html

[T22] Swift：字典
来源：http://dali.ppjwa.cn/Article/details/gtazkpgwaz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.pycfn.com/Article/details/gtyqgzygvg.html

[T23] Swift：函数
来源：http://dali.snrcjt.cn/Article/details/gtwqyqabwl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yongpay.top/Article/details/gtpklghkfv.html

[T24] Swift：闭包
来源：http://dali.hongshengwenyu.top/Article/details/gtupstajzq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gtqjlihsvm.html

[T25] Swift：结构体
来源：http://dali.guowangkeji.top/Article/details/gtgzoxojcf.html

struct P { var x: Int }
来源：http://dali.jiagoushi.top/Article/details/gtnghdlvgy.html

[T26] Swift：类与重写
来源：http://dali.andypj.xyz/Article/details/gtkbiyeeqn.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gtudrphbrv.html

[T27] Swift：错误处理
来源：http://dali.kuanghao11.cn/Article/details/gtqkmgmxqj.html

do { try f() } catch { print(error) }
来源：http://dali.daria6918.cn/Article/details/gtofppwfum.html

[T28] Swift：枚举
来源：http://dali.hnxiangtu.top/Article/details/gtmuumqvvr.html

enum Color { case red, green }
来源：http://dali.chenzaomai.com/Article/details/gtskqimclu.html

[T29] Swift：guard 提前返回
来源：http://dali.dianchejie.cn/Article/details/gttzrqcoaa.html

guard let x = opt else { return }
来源：http://dali.nanxinkj.top/Article/details/gtmppzjuvu.html

[T30] Swift：协议
来源：http://dali.vqdsnc.cn/Article/details/gtnwfpubpr.html

protocol Shape { func area() -> Double }
来源：http://dali.shzxlz.cn/Article/details/gtgrettnkz.html

[T31] Lua：Hello World
来源：http://dali.xylfe.cn/Article/details/gthvwhieax.html

print("Hello")
来源：http://dali.yj20258888.top/Article/details/gtviysvdov.html

[T32] Lua：局部变量
来源：http://dali.hongshengwenyu.top/Article/details/gtofmxdplm.html

local a = 1
来源：http://dali.jqgfzy.top/Article/details/gtnhewytew.html

[T33] Lua：表（数组）
来源：http://dali.havefunace.top/Article/details/gtzyxzamty.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cqqwz.cn/Article/details/gtgavmjpui.html

[T34] Lua：遍历表
来源：http://dali.havefunace.top/Article/details/gtajgomhla.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hammf.cn/Article/details/gtrcxnjdmf.html

[T35] Lua：字典表
来源：http://dali.feifeiyinyue.top/Article/details/gtcyyjgnvf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ybcxt.top/Article/details/gtoghkfenf.html

[T36] Lua：函数
来源：http://dali.svipenyu.cn/Article/details/gtuhgufusb.html

function add(a, b) return a + b end
来源：http://dali.zhixingplan.top/Article/details/gtxrfoshhs.html

[T37] Lua：字符串拼接
来源：http://dali.pycfn.com/Article/details/gtecmnvqsc.html

"a" .. "b"
来源：http://dali.gogol.net.cn/Article/details/gtrqqjgjhg.html

[T38] Lua：条件
来源：http://dali.cqqwz.cn/Article/details/gtqezocmlz.html

if x > 0 then print("正") end
来源：http://dali.cashguo.top/Article/details/gteazvdooc.html

[T39] Lua：模式匹配
来源：http://dali.tanke756.top/Article/details/gtvhrxqdon.html

string.find(s, "%d+")
来源：http://dali.wangshuangyany.cn/Article/details/gteontiqss.html

[T40] Lua：元表
来源：http://dali.guowangkeji.top/Article/details/gtfeslakhr.html

setmetatable({}, { __index = base })
来源：http://dali.fzhhl.top/Article/details/gtsimcswuv.html

[T41] Perl：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmrsgkfya.html

print "Hello\n";
来源：http://dali.mhx1999.top/Article/details/gthwdksosi.html

[T42] Perl：变量类型
来源：http://dali.yvedp.cn/Article/details/gtvypxxzeb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.chenjidiqi.icu/Article/details/gtnztjbync.html


<!-- 参考信息 -->