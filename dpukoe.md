代发 wailian999

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yangfankeji.com/Article/details/gtqqqomtox.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hfpthk.cn/Article/details/gtcncaztka.html

[Q13] 忽略重复插入
来源：http://dali.yangfankeji.com/Article/details/gtbwdseggh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.birdmap.top/Article/details/gtcgkqqemk.html

[Q14] 存在则更新（upsert）
来源：http://dali.jianghu66.top/Article/details/gtniblsqrm.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ydzc1.top/Article/details/gtvqdpfydc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cheryme.top/Article/details/gtivtlygeu.html

[Q15] 查询全部
来源：http://dali.smart0.xyz/Article/details/gtmpbdwdne.html

SELECT * FROM users;
来源：http://dali.shuidangran.top/Article/details/gtqiybhhkz.html

[Q16] 查询指定列
来源：http://dali.zhoulong.xyz/Article/details/gtbuljriav.html

SELECT id, name FROM users;
来源：http://dali.yonumen.top/Article/details/gtmqrrmrit.html

[Q17] 条件查询
来源：http://dali.redwolf501.top/Article/details/gtozdtozlj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.9152youxi.cn/Article/details/gtavskeplg.html

[Q18] 模糊匹配
来源：http://dali.cheryme.top/Article/details/gtfdqbaarv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.pengpengdd.cyou/Article/details/gtyqesdjwf.html

[Q19] 范围查询
来源：http://dali.yanxiufei.cn/Article/details/gtaipbwuvn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinqigufen.top/Article/details/gtxmrgallu.html

[Q20] IN 列表
来源：http://dali.zhongyouzk.top/Article/details/gtshthfpjm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtladnzeuw.html

[Q21] 空值判断
来源：http://dali.yvedp.cn/Article/details/gtxpyyqiuw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.nanxinkj.top/Article/details/gtpbrvxtco.html

[Q22] 排序
来源：http://dali.redwolf501.top/Article/details/gtjorhdray.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhiwuduotai.top/Article/details/gtpqfeympb.html

[Q23] 分页
来源：http://dali.xuanzx.com/Article/details/gtmfjvbqvu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.quarkkingdee.top/Article/details/gtberbatzl.html

[Q24] 去重
来源：http://dali.cheryme.top/Article/details/gtzhllrftf.html

SELECT DISTINCT city FROM users;
来源：http://dali.sweek.top/Article/details/gtqwfukmsv.html

[Q25] 只取前 N 条
来源：http://dali.jinghuilouyu.cn/Article/details/gtvdkclmeh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gaohongyu789.top/Article/details/gtzrgolwlx.html

[Q26] 计数
来源：http://dali.yangfankeji.com/Article/details/gtgeistptf.html

SELECT COUNT(*) FROM users;
来源：http://dali.redwolf501.top/Article/details/gtrfhdyskb.html

[Q27] 条件计数
来源：http://dali.shuidangran.top/Article/details/gteazobpkp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.andypj.xyz/Article/details/gtugzxoiey.html

[Q28] 求和与平均
来源：http://dali.aibaodan.cn/Article/details/gtibhymxqs.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtzmpcinop.html

[Q29] 最大最小值
来源：http://dali.zhengqikj.top/Article/details/gtowqfazvr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xuanzx.com/Article/details/gthbhgjtjs.html

[Q30] 分组统计
来源：http://dali.xziqi.cn/Article/details/gtjzgrtnwm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.daria6918.cn/Article/details/gtwljwrsfx.html

[Q31] 分组后过滤
来源：http://dali.kuanghao11.cn/Article/details/gtshxbirrt.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yuxming.cn/Article/details/gtmpsbonql.html

[Q32] 分组拼接字符串
来源：http://dali.yvedp.cn/Article/details/gtlqchfiuw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.sysykeji.top/Article/details/gteooahyol.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.fzhhl.top/Article/details/gticcenvjj.html

[Q33] 多列分组
来源：http://dali.cashguo.top/Article/details/gtfycgxmto.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.aizwys.cn/Article/details/gtutdstlvd.html

[Q34] 每组取第一条
来源：http://dali.jiagoushi.top/Article/details/gtsbrnscmp.html

