代发 wailian999

files=$(ls -1)
来源：http://dali.ehwqpu.com/Article/details/gtnikxikdf.html

[R38] 管道串联
来源：http://dali.snrcjt.cn/Article/details/gtkflldqfg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.vqdsnc.cn/Article/details/gthrwucaim.html

[R39] 重定向标准输出与错误
来源：http://dali.chenjidiqi.icu/Article/details/gtqqikczbm.html

cmd > out.log 2>&1
来源：http://dali.aizwys.cn/Article/details/gtfcxmctgl.html

[R40] 追加写日志
来源：http://dali.bjfxy.top/Article/details/gtrimigdlh.html

echo "log" >> out.log
来源：http://dali.zhoulong.xyz/Article/details/gtpdokqxye.html

[R41] 丢弃输出
来源：http://dali.shanyushiyangtech.top/Article/details/gtsjhlrksx.html

cmd >/dev/null 2>&1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtovxwbbzv.html

[R42] 输入重定向
来源：http://dali.shuidangran.top/Article/details/gtjyeubzgi.html

wc -l < a.txt
来源：http://dali.ybcxt.top/Article/details/gtnwdedzmz.html

[R43] 按名字查找文件
来源：http://dali.zhongyouzk.top/Article/details/gtviqwgwrh.html

find . -name "*.log" -type f
来源：http://dali.yonumen.top/Article/details/gttxcwaqau.html

[R44] 按修改时间查找
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtshblrsgs.html

find . -mtime -7 -type f
来源：http://dali.aibaodan.cn/Article/details/gtvymaxsxj.html

[R45] 批量删除
来源：http://dali.9152youxi.cn/Article/details/gtticwibxc.html

find . -name "*.tmp" -delete
来源：http://dali.gaohongyu789.top/Article/details/gtjsrduute.html

[R46] 递归替换文件内容
来源：http://dali.chenzaomai.com/Article/details/gtxzegbufm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.9152youxi.cn/Article/details/gtyoazreyu.html

[R47] sed 单行替换
来源：http://dali.ydzc1.top/Article/details/gtbltkqrio.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hnxiangtu.top/Article/details/gtchxgaghv.html

[R48] awk 取指定列
来源：http://dali.daria6918.cn/Article/details/gtrftqlqho.html

awk '{print $1, $3}' a.txt
来源：http://dali.tanke756.top/Article/details/gtdgyvsaky.html

[R49] awk 带条件
来源：http://dali.xinyue.icu/Article/details/gtbezmidak.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.aizwys.cn/Article/details/gtuijkyahr.html

[R50] awk 求和
来源：http://dali.tanke756.top/Article/details/gtsdmrykiv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.aibaodan.cn/Article/details/gtxuzovawm.html

[R51] 排序去重取前几
来源：http://dali.shanyushiyangtech.top/Article/details/gtgwyydkgt.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.quarkkingdee.top/Article/details/gtdcsuqhsi.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gtplzwclyh.html

wc -l a.txt
来源：http://dali.zhixingplan.top/Article/details/gtbqkbvhul.html

[R53] 查看文件头与实时尾
来源：http://dali.cqqwz.cn/Article/details/gtxsbawbns.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.smart0.xyz/Article/details/gtxdwhnthd.html

[R54] 比较两个文件
来源：http://dali.dashuyun.cn/Article/details/gtyprbuzie.html

diff a.txt b.txt
来源：http://dali.tian-w.cn/Article/details/gtpvpiutvw.html

[R55] 压缩与解压
来源：http://dali.zhoulong.xyz/Article/details/gtsompxvhy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.daria6918.cn/Article/details/gtfimrhlfp.html

[R56] 远程拷贝
来源：http://dali.yvedp.cn/Article/details/gtlntjdfhw.html

scp file user@host:/path/
来源：http://dali.redwolf501.top/Article/details/gtufwmliqq.html

[R57] 远程执行命令
来源：http://dali.hongshengwenyu.top/Article/details/gtflmxjjkh.html

ssh user@host 'uptime'
来源：http://dali.yanxiufei.cn/Article/details/gtpgogtdwx.html

