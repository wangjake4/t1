代发 wailian999

cmd >/dev/null 2>&1
来源：http://dali.ivvv.top/Article/details/gtdozfxyll.html

[R42] 输入重定向
来源：http://dali.jinqigfzy.top/Article/details/gtitcachcy.html

wc -l < a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtjjotgtpa.html

[R43] 按名字查找文件
来源：http://dali.xinyue.icu/Article/details/gtpdjhrlau.html

find . -name "*.log" -type f
来源：http://dali.birdmap.top/Article/details/gtmwfpvjnu.html

[R44] 按修改时间查找
来源：http://dali.xuetiantiany.cn/Article/details/gttmnsibmy.html

find . -mtime -7 -type f
来源：http://dali.hnxiangtu.top/Article/details/gtncyvwpiz.html

[R45] 批量删除
来源：http://dali.birdmap.top/Article/details/gtepmpvlwu.html

find . -name "*.tmp" -delete
来源：http://dali.gzhubu.top/Article/details/gtuozpnfjq.html

[R46] 递归替换文件内容
来源：http://dali.andypj.xyz/Article/details/gtppsxifos.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xylfe.cn/Article/details/gtmrohgtxo.html

[R47] sed 单行替换
来源：http://dali.sysykeji.top/Article/details/gtjxaalzax.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.birdmap.top/Article/details/gtfjdwekem.html

[R48] awk 取指定列
来源：http://dali.tianlin.xyz/Article/details/gttymbnofk.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtvikatwnr.html

[R49] awk 带条件
来源：http://dali.fzhhl.top/Article/details/gtirefaehl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.wangshuangyany.cn/Article/details/gtocivtuhx.html

[R50] awk 求和
来源：http://dali.chenlongwang.top/Article/details/gtsfslmkfy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.dianchejie.cn/Article/details/gtvhnopekc.html

[R51] 排序去重取前几
来源：http://dali.hywenlv.cn/Article/details/gtkjadoohb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.sxryk.cn/Article/details/gtsujfjscx.html

[R52] 统计行数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvqssgotz.html

wc -l a.txt
来源：http://dali.yonumen.top/Article/details/gttmosbmla.html

[R53] 查看文件头与实时尾
来源：http://dali.shanyushiyangkeji.top/Article/details/gtklburrrv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.haohaochexian.top/Article/details/gtytdvugpk.html

[R54] 比较两个文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvfvmaguy.html

diff a.txt b.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtpetzjcpd.html

[R55] 压缩与解压
来源：http://dali.quarkkingdee.top/Article/details/gtgdbrchuk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ppjwa.cn/Article/details/gtsgarhivf.html

[R56] 远程拷贝
来源：http://dali.yj20258888.top/Article/details/gtxvxljvot.html

scp file user@host:/path/
来源：http://dali.aizwys.cn/Article/details/gtruupuoxc.html

[R57] 远程执行命令
来源：http://dali.daria6918.cn/Article/details/gtjlevfueq.html

ssh user@host 'uptime'
来源：http://dali.ivvv.top/Article/details/gtdbvyhliy.html

[R58] 下载文件
来源：http://dali.meibo888.top/Article/details/gtzbzigvxc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hammf.cn/Article/details/gtchdbsdzw.html

[R59] 发 POST JSON
来源：http://dali.gaohongyu789.top/Article/details/gtfhtnlxyb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zycfv.cn/Article/details/gtpkrnpunu.html

[R60] 只看 HTTP 状态码
来源：http://dali.xylfe.cn/Article/details/gtqwgujbht.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gtlsrvrzet.html

[R61] 磁盘占用
来源：http://dali.xuanzx.com/Article/details/gtuptujgjl.html

df -h;  du -sh *
来源：http://dali.xinyue.icu/Article/details/gtiqjqfehg.html

[R62] 找最占空间的文件
来源：http://dali.yj202588.top/Article/details/gtsxmjabzg.html

du -ah . | sort -rh | head -10
来源：http://dali.0kj1m.cn/Article/details/gtgmzghqdi.html

[R63] 内存与进程
来源：http://dali.guowangkeji.top/Article/details/gtsrvxbnij.html

