代发 wailian999

files=$(ls -1)
来源：http://dali.fengsongda.top/Article/details/gtugytwwqx.html

[R38] 管道串联
来源：http://dali.shuidangran.top/Article/details/gthqtaltsu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jyoumei.cn/Article/details/gthfxokroh.html

[R39] 重定向标准输出与错误
来源：http://dali.kuanghao11.cn/Article/details/gtulwgkeep.html

cmd > out.log 2>&1
来源：http://dali.yj20258.top/Article/details/gtqykoetwi.html

[R40] 追加写日志
来源：http://dali.fzhhl.top/Article/details/gtoourzycu.html

echo "log" >> out.log
来源：http://dali.tianlin.xyz/Article/details/gtbtzjsxhl.html

[R41] 丢弃输出
来源：http://dali.smart0.xyz/Article/details/gtprfludka.html

cmd >/dev/null 2>&1
来源：http://dali.nanxinkj.top/Article/details/gtzwujrtsk.html

[R42] 输入重定向
来源：http://dali.yanxiufei.cn/Article/details/gtcrxszvrc.html

wc -l < a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtojcgjdba.html

[R43] 按名字查找文件
来源：http://dali.hfpthk.cn/Article/details/gtnnmacyly.html

find . -name "*.log" -type f
来源：http://dali.yanxiufei.cn/Article/details/gtxeryxrqt.html

[R44] 按修改时间查找
来源：http://dali.wangshuangyany.cn/Article/details/gtuzikxpiw.html

find . -mtime -7 -type f
来源：http://dali.yvedp.cn/Article/details/gtausrgaie.html

[R45] 批量删除
来源：http://dali.ehwqpu.com/Article/details/gtnjlkcbth.html

find . -name "*.tmp" -delete
来源：http://dali.yongpay.top/Article/details/gtfcmlwwbl.html

[R46] 递归替换文件内容
来源：http://dali.jyoumei.cn/Article/details/gtesqdtnkl.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.aibaodan.cn/Article/details/gtcvoqwrdi.html

[R47] sed 单行替换
来源：http://dali.zycfv.cn/Article/details/gtttknmqln.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.redwolf501.top/Article/details/gtmtvfpwls.html

[R48] awk 取指定列
来源：http://dali.cdnleiting.top/Article/details/gtpnudktor.html

awk '{print $1, $3}' a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtfjurswsg.html

[R49] awk 带条件
来源：http://dali.sxryk.cn/Article/details/gtdmueqife.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gogol.net.cn/Article/details/gtdjfrlmoe.html

[R50] awk 求和
来源：http://dali.c1oappe.top/Article/details/gttcbosony.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jqgufenzy.top/Article/details/gteicobhzz.html

[R51] 排序去重取前几
来源：http://dali.smart0.xyz/Article/details/gtblgxfwjs.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.fzhhl.top/Article/details/gtgdekoviy.html

[R52] 统计行数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtblmizvja.html

wc -l a.txt
来源：http://dali.andypj.xyz/Article/details/gtrhteuceg.html

[R53] 查看文件头与实时尾
来源：http://dali.dianchejie.cn/Article/details/gtfnttwfkb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.daria6918.cn/Article/details/gtoezieuxy.html

[R54] 比较两个文件
来源：http://dali.c1oappe.top/Article/details/gtrqcrkqtt.html

diff a.txt b.txt
来源：http://dali.gaohongyu789.top/Article/details/gtgqgownrk.html

[R55] 压缩与解压
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqpulxomb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yvedp.cn/Article/details/gtdsbnkwam.html

[R56] 远程拷贝
来源：http://dali.yj20258888.top/Article/details/gtywvvwptw.html

scp file user@host:/path/
来源：http://dali.yanxiufei.cn/Article/details/gtanuzefwk.html

[R57] 远程执行命令
来源：http://dali.cqqwz.cn/Article/details/gtdfmawukk.html

ssh user@host 'uptime'
来源：http://dali.shzxlz.cn/Article/details/gtwomqxjga.html

[R58] 下载文件
来源：http://dali.kuanghao11.cn/Article/details/gtnauuxpfn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.quarkkingdee.top/Article/details/gttpulidti.html

