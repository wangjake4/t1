代发 wailian999

SELECT * FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtqpdpkmrv.html

[Q16] 查询指定列
来源：http://dali.yuxming.cn/Article/details/gtmighlthe.html

SELECT id, name FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtdwnthskb.html

[Q17] 条件查询
来源：http://dali.cdnleiting.top/Article/details/gtdltioaca.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jiagoushi.top/Article/details/gtpyezuiqr.html

[Q18] 模糊匹配
来源：http://dali.jlsjyb.cn/Article/details/gtgoeomsie.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hfpthk.cn/Article/details/gtiisgqrjo.html

[Q19] 范围查询
来源：http://dali.aibaodan.cn/Article/details/gthhokgiru.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yuanzhike.top/Article/details/gtgjvarbzf.html

[Q20] IN 列表
来源：http://dali.jqgufenzy.top/Article/details/gtnixgdvff.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jyoumei.cn/Article/details/gtsiyroixv.html

[Q21] 空值判断
来源：http://dali.quarkkingdee.top/Article/details/gtqnciwkls.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jyoumei.cn/Article/details/gtutmhdcfb.html

[Q22] 排序
来源：http://dali.nwbrower.top/Article/details/gthxnglzvv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hongshengwenyu.top/Article/details/gtntaenupk.html

[Q23] 分页
来源：http://dali.jiagoushi.top/Article/details/gtbwbdpsjv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hammf.cn/Article/details/gtkmeskgbn.html

[Q24] 去重
来源：http://dali.daxiang520.top/Article/details/gtwbvobmpa.html

SELECT DISTINCT city FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtayrsnrsh.html

[Q25] 只取前 N 条
来源：http://dali.chenjidiqi.icu/Article/details/gtpwqrrscx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jiagoushi.top/Article/details/gtzatlndeu.html

[Q26] 计数
来源：http://dali.cucudq.cn/Article/details/gtxjkvbsrt.html

SELECT COUNT(*) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtdtaxrxfy.html

[Q27] 条件计数
来源：http://dali.gaohongyu789.top/Article/details/gtwumggcwm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtleqbufeo.html

[Q28] 求和与平均
来源：http://dali.jianghu66.top/Article/details/gtllkjmzgg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jianghu66.top/Article/details/gtvwendsgk.html

[Q29] 最大最小值
来源：http://dali.yonumen.top/Article/details/gtysgutsew.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnzgqzcun.html

[Q30] 分组统计
来源：http://dali.jinqigfzy.top/Article/details/gtmfxxbsxj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.wangshuangyany.cn/Article/details/gtxhgnxghr.html

[Q31] 分组后过滤
来源：http://dali.xuetiantiany.cn/Article/details/gtvuxwtmre.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhoulong.xyz/Article/details/gtsthglgmh.html

[Q32] 分组拼接字符串
来源：http://dali.gaohongyu789.top/Article/details/gtqibjgcnr.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.guannengcc.top/Article/details/gtszjspxnc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.0kj1m.cn/Article/details/gtypnctult.html

[Q33] 多列分组
来源：http://dali.jqgfzy.top/Article/details/gtjntupwzd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.svipenyu.cn/Article/details/gtvgijiaso.html

[Q34] 每组取第一条
来源：http://dali.zdqjudy.top/Article/details/gtdbpqcxye.html

SELECT * FROM (
来源：http://dali.bjfxy.top/Article/details/gthlatrsor.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xziqi.cn/Article/details/gtnysjoosj.html

) t WHERE rn = 1;
来源：http://dali.xuanzx.com/Article/details/gtgmeyirck.html

[Q35] 内连接
来源：http://dali.wangshuangyany.cn/Article/details/gtksitodzk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuxming.cn/Article/details/gtxvgexqbz.html

[Q36] 左连接
来源：http://dali.zhongyouzk.top/Article/details/gtlkiushds.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ppjwa.cn/Article/details/gtgxssoqeu.html

[Q37] 右连接
来源：http://dali.vqdsnc.cn/Article/details/gtdqnxlzcw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xuetiantiany.cn/Article/details/gtoszftbbn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jqgfzy.top/Article/details/gtxdogaewh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhengqikj.top/Article/details/gttedldncm.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gtdfziqipm.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hfpthk.cn/Article/details/gtuuwwudqc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.0kj1m.cn/Article/details/gttgbkskqg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sysykeji.top/Article/details/gthjobccxh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.gaohongyu789.top/Article/details/gtbwxtlybl.html

