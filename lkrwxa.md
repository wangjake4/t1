代发 wailian999

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2rantfpil.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmjyczl.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ngeorzqc.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2myjrvzaj.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnrhvnc.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqybfhb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvbkoxt.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvtmqte.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2slhcvyrq.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2wjzxorca.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lzfanayh.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ewumxprz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ejsopjvq.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvdwmyp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2izfywvgs.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqytpmw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2udbvzicz.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2kugmrpaa.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nlfwhknv.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2umovwkbs.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2djnvesbv.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jqttqvlk.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2khmacjvs.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2kavqhhjb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2hzsyasnp.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2iycxpjgz.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ucitoswz.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2jsmeesxv.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2abnshdpl.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uysvtwrs.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmeugur.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jyqgykcx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzlxrct.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2yvgjhuny.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2hyciijcr.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkwxxuv.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ipcuytcb.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jjeuerlh.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2wocwhruu.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2hudzhkdt.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2nldrjflh.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2oupkjglr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2lebyvvxk.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ezjdrrbo.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2nleqowym.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjaasxb.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2scngwbck.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxegbsb.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2dneafgnb.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2kblrvgzu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ejofnlfi.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2czlfovqp.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2vidogxjq.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2yewzasuu.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2pqkjsxtw.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wnviefbh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2aitmfkkj.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2aiurkdmd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eodowfdy.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvtjsxc.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2yegzfabt.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2irpxnkzw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jguhdhqb.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qngttbkm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ihulnflq.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hexbwvjx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2iffmfyii.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2fphbgxda.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ahcbblxk.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2qbsdlldl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2krlrboar.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2xctjmkab.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kkbplznv.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2qfspozrp.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2yqlapzbz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tbxswous.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwwsape.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qmyqwzkq.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ososmdoe.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ikkknwvb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2livmcguh.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2zjpgveiu.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2svzlgddv.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2qoqtvktt.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbtxhiza.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2xgquyisz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2zqkavjiy.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrpgweb.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrwjklyx.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxfphjp.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2exbjiinx.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nqutjjch.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2kzritzei.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2qsumbngg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzowlnin.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2inxcntwz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2cwhtmyhm.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2fkrzfgdd.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqqrybae.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vanehoak.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2rlaucrhn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2luggirsu.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2acfuihdj.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hlpzrzby.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkjdmori.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qotplrfn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2gxblwtjv.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwusmqi.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2jmklmxvl.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgfsezg.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hutppjwi.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2dkyrmfqh.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofviuttm.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vatoltyr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2qpiiaqey.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lfqtucyf.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2zowjzvhl.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2prkdribv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2jasukzrf.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2blegcwns.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2phhpqdwo.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ofbhsbgp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2xyslikaz.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2adzsxgaf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrgizml.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjhfiii.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2oivfcuzn.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ydeslfna.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtimqwvc.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2whtgenvf.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhwlmiqp.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ubiixrnf.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmzjzqt.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2utcvwalk.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lslpllbw.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2egxkkhrm.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2elohvicg.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2phrgpwwf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2grvkjous.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2wmeoriho.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2wjuxeojn.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmamhps.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2dirduvlq.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fctohkpb.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2rglqedgh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbbbptsi.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hmzkbihy.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmqtpuy.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2zpabgwjg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2judhhevz.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2htdajocv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2olebcgwx.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2bdwaoidz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnyvmbiz.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2mdchhtbq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzpdmdqq.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2yzgeduyp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwiqpgzt.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2umjrrtri.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2iyyctykz.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vyrbmeha.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2tbcnsxbn.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2loiildzh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwzsgfy.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2doppodla.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2elintdog.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vvpriwmw.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2osfgtaln.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2uullieyq.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2bemvttth.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2kcrowzmh.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvobvazw.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhapwuo.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lqvbdfqa.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvvlaoy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqzcrhph.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uoebslmz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wznbmtjd.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2opsimzli.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhwnlxhh.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jaraifsp.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2shfwlqie.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2jfkgsfpe.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rowribak.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxrxwaw.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbrosnl.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2wrsyqlwm.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2oiqoyrtv.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtotajru.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqjosqc.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrqlxyc.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ylfskhlf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzpavez.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2fqzxdluo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbardmk.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2odhrryse.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwysfxpa.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2gidhnxfe.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbijpkt.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2mdasgpwj.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ruqthqwz.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwytnmz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2woungssr.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxupfrz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2loalxmiz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iufiyqay.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2dvgahage.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ritllcme.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2okhnqqml.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jfdxnerg.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kkdfvuby.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbljvmz.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2doznybme.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jkbkbjgn.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2eaeevetx.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zwekblqb.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rplazlpq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2qdwkjsyg.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ukpaigbi.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofaaywfq.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wiausbzy.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gulymlwe.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmyhipn.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2clsdekom.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2opiukrbh.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2cdvqinjl.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mqhnzdsx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkbathk.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdajecg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqcvotdo.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2iwnambyb.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyknqmwh.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrgftgs.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2askbisvm.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pxsivgkm.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvhlzyn.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2qbetuctb.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvcqpmhp.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pogyiqqe.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cxyxbmmg.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2agpaycyu.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqwitqh.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2horgqmok.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ydhjxzpr.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2wktbmpir.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmiblck.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxzwiro.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsgaihis.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqjmdww.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xihlcscq.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtmxvsp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rmponfrz.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbexcie.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cycyhjzz.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2kejdpuyw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2joayjcsp.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2zjkxkoyz.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2aeinhzlx.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2qgeljzke.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2atkorfzn.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2omwwvrvt.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpredtr.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2oonekctk.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhgjnvyd.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2htwxztbq.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqzugjyw.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2bisatkln.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2poupnktr.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gjesypnh.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lyoaggxj.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjgrzur.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pqjczawf.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmqvibf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2pilardbb.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2zorxcofh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2dvchkdpa.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2vcfiqeeg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gvyawdas.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ghlpfgwk.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2kssajcvf.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2jgpmnmgs.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2innbqwfa.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gtitfsph.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2xcrorvks.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dltjrbnj.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxgljwy.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2aqcrjwci.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ghnoytzv.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2epsgoqnz.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2hdytfrsu.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbdgcpg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztaupvgy.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zmeihehz.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2nikztvot.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pquatvsp.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2veewczbp.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2acsznzra.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwezvla.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqbywbn.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwzoanl.html


<!-- 参考信息 -->