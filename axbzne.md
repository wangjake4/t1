代发 wailian999

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2nkobnjdb.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xfvtjhyr.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2zlqstily.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ykamlxnw.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2vwnzvcjd.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2vwtmyzxf.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kacpmhlm.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqnglta.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2cyqvxkxp.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2mhdqxmyc.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2unchtred.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qvlzqiks.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvikxjg.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ywrrzvjd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2pmukiiao.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zzutfseo.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jczxcqjt.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2unbleoym.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wynqqcvu.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwsmipm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrbysqq.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zkedkpzt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tquzwmac.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2takzvpcc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwdqfie.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2fiicoopz.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qdlpwsef.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2qojvstih.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2zeivdlby.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tlnkhxzu.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zkepfdwg.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2bmpitcop.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2oiyhrxvx.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zdklyfec.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2likcdqec.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2everprpu.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwuiygp.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ikoumjah.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2sygnwwwu.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2oxwyxxqo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxdakju.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2pxnusqcc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2wuufqhfa.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vonzrwav.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2lvdtatyh.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qqgvcijf.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ivkvrobm.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2cmendlkw.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2razuqxec.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2dyeknxzb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyfplxnb.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2sczsqqpq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2qzovfhue.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtgmlwd.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2fkuhpogt.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2xiebquyw.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2zoktfvpt.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2vgcxmtbh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwcelrg.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ifnokmlr.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmcidhs.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ruajgajs.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2rtzkbams.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2sfctnadw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2etclsepe.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2xkafxigk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cfuneajn.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ayuwcwxd.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2msutdzml.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmymhsx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jxcchccm.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vjkagtek.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2wgrqindj.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qtpsqsai.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2agmwwaah.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2gqkwnycr.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxqznna.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2cskbnloo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tpyrfuxf.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2fwgecgas.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lbzizrft.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2wkfgldxd.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ucuzzvhj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzckzbl.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtlysoz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rtndhaqq.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjhihrm.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2lidrhdod.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjxuqut.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmjaplq.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2crxjywhd.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2sghpftiw.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwwxyaz.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2wfkqzlqr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2fijonxtt.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uxloiwnq.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2czdccfpu.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqxwpht.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2smzzcxgt.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2lmbtjymb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrcpzif.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2nhiatdtg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxmgfctw.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2zryzhnzz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2jomhygdv.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2mwxpnohb.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxhennc.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jztxxdea.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhstxdf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzzlzdvs.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvvzuxa.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nejbdjai.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2migwhazw.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bmvabeyq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ermuvcok.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwtsrxw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ooeistus.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qecadoup.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vvfdgjii.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2zjeumerd.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvwytis.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2itzfldky.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojefshpr.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wniuahyj.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzhyksso.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mssyoifz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2eudwtozs.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2chmjoeoj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxabtld.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yksdhzou.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjypghgm.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2sfvkcuhl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwibnum.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2blcrfvej.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2hujezurc.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhynosw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxknlds.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2mvggweri.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgtsmsyv.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2hhruiapt.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2idtrssre.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fkarxzhc.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2odmnaslb.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2emxjhooy.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhgvauug.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtdrbpe.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbzisjsd.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2drxtjquk.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2kljhmabg.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2baxkzckq.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2dcsiwmmp.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtthczv.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2mrcxqgpm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbegrpqz.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gggjacgb.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2iactpmxd.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxsmnta.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2eplbhyzj.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2randwunh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlmflmz.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2anguiojg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sozolafy.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrmklni.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wthvivng.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ikptuusc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpoyorld.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2psfjxrbj.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qxoizluc.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2aznrfbqb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2sebohyfx.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2llmmvsse.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2grahbqex.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iqbqwnhn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wngcmymt.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwcpbzu.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2rinqtgpk.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2clenxovq.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfnmokvh.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2slwjdtzw.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqyarbxw.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbsvowu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmjielu.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2kkcpjmcj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2evawrjtn.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mcxrprvc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpwnxxfb.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2itmpmbcw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2iunvqxbr.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdhcyvrx.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nmcrprej.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2rrrjcadt.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxnoztm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgoeovo.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2btnnsumj.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcmlovv.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2kmsbelul.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbowcrna.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2bryllzmm.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhwbplv.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vvynxdsd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwcemuxr.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2drkdfyfb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xggfuugx.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ygssdrii.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjftwua.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mdddlflz.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkfmejdi.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2thvnmpxq.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgdvmjae.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2brgvjxle.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2huyvdqni.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ndggdkxt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2smunwjoz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rgtxedhj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2fisiyica.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wlksmazv.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yqcxchrz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbiuosb.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqpgqpm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2urrndycz.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ykswombo.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2karwmubu.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrhdekx.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mpzyqmir.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2iwurymkr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2hsacjapn.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2hfabmvlz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ushoecew.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dnpcqkhy.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngiacgcf.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2hfzflawp.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwzjahgy.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfmngrr.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqnkzgz.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zgasbjcj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2pqrqfgey.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2vlyiwgkm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbzlenm.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2zuakaojd.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2okfqtbnq.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2stbvcbue.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlerfods.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cirnruwv.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2nllbftcr.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2alkuhgzy.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifmljlnl.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxovtxb.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2grbndwwy.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mgpylvil.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ykfnpvef.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xbagddxz.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2vpnavuma.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2iafkuvay.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2furxjufv.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ziqinzva.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rilcyivl.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fyyjpylk.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqnfvkw.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2difotrmz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwzodku.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvesoqh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2enbodacf.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkovwwo.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2alqmsyjf.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2dufclibc.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqjsfat.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2wpfxjdoi.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnicfwi.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbeoztv.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rouluois.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vpcubcvt.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2wagebzhe.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2hdafhumy.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2egqxkppo.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2tqnvyatp.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtyspsul.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rhrxwbpz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mdssvvnl.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzthfcu.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2badbqney.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxetakt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2acpvuzqi.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2cjgpnpel.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2mniwexto.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjnmrtx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jagphnsm.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dmitqbbu.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2uhumsfzy.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2wdwgcior.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dgrregow.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2aftomnak.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2gwjoglmb.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ebsqfegt.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2iqeyogim.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2jyxatzxt.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2xqyglzmw.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ifpfmjtb.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvfwobm.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2aqglaomh.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2uoholmpv.html


<!-- 参考信息 -->