SELECT * FROM (
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbtnwzgjm.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hongshengwenyu.top/Article/details/gtdjbwpqyg.html

) t WHERE rn = 1;
来源：http://dali.andypj.xyz/Article/details/gthbwajdmn.html

[Q35] 内连接
来源：http://dali.fzhhl.top/Article/details/gtwekwdhpj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gaohongyu789.top/Article/details/gtiixbufcp.html

[Q36] 左连接
来源：http://dali.hnxiangtu.top/Article/details/gtnefocdet.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxinkj.top/Article/details/gtsnioypac.html

[Q37] 右连接
来源：http://dali.ehwqpu.com/Article/details/gteoajwdtm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hongshengwenyu.top/Article/details/gtwcwlnszj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shanyushiyangkeji.top/Article/details/gttgtwdlty.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xuetiantiany.cn/Article/details/gtkkvqrfoj.html

[Q39] 自连接（查上下级）
来源：http://dali.smart0.xyz/Article/details/gtymrrdcbc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.sweek.top/Article/details/gtoxjprecl.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhongyouzk.top/Article/details/gtakmtwnhp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.meibo888.top/Article/details/gtetbkyixm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jyoumei.cn/Article/details/gtjhipfall.html

[Q41] 多表连接
来源：http://dali.hnqzz.top/Article/details/gtqwlwmfqt.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.tanke756.top/Article/details/gtebroxkqv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hammf.cn/Article/details/gthvgqdiqi.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxadvfqja.html

[Q42] 连接条件附加过滤
来源：http://dali.316326.xyz/Article/details/gtliwtecoq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hnqzz.top/Article/details/gtbyudwnmp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.tian-w.cn/Article/details/gtbijcpkfr.html

[Q43] 标量子查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwfjthpgn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hfpthk.cn/Article/details/gtocqfiycn.html

[Q44] IN 子查询
来源：http://dali.sysykeji.top/Article/details/gtyykqxwaj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hnxiangtu.top/Article/details/gtziskfxkm.html

[Q45] EXISTS 判断存在
来源：http://dali.chenzaomai.com/Article/details/gtqobxrhxf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.feifeiyinyue.top/Article/details/gtdgnlyzbx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtvishyxit.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gotoacloud.top/Article/details/gtneliygbx.html

[Q47] 与平均值比较
来源：http://dali.vqdsnc.cn/Article/details/gtawdnhvpo.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ppjwa.cn/Article/details/gtitfwlcox.html

[Q48] CTE 公用表表达式
来源：http://dali.chenzaomai.com/Article/details/gtrpxerivq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.fzhhl.top/Article/details/gtqxkvyqvh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.feifeiyinyue.top/Article/details/gtllioasdb.html

[Q49] 更新单行
来源：http://dali.fzhhl.top/Article/details/gtvrgdhvia.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.fzhhl.top/Article/details/gtwtyiqjjw.html

[Q50] 批量更新
来源：http://dali.hammf.cn/Article/details/gtijckdzkr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.guannengcc.top/Article/details/gtubdhreya.html

[Q51] 用子查询更新
来源：http://dali.haohaochexian.top/Article/details/gtkdnxqtsa.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gogol.net.cn/Article/details/gtyeiuoelm.html

[Q52] 删除指定行
来源：http://dali.tian-w.cn/Article/details/gtdybwtknx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.sysykeji.top/Article/details/gtspxqoazl.html

[Q53] 按条件删除
来源：http://dali.yongpay.top/Article/details/gtlozljqbc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.cashguo.top/Article/details/gtwgqrhybx.html

[Q54] 清空表
来源：http://dali.yonumen.top/Article/details/gtwrhhqzac.html

TRUNCATE TABLE logs;
来源：http://dali.quarkkingdee.top/Article/details/gtwhvtgthx.html

[Q55] 排名（并列占位）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcxdbtxfj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.feifeiyinyue.top/Article/details/gtssdycvsw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.mhx1999.top/Article/details/gtguynjrbz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jqgfzy.top/Article/details/gtpfalqxel.html

[Q57] 行号
来源：http://dali.sweek.top/Article/details/gtxztdzsdv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.havefunace.top/Article/details/gtnahwmoeq.html

[Q58] 累计求和
来源：http://dali.nanxinkj.top/Article/details/gtlhjubnbp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtuzpyiamr.html

