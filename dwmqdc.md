代发 wailian999

);
来源：http://dali.yonumen.top/Article/details/gt2ezxkabdl.html

[Q03] 增加列
来源：http://dali.shuidangran.top/Article/details/gt2alprhrpt.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jqgfzy.top/Article/details/gt2wbypaelf.html

[Q04] 修改列类型
来源：http://dali.sxryk.cn/Article/details/gt2rdsmohqk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yongpay.top/Article/details/gt2eguprhfk.html

[Q05] 重命名列
来源：http://dali.feifeiyinyue.top/Article/details/gt2rdxckzdf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.tanke756.top/Article/details/gt2kthgmqku.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2ivdvnzes.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhixingplan.top/Article/details/gt2lnvilsvt.html

[Q07] 删除表
来源：http://dali.nanxinkj.top/Article/details/gt2emajiark.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhongyouzk.top/Article/details/gt2zucrhalc.html

[Q08] 创建普通索引
来源：http://dali.jyoumei.cn/Article/details/gt2bjtfxijw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2rudbuqla.html

[Q09] 创建唯一索引
来源：http://dali.jinqigufen.top/Article/details/gt2vbvoqxqx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yj20258888.top/Article/details/gt2bbnykdrn.html

[Q10] 插入单行
来源：http://dali.wangdashe.top/Article/details/gt2irskivqe.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fildtjct.html

[Q11] 一次插入多行
来源：http://dali.hammf.cn/Article/details/gt2eqrxlrqx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jqgufenzy.top/Article/details/gt2acrnlhfx.html

[Q12] 插入后取自增 ID
来源：http://dali.nanxinkj.top/Article/details/gt2urgqgrvm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sxryk.cn/Article/details/gt2qnwkkqww.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.fzhhl.top/Article/details/gt2eegwuvrk.html

[Q13] 忽略重复插入
来源：http://dali.xylfe.cn/Article/details/gt2vmqnzngl.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.sweek.top/Article/details/gt2tflicpoo.html

[Q14] 存在则更新（upsert）
来源：http://dali.yongpay.top/Article/details/gt2gfqusthf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ehwqpu.com/Article/details/gt2lecfztrr.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cashguo.top/Article/details/gt2hzbeychp.html

[Q15] 查询全部
来源：http://dali.kuanghao11.cn/Article/details/gt2mlzntuox.html

SELECT * FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2fjvghjcy.html

[Q16] 查询指定列
来源：http://dali.hysaishi.cn/Article/details/gt2afqqbzrs.html

SELECT id, name FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2fjuzjaci.html

[Q17] 条件查询
来源：http://dali.feifeiyinyue.top/Article/details/gt2yqssegdg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhixingplan.top/Article/details/gt2hfewwopd.html

[Q18] 模糊匹配
来源：http://dali.shzxlz.cn/Article/details/gt2ufecxred.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.iojbl.cn/Article/details/gt2vqhqmygl.html

[Q19] 范围查询
来源：http://dali.gaohongyu789.top/Article/details/gt2fithpnet.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinqigfzy.top/Article/details/gt2xcpihhen.html

[Q20] IN 列表
来源：http://dali.hnqzz.top/Article/details/gt2abocjusg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hnxiangtu.top/Article/details/gt2ajestqir.html

[Q21] 空值判断
来源：http://dali.zhixingplan.top/Article/details/gt2rpmrsfsq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhoulong.xyz/Article/details/gt2ssfkinfs.html

[Q22] 排序
来源：http://dali.cdnleiting.top/Article/details/gt2xmkefrrh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hongshengwenyu.top/Article/details/gt2xxznagyn.html

[Q23] 分页
来源：http://dali.haohaochexian.top/Article/details/gt2dgmupugs.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhengqikj.top/Article/details/gt2muqwmgcl.html

[Q24] 去重
来源：http://dali.hnqzz.top/Article/details/gt2ileqwxtn.html

SELECT DISTINCT city FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2cawgrnad.html

[Q25] 只取前 N 条
来源：http://dali.hysaishi.cn/Article/details/gt2kqvldequ.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hammf.cn/Article/details/gt2vhyoglfi.html

[Q26] 计数
来源：http://dali.sysykeji.top/Article/details/gt2wicrhmpx.html

SELECT COUNT(*) FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2oeujlldh.html

[Q27] 条件计数
来源：http://dali.pycfn.com/Article/details/gt2pqqbfsst.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2mqalcdel.html

