代发 wailian999

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2huafecjv.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rzwlhiwt.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkvqxxvs.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2khtznjmu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2krvhxmed.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2tlgylcwk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ntklvcci.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrlasixz.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2xozosdsq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2shlsuukp.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtpmbyl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqozgpnp.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrqoxbb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2gdarxzby.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qalzmupy.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2nosdfufu.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pektypod.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlgkbvef.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tpalarkp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2edxbzsnl.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2qozvajny.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgxlgkh.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxomvvo.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekreubtv.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dyzausbv.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ahpmgafa.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2qfdplekx.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2qvrgewgz.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dducnuon.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfrevot.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2vxuxkypt.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hprocguf.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymxdwdag.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2zcmsjcrf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2hmhbivnb.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bxdrrkdw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2khjuaipl.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvxoeju.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2blzxtafv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2umjnwfjs.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvtyhcf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwyauvp.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2gpekxfxq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2ftptoqth.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vjcydwat.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2whqmfyiy.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2cnrrgxuk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2rimgtjmj.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2nyzwignx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jarvsclw.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjldgop.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvmcjkx.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2aahydlqj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlypipk.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqbxpxg.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzffuzm.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2jzhipxvb.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwkojvp.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2txnntqgw.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdrbjec.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2zixuxhuq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ozxbcfxc.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jrghwdjo.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ottuzuef.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2oczgnwcm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2xljppzba.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2apfcaphu.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pcyhbtiw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2fdcochdw.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrmkgqr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwylelxo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yqraouye.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2valjsood.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gixvxkme.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2jhpaywfl.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2jfolfnah.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ihekyzei.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2zhovsaza.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2plmoable.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2szbpsmzx.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2idssnzcb.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vqsmadvd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2pklewlfq.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2lpdjdpln.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mhnofxvz.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tofkfjjy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmsacqi.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kjajvjoj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xvpfgfsj.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tsukwevj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2csxilizs.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nuysqoig.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkgexgj.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rzelxdnr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2iodbhupb.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2dthhlmzj.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2mdfnipcn.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvvpgfs.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2aemvnvlu.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxmckjkn.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2urxsbjab.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2humxqetm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bnyggzva.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nmbhmpaq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvhxmgw.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2oznomijc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uvctanpq.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uxlyrrsx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxzggji.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vcobussl.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gtexoziy.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2zaanjznx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjylfqf.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tqeahhpc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cobcetvo.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzkjccz.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ziiopjrl.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2wkgtqulo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hgoauxkh.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2znjgywwg.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2auqwdugq.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2puyxqciu.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwjyrnv.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iavjemum.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qsutqxyg.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lxaxfllf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqpdvjt.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2yerjudqz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mhnndawt.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zdrigmri.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2fkcatsts.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2zpcojagj.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2rkkajukb.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtmbaue.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2jobrvfje.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wulxbkye.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2scssmghf.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2pmerojst.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqmgskj.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxewufv.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qaihpbas.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2oftljqrq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aeochgzv.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2qkmzqhfd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2redbkupd.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2rfcfvhvv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2zmpiyour.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2fwlpdysg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2xtgclvxn.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fdmhiprx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2azddsewo.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mssohbks.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdyvkup.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ctyuyqtm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2kijihqol.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2fcbdwzbi.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2evjebztk.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lorrilng.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhafxfb.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2dczafjsx.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2btwcxmvf.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2zrnlrtck.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwsjzxj.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cvbznsjd.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2iwoyenuf.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2wjavnkyk.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnfgazj.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwialjh.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxadfmy.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2wkuydfct.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfjamsc.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tcafmhfs.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oprrvvcl.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2cidykjgx.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yqiylzym.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pnnntayi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ooghpqat.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2exzdcfmt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vokqvgsy.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2qywiibey.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqyvowo.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2mvjwjwqe.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oirkoihk.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2zanxmugo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2deytdbtw.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nowxjbee.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2crljcnba.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2dbdgymez.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2gverggrt.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2addesnlg.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvhpxyi.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2btjzwcra.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdsvmel.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2csgtlknn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2mjpawdqe.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2pzcbuaxu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2nhuiqipt.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdlmldl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2tyhwevlz.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2tnabspxf.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2duhkdmej.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rbfugewh.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2kyyfimvk.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ljzyzsao.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2qicwnhxv.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2npnjtsno.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnlqbhwo.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2jvnevoyi.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2pqjnkdcd.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2wsyzsefk.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2exckfqsn.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2fjclpzag.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2bpgijapd.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzteufu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxgwtyn.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2bqozqerb.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2htjclkha.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2wusijdhr.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2olwtuedy.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2yhlloflo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2wbuchhvs.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2barszjpj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gsdzhhgx.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2leyzkrfz.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvgslnk.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhwzuzt.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rldvxmfu.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwjqava.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2lokilaan.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hsqhpxko.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2xovsxvol.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2egcduboo.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvmgutk.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2dbkwqgpd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qnnkrfth.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmroiqz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cnzckpoq.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2exqtywec.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2wosgybrp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jkjwuyou.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2lkxbnrlo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jbcivtho.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2skxnyxyh.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2twawhrtt.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtxysuge.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2bwspziui.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbppojxt.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2pccsjgem.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ceoocvfm.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2xxdgnezo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2tqdkllbx.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2inaxwkfe.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucdzhdia.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zxddhxdb.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2tbyetvju.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2uotxnzhs.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxogwde.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2rusmhwlm.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbevtkn.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvbthut.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2npcynncm.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ohbcovyg.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2najblqsr.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rmeqgwgi.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2ggfwxlql.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jixduqom.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2puxebnmv.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rbplqppb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2wecovgov.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dmslbtmv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjmaeej.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmfjffn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2klismuht.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ahuzdaoc.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dfpstifq.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2qzstvbug.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezruwdoj.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dbokyhmd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2azylucdp.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lplicozw.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtpwrrz.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2aleojkkf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzhfayv.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2xeieofkl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjcxebvs.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rektkzkn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxrhkgf.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jouemvdn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqzzinyl.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2drcsvcwc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwpjunag.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2usooglbh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxicfjwm.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ellldvav.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2gepuysni.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2heeslsyn.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjehculg.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ymixbayw.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwvizova.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dmginhoo.html


<!-- 参考信息 -->