代发 wailian999

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2whicspgb.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kphmhguk.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2uffskdvw.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2bqnvlcev.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2szfllmkv.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2zuerjvgr.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2rnkrsqnb.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2olnvlgya.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sfaxotre.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgevofa.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ogimhnjg.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sgrwsemu.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbnvwxlt.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2iplkxgfg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcrpbhem.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2cwcfwafn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2kzqbzllj.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2bcyernxy.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vqurqwpb.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwcjhah.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2svisgexa.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2uwvgawjn.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2jgubzzjd.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2omefvxfk.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxbaowfb.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2zvsvleay.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2bulyqwfh.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lytqwpan.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2psjwwtfx.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mvnmdedd.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrxkkxb.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfeijkh.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2bxowuehg.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2kthhpndq.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2soenhmmh.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ppdptnhk.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2czqlfzhy.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2neunsmdh.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2tqlbeejq.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qnifenkn.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvlpsac.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2qaulfqpa.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhbuyso.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2boblflnf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iklnipql.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2uxzqmrip.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gniglpzy.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qwpjdauu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2zjrawkgg.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2elbqbdef.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jwlgnkjq.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2bheguibj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdkjeyx.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2trckeblz.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zlgpcyxo.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2cgyzlxdj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwnzijb.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gvnvigkr.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gadaiqji.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxwqukz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjxlcav.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kfllcybc.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2wrplutyl.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2lyeivdhd.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2izwldiss.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rdekhyom.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2eztowavu.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jibmqptd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2smfazfio.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2fhbuukui.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2worldzru.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2phcfldul.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2pmdcresc.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zpfsxrae.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2vpdkyioj.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2koxvumbi.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2bemtnigq.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2hyopjrav.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmknknsh.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2nxdronxm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2klalqzbx.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zwaayptm.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xdejcdhr.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2atnyvgnw.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ipyjfckw.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxtmldr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zpkizuvg.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2djcsqxom.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2myeyjays.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2noeuiget.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzteirq.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzftwru.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2oeietqof.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2oaamwxmo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xtptpkzx.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ukuzjsbe.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2mwydshjg.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2glvdmqid.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdltkqq.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hiymorsm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2usqdszvd.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mmvmwmmz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2liqexxwj.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2nasxkjnw.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2rtonxqhv.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjoaxte.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wyllgtys.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ykasgbru.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lqlnsaam.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2uonpadfa.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2yhccnghw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2whjnooip.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2uxfdtxzy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2byvpzkak.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2skwxvwbn.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2zieqcevq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzpqbyzy.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnyrlzr.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipsbiiry.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2mxctqdnl.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnuuvhlm.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2idffmzii.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2desscqgv.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gaarnjen.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vswkogwl.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfokrzq.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxdwvut.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cixplnsw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2wrbtcwda.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrwlsuq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxazeddy.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2oxetlvni.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2iyaeiwyi.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2kwkugdqn.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2kinvyskp.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qwgfwivo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2bdppsiqn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgteenku.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2fsrivysv.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gbovuidv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwnonrr.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwempcu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmeuufe.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2cabjtttg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2aedmeqqq.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ezjpaaxw.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qoeqvhpe.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2uwfluodj.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqvahew.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2veuipeun.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2wlwhphlo.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkwkqnq.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfzxtvy.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhngeic.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2aavvhdwu.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2caqfnfyy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2zobtkkeg.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ekgdzfro.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2fembyqtf.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2pryqfhcl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2frekkdjs.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2qaskjhar.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2drqmzvzl.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqmhkiw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2rldsuxnl.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2sjsplwie.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdehejh.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhotvvi.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2kohhiuci.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqiofrp.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbyntvmu.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vttehugq.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvamafms.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gfivdtrf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzadviz.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2cjjudquc.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ufrpxzno.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ywjxcwsx.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2fdlhqzzc.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2piuwwigd.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2odjzmljy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrpcjywk.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2myxsrrxt.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2hhceogmd.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2juwbdoho.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zivdtjsm.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrmyroq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2acjnumag.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2qjydecfn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpebixuq.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2yalfamig.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2akspwtdu.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrpwzyk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrztbdct.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2krickmpm.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmfxroj.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bsvpkzse.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ptgkefmf.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhqrptm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhnpighj.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vazdhila.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bxxsvbrr.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kivzfdwl.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2vzrmnbae.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2aixhboip.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmqcjjjq.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2eadwizmc.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxhwceot.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2hbnydmyh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhfhsmz.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzooedi.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2coroyshj.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bbspisnf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwlsuwih.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fxynemrm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpffpbc.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dklqkuzr.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2geqgboat.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2kxoxiajl.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2inpcqmve.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsslonmc.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2exzsjchn.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2uncgvabc.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2scekfxft.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvypmcwy.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2wwakgvtx.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2bollwizh.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dagecffd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjsbtma.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqvlzoq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhozzey.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2scruprrq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zziyrcne.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mkyxpuhu.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukxojcly.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2fgnddmtd.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqxkfxq.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2pbakbugz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxtpsqw.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ltopgxat.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfzktsc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2molcaomk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2jtbljelv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2byxgkbdq.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lucoplxl.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ucloungc.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2shemmbyy.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2kpmfcftm.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2naaminpo.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qofymdbu.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqjtnhu.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqpicby.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jchmtvvh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ocsnwwgq.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2remogjrj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmgamhmh.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gwfrvtrr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxxdubdn.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2rpsjieyn.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcuxotui.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2exvdnlgc.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2kfushdkk.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ufffukge.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjogpxa.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2vaqgqviz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwdhdno.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhyooyt.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcykomyn.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ivxadthp.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mssqtdku.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qblchdlo.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qryoaukz.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2llqdqlpe.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxuxvzsm.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2owoeiuwr.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2udvwcyck.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2cfocqanz.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2opkyfjrq.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2axvtdggx.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxabxpl.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwxsahk.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2evvbxlgm.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hzztefoe.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2imidephm.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2axvetfez.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gepbkptw.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cwoafelc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tviwamae.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpklgsr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jovrmzan.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvhksru.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpdmjqyw.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2yujlmozv.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbfvvagq.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2bjcbktjb.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxldpvni.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ounarhyc.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbkkbfz.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2atdzdqzz.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2mygkzprb.html


<!-- 参考信息 -->