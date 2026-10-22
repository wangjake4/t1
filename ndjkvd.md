代发 wailian999

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2pdyotouo.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.daxiang520.top/Article/details/gt2zvyhaldz.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2kkivgbin.html

[Q01] 创建表
来源：http://dali.shangyingyoupin.top/Article/details/gt2ncbgnubv.html

CREATE TABLE users (
来源：http://dali.dashuyun.cn/Article/details/gt2vzrdestq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nanxuanxn.top/Article/details/gt2lbflgaco.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zpluijkm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.chenlongwang.top/Article/details/gt2clnfbjsw.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.kuanghao11.cn/Article/details/gt2dnyfuquh.html

);
来源：http://dali.haohaochexian.top/Article/details/gt2mtaxgtqp.html

[Q02] 创建带外键的表
来源：http://dali.pycfn.com/Article/details/gt2vtvikydu.html

CREATE TABLE orders (
来源：http://dali.chenjidiqi.icu/Article/details/gt2qdheoypr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.feifeiyinyue.top/Article/details/gt2apyiegln.html

user_id INT NOT NULL,
来源：http://dali.kuanghao11.cn/Article/details/gt2yoxgssrm.html

amount DECIMAL(10, 2),
来源：http://dali.fzhhl.top/Article/details/gt2rrdxsbzr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zdqjudy.top/Article/details/gt2zpwpanpr.html

);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uhhxhlwp.html

[Q03] 增加列
来源：http://dali.redwolf501.top/Article/details/gt2oqkuaghv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.guannengcc.top/Article/details/gt2gbmcnege.html

[Q04] 修改列类型
来源：http://dali.fzhhl.top/Article/details/gt2ekoxfygc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhoulong.xyz/Article/details/gt2funucork.html

[Q05] 重命名列
来源：http://dali.yj202588.top/Article/details/gt2osknwqbh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jiagoushi.top/Article/details/gt2aeuzkklb.html

[Q06] 删除列
来源：http://dali.cucudq.cn/Article/details/gt2qcloefma.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.smart0.xyz/Article/details/gt2ptitqhzu.html

[Q07] 删除表
来源：http://dali.xinyue.icu/Article/details/gt2vkwxcxoo.html

DROP TABLE IF EXISTS orders;
来源：http://dali.nwbrower.top/Article/details/gt2vqzxagly.html

[Q08] 创建普通索引
来源：http://dali.cashguo.top/Article/details/gt2urrbazjh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.wangdashe.top/Article/details/gt2tyespoak.html

[Q09] 创建唯一索引
来源：http://dali.chenjidiqi.icu/Article/details/gt2guokoykl.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhiwuduotai.top/Article/details/gt2yowvutdh.html

[Q10] 插入单行
来源：http://dali.hnqzz.top/Article/details/gt2gzychcaq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xylfe.cn/Article/details/gt2izaeogos.html

[Q11] 一次插入多行
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iapgqphg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cdnleiting.top/Article/details/gt2titysjsa.html

[Q12] 插入后取自增 ID
来源：http://dali.hammf.cn/Article/details/gt2cmvmjclm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gotoacloud.top/Article/details/gt2crckwveh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.smart0.xyz/Article/details/gt2pxqxmxjq.html

[Q13] 忽略重复插入
来源：http://dali.zhixingplan.top/Article/details/gt2hiklmjpt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.smart0.xyz/Article/details/gt2afwcnunc.html

[Q14] 存在则更新（upsert）
来源：http://dali.xuanzx.com/Article/details/gt2ugtznmbl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhixingplan.top/Article/details/gt2aivhkjwe.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhengqikj.top/Article/details/gt2gzpnnqya.html

[Q15] 查询全部
来源：http://dali.hfpthk.cn/Article/details/gt2zsfdinnv.html

SELECT * FROM users;
来源：http://dali.ivvv.top/Article/details/gt2opqxbtrs.html

[Q16] 查询指定列
来源：http://dali.cqqwz.cn/Article/details/gt2lkfecaob.html

SELECT id, name FROM users;
来源：http://dali.316326.xyz/Article/details/gt2pgnkotqk.html

[Q17] 条件查询
来源：http://dali.cheryme.top/Article/details/gt2pvbqjpto.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.316326.xyz/Article/details/gt2vzvleemn.html

[Q18] 模糊匹配
来源：http://dali.yongpay.top/Article/details/gt2solriukg.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xsgorbsd.html

