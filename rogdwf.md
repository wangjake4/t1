代发 wailian999

files=$(ls -1)
来源：http://dali.yj20258888.top/Article/details/gtyqyzxnoe.html

[R38] 管道串联
来源：http://dali.dianchejie.cn/Article/details/gtoqorxjsb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinqigufen.top/Article/details/gtrbtuykkh.html

[R39] 重定向标准输出与错误
来源：http://dali.yj20258888.top/Article/details/gtbkjhfcwn.html

cmd > out.log 2>&1
来源：http://dali.daxiang520.top/Article/details/gtfunuoynv.html

[R40] 追加写日志
来源：http://dali.nanxinkj.top/Article/details/gtzrfgajpp.html

echo "log" >> out.log
来源：http://dali.sysykeji.top/Article/details/gtxxdjrunq.html

[R41] 丢弃输出
来源：http://dali.hfpthk.cn/Article/details/gtkutcsted.html

cmd >/dev/null 2>&1
来源：http://dali.316326.xyz/Article/details/gtakivoffa.html

[R42] 输入重定向
来源：http://dali.c1oappe.top/Article/details/gtmirakqxr.html

wc -l < a.txt
来源：http://dali.zhengqikj.top/Article/details/gtlrmhhssd.html

[R43] 按名字查找文件
来源：http://dali.jqgfzy.top/Article/details/gtmsejivob.html

find . -name "*.log" -type f
来源：http://dali.9152youxi.cn/Article/details/gtroovghjf.html

[R44] 按修改时间查找
来源：http://dali.hongshengwenyu.top/Article/details/gtqhtetlai.html

find . -mtime -7 -type f
来源：http://dali.pycfn.com/Article/details/gtvlfeozdq.html

[R45] 批量删除
来源：http://dali.kuanghao11.cn/Article/details/gtvfzswetx.html

find . -name "*.tmp" -delete
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuqpyzjsw.html

[R46] 递归替换文件内容
来源：http://dali.guowangkeji.top/Article/details/gtaehgtobf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.meibo888.top/Article/details/gtvwhjaowf.html

[R47] sed 单行替换
来源：http://dali.9152youxi.cn/Article/details/gtqgxpxjlo.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ivvv.top/Article/details/gtsrunikrr.html

[R48] awk 取指定列
来源：http://dali.wangshuangyany.cn/Article/details/gtvufjrpac.html

awk '{print $1, $3}' a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtbyrumqpo.html

[R49] awk 带条件
来源：http://dali.yuanzhike.top/Article/details/gtzawvnnzt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.kuanghao11.cn/Article/details/gtymowuyku.html

[R50] awk 求和
来源：http://dali.shzxlz.cn/Article/details/gtsdbzusjn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.fengsongda.top/Article/details/gtdhwjubwd.html

[R51] 排序去重取前几
来源：http://dali.cdnleiting.top/Article/details/gtdxkctaku.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jqgufenzy.top/Article/details/gtoyhzyogq.html

[R52] 统计行数
来源：http://dali.guannengcc.top/Article/details/gtcvgpezyr.html

wc -l a.txt
来源：http://dali.fengsongda.top/Article/details/gticpassxq.html

[R53] 查看文件头与实时尾
来源：http://dali.iojbl.cn/Article/details/gtdlhocgdt.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yongpay.top/Article/details/gtnvtqonso.html

[R54] 比较两个文件
来源：http://dali.snrcjt.cn/Article/details/gtpvniqrmu.html

diff a.txt b.txt
来源：http://dali.yongpay.top/Article/details/gtyqktsbcv.html

[R55] 压缩与解压
来源：http://dali.jiagoushi.top/Article/details/gtsksbzrqb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.fengsongda.top/Article/details/gtohocanng.html

[R56] 远程拷贝
来源：http://dali.aizwys.cn/Article/details/gtfbhlznot.html

scp file user@host:/path/
来源：http://dali.gzhubu.top/Article/details/gtzjeexfto.html

[R57] 远程执行命令
来源：http://dali.pycfn.com/Article/details/gtprpaqoth.html

