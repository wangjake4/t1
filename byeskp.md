代发 wailian999

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2xgvmmixz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2soskqbic.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2hmlvbnnm.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxnmiqx.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2viokxqho.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2zhzjurpn.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2krdxbjnb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2aufrdfsk.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ujdfswym.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2czzrfdou.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tzvujdza.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2trxviuwg.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtixsmt.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zydxsneo.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rhfwilfi.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bigsczyz.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2nlbnatfb.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcdnvmgs.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2sxisknxl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbnbzmw.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2hihyhqov.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ubnfhcbo.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2soluahrd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2aaktbjhf.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ydxvdjyq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2obxbrpdw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfmckwpf.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2eiglgmot.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtugxhx.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2xrbjrpfu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsgmvmnj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gzehzfyn.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2zmsjjech.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2amkertul.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2eymqaypt.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqmcbco.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ymanauyb.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2eaycjmds.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2mdrrpehv.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vcfidbep.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2oascequi.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwbptwm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2csjklgyy.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfyqgis.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzoixnm.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cbltsabn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lswahxnb.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uzveyhrv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sivjouif.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yagohzaz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ytubtasf.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hwafueje.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gxegkrmg.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxiahxx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvbhcro.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2pnkxfwpo.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2otsicjwr.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2thkwybzd.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbuqyypq.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbowwadv.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjbkdfa.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wukxwbeg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2umdlzrmk.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vtaczifr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2osphevml.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzrlein.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2srvmsftr.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kgixszbf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xueebgcr.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxtdafb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfuzxij.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgjmtbw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2awjariik.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2cnivrhbw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tihcrukp.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rmroahmz.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nmnshfpm.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2otnnkbvm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxsbgry.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2smufvxun.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uczyhqjg.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2mkekindx.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2onpnamfp.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pxfkppkk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xrkwtaba.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qnfrvcpp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rhdclrgb.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2hnfomgad.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sotvaqho.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cqardecp.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2lhanxaup.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ktnqpldq.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2zbbgivww.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2vrskxaer.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbybqvu.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rdyprfzn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fkgqdrcn.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2fktpnqvw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2acognprs.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hjkwjfnd.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mteaxkiq.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2wehicpjo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oiesvlbf.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2wknlmnzh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2vahtaxrz.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2uemirpxj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvufcdf.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ltaiqodm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2iscufffq.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xvifvaaj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2tlabiyek.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2twddhuum.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjvnfqtw.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2etfhiysw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2pdghbzpw.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwmzebk.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2mhvobxuu.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdqbhne.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2dvyrmzsj.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wkkznxew.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdyistf.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2tmsesatj.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2guqrmiuo.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xznhixep.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxpbxsh.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwnmsbb.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2yadvzkzj.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2kpgrldjc.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2trgisuvt.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2wievopxm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ficpdeof.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hqizomlb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xgslbrbe.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ijeazsij.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhirxug.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2plwhmhte.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhematq.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hgozgxjz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kjfvdbup.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2kykqdjrq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwfcymo.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2njoudwoh.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ynydlkyz.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2nrmpcqje.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2swiahcja.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ztotjrmi.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ygpykkmx.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrcjafc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2midvgfvt.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2bummtzre.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2reilvwlb.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2bjymazib.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2lmojueee.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbabqsu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2qaarfvtj.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjaolra.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2crdyscmk.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ffowvxqx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2iisubkvh.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2pobmuoht.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2kfobdwjp.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ldockrqj.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdpcaux.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ednkszot.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2rtixqtxi.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2kjrktrdf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2znmwexqd.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2wytnikmk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2imkqlohu.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2acrsdgbp.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2yqsfzufz.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2xrmokdbx.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2mmovhrkd.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2svhvzzmg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2awluaqrx.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2frllxgfa.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmtaokw.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2czeedkcu.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2gbozpsyt.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2truhjbil.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2pidndiep.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2kpljiekh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ckzspzby.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qeufkzym.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2fotrrcua.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2rdgucecn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2robbbusm.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rtkuvhpw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2qajeaxxh.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pperuyox.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2mvcfvpfj.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ojkigsgj.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2kbavrvye.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvftcfd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtcdyga.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzgooxj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lzcyokfv.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2pivgwpna.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2byefsfau.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2twthyrgf.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2olmvcmps.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bekyhxpv.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqgywpv.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2fukiavkl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnzgtmqt.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mwsernyq.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2jofefycr.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2laurvbax.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2aiylwdpi.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2frsvqgdi.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2oaiezojf.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tyygyhfa.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkifojc.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2txqovucn.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqnmnqa.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2whwxupdq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2gycogkun.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2vermxrzo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohroeskk.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwmjsxx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdsaxvf.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2fewsorrv.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2eugipvmx.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dzexmdgb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2omrqiozv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlsrxkud.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhtzxng.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2biumqqoo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwoanokh.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wumzdaui.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2cjwcnesd.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lyfyibsw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2cufwhfdq.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jnewngvl.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxqamqh.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2miweujas.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jztjkfec.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvenmfh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2crkqsuxy.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzzgjbg.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcqjhewn.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwaroiz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfqafux.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2dzurmybb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbonhyzt.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2szmxtana.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2egyaiqek.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qvhkfest.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqurcpu.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2fwpqqxto.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2laderpzj.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtfygcu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxggnnr.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxbxjle.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2cennfqxq.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2wjsjnpoz.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvntdbx.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2krsjbsxh.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rybmxpqg.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pmezhcrn.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmpwsaiz.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rqucxima.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ioucvbjr.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2zfsdrjyz.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2puragbru.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2musjwano.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkasxaj.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tenaurgt.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2edynormn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbardzn.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxyictm.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2lpimehjv.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2wztgalcq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekowoswu.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjdkvzt.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggddjwgp.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzyckyp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwurmgbm.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2wuhlgwpt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgqxtno.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqmiflb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwkxemf.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhpfabc.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2cuggdcgo.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cfpqmdvm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2cmezbvyp.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2aopfiveb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnnebhgd.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lryobltf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbiofqm.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ajycsdno.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2dambzyds.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2wufieukf.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2urfebyeh.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2uokkmyjf.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkbxjrfc.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2yekrhokk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rajydcff.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2nchoupqi.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2awvafsfr.html


<!-- 参考信息 -->