[Q19] 范围查询
来源：http://dali.guowangkeji.top/Article/details/gt2vudfrytn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinqigufen.top/Article/details/gt2jocejrgv.html

[Q20] IN 列表
来源：http://dali.zhiwuduotai.top/Article/details/gt2nuvxmxlz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yj20258.top/Article/details/gt2jpteqogt.html

[Q21] 空值判断
来源：http://dali.yonumen.top/Article/details/gt2vlpqbrma.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hywenlv.cn/Article/details/gt2jccyaxyq.html

[Q22] 排序
来源：http://dali.shanyushiyangtech.top/Article/details/gt2miwmcqzu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.kuanghao11.cn/Article/details/gt2fmgsjsrk.html

[Q23] 分页
来源：http://dali.ehwqpu.com/Article/details/gt2kdernfst.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.quarkkingdee.top/Article/details/gt2wljgweyh.html

[Q24] 去重
来源：http://dali.snrcjt.cn/Article/details/gt2laylcety.html

SELECT DISTINCT city FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2mhsyseee.html

[Q25] 只取前 N 条
来源：http://dali.shuidangran.top/Article/details/gt2gzuthsyj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shzxlz.cn/Article/details/gt2gypizick.html

[Q26] 计数
来源：http://dali.fengsongda.top/Article/details/gt2dsvvjyvb.html

SELECT COUNT(*) FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2fnbtaljl.html

[Q27] 条件计数
来源：http://dali.316326.xyz/Article/details/gt2peojvcsq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2pnaxytwr.html

[Q28] 求和与平均
来源：http://dali.ppjwa.cn/Article/details/gt2mxdkforn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zfhgjbor.html

[Q29] 最大最小值
来源：http://dali.sysykeji.top/Article/details/gt2rxafzumu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.meibo888.top/Article/details/gt2bgtwtuuq.html

[Q30] 分组统计
来源：http://dali.vqdsnc.cn/Article/details/gt2jiomikbp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jinqigufen.top/Article/details/gt2ebvmtuga.html

[Q31] 分组后过滤
来源：http://dali.ydzc1.top/Article/details/gt2uggonaok.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.gaohongyu789.top/Article/details/gt2hhfllrfq.html

[Q32] 分组拼接字符串
来源：http://dali.zhixingplan.top/Article/details/gt2cfqpizdo.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hongshengwenyu.top/Article/details/gt2rprmxmvx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xuetiantiany.cn/Article/details/gt2xsuignqt.html

[Q33] 多列分组
来源：http://dali.shangyingyoupin.top/Article/details/gt2pospqgpr.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xinyue.icu/Article/details/gt2cuppifvg.html

[Q34] 每组取第一条
来源：http://dali.0kj1m.cn/Article/details/gt2kzpmiedh.html

SELECT * FROM (
来源：http://dali.jiagoushi.top/Article/details/gt2gnhstlpr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jiagoushi.top/Article/details/gt2hidzjflv.html

) t WHERE rn = 1;
来源：http://dali.jiagoushi.top/Article/details/gt2gcacmfko.html

[Q35] 内连接
来源：http://dali.cqqwz.cn/Article/details/gt2szlutrpc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cashguo.top/Article/details/gt2wwthpofk.html

[Q36] 左连接
来源：http://dali.shuidangran.top/Article/details/gt2lggrqbed.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinqigfzy.top/Article/details/gt2ocvocncf.html

[Q37] 右连接
来源：http://dali.yuanzhike.top/Article/details/gt2ubxovuic.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.redwolf501.top/Article/details/gt2jrvmbiud.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2rmltyciu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.dianchejie.cn/Article/details/gt2tjeheinn.html

[Q39] 自连接（查上下级）
来源：http://dali.daxiang520.top/Article/details/gt2pihsewin.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yuxming.cn/Article/details/gt2oyidzdpf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hnqzz.top/Article/details/gt2mcgbkvjz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rwfcmlye.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yangfankeji.com/Article/details/gt2jzsjftmo.html

[Q41] 多表连接
来源：http://dali.cheryme.top/Article/details/gt2grqosjpd.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vceazfxe.html

JOIN users u ON u.id = o.user_id
来源：http://dali.pycfn.com/Article/details/gt2mqxiqrpi.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cucudq.cn/Article/details/gt2okvocwer.html

