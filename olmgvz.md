代发 wailian999

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iblqbnhs.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2rgisebea.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2joiwfmro.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwpnxcf.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdiiymk.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qtugdmhy.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2fqsypurv.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2yfevtiyw.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2xligjkyo.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2nyeythtk.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjtotfl.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hulxfgfj.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wlpquraj.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2pbsskciz.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2gejjpgxd.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2cvadcexe.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2oqrrghbm.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2creoygfu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2pjewgacq.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ljieseqi.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nldchopp.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2zekwevdz.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mirrstau.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yqorcoxi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2xulmjmek.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zgdrbxtu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gjyuwkdn.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2eggmwuzy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2lzkbzzbt.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2trsbqtop.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sczkdxdo.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2aepbecdo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2beeftypq.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xctdfwkz.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wrinbhoc.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2dvllqgvl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2glmohjic.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kihuswlo.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbihedd.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2rrciawao.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2azjdboaz.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2izbxchra.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2bynlfmav.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2iavrbbzm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2fqlplgos.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mubpnhqz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2voxamohw.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmvgzzw.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2hxqkmyys.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2riuttrax.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqxngfp.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2izilybuk.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2iqrjuocj.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2mskrfgyh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2avsjzord.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2zejqqmqz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2riimvieh.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vptnzqvp.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2usmqqwig.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2wabanlpv.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrjiqbf.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2tnliiigp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cxlywnaw.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2nllewlhs.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2njhfzgbb.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2pqpumoez.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2gboeqpep.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxqrzii.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ghqzxdoo.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2kuaxywjp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gmzwbmes.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwwhzri.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2nvycjdxn.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpaavap.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oxuegddj.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dcnkuvcc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2sinqtgey.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zktyovqt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvdppej.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxhtxtk.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2deoxtwfy.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbgeeqi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2awpawlvn.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2rhmfkhzm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqxvwuu.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2cuancwmq.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2tiqwxfug.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2msymxbmr.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2rosyyqse.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zulmljsk.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xzipwldn.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxnahco.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwptsxid.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jhobdfyg.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgnmzzcf.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2cawvqlsj.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlzywohk.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2czvanmys.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2vhheqziw.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ylntiiip.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpmmpkdl.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yyffmlsz.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ydyxrisv.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xncmjzwv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2fizzcawo.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2dqpqucnl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbrfcvsz.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ouegmkdc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2rjeqqztg.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2yicdaikr.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbolzqy.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zonkvfhv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2qyrjpmor.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2aemoaebz.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2mruucxzf.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2amoxnwix.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfuahqop.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kupfqzbk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2wuxmztey.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2quxldumx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2elxkmdfx.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvkfwci.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2izbtreye.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdnugdg.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2blujclzn.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ijwkeqwm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2viemixkt.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lnuukzes.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2azyycvep.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uuxmgsli.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2djmjjvaz.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqiqpng.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2msasfkmw.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2pxdegoxt.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxakoeid.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2mxncdudv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2simajigd.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2muijjilv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgicxjsc.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2mewbhoxe.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2anayelyc.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2oemtljun.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewuaalrj.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2kmtefxoj.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xttmfarm.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ipoutmif.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2elgroxin.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lqiiplsi.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2drqobvax.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rygksrpp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngiunvdr.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2kcltsikc.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfsumea.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjwifsb.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2dfbqujfm.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kozfchfr.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2oxiuhfbl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2obsnkhql.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uokoaczh.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2puxkxzpl.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ubogggav.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwwqihis.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2rhujdbrh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayknnpcw.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2umxzibtd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgayzzqb.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2zoyxcuew.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dohbidic.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2hzqhirkr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vklbdsqg.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2spbxeyzp.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wmpttusn.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2szqgdjoy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2gpfezuer.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nmebvpaf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjayonse.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrwwgks.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qzuubbni.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2amtiohwb.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ldileeek.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2dmlgsasi.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwmwqxu.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2flvitzuv.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2clezlssk.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2lnpzgpwx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2raxudtvf.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2snacbdlq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqwvncml.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bekhekke.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzeuyoel.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tidvssbe.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ousukroe.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwuonkft.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2utktkzkx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2pisyufqt.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2nvcnxmlj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2uogwggug.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2afpwzpul.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2tajzmmmz.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2kwvmpyqv.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqgnslj.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2srtufvnv.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxpicrns.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yszpuqvt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nuuwxtze.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2nxsjjuey.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhkozrgz.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2srjrlmwr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcuztdwh.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2amkoeujl.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsaymdzo.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2rhiwbxhg.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxryjmh.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wjfazryk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2reguvdrf.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cubtlayf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmpkere.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvjhpsl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2gksnlkxo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2atplsvlt.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rzuvumaw.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2eoloxkce.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kvnykdba.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxyxzad.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ifnfesnc.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ehonsvje.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2bddxpgln.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ukmkzzxm.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wtcjgrvh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2uicdvwez.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2fzibvejt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nanuljhq.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tdhogrbn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gckslwju.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2morzaglz.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2upenqdap.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjkcfci.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2pwbmguqv.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vovvxclu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxddxdu.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ooftccky.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxrjkcb.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhhxxzb.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwwdowhk.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2aayjcdnv.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwwhuoym.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gnlpgcdy.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmrpgjhz.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2uxztzltm.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2chwkznsx.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xriaddbh.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwsymnbt.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xlguxugq.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hizcmkyh.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2otaamxjq.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2zdgglhvv.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2zfsrtmcv.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gocmynfk.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nfheogdm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqkuzcno.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvyuvwt.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylisecbr.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kgznpafz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wqowzozm.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2itqagvip.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxdwwez.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2npscosdb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzosnriv.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2eibalhym.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmmpoyxa.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2rikihzbw.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwbfylfh.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dumfrvbf.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwybxmjl.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqanmyf.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2dclfdbim.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2esixbmor.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyuwhgbm.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ymcfxajp.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2amsdjjod.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uvxxyjev.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qfnbmchp.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bjexkaav.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2viwppcuj.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2zgsroqzj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2xjuyfxxj.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2foykmriv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2imamomne.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2luyktkxw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wqnwnkeh.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xdzabkml.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2lgutmvqm.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2odqadxpa.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjsjzgz.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2elhueoob.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2xtxsgteh.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vjexlwro.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvpefmb.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2jgyjxerz.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2osivxkwu.html


<!-- 参考信息 -->