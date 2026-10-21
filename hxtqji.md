代发 wailian999

cmd >/dev/null 2>&1
来源：http://dali.snrcjt.cn/Article/details/gtnbbghlvj.html

[R42] 输入重定向
来源：http://dali.xuetiantiany.cn/Article/details/gtrfiitwlj.html

wc -l < a.txt
来源：http://dali.aizwys.cn/Article/details/gtujagxbrz.html

[R43] 按名字查找文件
来源：http://dali.cashguo.top/Article/details/gtywuhwthd.html

find . -name "*.log" -type f
来源：http://dali.iojbl.cn/Article/details/gtmfymisvt.html

[R44] 按修改时间查找
来源：http://dali.sufxvd.cn/Article/details/gtqjymfaqv.html

find . -mtime -7 -type f
来源：http://dali.xinyue.icu/Article/details/gtmjyiynva.html

[R45] 批量删除
来源：http://dali.cqqwz.cn/Article/details/gtggcktqko.html

find . -name "*.tmp" -delete
来源：http://dali.hongshengwenyu.top/Article/details/gthghurbai.html

[R46] 递归替换文件内容
来源：http://dali.hnqzz.top/Article/details/gtmvxkcmft.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.meibo888.top/Article/details/gtaxzbkgzi.html

[R47] sed 单行替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmksrbvkz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.havefunace.top/Article/details/gtxovpajqp.html

[R48] awk 取指定列
来源：http://dali.zhongyouzk.top/Article/details/gtndrswkld.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhengqikj.top/Article/details/gtbprssvas.html

[R49] awk 带条件
来源：http://dali.tian-w.cn/Article/details/gteeqywyqz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.havefunace.top/Article/details/gtkzalckvh.html

[R50] awk 求和
来源：http://dali.yj202588.top/Article/details/gtqhgpvdua.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hysaishi.cn/Article/details/gtmojkalsr.html

[R51] 排序去重取前几
来源：http://dali.kuanghao11.cn/Article/details/gtdiplerto.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.chenjidiqi.icu/Article/details/gthprjurml.html

[R52] 统计行数
来源：http://dali.sysykeji.top/Article/details/gtoskwttfr.html

wc -l a.txt
来源：http://dali.meibo888.top/Article/details/gtnypfmztp.html

[R53] 查看文件头与实时尾
来源：http://dali.jinqigfzy.top/Article/details/gtwamecvcp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zdqjudy.top/Article/details/gtfwxiqdgh.html

[R54] 比较两个文件
来源：http://dali.birdmap.top/Article/details/gtrecprweb.html

diff a.txt b.txt
来源：http://dali.shzxlz.cn/Article/details/gtquonchaq.html

[R55] 压缩与解压
来源：http://dali.yvedp.cn/Article/details/gtcniymkmv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cashguo.top/Article/details/gteimevwvj.html

[R56] 远程拷贝
来源：http://dali.snrcjt.cn/Article/details/gtbdorcjah.html

scp file user@host:/path/
来源：http://dali.jianghu66.top/Article/details/gtkrtkyxom.html

[R57] 远程执行命令
来源：http://dali.ywan-chungtsiang.top/Article/details/gthletogxc.html

ssh user@host 'uptime'
来源：http://dali.jlsjyb.cn/Article/details/gtdcemmiib.html

[R58] 下载文件
来源：http://dali.dashuyun.cn/Article/details/gtwenlmjed.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.chenlongwang.top/Article/details/gtipjqiwmi.html

[R59] 发 POST JSON
来源：http://dali.0kj1m.cn/Article/details/gtvklwzhnc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shzxlz.cn/Article/details/gtsxesfmht.html

[R60] 只看 HTTP 状态码
来源：http://dali.quarkkingdee.top/Article/details/gtzhldevcc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cucudq.cn/Article/details/gttflbnqgy.html

[R61] 磁盘占用
来源：http://dali.guowangkeji.top/Article/details/gtqcgfvpfj.html

df -h;  du -sh *
来源：http://dali.zycfv.cn/Article/details/gtbblbsfnz.html

[R62] 找最占空间的文件
来源：http://dali.daxiang520.top/Article/details/gtfbpbmtuh.html