[Q42] 连接条件附加过滤
来源：http://dali.hongshengwenyu.top/Article/details/gt2opsjwxrw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shzxlz.cn/Article/details/gt2jjqqalji.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.aizwys.cn/Article/details/gt2htkmcbao.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwesnqd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xuetiantiany.cn/Article/details/gt2ruujadbe.html

[Q44] IN 子查询
来源：http://dali.guannengcc.top/Article/details/gt2xjxmzkwa.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cdnleiting.top/Article/details/gt2mfxylegw.html

[Q45] EXISTS 判断存在
来源：http://dali.nanxinkj.top/Article/details/gt2gwuwripz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sweek.top/Article/details/gt2tzgouwxj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhongyouzk.top/Article/details/gt2gloyngzk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jlsjyb.cn/Article/details/gt2lfhseuld.html

[Q47] 与平均值比较
来源：http://dali.zdqjudy.top/Article/details/gt2njkfjzpy.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.9152youxi.cn/Article/details/gt2hpiyzvlj.html

[Q48] CTE 公用表表达式
来源：http://dali.redwolf501.top/Article/details/gt2fcecwbrw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yanxiufei.cn/Article/details/gt2vnujoplt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jyoumei.cn/Article/details/gt2psrirxkt.html

[Q49] 更新单行
来源：http://dali.xziqi.cn/Article/details/gt2dsebewrb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jyoumei.cn/Article/details/gt2eioppeyv.html

[Q50] 批量更新
来源：http://dali.ybcxt.top/Article/details/gt2ipzxoibo.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.bjfxy.top/Article/details/gt2vuliiauh.html

[Q51] 用子查询更新
来源：http://dali.ybcxt.top/Article/details/gt2whxsauzj.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hnxiangtu.top/Article/details/gt2xvzufgje.html

[Q52] 删除指定行
来源：http://dali.hnxiangtu.top/Article/details/gt2lwammgrr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jyoumei.cn/Article/details/gt2yncmddrt.html

[Q53] 按条件删除
来源：http://dali.yj20258888.top/Article/details/gt2hfoqmckg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.nanxinkj.top/Article/details/gt2wllijods.html

[Q54] 清空表
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lxzefkey.html

TRUNCATE TABLE logs;
来源：http://dali.gotoacloud.top/Article/details/gt2wpestzfe.html

[Q55] 排名（并列占位）
来源：http://dali.yuxming.cn/Article/details/gt2mlzlofwd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cdnleiting.top/Article/details/gt2mzteqsfb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.nanxuanxn.top/Article/details/gt2kooefzdc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.bjfxy.top/Article/details/gt2mcgnptph.html

[Q57] 行号
来源：http://dali.yj20258.top/Article/details/gt2ehvokeol.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2welgeaav.html

[Q58] 累计求和
来源：http://dali.birdmap.top/Article/details/gt2lafnqhpe.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zycfv.cn/Article/details/gt2hwtelemv.html

[Q59] 分组内累计
来源：http://dali.wangshuangyany.cn/Article/details/gt2mjbckrqm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hnqzz.top/Article/details/gt2dskgzmht.html

[Q60] 取上一行 / 下一行
来源：http://dali.zdqjudy.top/Article/details/gt2jhbebpxv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.birdmap.top/Article/details/gt2heblvybp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gt2znhqcnrk.html

[Q61] 移动平均
来源：http://dali.jinqigufen.top/Article/details/gt2ptsjogor.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yueranfly.top/Article/details/gt2keywtaje.html

[Q62] 分组占比
来源：http://dali.cqqwz.cn/Article/details/gt2mzpexvyt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.chenlongwang.top/Article/details/gt2lgqzrugc.html

[Q63] 开启事务
来源：http://dali.hnqzz.top/Article/details/gt2yqfatgoo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.daxiang520.top/Article/details/gt2knwcixam.html

[Q64] 提交事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xtadknxi.html

COMMIT;
来源：http://dali.hongshengwenyu.top/Article/details/gt2tfkrgfzm.html

[Q65] 回滚事务
来源：http://dali.gaohongyu789.top/Article/details/gt2vgwlyxvu.html

ROLLBACK;
来源：http://dali.fengsongda.top/Article/details/gt2tdnwrwrl.html

[Q66] 行锁查询
来源：http://dali.guannengcc.top/Article/details/gt2cmylmhfn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.feifeiyinyue.top/Article/details/gt2kgepevjn.html

[Q67] 设置隔离级别
来源：http://dali.zhiwuduotai.top/Article/details/gt2uuvqadpj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.vqdsnc.cn/Article/details/gt2jtkiwrtr.html

