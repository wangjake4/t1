代发 wailian999

);
来源：http://dali.ydzc1.top/Article/details/gt2ualixfqu.html

[Q03] 增加列
来源：http://dali.redwolf501.top/Article/details/gt2uacojrje.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.gaohongyu789.top/Article/details/gt2kestumco.html

[Q04] 修改列类型
来源：http://dali.jinqigfzy.top/Article/details/gt2jtslupne.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ehwqpu.com/Article/details/gt2cysetvzz.html

[Q05] 重命名列
来源：http://dali.havefunace.top/Article/details/gt2ibmrclby.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.wangdashe.top/Article/details/gt2dzukdxxp.html

[Q06] 删除列
来源：http://dali.zhoulong.xyz/Article/details/gt2tmjkdqge.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lqccrjjj.html

[Q07] 删除表
来源：http://dali.fengsongda.top/Article/details/gt2bzifbcpc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xuanzx.com/Article/details/gt2fgzcdcjz.html

[Q08] 创建普通索引
来源：http://dali.hnxiangtu.top/Article/details/gt2zbmwffwg.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hnqzz.top/Article/details/gt2marepttg.html

[Q09] 创建唯一索引
来源：http://dali.cdnleiting.top/Article/details/gt2ulmgieie.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2eoduldlz.html

[Q10] 插入单行
来源：http://dali.haohaochexian.top/Article/details/gt2xtjfccpy.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hammf.cn/Article/details/gt2iysfvxne.html

[Q11] 一次插入多行
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jbclmisr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shangyingyoupin.top/Article/details/gt2ivmvtznx.html

[Q12] 插入后取自增 ID
来源：http://dali.tian-w.cn/Article/details/gt2sgkigpuv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2valilgqd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jsipjufc.html

[Q13] 忽略重复插入
来源：http://dali.ydzc1.top/Article/details/gt2twphmoda.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jyoumei.cn/Article/details/gt2kpuvrfos.html

[Q14] 存在则更新（upsert）
来源：http://dali.jianghu66.top/Article/details/gt2hfywyygv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.wangshuangyany.cn/Article/details/gt2luvrdwca.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtawycvn.html

[Q15] 查询全部
来源：http://dali.ydzc1.top/Article/details/gt2hyomtbcv.html

SELECT * FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kgbyuqng.html

[Q16] 查询指定列
来源：http://dali.meibo888.top/Article/details/gt2ujyuobwg.html

SELECT id, name FROM users;
来源：http://dali.zycfv.cn/Article/details/gt2lpzuqjyk.html

[Q17] 条件查询
来源：http://dali.daxiang520.top/Article/details/gt2dboghhpz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hywenlv.cn/Article/details/gt2ipencrum.html

[Q18] 模糊匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2heqvfcqx.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.quarkkingdee.top/Article/details/gt2gxoznvjg.html

[Q19] 范围查询
来源：http://dali.svipenyu.cn/Article/details/gt2qbkijfmn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.316326.xyz/Article/details/gt2jcxgbjbf.html

[Q20] IN 列表
来源：http://dali.nanxuanxn.top/Article/details/gt2vzqqabmk.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.mhx1999.top/Article/details/gt2ywxlclad.html

[Q21] 空值判断
来源：http://dali.c1oappe.top/Article/details/gt2epjgxanf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.mhx1999.top/Article/details/gt2upznghwk.html

[Q22] 排序
来源：http://dali.pengpengdd.cyou/Article/details/gt2gkzzhrny.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.chenzaomai.com/Article/details/gt2egsurovh.html

[Q23] 分页
来源：http://dali.kuanghao11.cn/Article/details/gt2hbrrjyvd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cheryme.top/Article/details/gt2dnbgxwev.html

[Q24] 去重
来源：http://dali.wangdashe.top/Article/details/gt2fwqvgchz.html

SELECT DISTINCT city FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2orpbkyhu.html

[Q25] 只取前 N 条
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lwcslyen.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yuanzhike.top/Article/details/gt2knghhmrc.html

[Q26] 计数
来源：http://dali.zhixingplan.top/Article/details/gt2lgmxumxr.html

SELECT COUNT(*) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tkstasis.html

[Q27] 条件计数
来源：http://dali.nanxuanxn.top/Article/details/gt2elurxfie.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2tyezompj.html