[Q59] 分组内累计
来源：http://dali.cheryme.top/Article/details/gtpzxxxgrj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gtfhciteij.html

[Q60] 取上一行 / 下一行
来源：http://dali.yueranfly.top/Article/details/gtcoiajjqp.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yj20258888.top/Article/details/gttgqicwvy.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsdzavcqv.html

[Q61] 移动平均
来源：http://dali.nanxuanxn.top/Article/details/gtsqikljfa.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gthwiauqgq.html

[Q62] 分组占比
来源：http://dali.nwbrower.top/Article/details/gtscxwgnnu.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.haohaochexian.top/Article/details/gtgttshope.html

[Q63] 开启事务
来源：http://dali.redwolf501.top/Article/details/gtmbbuiaxi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.tianlin.xyz/Article/details/gtjikzqnsh.html

[Q64] 提交事务
来源：http://dali.guowangkeji.top/Article/details/gtyzczqvky.html

COMMIT;
来源：http://dali.fengsongda.top/Article/details/gtccpvcmea.html

[Q65] 回滚事务
来源：http://dali.yj202588.top/Article/details/gtmywbmzap.html

ROLLBACK;
来源：http://dali.tian-w.cn/Article/details/gtludykhfe.html

[Q66] 行锁查询
来源：http://dali.hongshengwenyu.top/Article/details/gtvakiviss.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.vqdsnc.cn/Article/details/gtppxxrbrj.html

[Q67] 设置隔离级别
来源：http://dali.xuetiantiany.cn/Article/details/gtvgfidjhv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.tianlin.xyz/Article/details/gtzmiaorpq.html

[Q68] 保存点
来源：http://dali.zhengqikj.top/Article/details/gtezcbhuda.html

SAVEPOINT sp1;
来源：http://dali.vqdsnc.cn/Article/details/gtxbfprnaq.html

ROLLBACK TO sp1;
来源：http://dali.fzhhl.top/Article/details/gthewuhkxg.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gtilkzcyzj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.dianchejie.cn/Article/details/gtqiweskho.html

[Q70] 更新统计信息
来源：http://dali.gotoacloud.top/Article/details/gtcdufgrmv.html

ANALYZE TABLE users;
来源：http://dali.smart0.xyz/Article/details/gtlypfotxn.html

[Q71] 查看建表语句
来源：http://dali.guannengcc.top/Article/details/gtgyjcgimf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yonumen.top/Article/details/gtswznyqsk.html

[Q72] 查看索引
来源：http://dali.tianlin.xyz/Article/details/gtrvgkwqna.html

SHOW INDEX FROM users;
来源：http://dali.redwolf501.top/Article/details/gtjkzlhtrg.html

[Q73] 查看表状态
来源：http://dali.shanyushiyangtech.top/Article/details/gtmwkwreep.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ivvv.top/Article/details/gtlbnxfdzd.html

[Q74] 强制使用索引
来源：http://dali.hnqzz.top/Article/details/gtdwcdqhti.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.chenjidiqi.icu/Article/details/gtrrruboch.html

[Q75] 日期格式化
来源：http://dali.hnqzz.top/Article/details/gtekdrfvuu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtlggysusz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.316326.xyz/Article/details/gtdvqajpno.html

[Q76] 按天统计
来源：http://dali.shanyushiyangtech.top/Article/details/gtdkwlekex.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shangyingyoupin.top/Article/details/gtziixhdgf.html

[Q77] 时间加减
来源：http://dali.yvedp.cn/Article/details/gtkgcfghna.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xuetiantiany.cn/Article/details/gtcfuwwrap.html

[Q78] 当前时间
来源：http://dali.vqdsnc.cn/Article/details/gtqbmgxhmb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.quarkkingdee.top/Article/details/gtkqxekeki.html

[Q79] 字符串拼接
来源：http://dali.nanxuanxn.top/Article/details/gtnhuzjmdx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yanxiufei.cn/Article/details/gtjmwpjime.html

[Q80] 字符串截取
来源：http://dali.gotoacloud.top/Article/details/gtxnjagyex.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtehwsmpgh.html

[Q81] 字符串替换
来源：http://dali.c1oappe.top/Article/details/gtwauxfvyb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xziqi.cn/Article/details/gtwmqbnipq.html

