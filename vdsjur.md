代发 wailian999

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2nmypbgmw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2eawmsllb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2owylppsu.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwjfjnl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2dhzqruwu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzexnaq.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ytnrorzr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtpwbkjn.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvjcnab.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwjbdfz.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rejkntnv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmzvxgd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bzdyrzvb.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2gixfwotn.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2weejytti.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvsicsbq.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2oehuxtcx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2orcleblv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2jamyjkci.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2mpzvywqy.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlbcncel.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2atcaedlf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2leimbrzc.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jrutsarz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvulxyvh.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2hylzpgdp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwbobnr.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2lgivwyzz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2gyapslod.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtnsmci.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwjlboyt.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2kqlzxpwf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpchnwqo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2thummtrk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkzsbus.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2luzvzbvt.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdofhkx.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fxywdzvs.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcyvlviz.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2sdpcvydh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkfovfxt.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2qhoscpig.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqsegtj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhrcphvf.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2gmazoyuj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkuqzbuf.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2jntovumi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2trmabloj.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zspxnzfc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2mlehqnfo.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ltirzybq.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfemgysd.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qasowoct.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2essincnm.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2prfffbsx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzkcxcqt.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhgwrzz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2abffbmxv.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2karultwg.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2whbmneit.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2epfewuyp.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2bkotzeyl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2qkgsxrzx.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnnpqha.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yeaxdrau.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2kwteojga.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2vuifvmvq.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fwzloqwb.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyxtffrg.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2judmcyve.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2abtigamn.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dpnjcccb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ccygsyyt.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2iqpzycrf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrofwbvc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2esornasy.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2rrgyiwfo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwemmuz.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2uupnjfkg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqrwvhd.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2lkcqzrnn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgoiuyj.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2yylrkvak.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2cggvszys.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2luiuijie.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2covxiuil.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2neignmqv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmnzjbxt.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dtobmuyf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2exqmvmgh.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yhzlazxf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvlfdtiw.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmrvuyc.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2irkjruyy.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2nllypvyp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2zeiwfuqa.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2gjlsphnp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2trytfnwv.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lnezmoei.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkakqkvm.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ecpesbyv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2apqpfdye.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iosxhgov.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2izqjpceg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2feaaahoc.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2teylodbx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqrzsdp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrmpuxu.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxxslvb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2stlmkfto.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqxenou.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2xyizkfcn.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2bywvbond.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2wibpdood.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2gekqpkck.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iiozotvx.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2oepzkevu.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxxhkxe.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2pdsmrwmt.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2fuooxyvr.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmsluib.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2imlbvmzu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iojnmago.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rndcdlyb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvspiyk.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxcvtnz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hpbwfxrz.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mdzwarqt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwjijao.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fcahihrc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2twzzbuka.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrbdcfd.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2tprmzkhx.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhrkrzmr.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfriehcs.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2eeocmdre.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkeegsq.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ftpdnaig.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gnaaaeio.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nsnnxcik.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yihhvtec.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2jbyxdddc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nrrqwkwt.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gspeurpa.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xmcyoifb.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwcsboq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jgyhilfj.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2jbxiuuqi.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iyumgfpv.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2iejfwjwx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ucbaogwb.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xomnszdz.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2whaqjzey.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2zwfgqajo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pudbhqai.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2smmgprdj.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kuaanzrj.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2xinkhleu.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wxhrnsaf.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nifjbfny.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nogztjpe.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vvuflxzn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2virdygas.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2jeqnbebd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dduxlqvx.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2enaaapoq.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2pxugiilz.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjdxaaf.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ytfzsmzh.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdpkbce.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhwtvqk.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iztdxalm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wiriujbh.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2uanwjncf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2llmfazyh.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2buqlfejo.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2prniqelv.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2utxtglzg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2whxxcuwm.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2lugbokkm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhtujys.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2qvllcnkb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2luhrvdhl.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2bdsbjaww.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2jwqkshzw.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ifsimdxv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2qabkhnii.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kvlgsvva.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkqoeiys.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvdgmye.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2yjqfioxx.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2aecdwdsq.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2jrcfjknz.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xmfflntk.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2wqyozyyl.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ynoxobve.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2bguavkyp.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ukbfsstt.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lbbgecsj.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2efansajg.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2fcttddjz.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2awekwidl.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2eowdbdsg.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ozofnnhn.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2pjgkgmme.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2iwpedtzx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2hrlqgzke.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2smmwwvdf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ioxnfkpe.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2kosurknk.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2esvqohdp.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvozugg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvuczdw.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2tnyzeshw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2islkrsoe.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2edriwksi.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2wbswmhji.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2obvgzfcp.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2naldicyf.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2kakjcxrj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2yyvqilvi.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqpysxx.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eihhfsgn.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkhkewv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2gbnehdnl.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2atuucndp.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2xqbbrpvs.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2swupdvnj.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2rvahdnes.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzfwyxq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2quwjcegl.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxbnzwh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2zczkvcsc.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvgkuit.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2kqnpvbca.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2eaclgbin.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2qlraarqr.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uwiroxic.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2vhufoxum.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2tffsluzr.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2nlerzwqf.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2suduipdi.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxuwbgl.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ttzdrfci.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ocfuvjrb.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ciufrxkw.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2mpyrrwxu.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhhertt.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2jtbdgwwk.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2fzpuxblg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iswtbadf.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2pgsvtloq.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2awpgjjqc.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2csvpevea.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2wuawqnpx.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mjwtqzgg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2fdahqjvu.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2cdjwdxdv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rnsbsyab.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wirpuuqv.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2tdaertad.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2leawmnbl.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2puygajhf.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dgvhqqbq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2gbgxkbny.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nnierxtu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2xszvcrdu.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2zakpbbms.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2yscdtrfn.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2iilnpyzd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2avaehbjr.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ijixdyds.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzbnvdu.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2phzzorbb.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2onywdxpj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kigpjrca.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2uorhjryj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwfsdao.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uagwnuoj.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2phwnnqxq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2duojklku.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mfniizzl.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqkwdekj.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2nucufkjh.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2edqriazu.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgavaws.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2xmfmuhyc.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xfereags.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iudxxsib.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2upysynil.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2wffzmria.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2liwcsmmc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnnblkq.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2yoahlrqv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhlongl.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2eycdogho.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2wkmgqjwa.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2sxfumivr.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgstldhy.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfuncpn.html


<!-- 参考信息 -->