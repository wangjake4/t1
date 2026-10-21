代发 wailian999

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.nwbrower.top/Article/details/gtujphgsgy.html

[Q11] 一次插入多行
来源：http://dali.svipenyu.cn/Article/details/gtncqgbsms.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hnqzz.top/Article/details/gtxokpnjsw.html

[Q12] 插入后取自增 ID
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwopunvzf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.haohaochexian.top/Article/details/gtxhofhrnz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.9152youxi.cn/Article/details/gtxwqzghxq.html

[Q13] 忽略重复插入
来源：http://dali.daxiang520.top/Article/details/gtvqamqhym.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.daria6918.cn/Article/details/gtxcpmlxif.html

[Q14] 存在则更新（upsert）
来源：http://dali.bjfxy.top/Article/details/gthgftfaso.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.redwolf501.top/Article/details/gtcdwsgqwe.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.daxiang520.top/Article/details/gtrjnovoia.html

[Q15] 查询全部
来源：http://dali.haohaochexian.top/Article/details/gtxchaaomx.html

SELECT * FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gthdiwvghm.html

[Q16] 查询指定列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtohytwahd.html

SELECT id, name FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnitnbcrb.html

[Q17] 条件查询
来源：http://dali.pycfn.com/Article/details/gtkqqsfvzv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.snrcjt.cn/Article/details/gtuczrpzli.html

[Q18] 模糊匹配
来源：http://dali.chenlongwang.top/Article/details/gtsvqpguse.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.kuanghao11.cn/Article/details/gtdmyvfzay.html

[Q19] 范围查询
来源：http://dali.nwbrower.top/Article/details/gtyibrtadp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.iojbl.cn/Article/details/gtqsfrvhlv.html

[Q20] IN 列表
来源：http://dali.xinyue.icu/Article/details/gtfnbxnkpp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinqigfzy.top/Article/details/gtgfqtbcot.html

[Q21] 空值判断
来源：http://dali.chenzaomai.com/Article/details/gttrnakcfb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xuanzx.com/Article/details/gtcyehsrzb.html

[Q22] 排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwhuxulxe.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yj202588.top/Article/details/gtynvuuvml.html

[Q23] 分页
来源：http://dali.yangfankeji.com/Article/details/gtmsdpzdtw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xinyue.icu/Article/details/gtgjdcvgbt.html

[Q24] 去重
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjcfitgoo.html

SELECT DISTINCT city FROM users;
来源：http://dali.nwbrower.top/Article/details/gtexffpwdm.html

[Q25] 只取前 N 条
来源：http://dali.9152youxi.cn/Article/details/gtmgnehpff.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.fzhhl.top/Article/details/gtuofkudnf.html

[Q26] 计数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtolcysqxn.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxlxdxavy.html

[Q27] 条件计数
来源：http://dali.sufxvd.cn/Article/details/gtvbpyqdyo.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yueranfly.top/Article/details/gtjbohqgwi.html

[Q28] 求和与平均
来源：http://dali.bjfxy.top/Article/details/gtcutbqqtt.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cheryme.top/Article/details/gtziuxvbud.html

[Q29] 最大最小值
来源：http://dali.mhx1999.top/Article/details/gtwcuxkuuq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xinyue.icu/Article/details/gtkexsbljc.html

[Q30] 分组统计
来源：http://dali.dianchejie.cn/Article/details/gtlueiugrf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.aizwys.cn/Article/details/gtsucnatxt.html

[Q31] 分组后过滤
来源：http://dali.redwolf501.top/Article/details/gtmjrgaqpq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yueranfly.top/Article/details/gtbdpytgdr.html

[Q32] 分组拼接字符串
来源：http://dali.hywenlv.cn/Article/details/gtfhpbqjsc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkondqroe.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.shuidangran.top/Article/details/gtjkggkkyy.html

[Q33] 多列分组
来源：http://dali.zdqjudy.top/Article/details/gtkfdxrfeg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shuidangran.top/Article/details/gtghphecme.html

[Q34] 每组取第一条
来源：http://dali.yj20258888.top/Article/details/gtzhzrutbh.html

SELECT * FROM (
来源：http://dali.jianghu66.top/Article/details/gtjqqmdpci.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.sufxvd.cn/Article/details/gtqxiljyyp.html

) t WHERE rn = 1;
来源：http://dali.dianchejie.cn/Article/details/gtyjccvhlt.html