[R59] 发 POST JSON
来源：http://dali.ydzc1.top/Article/details/gtybktamqk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.quarkkingdee.top/Article/details/gtmuboigbc.html

[R60] 只看 HTTP 状态码
来源：http://dali.shzxlz.cn/Article/details/gtqxhdlgxn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.haohaochexian.top/Article/details/gtaqwvjghe.html

[R61] 磁盘占用
来源：http://dali.sufxvd.cn/Article/details/gtkurtmnaj.html

df -h;  du -sh *
来源：http://dali.ydzc1.top/Article/details/gturpjnwbl.html

[R62] 找最占空间的文件
来源：http://dali.jinqigfzy.top/Article/details/gtbyrfzywg.html

du -ah . | sort -rh | head -10
来源：http://dali.dashuyun.cn/Article/details/gtuhyvyohw.html

[R63] 内存与进程
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpdzgfnya.html

free -h;  ps aux | grep nginx
来源：http://dali.aizwys.cn/Article/details/gtsflbpvbp.html

[R64] 结束进程
来源：http://dali.vqdsnc.cn/Article/details/gtlebnuyqq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xylfe.cn/Article/details/gtkpjzstxi.html

[R65] 查看端口占用
来源：http://dali.nanxinkj.top/Article/details/gtfkruisfw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xylfe.cn/Article/details/gtunsbdccm.html

[R66] 定时任务
来源：http://dali.xylfe.cn/Article/details/gtssrnrnxk.html

crontab -e;  crontab -l
来源：http://dali.guowangkeji.top/Article/details/gtoxpupnhl.html

[R67] 生成随机十六进制串
来源：http://dali.9152youxi.cn/Article/details/gtmeemfesw.html

openssl rand -hex 16
来源：http://dali.andypj.xyz/Article/details/gtxjhwibgu.html

[R68] 计算文件校验值
来源：http://dali.0kj1m.cn/Article/details/gtlilkrspx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hammf.cn/Article/details/gtddplnyum.html

[R69] 生成随机密码
来源：http://dali.tianlin.xyz/Article/details/gtcixfrxyw.html

head -c 16 /dev/urandom | base64
来源：http://dali.redwolf501.top/Article/details/gtzyxnxhek.html

[R70] 时间戳与互转
来源：http://dali.yj20258.top/Article/details/gtkupyhikr.html

date +%s;  date -d @1700000000
来源：http://dali.9152youxi.cn/Article/details/gtlaivkzbw.html

[R71] 日期格式化
来源：http://dali.cqqwz.cn/Article/details/gtpaoggxfz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.nwbrower.top/Article/details/gtygfiaoii.html

[R72] 等待端口就绪
来源：http://dali.fengsongda.top/Article/details/gtbppeckyb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hywenlv.cn/Article/details/gtkvjhzwdw.html

[R73] 分割大日志
来源：http://dali.iojbl.cn/Article/details/gtcprbjahb.html

split -l 1000 big.log part_
来源：http://dali.yueranfly.top/Article/details/gtuipqjuba.html

[R74] 批量重命名
来源：http://dali.cucudq.cn/Article/details/gtcrebhgls.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.chenlongwang.top/Article/details/gtaviyzlky.html

[R75] 导出环境变量
来源：http://dali.sufxvd.cn/Article/details/gtvfutjuhy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xylfe.cn/Article/details/gteovboaxh.html

[R76] 使用临时文件
来源：http://dali.tanke756.top/Article/details/gtwaoigubb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinghuilouyu.cn/Article/details/gtcxsuiclw.html

[R77] 读取用户输入
来源：http://dali.hongshengwenyu.top/Article/details/gtgizhejtf.html

read -rp "请输入: " ans
来源：http://dali.cqqwz.cn/Article/details/gtvxlhqpiy.html

[R78] 交互式菜单
来源：http://dali.zdqjudy.top/Article/details/gtbfgsqkqp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.svipenyu.cn/Article/details/gtxbeiissn.html