[Q28] 求和与平均
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ppagdbzk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ftycheth.html

[Q29] 最大最小值
来源：http://dali.hfpthk.cn/Article/details/gt2cynjjuss.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2sdlrcfqi.html

[Q30] 分组统计
来源：http://dali.0kj1m.cn/Article/details/gt2vcdgogmx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xuanzx.com/Article/details/gt2lnjdbptg.html

[Q31] 分组后过滤
来源：http://dali.andypj.xyz/Article/details/gt2yfkxxhib.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.bjfxy.top/Article/details/gt2bybnoafr.html

[Q32] 分组拼接字符串
来源：http://dali.ehwqpu.com/Article/details/gt2bkjvigai.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.nwbrower.top/Article/details/gt2jsjotbtj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhiwuduotai.top/Article/details/gt2yjawxtpn.html

[Q33] 多列分组
来源：http://dali.yuanzhike.top/Article/details/gt2hhytaocx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2imzqaznl.html

[Q34] 每组取第一条
来源：http://dali.yj202588.top/Article/details/gt2ajigmies.html

SELECT * FROM (
来源：http://dali.tian-w.cn/Article/details/gt2xxrvqfwa.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gzhubu.top/Article/details/gt2mycusgij.html

) t WHERE rn = 1;
来源：http://dali.chenlongwang.top/Article/details/gt2muopojzf.html

[Q35] 内连接
来源：http://dali.feifeiyinyue.top/Article/details/gt2svpfudhp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zdqjudy.top/Article/details/gt2ytulnpdd.html

[Q36] 左连接
来源：http://dali.xuanzx.com/Article/details/gt2bmkwhigm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.tanke756.top/Article/details/gt2fxnfjoob.html

[Q37] 右连接
来源：http://dali.xylfe.cn/Article/details/gt2fzfbqqcv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yj202588.top/Article/details/gt2uhwcpihv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hysaishi.cn/Article/details/gt2xgtwypky.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cdnleiting.top/Article/details/gt2wjqraszs.html

[Q39] 自连接（查上下级）
来源：http://dali.sweek.top/Article/details/gt2xoinwbwa.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.haohaochexian.top/Article/details/gt2mxwlrgvq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yueranfly.top/Article/details/gt2kbhtpynk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hammf.cn/Article/details/gt2pxmbwkej.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xuanzx.com/Article/details/gt2vevpnsct.html

[Q41] 多表连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zprqkaho.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xylfe.cn/Article/details/gt2fswgragk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jlsjyb.cn/Article/details/gt2aavsynwf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ejbmwfyo.html

[Q42] 连接条件附加过滤
来源：http://dali.yj20258888.top/Article/details/gt2rosqnpvm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cheryme.top/Article/details/gt2educujpt.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ljczeaha.html

[Q43] 标量子查询
来源：http://dali.nwbrower.top/Article/details/gt2hberqadz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.kuanghao11.cn/Article/details/gt2ujhrbnar.html

[Q44] IN 子查询
来源：http://dali.hnqzz.top/Article/details/gt2dtqnlbyj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pvyguhgr.html

[Q45] EXISTS 判断存在
来源：http://dali.xuetiantiany.cn/Article/details/gt2vtmucmkm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yueranfly.top/Article/details/gt2qcornbzf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shangyingyoupin.top/Article/details/gt2wppausoe.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sysykeji.top/Article/details/gt2vrumewap.html

[Q47] 与平均值比较
来源：http://dali.iojbl.cn/Article/details/gt2ugmuqqfx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ckfamhfy.html

[Q48] CTE 公用表表达式
来源：http://dali.c1oappe.top/Article/details/gt2qdvhuoag.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.tianlin.xyz/Article/details/gt2sefzmgkz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gogol.net.cn/Article/details/gt2rnxhmxdq.html

[Q49] 更新单行
来源：http://dali.nwbrower.top/Article/details/gt2oloojetw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yuanzhike.top/Article/details/gt2byhogrgk.html

[Q50] 批量更新
来源：http://dali.hongshengwenyu.top/Article/details/gt2hwealfvb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.fengsongda.top/Article/details/gt2bqtyismm.html

[Q51] 用子查询更新
来源：http://dali.yvedp.cn/Article/details/gt2jfqzrtup.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zycfv.cn/Article/details/gt2wguahitm.html