[Q35] 内连接
来源：http://dali.fzhhl.top/Article/details/gtsetuezka.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwzixhvkr.html

[Q36] 左连接
来源：http://dali.jlsjyb.cn/Article/details/gtanrybvww.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.fzhhl.top/Article/details/gtoaishkop.html

[Q37] 右连接
来源：http://dali.xuetiantiany.cn/Article/details/gtqcaxwdhv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.svipenyu.cn/Article/details/gtfpwudohn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yueranfly.top/Article/details/gtevcpomdr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.sysykeji.top/Article/details/gthqfhfaav.html

[Q39] 自连接（查上下级）
来源：http://dali.xinyue.icu/Article/details/gtkptscybv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.meibo888.top/Article/details/gttfmigdgy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.sufxvd.cn/Article/details/gthzkkohwx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.chenlongwang.top/Article/details/gtkvwfrewo.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yonumen.top/Article/details/gtnuahzlmr.html

[Q41] 多表连接
来源：http://dali.jlsjyb.cn/Article/details/gtyhdzuhuc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.haohaochexian.top/Article/details/gtetotfutw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.snrcjt.cn/Article/details/gtauuiebfv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.daria6918.cn/Article/details/gtkggbmbln.html

[Q42] 连接条件附加过滤
来源：http://dali.yanxiufei.cn/Article/details/gtxmvlxvaf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.feifeiyinyue.top/Article/details/gtwbxcwltk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yj20258.top/Article/details/gtzsmshfwo.html

[Q43] 标量子查询
来源：http://dali.hysaishi.cn/Article/details/gtwivisnyg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jinqigfzy.top/Article/details/gteitprfvx.html

[Q44] IN 子查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrehglqcc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.sufxvd.cn/Article/details/gtkmntdzey.html

[Q45] EXISTS 判断存在
来源：http://dali.yuxming.cn/Article/details/gtbtgneysi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yvedp.cn/Article/details/gtafguwnja.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hywenlv.cn/Article/details/gthvnoualh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhengqikj.top/Article/details/gtaimlsyou.html

[Q47] 与平均值比较
来源：http://dali.hammf.cn/Article/details/gtnjdhhftg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.guowangkeji.top/Article/details/gtgvjlxuao.html

[Q48] CTE 公用表表达式
来源：http://dali.yj202588.top/Article/details/gtvncqssdo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinghuilouyu.cn/Article/details/gttzofbiww.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxbxqcakz.html

[Q49] 更新单行
来源：http://dali.zhoulong.xyz/Article/details/gtrsvukxpv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jiagoushi.top/Article/details/gtrlcrpdud.html

[Q50] 批量更新
来源：http://dali.jqgufenzy.top/Article/details/gthxjeigyc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.gogol.net.cn/Article/details/gtwsndxqva.html

[Q51] 用子查询更新
来源：http://dali.0kj1m.cn/Article/details/gtppjtpuqn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkemlppnw.html

[Q52] 删除指定行
来源：http://dali.zhixingplan.top/Article/details/gtggfamitq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jiagoushi.top/Article/details/gtykdrxnjb.html

[Q53] 按条件删除
来源：http://dali.hongshengwenyu.top/Article/details/gtsftghrnk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.feifeiyinyue.top/Article/details/gthifmntjp.html

[Q54] 清空表
来源：http://dali.hnqzz.top/Article/details/gtrtihhwtb.html

TRUNCATE TABLE logs;
来源：http://dali.jiagoushi.top/Article/details/gtvkgjrfxz.html

[Q55] 排名（并列占位）
来源：http://dali.yuxming.cn/Article/details/gttvapxsrd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.snrcjt.cn/Article/details/gtfryambyq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.sweek.top/Article/details/gtjvvdawbo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yvedp.cn/Article/details/gtbmqarchr.html

[Q57] 行号
来源：http://dali.zhixingplan.top/Article/details/gtpkfzctrf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtnwgdfkrz.html

[Q58] 累计求和
来源：http://dali.iojbl.cn/Article/details/gthdtqjwea.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ybcxt.top/Article/details/gtkehthlzt.html

[Q59] 分组内累计
来源：http://dali.zdqjudy.top/Article/details/gtbkiqawnv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gtezsstted.html