[R79] 解析命令行选项
来源：http://dali.yuanzhike.top/Article/details/gtuetgefhy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yuanzhike.top/Article/details/gtmwepnkzn.html

[R80] 查看脚本执行耗时
来源：http://dali.wangdashe.top/Article/details/gtrrftpiyj.html

time ./run.sh
来源：http://dali.dashuyun.cn/Article/details/gtetzinrrc.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtxpharycr.html

S. C / C++ 专题
来源：http://dali.chenjidiqi.icu/Article/details/gtuddtxzia.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtihmeegts.html

[S01] C：Hello World
来源：http://dali.daria6918.cn/Article/details/gtxcwglycw.html

#include <stdio.h>
来源：http://dali.meibo888.top/Article/details/gtkgqhflur.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.guannengcc.top/Article/details/gtawsshhto.html

[S02] C：变量与格式化输出
来源：http://dali.ehwqpu.com/Article/details/gtniqjmptl.html

int a = 10; printf("%d\n", a);
来源：http://dali.tianlin.xyz/Article/details/gtwvakjwvl.html

[S03] C：读入整数
来源：http://dali.jinghuilouyu.cn/Article/details/gtbwbdijxo.html

int x; scanf("%d", &x);
来源：http://dali.zhoulong.xyz/Article/details/gtrykiabgd.html

[S04] C：字符串复制
来源：http://dali.yj202588.top/Article/details/gtizudcxkm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sweek.top/Article/details/gtjnfhyrwl.html

[S05] C：字符串长度
来源：http://dali.gotoacloud.top/Article/details/gtczxpntfp.html

strlen(s)
来源：http://dali.zhengqikj.top/Article/details/gtuelzhhdy.html

[S06] C：字符串比较
来源：http://dali.jiagoushi.top/Article/details/gtpvizzyvz.html

strcmp(a, b) == 0
来源：http://dali.quarkkingdee.top/Article/details/gtuinhyyfd.html

[S07] C：数组遍历求和
来源：http://dali.yvedp.cn/Article/details/gtohmgrfjc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.iojbl.cn/Article/details/gtxkixqzey.html

[S08] C：动态内存分配与释放
来源：http://dali.daria6918.cn/Article/details/gtjkneyplf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zycfv.cn/Article/details/gtojavvlla.html

[S09] C：结构体定义与初始化
来源：http://dali.jinqigfzy.top/Article/details/gtlamkdoku.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.aibaodan.cn/Article/details/gtmsiyekwv.html

[S10] C：指针与解引用
来源：http://dali.316326.xyz/Article/details/gtmheopuew.html

int *p = &a;  *p = 5;
来源：http://dali.jinqigfzy.top/Article/details/gtnumvizpj.html

[S11] C：逐行读文件
来源：http://dali.cucudq.cn/Article/details/gtmagbdthp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xuanzx.com/Article/details/gtdwmmaqoe.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hysaishi.cn/Article/details/gtndcvilix.html

fclose(f);
来源：http://dali.gaohongyu789.top/Article/details/gtrxzaxcrw.html

[S12] C：写文件
来源：http://dali.cqqwz.cn/Article/details/gtdompxlbj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.andypj.xyz/Article/details/gtilgkkxog.html

[S13] C：宏定义
来源：http://dali.nwbrower.top/Article/details/gthhbqcaqy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhongyouzk.top/Article/details/gtkgwlorgm.html

[S14] C：枚举
来源：http://dali.chenzaomai.com/Article/details/gtnzawtipl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.redwolf501.top/Article/details/gtathjfich.html

[S15] C：类型转换
来源：http://dali.yueranfly.top/Article/details/gtjgkyfucg.html

(double) a / b
来源：http://dali.jlsjyb.cn/Article/details/gteszsqrdl.html

[S16] C：位操作置位
来源：http://dali.gzhubu.top/Article/details/gtjosdophl.html

x |= (1 << 3);
来源：http://dali.sxryk.cn/Article/details/gtzwvlfqki.html

[S17] C：安全拼接字符串
来源：http://dali.tanke756.top/Article/details/gtmtfkbmhr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.c1oappe.top/Article/details/gtjnywhxvu.html

