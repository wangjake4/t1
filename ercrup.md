代发 wailian999

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2hmyhctka.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpvbqfu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2pyqvammr.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrlycgj.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzulaqxi.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwqoqzm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhzpkjs.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2bkpkcvfl.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2vezlpqqg.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvonvix.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2equvkxzu.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2riyjghxp.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2mooitrvn.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ceuteqoj.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnvkhnw.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2juvcywkc.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgwsqnw.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwxxsrx.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wlizhpih.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2comwsbkp.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2fkuoghlo.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtojucw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2rawlgquz.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqdsibw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2swzudtjs.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmspvaj.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bfccfrch.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2slarcnls.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2wroghxln.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2oacpzlby.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fwcbcszm.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2gnbpzkof.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2qgcwduut.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ijwgpwqt.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kcktskcc.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2prweyugg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqobcyw.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2snxpazrs.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2epomdzam.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2auvaruny.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2wydzxipn.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xkruggvn.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhdflge.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2qzmkoyto.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2gnbubhsc.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmhbzmh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2wfmmrsif.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2iuqervsw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2exfdgtsk.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2uojmpdkk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2rtddbfsh.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrnwyrt.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2uuuxxhjv.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jszddhko.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2zcutxbtz.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2sxtzrkck.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2sapbgxug.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2xguyhovp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmnwjiqn.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2lxihklvb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2aonzgjrn.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwjrycq.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2szvzvycz.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2kffuxdxp.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2swesowzm.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2devtifxb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhwvgtz.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2enujbvdj.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2xrekcgme.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2kaauwowt.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2iadfttfe.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gtkpntrs.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2pdlyggqf.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2wujvnedq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ghbfgski.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rtxmqdbk.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2zjpypdme.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2wwnyctlm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eaqlkyur.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cfmnejef.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2xvqmdvub.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jeghmgii.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbhepzt.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ldnhyobe.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfadezd.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfvcnpv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfbdjiy.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjvfzuh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rsecwvyc.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2tyhqczia.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2cyvxtqsq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qnvqaqlw.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2sppdgyfs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2stuowwaj.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cxbeowyv.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2gvopqowa.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2astwcezi.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2dluqhhzd.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqxcptm.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxyxfvp.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2uturafjv.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2zqpebuhb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2fwrajaoo.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vskrdjnn.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgvrwhqy.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yachbicb.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2fecttvqb.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xapjapvb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2jxykbzsg.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2znmxkilv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2xiepjwzq.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnvjwkg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2crlbvkta.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2hxcxrele.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2oliaokjo.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqqigyb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2alddoyyp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2echrlvfv.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvasrfkx.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2reevfmna.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpzhshkh.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2aazpcuyq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2xojepfpc.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pjsbayaz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2cmtnfrml.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pmetxjnn.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2tddczjyi.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2jjozbqin.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtubwjc.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2snpslbov.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2etygfwra.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qefpnuap.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocrkribw.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2adubpbwt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgppgbdx.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjyppvc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2epspugky.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mystogox.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjpsrxt.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqomory.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwqgnnv.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2osghgoss.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2eurvxfiy.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2jrksklir.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmzhdpn.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2yjkfypqj.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvlbcnq.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2btqadgwu.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmzaslpn.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nloevplg.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ziquhjef.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnlltkp.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqgyite.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qjlucbyn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxotugv.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2mifnapvj.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2hkshstay.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxznlvl.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2qudboiqe.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xmnvldrj.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2tmefgwvf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iluhltxx.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwnbhbp.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2olxfxtqw.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2cgwcwwfo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycjiscks.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2rfyjdcib.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nutfglup.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2tffdruhb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmcicpsl.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2olwybwvd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhebkdgh.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2oijraqpo.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wijhmkdg.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vsmxowys.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfmvrob.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrvfebg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2sesfyrnd.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2riiwccoy.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2axpyoyey.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gmcimiye.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ldgoxhzi.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dzesjbhk.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2fuevcsah.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2gyydoboh.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjdiegu.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2lrsajcde.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lddtqoua.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ycankbrk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pgrjojxu.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2jynmnpmx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdkdoge.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ieiblrrf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2halaycag.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2krcleclc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxqfhvid.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2csokoris.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjisdnu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2czspcyqv.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2uwbhvzpp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbkniyo.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vocyfrlg.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ioskjjsy.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2crsxlsij.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2awlpxghv.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2jfthfgda.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppsyezpz.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kzoxzqmz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmogkzt.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2prqkrgyw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrlzhgqn.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2dxheamfb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddklwbbp.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nadkdimu.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2aymmkgej.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2yzbphelw.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkrznqwy.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qnleairh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2wivchzpc.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2meoetoaa.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2oumhjbuz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2otydwrbh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmpziqj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2acedafac.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wuuvnzja.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ktivplav.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bylvlimg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqkrmit.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2sxnftrda.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2edyafhnr.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2uxwyjqyy.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vcuvehvx.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rfgctpxy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2bpgthheb.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2knhdcbbh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hflafoht.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdtenxd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkxqwtw.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2vsvwsspi.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zewujzma.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vdihieap.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjusuov.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2asryroac.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ubehhaxy.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2itpsdeho.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2mctwptmy.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2jbicwdfn.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebihtvqs.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2idhrlymt.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kaguvuls.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvtmltm.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvicqqm.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2aakvxdpc.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzbcabr.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2moaukycc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2aqqdeffo.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2cosgxjjg.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uqaafuql.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2svkzklvp.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2uxrxkxrw.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2kgistpnf.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2luwzziai.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzlfezv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2asdworhf.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tabfsybx.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkokwzxk.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2uvxdqkct.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2irsraiof.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pfpsnzth.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxnqthu.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2etalskzf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqwdsehd.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ucioqfwv.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2oeqldgkj.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkhofeh.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zermkeix.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hyemfsyk.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pklhdfsc.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2perewjjg.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbclpofa.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2gfssyycn.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxgepcj.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2wwtzszhy.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkunlzql.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gqzsnmxc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xqfoutnm.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cvgmfvwv.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2idyaxfif.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2illrwzym.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2funqealx.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2pisflqpv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2jsndzdvw.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2qkziuveg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2usfkdvzh.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfppkbd.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2xudvxqvp.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2xweupukp.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lezncpsf.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kswazyyt.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2rfcdvuko.html


<!-- 参考信息 -->