[Q60] 取上一行 / 下一行
来源：http://dali.yuanzhike.top/Article/details/gtbbxkuixa.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yongpay.top/Article/details/gtmvglsfuc.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.aizwys.cn/Article/details/gtdnvxpqvu.html

[Q61] 移动平均
来源：http://dali.sysykeji.top/Article/details/gtjveukqop.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtvbifqchw.html

[Q62] 分组占比
来源：http://dali.cashguo.top/Article/details/gtdkyspoaz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yangfankeji.com/Article/details/gtjkhwcmgl.html

[Q63] 开启事务
来源：http://dali.nanxuanxn.top/Article/details/gtwrkfgawh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jyoumei.cn/Article/details/gtsfuwvqfw.html

[Q64] 提交事务
来源：http://dali.gotoacloud.top/Article/details/gtwkudbwvr.html

COMMIT;
来源：http://dali.shuidangran.top/Article/details/gtpqtsftrr.html

[Q65] 回滚事务
来源：http://dali.havefunace.top/Article/details/gtfhlhhcir.html

ROLLBACK;
来源：http://dali.andypj.xyz/Article/details/gtvydssuml.html

[Q66] 行锁查询
来源：http://dali.chenlongwang.top/Article/details/gtpcutxchd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sweek.top/Article/details/gtlgvsxnkz.html

[Q67] 设置隔离级别
来源：http://dali.yj20258888.top/Article/details/gtqtveabdu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.svipenyu.cn/Article/details/gtyhqdrzyf.html

[Q68] 保存点
来源：http://dali.snrcjt.cn/Article/details/gtyvrrnsai.html

SAVEPOINT sp1;
来源：http://dali.yuxming.cn/Article/details/gtxznnoqpq.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gtdkrvffgz.html

[Q69] 查看执行计划
来源：http://dali.hfpthk.cn/Article/details/gtzaqeeyig.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ybcxt.top/Article/details/gtipyrpqao.html

[Q70] 更新统计信息
来源：http://dali.dianchejie.cn/Article/details/gtoakrdlsh.html

ANALYZE TABLE users;
来源：http://dali.sysykeji.top/Article/details/gtrajegbjc.html

[Q71] 查看建表语句
来源：http://dali.dashuyun.cn/Article/details/gtycvmglge.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hnqzz.top/Article/details/gtehebnmme.html

[Q72] 查看索引
来源：http://dali.yongpay.top/Article/details/gthszzyzpp.html

SHOW INDEX FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtqevpwssc.html

[Q73] 查看表状态
来源：http://dali.xuanzx.com/Article/details/gttrjlanqw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.dianchejie.cn/Article/details/gtnzzwyucj.html

[Q74] 强制使用索引
来源：http://dali.iojbl.cn/Article/details/gtpspzrqyd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xylfe.cn/Article/details/gtenjlosrh.html

[Q75] 日期格式化
来源：http://dali.hnqzz.top/Article/details/gtmcqclpta.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gtpmgxaunn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.kuanghao11.cn/Article/details/gtdbvzyxja.html

[Q76] 按天统计
来源：http://dali.cqqwz.cn/Article/details/gtvbzltadt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.daria6918.cn/Article/details/gtblerbckl.html

[Q77] 时间加减
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdyqmzlcs.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.c1oappe.top/Article/details/gtgnwjblbz.html

[Q78] 当前时间
来源：http://dali.yj202588.top/Article/details/gthtvgyrha.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhixingplan.top/Article/details/gtuzwdpfhz.html

[Q79] 字符串拼接
来源：http://dali.xuanzx.com/Article/details/gtdnkrknbs.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.wangdashe.top/Article/details/gtkkyqopfk.html

[Q80] 字符串截取
来源：http://dali.jinqigufen.top/Article/details/gtqeylablx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yvedp.cn/Article/details/gthaqejbeo.html

[Q81] 字符串替换
来源：http://dali.ybcxt.top/Article/details/gtuecbagbj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtylvccyge.html

[Q82] 字符长度与字节长度
来源：http://dali.sweek.top/Article/details/gtlxhlwjll.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cashguo.top/Article/details/gtbjrkjtki.html

[Q83] 大小写转换
来源：http://dali.meibo888.top/Article/details/gtnnbsgnuc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ydzc1.top/Article/details/gteteshshj.html