[S18] C：命令行参数
来源：http://dali.nanxuanxn.top/Article/details/gtwrppkjss.html

int main(int argc, char **argv)
来源：http://dali.xuanzx.com/Article/details/gtbhlfynug.html

[S19] C：快速排序
来源：http://dali.dashuyun.cn/Article/details/gtwzamlszc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jinqigufen.top/Article/details/gtkuyxtfzq.html

[S20] C：二分查找
来源：http://dali.ydzc1.top/Article/details/gtfkhqxmap.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.kuanghao11.cn/Article/details/gtjzwngyes.html

[S21] C：字符类别判断
来源：http://dali.zhongyouzk.top/Article/details/gtzubdupbv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jyoumei.cn/Article/details/gtljwaxovn.html

[S22] C：字符串转数字
来源：http://dali.jinqigfzy.top/Article/details/gtitetatmd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cheryme.top/Article/details/gtxhflkxsj.html

[S23] C：随机数
来源：http://dali.nanxinkj.top/Article/details/gtugvpadzy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.aizwys.cn/Article/details/gtyqyzjuva.html

[S24] C：获取本地时间
来源：http://dali.chenzaomai.com/Article/details/gtffsidrwn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.gzhubu.top/Article/details/gtdfhahvfi.html

[S25] C：内存拷贝
来源：http://dali.jinqigufen.top/Article/details/gtyfkqxpdu.html

memcpy(dst, src, n);
来源：http://dali.jinghuilouyu.cn/Article/details/gthfkdstyh.html

[S26] C：内存清零
来源：http://dali.hammf.cn/Article/details/gthdjyzaee.html

memset(a, 0, sizeof a);
来源：http://dali.ehwqpu.com/Article/details/gtgumghqyf.html

[S27] C：定义常量
来源：http://dali.nanxuanxn.top/Article/details/gttgkawxem.html

const double PI = 3.14159;
来源：http://dali.tian-w.cn/Article/details/gteezrdmyo.html

[S28] C：静态变量
来源：http://dali.yongpay.top/Article/details/gtmisirrqv.html

static int counter = 0;
来源：http://dali.jinqigufen.top/Article/details/gtpvspqmxk.html

[S29] C：变参函数
来源：http://dali.dashuyun.cn/Article/details/gtjpavtznx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhengqikj.top/Article/details/gtozmlyvfq.html

[S30] C：头文件保护
来源：http://dali.jinghuilouyu.cn/Article/details/gtuychzjed.html

#ifndef X_H
来源：http://dali.andypj.xyz/Article/details/gtuchlynrw.html

#define X_H
来源：http://dali.hywenlv.cn/Article/details/gthrfwbxpj.html

#endif
来源：http://dali.shuidangran.top/Article/details/gtwdxugpfj.html

[S31] C++：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtunsurbtv.html

#include <iostream>
来源：http://dali.jinghuilouyu.cn/Article/details/gtzdbdmxxy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtnrzimcsy.html

[S32] C++：字符串
来源：http://dali.hnxiangtu.top/Article/details/gtrxsguayp.html

std::string s = "hi";  s += "!";
来源：http://dali.yonumen.top/Article/details/gtdpujoask.html

[S33] C++：vector 增删
来源：http://dali.snrcjt.cn/Article/details/gtvxzsbiwc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yvedp.cn/Article/details/gtfwhkejif.html

[S34] C++：遍历 vector
来源：http://dali.gotoacloud.top/Article/details/gtxmzgdhcz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.birdmap.top/Article/details/gtpndotalt.html

[S35] C++：map
来源：http://dali.ybcxt.top/Article/details/gtsnuxwgzm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.dashuyun.cn/Article/details/gtkziaqsrg.html

[S36] C++：unordered_map
来源：http://dali.guannengcc.top/Article/details/gtktjdwgsq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.316326.xyz/Article/details/gtudylptum.html

[S37] C++：set
来源：http://dali.316326.xyz/Article/details/gtvihnesem.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cashguo.top/Article/details/gthxctkcem.html

[S38] C++：排序
来源：http://dali.smart0.xyz/Article/details/gtwhuctnhl.html

