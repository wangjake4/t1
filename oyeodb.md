代发 wailian999

files=$(ls -1)
来源：http://dali.iojbl.cn/Article/details/gtexdrvzxw.html

[R38] 管道串联
来源：http://dali.gzhubu.top/Article/details/gtkeguripy.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinqigfzy.top/Article/details/gtknljtcbk.html

[R39] 重定向标准输出与错误
来源：http://dali.fzhhl.top/Article/details/gtfmgjjwfk.html

cmd > out.log 2>&1
来源：http://dali.hfpthk.cn/Article/details/gtgnjigvnr.html

[R40] 追加写日志
来源：http://dali.xuetiantiany.cn/Article/details/gtdczuduzj.html

echo "log" >> out.log
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttutecqgi.html

[R41] 丢弃输出
来源：http://dali.xinyue.icu/Article/details/gtkypjwntu.html

cmd >/dev/null 2>&1
来源：http://dali.gaohongyu789.top/Article/details/gtkvrqxkpl.html

[R42] 输入重定向
来源：http://dali.hnxiangtu.top/Article/details/gtfgtvjcsr.html

wc -l < a.txt
来源：http://dali.jianghu66.top/Article/details/gtactaxffh.html

[R43] 按名字查找文件
来源：http://dali.cucudq.cn/Article/details/gtzjfuzvos.html

find . -name "*.log" -type f
来源：http://dali.zdqjudy.top/Article/details/gtnfuykddn.html

[R44] 按修改时间查找
来源：http://dali.yongpay.top/Article/details/gtfdtetquw.html

find . -mtime -7 -type f
来源：http://dali.shanyushiyangtech.top/Article/details/gtwzfkklrv.html

[R45] 批量删除
来源：http://dali.aizwys.cn/Article/details/gteosorwsj.html

find . -name "*.tmp" -delete
来源：http://dali.iojbl.cn/Article/details/gtrozmpygw.html

[R46] 递归替换文件内容
来源：http://dali.hywenlv.cn/Article/details/gtprzadmjz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.nanxuanxn.top/Article/details/gtadjshvpm.html

[R47] sed 单行替换
来源：http://dali.daria6918.cn/Article/details/gtyqiurbcp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zdqjudy.top/Article/details/gtlxiafupo.html

[R48] awk 取指定列
来源：http://dali.316326.xyz/Article/details/gtmlntzpiq.html

awk '{print $1, $3}' a.txt
来源：http://dali.hfpthk.cn/Article/details/gthjqiyngy.html

[R49] awk 带条件
来源：http://dali.hywenlv.cn/Article/details/gtizrhxqgo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gtmjwjmezu.html

[R50] awk 求和
来源：http://dali.yonumen.top/Article/details/gtypkkbrlg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtrotdcxtr.html

[R51] 排序去重取前几
来源：http://dali.jyoumei.cn/Article/details/gtmtltrnjj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.sweek.top/Article/details/gtqwpqjjpi.html

[R52] 统计行数
来源：http://dali.aizwys.cn/Article/details/gtjuiaztfn.html

wc -l a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkyvjdhji.html

[R53] 查看文件头与实时尾
来源：http://dali.yj20258.top/Article/details/gtojdswyfk.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinghuilouyu.cn/Article/details/gtctwtxcmp.html

[R54] 比较两个文件
来源：http://dali.tian-w.cn/Article/details/gtlfzfcqwk.html

diff a.txt b.txt
来源：http://dali.nanxinkj.top/Article/details/gtfmqxnluo.html

[R55] 压缩与解压
来源：http://dali.svipenyu.cn/Article/details/gturvdwklz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.birdmap.top/Article/details/gtmxzialwy.html

[R56] 远程拷贝
来源：http://dali.smart0.xyz/Article/details/gtiunkgynp.html

scp file user@host:/path/
来源：http://dali.cheryme.top/Article/details/gtslgdchfp.html

[R57] 远程执行命令
来源：http://dali.bjfxy.top/Article/details/gtefzbvnbw.html

ssh user@host 'uptime'
来源：http://dali.chenlongwang.top/Article/details/gtyrhzpsdg.html

