代发 wailian999

cmd > out.log 2>&1
来源：http://dali.gaohongyu789.top/Article/details/gtrdomxygt.html

[R40] 追加写日志
来源：http://dali.chenzaomai.com/Article/details/gtubyllphz.html

echo "log" >> out.log
来源：http://dali.xylfe.cn/Article/details/gtgtutdkpm.html

[R41] 丢弃输出
来源：http://dali.bjfxy.top/Article/details/gtreyzihkv.html

cmd >/dev/null 2>&1
来源：http://dali.snrcjt.cn/Article/details/gtjbyqevcy.html

[R42] 输入重定向
来源：http://dali.svipenyu.cn/Article/details/gtabwqzqth.html

wc -l < a.txt
来源：http://dali.zhengqikj.top/Article/details/gtilxqpntg.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gtrnkwgdhx.html

find . -name "*.log" -type f
来源：http://dali.hysaishi.cn/Article/details/gtbavchxtc.html

[R44] 按修改时间查找
来源：http://dali.nanxuanxn.top/Article/details/gtavzmgzch.html

find . -mtime -7 -type f
来源：http://dali.iojbl.cn/Article/details/gtqijnajml.html

[R45] 批量删除
来源：http://dali.sufxvd.cn/Article/details/gtyeaiqcfd.html

find . -name "*.tmp" -delete
来源：http://dali.shzxlz.cn/Article/details/gtlkhfyhsn.html

[R46] 递归替换文件内容
来源：http://dali.ybcxt.top/Article/details/gtosqezxiu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhoulong.xyz/Article/details/gtqtqrgdma.html

[R47] sed 单行替换
来源：http://dali.cheryme.top/Article/details/gtanuivijl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yangfankeji.com/Article/details/gtxosqzmzi.html

[R48] awk 取指定列
来源：http://dali.sweek.top/Article/details/gtddryqufd.html

awk '{print $1, $3}' a.txt
来源：http://dali.nanxuanxn.top/Article/details/gtncmftzhg.html

[R49] awk 带条件
来源：http://dali.mhx1999.top/Article/details/gtntuiejad.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhengqikj.top/Article/details/gtdmxhacdh.html

[R50] awk 求和
来源：http://dali.yj20258888.top/Article/details/gtujuikppi.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.316326.xyz/Article/details/gtjuvizfgl.html

[R51] 排序去重取前几
来源：http://dali.yuxming.cn/Article/details/gtgbnhejbx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.fengsongda.top/Article/details/gtfklzmzkw.html

[R52] 统计行数
来源：http://dali.cdnleiting.top/Article/details/gtjqiohdez.html

wc -l a.txt
来源：http://dali.redwolf501.top/Article/details/gtvoqujtmw.html

[R53] 查看文件头与实时尾
来源：http://dali.nanxuanxn.top/Article/details/gtrxtpkbuw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jlsjyb.cn/Article/details/gthoqmwemj.html

[R54] 比较两个文件
来源：http://dali.jinqigufen.top/Article/details/gtjswijosq.html

diff a.txt b.txt
来源：http://dali.jqgfzy.top/Article/details/gttxpjkucu.html

[R55] 压缩与解压
来源：http://dali.dianchejie.cn/Article/details/gtyhwoyvyt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.havefunace.top/Article/details/gtjxzizvty.html

[R56] 远程拷贝
来源：http://dali.birdmap.top/Article/details/gtebmxuldv.html

scp file user@host:/path/
来源：http://dali.tanke756.top/Article/details/gtqiwzeppj.html

[R57] 远程执行命令
来源：http://dali.kuanghao11.cn/Article/details/gtcgkxsnjb.html

ssh user@host 'uptime'
来源：http://dali.c1oappe.top/Article/details/gtpuwtznjl.html

[R58] 下载文件
来源：http://dali.c1oappe.top/Article/details/gtcbjahnqe.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cdnleiting.top/Article/details/gtwkytrmpt.html

[R59] 发 POST JSON
来源：http://dali.hnqzz.top/Article/details/gtjjtskrub.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinyuanbaomall.cn/Article/details/gthipvjass.html