std::sort(v.begin(), v.end());
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmfexmubl.html

[S39] C++：自定义比较器排序
来源：http://dali.cheryme.top/Article/details/gtkddytmdw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cqqwz.cn/Article/details/gthoqxxasj.html

[S40] C++：查找元素
来源：http://dali.nanxuanxn.top/Article/details/gtzwvricyg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.dianchejie.cn/Article/details/gtvpayqmbs.html

[S41] C++：类与构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gtswutkahu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ydzc1.top/Article/details/gtdrlpoxpj.html

[S42] C++：继承与虚函数
来源：http://dali.chenjidiqi.icu/Article/details/gtoccvizyn.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhoulong.xyz/Article/details/gtqznyyggl.html

[S43] C++：智能指针
来源：http://dali.svipenyu.cn/Article/details/gtjzejfrec.html

auto p = std::make_unique<int>(5);
来源：http://dali.birdmap.top/Article/details/gtdyuwjnuv.html

[S44] C++：引用传参
来源：http://dali.yuxming.cn/Article/details/gtmeinyjfs.html

void inc(int &x) { ++x; }
来源：http://dali.0kj1m.cn/Article/details/gtjyzbugto.html

[S45] C++：lambda
来源：http://dali.jyoumei.cn/Article/details/gtvzhoacbx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ivvv.top/Article/details/gtuwpiobbh.html

[S46] C++：函数模板
来源：http://dali.jqgufenzy.top/Article/details/gtaxghcthv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.guowangkeji.top/Article/details/gtmbrlzdfs.html

[S47] C++：结构化绑定遍历
来源：http://dali.hfpthk.cn/Article/details/gtifddczns.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gotoacloud.top/Article/details/gtnidhydue.html

[S48] C++：逐行读文件
来源：http://dali.guannengcc.top/Article/details/gtddtwsxhi.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.andypj.xyz/Article/details/gttfmqizdn.html

while (std::getline(in, line)) { }
来源：http://dali.jqgufenzy.top/Article/details/gteshwhgxx.html

[S49] C++：写文件
来源：http://dali.xinyue.icu/Article/details/gtggjhmzgz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhongyouzk.top/Article/details/gtmoxoskti.html

[S50] C++：格式化数字
来源：http://dali.vqdsnc.cn/Article/details/gtenyodxoi.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ivvv.top/Article/details/gtnhlrzapl.html

[S51] C++：显式类型转换
来源：http://dali.aibaodan.cn/Article/details/gtpxqbrcjv.html

static_cast<double>(a) / b
来源：http://dali.yonumen.top/Article/details/gtbouzfwab.html

[S52] C++：const 与 noexcept
来源：http://dali.gotoacloud.top/Article/details/gtehruhjew.html

int size() const noexcept { return n_; }
来源：http://dali.cashguo.top/Article/details/gtlgrgbych.html

[S53] C++：移动语义
来源：http://dali.yj20258.top/Article/details/gtusfvxddj.html

std::vector<int> w = std::move(v);
来源：http://dali.gogol.net.cn/Article/details/gtpgoxebie.html

[S54] C++：异常处理
来源：http://dali.yj202588.top/Article/details/gtbhwmgocw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinqigfzy.top/Article/details/gtnqkcvjxi.html

[S55] C++：结构化绑定
来源：http://dali.xylfe.cn/Article/details/gtgxglczxj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yj20258.top/Article/details/gtjjfjzhme.html

[S56] C++：optional
来源：http://dali.mhx1999.top/Article/details/gtttzvpboc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.fengsongda.top/Article/details/gtiaptjodh.html

[S57] C++：编译期常量
来源：http://dali.ppjwa.cn/Article/details/gtcdmbvqnd.html

constexpr int N = 10;
来源：http://dali.yueranfly.top/Article/details/gtpgsszgmo.html

[S58] C++：命名空间
来源：http://dali.jqgufenzy.top/Article/details/gtarrumlvn.html

namespace ns { int f() { return 1; } }
来源：http://dali.jqgfzy.top/Article/details/gtrxpvuhhy.html