[Q52] 删除指定行
来源：http://dali.tanke756.top/Article/details/gt2etqtkwpz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ehwqpu.com/Article/details/gt2kigzlpdb.html

[Q53] 按条件删除
来源：http://dali.ydzc1.top/Article/details/gt2aqjmmrcs.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jqgufenzy.top/Article/details/gt2phcwhfzi.html

[Q54] 清空表
来源：http://dali.svipenyu.cn/Article/details/gt2mjhnerkl.html

TRUNCATE TABLE logs;
来源：http://dali.yangfankeji.com/Article/details/gt2cdaemrfn.html

[Q55] 排名（并列占位）
来源：http://dali.cucudq.cn/Article/details/gt2tefiyqfy.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.andypj.xyz/Article/details/gt2cjdwcfem.html

[Q56] 密集排名（并列不占位）
来源：http://dali.guowangkeji.top/Article/details/gt2ogijdevp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.daria6918.cn/Article/details/gt2sjkamcvb.html

[Q57] 行号
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ckllmzcf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2usilsijm.html

[Q58] 累计求和
来源：http://dali.cqqwz.cn/Article/details/gt2xdrdcvcy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jianghu66.top/Article/details/gt2yxopmoto.html

[Q59] 分组内累计
来源：http://dali.yueranfly.top/Article/details/gt2zcekcnzf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gt2dyajlcst.html

[Q60] 取上一行 / 下一行
来源：http://dali.haohaochexian.top/Article/details/gt2txvuwkqx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jinqigfzy.top/Article/details/gt2cmavsbif.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jianghu66.top/Article/details/gt2ilclwaez.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmjdlod.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oeqghrmx.html

[Q62] 分组占比
来源：http://dali.fengsongda.top/Article/details/gt2xsipvbiz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.mhx1999.top/Article/details/gt2oyhctwnk.html

[Q63] 开启事务
来源：http://dali.kuanghao11.cn/Article/details/gt2gftyapte.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xziqi.cn/Article/details/gt2mmcvhuqt.html

[Q64] 提交事务
来源：http://dali.svipenyu.cn/Article/details/gt2ebsrqkrk.html

COMMIT;
来源：http://dali.pengpengdd.cyou/Article/details/gt2qwozcamt.html

[Q65] 回滚事务
来源：http://dali.yuanzhike.top/Article/details/gt2posrghrb.html

ROLLBACK;
来源：http://dali.jianghu66.top/Article/details/gt2vmumrrrf.html

[Q66] 行锁查询
来源：http://dali.aizwys.cn/Article/details/gt2agnzluei.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yonumen.top/Article/details/gt2idanyfnl.html

[Q67] 设置隔离级别
来源：http://dali.jyoumei.cn/Article/details/gt2rlonlqny.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yuanzhike.top/Article/details/gt2drdvuheb.html

[Q68] 保存点
来源：http://dali.cqqwz.cn/Article/details/gt2hugledsm.html

SAVEPOINT sp1;
来源：http://dali.nwbrower.top/Article/details/gt2bykiccbe.html

ROLLBACK TO sp1;
来源：http://dali.dashuyun.cn/Article/details/gt2vdkbcsya.html

[Q69] 查看执行计划
来源：http://dali.wangdashe.top/Article/details/gt2ropcorfw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.aibaodan.cn/Article/details/gt2quemneag.html

[Q70] 更新统计信息
来源：http://dali.shangyingyoupin.top/Article/details/gt2utewysmc.html

ANALYZE TABLE users;
来源：http://dali.yongpay.top/Article/details/gt2qvjbakjs.html

[Q71] 查看建表语句
来源：http://dali.xziqi.cn/Article/details/gt2ovlnajkw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shuidangran.top/Article/details/gt2vagevmnx.html

[Q72] 查看索引
来源：http://dali.jinqigfzy.top/Article/details/gt2soxccvyb.html

SHOW INDEX FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gt2kwmngikn.html

[Q73] 查看表状态
来源：http://dali.kuanghao11.cn/Article/details/gt2fszeukfo.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.316326.xyz/Article/details/gt2pvnioshg.html

[Q74] 强制使用索引
来源：http://dali.havefunace.top/Article/details/gt2dblsuylp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jiagoushi.top/Article/details/gt2hjpfaprn.html

[Q75] 日期格式化
来源：http://dali.nwbrower.top/Article/details/gt2adeosgab.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yj20258888.top/Article/details/gt2qckdjblf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.0kj1m.cn/Article/details/gt2hsyeqokg.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ksnpsbjb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.kuanghao11.cn/Article/details/gt2lhcpnbqp.html