[Q68] 保存点
来源：http://dali.yuxming.cn/Article/details/gt2tkmpfahy.html

SAVEPOINT sp1;
来源：http://dali.zycfv.cn/Article/details/gt2yhngaxni.html

ROLLBACK TO sp1;
来源：http://dali.sufxvd.cn/Article/details/gt2gylzryab.html

[Q69] 查看执行计划
来源：http://dali.fzhhl.top/Article/details/gt2ivsvgqsw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xuanzx.com/Article/details/gt2tkojhaiw.html

[Q70] 更新统计信息
来源：http://dali.yj202588.top/Article/details/gt2jtfqpunj.html

ANALYZE TABLE users;
来源：http://dali.jiagoushi.top/Article/details/gt2vzymluna.html

[Q71] 查看建表语句
来源：http://dali.yj202588.top/Article/details/gt2plcdxqsx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.gotoacloud.top/Article/details/gt2cvektzgo.html

[Q72] 查看索引
来源：http://dali.fzhhl.top/Article/details/gt2yeztdriu.html

SHOW INDEX FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2prootsmr.html

[Q73] 查看表状态
来源：http://dali.yj20258888.top/Article/details/gt2pvtsinhh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.andypj.xyz/Article/details/gt2ogciivhp.html

[Q74] 强制使用索引
来源：http://dali.fengsongda.top/Article/details/gt2qeohkdeb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jyoumei.cn/Article/details/gt2ggkycklx.html

[Q75] 日期格式化
来源：http://dali.ivvv.top/Article/details/gt2usxlbjzg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shuidangran.top/Article/details/gt2fyqosqoj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jqgufenzy.top/Article/details/gt2lorpodvs.html

[Q76] 按天统计
来源：http://dali.havefunace.top/Article/details/gt2vxescxsr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jianghu66.top/Article/details/gt2tajkeahk.html

[Q77] 时间加减
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ccwocedt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gaohongyu789.top/Article/details/gt2zkcddjli.html

[Q78] 当前时间
来源：http://dali.shuidangran.top/Article/details/gt2cndvvezt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.daria6918.cn/Article/details/gt2ccyilleo.html

[Q79] 字符串拼接
来源：http://dali.ivvv.top/Article/details/gt2ujyywqbh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.tianlin.xyz/Article/details/gt2snrfpcsd.html

[Q80] 字符串截取
来源：http://dali.aibaodan.cn/Article/details/gt2qkuaugtn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.pycfn.com/Article/details/gt2zjppilrj.html

[Q81] 字符串替换
来源：http://dali.andypj.xyz/Article/details/gt2irraqarw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2dpdcaxmr.html

[Q82] 字符长度与字节长度
来源：http://dali.bjfxy.top/Article/details/gt2wsdsymeh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2lqyimays.html

[Q83] 大小写转换
来源：http://dali.chenlongwang.top/Article/details/gt2bvitodnm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2anmxgfti.html

[Q84] 去除首尾空格
来源：http://dali.hnqzz.top/Article/details/gt2cylknpgl.html