ssh user@host 'uptime'
来源：http://dali.zhoulong.xyz/Article/details/gtappqafmu.html

[R58] 下载文件
来源：http://dali.xinyue.icu/Article/details/gtidpsrgrj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmdszsgjb.html

[R59] 发 POST JSON
来源：http://dali.cucudq.cn/Article/details/gtgygtticj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shangyingyoupin.top/Article/details/gtknlspifr.html

[R60] 只看 HTTP 状态码
来源：http://dali.jiagoushi.top/Article/details/gtootsxuhs.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ehwqpu.com/Article/details/gtyvjkuicd.html

[R61] 磁盘占用
来源：http://dali.dashuyun.cn/Article/details/gtvruqtrdr.html

df -h;  du -sh *
来源：http://dali.yj20258.top/Article/details/gtbllbizaq.html

[R62] 找最占空间的文件
来源：http://dali.jyoumei.cn/Article/details/gtropecciz.html

du -ah . | sort -rh | head -10
来源：http://dali.guannengcc.top/Article/details/gtgzdszikl.html

[R63] 内存与进程
来源：http://dali.cashguo.top/Article/details/gtypsdnifj.html

free -h;  ps aux | grep nginx
来源：http://dali.dashuyun.cn/Article/details/gttwpmnieh.html

[R64] 结束进程
来源：http://dali.quarkkingdee.top/Article/details/gtxhnajaff.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jqgufenzy.top/Article/details/gtcloujeve.html

[R65] 查看端口占用
来源：http://dali.zhiwuduotai.top/Article/details/gtvcyzkrmu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.haohaochexian.top/Article/details/gtrsyeiotk.html

[R66] 定时任务
来源：http://dali.zdqjudy.top/Article/details/gtbarmxeer.html

crontab -e;  crontab -l
来源：http://dali.zhiwuduotai.top/Article/details/gtnmccdvgn.html

[R67] 生成随机十六进制串
来源：http://dali.vqdsnc.cn/Article/details/gtvuegqapu.html

openssl rand -hex 16
来源：http://dali.zhiwuduotai.top/Article/details/gtsqdmepwi.html

[R68] 计算文件校验值
来源：http://dali.yvedp.cn/Article/details/gtrjbeyfgv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zycfv.cn/Article/details/gtmibufhgj.html

[R69] 生成随机密码
来源：http://dali.jqgfzy.top/Article/details/gturndbudm.html

head -c 16 /dev/urandom | base64
来源：http://dali.ydzc1.top/Article/details/gtkbfbgacg.html

[R70] 时间戳与互转
来源：http://dali.jinqigfzy.top/Article/details/gttgullhap.html

date +%s;  date -d @1700000000
来源：http://dali.jqgfzy.top/Article/details/gtghapkkwu.html

[R71] 日期格式化
来源：http://dali.ppjwa.cn/Article/details/gtevkcmoxb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yuanzhike.top/Article/details/gtjwlotfss.html

[R72] 等待端口就绪
来源：http://dali.sufxvd.cn/Article/details/gtbeuvslka.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yanxiufei.cn/Article/details/gtegyxgtcx.html

[R73] 分割大日志
来源：http://dali.sxryk.cn/Article/details/gtaideugev.html

split -l 1000 big.log part_
来源：http://dali.9152youxi.cn/Article/details/gtmbcoboqo.html

[R74] 批量重命名
来源：http://dali.daxiang520.top/Article/details/gtesroqxdx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hnqzz.top/Article/details/gtkqsdutwp.html

[R75] 导出环境变量
来源：http://dali.chenlongwang.top/Article/details/gtvkocvjvl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.daxiang520.top/Article/details/gtiflqxjny.html

[R76] 使用临时文件
来源：http://dali.dianchejie.cn/Article/details/gtwjrrcgqf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.snrcjt.cn/Article/details/gtyczpswcn.html

[R77] 读取用户输入
来源：http://dali.yuxming.cn/Article/details/gtiaqirwwc.html

read -rp "请输入: " ans
来源：http://dali.jinqigfzy.top/Article/details/gttfrcubsr.html