[R58] 下载文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtgmrjkqxh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.quarkkingdee.top/Article/details/gtlcqnkoxq.html

[R59] 发 POST JSON
来源：http://dali.guannengcc.top/Article/details/gtanxmdgts.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yuanzhike.top/Article/details/gtchqeahlp.html

[R60] 只看 HTTP 状态码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxuxeixoj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shangyingyoupin.top/Article/details/gtqhllvlrf.html

[R61] 磁盘占用
来源：http://dali.pengpengdd.cyou/Article/details/gttezztiza.html

df -h;  du -sh *
来源：http://dali.xinyue.icu/Article/details/gturrmkboy.html

[R62] 找最占空间的文件
来源：http://dali.quarkkingdee.top/Article/details/gtrsggvhky.html

du -ah . | sort -rh | head -10
来源：http://dali.aibaodan.cn/Article/details/gtlljhimmi.html

[R63] 内存与进程
来源：http://dali.chenzaomai.com/Article/details/gtzijdislo.html

free -h;  ps aux | grep nginx
来源：http://dali.hongshengwenyu.top/Article/details/gtjwnyavsz.html

[R64] 结束进程
来源：http://dali.jyoumei.cn/Article/details/gtrkrprbtt.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hywenlv.cn/Article/details/gtmabwudvj.html

[R65] 查看端口占用
来源：http://dali.dianchejie.cn/Article/details/gtllqwssoy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhongyouzk.top/Article/details/gtrfdisncx.html

[R66] 定时任务
来源：http://dali.meibo888.top/Article/details/gtpyrbxmqs.html

crontab -e;  crontab -l
来源：http://dali.cheryme.top/Article/details/gtjqnmncko.html

[R67] 生成随机十六进制串
来源：http://dali.316326.xyz/Article/details/gtimervgoh.html

openssl rand -hex 16
来源：http://dali.xuetiantiany.cn/Article/details/gtyuhvpbba.html

[R68] 计算文件校验值
来源：http://dali.ehwqpu.com/Article/details/gtczfydsyz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.meibo888.top/Article/details/gtrgtzshdi.html

[R69] 生成随机密码
来源：http://dali.hnxiangtu.top/Article/details/gtxpfamdih.html

head -c 16 /dev/urandom | base64
来源：http://dali.daxiang520.top/Article/details/gtbbswmely.html

[R70] 时间戳与互转
来源：http://dali.snrcjt.cn/Article/details/gtszbnvrhu.html

date +%s;  date -d @1700000000
来源：http://dali.dianchejie.cn/Article/details/gtfnmnsbqe.html

[R71] 日期格式化
来源：http://dali.zhiwuduotai.top/Article/details/gtcfwxdkto.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hongshengwenyu.top/Article/details/gttrpkvlrg.html

[R72] 等待端口就绪
来源：http://dali.fengsongda.top/Article/details/gtzbrdtlox.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hammf.cn/Article/details/gtyookdsxk.html

[R73] 分割大日志
来源：http://dali.xinyue.icu/Article/details/gtrhehxury.html

split -l 1000 big.log part_
来源：http://dali.quarkkingdee.top/Article/details/gtraakarys.html

[R74] 批量重命名
来源：http://dali.daria6918.cn/Article/details/gtjicxyjne.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.daria6918.cn/Article/details/gtozxwgcqi.html

[R75] 导出环境变量
来源：http://dali.nanxinkj.top/Article/details/gtfpwvmhql.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yueranfly.top/Article/details/gtopyiesgf.html

[R76] 使用临时文件
来源：http://dali.yongpay.top/Article/details/gtcqegkpdw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhengqikj.top/Article/details/gtbsocgddz.html

[R77] 读取用户输入
来源：http://dali.zdqjudy.top/Article/details/gtyhhtsvgs.html

read -rp "请输入: " ans
来源：http://dali.aibaodan.cn/Article/details/gtoofgqams.html

[R78] 交互式菜单
来源：http://dali.pycfn.com/Article/details/gtuivzjord.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gzhubu.top/Article/details/gtkeskuvom.html