[R58] 下载文件
来源：http://dali.hammf.cn/Article/details/gtjngdilix.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hywenlv.cn/Article/details/gtcstdzcgp.html

[R59] 发 POST JSON
来源：http://dali.jinqigfzy.top/Article/details/gtgjwpnldo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.havefunace.top/Article/details/gtgqmjdncx.html

[R60] 只看 HTTP 状态码
来源：http://dali.smart0.xyz/Article/details/gtaskzeeyo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cdnleiting.top/Article/details/gtrxonsljl.html

[R61] 磁盘占用
来源：http://dali.yonumen.top/Article/details/gtjuhtavat.html

df -h;  du -sh *
来源：http://dali.nwbrower.top/Article/details/gtclhkcxoe.html

[R62] 找最占空间的文件
来源：http://dali.cqqwz.cn/Article/details/gtzlzwftdy.html

du -ah . | sort -rh | head -10
来源：http://dali.zhixingplan.top/Article/details/gtxvungoao.html

[R63] 内存与进程
来源：http://dali.mhx1999.top/Article/details/gtxtzqeach.html

free -h;  ps aux | grep nginx
来源：http://dali.meibo888.top/Article/details/gthgvfdahc.html

[R64] 结束进程
来源：http://dali.meibo888.top/Article/details/gtcjhjspxi.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cheryme.top/Article/details/gtntqaylyb.html

[R65] 查看端口占用
来源：http://dali.xuetiantiany.cn/Article/details/gtptublosw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xuanzx.com/Article/details/gtxhlkecvm.html

[R66] 定时任务
来源：http://dali.smart0.xyz/Article/details/gtadrokzgi.html

crontab -e;  crontab -l
来源：http://dali.zhiwuduotai.top/Article/details/gtjzxqvkdh.html

[R67] 生成随机十六进制串
来源：http://dali.yj20258888.top/Article/details/gtyjhvajkv.html

openssl rand -hex 16
来源：http://dali.cucudq.cn/Article/details/gtfjeuehyk.html

[R68] 计算文件校验值
来源：http://dali.hywenlv.cn/Article/details/gtheiwxxzg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ehwqpu.com/Article/details/gtspwwlmtm.html

[R69] 生成随机密码
来源：http://dali.chenzaomai.com/Article/details/gtjehnwsrk.html

head -c 16 /dev/urandom | base64
来源：http://dali.daria6918.cn/Article/details/gtpzeahnkx.html

[R70] 时间戳与互转
来源：http://dali.dianchejie.cn/Article/details/gtnbjgradn.html

date +%s;  date -d @1700000000
来源：http://dali.vqdsnc.cn/Article/details/gtgsknebcm.html

[R71] 日期格式化
来源：http://dali.yongpay.top/Article/details/gtjswbekbz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.c1oappe.top/Article/details/gtzadqreep.html

[R72] 等待端口就绪
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrlmaanfm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.316326.xyz/Article/details/gtvpnlmznf.html

[R73] 分割大日志
来源：http://dali.jinghuilouyu.cn/Article/details/gtckeenzjq.html

split -l 1000 big.log part_
来源：http://dali.ydzc1.top/Article/details/gtsgiyauoy.html

[R74] 批量重命名
来源：http://dali.c1oappe.top/Article/details/gtiymhctue.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.svipenyu.cn/Article/details/gttkwyunlz.html

[R75] 导出环境变量
来源：http://dali.yuanzhike.top/Article/details/gtxclkimda.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jqgfzy.top/Article/details/gtbnqgdudd.html

[R76] 使用临时文件
来源：http://dali.ppjwa.cn/Article/details/gteaklfbwy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hywenlv.cn/Article/details/gtqvxmxoqi.html

[R77] 读取用户输入
来源：http://dali.jiagoushi.top/Article/details/gtfhccprrh.html

read -rp "请输入: " ans
来源：http://dali.meibo888.top/Article/details/gtrkzkquit.html

[R78] 交互式菜单
来源：http://dali.yj20258888.top/Article/details/gtmoabtsky.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.c1oappe.top/Article/details/gtjkslisfs.html

[R79] 解析命令行选项
来源：http://dali.ppjwa.cn/Article/details/gtqtwbyeri.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hfpthk.cn/Article/details/gtnpqriwij.html