du -ah . | sort -rh | head -10
来源：http://dali.wangshuangyany.cn/Article/details/gtiqyqxuoi.html

[R63] 内存与进程
来源：http://dali.tian-w.cn/Article/details/gtysxaihcu.html

free -h;  ps aux | grep nginx
来源：http://dali.yangfankeji.com/Article/details/gtanipdirg.html

[R64] 结束进程
来源：http://dali.meibo888.top/Article/details/gttwnitdgq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hongshengwenyu.top/Article/details/gtcvkoctea.html

[R65] 查看端口占用
来源：http://dali.hongshengwenyu.top/Article/details/gteymojzjm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hywenlv.cn/Article/details/gtfeohkpxp.html

[R66] 定时任务
来源：http://dali.cqqwz.cn/Article/details/gtkjbblogd.html

crontab -e;  crontab -l
来源：http://dali.c1oappe.top/Article/details/gtcpapwoqz.html

[R67] 生成随机十六进制串
来源：http://dali.dashuyun.cn/Article/details/gtffkongls.html

openssl rand -hex 16
来源：http://dali.hfpthk.cn/Article/details/gtknfufjma.html

[R68] 计算文件校验值
来源：http://dali.gogol.net.cn/Article/details/gtedppiaks.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.dianchejie.cn/Article/details/gtkyzemxnf.html

[R69] 生成随机密码
来源：http://dali.jlsjyb.cn/Article/details/gtwevstxoa.html

head -c 16 /dev/urandom | base64
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmutjzbsm.html

[R70] 时间戳与互转
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgdlpgjbs.html

date +%s;  date -d @1700000000
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthzjghtcr.html

[R71] 日期格式化
来源：http://dali.gzhubu.top/Article/details/gtgyntbgzz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yvedp.cn/Article/details/gtflwfrfkn.html

[R72] 等待端口就绪
来源：http://dali.yj202588.top/Article/details/gtjjsmtafo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hnqzz.top/Article/details/gtkldvjync.html

[R73] 分割大日志
来源：http://dali.ywan-chungtsiang.top/Article/details/gtakmyjmfh.html

split -l 1000 big.log part_
来源：http://dali.jiagoushi.top/Article/details/gteiolcceh.html

[R74] 批量重命名
来源：http://dali.nanxinkj.top/Article/details/gtrdnrwacb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaotipryo.html

[R75] 导出环境变量
来源：http://dali.chenlongwang.top/Article/details/gtuwjsfgcr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hfpthk.cn/Article/details/gteljdduvd.html

[R76] 使用临时文件
来源：http://dali.andypj.xyz/Article/details/gtzwboisie.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.birdmap.top/Article/details/gtjhrezcmj.html

[R77] 读取用户输入
来源：http://dali.yvedp.cn/Article/details/gtugryywnc.html

read -rp "请输入: " ans
来源：http://dali.cheryme.top/Article/details/gtwnmrufay.html

[R78] 交互式菜单
来源：http://dali.sxryk.cn/Article/details/gtaphnvfil.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shuidangran.top/Article/details/gtzcszxlop.html

[R79] 解析命令行选项
来源：http://dali.xylfe.cn/Article/details/gtmkscqgwh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xuetiantiany.cn/Article/details/gtdmqwxsgc.html

[R80] 查看脚本执行耗时
来源：http://dali.cashguo.top/Article/details/gtcmevzwbn.html

time ./run.sh
来源：http://dali.xylfe.cn/Article/details/gticmzfygq.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtfqsfqdfl.html

S. C / C++ 专题
来源：http://dali.xinyue.icu/Article/details/gtijpvkrsv.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxsiartww.html

[S01] C：Hello World
来源：http://dali.fengsongda.top/Article/details/gtbrrapwyf.html

#include <stdio.h>
来源：http://dali.nanxuanxn.top/Article/details/gtnxfmowsl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shuidangran.top/Article/details/gtlvhtwtkt.html

[S02] C：变量与格式化输出
来源：http://dali.wangshuangyany.cn/Article/details/gtqsukqjdv.html

int a = 10; printf("%d\n", a);
来源：http://dali.meibo888.top/Article/details/gtcpytuyvo.html