[Q84] 去除首尾空格
来源：http://dali.yangfankeji.com/Article/details/gteqltqois.html

SELECT TRIM(name) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtnewxgmmu.html

[Q85] 数值取整
来源：http://dali.cashguo.top/Article/details/gtixxzsybm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhixingplan.top/Article/details/gtfhgrrqso.html

[Q86] 读取 JSON 字段
来源：http://dali.ehwqpu.com/Article/details/gtpdllllwu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.316326.xyz/Article/details/gtaiaqrsor.html

[Q87] JSON 字段做条件
来源：http://dali.dianchejie.cn/Article/details/gttubgicml.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xylfe.cn/Article/details/gtbiitgddm.html

[Q88] 行转列（条件聚合）
来源：http://dali.dianchejie.cn/Article/details/gthidkxegp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.fzhhl.top/Article/details/gtvahtyend.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtlfqldjtb.html

[Q89] 判断表是否存在
来源：http://dali.aizwys.cn/Article/details/gtjheipvqz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cucudq.cn/Article/details/gtiefeioka.html

[Q90] 生成序号列
来源：http://dali.hywenlv.cn/Article/details/gtxgjvcpcg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tanke756.top/Article/details/gtquwtcrhz.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtmnwyvyyi.html

R. Bash 专题
来源：http://dali.zhoulong.xyz/Article/details/gtbvaqtiag.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtfxcwtmfl.html

[R01] shebang 与严格模式
来源：http://dali.hnxiangtu.top/Article/details/gtcewmjtmn.html

#!/usr/bin/env bash
来源：http://dali.hywenlv.cn/Article/details/gtxvqmgvuc.html

set -euo pipefail
来源：http://dali.hysaishi.cn/Article/details/gtpveeisng.html

[R02] 变量赋值与使用
来源：http://dali.yuanzhike.top/Article/details/gtivxbibuc.html

name="Tom"; echo "$name"
来源：http://dali.quarkkingdee.top/Article/details/gteilovlhw.html

[R03] 只读变量
来源：http://dali.hysaishi.cn/Article/details/gtvlndmrss.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gtfbysavyw.html

[R04] 位置参数
来源：http://dali.xuetiantiany.cn/Article/details/gtadtuqhnh.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xziqi.cn/Article/details/gtoztxpwwp.html

[R05] 参数默认值
来源：http://dali.chenlongwang.top/Article/details/gtadkonxlb.html

name="${1:-default}"
来源：http://dali.dashuyun.cn/Article/details/gtqudrizqw.html

[R06] 判断命令是否存在
来源：http://dali.yanxiufei.cn/Article/details/gtjuqrhuvz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jianghu66.top/Article/details/gtjzmagohv.html

[R07] if 判断文件
来源：http://dali.ppjwa.cn/Article/details/gtalpduyqs.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cashguo.top/Article/details/gtwtnlskxl.html

[R08] 数值比较
来源：http://dali.hfpthk.cn/Article/details/gtbvbjrbjo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gotoacloud.top/Article/details/gtsayqdzmr.html

[R09] 字符串比较
来源：http://dali.shuidangran.top/Article/details/gtipgtfmvr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.vqdsnc.cn/Article/details/gtglclwblo.html

[R10] 正则匹配
来源：http://dali.feifeiyinyue.top/Article/details/gtdacwlsyu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cqqwz.cn/Article/details/gttpwzauiy.html

[R11] case 多分支
来源：http://dali.xziqi.cn/Article/details/gtkiqhykft.html

case "$1" in
来源：http://dali.sufxvd.cn/Article/details/gtwkuxbnyk.html

start) echo "启动" ;;
来源：http://dali.chenzaomai.com/Article/details/gttuhqcvng.html

stop)  echo "停止" ;;
来源：http://dali.ivvv.top/Article/details/gtskpivskc.html

*)     echo "未知命令" ;;
来源：http://dali.xuetiantiany.cn/Article/details/gtmxvtclmx.html

esac
来源：http://dali.xziqi.cn/Article/details/gticxgngub.html

[R12] for 遍历文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtrnrajoen.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xziqi.cn/Article/details/gtzwvwcqha.html

[R13] for 计数循环
来源：http://dali.yongpay.top/Article/details/gtizahexsw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cqqwz.cn/Article/details/gtdowhvouz.html

