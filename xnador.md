代发 wailian999

find . -name "*.tmp" -delete
来源：http://dali.ehwqpu.com/Article/details/gtqoodyyji.html

[R46] 递归替换文件内容
来源：http://dali.nanxinkj.top/Article/details/gtcwtavujj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.havefunace.top/Article/details/gtepwulsct.html

[R47] sed 单行替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmkhqatyb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xinyue.icu/Article/details/gtzxnzkeni.html

[R48] awk 取指定列
来源：http://dali.yangfankeji.com/Article/details/gtezortsfq.html

awk '{print $1, $3}' a.txt
来源：http://dali.ehwqpu.com/Article/details/gtatfjewjg.html

[R49] awk 带条件
来源：http://dali.xziqi.cn/Article/details/gtgubxjnyt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shzxlz.cn/Article/details/gtijtecfpu.html

[R50] awk 求和
来源：http://dali.jinqigfzy.top/Article/details/gtljhlsgmx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zycfv.cn/Article/details/gtreegdlkt.html

[R51] 排序去重取前几
来源：http://dali.ehwqpu.com/Article/details/gtwpuxlufz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cheryme.top/Article/details/gtaicsrfce.html

[R52] 统计行数
来源：http://dali.wangshuangyany.cn/Article/details/gtjrlvmdzy.html

wc -l a.txt
来源：http://dali.yongpay.top/Article/details/gtwytihicq.html

[R53] 查看文件头与实时尾
来源：http://dali.zhongyouzk.top/Article/details/gtetkeaeul.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xuetiantiany.cn/Article/details/gtjruknvhi.html

[R54] 比较两个文件
来源：http://dali.xinyue.icu/Article/details/gtrdzdxghh.html

diff a.txt b.txt
来源：http://dali.cucudq.cn/Article/details/gtntlldlyg.html

[R55] 压缩与解压
来源：http://dali.zhoulong.xyz/Article/details/gtbtsuabni.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.sysykeji.top/Article/details/gtdqgfahpm.html

[R56] 远程拷贝
来源：http://dali.ppjwa.cn/Article/details/gtvpxyzabl.html

scp file user@host:/path/
来源：http://dali.sxryk.cn/Article/details/gtzpishqhv.html

[R57] 远程执行命令
来源：http://dali.vqdsnc.cn/Article/details/gtdidbggxd.html

ssh user@host 'uptime'
来源：http://dali.316326.xyz/Article/details/gtouxhcsey.html

[R58] 下载文件
来源：http://dali.chenlongwang.top/Article/details/gtqonypbmb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yanxiufei.cn/Article/details/gtixtjprrf.html

[R59] 发 POST JSON
来源：http://dali.chenjidiqi.icu/Article/details/gtmgoqytmj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shzxlz.cn/Article/details/gtqbcqbhpb.html

[R60] 只看 HTTP 状态码
来源：http://dali.kuanghao11.cn/Article/details/gttoqsnksd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhoulong.xyz/Article/details/gtmldqutrn.html

[R61] 磁盘占用
来源：http://dali.c1oappe.top/Article/details/gtcngvdehv.html

df -h;  du -sh *
来源：http://dali.nanxuanxn.top/Article/details/gtzptkdxtt.html

[R62] 找最占空间的文件
来源：http://dali.yj202588.top/Article/details/gtkmkrsaoi.html

du -ah . | sort -rh | head -10
来源：http://dali.yanxiufei.cn/Article/details/gtbzmvvhpe.html

[R63] 内存与进程
来源：http://dali.vqdsnc.cn/Article/details/gtkmuwduxp.html

free -h;  ps aux | grep nginx
来源：http://dali.xziqi.cn/Article/details/gtfgysfxlo.html

[R64] 结束进程
来源：http://dali.ivvv.top/Article/details/gttoepdunq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yueranfly.top/Article/details/gtjujrummq.html

[R65] 查看端口占用
来源：http://dali.svipenyu.cn/Article/details/gtqegcqebj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.andypj.xyz/Article/details/gtwcowvsmk.html

[R66] 定时任务
来源：http://dali.gotoacloud.top/Article/details/gtfpfyaowh.html

