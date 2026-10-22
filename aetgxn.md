代发 wailian999

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlmpqhc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ceezgdoi.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2bdcvndpp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ubyadsuu.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2uduggezf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqojkynt.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fanwfgnw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2evhwlrdx.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pyqdvcws.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkunlruk.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yvskxwqm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lasbdlbw.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2flsxvsps.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tarjcgcg.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2wszyxrjv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2dleukpvd.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmtqzxs.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2icmejdtb.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqvivtk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2pehxbjdx.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2aqvitxqm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2geqkbgfh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2scpihbce.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tdniwytt.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2uszcftyh.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2lldueiqr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qawwltvu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ioqkdzxe.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2rpveklbf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfnqrbd.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2gplplztd.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2yvllnrtw.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmhqiyv.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2pepsiirw.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qblhklxz.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2txdzieem.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2njgyydcb.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ibgydhsk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkrknva.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ollsusia.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vroaqtea.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hsoyhwoa.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdoywob.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2szwlpvrr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxdgxng.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxucmin.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjvvfon.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yejccggg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjxivam.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bscnrsoi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2uywnmsww.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2zxekribd.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2qjoeejql.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlgusjfq.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jombiqdq.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvvsdzh.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ahitrfhh.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbtqexv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjiidpw.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cjywbzpt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ocyrcdod.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2uvzhdugw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2srsneqwu.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwzantb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqjyhgq.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2eoyqxocq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2touooyop.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2fubxckoq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxkuawl.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2sllisohf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2donwilts.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dcnsjbws.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2giidgafu.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxnoyhw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2koofipvi.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dzpghhjj.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nmecuqqo.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwbqnmv.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zsrdobeo.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtlflyo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzlocjo.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2sumzdsbx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdyqkmz.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2lpvgjgcs.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rfhcrcng.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2izrzbzmp.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2aepqwhsb.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2xnwrolkp.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2yidldvbl.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2wdqygyeo.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2cjyjxlle.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2atbonyyg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jzyoibpw.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjohqvy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2qdlzyetn.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kzexbjww.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2izlpqlha.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2tvqbplnw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2huqpcgym.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2nzaxbhom.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2bhglsbne.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ospjpngr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxftjng.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2etcftxqi.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2qimzjvnz.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jgsmtkvk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ypplstgo.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2svpzuzvq.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqyotrz.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2wzfkbcmw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2oxixwkxl.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2yaemuciq.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2rvjfqijf.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwrvyux.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqpbror.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdqdfbz.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2vilzsxjp.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2gxhapexz.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bnnpfnmw.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ykrdzmdr.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2vlgohorr.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqpvdhy.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ccziinmu.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qibpmvax.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2juxolfmu.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfudrhp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2wdgozyyi.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tokdhjzx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vpssvvqs.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbzrzvg.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ledpfzss.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cvtaltwk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2mzadrcjq.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2txihogzj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jbbyazgf.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2pusoklum.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfucxxq.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvhcosu.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2isrdioml.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2htygdldd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2bioywftt.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2usxhrrbz.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kklkqzmh.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2pustqbll.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2rcqsrvzb.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vjpktgtt.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2geemxbkc.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbxnkfo.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2qpdnbsvs.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2terczdsh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2nsbcehdv.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2cadebdmz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2fdmqrmey.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvddfpe.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2pwnvtjpb.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2acwflcfa.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2irvqhgpt.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jlyslzjv.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2siqtlrgv.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2bxbtkghw.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2omsfnsyw.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2eccuxmke.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgomamir.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2sjuahlvd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2wxzsuxqc.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvigggn.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2daomotrk.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2fbrwqdwx.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2rotmvnyl.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2mnuizsum.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdgyetu.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2lrieevov.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2rnlfhcoo.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjnxmjc.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2zpszbcvl.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qkvpnszm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ldijemis.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2geoigrop.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hiocdlgi.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gojjafau.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2emmsvcdd.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2vzvkpvrl.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvnqvpy.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2flkppokq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2nwuevmxm.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2clanguik.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2qoywkyah.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfnhnhz.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqpjhrt.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2gjuycvuv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2njzmqjga.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2giblymwf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hvrkbdvd.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2lxsusqlm.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2kmfnemkn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bprfrjpn.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2xyyoenrz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tiuzjkjk.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtccmwr.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2waenomrk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrjzjks.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2qcuhfxiq.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2soogagng.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2fdyuwfft.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwrwyjh.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2rvgegzbw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhkwrhg.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kiedovrw.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnnbtrza.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fqimqqgy.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2lssnamqa.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2dneaefyg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2omobgejk.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2odryfjyf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppucokxg.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ridiovsz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwtjshn.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2iwnepfok.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlbwxnkm.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pzqcrppr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2juyrqjzc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbtddfe.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmbygwgd.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vcuwhash.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmjiugxf.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2aueadagv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2zaopxgzo.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pnnmshxv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2sxecmlxq.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2chdgjlpw.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2unwvtkmr.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2tizspmox.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sacyiehd.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oeacmeyh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqaqfjju.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jwhzdzdv.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2hitbxkvf.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cxlipmej.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfjwnwjw.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2swjlnlwa.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2nudyuepw.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2piqyzvae.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2joavbefc.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2snjvpmuo.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2slijvckk.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2qlueaxxq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjcrnhru.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ofzxxilt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwrebvnb.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2glejxiht.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2corkxmyv.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2mhiqtlwm.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2zeaqtpud.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdtprri.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ryfbvauo.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nceynutp.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvdnkbw.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmhbfth.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2raxcelpv.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ogukmyjw.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qmrtgxtc.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jslnrvei.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ksivtjfp.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zjnnqnsg.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhjobea.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcfrpdmh.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2azupbeaw.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2jqmstupd.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2nkwvzxsh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqbkkvtj.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbawaln.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2voigaddu.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2rkphugcf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdalgoyf.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtedeek.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgsywzkb.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2sfuxtpcx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ruzppsoz.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2izefiird.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmpoqos.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hqlqqcdm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvvjmre.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jmudrwsi.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvgenubj.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2imrbklxb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ahugjyxi.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lwktydgb.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxwonlt.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2bypxzges.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmptxbdh.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2bxhmxwvc.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqbrvrvn.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ezrtqebm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2upaguksd.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2tjcescxj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxldort.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qeznwekb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqfancj.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uhtelonk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtzlofw.html


<!-- 参考信息 -->