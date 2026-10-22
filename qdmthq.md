代发 wailian999

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2bvgpcinr.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2wlprsloc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbjrqpn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iiigdsfu.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2lqyzgycl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxjrece.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ylijrbkh.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2wystljbv.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2tmivzzun.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ddagqkrl.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2gwnvwyzg.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eusmxwsa.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2wbeovewo.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uiwqooxv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ztafxpsj.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2mqvxhcfk.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxjkcip.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rjynfbos.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkcfloir.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2igarftku.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwsrkvk.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2amafhgnb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ctoxamsl.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bxaigcuc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2apyliikv.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hutecgil.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hphoejuu.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2vhtaxxak.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2vperivge.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2blzpokbh.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgleqzkx.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgoqexbw.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxwudla.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gehupfot.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dztpjnqx.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lafggyom.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2etvetuia.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2kaqayehs.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkeyqgb.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xixfcsrg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzfszrk.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2adtaijfg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zjoqfemy.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2dqxqtjwo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ikrsogzq.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2erkkyujt.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bbyeleec.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qrchwfzt.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zqpeaitj.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2zhyhszxh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2snmdgvej.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xtgqokqe.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sxohvcbt.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2llytapdx.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tvzuonkz.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vteigqnp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzcpwco.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dgbucsgs.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdaayoa.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2eciuejbe.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xznhpsxe.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wdumzfol.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2egtpbtvc.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2nskchulf.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2kvcbvvli.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ajpyzjew.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2hgsmvsuu.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2duseauil.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mfcsdztj.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2aurvmbjm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ryxtvyuy.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ufzowdxm.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqjhoopy.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2cbnovunu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmljiwrn.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2hrobzwho.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2vywvdhzw.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2gtraghsi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2dwumtmho.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2flzctyjy.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2dsshibjj.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jrntcjeg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2kiuiyksj.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wdngoqzr.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwzrsvux.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2wjczfqlw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2udaouocj.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wqqiodih.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2evlhotso.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qumxfzyb.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2lyltxqpp.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ymjjwtqz.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2nxbhflvr.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2huboulsx.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2plndyxml.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgrafol.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtyjgfx.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2vgrdsdps.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2dpcyssbr.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2iimsyviq.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2uubhsiyi.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmqfkpn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2kzvfhqpg.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2funajrfw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2derzfrfp.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxxwilf.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gevjirla.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gfqosodw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2lvvezyzh.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zfvjqxoy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2apuxfgma.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2frwtwitw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ctpeobap.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2mvtvsaut.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uwfygeao.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2gxsgszcw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2msjiytei.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eoywzbpp.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hdttdewu.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2wugrnddg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrlxagi.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2iocxyucc.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvshidn.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2tyoafnnc.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2utflyigj.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gbxtmvwp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2uzlnutzd.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2frwwelhe.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2desxyzxu.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zesvbjrg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2dubzflre.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2opbubpae.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2csbnskqm.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjbigkm.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2dbovktoo.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2vszerrnh.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2tvkeymoh.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2wplvoiku.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbbzyrzh.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2gwaxmfxp.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2yhamzqlg.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwqxpze.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2umeurlsj.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2flhfsasn.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2xvudejrg.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2sgssblhu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zqiulmrj.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2msiazrhd.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2upqeluzu.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2jhktgwyk.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxikuos.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wubkksxz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2huwvnmeh.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ucjypqyh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wieqczzn.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2djqoqeov.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2dozyfrkt.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2bxghizsu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2riptqdix.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2etnndtak.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2twkfjvzo.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfrqbop.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2lssickkn.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2bpcdtmhy.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2yxomryjx.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ldacnhrq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mubjazbs.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2jyathvar.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hibqnoun.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2gqrifucp.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbepihr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qhtvqtad.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2cnogcqvg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxxusuy.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jmshlhjj.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ruovnvsj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zubxitwo.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfubpby.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcilfsws.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2tvoogkda.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxlvhvgj.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2mhynpcqh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2fcbidart.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dktbartw.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjqqazy.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vphsvnpp.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2mffyuvbz.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2upgwepno.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwmltzz.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2zyjksthe.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbtpbcb.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjxlsda.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxjvxsq.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2suprdkfh.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqnxycxo.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iaennwdv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfevcpz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tanitaax.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzyzarf.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dhexaemr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2itxrkatj.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2fhbcvxrd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2orljkbfu.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vtuqwgaz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2wulniyrp.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2idewxkmn.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2amjvosji.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2tydhytlb.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvtgfgs.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2snxbjuqj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2epmfisxg.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yyptoezq.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwvkpju.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xgjedjvd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppyzlgam.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2wvlzpasq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2sprglddp.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhhclce.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2axbvtgjt.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2uxsoasrm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsejmhfh.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2moliwnvt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2iavxgcee.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2sxbechai.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvemjygk.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2bxpkgsnp.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgxtuhrg.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2sbamcpdw.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxtonac.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzfstbe.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2iaovwrfj.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rmnbmego.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrnzxbd.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjalyir.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlngwfij.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2xikctriw.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2gqtvxuno.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2sjkzqtjv.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzxeddr.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2aqqyuslr.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2eqylvifr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2trnvtgiz.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxpilds.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2hoxukisf.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ctotkagq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2grtojpql.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfjgubu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqalsrc.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmcpmxm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnojrlbp.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2zghidlep.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihdhgfop.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2hxdacufs.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfnfiefl.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hshoaqpk.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2foozjxqv.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ympfchwy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2xvgcwapz.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2redgsldb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxxhvox.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xgnfeqlf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yecvhcbi.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vbwyakup.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2suqkluhr.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2bddiolxk.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdyxpeq.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ektcvncx.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixshkdza.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2quvvtxob.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ccsehrad.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2gwugqqcz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2llygoypw.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cxyxsdbc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgpjolot.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wsuivsem.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2khwofppm.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwktmwrh.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sleloeyi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2goeddsxd.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2huqcfqdf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdpsuhez.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bqiqffzx.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ifsbzvvo.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2fviwapcu.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zetkyurv.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2fjkizuqw.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2djaxiddn.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkjuaqx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmaqryzg.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2cyruhiwn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ficolhod.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2uoftacvx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvlgxgf.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2chsvcsrd.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgzbjcam.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2dkihdfgg.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggrbqael.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdbpjqv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2zypbncfv.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2twfkcrqq.html


<!-- 参考信息 -->