crontab -e;  crontab -l
来源：http://dali.yueranfly.top/Article/details/gtdbvbnoil.html

[R67] 生成随机十六进制串
来源：http://dali.havefunace.top/Article/details/gtvzicutsj.html

openssl rand -hex 16
来源：http://dali.dianchejie.cn/Article/details/gtnkuyuxzk.html

[R68] 计算文件校验值
来源：http://dali.tianlin.xyz/Article/details/gtsazfpcya.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cdnleiting.top/Article/details/gtfcgiumla.html

[R69] 生成随机密码
来源：http://dali.aizwys.cn/Article/details/gtjblaidhb.html

head -c 16 /dev/urandom | base64
来源：http://dali.hfpthk.cn/Article/details/gtvklefyie.html

[R70] 时间戳与互转
来源：http://dali.gotoacloud.top/Article/details/gtgblkyyjp.html

date +%s;  date -d @1700000000
来源：http://dali.tianlin.xyz/Article/details/gtdpkdruiy.html

[R71] 日期格式化
来源：http://dali.snrcjt.cn/Article/details/gtlykhpbnu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shanyushiyangtech.top/Article/details/gtwnzmbjme.html

[R72] 等待端口就绪
来源：http://dali.feifeiyinyue.top/Article/details/gtlhnvmnmj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.quarkkingdee.top/Article/details/gtljksrvqt.html

[R73] 分割大日志
来源：http://dali.wangdashe.top/Article/details/gtlziaihbc.html

split -l 1000 big.log part_
来源：http://dali.tian-w.cn/Article/details/gtwrardgmh.html

[R74] 批量重命名
来源：http://dali.smart0.xyz/Article/details/gtnjuyhumn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sxryk.cn/Article/details/gteoudebko.html

[R75] 导出环境变量
来源：http://dali.chenlongwang.top/Article/details/gtzoggzyxp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.aizwys.cn/Article/details/gtkkmqfbra.html

[R76] 使用临时文件
来源：http://dali.yj20258.top/Article/details/gtrbaiphnc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yangfankeji.com/Article/details/gtkrcosvim.html

[R77] 读取用户输入
来源：http://dali.gotoacloud.top/Article/details/gtcaazvzhp.html

read -rp "请输入: " ans
来源：http://dali.yj20258888.top/Article/details/gtcvtdezld.html

[R78] 交互式菜单
来源：http://dali.yuanzhike.top/Article/details/gtlpdolxmi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.daxiang520.top/Article/details/gtansvegxm.html

[R79] 解析命令行选项
来源：http://dali.ybcxt.top/Article/details/gtrynnmftf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.dashuyun.cn/Article/details/gtiunpwymq.html

[R80] 查看脚本执行耗时
来源：http://dali.yuanzhike.top/Article/details/gthlqlgbph.html

time ./run.sh
来源：http://dali.c1oappe.top/Article/details/gtxchostpo.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtfipyufiv.html

S. C / C++ 专题
来源：http://dali.jinghuilouyu.cn/Article/details/gtjhksmbgk.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtihwxglzf.html

[S01] C：Hello World
来源：http://dali.ybcxt.top/Article/details/gtfyebtlus.html

#include <stdio.h>
来源：http://dali.sxryk.cn/Article/details/gtnsqtuwtr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.dianchejie.cn/Article/details/gtaviokxyd.html

[S02] C：变量与格式化输出
来源：http://dali.zhoulong.xyz/Article/details/gtjpkmlgjl.html

int a = 10; printf("%d\n", a);
来源：http://dali.yj202588.top/Article/details/gtecwuweee.html

[S03] C：读入整数
来源：http://dali.jinghuilouyu.cn/Article/details/gtlpkmhsxg.html

int x; scanf("%d", &x);
来源：http://dali.cucudq.cn/Article/details/gtptfwcqvs.html

[S04] C：字符串复制
来源：http://dali.bjfxy.top/Article/details/gtwaznkvya.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhaomingkeji.xyz/Article/details/gteioyicmu.html

[S05] C：字符串长度
来源：http://dali.zycfv.cn/Article/details/gtrgkozznw.html

strlen(s)
来源：http://dali.nanxuanxn.top/Article/details/gtakdeiwrt.html

