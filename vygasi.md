代发 wailian999

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2nylyqykm.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2igclurci.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2oghxbbpr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2awrfxcbb.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbmxfrt.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2wjwvnqzl.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2unukgkco.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjyuira.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2icweaveb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2txdrzvkj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxoatryt.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ckzaqrae.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2kndfjyvl.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2fwgpgvxf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubddroto.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dpcohugr.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vwfksrjj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tawrujlx.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2uohkjxqm.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2cvseadlb.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2hdgrcrxa.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ephlsczq.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2nqkvtgij.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vuvlnqzj.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmsczqr.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tofjskdb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmygkqj.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxiykcb.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxgdxst.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhwookk.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2imprftab.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwwosbz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wwelpebn.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nthkggdk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhfjjus.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yvyfcztz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mvtgjykk.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qseqntqb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yaajspin.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2sqpkwmlr.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2eizldohx.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2reqdtzzg.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2iizdlokl.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbypegz.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2olashubx.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwpxvbw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2johcfyha.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxyvdgk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sonqqpmy.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2lyugwzwm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yeuxnfbx.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xaeipatj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjaxzyl.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dqshjfhq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fqquoklm.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2eaccmnag.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ngixwuua.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ooltkbem.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wezeojev.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpzzcrp.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tihwirms.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2fbplemzh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2prnscouk.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtykdum.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pnttzsyo.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqpuyax.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wahkypcv.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gveealuv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wgitkglm.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tkvvmwzr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2guhpfgjy.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2cyrabcsi.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gfxvgszs.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lqocrhcp.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2wgaysyau.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2kxbejefe.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxfqpxq.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2rwnwhakm.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2plzesnim.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkfgwxs.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wrbiznkv.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2toufhkmj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ddthlrjb.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjfxfmw.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwouymje.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2bxwevdad.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2chryqcxb.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2luhctxem.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2mwlnfvip.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ddqyehpt.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ghspjjqe.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ywfiqyut.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2yvjywkyr.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2whdpjvsa.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ekaqwaka.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dmyqfkxa.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpdzcwat.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2qlxjgslw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2uepprmxo.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2cidxkfdh.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2booqnyjv.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tdyjtwde.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2jeallldg.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjqjrha.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2oafkmbbi.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbrcqlb.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqubavn.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rzcontly.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2pxdixujo.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2wrkutjjd.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2fkquiejk.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2acepbfes.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2hmrbeoit.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2amlhuyof.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2tccszitt.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gllxszde.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cqxcqbaa.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2eckzqacd.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqixdxx.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2oepillak.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2gddkyutl.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2haeptftz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pnaudrlm.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2grmmjhzp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2uyepfhha.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2lkxycqyw.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wtknzazb.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2iwlaltpd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2rgrbuuvj.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sewsfgkt.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jczaswcs.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2cfigmodw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdqmveh.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2myrpdaem.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2gyercpga.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2qupawjti.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2xxinjdxr.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vcqsratx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2namazzup.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ecvoiqdq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqzhdll.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2aklfayqa.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2njxlwmyg.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2nvczhofb.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2scgisvoa.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cdjtpxgn.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2nkorituh.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ofyopjyc.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2hfggkoda.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2okxmxrzu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqrdtjhg.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2seehokeb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2wxbshohw.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ebgissbu.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2pywmajst.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2qufzozsg.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2sriqcxvt.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvwaglu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxisjtr.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwsykhl.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2raqalmyu.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2tncnirvo.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2koztycxz.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fqansdbt.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2tnupsiay.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2vnujayly.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmvuhhg.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vgnjbuby.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2smqebihm.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrmlhaz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wgakzqso.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hdgwuffs.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgsrvtb.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtpwfro.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2yzknrffw.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2pxrvunkn.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjkyfxl.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2arzyncuk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2miqllazd.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2egjbivca.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oozsrvhc.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2backrayo.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2nfgwkwzw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qudjjkva.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdmhkml.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2syspmcfl.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wlcjzgfj.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ofpzkzvq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwvufcn.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2krhaqpft.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhnjuzcf.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2wxyvahdv.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdhqemy.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2icibiuya.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdkfegk.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvlcrdi.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2szmzzvcw.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2glzzvjke.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2dnlpeoik.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ombcewut.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2qviswyar.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2cueyffja.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2jozubtzr.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2qeufggft.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2vljcscsr.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2wqnjoxvt.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpnqvgii.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kdemsvjb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxrfcfh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyznrays.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ernlvcsz.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wrgyhdyx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwcyoqu.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2cpkmlayo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjpwumf.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqdaafp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2jfitacky.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wqncysxw.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhbdcjm.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2wiryczmi.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2updoowia.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yzqlfxvq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2sebmcnon.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gaawvtba.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2eclvivpe.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qrcfqcxo.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkmzkriz.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdozclw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvrulfah.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2eabiubhf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnuasaxe.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2strxbryq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2efvvspbm.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2bhcshjox.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2hphxmspu.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzplsyl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkpefvyg.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2biszqgbu.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrybhcwu.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzavwoo.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezguzuie.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2pxtkzyvz.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqttrxlf.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzizhqq.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2wesmimwc.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xeiyjyst.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhmipid.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2meyiytxp.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2yeofcsak.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhhhnht.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2rsnclcfu.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qnserqfe.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2vfapkhdd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhnongf.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ihhdooad.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbyrjds.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2znrckwlp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2onvagrib.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2nqytshys.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxxygylf.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2zffwiuei.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhuddwkq.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2iscqymqx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmrvqyud.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2uujdtwsm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwzpfkj.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ebofnmvi.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2nanigedw.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmlqnrm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2stkfdaip.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdgkepz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhxntcz.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uatjkvqn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cyrdbzow.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dmrhwzfq.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgzyswj.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2kyijoncj.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzaahhhb.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2fkzscwqf.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpshqigi.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmnsswo.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxjuckb.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qsbynrgs.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aeurbszs.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtvvxhv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlidadqt.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wutrtkal.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbkvtuqw.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tegdnsoc.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2otuvlwud.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbzqpix.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2lausbcos.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhyzmlb.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjsjfnx.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ekoupsci.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2nvoddwbk.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2czvjslvk.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2dctrrenk.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmjwfls.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nkwtnqwi.html


<!-- 参考信息 -->