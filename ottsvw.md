代发 wailian999

cmd >/dev/null 2>&1
来源：http://dali.hfpthk.cn/Article/details/gtyokxelnc.html

[R42] 输入重定向
来源：http://dali.quarkkingdee.top/Article/details/gtjmgkjtrp.html

wc -l < a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvnujmhta.html

[R43] 按名字查找文件
来源：http://dali.xinyue.icu/Article/details/gtxifbdcew.html

find . -name "*.log" -type f
来源：http://dali.hfpthk.cn/Article/details/gtbmtuyoac.html

[R44] 按修改时间查找
来源：http://dali.sufxvd.cn/Article/details/gtidiklfkv.html

find . -mtime -7 -type f
来源：http://dali.fengsongda.top/Article/details/gtpztpshit.html

[R45] 批量删除
来源：http://dali.vqdsnc.cn/Article/details/gtyqhbfjvg.html

find . -name "*.tmp" -delete
来源：http://dali.hywenlv.cn/Article/details/gtaytggizk.html

[R46] 递归替换文件内容
来源：http://dali.316326.xyz/Article/details/gtkpehiyla.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.9152youxi.cn/Article/details/gtixbyfezu.html

[R47] sed 单行替换
来源：http://dali.sxryk.cn/Article/details/gtcmdxrcuw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xinyue.icu/Article/details/gtedmgirbg.html

[R48] awk 取指定列
来源：http://dali.yj202588.top/Article/details/gttjiwdozc.html

awk '{print $1, $3}' a.txt
来源：http://dali.ybcxt.top/Article/details/gtvhfoonna.html

[R49] awk 带条件
来源：http://dali.jiagoushi.top/Article/details/gtktsfltlm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.snrcjt.cn/Article/details/gtaoprzbld.html

[R50] awk 求和
来源：http://dali.sysykeji.top/Article/details/gtlxegqhsn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yangfankeji.com/Article/details/gtejugpoyr.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gtlaqcctow.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gogol.net.cn/Article/details/gtrtefrbke.html

[R52] 统计行数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsccdvlfj.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gtbqhcnxze.html

[R53] 查看文件头与实时尾
来源：http://dali.chenzaomai.com/Article/details/gtfwjkzpmc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhengqikj.top/Article/details/gthknnjlqw.html

[R54] 比较两个文件
来源：http://dali.meibo888.top/Article/details/gtsfmdigys.html

diff a.txt b.txt
来源：http://dali.ydzc1.top/Article/details/gtiobfuobi.html

[R55] 压缩与解压
来源：http://dali.zhengqikj.top/Article/details/gttyjgeble.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.quarkkingdee.top/Article/details/gtcbtisysd.html

[R56] 远程拷贝
来源：http://dali.ppjwa.cn/Article/details/gtfhvyhvsz.html

scp file user@host:/path/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcbowvoyk.html

[R57] 远程执行命令
来源：http://dali.zycfv.cn/Article/details/gtdyiksxxz.html

ssh user@host 'uptime'
来源：http://dali.jqgufenzy.top/Article/details/gtnmlxgtgb.html

[R58] 下载文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpknuoumq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yj202588.top/Article/details/gtnkjdtwth.html

[R59] 发 POST JSON
来源：http://dali.zhongyouzk.top/Article/details/gtliwwywgc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.vqdsnc.cn/Article/details/gtmgulctaf.html

[R60] 只看 HTTP 状态码
来源：http://dali.zycfv.cn/Article/details/gtfsjrkzfn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cheryme.top/Article/details/gtfoeyhnno.html

[R61] 磁盘占用
来源：http://dali.zhengqikj.top/Article/details/gtiuoslkcn.html

df -h;  du -sh *
来源：http://dali.dashuyun.cn/Article/details/gtaqmyndgt.html

[R62] 找最占空间的文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsddaamhk.html

du -ah . | sort -rh | head -10
来源：http://dali.xylfe.cn/Article/details/gtneuuvcse.html

[R63] 内存与进程
来源：http://dali.yj202588.top/Article/details/gtahwvpkzw.html