[S06] C：字符串比较
来源：http://dali.feifeiyinyue.top/Article/details/gtsftwamtl.html

strcmp(a, b) == 0
来源：http://dali.wangshuangyany.cn/Article/details/gtilgdslbo.html

[S07] C：数组遍历求和
来源：http://dali.nwbrower.top/Article/details/gtpmarjtnv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shangyingyoupin.top/Article/details/gtdvxxbsst.html

[S08] C：动态内存分配与释放
来源：http://dali.xylfe.cn/Article/details/gtlvyxmcou.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.havefunace.top/Article/details/gtbgifrpwj.html

[S09] C：结构体定义与初始化
来源：http://dali.cqqwz.cn/Article/details/gtjlkwaniw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.0kj1m.cn/Article/details/gtyreimrbt.html

[S10] C：指针与解引用
来源：http://dali.smart0.xyz/Article/details/gtzuraxivm.html

int *p = &a;  *p = 5;
来源：http://dali.zdqjudy.top/Article/details/gtcszvavmi.html

[S11] C：逐行读文件
来源：http://dali.shzxlz.cn/Article/details/gtzjlykxgi.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jiagoushi.top/Article/details/gtxdhwwhjv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhoulong.xyz/Article/details/gtfzutjaob.html

fclose(f);
来源：http://dali.nanxinkj.top/Article/details/gtshdlsbcc.html

[S12] C：写文件
来源：http://dali.vqdsnc.cn/Article/details/gtfvvundaa.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yanxiufei.cn/Article/details/gttstxgbac.html

[S13] C：宏定义
来源：http://dali.yj202588.top/Article/details/gttryfmtuy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jqgfzy.top/Article/details/gtvymnnsqo.html

[S14] C：枚举
来源：http://dali.daria6918.cn/Article/details/gtfduqswqp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.tianlin.xyz/Article/details/gtbhwqugwx.html

[S15] C：类型转换
来源：http://dali.jinqigufen.top/Article/details/gtearprwnr.html

(double) a / b
来源：http://dali.zdqjudy.top/Article/details/gtiqjjfnhr.html

[S16] C：位操作置位
来源：http://dali.zhixingplan.top/Article/details/gtqiehrhdk.html

x |= (1 << 3);
来源：http://dali.cqqwz.cn/Article/details/gtvpogbsqg.html

[S17] C：安全拼接字符串
来源：http://dali.nanxuanxn.top/Article/details/gtpbxyphsh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shanyushiyangtech.top/Article/details/gtaptkjvwo.html

[S18] C：命令行参数
来源：http://dali.sxryk.cn/Article/details/gtusfhljxc.html

int main(int argc, char **argv)
来源：http://dali.ydzc1.top/Article/details/gteodeolav.html

[S19] C：快速排序
来源：http://dali.jqgfzy.top/Article/details/gteagtlniz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.snrcjt.cn/Article/details/gtrvyyxqrw.html

[S20] C：二分查找
来源：http://dali.dianchejie.cn/Article/details/gtzazvrtbc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jiagoushi.top/Article/details/gtphscdbif.html

[S21] C：字符类别判断
来源：http://dali.ivvv.top/Article/details/gtkoqwxawr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.vqdsnc.cn/Article/details/gtyrkzjsrd.html

[S22] C：字符串转数字
来源：http://dali.nwbrower.top/Article/details/gtpqeglnuf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.havefunace.top/Article/details/gtpcppicjj.html

[S23] C：随机数
来源：http://dali.sxryk.cn/Article/details/gtsbtaplcj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yonumen.top/Article/details/gtorumvcbv.html

[S24] C：获取本地时间
来源：http://dali.chenlongwang.top/Article/details/gtnoriypop.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmexgcgqv.html

[S25] C：内存拷贝
来源：http://dali.meibo888.top/Article/details/gtffvvqpgi.html

memcpy(dst, src, n);
来源：http://dali.meibo888.top/Article/details/gtiaafdasx.html

[S26] C：内存清零
来源：http://dali.aizwys.cn/Article/details/gthqxudxrj.html

memset(a, 0, sizeof a);
来源：http://dali.hnqzz.top/Article/details/gtqgmdficf.html

