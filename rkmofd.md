代发 wailian999

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2scyyvggp.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2jyomadcd.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2wtxlxglf.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zmaapgin.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2crslqvce.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2tvghoeqj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2wtttodjn.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lopygjtc.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkinlfwl.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2yivnxiwq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2opobvecy.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2sceschbv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2urbqcwri.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2qhymctjo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmqrlds.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnewkkb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2wrmpuljj.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gbsyrghm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxayufz.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hurvjlqv.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjjaubj.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2oitfdaff.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2flyrbmbt.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2hmmrhalj.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2chdqzlqt.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zmomhugt.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ouavidno.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2nvgnikup.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2pmcyspys.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2mcahkonf.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sykxzuyl.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fndanenb.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2lotygxpd.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzqwkqw.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2xpdatzto.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ecpuhhjn.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2djipiyly.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2wndfokal.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2xuzdqsrk.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmkvgzu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rxwhrnry.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2pzezgvas.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jxpzqfwy.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2phgweoyh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhdjujb.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdwggle.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmtvyjq.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2lywaicka.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2zizxlaha.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjarmly.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmgkmuy.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2qwowejyy.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2vqgpezgf.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdvtqqr.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pszixqxl.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2lcylotnu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtuuwbx.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2scrvxqcv.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2wbplugpz.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2zvntiqty.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2kkjffogk.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wjzqlyeg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2azkikcha.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2sstrpncp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlsiymj.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpmbgik.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2urcaeuwd.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2rtyyhvaw.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2nnnortet.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ytekwqdh.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2nykaluzy.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ggaszipz.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2artyoxot.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2othlqeyu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjrrxrj.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2mdriuaay.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2bpngmfzu.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2exsozqyc.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2qvvjzxdf.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2tfrooouc.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvxcvbk.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2zguosqox.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2shwpurax.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2luudwwuf.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2maolcmld.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2kmilxtci.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2kfwzsbhq.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bfduzbrd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgyfpei.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2mvrvmkyj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nszvplek.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjijwsn.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2jqyrdcfy.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2bthetomc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kymowsqs.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ugeggpbb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2awftlovg.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wobigpls.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwuztto.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2bknjtmvq.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2husockoz.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ghslhnup.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kstwbmar.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgkbjwy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cdrgegvw.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2babyzzmk.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2zorkawrc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fupwjkvq.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2bpfetavn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2owyptgea.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2guutxvla.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjlakjx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmfnjppf.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wdortbwp.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugtfdfrb.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2tskivwia.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2tycxxeef.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2usehqqki.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ryrsqskt.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ftgabmzn.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhgejorj.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbdepsd.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2hfisvumg.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvdpkjb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2gqxsipmk.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2pwaadtac.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2lugmecaw.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2xvyquygz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2stcffekp.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2aejxzkpb.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2pavhrmjs.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yeukyrdm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2kusixkdn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dahluadb.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2tseuneod.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tukdzqfg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrynjmjo.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ryfvmrlj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2qkyyputl.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrxodci.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxcuygr.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bvrcqbbh.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2mlzfzkeb.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2uvglolci.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2slbyzhqt.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kxyqjcho.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2grqigfor.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ptcnorks.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2sufgqjqx.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqwhova.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2crqfrwnv.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2iuqcmnyf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cuirynvx.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2sstatoqc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjqdglk.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2nxmkaoij.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwaqlcrw.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2wyrfcruy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2awjvpuzs.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2suvltekm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppeeldop.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ypquvdex.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtuvwbdo.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2tuiwxkjd.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ridlueer.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ajrrbfyo.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjookjc.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ptniktpr.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqzwphg.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oqfzeajb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2zyjiloyl.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhnxpei.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2dztzdrvv.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jgpnacal.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2kasrkbiq.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uvoxgwsa.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2eixwdjwc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjqlbra.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2miqfuxgf.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2yqiaznul.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2eytjmofv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2thlryjmv.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2sveesfsr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pectlmal.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxajokl.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2czubvjmf.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2gjllfvrc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktjlmvhc.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2rfquyqux.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvpidocl.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zaeapvby.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2btqfbkgt.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yuxfmogw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhvoypx.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2efctyifc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqcyebkd.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gqcimfmb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2njaarsbu.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jhgigcry.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfawbbv.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ineiuskt.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgcruktg.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdftcri.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2upkxoiqe.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhxllez.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbkihjb.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2jnadiglb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2utzakvca.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2aknoezbw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pncjuhxf.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2owkoegls.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqgmafei.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xokulaby.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hckoojxk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxlpzej.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rgczazak.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufcjqcmj.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwnobbi.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpnixkn.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2juupqgcg.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2thxisami.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2acikkrtr.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjngbhsa.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lhtxxuiv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hknlnhyd.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2kzjryqpv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmarwgoj.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2dhekypbw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ophpmiht.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ckwppqsh.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mucemdyl.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2cglzgjyj.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdoaxftx.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xwlewild.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2aidgguma.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmmzzsn.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2mejaekwd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtapphi.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2iffbxqek.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hdvibeim.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2edtsxhus.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pxbjqqdn.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gptzydyg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2jyuivqre.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2tafxlhyz.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zoupfwek.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2aefagccr.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rwnozgfm.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbymkve.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2kflafgmx.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2gejdtlyg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovkirltr.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2umdavmpp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2aelnqjzs.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2cansfkek.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrnpvpay.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2srhuzxvq.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2vievpmoc.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2botpcbvi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2eawidvui.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2yeynivra.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2dexcrxpg.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2opwhonyg.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2osfmjiqg.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2vqxbeetu.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjbwunl.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dwdbspdf.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2frqiqvgc.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2hflzlnoj.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2elpcllid.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2adjrcjbz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zeqfboae.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xeuzvmgt.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vqszsiea.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2omiyuozp.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2thwkgvrh.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2kaftmuxp.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfedjmmn.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2htqvvvpu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzacpfiz.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ldhcrdep.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvkcqcd.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jnzcqhkm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2doukhkdg.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2shlodkxj.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2isryxavo.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ktokjzsd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2irjkoxjo.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdwhpkx.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqasvsgb.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2wwynapes.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmdizwi.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vtshevzp.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2blatogyh.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqkpvfh.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2warasglt.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2vwnkuvfm.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2evdbuuxb.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2esbckjzi.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2hugobmwn.html


<!-- 参考信息 -->