[S03] C：读入整数
来源：http://dali.tianlin.xyz/Article/details/gtxjhcfhkn.html

int x; scanf("%d", &x);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlredsmaw.html

[S04] C：字符串复制
来源：http://dali.xylfe.cn/Article/details/gtdftvefdl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhongyouzk.top/Article/details/gtzmvlyzfm.html

[S05] C：字符串长度
来源：http://dali.feifeiyinyue.top/Article/details/gtpjthdmwu.html

strlen(s)
来源：http://dali.iojbl.cn/Article/details/gtyynmumsn.html

[S06] C：字符串比较
来源：http://dali.hnxiangtu.top/Article/details/gtvkujffuk.html

strcmp(a, b) == 0
来源：http://dali.yuanzhike.top/Article/details/gtcodnpdso.html

[S07] C：数组遍历求和
来源：http://dali.gaohongyu789.top/Article/details/gtjylbbyrk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.dashuyun.cn/Article/details/gtzgichifx.html

[S08] C：动态内存分配与释放
来源：http://dali.cheryme.top/Article/details/gtovkyjohw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsxvvhsod.html

[S09] C：结构体定义与初始化
来源：http://dali.feifeiyinyue.top/Article/details/gtwcobaajk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xuanzx.com/Article/details/gtorhmlpwu.html

[S10] C：指针与解引用
来源：http://dali.yonumen.top/Article/details/gtnaomquji.html

int *p = &a;  *p = 5;
来源：http://dali.sysykeji.top/Article/details/gtsuxscosa.html

[S11] C：逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gtjuuqklha.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.tianlin.xyz/Article/details/gtfqlricje.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.dashuyun.cn/Article/details/gtdleaocgi.html

fclose(f);
来源：http://dali.gotoacloud.top/Article/details/gtmcxzbwwz.html

[S12] C：写文件
来源：http://dali.haohaochexian.top/Article/details/gtdgoweknb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cashguo.top/Article/details/gtfjsdsnhx.html

[S13] C：宏定义
来源：http://dali.pycfn.com/Article/details/gtxbisaomy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhiwuduotai.top/Article/details/gtebpqyuzv.html

[S14] C：枚举
来源：http://dali.yanxiufei.cn/Article/details/gtgamamhty.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xziqi.cn/Article/details/gtgqcoxpdt.html

[S15] C：类型转换
来源：http://dali.yangfankeji.com/Article/details/gtywgoswdl.html

(double) a / b
来源：http://dali.smart0.xyz/Article/details/gtsmochuhp.html

[S16] C：位操作置位
来源：http://dali.cdnleiting.top/Article/details/gtfcbmrmzt.html

x |= (1 << 3);
来源：http://dali.yanxiufei.cn/Article/details/gtjfjzsijc.html

[S17] C：安全拼接字符串
来源：http://dali.gzhubu.top/Article/details/gtylbbkytj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yj20258888.top/Article/details/gtuaeiwzev.html

[S18] C：命令行参数
来源：http://dali.jlsjyb.cn/Article/details/gtguutcqjo.html

int main(int argc, char **argv)
来源：http://dali.tanke756.top/Article/details/gtjffsksgh.html

[S19] C：快速排序
来源：http://dali.quarkkingdee.top/Article/details/gtujamattb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.gotoacloud.top/Article/details/gtqdacwdtc.html

[S20] C：二分查找
来源：http://dali.nwbrower.top/Article/details/gtbtecszvf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhoulong.xyz/Article/details/gtldmvwpxd.html

[S21] C：字符类别判断
来源：http://dali.c1oappe.top/Article/details/gtzqelylht.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gaohongyu789.top/Article/details/gtjdkgkpja.html

[S22] C：字符串转数字
来源：http://dali.jqgfzy.top/Article/details/gtgdueymeh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.nwbrower.top/Article/details/gtihfbbvpg.html

[S23] C：随机数
来源：http://dali.zhiwuduotai.top/Article/details/gthwvcyquw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.nwbrower.top/Article/details/gtzshfwfcf.html

[S24] C：获取本地时间
来源：http://dali.yongpay.top/Article/details/gtorghmjpo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.iojbl.cn/Article/details/gtedwqphyl.html

