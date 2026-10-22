代发 wailian999

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2snglphpf.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2cbynokvj.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2awstuugu.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxawosb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqbfxkx.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmzidpf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2egftwfkd.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgovrhf.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2koedzikl.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2fzrprxyt.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aibeniln.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2wdnwdqpy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqwkvha.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2krurnlxa.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2mmijhnej.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2fojltzyc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2isuojpfx.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2upoqpjad.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2xndokwzj.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lrsjjodo.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqaglpdr.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2rqyflolc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2bdktzauz.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2yysgzsmh.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2uypbbons.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2behsagqk.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2pufiwfdn.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2doaexcyg.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2xaaeekhz.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2sdfrupzf.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gzsiuyan.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zvpinhob.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2kxgxdwtq.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2adnolvuj.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwkyrhl.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2elzcnovp.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvilhgz.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjkbboz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2kodeakyd.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rqcmlopb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2metgczan.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2flrgsuaw.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pwyqjqyz.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xihzxxfe.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhwlayn.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2waujrwkq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2izezwjaz.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2gojawhqj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2kmortgft.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2tqtejvxf.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wadlawkj.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2mhaiknra.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdizlck.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uedhtcwp.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2otldlypd.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2rhlwyfyp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqkidnt.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wqilcyip.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2cuulwlgm.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdmvnwb.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxwllmi.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wepttdmq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2kofrjygl.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jokdwrin.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2bbdffxcp.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2laocueco.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdlddkc.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2xuigjshd.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2askagevp.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lovqmbyn.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2pwinsndf.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2hweysrrs.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2aajpjqqp.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2vbvhtksz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkadeyav.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2tabhmskr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbkpwqx.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ttffempx.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2eaammahy.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2vstoqgww.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxokpox.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2emdxzaui.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ilepompm.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2txacibmu.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgxhrhd.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ftgjnmdh.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2zmklcbmd.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpeotpt.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2zflwrlau.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvimtsy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mfbozpii.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2isplynja.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2cumcfvfz.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2lhfljxsf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bpyvvijs.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2prxloupv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2qwijtowl.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kotskiqe.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2nstguszg.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ykkomwri.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2wclucbcv.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmcjkbh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ckoagnmn.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2upmggsmf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pqoahnev.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2mgujkzqx.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2vejimfkv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2htmfgqvk.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ccwjocwp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gjnqsvhq.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ysunyqrb.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ispkwsnc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2asqrpsov.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2uuaqbdsb.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbfatepd.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwkzlnb.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2iixkusry.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2mqgbifyr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qxcbrsdh.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rympkscw.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jopuddkf.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ehbayxgw.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvexroz.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdadhhz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2zpupgxpo.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ufkczujb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbteidzl.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2uwgwcdzv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ygnrtzob.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2mmehhvuz.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajqkhraz.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yvuqnwzy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2chutrekk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdkbplhv.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvmsucfk.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gebbgygv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rpdltkpd.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvstdiy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2zpncyimi.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xoomjsam.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwbebfm.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qecmvbou.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2kcdjlevw.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbggupq.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxcmkxg.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvcexxj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2pevuspdt.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhkbgfa.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2eetqbvnq.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2awuvursu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgrowzou.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2drneulsn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2lcyyxqqz.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhvothp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2jurdpzaa.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zzsivspt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhsylgaw.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2gsnpetko.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnqbbphh.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2pywmfagp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozbhscyl.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ovciqjtx.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzgaqwu.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2drveepiv.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjqpbual.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2awumhqii.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwscqzq.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dllyinrd.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2glnuaysx.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ggblvfes.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbefamco.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdruntt.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2inzkpgzk.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2dghnvijc.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ydzeycqy.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2arfxlyib.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ycrmnmgq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjlzpzin.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2chhgptyn.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2oqtjegzy.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2srodqkea.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2euwdsptj.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2jagsbdlj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwloghko.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2joxajkwe.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwrzpxx.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2msfnjzjd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kpaxldan.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2alhmqyvp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2malkryav.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jxzfzava.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xshpaaxq.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2phumxroo.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2djubuzxy.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ammkozcm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2akhzkoog.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2myalypdc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwcvior.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxwipuy.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ufifwypb.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ovhepigw.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmukuekz.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2jasfupny.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wniwoqdm.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjmanhp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cjhuohke.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2limhfsft.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjuxhsqw.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ptepfmwa.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkbehqa.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lgwnnbxr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2oiivhyng.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfszleoo.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvhzvsb.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2quuzslbc.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zeiirucg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjkidors.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpojniq.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2pcqushrk.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjndrqv.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmxubof.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvnyspi.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwecsgav.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vubzhztw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2psheehco.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2iurtiycp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwyawnuq.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2mybpvxnm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxggfrzh.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nilagipw.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2auyuefhh.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ailwpcod.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqymqpz.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2zjimguda.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2watvtpkq.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bowycaws.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2twdwqtxr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ihadjpnu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2hshwnuhb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ksarpmbp.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wtlmwzyg.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmqvlon.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjyquha.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2fdxzpkvv.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2kwrawtap.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfnrzkz.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2snnsimof.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hlvjmyto.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxnxxbw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2jwgldpry.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2prqhwomj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhjmehg.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gymxvlie.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjthlsqb.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2lhywazba.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwnipxqh.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bghjcnkv.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2dwtfqsmw.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2euzeindx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2bokddsch.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2zsinjikl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2qafdbqha.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ujgijdwr.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2neenmqts.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2nukrvrvo.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbbdcob.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2beaxvabn.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggufoygi.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2edlkhlxg.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrfcvjsj.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2azulwvgg.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2azeldsde.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ntrprono.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmooacg.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lkcqegey.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhuizqn.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2cuilrfdq.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmsznndq.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jotenjul.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjjoeubc.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fabvehbn.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghsdzsdv.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2msdmwzod.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2izuwndgd.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2utjfufpb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptpmfhub.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2sdwiucqk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nadmrlhr.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2nbshbrte.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2djftwbpo.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2tytrfpdl.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2lauveknq.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mukbgyck.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjldzjr.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2uienqpml.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfcnriro.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2nykaqyrl.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2xajrfxld.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2fsggsgpz.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2aalktqqt.html


<!-- 参考信息 -->