[R60] 只看 HTTP 状态码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqirowaib.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.guannengcc.top/Article/details/gtvhkbutal.html

[R61] 磁盘占用
来源：http://dali.chenzaomai.com/Article/details/gtawtpzcod.html

df -h;  du -sh *
来源：http://dali.nanxuanxn.top/Article/details/gtwbppcaia.html

[R62] 找最占空间的文件
来源：http://dali.chenjidiqi.icu/Article/details/gtnlidobye.html

du -ah . | sort -rh | head -10
来源：http://dali.zhengqikj.top/Article/details/gtzuhbkkoh.html

[R63] 内存与进程
来源：http://dali.fzhhl.top/Article/details/gtrdxkvysy.html

free -h;  ps aux | grep nginx
来源：http://dali.nanxuanxn.top/Article/details/gtipnaqxua.html

[R64] 结束进程
来源：http://dali.shzxlz.cn/Article/details/gtmevynigb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.tanke756.top/Article/details/gtiutykczq.html

[R65] 查看端口占用
来源：http://dali.zhengqikj.top/Article/details/gtmifdwaiq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.quarkkingdee.top/Article/details/gtiymlujob.html

[R66] 定时任务
来源：http://dali.iojbl.cn/Article/details/gtjmherzkd.html

crontab -e;  crontab -l
来源：http://dali.daria6918.cn/Article/details/gtlerbuize.html

[R67] 生成随机十六进制串
来源：http://dali.iojbl.cn/Article/details/gthehaiilw.html

openssl rand -hex 16
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvgvxghwi.html

[R68] 计算文件校验值
来源：http://dali.xuanzx.com/Article/details/gtkjmzwbdo.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sufxvd.cn/Article/details/gtaymzyyzw.html

[R69] 生成随机密码
来源：http://dali.ppjwa.cn/Article/details/gtneryzdde.html

head -c 16 /dev/urandom | base64
来源：http://dali.daria6918.cn/Article/details/gtzcavqxoz.html

[R70] 时间戳与互转
来源：http://dali.xylfe.cn/Article/details/gtvkmtuikl.html

date +%s;  date -d @1700000000
来源：http://dali.pengpengdd.cyou/Article/details/gtwkcclxky.html

[R71] 日期格式化
来源：http://dali.jiagoushi.top/Article/details/gtigsexraa.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gaohongyu789.top/Article/details/gtuyhjaznl.html

[R72] 等待端口就绪
来源：http://dali.shuidangran.top/Article/details/gtaardrlwi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinqigufen.top/Article/details/gtvxmmhqpm.html

[R73] 分割大日志
来源：http://dali.hywenlv.cn/Article/details/gtmsaybdql.html

split -l 1000 big.log part_
来源：http://dali.cqqwz.cn/Article/details/gtbvfqojvy.html

[R74] 批量重命名
来源：http://dali.aizwys.cn/Article/details/gtxvidnvco.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yueranfly.top/Article/details/gtsjffhmgy.html

[R75] 导出环境变量
来源：http://dali.andypj.xyz/Article/details/gthstairgu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jinghuilouyu.cn/Article/details/gtjocmswyj.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gtmdtwhfha.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.mhx1999.top/Article/details/gtvoubndzc.html

[R77] 读取用户输入
来源：http://dali.jiagoushi.top/Article/details/gtjpwonbxl.html

read -rp "请输入: " ans
来源：http://dali.tanke756.top/Article/details/gtljzkoatr.html

[R78] 交互式菜单
来源：http://dali.guowangkeji.top/Article/details/gtyrsrjzhh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.tanke756.top/Article/details/gttyiqsuup.html

[R79] 解析命令行选项
来源：http://dali.jlsjyb.cn/Article/details/gtkkwasbjv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shuidangran.top/Article/details/gtwafmlejj.html

[R80] 查看脚本执行耗时
来源：http://dali.fengsongda.top/Article/details/gtdkuowjdq.html

time ./run.sh
来源：http://dali.jiagoushi.top/Article/details/gtsiutckcu.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtbqnmxelb.html

S. C / C++ 专题
来源：http://dali.jinghuilouyu.cn/Article/details/gtzwvjqddk.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtekdzniqf.html

