代发 wailian999

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2psqbdkhm.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2xdqpxiio.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdyuodi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2brxqkrnf.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vadivewk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2geajfunn.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2euxrscis.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2bvljntcp.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ndldumhy.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwitxuw.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2bjsauqxr.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gpuhjltd.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqnmoyk.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fgthzkhe.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2skfrlwpp.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2wjeokjuz.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqrbfqb.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kkshhgua.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwaggqhj.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2acrxywiw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mdrudgja.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hultedmf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2npokngvs.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nbluveol.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ovkmmxrb.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jpunfyyz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2karaqpkt.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2jfkfiwxm.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdgjdqt.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpwusub.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2exsjgqdl.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nooaistq.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2voihuqsf.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2svbyqsqy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gttqrgcy.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zlzzyvgt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nhczfuei.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2hwavkmqk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mjrvsvjh.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrsagsx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uygqacwy.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ppuseeap.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2flafmgfs.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlxlbfu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqnxmya.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ybaxziad.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2djxenufd.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nndraiad.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gursbmqu.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ipquxchq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vgljsfed.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dddrwjbm.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjxghze.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2asoswdab.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dhadfrgt.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxzwkmr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nckmsgxl.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tnrirqlx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rxwepqfj.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2rdnvrdef.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vapiycpr.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rnsdmtkk.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2sxngmiag.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzzlbuh.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2gibwztts.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2pmgfhdfx.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2vqxdysos.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zerzqzbk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwimumf.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2nijktkgl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2yijjgrdh.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2syvyvykk.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwnzudw.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxoaccy.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzbqwqi.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2gpnerlfb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2chlxgcmg.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxhcsvk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxwopij.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2whftfvrt.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2peoqnlrh.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ahihvxbj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2izlkbovf.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qnjbwxyw.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eabvhmfr.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2gimhbyrk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2hkkuyvvx.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2vhkwtwjj.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwywwrt.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bwabcrgp.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2qplmtqfg.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2bndghzdz.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2mtnmcmwl.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2bvazeryg.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2thmtxhsc.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ufdfogci.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ycfrjbvy.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqdgvzc.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2oofugaoe.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2xosbbqzg.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdlyqwu.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2lszoodql.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvtflgj.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2elrctqxs.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2prmhhiol.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqfzoct.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2szdbbriw.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lvttulaj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmmnsjz.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2tfczaelu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tnczadii.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ioempyaf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2sigvruvk.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2cluhzllr.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kikskera.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2czrjsilm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2qhszzmfo.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxqmkpk.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rweohxts.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2evndrhro.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqyvjmr.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fvztbrcf.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjlajhy.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqcljmi.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxqtwkm.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cxsmkzey.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ieasfjwp.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2tpcizlsv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2oyyzwyko.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2viokqfkv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2skljqvbt.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vbncggms.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2bfosfzmp.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2drgpxzja.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvebjzs.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2kphhwscc.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2zvnwqzqd.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2pyamqpuy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgphypcm.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2izopscri.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2zqexschr.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dfbkcvrc.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxoyjgi.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2fhbvecdm.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2etmmggix.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjaeqmx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2muimugpt.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ecfijiex.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2lafqoqtp.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2tcsvbegt.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2thkaydmd.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjpmcmo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2esszzira.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2dehtopcz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvnpyrc.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxthmom.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2noiafvnp.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2genprvfp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ufpdhsgo.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2welklenz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2qucffrer.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wqntnzdm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vohcnjpx.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2wvwpglih.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2lzkdgrka.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmuyjco.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrszswb.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwiagvd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjamutc.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2cgdrtzbh.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2vfcvtugt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cuaqbmer.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2neanhrfh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgwghyh.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fgdumvow.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ckdfmtnx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oenuneaf.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzekili.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhypjqv.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2cwjfxymr.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2fizojgtx.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2xjduqtqq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjxtkgc.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jpjndpss.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wupizyea.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxlildv.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbnlzzl.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2yxgefayy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2glstovtz.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2jjzdelbx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlreadob.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2xogzbgoi.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2uveolaur.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2dplrcqaq.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhhwlpr.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tngcubwd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2tuaynzux.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2beybeedh.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2dthdfxhy.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2juqfjwie.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2twlkhnmw.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ypcxhxfe.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxwgiqo.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2npzqdpzh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2afdoyoha.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2foexoijl.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2voxsnnkr.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2swwwcxby.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcvyakuk.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nvhvwxup.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqioafmp.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxptqyq.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdgexmrv.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wtstnabw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2decjtvpp.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwgeolj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2eupsmsrq.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vuotulwz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2evopfehy.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ehiqcyzd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2aeujomto.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvmucyh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2cecvpqwl.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2umdvlone.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzcjlqtz.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2smyrzcbp.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2slijcntx.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2cykeogio.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2orfuzwrd.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kkuvjfxw.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvnhuimv.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcxayxt.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2gipmhqku.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gujzhgbi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhoqrssg.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxqrcgc.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2mwgoyify.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2vdewzsyo.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2srtbxorb.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxhqwet.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2bjeahsfj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvlfpkys.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxxerwd.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2fxgvaouj.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2qhflyqbu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nazpshcm.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2cifiedah.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpturate.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2yxpqrwyx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2adtdvcde.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2rgkshodp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oosjkqab.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2poielnvy.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2plmsfeid.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zdhfmgbn.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2mnnevhdq.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhwzgzd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2guyurmgn.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2luoojjdr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lyrljboe.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2juvqddyf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2inkjbkna.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pakjjxik.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2twonuxbq.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2xypgqwmw.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2bppxiysg.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfzoxgu.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnohozph.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2jwoaxehu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hwwfrmwz.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qiihuqao.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tytsxkhl.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxstdti.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lisqzomk.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2quclinvg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2zolwinss.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qoatbyrw.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhccbej.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjjedbj.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmctfev.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukltxpqj.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bynblvhg.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zxtgpuoi.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ajkqcoeo.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bamspnkm.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2ulnqqkou.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbajjpzn.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qlmzqicp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2akjlahyf.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2veforvkc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhhaskls.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ypfumdlc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfiyotb.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ennnaeuc.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yovpcgqq.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2uopchdmf.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gapexfic.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2cijucgng.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqperga.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vyeeizhb.html


<!-- 参考信息 -->