free -h;  ps aux | grep nginx
来源：http://dali.jyoumei.cn/Article/details/gtywvjwjnc.html

[R64] 结束进程
来源：http://dali.aibaodan.cn/Article/details/gtyvbqsyzp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.fengsongda.top/Article/details/gtuuadknps.html

[R65] 查看端口占用
来源：http://dali.shuidangran.top/Article/details/gtxxoztyag.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbkotgyaj.html

[R66] 定时任务
来源：http://dali.aizwys.cn/Article/details/gtbtyixeji.html

crontab -e;  crontab -l
来源：http://dali.316326.xyz/Article/details/gtfbcvciky.html

[R67] 生成随机十六进制串
来源：http://dali.yonumen.top/Article/details/gttaykigdw.html

openssl rand -hex 16
来源：http://dali.hywenlv.cn/Article/details/gtulnfrtvt.html

[R68] 计算文件校验值
来源：http://dali.zhoulong.xyz/Article/details/gtlsdrynix.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.fzhhl.top/Article/details/gtsfqdwjuj.html

[R69] 生成随机密码
来源：http://dali.gotoacloud.top/Article/details/gteyyhtfit.html

head -c 16 /dev/urandom | base64
来源：http://dali.cucudq.cn/Article/details/gttgwiqkhb.html

[R70] 时间戳与互转
来源：http://dali.chenzaomai.com/Article/details/gtqdfycbca.html

date +%s;  date -d @1700000000
来源：http://dali.redwolf501.top/Article/details/gtwddwglfh.html

[R71] 日期格式化
来源：http://dali.xylfe.cn/Article/details/gthmqtnorq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.wangdashe.top/Article/details/gtlccgfhdi.html

[R72] 等待端口就绪
来源：http://dali.cdnleiting.top/Article/details/gtblrgdsuq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhoulong.xyz/Article/details/gtgfmartqz.html

[R73] 分割大日志
来源：http://dali.zhongyouzk.top/Article/details/gtnbjwxyzx.html

split -l 1000 big.log part_
来源：http://dali.cqqwz.cn/Article/details/gtolbayweq.html

[R74] 批量重命名
来源：http://dali.zdqjudy.top/Article/details/gtladyobgn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhixingplan.top/Article/details/gtpduksjax.html

[R75] 导出环境变量
来源：http://dali.tanke756.top/Article/details/gtezjqniuk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.svipenyu.cn/Article/details/gtytzkpdqp.html

[R76] 使用临时文件
来源：http://dali.yanxiufei.cn/Article/details/gtechugxir.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqurzqdkl.html

[R77] 读取用户输入
来源：http://dali.cucudq.cn/Article/details/gtbgjcgjpg.html

read -rp "请输入: " ans
来源：http://dali.feifeiyinyue.top/Article/details/gtsqdgootc.html

[R78] 交互式菜单
来源：http://dali.316326.xyz/Article/details/gthwenzrdv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hammf.cn/Article/details/gtrswcamyf.html

[R79] 解析命令行选项
来源：http://dali.yonumen.top/Article/details/gtbciddbfu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.andypj.xyz/Article/details/gthumlzsld.html

[R80] 查看脚本执行耗时
来源：http://dali.yj20258888.top/Article/details/gtzzdpuyfk.html

time ./run.sh
来源：http://dali.nwbrower.top/Article/details/gtquqnohnd.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtvggpttqx.html

S. C / C++ 专题
来源：http://dali.316326.xyz/Article/details/gtvytswxkr.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtvkykwerx.html

[S01] C：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtouzwavpz.html

#include <stdio.h>
来源：http://dali.snrcjt.cn/Article/details/gtxltyejab.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.aizwys.cn/Article/details/gtnovvkaqv.html

[S02] C：变量与格式化输出
来源：http://dali.xziqi.cn/Article/details/gtptjiokak.html

int a = 10; printf("%d\n", a);
来源：http://dali.yj20258888.top/Article/details/gtcxleysxm.html

[S03] C：读入整数
来源：http://dali.kuanghao11.cn/Article/details/gtlnbebhwx.html