free -h;  ps aux | grep nginx
来源：http://dali.hfpthk.cn/Article/details/gtgtiucpcf.html

[R64] 结束进程
来源：http://dali.xziqi.cn/Article/details/gtukghqxsd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtguuuezfs.html

[R65] 查看端口占用
来源：http://dali.sxryk.cn/Article/details/gtdkuiokvu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhoulong.xyz/Article/details/gtadgelvhq.html

[R66] 定时任务
来源：http://dali.hysaishi.cn/Article/details/gtugfpzlym.html

crontab -e;  crontab -l
来源：http://dali.sweek.top/Article/details/gtjaaznzfx.html

[R67] 生成随机十六进制串
来源：http://dali.tianlin.xyz/Article/details/gtyatkiaqm.html

openssl rand -hex 16
来源：http://dali.zhiwuduotai.top/Article/details/gtogzjqwwe.html

[R68] 计算文件校验值
来源：http://dali.shangyingyoupin.top/Article/details/gtksdjdhhh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sxryk.cn/Article/details/gtwmxswdnk.html

[R69] 生成随机密码
来源：http://dali.yueranfly.top/Article/details/gtxvhxvzxp.html

head -c 16 /dev/urandom | base64
来源：http://dali.9152youxi.cn/Article/details/gtlsdigqaj.html

[R70] 时间戳与互转
来源：http://dali.redwolf501.top/Article/details/gtqetolcuh.html

date +%s;  date -d @1700000000
来源：http://dali.havefunace.top/Article/details/gtxabyzein.html

[R71] 日期格式化
来源：http://dali.jinghuilouyu.cn/Article/details/gtvhlcflhi.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hongshengwenyu.top/Article/details/gtiyslixlq.html

[R72] 等待端口就绪
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfjwiizjg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwxnuuylo.html

[R73] 分割大日志
来源：http://dali.fzhhl.top/Article/details/gtosxeqqvt.html

split -l 1000 big.log part_
来源：http://dali.zhiwuduotai.top/Article/details/gteesucgjr.html

[R74] 批量重命名
来源：http://dali.pengpengdd.cyou/Article/details/gtishhzudz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.pycfn.com/Article/details/gtittmduyv.html

[R75] 导出环境变量
来源：http://dali.andypj.xyz/Article/details/gttszdpppf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.chenlongwang.top/Article/details/gtetmsbrii.html

[R76] 使用临时文件
来源：http://dali.xinyue.icu/Article/details/gtdgmimfmj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.sufxvd.cn/Article/details/gtopztawaf.html

[R77] 读取用户输入
来源：http://dali.jianghu66.top/Article/details/gtncdmwbxy.html

read -rp "请输入: " ans
来源：http://dali.yj20258888.top/Article/details/gtamjakyop.html

[R78] 交互式菜单
来源：http://dali.dashuyun.cn/Article/details/gtbkiewokw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.smart0.xyz/Article/details/gtlaajmkip.html

[R79] 解析命令行选项
来源：http://dali.yj20258888.top/Article/details/gtbezqeljt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.fengsongda.top/Article/details/gtrjwpwtex.html

[R80] 查看脚本执行耗时
来源：http://dali.jqgfzy.top/Article/details/gtnxmvycuv.html

time ./run.sh
来源：http://dali.gogol.net.cn/Article/details/gtscscwjey.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtqgyvkzbl.html

S. C / C++ 专题
来源：http://dali.zhongyouzk.top/Article/details/gtvkjrywsk.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gttnichwjk.html

[S01] C：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtplyapbrk.html

#include <stdio.h>
来源：http://dali.cqqwz.cn/Article/details/gtbbyvnbgb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jiagoushi.top/Article/details/gtnkvssvkg.html

[S02] C：变量与格式化输出
来源：http://dali.shuidangran.top/Article/details/gtiesiejhe.html

int a = 10; printf("%d\n", a);
来源：http://dali.0kj1m.cn/Article/details/gttchrgsek.html

[S03] C：读入整数
来源：http://dali.tanke756.top/Article/details/gtxnhsyrbz.html