[S59] C++：静态断言
来源：http://dali.vqdsnc.cn/Article/details/gtipffvxas.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.smart0.xyz/Article/details/gtqjmlrctq.html

[S60] C++：遍历并删除元素
来源：http://dali.jinqigfzy.top/Article/details/gtchuqhwvz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gtirkpsqbt.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtvrqlinfq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhiwuduotai.top/Article/details/gtioflnseg.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtsrxngfsy.html

[T01] Kotlin：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtjorleqql.html

println("Hello")
来源：http://dali.ivvv.top/Article/details/gtynxudirm.html

[T02] Kotlin：变量
来源：http://dali.sufxvd.cn/Article/details/gtwxrylgfx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.chenlongwang.top/Article/details/gthqzzopvb.html

[T03] Kotlin：字符串模板
来源：http://dali.ydzc1.top/Article/details/gtzfevrdxk.html

"值: $b"
来源：http://dali.yj202588.top/Article/details/gtceuldhgo.html

[T04] Kotlin：空安全
来源：http://dali.sweek.top/Article/details/gteipoylua.html

val n: String? = null;  n?.length
来源：http://dali.andypj.xyz/Article/details/gttbjiztle.html

[T05] Kotlin：when 表达式
来源：http://dali.ivvv.top/Article/details/gtxzdadrso.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xinyue.icu/Article/details/gtgjkulrpw.html

[T06] Kotlin：集合映射
来源：http://dali.ydzc1.top/Article/details/gtanharfay.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gtszfttcde.html

[T07] Kotlin：集合过滤
来源：http://dali.snrcjt.cn/Article/details/gteecifxhb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zdqjudy.top/Article/details/gtfsktozqb.html

[T08] Kotlin：数据类
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzzchlhep.html

data class User(val name: String, val age: Int)
来源：http://dali.hywenlv.cn/Article/details/gtriyiffdc.html

[T09] Kotlin：扩展函数
来源：http://dali.daria6918.cn/Article/details/gtuwluarsl.html

fun String.exclaim() = this + "!"
来源：http://dali.sufxvd.cn/Article/details/gthnjfjzdz.html

[T10] Kotlin：默认参数
来源：http://dali.jinqigfzy.top/Article/details/gtfeexrvtj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.aizwys.cn/Article/details/gtktkcapau.html

[T11] Kotlin：协程
来源：http://dali.zhixingplan.top/Article/details/gtncruscfs.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.316326.xyz/Article/details/gtsdrzeeft.html

[T12] Kotlin：解构声明
来源：http://dali.chenlongwang.top/Article/details/gtridowqyj.html

val (a, b) = Pair(1, 2)
来源：http://dali.yuxming.cn/Article/details/gtoalsevmp.html

[T13] Kotlin：只读 Map
来源：http://dali.zycfv.cn/Article/details/gtyhcqfeng.html

val m = mapOf("a" to 1)
来源：http://dali.smart0.xyz/Article/details/gtxwsjpwyk.html

[T14] Kotlin：循环
来源：http://dali.havefunace.top/Article/details/gtnlzorsdd.html

for (i in 1..10) println(i)
来源：http://dali.yangfankeji.com/Article/details/gtqcyeakxt.html

[T15] Kotlin：接口
来源：http://dali.iojbl.cn/Article/details/gtbgkjwgyx.html

interface Shape { fun area(): Double }
来源：http://dali.redwolf501.top/Article/details/gtnhatiefh.html

[T16] Swift：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gthdahaymr.html

print("Hello")
来源：http://dali.zhixingplan.top/Article/details/gtksfptrfz.html

[T17] Swift：变量与常量
来源：http://dali.hammf.cn/Article/details/gtoafatlnn.html

var a = 1;  let b = 2
来源：http://dali.smart0.xyz/Article/details/gtomnoavqz.html

[T18] Swift：字符串插值
来源：http://dali.hnxiangtu.top/Article/details/gtmhakxmbl.html

"值: \(b)"
来源：http://dali.tian-w.cn/Article/details/gtpgudxspn.html

[T19] Swift：可选绑定
来源：http://dali.gogol.net.cn/Article/details/gtgywsrxor.html