int x; scanf("%d", &x);
来源：http://dali.tian-w.cn/Article/details/gtywdhnset.html

[S04] C：字符串复制
来源：http://dali.jqgufenzy.top/Article/details/gtubdchjgl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hnxiangtu.top/Article/details/gtabtrvcai.html

[S05] C：字符串长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfqeaznjj.html

strlen(s)
来源：http://dali.dashuyun.cn/Article/details/gtvafrgbpu.html

[S06] C：字符串比较
来源：http://dali.ppjwa.cn/Article/details/gtmqltvbog.html

strcmp(a, b) == 0
来源：http://dali.yj20258888.top/Article/details/gtpuhnkesn.html

[S07] C：数组遍历求和
来源：http://dali.zhiwuduotai.top/Article/details/gtlgzzyndo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xuanzx.com/Article/details/gtgcfguyab.html

[S08] C：动态内存分配与释放
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmkrwlwvx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.daria6918.cn/Article/details/gtwtsijitq.html

[S09] C：结构体定义与初始化
来源：http://dali.nanxuanxn.top/Article/details/gtwfoccpfy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.vqdsnc.cn/Article/details/gtlpxcvqhd.html

[S10] C：指针与解引用
来源：http://dali.shuidangran.top/Article/details/gtyriksxwh.html

int *p = &a;  *p = 5;
来源：http://dali.haohaochexian.top/Article/details/gttvbezvqn.html

[S11] C：逐行读文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtjxfinita.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jyoumei.cn/Article/details/gtjjsmneaz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jyoumei.cn/Article/details/gtsbygaiol.html

fclose(f);
来源：http://dali.shuidangran.top/Article/details/gtjcoavxfn.html

[S12] C：写文件
来源：http://dali.fzhhl.top/Article/details/gtxdmngetr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.quarkkingdee.top/Article/details/gthmqavztn.html

[S13] C：宏定义
来源：http://dali.yj202588.top/Article/details/gtzlaawaro.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xuanzx.com/Article/details/gtkgbhpjde.html

[S14] C：枚举
来源：http://dali.cdnleiting.top/Article/details/gtxtvkvhas.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.iojbl.cn/Article/details/gtlqjlbgcm.html

[S15] C：类型转换
来源：http://dali.ehwqpu.com/Article/details/gtvmyjscxz.html

(double) a / b
来源：http://dali.pengpengdd.cyou/Article/details/gtqwhswdeh.html

[S16] C：位操作置位
来源：http://dali.yj20258888.top/Article/details/gtzkvglsev.html

x |= (1 << 3);
来源：http://dali.haohaochexian.top/Article/details/gtiunnoypw.html

[S17] C：安全拼接字符串
来源：http://dali.zhengqikj.top/Article/details/gtmiynimar.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.c1oappe.top/Article/details/gtbwzcnaep.html

[S18] C：命令行参数
来源：http://dali.aizwys.cn/Article/details/gtpbvegohv.html

int main(int argc, char **argv)
来源：http://dali.shzxlz.cn/Article/details/gtudrirovv.html

[S19] C：快速排序
来源：http://dali.mhx1999.top/Article/details/gtdhojxety.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jinghuilouyu.cn/Article/details/gtdrsoawsh.html

[S20] C：二分查找
来源：http://dali.hnxiangtu.top/Article/details/gthxbpemwj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cheryme.top/Article/details/gtbauboxzb.html

[S21] C：字符类别判断
来源：http://dali.cdnleiting.top/Article/details/gtmipbpjyv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yuxming.cn/Article/details/gthmkuaqzl.html

[S22] C：字符串转数字
来源：http://dali.pengpengdd.cyou/Article/details/gtdotugqtq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hysaishi.cn/Article/details/gtqamsackb.html

[S23] C：随机数
来源：http://dali.kuanghao11.cn/Article/details/gtnsrnrrfr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj20258888.top/Article/details/gtkgffpowx.html

[S24] C：获取本地时间
来源：http://dali.yj202588.top/Article/details/gtmpukjvwn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cashguo.top/Article/details/gtxojvlmxm.html

