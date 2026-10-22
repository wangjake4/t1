代发 wailian999

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ugbgjtbg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2hfoacnhk.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjcakcb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2iltlwvza.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ydgcqjre.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ktkxcpzd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkgnyucm.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zybvhoas.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwqsqhr.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2wimcxwaa.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppbvgrli.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kyykupmx.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbbhfmi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wwurthjj.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2wgftwtij.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2rkogioqo.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtiqbmh.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2voemtmol.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ngdbnzte.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2upjissho.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2orogmqpm.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ljpywnge.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2tgnisijb.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwoykkv.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aoiksnyo.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2znghxoyz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vntfpjld.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2blsmrwje.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rrecpfvw.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fdkeefuj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bzgccnhb.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmktjyh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pcqnmqcp.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wlrfckep.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtbilnc.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2dbkkpfoj.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2orllkxhb.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsnjvisp.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxjixbzh.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdunexu.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2oahimuqd.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hzccfeag.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bzgexsyc.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ebaaffgw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vscqswcg.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2pnsqbtns.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2saqmmmkr.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qffrzglp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tdbkxbsj.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qtapyupu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mignlcgm.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2yeuhesrl.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdbosfs.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rlovtxgj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2amboeoqg.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwanjeg.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qmszlvxb.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2jhqiegau.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pzejctrk.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjnurvl.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2luglayql.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2rzkcrfua.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xfpzoscu.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zttnhscp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qataepon.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mcwosdvv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wynjpkpm.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2qoffnrgo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2llpozdpm.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfgyhwr.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2kryynajp.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ndomnqrn.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2yycsrywu.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2fbttnlxp.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2suhkxhwh.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2idebbczn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xdavhimm.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2jtasmnsn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2jbfzwqqy.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mdkyesqs.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vskjizxu.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2gghjybeo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cuyfkggq.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2dudmcpnt.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlsgiom.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqchkwf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbvmqlm.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwziwlq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ujisqdig.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mjunbxwj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2onjgcttu.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dxffgjhw.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqwhsmac.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2megyangw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkabzcg.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2fwohbcqu.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2yfrnfepq.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gcyeeroo.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2rqzrvfzg.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxzgkyu.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2lborzcaf.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2shkcvdfi.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fwcdgyvb.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2spavxiai.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2lfdxwtjt.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2uewyzpyj.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjzzzdh.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2scwwdrwj.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2nfjhdumj.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2yzpuwbqg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ybthhjpy.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ykzlsuug.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2psdjrqcf.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2pwcioanz.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwwhfvu.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfysjbn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2shvhswez.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qoihuwvs.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ykobygip.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2kyineyif.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2duabzzqq.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2wdvfhbue.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gntuccdf.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ymkjppef.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2wzyidyfl.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2edypkbvj.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2plscdpvf.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2huhznhis.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ozfxuzla.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2mkkfgiii.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2jfdwauyo.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2doinpttg.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2wktztlpx.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2szvabbbp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ktfvshdp.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgycxva.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2yjfngmqf.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2xeqwgaxo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ofsgpght.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2xyayqzoi.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwrybta.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qijakgvf.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2qehqzlgp.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2pujzfywj.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2iszxihke.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhcigfm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzedwamk.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2moptnikj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2zulioryr.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2htapqzna.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvwkngb.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtjgkmv.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2erhqintb.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2tcjbyvia.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rvafrnpy.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ocypebsl.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2llyftsdg.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2whnxdwkg.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrgftem.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zifzcgvo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjvvuvq.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2eniqbuzr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yamumbok.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pghuzjjz.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvaxxxz.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2yxzhbgtu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tsajfieg.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xudbqihz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjowpzj.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vqnoohah.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2okrazlib.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2yqpvdtti.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpybanh.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2dhairzhj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2igkqrpoc.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2enrdrcju.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxjquyy.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2phymxwyi.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2olactonn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eiosfawi.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2bccmcimy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mcacwfvh.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yhtifxil.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ercppale.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdlmtkwq.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2qzivsvrx.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2cctoivfu.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2fxfaczoj.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkfowrd.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ewgvoaqj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2nxrsxcxw.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2iwcnzrne.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbsusopk.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qpaiveow.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqssmkz.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rlvkthca.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbiahsa.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2idwajvcm.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2esoqfkkm.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2zucwxaex.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ywjdbdjs.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2qnsvaexe.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmlgnxex.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wszpfmhb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2ybqglekv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmegnyog.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpmjski.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhkrwgd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2csfjpvoc.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vucrykvs.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgadntu.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqboruw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2umtiwmxr.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2aajrgegb.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dcmkyogh.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ypsacsdv.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubauycgo.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2teidxknl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxljsato.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eyabdgeq.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ceyopcga.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uwvtbdvl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gohbrpfu.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2jgzvvybx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwifriwb.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmegnpn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ncatesnh.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2cybejohm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2jisyjcew.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2wpemglvw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsygrgqm.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2oicyuxox.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2gchuwclm.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2dvtywfob.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqgifbv.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2tngllglu.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2wihltkas.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2yiykjxai.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxfynizx.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqjpcfq.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2xisaxjlr.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxvmynt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2kyxlwikp.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfhqgye.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2bnesuezv.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2zjsvolfg.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2wpbnwzro.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmcxkof.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxyyymp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgezmjsw.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfiezbn.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2retxiwib.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2vheupwhi.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgenvrem.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2dginpejb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnzeeuxf.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2msxbxnsz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oakvyeoe.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2baanuzrh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kaxokqpm.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2xgahdavs.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwktikq.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mrrsparb.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmjqfjx.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gjsvcnaj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ifzhhthp.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ictjizkj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjqljnc.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqzjges.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tixfvlgh.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ehbvllmt.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2egsbrmtp.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwwaske.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvvwlvu.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtutfma.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtlrkyne.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjddrgf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbinmnd.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwtnuta.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlolkjwu.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lykcydub.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfryaqra.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qktaklgx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2whyngmbe.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2veshhqyp.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rlakwrhl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2pqhknyem.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbroqws.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgudfpxw.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvlzpil.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hrbqydrw.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2coinwctw.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltodnheq.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2isfkohbo.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlqzsll.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bbuumnvy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdjkvlnq.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2htlyfxtb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2tezntgdr.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2urhdrpjz.html


<!-- 参考信息 -->