代发 wailian999

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hxsiswpd.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2rmyxgsrk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2uapmenjb.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2onndwuww.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iybcidsm.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2csqofkst.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2twuhsfas.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2dcqzbgxm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdxzoon.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2pxpikbek.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2fzabclvt.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwvjyun.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2gbofuuri.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2thhuxrxx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2jlpipzgh.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jzovzmgf.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fiskjtdk.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2hzrmxisl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2baocuocl.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ficcfgzw.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2acpfuxpc.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2aavediqa.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2mukvwgre.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqpbmxc.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjwvect.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2fgqahokc.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrgudfg.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hlpfqllv.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2oaojjics.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2fstnvvma.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2kqzgiaym.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2scnellcd.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2mmztazuj.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2htpytbti.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2rjymkryj.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tsomtyur.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fytqdalk.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2tixayrow.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxbxhve.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2msddeveh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2nwzkqnxv.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvjvhei.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aakyvofq.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2kayqnwks.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2gtmcmquj.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2sqfplphs.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oiyivyvk.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxqqfkv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2jatbmjgx.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lorovzhk.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xwseaiwj.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2adoubiih.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvomtzr.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxmvmar.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2bqkzztmk.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2mssianxf.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2jmmmccha.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2raovxrcc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2qphzuojn.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2rjcgxxhi.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2vosotzzy.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2nvtaxxri.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2dudzygoq.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2aptgetcz.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2jfynivvp.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jsleofkr.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2vthxjnlk.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnxaiko.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2kynnvjvj.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2wtqwgpkx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2slitsipo.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2bztjobvm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2lbnqqyjy.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ynywouis.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2djvwcqbg.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2dftmqmfn.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2envuqdrg.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjpkmzr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2efcpoxmv.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhtkybv.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2fshxmawi.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2dowkerax.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2uxubbidu.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hocjzjkh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfrkswp.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2bxaqjbvl.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yoptblag.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkmtzir.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ywcmovts.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzhhvhk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wifztdxw.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gfsbzrtc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwyfmbh.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rtblgzur.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2droppyaz.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2njbfukrt.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2llolmslj.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2hbecdymo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2felvxgwd.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2prswylcd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pznmhwcy.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ijljvivx.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2nazfyugu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cizyeurc.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ddtbahnv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qgcmufsx.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtckfzw.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2azokjbzf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwigzwni.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxkaijo.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjlgnam.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2nlnzqcpy.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2zsnmhvah.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2lefheznl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjlpitq.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2atkpzfhr.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuikhbnm.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqiiipe.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbqectx.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2iijqpwmk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlembnm.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2rovsrmmx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2civsyfnh.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2sxbwpchg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2qrozpwid.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2rtjlutlh.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqhfvmb.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mwodhwqy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2qptprfvq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvnyhjts.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqskofg.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2opqrjpcl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovljwxzs.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2yubtuppe.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2wkxbfqnz.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ujtgcycn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ssscbxle.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yiurngwf.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2bukfnemm.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2zmcimowr.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2evyhmiir.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yvblymil.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvonqtgp.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bjxyowme.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2aahpiwjc.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dullwthq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ficafraa.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjeffwm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkcpatft.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2maxynban.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlnraqnn.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2mzymwzen.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2urzmpepp.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2scwxrgjw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2wagxwlxa.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfbqzew.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2gihgbyii.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2dfqcbhju.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2kubzztna.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2yvsdjopi.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbvywwg.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfyivih.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ockeexfd.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhlhqvy.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2aznzmdox.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lbzpjfjh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwmizzt.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2jgvbgdtt.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qylsqlsk.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2kccuuotg.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2lndhxtbl.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2njiyabqf.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2tzqmmxtz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xefmphnp.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2csyeopao.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2scfympqq.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzonqtn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrnxyaqm.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2odiuspib.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjpxoaam.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2nmibwevq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2aigkbbck.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2zhluntlv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2diaentzi.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2jnrowvaz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytnayhdj.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ehynhnec.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ukecnxai.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pmarglav.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2llgkvkmp.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uvelnrls.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2opbrhzxj.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xdyfsmqe.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwgeqkd.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2shaznvpm.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2otlrjtin.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2afvuufrt.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytlrjvnv.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2qoijumsp.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2udtfmkcf.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrknwjv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2epnddnva.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xnntlizr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksahclgh.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2eauksjdk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eoslwrlz.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2msqhsqpy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmkyyrim.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjmjzlnx.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2drxqyhkn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2pbqdbdwe.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxjwolj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2heoupusl.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ifcbxsoa.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2pqynfcyh.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjvvwke.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjekemhs.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2dyeuachk.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2vaztgcpp.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqnggvx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyxvqtnt.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2tqcizcxh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmsnpfd.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2zbkxrrmx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwfhjgbx.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwftvuf.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2afdhzzlj.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdaabfw.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxmlbsv.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2nvcjaugf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdnoihe.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2giyvugwb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2snzvaxfv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cacnluid.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2zvdxfoxg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxkpdpn.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2umysyoid.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdebcis.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mmoayxpm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ymxnhpdc.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2fhsozoql.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wunqcwrb.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2mtrjvjpo.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wioplrpa.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ryoghsef.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ttysczfn.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2rkffjsfy.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uioossox.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2eoljuxsq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvsolypi.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2wpogrbrw.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2phfneeif.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hhlzdnzl.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2cfrjsbpp.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ugtmcfel.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2tzvbgtma.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhfopwt.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2isyjomcv.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2sffvwwqr.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ximsgxzi.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2llhbviji.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzcqybjn.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2suifgrpn.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmegoavz.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2cikdjvpq.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyboocuu.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mfuvdhxd.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxenfjo.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ghyjewkn.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2elfosbjm.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2iplzzmxf.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2bwffkgoh.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2blzocsqe.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzguwdk.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ttsculsm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrwqfel.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2saxtosgc.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2arqfpijh.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2clyrmqqu.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hjfmefdx.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nheonwuh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjuhyysf.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2vahxmmkm.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqwolbp.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgscanu.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2aysgrklb.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjxhphh.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnfkztji.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ioyyrnil.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcvytmxp.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2eknykjze.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvoeeqf.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkgvvju.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2fizvekiz.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2nqqbggaa.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbnjpvat.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2efdslqku.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rorjmwus.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ysauwdzl.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sdqydfmd.html


<!-- 参考信息 -->