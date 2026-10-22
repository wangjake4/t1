代发 wailian999

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.andypj.xyz/Article/details/gt2eqvutonu.html

user_id INT NOT NULL,
来源：http://dali.pycfn.com/Article/details/gt2axdnlxwm.html

amount DECIMAL(10, 2),
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gpxztyss.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jianghu66.top/Article/details/gt2jgrblzjn.html

);
来源：http://dali.gogol.net.cn/Article/details/gt2tcnhzdfi.html

[Q03] 增加列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mrglwooa.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hnqzz.top/Article/details/gt2qkoexayy.html

[Q04] 修改列类型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ayhdpaez.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cdnleiting.top/Article/details/gt2ybridtzw.html

[Q05] 重命名列
来源：http://dali.shangyingyoupin.top/Article/details/gt2loeooskm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhixingplan.top/Article/details/gt2whjpbkzr.html

[Q06] 删除列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kkehksnm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.0kj1m.cn/Article/details/gt2iljpawjy.html

[Q07] 删除表
来源：http://dali.zdqjudy.top/Article/details/gt2ktkvvulz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yj20258888.top/Article/details/gt2drfxunnr.html

[Q08] 创建普通索引
来源：http://dali.xuetiantiany.cn/Article/details/gt2fhlnqkzt.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xziqi.cn/Article/details/gt2dbbnwszs.html

[Q09] 创建唯一索引
来源：http://dali.gzhubu.top/Article/details/gt2pvhmsoqn.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.meibo888.top/Article/details/gt2knqoyrhy.html

[Q10] 插入单行
来源：http://dali.iojbl.cn/Article/details/gt2onlpbzbx.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hnqzz.top/Article/details/gt2tksdragg.html

[Q11] 一次插入多行
来源：http://dali.zhiwuduotai.top/Article/details/gt2uucfvhmw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yuanzhike.top/Article/details/gt2ljartwto.html

[Q12] 插入后取自增 ID
来源：http://dali.xylfe.cn/Article/details/gt2rtlhvtbe.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gzhubu.top/Article/details/gt2bpatkecu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zycfv.cn/Article/details/gt2mdhotskz.html

[Q13] 忽略重复插入
来源：http://dali.nwbrower.top/Article/details/gt2crogahfb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yongpay.top/Article/details/gt2lbbxouiz.html

[Q14] 存在则更新（upsert）
来源：http://dali.pengpengdd.cyou/Article/details/gt2uyhltfsi.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gzhubu.top/Article/details/gt2dlcitktu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.feifeiyinyue.top/Article/details/gt2xenpncis.html

[Q15] 查询全部
来源：http://dali.ppjwa.cn/Article/details/gt2hgsizrwd.html

SELECT * FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2vtxbqokm.html

[Q16] 查询指定列
来源：http://dali.cashguo.top/Article/details/gt2jutunkup.html

SELECT id, name FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2djrbxvjc.html

[Q17] 条件查询
来源：http://dali.yongpay.top/Article/details/gt2vguldnhe.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.quarkkingdee.top/Article/details/gt2sslrxaah.html

[Q18] 模糊匹配
来源：http://dali.yuxming.cn/Article/details/gt2cbfcvmva.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.gogol.net.cn/Article/details/gt2otuzoroh.html

[Q19] 范围查询
来源：http://dali.dianchejie.cn/Article/details/gt2iuwgyhut.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.chenjidiqi.icu/Article/details/gt2esiikxfc.html

[Q20] IN 列表
来源：http://dali.xuanzx.com/Article/details/gt2qfwtdixr.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.andypj.xyz/Article/details/gt2agzatlra.html

[Q21] 空值判断
来源：http://dali.birdmap.top/Article/details/gt2typepxkv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.andypj.xyz/Article/details/gt2krvllqyp.html

[Q22] 排序
来源：http://dali.svipenyu.cn/Article/details/gt2kxzrdenb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hnqzz.top/Article/details/gt2tiwliujk.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2fqonnchw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yonumen.top/Article/details/gt2stabetzn.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2rusblymz.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2hnhmddqi.html

[Q25] 只取前 N 条
来源：http://dali.xuanzx.com/Article/details/gt2mgnfcken.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yangfankeji.com/Article/details/gt2nbpvjanq.html

[Q26] 计数
来源：http://dali.jqgufenzy.top/Article/details/gt2plfvochy.html