[S01] C：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtoskvwhfw.html

#include <stdio.h>
来源：http://dali.shuidangran.top/Article/details/gtmhysrkzy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yangfankeji.com/Article/details/gtphmgpysh.html

[S02] C：变量与格式化输出
来源：http://dali.havefunace.top/Article/details/gtsgrpvnle.html

int a = 10; printf("%d\n", a);
来源：http://dali.tianlin.xyz/Article/details/gtzarietek.html

[S03] C：读入整数
来源：http://dali.daria6918.cn/Article/details/gtubkxjkvh.html

int x; scanf("%d", &x);
来源：http://dali.yueranfly.top/Article/details/gtxdbdcapf.html

[S04] C：字符串复制
来源：http://dali.aibaodan.cn/Article/details/gtqfqdvnas.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xziqi.cn/Article/details/gturflcdvs.html

[S05] C：字符串长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtreuhvsmg.html

strlen(s)
来源：http://dali.nanxuanxn.top/Article/details/gtytjzsrxa.html

[S06] C：字符串比较
来源：http://dali.pycfn.com/Article/details/gtncytyimr.html

strcmp(a, b) == 0
来源：http://dali.ivvv.top/Article/details/gtdtlumnwg.html

[S07] C：数组遍历求和
来源：http://dali.zhongyouzk.top/Article/details/gtnerkvqod.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jiagoushi.top/Article/details/gtjphlzobd.html

[S08] C：动态内存分配与释放
来源：http://dali.jiagoushi.top/Article/details/gtuykhsdah.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.bjfxy.top/Article/details/gtifcvabek.html

[S09] C：结构体定义与初始化
来源：http://dali.yangfankeji.com/Article/details/gteqvaaydx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbiupndhr.html

[S10] C：指针与解引用
来源：http://dali.quarkkingdee.top/Article/details/gtusztfhvt.html

int *p = &a;  *p = 5;
来源：http://dali.haohaochexian.top/Article/details/gthjhqigqu.html

[S11] C：逐行读文件
来源：http://dali.jinqigufen.top/Article/details/gtwtijqhea.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.sufxvd.cn/Article/details/gtbueebmrg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.pengpengdd.cyou/Article/details/gtlbvtcsna.html

fclose(f);
来源：http://dali.gotoacloud.top/Article/details/gtdanqqanj.html

[S12] C：写文件
来源：http://dali.cashguo.top/Article/details/gtnouapjcs.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.aibaodan.cn/Article/details/gtdagwheuc.html

[S13] C：宏定义
来源：http://dali.yueranfly.top/Article/details/gttffdqwgm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jianghu66.top/Article/details/gtqkpetufg.html

[S14] C：枚举
来源：http://dali.yueranfly.top/Article/details/gtolsylclb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuaquthnx.html

[S15] C：类型转换
来源：http://dali.mhx1999.top/Article/details/gthoniausa.html

(double) a / b
来源：http://dali.jinqigufen.top/Article/details/gttxgevxap.html

[S16] C：位操作置位
来源：http://dali.jqgfzy.top/Article/details/gtiidmiozs.html

x |= (1 << 3);
来源：http://dali.feifeiyinyue.top/Article/details/gthsmgzoax.html

[S17] C：安全拼接字符串
来源：http://dali.aibaodan.cn/Article/details/gtcwnaekek.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.guannengcc.top/Article/details/gtpscnoewc.html

[S18] C：命令行参数
来源：http://dali.zhongyouzk.top/Article/details/gtqxknhjtk.html

int main(int argc, char **argv)
来源：http://dali.ppjwa.cn/Article/details/gtnvdwxewz.html

[S19] C：快速排序
来源：http://dali.tian-w.cn/Article/details/gtdtwqudzj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.svipenyu.cn/Article/details/gtmpcoxzcx.html

[S20] C：二分查找
来源：http://dali.yonumen.top/Article/details/gtvjehtqqr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.nanxuanxn.top/Article/details/gtcqeikyco.html

[S21] C：字符类别判断
来源：http://dali.ehwqpu.com/Article/details/gteolnzwto.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xuetiantiany.cn/Article/details/gtgwyetqun.html