[Q77] 时间加减
来源：http://dali.yongpay.top/Article/details/gt2nwkmecez.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gogol.net.cn/Article/details/gt2vscjrjkn.html

[Q78] 当前时间
来源：http://dali.cqqwz.cn/Article/details/gt2rnzmdrws.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.haohaochexian.top/Article/details/gt2yorybffv.html

[Q79] 字符串拼接
来源：http://dali.kuanghao11.cn/Article/details/gt2zqdotcyi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinqigufen.top/Article/details/gt2spvjyjun.html

[Q80] 字符串截取
来源：http://dali.tanke756.top/Article/details/gt2tclncvuo.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2qobfokgt.html

[Q81] 字符串替换
来源：http://dali.iojbl.cn/Article/details/gt2ifokxqhe.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2aevitgjp.html

[Q82] 字符长度与字节长度
来源：http://dali.vqdsnc.cn/Article/details/gt2seibezan.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2bmxacrrc.html

[Q83] 大小写转换
来源：http://dali.shuidangran.top/Article/details/gt2dxiadbrq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2kqmjuqbx.html

[Q84] 去除首尾空格
来源：http://dali.yj20258888.top/Article/details/gt2puezktss.html

SELECT TRIM(name) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yzkafdpf.html

[Q85] 数值取整
来源：http://dali.dianchejie.cn/Article/details/gt2nciyuszu.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yj202588.top/Article/details/gt2vbvgobdh.html

[Q86] 读取 JSON 字段
来源：http://dali.guowangkeji.top/Article/details/gt2meccfijd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.chenjidiqi.icu/Article/details/gt2kqxzjnab.html

[Q87] JSON 字段做条件
来源：http://dali.fzhhl.top/Article/details/gt2pkxaidqg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xuanzx.com/Article/details/gt2oysaqiye.html

[Q88] 行转列（条件聚合）
来源：http://dali.kuanghao11.cn/Article/details/gt2bxtsbzkq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.chenlongwang.top/Article/details/gt2jogyxlbp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.meibo888.top/Article/details/gt2oheqmgzt.html

[Q89] 判断表是否存在
来源：http://dali.birdmap.top/Article/details/gt2eascpnof.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hysaishi.cn/Article/details/gt2cxnujedo.html

[Q90] 生成序号列
来源：http://dali.nanxuanxn.top/Article/details/gt2cuptxlvb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xuetiantiany.cn/Article/details/gt2vwvqmgqn.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zvsnxrhy.html

R. Bash 专题
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yjjggucy.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2nkfbdxqg.html

[R01] shebang 与严格模式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2svqogfae.html

#!/usr/bin/env bash
来源：http://dali.zhengqikj.top/Article/details/gt2niirkqvs.html

set -euo pipefail
来源：http://dali.yuanzhike.top/Article/details/gt2rtelsaid.html

[R02] 变量赋值与使用
来源：http://dali.tianlin.xyz/Article/details/gt2caxyncmk.html

name="Tom"; echo "$name"
来源：http://dali.guowangkeji.top/Article/details/gt2ruxthehk.html

[R03] 只读变量
来源：http://dali.yj20258888.top/Article/details/gt2kpsixhdf.html

readonly PI=3.14
来源：http://dali.yangfankeji.com/Article/details/gt2onunyozh.html

[R04] 位置参数
来源：http://dali.yvedp.cn/Article/details/gt2cotrxdfc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.dianchejie.cn/Article/details/gt2tvnrgrkc.html

[R05] 参数默认值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pbvmyzzs.html

name="${1:-default}"
来源：http://dali.sxryk.cn/Article/details/gt2lcfgzrlz.html

[R06] 判断命令是否存在
来源：http://dali.shzxlz.cn/Article/details/gt2mxrkegcm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.aizwys.cn/Article/details/gt2pmkfmbab.html

[R07] if 判断文件
来源：http://dali.dianchejie.cn/Article/details/gt2hyivbymp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.wangdashe.top/Article/details/gt2skbuwcrv.html

[R08] 数值比较
来源：http://dali.tianlin.xyz/Article/details/gt2hqogvntw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhoulong.xyz/Article/details/gt2aehkdksl.html

[R09] 字符串比较
来源：http://dali.dianchejie.cn/Article/details/gt2gulfvwfg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jianghu66.top/Article/details/gt2ksahcvva.html

