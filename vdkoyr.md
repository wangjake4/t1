代发 wailian999

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2satprdgg.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrcszpe.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ylpyqmhv.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkubxif.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2quehldsx.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2yibgozhx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2sfgofjuu.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kxplqrnl.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhdwgqb.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2iyywppsh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrvkndj.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2irsleary.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2gwgkyzcu.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxtxiac.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhxkiqb.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2eobfhkyf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2llngljoc.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hykhwmpb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2mvsxbykh.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jojgybla.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlizartp.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ptllruuw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2imdcvrse.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhgqhrj.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2iakoyjdf.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kfchmady.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ojeuduui.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2yrcijetk.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2xvsxhqii.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2cbojtbmr.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qsfpwzqi.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ratyvoih.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2xisacuhv.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2wwuclqvg.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2spoddrrp.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2urpckttn.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ehpuprdp.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwoyeoz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2otqymxkl.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lebsyykq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tvqlfxnc.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2sjrupgst.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtegris.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2buwulvse.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2repiymxf.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fibmaqfr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cpyvgzwy.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2afkvzhzw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvyympg.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqbjmkk.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqktipb.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2cfznwnwr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmtyazd.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nypkrler.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bkguvnli.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2olxigjob.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2emhcrkgi.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lcsrieml.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2imugxzhh.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ceysswck.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ainqsdty.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2joaabxxf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2bdkthkeh.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2dgmxoqzg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmnaywc.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfoirzv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhlgtvu.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2syhveytj.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2tfikrwuw.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2icsmzdeu.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbligha.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2uccpcbps.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2gfuhjelx.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2nspcmirc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyieeowh.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vlarobeh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2vyslucfr.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fczmbhgp.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmfdgwf.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2leazzpxs.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmdknkc.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2kvssgizc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhamwmu.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2etqrbuxe.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2jadthhdj.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2gupgndxz.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2cqchcaew.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2myrgugar.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrjlpmr.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxlqgyv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2seyfotzl.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2swipnxzd.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbwrxqd.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhzttoe.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mbawennh.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wgixqoad.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2vnfqqjzm.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cfddrihh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwezkyv.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2lojuixzd.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2yziqzjzm.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2keetjhoy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hmzosjfh.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2hjohayrg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2meeexjgj.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2vgoljckm.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwbgaib.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mjegkfsw.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrejhhm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jwzfrniv.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nqopdzms.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2utzrthhu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2btaszqor.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvqirwn.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2scwmffum.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2znriyknn.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2tairjpdy.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2lmcsinfg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjhhrji.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xblnbzva.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yptrarjs.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qfzdpbnx.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2pcizimtb.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2embwndsb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2zvepgayq.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2astvoowx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2agrqysjq.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2vnfxcnrg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2cnuxrwfg.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2gllwcdtb.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2tghtbtrw.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2npxmzzvq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2wkjarfzh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldiyamcz.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2augffgar.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hnyzqgox.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2itdktlse.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qmyradrw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxhkhtp.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwambha.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2uzaolsty.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xclswbyu.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2frvkuhkb.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvhogzg.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pelrjemf.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hxnmanag.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2nekjekty.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2evnjojnr.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2plxwifkm.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bsakisst.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhhntnhg.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2locitxuy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqzikjzg.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zstjwkif.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjlehuv.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzuqhdd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbucgjeo.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2byuobecn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhjbtwg.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcpoaga.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrqokjh.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2djaklmdt.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2hoyaooif.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2wpekbthw.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rffchmsg.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2uhaxmjlv.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwyyaqo.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ajglcaac.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2unhkohrz.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ahuifpzr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqytrnqo.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2rphofcoo.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxyoxvj.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmlenlf.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2bkoynepn.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2scvjiucq.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2skorwuss.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wawtgukq.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mopidcbm.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2mawljmuc.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2eaiduyzj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtixolxs.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2kiaylfrb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kinatecc.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2vomxflii.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2csuxajsu.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2wisialcd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jusuyhjj.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2peyhuwyc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjkttakj.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mmcithwa.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2yrsphiha.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2aosqqjxm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2axtmxdqp.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2eymauuwd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xazurcut.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtzionn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sjnqxngy.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fjiyioit.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2qjdjvpgv.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2fhzoridz.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjccqgm.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2fyyqynwp.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbakvbnu.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2myxbgian.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cxlzxbbb.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2iserbpqi.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcgvsvtb.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uzofzrnd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmigpfp.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uwzswjcc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzubljh.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zocdvyqm.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vcjlwgac.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2txqykjix.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2trhxhjul.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2osldgxxt.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxtbqnx.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmbmscr.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzyllly.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2owylvyhj.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2dlmqparl.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcncxbuz.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nopgsadp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcosrcaz.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2jhcuqmgd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlnunyug.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2zazpmorv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iokzrjgj.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2etakhtko.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggayuqes.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2txhbyqpz.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2enatekwc.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhhxbyl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqwgwzh.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqagysg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2rejnqzrg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yzcfunud.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ehheyqds.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvzqxhk.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvinpaa.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwkaalf.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhqttsb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2unatxuqk.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2niefkwqj.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwdslnv.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2dorcnvky.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fnomykkj.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2edvmqews.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2nrejqqrt.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ttddiivi.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2djqlmgsh.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gclfmejj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yubqrvnh.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2fltsmwad.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhrrybw.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjineyw.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkdvduw.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yblivfdi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2svizafsp.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvzlfeg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofzbsnwk.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2sjaapnjd.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2juayjypr.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2kqaafctq.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlzlikuc.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fhzphlnp.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2gahlfguw.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2xhccuvan.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbyftcek.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ustqkdun.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbntvoc.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2elvcxvvt.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cscvpwjf.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dncctjkf.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ytfltmfm.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2mkbeqrbv.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgasryos.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tafhictz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfivfcsy.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tyxkipya.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccroiott.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtprioc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2padfkttn.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dfgujoyl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2eetaxwpq.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2kesulglw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lylytdjj.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2sgfcxoee.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2zyzcfuos.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2dzeoxvxg.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqkxlhdg.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tksolwrx.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2emqanlfw.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hamcnqtp.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjckrbqv.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2yzhgwxia.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcovskdk.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2lxfwclzz.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2diyllere.html


<!-- 参考信息 -->