[R78] 交互式菜单
来源：http://dali.zhixingplan.top/Article/details/gtdtcsroio.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gzhubu.top/Article/details/gtjcqyhkwb.html

[R79] 解析命令行选项
来源：http://dali.zdqjudy.top/Article/details/gtzraxawjk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shuidangran.top/Article/details/gtaskbfnaw.html

[R80] 查看脚本执行耗时
来源：http://dali.svipenyu.cn/Article/details/gtvskgqdow.html

time ./run.sh
来源：http://dali.gotoacloud.top/Article/details/gthumeoqwc.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gttshooama.html

S. C / C++ 专题
来源：http://dali.jinghuilouyu.cn/Article/details/gtjpjzvuov.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gttaktvhkn.html

[S01] C：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtzycwqziw.html

#include <stdio.h>
来源：http://dali.cashguo.top/Article/details/gtcnmlmzxf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yj202588.top/Article/details/gtgpqfnuts.html

[S02] C：变量与格式化输出
来源：http://dali.tanke756.top/Article/details/gtsnyfcnzj.html

int a = 10; printf("%d\n", a);
来源：http://dali.redwolf501.top/Article/details/gtdslsybyt.html

[S03] C：读入整数
来源：http://dali.dashuyun.cn/Article/details/gtgedyaqrg.html

int x; scanf("%d", &x);
来源：http://dali.yj20258.top/Article/details/gtlxwwtsgf.html

[S04] C：字符串复制
来源：http://dali.yongpay.top/Article/details/gtdbnigwpk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhongyouzk.top/Article/details/gtqdwcjqst.html

[S05] C：字符串长度
来源：http://dali.chenzaomai.com/Article/details/gthksuggwd.html

strlen(s)
来源：http://dali.sufxvd.cn/Article/details/gtqhkdugud.html

[S06] C：字符串比较
来源：http://dali.snrcjt.cn/Article/details/gtpkhtssrm.html

strcmp(a, b) == 0
来源：http://dali.feifeiyinyue.top/Article/details/gtkhyjrpli.html

[S07] C：数组遍历求和
来源：http://dali.mhx1999.top/Article/details/gtagqsaeeg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.fengsongda.top/Article/details/gtehdrjknw.html

[S08] C：动态内存分配与释放
来源：http://dali.nanxinkj.top/Article/details/gtahhfioml.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hongshengwenyu.top/Article/details/gtfhumwluq.html

[S09] C：结构体定义与初始化
来源：http://dali.nwbrower.top/Article/details/gthljabfkk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.vqdsnc.cn/Article/details/gteytycpcf.html

[S10] C：指针与解引用
来源：http://dali.xuetiantiany.cn/Article/details/gtpbyjqhkh.html

int *p = &a;  *p = 5;
来源：http://dali.yj202588.top/Article/details/gtiawawvcg.html

[S11] C：逐行读文件
来源：http://dali.jianghu66.top/Article/details/gtkwukcwyp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.redwolf501.top/Article/details/gticbgowvg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zdqjudy.top/Article/details/gtgroreyui.html

fclose(f);
来源：http://dali.jyoumei.cn/Article/details/gtyvdzzgjg.html

[S12] C：写文件
来源：http://dali.0kj1m.cn/Article/details/gtcwpdgccm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yangfankeji.com/Article/details/gtzcdcblqy.html

[S13] C：宏定义
来源：http://dali.zhengqikj.top/Article/details/gtbqnzzynr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ydzc1.top/Article/details/gtvpuanomo.html

[S14] C：枚举
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqtikfuqe.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.tanke756.top/Article/details/gtezgucdbb.html

[S15] C：类型转换
来源：http://dali.jlsjyb.cn/Article/details/gtmnbmlgqq.html

(double) a / b
来源：http://dali.ehwqpu.com/Article/details/gtwyetajao.html

[S16] C：位操作置位
来源：http://dali.chenlongwang.top/Article/details/gtvfxajzhl.html

x |= (1 << 3);
来源：http://dali.bjfxy.top/Article/details/gtggxryctn.html

[S17] C：安全拼接字符串
来源：http://dali.jlsjyb.cn/Article/details/gteocyriqb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.meibo888.top/Article/details/gticizaeph.html