SELECT TRIM(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gt2olnsjqab.html

[Q85] 数值取整
来源：http://dali.gogol.net.cn/Article/details/gt2aorqqazc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.vqdsnc.cn/Article/details/gt2mtwwmvzm.html

[Q86] 读取 JSON 字段
来源：http://dali.gogol.net.cn/Article/details/gt2rstgxsvs.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.nwbrower.top/Article/details/gt2fsulrkmm.html

[Q87] JSON 字段做条件
来源：http://dali.xziqi.cn/Article/details/gt2eaftkwov.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.tanke756.top/Article/details/gt2tbqqkigp.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhengqikj.top/Article/details/gt2idrilcbn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.smart0.xyz/Article/details/gt2lqkbfllm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cheryme.top/Article/details/gt2ekdaryjf.html

[Q89] 判断表是否存在
来源：http://dali.hnqzz.top/Article/details/gt2ahdcqfhd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.birdmap.top/Article/details/gt2tjilesfp.html

[Q90] 生成序号列
来源：http://dali.yongpay.top/Article/details/gt2leqomeig.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.0kj1m.cn/Article/details/gt2jqpjbsgw.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2hdtywrxn.html

R. Bash 专题
来源：http://dali.jiagoushi.top/Article/details/gt2msetmqzd.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2cgwknoij.html

[R01] shebang 与严格模式
来源：http://dali.hnxiangtu.top/Article/details/gt2pqkfqmkm.html

#!/usr/bin/env bash
来源：http://dali.hywenlv.cn/Article/details/gt2tqorvsrb.html

set -euo pipefail
来源：http://dali.chenjidiqi.icu/Article/details/gt2xuvudwcb.html

[R02] 变量赋值与使用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yyirdzwc.html

name="Tom"; echo "$name"
来源：http://dali.pycfn.com/Article/details/gt2iofsgtjv.html

[R03] 只读变量
来源：http://dali.fzhhl.top/Article/details/gt2fectxoar.html

readonly PI=3.14
来源：http://dali.zhongyouzk.top/Article/details/gt2xtvdwfhg.html

[R04] 位置参数
来源：http://dali.hnqzz.top/Article/details/gt2wnytkqif.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jqgufenzy.top/Article/details/gt2ynmktzar.html

[R05] 参数默认值
来源：http://dali.jqgufenzy.top/Article/details/gt2koekeidt.html

name="${1:-default}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2uzuxsibb.html

[R06] 判断命令是否存在
来源：http://dali.daxiang520.top/Article/details/gt2ikjbcect.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.fengsongda.top/Article/details/gt2aalgilgo.html

[R07] if 判断文件
来源：http://dali.yuxming.cn/Article/details/gt2dstemzpv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.nwbrower.top/Article/details/gt2uqnuiizh.html

[R08] 数值比较
来源：http://dali.ppjwa.cn/Article/details/gt2pglpqzze.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sysykeji.top/Article/details/gt2izkvizin.html

[R09] 字符串比较
来源：http://dali.zhiwuduotai.top/Article/details/gt2ffbialae.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ivvv.top/Article/details/gt2hbqqfgbm.html

[R10] 正则匹配
来源：http://dali.yuxming.cn/Article/details/gt2hvifjoxe.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sweek.top/Article/details/gt2uducglii.html

[R11] case 多分支
来源：http://dali.zhongyouzk.top/Article/details/gt2akdhclac.html

case "$1" in
来源：http://dali.smart0.xyz/Article/details/gt2waagktgt.html

start) echo "启动" ;;
来源：http://dali.hammf.cn/Article/details/gt2qozvxoiq.html

stop)  echo "停止" ;;
来源：http://dali.daria6918.cn/Article/details/gt2fzpdctek.html

*)     echo "未知命令" ;;
来源：http://dali.jinqigfzy.top/Article/details/gt2gvvpqqvm.html

esac
来源：http://dali.cqqwz.cn/Article/details/gt2ugadvkoo.html

[R12] for 遍历文件
来源：http://dali.jqgfzy.top/Article/details/gt2hswxkkus.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sxryk.cn/Article/details/gt2tlztmjxz.html

[R13] for 计数循环
来源：http://dali.dianchejie.cn/Article/details/gt2kmnkjbpy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.wangshuangyany.cn/Article/details/gt2geqxkifv.html

[R14] C 风格 for
来源：http://dali.hfpthk.cn/Article/details/gt2gzbsucfi.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.guannengcc.top/Article/details/gt2dpjbuqac.html

[R15] while 逐行读文件
来源：http://dali.redwolf501.top/Article/details/gt2rcmluvek.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.haohaochexian.top/Article/details/gt2qocfgubv.html

[R16] until 等待条件
来源：http://dali.shangyingyoupin.top/Article/details/gt2dfhlkjen.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hongshengwenyu.top/Article/details/gt2szqchfqz.html

[R17] 数组定义与取值
来源：http://dali.svipenyu.cn/Article/details/gt2nexaoacy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yj20258.top/Article/details/gt2vxhwmcyn.html

[R18] 遍历数组
来源：http://dali.kuanghao11.cn/Article/details/gt2jiecrnzy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gogol.net.cn/Article/details/gt2uqpvuxpu.html

[R19] 数组长度
来源：http://dali.sufxvd.cn/Article/details/gt2kfpzielv.html

echo "${#arr[@]}"
来源：http://dali.zdqjudy.top/Article/details/gt2rnfbehys.html

[R20] 关联数组（字典）
来源：http://dali.daria6918.cn/Article/details/gt2cejygsbt.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sxryk.cn/Article/details/gt2wdipcmes.html

[R21] 字符串长度
来源：http://dali.bjfxy.top/Article/details/gt2vtiyzcck.html

