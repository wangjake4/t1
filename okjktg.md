代发 wailian999

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2eupwdial.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2uvnqhnok.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2okmgsvyw.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzeimio.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2pihzupjv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxtkifp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhdzahc.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2zulgloim.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpnsflt.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kuqzmgxr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnngokhk.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2gdfkwwfv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlgzglwl.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ijtzujjb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2emrtkfcl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2motfgooc.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhotcaf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cethznlw.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwtbnsm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlyvzkke.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xgpjniws.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ytclcyei.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fghxnumh.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2qawcuzrb.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mmzfhplq.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkkdgvmj.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gojewkig.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhinvkum.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2lwndlmic.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2assejwho.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2kwsfrbgz.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppguzzem.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogcruhcc.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2wqyzwnjw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2tqnlxoog.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ezffywzk.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbmyxoc.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2cyabehdx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2hknmecsw.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2sxdqdrmq.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwphijmi.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvcvcmu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2hckudcsz.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2cytxmgmr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ohgmacgz.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2irrdrgnw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybaffnyk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2wnluzuqr.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2aafcfdfu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlesqlog.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2eakpqmgz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2prlzyvhm.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2sriaqern.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2eiaaydcl.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2flqllcsp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2swxcrdnw.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2muvttsim.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkefwfdw.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdkwbkk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fltkwfoy.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vrqisxpl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eorueoqs.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dfbaaaol.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrhhoowp.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2jlbburwe.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvxabinj.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2rulogyvy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2zyonifoq.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2npeihmjc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2nhlaidvz.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjaefzk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsygkwkm.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2kwbcdbkg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2rshwbxlg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cryauvft.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2loteotdq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbvkqid.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2hhyyumdh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkibjiod.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtmwbbj.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2giudytho.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lmafsmtc.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2qvrccnpr.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2xehboozf.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2cnzhuzmq.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2uoyuakqq.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2jryepair.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dswwxthn.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdrrhxe.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nceuablp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvbjneg.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2sskodpvi.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bstbeyfp.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrlulxw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2stlikppf.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hivgqfni.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zfyaoyny.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhzgrss.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2czuvfczs.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fgkfupzj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jxqosxha.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ikdrcphd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2woocetvd.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ukgxugre.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2oiuwhulk.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2khplogdw.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzzcqben.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzvbdvdk.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkfykox.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jnmgexcc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cnicgehe.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hxcnzkhe.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bygvnqln.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2stnodkbb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jlozorln.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmhovro.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2orlntswz.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ugsrppqp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gvyaljvr.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2cmnjgycv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uyrvvrhk.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2cuypwzkj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zmrppxbm.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rhliobwi.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cvdetwav.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2czalxrxt.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qkpazklv.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rfuyhjny.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kyrbabkl.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2syrpgqta.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjkoenp.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uwqlaieo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqyomzm.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2schggrdx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gdcdmkyi.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2rbpdixvm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wosjceko.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bklpmgrc.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2cfvrzlgb.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2jdzbvcet.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqmmcqp.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2hfolkxqs.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2qsillmja.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtubhis.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jbgqlxgi.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhapugi.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2cmibzdml.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lzitpwze.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrbhuypb.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2kngdnnft.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2exdwdveu.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2gghyjmfv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqaghwf.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwzlulv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2pdgkajcj.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqlwwoe.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2rxzamceq.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vfktnaia.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2liwlovaf.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wzinhkix.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkepwqmm.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ktjykfpr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxcyvqx.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2eysnhnzm.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnwjokg.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bmfzdeef.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2llutuwto.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjvkcti.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2yjijuhdx.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2gzpamtci.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2niyjtnml.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2inggqlnm.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2obxwlcrk.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2euwaotwx.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqaxmeb.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmhvwwn.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ksiyqgpz.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2djxonhcx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjpgmtk.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kljxckrh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lsftzznq.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2qdotfffe.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dkyhpxja.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jzhbrvst.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2fcpzmsze.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2bevyawqj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dvqwmfmy.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2snlgqkol.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmksraw.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ytaiftmn.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwxknrm.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2eymhfiqc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2vpaxnfwq.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtlkrix.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cdsoysyw.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2mjnakfeb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2kxgtqwvj.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdbkgzo.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2kdasernk.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2rzsdfwlf.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ktdensya.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxzzsyk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbgnqbu.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xwwcdgkz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2adfajmju.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2hqfskhsp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2dxadavey.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwsnmqr.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2vuahdakz.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mzgejwnw.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2trufjsiq.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2yyddzywa.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2dyobanxc.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2djqztzoe.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2rozmmmuw.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2qfoxyrlz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2txwheimz.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2wlewebbm.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2mpemyxzp.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxiyfsb.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2szujsnte.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2jsiiaevz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tiuwzmam.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2crfpknfv.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ctdmicli.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2nagussef.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ydbtxsme.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqvhtpa.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2eyovhute.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2xrodvaju.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wpcrrqlj.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yfigvhct.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2hfkptokz.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2okfsqrft.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mfcxtkbi.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qplzdjjl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2wcourlpy.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2btkngvwv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxmtxus.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2hwsxqqmm.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2vgzfwukl.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2abkyrzmq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tponutls.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ynsvtfgh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwrpcal.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2iayluwrk.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2avkgflsj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2holvfusm.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2gviqiokz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vovfeulw.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fldnyydb.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2qvwytqje.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dctzyoup.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2snkutrii.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ouchlypi.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2yyvagxcs.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtcnllhn.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2vxmvdpig.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2dckqlpec.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xigcagcs.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2unenulen.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rujainvg.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2jaaxpzam.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2psqamtaw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2agksfzkj.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2bnqqapce.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2tsibfdkj.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdqflwb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2blttzeaq.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhuudrc.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnmigwkh.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lxigdwzp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2bpugpbnt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgpkrfrv.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2oempfhye.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uenkyoec.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqsciljj.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vixujyem.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ebcwpshi.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2yhpymryj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2znsrxhun.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2unmgcqum.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2nlulwcua.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2saxkizzc.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2akjizjny.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ixbkqhxc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2rsseqfgb.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kikygngz.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2iiabrfnr.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwqhrke.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhzbhomr.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhniwtv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjnhovou.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2aixrtxrn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebgcnnez.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kgbqlpng.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzclhel.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2szqspvgm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2yltxcngv.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ahconghs.html


<!-- 参考信息 -->