[S18] C：命令行参数
来源：http://dali.quarkkingdee.top/Article/details/gtlqeslvax.html

int main(int argc, char **argv)
来源：http://dali.nwbrower.top/Article/details/gtazlhxidr.html

[S19] C：快速排序
来源：http://dali.xylfe.cn/Article/details/gtlqtdmmww.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.birdmap.top/Article/details/gtsetxhtjq.html

[S20] C：二分查找
来源：http://dali.yonumen.top/Article/details/gtdscyrima.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhoulong.xyz/Article/details/gttssdoexa.html

[S21] C：字符类别判断
来源：http://dali.chenzaomai.com/Article/details/gtwyysndtf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.meibo888.top/Article/details/gtpxmmxtyr.html

[S22] C：字符串转数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gtevtwkkse.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ybcxt.top/Article/details/gtsjxpxvwr.html

[S23] C：随机数
来源：http://dali.hysaishi.cn/Article/details/gtvvfrfkxk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.andypj.xyz/Article/details/gtgzeihmhn.html

[S24] C：获取本地时间
来源：http://dali.daxiang520.top/Article/details/gtlwsvqwjq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yangfankeji.com/Article/details/gtdastcgnu.html

[S25] C：内存拷贝
来源：http://dali.cheryme.top/Article/details/gtuqqcnwps.html

memcpy(dst, src, n);
来源：http://dali.hysaishi.cn/Article/details/gtyddlstvv.html

[S26] C：内存清零
来源：http://dali.yuxming.cn/Article/details/gtogsozvtc.html

memset(a, 0, sizeof a);
来源：http://dali.zhiwuduotai.top/Article/details/gtfnxdnlaf.html

[S27] C：定义常量
来源：http://dali.dashuyun.cn/Article/details/gtrpvmtspd.html

const double PI = 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gtstkvzngk.html

[S28] C：静态变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtgszguuex.html

static int counter = 0;
来源：http://dali.xziqi.cn/Article/details/gtwwsdjprn.html

[S29] C：变参函数
来源：http://dali.tian-w.cn/Article/details/gtcmmtefqu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvkbrtbcy.html

[S30] C：头文件保护
来源：http://dali.zdqjudy.top/Article/details/gtnuzaddld.html

#ifndef X_H
来源：http://dali.quarkkingdee.top/Article/details/gtpkunygug.html

#define X_H
来源：http://dali.yongpay.top/Article/details/gtkouzpvfb.html

#endif
来源：http://dali.haohaochexian.top/Article/details/gtynsungnl.html

[S31] C++：Hello World
来源：http://dali.xinyue.icu/Article/details/gtmqgtbzsw.html

#include <iostream>
来源：http://dali.yangfankeji.com/Article/details/gtvensqzpr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.aizwys.cn/Article/details/gtrywdoekr.html

[S32] C++：字符串
来源：http://dali.haohaochexian.top/Article/details/gtixshnata.html

std::string s = "hi";  s += "!";
来源：http://dali.gaohongyu789.top/Article/details/gtocizvozb.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gtfwwhgfes.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ehwqpu.com/Article/details/gtfxivtzic.html

[S34] C++：遍历 vector
来源：http://dali.cqqwz.cn/Article/details/gthlgndykf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hnxiangtu.top/Article/details/gtpcmcquzr.html

[S35] C++：map
来源：http://dali.cqqwz.cn/Article/details/gtcexvfdbr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cdnleiting.top/Article/details/gtwwkhvsaj.html

[S36] C++：unordered_map
来源：http://dali.zhongyouzk.top/Article/details/gtzvspnnqp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuanzx.com/Article/details/gtpzhvlubj.html

[S37] C++：set
来源：http://dali.yj20258.top/Article/details/gtnzpfqpdx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.svipenyu.cn/Article/details/gtfamxxvfk.html

[S38] C++：排序
来源：http://dali.yj20258888.top/Article/details/gtinkjthxs.html

std::sort(v.begin(), v.end());
来源：http://dali.hfpthk.cn/Article/details/gtkwypwbig.html