echo "${#s}"
来源：http://dali.shuidangran.top/Article/details/gt2texkdawl.html

[R22] 截取子串
来源：http://dali.nwbrower.top/Article/details/gt2ywchuwxh.html

echo "${s:0:5}"
来源：http://dali.zdqjudy.top/Article/details/gt2davjlcmg.html

[R23] 字符串替换
来源：http://dali.yueranfly.top/Article/details/gt2tzwsouuu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ehwqpu.com/Article/details/gt2ceqbovkb.html

[R24] 大小写转换
来源：http://dali.fengsongda.top/Article/details/gt2ewacmpiw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cdnleiting.top/Article/details/gt2qyvwzgsk.html

[R25] 去后缀 / 去前缀
来源：http://dali.andypj.xyz/Article/details/gt2tcadbhib.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zbztevjz.html

[R26] 命令替换
来源：http://dali.0kj1m.cn/Article/details/gt2flhsrzta.html

now=$(date +%F); echo "$now"
来源：http://dali.birdmap.top/Article/details/gt2klvvvxqp.html

[R27] 算术展开
来源：http://dali.xuanzx.com/Article/details/gt2jwvcbpwv.html

echo $((1 + 2 * 3))
来源：http://dali.hfpthk.cn/Article/details/gt2hjajggpe.html

[R28] 浮点运算
来源：http://dali.smart0.xyz/Article/details/gt2dtbaiiib.html

echo "scale=2; 10/3" | bc
来源：http://dali.redwolf501.top/Article/details/gt2xmdgdtpb.html

[R29] 定义函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2inmqlqkt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yj20258.top/Article/details/gt2qqwqqbel.html

[R30] 函数返回状态码
来源：http://dali.zhiwuduotai.top/Article/details/gt2nmplohlr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.wangdashe.top/Article/details/gt2ifcdlyyf.html

[R31] 局部变量
来源：http://dali.chenlongwang.top/Article/details/gt2hqwnzaeq.html

f() { local x=1; echo "$x"; }
来源：http://dali.hnqzz.top/Article/details/gt2chosbmqe.html

[R32] 参数个数校验
来源：http://dali.jinqigufen.top/Article/details/gt2lnulwxgt.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yanxiufei.cn/Article/details/gt2frpuljbw.html

[R33] 捕获错误并提示行号
来源：http://dali.mhx1999.top/Article/details/gt2nkohvsnm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sysykeji.top/Article/details/gt2hyyjtyrd.html

[R34] 退出时清理
来源：http://dali.jiagoushi.top/Article/details/gt2bzgarfwt.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.daria6918.cn/Article/details/gt2ntwujhgs.html

[R35] 后台执行并等待
来源：http://dali.jyoumei.cn/Article/details/gt2ziimcphy.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jianghu66.top/Article/details/gt2ttyxywkp.html

[R36] 并发执行多个任务
来源：http://dali.jiagoushi.top/Article/details/gt2pqhbxmqx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.pycfn.com/Article/details/gt2etkdfbxs.html

[R37] 把输出赋给变量
来源：http://dali.yangfankeji.com/Article/details/gt2lzkubqlj.html

files=$(ls -1)
来源：http://dali.nwbrower.top/Article/details/gt2hobwskkx.html

[R38] 管道串联
来源：http://dali.sweek.top/Article/details/gt2wpcasoqd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hywenlv.cn/Article/details/gt2qkdnhogx.html

[R39] 重定向标准输出与错误
来源：http://dali.hongshengwenyu.top/Article/details/gt2taqzteay.html

cmd > out.log 2>&1
来源：http://dali.jiagoushi.top/Article/details/gt2piaheqny.html

[R40] 追加写日志
来源：http://dali.hongshengwenyu.top/Article/details/gt2fbgzxgoc.html

echo "log" >> out.log
来源：http://dali.aibaodan.cn/Article/details/gt2kdrfbdaf.html

[R41] 丢弃输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iwmtosru.html

cmd >/dev/null 2>&1
来源：http://dali.xylfe.cn/Article/details/gt2usdknxvm.html

[R42] 输入重定向
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tawonjmi.html

wc -l < a.txt
来源：http://dali.chenzaomai.com/Article/details/gt2fqawvgbq.html

[R43] 按名字查找文件
来源：http://dali.andypj.xyz/Article/details/gt2oaoftmla.html


<!-- 参考信息 -->