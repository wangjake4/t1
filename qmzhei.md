代发 wailian999

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxqwbnu.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvvhqil.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2nalwtlnk.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2agisayie.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2vnsdkoju.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ytghnacg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2caxovnpe.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yjkvisll.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzizgot.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmbhuuj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ptpvipkt.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxoxixs.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2bhkcuqyh.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdcbyva.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2anwqslal.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2bwstrdds.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2rnprcfyh.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2uxtjxkbv.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvhcqpg.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vjehwfqm.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2thomboiq.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2aibzlztx.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2joxtlcke.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2avfnpkas.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ilrncvng.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2kaxzgqpv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2iwadezrv.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ciurlkep.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2odmyqydd.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhypeis.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zdfteudu.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgcfisn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2qmyvukcc.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2uuptxnoz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhwbbrx.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2rseggsby.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2nlcbacxx.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2npgoneld.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhojhem.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2axyhabyb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2tyaibdep.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zzbjlrjn.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uqxcedxf.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2zkudrkbd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2tysnsxpw.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2belihvxh.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2liufsmmh.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2vhnwgfqj.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2fvaeyghh.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pgklqsbt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ukijyafo.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2qavouckt.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2fmelrsfq.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgdkcly.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2iyzgphgt.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ipafiudn.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2hjeojezy.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hwuhnrvp.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvmwrxz.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2hzjjlqyi.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrgtmjy.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2decvmcje.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2scapoibe.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2bsizjxqu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2twhtvwwu.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2sncylvji.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2crsauqso.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ocryzjcr.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2zdegqmco.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ymrvwykn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jpovlhpd.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2tplxivxl.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2bclwgarq.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2djfkeayr.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2sqrhlmja.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jpsepaso.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2zptoqixc.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2dikjqofp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2exoazwrx.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbjhipi.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2prvyynpe.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2dxqekirk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpaumat.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yiooyznr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2vxamjzap.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gtynjhnc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdtryix.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ojddwjzk.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2tzjeztgm.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2mycfbpfc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gszrfqbx.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2bbqhudvh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2smjuugji.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2lqodwerc.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2bobkinha.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2silafczm.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2dsnotlrv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmjdakl.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hpkmipaj.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2gdgadpdv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lobqlkgu.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2zdtziouy.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxcsfcy.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2rimpnihc.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgvbdbtc.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2tepitanj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2fksuqgof.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ynpolpiw.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bssobxkw.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qzkplkdr.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2askehewp.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kpfcgdrf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjluplv.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2vbshdmsz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcfyfcjp.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2nczsopxd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2rivmvfbp.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2mgmocukt.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqzlwrgc.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rigfurht.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2zavrikwm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmbdolx.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2grcvuuhy.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqmlygk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxdczjr.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdjzfzh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2kqxggvfu.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wzhynhtm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2rwsisrnc.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gmluxynk.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2fhzwpkmb.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2mpiobjzv.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2puuhhont.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gxvcdezh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2alzmlibm.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mooqieul.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsiqklfq.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qhzissga.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxcnqxan.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2uhfbkcyf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2beesxqfq.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfhzfgz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2isvvyuhj.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjaluxk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfojzjs.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2fccrpdte.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2thynjhqg.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmtxlgk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2docgpnlp.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcwdoft.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2fyutcotp.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2essznkzc.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2nicmggvr.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zaxgavxl.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcktsdjk.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vnjuflzh.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxwfzing.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmvhite.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwnbvlp.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2fyalkulb.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwlyzdz.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2tptvblvp.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ahnvdazo.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lawpbgyn.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2yalnezln.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2luazuybk.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lbfbxrju.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2qaaeinai.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2txgtgpkz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2luxhqzfj.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2carpjydi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhxitssk.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2liqogpyk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2njxcqyjx.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwxhkse.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojibpxuk.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2wjwydaaa.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2izbjhuck.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxlelat.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2krlhowjv.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjgkfbs.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2deqrruog.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qxzuuykq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewhrcdtu.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mclyksot.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zdfmhoil.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2utuahmby.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbtratd.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2uspchggj.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2igmitpxf.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2nptlesmt.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gokqvres.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2qttcuddf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2acgkpbfy.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2uccgokqk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2grykmypq.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2coasfdad.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkkvroos.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rzvkfbzd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2uephxdve.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxysufb.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hqstdnfi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2yhtcblrr.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bjhkggwg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxehmnz.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dditdxia.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2sdvsniqc.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2cfaaqldj.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fctzcaff.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2eqilkbix.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2oapmgpoj.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tuddwawm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2idchkqky.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhtgmun.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2axatcjpw.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2rojajaei.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsgzwbza.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tpezermd.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nutduvjo.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2reafssko.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqyqapan.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2dzzleuzs.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2cdyxbvvn.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rwigvjig.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2evenaxrz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbcmtaj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2veeoizau.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hjihzdiw.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bpedwpms.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vzlgysak.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zdaxvyzc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2rzpsexpn.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2wegccckv.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2eopfjzec.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2jqaziuid.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rcpcektv.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2stgybfxy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2agadokaz.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvcdhlm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgyvbcus.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwzayru.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyhhexst.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2mcfqzkmb.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcdqzziu.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2adwnqmqr.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2imbwpwjq.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nveusiho.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvvptht.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmmejaa.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvnlizuu.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2clozedpn.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyylrwqg.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2splkfbyl.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzupykw.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gqnhwjgu.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsvpefgu.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2kkehhijx.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpzshpjs.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dllyjmbp.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tcosaaev.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bfcdyplj.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vkelcrym.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bcuqqxvi.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2yprekjtj.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2tvvsrbgn.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzmgmhx.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gklidrsd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhniuvv.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jwaorgvv.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pganktre.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rnrkdfwu.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2enkcnwhc.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2piltioez.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkasibfn.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2tndxhjez.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjuzilnm.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2bsydvlgp.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2biriyadw.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2bfrgzfeq.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmoyjreh.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vrxqrmou.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvafekwx.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2phaqflbu.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2urjqcesl.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjccsvy.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmykony.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtpmeaa.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwkbujp.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxgensi.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqzdqnn.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qeelliko.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbortbj.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2brghsqui.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2expnglmb.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2egqojmkp.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2eyotcxbh.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbdscif.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nbvgaecq.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmlzccc.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2tcfeeoor.html


<!-- 参考信息 -->