[S27] C：定义常量
来源：http://dali.jinqigufen.top/Article/details/gtaesulznw.html

const double PI = 3.14159;
来源：http://dali.sysykeji.top/Article/details/gteunzojbn.html

[S28] C：静态变量
来源：http://dali.zhixingplan.top/Article/details/gtidzqwtbw.html

static int counter = 0;
来源：http://dali.meibo888.top/Article/details/gtjwycakhw.html

[S29] C：变参函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtntdmcgss.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.nanxuanxn.top/Article/details/gtookbobkm.html

[S30] C：头文件保护
来源：http://dali.316326.xyz/Article/details/gtxdadlxye.html

#ifndef X_H
来源：http://dali.smart0.xyz/Article/details/gttsacmtpg.html

#define X_H
来源：http://dali.fengsongda.top/Article/details/gtuzqgxydv.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gtrcfdgtas.html

[S31] C++：Hello World
来源：http://dali.fzhhl.top/Article/details/gtxysryiss.html

#include <iostream>
来源：http://dali.nanxinkj.top/Article/details/gtlwbmywrz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xuanzx.com/Article/details/gtpiapbina.html

[S32] C++：字符串
来源：http://dali.cdnleiting.top/Article/details/gtwmruaqxu.html

std::string s = "hi";  s += "!";
来源：http://dali.jinqigufen.top/Article/details/gtvgtcxdva.html

[S33] C++：vector 增删
来源：http://dali.vqdsnc.cn/Article/details/gtspmwlgew.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hfpthk.cn/Article/details/gtjjiaaflo.html

[S34] C++：遍历 vector
来源：http://dali.mhx1999.top/Article/details/gtzxhvyhro.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.vqdsnc.cn/Article/details/gtokpwettu.html

[S35] C++：map
来源：http://dali.chenjidiqi.icu/Article/details/gtgelnoczh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fengsongda.top/Article/details/gtehzorhoc.html

[S36] C++：unordered_map
来源：http://dali.gzhubu.top/Article/details/gtjigojcul.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jlsjyb.cn/Article/details/gtqcaffomm.html

[S37] C++：set
来源：http://dali.hywenlv.cn/Article/details/gttctfkcac.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.kuanghao11.cn/Article/details/gtwwwtikqs.html

[S38] C++：排序
来源：http://dali.cdnleiting.top/Article/details/gthpqjtipq.html

std::sort(v.begin(), v.end());
来源：http://dali.yj202588.top/Article/details/gtovmxipxf.html

[S39] C++：自定义比较器排序
来源：http://dali.nanxinkj.top/Article/details/gtzarjpcbk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.daxiang520.top/Article/details/gtrqmlcvxf.html

[S40] C++：查找元素
来源：http://dali.shzxlz.cn/Article/details/gtcekvigar.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsossatsk.html

[S41] C++：类与构造函数
来源：http://dali.sxryk.cn/Article/details/gtiwhisnes.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.andypj.xyz/Article/details/gtgjzvklvp.html

[S42] C++：继承与虚函数
来源：http://dali.hnxiangtu.top/Article/details/gtdlfqqump.html

class B : public Base { public: void f() override {} };
来源：http://dali.havefunace.top/Article/details/gtsbqwnjff.html

[S43] C++：智能指针
来源：http://dali.yj20258888.top/Article/details/gtwdiamekl.html

auto p = std::make_unique<int>(5);
来源：http://dali.redwolf501.top/Article/details/gtjadgjvfq.html

[S44] C++：引用传参
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxthyzhmk.html

void inc(int &x) { ++x; }
来源：http://dali.sufxvd.cn/Article/details/gtsijwzwfy.html

[S45] C++：lambda
来源：http://dali.pengpengdd.cyou/Article/details/gtjbiwnurm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sweek.top/Article/details/gtwvuhysjw.html

[S46] C++：函数模板
来源：http://dali.shangyingyoupin.top/Article/details/gtolxezycw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.chenlongwang.top/Article/details/gthswlqqpu.html

[S47] C++：结构化绑定遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gtspohmewr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.bjfxy.top/Article/details/gtybbsuahf.html