[R80] 查看脚本执行耗时
来源：http://dali.chenjidiqi.icu/Article/details/gtkcmpnlpz.html

time ./run.sh
来源：http://dali.pycfn.com/Article/details/gtnjwkqasi.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtsbkanszm.html

S. C / C++ 专题
来源：http://dali.wangdashe.top/Article/details/gtlcmqohnp.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtlbuiublc.html

[S01] C：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtgyufqhvy.html

#include <stdio.h>
来源：http://dali.tian-w.cn/Article/details/gtybilvawd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yj20258888.top/Article/details/gtbtgnddgd.html

[S02] C：变量与格式化输出
来源：http://dali.chenzaomai.com/Article/details/gtrkbwcnqg.html

int a = 10; printf("%d\n", a);
来源：http://dali.daria6918.cn/Article/details/gtmyxcxzgj.html

[S03] C：读入整数
来源：http://dali.hysaishi.cn/Article/details/gtbfajmsjo.html

int x; scanf("%d", &x);
来源：http://dali.smart0.xyz/Article/details/gtdfpvvzmf.html

[S04] C：字符串复制
来源：http://dali.hywenlv.cn/Article/details/gtpjgecijm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ehwqpu.com/Article/details/gtuetgbwaj.html

[S05] C：字符串长度
来源：http://dali.daria6918.cn/Article/details/gtljszwzyi.html

strlen(s)
来源：http://dali.316326.xyz/Article/details/gtdzjojjnw.html

[S06] C：字符串比较
来源：http://dali.yj20258.top/Article/details/gtyaddhzpq.html

strcmp(a, b) == 0
来源：http://dali.feifeiyinyue.top/Article/details/gtijfqxxwa.html

[S07] C：数组遍历求和
来源：http://dali.316326.xyz/Article/details/gtlmmhbzuc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shuidangran.top/Article/details/gtorizgpnv.html

[S08] C：动态内存分配与释放
来源：http://dali.9152youxi.cn/Article/details/gtshykiyta.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yanxiufei.cn/Article/details/gtotpzhtmi.html

[S09] C：结构体定义与初始化
来源：http://dali.gotoacloud.top/Article/details/gtxkxumjbf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cucudq.cn/Article/details/gtfhwpodzc.html

[S10] C：指针与解引用
来源：http://dali.andypj.xyz/Article/details/gthvwlgwvn.html

int *p = &a;  *p = 5;
来源：http://dali.yvedp.cn/Article/details/gtylutwgin.html

[S11] C：逐行读文件
来源：http://dali.xuetiantiany.cn/Article/details/gtqyvhusmx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.0kj1m.cn/Article/details/gtbdvsnprt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cdnleiting.top/Article/details/gtgqaunpmn.html

fclose(f);
来源：http://dali.sweek.top/Article/details/gtrufyrbde.html

[S12] C：写文件
来源：http://dali.jqgfzy.top/Article/details/gtvesqcksk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ivvv.top/Article/details/gtunmnauys.html

[S13] C：宏定义
来源：http://dali.0kj1m.cn/Article/details/gtvwexvkkb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.daria6918.cn/Article/details/gtllusepzj.html

[S14] C：枚举
来源：http://dali.ywan-chungtsiang.top/Article/details/gtecvfucjs.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.quarkkingdee.top/Article/details/gtyxafqgzy.html

[S15] C：类型转换
来源：http://dali.jlsjyb.cn/Article/details/gtkbabveoz.html

(double) a / b
来源：http://dali.yuxming.cn/Article/details/gtnrlosywx.html

[S16] C：位操作置位
来源：http://dali.ydzc1.top/Article/details/gtqsbhbmmn.html

x |= (1 << 3);
来源：http://dali.hnxiangtu.top/Article/details/gtsyodtjsk.html

[S17] C：安全拼接字符串
来源：http://dali.c1oappe.top/Article/details/gtleapkgkl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhengqikj.top/Article/details/gtsdejshlv.html

[S18] C：命令行参数
来源：http://dali.cqqwz.cn/Article/details/gtkvjjyrtx.html

int main(int argc, char **argv)
来源：http://dali.quarkkingdee.top/Article/details/gtfinupjuc.html