[S25] C：内存拷贝
来源：http://dali.gzhubu.top/Article/details/gtkkenvurw.html

memcpy(dst, src, n);
来源：http://dali.gzhubu.top/Article/details/gtbtdyyqxw.html

[S26] C：内存清零
来源：http://dali.jyoumei.cn/Article/details/gtfszolaqv.html

memset(a, 0, sizeof a);
来源：http://dali.fzhhl.top/Article/details/gtwuorhtgo.html

[S27] C：定义常量
来源：http://dali.tian-w.cn/Article/details/gtwgmftltp.html

const double PI = 3.14159;
来源：http://dali.jqgufenzy.top/Article/details/gtxqcghyan.html

[S28] C：静态变量
来源：http://dali.redwolf501.top/Article/details/gtoyupvbsu.html

static int counter = 0;
来源：http://dali.wangshuangyany.cn/Article/details/gtgnmajoxo.html

[S29] C：变参函数
来源：http://dali.zhongyouzk.top/Article/details/gtakkvuyuz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cucudq.cn/Article/details/gtojppblpb.html

[S30] C：头文件保护
来源：http://dali.jqgfzy.top/Article/details/gtucfjipgq.html

#ifndef X_H
来源：http://dali.jinqigfzy.top/Article/details/gtqvoxnnxc.html

#define X_H
来源：http://dali.ydzc1.top/Article/details/gtvxfvuysg.html

#endif
来源：http://dali.jiagoushi.top/Article/details/gthsljwozx.html

[S31] C++：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtefaxwxza.html

#include <iostream>
来源：http://dali.zdqjudy.top/Article/details/gtjgqaafdb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gaohongyu789.top/Article/details/gtgygmfdgu.html

[S32] C++：字符串
来源：http://dali.jiagoushi.top/Article/details/gtpnyaxjfl.html

std::string s = "hi";  s += "!";
来源：http://dali.zdqjudy.top/Article/details/gtoexombvz.html

[S33] C++：vector 增删
来源：http://dali.redwolf501.top/Article/details/gttbjvuphx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.dianchejie.cn/Article/details/gtlqmnxonj.html

[S34] C++：遍历 vector
来源：http://dali.chenlongwang.top/Article/details/gtqxjryniz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yonumen.top/Article/details/gtroiqijga.html

[S35] C++：map
来源：http://dali.havefunace.top/Article/details/gtziqhwwln.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gtrkutnfpu.html

[S36] C++：unordered_map
来源：http://dali.chenzaomai.com/Article/details/gtxxkpgaxo.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hfpthk.cn/Article/details/gtclfvylky.html

[S37] C++：set
来源：http://dali.gzhubu.top/Article/details/gtjhujbqjl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gtgwsibkaj.html

[S38] C++：排序
来源：http://dali.pycfn.com/Article/details/gtpfsejzsj.html

std::sort(v.begin(), v.end());
来源：http://dali.vqdsnc.cn/Article/details/gtxzvchqia.html

[S39] C++：自定义比较器排序
来源：http://dali.feifeiyinyue.top/Article/details/gtvraunapx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shanyushiyangtech.top/Article/details/gtskxlmigq.html

[S40] C++：查找元素
来源：http://dali.nwbrower.top/Article/details/gtognreclh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.bjfxy.top/Article/details/gtxubcveif.html

[S41] C++：类与构造函数
来源：http://dali.yuxming.cn/Article/details/gtredawlas.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.chenjidiqi.icu/Article/details/gtgemppvmg.html

[S42] C++：继承与虚函数
来源：http://dali.quarkkingdee.top/Article/details/gtaoqkizys.html

class B : public Base { public: void f() override {} };
来源：http://dali.yongpay.top/Article/details/gtignaqzba.html

[S43] C++：智能指针
来源：http://dali.smart0.xyz/Article/details/gtfcpupkld.html

auto p = std::make_unique<int>(5);
来源：http://dali.wangshuangyany.cn/Article/details/gtekfhswkh.html

[S44] C++：引用传参
来源：http://dali.zhengqikj.top/Article/details/gtjsgpubcz.html