[Q28] 求和与平均
来源：http://dali.yongpay.top/Article/details/gt2fzdwxecl.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gt2ztrbqola.html

[Q29] 最大最小值
来源：http://dali.guowangkeji.top/Article/details/gt2zxywbggo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ivvv.top/Article/details/gt2htbbbdgu.html

[Q30] 分组统计
来源：http://dali.chenjidiqi.icu/Article/details/gt2usdxrbos.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hywenlv.cn/Article/details/gt2yxajbskz.html

[Q31] 分组后过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xydmbycy.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yvedp.cn/Article/details/gt2hfdocurs.html

[Q32] 分组拼接字符串
来源：http://dali.chenzaomai.com/Article/details/gt2snqnnuxj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shangyingyoupin.top/Article/details/gt2oairjsqn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.feifeiyinyue.top/Article/details/gt2vnyvfyve.html

[Q33] 多列分组
来源：http://dali.tanke756.top/Article/details/gt2uxyfiwkc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.chenjidiqi.icu/Article/details/gt2yzgqihxl.html

[Q34] 每组取第一条
来源：http://dali.ybcxt.top/Article/details/gt2horqxxuw.html

SELECT * FROM (
来源：http://dali.meibo888.top/Article/details/gt2ulojfcmw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hammf.cn/Article/details/gt2urfebhms.html

) t WHERE rn = 1;
来源：http://dali.zhengqikj.top/Article/details/gt2lumpjfah.html

[Q35] 内连接
来源：http://dali.chenlongwang.top/Article/details/gt2aeynrmqn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.dashuyun.cn/Article/details/gt2rsiqszed.html

[Q36] 左连接
来源：http://dali.hnqzz.top/Article/details/gt2njvngazu.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzspyskg.html

[Q37] 右连接
来源：http://dali.xziqi.cn/Article/details/gt2hbbrtcsz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.tian-w.cn/Article/details/gt2iykbimxh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.birdmap.top/Article/details/gt2efrgbpag.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.mhx1999.top/Article/details/gt2hmfybuxn.html

[Q39] 自连接（查上下级）
来源：http://dali.yueranfly.top/Article/details/gt2pmtsojrt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yuanzhike.top/Article/details/gt2bflzzsrn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xuetiantiany.cn/Article/details/gt2ddbooeuf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.iojbl.cn/Article/details/gt2nbkabpps.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cashguo.top/Article/details/gt2olrlhiin.html

[Q41] 多表连接
来源：http://dali.ydzc1.top/Article/details/gt2yeihutdf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.pycfn.com/Article/details/gt2etxgidny.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xylfe.cn/Article/details/gt2xnbgbjdp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.daxiang520.top/Article/details/gt2pmeqwccw.html

[Q42] 连接条件附加过滤
来源：http://dali.zhiwuduotai.top/Article/details/gt2idotlqrn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.daxiang520.top/Article/details/gt2kznwuywn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.chenlongwang.top/Article/details/gt2xxtqwdul.html

[Q43] 标量子查询
来源：http://dali.dashuyun.cn/Article/details/gt2polblvec.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ppjwa.cn/Article/details/gt2kzkijagb.html

[Q44] IN 子查询
来源：http://dali.fengsongda.top/Article/details/gt2sqmvicpc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zycfv.cn/Article/details/gt2mtfmcmaf.html

[Q45] EXISTS 判断存在
来源：http://dali.yonumen.top/Article/details/gt2bblgfquc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.meibo888.top/Article/details/gt2zooagywz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.chenzaomai.com/Article/details/gt2bwlwmlwn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhixingplan.top/Article/details/gt2sbrfqbld.html

[Q47] 与平均值比较
来源：http://dali.ehwqpu.com/Article/details/gt2tswjjgrv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xylfe.cn/Article/details/gt2vvuunynn.html

[Q48] CTE 公用表表达式
来源：http://dali.ppjwa.cn/Article/details/gt2ehlwkilg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.daria6918.cn/Article/details/gt2rgujfcuu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jyoumei.cn/Article/details/gt2jbavqotp.html

[Q49] 更新单行
来源：http://dali.yuxming.cn/Article/details/gt2zmrozofz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xinyue.icu/Article/details/gt2bdlsgiqu.html

