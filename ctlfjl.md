代发 wailian999

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwovfbmm.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ruyqkvfo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iguozqtp.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2clamemcb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tojeisjh.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2omsmaknl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbqxaax.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbyahjfz.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzcdvvb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtgldnur.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2gjylrvdh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2uydghvik.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fiahqtdv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdbwquv.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ozpvywfa.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxoporp.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwocbaa.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfnuzqby.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkmulue.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkvbqlml.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2aijjysjn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhtpuuvj.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdgvkor.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vogyaowk.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xksplynk.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2umcnlqtc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2giifzbvt.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2uwiyegek.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2txadhdpz.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2newoilyj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2wxypjxgs.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kmcjvlku.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2abnmqwrq.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ygeoebhm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2oawrivnr.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqlqpxs.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2fzivegka.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2iytntapf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2idnlobpr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2mffzoxup.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2sjzfqhtw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2oyzgpvnt.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2rcnbrcyz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2cvyjbric.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2lpffoxrs.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhvbtxv.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqksanr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ylntkmpr.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqgzpjf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmssspyl.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ihtfqnji.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjsekjt.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbqnnls.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfyajfaq.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwlrsym.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2piqivpyw.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmeyqca.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxcpzruk.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvsplgz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwszldfn.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2kvnjyfws.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2pveywing.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwuusdh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjynpsk.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2adogcjbu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2gfcwhdvj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfipfwd.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gyetsuon.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2duprtxba.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2jomfjehj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2gchcalch.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hrxtqudl.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2gypklevq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2biyylpzi.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2kysileom.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2qdlhhpcx.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2yycpezgz.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2sbfiqfcv.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qwmysqnc.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dlewbgus.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2pesaqcnp.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gpyagwwv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjwwqei.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvkftbt.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2osmnjglr.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2labtwabu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lurrbtaz.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqtmpxz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2atwqufrl.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qwmwqjxk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nlcervug.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tmalrrdp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gzpaksak.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mskxnbni.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2egdaxjxq.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2szjbmwmw.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbnxccg.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2toowilwh.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewuqnvye.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2auzxcwlr.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2tcvajwyu.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lskcpluk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vtlwhenc.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxhdqsz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hewnzvqx.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2rzupqedc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zosazawq.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fznbzfns.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jvobomfr.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwirraw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yrucfwys.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ukxkxbjx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2shtnjhsn.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kuyedbjx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2miirphmr.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sczuiccq.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbqhjer.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2jtasexus.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2utnwxqyz.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2neyvzhaf.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lhahrqwg.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2iowrxuyi.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qcfelzgv.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lyknhrsb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mjurnxna.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqgluzi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tojiyual.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2razigezm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2upanrycp.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ovjabcqs.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2eoghlugr.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2aebkbvwr.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2cvyjrjwk.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2iyqwoins.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2rcfszcib.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2launjgcq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qpidwzne.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2shavwulu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2yclpfhxz.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmjxxkf.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aixktphf.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ffsjtcdq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dufrnblc.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2xahvnzyv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2fxguyryf.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2wtyawldn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2tiuamomw.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2xmjuusic.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgiuipi.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bztygmkz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2tfzzuxxn.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdaerui.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqkvzfi.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdvmyfh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2tphvpzrw.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2oyncdful.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2jaezcedw.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jylwzyde.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gdvozbmk.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jvozonwd.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2oimojllq.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2gdctmzly.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2grixeaaz.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbmtnxc.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2thcyxllt.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2pydwmzzg.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2tvtlouwf.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ebnxlooe.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2dkelyjcb.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2kyybemjy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2iaskmfdp.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tozppzex.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hljveucm.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2hmggngeo.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vniefafy.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pmjfhicp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2oyrlcuuh.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nvfegkdi.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zchlhcod.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2curgrdqn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2njtgiuvf.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxvpjuq.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ecrnnqsl.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2divvfikr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2fwtqcytt.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2najxhdwb.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dfldhhfh.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ttpzlnvg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2vvocwfyn.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lodxzcqf.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2veudaemc.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2tylqazzg.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2inehxdhq.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jgpjrjla.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2uromquht.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2vryqdpui.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2glytgdqs.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbbliya.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2fhcrsfrv.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2amqqbmuw.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2htljmvfo.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2etsoolcn.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2pweagwnn.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2whbdafpa.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2hdvqapvp.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2klxuqmes.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtrkcam.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2gzeymjwb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2aupaoazl.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ppsotbba.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2itygapie.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2eofrkbqi.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2xiymrgfv.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2wojzbtvu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cdvgytcj.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ijglvtbi.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzjaydf.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvvqzvk.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqcrzpk.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ctaeyyxp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2lwlrnknq.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2bydtujbj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2peewsaqo.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2iikxbmdm.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdvoxgt.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvxhltv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xdhihhom.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzhzvoo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2vvesjbkw.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qozcqvlx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrzbjin.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2qegujnfg.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2fmcnhgkl.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ildmltsj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rruacuig.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvvmrdx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ielzlqnj.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2kihvojaf.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2okzisiry.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uipiewwq.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2dhrdssbq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zbeldlyk.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jollpqgb.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ejrmejds.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhimwwor.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ewyfabwx.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2utdsxsww.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2gzarbhkc.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgrxbdm.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ouiahsun.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvbigwg.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2oqcivwjb.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmbbxbx.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kmyopens.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2klljlull.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqxtqef.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2yhoexdnf.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2abrrrrin.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2zybirxrd.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2hzsvqtut.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2qkftghgp.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ltnkwtqz.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2apiqlzbc.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2apxcuank.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2hvefxudr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjcrbyay.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2anwwjbvw.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2shnvzarl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwphtxhx.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ypmkvird.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjcvfdl.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhryhns.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2zldfxnsc.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fixmufxs.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ccwjebqc.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjapmsr.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qpikuagl.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ebahxmcm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxiksmcn.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcxcldx.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2xufhsqrn.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zocupsuj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2itcybhmm.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2lsybdfei.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxbpdhya.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2uflngzfo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2seolekny.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2acmoxeoq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2aswcgzsg.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2vomtixyg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxgnmrbw.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxfmfkn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2qccmnqms.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwoyfxk.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2bycrfdwp.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmaxxjl.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzgnxgb.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vgzkbzyl.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2icxtsroa.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dutoycko.html


<!-- 参考信息 -->