SELECT COUNT(*) FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2nwueyjhg.html

[Q27] 条件计数
来源：http://dali.birdmap.top/Article/details/gt2lgnaiyid.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.tanke756.top/Article/details/gt2eymewbhq.html

[Q28] 求和与平均
来源：http://dali.hnqzz.top/Article/details/gt2nrqztwlu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gt2zvnqlmfv.html

[Q29] 最大最小值
来源：http://dali.yvedp.cn/Article/details/gt2mgxrfkej.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2ozzhpvsz.html

[Q30] 分组统计
来源：http://dali.pengpengdd.cyou/Article/details/gt2wnjzfqjo.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shzxlz.cn/Article/details/gt2fjqtduce.html

[Q31] 分组后过滤
来源：http://dali.gotoacloud.top/Article/details/gt2eehsjpeq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.nwbrower.top/Article/details/gt2sfzhitgv.html

[Q32] 分组拼接字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2oypqsgau.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hruifbuj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.tian-w.cn/Article/details/gt2bwlizpyu.html

[Q33] 多列分组
来源：http://dali.meibo888.top/Article/details/gt2owklcmkd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yuxming.cn/Article/details/gt2xsnlxwhl.html

[Q34] 每组取第一条
来源：http://dali.andypj.xyz/Article/details/gt2dudurdne.html

SELECT * FROM (
来源：http://dali.daxiang520.top/Article/details/gt2fxzzalii.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zdqjudy.top/Article/details/gt2ahaxgccy.html

) t WHERE rn = 1;
来源：http://dali.yongpay.top/Article/details/gt2xdgswxxi.html

[Q35] 内连接
来源：http://dali.shangyingyoupin.top/Article/details/gt2ozmzdrli.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yangfankeji.com/Article/details/gt2udvpurky.html

[Q36] 左连接
来源：http://dali.hywenlv.cn/Article/details/gt2nehbgjqq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.aibaodan.cn/Article/details/gt2fpndkjna.html

[Q37] 右连接
来源：http://dali.wangshuangyany.cn/Article/details/gt2gnbiyjaf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yuxming.cn/Article/details/gt2zhitjbde.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.fzhhl.top/Article/details/gt2wzkigphd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zdqjudy.top/Article/details/gt2xdokwsgg.html

[Q39] 自连接（查上下级）
来源：http://dali.ppjwa.cn/Article/details/gt2zlqegccb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jqgfzy.top/Article/details/gt2cbnlzyxu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hammf.cn/Article/details/gt2kscilsrd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhongyouzk.top/Article/details/gt2whxvpsyu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.smart0.xyz/Article/details/gt2nuvtcutf.html

[Q41] 多表连接
来源：http://dali.shanyushiyangtech.top/Article/details/gt2huamikov.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ybcxt.top/Article/details/gt2hvwoylmq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2prswbenv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jinqigufen.top/Article/details/gt2pgjcdmeo.html

[Q42] 连接条件附加过滤
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2alxuciye.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhongyouzk.top/Article/details/gt2najclick.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.gogol.net.cn/Article/details/gt2dywzjwff.html

[Q43] 标量子查询
来源：http://dali.andypj.xyz/Article/details/gt2izptmfgo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.0kj1m.cn/Article/details/gt2gztzazsl.html

[Q44] IN 子查询
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lmhbxyqz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.daria6918.cn/Article/details/gt2yteubjdp.html

[Q45] EXISTS 判断存在
来源：http://dali.haohaochexian.top/Article/details/gt2vpbceiyg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yuanzhike.top/Article/details/gt2rwtcdigw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.iojbl.cn/Article/details/gt2tnyofmwx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cashguo.top/Article/details/gt2irpjvjgk.html

[Q47] 与平均值比较
来源：http://dali.hongshengwenyu.top/Article/details/gt2alkfndav.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.0kj1m.cn/Article/details/gt2hzjhelwk.html

[Q48] CTE 公用表表达式
来源：http://dali.smart0.xyz/Article/details/gt2mxotflmh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.dianchejie.cn/Article/details/gt2elrrxall.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.iojbl.cn/Article/details/gt2ckdznsqt.html

[Q49] 更新单行
来源：http://dali.yanxiufei.cn/Article/details/gt2gakjzrlb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.sweek.top/Article/details/gt2ucltgnsq.html