[S22] C：字符串转数字
来源：http://dali.yvedp.cn/Article/details/gtnxpopvqc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hfpthk.cn/Article/details/gtswxwbrvh.html

[S23] C：随机数
来源：http://dali.pengpengdd.cyou/Article/details/gtymdrjngd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.tianlin.xyz/Article/details/gttnlwenpb.html

[S24] C：获取本地时间
来源：http://dali.aibaodan.cn/Article/details/gtfpfwfqjz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.haohaochexian.top/Article/details/gtaqabipox.html

[S25] C：内存拷贝
来源：http://dali.bjfxy.top/Article/details/gtzlonjplp.html

memcpy(dst, src, n);
来源：http://dali.zhengqikj.top/Article/details/gtcaleabgz.html

[S26] C：内存清零
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbgqsuipw.html

memset(a, 0, sizeof a);
来源：http://dali.sxryk.cn/Article/details/gtlbanlunh.html

[S27] C：定义常量
来源：http://dali.pengpengdd.cyou/Article/details/gtceeqktre.html

const double PI = 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gtidfoklni.html

[S28] C：静态变量
来源：http://dali.gotoacloud.top/Article/details/gtrzpyxvew.html

static int counter = 0;
来源：http://dali.bjfxy.top/Article/details/gtjrmfghac.html

[S29] C：变参函数
来源：http://dali.quarkkingdee.top/Article/details/gtetaxeuap.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.andypj.xyz/Article/details/gtatlraqbn.html

[S30] C：头文件保护
来源：http://dali.cucudq.cn/Article/details/gtcavoxyyg.html

#ifndef X_H
来源：http://dali.xziqi.cn/Article/details/gtvslaldid.html

#define X_H
来源：http://dali.316326.xyz/Article/details/gtatjnewkz.html

#endif
来源：http://dali.zhongyouzk.top/Article/details/gthqkbhutv.html

[S31] C++：Hello World
来源：http://dali.nanxinkj.top/Article/details/gtazmcgxew.html

#include <iostream>
来源：http://dali.cucudq.cn/Article/details/gtevevddby.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.kuanghao11.cn/Article/details/gtyzzijwmy.html

[S32] C++：字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxspcysfv.html

std::string s = "hi";  s += "!";
来源：http://dali.0kj1m.cn/Article/details/gtluafszaw.html

[S33] C++：vector 增删
来源：http://dali.xuetiantiany.cn/Article/details/gtfhfnvota.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.redwolf501.top/Article/details/gtltquephf.html

[S34] C++：遍历 vector
来源：http://dali.xuetiantiany.cn/Article/details/gtsftvrzbz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinqigufen.top/Article/details/gtkowloore.html

[S35] C++：map
来源：http://dali.chenlongwang.top/Article/details/gtbcejugda.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tian-w.cn/Article/details/gtqxcduzpm.html

[S36] C++：unordered_map
来源：http://dali.yj20258888.top/Article/details/gtckxzlwtp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zycfv.cn/Article/details/gtccpqbdsd.html

[S37] C++：set
来源：http://dali.havefunace.top/Article/details/gtnqnprjok.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.dianchejie.cn/Article/details/gtairrsfzo.html

[S38] C++：排序
来源：http://dali.cqqwz.cn/Article/details/gtjuzvowsf.html

std::sort(v.begin(), v.end());
来源：http://dali.chenlongwang.top/Article/details/gtonwubtto.html

[S39] C++：自定义比较器排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtspubgfcg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.meibo888.top/Article/details/gtafazlvzu.html

[S40] C++：查找元素
来源：http://dali.guowangkeji.top/Article/details/gtywtdabhm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ivvv.top/Article/details/gtodyprdsx.html

[S41] C++：类与构造函数
来源：http://dali.haohaochexian.top/Article/details/gtpmzccsdr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shanyushiyangtech.top/Article/details/gtbteojftc.html

[S42] C++：继承与虚函数
来源：http://dali.hnqzz.top/Article/details/gtynrqlvcz.html