void inc(int &x) { ++x; }
来源：http://dali.zhengqikj.top/Article/details/gtfheeyqat.html

[S45] C++：lambda
来源：http://dali.meibo888.top/Article/details/gtquewvwca.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.daria6918.cn/Article/details/gtrqcwprhc.html

[S46] C++：函数模板
来源：http://dali.yj202588.top/Article/details/gtyllwldqg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.fengsongda.top/Article/details/gtbernbxlw.html

[S47] C++：结构化绑定遍历
来源：http://dali.dianchejie.cn/Article/details/gtarnvlzvu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jqgufenzy.top/Article/details/gtrcrvhqah.html

[S48] C++：逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gtkdfbwuki.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhengqikj.top/Article/details/gtjqwdomyf.html

while (std::getline(in, line)) { }
来源：http://dali.hfpthk.cn/Article/details/gtmguptogi.html

[S49] C++：写文件
来源：http://dali.316326.xyz/Article/details/gtbmppygiu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ivvv.top/Article/details/gtamjitsua.html

[S50] C++：格式化数字
来源：http://dali.chenlongwang.top/Article/details/gtobktzksx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.fzhhl.top/Article/details/gtfnczqlke.html

[S51] C++：显式类型转换
来源：http://dali.snrcjt.cn/Article/details/gtrriaqaiq.html

static_cast<double>(a) / b
来源：http://dali.jlsjyb.cn/Article/details/gtshruqrqx.html

[S52] C++：const 与 noexcept
来源：http://dali.shuidangran.top/Article/details/gthnnljfti.html

int size() const noexcept { return n_; }
来源：http://dali.gogol.net.cn/Article/details/gtdvzhrhbw.html

[S53] C++：移动语义
来源：http://dali.jinqigfzy.top/Article/details/gtbwwmkysu.html

std::vector<int> w = std::move(v);
来源：http://dali.iojbl.cn/Article/details/gtavijajml.html

[S54] C++：异常处理
来源：http://dali.aizwys.cn/Article/details/gtvbrmspvh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shanyushiyangtech.top/Article/details/gthoprjlef.html

[S55] C++：结构化绑定
来源：http://dali.jinghuilouyu.cn/Article/details/gtslyumypb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.birdmap.top/Article/details/gtsbftgmsj.html

[S56] C++：optional
来源：http://dali.zhaomingkeji.xyz/Article/details/gtklbgddee.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xuetiantiany.cn/Article/details/gtwumkjpwj.html

[S57] C++：编译期常量
来源：http://dali.9152youxi.cn/Article/details/gtamvrdvll.html

constexpr int N = 10;
来源：http://dali.daxiang520.top/Article/details/gteovgkuqa.html

[S58] C++：命名空间
来源：http://dali.tian-w.cn/Article/details/gtcyazlswy.html

namespace ns { int f() { return 1; } }
来源：http://dali.sweek.top/Article/details/gtzcgljifb.html

[S59] C++：静态断言
来源：http://dali.yanxiufei.cn/Article/details/gtqzyghkin.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.kuanghao11.cn/Article/details/gtlehdrlkp.html

[S60] C++：遍历并删除元素
来源：http://dali.aizwys.cn/Article/details/gtteojxscr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jiagoushi.top/Article/details/gtalrjemdd.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gterttspeh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinqigfzy.top/Article/details/gtsntayynx.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtshxqudmf.html

[T01] Kotlin：Hello World
来源：http://dali.ybcxt.top/Article/details/gtnszuhtxo.html

