代发 wailian999

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ajclzlih.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bldovtwt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uvlyypqm.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lxcpejhk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2utsejrny.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2yklifbkz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2chzihowl.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ozyyorma.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2anqipdrt.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjtonlf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2clexvmpo.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2cthzssfv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lyawfiss.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fjzqlmin.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cgcarjvr.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pthpdxgv.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2njbmrxpa.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2wzztuecb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hffrpwgi.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdzodas.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aftcimcj.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2fnkmxzys.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ubravydh.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tudlajqt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yucwkqqj.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gghvhddd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yltuoqlt.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2agtvpbmi.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wljulcud.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2daofcjtw.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2zhupswsk.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrewhka.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2iwoogdhv.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2nxwvnwdk.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2fwcdrvkr.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dmbyjkuu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xxwfufej.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2frgmksrr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2raexhmfn.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fkgzwyjy.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kefxtafk.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2yutlweju.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxjbgec.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2biytgqro.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2gvggjgfq.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2qwztofbc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxigpbt.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvkqkbe.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkibvab.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2acucalqa.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ueviknsr.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bveoprpk.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qivaugbu.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzptavv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2dhyewahh.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmsgnjb.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2gsgkebjs.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zfntfaxt.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhntqgh.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhfseji.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmmuoww.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhhutfk.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2itdfbgml.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qgjoodkh.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2jgcvhuit.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2xxwlnuan.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqylfko.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2klutonoq.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwazgib.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2qsihgoqt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxlwloc.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qedvpgbb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhyyxjk.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2mxfuhbsx.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzeaygy.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkhvigb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtqgfxr.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2aemxhkgf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hrukcoel.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2gygvyddx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2mftqwsnq.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2rvlcigvm.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vslgxmjq.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2syzuystx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2veaczqmv.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2othcixoc.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lpuzkmls.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2caulpode.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ftsxudqs.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbcrujh.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2hnrvinex.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2nrvlyshv.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2xzxyceyr.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqkskjq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxprume.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2sutqtnkb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2iharlzxn.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zsmvsfqd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2bagpeggb.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2hoezhugw.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2hmxthgtm.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdqgjch.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmafrbn.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2hmdfxhjo.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2serqwmdm.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqzsxlv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckebquga.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2gotbobln.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgknarf.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2evuubeav.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vikbrkmc.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhflpfe.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwnyjfl.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjjqsty.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2leqbjwiy.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2pswqnrqe.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhprhkd.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjlqwnd.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhhpsfy.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqfobpj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ddtkldvd.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2hctyszgj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aqwbwpxd.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ygoyyrff.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2dkxrtpvk.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2izfgfdlb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dwcxbonq.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mmnnynia.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2wcommwyj.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmajezg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2emjfmpac.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvalhsb.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2zbcwccem.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2cdcqzydy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lutwuzyh.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2rllgzueu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hgpnuuzy.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ptdragpe.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2fqufqgmk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2labtkomg.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2bzetmvqr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uywsymrx.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rzuqgvqs.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2tnugwiwh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nptxbuzy.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2pkqisbeu.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdsugye.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jmxzqhoc.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2jobmwuia.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqjrskf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2oxvgqowk.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gkeltlva.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2airdmzrv.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fsluzebk.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ftcvzfbi.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2eyecnail.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrmwodc.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtqagof.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjamhbgg.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2yoachsfg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2rljbzvpf.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2efxlscgt.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpgxfzct.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmsvoaq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2lgmypfdb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtobavcr.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbubifow.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ozsfbwqm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2jlvgdmmg.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rphxludk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2vzsqijdg.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dllgwkqb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2fzdpdeby.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2iajbtbkp.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdopqwy.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2czfkfnjz.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhpmdrva.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2flfhscys.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2pekyhofn.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2aindxrhw.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwcklax.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2eiickpwc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfatkdni.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2jlfgsbwd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrtgfpy.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbvmdee.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2opdzpdse.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2iisqukdq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkdnkhhp.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2zxfomadp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxrqlyz.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2orhgfycz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2kijsczsn.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fkfzwczm.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2prkjtadv.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ybqfddqw.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2amtjsbsu.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mkhbbous.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2itpdbsrx.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2onkxymrc.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkrvwcrw.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xaosbkqe.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdntsilt.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2qfbunbkc.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ykfzskfp.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2anylpprx.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2fupmcbfx.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yziaecjn.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2dboxvkhv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yiegewvq.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwdctzc.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2tcnnrjwm.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2dfxchihp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxclxdiw.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2alzltmcb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhflsbfa.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2yvedftwe.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mautxugb.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2hwalwbtz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgneckfq.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgycdsu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wemzirum.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qbtuwgwr.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zjybvhcj.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kgzvxvvh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2plxszgaq.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmaxpwe.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibbcrxfp.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nfvvdcmy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxwalwa.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ettululo.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ujaqfcnj.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwryndz.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucusngtd.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2jydvkwgl.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2myjfnnfo.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2svrrlbcf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2imyxeneq.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmhwdwn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wszosqnn.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqqktrh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpiegege.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zaxkgwqb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmedkesb.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ruokmavp.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2otokqgym.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkvgfbm.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2pzrhcwyi.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjjfoni.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wohayuwx.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdyqrmg.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqxbtie.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewytkmmr.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2anzisanh.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2oczvosim.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjufvsn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnelswf.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2miezeghj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhisluz.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2kxrihbry.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofvjdyma.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2pfleumuz.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxlsibpw.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2wbeofswa.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2obrfslyr.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2amfgmnff.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2pucqjwzd.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2sbhnckbv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vqsmacyl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gbtbiwgl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2xjryidrk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wihcfszt.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cnrtulbj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wjfavnie.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rofwjsul.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ibztbnmo.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxjombv.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjhxoiz.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2pgykblwa.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2asfavfia.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2exokwldj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkduehy.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2xppahasc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eigzbsyy.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cngrggts.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvtbheb.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2egycqosb.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2gydymyvg.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ronmosib.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2yhbfzukz.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2oqzvhezn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2zywiabde.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2cybjylqr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlsgykdu.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2soqvpgra.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jswzjaxg.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2iszqyqaq.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mijuudfq.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ryaykmtp.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxfehlca.html


<!-- 参考信息 -->