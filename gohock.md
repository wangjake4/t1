代发 wailian999

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2fswqvkqq.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqjrqea.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2pgfbetgv.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwnfqhb.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cbabuayx.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzxtxth.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kddzvknf.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oghdcgbc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jjraazfp.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qpdxqvho.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2oxingbqj.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kkaljcfd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhtmbhu.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xtbbbnqk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tejizxar.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2wzosxdva.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2unzoaqxo.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2icmmagup.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2eryfpslw.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xptmvvtp.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2pwpztddk.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iaahfvsx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qusmgmlc.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2foqievny.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uwddsegp.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2jzoplzrj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tsbnqlks.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gndlgnxv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jjskgier.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcwwfmv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cdlfekuv.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2sftfrakq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2napdaiwd.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2eywkycrn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lcsuwdtw.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nfofgwjz.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ryxqcmnr.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2aouwbaqm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kjparluh.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yqdzykme.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ycjmzphy.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbbtgcj.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2apkaaurb.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dhfxsynk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iqudztss.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2docjklfy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxxtlwt.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2amqgzige.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yasltxwn.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kigehnax.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2citrtrvc.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2hthkhmdc.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2otvxsvcr.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2basqadrr.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqaouvh.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wprsypxy.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tahfrins.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2vwnhiump.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2emkqqzul.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2udvtffqb.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aepshrwj.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbbpnzo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwsybdxy.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ucnobqtv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2hjvejfap.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ytexoavf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdjyscy.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2cyeybxxa.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2reymnyrb.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhjxalz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2vmkwmkfp.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dxkdrtyz.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmkatkw.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2tyjqbvte.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2uhuqcodb.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhescwb.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2efagzcot.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wfnbbmqj.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2iswuflpn.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lvriynct.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2tkrtgafl.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxfmzwy.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvwdiai.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zqovqchl.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2swuuzroc.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2epdyfwls.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2stlcpzqv.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbnstwu.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvtcucp.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2xptabygr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2tmzvhjgr.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbfypng.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ajcyvkhk.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2shjzhryz.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2byjlcmlv.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wcjcsgku.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2mudxzpwl.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ndvwdxdk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rfvruske.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2dynvsenn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2izpgwsnb.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2xtsodtwl.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ebcozvgy.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2lvkfgfsu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkqyrgv.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tnyrpuhp.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tukuuzsg.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmwhroy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2yupimoss.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hdgzkpxk.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ufcnmaar.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvbaisf.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2grlvwhlf.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqmvmso.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2flpqhobz.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mikewahg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2keeamvcv.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ulawosno.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2rafurezy.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwowblo.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2acvreaik.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2irnhrfbp.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2xnqxluyc.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2hkkhongc.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2svsljjed.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2fmibzbgw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2coyqqecj.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2syghalgm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2amufczzj.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vulmgfmb.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzqijeq.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2nlwiavuo.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2vlalhbgy.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2kvaxbjjz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2voazzlvc.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2mqcnqwwz.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ufiomkne.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2vychhluc.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2uikbqfte.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjjlkcp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2tuteiljh.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2stmaysvc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2czuuvsel.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lfverbbj.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2yyvjpjqw.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2jiqoebdv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wmerpsxs.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwjuznf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2lrsokcme.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlpkexd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2dapkczpy.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvdjfjl.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2lmfsstlr.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2hkksfwif.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwswizg.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2fhykhdxa.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jknfyzca.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhmdjia.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2clygufsp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2evaphlab.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vbwvoufj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nkcfwqhp.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yghdygoy.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2oeukeiya.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2krsojtoz.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2apggcvgc.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2sawctwbz.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ydptsmrt.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbovunz.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2xknpisup.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2gvjdwrib.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvqstyx.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2devucciw.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ffszbtxx.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2vvsjkpdt.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2maktsffc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2qwkzlxue.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ioqlqcem.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfysgcvd.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2hefkumuq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2jtggupoi.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2uzquuxpc.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvdbutqb.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rvrohaqm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2rmrdtmad.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2flysbtgs.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbatbvod.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2akbpywic.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzwfadvc.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xthlmzbv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2mygfbltt.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bjgmnaot.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmwjggn.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2moyhhzqe.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2raodahdt.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2thurvecz.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vsaggeqn.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tsbqmcfg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwcmjqya.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nevfsoiq.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2tephddpd.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2aifhsrle.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gapjfzfv.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2wbgfmchm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2koarzpqv.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xagbwnbp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2udzbymed.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2pnokhmlx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkegfroc.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2xmipkwxc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmyxycx.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmrsuak.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcydyhtr.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2uftdivib.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdlfedmr.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2khuekypd.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkzzeisx.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwsmkhm.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2uajntxtv.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2krbkqoew.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2mknlrvwb.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvrhidi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtwshhd.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2dtfgwccj.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2agyjibyv.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2bjhvahvo.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvdzypx.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2auhpjurp.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2vlawcncr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2keuuxozp.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bbvwrrco.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2yozenloj.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ddnszdci.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdfojax.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2nwyrcvov.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2evxbvpmp.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ippfkuig.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jikwvrqk.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2bccmvrfa.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfazhilu.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2prpbeiet.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2eohhbgrn.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kmzfaumk.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2gcbjvbkx.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qoofkgpm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2srfayjru.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xlygelgs.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxyozckb.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pozahrjt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jkgdlvoh.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uilempxh.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2upbecqry.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2fguarkjw.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2firzjqwu.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2svmmzadq.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjsjbzm.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2xxwqhhnp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ovbtutnv.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2mtmpdher.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dafeaiok.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mmlnjkvr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhfkpykt.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qstqafhj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2yexrbzeg.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rglemrcl.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2liwuyolk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2eksfpkwv.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kwrbjoyz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkzihxwt.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwdqswu.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwcgtwx.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2zgcppiaz.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcatlebv.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvxktse.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2trgtifjw.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rbczvhhs.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2scwtrynn.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2sodjnfrp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdpyyru.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2yfyppzzv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pedhaaum.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2arficiux.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajpuajls.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmwcrlf.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xybgdyeq.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2yfyorljs.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzbtwje.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uthgbqiu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2jbrgzybp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dlwataem.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjuccjh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2okhnvtsr.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zmihdhrr.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yywvmhez.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lstafuov.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ohnlffhk.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2nblvhtew.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hfaqhxhj.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2vbvvsyke.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2declgtad.html


<!-- 参考信息 -->