[S25] C：内存拷贝
来源：http://dali.xuanzx.com/Article/details/gtfbbhoqqa.html

memcpy(dst, src, n);
来源：http://dali.daria6918.cn/Article/details/gtqhfxjbyw.html

[S26] C：内存清零
来源：http://dali.aizwys.cn/Article/details/gtnwbwdrfw.html

memset(a, 0, sizeof a);
来源：http://dali.yuanzhike.top/Article/details/gtjrfptmrk.html

[S27] C：定义常量
来源：http://dali.nwbrower.top/Article/details/gtodolymsu.html

const double PI = 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gtmqgvrdot.html

[S28] C：静态变量
来源：http://dali.haohaochexian.top/Article/details/gtdxywszby.html

static int counter = 0;
来源：http://dali.zhixingplan.top/Article/details/gtrxmvbfut.html

[S29] C：变参函数
来源：http://dali.fzhhl.top/Article/details/gtructgycg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shanyushiyangtech.top/Article/details/gtyhnpqzxl.html

[S30] C：头文件保护
来源：http://dali.zhiwuduotai.top/Article/details/gtgypdpsmb.html

#ifndef X_H
来源：http://dali.jinghuilouyu.cn/Article/details/gtrgjilycp.html

#define X_H
来源：http://dali.yuanzhike.top/Article/details/gtvtqdwkuw.html

#endif
来源：http://dali.shangyingyoupin.top/Article/details/gthojjyhmf.html

[S31] C++：Hello World
来源：http://dali.zycfv.cn/Article/details/gtoykhoftz.html

#include <iostream>
来源：http://dali.gogol.net.cn/Article/details/gtydkidmir.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jinqigfzy.top/Article/details/gtxfhfqxsq.html

[S32] C++：字符串
来源：http://dali.hammf.cn/Article/details/gtcyoxvkfx.html

std::string s = "hi";  s += "!";
来源：http://dali.iojbl.cn/Article/details/gtjxaubfln.html

[S33] C++：vector 增删
来源：http://dali.yvedp.cn/Article/details/gtcdypujms.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ppjwa.cn/Article/details/gtjfyuaslx.html

[S34] C++：遍历 vector
来源：http://dali.tianlin.xyz/Article/details/gtduyfngsk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.tianlin.xyz/Article/details/gtmvoiahms.html

[S35] C++：map
来源：http://dali.yvedp.cn/Article/details/gtewwumner.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cqqwz.cn/Article/details/gtwbhpkhec.html

[S36] C++：unordered_map
来源：http://dali.haohaochexian.top/Article/details/gtscdzkapy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xylfe.cn/Article/details/gtuoaxulhq.html

[S37] C++：set
来源：http://dali.feifeiyinyue.top/Article/details/gtyghiblsy.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xuanzx.com/Article/details/gtuiequlqp.html

[S38] C++：排序
来源：http://dali.shzxlz.cn/Article/details/gttsedjjxv.html

std::sort(v.begin(), v.end());
来源：http://dali.tanke756.top/Article/details/gtomvosufg.html

[S39] C++：自定义比较器排序
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlrkgmbdy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ivvv.top/Article/details/gtbbttlycx.html

[S40] C++：查找元素
来源：http://dali.quarkkingdee.top/Article/details/gtixlhvtqw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.sxryk.cn/Article/details/gtdsisjhmd.html

[S41] C++：类与构造函数
来源：http://dali.wangdashe.top/Article/details/gtkjjvohfq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hnxiangtu.top/Article/details/gtnmmreeks.html

[S42] C++：继承与虚函数
来源：http://dali.sxryk.cn/Article/details/gtgrehybta.html

class B : public Base { public: void f() override {} };
来源：http://dali.316326.xyz/Article/details/gtunnehhxw.html

[S43] C++：智能指针
来源：http://dali.chenzaomai.com/Article/details/gtupubkjql.html

auto p = std::make_unique<int>(5);
来源：http://dali.mhx1999.top/Article/details/gttbiyvbld.html

[S44] C++：引用传参
来源：http://dali.zhaomingkeji.xyz/Article/details/gtarfddmxu.html