[R14] C 风格 for
来源：http://dali.hywenlv.cn/Article/details/gtzzaldunn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gzhubu.top/Article/details/gtmprymett.html

[R15] while 逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gtdptfuxlj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sufxvd.cn/Article/details/gtisyaiels.html

[R16] until 等待条件
来源：http://dali.zdqjudy.top/Article/details/gticsmgfyd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hywenlv.cn/Article/details/gtunlfaeqd.html

[R17] 数组定义与取值
来源：http://dali.gaohongyu789.top/Article/details/gtdogsshzo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.aizwys.cn/Article/details/gtgnaarrdn.html

[R18] 遍历数组
来源：http://dali.wangshuangyany.cn/Article/details/gthkxzyucv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jiagoushi.top/Article/details/gtoswyhxbf.html

[R19] 数组长度
来源：http://dali.shuidangran.top/Article/details/gtewdiitib.html

echo "${#arr[@]}"
来源：http://dali.gogol.net.cn/Article/details/gtiwgtzesg.html

[R20] 关联数组（字典）
来源：http://dali.zhoulong.xyz/Article/details/gtttucwvri.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhoulong.xyz/Article/details/gtbyoisgie.html

[R21] 字符串长度
来源：http://dali.ydzc1.top/Article/details/gthcwtxbif.html

echo "${#s}"
来源：http://dali.zhoulong.xyz/Article/details/gtyauuoxey.html

[R22] 截取子串
来源：http://dali.hammf.cn/Article/details/gtnndudsme.html

echo "${s:0:5}"
来源：http://dali.bjfxy.top/Article/details/gtmfsvyshp.html

[R23] 字符串替换
来源：http://dali.nwbrower.top/Article/details/gtqdotbqqr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtubzlbtgu.html

[R24] 大小写转换
来源：http://dali.xinyue.icu/Article/details/gthjtvbvvv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.nanxinkj.top/Article/details/gtkenmgrea.html

[R25] 去后缀 / 去前缀
来源：http://dali.gzhubu.top/Article/details/gtnddyyzux.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shanyushiyangtech.top/Article/details/gttyhvehwu.html

[R26] 命令替换
来源：http://dali.yvedp.cn/Article/details/gtxkmtergc.html

now=$(date +%F); echo "$now"
来源：http://dali.andypj.xyz/Article/details/gtlhqysyhq.html

[R27] 算术展开
来源：http://dali.zhiwuduotai.top/Article/details/gttctjlreq.html

echo $((1 + 2 * 3))
来源：http://dali.shangyingyoupin.top/Article/details/gtlcjlfzac.html

[R28] 浮点运算
来源：http://dali.xziqi.cn/Article/details/gtkfkzeipg.html

echo "scale=2; 10/3" | bc
来源：http://dali.yj202588.top/Article/details/gtsefhijlp.html

[R29] 定义函数
来源：http://dali.yanxiufei.cn/Article/details/gtiycirdxz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.quarkkingdee.top/Article/details/gthrhpmzmp.html

[R30] 函数返回状态码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxfmcquvn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ehwqpu.com/Article/details/gtdkifbwoy.html

[R31] 局部变量
来源：http://dali.hnxiangtu.top/Article/details/gtlnmoqgay.html

f() { local x=1; echo "$x"; }
来源：http://dali.sweek.top/Article/details/gtbrvevvqg.html

[R32] 参数个数校验
来源：http://dali.shuidangran.top/Article/details/gtdjzfmyuu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cashguo.top/Article/details/gtflfrzoyh.html

[R33] 捕获错误并提示行号
来源：http://dali.aibaodan.cn/Article/details/gtlqfvzsgx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sweek.top/Article/details/gtndfybajt.html

[R34] 退出时清理
来源：http://dali.fzhhl.top/Article/details/gtqwrhjwhd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hywenlv.cn/Article/details/gthiivgzqs.html

[R35] 后台执行并等待
来源：http://dali.jiagoushi.top/Article/details/gtrallzysc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.dianchejie.cn/Article/details/gtgblfuluq.html

[R36] 并发执行多个任务
来源：http://dali.yj202588.top/Article/details/gtqdrrkwws.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.iojbl.cn/Article/details/gtedojatal.html

[R37] 把输出赋给变量
来源：http://dali.sufxvd.cn/Article/details/gtyvmtbjfx.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gtqeenszvk.html