[Q41] 多表连接
来源：http://dali.andypj.xyz/Article/details/gtfrrktebz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hongshengwenyu.top/Article/details/gtahvdzula.html

JOIN users u ON u.id = o.user_id
来源：http://dali.316326.xyz/Article/details/gtdgejbrlx.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.316326.xyz/Article/details/gtoomjihms.html

[Q42] 连接条件附加过滤
来源：http://dali.yueranfly.top/Article/details/gtvbxqsogm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhoulong.xyz/Article/details/gtypbgbjys.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.vqdsnc.cn/Article/details/gtopcgdhpo.html

[Q43] 标量子查询
来源：http://dali.hongshengwenyu.top/Article/details/gtereacosy.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xuetiantiany.cn/Article/details/gtzxjxfqlr.html

[Q44] IN 子查询
来源：http://dali.wangshuangyany.cn/Article/details/gtmabsmlus.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.pycfn.com/Article/details/gtstzrjksh.html

[Q45] EXISTS 判断存在
来源：http://dali.hysaishi.cn/Article/details/gttewmjfbm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cheryme.top/Article/details/gtykzjwajt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.sysykeji.top/Article/details/gtvmrhnlrt.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hnxiangtu.top/Article/details/gtcwazrida.html

[Q47] 与平均值比较
来源：http://dali.svipenyu.cn/Article/details/gtbcqlcspw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.andypj.xyz/Article/details/gtihheizbo.html

[Q48] CTE 公用表表达式
来源：http://dali.zhoulong.xyz/Article/details/gtqtwrrvwk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cqqwz.cn/Article/details/gtfjuxwtbg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.daria6918.cn/Article/details/gtnvbgyobe.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gtluieuktm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgzkkazic.html

[Q50] 批量更新
来源：http://dali.yj202588.top/Article/details/gtflawvagh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yanxiufei.cn/Article/details/gtxwokrivh.html

[Q51] 用子查询更新
来源：http://dali.wangdashe.top/Article/details/gtilogswtd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cqqwz.cn/Article/details/gtcehsdazl.html

[Q52] 删除指定行
来源：http://dali.zdqjudy.top/Article/details/gturhcvdee.html

DELETE FROM users WHERE id = 10;
来源：http://dali.fengsongda.top/Article/details/gthtqktlvz.html

[Q53] 按条件删除
来源：http://dali.sweek.top/Article/details/gtcilyakst.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.kuanghao11.cn/Article/details/gtslmwarbq.html

[Q54] 清空表
来源：http://dali.meibo888.top/Article/details/gtqkhkmnxi.html

TRUNCATE TABLE logs;
来源：http://dali.sysykeji.top/Article/details/gtqmbdesus.html

[Q55] 排名（并列占位）
来源：http://dali.iojbl.cn/Article/details/gtjlsrsbmp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jyoumei.cn/Article/details/gteiidauun.html

[Q56] 密集排名（并列不占位）
来源：http://dali.nwbrower.top/Article/details/gttowqpqfr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yongpay.top/Article/details/gtplodpper.html

[Q57] 行号
来源：http://dali.guowangkeji.top/Article/details/gtwogcmlky.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtfywxaymv.html

[Q58] 累计求和
来源：http://dali.yanxiufei.cn/Article/details/gtirgetkku.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gtjyctqnqt.html

[Q59] 分组内累计
来源：http://dali.gotoacloud.top/Article/details/gthnjwgqjf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gtmhnkdacl.html

[Q60] 取上一行 / 下一行
来源：http://dali.birdmap.top/Article/details/gtqsrbzvyu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmdhteoen.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gtjkrqdrrh.html

[Q61] 移动平均
来源：http://dali.daxiang520.top/Article/details/gtravoftne.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.fzhhl.top/Article/details/gtymrkfhfs.html

[Q62] 分组占比
来源：http://dali.yongpay.top/Article/details/gtobqadgsi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ybcxt.top/Article/details/gtxoiqxeyb.html

[Q63] 开启事务
来源：http://dali.xziqi.cn/Article/details/gttixvrian.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.haohaochexian.top/Article/details/gticjgmvvr.html

[Q64] 提交事务
来源：http://dali.xinyue.icu/Article/details/gtvolpvmvm.html

