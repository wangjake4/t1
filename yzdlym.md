代发 wailian999

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwjkssfm.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2uhxhczng.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2chzrfxsd.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2nyowdcrk.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2umzyxasx.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bgfyynsu.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2agaxdhgg.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmjxawm.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ztlwbekm.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxsnryz.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2grkoajnx.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzsqjfe.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wagetkuh.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2elqclrrm.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxwzmtz.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmtdula.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2fggwvrxw.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2wtgvhvzn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2reihkvmq.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ywdgdzdz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2njsppezt.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2wqwpvvyk.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ewuxvntf.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2iqyebhhi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2elcumimh.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2aqgxgkiq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkonyzg.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2enlrhixw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2wzijhapz.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2yyaqkkik.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2msmpsajh.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2leaqywss.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2culmxilx.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zhfdlbld.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2txejdcnm.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2lfscyalr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfufiyp.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2pieqxmri.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2rpspwpju.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2vtrayras.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2bdkxkruj.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bvunmrxs.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2nnaarldx.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2siyocrax.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2szpjditn.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2puuvdmvv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzybllc.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzlijjc.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlkwpvk.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2unuoommo.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2hbgplkxl.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2eawawzya.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2kouarioh.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2hnztnjrk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2myyulrse.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxqxilz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2gdhjkyfv.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2nkboeqgg.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2mzpnorwj.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrgglxh.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2rbuchutc.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ksghdxuu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ycucsurw.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2cwhpunfu.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2lrafcqdo.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2cyukuoac.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2cjpijrwo.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2iznnyhbo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2bddlbsbe.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2zvemexgx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hfdsxajh.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ewguzjkh.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2vraqfmkr.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2wxptoqxk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tixihxqf.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2axinbzub.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2qqcaatod.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvhuwnf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2mifgdvtq.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2rdbtjoow.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2aymcdfpf.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwgjsjv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kpdnszdd.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2xreftgse.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vrgvrdjz.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ogkhxxuk.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2fmnyrmfq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ftvmbhdz.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhelqzx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhdnusg.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2svcefhmj.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2abmuwqsb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ditiizap.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2qseoztjy.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmkglox.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ccgkumrf.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvmhons.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2omamjjsa.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2hnpllxod.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bpkdsiiz.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxywhqwq.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2leelkkio.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xibzexoq.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2calrgpss.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2gtusauue.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ksoodwqh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqqhyuc.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2tsudtmnp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2jopxzjty.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2vfkzeyqd.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbozccgz.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gnreztlc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2ymlryfml.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2weyjsjbn.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2wucxcdvt.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kuatuwxq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbjjploc.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2voyfkgyn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtkuucy.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hehvbwvm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqeqtlg.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gvayxteb.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2owwghfnu.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2achomqrc.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2huzqwxks.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvopikn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkfzhsxe.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hhtikdbe.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqpathk.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mgoooyln.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxievokt.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2eahfsncw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2sebpbdya.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gjreqftv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2yndeaqrn.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2digkrhtp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjbralzj.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqbcpfj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2yijiiibj.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2qxoknars.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2vylcfwqj.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2orbfzlgb.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlfqqogn.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2wwzvrhon.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rpkctmbx.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2awhkjqat.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwixpbpm.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bznahzoe.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqgyttfz.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vnixaqjw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2byltvaxq.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2rkbrkmjb.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ovugyhna.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2bioflwwb.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2fuefxpwt.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrfmlho.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxsedcq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdownyri.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gcngisqs.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2oacpjbck.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2grmcprvu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2abgfjghb.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjxclze.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxykskua.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2skvoyjas.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fntahibz.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2cicuhcyc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdlejiy.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2oivafkhw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsgbklqp.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fdgximxi.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2rzloikiv.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2akkemxps.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2pdewxwbf.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2acngrnnf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2eliitwcl.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wiponupz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mhgrzfcf.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2crtvzpij.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtisayk.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2vzsqwuev.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2owdtfobt.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2afncafxt.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhahsops.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2tbojlirl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tdbytxeo.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xzwcoisg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2okngoagr.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lxurigsi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbyoewlg.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfewarr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2dztantvn.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2extmbafb.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxvdnxe.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2llhayiks.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qivekxys.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2enaotqgr.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nktkunkg.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmycmhk.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2vccboeqn.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzcoaqpy.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfobhew.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2svytmrlg.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bezajcrg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfwzigxr.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbyunvu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lozskfee.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2zxfqpjob.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvlbtlx.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2aajbmhfq.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzoegzlb.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqiwogp.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wadxtneu.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2pskhbsit.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2rubbjqda.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvferve.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2cvwfkxpv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gmirvpsp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2crjgpbac.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmtquim.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mlawllgv.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbbjqsd.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fkkvubyz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2rnobpezc.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ommpmzzu.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvyyamx.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2rkppqgsh.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kmnrspte.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvbmlja.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2kevteswg.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmlhyel.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpnotycd.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2klitbkyg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytobqwjw.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2lffsaqgf.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdanhfh.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmhwlrz.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhdmihu.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ryubevxr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2txupxgrz.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2pqqirpqm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzyusvp.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2hkpawqtz.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtovaek.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2telcslrv.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgemlfgo.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxzbjqm.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnufshjq.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2siiimfck.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhibfvg.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pizwpwxh.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vazpjges.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hutdydfh.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cpegrfmr.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqbjuop.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2nelknyxd.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2hsorkufx.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcfdnqpm.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gydoedof.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmnlxxxh.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zbbxuqwe.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgmwpnx.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2goqnbsab.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wwqnnktd.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfaqigd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzkmjsic.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2bppfxtfc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfdydqis.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2lqvpbxlh.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjuuilae.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2chbaqjgf.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2marqundt.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkppkhj.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsavijmz.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nhyuswuu.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqpzmlgh.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2msvrjrtl.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwgumsnn.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2kpbrsfla.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjrtbpqa.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2acsnjshz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lsdhdrts.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ehafyxvu.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjcdzbs.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2zfzvqheq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2qdribexe.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2jfzepnyt.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2erdlcrap.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2apnniwns.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmjalww.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ukpelcdu.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2fiujdbdu.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2yyiwpluu.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hqivromm.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2geriwrzs.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbdviqc.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tlshnkor.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlcqsru.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2exdnxygr.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2hfssvoyp.html


<!-- 参考信息 -->