[S19] C：快速排序
来源：http://dali.zycfv.cn/Article/details/gtbaafqanm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cdnleiting.top/Article/details/gtsaydagfq.html

[S20] C：二分查找
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwuxcqssf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.9152youxi.cn/Article/details/gtcevbhziv.html

[S21] C：字符类别判断
来源：http://dali.tanke756.top/Article/details/gtaoxpmkoq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hysaishi.cn/Article/details/gtmpwgxzzc.html

[S22] C：字符串转数字
来源：http://dali.shuidangran.top/Article/details/gtbfnxidnj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinqigufen.top/Article/details/gtbdxbcebe.html

[S23] C：随机数
来源：http://dali.gzhubu.top/Article/details/gtmqujicyj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shangyingyoupin.top/Article/details/gttawnhusq.html

[S24] C：获取本地时间
来源：http://dali.ivvv.top/Article/details/gtneojuhwg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.tian-w.cn/Article/details/gtsxkggnqz.html

[S25] C：内存拷贝
来源：http://dali.guowangkeji.top/Article/details/gtzajttwzd.html

memcpy(dst, src, n);
来源：http://dali.cqqwz.cn/Article/details/gtwosnficd.html

[S26] C：内存清零
来源：http://dali.gogol.net.cn/Article/details/gtycbfhfgl.html

memset(a, 0, sizeof a);
来源：http://dali.jinqigfzy.top/Article/details/gtivynwgfg.html

[S27] C：定义常量
来源：http://dali.cqqwz.cn/Article/details/gtbwgybdvc.html

const double PI = 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gtvnyhrkpa.html

[S28] C：静态变量
来源：http://dali.jlsjyb.cn/Article/details/gthdeocuqp.html

static int counter = 0;
来源：http://dali.fzhhl.top/Article/details/gtseywnvtm.html

[S29] C：变参函数
来源：http://dali.smart0.xyz/Article/details/gtgvfjgdwn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.redwolf501.top/Article/details/gtpihqjmor.html

[S30] C：头文件保护
来源：http://dali.jianghu66.top/Article/details/gtaanlnryf.html

#ifndef X_H
来源：http://dali.guannengcc.top/Article/details/gtimvckviq.html

#define X_H
来源：http://dali.jiagoushi.top/Article/details/gtsbkbqcha.html

#endif
来源：http://dali.shuidangran.top/Article/details/gtadqlmixk.html

[S31] C++：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtnkpppxks.html

#include <iostream>
来源：http://dali.nanxuanxn.top/Article/details/gtsibtxmng.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.redwolf501.top/Article/details/gtccckjxah.html

[S32] C++：字符串
来源：http://dali.yonumen.top/Article/details/gtsemrjdkx.html

std::string s = "hi";  s += "!";
来源：http://dali.havefunace.top/Article/details/gtmyltbuul.html

[S33] C++：vector 增删
来源：http://dali.ydzc1.top/Article/details/gtaqftrkbi.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.fengsongda.top/Article/details/gtwjdqkcao.html

[S34] C++：遍历 vector
来源：http://dali.yongpay.top/Article/details/gtkwbaczoz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.fzhhl.top/Article/details/gtrecgdzyj.html

[S35] C++：map
来源：http://dali.aibaodan.cn/Article/details/gtfvnjtosw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aizwys.cn/Article/details/gttgbvzcto.html

[S36] C++：unordered_map
来源：http://dali.cashguo.top/Article/details/gtimztoalr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.dashuyun.cn/Article/details/gtbkpphkqy.html

[S37] C++：set
来源：http://dali.shzxlz.cn/Article/details/gtblsrzbnn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yj20258888.top/Article/details/gtyschowgv.html

[S38] C++：排序
来源：http://dali.hammf.cn/Article/details/gtocbbtqbt.html

std::sort(v.begin(), v.end());
来源：http://dali.yueranfly.top/Article/details/gtkndkxnjf.html

[S39] C++：自定义比较器排序
来源：http://dali.9152youxi.cn/Article/details/gtetheqqal.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.aizwys.cn/Article/details/gtvyoubmuw.html