[S48] C++：逐行读文件
来源：http://dali.cucudq.cn/Article/details/gtttywjcnv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.vqdsnc.cn/Article/details/gtsifljjuh.html

while (std::getline(in, line)) { }
来源：http://dali.andypj.xyz/Article/details/gteptwszmw.html

[S49] C++：写文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuyfrtlqk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yuanzhike.top/Article/details/gtdrcxeljw.html

[S50] C++：格式化数字
来源：http://dali.cdnleiting.top/Article/details/gtgvmejhqc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gtzliowktr.html

[S51] C++：显式类型转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrdbtmmrv.html

static_cast<double>(a) / b
来源：http://dali.hfpthk.cn/Article/details/gtsbaaywvm.html

[S52] C++：const 与 noexcept
来源：http://dali.snrcjt.cn/Article/details/gtluwabbnt.html

int size() const noexcept { return n_; }
来源：http://dali.zhengqikj.top/Article/details/gthdfyhbpy.html

[S53] C++：移动语义
来源：http://dali.yangfankeji.com/Article/details/gtyuvanfwj.html

std::vector<int> w = std::move(v);
来源：http://dali.birdmap.top/Article/details/gtauntfjlt.html

[S54] C++：异常处理
来源：http://dali.tanke756.top/Article/details/gtynqdhmvs.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.svipenyu.cn/Article/details/gtcdyvwluz.html

[S55] C++：结构化绑定
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdqfuajzl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sxryk.cn/Article/details/gtymcschpn.html

[S56] C++：optional
来源：http://dali.ivvv.top/Article/details/gthkeiwugo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.meibo888.top/Article/details/gtjrvnjjlh.html

[S57] C++：编译期常量
来源：http://dali.bjfxy.top/Article/details/gtjhryxlkb.html

constexpr int N = 10;
来源：http://dali.shangyingyoupin.top/Article/details/gtzhrddldc.html

[S58] C++：命名空间
来源：http://dali.quarkkingdee.top/Article/details/gtauuiteji.html

namespace ns { int f() { return 1; } }
来源：http://dali.dashuyun.cn/Article/details/gtqhrpzxju.html

[S59] C++：静态断言
来源：http://dali.ydzc1.top/Article/details/gtqdczxepb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xinyue.icu/Article/details/gteomsasou.html

[S60] C++：遍历并删除元素
来源：http://dali.kuanghao11.cn/Article/details/gtoinvmvxn.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.guowangkeji.top/Article/details/gtwlehhfuj.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtrvapwxyb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yonumen.top/Article/details/gtmujeofmg.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtenaisnqf.html

[T01] Kotlin：Hello World
来源：http://dali.yj202588.top/Article/details/gtquteuvjk.html

println("Hello")
来源：http://dali.yj202588.top/Article/details/gtioeomjtw.html

[T02] Kotlin：变量
来源：http://dali.ivvv.top/Article/details/gtenelxbrd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.quarkkingdee.top/Article/details/gtqbndspgk.html

[T03] Kotlin：字符串模板
来源：http://dali.shuidangran.top/Article/details/gtfeohwnxj.html

"值: $b"
来源：http://dali.chenlongwang.top/Article/details/gtoaveersr.html

[T04] Kotlin：空安全
来源：http://dali.0kj1m.cn/Article/details/gtgjsqrqbj.html

val n: String? = null;  n?.length
来源：http://dali.jianghu66.top/Article/details/gtnzvotqbs.html

[T05] Kotlin：when 表达式
来源：http://dali.zhoulong.xyz/Article/details/gtwoigtadu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cheryme.top/Article/details/gtuftscpfe.html

[T06] Kotlin：集合映射
来源：http://dali.yj20258.top/Article/details/gtjfofuqux.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.daxiang520.top/Article/details/gtcrmfkgpf.html

[T07] Kotlin：集合过滤
来源：http://dali.zhixingplan.top/Article/details/gtvllomujw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.nanxinkj.top/Article/details/gtvapzbbee.html

[T08] Kotlin：数据类
来源：http://dali.zhengqikj.top/Article/details/gtdyxtmifi.html

data class User(val name: String, val age: Int)
来源：http://dali.shangyingyoupin.top/Article/details/gtqmhnkcpy.html