void inc(int &x) { ++x; }
来源：http://dali.0kj1m.cn/Article/details/gtijbwogpg.html

[S45] C++：lambda
来源：http://dali.jinghuilouyu.cn/Article/details/gtkderzxqs.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jqgfzy.top/Article/details/gtaxzdgqrz.html

[S46] C++：函数模板
来源：http://dali.wangdashe.top/Article/details/gtwhxpubht.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sxryk.cn/Article/details/gtcfkwtwzs.html

[S47] C++：结构化绑定遍历
来源：http://dali.zdqjudy.top/Article/details/gtxhjjrxep.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.snrcjt.cn/Article/details/gtnlfzacah.html

[S48] C++：逐行读文件
来源：http://dali.c1oappe.top/Article/details/gtjlrzgwte.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.0kj1m.cn/Article/details/gtuxrqyorv.html

while (std::getline(in, line)) { }
来源：http://dali.feifeiyinyue.top/Article/details/gtuvvvelzv.html

[S49] C++：写文件
来源：http://dali.ehwqpu.com/Article/details/gtsquzdkag.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.meibo888.top/Article/details/gtokbcpmwf.html

[S50] C++：格式化数字
来源：http://dali.zhongyouzk.top/Article/details/gtstcutsyc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.meibo888.top/Article/details/gtlyrfrkjj.html

[S51] C++：显式类型转换
来源：http://dali.aizwys.cn/Article/details/gtbimnhfew.html

static_cast<double>(a) / b
来源：http://dali.chenjidiqi.icu/Article/details/gtyhhmfsug.html

[S52] C++：const 与 noexcept
来源：http://dali.xylfe.cn/Article/details/gtbyghgwax.html

int size() const noexcept { return n_; }
来源：http://dali.yangfankeji.com/Article/details/gtccdxhzco.html

[S53] C++：移动语义
来源：http://dali.0kj1m.cn/Article/details/gtsjhgnzye.html

std::vector<int> w = std::move(v);
来源：http://dali.ivvv.top/Article/details/gtuuemkkjw.html

[S54] C++：异常处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvmtrqgwv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yuxming.cn/Article/details/gttpcymlag.html

[S55] C++：结构化绑定
来源：http://dali.jlsjyb.cn/Article/details/gtphceolse.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ivvv.top/Article/details/gtldiszwsk.html

[S56] C++：optional
来源：http://dali.daria6918.cn/Article/details/gtntuqwstn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhoulong.xyz/Article/details/gtdttsyqgl.html

[S57] C++：编译期常量
来源：http://dali.jinqigfzy.top/Article/details/gtafttbrxg.html

constexpr int N = 10;
来源：http://dali.yuanzhike.top/Article/details/gtvmxrxdvw.html

[S58] C++：命名空间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcpxlwmdy.html

namespace ns { int f() { return 1; } }
来源：http://dali.yj20258888.top/Article/details/gtayxzqqgh.html

[S59] C++：静态断言
来源：http://dali.smart0.xyz/Article/details/gtdloptmnw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.daria6918.cn/Article/details/gtqfdlooft.html

[S60] C++：遍历并删除元素
来源：http://dali.daxiang520.top/Article/details/gtzsjofsrn.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zdqjudy.top/Article/details/gtxhttkirm.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtexcspshh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tianlin.xyz/Article/details/gtgezsaehy.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtjpfjxbss.html

[T01] Kotlin：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtmmccqqep.html

println("Hello")
来源：http://dali.yvedp.cn/Article/details/gttnuwfrza.html

[T02] Kotlin：变量
来源：http://dali.snrcjt.cn/Article/details/gtuydmocch.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jinyuanbaomall.cn/Article/details/gttffpaxzc.html

[T03] Kotlin：字符串模板
来源：http://dali.cdnleiting.top/Article/details/gtorwjzfmk.html

"值: $b"
来源：http://dali.gogol.net.cn/Article/details/gtxnfktffp.html

[T04] Kotlin：空安全
来源：http://dali.hammf.cn/Article/details/gtvydwpwhv.html

val n: String? = null;  n?.length
来源：http://dali.dianchejie.cn/Article/details/gtysyfnvvz.html

