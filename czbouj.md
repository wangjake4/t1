代发 wailian999

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbfqkrtb.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2kzvlqoub.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwfzwvlm.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2nfmabzwb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2tutpwsva.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqpddan.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxrvpbw.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2bahpstrg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2mcxtlupn.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ekcftwtt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2jwsgesyd.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qqcqlzaq.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oejewqls.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtyoesc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2zcutnofk.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2thkcfohc.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2koxpyncn.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xkzwiwdo.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2eonnjwpx.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ramehbui.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2dhukdseo.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2cralswbe.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jfpevlfo.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxonbsf.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2xntsxdrk.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvngxvo.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmxowqz.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2irfgwafz.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2hcyjwgdj.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2wtrgssiz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ppvrifqe.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjswnrq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mdjscvjr.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2gpnjvkee.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rlsjcqfm.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qpoilzjs.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2kcalsfmw.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zzugfvgv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxqxxym.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2uzizzmvm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvfjvcb.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ircszyav.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gktijals.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2xkiqenbu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrqzmwg.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ihknpkfd.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2blhfthge.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2yegxgzdq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2dyypsrcj.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2joprwuns.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2onsrjvtk.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzzrqqi.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2byjvhxul.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mzypedlz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2qjqsmfyf.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjdanqx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfimblg.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2oadkhtcr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2epdtyysy.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2pleqizzz.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2eghapkik.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhummwz.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2kyoedblj.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2hundzuya.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2sgruhvst.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdvlern.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ooccrjit.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2zrrguptz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2jzdsuzor.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ldgnxllb.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2jzzqnadi.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2cjkpcbjo.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2dmpxboly.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2xkhptmyn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvlfhqb.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2nrlupnlc.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2kizebpnh.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2crvnxdpd.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ejrnrbki.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ejfgavva.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2lgoepeur.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2mcxttfuk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjnkvqb.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cramanot.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2adrvyybz.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2qejwyhfl.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnjvdze.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mdgntvwv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmyxqms.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yudnrxgq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2qtnbwqva.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2iviiwbgo.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2auiaorqn.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2dqdhkfcr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kbysnehv.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqjutwe.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdbojru.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2crxzqjqp.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvboznh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nywdsseb.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2frjqpweg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kphffoop.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2eamyxbuy.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2jijffcxq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxswswgd.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2czhaezch.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqsfaeva.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2tyyzxpzi.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2zplosxob.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2lafcrolz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2jrsbobbz.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wsnrnfpr.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwouskmc.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kwvvwomn.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2lgeovphj.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kroscitt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2nrkoefgj.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ydprmtxg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2kievmcbn.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2shstqgsg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2alsvmgzr.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2zeykurkn.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2egjeeptx.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bntfcbhm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhqfazq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zktfrgzh.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrjpbkq.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nqpahtbf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2fycihzmo.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvducdq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2asnneefc.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nzsigioq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxoxnci.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bhtqemod.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2lgnooldv.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2wfswiizh.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekdcgcfd.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ybniesvj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmymrwcj.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmdxohv.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2uluocasg.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nnqmejcq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqjlmah.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvkyjsa.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnunxxd.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kezopthg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ylndnlor.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmleymk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2xivjvnsa.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2wtabfyoh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvyyfeg.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2pdaamnbg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2xynbntbl.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2sihutvzi.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjglxjrd.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2jdmmnxrw.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2zppwkjlw.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tnstmhog.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2uaofujfy.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yqwoumse.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjmttmy.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jrylgbsi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2uawemoma.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ydbssaoc.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2dslfvtfb.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ceiplrdl.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2jywgvfve.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xcblqvdb.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2legdqihl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iilyqqlj.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cftpaxju.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2juqkgcun.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtknjil.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2elsrjebn.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ufiuxnqj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2owmxvoan.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2dzazvmhi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2djoifotx.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfhmnbv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qyonissx.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2fgyqkroe.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2roltgctf.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pnobrmhp.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2isyhtmfk.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2unmmvfab.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2kbstrexd.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqmeell.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqswgopj.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dufserxf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vcpsfvjr.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2duaruvhd.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2jpikaume.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqdymgv.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2iucfttht.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2smfcnauz.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2imzzcozn.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqzddos.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cflckjqw.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxtnfrf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vukihguw.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2epetyvbv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbwynsd.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iqorexta.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2birbezob.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtmiqnf.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vcidcmeh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtjckja.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2btmsvril.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yysrkyau.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wrfqguol.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zsdqjhyz.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2hozwphdb.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2joyulueb.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2hypiucqt.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrzoize.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2apijrvhs.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxuqwllx.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2mjnrwzjn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzfgggg.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2mquatuns.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpygsnck.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2cszcroqq.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlgfarii.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2dudurzzr.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmkkpdo.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2slkeidcu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2yuzcsrtn.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ejifwpun.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2isxhneth.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxwivre.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2yilckvdl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2abhuqnpf.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qjphgaio.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kbudigmu.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uporkmvh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2vndfnnko.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2oynhifik.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kkizzgfc.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkbjkoi.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qovvjzza.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jnykqmtk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxktchz.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2rpftfgyq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mddezlnb.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2meyosezu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwapnhdo.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2khoncjan.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwywcxpi.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqxllrr.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2cmekbxbi.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kenfdvcz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2fjivmmbf.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwwiebn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzerdqck.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwdegpz.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwtssxeq.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ovhihdnb.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvzqjnv.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fygzcfis.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgitgfn.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2usnhbcyo.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxoynrh.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vonqxbkl.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibrtxsgv.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhchzlc.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eanfysrm.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvkwhrv.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2mcpnyzdk.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2bbfxwmso.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2emmnwdij.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nzihrdxq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fftodfsq.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wedfrflm.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmirklrk.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzjccnv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dpuzeetx.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzicxir.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzurbyk.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxcbsnz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifevtmni.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2rldwgipp.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzhkibnm.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxasimt.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2aodhgiwr.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xwfqshix.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2daqfgmdt.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fouymlly.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmgezta.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2jxnpqnal.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2yovnblpq.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkqqlmc.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2znsatvnd.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uqpzxecm.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2eorgrvgb.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtrfppw.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kpotepcj.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2fofuvuhu.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2vwunxglx.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2zutlbltl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2nprrefxv.html


<!-- 参考信息 -->