int x; scanf("%d", &x);
来源：http://dali.tanke756.top/Article/details/gtblxzpxec.html

[S04] C：字符串复制
来源：http://dali.hongshengwenyu.top/Article/details/gtlqgfhnjb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.nanxinkj.top/Article/details/gtvbxmhlbc.html

[S05] C：字符串长度
来源：http://dali.316326.xyz/Article/details/gtpdrwnmqb.html

strlen(s)
来源：http://dali.sweek.top/Article/details/gtyvqttlcq.html

[S06] C：字符串比较
来源：http://dali.yj20258888.top/Article/details/gtnwgqelje.html

strcmp(a, b) == 0
来源：http://dali.316326.xyz/Article/details/gtmwxgemqu.html

[S07] C：数组遍历求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gtroquzytz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hongshengwenyu.top/Article/details/gtwqhbihcc.html

[S08] C：动态内存分配与释放
来源：http://dali.tianlin.xyz/Article/details/gtmfidittg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.nanxinkj.top/Article/details/gtsmfqidlj.html

[S09] C：结构体定义与初始化
来源：http://dali.kuanghao11.cn/Article/details/gtyloxhzdg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.tian-w.cn/Article/details/gtzsilfjkz.html

[S10] C：指针与解引用
来源：http://dali.yanxiufei.cn/Article/details/gtgbmpktcg.html

int *p = &a;  *p = 5;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqmbykrof.html

[S11] C：逐行读文件
来源：http://dali.sxryk.cn/Article/details/gtphgpugyt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zycfv.cn/Article/details/gtevpuwjpf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jinqigufen.top/Article/details/gtbimmvmet.html

fclose(f);
来源：http://dali.hnqzz.top/Article/details/gtmdmkjawd.html

[S12] C：写文件
来源：http://dali.birdmap.top/Article/details/gtvuqkozls.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.nwbrower.top/Article/details/gtbknobirk.html

[S13] C：宏定义
来源：http://dali.mhx1999.top/Article/details/gtxrlchklw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ydzc1.top/Article/details/gtykuvfdzj.html

[S14] C：枚举
来源：http://dali.xuanzx.com/Article/details/gtdgclcemm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zdqjudy.top/Article/details/gtuguhytkh.html

[S15] C：类型转换
来源：http://dali.hysaishi.cn/Article/details/gtlzadcztc.html

(double) a / b
来源：http://dali.cqqwz.cn/Article/details/gtjpgcaser.html

[S16] C：位操作置位
来源：http://dali.hnqzz.top/Article/details/gtfzqfequp.html

x |= (1 << 3);
来源：http://dali.zhixingplan.top/Article/details/gtiuhrdzgt.html

[S17] C：安全拼接字符串
来源：http://dali.tian-w.cn/Article/details/gtjlukjpkf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinqigufen.top/Article/details/gtcddaeajk.html

[S18] C：命令行参数
来源：http://dali.shangyingyoupin.top/Article/details/gtskgqybec.html

int main(int argc, char **argv)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtffpdepas.html

[S19] C：快速排序
来源：http://dali.yonumen.top/Article/details/gtwiryxvsl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.quarkkingdee.top/Article/details/gttxzxguuc.html

[S20] C：二分查找
来源：http://dali.nwbrower.top/Article/details/gtosirixwd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xuetiantiany.cn/Article/details/gtpqlayjtm.html

[S21] C：字符类别判断
来源：http://dali.yuanzhike.top/Article/details/gtvwwdylpg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhengqikj.top/Article/details/gtpunndfuj.html

[S22] C：字符串转数字
来源：http://dali.jyoumei.cn/Article/details/gtblyfeggp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ehwqpu.com/Article/details/gtdrrwkxnw.html

[S23] C：随机数
来源：http://dali.yuxming.cn/Article/details/gtttzvzyyy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.svipenyu.cn/Article/details/gtbbdywjeh.html

[S24] C：获取本地时间
来源：http://dali.wangshuangyany.cn/Article/details/gtvguuddyf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.chenzaomai.com/Article/details/gtgxkeampb.html

