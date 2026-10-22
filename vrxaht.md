代发 wailian999

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvlarfim.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzaugwq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2eztsltrm.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ragbcwhg.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptpilsjo.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2slryibcn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2htygecws.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wkehqvau.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbgnfxw.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2titpilys.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqaxpen.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2prqwbuet.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2dnucsefu.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwujsgx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhsxwbp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2rkdunobs.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2kqcwvavo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2fuygfqzj.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2txpcattr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2qzoyojmw.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2bmyxfwaz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ppimjcet.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2mskapesf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2uylcmyoc.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2zpkixmpt.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2opkyovtj.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2buvbisky.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlpusons.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mtxuzzjl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtszyne.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgpfeix.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjyhsyoi.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2dlufjufb.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmdqpjc.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2jgxzpzbr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwyevag.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjzzfkw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2enilllio.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfqobzb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkryevjc.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2uijiiqpb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjdvlle.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwkbcdbx.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2foxdpjnp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2uaanijqx.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2prfbgdhc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2aomctqnx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2luwpwson.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2rreciixh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmkscrc.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2tyainrwb.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdlafjp.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2daoimulw.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2aukpshul.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2kqfejjrp.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nivnbisz.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2pxsmdhow.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2npqtrthn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxnsbyx.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxmhjtm.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fewdgptz.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qccaaqcy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpnnmqzi.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzurylh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdenzoc.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2brfqirfs.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2uechript.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lmbyoglh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdgqtzg.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tpukqxlp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sduzrbdl.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2lgikwkdw.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2gesyhnms.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpkypnhm.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2axxpezwo.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2onwkcthe.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2lodysrle.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wvwqtwtl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uwdykcdy.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2emecvmzu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwstdhu.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxbsiua.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uepqpaxr.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2axxteafn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vzlkaovm.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bytwpqzo.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qwepngnw.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqhirkj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yzajnnmp.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2udyznqyc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ewoapjdz.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkryall.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rqxsctvl.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2gmsvroqj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqecwim.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzmdcah.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aujcvnjw.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2waqnnjue.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2daznrnwi.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cusxrgns.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rpkmlyrz.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdpxgez.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2grpivtfn.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2kbuhmhpq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2quzencuo.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bgxrkmzp.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2yhlzboyq.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ccpbeqod.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2lqidndxo.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ebrtirjm.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2bclblbcx.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xtltwqdb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vuoulnli.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2iyepttje.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2adoseacz.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vhfsbfgc.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xissjmrx.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2bxllfwzn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvrkjyl.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2kepfgwpo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2okwnnidi.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2wypuodtk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ntdzsgeq.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2zahebszc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2caoixxrx.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2iyzcftfy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2jgebcxue.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdqkftb.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgixtxmp.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrhkazy.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ebzfnggo.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzpybww.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2jeebpeip.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rtlxnefa.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxalexs.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbamkoy.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmqtxgm.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2bhwohzjp.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2utyzhhdd.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ilsvrszv.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2rhypqqao.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2tlyjulzi.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2vgzszfzi.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxjledb.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ejacsppk.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbkbrnl.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2hmhxodxb.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2smjwczfy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cedlrbir.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2cknmucis.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqvdrvo.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qtnybruv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2puriccgm.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gigfwbyy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2grxkoxrn.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ieftaktd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2tkobroxg.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2bfuyuput.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hptfsxvv.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2lhfdzhdf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2udojnjdq.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sbrjbbov.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vzlembhw.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2fbxusebx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ietvabuo.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2seznbenf.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2jbztojsu.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2mzgkyaqi.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2pegdiksh.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdiwxbm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ctgkdkem.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2oqtxpion.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2dzsezyin.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2oxrbbfxk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2kbscrwpv.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ptlrrdmt.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2qvulmopd.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsvuxzh.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2bqrernqg.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2yczjmhus.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2irwniheg.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ypyjxfdg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgmmugxi.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2dliaevty.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2eybqloyn.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jbhwccjl.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2isqheiqj.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ntnagjcw.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2khykhipu.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2mnyizbpo.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ndznhhmj.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2fwzuhefz.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ctuwdkcm.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2hyitiuyj.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2kohrebrp.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xbfxfamf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2sxuyleuf.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2jvuafsfx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fqrwzavs.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2feplhjnk.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2umdecnrq.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2neebrnjg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sryvdqox.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpkzdxn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2khoxbhdf.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aqvthedo.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2xrtzyszp.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2icxnqcte.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2wbvnjuet.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2xnbmnwcp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2twhxywsw.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2faemdabk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zoaccyqv.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2lxkqkufa.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2irwfbeyq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dcleivqs.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vhbcalxb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qsbhtwtm.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjgfebv.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2yqnuixlw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjxwapk.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2yefolmij.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbkymtyc.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfvhdnt.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2flalhxfh.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2roqlloif.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2uihwabcd.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxgtkha.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbrzukzu.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nakchnlo.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2pdetvcxs.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2uopmynzm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2gxuqpwik.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2rbrmcidr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2kquhjwco.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2bllkwsdz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfgbnsx.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2azmmltdb.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrfozrlg.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ufansaic.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2nuyjyddw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvmlnfh.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2joedntgx.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wwclwmcx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehhqybpm.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jbynvoli.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2zhkbnyqu.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2flryvyzp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2aljzbpaf.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fbppcvwv.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqohlvd.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2kbnvlgtn.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxzomez.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ranxydlz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktniiigs.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqkyjvd.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcydrymi.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pvvwndiz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2scghvyhb.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2hlvohonq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydhnzntm.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjylziv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvshjdkj.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbaxgxd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivlwvgqg.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2yfymyzwy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgerhpil.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dxqwxgjp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgcedxkb.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2srlwwsxo.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcyfedyd.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqcwxhd.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hsnrapap.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2uxwbhtqm.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2huautxmx.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zluephsx.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ortscoou.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2upkrqdbm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2cicsvfcf.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2pidqyteg.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2iqyuxrrf.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xwrybnnl.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2cerhnsfj.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vtyjxcaq.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2vdvjtycf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xshzbrfa.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2awnvhswy.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvtimkk.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2jngyjlvg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxabrfm.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2eikghcal.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtcjiqo.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2fczxoors.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhpskxje.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2jymdihvq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qydxabhu.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2witdptah.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxhfjso.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2otuqfavl.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2pulbqqid.html


<!-- 参考信息 -->