[R38] 管道串联
来源：http://dali.shzxlz.cn/Article/details/gtyoeauohn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.316326.xyz/Article/details/gtprnnqfhk.html

[R39] 重定向标准输出与错误
来源：http://dali.yanxiufei.cn/Article/details/gtuskmijuj.html

cmd > out.log 2>&1
来源：http://dali.jqgfzy.top/Article/details/gtdyovirzn.html

[R40] 追加写日志
来源：http://dali.xinyue.icu/Article/details/gtaqokuict.html

echo "log" >> out.log
来源：http://dali.sweek.top/Article/details/gtbzpyfzrl.html

[R41] 丢弃输出
来源：http://dali.meibo888.top/Article/details/gtuxcxwkef.html

cmd >/dev/null 2>&1
来源：http://dali.hysaishi.cn/Article/details/gtatwmftrz.html

[R42] 输入重定向
来源：http://dali.quarkkingdee.top/Article/details/gtpsqrpkjt.html

wc -l < a.txt
来源：http://dali.yj202588.top/Article/details/gtivivykzf.html

[R43] 按名字查找文件
来源：http://dali.hnqzz.top/Article/details/gtuiuvrcua.html

find . -name "*.log" -type f
来源：http://dali.haohaochexian.top/Article/details/gthhwrabja.html

[R44] 按修改时间查找
来源：http://dali.ivvv.top/Article/details/gtyqszwtef.html

find . -mtime -7 -type f
来源：http://dali.yanxiufei.cn/Article/details/gtdikckqla.html

[R45] 批量删除
来源：http://dali.quarkkingdee.top/Article/details/gtduiailcq.html

find . -name "*.tmp" -delete
来源：http://dali.yongpay.top/Article/details/gtljzahyvu.html

[R46] 递归替换文件内容
来源：http://dali.daxiang520.top/Article/details/gtfxqlbwby.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.snrcjt.cn/Article/details/gtlqzcpyim.html

[R47] sed 单行替换
来源：http://dali.xinyue.icu/Article/details/gtendrvccm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.c1oappe.top/Article/details/gtgwjqwkps.html

[R48] awk 取指定列
来源：http://dali.hammf.cn/Article/details/gturwpfizy.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhixingplan.top/Article/details/gttkwmcavq.html

[R49] awk 带条件
来源：http://dali.mhx1999.top/Article/details/gtlhqyhpym.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.pycfn.com/Article/details/gtnwrycbyf.html

[R50] awk 求和
来源：http://dali.andypj.xyz/Article/details/gtfwfqtdmy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yanxiufei.cn/Article/details/gttkzvrmyt.html

[R51] 排序去重取前几
来源：http://dali.guowangkeji.top/Article/details/gtlliacjgz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.vqdsnc.cn/Article/details/gtwcmjhybw.html

[R52] 统计行数
来源：http://dali.zhongyouzk.top/Article/details/gtxlyvwcoy.html

wc -l a.txt
来源：http://dali.sweek.top/Article/details/gthjjumiqp.html

[R53] 查看文件头与实时尾
来源：http://dali.yuxming.cn/Article/details/gtaucglxfv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.tanke756.top/Article/details/gtxvlikuyc.html

[R54] 比较两个文件
来源：http://dali.yvedp.cn/Article/details/gtxhaqcefa.html

diff a.txt b.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkatowguz.html

[R55] 压缩与解压
来源：http://dali.jqgufenzy.top/Article/details/gtqrlkjxvx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.nwbrower.top/Article/details/gtfwsgqjqd.html

[R56] 远程拷贝
来源：http://dali.chenzaomai.com/Article/details/gtunjolcgq.html

scp file user@host:/path/
来源：http://dali.jqgfzy.top/Article/details/gtktjmmwzg.html

[R57] 远程执行命令
来源：http://dali.aizwys.cn/Article/details/gtbpxnnxcl.html

ssh user@host 'uptime'
来源：http://dali.iojbl.cn/Article/details/gtzacufezz.html

[R58] 下载文件
来源：http://dali.nanxinkj.top/Article/details/gtzcohffij.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gtpfzzvvgt.html

[R59] 发 POST JSON
来源：http://dali.wangdashe.top/Article/details/gtyysbmkkj.html


<!-- 参考信息 -->