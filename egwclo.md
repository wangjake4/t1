代发 wailian999

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qxsqwrsv.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2itrsfnru.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vpqdwzdr.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2fnwipyps.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ckpznsmq.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfldvhp.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2fijvnxiu.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2oglbkpdd.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2hksmdchq.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pukpppwh.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aztahanx.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwjlxga.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2itgnzyct.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2kcawggrg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xpssybqp.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ieainbjf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kuewwffx.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2owkqjgxx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2avrbdmrp.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvrzhyr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dlwiizbg.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvzpoaz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gcbsqklh.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bcsrpafo.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ifpppfqm.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2mkderpap.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2welsaboe.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fbnkwfmd.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mlziioxj.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2rygnkzyk.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnuqaiv.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fhhyriyc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtpyyru.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dumllbro.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbzpvru.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2khbddrht.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2khzojxrq.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvuxtwi.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrrdtxf.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ohoxinxm.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2laemihdh.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqgwyzr.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2jusgayrm.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cghqqztn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrqwbwa.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2pngahdsb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2xhezyrar.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rkgyglmd.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2asdacbkc.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2wusdrvud.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2figeqldv.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2gvfylcyi.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2xtotgmql.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2mfybjejf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2haomumor.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2tznrzswq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqmffqo.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hghnhuuo.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxpmjmf.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2diwywmnj.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvlbrfqp.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2idrlrecn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2nxkodqqo.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2togxpxsy.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2lmlnddky.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gmwfzjbb.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwhnbni.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2qjohmvoc.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2bliksvrf.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2vqlsaqow.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqtarmz.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2prmqrurw.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2voinbfjq.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2blrdxaqw.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2mqdzleht.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2fgndxova.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2xybopovx.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2jyvlgejg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2vvdcnvuf.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2prvccktl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ckwdjano.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2oaaibcbi.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vialcbzn.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhefvrs.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2laezztxr.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2iqgkhrhz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fbkkprcj.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2drujtafe.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2xpcpsgug.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2cokoltfg.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hwrdgxkn.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2vrgysrvv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2rimmxyra.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhdwmco.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zhrfktrc.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2zilgvkae.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2zjahrgur.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjoegqg.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2qxayuyhu.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxpqclv.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2coykrzvm.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2onosekpv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2rdtsxiua.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2kttygldx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2capnuruh.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mfrvrhob.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqsxccg.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2zudltlhh.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqaqyws.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hewohoxx.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2vrxkuche.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2rirartyl.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkbrmnl.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2odjfbqce.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkbklznn.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2wacoeuxq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2jkdvuwko.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qweckblw.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ylzidmgl.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2knnvyfbp.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2rvjqxoyw.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2didrrmed.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnqteyj.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2modlhfiz.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2agdkyzck.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2cjyankcq.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2tmkugyhy.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ggniiach.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2nvfdgqwp.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2kbbaeesw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qlycjhnz.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qsjeohaw.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2qztbgxkp.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2kozimpob.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dvwgbxrl.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxleyhh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2tntylysv.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2expdmmxg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2yiwhpzae.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2uincdnxm.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2wxhwlvfc.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2gazbkqyl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tdvcjibr.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgwcclf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mobqbygj.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2xizcpfkz.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2eytjrqhq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kahruqub.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2snbfcewi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jrfcqtoz.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cagstfkh.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2xppsusnt.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpybaicb.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2kaugijpt.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2jsinniik.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2woaayvzp.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2qphrxtao.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2tadewzhu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ubrlpxpo.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wzretius.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyrenfbr.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jwciydmk.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2oqzttioz.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ykpipioi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2miuzhyes.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ujyavktp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhqiimie.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2rnyfcolb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvelfiy.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2kdruqjgo.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2irwwwnuh.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fumgtqcr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2jydvvirn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmvtakvo.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2eredvmyp.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xxuohocd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2fefubvma.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2suygilck.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2yklxlaby.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lqqujaog.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdqfhbp.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mlzhxfft.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2pjuanixj.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2xiqhdpfu.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvohbjs.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lmbemoqz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2itemhhyh.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqumgul.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwqtkrn.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dopceyxq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2drnblegi.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgkurxn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xyiqesjx.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fltubjbk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdwdyff.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2tomesbud.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2wsarmryd.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2uimevffn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2aptrfsgd.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2jzgfxyiq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfiucjzd.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ziqynhks.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgxlujs.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2pzokpnbu.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmibxqif.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2gelwzcpt.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ognsoskc.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2agwbseqr.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzzfcwx.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2alkormif.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2wktsltcr.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2uyritymk.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2wdeblppl.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjxgdrh.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2fisactpi.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hlvutodo.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2koucilbe.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yszztugk.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pagowfts.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2avchkfty.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ipbolqav.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwiepezm.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ywkwetiw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvgdojbs.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2vgvfwfyz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mguohadl.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqyblwa.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwxeeom.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2jakmxsya.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgpevqxj.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nytoqpyf.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wwuyhhyw.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhkqmfc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2xmcplmpw.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ccmbdlmf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2auvuabjy.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2enmjdkju.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rhfeazfh.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xhdqmfgb.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2yqokinrv.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2vengheao.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2vamhujaz.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqkpsgv.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jelxqnlt.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2vepmjkky.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jkprchds.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2pfnivhap.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nblnwwtm.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uckgrtuz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2giurnfjv.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wwexbwqv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfemewvq.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xadjhlar.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wxopeuko.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxikvrg.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zhoigjau.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zljakfor.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2syxmfbed.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2kydoiizf.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2aagvknyf.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdtrbha.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2rckoikay.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2ooghiyci.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2heovrtvk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzliyuni.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2yyrlwanv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccpllwpk.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2etvcypuu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwlwqpv.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hzshkyca.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikbibthb.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2vdzytkjc.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2psplyvlb.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2yqoqfebo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2rtrpyxiw.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hipslnwb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wlazeorm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2izalojqs.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2wuavrkte.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qszblrhl.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2awiwvwwm.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zkkmwsyl.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvylimz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxdvloy.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnrvsmn.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2pysfogvd.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2isgksvaf.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2njhkvavi.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kiouegvl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2tbcsxifv.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2wkmolxok.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfpfjom.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqbiztg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uaiwhiwj.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2lhipdjnu.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2gypwmmmo.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2chgajmks.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2mlssicfp.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kddxyabv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2wjeiscst.html


<!-- 参考信息 -->