COMMIT;
来源：http://dali.fzhhl.top/Article/details/gtxqocmwvp.html

[Q65] 回滚事务
来源：http://dali.zhoulong.xyz/Article/details/gtrvqgvmdu.html

ROLLBACK;
来源：http://dali.jinqigfzy.top/Article/details/gtpfvdrnbx.html

[Q66] 行锁查询
来源：http://dali.chenzaomai.com/Article/details/gtgntweavj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.nwbrower.top/Article/details/gtunxxettn.html

[Q67] 设置隔离级别
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgferqrvv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yonumen.top/Article/details/gtyukuwjlq.html

[Q68] 保存点
来源：http://dali.snrcjt.cn/Article/details/gtpppzjyvn.html

SAVEPOINT sp1;
来源：http://dali.cqqwz.cn/Article/details/gtxublfcdd.html

ROLLBACK TO sp1;
来源：http://dali.sufxvd.cn/Article/details/gtuvsecdej.html

[Q69] 查看执行计划
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtidijhmlk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xuetiantiany.cn/Article/details/gtpwsuxdqm.html

[Q70] 更新统计信息
来源：http://dali.wangdashe.top/Article/details/gtdalvpsxm.html

ANALYZE TABLE users;
来源：http://dali.zhengqikj.top/Article/details/gtzuwjzjvm.html

[Q71] 查看建表语句
来源：http://dali.hnqzz.top/Article/details/gtfirkvark.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yj20258.top/Article/details/gtptggyskd.html

[Q72] 查看索引
来源：http://dali.yonumen.top/Article/details/gtnyggxoxa.html

SHOW INDEX FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtbgjoenuc.html

[Q73] 查看表状态
来源：http://dali.birdmap.top/Article/details/gteefcqjfs.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jyoumei.cn/Article/details/gtoaahypes.html

[Q74] 强制使用索引
来源：http://dali.zycfv.cn/Article/details/gtqskcxdqt.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yueranfly.top/Article/details/gtjcvlyfty.html

[Q75] 日期格式化
来源：http://dali.shangyingyoupin.top/Article/details/gtwexovtvl.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gtguulzvut.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.smart0.xyz/Article/details/gtnguanmlo.html

[Q76] 按天统计
来源：http://dali.kuanghao11.cn/Article/details/gtixkvzulb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.aibaodan.cn/Article/details/gtifniwxgv.html

[Q77] 时间加减
来源：http://dali.birdmap.top/Article/details/gtfudhbiza.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zycfv.cn/Article/details/gtgadqraca.html

[Q78] 当前时间
来源：http://dali.yuanzhike.top/Article/details/gtkhetsoar.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zdqjudy.top/Article/details/gtgskadiyt.html

[Q79] 字符串拼接
来源：http://dali.wangdashe.top/Article/details/gttlzlaqhn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ywan-chungtsiang.top/Article/details/gthrgiixat.html

[Q80] 字符串截取
来源：http://dali.chenjidiqi.icu/Article/details/gtstelaydm.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtrfgbnrec.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gtrtjmlkru.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shuidangran.top/Article/details/gttgvnwttn.html

[Q82] 字符长度与字节长度
来源：http://dali.quarkkingdee.top/Article/details/gtmsengdip.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yuxming.cn/Article/details/gthiceyrev.html

[Q83] 大小写转换
来源：http://dali.jqgufenzy.top/Article/details/gtquogjqwa.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtlxfhgwwl.html

[Q84] 去除首尾空格
来源：http://dali.nanxinkj.top/Article/details/gtpqhjhxip.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtincrqlpo.html

[Q85] 数值取整
来源：http://dali.zhongyouzk.top/Article/details/gtiiubshzo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.tianlin.xyz/Article/details/gtljflpepb.html

[Q86] 读取 JSON 字段
来源：http://dali.sxryk.cn/Article/details/gtquybbmpp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.bjfxy.top/Article/details/gtwdrdzswz.html

[Q87] JSON 字段做条件
来源：http://dali.guannengcc.top/Article/details/gtwgclyjup.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.sxryk.cn/Article/details/gtnrvlwnhj.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhoulong.xyz/Article/details/gttulkxxpx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hnxiangtu.top/Article/details/gtspmmsnds.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtspwrhybp.html

[Q89] 判断表是否存在
来源：http://dali.daxiang520.top/Article/details/gtsgfrhmaj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shangyingyoupin.top/Article/details/gtzjcxkvtr.html