[S25] C：内存拷贝
来源：http://dali.fzhhl.top/Article/details/gtcahncypf.html

memcpy(dst, src, n);
来源：http://dali.aibaodan.cn/Article/details/gtyesneoof.html

[S26] C：内存清零
来源：http://dali.nanxinkj.top/Article/details/gtanyifotn.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gtfwikxhvx.html

[S27] C：定义常量
来源：http://dali.yj20258.top/Article/details/gtrgfsvnmx.html

const double PI = 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gtwjzgeseu.html

[S28] C：静态变量
来源：http://dali.fengsongda.top/Article/details/gtjwhdhraf.html

static int counter = 0;
来源：http://dali.jqgufenzy.top/Article/details/gtbpoqkwme.html

[S29] C：变参函数
来源：http://dali.bjfxy.top/Article/details/gteitabfal.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gaohongyu789.top/Article/details/gtfdgsmyrs.html

[S30] C：头文件保护
来源：http://dali.tian-w.cn/Article/details/gtiaxfuvop.html

#ifndef X_H
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuvimmuxy.html

#define X_H
来源：http://dali.mhx1999.top/Article/details/gttdgcjqyi.html

#endif
来源：http://dali.quarkkingdee.top/Article/details/gtafolyvii.html

[S31] C++：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtjlundzhc.html

#include <iostream>
来源：http://dali.xylfe.cn/Article/details/gtuuiflobh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.redwolf501.top/Article/details/gtrbznbejz.html

[S32] C++：字符串
来源：http://dali.jinqigufen.top/Article/details/gtqkdretba.html

std::string s = "hi";  s += "!";
来源：http://dali.bjfxy.top/Article/details/gtlvsokzrz.html

[S33] C++：vector 增删
来源：http://dali.sweek.top/Article/details/gtfvojbibs.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shangyingyoupin.top/Article/details/gtcpjmzmub.html

[S34] C++：遍历 vector
来源：http://dali.zhengqikj.top/Article/details/gtgpatemai.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cqqwz.cn/Article/details/gtytxeerme.html

[S35] C++：map
来源：http://dali.cdnleiting.top/Article/details/gtawipqgmd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gtjzzktxby.html

[S36] C++：unordered_map
来源：http://dali.wangdashe.top/Article/details/gtyiaryvdx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cucudq.cn/Article/details/gtkxlszmfi.html

[S37] C++：set
来源：http://dali.yanxiufei.cn/Article/details/gtqdgdqraw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.chenzaomai.com/Article/details/gtautcesvg.html

[S38] C++：排序
来源：http://dali.gzhubu.top/Article/details/gtpfwyoddx.html

std::sort(v.begin(), v.end());
来源：http://dali.ydzc1.top/Article/details/gtiqwfepxq.html

[S39] C++：自定义比较器排序
来源：http://dali.cucudq.cn/Article/details/gtmyqybgjw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shangyingyoupin.top/Article/details/gtmtypjhul.html

[S40] C++：查找元素
来源：http://dali.cucudq.cn/Article/details/gtifnkdsez.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jianghu66.top/Article/details/gtzqegqxnc.html

[S41] C++：类与构造函数
来源：http://dali.vqdsnc.cn/Article/details/gtujyandgx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sysykeji.top/Article/details/gthapecsok.html

[S42] C++：继承与虚函数
来源：http://dali.yuxming.cn/Article/details/gtaqzuyveo.html

class B : public Base { public: void f() override {} };
来源：http://dali.cheryme.top/Article/details/gtmimppobk.html

[S43] C++：智能指针
来源：http://dali.chenlongwang.top/Article/details/gtfjrwdtuv.html

auto p = std::make_unique<int>(5);
来源：http://dali.quarkkingdee.top/Article/details/gturmzsiiz.html

[S44] C++：引用传参
来源：http://dali.hammf.cn/Article/details/gtxqavefoq.html

void inc(int &x) { ++x; }
来源：http://dali.jqgufenzy.top/Article/details/gtnsgxgoht.html

[S45] C++：lambda
来源：http://dali.cdnleiting.top/Article/details/gtywopwfjd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.c1oappe.top/Article/details/gtwxgzsfhw.html