if let n = opt { print(n) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtaxxiohln.html

[T20] Swift：数组操作
来源：http://dali.cashguo.top/Article/details/gtptrlpdpy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhixingplan.top/Article/details/gttaokmhku.html

[T21] Swift：遍历
来源：http://dali.bjfxy.top/Article/details/gtoqtdbuuy.html

for x in a { print(x) }
来源：http://dali.smart0.xyz/Article/details/gtewatnbgg.html

[T22] Swift：字典
来源：http://dali.dashuyun.cn/Article/details/gtckrtphaa.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.iojbl.cn/Article/details/gtqylcwhyo.html

[T23] Swift：函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtimtvgvns.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sysykeji.top/Article/details/gtiphqxsqp.html

[T24] Swift：闭包
来源：http://dali.andypj.xyz/Article/details/gthfddkibu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jqgfzy.top/Article/details/gtfcmragbz.html

[T25] Swift：结构体
来源：http://dali.zhengqikj.top/Article/details/gthatooypp.html

struct P { var x: Int }
来源：http://dali.cashguo.top/Article/details/gtrpvqvimh.html

[T26] Swift：类与重写
来源：http://dali.yongpay.top/Article/details/gtlykrmtli.html

class A: Base { override func f() {} }
来源：http://dali.iojbl.cn/Article/details/gtzffquxal.html

[T27] Swift：错误处理
来源：http://dali.cucudq.cn/Article/details/gtzfhmobbt.html

do { try f() } catch { print(error) }
来源：http://dali.ydzc1.top/Article/details/gtvikirvdm.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gtixylamfx.html

enum Color { case red, green }
来源：http://dali.hammf.cn/Article/details/gtprqesglr.html

[T29] Swift：guard 提前返回
来源：http://dali.redwolf501.top/Article/details/gtmvgpqihi.html

guard let x = opt else { return }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtackrscoh.html

[T30] Swift：协议
来源：http://dali.yongpay.top/Article/details/gtydeykxqc.html

protocol Shape { func area() -> Double }
来源：http://dali.cqqwz.cn/Article/details/gtrfhwsdrw.html

[T31] Lua：Hello World
来源：http://dali.daria6918.cn/Article/details/gtqhkujtfo.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gtgrrvczok.html

[T32] Lua：局部变量
来源：http://dali.xylfe.cn/Article/details/gturxxwnch.html

local a = 1
来源：http://dali.redwolf501.top/Article/details/gthbclcvqb.html

[T33] Lua：表（数组）
来源：http://dali.c1oappe.top/Article/details/gtgybaffvs.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.dianchejie.cn/Article/details/gtybgfebbn.html

[T34] Lua：遍历表
来源：http://dali.guannengcc.top/Article/details/gtynbkshgq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yvedp.cn/Article/details/gtlikgkmxw.html

[T35] Lua：字典表
来源：http://dali.jinqigufen.top/Article/details/gtojjmucpx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xinyue.icu/Article/details/gtkfawaxbh.html

[T36] Lua：函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtetjjmltl.html

function add(a, b) return a + b end
来源：http://dali.cheryme.top/Article/details/gtmwittiiu.html

[T37] Lua：字符串拼接
来源：http://dali.dianchejie.cn/Article/details/gtfnsqjyjw.html

"a" .. "b"
来源：http://dali.cqqwz.cn/Article/details/gtgqnypcdm.html

[T38] Lua：条件
来源：http://dali.guowangkeji.top/Article/details/gtiqsvwpni.html

if x > 0 then print("正") end
来源：http://dali.zycfv.cn/Article/details/gtehaearzn.html

[T39] Lua：模式匹配
来源：http://dali.yj20258888.top/Article/details/gtredfrdxq.html

string.find(s, "%d+")
来源：http://dali.yj20258888.top/Article/details/gtsprlsaxb.html

[T40] Lua：元表
来源：http://dali.meibo888.top/Article/details/gtssyfrwbq.html

setmetatable({}, { __index = base })
来源：http://dali.gaohongyu789.top/Article/details/gthjpbqwyr.html


<!-- 参考信息 -->