[Q90] 生成序号列
来源：http://dali.meibo888.top/Article/details/gtockwemcp.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhiwuduotai.top/Article/details/gturloidia.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtuarsntew.html

R. Bash 专题
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwremibxv.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtgbzaxtdf.html

[R01] shebang 与严格模式
来源：http://dali.yvedp.cn/Article/details/gtiftuudwn.html

#!/usr/bin/env bash
来源：http://dali.snrcjt.cn/Article/details/gtqfhsvwzr.html

set -euo pipefail
来源：http://dali.iojbl.cn/Article/details/gtyckbqqmo.html

[R02] 变量赋值与使用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgjechtxd.html

name="Tom"; echo "$name"
来源：http://dali.ydzc1.top/Article/details/gtrxlboorw.html

[R03] 只读变量
来源：http://dali.redwolf501.top/Article/details/gtxukwnluk.html

readonly PI=3.14
来源：http://dali.iojbl.cn/Article/details/gtnmncvayy.html

[R04] 位置参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyzpwtwif.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.redwolf501.top/Article/details/gtguhrzvey.html

[R05] 参数默认值
来源：http://dali.zhoulong.xyz/Article/details/gtervoptmi.html

name="${1:-default}"
来源：http://dali.jyoumei.cn/Article/details/gtmvjugabm.html

[R06] 判断命令是否存在
来源：http://dali.0kj1m.cn/Article/details/gtclbczczx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwjqlaodz.html

[R07] if 判断文件
来源：http://dali.zhoulong.xyz/Article/details/gtckcvqmvd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ydzc1.top/Article/details/gtnlkwiaau.html

[R08] 数值比较
来源：http://dali.yuanzhike.top/Article/details/gtxnevjxvv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.snrcjt.cn/Article/details/gtfbspzomk.html

[R09] 字符串比较
来源：http://dali.nwbrower.top/Article/details/gtiqpkfyyo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yanxiufei.cn/Article/details/gtikvnnptv.html

[R10] 正则匹配
来源：http://dali.hnqzz.top/Article/details/gtyqbykpuk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ybcxt.top/Article/details/gttvudqhxt.html

[R11] case 多分支
来源：http://dali.nanxinkj.top/Article/details/gtvcrqllwm.html

case "$1" in
来源：http://dali.hongshengwenyu.top/Article/details/gtlupbhtbx.html

start) echo "启动" ;;
来源：http://dali.nanxinkj.top/Article/details/gtqpspatke.html

stop)  echo "停止" ;;
来源：http://dali.meibo888.top/Article/details/gtnxrymesu.html

*)     echo "未知命令" ;;
来源：http://dali.bjfxy.top/Article/details/gtbvzvgkgc.html

esac
来源：http://dali.ywan-chungtsiang.top/Article/details/gtydeqycis.html

[R12] for 遍历文件
来源：http://dali.zhongyouzk.top/Article/details/gtmvhndfwz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.guannengcc.top/Article/details/gtfbrswdrz.html

[R13] for 计数循环
来源：http://dali.hfpthk.cn/Article/details/gtmrakhvpe.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.havefunace.top/Article/details/gtyexfgnwk.html

[R14] C 风格 for
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqlkjtynf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.wangshuangyany.cn/Article/details/gtbgdmuoxq.html

[R15] while 逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gtlaptllcz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.nwbrower.top/Article/details/gtwfcvognk.html

[R16] until 等待条件
来源：http://dali.cdnleiting.top/Article/details/gtwdhvmvjm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.0kj1m.cn/Article/details/gtioqpzmpz.html

[R17] 数组定义与取值
来源：http://dali.chenlongwang.top/Article/details/gtuuyxxxmx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yj20258.top/Article/details/gtffocvhbr.html

[R18] 遍历数组
来源：http://dali.yangfankeji.com/Article/details/gtllnuxrxo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hammf.cn/Article/details/gtgbldzefb.html

[R19] 数组长度
来源：http://dali.nanxuanxn.top/Article/details/gtrzbfgbfv.html

echo "${#arr[@]}"
来源：http://dali.jinqigfzy.top/Article/details/gtrhjaarrx.html

[R20] 关联数组（字典）
来源：http://dali.andypj.xyz/Article/details/gtddfmvlwh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.pengpengdd.cyou/Article/details/gtskcwjjhp.html

