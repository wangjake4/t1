代发 wailian999

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ihrctbcc.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bwnllynh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lhxpqdub.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2iikxbjbi.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dbacsmtc.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gltymnma.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2srlbwzjo.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ikycfrke.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2yafdjsac.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2uqcacnxp.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2aiequixe.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqolrsp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2aptstipi.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2voieiqhl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2psnrisiu.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbqnsjc.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwpuodh.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2lllvshak.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ioifvmzo.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2taeowhen.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2reqsrwiy.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2wagbxysu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2drrbwsrp.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2kkelzcys.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ebdzrcjt.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxviaaa.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2hrcncdad.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mmyrxtit.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtyxyokg.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2saokfupx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxlcnvj.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmqvyls.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2omunosph.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zprpihwr.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjcjfjn.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2fufpurpx.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2rkdrpcce.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmqknus.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ugglxdvz.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ovcfmfuo.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ffqublju.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2rksqzwai.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmqubvz.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2pozlodhr.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwdpdyg.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmzgewn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2flhrqeaq.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2knhioohr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2acqacpkw.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2fljivovc.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ggilvopq.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gcgkxfvj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2yztqgxfg.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxjpiia.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oscuvubg.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2slerwzcd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjyaqod.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2uowwjroa.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ikcblbsd.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2szearvsb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2evvodfon.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2clwzbrwu.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kiccguok.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2qlehcqos.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2oreofkde.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jbpjcbgc.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ixyujjru.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2muqarart.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2udroappb.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2khekuvtc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2fgcefhir.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbcximh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2egabcmlc.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjtcmwz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2nccaonxt.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2nhnhxsul.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2zafafzkx.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2flvovggf.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2jqbcjekx.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnqfxit.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdswpon.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbotzxs.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwomnigx.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2bcaufpgv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2roscookg.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xqynlnjm.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2gaanzhxd.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2oilrnbbf.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2lzndkrtc.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbiqdyb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2okksjfxl.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2dscadpkx.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2inwkkblw.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2kbtcoyqq.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2hxnkctul.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gsswlzyi.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2jogqsvih.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2fnwtfppa.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjemsii.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2uhswcjxl.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2cqsirayw.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2yhsatfjq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yvqskgfc.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2boeoolhr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2zgimkdfp.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzjievy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhghgpx.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2orjqgjkn.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmswthn.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2sxyvldfk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wqgnlwxf.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2zdsccyej.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqnxcgg.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2krpvgpxc.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtaizfp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nnnidzed.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2zlamexsl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rfxtuctw.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hyfwnjhr.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2hxzhpppz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkiliuci.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbojhkw.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2cozflheb.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2esosbblc.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2oknnugpl.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2aaoetzbz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2rhichhkc.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2elbtjwus.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tggzsuuu.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lnzeaabt.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2gckvusyc.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ngriwnrr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2knogovlz.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ywidjlgd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmwgcyq.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvpvnug.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2kvuunrig.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2pcjihyvg.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgmrmmb.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kyfnviyy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2chudscqd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2btxanhqb.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2kokflocd.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2afcdyolc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjgmfbc.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vcjvxhbp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbsjscd.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wmatrmjo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2rxkgpxtq.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2htivvmdx.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2nykrdiua.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxzmgmj.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcwoldxo.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbxcewx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdejpggj.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2acwubliy.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvlsqxhy.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ecelluwj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqpnzkb.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2vgsnwfvh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgitippv.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mrsuajur.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2sarqyuez.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fbnineiy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2woabuvhv.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2nectdetu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2yiuaiuja.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2xecyivxp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2nostqvln.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwdgwyz.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2iptwkitz.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrjpkph.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxktmrds.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2coafexns.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjhvbjn.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2roodofht.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvekxard.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ivrvlggl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdrgwehj.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2zpfixzzt.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2uyiajxxb.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xyppjzaf.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2mrzvhsnl.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kwassmzb.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2nxmctmor.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zuxmbygd.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hmxyhjjt.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ozeyysyu.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2gycevpxz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlknniea.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2rmelfbgc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxybzfvu.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfqjwns.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvjrnft.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2asvvjicp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2keiwokve.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2libgdcnf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2flyoiblp.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2synuttud.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2mmfhtxbu.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vgppyjiu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2sxeguhgv.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vjnjbddm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjogvcm.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xezmpaga.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2swdfksgj.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2knwjabym.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrorzpm.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2shiqgtyq.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2kubgvpkd.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2qqpyruao.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdaywqpj.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbobqwq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2whidnpnf.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2bdlusmtw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgdqjvz.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2prqkvxqm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsezlipd.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ovcyslqu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgmobrrl.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvnvaon.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmgnoum.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfkhtao.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ytffaqrq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdxqjpfj.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jalvaizk.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2famhohxz.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2cqlpcycn.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kalokcdz.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2duijsoxm.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2empvacsl.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pqbrybqd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mynhyfwg.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdgkjta.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vsgygrjc.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2yuyxqfrp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqpmqlwp.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bffcqubp.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2waexqiuq.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2nykodqle.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2axumfmwn.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2hjbgwsys.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2qdthtohd.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zsnqoswv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2gggvwpgy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2egcymxng.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2mnfzzaay.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ninganxc.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2khgitkjt.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xgbkbfnx.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmbdpib.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2jbbstbea.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqjhqwj.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tivztsfm.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtaydhj.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kxllcudc.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ehljlsyf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2eatscpgs.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2btsmqzuq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2btsnhvcv.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hskygafn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2obnpqovh.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2mafoghte.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2blqouxef.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qaqlxxyw.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2efzvqihu.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hapkwfba.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ufdrgbhc.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ibcdbtsb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2wimunqtx.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxhiwbg.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvtlomq.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2paxwherd.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogyntojj.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2iudtjbcu.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptsssbho.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2nplnpvpo.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrzqyrl.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xsrnyfzf.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tclhxibc.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2osujpmwj.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jpbnmubw.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdvlsxs.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2cnugwjve.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2pufbpuex.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhncvhjt.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxtlafu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbagoxgo.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rixnnylk.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewkvuorj.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbcayek.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjmiftw.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kfcnuxea.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkcfuttw.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2pyaudutu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2plegtjnb.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2oqixyqlo.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2hunwsprz.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2ekrxrjcn.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwoynpx.html


<!-- 参考信息 -->