println("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gtybuqoksw.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gtrrlvfxoi.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.aizwys.cn/Article/details/gtdvldvaix.html

[T03] Kotlin：字符串模板
来源：http://dali.wangshuangyany.cn/Article/details/gtrtmyiwnv.html

"值: $b"
来源：http://dali.xuanzx.com/Article/details/gtvsuyizlc.html

[T04] Kotlin：空安全
来源：http://dali.0kj1m.cn/Article/details/gtuhkkdibn.html

val n: String? = null;  n?.length
来源：http://dali.tianlin.xyz/Article/details/gtjwvdfmfc.html

[T05] Kotlin：when 表达式
来源：http://dali.chenjidiqi.icu/Article/details/gtvyfqinld.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yj20258888.top/Article/details/gtsasjyilc.html

[T06] Kotlin：集合映射
来源：http://dali.nanxinkj.top/Article/details/gthvzuktlm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jlsjyb.cn/Article/details/gtqdozfsya.html

[T07] Kotlin：集合过滤
来源：http://dali.bjfxy.top/Article/details/gtweipmvqy.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpkyxvkrz.html

[T08] Kotlin：数据类
来源：http://dali.havefunace.top/Article/details/gtgvvpqnso.html

data class User(val name: String, val age: Int)
来源：http://dali.guowangkeji.top/Article/details/gtmyupnmtw.html

[T09] Kotlin：扩展函数
来源：http://dali.chenlongwang.top/Article/details/gtydihmsph.html

fun String.exclaim() = this + "!"
来源：http://dali.havefunace.top/Article/details/gtgxjikqff.html

[T10] Kotlin：默认参数
来源：http://dali.hysaishi.cn/Article/details/gtfgkxrhli.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.tian-w.cn/Article/details/gtvnuwvylq.html

[T11] Kotlin：协程
来源：http://dali.smart0.xyz/Article/details/gtrvpsgvql.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.tian-w.cn/Article/details/gtznumwpir.html

[T12] Kotlin：解构声明
来源：http://dali.hnqzz.top/Article/details/gtvktxqzuy.html

val (a, b) = Pair(1, 2)
来源：http://dali.daria6918.cn/Article/details/gtgyfebrcr.html

[T13] Kotlin：只读 Map
来源：http://dali.yuanzhike.top/Article/details/gtbqhptigj.html

val m = mapOf("a" to 1)
来源：http://dali.sufxvd.cn/Article/details/gtldeqzbnk.html

[T14] Kotlin：循环
来源：http://dali.yanxiufei.cn/Article/details/gtjxgrqljg.html

for (i in 1..10) println(i)
来源：http://dali.bjfxy.top/Article/details/gtxtvslllg.html

[T15] Kotlin：接口
来源：http://dali.dashuyun.cn/Article/details/gtfrgyjlpt.html

interface Shape { fun area(): Double }
来源：http://dali.hammf.cn/Article/details/gtopglxvtx.html

[T16] Swift：Hello World
来源：http://dali.aizwys.cn/Article/details/gtqvtppsvh.html

print("Hello")
来源：http://dali.jinqigufen.top/Article/details/gthfzoddiy.html

[T17] Swift：变量与常量
来源：http://dali.yvedp.cn/Article/details/gtjfhmoyuc.html

var a = 1;  let b = 2
来源：http://dali.jianghu66.top/Article/details/gtjppmmgjk.html

[T18] Swift：字符串插值
来源：http://dali.zhoulong.xyz/Article/details/gtcnkzuiai.html

"值: \(b)"
来源：http://dali.hysaishi.cn/Article/details/gtvjvdvmho.html

[T19] Swift：可选绑定
来源：http://dali.guowangkeji.top/Article/details/gtkjxkdspz.html

if let n = opt { print(n) }
来源：http://dali.shangyingyoupin.top/Article/details/gtdvjeywnb.html

[T20] Swift：数组操作
来源：http://dali.shangyingyoupin.top/Article/details/gtkfbdqihc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xuanzx.com/Article/details/gtpcrpkvdz.html

[T21] Swift：遍历
来源：http://dali.jinqigfzy.top/Article/details/gtheouczue.html

for x in a { print(x) }
来源：http://dali.yongpay.top/Article/details/gtwwyxefbc.html

[T22] Swift：字典
来源：http://dali.wangshuangyany.cn/Article/details/gtucamfbqw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhongyouzk.top/Article/details/gtrxkckvav.html

[T23] Swift：函数
来源：http://dali.gzhubu.top/Article/details/gtezxluqlm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.gzhubu.top/Article/details/gtulxswtut.html

[T24] Swift：闭包
来源：http://dali.yuxming.cn/Article/details/gtbwvabonb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xziqi.cn/Article/details/gttjxcplyd.html

[T25] Swift：结构体
来源：http://dali.guowangkeji.top/Article/details/gthiolehgy.html

struct P { var x: Int }
来源：http://dali.jiagoushi.top/Article/details/gtdmfujdps.html

[T26] Swift：类与重写
来源：http://dali.yj20258.top/Article/details/gtfnvmgzcl.html

class A: Base { override func f() {} }
来源：http://dali.dashuyun.cn/Article/details/gtbhfxmvbo.html

[T27] Swift：错误处理
来源：http://dali.daxiang520.top/Article/details/gtsiietmzb.html

do { try f() } catch { print(error) }
来源：http://dali.kuanghao11.cn/Article/details/gtjuqtsalb.html

[T28] Swift：枚举
来源：http://dali.yj20258888.top/Article/details/gtwmyvsllp.html

enum Color { case red, green }
来源：http://dali.birdmap.top/Article/details/gtkvwpkvhg.html

[T29] Swift：guard 提前返回
来源：http://dali.jianghu66.top/Article/details/gtzpoexuxn.html

guard let x = opt else { return }
来源：http://dali.jianghu66.top/Article/details/gtjvttyyjr.html

[T30] Swift：协议
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgvdsfnio.html

protocol Shape { func area() -> Double }
来源：http://dali.hywenlv.cn/Article/details/gtngxeykui.html

[T31] Lua：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtykvowzit.html

print("Hello")
来源：http://dali.sufxvd.cn/Article/details/gtiakfdyeu.html

[T32] Lua：局部变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvteuydsl.html

local a = 1
来源：http://dali.daxiang520.top/Article/details/gtdnpegnxr.html

[T33] Lua：表（数组）
来源：http://dali.quarkkingdee.top/Article/details/gtrjnjcjvg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shuidangran.top/Article/details/gtworzaabv.html

[T34] Lua：遍历表
来源：http://dali.sufxvd.cn/Article/details/gtwxuljsms.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shanyushiyangtech.top/Article/details/gtyuyhpnvh.html

[T35] Lua：字典表
来源：http://dali.shzxlz.cn/Article/details/gtoceltzxe.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sufxvd.cn/Article/details/gtngnagute.html

[T36] Lua：函数
来源：http://dali.yuanzhike.top/Article/details/gtznnbzfhp.html

function add(a, b) return a + b end
来源：http://dali.zhengqikj.top/Article/details/gtujmwolnt.html

[T37] Lua：字符串拼接
来源：http://dali.zhixingplan.top/Article/details/gtfacxhqcx.html

"a" .. "b"
来源：http://dali.cheryme.top/Article/details/gtfqcseuut.html

[T38] Lua：条件
来源：http://dali.aizwys.cn/Article/details/gttstdogch.html

if x > 0 then print("正") end
来源：http://dali.yvedp.cn/Article/details/gtivixacco.html

[T39] Lua：模式匹配
来源：http://dali.gaohongyu789.top/Article/details/gttijyihvn.html

string.find(s, "%d+")
来源：http://dali.ppjwa.cn/Article/details/gtbtefoxzd.html

[T40] Lua：元表
来源：http://dali.mhx1999.top/Article/details/gtyrmawlrj.html

setmetatable({}, { __index = base })
来源：http://dali.jyoumei.cn/Article/details/gtsvyysncr.html

[T41] Perl：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtajhdlexn.html

print "Hello\n";
来源：http://dali.tianlin.xyz/Article/details/gtyngigxrm.html

[T42] Perl：变量类型
来源：http://dali.gaohongyu789.top/Article/details/gtpaoxnbgw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hysaishi.cn/Article/details/gtqdhsoqsa.html

[T43] Perl：字符串插值
来源：http://dali.316326.xyz/Article/details/gtxqvukxce.html

"值: $a"
来源：http://dali.haohaochexian.top/Article/details/gtnhqscmdw.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gtidzejxmv.html

if ($a > 0) { print "正"; }
来源：http://dali.chenlongwang.top/Article/details/gtcvttmlky.html


<!-- 参考信息 -->