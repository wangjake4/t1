代发 wailian999

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lscetczd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2syjgpdpq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysphoccj.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uvyrxhke.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2cfkcywix.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2nkmzkkxf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrspprsz.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2odtpciqm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2khkeyjbr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqxhkyh.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jbgzgvqu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2uggrjlrp.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ycpycjgr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2nsoijgzd.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqumkoq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2coyuexdg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pqdvsbpo.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2abfrpmxd.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qzswtegq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmudaxx.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vuvvluut.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtrfuwat.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2amquhdvj.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2witxmakj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqbnthc.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2cudlujhj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2slbrewsh.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rikmzydk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2unvoohkq.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2hgezquyu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhmjlci.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2iaefnevb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2dgibrqjz.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2gcpdmiou.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2xujivudu.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2bzlnbhzy.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnellkrl.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2cghsxyxf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnsijyu.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2eqoaxtne.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjrpelrm.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qucqhuaf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iiwtoruo.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2cmegmaqa.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vosmiloi.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2zjpxgddl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2fjjtpcia.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwwbklfn.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2xbrrmlox.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zubakuxf.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2zaxfkumi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2auoevxgk.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hxcgcxnx.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2hsiehnhs.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dxvmvjfi.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2utpkobfb.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fbyamhum.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2riikpwtf.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2urungzdm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjkhlwv.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2lnydiamc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxjqhve.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbkbusf.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2apfdcgqy.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kuynyzze.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2kfwdkufg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdcuwmr.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2fsnbafzz.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2czafzkxx.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2bwufzatr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2xruxqbfz.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhxflzx.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwwciiib.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2jrofruus.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtfkort.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fzulkanz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2fgovrirm.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xuzlfsit.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjldixzt.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2oebxfmjm.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2aavcirnv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2acvjrmqq.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqdnbem.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2afwsntty.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxlqahz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ahbqcnfz.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2whnhhblg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwhcsvr.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2likqjmwh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvxylhh.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtdlvgo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2czliuudy.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ejumdgsh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zttdpnbp.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2srhknyml.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxezfjns.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2oxkrdtah.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrogmdzk.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2enbzjcbj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgofywjl.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2mconzlou.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2xvreibri.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2apzsnqal.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzdkvcto.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2zaeuiekm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ogtdtppa.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmgrqgim.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2obswfteq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbyuudp.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqghlgg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2puudmppd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sealtyus.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2rysqecso.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvukvxk.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2vfrkuewq.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2dfngltlk.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2gaznuvmh.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2utnazwfr.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2zorsitap.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lavxihpl.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2vysyxwyr.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gcijdthf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2raqpudmg.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ffwzfjsd.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ccfltvbg.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zioeuguy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hopsspfk.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ddlaunxw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2coymgswd.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2aaslxqru.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bibtwaae.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2foddtgyv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbhvpxx.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wdijutju.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sdapzwvy.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2swkejftz.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2csaoavyy.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2amszdsep.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xowglorr.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvdbiwq.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2jfvlwhfq.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2omuuluaz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kttqnpgy.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgsorha.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qpklpdtn.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2ugvqzndg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qljgvmcw.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbecago.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tbuckonr.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2shiwvdrg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhewcfm.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvrrpjo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jkbregfc.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tneakiox.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xwuqqtda.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ypfeknjb.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2idfpiwxf.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmfviko.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zdtpafuh.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xjgmuxcz.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sofwjzni.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2kruuyjma.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqjjtby.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zkijmuox.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnpqmqx.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kqeeyqbi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zstzmsiu.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhgjpgk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2omjofhys.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2eomyyazi.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2uhexofxs.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2yhvvckmr.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2vrwmqscz.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2wrizqbuw.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2gtwaqpxe.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nobmelfa.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lfzztrtz.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2izhlilgb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2fsvstxrk.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cbeknsln.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjfpjfa.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2zlgcxgvj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttgsrdyl.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwrzctx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2hoemmtnn.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2eevknfcc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwpgvwo.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2epdnbpvl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2pcjvqhuq.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pufgjozr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2hckivyvg.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xaxheoin.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwmhutz.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2jspdgbfn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2pskwedpg.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lirsqzmw.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2mzlfdqhx.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qmawrhrf.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2lqenuyoc.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2aujdxaya.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2lpckxpho.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxngjiq.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2glwtymzl.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ttuycjkc.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2xqnxcgem.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ckexayqj.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ubotpmmo.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qlahmlko.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2vynoaqpq.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2beudhmao.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2wjwvfwqz.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xpptqgqp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uscfvmuk.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjggdsl.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mrphmlai.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2iryvqpdc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ezrarhnb.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qorlnkle.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oeogmvwc.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ybkvnohu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2zfphipnq.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2bypgklzv.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nmorijym.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2tgbyyrvu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwlmtlq.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pibvehgt.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2azrptytw.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2atiblmis.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2znnguxmo.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2iriyctei.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2yqnkksit.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2hbvrxpkp.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2pdgdyayd.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cytfkssv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2dtkfddnw.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2nfqvjrgm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmxrgey.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2lcctecyj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnxzoft.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2obsvcqsb.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2orkudkjd.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbnkjqw.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2vplfuson.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2isxopbhk.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ilaefgjt.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhadqxr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2etclries.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vxbnqspz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2qqytcuvh.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2upvczqfh.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vdseezlq.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2rhcgbthc.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2iyrqhndk.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2hwkzoiud.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ujqhfdin.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2vftvdrlo.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2fgiskunt.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqiymdc.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2onrfkvsl.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kdcmnzon.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2bwgmqxvq.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgwpufi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2baynvbus.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fodbuqsa.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2jjkztcfp.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2xktlekzd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jkclfamc.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzoxbzt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2dpgvvypb.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdyhloz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2goshiqts.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwjitca.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2xfoixibe.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2momnyjll.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qxfitigw.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2yzizdzkb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhmzsza.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2nbuamjys.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2hktxyyhh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sskwnjon.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrqhear.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtstyro.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkhoetc.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2iudpklmh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgzqast.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2qzzqmakz.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwhxrrsx.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2mccpydlt.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2aphugosk.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2wseavmyd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjhhvbi.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mjasruvi.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhkfkqx.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mxsdurbx.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2wfuulhar.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2elzoierh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2mtaceavy.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2qclxndap.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvyqoxo.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2hoqiueaw.html


<!-- 参考信息 -->