[R10] 正则匹配
来源：http://dali.zhiwuduotai.top/Article/details/gt2ffxrkvko.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yanxiufei.cn/Article/details/gt2vjfkegve.html

[R11] case 多分支
来源：http://dali.wangdashe.top/Article/details/gt2zkmxubqk.html

case "$1" in
来源：http://dali.zhiwuduotai.top/Article/details/gt2amohzmyv.html

start) echo "启动" ;;
来源：http://dali.andypj.xyz/Article/details/gt2ojxxnzlt.html

stop)  echo "停止" ;;
来源：http://dali.xylfe.cn/Article/details/gt2ncljgkmw.html

*)     echo "未知命令" ;;
来源：http://dali.cucudq.cn/Article/details/gt2ndmewfxp.html

esac
来源：http://dali.ehwqpu.com/Article/details/gt2xfnmadqw.html

[R12] for 遍历文件
来源：http://dali.shzxlz.cn/Article/details/gt2qqlhmqqq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xylfe.cn/Article/details/gt2xzufarvx.html

[R13] for 计数循环
来源：http://dali.jyoumei.cn/Article/details/gt2lxzxzbvd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.bjfxy.top/Article/details/gt2uzuxoppo.html

[R14] C 风格 for
来源：http://dali.wangdashe.top/Article/details/gt2kuheaece.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kmfkzavo.html

[R15] while 逐行读文件
来源：http://dali.cashguo.top/Article/details/gt2zximjfai.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gogol.net.cn/Article/details/gt2zehyfzji.html

[R16] until 等待条件
来源：http://dali.iojbl.cn/Article/details/gt2bnpyspub.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shuidangran.top/Article/details/gt2inrrgyzw.html

[R17] 数组定义与取值
来源：http://dali.zhengqikj.top/Article/details/gt2fovhoexn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rngaaibc.html

[R18] 遍历数组
来源：http://dali.mhx1999.top/Article/details/gt2ccigvdde.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yanxiufei.cn/Article/details/gt2eyntguvm.html

[R19] 数组长度
来源：http://dali.cashguo.top/Article/details/gt2yvqujucq.html

echo "${#arr[@]}"
来源：http://dali.redwolf501.top/Article/details/gt2vmeiaqxj.html

[R20] 关联数组（字典）
来源：http://dali.yj202588.top/Article/details/gt2zomjcjvq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.chenzaomai.com/Article/details/gt2vzeszoxl.html

[R21] 字符串长度
来源：http://dali.jinqigfzy.top/Article/details/gt2wriptebq.html

echo "${#s}"
来源：http://dali.guannengcc.top/Article/details/gt2ajcryqfm.html

[R22] 截取子串
来源：http://dali.haohaochexian.top/Article/details/gt2yrmqzljp.html

echo "${s:0:5}"
来源：http://dali.hnqzz.top/Article/details/gt2qpxukvrf.html

[R23] 字符串替换
来源：http://dali.xuetiantiany.cn/Article/details/gt2iqjfhyph.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zycfv.cn/Article/details/gt2hlxkrkqc.html

[R24] 大小写转换
来源：http://dali.quarkkingdee.top/Article/details/gt2unjjqols.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hnxiangtu.top/Article/details/gt2pudwbnfa.html

[R25] 去后缀 / 去前缀
来源：http://dali.yonumen.top/Article/details/gt2tvmdgzyx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.dianchejie.cn/Article/details/gt2rlcvkqbi.html

[R26] 命令替换
来源：http://dali.daxiang520.top/Article/details/gt2baehtjfq.html

now=$(date +%F); echo "$now"
来源：http://dali.haohaochexian.top/Article/details/gt2feenlpit.html

[R27] 算术展开
来源：http://dali.hysaishi.cn/Article/details/gt2ylqyfnmk.html

echo $((1 + 2 * 3))
来源：http://dali.nanxinkj.top/Article/details/gt2qaycamud.html

[R28] 浮点运算
来源：http://dali.yuanzhike.top/Article/details/gt2osaemcaa.html

echo "scale=2; 10/3" | bc
来源：http://dali.cqqwz.cn/Article/details/gt2leepcikz.html

[R29] 定义函数
来源：http://dali.daxiang520.top/Article/details/gt2njycshpb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shuidangran.top/Article/details/gt2bmfznhgd.html