[Q50] 批量更新
来源：http://dali.iojbl.cn/Article/details/gt2jpubzbfj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhixingplan.top/Article/details/gt2nnlcbgts.html

[Q51] 用子查询更新
来源：http://dali.guowangkeji.top/Article/details/gt2uaihuptu.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gotoacloud.top/Article/details/gt2bwopxwug.html

[Q52] 删除指定行
来源：http://dali.fengsongda.top/Article/details/gt2coggfcvq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.meibo888.top/Article/details/gt2zdnwrmbs.html

[Q53] 按条件删除
来源：http://dali.sysykeji.top/Article/details/gt2zhxhjokc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.cheryme.top/Article/details/gt2argelojd.html

[Q54] 清空表
来源：http://dali.wangshuangyany.cn/Article/details/gt2ccccqpvc.html

TRUNCATE TABLE logs;
来源：http://dali.ydzc1.top/Article/details/gt2rzcxcqeh.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2intukhmj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.nanxuanxn.top/Article/details/gt2khoilucd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.c1oappe.top/Article/details/gt2jnblpcai.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.andypj.xyz/Article/details/gt2qpndtjnn.html

[Q57] 行号
来源：http://dali.ivvv.top/Article/details/gt2cujraepy.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2alsrstna.html

[Q58] 累计求和
来源：http://dali.sweek.top/Article/details/gt2takbzzwm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yonumen.top/Article/details/gt2qxsznjro.html

[Q59] 分组内累计
来源：http://dali.jinqigfzy.top/Article/details/gt2yewsjxdm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gt2kldihumt.html

[Q60] 取上一行 / 下一行
来源：http://dali.bjfxy.top/Article/details/gt2eyqnkjvp.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yonumen.top/Article/details/gt2bxqkknzi.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gt2nufmtjra.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2wwerxovn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xinyue.icu/Article/details/gt2kmcxrwon.html

[Q62] 分组占比
来源：http://dali.quarkkingdee.top/Article/details/gt2pjswynus.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.dianchejie.cn/Article/details/gt2mttkjukv.html

[Q63] 开启事务
来源：http://dali.bjfxy.top/Article/details/gt2sstukggo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ybcxt.top/Article/details/gt2ssxyxrfc.html

[Q64] 提交事务
来源：http://dali.chenlongwang.top/Article/details/gt2eknsywsg.html

COMMIT;
来源：http://dali.zhengqikj.top/Article/details/gt2hteieilv.html

[Q65] 回滚事务
来源：http://dali.zhengqikj.top/Article/details/gt2ebposrls.html

ROLLBACK;
来源：http://dali.cashguo.top/Article/details/gt2mrapkoor.html

[Q66] 行锁查询
来源：http://dali.zdqjudy.top/Article/details/gt2atodxisz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.tianlin.xyz/Article/details/gt2ddqgvupa.html

[Q67] 设置隔离级别
来源：http://dali.shangyingyoupin.top/Article/details/gt2qgfmpkaa.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.gzhubu.top/Article/details/gt2axuecyji.html

[Q68] 保存点
来源：http://dali.svipenyu.cn/Article/details/gt2uguspzgi.html

SAVEPOINT sp1;
来源：http://dali.hnqzz.top/Article/details/gt2wzyvroup.html

ROLLBACK TO sp1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kubwymjh.html

[Q69] 查看执行计划
来源：http://dali.hnxiangtu.top/Article/details/gt2pmjlrjgm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gogol.net.cn/Article/details/gt2xesanlws.html

[Q70] 更新统计信息
来源：http://dali.sysykeji.top/Article/details/gt2veuvtnqj.html

ANALYZE TABLE users;
来源：http://dali.tianlin.xyz/Article/details/gt2poknofsq.html

[Q71] 查看建表语句
来源：http://dali.yanxiufei.cn/Article/details/gt2dgkshare.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shuidangran.top/Article/details/gt2vcsqigri.html

[Q72] 查看索引
来源：http://dali.gaohongyu789.top/Article/details/gt2dfjepwmx.html

SHOW INDEX FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2pobgfgke.html

[Q73] 查看表状态
来源：http://dali.jqgufenzy.top/Article/details/gt2mqzrmbqg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.andypj.xyz/Article/details/gt2uxoakswr.html

[Q74] 强制使用索引
来源：http://dali.ivvv.top/Article/details/gt2xyvuogoi.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hnqzz.top/Article/details/gt2lqvknnxy.html