[S39] C++：自定义比较器排序
来源：http://dali.cucudq.cn/Article/details/gtowtpvfpe.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.dianchejie.cn/Article/details/gtpgttivdr.html

[S40] C++：查找元素
来源：http://dali.zdqjudy.top/Article/details/gtysollyyi.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yvedp.cn/Article/details/gtsfdtvygi.html

[S41] C++：类与构造函数
来源：http://dali.yvedp.cn/Article/details/gttmndzalr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdaisbztu.html

[S42] C++：继承与虚函数
来源：http://dali.svipenyu.cn/Article/details/gtfhimlthx.html

class B : public Base { public: void f() override {} };
来源：http://dali.yj202588.top/Article/details/gtpjocnfko.html

[S43] C++：智能指针
来源：http://dali.zhengqikj.top/Article/details/gtakygxcjr.html

auto p = std::make_unique<int>(5);
来源：http://dali.gotoacloud.top/Article/details/gtpzgjtecm.html

[S44] C++：引用传参
来源：http://dali.kuanghao11.cn/Article/details/gtgtznycgj.html

void inc(int &x) { ++x; }
来源：http://dali.zhiwuduotai.top/Article/details/gtnettkrgo.html

[S45] C++：lambda
来源：http://dali.ydzc1.top/Article/details/gtyejhaoyz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sxryk.cn/Article/details/gtgslenshg.html

[S46] C++：函数模板
来源：http://dali.chenzaomai.com/Article/details/gtksghzupd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtgnjpjsuk.html

[S47] C++：结构化绑定遍历
来源：http://dali.gogol.net.cn/Article/details/gtsqiiazcy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhixingplan.top/Article/details/gtcivdfjxb.html

[S48] C++：逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gtdmuoyytj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shangyingyoupin.top/Article/details/gtjcedwlyq.html

while (std::getline(in, line)) { }
来源：http://dali.sufxvd.cn/Article/details/gtkbfomtin.html

[S49] C++：写文件
来源：http://dali.ybcxt.top/Article/details/gtxhqygles.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.aizwys.cn/Article/details/gtpyaqvgsv.html

[S50] C++：格式化数字
来源：http://dali.redwolf501.top/Article/details/gtwgcajnii.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gzhubu.top/Article/details/gtwaovlyeh.html

[S51] C++：显式类型转换
来源：http://dali.ydzc1.top/Article/details/gtkkqnsqzp.html

static_cast<double>(a) / b
来源：http://dali.bjfxy.top/Article/details/gtasigytfl.html

[S52] C++：const 与 noexcept
来源：http://dali.haohaochexian.top/Article/details/gtflaksryq.html

int size() const noexcept { return n_; }
来源：http://dali.zhiwuduotai.top/Article/details/gtztvvvvss.html

[S53] C++：移动语义
来源：http://dali.jianghu66.top/Article/details/gtmekzwinh.html

std::vector<int> w = std::move(v);
来源：http://dali.yj202588.top/Article/details/gtqxgjowls.html

[S54] C++：异常处理
来源：http://dali.jqgfzy.top/Article/details/gtywfauqig.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.haohaochexian.top/Article/details/gtnedevazv.html

[S55] C++：结构化绑定
来源：http://dali.hfpthk.cn/Article/details/gtpgzpiymz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gzhubu.top/Article/details/gtxizndgpa.html

[S56] C++：optional
来源：http://dali.hnqzz.top/Article/details/gtvjoqmeqp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tanke756.top/Article/details/gtsuapoydh.html

[S57] C++：编译期常量
来源：http://dali.nanxinkj.top/Article/details/gtqjkihsyn.html

constexpr int N = 10;
来源：http://dali.yj20258888.top/Article/details/gtdgtdpydi.html

[S58] C++：命名空间
来源：http://dali.redwolf501.top/Article/details/gtstdcntot.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhengqikj.top/Article/details/gtafxbztvv.html

[S59] C++：静态断言
来源：http://dali.xuetiantiany.cn/Article/details/gtyurpsbet.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yangfankeji.com/Article/details/gtdbpyfemi.html

