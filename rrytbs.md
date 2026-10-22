代发 wailian999

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2kwshuiej.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ifzwshug.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cslvzlxz.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgxmwhe.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2icealtlq.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbsydza.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvaprqs.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mnvaehph.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2delajfbe.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tavjsucp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2camlzctc.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ikfrctaj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbcupti.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2cgflgdsg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2itlzwahj.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2insprslv.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xqnaaksl.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvamgia.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wxbdbobt.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bdtfxvqv.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jqpndyxq.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2otkoagzo.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vkmtlpgg.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjldouc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hbpqgrjb.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xryixlxn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbecctv.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ivyzjcba.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hafywkej.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qhstiwtx.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2vrytplyj.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxycfky.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxkqhxe.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2vvpjuigc.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqdpojl.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jwzqmwcs.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wwjuyuml.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ugefjwzx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2jqsgxenl.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nmpjcijv.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufosfenk.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2iitjytry.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlitmzfw.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2svjogvts.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2xaegpqys.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2fkanvxmd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2qvlvjotp.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2bcrnlvcz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ixesguwq.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xxnrfomg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2rpqasmde.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2njhxxsoo.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsiugjfu.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2xdypbxkv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2cgsarrad.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2bkdkvhqn.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2efjpffmm.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bslxkbxe.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2dcmjjxgr.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xguafesn.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2sqsbnbwe.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2pgupcgsw.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wkypvkot.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zjrgpunl.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2mqcdggtn.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2uylshgiq.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2nnenjzeu.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2gclqqrba.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2sopfoudk.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2mqwxmgny.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2grodovpj.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dbfpxdac.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xadanowg.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2pjsaycyv.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ximrsaqf.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkgvabf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2dfurohgq.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hjtpujkq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlqwvjy.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhjxjhb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2xopxyssv.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2turtgjjs.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2efyfefgt.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqnmokd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhohkzi.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xkbuctpa.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjttfdp.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqffxqv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2kxsmnhkd.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxmlyxp.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhrbmnu.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2yowtkqmn.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2gaatpxhm.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fiweeezg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkdyvjc.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2wsihsnfi.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2bmnezkgc.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2equuipcs.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ahnnkhph.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2eoufshxi.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2hoghwqzl.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxivdbt.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2vzyilcco.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqdepgn.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmlgrqp.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ucealttf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2epvjtgyf.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2owygoplf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2afariojl.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mzygtxvf.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhwrxmd.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2qtheuazj.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2tkoadtvk.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqgrsgu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2krjydrgm.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2gvkkubvj.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvyoxwc.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2qdkvcjcj.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2lcrdifub.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ijdrkmbw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2xavjpgsp.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ughdswiu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cktrpzin.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xijpiaeb.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2rtiwopvb.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2laxlxanz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2djstceqj.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fitofvaf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2riniqmss.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2waxqvtom.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdnqybx.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2phqdokne.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2mgmqtwnm.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2qikuyuhh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdswrha.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2qwtznjmr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvocads.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2fnpeuvva.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2egthwexr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gbzmrycw.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2wpdxsixz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yjgytpmt.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lcrmqxfh.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2xjsnzolg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cokudbwk.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2tbceicru.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2golknlte.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2utbewhty.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2kssnkjsl.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2abjgdigd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzmjdmu.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2felmumci.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfydmcpg.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wisetnbj.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2torqqabu.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhrprrt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvlpyoz.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2jlbitros.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2opjwftsf.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwiwcwl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2mekehkkx.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2egreulrr.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2htvlckvt.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oighzvzt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2bdvgynbm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddablapl.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbkgpfna.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2abighnwp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgbmwgyf.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2liueewwk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2icdflddd.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvqeepv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2gtybjpvd.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtzfraf.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2gwlgrjcb.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2qttsgbjv.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmxgdrb.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jaynanas.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxqniyq.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mywmtkvy.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbhzydn.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2shyvzzaf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2adrfqlmd.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxskagp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2islwbsld.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zjffkjzb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwmmrwi.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ehgzjejl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqnwori.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2aihvslod.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2spwufwbd.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2kuqyfoao.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulweqvqm.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjoajsa.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2iflpvpkv.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ymloybaa.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2acamvmbz.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2smamqsag.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vljovzcz.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rzwdszkb.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2rftvjiez.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ktirpxhu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmbkxmk.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ghdruqvr.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2onrgmrxe.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2idvecoqf.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhqyedd.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cpeljhyo.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2qinlwtnh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqefhguo.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ntckcozj.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2jptjpfvj.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2mshqmqvs.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2crmtjgpx.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2bmrehbfz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocfdcwbn.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2dborjbsu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2epxtvfgm.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2khcrmsbd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrywpacg.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2tpcyfetc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwquxpam.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2miidyvur.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zvlokilu.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wsiozlam.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2txqffgea.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2waawefcc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kokdvjvl.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tmllvhzo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2oapydlgl.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sbzywieh.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzykuyu.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2dnphbjgc.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2phrcvxno.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2laaehhzk.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bndrifxz.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvnwkqj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2owofbzwr.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2oisphryd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhrhqjoc.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjmfkeo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcuqdep.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sxphdghd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2etwpmxsl.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxpbrdtv.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hmmrcfel.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2cnikkdhb.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2mufpstxu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ciaafsbk.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ewkrftfh.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2yeycdfrj.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2bxrpunqw.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xedouzeb.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2hqieelzu.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2njnkdesm.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ydurtppu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2puswlyti.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2vabonomp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2eikgwaua.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2xsxwkjns.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yowowoiv.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nfptehvu.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqrnnxcp.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2pdidshpf.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fouppvei.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2znolojdn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2xvewnhco.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmvqxvm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjjgnzs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwyzcou.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2esdcfpew.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhmovta.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fuszocru.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwsxwra.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwyuprm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2zqirdpqt.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2cxrxwlwj.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgvstni.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmwmvdl.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2johovnph.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kgoyogyc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2qwkoupht.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2bniovdcj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnkvusln.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbhbtle.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2htwlkqfm.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xnqnitkp.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2tawwxzin.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uugzeukh.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2uzlaplmi.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jaopgnou.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2skszugzc.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2gslkfofu.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2glqpntpd.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgkqtly.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gweatwxa.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2kbzzhkwj.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hapmnyis.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzqymam.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vealpoje.html


<!-- 参考信息 -->