[S46] C++：函数模板
来源：http://dali.aizwys.cn/Article/details/gtrrvgfchk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jiagoushi.top/Article/details/gtosxddtgx.html

[S47] C++：结构化绑定遍历
来源：http://dali.guannengcc.top/Article/details/gtxhgqxqxm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ppjwa.cn/Article/details/gthhrdghzt.html

[S48] C++：逐行读文件
来源：http://dali.dashuyun.cn/Article/details/gtfwzvqiwo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ppjwa.cn/Article/details/gtsidwibjn.html

while (std::getline(in, line)) { }
来源：http://dali.jlsjyb.cn/Article/details/gtumbeyakl.html

[S49] C++：写文件
来源：http://dali.yanxiufei.cn/Article/details/gtrpsavqxx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.andypj.xyz/Article/details/gteulfoxca.html

[S50] C++：格式化数字
来源：http://dali.dashuyun.cn/Article/details/gtutmddrog.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yvedp.cn/Article/details/gtnthecihv.html

[S51] C++：显式类型转换
来源：http://dali.dashuyun.cn/Article/details/gtgaequprf.html

static_cast<double>(a) / b
来源：http://dali.jianghu66.top/Article/details/gtsdkjbdvy.html

[S52] C++：const 与 noexcept
来源：http://dali.yj20258.top/Article/details/gtnrvjbuoe.html

int size() const noexcept { return n_; }
来源：http://dali.hysaishi.cn/Article/details/gtkdxcupqp.html

[S53] C++：移动语义
来源：http://dali.guowangkeji.top/Article/details/gteswtavxx.html

std::vector<int> w = std::move(v);
来源：http://dali.svipenyu.cn/Article/details/gthtnbvipj.html

[S54] C++：异常处理
来源：http://dali.jyoumei.cn/Article/details/gtvpeitbtx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.tian-w.cn/Article/details/gtforvjnpg.html

[S55] C++：结构化绑定
来源：http://dali.yueranfly.top/Article/details/gtugzumddv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ppjwa.cn/Article/details/gtmeoczvwz.html

[S56] C++：optional
来源：http://dali.shanyushiyangtech.top/Article/details/gtbjypssms.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xylfe.cn/Article/details/gtnbsfuunk.html

[S57] C++：编译期常量
来源：http://dali.xuetiantiany.cn/Article/details/gtntcxecbz.html

constexpr int N = 10;
来源：http://dali.9152youxi.cn/Article/details/gtwahxvxjt.html

[S58] C++：命名空间
来源：http://dali.bjfxy.top/Article/details/gtnbxkiytg.html

namespace ns { int f() { return 1; } }
来源：http://dali.xinyue.icu/Article/details/gtthyhnhyg.html

[S59] C++：静态断言
来源：http://dali.feifeiyinyue.top/Article/details/gtbiusrqxw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.svipenyu.cn/Article/details/gtpiwfqbcp.html

[S60] C++：遍历并删除元素
来源：http://dali.yuanzhike.top/Article/details/gtcfvthean.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.316326.xyz/Article/details/gtdorwlprp.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtduhbwxlt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.smart0.xyz/Article/details/gtlaayfrob.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtfwcpoaoz.html

[T01] Kotlin：Hello World
来源：http://dali.hnqzz.top/Article/details/gtiuulwhel.html

println("Hello")
来源：http://dali.nanxinkj.top/Article/details/gthhcfhuzq.html

[T02] Kotlin：变量
来源：http://dali.jinqigfzy.top/Article/details/gtmjibdbpq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shanyushiyangkeji.top/Article/details/gttfzkrjhl.html

[T03] Kotlin：字符串模板
来源：http://dali.guannengcc.top/Article/details/gtreivfwur.html

"值: $b"
来源：http://dali.nwbrower.top/Article/details/gtchzpkxlf.html

[T04] Kotlin：空安全
来源：http://dali.nanxinkj.top/Article/details/gtjwwzlyhz.html

val n: String? = null;  n?.length
来源：http://dali.yonumen.top/Article/details/gtbowzndng.html