[S60] C++：遍历并删除元素
来源：http://dali.mhx1999.top/Article/details/gtmpoiztiw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.daria6918.cn/Article/details/gtypobqprp.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtkpwpqyoe.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhixingplan.top/Article/details/gtyobfvegn.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtibmicziy.html

[T01] Kotlin：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gttfdooyoz.html

println("Hello")
来源：http://dali.316326.xyz/Article/details/gtbjwbwgme.html

[T02] Kotlin：变量
来源：http://dali.haohaochexian.top/Article/details/gtzrutmkdr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jqgfzy.top/Article/details/gtcwxwdjyg.html

[T03] Kotlin：字符串模板
来源：http://dali.yj20258.top/Article/details/gtgvqugumd.html

"值: $b"
来源：http://dali.daria6918.cn/Article/details/gtcvvrfbui.html

[T04] Kotlin：空安全
来源：http://dali.zhongyouzk.top/Article/details/gtdzwyzvfx.html

val n: String? = null;  n?.length
来源：http://dali.vqdsnc.cn/Article/details/gtagswrmqf.html

[T05] Kotlin：when 表达式
来源：http://dali.yj20258.top/Article/details/gthhgldhpq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.chenjidiqi.icu/Article/details/gtmrmhmutr.html

[T06] Kotlin：集合映射
来源：http://dali.meibo888.top/Article/details/gtywaxcpmz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.meibo888.top/Article/details/gtvzcdebvo.html

[T07] Kotlin：集合过滤
来源：http://dali.zhoulong.xyz/Article/details/gtxcshqpzl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhiwuduotai.top/Article/details/gtagjiugag.html

[T08] Kotlin：数据类
来源：http://dali.cheryme.top/Article/details/gtgqzacubl.html

data class User(val name: String, val age: Int)
来源：http://dali.gaohongyu789.top/Article/details/gtvvhprktf.html

[T09] Kotlin：扩展函数
来源：http://dali.hammf.cn/Article/details/gtkrwwjumb.html

fun String.exclaim() = this + "!"
来源：http://dali.zhiwuduotai.top/Article/details/gtpghjgsbz.html

[T10] Kotlin：默认参数
来源：http://dali.jyoumei.cn/Article/details/gtidzvcols.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gtxhnpwzhr.html

[T11] Kotlin：协程
来源：http://dali.chenlongwang.top/Article/details/gtmbnzmkju.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.meibo888.top/Article/details/gtzsczxbpm.html

[T12] Kotlin：解构声明
来源：http://dali.yuxming.cn/Article/details/gtrbygnler.html

val (a, b) = Pair(1, 2)
来源：http://dali.cashguo.top/Article/details/gtxloprxij.html

[T13] Kotlin：只读 Map
来源：http://dali.ydzc1.top/Article/details/gtxdwjdltz.html

val m = mapOf("a" to 1)
来源：http://dali.ehwqpu.com/Article/details/gtavjeyzct.html

[T14] Kotlin：循环
来源：http://dali.yangfankeji.com/Article/details/gtnknhzhdt.html

for (i in 1..10) println(i)
来源：http://dali.zhongyouzk.top/Article/details/gtjbknwnmj.html

[T15] Kotlin：接口
来源：http://dali.zhixingplan.top/Article/details/gtauawuhfq.html

interface Shape { fun area(): Double }
来源：http://dali.shzxlz.cn/Article/details/gtdbydjcay.html

[T16] Swift：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkviyghqn.html

print("Hello")
来源：http://dali.svipenyu.cn/Article/details/gtvhkkpmpw.html

[T17] Swift：变量与常量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgeexbonl.html

var a = 1;  let b = 2
来源：http://dali.hywenlv.cn/Article/details/gtzmplqaqi.html

[T18] Swift：字符串插值
来源：http://dali.xinyue.icu/Article/details/gtyomzsqna.html

"值: \(b)"
来源：http://dali.9152youxi.cn/Article/details/gthxsvpdlm.html

[T19] Swift：可选绑定
来源：http://dali.cdnleiting.top/Article/details/gtisvcbdll.html

if let n = opt { print(n) }
来源：http://dali.chenlongwang.top/Article/details/gtxxinsrxp.html