[S40] C++：查找元素
来源：http://dali.jqgfzy.top/Article/details/gtwkadhqbc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.9152youxi.cn/Article/details/gtorzbbezl.html

[S41] C++：类与构造函数
来源：http://dali.jqgfzy.top/Article/details/gtprnbciqo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jyoumei.cn/Article/details/gtbzpxpjsl.html

[S42] C++：继承与虚函数
来源：http://dali.tianlin.xyz/Article/details/gtewdilxnk.html

class B : public Base { public: void f() override {} };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtokkhybzn.html

[S43] C++：智能指针
来源：http://dali.xuanzx.com/Article/details/gtagcapjgp.html

auto p = std::make_unique<int>(5);
来源：http://dali.cucudq.cn/Article/details/gtmdhbqshj.html

[S44] C++：引用传参
来源：http://dali.zhoulong.xyz/Article/details/gtvrfxierj.html

void inc(int &x) { ++x; }
来源：http://dali.zhiwuduotai.top/Article/details/gthjqasdew.html

[S45] C++：lambda
来源：http://dali.zhaomingkeji.xyz/Article/details/gtunkchcgi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sweek.top/Article/details/gtolnbkshd.html

[S46] C++：函数模板
来源：http://dali.cdnleiting.top/Article/details/gtoihnufuq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.meibo888.top/Article/details/gtwdkjfgfs.html

[S47] C++：结构化绑定遍历
来源：http://dali.chenzaomai.com/Article/details/gtdjcfqtru.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hysaishi.cn/Article/details/gtcptqlgpc.html

[S48] C++：逐行读文件
来源：http://dali.cucudq.cn/Article/details/gtrezyuzfk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.316326.xyz/Article/details/gtwzsxceby.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gttpqzggnm.html

[S49] C++：写文件
来源：http://dali.pycfn.com/Article/details/gtaumyfoep.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cucudq.cn/Article/details/gtsuwtbrqt.html

[S50] C++：格式化数字
来源：http://dali.jinghuilouyu.cn/Article/details/gtndzbxipy.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yj20258.top/Article/details/gtkpzbambp.html

[S51] C++：显式类型转换
来源：http://dali.quarkkingdee.top/Article/details/gtspdklmnt.html

static_cast<double>(a) / b
来源：http://dali.wangdashe.top/Article/details/gtbntlrbue.html

[S52] C++：const 与 noexcept
来源：http://dali.chenlongwang.top/Article/details/gtmbmfwdzn.html

int size() const noexcept { return n_; }
来源：http://dali.andypj.xyz/Article/details/gtegrffvlj.html

[S53] C++：移动语义
来源：http://dali.yj20258.top/Article/details/gtjuorfest.html

std::vector<int> w = std::move(v);
来源：http://dali.ehwqpu.com/Article/details/gtybnuiqqt.html

[S54] C++：异常处理
来源：http://dali.zhiwuduotai.top/Article/details/gtylunzila.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhoulong.xyz/Article/details/gtvraksmqa.html

[S55] C++：结构化绑定
来源：http://dali.svipenyu.cn/Article/details/gtxhbichyx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinqigfzy.top/Article/details/gtcwuhywwu.html

[S56] C++：optional
来源：http://dali.snrcjt.cn/Article/details/gtgtgkxxng.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hongshengwenyu.top/Article/details/gtljueacqo.html

[S57] C++：编译期常量
来源：http://dali.gaohongyu789.top/Article/details/gttlrnpump.html

constexpr int N = 10;
来源：http://dali.yvedp.cn/Article/details/gtmleyenkt.html

[S58] C++：命名空间
来源：http://dali.havefunace.top/Article/details/gtenvvdmuz.html

namespace ns { int f() { return 1; } }
来源：http://dali.yj20258.top/Article/details/gtqnpudsqs.html

[S59] C++：静态断言
来源：http://dali.pengpengdd.cyou/Article/details/gtuajsgfvi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jyoumei.cn/Article/details/gtzgcbhvru.html

[S60] C++：遍历并删除元素
来源：http://dali.sysykeji.top/Article/details/gtpwpsizyc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yuxming.cn/Article/details/gtbgsvckll.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtnhwofxxx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinqigufen.top/Article/details/gtdcvoxwci.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtaohithid.html