class B : public Base { public: void f() override {} };
来源：http://dali.hfpthk.cn/Article/details/gteoxadsro.html

[S43] C++：智能指针
来源：http://dali.zhoulong.xyz/Article/details/gtohovuxly.html

auto p = std::make_unique<int>(5);
来源：http://dali.gogol.net.cn/Article/details/gtdvxmpclr.html

[S44] C++：引用传参
来源：http://dali.andypj.xyz/Article/details/gtapmoynon.html

void inc(int &x) { ++x; }
来源：http://dali.yonumen.top/Article/details/gtathdpryt.html

[S45] C++：lambda
来源：http://dali.zhengqikj.top/Article/details/gticcyipsz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtshzuytuh.html

[S46] C++：函数模板
来源：http://dali.cucudq.cn/Article/details/gtjvdusish.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yvedp.cn/Article/details/gtwqzqnoen.html

[S47] C++：结构化绑定遍历
来源：http://dali.yj20258888.top/Article/details/gttcycohmp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.tianlin.xyz/Article/details/gtoxdjnobi.html

[S48] C++：逐行读文件
来源：http://dali.c1oappe.top/Article/details/gtghmqwwrj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shangyingyoupin.top/Article/details/gtcdboijox.html

while (std::getline(in, line)) { }
来源：http://dali.jqgufenzy.top/Article/details/gtmzgnrsed.html

[S49] C++：写文件
来源：http://dali.mhx1999.top/Article/details/gtdsnzzvbe.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhoulong.xyz/Article/details/gtrndotvuy.html

[S50] C++：格式化数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzpesnyua.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gtlqbzmdrc.html

[S51] C++：显式类型转换
来源：http://dali.cheryme.top/Article/details/gtdqmehnbk.html

static_cast<double>(a) / b
来源：http://dali.sxryk.cn/Article/details/gtugxsmell.html

[S52] C++：const 与 noexcept
来源：http://dali.zycfv.cn/Article/details/gtkavhwqnn.html

int size() const noexcept { return n_; }
来源：http://dali.smart0.xyz/Article/details/gtwbpkmfif.html

[S53] C++：移动语义
来源：http://dali.jlsjyb.cn/Article/details/gtfhxvdepo.html

std::vector<int> w = std::move(v);
来源：http://dali.aizwys.cn/Article/details/gtywyhpkeb.html

[S54] C++：异常处理
来源：http://dali.xziqi.cn/Article/details/gtjepjuvtp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhixingplan.top/Article/details/gtmmnqiebt.html

[S55] C++：结构化绑定
来源：http://dali.jiagoushi.top/Article/details/gtgdbvjxxe.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cdnleiting.top/Article/details/gtzgplfyig.html

[S56] C++：optional
来源：http://dali.jlsjyb.cn/Article/details/gtjgjtiqgx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hnqzz.top/Article/details/gtqkfgoknq.html

[S57] C++：编译期常量
来源：http://dali.316326.xyz/Article/details/gtobcchgob.html

constexpr int N = 10;
来源：http://dali.jqgufenzy.top/Article/details/gtacrijyvg.html

[S58] C++：命名空间
来源：http://dali.jqgfzy.top/Article/details/gtlkknnrsh.html

namespace ns { int f() { return 1; } }
来源：http://dali.yj20258888.top/Article/details/gtluamiprc.html

[S59] C++：静态断言
来源：http://dali.zhengqikj.top/Article/details/gtsldwtoqi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.quarkkingdee.top/Article/details/gthpizkqbh.html

[S60] C++：遍历并删除元素
来源：http://dali.hammf.cn/Article/details/gtvlctnxuj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zdqjudy.top/Article/details/gtafbtdzdn.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtjuvaizer.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yj202588.top/Article/details/gtyeuvfmgv.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtoqmmgeqe.html

[T01] Kotlin：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtyreypvcu.html