[Q82] 字符长度与字节长度
来源：http://dali.havefunace.top/Article/details/gtcebfgwtz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xylfe.cn/Article/details/gtftcpjsdg.html

[Q83] 大小写转换
来源：http://dali.andypj.xyz/Article/details/gtnpydiwis.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtagcdfobx.html

[Q84] 去除首尾空格
来源：http://dali.feifeiyinyue.top/Article/details/gtratrenol.html

SELECT TRIM(name) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gthrgthkkp.html

[Q85] 数值取整
来源：http://dali.tian-w.cn/Article/details/gtotgzycnm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cqqwz.cn/Article/details/gtgblmtkao.html

[Q86] 读取 JSON 字段
来源：http://dali.0kj1m.cn/Article/details/gtzxifkagz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.wangdashe.top/Article/details/gtjiagtgsh.html

[Q87] JSON 字段做条件
来源：http://dali.vqdsnc.cn/Article/details/gtzkctggoh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.daxiang520.top/Article/details/gtmrjivuse.html

[Q88] 行转列（条件聚合）
来源：http://dali.wangshuangyany.cn/Article/details/gterqorwfz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yj20258.top/Article/details/gtintbfshd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yj202588.top/Article/details/gtvktcarwf.html

[Q89] 判断表是否存在
来源：http://dali.sufxvd.cn/Article/details/gtluvqhpyu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cucudq.cn/Article/details/gtzpflcpby.html

[Q90] 生成序号列
来源：http://dali.fzhhl.top/Article/details/gtozhplvuk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sysykeji.top/Article/details/gttajnakcj.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtxzpvacwb.html

R. Bash 专题
来源：http://dali.svipenyu.cn/Article/details/gtbisaxkrg.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtjruufulz.html

[R01] shebang 与严格模式
来源：http://dali.hysaishi.cn/Article/details/gtxidmnuqn.html

#!/usr/bin/env bash
来源：http://dali.c1oappe.top/Article/details/gtomldabpg.html

set -euo pipefail
来源：http://dali.meibo888.top/Article/details/gtonydjscg.html

[R02] 变量赋值与使用
来源：http://dali.tian-w.cn/Article/details/gtgzmyiqcn.html

name="Tom"; echo "$name"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxfzvwjjz.html

[R03] 只读变量
来源：http://dali.cucudq.cn/Article/details/gtjqnxosrc.html

readonly PI=3.14
来源：http://dali.nwbrower.top/Article/details/gtrgkkfddf.html

[R04] 位置参数
来源：http://dali.gzhubu.top/Article/details/gtvatuftjs.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yj202588.top/Article/details/gtzowecwds.html

[R05] 参数默认值
来源：http://dali.jiagoushi.top/Article/details/gtaxbsandc.html

name="${1:-default}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtonsboqmj.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gtfgggowzq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yvedp.cn/Article/details/gtivonqtiv.html

[R07] if 判断文件
来源：http://dali.cheryme.top/Article/details/gtsrhupgln.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gzhubu.top/Article/details/gtmltnobkg.html

[R08] 数值比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrcoixgvp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hywenlv.cn/Article/details/gtrawbfttj.html

[R09] 字符串比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gterhmtwar.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ppjwa.cn/Article/details/gtlicgexiz.html

[R10] 正则匹配
来源：http://dali.tian-w.cn/Article/details/gtsmlrmryh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sysykeji.top/Article/details/gtonnnglmd.html

[R11] case 多分支
来源：http://dali.fzhhl.top/Article/details/gtehwsczjn.html

case "$1" in
来源：http://dali.cucudq.cn/Article/details/gteizwbnvs.html

start) echo "启动" ;;
来源：http://dali.sxryk.cn/Article/details/gtgnpebdxn.html

stop)  echo "停止" ;;
来源：http://dali.ivvv.top/Article/details/gttepnnlbo.html

*)     echo "未知命令" ;;
来源：http://dali.andypj.xyz/Article/details/gtllfoqmqo.html

esac
来源：http://dali.hnxiangtu.top/Article/details/gtyefsvanf.html

[R12] for 遍历文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpvhydrzr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yj20258.top/Article/details/gtossytqiu.html

[R13] for 计数循环
来源：http://dali.gaohongyu789.top/Article/details/gtqjrymudy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zdqjudy.top/Article/details/gtuotbsbwl.html