[T20] Swift：数组操作
来源：http://dali.redwolf501.top/Article/details/gtwzztehjn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.sweek.top/Article/details/gtbijxrugd.html

[T21] Swift：遍历
来源：http://dali.cucudq.cn/Article/details/gtgdvhcrsa.html

for x in a { print(x) }
来源：http://dali.shangyingyoupin.top/Article/details/gtqidzlbco.html

[T22] Swift：字典
来源：http://dali.cashguo.top/Article/details/gthiyxarwf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cheryme.top/Article/details/gtmmlsfjmk.html

[T23] Swift：函数
来源：http://dali.ppjwa.cn/Article/details/gttkojumgq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.dianchejie.cn/Article/details/gtyepavjjs.html

[T24] Swift：闭包
来源：http://dali.yuanzhike.top/Article/details/gtocxzchre.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.redwolf501.top/Article/details/gtwuiddfao.html

[T25] Swift：结构体
来源：http://dali.yanxiufei.cn/Article/details/gtawhkawgg.html

struct P { var x: Int }
来源：http://dali.shangyingyoupin.top/Article/details/gtmzspwhul.html

[T26] Swift：类与重写
来源：http://dali.wangdashe.top/Article/details/gthnmhpyfj.html

class A: Base { override func f() {} }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyhjgfmbu.html

[T27] Swift：错误处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzdgnrtti.html

do { try f() } catch { print(error) }
来源：http://dali.316326.xyz/Article/details/gtvzwuwzxy.html

[T28] Swift：枚举
来源：http://dali.9152youxi.cn/Article/details/gttwvqkoxt.html

enum Color { case red, green }
来源：http://dali.hysaishi.cn/Article/details/gthtgnirvm.html

[T29] Swift：guard 提前返回
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjnifzobq.html

guard let x = opt else { return }
来源：http://dali.shuidangran.top/Article/details/gtjoydqvvb.html

[T30] Swift：协议
来源：http://dali.chenlongwang.top/Article/details/gtozdsinwb.html

protocol Shape { func area() -> Double }
来源：http://dali.meibo888.top/Article/details/gtymdofrkl.html

[T31] Lua：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtrntfrkkb.html

print("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gtrnwldcaf.html

[T32] Lua：局部变量
来源：http://dali.zhixingplan.top/Article/details/gtqetjlcvg.html

local a = 1
来源：http://dali.wangshuangyany.cn/Article/details/gtsficlotz.html

[T33] Lua：表（数组）
来源：http://dali.jlsjyb.cn/Article/details/gtqypaauqy.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cucudq.cn/Article/details/gtmipmapda.html

[T34] Lua：遍历表
来源：http://dali.yvedp.cn/Article/details/gtfuiixswh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jinghuilouyu.cn/Article/details/gtsdugwnvt.html

[T35] Lua：字典表
来源：http://dali.ppjwa.cn/Article/details/gttmojdgmr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.guowangkeji.top/Article/details/gtjgjgqeok.html

[T36] Lua：函数
来源：http://dali.tanke756.top/Article/details/gtwgtfmjsm.html

function add(a, b) return a + b end
来源：http://dali.cqqwz.cn/Article/details/gtpsijirdk.html

[T37] Lua：字符串拼接
来源：http://dali.fengsongda.top/Article/details/gtdkrdjqeh.html

"a" .. "b"
来源：http://dali.0kj1m.cn/Article/details/gtyjvvxcyg.html

[T38] Lua：条件
来源：http://dali.chenjidiqi.icu/Article/details/gtefutqqcl.html

if x > 0 then print("正") end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtazeynjxv.html

[T39] Lua：模式匹配
来源：http://dali.haohaochexian.top/Article/details/gttwkfqvnv.html

string.find(s, "%d+")
来源：http://dali.nwbrower.top/Article/details/gtrskhnfka.html

[T40] Lua：元表
来源：http://dali.pycfn.com/Article/details/gtliozdrol.html

setmetatable({}, { __index = base })
来源：http://dali.zhongyouzk.top/Article/details/gtopphynqm.html


<!-- 参考信息 -->