[Q50] 批量更新
来源：http://dali.daxiang520.top/Article/details/gt2oijdjiww.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zdqjudy.top/Article/details/gt2vzncwawi.html

[Q51] 用子查询更新
来源：http://dali.yonumen.top/Article/details/gt2llnndnhv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.tanke756.top/Article/details/gt2muedjeca.html

[Q52] 删除指定行
来源：http://dali.xuetiantiany.cn/Article/details/gt2ishywdle.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zycfv.cn/Article/details/gt2bwxljkrv.html

[Q53] 按条件删除
来源：http://dali.snrcjt.cn/Article/details/gt2xlydwqux.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xuanzx.com/Article/details/gt2todguwan.html

[Q54] 清空表
来源：http://dali.chenjidiqi.icu/Article/details/gt2zcbyirjo.html

TRUNCATE TABLE logs;
来源：http://dali.fzhhl.top/Article/details/gt2uxntpjyi.html

[Q55] 排名（并列占位）
来源：http://dali.cdnleiting.top/Article/details/gt2nhiqmngi.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jlsjyb.cn/Article/details/gt2juesnpaj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.gogol.net.cn/Article/details/gt2trkzwayu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yuanzhike.top/Article/details/gt2scfzpbnc.html

[Q57] 行号
来源：http://dali.nanxinkj.top/Article/details/gt2gvjbkcfk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2zsqqwhme.html

[Q58] 累计求和
来源：http://dali.chenzaomai.com/Article/details/gt2ltrakdlu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gt2iojuinqn.html

[Q59] 分组内累计
来源：http://dali.zhixingplan.top/Article/details/gt2xoctakaz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gt2luchdalk.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhiwuduotai.top/Article/details/gt2abffiban.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhixingplan.top/Article/details/gt2hyfzwqrc.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sysykeji.top/Article/details/gt2pmzwtrga.html

[Q61] 移动平均
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ofkqiozs.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gt2gzofqjmz.html

[Q62] 分组占比
来源：http://dali.havefunace.top/Article/details/gt2tiywkoaq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xziqi.cn/Article/details/gt2gjfnzuuy.html

[Q63] 开启事务
来源：http://dali.cashguo.top/Article/details/gt2tttbzdko.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cashguo.top/Article/details/gt2peviuade.html

[Q64] 提交事务
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2koazinld.html

COMMIT;
来源：http://dali.hywenlv.cn/Article/details/gt2hvsvmdap.html

[Q65] 回滚事务
来源：http://dali.ydzc1.top/Article/details/gt2hkfyxnlr.html

ROLLBACK;
来源：http://dali.wangdashe.top/Article/details/gt2faanrbwt.html

[Q66] 行锁查询
来源：http://dali.nwbrower.top/Article/details/gt2tubsrdjq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.havefunace.top/Article/details/gt2kqtsqwcn.html

[Q67] 设置隔离级别
来源：http://dali.nanxinkj.top/Article/details/gt2caieqmhu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.daria6918.cn/Article/details/gt2qyqwfxct.html

[Q68] 保存点
来源：http://dali.jinqigfzy.top/Article/details/gt2fpxeomgs.html

SAVEPOINT sp1;
来源：http://dali.sufxvd.cn/Article/details/gt2sxuoumtw.html

ROLLBACK TO sp1;
来源：http://dali.cdnleiting.top/Article/details/gt2vbfzcigk.html

[Q69] 查看执行计划
来源：http://dali.hywenlv.cn/Article/details/gt2wretkbwl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinqigfzy.top/Article/details/gt2fklvvesg.html

[Q70] 更新统计信息
来源：http://dali.yuanzhike.top/Article/details/gt2rcllflmt.html

ANALYZE TABLE users;
来源：http://dali.svipenyu.cn/Article/details/gt2htskiwdb.html

[Q71] 查看建表语句
来源：http://dali.aizwys.cn/Article/details/gt2osarecfy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenzaomai.com/Article/details/gt2wtkrxvsb.html

[Q72] 查看索引
来源：http://dali.jlsjyb.cn/Article/details/gt2ewocamcl.html

SHOW INDEX FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2lqqmzrad.html

[Q73] 查看表状态
来源：http://dali.andypj.xyz/Article/details/gt2eocgncqc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.chenlongwang.top/Article/details/gt2kyyxqjkn.html