[R79] 解析命令行选项
来源：http://dali.haohaochexian.top/Article/details/gtpsujkywc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.fengsongda.top/Article/details/gtatcpvexa.html

[R80] 查看脚本执行耗时
来源：http://dali.wangshuangyany.cn/Article/details/gtkxlxbytn.html

time ./run.sh
来源：http://dali.ivvv.top/Article/details/gtwatjbprr.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtmhebcwlo.html

S. C / C++ 专题
来源：http://dali.hongshengwenyu.top/Article/details/gtzemlrxbd.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtufytdzgh.html

[S01] C：Hello World
来源：http://dali.bjfxy.top/Article/details/gtrdirxygp.html

#include <stdio.h>
来源：http://dali.yj20258.top/Article/details/gtkgyvvgmp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hysaishi.cn/Article/details/gtemrsjznx.html

[S02] C：变量与格式化输出
来源：http://dali.ehwqpu.com/Article/details/gtxhwletck.html

int a = 10; printf("%d\n", a);
来源：http://dali.xuetiantiany.cn/Article/details/gtmdjwfscs.html

[S03] C：读入整数
来源：http://dali.xziqi.cn/Article/details/gtagzfklur.html

int x; scanf("%d", &x);
来源：http://dali.hammf.cn/Article/details/gtcwefxdpn.html

[S04] C：字符串复制
来源：http://dali.snrcjt.cn/Article/details/gtkosnqfog.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.aizwys.cn/Article/details/gtxhtvarju.html

[S05] C：字符串长度
来源：http://dali.yuxming.cn/Article/details/gtcqruoznv.html

strlen(s)
来源：http://dali.jqgfzy.top/Article/details/gtezorsevp.html

[S06] C：字符串比较
来源：http://dali.yonumen.top/Article/details/gtwjugiisq.html

strcmp(a, b) == 0
来源：http://dali.yj202588.top/Article/details/gtlvejeduj.html

[S07] C：数组遍历求和
来源：http://dali.nanxinkj.top/Article/details/gtilgsvgfx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xuanzx.com/Article/details/gtljhvesfz.html

[S08] C：动态内存分配与释放
来源：http://dali.kuanghao11.cn/Article/details/gtinpphpfd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinghuilouyu.cn/Article/details/gtuczfitpd.html

[S09] C：结构体定义与初始化
来源：http://dali.iojbl.cn/Article/details/gthzuoytdy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jqgfzy.top/Article/details/gtdywgwtgw.html

[S10] C：指针与解引用
来源：http://dali.cashguo.top/Article/details/gtdglmotml.html

int *p = &a;  *p = 5;
来源：http://dali.0kj1m.cn/Article/details/gtfplkvqla.html

[S11] C：逐行读文件
来源：http://dali.zhiwuduotai.top/Article/details/gtpybjxobp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gtlhzgtwmf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yvedp.cn/Article/details/gtfcrgwtrc.html

fclose(f);
来源：http://dali.nanxuanxn.top/Article/details/gtfeyvcwmk.html

[S12] C：写文件
来源：http://dali.daria6918.cn/Article/details/gtjqxrrfmg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhiwuduotai.top/Article/details/gtyscvxvwr.html

[S13] C：宏定义
来源：http://dali.ivvv.top/Article/details/gtxbmdnedo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shuidangran.top/Article/details/gtehwuglub.html

[S14] C：枚举
来源：http://dali.cheryme.top/Article/details/gtltdfwffj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yongpay.top/Article/details/gtbvmlreom.html

[S15] C：类型转换
来源：http://dali.hongshengwenyu.top/Article/details/gtoclbabqp.html

(double) a / b
来源：http://dali.pengpengdd.cyou/Article/details/gtxmnmbvgl.html

[S16] C：位操作置位
来源：http://dali.dashuyun.cn/Article/details/gtaldaadok.html