[T05] Kotlin：when 表达式
来源：http://dali.hysaishi.cn/Article/details/gtwdtjpgdd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jiagoushi.top/Article/details/gtgjfpxpex.html

[T06] Kotlin：集合映射
来源：http://dali.yuxming.cn/Article/details/gtsyauwmfc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.guowangkeji.top/Article/details/gtmuoxmcvm.html

[T07] Kotlin：集合过滤
来源：http://dali.tanke756.top/Article/details/gtdzgagkkh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.chenjidiqi.icu/Article/details/gtjfppdtkk.html

[T08] Kotlin：数据类
来源：http://dali.shanyushiyangtech.top/Article/details/gtvwfhlnfa.html

data class User(val name: String, val age: Int)
来源：http://dali.aibaodan.cn/Article/details/gtopllqwbw.html

[T09] Kotlin：扩展函数
来源：http://dali.c1oappe.top/Article/details/gtqzpkkqre.html

fun String.exclaim() = this + "!"
来源：http://dali.dianchejie.cn/Article/details/gtpozwtnsy.html

[T10] Kotlin：默认参数
来源：http://dali.svipenyu.cn/Article/details/gtgkfsmmgc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.tanke756.top/Article/details/gtuweorfmu.html

[T11] Kotlin：协程
来源：http://dali.cucudq.cn/Article/details/gtgebqktut.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.meibo888.top/Article/details/gtqunsipgp.html

[T12] Kotlin：解构声明
来源：http://dali.nanxinkj.top/Article/details/gtrjldywnm.html

val (a, b) = Pair(1, 2)
来源：http://dali.nwbrower.top/Article/details/gthqzqxowt.html

[T13] Kotlin：只读 Map
来源：http://dali.sweek.top/Article/details/gtmixyqmpf.html