[Q74] 强制使用索引
来源：http://dali.wangdashe.top/Article/details/gt2jgecoykw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.redwolf501.top/Article/details/gt2gipsmmxh.html

[Q75] 日期格式化
来源：http://dali.chenzaomai.com/Article/details/gt2yiiyroun.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yj20258.top/Article/details/gt2rovxxtqx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ybcxt.top/Article/details/gt2npyuasur.html

[Q76] 按天统计
来源：http://dali.andypj.xyz/Article/details/gt2rgxvjdln.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ivvv.top/Article/details/gt2qpkvxjyu.html

[Q77] 时间加减
来源：http://dali.havefunace.top/Article/details/gt2bzpcnmbi.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinqigufen.top/Article/details/gt2znqmyvdm.html

[Q78] 当前时间
来源：http://dali.chenlongwang.top/Article/details/gt2dzebixjf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jiagoushi.top/Article/details/gt2ysrnmcrg.html

[Q79] 字符串拼接
来源：http://dali.bjfxy.top/Article/details/gt2plwkigqx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhixingplan.top/Article/details/gt2xvidvepk.html

[Q80] 字符串截取
来源：http://dali.nanxuanxn.top/Article/details/gt2pjdujksv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2vpchgcht.html

[Q81] 字符串替换
来源：http://dali.jinqigufen.top/Article/details/gt2mngmosqw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2dlqhpttc.html

[Q82] 字符长度与字节长度
来源：http://dali.sweek.top/Article/details/gt2oacsnaqw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gbxaafnx.html

[Q83] 大小写转换
来源：http://dali.shzxlz.cn/Article/details/gt2ncjqtvnk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.havefunace.top/Article/details/gt2ghyzcgmm.html

[Q84] 去除首尾空格
来源：http://dali.nanxuanxn.top/Article/details/gt2eviwcowi.html

SELECT TRIM(name) FROM users;
来源：http://dali.jianghu66.top/Article/details/gt2fnzquluu.html

[Q85] 数值取整
来源：http://dali.fengsongda.top/Article/details/gt2mokcbmzf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yongpay.top/Article/details/gt2kiisxjnv.html

[Q86] 读取 JSON 字段
来源：http://dali.c1oappe.top/Article/details/gt2szxuoaqa.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjzaxdg.html

[Q87] JSON 字段做条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qsmpiktm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.andypj.xyz/Article/details/gt2jasitozu.html

[Q88] 行转列（条件聚合）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2emxladxt.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.havefunace.top/Article/details/gt2jffldwbu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2hlltkroi.html

[Q89] 判断表是否存在
来源：http://dali.andypj.xyz/Article/details/gt2khzckdxq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.wangshuangyany.cn/Article/details/gt2oxuzdvbc.html

[Q90] 生成序号列
来源：http://dali.cucudq.cn/Article/details/gt2czrowoyo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.nwbrower.top/Article/details/gt2gmqkamrw.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2obgxpeht.html

R. Bash 专题
来源：http://dali.quarkkingdee.top/Article/details/gt2vpsuyjdq.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2queqjkqe.html

[R01] shebang 与严格模式
来源：http://dali.aizwys.cn/Article/details/gt2oiwrxshr.html

#!/usr/bin/env bash
来源：http://dali.yuanzhike.top/Article/details/gt2bsdjnbpi.html

set -euo pipefail
来源：http://dali.ppjwa.cn/Article/details/gt2hktsitgk.html

[R02] 变量赋值与使用
来源：http://dali.yuanzhike.top/Article/details/gt2xqraadga.html

name="Tom"; echo "$name"
来源：http://dali.xinyue.icu/Article/details/gt2mdktcfba.html

[R03] 只读变量
来源：http://dali.chenzaomai.com/Article/details/gt2idgzrjgz.html

readonly PI=3.14
来源：http://dali.yueranfly.top/Article/details/gt2qracvetb.html

[R04] 位置参数
来源：http://dali.jyoumei.cn/Article/details/gt2prxilvle.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cqqwz.cn/Article/details/gt2yjaknjgp.html

[R05] 参数默认值
来源：http://dali.yj202588.top/Article/details/gt2dkrozisa.html

name="${1:-default}"
来源：http://dali.andypj.xyz/Article/details/gt2ucsvcwjp.html