[R14] C 风格 for
来源：http://dali.yj20258.top/Article/details/gtidyhoorz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtntlefecx.html

[R15] while 逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gtzsizcprk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtsmhsbjcy.html

[R16] until 等待条件
来源：http://dali.aibaodan.cn/Article/details/gtrrzwzkds.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.tanke756.top/Article/details/gtwzptfxhr.html

[R17] 数组定义与取值
来源：http://dali.daria6918.cn/Article/details/gtgyeczpar.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ehwqpu.com/Article/details/gtwzfsudjj.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gteczanlrx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jqgufenzy.top/Article/details/gtnrxzpvnm.html

[R19] 数组长度
来源：http://dali.gaohongyu789.top/Article/details/gtlrvgjzys.html

echo "${#arr[@]}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpiocweor.html

[R20] 关联数组（字典）
来源：http://dali.chenzaomai.com/Article/details/gtkknlhwzt.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ivvv.top/Article/details/gtbifhvxgd.html

[R21] 字符串长度
来源：http://dali.hywenlv.cn/Article/details/gtzaktpdjq.html

echo "${#s}"
来源：http://dali.gzhubu.top/Article/details/gtqavpmnza.html

[R22] 截取子串
来源：http://dali.quarkkingdee.top/Article/details/gtmflhgakw.html

echo "${s:0:5}"
来源：http://dali.jyoumei.cn/Article/details/gtqbcnkpnf.html

[R23] 字符串替换
来源：http://dali.zhixingplan.top/Article/details/gtswjfzovk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yvedp.cn/Article/details/gtpalwbbvs.html

[R24] 大小写转换
来源：http://dali.kuanghao11.cn/Article/details/gtfmimdfid.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zycfv.cn/Article/details/gtlbekjzfz.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhoulong.xyz/Article/details/gtwdubhyjh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hnxiangtu.top/Article/details/gtqvmvqdkz.html

[R26] 命令替换
来源：http://dali.jlsjyb.cn/Article/details/gtdzvmkuzb.html

now=$(date +%F); echo "$now"
来源：http://dali.hfpthk.cn/Article/details/gtuhbogxtd.html

[R27] 算术展开
来源：http://dali.hnxiangtu.top/Article/details/gtmkzxyuxr.html

echo $((1 + 2 * 3))
来源：http://dali.yongpay.top/Article/details/gtbnyadwts.html

[R28] 浮点运算
来源：http://dali.ywan-chungtsiang.top/Article/details/gthjbrpwll.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbsqndweu.html

[R29] 定义函数
来源：http://dali.sxryk.cn/Article/details/gtvrcczupf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hammf.cn/Article/details/gtuuhyrbvf.html

[R30] 函数返回状态码
来源：http://dali.zycfv.cn/Article/details/gtkzpsyscp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shangyingyoupin.top/Article/details/gtdnbsxbwe.html

[R31] 局部变量
来源：http://dali.xuetiantiany.cn/Article/details/gtfottausz.html

f() { local x=1; echo "$x"; }
来源：http://dali.dianchejie.cn/Article/details/gtbckhagfk.html

[R32] 参数个数校验
来源：http://dali.ehwqpu.com/Article/details/gtdemjnpny.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shanyushiyangtech.top/Article/details/gthcbimjwa.html

[R33] 捕获错误并提示行号
来源：http://dali.yj202588.top/Article/details/gtvarmkysu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.316326.xyz/Article/details/gtzkccmszw.html

[R34] 退出时清理
来源：http://dali.hongshengwenyu.top/Article/details/gtgslpaexs.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgufenzy.top/Article/details/gtrafstyvv.html

[R35] 后台执行并等待
来源：http://dali.vqdsnc.cn/Article/details/gtjdqeyhda.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cheryme.top/Article/details/gtfjnoacoo.html

[R36] 并发执行多个任务
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjwywepfd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.tanke756.top/Article/details/gtdhepvafp.html

[R37] 把输出赋给变量
来源：http://dali.bjfxy.top/Article/details/gtzgrdmdue.html

files=$(ls -1)
来源：http://dali.hfpthk.cn/Article/details/gtnxfcuqpc.html