x |= (1 << 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtemhhssoc.html

[S17] C：安全拼接字符串
来源：http://dali.zdqjudy.top/Article/details/gtjyehvqbq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ydzc1.top/Article/details/gtmdlsqcay.html

[S18] C：命令行参数
来源：http://dali.sysykeji.top/Article/details/gttgfmdsqr.html

int main(int argc, char **argv)
来源：http://dali.wangshuangyany.cn/Article/details/gtkutanedo.html

[S19] C：快速排序
来源：http://dali.hfpthk.cn/Article/details/gtblbpdapv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zycfv.cn/Article/details/gtltlvubcf.html

[S20] C：二分查找
来源：http://dali.zhiwuduotai.top/Article/details/gtqiawvroj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xuetiantiany.cn/Article/details/gtuvaxzdpb.html

[S21] C：字符类别判断
来源：http://dali.redwolf501.top/Article/details/gtqdzravle.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.birdmap.top/Article/details/gttycrqeyp.html

[S22] C：字符串转数字
来源：http://dali.shangyingyoupin.top/Article/details/gtpmuzxgsm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.9152youxi.cn/Article/details/gtynnbgrbv.html

[S23] C：随机数
来源：http://dali.fzhhl.top/Article/details/gtkjyqqsmj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shzxlz.cn/Article/details/gtapeelswt.html

[S24] C：获取本地时间
来源：http://dali.hammf.cn/Article/details/gtpqrfzchy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yj20258888.top/Article/details/gtqupitfob.html

[S25] C：内存拷贝
来源：http://dali.pycfn.com/Article/details/gtyjklumuy.html

memcpy(dst, src, n);
来源：http://dali.kuanghao11.cn/Article/details/gtpnmabeqz.html

[S26] C：内存清零
来源：http://dali.shuidangran.top/Article/details/gtofeiwdfm.html

memset(a, 0, sizeof a);
来源：http://dali.hysaishi.cn/Article/details/gtcqpupssy.html

[S27] C：定义常量
来源：http://dali.hywenlv.cn/Article/details/gtmiaxqlyz.html

const double PI = 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gtvsfswhek.html

[S28] C：静态变量
来源：http://dali.xinyue.icu/Article/details/gtphruatvz.html

static int counter = 0;
来源：http://dali.yuanzhike.top/Article/details/gtdvmwueqt.html

[S29] C：变参函数
来源：http://dali.jlsjyb.cn/Article/details/gtuqbsmusj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.kuanghao11.cn/Article/details/gtoonntdru.html

[S30] C：头文件保护
来源：http://dali.hysaishi.cn/Article/details/gtsgbctizl.html

#ifndef X_H
来源：http://dali.yongpay.top/Article/details/gthgprftyk.html

#define X_H
来源：http://dali.yongpay.top/Article/details/gtmfsscjsf.html

#endif
来源：http://dali.xziqi.cn/Article/details/gttbpvjmzu.html

[S31] C++：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtlxofbvpv.html

#include <iostream>
来源：http://dali.jinqigfzy.top/Article/details/gttukokeun.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.mhx1999.top/Article/details/gtvsaowhxv.html

[S32] C++：字符串
来源：http://dali.xuanzx.com/Article/details/gtjoyfddnt.html

std::string s = "hi";  s += "!";
来源：http://dali.xziqi.cn/Article/details/gtjrlxfnge.html

[S33] C++：vector 增删
来源：http://dali.hongshengwenyu.top/Article/details/gtossrhawz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cheryme.top/Article/details/gtqrbhqjeu.html

[S34] C++：遍历 vector
来源：http://dali.cucudq.cn/Article/details/gtuqgpfyth.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtytwsoknq.html

[S35] C++：map
来源：http://dali.daria6918.cn/Article/details/gtnwdfducu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtjfoelugq.html

[S36] C++：unordered_map
来源：http://dali.tian-w.cn/Article/details/gtrblonsbg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiwnsllkx.html

[S37] C++：set
来源：http://dali.tian-w.cn/Article/details/gtncvjrdbx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yueranfly.top/Article/details/gtxwttxcjn.html

[S38] C++：排序
来源：http://dali.shanyushiyangtech.top/Article/details/gtewvoyomf.html

std::sort(v.begin(), v.end());
来源：http://dali.yj20258.top/Article/details/gtglrdpimn.html

[S39] C++：自定义比较器排序
来源：http://dali.zdqjudy.top/Article/details/gtjqiaropz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gogol.net.cn/Article/details/gtfyyuzblr.html

[S40] C++：查找元素
来源：http://dali.sxryk.cn/Article/details/gtsigldvzi.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.daria6918.cn/Article/details/gtqauziole.html

[S41] C++：类与构造函数
来源：http://dali.gzhubu.top/Article/details/gteriejglr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jyoumei.cn/Article/details/gtzmdjysej.html

[S42] C++：继承与虚函数
来源：http://dali.zhixingplan.top/Article/details/gtaieiqcwj.html

class B : public Base { public: void f() override {} };
来源：http://dali.tian-w.cn/Article/details/gtqumxvcod.html

[S43] C++：智能指针
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnffmytxk.html

auto p = std::make_unique<int>(5);
来源：http://dali.svipenyu.cn/Article/details/gtugfveajh.html

[S44] C++：引用传参
来源：http://dali.smart0.xyz/Article/details/gtxxoxabnw.html

void inc(int &x) { ++x; }
来源：http://dali.chenzaomai.com/Article/details/gtqiqtafnw.html

[S45] C++：lambda
来源：http://dali.zhoulong.xyz/Article/details/gtvebrrjtg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cheryme.top/Article/details/gteemqfgyt.html

[S46] C++：函数模板
来源：http://dali.xylfe.cn/Article/details/gtyocftfzv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yvedp.cn/Article/details/gtlncvurkg.html

[S47] C++：结构化绑定遍历
来源：http://dali.gotoacloud.top/Article/details/gtzcmdmvxq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.redwolf501.top/Article/details/gttkzotldk.html

[S48] C++：逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gtojasewhx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.bjfxy.top/Article/details/gtqxfzeiox.html

while (std::getline(in, line)) { }
来源：http://dali.xuanzx.com/Article/details/gtudaosudx.html

[S49] C++：写文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtopptwirm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtghefgytk.html

[S50] C++：格式化数字
来源：http://dali.guannengcc.top/Article/details/gtdtygkmml.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gtkjzxxevq.html

[S51] C++：显式类型转换
来源：http://dali.tianlin.xyz/Article/details/gtbhhptfos.html

static_cast<double>(a) / b
来源：http://dali.andypj.xyz/Article/details/gtvleqtzpo.html

[S52] C++：const 与 noexcept
来源：http://dali.kuanghao11.cn/Article/details/gthaewlasi.html

int size() const noexcept { return n_; }
来源：http://dali.wangdashe.top/Article/details/gtlphfncxw.html

[S53] C++：移动语义
来源：http://dali.tian-w.cn/Article/details/gtsjhdtubb.html

std::vector<int> w = std::move(v);
来源：http://dali.yuxming.cn/Article/details/gtjyfttzjq.html

[S54] C++：异常处理
来源：http://dali.shuidangran.top/Article/details/gtdaytbwsc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.pycfn.com/Article/details/gttegwvmwx.html

[S55] C++：结构化绑定
来源：http://dali.guannengcc.top/Article/details/gtgnexajag.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.wangdashe.top/Article/details/gtnqtkviud.html

[S56] C++：optional
来源：http://dali.zycfv.cn/Article/details/gtnwyycgmv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yonumen.top/Article/details/gtdwwalcwp.html

[S57] C++：编译期常量
来源：http://dali.jqgufenzy.top/Article/details/gtlsxjlxxl.html

constexpr int N = 10;
来源：http://dali.yangfankeji.com/Article/details/gtdnapouku.html

[S58] C++：命名空间
来源：http://dali.yongpay.top/Article/details/gttjpzywud.html

namespace ns { int f() { return 1; } }
来源：http://dali.havefunace.top/Article/details/gtwuqhtcjv.html

[S59] C++：静态断言
来源：http://dali.jqgfzy.top/Article/details/gtvtlqkxwi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zdqjudy.top/Article/details/gtzgpfswbz.html

[S60] C++：遍历并删除元素
来源：http://dali.xuanzx.com/Article/details/gtwvlrsqef.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.pengpengdd.cyou/Article/details/gtzprrgvsq.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtuhyuoqnk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gtcndncham.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtcppopzgp.html

[T01] Kotlin：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gtalvupdqu.html

println("Hello")
来源：http://dali.cashguo.top/Article/details/gtqzgrvare.html

[T02] Kotlin：变量
来源：http://dali.havefunace.top/Article/details/gtmkkclisa.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yueranfly.top/Article/details/gtqvvlnjmp.html

[T03] Kotlin：字符串模板
来源：http://dali.yueranfly.top/Article/details/gtcfioqeua.html

"值: $b"
来源：http://dali.kuanghao11.cn/Article/details/gtqawdhrkn.html

[T04] Kotlin：空安全
来源：http://dali.kuanghao11.cn/Article/details/gtlvmitxzl.html

val n: String? = null;  n?.length
来源：http://dali.jqgfzy.top/Article/details/gtgqwdtuki.html

[T05] Kotlin：when 表达式
来源：http://dali.yongpay.top/Article/details/gtfsewppyr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jqgfzy.top/Article/details/gtrifdfkpy.html

[T06] Kotlin：集合映射
来源：http://dali.shzxlz.cn/Article/details/gtrzjubdyy.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hnxiangtu.top/Article/details/gtsgmsnunb.html

[T07] Kotlin：集合过滤
来源：http://dali.fzhhl.top/Article/details/gtimlptohs.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.vqdsnc.cn/Article/details/gthpibwqri.html

[T08] Kotlin：数据类
来源：http://dali.ivvv.top/Article/details/gtomhwlemv.html

data class User(val name: String, val age: Int)
来源：http://dali.chenjidiqi.icu/Article/details/gtfsinwbno.html

[T09] Kotlin：扩展函数
来源：http://dali.daxiang520.top/Article/details/gtrcxrkslo.html

fun String.exclaim() = this + "!"
来源：http://dali.yj20258888.top/Article/details/gtymevxtbl.html

[T10] Kotlin：默认参数
来源：http://dali.havefunace.top/Article/details/gtfofzgyqr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hnqzz.top/Article/details/gtfgynrrau.html

[T11] Kotlin：协程
来源：http://dali.snrcjt.cn/Article/details/gtbgsavipm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xuetiantiany.cn/Article/details/gtmkfshipr.html

[T12] Kotlin：解构声明
来源：http://dali.shanyushiyangtech.top/Article/details/gtblbknovx.html

val (a, b) = Pair(1, 2)
来源：http://dali.meibo888.top/Article/details/gtwafsxxlu.html

[T13] Kotlin：只读 Map
来源：http://dali.zhoulong.xyz/Article/details/gtjpoxwouu.html

val m = mapOf("a" to 1)
来源：http://dali.zhixingplan.top/Article/details/gtyamdcxdk.html

[T14] Kotlin：循环
来源：http://dali.yvedp.cn/Article/details/gtrzlpowcd.html

for (i in 1..10) println(i)
来源：http://dali.aizwys.cn/Article/details/gtjegtpmwy.html

[T15] Kotlin：接口
来源：http://dali.zhaomingkeji.xyz/Article/details/gtckflcpbs.html

interface Shape { fun area(): Double }
来源：http://dali.zhengqikj.top/Article/details/gtohrtfres.html

[T16] Swift：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gtlzydgtuj.html

print("Hello")
来源：http://dali.zhongyouzk.top/Article/details/gtzxawljzf.html

[T17] Swift：变量与常量
来源：http://dali.dianchejie.cn/Article/details/gtpjdyoyce.html

var a = 1;  let b = 2
来源：http://dali.zhengqikj.top/Article/details/gtrrmllbdm.html

[T18] Swift：字符串插值
来源：http://dali.jinghuilouyu.cn/Article/details/gtyvepqjfc.html

"值: \(b)"
来源：http://dali.ybcxt.top/Article/details/gtppgaroga.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gtwpxonlsb.html

if let n = opt { print(n) }
来源：http://dali.xuetiantiany.cn/Article/details/gtdgomixtb.html

[T20] Swift：数组操作
来源：http://dali.c1oappe.top/Article/details/gtiqnnrbkz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdbixsvfc.html

[T21] Swift：遍历
来源：http://dali.havefunace.top/Article/details/gtakonxgey.html

for x in a { print(x) }
来源：http://dali.daxiang520.top/Article/details/gteqtqlsni.html

[T22] Swift：字典
来源：http://dali.jlsjyb.cn/Article/details/gtotmupzth.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.aibaodan.cn/Article/details/gtjhkcgywv.html

[T23] Swift：函数
来源：http://dali.yj202588.top/Article/details/gtoqqmobbr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.guannengcc.top/Article/details/gtlkovhbxi.html

[T24] Swift：闭包
来源：http://dali.sxryk.cn/Article/details/gtclyhnrjz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.birdmap.top/Article/details/gtzoxzqlxg.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gtonpvkpuc.html

struct P { var x: Int }
来源：http://dali.xuetiantiany.cn/Article/details/gtclmqyint.html

[T26] Swift：类与重写
来源：http://dali.xuetiantiany.cn/Article/details/gtlrshmikh.html

class A: Base { override func f() {} }
来源：http://dali.tanke756.top/Article/details/gtypthtnuw.html

[T27] Swift：错误处理
来源：http://dali.yanxiufei.cn/Article/details/gtonydjneq.html

do { try f() } catch { print(error) }
来源：http://dali.aizwys.cn/Article/details/gtcjfqimmj.html

[T28] Swift：枚举
来源：http://dali.jqgfzy.top/Article/details/gtxjwoobkz.html

enum Color { case red, green }
来源：http://dali.jinqigufen.top/Article/details/gtxkauikom.html

[T29] Swift：guard 提前返回
来源：http://dali.snrcjt.cn/Article/details/gtkshoqfnh.html

guard let x = opt else { return }
来源：http://dali.wangdashe.top/Article/details/gtkkuplxod.html

[T30] Swift：协议
来源：http://dali.c1oappe.top/Article/details/gtphyegyjn.html

protocol Shape { func area() -> Double }
来源：http://dali.yangfankeji.com/Article/details/gtdtebzobf.html

[T31] Lua：Hello World
来源：http://dali.tian-w.cn/Article/details/gtnptkovsb.html

print("Hello")
来源：http://dali.quarkkingdee.top/Article/details/gttsuatdza.html

[T32] Lua：局部变量
来源：http://dali.c1oappe.top/Article/details/gtxrdyabyi.html

local a = 1
来源：http://dali.tianlin.xyz/Article/details/gtyivbqeik.html

[T33] Lua：表（数组）
来源：http://dali.xuetiantiany.cn/Article/details/gtqpfnifyr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shangyingyoupin.top/Article/details/gtbrjlfgib.html

[T34] Lua：遍历表
来源：http://dali.pycfn.com/Article/details/gtoqobchgj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zycfv.cn/Article/details/gtvtoqkemc.html

[T35] Lua：字典表
来源：http://dali.hfpthk.cn/Article/details/gtcdootshv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sxryk.cn/Article/details/gtpxbtkkvm.html

[T36] Lua：函数
来源：http://dali.guannengcc.top/Article/details/gtbowiqrmq.html

function add(a, b) return a + b end
来源：http://dali.aibaodan.cn/Article/details/gtwsfnagdx.html

[T37] Lua：字符串拼接
来源：http://dali.9152youxi.cn/Article/details/gtacfyjcpl.html

"a" .. "b"
来源：http://dali.cucudq.cn/Article/details/gtbmvcggto.html

[T38] Lua：条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdyeivjds.html

if x > 0 then print("正") end
来源：http://dali.zhiwuduotai.top/Article/details/gtbgvedxnz.html

[T39] Lua：模式匹配
来源：http://dali.sysykeji.top/Article/details/gtajtryria.html

string.find(s, "%d+")
来源：http://dali.cashguo.top/Article/details/gtrosvqiwa.html

[T40] Lua：元表
来源：http://dali.sufxvd.cn/Article/details/gtbmdexpbq.html

setmetatable({}, { __index = base })
来源：http://dali.zhoulong.xyz/Article/details/gtflvfbnyu.html


<!-- 参考信息 -->