println("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gttpynbeaw.html

[T02] Kotlin：变量
来源：http://dali.chenjidiqi.icu/Article/details/gtfbeayqph.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhixingplan.top/Article/details/gtqvgjzxyw.html

[T03] Kotlin：字符串模板
来源：http://dali.c1oappe.top/Article/details/gtbenrbdes.html

"值: $b"
来源：http://dali.svipenyu.cn/Article/details/gtecrxcqbi.html

[T04] Kotlin：空安全
来源：http://dali.sufxvd.cn/Article/details/gtgunpcvmo.html

val n: String? = null;  n?.length
来源：http://dali.zhongyouzk.top/Article/details/gtyfsbhadu.html

[T05] Kotlin：when 表达式
来源：http://dali.redwolf501.top/Article/details/gtgobnewbi.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinqigufen.top/Article/details/gtreiksbdu.html

[T06] Kotlin：集合映射
来源：http://dali.xinyue.icu/Article/details/gteqdcugef.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.chenzaomai.com/Article/details/gtbhdfqkzg.html

[T07] Kotlin：集合过滤
来源：http://dali.sweek.top/Article/details/gtphcvcror.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.daria6918.cn/Article/details/gtaveuhocx.html

[T08] Kotlin：数据类
来源：http://dali.gogol.net.cn/Article/details/gtsnmmcwfa.html

data class User(val name: String, val age: Int)
来源：http://dali.jyoumei.cn/Article/details/gtfobpqqkr.html

[T09] Kotlin：扩展函数
来源：http://dali.daria6918.cn/Article/details/gtadqgspcg.html

fun String.exclaim() = this + "!"
来源：http://dali.yangfankeji.com/Article/details/gtrfptgsgy.html

[T10] Kotlin：默认参数
来源：http://dali.316326.xyz/Article/details/gtvkkwvxmd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zycfv.cn/Article/details/gtsdyshkdx.html

[T11] Kotlin：协程
来源：http://dali.dashuyun.cn/Article/details/gtvzaqcvsp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xuetiantiany.cn/Article/details/gtkidzhslr.html

[T12] Kotlin：解构声明
来源：http://dali.xylfe.cn/Article/details/gttpslxycv.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcbnotppe.html

[T13] Kotlin：只读 Map
来源：http://dali.hammf.cn/Article/details/gtyvpuldsz.html

val m = mapOf("a" to 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttqoscxcx.html

[T14] Kotlin：循环
来源：http://dali.tian-w.cn/Article/details/gtrsfmyxxo.html

for (i in 1..10) println(i)
来源：http://dali.jqgfzy.top/Article/details/gtwznuaqtw.html

[T15] Kotlin：接口
来源：http://dali.sweek.top/Article/details/gtnbcufqet.html

interface Shape { fun area(): Double }
来源：http://dali.nwbrower.top/Article/details/gtbaxvwfyv.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtqyddmfxa.html

print("Hello")
来源：http://dali.fzhhl.top/Article/details/gtaiwaahsi.html

[T17] Swift：变量与常量
来源：http://dali.ivvv.top/Article/details/gtjglsbbqy.html

var a = 1;  let b = 2
来源：http://dali.yuanzhike.top/Article/details/gtsjnyizbk.html

[T18] Swift：字符串插值
来源：http://dali.jlsjyb.cn/Article/details/gtpouxlmgk.html

"值: \(b)"
来源：http://dali.yuanzhike.top/Article/details/gtfmmftgpo.html

[T19] Swift：可选绑定
来源：http://dali.gogol.net.cn/Article/details/gtqkicdwvz.html

if let n = opt { print(n) }
来源：http://dali.yj202588.top/Article/details/gthsvpoqvz.html

[T20] Swift：数组操作
来源：http://dali.sufxvd.cn/Article/details/gtpfnukoyy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ydzc1.top/Article/details/gtntpmkani.html

[T21] Swift：遍历
来源：http://dali.yanxiufei.cn/Article/details/gtodbaiddi.html

for x in a { print(x) }
来源：http://dali.xinyue.icu/Article/details/gtlswrjcld.html

[T22] Swift：字典
来源：http://dali.hnqzz.top/Article/details/gtsceqsjos.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.tian-w.cn/Article/details/gtprwfjgsw.html

[T23] Swift：函数
来源：http://dali.yonumen.top/Article/details/gtffbxhevd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yanxiufei.cn/Article/details/gtljcgfefy.html

[T24] Swift：闭包
来源：http://dali.zdqjudy.top/Article/details/gtqqgbolxc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yj20258.top/Article/details/gtbeqjrzpb.html

[T25] Swift：结构体
来源：http://dali.dianchejie.cn/Article/details/gtjytydovz.html

struct P { var x: Int }
来源：http://dali.hywenlv.cn/Article/details/gtidxjowwa.html

[T26] Swift：类与重写
来源：http://dali.yanxiufei.cn/Article/details/gtshnwktai.html

class A: Base { override func f() {} }
来源：http://dali.0kj1m.cn/Article/details/gtwzjokbww.html

[T27] Swift：错误处理
来源：http://dali.yongpay.top/Article/details/gtmsdblifs.html

do { try f() } catch { print(error) }
来源：http://dali.jqgufenzy.top/Article/details/gtcavqjidw.html

[T28] Swift：枚举
来源：http://dali.pycfn.com/Article/details/gtxkxfcnyo.html

enum Color { case red, green }
来源：http://dali.zhixingplan.top/Article/details/gtkxzlcfdy.html

[T29] Swift：guard 提前返回
来源：http://dali.iojbl.cn/Article/details/gtydrtzaxt.html

guard let x = opt else { return }
来源：http://dali.ppjwa.cn/Article/details/gtoawejpno.html

[T30] Swift：协议
来源：http://dali.dianchejie.cn/Article/details/gtnkhjifbx.html

protocol Shape { func area() -> Double }
来源：http://dali.jlsjyb.cn/Article/details/gttdzthjnj.html

[T31] Lua：Hello World
来源：http://dali.gzhubu.top/Article/details/gtohnbqhgx.html

print("Hello")
来源：http://dali.yuanzhike.top/Article/details/gtriodlcpw.html

[T32] Lua：局部变量
来源：http://dali.yongpay.top/Article/details/gtmtqijozd.html

local a = 1
来源：http://dali.jinqigufen.top/Article/details/gtsfjuhwmi.html

[T33] Lua：表（数组）
来源：http://dali.cqqwz.cn/Article/details/gthvunzcdb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.andypj.xyz/Article/details/gttgrlqdla.html

[T34] Lua：遍历表
来源：http://dali.yj20258888.top/Article/details/gtviwtugqv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shzxlz.cn/Article/details/gtvyftkzil.html

[T35] Lua：字典表
来源：http://dali.jinqigfzy.top/Article/details/gtonpxlzue.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cucudq.cn/Article/details/gtkcvwjzcy.html

[T36] Lua：函数
来源：http://dali.yuanzhike.top/Article/details/gtqmemxmrb.html

function add(a, b) return a + b end
来源：http://dali.yj202588.top/Article/details/gtvinpbhud.html

[T37] Lua：字符串拼接
来源：http://dali.gogol.net.cn/Article/details/gtfiuwxous.html

"a" .. "b"
来源：http://dali.jqgufenzy.top/Article/details/gtnvrklznt.html

[T38] Lua：条件
来源：http://dali.shzxlz.cn/Article/details/gtdssdifbq.html

if x > 0 then print("正") end
来源：http://dali.yongpay.top/Article/details/gtfvvamgbf.html

[T39] Lua：模式匹配
来源：http://dali.zycfv.cn/Article/details/gtmtcodvrl.html

string.find(s, "%d+")
来源：http://dali.hnxiangtu.top/Article/details/gtktupfixj.html

[T40] Lua：元表
来源：http://dali.gogol.net.cn/Article/details/gtarhmcnlw.html

setmetatable({}, { __index = base })
来源：http://dali.nwbrower.top/Article/details/gtqclmkmrg.html

[T41] Perl：Hello World
来源：http://dali.hysaishi.cn/Article/details/gtqgykbytv.html

print "Hello\n";
来源：http://dali.gogol.net.cn/Article/details/gtomfwoghy.html

[T42] Perl：变量类型
来源：http://dali.gogol.net.cn/Article/details/gtdfapwqzx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.feifeiyinyue.top/Article/details/gtqiempkmo.html


<!-- 参考信息 -->