[T05] Kotlin：when 表达式
来源：http://dali.sweek.top/Article/details/gtumglvudw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shzxlz.cn/Article/details/gtnbdxcnwu.html

[T06] Kotlin：集合映射
来源：http://dali.gogol.net.cn/Article/details/gthkqyrplr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.mhx1999.top/Article/details/gtfqpwzbup.html

[T07] Kotlin：集合过滤
来源：http://dali.yuanzhike.top/Article/details/gtqwvavale.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.guannengcc.top/Article/details/gtisxbhhur.html

[T08] Kotlin：数据类
来源：http://dali.jyoumei.cn/Article/details/gtjtosvssj.html

data class User(val name: String, val age: Int)
来源：http://dali.daxiang520.top/Article/details/gtnxflccix.html

[T09] Kotlin：扩展函数
来源：http://dali.sufxvd.cn/Article/details/gtlniphise.html

fun String.exclaim() = this + "!"
来源：http://dali.hnqzz.top/Article/details/gtnfnefdjq.html

[T10] Kotlin：默认参数
来源：http://dali.shuidangran.top/Article/details/gtjmhicbkr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.chenjidiqi.icu/Article/details/gtiagldpjq.html

[T11] Kotlin：协程
来源：http://dali.dianchejie.cn/Article/details/gtzkkoaacj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yuanzhike.top/Article/details/gtjmugntzq.html

[T12] Kotlin：解构声明
来源：http://dali.cheryme.top/Article/details/gtpbmwqpex.html

val (a, b) = Pair(1, 2)
来源：http://dali.wangdashe.top/Article/details/gtrcvrkdqp.html

[T13] Kotlin：只读 Map
来源：http://dali.hfpthk.cn/Article/details/gtrizmvmcw.html

val m = mapOf("a" to 1)
来源：http://dali.daria6918.cn/Article/details/gtjaapxzug.html

[T14] Kotlin：循环
来源：http://dali.guowangkeji.top/Article/details/gtohbozoyy.html

for (i in 1..10) println(i)
来源：http://dali.zdqjudy.top/Article/details/gtbygnqupm.html

[T15] Kotlin：接口
来源：http://dali.jinqigufen.top/Article/details/gtnhcpcrkq.html

interface Shape { fun area(): Double }
来源：http://dali.gaohongyu789.top/Article/details/gtyvrxezyd.html

[T16] Swift：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gthxbhqqaa.html

print("Hello")
来源：http://dali.9152youxi.cn/Article/details/gthekpwdmc.html

[T17] Swift：变量与常量
来源：http://dali.ydzc1.top/Article/details/gthyzoeqtv.html

var a = 1;  let b = 2
来源：http://dali.cdnleiting.top/Article/details/gtquuprvdq.html

[T18] Swift：字符串插值
来源：http://dali.yonumen.top/Article/details/gtdodkfojx.html

"值: \(b)"
来源：http://dali.ybcxt.top/Article/details/gtwvhivqzu.html

[T19] Swift：可选绑定
来源：http://dali.jiagoushi.top/Article/details/gtirnreavu.html

