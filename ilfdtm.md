代发 wailian999

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rtszgvqv.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2axnzresw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2poggwvyh.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbgxchv.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjapqef.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttidjyab.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpdfczj.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmqrhlt.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2uakpbaeo.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tffdfrkt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2juhouefd.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dcnrzwxc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tvacpudh.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2mythwznq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hjqxwtvm.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cybxfvek.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qiujudse.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwmiqao.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ntpkfwhp.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2gfcebodj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2prxdbqwg.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2frrpyrnd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uiajghho.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sgitdpck.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iacsldkm.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvkymyc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqudfmy.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qosghgqq.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xjlbbjbz.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2aazxjzby.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvasnju.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nogpyjob.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jvasupzl.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2griagmbs.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mxsuzzmp.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2pjcxmtvn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnrdzvn.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qgsaxawf.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnapnnj.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdvqrpw.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdsxbfi.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2qdofonvq.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwmanhg.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xndplgoe.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2buwrynrp.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2styivsru.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2hznfapsw.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gavztunq.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqrjrkwc.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2jrxmvnpd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjujukc.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2locndguv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2bjsowfxo.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqllyla.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2zpflkcbs.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2qdiuvpnh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2anuiywso.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ozycffuw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2dgoywcgb.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2inujrdol.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgeqners.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2xhgqllxo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2dtzyqayl.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lklwlcjt.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwrwnkh.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ffgqnhec.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2rxafwplr.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2spxlekcn.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ainnuthb.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2lqedmrkx.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2awnqyejp.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2baintrsr.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwtfcka.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2uyspefcf.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ejrleadx.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ggjffkpt.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2bcwxophf.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2zaynryhc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ztoshahg.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zsauckog.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zaaoqcsa.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2uzsdmqvz.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2abdauqbn.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjpplao.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjipjni.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2izqdtxlo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uwhptcpb.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2vkmjkgeg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvsjdbv.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqczaye.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uqmnjwlg.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2iftzoigr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2xprgdkww.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oatworra.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhftwqp.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2dvrzgzpf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2wintvpxz.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vcgeorfu.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2unatyzxg.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2utbqaazi.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2rzsgduvg.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mpjhdqco.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2wkyedvej.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2fylolrmp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2fcbsxdwx.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2oezofqez.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2bewwcfpg.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2iahyxtyg.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2xqzimxcr.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eijrzfqq.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2rxeiiwqv.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcozmyz.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2phczhlvo.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ebcggirr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2gimkjkhn.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2kqobrlpk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvcjmze.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kipcicze.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvjeedl.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2poaosare.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2iybtdpad.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2nnarugko.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhwlxpi.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2gemfxjul.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2kilynplh.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2wznuuzdv.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2pgfjhkme.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2utnlodwc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2egkgcbzq.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2otqjesyg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwrfnjp.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kxuqueqv.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwhkvwa.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2vkrbdipg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eqepdrvk.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cchryjvh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2vwkqgwdx.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2khzcbrma.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2azfhuytp.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2grjlfenx.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2hbycyhea.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2edxerjzy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nyxrluvy.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2dwlyrpnb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fktarxiy.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmpmfaf.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwuubmr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uqkhoxjp.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2enapnhkj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aocyyvom.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wyicgrwz.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjeyydu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkaldlq.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2rjevqeot.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2vryrpswq.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2lwkzgrxb.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2javfjftg.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ougbheha.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2xejhzvkq.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jyyfdpww.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2goqvuyzx.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jzffajns.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2vewyccvg.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzqabpf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2mxaiaxwj.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ravdpcky.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnpdlezb.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2cjjwlazd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2hukjecdr.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxtottc.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxzqogo.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ilmzbmdj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2kfcnmgwh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2skjlrnjx.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zoceelci.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2culvcmut.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2erdirupy.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2unmirmet.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2mbcdxsuq.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ydbrgvza.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2oxexcgrp.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhspwrj.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2murfjhou.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2pjmherim.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvuzesiq.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yxucxvjn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2aeolrtqk.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qjnmrrln.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkcdlsrd.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2utdlcraz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjomluqq.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2bbonxqvj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2akiviucl.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwrdtwk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2uugrcrhm.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbrhwjo.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2alkyznht.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2nnuvklqy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xakohxlv.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zizwggyf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxxlvza.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hbnszals.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhwzydcj.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ipadtgyh.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzcziwzy.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wacxxzpc.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzzrxjmm.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yfgrralf.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvzkerol.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xuthxwhc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2sijzzcue.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2jazgvhhu.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2tepxxqjg.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdbotrb.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2qtyrzvpg.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cisbygts.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2xpnnrzhn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2llonpqsj.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gcfornxd.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2yukwaqzw.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2pwlosbmw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uccexols.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjhrgol.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdzzfhfv.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2czhikkou.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipsjdcae.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2nnthvjwu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqbcyjk.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2cxozvdfd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2whnhjbit.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zlltxcxt.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ywboylqa.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2glsemrbp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjcbgcp.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hqdmdrxt.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcndvugf.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pcoymcbp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tityxlwe.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2duafrrzq.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2htkflaak.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2rlzkygub.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwpxhxpv.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2dmcpeagi.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eewmuorc.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxhcqfz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rnlzggga.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qyteqker.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2shgasnco.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2shuxqesk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vssulqbb.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nmoyajfa.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrqxwdv.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzcnxzjg.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wfasslwe.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2qyaxvnpt.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hjvyaaem.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xclnnhvo.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbwiwgm.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2efikzzdt.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2uimvyato.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdkkxnmu.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmegvab.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhstucta.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2upklmsjv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zafhgwqb.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2kdtdmqew.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2clutfoir.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2yfgaxfip.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvoalbav.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2pgwpashd.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtllold.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2fdmamden.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdkrgosp.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhkvcek.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2qxllthxs.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mlvhgjti.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vhojgnvl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hujwnlzl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2behrubtj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dsahbiwj.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2duinksfp.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cucfzyts.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aftbuhgh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2qsolcfeh.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2uxciqpgx.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2eqyukukf.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2spkbutmh.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qnckoycr.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gedhnpik.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbwrsch.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2rfwgpgcm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxnkjwxn.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2iukikodg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhepieyv.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2tljhqfmr.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2kywafryk.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2comkzpsp.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhcraqm.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gudrrksw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2lpvptdrj.html


<!-- 参考信息 -->