val m = mapOf("a" to 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gturscekju.html

[T14] Kotlin：循环
来源：http://dali.cheryme.top/Article/details/gtmjjkqluz.html

for (i in 1..10) println(i)
来源：http://dali.jyoumei.cn/Article/details/gtscvpgmym.html

[T15] Kotlin：接口
来源：http://dali.wangshuangyany.cn/Article/details/gtxyzeahba.html

interface Shape { fun area(): Double }
来源：http://dali.hnqzz.top/Article/details/gtgtuedtny.html

[T16] Swift：Hello World
来源：http://dali.yj202588.top/Article/details/gttbvapufz.html

print("Hello")
来源：http://dali.0kj1m.cn/Article/details/gtirpsfsss.html

[T17] Swift：变量与常量
来源：http://dali.hnqzz.top/Article/details/gtpzmfldjk.html

var a = 1;  let b = 2
来源：http://dali.andypj.xyz/Article/details/gtlhfrfplx.html

[T18] Swift：字符串插值
来源：http://dali.kuanghao11.cn/Article/details/gtkdyjzdex.html

"值: \(b)"
来源：http://dali.zycfv.cn/Article/details/gtxjimidim.html

[T19] Swift：可选绑定
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaawopvuf.html

if let n = opt { print(n) }
来源：http://dali.0kj1m.cn/Article/details/gtzoacvqer.html

[T20] Swift：数组操作
来源：http://dali.shuidangran.top/Article/details/gthatuxwdy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ppjwa.cn/Article/details/gtpebbioqz.html

[T21] Swift：遍历
来源：http://dali.yuanzhike.top/Article/details/gtrbtqghqy.html

for x in a { print(x) }
来源：http://dali.zhoulong.xyz/Article/details/gteptpocmf.html

[T22] Swift：字典
来源：http://dali.hongshengwenyu.top/Article/details/gttveddkxv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.vqdsnc.cn/Article/details/gtdnwjpobj.html

[T23] Swift：函数
来源：http://dali.wangshuangyany.cn/Article/details/gtwrlhcjbb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cdnleiting.top/Article/details/gtssuxzild.html

[T24] Swift：闭包
来源：http://dali.smart0.xyz/Article/details/gtuegotqea.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.nanxuanxn.top/Article/details/gtpbqvmqla.html

[T25] Swift：结构体
来源：http://dali.yongpay.top/Article/details/gtsuokwsha.html

struct P { var x: Int }
来源：http://dali.nanxuanxn.top/Article/details/gtrhaojbbe.html

[T26] Swift：类与重写
来源：http://dali.cdnleiting.top/Article/details/gtpmegbyzx.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gtdlfdicag.html

[T27] Swift：错误处理
来源：http://dali.haohaochexian.top/Article/details/gtvcqmhbnm.html

do { try f() } catch { print(error) }
来源：http://dali.yuanzhike.top/Article/details/gteovqiyyt.html

[T28] Swift：枚举
来源：http://dali.shzxlz.cn/Article/details/gtchezeewd.html

enum Color { case red, green }
来源：http://dali.pycfn.com/Article/details/gtzkaznmhx.html

[T29] Swift：guard 提前返回
来源：http://dali.aizwys.cn/Article/details/gtwhrzeljk.html

guard let x = opt else { return }
来源：http://dali.shangyingyoupin.top/Article/details/gtcjsqnubi.html

[T30] Swift：协议
来源：http://dali.shanyushiyangtech.top/Article/details/gtvzyuypdp.html

protocol Shape { func area() -> Double }
来源：http://dali.xziqi.cn/Article/details/gtusgpjqlb.html

[T31] Lua：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnekqobvn.html

print("Hello")
来源：http://dali.yuxming.cn/Article/details/gtjcdedkws.html

[T32] Lua：局部变量
来源：http://dali.cdnleiting.top/Article/details/gtgdlgjygu.html

local a = 1
来源：http://dali.kuanghao11.cn/Article/details/gtdyoufdxj.html

[T33] Lua：表（数组）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdycbfknt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cqqwz.cn/Article/details/gtrurzvxog.html

[T34] Lua：遍历表
来源：http://dali.svipenyu.cn/Article/details/gtlydlidjl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.feifeiyinyue.top/Article/details/gtkslqkpnp.html

[T35] Lua：字典表
来源：http://dali.yongpay.top/Article/details/gtmkxseyez.html

local d = { a = 1 };  d.b = 2
来源：http://dali.haohaochexian.top/Article/details/gthqauiunt.html

[T36] Lua：函数
来源：http://dali.316326.xyz/Article/details/gtdugsajho.html

function add(a, b) return a + b end
来源：http://dali.xziqi.cn/Article/details/gtmrpfgcxe.html

[T37] Lua：字符串拼接
来源：http://dali.wangdashe.top/Article/details/gtoerfwzdc.html

"a" .. "b"
来源：http://dali.jinqigufen.top/Article/details/gtlmjczins.html

[T38] Lua：条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrjerfxqm.html

if x > 0 then print("正") end
来源：http://dali.aibaodan.cn/Article/details/gtkyghbjey.html

[T39] Lua：模式匹配
来源：http://dali.quarkkingdee.top/Article/details/gtnlgcebfc.html

string.find(s, "%d+")
来源：http://dali.shangyingyoupin.top/Article/details/gtetbrjjbb.html

[T40] Lua：元表
来源：http://dali.shangyingyoupin.top/Article/details/gtmqhxmdxg.html

setmetatable({}, { __index = base })
来源：http://dali.birdmap.top/Article/details/gtvbtovubf.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtritzouab.html

print "Hello\n";
来源：http://dali.yj20258.top/Article/details/gtvvpybfkd.html

[T42] Perl：变量类型
来源：http://dali.andypj.xyz/Article/details/gtmgqmchmi.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yj202588.top/Article/details/gtuawjcqkl.html

[T43] Perl：字符串插值
来源：http://dali.yonumen.top/Article/details/gtgcqrttwm.html

"值: $a"
来源：http://dali.bjfxy.top/Article/details/gtpbijefzk.html

[T44] Perl：条件
来源：http://dali.hnqzz.top/Article/details/gtaqepqxqt.html

if ($a > 0) { print "正"; }
来源：http://dali.dianchejie.cn/Article/details/gtagoladow.html


<!-- 参考信息 -->