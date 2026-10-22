代发 wailian999

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2twkfojgu.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wgininex.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ryymzysr.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2nmnncriv.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhsggna.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2kdquyjrr.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxtrbwa.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qbbjpfri.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iayikfaa.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zdsuxioy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2wzseofxi.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rqiivgpj.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2biicoywx.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2msignbro.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2omihzzwj.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2djyhmjsi.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2gmgxpjbr.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbdmmjq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2dqffuvyr.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2kiebjrem.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwgvuvs.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gfrdieci.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2soqcymlp.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2saiocwwj.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bysdgpim.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhuqvel.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkxpwuc.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2kwkbufvl.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2efwqlyxy.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2oghwrkby.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhkintv.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2acsebise.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2nlghiusf.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2kohaquop.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2czomsjvp.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vziihnhe.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ybrvkckt.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmgktef.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ptrcqpor.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2xmkdbfzc.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2spnvlrey.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ercjnogo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjavqru.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hymuukgc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2perywlcg.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2elcdtnvu.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fjlwikxp.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yoblrokl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2gvyyiajm.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwnhtqe.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhrnfhe.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2tbasovsy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2zwfnpnod.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ajqdwdem.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2plkagulj.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2taeomeex.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmpwery.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2votyrwlb.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mudtebiq.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2dyplxtct.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmlbynb.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ujyqmiiy.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2paunmeyr.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2lbckqzrb.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2srvemufc.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qhlykxvo.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzdqpbh.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2cyxsitih.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2miegiwsj.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2duosbmul.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ncdacufn.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2jaacrvci.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2oxajuxvd.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2swfwsvnh.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2fupkyrxq.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2okdkonfv.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2khysiztv.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2leaecrfn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbvzvjr.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkmwevt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2yqsqkjge.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2cqzzshbq.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2wilzqweg.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2tmtrtwsx.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2zcoqgrti.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2odueehdh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gocfptec.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2xccknmko.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2fakmcxys.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjeihqj.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2brwappfx.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pdygdmxl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ickgafwm.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2cjyjrymw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fdzjgasa.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ozbhloht.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqfqqcy.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2xtoifrxu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rfztfwck.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nfcehbli.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdrrapt.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjsomsc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2pavyxtzo.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2bbfghrlu.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2udrfqzjv.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvzokqn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcjxaqy.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2bwnzvzyt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wyslhjar.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2aczasfdo.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2aunqawpv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rahvmylo.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2uzchivbs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qspowstq.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kgfjgagn.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2oguymsvh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2whhbakpw.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2nersdpst.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgxvmkg.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2tdljoedv.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2nelhugep.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2lxcbymnt.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2lrwkdsmi.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnapbrt.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqeqsge.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lpolvcgz.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2kfhsrhdl.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2adlyrrhf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgvyyev.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2svjzamgz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpdmdhmn.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2rizujezm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2optjogvj.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhssehi.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2vscwuauh.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bojulbzq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2etuntvnq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwovgwkr.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zeuuskag.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdnissp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofauccta.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhcvvgd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2efeaqood.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2scsbfqoh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2wyqwruof.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rcliaxhx.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vprzcaco.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2bqyqnbyo.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpnohegg.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jzyiblgd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbudqvs.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xaanumki.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpuzcrry.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gbqiaatl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxjunsw.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ouepfieq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulfrflny.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2abotukwd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2eadufxfi.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2innachdf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovofseta.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2sdqbedqy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjlqhlh.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2tnpsvife.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbazpqmp.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kjporsqu.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtmppnk.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2hzpxdgos.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtinvkr.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rmimufrv.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkgbxfgt.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ulbbhbiu.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2unlkinmz.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqwkhhj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2velewrkq.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2wqrwaant.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jgauienc.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqwmgnb.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2uupnztgb.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqsobmg.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2djobyxpc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzhqnfs.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2myyvsjeq.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwkjwpn.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkiucvm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2phriwonl.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2jmxagjoo.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxikjul.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2kazqrbkp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ainugotl.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxxhfyf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2igtxjohx.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvqogsk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wslelyzm.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cxpuibsq.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxsomjb.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2havrafmi.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2pkbuafoz.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rljxpcse.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbinbdaq.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vizhvamr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjjvkqp.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zprqsnfm.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2rgogdmup.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2thymwcnm.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqdrwxc.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2dfuayloy.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2elovrchl.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2gwlsiiyt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjndibg.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2utzrmrqd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmrfltx.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qstdopbl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfixzjcf.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mexunxqb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2spnyvnro.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwaznhre.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzlrdqr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2xgvmakob.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgbnbuj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yygqqvtu.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2uilmyojk.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2wcgwgffq.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2svwmfumy.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmlhkln.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2oaypsagk.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwohgumb.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2sbcrhntk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrzdodfo.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2wvlgzwag.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dsctdfos.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ozkysgus.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qigakefa.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwagrlb.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqaxvlg.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxmgkqw.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkyqbdmi.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2myexpcmi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2azdrzwjl.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rexkamgj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2yzqjpyxb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gygwxddn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2sdskhwee.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kmymiphf.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dwnxkcpt.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zahuixwp.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wegpzemz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxfbprp.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qktkshxe.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2nkacpfev.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmlnxle.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2glcusowx.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jkgyfpqv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2dmuelqpv.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2uraykhsi.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2azowrpug.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmjkztw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbesgmi.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2gwiowumv.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhywajjp.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2afdlfuzj.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2nwzdpblo.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbvswkt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2dyzztnut.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2nldtgddo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovyhvgep.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2bpkishdo.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhlkxmad.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbtptpr.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbhcdps.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2baqoeypk.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2yaysejvd.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvfphyb.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocdjsoow.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2slycshcc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2leultnhy.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vfugjlde.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hoeilhzu.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tblxaxah.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2mgkkgwjh.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2sotqqrtz.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcettsbk.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzworun.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2byahcqwk.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uymulyid.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzyknuhl.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2svsffmwb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ynlrxweo.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ocbvstsg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyweqysm.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2bkacfbwg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzpxvtov.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2oenbwyng.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2covitxhc.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdavszi.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhtzwlx.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tduelmfs.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyepylcp.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mwsehvgd.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2uihcocvt.html


<!-- 参考信息 -->