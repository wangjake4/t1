代发 wailian999

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2lcpenmye.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2scmtvgge.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2viqauwpz.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwiaowg.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yynkvtav.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2xpzcbhix.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2sksgjftm.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2errdhhvx.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2tfwslyjx.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yacxbnuo.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ykuzxqqh.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2okejpjfj.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdatvde.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2byhepakp.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fonozont.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pzsvmiiu.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2gnzqqeiq.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2swyjoubi.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2chcspcdu.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2afrlewax.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2fczmuado.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2lwbchtxa.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ktcrsihx.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrmojcc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bftmqddj.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2jffrmyba.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rfprcyei.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nfafghmw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ughzuefr.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2dvnjxtda.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdguyck.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2sydehjtp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2frrvabst.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2yfiazxnu.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nsffnylo.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2yavdgtpq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrbqylz.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jingohej.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bvarichz.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2pojboarl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjkuxse.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2azznwpvi.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2nznexjii.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2aqgubuar.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2eaahfysp.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gbxakxlv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2jnksihsb.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2wdeljzif.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2nkusqzfh.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2fjlvarwt.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2usdxjolh.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2nicmtszx.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ntrijspw.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ozopqker.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqsohdk.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2airvljvl.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2svxsnuvw.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxwkafb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmwzrwrt.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzqrsra.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2qlcdfmhv.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2alrvttvw.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxzggco.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqeirvu.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2kciurudz.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2nohbfxll.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vlroeitq.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxhcmzv.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2dqnifljj.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2shvfegfv.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2xdfbyidn.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2utxvsdoi.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2wpcvjvlw.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdhjjzs.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rvpkwjmq.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zbpevzep.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2zvquahty.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2kjrrqnzy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2luzxgeme.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2prmineoh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgcbkss.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gvphjobs.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ezilwnos.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ujffogyf.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmfkpyn.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2pzleyubf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xnvjcpoy.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2hljvvufa.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmwokbu.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2vtfwsrnm.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2syjsuoqe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jliphiuy.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2bxukgylw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvyhnvw.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqskikd.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2neozplmg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwgepswl.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2yquapuzh.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgfybtru.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2fxnebnls.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2bymyvepe.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2tbrtjebk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ibtvibwo.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xgiajjgl.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpwfhwj.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jonouuss.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2muaybbfe.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qthxyxch.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtnlcbm.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2xcizomsi.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqamsimz.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2sldrlidd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2cusjfkik.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2kbayznif.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2derbgqeg.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrrijxf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqtrpjt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnzgvkn.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcyjldfu.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rykbdxqi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgpsbjkh.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkqxwcb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2blbxtwzo.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2maolluuo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2kljdqcbf.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qnvkbxhk.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwyihbd.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2wfzwktlt.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uigdutoo.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2svuqhkrs.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2egtvixxq.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pxnzjovs.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2yodsqhru.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fznrcfla.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2aehyvewe.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2takfzldq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2aidokqcp.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtbjrjk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2byysbfif.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hpsgfbul.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2falwwqvd.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdalyun.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2eushwigd.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vbewysin.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2enaishwu.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2oqphmskr.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2eailrggu.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2cnhvasik.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2gspjjyaa.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mfppittk.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdolzxgx.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mhxyqday.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrjpglwc.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wrlghzlq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2yoyjjvvw.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2rurxkimy.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbypiwl.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqvkniq.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2znnylyzq.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vtboxejh.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2hsyoiytb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxsystp.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmcwyko.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2eltalemu.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2yznxmelq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezvryopq.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqefqif.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eubihrbt.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2bxibzxjk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzlxtyiu.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ddmhyhqb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhiptbq.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ukojdxem.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqkaemg.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tgflpxqs.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2yokmkkej.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pclcbxik.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2furtwixb.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjqkpfa.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2aoortkvb.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lufxkvhj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nwbzuoqj.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2okyeispe.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2tmybmasa.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2vijoajsa.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjpilzxl.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2wvarmyqo.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2whdqcspt.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtjkuzl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqcmeag.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqvqgwt.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pagcgdcr.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zymonycz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aahiymdp.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ejybtolx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydvdjmrs.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvygijx.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lmymazho.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxmxmlh.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2cscydlco.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqpczdoh.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fzgmuhch.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dwepbrvz.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2vkytitop.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2luugpmpz.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2kkklagwg.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2diyfildt.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zztpqont.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwezbnl.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2menhteok.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnnulvix.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2wugsjhgi.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqxkgodu.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvcdard.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzklfujd.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvftsrr.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqsyzzk.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2assdwxak.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2xghfsggu.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qpasyhsv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhynqsx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrxmalw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2jxnizfmb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdezeat.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrvoddl.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhjnrxa.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bitnnmkh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2exuhspxj.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2muducjub.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkwkptn.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2mqbvbyyy.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yrxmcbzt.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xbjucagr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2jwyhttyg.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2iesigers.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbaqwdq.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2snzxefbl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdnrbrib.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2qhynvtsm.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhfksylo.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2krrqhzkq.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2scisayql.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zdoqztrj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2fvkceyxy.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2rfrdkbvm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwhnnkb.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2hranuslq.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjzotrhm.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2vycqpfek.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnfrzyuc.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kphupzyo.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqrflhbi.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2iiwcqjbn.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwenzslz.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ueypykgj.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvyvlmbl.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fssbgcos.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqemyvk.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lnzceuau.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwcexde.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvwmxok.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgbznfk.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lekcdbcs.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2drsmozpv.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bpgvvdzu.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2unldzhac.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkklgoq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ozrzuouy.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qbcjvemg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnmeovti.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2izxesazb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2iegontod.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2xyzunsxp.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtbvsmk.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2smdpcucu.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpeawzzf.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ffpzftpm.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2htbufymi.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ibcjwcnj.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2opasvwvk.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2jlalgdpi.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2umtihhrw.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvzrtfo.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvtoajc.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jwidhnia.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2csmixlav.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ejgnyurb.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2onvudbrj.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2vbzlwhdd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2fazgkvgx.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ifnzrsir.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ebrzapyo.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2hznuozge.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uthutnmm.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ojthdpkw.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2ezqijxzm.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2mvffnfhz.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kcumplln.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ytgjsols.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2yncrvybj.html


<!-- 参考信息 -->