[R06] 判断命令是否存在
来源：http://dali.zycfv.cn/Article/details/gt2qbabhrwy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.daxiang520.top/Article/details/gt2kokrmjdo.html

[R07] if 判断文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zlfovxcq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.tanke756.top/Article/details/gt2kkdiruvt.html

[R08] 数值比较
来源：http://dali.shuidangran.top/Article/details/gt2myzyslkm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.tanke756.top/Article/details/gt2bmiwowgp.html

[R09] 字符串比较
来源：http://dali.cqqwz.cn/Article/details/gt2qmhjwfgi.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gt2kxwoxlnk.html

[R10] 正则匹配
来源：http://dali.jqgufenzy.top/Article/details/gt2kqosjdpv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.nwbrower.top/Article/details/gt2xjhmfzrf.html

[R11] case 多分支
来源：http://dali.cdnleiting.top/Article/details/gt2thwyhhmd.html

case "$1" in
来源：http://dali.9152youxi.cn/Article/details/gt2xtgttayb.html

start) echo "启动" ;;
来源：http://dali.yongpay.top/Article/details/gt2cgyjzdnz.html

stop)  echo "停止" ;;
来源：http://dali.ydzc1.top/Article/details/gt2irwxmyau.html

*)     echo "未知命令" ;;
来源：http://dali.gzhubu.top/Article/details/gt2ggqrtzne.html

esac
来源：http://dali.gzhubu.top/Article/details/gt2avsojafb.html

[R12] for 遍历文件
来源：http://dali.sweek.top/Article/details/gt2aetxsqms.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jianghu66.top/Article/details/gt2dwqbheah.html

[R13] for 计数循环
来源：http://dali.hysaishi.cn/Article/details/gt2entbyvfc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ivvv.top/Article/details/gt2jyjuttwl.html

[R14] C 风格 for
来源：http://dali.yuanzhike.top/Article/details/gt2robqjinp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zdqjudy.top/Article/details/gt2ohwlowjy.html

[R15] while 逐行读文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2lasidivj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.0kj1m.cn/Article/details/gt2dqmaqcra.html

[R16] until 等待条件
来源：http://dali.xuetiantiany.cn/Article/details/gt2lxftrapn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pmlfpblo.html

[R17] 数组定义与取值
来源：http://dali.havefunace.top/Article/details/gt2ekjtdpqe.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kpiaodvj.html

[R18] 遍历数组
来源：http://dali.ppjwa.cn/Article/details/gt2nhhyghaq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.nanxinkj.top/Article/details/gt2kyfrywfk.html

[R19] 数组长度
来源：http://dali.yangfankeji.com/Article/details/gt2zgwsutaz.html

echo "${#arr[@]}"
来源：http://dali.yvedp.cn/Article/details/gt2briddhzd.html

[R20] 关联数组（字典）
来源：http://dali.cucudq.cn/Article/details/gt2dnvpbtwl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.andypj.xyz/Article/details/gt2licmugzg.html

[R21] 字符串长度
来源：http://dali.dashuyun.cn/Article/details/gt2clcsmevn.html

echo "${#s}"
来源：http://dali.chenlongwang.top/Article/details/gt2tluxboju.html

[R22] 截取子串
来源：http://dali.jqgufenzy.top/Article/details/gt2yzlahtwz.html

echo "${s:0:5}"
来源：http://dali.jiagoushi.top/Article/details/gt2mjskydst.html

[R23] 字符串替换
来源：http://dali.daria6918.cn/Article/details/gt2ykmhwomi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.fzhhl.top/Article/details/gt2uqqqzxww.html

[R24] 大小写转换
来源：http://dali.xylfe.cn/Article/details/gt2wrazayzg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xuanzx.com/Article/details/gt2neojfibb.html

[R25] 去后缀 / 去前缀
来源：http://dali.yangfankeji.com/Article/details/gt2cxwzjabb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hywenlv.cn/Article/details/gt2cfxqgffe.html

[R26] 命令替换
来源：http://dali.vqdsnc.cn/Article/details/gt2bjykzitd.html

now=$(date +%F); echo "$now"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jgrtsaoh.html

[R27] 算术展开
来源：http://dali.vqdsnc.cn/Article/details/gt2cfsybdee.html

echo $((1 + 2 * 3))
来源：http://dali.haohaochexian.top/Article/details/gt2gfclorfz.html

