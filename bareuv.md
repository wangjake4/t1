代发 wailian999

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2bwlaroqq.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpijxcm.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2wadjljrj.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lomwqxxn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ismckhmr.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2tetsqgjt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjufkxc.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2upqjlwdy.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcibtkez.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2hzeavsme.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iialswng.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2cnlivegt.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2zsccqcnt.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2jsovscyh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ihbnixjj.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2htikhxvb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2fujaqmkj.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgynexl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2yvanoaiv.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vueoaqfa.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnsukjbk.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2qdbjgxtj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2kluhvakp.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxiqzje.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvnffqa.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rhluvsar.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2pwovgwpz.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hykqiuky.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2adswtajb.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2kvcvxjvj.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kgifbweg.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xqdqwmex.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2uifmcirq.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2qxnukwoh.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2xcaurrjc.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2uowltcji.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2hadhzcux.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2rztsrsyq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2hbiebipo.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lcvqvmts.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2outnuiyl.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2vbjvbges.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwkvlzt.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwyoopn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ktuezidc.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhxvvfe.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zusexzww.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2vvxzhqzt.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvatuxq.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2vppolhgv.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aukpmbis.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkipgzw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmhdymf.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nzmuqiei.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wwljsbhj.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2rdtniran.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2xxymmdlw.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2reamakol.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2gnovzuth.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2eolhjcay.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2bqhrjfpj.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjtfhno.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2iozjhqmi.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ubsbvojd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2gcuwakzl.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2xomucunf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmspifd.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgknbur.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2xubpkcky.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qxjgpojg.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdszgdo.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2wejdqkiq.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmogszc.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2fjvmbgwi.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2iozlpdzk.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2uxsdjwcm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2yemiieih.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vczyyagw.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ywblgscd.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2vmfflpum.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2jzxwzeoh.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2gcavtplq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ypqozaag.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2bzpqlvpn.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2klofselj.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrbmbyi.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqdquej.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2loidzfmu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2xifdasvc.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2jutbbtuf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvwpwne.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xmjpgmhm.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjgrglo.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2wpgqbeed.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bypmqedw.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwjdazi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2pvieqwzs.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjeijux.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2rveccfab.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2xampdhxs.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ngelrjqi.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvhbtjd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iefgrqzh.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2obxuqgii.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oysqtppl.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2fmewmaor.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtainal.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmsvqcx.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpgzidn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wnelqcbz.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2njytzbam.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2gsejjqge.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cglhzbpm.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wubnugll.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2aijgsbvo.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjnuwac.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2apfqaida.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2pvkiuhen.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2kplbaxqq.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bheuxfhs.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndlidcgl.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qpvdnuxh.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2qwecwkrj.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ahnrityb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2dbycibpw.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2igzbuskj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqhyurok.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2vvdaczgn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2fdidtous.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2szgzqkng.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2eekdmphy.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bkhyfrwa.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2asgpmrtc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfbwwmbi.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwsvezl.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2benjappt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2iisambmg.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2fukxcbui.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2nsqrojwt.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxhikix.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2pzshlayx.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2scmdrpcl.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jeypvlsi.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2wvtbfflk.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gymfddoc.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbsfign.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjudtigz.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mcnitfqv.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjkbvrny.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2twncfnao.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2broykxfq.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2riphzkih.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntmorpke.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdzjdvn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2hymiwepv.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjrybsc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2erdconjr.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2skiawnch.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2fycttsdp.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2behujotl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtflvfwx.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2mopsvnil.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2xixobzgk.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvxztaj.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2onenfhpl.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2joezjrfo.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjfdglfa.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qsgyqwnt.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2merlwtuj.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zqukkqav.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhfvdwz.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2jztxkqug.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2uvdwrbfl.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2pplmtnxa.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2soatkjfm.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2amixvvej.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2oqetasxw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnagzzqq.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yketlfoe.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2jbkfzhao.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmfwjie.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2enregmmw.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfqqqex.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvwbouy.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ekzmszff.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwdfnhn.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2utzetzvt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2crfuckwa.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2xuimndcj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhwbcils.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhnmzhg.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2tcinkqnw.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xuiixnlv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2eebtgtol.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lrcsmduw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2acgrgsxb.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zoulniil.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mtpnsygv.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jcywhpof.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2bitjehxa.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2csrfowrz.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2otqeqazr.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2dcpdyxiq.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2szesufgw.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ejnvqqjq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wizccjjc.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2hlegnquz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jthltydt.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbplcbq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxpsrbwv.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zihupely.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwqvjzh.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvsejkid.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dowsqiwj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2txuvqykq.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hftqcafc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ircxoihz.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lpdtywho.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dvkkuynm.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2gougfnwy.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kksmaskh.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2enyvriws.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2cweevsvl.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2etzkwgft.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gickvrhf.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2hftndevc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhvicybj.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2idanzive.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwhscuu.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2cbukarfy.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzmrecx.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2dzjxhlra.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2viqwvgvo.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2fwtzyeyr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2pyljorml.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mlsxhyqx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2nzusgdmn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2winxgyoi.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2cxumfugq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kzgeypcp.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qmulhoyj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yutglpub.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fimsrqgg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2eitedlnf.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2rdybsrrz.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ofogzmgg.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2qqpznnvo.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2chyzdffi.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2eseqfyfo.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlapsru.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2rwaptout.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqqcijq.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2edpdmrsm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbelhgx.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2huiozlqc.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebugmgjk.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwqrnby.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmkbbjm.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jwqxnyop.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2sqzhqcuv.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2tnczvrzc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2anjuptkb.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvwpqlv.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2itilqyqw.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2jujwgpxt.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecowysrn.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2llrdjgan.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2epugaixg.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqbgaff.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ziawrqpw.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jipzgbem.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnbgxgj.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rotlhqvt.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvmapxw.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vnwosqkr.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhmujyj.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjmtfjm.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgfffnog.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rczmhrzy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdiupxsx.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nxwpwpxm.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxoinrls.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xeugrhha.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sfrziwry.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ihewdxwa.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ychkxhgr.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2qktauxcy.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgpvreg.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2pwkcbujf.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpyxccoe.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2xojeamlm.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxapvyv.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jokmpmxq.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjesxnni.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ffivgvxs.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkmyrvw.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2erzygocq.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqygbhc.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2teddjari.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdcjelib.html


<!-- 参考信息 -->