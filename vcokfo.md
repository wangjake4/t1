代发 wailian999

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pswliykf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqmmqtw.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jkyllxup.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uivzkeaz.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwwdcwp.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2edhyuqjh.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2huyfztaq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2brdvvwns.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2llszznsu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ltryorik.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmqmjpl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2nojbmorw.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2fonnsatw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2zoknbmod.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eefeoryy.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrwbfyn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2gnyqclcb.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbqhwjq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2oogapetg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xjcslnvf.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2tskwahuz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jbseeiym.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2mqhgnbli.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2fubjjmwz.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2scwbvntw.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwojcpu.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2tgagkesv.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vbsydpwg.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2oxorcwtr.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqcfxkz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2kvyqlmyk.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtufwfz.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qpohvgtz.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvzzsum.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwcbvyh.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmbcjom.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wqhskhsn.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uykxayiu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmijchf.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2akptqqef.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqzwfxu.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2taoxkxzg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2maadgqke.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2edhulsnu.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2iwitnpcz.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmqdqjv.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylvzlwto.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfxlgyg.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2uwexezhm.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jvcjfzsi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sacbwdss.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnowmmu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2girfjlth.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2tajwbvpp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lchnrmvy.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tsyzjvuu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zebanezw.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nmvmadgk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fdbqoxlx.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnpqicn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xejghhva.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2msdwasfo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjspmpo.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2csludzma.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvmiaeq.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2lomknagr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wosdqdkf.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yerkbebx.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxrclmu.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2abbpdnoi.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ijbzsxot.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2owtdpxyu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rcudbzpo.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmbuxbp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2utbyuccs.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2lukqqbfn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lmeppgmj.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ctaqylvc.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2mhtjjjff.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2hcivfrsa.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2irizbavn.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2plcdpnag.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2fpoupkzn.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2egncoqht.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bteinxhv.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zavoevcf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2azoxciqk.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aswsyaml.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqswzqpo.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhshuay.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipcmepzx.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2hozpgusm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2nuyhtqlo.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2qdkgvgus.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2znxflays.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2skjhquyj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ubelyogf.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tpplmsru.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjwpbkz.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2darwqsfk.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2htgmxdno.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2boeuyvhp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2aykaxmvb.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmxrdbz.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ztpzewxq.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mnoqicph.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtrbyjo.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lzohgsar.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2wucpfrvy.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2lipoogpg.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhzeein.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nknmkmvo.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2horzexad.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2erhmjtfs.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2fnotrrzf.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2strertus.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ftfexkps.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2gknazqho.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2hkddvlcg.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nbpemzhx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yobjyytp.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2enljbabm.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yczfrmhs.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mprpwipm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2dampqmen.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ulbnlqqj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nmxqxfel.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2eymbwlvo.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2nnllzdtc.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2uvukakta.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2haixcjkl.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2zojzrisz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2hevjovll.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdahlob.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lnxjihpb.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2xicfcvam.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2bzvbmgco.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2bviuayaw.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmkkluf.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2htgiebml.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ytlrtigw.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2azdilvvc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2eexkeqyb.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mbypskfs.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2dqfddjyc.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ifnwmigh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmgyxto.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2wixfeizh.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2nlewbcda.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lvuddsdw.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2avizmhbn.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ihulhfay.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2aeaunrmy.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2hhsnnnph.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzeepbvp.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2dpvxxcdu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2rdgylxbg.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjrqxmj.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwtcidy.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2jlkqjhso.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ujyvjzge.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2wvcmkuww.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gjruiily.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2nebikzsc.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2bupcfpnd.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ofkhxwkn.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2zaikuooj.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ykixjmkt.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2grjjamjr.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2hzyvcduw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iuinhqwa.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2depmnjsn.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwyavuq.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2dgiflbdm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bzkfrchq.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkptlsi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2gdesrriv.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nywpfwuq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlsvnmk.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ccpjnvnr.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqpkwbb.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2gvnnprcw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oastclrm.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxbuthf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kspyhwvy.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2jubxowke.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2jdrqzqth.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjgbwpi.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwgykmo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tldackds.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wljszrlv.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2txrirjms.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sycezjsf.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2nbkxnslz.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqtuyrba.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2xomuskha.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqabbgxn.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrnlkmf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxqwvgg.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tesyrhgi.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsbltmot.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2roicqwxv.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvdyfhx.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kkyvcljp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2eotgdosr.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwcaghe.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxnkcctm.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2bocickld.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2lotgbavw.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2nzsppfzk.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2izauzvgx.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lyyiznsc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqkzpbc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgickfik.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qucednlv.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sorhista.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2wavhhqso.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbizyep.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2gpveshtx.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2otyxmktl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2msrjurqi.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nrmvjick.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jnleqieu.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2agiatedd.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qydjkwim.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rylrnobz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrwyiaa.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2moiplbla.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkwrmxog.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhybwbj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2uieitrvo.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2eptjelvv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwrbmpy.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2snmzncbb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2aunwqqbz.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2xxaagkvc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2noetrjdy.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2bclurwjd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltfyviti.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2itwxfxxz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2isijehym.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jiyhkyhx.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzarbrvp.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2oubqmcye.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2fezfdhlj.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2njbhzioe.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjefnyg.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2osfxpide.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2klnhqjth.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2clraakgm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqlzyxo.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2dxijywbo.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2kcajmxyg.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2kmnkfnju.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2dwsevsgy.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zsnwhslb.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpdbyvn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkohgnaw.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gqccietn.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2yrcheifu.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2arjxmpsr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvyfayup.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvdtzor.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2heukiagi.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ypdpyybw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrfbvfro.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzagkca.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufeumtab.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2apmarwsn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjxqowoo.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jrcpadeq.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2izbwdvpa.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uplnlwuv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2xucfqueb.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zysvxrcl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcgzyuqm.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2memcvkjz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qojsffwt.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vnmzekft.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2mxuhhtam.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2zyfvdiet.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbuhofx.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ospqccul.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxwoxyf.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2vlsifklz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2anwudlzu.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2tpteofbz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzzpozoy.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tuylhvdo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpfhpusg.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwkjanm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2sojrqrqi.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrpdvgai.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pxpmgiki.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2algbwrjr.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zpriimfx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tetzxzij.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vuqqvdsq.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hxcqjwjl.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2vifdwvzi.html


<!-- 参考信息 -->