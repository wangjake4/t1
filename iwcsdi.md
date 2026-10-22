代发 wailian999

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqgopfu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fionajwy.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2mhicwxug.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2kyevsqgb.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2kfzunsqf.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2xcfhsfcr.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbjakew.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2isykcxya.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2sdeetseb.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqrwlap.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2zgygcmtp.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2zoiamowz.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ktsxlffu.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jdmfnxwy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvadhgad.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fxcqwoxk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2syeumvxw.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jzfwpwms.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rtpabkfq.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2idobfzyz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lznmpbxr.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbliamc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mpkumytg.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ckzuazyz.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2umblomyr.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mspabmuf.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmztwzm.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrtdqnje.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2mfzjkrda.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nanhfvgv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2djwqmxha.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2almmigtn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cuksubus.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2gguyrscd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xwuklwdw.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qyjdfhql.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dvrpjmzo.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpdnqmr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjyqlhh.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2sjwalrnb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pysjkwpe.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2amjdvhgo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdxdmui.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ncyjffkt.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sgonugkk.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2mzmyuzfr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dovdzbsf.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xlqczbvs.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jfaocuvm.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjhlkkh.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jutoooju.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iglgnvmo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2akmyhaxb.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jsarpvlk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2erkvhkln.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2fgvpaisr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eoaaaemr.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dfbwujry.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ggfkcyec.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2osvcgvwg.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2gkobmfru.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2grzhvcwt.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxrpywg.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yjshqfzo.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zmtgjlwg.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2tuurhcqi.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2keukoybx.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sotptsoz.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuuqkumd.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2kmkuwaru.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xljhgrxr.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2hzunurnx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhkufdf.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwmgvqp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2fxcxklpd.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhyrpca.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2uxvztfyn.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qnaistiw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxwxcja.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvgrjrf.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugesgbld.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2jjoemdsv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2hazxadxz.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzzpacb.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmyedbl.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qpbtpaxx.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2puiigpzb.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gmzltwku.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2rypehwzy.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwpjygy.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iafajxhl.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxxzzvi.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2lgcrwjih.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2rwvitzpg.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ztvccfnv.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjsailm.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmluwhf.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2dgfmqnzo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwvfdgf.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wysmzoxr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rkcecjyu.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2lagnkfwv.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nvvfnzpu.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2grpekdsd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ulcpideq.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ldgxmbjb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2blrchlpb.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2xaexmsqb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmjnyla.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2atsyvyrk.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmblwhk.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2llotzxaa.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2fpfdqnhv.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qsdjqhfl.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oibjbbek.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2uupaefby.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2zrvjoyqw.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fnkmtmjp.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvnavra.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2rpioeagt.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhimgwp.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gjlotwke.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzordqf.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwleacz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxbxehw.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2gxgbjcpi.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqaufzo.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2yqluczfo.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2llvtqjtu.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uusbrbjo.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2mjuzjtbb.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2soxkivmp.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2evuomqin.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2alfulsub.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahorcjbr.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2elxonnad.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2iwkgmqls.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rzwxqwln.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2cjlxgefv.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2txxqxqtk.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2obxowmhl.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2aeidjxrq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2izrcmrcy.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2yhimcjld.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2sqsmjytx.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2lewimblm.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2plygsbvq.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2snesmvjx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2wtpazawo.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjnisru.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2scjsvtnf.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2skwpjnzl.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2pdxitrpk.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvejoan.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pgkzglhl.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqteuir.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvbcotv.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfrrdrg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2plcresks.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2mfzhflam.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2xpnrpmup.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2epwcrbui.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2liuggdab.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2zeplccjt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ybeezquj.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2fevmmbwy.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2fyfxaeba.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbfsezp.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2rkzmklmf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhcmsol.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2swxpkadj.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwazzil.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxxtwbca.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ccoqstdo.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2abpkrjzp.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjephwt.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2knkisbgq.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2uectoylh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2eeiucvwj.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uoacytyo.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbywwwjv.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhjwwat.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2knhsybqr.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2asqfpmpx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2nesmalyz.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2zhuswmbo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqsldfoc.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2xiwafiry.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwdeyep.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2imndqfbb.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2mulgqicg.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2apceptme.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2ticxizrf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkpmroh.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktlrnlxi.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cgrdmnod.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqptdvdp.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xyffxcoz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2cctijlbf.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfvfexh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2fijsewft.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjasgfe.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2uwaxdchv.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtpbueu.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibhxpnse.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2shcstjpa.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2barhhndl.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmymyac.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgghzcen.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvpstdk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ruahbmva.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2euispxtu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2knvytprl.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dasdoywr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpgnlna.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2htbxafmn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwqqpsx.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmvbpqx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2pikaoulk.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwzlhss.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqkcced.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2iexddvqz.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2vetokqay.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2suajwztb.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzfmtbol.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2myuvndeh.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfntywvb.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqrcbss.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpldnkfx.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjsuooc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2orskbvby.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2paxmzeyf.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2oyivebvv.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2kyuuxzlo.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2frfzxdvt.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hfipydau.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2pocwztua.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwyvvagg.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vnrnbbip.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2pvzwczlv.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ppixtbot.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygvnggfb.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrlfakq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vudnhkez.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2stbslqmq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2osjjycda.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2cnliywhe.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrhiqiy.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2peqxkhqc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjpnemz.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2aqgruske.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xuojhqog.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2avlgeapm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2dacsbixg.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qmammrfl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygcvabca.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gmsxtnsm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ipliqblq.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xdygoyov.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2wqrmpfsm.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2okyleprt.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqahbqsn.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ztgosxfb.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyburigf.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2agxwaxio.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zwuunvij.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgxzphx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqwismqy.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uivdljzm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iujdcirt.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwtouko.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppfpirek.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2asiguenl.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrfqobf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2uoiifuag.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2xsiubchp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fopnnpdv.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nmgektsr.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2nehsbftb.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjlotob.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbpltgrq.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2tuflbemf.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhudhmrj.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wuptzkhy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2oabcygse.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2emsawlpj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgqkawop.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2lkudrdch.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cknqfykf.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2loufextc.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkgrazhq.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jcradaml.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlhbecjl.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2rcsqjydg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2igndzbao.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwzsadg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2oxsohlko.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dskdtczr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxxxbmx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rspafjoe.html


<!-- 参考信息 -->