[T09] Kotlin：扩展函数
来源：http://dali.yj202588.top/Article/details/gtmlmxtaof.html

fun String.exclaim() = this + "!"
来源：http://dali.aizwys.cn/Article/details/gtkpbecoak.html

[T10] Kotlin：默认参数
来源：http://dali.jianghu66.top/Article/details/gtzbeoiebv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.nwbrower.top/Article/details/gtltngtwke.html

[T11] Kotlin：协程
来源：http://dali.nwbrower.top/Article/details/gtfccxlcka.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.mhx1999.top/Article/details/gtbfmeaahy.html

[T12] Kotlin：解构声明
来源：http://dali.shanyushiyangtech.top/Article/details/gtdmhyexaf.html

val (a, b) = Pair(1, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdllisfyz.html

[T13] Kotlin：只读 Map
来源：http://dali.gogol.net.cn/Article/details/gtwtroybah.html

val m = mapOf("a" to 1)
来源：http://dali.zhoulong.xyz/Article/details/gtwllxglib.html

[T14] Kotlin：循环
来源：http://dali.mhx1999.top/Article/details/gtzjmhsvjs.html

for (i in 1..10) println(i)
来源：http://dali.chenjidiqi.icu/Article/details/gtkbkmvbta.html

[T15] Kotlin：接口
来源：http://dali.zycfv.cn/Article/details/gtjoliuukp.html

interface Shape { fun area(): Double }
来源：http://dali.iojbl.cn/Article/details/gtxcmyqjnr.html

[T16] Swift：Hello World
来源：http://dali.yj20258.top/Article/details/gtcutxtook.html

print("Hello")
来源：http://dali.daria6918.cn/Article/details/gtotrpayjg.html

[T17] Swift：变量与常量
来源：http://dali.cashguo.top/Article/details/gthrpzuasw.html

var a = 1;  let b = 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtjvkxbdmz.html

[T18] Swift：字符串插值
来源：http://dali.yj20258888.top/Article/details/gtbwrpxira.html

"值: \(b)"
来源：http://dali.redwolf501.top/Article/details/gtzrozwkqi.html

[T19] Swift：可选绑定
来源：http://dali.shanyushiyangtech.top/Article/details/gtopntjzee.html

if let n = opt { print(n) }
来源：http://dali.jinqigufen.top/Article/details/gtrmmanwig.html

[T20] Swift：数组操作
来源：http://dali.hnqzz.top/Article/details/gtgabilzxb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hfpthk.cn/Article/details/gtdfkmfmwt.html

[T21] Swift：遍历
来源：http://dali.smart0.xyz/Article/details/gtaefubtlq.html

for x in a { print(x) }
来源：http://dali.nwbrower.top/Article/details/gtdmwjtnql.html

[T22] Swift：字典
来源：http://dali.gotoacloud.top/Article/details/gtidrujuup.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.quarkkingdee.top/Article/details/gthwtikcdf.html

[T23] Swift：函数
来源：http://dali.yj202588.top/Article/details/gtfmfbzkht.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.kuanghao11.cn/Article/details/gtkueckoxa.html

[T24] Swift：闭包
来源：http://dali.chenlongwang.top/Article/details/gtceyrpmnk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhixingplan.top/Article/details/gtypyhhdhb.html

[T25] Swift：结构体
来源：http://dali.xinyue.icu/Article/details/gtvmxpintw.html

struct P { var x: Int }
来源：http://dali.dashuyun.cn/Article/details/gteuhkkzvo.html

[T26] Swift：类与重写
来源：http://dali.wangdashe.top/Article/details/gttnejjzsy.html

class A: Base { override func f() {} }
来源：http://dali.yonumen.top/Article/details/gtrcyozail.html

[T27] Swift：错误处理
来源：http://dali.shanyushiyangtech.top/Article/details/gtfoopctwt.html

do { try f() } catch { print(error) }
来源：http://dali.gotoacloud.top/Article/details/gtqrdndbwb.html

[T28] Swift：枚举
来源：http://dali.bjfxy.top/Article/details/gthymrwiap.html

enum Color { case red, green }
来源：http://dali.daria6918.cn/Article/details/gtuumtnkxp.html

[T29] Swift：guard 提前返回
来源：http://dali.yonumen.top/Article/details/gtymunmngy.html

guard let x = opt else { return }
来源：http://dali.sufxvd.cn/Article/details/gtgovxljpp.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gtxiufrnbu.html

protocol Shape { func area() -> Double }
来源：http://dali.ybcxt.top/Article/details/gtkffayjai.html

[T31] Lua：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gttycxvcpq.html

print("Hello")
来源：http://dali.ybcxt.top/Article/details/gthlfrrwys.html

[T32] Lua：局部变量
来源：http://dali.vqdsnc.cn/Article/details/gtczmhmycd.html

local a = 1
来源：http://dali.yonumen.top/Article/details/gtqfndoqne.html

[T33] Lua：表（数组）
来源：http://dali.yongpay.top/Article/details/gtmvsjyhib.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.dashuyun.cn/Article/details/gtwyioowun.html

[T34] Lua：遍历表
来源：http://dali.redwolf501.top/Article/details/gtbtxwxeia.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jinqigfzy.top/Article/details/gtuhftkpvx.html

[T35] Lua：字典表
来源：http://dali.shangyingyoupin.top/Article/details/gtgwgvvjiw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hammf.cn/Article/details/gtspettgbc.html

[T36] Lua：函数
来源：http://dali.shzxlz.cn/Article/details/gtmnghcort.html

function add(a, b) return a + b end
来源：http://dali.hongshengwenyu.top/Article/details/gtvbbomtfo.html

[T37] Lua：字符串拼接
来源：http://dali.zycfv.cn/Article/details/gtvxtscvsk.html

"a" .. "b"
来源：http://dali.ehwqpu.com/Article/details/gtnlifhorm.html

[T38] Lua：条件
来源：http://dali.xziqi.cn/Article/details/gthxkdiwyg.html

if x > 0 then print("正") end
来源：http://dali.redwolf501.top/Article/details/gteszehwjy.html

[T39] Lua：模式匹配
来源：http://dali.kuanghao11.cn/Article/details/gtwqhbryqe.html

string.find(s, "%d+")
来源：http://dali.daria6918.cn/Article/details/gtssjwejgd.html

[T40] Lua：元表
来源：http://dali.daxiang520.top/Article/details/gtikjflkwe.html

setmetatable({}, { __index = base })
来源：http://dali.guowangkeji.top/Article/details/gtdmoqeirx.html

[T41] Perl：Hello World
来源：http://dali.xylfe.cn/Article/details/gtegfzsjly.html

print "Hello\n";
来源：http://dali.cashguo.top/Article/details/gtpxgtteel.html

[T42] Perl：变量类型
来源：http://dali.zhengqikj.top/Article/details/gtuylqelyk.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gtswpvlzzh.html

[T43] Perl：字符串插值
来源：http://dali.quarkkingdee.top/Article/details/gtwdutbvrw.html

"值: $a"
来源：http://dali.ivvv.top/Article/details/gtqhhgsqcz.html

[T44] Perl：条件
来源：http://dali.9152youxi.cn/Article/details/gtoeqieemz.html

if ($a > 0) { print "正"; }
来源：http://dali.chenzaomai.com/Article/details/gtgqukndcx.html

[T45] Perl：数组遍历
来源：http://dali.jiagoushi.top/Article/details/gtgtmjnqhy.html

for my $x (@arr) { print $x; }
来源：http://dali.chenlongwang.top/Article/details/gttvowigdh.html

[T46] Perl：哈希操作
来源：http://dali.gaohongyu789.top/Article/details/gtseamxuza.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yj202588.top/Article/details/gtefdfimgg.html

[T47] Perl：正则捕获
来源：http://dali.aibaodan.cn/Article/details/gtmfurwdsr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zdqjudy.top/Article/details/gtuoaggdln.html

[T48] Perl：正则替换
来源：http://dali.guannengcc.top/Article/details/gthbjsmvtb.html

$s =~ s/old/new/g;
来源：http://dali.quarkkingdee.top/Article/details/gtpgriukac.html


<!-- 参考信息 -->