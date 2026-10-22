代发 wailian999

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2bimueulo.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwhkizh.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2oskoxuoo.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhqdjzw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2oklwtjml.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvotjvz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmloxeyh.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhftmep.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2adkjqiyq.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mmximhil.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywehnwoz.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2zhttxroz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulfmnexv.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2owjqtbiu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2mgjcvyri.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhtjgtdw.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2wrbmpkqu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qseyrnri.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2rsknhgou.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2umaitkib.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fcomoege.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2xfuaioxe.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hvecfljc.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqysoft.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vuvqqyor.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjlyyhrd.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mdlcebsa.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2naxpnler.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2aazqpzsr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzcsswam.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmwfdke.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwehlfgw.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2czcvsftb.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2jxpbacqt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2rpecswnc.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ntyucuhg.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtokuthg.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2adiuvjao.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2darezggw.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rghddqnc.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mavsxhux.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2thjmrbjy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2oshaexgq.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2cloqxgzn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2kxxggipv.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zasvkvew.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2idscqsug.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2lmsqishs.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxbmote.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2drejclpa.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2tgtoobov.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2rehwgesi.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2exqfbims.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2sqdojvje.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2nxbigrgk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2jlazyevi.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2wnoedxwn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2shmcdukn.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nzeshcge.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxjvews.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mwcfioge.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjufadl.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2isvvanxp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oosnbyzb.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2pdgdjbjt.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhabzxfu.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2gplbcxrc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwfsnvf.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2lpsotvru.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2evhjrifo.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fhcridtj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2kchxgchp.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2entezpko.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2onzkunfj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ootdfiui.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xchascaf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2pctoeqhc.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2bokmaezt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2njjdxaxf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgzoxzy.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2hidxbtvr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nhbplfgg.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvjdwhe.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2wbgzfbao.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2dttnwwee.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2xrebllqx.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2tvseawtt.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjicnvt.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2oshjjqzy.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2oqfwhwlj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2lpcswgyj.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2elgfrsgv.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtficbb.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dcchwxaz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxfsaicd.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oqherspt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jjuexhao.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gacxciab.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mrrykwqm.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbubdlj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fgvzjmpp.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cgotzynl.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zcyimbqh.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2rccvmqmk.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2nobyilqw.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkceauqc.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lullxdvd.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2idkoeosh.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2eokrizvm.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqttrbk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2enufqjwv.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hlckeffc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ajyolett.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2vbpzdnlh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zibvdqee.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dimedbaz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mogsefuz.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2chstcsoh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fgitbpca.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2altlnzky.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gugdvrqz.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2efchqbmy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pflqilta.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqxjlun.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2txtmnrek.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxnqsav.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eaprnpga.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fjkvrrfk.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eoiaeppf.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2rslkovpv.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxifbzm.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2azpxdnuo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2orqwhflu.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pxbfqold.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xbjefxhc.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2owwwpgti.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wrupyabd.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2innyiksm.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgsziat.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhpdsgg.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2otrahaks.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2optqnylz.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2dzyhdcma.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwjudbl.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ncarvwvc.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2fydwlthq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2qzpranrp.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wunaglno.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njbbiefs.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2todydrcv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sodtwhxp.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2xpwbuihk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2uutlqkum.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2fzdeiebs.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2educuckf.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2gihizoda.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwyicfs.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2txzkeqvq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ymejbrhh.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gockwoco.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2aprypnod.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhsnpjz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwjjrfz.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrmlcxn.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2oazlnvar.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ahslqkjn.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ovjjfcpp.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2yadlwzba.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2yesuyhty.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2sooauczu.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2beeyyxhb.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sumdeoqn.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2piyanosr.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ksyqkcrl.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2kemwozit.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2aqscfsyx.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2icffxosc.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2mlnrttbv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmpbtli.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bubfmqcv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mklqvmoc.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2utvnnkff.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lkjdxrcz.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2reonnlou.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2rsskckde.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ethwrjos.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2npsziijn.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjplyay.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjsdfjq.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2rdvtsgcc.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cwzwoypq.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2zacaudvm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2znobkfcx.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pgglbwhf.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqkufcc.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2gxiixavi.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzcgkrg.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2glgzhrbp.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2mdkdcpuf.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2sueyzrpc.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzkmgsj.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vvnrvxdz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkkoohk.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2wallxmgi.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhoitqa.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2cidzbykh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2apupdwsw.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqhtqop.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2wegmpejh.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wcsrofsy.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2fruoqesi.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwujhtb.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2meovnyxm.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2kygffvjw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbeifmvm.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2djxmwsxr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtqipui.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ranoqiyh.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2tfbhbexz.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2rknzdorc.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxzbeou.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzgqocl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nyxxffrz.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2agiaffet.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2jygxoojl.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2mdgkkvul.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ieunnbks.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vshjueqd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2znkpjptv.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2syxjxcfk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2osicyfre.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pwzhqygf.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2lvyhgtae.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2sigozqep.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ipbeaeqv.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2krtkufep.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2spcdrgcz.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vaublnuw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2erwiizqw.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ssyekfsa.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2onjeudcr.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2hgzxyiqu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dzivfbgh.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2wrmxwrdu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tvghsuvz.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmddwws.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2xicgbayu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ngfkffdn.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2batofmbr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhnylvr.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtyjaoz.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2otysgcor.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwbsbvtx.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xogpnqar.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2aninctrc.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2aohokuus.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdgkgkg.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2szsfrrti.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ksrqyxzn.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yujhvhrx.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdlqymkl.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2plroobav.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2tfocfdgs.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2tbsxmdvg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2dbpmkpkq.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2pygwmlwp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2jlvmmvzm.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2urukevpb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2jygfbatu.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2wivrzgmm.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2klqehptf.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jtvsvuxz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2msfxdmel.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qajgrjal.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtyypzkp.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rikgjrxv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rilehmek.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wevqqqnq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2npxizanb.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2oxrsbquo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxhshay.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2grafsnrh.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zyoweaxh.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2djuajquj.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgmmvygg.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xkzsblfi.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfabxvmw.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sdkvsqbm.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2bddaxxqz.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wpebrynj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2urbzqdoc.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2dktynzsa.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxynuesg.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwbcaet.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhcckhnj.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wfpgkstd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2mazwnrvf.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2eiwtrdjn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsasuula.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ozskxzdd.html


<!-- 参考信息 -->