代发 wailian999

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vggwehyo.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cklkhfxq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtrzzqbf.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2rocesibc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dypbkiry.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2jgpnpefj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmahaww.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjcqqsmw.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2daelafse.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2utxfiwmi.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkbvykg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2chcstdeh.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2uogwnhag.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwvojot.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zplvktip.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2hysfmlmn.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ejyrdfvc.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2pallgids.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dcfiehol.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdhggwh.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2vuqqrnnn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmgsgqq.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2clzisyoq.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2boydiqpe.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ectafqcw.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ifprpoks.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2zhjfvaop.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2tbmjtjgj.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdslegag.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ytaymmra.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2jiybcgor.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvyaiwi.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjudwxth.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2fydovdpj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2siuswmih.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2sjaeibps.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ptioxuez.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2israzict.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfbcugi.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2xthaypwp.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2huusotqf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2jivptqiv.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2nkthhetf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2ilrxwxos.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2nmqzcadl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ftvjsypd.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2deszjdyh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2qvcrpudh.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2lpyyxbjk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2niiknpys.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2enoerdqw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcvnruin.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hmlgrokb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhseakkf.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2uriavauo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkhfzqqo.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2mghgypfb.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2melezksf.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2dahphchb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2obbsvhip.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2mgksswdo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2wrstbdzz.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ohpxrybs.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttozukwi.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzxbzyy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2sqyiuhjn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfaflnoj.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pazozvrb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qegmrrrn.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2bdskzqdz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwefzyf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2moknntbn.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ckdolxmr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbiupdf.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2fxcrghls.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkxxcnt.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2zihnwpfa.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ebiehgyf.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2pahrchgh.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yjblinbw.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2xigitcbt.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qqetzxye.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqisarc.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2mtzlzeju.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jhnwfsza.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2npavsoqe.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2acndbzsx.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2utzonmit.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2moppjdis.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2buhdphzc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cyyuydcp.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cbtmyqmo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mmbtotov.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhozvtr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tunhxrbi.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2crehqvlr.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2wnmhtbfv.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mujrunxd.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzdtgcjw.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jczvmvfk.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2csmbmwys.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yhpurjsy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qncwqlti.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvtglou.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqqddpd.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2lkyoeuaj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqsdgmb.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2efibglpn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrpyore.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2csvmvhgb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nuolsnvp.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2abgarhmk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wpgtocbd.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ksbzwill.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxyxbtp.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kbajaloh.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbhlhks.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2uuzwqptv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pknknamg.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qdcnswuh.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tmkcyvtn.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgpeuis.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zzyvwonx.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fgmesvyn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2troxhdwv.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2peoiboct.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nowsumdg.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2nmbozfmc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2utmxpwlo.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2syqtqcku.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2wbiybegt.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2wdriasok.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvqthuf.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2dggkdbhf.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2keaviugi.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vgoyakiv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2frxiqpex.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdldqej.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2rafepmvw.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kcrmdvch.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpmofydd.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdxyakj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxgrdpwm.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2sgcraypf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2derrsuah.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2xcfkrmrn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2apcqkjft.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2znalxvig.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqicfgf.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xefwasrj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2tbxpwnpy.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iylezxuh.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lldxatsc.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ifncuqgn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqzrsls.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xvynomct.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwkfkfl.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2idikhljk.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2umcvdqjq.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2nenwxwmt.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxfllwa.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2winxpenq.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vzlacyks.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iupthmvl.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2pxlqjzon.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2sczlvwsz.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wojfohgs.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2luufoqgj.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2aqrkltzo.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2zgcikpxd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2btnbifdg.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtygppv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hqteiswe.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2vrtyrxja.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oucbayox.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yybghkre.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ttbmplgx.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxclago.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wzsguday.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzcprlj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvdfthv.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2qdcyjsml.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sklwmroj.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2rpofkowy.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbexmea.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vvlxmtsf.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2thuxhktc.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2cusymuxi.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2hopfpzni.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2txyptjdj.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2woespftd.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2vfumgkes.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2gpohhout.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jcvlizgz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2yvuoxnsb.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2otiajghq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkrvwwr.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2jurvwmks.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2tkolpqpk.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2upwthggs.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2oqqdrres.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pcqrlpqy.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbzmsdv.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2fxukzknu.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2qiiuscio.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ihlnzveu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2btlpabtp.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2glsxmraf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwefamb.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2sgrsxycx.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2fjieqiev.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtfsdwi.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxuiipr.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2wjuwhbtk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mywepgek.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2yzwpnybg.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2kqsmvnro.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxdglgb.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbrgbrv.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbtpnre.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2yyeptqtg.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2tywyghup.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lkoceouj.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2olmpekvk.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2kncqrsof.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2kboisnaj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfpcgzh.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2efyvnntn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2gtckjjoy.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mcwnodcv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2eqrullws.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2cnykqyyg.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ocrtcizv.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzyxlvb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2duxrixyp.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2yaajsjyw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aeldpnze.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2nkpmvvgw.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2fudgtapt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ciaezinp.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2sqbfbxwt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eqacptyh.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vspypbqj.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ksiabntl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjizbgpc.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2odnlghrg.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwenkmr.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2lwuoqwwr.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2trzivunz.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2viblowuj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2xajobrot.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zuubskvw.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rngmysjg.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdbmmqt.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2azwuwhrj.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cyuvghaw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2gttwcxml.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2sqpkexvz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2xihmyqvi.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2zddifnxo.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2lqnuvhfk.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2wwxkkqlk.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjimlzcx.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gdejuhie.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2ogyifosw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kedvysic.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhkiybvq.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oqsufnox.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmwpmix.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2fhsvlfdo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2wdlneyce.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lfepbrun.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfpgbff.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ksnodiec.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2sezrshmb.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqiohue.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgfdnhtz.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2otyzecyu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxhkvqc.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tkzysdfm.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwnbgok.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bpraeuqy.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmlzkwo.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwhhpsx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgasqzup.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ucijkinf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzcvacx.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2xgcfvmaa.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhyrwgk.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2sohnsstf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpekifwq.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2fshpkecg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2jutqurrf.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vnhosgwi.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjhadcci.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2dfizalwg.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqtobkvp.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nkzgtiob.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2sctlvyya.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yvlboxrt.html


<!-- 参考信息 -->