[R38] 管道串联
来源：http://dali.hfpthk.cn/Article/details/gtzewwvnsb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.daria6918.cn/Article/details/gtmnltbltn.html

[R39] 重定向标准输出与错误
来源：http://dali.quarkkingdee.top/Article/details/gttfdopiol.html

cmd > out.log 2>&1
来源：http://dali.yj20258.top/Article/details/gtusswemfi.html

[R40] 追加写日志
来源：http://dali.sxryk.cn/Article/details/gtouzqcfsz.html

echo "log" >> out.log
来源：http://dali.zhengqikj.top/Article/details/gtrfeozicc.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gtzdaunjrl.html

cmd >/dev/null 2>&1
来源：http://dali.ybcxt.top/Article/details/gtrjwjprxt.html

[R42] 输入重定向
来源：http://dali.jiagoushi.top/Article/details/gtkbeidyzp.html

wc -l < a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtfmbepnyq.html

[R43] 按名字查找文件
来源：http://dali.zycfv.cn/Article/details/gtzknhfjye.html

find . -name "*.log" -type f
来源：http://dali.sysykeji.top/Article/details/gtjolasmga.html

[R44] 按修改时间查找
来源：http://dali.yj20258.top/Article/details/gthrfdjqrk.html

find . -mtime -7 -type f
来源：http://dali.sxryk.cn/Article/details/gtbtnvitpb.html

[R45] 批量删除
来源：http://dali.jinqigufen.top/Article/details/gtsnbxamev.html

find . -name "*.tmp" -delete
来源：http://dali.meibo888.top/Article/details/gthbuwbiwd.html

[R46] 递归替换文件内容
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrxjcsgei.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.gogol.net.cn/Article/details/gtlyalshdl.html

[R47] sed 单行替换
来源：http://dali.sweek.top/Article/details/gtquxbomjv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.nanxuanxn.top/Article/details/gtfarhanqt.html

[R48] awk 取指定列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfhpngjcb.html

awk '{print $1, $3}' a.txt
来源：http://dali.gogol.net.cn/Article/details/gtrionseqo.html

[R49] awk 带条件
来源：http://dali.cucudq.cn/Article/details/gtyjzpchaz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hfpthk.cn/Article/details/gtyzbfactm.html

[R50] awk 求和
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnluolmaj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtoaywbhvc.html

[R51] 排序去重取前几
来源：http://dali.cdnleiting.top/Article/details/gtzgusxylh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.daria6918.cn/Article/details/gtkeakwask.html

[R52] 统计行数
来源：http://dali.kuanghao11.cn/Article/details/gtnhewmstg.html

wc -l a.txt
来源：http://dali.gzhubu.top/Article/details/gtttacoqiy.html

[R53] 查看文件头与实时尾
来源：http://dali.zycfv.cn/Article/details/gtrgyjsqkx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ppjwa.cn/Article/details/gtpfhtfgca.html

[R54] 比较两个文件
来源：http://dali.chenzaomai.com/Article/details/gtvbbzrooh.html

diff a.txt b.txt
来源：http://dali.shuidangran.top/Article/details/gtvduqebcl.html

[R55] 压缩与解压
来源：http://dali.hywenlv.cn/Article/details/gtpdmqliux.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhongyouzk.top/Article/details/gtcnpsttfa.html

[R56] 远程拷贝
来源：http://dali.jinghuilouyu.cn/Article/details/gtluzgeoer.html

scp file user@host:/path/
来源：http://dali.yj202588.top/Article/details/gtvwnntjua.html

[R57] 远程执行命令
来源：http://dali.snrcjt.cn/Article/details/gtokiqzfji.html

ssh user@host 'uptime'
来源：http://dali.cqqwz.cn/Article/details/gtgkhknrbn.html

[R58] 下载文件
来源：http://dali.xylfe.cn/Article/details/gtqufekvxy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yvedp.cn/Article/details/gtretdldwy.html

[R59] 发 POST JSON
来源：http://dali.yvedp.cn/Article/details/gtchmtlpgc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xylfe.cn/Article/details/gtvldtdssk.html

[R60] 只看 HTTP 状态码
来源：http://dali.xinyue.icu/Article/details/gthknsuztj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hongshengwenyu.top/Article/details/gtefpixsnl.html

[R61] 磁盘占用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtunlradmh.html


<!-- 参考信息 -->