[T01] Kotlin：Hello World
来源：http://dali.iojbl.cn/Article/details/gtngndfxqn.html

println("Hello")
来源：http://dali.nanxuanxn.top/Article/details/gtsrfenyia.html

[T02] Kotlin：变量
来源：http://dali.jqgfzy.top/Article/details/gtbqtlmpnb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xziqi.cn/Article/details/gtrihnwuiq.html

[T03] Kotlin：字符串模板
来源：http://dali.zhoulong.xyz/Article/details/gtmuuizeoc.html

"值: $b"
来源：http://dali.zhiwuduotai.top/Article/details/gtzzmcndty.html

[T04] Kotlin：空安全
来源：http://dali.zdqjudy.top/Article/details/gtsefiwjop.html

val n: String? = null;  n?.length
来源：http://dali.snrcjt.cn/Article/details/gtrncvsmkn.html

[T05] Kotlin：when 表达式
来源：http://dali.sxryk.cn/Article/details/gttuxaihkq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jianghu66.top/Article/details/gtakewqmav.html

[T06] Kotlin：集合映射
来源：http://dali.chenlongwang.top/Article/details/gtpqmcbrzr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zycfv.cn/Article/details/gtwdokmgpl.html

[T07] Kotlin：集合过滤
来源：http://dali.aizwys.cn/Article/details/gtcktbgcmt.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gogol.net.cn/Article/details/gtboezuion.html

[T08] Kotlin：数据类
来源：http://dali.jinqigfzy.top/Article/details/gtevkxtwwm.html

data class User(val name: String, val age: Int)
来源：http://dali.yj202588.top/Article/details/gtxxkmtmvu.html

[T09] Kotlin：扩展函数
来源：http://dali.yvedp.cn/Article/details/gtelcknedr.html

fun String.exclaim() = this + "!"
来源：http://dali.bjfxy.top/Article/details/gttbmgdweo.html

[T10] Kotlin：默认参数
来源：http://dali.0kj1m.cn/Article/details/gtrzxmdwym.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.nanxinkj.top/Article/details/gtfkscbqwl.html

[T11] Kotlin：协程
来源：http://dali.hammf.cn/Article/details/gtfykvuwno.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ehwqpu.com/Article/details/gtirxkywrh.html

[T12] Kotlin：解构声明
来源：http://dali.fzhhl.top/Article/details/gtrkysjomj.html

val (a, b) = Pair(1, 2)
来源：http://dali.jlsjyb.cn/Article/details/gtbxkbzykf.html

[T13] Kotlin：只读 Map
来源：http://dali.andypj.xyz/Article/details/gtkouzticg.html

val m = mapOf("a" to 1)
来源：http://dali.haohaochexian.top/Article/details/gtdytmucgb.html

[T14] Kotlin：循环
来源：http://dali.zhoulong.xyz/Article/details/gtyjtfgvqf.html

for (i in 1..10) println(i)
来源：http://dali.aibaodan.cn/Article/details/gtczhesifo.html

[T15] Kotlin：接口
来源：http://dali.redwolf501.top/Article/details/gtxqxwueqq.html

interface Shape { fun area(): Double }
来源：http://dali.ydzc1.top/Article/details/gtjutwynfy.html

[T16] Swift：Hello World
来源：http://dali.cucudq.cn/Article/details/gttqshgtcr.html