[Q75] 日期格式化
来源：http://dali.pycfn.com/Article/details/gt2zhhtizba.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gt2nptazptg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ivvv.top/Article/details/gt2xuulylua.html

[Q76] 按天统计
来源：http://dali.hammf.cn/Article/details/gt2hopiwchw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.daxiang520.top/Article/details/gt2auawltvh.html

[Q77] 时间加减
来源：http://dali.fzhhl.top/Article/details/gt2bmjxnfwn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shangyingyoupin.top/Article/details/gt2jlsoimpc.html

[Q78] 当前时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ithocrla.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yj202588.top/Article/details/gt2jxcnjidn.html

[Q79] 字符串拼接
来源：http://dali.yj20258.top/Article/details/gt2frrutmwr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gzhubu.top/Article/details/gt2alillwip.html

[Q80] 字符串截取
来源：http://dali.hnqzz.top/Article/details/gt2xwjiuold.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.pycfn.com/Article/details/gt2wbecrpuy.html

[Q81] 字符串替换
来源：http://dali.jqgufenzy.top/Article/details/gt2lzxqnrng.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2bknnybmv.html

[Q82] 字符长度与字节长度
来源：http://dali.tanke756.top/Article/details/gt2blgkuzlg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.tian-w.cn/Article/details/gt2bfgfyjtl.html

[Q83] 大小写转换
来源：http://dali.yj202588.top/Article/details/gt2kuefgdbo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2dkfitosn.html

[Q84] 去除首尾空格
来源：http://dali.0kj1m.cn/Article/details/gt2yvdubpuf.html

SELECT TRIM(name) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mvprhyvl.html

[Q85] 数值取整
来源：http://dali.0kj1m.cn/Article/details/gt2tbkurken.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.9152youxi.cn/Article/details/gt2vrjicfpz.html

[Q86] 读取 JSON 字段
来源：http://dali.yj202588.top/Article/details/gt2paifevrp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.dianchejie.cn/Article/details/gt2eutyjznm.html

[Q87] JSON 字段做条件
来源：http://dali.xinyue.icu/Article/details/gt2scmvwgsw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gogol.net.cn/Article/details/gt2tcvmzbyp.html

[Q88] 行转列（条件聚合）
来源：http://dali.ybcxt.top/Article/details/gt2vrqqhbjw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.sysykeji.top/Article/details/gt2qglrwypm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zycfv.cn/Article/details/gt2pkbzrrsa.html

[Q89] 判断表是否存在
来源：http://dali.hnxiangtu.top/Article/details/gt2cuqujnbv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hnxiangtu.top/Article/details/gt2eirssglr.html

[Q90] 生成序号列
来源：http://dali.xinyue.icu/Article/details/gt2cehbjjks.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ydzc1.top/Article/details/gt2cjylcgsg.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2qujnngeu.html

R. Bash 专题
来源：http://dali.ydzc1.top/Article/details/gt2jofuktou.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2vjhmbqbd.html

[R01] shebang 与严格模式
来源：http://dali.bjfxy.top/Article/details/gt2ifijtgzy.html

#!/usr/bin/env bash
来源：http://dali.svipenyu.cn/Article/details/gt2lewcsduo.html

set -euo pipefail
来源：http://dali.ivvv.top/Article/details/gt2bkzfkntg.html

[R02] 变量赋值与使用
来源：http://dali.yangfankeji.com/Article/details/gt2cccauglr.html

name="Tom"; echo "$name"
来源：http://dali.guannengcc.top/Article/details/gt2fnsjqflw.html

[R03] 只读变量
来源：http://dali.jianghu66.top/Article/details/gt2jhagiudw.html

readonly PI=3.14
来源：http://dali.guowangkeji.top/Article/details/gt2fpuysbuq.html

[R04] 位置参数
来源：http://dali.hnxiangtu.top/Article/details/gt2baivtosm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.c1oappe.top/Article/details/gt2odebsztx.html

[R05] 参数默认值
来源：http://dali.hfpthk.cn/Article/details/gt2pxtputip.html

name="${1:-default}"
来源：http://dali.yj20258.top/Article/details/gt2ctuwxxtg.html

[R06] 判断命令是否存在
来源：http://dali.gotoacloud.top/Article/details/gt2wfkfhnhj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gzhubu.top/Article/details/gt2dsoperyp.html