[R30] 函数返回状态码
来源：http://dali.tanke756.top/Article/details/gt2bnkfobox.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hammf.cn/Article/details/gt2kttxhnpa.html

[R31] 局部变量
来源：http://dali.xinyue.icu/Article/details/gt2iqpwnqxa.html

f() { local x=1; echo "$x"; }
来源：http://dali.yj20258.top/Article/details/gt2wdpyiohc.html

[R32] 参数个数校验
来源：http://dali.yuxming.cn/Article/details/gt2hqugrmsn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zdqjudy.top/Article/details/gt2wiynnhyy.html

[R33] 捕获错误并提示行号
来源：http://dali.zhoulong.xyz/Article/details/gt2wzdkcyts.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gogol.net.cn/Article/details/gt2muirnfzr.html

[R34] 退出时清理
来源：http://dali.zhongyouzk.top/Article/details/gt2ibwpnyay.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ivvv.top/Article/details/gt2sdkchigu.html

[R35] 后台执行并等待
来源：http://dali.shangyingyoupin.top/Article/details/gt2pcpcffcy.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.tian-w.cn/Article/details/gt2pcpvfgbg.html

[R36] 并发执行多个任务
来源：http://dali.smart0.xyz/Article/details/gt2oltlowte.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.fengsongda.top/Article/details/gt2sxkgglmh.html

[R37] 把输出赋给变量
来源：http://dali.pycfn.com/Article/details/gt2ypdxqklm.html

files=$(ls -1)
来源：http://dali.jianghu66.top/Article/details/gt2joclxzqx.html

[R38] 管道串联
来源：http://dali.chenlongwang.top/Article/details/gt2mylyzrsf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sysykeji.top/Article/details/gt2likrztzu.html

[R39] 重定向标准输出与错误
来源：http://dali.hammf.cn/Article/details/gt2tcxyrmql.html

cmd > out.log 2>&1
来源：http://dali.zdqjudy.top/Article/details/gt2aafmmznz.html

[R40] 追加写日志
来源：http://dali.nanxinkj.top/Article/details/gt2lbzfmnvm.html

echo "log" >> out.log
来源：http://dali.hnxiangtu.top/Article/details/gt2mawqcxkt.html

[R41] 丢弃输出
来源：http://dali.ppjwa.cn/Article/details/gt2awikradt.html

cmd >/dev/null 2>&1
来源：http://dali.nwbrower.top/Article/details/gt2bhnxrufw.html

[R42] 输入重定向
来源：http://dali.xylfe.cn/Article/details/gt2bkixvwft.html

wc -l < a.txt
来源：http://dali.cucudq.cn/Article/details/gt2uwcqvykp.html

[R43] 按名字查找文件
来源：http://dali.andypj.xyz/Article/details/gt2syciqfpk.html

find . -name "*.log" -type f
来源：http://dali.ehwqpu.com/Article/details/gt2rdepmprm.html

[R44] 按修改时间查找
来源：http://dali.bjfxy.top/Article/details/gt2phgnqgak.html

find . -mtime -7 -type f
来源：http://dali.cashguo.top/Article/details/gt2ukxblnxp.html

[R45] 批量删除
来源：http://dali.yvedp.cn/Article/details/gt2qsukyvwh.html

find . -name "*.tmp" -delete
来源：http://dali.chenjidiqi.icu/Article/details/gt2ofexvwim.html

[R46] 递归替换文件内容
来源：http://dali.birdmap.top/Article/details/gt2vgfgeuzh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shzxlz.cn/Article/details/gt2pbpmetmf.html

[R47] sed 单行替换
来源：http://dali.svipenyu.cn/Article/details/gt2qsboqzmo.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.andypj.xyz/Article/details/gt2imsobmzj.html

[R48] awk 取指定列
来源：http://dali.jianghu66.top/Article/details/gt2utdrqynq.html

awk '{print $1, $3}' a.txt
来源：http://dali.mhx1999.top/Article/details/gt2ttwsahdj.html

[R49] awk 带条件
来源：http://dali.daxiang520.top/Article/details/gt2dkykfpwx.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rrtbrlqm.html

[R50] awk 求和
来源：http://dali.svipenyu.cn/Article/details/gt2ymdrdtqt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yueranfly.top/Article/details/gt2msxrfise.html

[R51] 排序去重取前几
来源：http://dali.316326.xyz/Article/details/gt2pxdqfyfr.html


<!-- 参考信息 -->