if let n = opt { print(n) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtosbrhtkl.html

[T20] Swift：数组操作
来源：http://dali.hammf.cn/Article/details/gtexshyhqv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.snrcjt.cn/Article/details/gtascretcx.html

[T21] Swift：遍历
来源：http://dali.svipenyu.cn/Article/details/gtuhnkljak.html

for x in a { print(x) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtilafkqqa.html

[T22] Swift：字典
来源：http://dali.aizwys.cn/Article/details/gtewckaudj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.sweek.top/Article/details/gtfxjjihmy.html

[T23] Swift：函数
来源：http://dali.xuetiantiany.cn/Article/details/gtbdssgdxf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.guannengcc.top/Article/details/gtgeikfcmf.html

[T24] Swift：闭包
来源：http://dali.shzxlz.cn/Article/details/gthmgqjwlu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yj202588.top/Article/details/gtpftscgrg.html

[T25] Swift：结构体
来源：http://dali.aibaodan.cn/Article/details/gtsoyrsobs.html

struct P { var x: Int }
来源：http://dali.9152youxi.cn/Article/details/gtediahuzh.html

[T26] Swift：类与重写
来源：http://dali.wangshuangyany.cn/Article/details/gtywkrdgnl.html

class A: Base { override func f() {} }
来源：http://dali.chenlongwang.top/Article/details/gtpnfjwdyk.html

[T27] Swift：错误处理
来源：http://dali.jyoumei.cn/Article/details/gtprhexvvt.html

do { try f() } catch { print(error) }
来源：http://dali.zhoulong.xyz/Article/details/gtdukzxuyv.html

[T28] Swift：枚举
来源：http://dali.yj20258888.top/Article/details/gtxlkklchu.html

enum Color { case red, green }
来源：http://dali.zhixingplan.top/Article/details/gtnalckceo.html

[T29] Swift：guard 提前返回
来源：http://dali.ydzc1.top/Article/details/gtlrbsdocf.html

guard let x = opt else { return }
来源：http://dali.cucudq.cn/Article/details/gtjnxhuaww.html

[T30] Swift：协议
来源：http://dali.yuanzhike.top/Article/details/gtfhcniqnt.html

protocol Shape { func area() -> Double }
来源：http://dali.jyoumei.cn/Article/details/gtazxoeyay.html

[T31] Lua：Hello World
来源：http://dali.cdnleiting.top/Article/details/gtbtkihxbm.html

print("Hello")
来源：http://dali.fzhhl.top/Article/details/gtpxvwbibq.html

[T32] Lua：局部变量
来源：http://dali.yj20258.top/Article/details/gtbjbktllk.html

local a = 1
来源：http://dali.cdnleiting.top/Article/details/gthhrqfkxd.html

[T33] Lua：表（数组）
来源：http://dali.dashuyun.cn/Article/details/gtyypzijvp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinqigufen.top/Article/details/gtusnzuuaf.html

[T34] Lua：遍历表
来源：http://dali.yj202588.top/Article/details/gtspvykaum.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.mhx1999.top/Article/details/gtbfjrzhcb.html

[T35] Lua：字典表
来源：http://dali.hongshengwenyu.top/Article/details/gtmsxejrtn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.nanxinkj.top/Article/details/gtdxfsgzde.html

[T36] Lua：函数
来源：http://dali.gogol.net.cn/Article/details/gtgjddpgfq.html

function add(a, b) return a + b end
来源：http://dali.jlsjyb.cn/Article/details/gtujiipbct.html

[T37] Lua：字符串拼接
来源：http://dali.xylfe.cn/Article/details/gtdnwcbfms.html

"a" .. "b"
来源：http://dali.wangdashe.top/Article/details/gtbpzfyuvx.html

[T38] Lua：条件
来源：http://dali.hongshengwenyu.top/Article/details/gtlrasjnbk.html

if x > 0 then print("正") end
来源：http://dali.havefunace.top/Article/details/gthwovhbmx.html

[T39] Lua：模式匹配
来源：http://dali.316326.xyz/Article/details/gtlbsasmxv.html

string.find(s, "%d+")
来源：http://dali.kuanghao11.cn/Article/details/gtjlgpwztx.html

[T40] Lua：元表
来源：http://dali.guowangkeji.top/Article/details/gtsahufbzs.html

setmetatable({}, { __index = base })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtplkiqbce.html

[T41] Perl：Hello World
来源：http://dali.aizwys.cn/Article/details/gtkkucheaq.html

print "Hello\n";
来源：http://dali.wangshuangyany.cn/Article/details/gtleyzweya.html

[T42] Perl：变量类型
来源：http://dali.shzxlz.cn/Article/details/gtjttyzlzl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hnqzz.top/Article/details/gtizudoygz.html

[T43] Perl：字符串插值
来源：http://dali.mhx1999.top/Article/details/gtwgpvxqkb.html

"值: $a"
来源：http://dali.yj20258.top/Article/details/gtiqosmsqv.html

[T44] Perl：条件
来源：http://dali.zhoulong.xyz/Article/details/gtuupmzfji.html

if ($a > 0) { print "正"; }
来源：http://dali.dianchejie.cn/Article/details/gtwprbwadx.html


<!-- 参考信息 -->