[R07] if 判断文件
来源：http://dali.sysykeji.top/Article/details/gt2hlkkvavm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.tianlin.xyz/Article/details/gt2qsekubcj.html

[R08] 数值比较
来源：http://dali.tanke756.top/Article/details/gt2ujtdlron.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gotoacloud.top/Article/details/gt2jfhphegx.html

[R09] 字符串比较
来源：http://dali.quarkkingdee.top/Article/details/gt2ofotwfuz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sazameai.html

[R10] 正则匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lesbaamd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhiwuduotai.top/Article/details/gt2mjmlekqq.html

[R11] case 多分支
来源：http://dali.cashguo.top/Article/details/gt2iagrzyhx.html

case "$1" in
来源：http://dali.yj20258888.top/Article/details/gt2rvdqkuxg.html

start) echo "启动" ;;
来源：http://dali.ivvv.top/Article/details/gt2jtcfffhc.html

stop)  echo "停止" ;;
来源：http://dali.jlsjyb.cn/Article/details/gt2kbzunkdb.html

*)     echo "未知命令" ;;
来源：http://dali.sufxvd.cn/Article/details/gt2nooiatlw.html

esac
来源：http://dali.tian-w.cn/Article/details/gt2hnfvzmtv.html

[R12] for 遍历文件
来源：http://dali.xziqi.cn/Article/details/gt2dxgdmwqi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.pycfn.com/Article/details/gt2weccjlnu.html

[R13] for 计数循环
来源：http://dali.pycfn.com/Article/details/gt2iltjjtze.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinqigufen.top/Article/details/gt2wkilueyt.html

[R14] C 风格 for
来源：http://dali.aizwys.cn/Article/details/gt2rudqmapz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.chenjidiqi.icu/Article/details/gt2spxurvln.html

[R15] while 逐行读文件
来源：http://dali.fengsongda.top/Article/details/gt2ppeiptzc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinqigufen.top/Article/details/gt2oylokjbt.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqxcwsl.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ebfhixal.html

[R17] 数组定义与取值
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lqsugiwm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.redwolf501.top/Article/details/gt2bprboxdf.html

[R18] 遍历数组
来源：http://dali.guowangkeji.top/Article/details/gt2scxocrou.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.quarkkingdee.top/Article/details/gt2jgzefslf.html

[R19] 数组长度
来源：http://dali.redwolf501.top/Article/details/gt2qfwakymf.html

echo "${#arr[@]}"
来源：http://dali.yanxiufei.cn/Article/details/gt2vxxuuidl.html

[R20] 关联数组（字典）
来源：http://dali.ivvv.top/Article/details/gt2hlkirxjw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rfdwqcng.html

[R21] 字符串长度
来源：http://dali.sweek.top/Article/details/gt2tbgoxvbh.html

echo "${#s}"
来源：http://dali.hammf.cn/Article/details/gt2ctcwrnve.html

[R22] 截取子串
来源：http://dali.yj20258888.top/Article/details/gt2gdoeqkge.html

echo "${s:0:5}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2licpcian.html

[R23] 字符串替换
来源：http://dali.ivvv.top/Article/details/gt2ukcqkxnh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.nanxuanxn.top/Article/details/gt2fdlineow.html

[R24] 大小写转换
来源：http://dali.yonumen.top/Article/details/gt2vrztrqgw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2wdpmsjyb.html

[R25] 去后缀 / 去前缀
来源：http://dali.fengsongda.top/Article/details/gt2ktqutidd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.nwbrower.top/Article/details/gt2sbxpqdkq.html

[R26] 命令替换
来源：http://dali.cashguo.top/Article/details/gt2jajeeezv.html

now=$(date +%F); echo "$now"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dfagnijl.html

[R27] 算术展开
来源：http://dali.gzhubu.top/Article/details/gt2ivezcofz.html

echo $((1 + 2 * 3))
来源：http://dali.vqdsnc.cn/Article/details/gt2fbcwinqg.html

[R28] 浮点运算
来源：http://dali.daria6918.cn/Article/details/gt2newsfslm.html

echo "scale=2; 10/3" | bc
来源：http://dali.9152youxi.cn/Article/details/gt2twpcxqdk.html

