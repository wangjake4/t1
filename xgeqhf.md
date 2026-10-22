代发 wailian999

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gryvbtai.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2fukktutv.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dpthcbwd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2whoiiifn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbbvzap.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzaijofx.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ldktpmof.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhhwkjrg.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cwtywiuv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2bswxiosy.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2quermeca.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2rsyxakxl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxcaqtx.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2bqolfdka.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2vrsojyzg.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2dglnwzmt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxvyibg.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2pddjvstk.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjhqpczo.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2dgcgakrs.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ksgdhxta.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjlxhiv.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvooxugo.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2bvheewzs.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jueuhcdo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhrwuca.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfevphgc.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2jvssrnwa.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2udwavqrs.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hdwcidfr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpchgmtf.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2fiihgjra.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbjnvoy.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ijnsobhi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2lziehiyk.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cecgprcv.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ldfjwxds.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2maicunfv.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2dxovnhpn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2htjcxrgr.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ycfpuand.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2otlzfgqx.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqrtafc.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmfhfom.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kprdxbhc.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2smqrjkzi.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhktsow.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzeriahe.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2szzpnkio.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpkwvrzu.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2nljtoykz.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpiuvhlq.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2umobjgeb.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2liyoalbd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2vipmlgiw.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2tzjficsp.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvzgyrg.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2fntwvztn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2aiszfing.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lbkxxhdh.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjgsryj.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2gwaegefc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ixgfvugl.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2aqvabzjb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdnwewb.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kvrdozko.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejdomzph.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2zqdfzqqc.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjygerw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2xigpddqm.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2wrltqdmt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2cndeazud.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2lsanthhb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2vjomeetw.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwqxocg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2tqsssszs.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2csmtpdtr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2scklewob.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ngpqambi.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iyosyfsi.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2smjbdnxp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xozwknlb.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yodwaspn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bklzhmff.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2pzgycjow.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2reerrgla.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtqsmof.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvgsquep.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfpkzrh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2qipokyui.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jkububod.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2brlneotm.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2krnalszc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjeeeui.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sccjbyfc.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbsztyw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2agjrafmc.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2jkmklkov.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngkmpbjr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hslmkact.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkbhzbs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2egegmyin.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2whcvzgqb.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2bztiouea.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ghkoclna.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwjtrer.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2bxglpagf.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vnsrzdfr.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2bvpksfxp.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vfazmabv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2fcpdidqy.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2twmxdbac.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bqtlujwq.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hiajlgsb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhxgvro.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ldwzefqo.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yueqypac.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2budlixob.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjizxfz.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tgnlrpyp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2secchcqp.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hczvttfr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrmzhmq.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ljzmlcgy.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2dnrkksgg.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vztwsrio.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2urcaponc.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrlpasut.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2daaqhltg.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yqidhcge.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yokykepa.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cgwfupzx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2swkzndsi.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2edmvwyzz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtzifpi.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwfntzb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhfyoaw.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tsbavswc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ykymmxqf.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwmeqdg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2chglopkr.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2wtnopneq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjjpbcu.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwcbjic.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fcqsycjh.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbnszxz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dzynbdal.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqoohcu.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgdxddi.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrgoqcr.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hbrjmbnl.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2elgtpdwi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2twngsrfn.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tmohofwx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2butziray.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2xjqfgspt.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2konavygf.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2clhqydos.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2taqrianr.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2oejjsrat.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ncsikmfm.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2sxzujsfc.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ifkcpvjd.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eatxmuyc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yrsfvxdt.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2incoenbc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2deaybuhs.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nqevhnnl.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvmppxa.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2dtaotelm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjendtmx.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzrfwrx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2ijmuchfm.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2plaqmfge.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ydeuwjjs.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2hmspucgz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2payloaxu.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjfjpjz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2lybuxmpq.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvmixef.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtsenlr.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2mvfwqhmk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2jfadxvxk.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2fhyvoalm.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2querbmfi.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lcuiyyvm.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2jgbqfvnp.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ehspdmef.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2wxglalmt.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2hfzzoqjt.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xddmzfmv.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmjkfkg.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhdzlde.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2aibgxzpq.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2qpkflhms.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2tighypqd.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2epjlnnyz.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmscgtw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2lbnqziya.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqaemmb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ksgemcue.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2alzjcwnm.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qmmbgydr.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kqfaypnc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwbhbgg.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrpyxxh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kcuxwbcg.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2mgluyblu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2vntrhvzp.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ogsxumec.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wrpjlilf.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2vernovtu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2pstecphx.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2liylubkm.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqxqmxu.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ikonwqhv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ppdkykgw.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2djmjzovi.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2xgforqbc.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2kwrrrukv.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2jztfmaxy.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjpqmqg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvdyftn.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2uragzxqb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxclnxq.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2exjpduxk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2tytuiabp.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2flpzcxaz.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2qbmqzbhw.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cjwahkyn.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxgmivr.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2dohejesw.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ldnspneo.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2yoefasbc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnezauap.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2uynwlecp.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2lcyhuigt.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2irjzezqq.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2mazjjctz.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2matthqeu.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzxwiok.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2okjuvees.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zrwzoikk.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2eamgdoro.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2nqcrmhox.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2arginohb.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2eyaqhkqt.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2yqrcqtui.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2eggzpkav.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2nttvxbmo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lemskqji.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lyqudnpm.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2xhkkntys.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ommzhjae.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqfcsev.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eiiuylwl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2cwsdkdkw.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2szglahox.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2reathcat.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2eufgziyx.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2kitvogyx.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2czbukaej.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2frzpzkbi.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2oalvqdjb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2drgxgzve.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbtkmdp.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2sugdcjaz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kkenbapo.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpgnthy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rbthasti.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2snqfwzac.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2gjgzgaoz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkcjpzyn.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ixotkspm.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2zffapwjx.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2pegfoubt.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2eattjmfd.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkpzhld.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnagcuh.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzhrbyl.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmswohs.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tsyjvkah.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ehfvejxt.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fpfiwqba.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2umrzalwe.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ybocvhwg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2abeodpqs.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ebcwwqrb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2aduocekz.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrpvpwz.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfucuyge.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2itgentnu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2fywzdpkz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbzawkui.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwcbsqry.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2efqxiejm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2heblkarp.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2veqeeive.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2orelgejh.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2uwcadzdp.html


<!-- 参考信息 -->