print("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gtsanblgno.html

[T17] Swift：变量与常量
来源：http://dali.nwbrower.top/Article/details/gtesbqpzdo.html

var a = 1;  let b = 2
来源：http://dali.feifeiyinyue.top/Article/details/gtqrzxweun.html

[T18] Swift：字符串插值
来源：http://dali.meibo888.top/Article/details/gtmmdolxck.html

"值: \(b)"
来源：http://dali.havefunace.top/Article/details/gtbkmlsbky.html

[T19] Swift：可选绑定
来源：http://dali.cashguo.top/Article/details/gtntdrnxdt.html

if let n = opt { print(n) }
来源：http://dali.cucudq.cn/Article/details/gtjgenftdf.html

[T20] Swift：数组操作
来源：http://dali.smart0.xyz/Article/details/gtdberqcgo.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ehwqpu.com/Article/details/gtgmcuuvcj.html

[T21] Swift：遍历
来源：http://dali.svipenyu.cn/Article/details/gthncevmcp.html

for x in a { print(x) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gterfvnwbg.html

[T22] Swift：字典
来源：http://dali.havefunace.top/Article/details/gtrjjcujny.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.dianchejie.cn/Article/details/gtbdadslef.html

[T23] Swift：函数
来源：http://dali.gaohongyu789.top/Article/details/gtzmomkirn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhengqikj.top/Article/details/gtgzztzeaj.html

[T24] Swift：闭包
来源：http://dali.meibo888.top/Article/details/gtrtwragml.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yj20258888.top/Article/details/gtkinzrwfd.html

[T25] Swift：结构体
来源：http://dali.meibo888.top/Article/details/gtpshbknwv.html

struct P { var x: Int }
来源：http://dali.yangfankeji.com/Article/details/gtiyfltlwq.html

[T26] Swift：类与重写
来源：http://dali.shuidangran.top/Article/details/gtbyivwvuv.html

class A: Base { override func f() {} }
来源：http://dali.pycfn.com/Article/details/gtjfchayle.html

[T27] Swift：错误处理
来源：http://dali.chenzaomai.com/Article/details/gtzepuaosp.html

do { try f() } catch { print(error) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcakxwigk.html

[T28] Swift：枚举
来源：http://dali.ivvv.top/Article/details/gtgzleytjy.html

enum Color { case red, green }
来源：http://dali.daria6918.cn/Article/details/gtdkbmbdbp.html

[T29] Swift：guard 提前返回
来源：http://dali.guowangkeji.top/Article/details/gthhzowzbl.html

guard let x = opt else { return }
来源：http://dali.yangfankeji.com/Article/details/gtsaocsxkz.html

[T30] Swift：协议
来源：http://dali.dashuyun.cn/Article/details/gtelififvh.html

protocol Shape { func area() -> Double }
来源：http://dali.jinqigfzy.top/Article/details/gtkkigghkb.html

[T31] Lua：Hello World
来源：http://dali.havefunace.top/Article/details/gtmhlrdxch.html

print("Hello")
来源：http://dali.sxryk.cn/Article/details/gtfchdpvko.html

[T32] Lua：局部变量
来源：http://dali.hfpthk.cn/Article/details/gtfpukjgaa.html

local a = 1
来源：http://dali.jinqigufen.top/Article/details/gtjvglkqaa.html

[T33] Lua：表（数组）
来源：http://dali.c1oappe.top/Article/details/gtcwxoocuz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cheryme.top/Article/details/gtesydeqhn.html

[T34] Lua：遍历表
来源：http://dali.tanke756.top/Article/details/gtcswnoalp.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.sxryk.cn/Article/details/gtmkphwqhb.html

[T35] Lua：字典表
来源：http://dali.ppjwa.cn/Article/details/gtslftnvyf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.daria6918.cn/Article/details/gtwqfhjmis.html

[T36] Lua：函数
来源：http://dali.xziqi.cn/Article/details/gtkmcqhhts.html

function add(a, b) return a + b end
来源：http://dali.hnqzz.top/Article/details/gtnprlaoro.html

[T37] Lua：字符串拼接
来源：http://dali.zhoulong.xyz/Article/details/gtmxcdgqor.html

"a" .. "b"
来源：http://dali.shuidangran.top/Article/details/gtvknhjwsv.html

[T38] Lua：条件
来源：http://dali.hnxiangtu.top/Article/details/gtvxewprvk.html

if x > 0 then print("正") end
来源：http://dali.dashuyun.cn/Article/details/gtwnxajxlo.html

[T39] Lua：模式匹配
来源：http://dali.jianghu66.top/Article/details/gtgswlgymi.html

string.find(s, "%d+")
来源：http://dali.xziqi.cn/Article/details/gtatnsfxuk.html

[T40] Lua：元表
来源：http://dali.gzhubu.top/Article/details/gtfwmqkwgq.html

setmetatable({}, { __index = base })
来源：http://dali.yonumen.top/Article/details/gtihuzqroz.html


<!-- 参考信息 -->