[R29] 定义函数
来源：http://dali.zhoulong.xyz/Article/details/gt2nhanqzhy.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yanxiufei.cn/Article/details/gt2qfjlpcek.html

[R30] 函数返回状态码
来源：http://dali.svipenyu.cn/Article/details/gt2jurhtloq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sxryk.cn/Article/details/gt2hcctnclp.html

[R31] 局部变量
来源：http://dali.nwbrower.top/Article/details/gt2aisihmfd.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2jowhhbpi.html

[R32] 参数个数校验
来源：http://dali.jqgfzy.top/Article/details/gt2qyxmqntz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hfpthk.cn/Article/details/gt2iaeyxwkl.html

[R33] 捕获错误并提示行号
来源：http://dali.mhx1999.top/Article/details/gt2wklfpsti.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yj202588.top/Article/details/gt2gcljkirr.html

[R34] 退出时清理
来源：http://dali.xziqi.cn/Article/details/gt2jjquaxhw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.dianchejie.cn/Article/details/gt2lmcerkaq.html

[R35] 后台执行并等待
来源：http://dali.smart0.xyz/Article/details/gt2fbxnxrwb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zycfv.cn/Article/details/gt2odbizriw.html

[R36] 并发执行多个任务
来源：http://dali.jiagoushi.top/Article/details/gt2dzclylfz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.tanke756.top/Article/details/gt2wusnpqoc.html

[R37] 把输出赋给变量
来源：http://dali.jiagoushi.top/Article/details/gt2bffkjzwg.html

files=$(ls -1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kmydksfe.html

[R38] 管道串联
来源：http://dali.smart0.xyz/Article/details/gt2ojtxqfda.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sweek.top/Article/details/gt2smpqrtgu.html

[R39] 重定向标准输出与错误
来源：http://dali.zdqjudy.top/Article/details/gt2amssnlmk.html

cmd > out.log 2>&1
来源：http://dali.fzhhl.top/Article/details/gt2yzeeuoqr.html

[R40] 追加写日志
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rzgsxlrh.html

echo "log" >> out.log
来源：http://dali.zhixingplan.top/Article/details/gt2vaqnheyq.html

[R41] 丢弃输出
来源：http://dali.cdnleiting.top/Article/details/gt2eaeousfu.html

cmd >/dev/null 2>&1
来源：http://dali.chenzaomai.com/Article/details/gt2btapyfpi.html

[R42] 输入重定向
来源：http://dali.ivvv.top/Article/details/gt2jboisbso.html

wc -l < a.txt
来源：http://dali.ydzc1.top/Article/details/gt2bjgtxctq.html

[R43] 按名字查找文件
来源：http://dali.vqdsnc.cn/Article/details/gt2oucbzkey.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zetvmxjy.html

[R44] 按修改时间查找
来源：http://dali.cdnleiting.top/Article/details/gt2nmpsxuyo.html

find . -mtime -7 -type f
来源：http://dali.dianchejie.cn/Article/details/gt2sxdhzbnm.html

[R45] 批量删除
来源：http://dali.xuetiantiany.cn/Article/details/gt2wijetrzq.html

find . -name "*.tmp" -delete
来源：http://dali.zhongyouzk.top/Article/details/gt2dbrahixt.html

[R46] 递归替换文件内容
来源：http://dali.yonumen.top/Article/details/gt2uaprmwlb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.gzhubu.top/Article/details/gt2rmbrsawt.html

[R47] sed 单行替换
来源：http://dali.gotoacloud.top/Article/details/gt2udabddgp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.bjfxy.top/Article/details/gt2erwbfkmk.html

[R48] awk 取指定列
来源：http://dali.xylfe.cn/Article/details/gt2tuoeogcf.html

awk '{print $1, $3}' a.txt
来源：http://dali.yangfankeji.com/Article/details/gt2nteybjqj.html

[R49] awk 带条件
来源：http://dali.yuxming.cn/Article/details/gt2cwtrgplm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.tianlin.xyz/Article/details/gt2mepxfivi.html

[R50] awk 求和
来源：http://dali.wangdashe.top/Article/details/gt2jhjbpbip.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.havefunace.top/Article/details/gt2iswsukzn.html

[R51] 排序去重取前几
来源：http://dali.feifeiyinyue.top/Article/details/gt2maybkedg.html


<!-- 参考信息 -->