[R28] 浮点运算
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kyyzczsj.html

echo "scale=2; 10/3" | bc
来源：http://dali.aizwys.cn/Article/details/gt2kyoqbsnb.html

[R29] 定义函数
来源：http://dali.yj20258.top/Article/details/gt2yzjajewu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yongpay.top/Article/details/gt2ydfembpk.html

[R30] 函数返回状态码
来源：http://dali.hfpthk.cn/Article/details/gt2yjsoagsw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinqigfzy.top/Article/details/gt2bjrybrwx.html

[R31] 局部变量
来源：http://dali.pycfn.com/Article/details/gt2unzmcehf.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2zkfyswpb.html

[R32] 参数个数校验
来源：http://dali.sweek.top/Article/details/gt2beypkujr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.haohaochexian.top/Article/details/gt2srwiqaut.html

[R33] 捕获错误并提示行号
来源：http://dali.ydzc1.top/Article/details/gt2ettgaehn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2crpqznka.html

[R34] 退出时清理
来源：http://dali.redwolf501.top/Article/details/gt2jtbnyhac.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.9152youxi.cn/Article/details/gt2lmsxtjoo.html

[R35] 后台执行并等待
来源：http://dali.yuanzhike.top/Article/details/gt2gzwgvvfj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ppjwa.cn/Article/details/gt2stkttbhw.html

[R36] 并发执行多个任务
来源：http://dali.jinqigfzy.top/Article/details/gt2nflbvdex.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.iojbl.cn/Article/details/gt2dsqimzqg.html

[R37] 把输出赋给变量
来源：http://dali.hammf.cn/Article/details/gt2xsdhmslb.html

files=$(ls -1)
来源：http://dali.cdnleiting.top/Article/details/gt2pwiljjmg.html

[R38] 管道串联
来源：http://dali.yuanzhike.top/Article/details/gt2lwunoamy.html

cat a.txt | grep -i error | wc -l
来源：http://dali.svipenyu.cn/Article/details/gt2invnktdl.html

[R39] 重定向标准输出与错误
来源：http://dali.hammf.cn/Article/details/gt2fmfgcwao.html

cmd > out.log 2>&1
来源：http://dali.cucudq.cn/Article/details/gt2kcemlflu.html

[R40] 追加写日志
来源：http://dali.jiagoushi.top/Article/details/gt2dmpdfvmd.html

echo "log" >> out.log
来源：http://dali.ybcxt.top/Article/details/gt2bogprpde.html

[R41] 丢弃输出
来源：http://dali.jiagoushi.top/Article/details/gt2izutthpe.html

cmd >/dev/null 2>&1
来源：http://dali.gogol.net.cn/Article/details/gt2kjcznish.html

[R42] 输入重定向
来源：http://dali.iojbl.cn/Article/details/gt2mdhvcpis.html

wc -l < a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gt2rzujtjft.html

[R43] 按名字查找文件
来源：http://dali.iojbl.cn/Article/details/gt2ibxvuaae.html

find . -name "*.log" -type f
来源：http://dali.gogol.net.cn/Article/details/gt2wgtpsanl.html

[R44] 按修改时间查找
来源：http://dali.xinyue.icu/Article/details/gt2xvcntcvq.html

find . -mtime -7 -type f
来源：http://dali.sysykeji.top/Article/details/gt2kkcxhcmq.html

[R45] 批量删除
来源：http://dali.meibo888.top/Article/details/gt2gdcicdlz.html

find . -name "*.tmp" -delete
来源：http://dali.xziqi.cn/Article/details/gt2acpmhjsh.html

[R46] 递归替换文件内容
来源：http://dali.sysykeji.top/Article/details/gt2vmtjekom.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.guowangkeji.top/Article/details/gt2qsnoksvt.html

[R47] sed 单行替换
来源：http://dali.yj20258888.top/Article/details/gt2zxlidzsu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xziqi.cn/Article/details/gt2pxffhlun.html

[R48] awk 取指定列
来源：http://dali.nanxuanxn.top/Article/details/gt2uowalwsx.html

awk '{print $1, $3}' a.txt
来源：http://dali.mhx1999.top/Article/details/gt2zrlwmlkj.html

[R49] awk 带条件
来源：http://dali.shzxlz.cn/Article/details/gt2xsznvisw.html


<!-- 参考信息 -->