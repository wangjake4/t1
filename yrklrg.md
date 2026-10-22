代发 wailian999

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2toghbrgt.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2qinibych.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2dphyvyuk.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhpsuic.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ndnpmjdo.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2eiprnefw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2nukqowrc.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ziulxfea.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvrhvbtb.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2thjuutzw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zleqvsrl.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2liawiblf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2awytpqhi.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2hupugbzr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzxqblg.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2bkaagcmd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2wejcvgzy.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwjifrg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2kxcecuvb.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zybwmfgf.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkrqueq.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2muhxkgnn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2cdlqagtb.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2etknkfwa.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2sahufxxf.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2odlcjxdp.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ublcrjjc.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2aeuxauir.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2fibivnpy.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2vbghihjf.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xkswsvca.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2usgksmzf.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2exlspqdb.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2tmicsvtb.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2hzcfcyeb.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ghaptidx.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2sxfbcdkc.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2shqzdbfp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ozfnlnar.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jwimmeka.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yrznzktq.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2vvoaadwa.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2riuojdxk.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ntokgxqd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ronwslkd.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cvfcpnin.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xidjwrzr.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxwazyz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2aatbjpoh.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2njjqrtlq.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xhifufnj.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2swnxhpgb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwzzinl.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ucudqgvl.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2untdrpuj.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2zbigwxsr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqkoant.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jglijilf.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ithwaedh.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfiaiuv.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2armpxrpw.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vnagtuxr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvnaqxa.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2iagdprmy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ddalojkp.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ykemyzzd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2nsbhpuqu.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2zvquxggk.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2utzwigzm.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mnkqcsjy.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2pddyqxxn.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ktnpegbx.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2mbiesvmw.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2cphjffhn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2sofdlycu.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2lonfmnqu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2sxfdfenh.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2lkcljoex.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2mjflnrxh.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjugvfg.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkzshbv.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfyqfow.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2abfcqlof.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqjtovi.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2xnbdchpp.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2wneqkwtw.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2wsschliu.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ddqvljsw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2nwnotzxr.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ijourzsj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tottsrqp.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbkweas.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2cddvviix.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2owolfmnc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qyezkrak.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jxldslcd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2egwihqxg.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2igmcxbil.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2puaoojqr.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2pojezini.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2jcpnkbka.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxjzyvg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2guzlzicw.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ownuyrhs.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cxygkcxs.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhjphob.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhrbxru.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nuyivcet.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ldufvnwf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ykidxvip.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2leaojfcs.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2huyxspxp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uuushbwu.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2rziditae.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqtarhm.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2nyblmxov.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwwwkjk.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2rlerzvxh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2znpggryl.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wktbzhcs.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzzizym.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2twnlzjxb.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2hfkpyywk.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rupkrvyu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwrhgda.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2jvigmdhs.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2flsumguv.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2fwphrbwc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwoooik.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmgezcw.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2azuhakpf.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vnelxjya.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2abtmghyh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtpbnovn.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxqoeqy.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ovoutkoc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekcoyjcp.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxkaire.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2bveowqgs.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qrlreasm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2llhkyxpo.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rarteoek.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrxvibp.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2irzxvxmz.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2afhshddy.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hcszqvzp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzkvgvx.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ufzikvqr.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcirleeo.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2oebljwcx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkrpljdc.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2dqnxjzgj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2niqsaxtg.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjcteie.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ncknkufq.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kxzxvkpj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2luxkgmgb.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2uatkhwts.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlcdtazt.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zmokhrsw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2tsghuqrw.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jueoaqjs.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxurhas.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2gasjsatm.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjgerot.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2foqdqbfr.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbzsoqbr.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2valsmdjj.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2aagmgjcy.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qgftvxub.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnawwsae.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2qlntwtyq.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qqehblha.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2plarjzmr.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2zqcmiyow.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cfvdirip.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvdnhpx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgxqndb.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2japjywiy.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjzvice.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2hvsxtaco.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2aogsduup.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2rijnrcuu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uetminym.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2sqkzwqup.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikevmicm.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbdmdnd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2auhjximb.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2oiahzrbc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2piudpbpb.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xkmngomt.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwgpmev.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cmzaaspe.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2tmpknygq.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqjzsxq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpukehtu.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhtbipj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxybtlx.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqnjfdb.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2cvpsyvmt.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2jrbzwwix.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2rytybxba.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2cputbvit.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uspwnpki.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2loeaqrcl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhovbfz.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qktedizj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmkcwfuv.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pugzagtx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hycxqvfo.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvckzmi.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipkrkcoz.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdhanez.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ifsnuunl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2fneicbay.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rtvielye.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tisgxsuw.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2umaeoxrs.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2urzyujkb.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2fbracyob.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjmdhojd.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2zxsuhlzw.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmxghhr.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2duyezxds.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjbqgzm.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2pltlvnkn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtdzkkxf.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2nopwwznb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjcncht.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zaydjzes.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wshyfgmy.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjaozff.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2idzjjtpt.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ltpesxfq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfnannj.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jjyhymdm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2uraqpoix.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hxwozapr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2vnwtunqx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ehiobkfi.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hafwlruk.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qdfputna.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yrxfungm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2nrtawzpn.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgllcrd.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lmkmxwzk.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2zsrsxooj.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ntuzkmuv.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zbrtcplq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvrrzvl.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2esynidrf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmxeghv.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hhinueqo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnsolots.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2qcclhpcu.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mudleiqu.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mupbpwxi.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2cmxaswau.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ovhbbmzm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2pucivlgs.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2iszoshou.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkydkqm.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2kjcvalzc.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2abnadyry.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2aieqjomh.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkvtamow.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pylrpqtd.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2kukstydy.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2clagsouo.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2tznlrgve.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfhiiym.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2arxxchoq.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kocgtuyz.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qdhbdwln.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wokdumyq.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2iohtmsxj.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpfbskg.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zoyzjnrv.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2uabmybkw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqkwvmuj.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nngxaved.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfsisvpl.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ugpjtwej.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmecouh.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2croxjbar.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwkaefe.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2lfogfcfs.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmfbeoqs.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2axsxtfsi.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrddpffq.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpqjjnb.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhublrms.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2celtnbcc.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgmkugpl.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xulityco.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqzrnpe.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2dvekheju.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwwukyti.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2wegfjwig.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2hllmzcuu.html


<!-- 参考信息 -->