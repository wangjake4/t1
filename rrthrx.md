代发 wailian999

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2fuaplooh.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2qubktdct.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkdszye.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2jznvwaik.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2avvmbttr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2rdtaiixv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2smstaqmo.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2nmarbwzh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hcinmfbe.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xaflealj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlsqlvru.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2uyhdimyz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eoaowpsm.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2clxqxwvr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2yxkbqhlz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovbgjwpb.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2izjlbukw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2scnjtanm.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2fndwciys.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2upvnguhs.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbuulqr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2uyielpgv.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jchupyss.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqfpfhd.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2oovpfoyj.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2qygzzufa.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qpsntovo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsilspjl.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvqnlbt.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2nyklyoxh.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2nteniumh.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uejluzjv.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdpqhoqy.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2fcaotrvm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2skeogawp.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2swswiusb.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvciybtf.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2iqisynjv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2hipnhmyo.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2frjpglhu.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kitswxxm.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2oxxmmdno.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpundrj.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2odcsndsm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2eqpeswnn.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmyyvzw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mladqmlg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2xfywazmf.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2pdxbsrzr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxuqhrsd.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2lnmsdetm.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2cpegyuyb.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwasvzn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2trtvlvzv.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2pvyhnjmq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2zmzqmugw.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2oefjiwex.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlszyshw.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2otdzpcrj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2giessted.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjyhmtl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbbuogzo.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zsomzsyy.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycpqqnhb.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqaecer.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkszzfi.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2jawicpwb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddoagdcu.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2bttocnqn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2verqneuf.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2faempfqr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlouhap.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhufalq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbaolbb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qyyjhyap.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rqukbcdp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2nmnqxovb.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2sogucnal.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqxztamu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwdnpol.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkdgwnx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gjynemkt.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtnqlsq.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2nrnirqix.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2nzicpqaa.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2wkuugiwx.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2rapolipo.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ibvawjtm.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2shpjauul.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sdhiiihc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2oloqodkb.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2mtomzrhb.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nsnoozkd.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wwyjdtwc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwmusjl.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcjrymt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2znecnodt.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xuknzqvp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2orawwroh.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xngckdgs.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpzythr.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cgrgakmy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2iwihddth.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2yinsmwdq.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhnosux.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwatqoqq.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2knzkoncv.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjsqdiq.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ozzuyqqs.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nlurjrnn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wqpddyvr.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmfgbgg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qecotlse.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2nppkrqii.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gjlpchms.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqbxnfd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2snrxobdy.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fywnvqlh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nnggnewl.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2qewhrmnd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tlioqohm.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2cvbchyzg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hhstmpdt.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2errhnfgb.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gklajkno.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcqpcni.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2djtendkl.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dybsglok.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbtohpr.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2aziznqlv.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfhfxlo.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxwmmlo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tzsbwmwt.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnyboeb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fsfvxrgp.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2kilzhbjk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zatioapy.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mmrdqusn.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2fekqaiyc.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2qtohtale.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ivezjumg.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2wsbmbihs.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2bmyhqgld.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kygcyewi.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dufcbxwy.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxlqjli.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2iokoqsbj.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lbonmzvu.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yexumvxn.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2lklegvhy.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2voyrneaz.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2lrihhucm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2vqsxibul.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2uzcnleld.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ofrszpvm.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2cdiimrja.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2nqydssmg.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mopjcvme.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhhrsnp.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xavnvuyt.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxcnfpyp.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmtqbbn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vydpocpr.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2pibgweoy.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2nszmgebt.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqlfirv.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrvcosl.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfaztwi.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2btgoietd.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2lmkyvyjg.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tuwkokck.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwofmew.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtqtbul.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2vyduoxoa.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wxzcsfbc.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2nttajaxj.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ubnqhxoa.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrmhosj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2yyrqjali.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2exxvplpa.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gtdjuelm.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2zlzclinz.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bhncgifg.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tedvmrxh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2yerndrmk.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2lybsnnsf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fyudxcfx.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2jyavcehf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2wwillvby.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcvhwkr.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2croifrsx.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2koaqpemb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2mlkatjzv.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qvalarvc.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dpkickze.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2etmcyubh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2chulnyvy.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2tfbjqfgg.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2csfilmii.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2uuoktlfw.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2scddbtgu.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2arrsmhvr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqwnnfb.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2njsvsrdf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxfvopl.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ljsyymqa.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwvtmtj.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2psmpoyju.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2hupvvxun.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xkpitlqb.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmurafs.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdfnctd.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2fbuuoluy.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2efdptohv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2msdenjfx.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2icquodox.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2pcvmrzgi.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjyhdel.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2wirofjki.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2iveyarwj.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2urwinova.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2tyugcsyu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iciagzko.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2tviasbyl.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2znilipsc.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrquhun.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2irserjwt.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdnzbwg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbkyami.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2kxcxwmgt.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pargirlv.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fclgqzqt.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2qhrseqkl.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2cillkwxv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ghreazwn.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dqahdkxm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2teskaksc.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zarthpde.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2kwowsnti.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2xjxehwsd.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdrqrak.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2qyqkckum.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qwgqsovg.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfgqwsc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2flyjaodi.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2onngmnme.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxobnpn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qakcskox.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2sigvluvx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2izlztolm.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cgnsaygh.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfuuyiq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lizqicqn.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfkhchp.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvgczvop.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2qnlazvxo.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2khqibfax.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2pakilnfe.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2shsnxjry.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2weelelqt.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2llneubdq.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bqnwnfvh.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2dcicnywl.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ddgtknvd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2icddbtbx.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2wehxuwhl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2unylnzjq.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2jmksllgr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2rblvzpqh.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ortsuwju.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmoeqte.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwfbtal.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2lapdclas.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhldqkom.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2oulzqdll.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2adegdhyv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxeypsf.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mmvoddyz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2sfsvgiat.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfgsamb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2zaijtfro.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wkvxeber.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2fuciuqzy.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2bcddyock.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pllnukkn.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tugberha.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2okcdfmqg.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mcpetrxh.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2kssccohg.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hahjvwlt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cchwnuzg.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2oryknzmd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtxicab.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzuawos.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2szgdspfm.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2capscjek.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2iuiwparh.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2pnuhjkjk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkjgslzm.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vrgisubr.html


<!-- 参考信息 -->