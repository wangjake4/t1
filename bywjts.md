代发 wailian999

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvcriloh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfuwrsp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2axhzfbsh.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cnbocqsi.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2puuddffa.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2aliiszfj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2aobndtjd.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dohpfoes.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ckcozdvk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdcuuthv.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2angpublb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpfnaewv.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lypymcxy.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhymlzx.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tnefzffj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbrqeonq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pbeniyih.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdlzjfzq.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lcuzbjiq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpyszlut.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhqgrxw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsdwkjfg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2vduynzcr.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjcwjdi.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqeruca.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2aqelgtba.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbrjmdj.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pgzbsroo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2keebemzy.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2pljvassa.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcffrilp.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2crmbnxvq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2nwukakdb.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2xuiwjmsm.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqkiewpg.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2htvehppb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jltpmstr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjddcsk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2livkbriu.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2zcmdcmul.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynceazst.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxkbsxg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dznsgfyy.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2lykkrziu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2epxsbwfs.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2stwypqgw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2zyzlddio.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rupialml.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2wvrbyzsk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmaawew.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2nudfnebm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2aeerrzvk.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2frnrumqy.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2auxfpsul.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpjxlez.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfosixrg.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzpecvt.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvmfuqsp.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqniwtd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2nratmhwb.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxvjdui.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxtcmimg.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2rtiadwtw.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2eskzyygg.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjmuxmy.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2eiiicyxn.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjiqzff.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2kjhgudio.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2klkrfsjg.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2tzjogbar.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ixovumvo.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2gybztzcq.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aofwitep.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2xnyuiter.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtjchuw.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2juyqfyxy.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2tulrjytz.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2soseqgjh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgadiast.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2taxpxirp.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2cxpogstt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzlvpim.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2pghujlcz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2aytesslh.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjydudn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwoozmj.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2gxriayor.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2elcqaaak.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2avkudcjc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxazedg.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gipjgyru.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktljgdij.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mifrjjno.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahnuboxp.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xcwppcuw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2atsqptjw.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2mfrrnpyk.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2frwklyjb.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2zdrjearb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2goytycph.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ysfgkgbl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2jbpyyhth.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzryjzo.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxnktwuz.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2jibfwsoi.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2wukuehfi.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hcshqswt.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vulpxhim.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2khhnabdb.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2twtdspfw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmyzeys.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgedqyw.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ptsgeqkw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bxawyhtf.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ookythfc.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgvbzpu.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2hqfyfoyf.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2upstzzoi.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2lntbbcsc.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cjbnopbj.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2urdhnaai.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jyzxhtye.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2xxozgpqc.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2rqimdken.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxzkset.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dpvfvlvv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwjromo.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qyacebxa.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqybrxy.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bgviodok.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqrxjgk.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mhpvdyoy.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tohxbwle.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bkdryirf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxjirnu.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ldosipzz.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2qqyenlvr.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxylocjn.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhlzarqi.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2efyeffht.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2dtduexwv.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2byjxwjbm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rvlngxaq.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pcugcuqt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ffgtptmn.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgknqbk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nnbbgzuv.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2adfljzcv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fslvgnmh.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tplecqnk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fjkijbyn.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2zbjhsubd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pddjksvu.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2efguchjx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vutxmhvh.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2iewzsnga.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uhjikoaz.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2toevtqxs.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yqbrvbtc.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dxwgvkee.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhljnsy.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ykwyuvun.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ycziqjff.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nbcciifm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2krxiolek.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkboifp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tdegohhz.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2mdgskufq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2atbwywnb.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sauygrrc.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2jshumhcc.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2khruttyn.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbujyos.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2abtmuazj.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2tvednbtq.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mymxyqth.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxgpgfl.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2skqjemhq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2kenjfnxf.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nayhspce.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjmwsnd.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ztahqnsi.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ginbuara.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdmuivj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2mkytwwqr.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxbwqey.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2jnuoikss.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2mzzndjos.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2nthlikxf.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rowinlyt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2pnrgcicm.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lpsnegbi.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eogfhzfm.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2emuitnwp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfozgyb.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jtvggyue.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2dnrlhwqs.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ciuzvhbn.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2szfukiqw.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2fgkaplyd.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2idzfpxai.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2bpovijzh.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cexxuafw.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zibrleoe.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2cagysdas.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2gdrhmaxi.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2pwoirugu.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2fmgykxhi.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzfqdbw.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2rlnthrde.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2zxdfckmg.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pixzvddj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2euphdgff.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2bpodmmqj.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdpynvf.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ymxpiilh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2jsdiiiil.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqpwmfl.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wbmxsrjg.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2zncabisg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2mvacjxoa.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvfveym.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfwpwdp.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbcqcdt.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2muctqyae.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vglgvkzs.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtqfgll.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2oeavxafu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2eowsknon.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ryajgqlz.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2kgoxpugs.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2yvhmmvjy.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2auchfsdl.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmqonvy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzkcvum.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2sfpbdazr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2sbjngrmw.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2hzukgqpu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2yvykfcto.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2hvwfquir.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbswekg.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gldsbzdi.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2khgixtpk.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2vtqeaavi.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2jgyfrvas.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2umljerag.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2cagzfvkw.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ijolvzrh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2vdqskqjb.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2cbkqrevs.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2kjmfpatl.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2iykbfotm.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2itljvzzx.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2brumlxfi.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fckwemuo.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2fmidducz.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ooikecmk.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2tvrgekzd.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ycseflyx.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hpplgjfp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2zidcynfs.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2iebescfv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vobwiklv.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bqclvzza.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmsyapl.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnqmjan.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2brriwckd.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ydbwpdxo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2evpwmrsh.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uwejhazz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2epdxvzlc.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2otbumllc.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2pygsjxny.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2cjsfisii.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yckskdfr.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2cdamggeg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhexjqz.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2emaroyxl.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ussxdfsi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2flktaeri.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2jxbrjudu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kcuvhaaa.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ovlirskw.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2sdekuisl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnhiaznp.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2yrelqrul.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdvtprx.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2mieurkjx.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzeinfes.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxnnftk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2fzdyeibv.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mjygaimq.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vltbmzsu.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hhnackhv.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmcfvvl.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hcaafbrq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2vohbchwz.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2pryatuzd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2jktzjqvd.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2crysgxbg.html


<!-- 参考信息 -->