[R21] 字符串长度
来源：http://dali.yvedp.cn/Article/details/gtfvwmnixy.html

echo "${#s}"
来源：http://dali.fzhhl.top/Article/details/gtetxichyy.html

[R22] 截取子串
来源：http://dali.dianchejie.cn/Article/details/gtjyiubacy.html

echo "${s:0:5}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gttiskqxhn.html

[R23] 字符串替换
来源：http://dali.yuxming.cn/Article/details/gtlwlufoom.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yuxming.cn/Article/details/gtrmjkqacb.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gtassycuvq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.dashuyun.cn/Article/details/gtehwzpdkv.html

[R25] 去后缀 / 去前缀
来源：http://dali.wangshuangyany.cn/Article/details/gtailmhesj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.svipenyu.cn/Article/details/gtdlxdrgqu.html

[R26] 命令替换
来源：http://dali.yongpay.top/Article/details/gtgjmqinjq.html

now=$(date +%F); echo "$now"
来源：http://dali.hnqzz.top/Article/details/gtskzwuxxs.html

[R27] 算术展开
来源：http://dali.dianchejie.cn/Article/details/gtsatxmnvj.html

echo $((1 + 2 * 3))
来源：http://dali.tianlin.xyz/Article/details/gtztxlbhgy.html

[R28] 浮点运算
来源：http://dali.shangyingyoupin.top/Article/details/gtyvhtlubr.html

echo "scale=2; 10/3" | bc
来源：http://dali.c1oappe.top/Article/details/gtamooigel.html

[R29] 定义函数
来源：http://dali.mhx1999.top/Article/details/gtoxilgxtz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ehwqpu.com/Article/details/gtrnbakxqa.html

[R30] 函数返回状态码
来源：http://dali.zhoulong.xyz/Article/details/gtxhcfqdhy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.dianchejie.cn/Article/details/gtjuepdmye.html

[R31] 局部变量
来源：http://dali.hfpthk.cn/Article/details/gtjdsuxfdl.html

f() { local x=1; echo "$x"; }
来源：http://dali.daxiang520.top/Article/details/gtkpzynuip.html

[R32] 参数个数校验
来源：http://dali.svipenyu.cn/Article/details/gtuafjmijr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hongshengwenyu.top/Article/details/gtatyxwfjk.html

[R33] 捕获错误并提示行号
来源：http://dali.gzhubu.top/Article/details/gtagjmfibd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.aibaodan.cn/Article/details/gtnpnpokzv.html

[R34] 退出时清理
来源：http://dali.tian-w.cn/Article/details/gtsvwhfbat.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cheryme.top/Article/details/gtjirpfczw.html

[R35] 后台执行并等待
来源：http://dali.chenjidiqi.icu/Article/details/gtwprdzved.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cucudq.cn/Article/details/gtzvsxyege.html

[R36] 并发执行多个任务
来源：http://dali.dianchejie.cn/Article/details/gtqvctwrrv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.chenlongwang.top/Article/details/gtgjfaikyt.html

[R37] 把输出赋给变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtihtfqhoy.html

files=$(ls -1)
来源：http://dali.xylfe.cn/Article/details/gtnwymywez.html

[R38] 管道串联
来源：http://dali.cqqwz.cn/Article/details/gtxdzyzizr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.havefunace.top/Article/details/gtmkkaoqhk.html

[R39] 重定向标准输出与错误
来源：http://dali.svipenyu.cn/Article/details/gtvqbjyuzl.html

cmd > out.log 2>&1
来源：http://dali.bjfxy.top/Article/details/gtpfdayqui.html

[R40] 追加写日志
来源：http://dali.aibaodan.cn/Article/details/gtzsjuzggn.html

echo "log" >> out.log
来源：http://dali.0kj1m.cn/Article/details/gtqhhmouxj.html

[R41] 丢弃输出
来源：http://dali.jqgfzy.top/Article/details/gtrefxkptn.html

cmd >/dev/null 2>&1
来源：http://dali.svipenyu.cn/Article/details/gterjknnwg.html

[R42] 输入重定向
来源：http://dali.jlsjyb.cn/Article/details/gtrqhztnlh.html

wc -l < a.txt
来源：http://dali.yj202588.top/Article/details/gtmcfcpmcj.html

[R43] 按名字查找文件
来源：http://dali.pycfn.com/Article/details/gttpfwcehg.html

find . -name "*.log" -type f
来源：http://dali.nanxuanxn.top/Article/details/gtrzjtlrii.html

[R44] 按修改时间查找
来源：http://dali.sufxvd.cn/Article/details/gtdwzuehzs.html

find . -mtime -7 -type f
来源：http://dali.yonumen.top/Article/details/gtofokluns.html

[R45] 批量删除
来源：http://dali.gzhubu.top/Article/details/gtsmwvagdw.html

find . -name "*.tmp" -delete
来源：http://dali.zdqjudy.top/Article/details/gtzpoiivld.html

[R46] 递归替换文件内容
来源：http://dali.shanyushiyangtech.top/Article/details/gtdmcqfgty.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.tianlin.xyz/Article/details/gtsymfgnhr.html

[R47] sed 单行替换
来源：http://dali.quarkkingdee.top/Article/details/gtzugpvieo.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sufxvd.cn/Article/details/gtmukhhgpn.html

[R48] awk 取指定列
来源：http://dali.hysaishi.cn/Article/details/gtnskwckks.html

awk '{print $1, $3}' a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoxbfwcab.html

[R49] awk 带条件
来源：http://dali.yonumen.top/Article/details/gtyfiiygoy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhixingplan.top/Article/details/gthwuxtvqo.html

[R50] awk 求和
来源：http://dali.0kj1m.cn/Article/details/gtfchhpnoc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hnqzz.top/Article/details/gtgumkhldj.html

[R51] 排序去重取前几
来源：http://dali.haohaochexian.top/Article/details/gtboiyvaqu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.andypj.xyz/Article/details/gtstcyizga.html

[R52] 统计行数
来源：http://dali.jinqigufen.top/Article/details/gtxvefzlnr.html

wc -l a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtbmhxogkp.html

[R53] 查看文件头与实时尾
来源：http://dali.redwolf501.top/Article/details/gtlophwgbb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.birdmap.top/Article/details/gtfrfckdus.html

[R54] 比较两个文件
来源：http://dali.ehwqpu.com/Article/details/gtlbxzojqt.html

diff a.txt b.txt
来源：http://dali.yj202588.top/Article/details/gtvtcimcbq.html

[R55] 压缩与解压
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjyjcignn.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.meibo888.top/Article/details/gtswvkzsrk.html

[R56] 远程拷贝
来源：http://dali.zhongyouzk.top/Article/details/gttszkxrzy.html

scp file user@host:/path/
来源：http://dali.sysykeji.top/Article/details/gtlksqotsw.html

[R57] 远程执行命令
来源：http://dali.jinqigufen.top/Article/details/gtcldzuczw.html

ssh user@host 'uptime'
来源：http://dali.hammf.cn/Article/details/gttnxlivod.html

[R58] 下载文件
来源：http://dali.cheryme.top/Article/details/gtzrktrocs.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.havefunace.top/Article/details/gtlxnwfgaq.html

[R59] 发 POST JSON
来源：http://dali.gotoacloud.top/Article/details/gtixmkebwd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.iojbl.cn/Article/details/gtehjumisz.html

[R60] 只看 HTTP 状态码
来源：http://dali.cashguo.top/Article/details/gtxgtamgar.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jianghu66.top/Article/details/gtelgcmweu.html

[R61] 磁盘占用
来源：http://dali.yj20258.top/Article/details/gtocqdiskj.html

df -h;  du -sh *
来源：http://dali.nwbrower.top/Article/details/gtcsqzdwkh.html

[R62] 找最占空间的文件
来源：http://dali.shzxlz.cn/Article/details/gtfhpzunui.html

du -ah . | sort -rh | head -10
来源：http://dali.jinyuanbaomall.cn/Article/details/gttefbkxdh.html

[R63] 内存与进程
来源：http://dali.wangdashe.top/Article/details/gtxcqqtpsc.html

free -h;  ps aux | grep nginx
来源：http://dali.dianchejie.cn/Article/details/gtztimhqrc.html

[R64] 结束进程
来源：http://dali.shuidangran.top/Article/details/gtinirilho.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xuanzx.com/Article/details/gtqfzzgfgy.html

[R65] 查看端口占用
来源：http://dali.yongpay.top/Article/details/gtvubvmsaw.html


<!-- 参考信息 -->