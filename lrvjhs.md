代发 wailian999

);
来源：http://dali.chenzaomai.com/Article/details/gt2tnrrackh.html

[Q03] 增加列
来源：http://dali.cucudq.cn/Article/details/gt2gentoatq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.bjfxy.top/Article/details/gt2tpctwsdk.html

[Q04] 修改列类型
来源：http://dali.cashguo.top/Article/details/gt2oppzdsqh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhoulong.xyz/Article/details/gt2fbhsczmq.html

[Q05] 重命名列
来源：http://dali.dashuyun.cn/Article/details/gt2gkhsqstv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.nanxuanxn.top/Article/details/gt2efwhaccl.html

[Q06] 删除列
来源：http://dali.zhiwuduotai.top/Article/details/gt2jvffezqq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ydzc1.top/Article/details/gt2mplhgrmv.html

[Q07] 删除表
来源：http://dali.ybcxt.top/Article/details/gt2xnidvleq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.haohaochexian.top/Article/details/gt2hudfeekt.html

[Q08] 创建普通索引
来源：http://dali.smart0.xyz/Article/details/gt2tdckxwdh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lswzeuek.html

[Q09] 创建唯一索引
来源：http://dali.xinyue.icu/Article/details/gt2qyombrgg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhongyouzk.top/Article/details/gt2alzcexqf.html

[Q10] 插入单行
来源：http://dali.birdmap.top/Article/details/gt2wqfndzcv.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cqqwz.cn/Article/details/gt2xsdwkgcb.html

[Q11] 一次插入多行
来源：http://dali.guannengcc.top/Article/details/gt2frqohlfh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shuidangran.top/Article/details/gt2ezvmkoll.html

[Q12] 插入后取自增 ID
来源：http://dali.jlsjyb.cn/Article/details/gt2pvomhekt.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gaohongyu789.top/Article/details/gt2whtlxkqa.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xziqi.cn/Article/details/gt2dwunfyzb.html

[Q13] 忽略重复插入
来源：http://dali.hywenlv.cn/Article/details/gt2mmhxrqni.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cheryme.top/Article/details/gt2krlxfwls.html

[Q14] 存在则更新（upsert）
来源：http://dali.nanxuanxn.top/Article/details/gt2mlymnzdn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xuetiantiany.cn/Article/details/gt2yyasajnk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.guowangkeji.top/Article/details/gt2zftpfxtp.html

[Q15] 查询全部
来源：http://dali.cucudq.cn/Article/details/gt2lemjgvtf.html

SELECT * FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2aspiycto.html

[Q16] 查询指定列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rwrzyeig.html

SELECT id, name FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2xtrlqwpg.html

[Q17] 条件查询
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wabtoiyi.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.kuanghao11.cn/Article/details/gt2ytossqhe.html

[Q18] 模糊匹配
来源：http://dali.jianghu66.top/Article/details/gt2pbduqkhv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hammf.cn/Article/details/gt2rhwbexvd.html

[Q19] 范围查询
来源：http://dali.sufxvd.cn/Article/details/gt2rdlhoxuu.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.vqdsnc.cn/Article/details/gt2dosswqyv.html

[Q20] IN 列表
来源：http://dali.hfpthk.cn/Article/details/gt2bviklkgz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.9152youxi.cn/Article/details/gt2xnyjyovk.html

[Q21] 空值判断
来源：http://dali.daxiang520.top/Article/details/gt2vtlqgidj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zycfv.cn/Article/details/gt2mpnppybp.html

[Q22] 排序
来源：http://dali.c1oappe.top/Article/details/gt2seuoztxg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cqqwz.cn/Article/details/gt2imhcttso.html

[Q23] 分页
来源：http://dali.hnqzz.top/Article/details/gt2ujtakgfh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shangyingyoupin.top/Article/details/gt2dcmrykld.html

[Q24] 去重
来源：http://dali.ppjwa.cn/Article/details/gt2tilxviir.html

SELECT DISTINCT city FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2rgmcytyh.html

[Q25] 只取前 N 条
来源：http://dali.ydzc1.top/Article/details/gt2sefjbhry.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jqgfzy.top/Article/details/gt2zalamtry.html

[Q26] 计数
来源：http://dali.yueranfly.top/Article/details/gt2andpiyrh.html

SELECT COUNT(*) FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2sjsqvuma.html

[Q27] 条件计数
来源：http://dali.redwolf501.top/Article/details/gt2itpgzewr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2ikjhokkz.html

[Q28] 求和与平均
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eusmfjje.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gt2eczsbswz.html

[Q29] 最大最小值
来源：http://dali.birdmap.top/Article/details/gt2ifyctucp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2zdqgeymn.html

[Q30] 分组统计
来源：http://dali.yanxiufei.cn/Article/details/gt2xbionhur.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.nwbrower.top/Article/details/gt2jwrlkvrh.html

[Q31] 分组后过滤
来源：http://dali.hysaishi.cn/Article/details/gt2efimohcl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.andypj.xyz/Article/details/gt2ggxofxea.html

[Q32] 分组拼接字符串
来源：http://dali.jlsjyb.cn/Article/details/gt2dqitsoho.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yangfankeji.com/Article/details/gt2jqgazmwn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.snrcjt.cn/Article/details/gt2aoxkmpdf.html

[Q33] 多列分组
来源：http://dali.fengsongda.top/Article/details/gt2izyuotmd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.chenzaomai.com/Article/details/gt2xuxjsylq.html

[Q34] 每组取第一条
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xdyedxlu.html

SELECT * FROM (
来源：http://dali.cqqwz.cn/Article/details/gt2hclhkbpn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.feifeiyinyue.top/Article/details/gt2rkilvzjt.html

) t WHERE rn = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gt2ozxuxilr.html

[Q35] 内连接
来源：http://dali.daria6918.cn/Article/details/gt2jtvuoqvm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.tanke756.top/Article/details/gt2fuqrpalr.html

[Q36] 左连接
来源：http://dali.chenzaomai.com/Article/details/gt2bdfhflpn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hongshengwenyu.top/Article/details/gt2qepfprzr.html

[Q37] 右连接
来源：http://dali.andypj.xyz/Article/details/gt2tfuvgtmp.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.guowangkeji.top/Article/details/gt2xigicjpy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yongpay.top/Article/details/gt2vfnbayqp.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hammf.cn/Article/details/gt2cfhvyvfj.html

[Q39] 自连接（查上下级）
来源：http://dali.yuanzhike.top/Article/details/gt2ljcyhogf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinqigfzy.top/Article/details/gt2jahpvrgk.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hywenlv.cn/Article/details/gt2gbumnquh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hongshengwenyu.top/Article/details/gt2cjagurrn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.9152youxi.cn/Article/details/gt2vsaebrgq.html

[Q41] 多表连接
来源：http://dali.yuanzhike.top/Article/details/gt2jxdakjga.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinqigufen.top/Article/details/gt2riaxveux.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zycfv.cn/Article/details/gt2mbuxjtqu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sufxvd.cn/Article/details/gt2eyjliiic.html

[Q42] 连接条件附加过滤
来源：http://dali.aizwys.cn/Article/details/gt2acojpkpm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.bjfxy.top/Article/details/gt2mlokqidv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cqqwz.cn/Article/details/gt2zvufwunr.html

[Q43] 标量子查询
来源：http://dali.jlsjyb.cn/Article/details/gt2aoyycxut.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jlnrbnta.html

[Q44] IN 子查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uklvnbdo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uorkbtfr.html

[Q45] EXISTS 判断存在
来源：http://dali.tianlin.xyz/Article/details/gt2ozmwizrn.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ehwqpu.com/Article/details/gt2tmfavooj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.feifeiyinyue.top/Article/details/gt2xyidchid.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ivvv.top/Article/details/gt2feqdqxve.html

[Q47] 与平均值比较
来源：http://dali.fengsongda.top/Article/details/gt2orvpkfvz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.pengpengdd.cyou/Article/details/gt2lgeyltzc.html

[Q48] CTE 公用表表达式
来源：http://dali.tianlin.xyz/Article/details/gt2yxmqmnuf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.svipenyu.cn/Article/details/gt2ohptaunb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xinyue.icu/Article/details/gt2fspmaaxh.html

[Q49] 更新单行
来源：http://dali.guowangkeji.top/Article/details/gt2xriqijrg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.andypj.xyz/Article/details/gt2vyfeljzg.html

[Q50] 批量更新
来源：http://dali.ivvv.top/Article/details/gt2xqnmcwjc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.316326.xyz/Article/details/gt2pdwqdpyu.html

[Q51] 用子查询更新
来源：http://dali.tanke756.top/Article/details/gt2awcseijq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xuanzx.com/Article/details/gt2ujfguadf.html

[Q52] 删除指定行
来源：http://dali.zhongyouzk.top/Article/details/gt2dchgaeas.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sqsejfrc.html

[Q53] 按条件删除
来源：http://dali.shzxlz.cn/Article/details/gt2pzaymwfj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jianghu66.top/Article/details/gt2xwbseenz.html

[Q54] 清空表
来源：http://dali.xziqi.cn/Article/details/gt2wjjupnpe.html

TRUNCATE TABLE logs;
来源：http://dali.haohaochexian.top/Article/details/gt2dmpwjlmr.html

[Q55] 排名（并列占位）
来源：http://dali.shangyingyoupin.top/Article/details/gt2qylnmmpe.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jlsjyb.cn/Article/details/gt2urgxgsvx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bubpotqm.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.316326.xyz/Article/details/gt2irrdkxpf.html

[Q57] 行号
来源：http://dali.redwolf501.top/Article/details/gt2fwmayzgs.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.sweek.top/Article/details/gt2dedemnrx.html

[Q58] 累计求和
来源：http://dali.tian-w.cn/Article/details/gt2pxyabapq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.guannengcc.top/Article/details/gt2cxcmlhmy.html

[Q59] 分组内累计
来源：http://dali.daria6918.cn/Article/details/gt2rzkfgjtn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.c1oappe.top/Article/details/gt2tkessbyj.html

[Q60] 取上一行 / 下一行
来源：http://dali.zdqjudy.top/Article/details/gt2qlrfajni.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hnxiangtu.top/Article/details/gt2smedfwpm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hammf.cn/Article/details/gt2izwxpovz.html

[Q61] 移动平均
来源：http://dali.yvedp.cn/Article/details/gt2ongkixfi.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gt2mmoxzisv.html

[Q62] 分组占比
来源：http://dali.jinqigfzy.top/Article/details/gt2dqitlrqp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.daxiang520.top/Article/details/gt2peyglrhz.html

[Q63] 开启事务
来源：http://dali.mhx1999.top/Article/details/gt2uzxtbjsd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hnxiangtu.top/Article/details/gt2otgomzwr.html

[Q64] 提交事务
来源：http://dali.shangyingyoupin.top/Article/details/gt2hkbxxffy.html

COMMIT;
来源：http://dali.sysykeji.top/Article/details/gt2lbzrurwy.html

[Q65] 回滚事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2edxqjqgv.html

ROLLBACK;
来源：http://dali.gogol.net.cn/Article/details/gt2dxejuaso.html

[Q66] 行锁查询
来源：http://dali.hnxiangtu.top/Article/details/gt2kroolzbq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bbbygfih.html

[Q67] 设置隔离级别
来源：http://dali.gaohongyu789.top/Article/details/gt2dqcgrqxh.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shangyingyoupin.top/Article/details/gt2qpcvmglz.html

[Q68] 保存点
来源：http://dali.chenlongwang.top/Article/details/gt2bsptfsvj.html

SAVEPOINT sp1;
来源：http://dali.yj202588.top/Article/details/gt2epjgfhgt.html

ROLLBACK TO sp1;
来源：http://dali.jyoumei.cn/Article/details/gt2wjcuhumy.html

[Q69] 查看执行计划
来源：http://dali.hnxiangtu.top/Article/details/gt2vsunsdof.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hfpthk.cn/Article/details/gt2zbjxrroa.html

[Q70] 更新统计信息
来源：http://dali.316326.xyz/Article/details/gt2sfzgzjat.html

ANALYZE TABLE users;
来源：http://dali.guowangkeji.top/Article/details/gt2cjldwyhq.html

[Q71] 查看建表语句
来源：http://dali.shangyingyoupin.top/Article/details/gt2muuzhoae.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yuxming.cn/Article/details/gt2edzulxjr.html

[Q72] 查看索引
来源：http://dali.yanxiufei.cn/Article/details/gt2fbpyepjf.html

SHOW INDEX FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2jfqrmwaz.html

[Q73] 查看表状态
来源：http://dali.wangdashe.top/Article/details/gt2hhoclenc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhixingplan.top/Article/details/gt2alrgaeti.html

[Q74] 强制使用索引
来源：http://dali.shangyingyoupin.top/Article/details/gt2vrobaekg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qhjogkhp.html

[Q75] 日期格式化
来源：http://dali.jianghu66.top/Article/details/gt2jufncuyg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gt2pxlmmjck.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.9152youxi.cn/Article/details/gt2pcxlalbo.html

[Q76] 按天统计
来源：http://dali.wangdashe.top/Article/details/gt2dqrdwpyo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.daxiang520.top/Article/details/gt2mbdgiqoi.html

[Q77] 时间加减
来源：http://dali.9152youxi.cn/Article/details/gt2fvultkki.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yangfankeji.com/Article/details/gt2hwnonniq.html

[Q78] 当前时间
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yhqggnxo.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.chenjidiqi.icu/Article/details/gt2fvbimmhf.html

[Q79] 字符串拼接
来源：http://dali.redwolf501.top/Article/details/gt2dgvyyfhp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhengqikj.top/Article/details/gt2fmgzytzy.html

[Q80] 字符串截取
来源：http://dali.chenjidiqi.icu/Article/details/gt2tqrahilg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2uigtvccn.html

[Q81] 字符串替换
来源：http://dali.yongpay.top/Article/details/gt2wsythnal.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.tian-w.cn/Article/details/gt2npikvkjx.html

[Q82] 字符长度与字节长度
来源：http://dali.sufxvd.cn/Article/details/gt2osuxkwyn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2wxrtvmdn.html

[Q83] 大小写转换
来源：http://dali.kuanghao11.cn/Article/details/gt2ulyayjhi.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2bewihipi.html

[Q84] 去除首尾空格
来源：http://dali.cucudq.cn/Article/details/gt2lpqarxmp.html

SELECT TRIM(name) FROM users;
来源：http://dali.sxryk.cn/Article/details/gt2afaaqrzc.html

[Q85] 数值取整
来源：http://dali.316326.xyz/Article/details/gt2sruwvngd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yvedp.cn/Article/details/gt2kxbprbfh.html

[Q86] 读取 JSON 字段
来源：http://dali.yuanzhike.top/Article/details/gt2mhbexeqj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.havefunace.top/Article/details/gt2zynwckdo.html

[Q87] JSON 字段做条件
来源：http://dali.c1oappe.top/Article/details/gt2kpcbqabu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ylrxtvmm.html

[Q88] 行转列（条件聚合）
来源：http://dali.jinqigufen.top/Article/details/gt2bsujzmfi.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yvedp.cn/Article/details/gt2vtlgoegr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yongpay.top/Article/details/gt2kpoxbaho.html

[Q89] 判断表是否存在
来源：http://dali.jqgfzy.top/Article/details/gt2xottgtih.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tepwtzjs.html

[Q90] 生成序号列
来源：http://dali.bjfxy.top/Article/details/gt2wtwfqvyx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hysaishi.cn/Article/details/gt2tkwymzdh.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2lgabwolh.html

R. Bash 专题
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mlzrarak.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2kmihruss.html

[R01] shebang 与严格模式
来源：http://dali.xuetiantiany.cn/Article/details/gt2qjpfwcej.html

#!/usr/bin/env bash
来源：http://dali.zdqjudy.top/Article/details/gt2wvlnmubm.html

set -euo pipefail
来源：http://dali.9152youxi.cn/Article/details/gt2mdsqvdum.html

[R02] 变量赋值与使用
来源：http://dali.guowangkeji.top/Article/details/gt2cldkbxol.html

name="Tom"; echo "$name"
来源：http://dali.tianlin.xyz/Article/details/gt2xqqyzwxw.html

[R03] 只读变量
来源：http://dali.jlsjyb.cn/Article/details/gt2hpmwmijs.html

readonly PI=3.14
来源：http://dali.ivvv.top/Article/details/gt2kpxkqfnq.html

[R04] 位置参数
来源：http://dali.gaohongyu789.top/Article/details/gt2nmpugukd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.wangdashe.top/Article/details/gt2uuzinysh.html

[R05] 参数默认值
来源：http://dali.cheryme.top/Article/details/gt2spgfjmrt.html

name="${1:-default}"
来源：http://dali.yj202588.top/Article/details/gt2jfjokzhy.html

[R06] 判断命令是否存在
来源：http://dali.9152youxi.cn/Article/details/gt2rvbiwfvg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.smart0.xyz/Article/details/gt2ugnujknp.html

[R07] if 判断文件
来源：http://dali.yuanzhike.top/Article/details/gt2dnfmkdxo.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.tian-w.cn/Article/details/gt2uiuynsck.html

[R08] 数值比较
来源：http://dali.iojbl.cn/Article/details/gt2dnncohwx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gaohongyu789.top/Article/details/gt2dmjlafzt.html

[R09] 字符串比较
来源：http://dali.xziqi.cn/Article/details/gt2jmnhjiiz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj20258.top/Article/details/gt2efclixjw.html

[R10] 正则匹配
来源：http://dali.cheryme.top/Article/details/gt2lklhldpf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.c1oappe.top/Article/details/gt2eupziivc.html

[R11] case 多分支
来源：http://dali.sxryk.cn/Article/details/gt2jqipxrkj.html

case "$1" in
来源：http://dali.guannengcc.top/Article/details/gt2hzsqgmex.html

start) echo "启动" ;;
来源：http://dali.pycfn.com/Article/details/gt2iuulscrp.html

stop)  echo "停止" ;;
来源：http://dali.gzhubu.top/Article/details/gt2xywgirpy.html

*)     echo "未知命令" ;;
来源：http://dali.hnxiangtu.top/Article/details/gt2klbkivjp.html

esac
来源：http://dali.bjfxy.top/Article/details/gt2edrcckag.html

[R12] for 遍历文件
来源：http://dali.iojbl.cn/Article/details/gt2badqwyjw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.pycfn.com/Article/details/gt2uekbmgbe.html

[R13] for 计数循环
来源：http://dali.haohaochexian.top/Article/details/gt2noepyhmq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.nanxuanxn.top/Article/details/gt2kvrhlzbq.html

[R14] C 风格 for
来源：http://dali.shangyingyoupin.top/Article/details/gt2arrlnfkf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.daxiang520.top/Article/details/gt2fpwoxbiw.html

[R15] while 逐行读文件
来源：http://dali.yj20258888.top/Article/details/gt2sqjkszeb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.dashuyun.cn/Article/details/gt2vbepvkdp.html

[R16] until 等待条件
来源：http://dali.jyoumei.cn/Article/details/gt2gyhizlbj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hongshengwenyu.top/Article/details/gt2olddbskp.html

[R17] 数组定义与取值
来源：http://dali.yongpay.top/Article/details/gt2lrouhrek.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cheryme.top/Article/details/gt2uvdqbdbb.html

[R18] 遍历数组
来源：http://dali.jinqigufen.top/Article/details/gt2ubuoactu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.haohaochexian.top/Article/details/gt2ninzumlw.html

[R19] 数组长度
来源：http://dali.gogol.net.cn/Article/details/gt2raguanub.html

echo "${#arr[@]}"
来源：http://dali.fzhhl.top/Article/details/gt2wwtyevio.html

[R20] 关联数组（字典）
来源：http://dali.chenzaomai.com/Article/details/gt2zdlqcpbj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shuidangran.top/Article/details/gt2qoodrguu.html

[R21] 字符串长度
来源：http://dali.yanxiufei.cn/Article/details/gt2falkxmnx.html

echo "${#s}"
来源：http://dali.yvedp.cn/Article/details/gt2tgreqdfx.html

[R22] 截取子串
来源：http://dali.zhongyouzk.top/Article/details/gt2nnmypmin.html

echo "${s:0:5}"
来源：http://dali.gzhubu.top/Article/details/gt2opajvyoh.html

[R23] 字符串替换
来源：http://dali.zhixingplan.top/Article/details/gt2xxbjvuyg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jqgufenzy.top/Article/details/gt2yjjfodqt.html

[R24] 大小写转换
来源：http://dali.meibo888.top/Article/details/gt2iqatrcdd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.havefunace.top/Article/details/gt2jfiegrmf.html

[R25] 去后缀 / 去前缀
来源：http://dali.0kj1m.cn/Article/details/gt2uxyuzawn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sweek.top/Article/details/gt2zxcaitwq.html

[R26] 命令替换
来源：http://dali.yuanzhike.top/Article/details/gt2tbkkhitl.html

now=$(date +%F); echo "$now"
来源：http://dali.gaohongyu789.top/Article/details/gt2xbksoyfi.html

[R27] 算术展开
来源：http://dali.shangyingyoupin.top/Article/details/gt2zcgtojkk.html

echo $((1 + 2 * 3))
来源：http://dali.yuxming.cn/Article/details/gt2ujwzwlfu.html

[R28] 浮点运算
来源：http://dali.ppjwa.cn/Article/details/gt2kdepkzqf.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2obtzoyqd.html

[R29] 定义函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2astevxmr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.tian-w.cn/Article/details/gt2neiaozfk.html

[R30] 函数返回状态码
来源：http://dali.kuanghao11.cn/Article/details/gt2dtdxjzzz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cucudq.cn/Article/details/gt2ehwousje.html

[R31] 局部变量
来源：http://dali.yj20258888.top/Article/details/gt2jtvtbcad.html

f() { local x=1; echo "$x"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2gxicxhcx.html

[R32] 参数个数校验
来源：http://dali.feifeiyinyue.top/Article/details/gt2jyybeaca.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.birdmap.top/Article/details/gt2lwwxbmvb.html

[R33] 捕获错误并提示行号
来源：http://dali.sufxvd.cn/Article/details/gt2lyuvgygu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jinqigfzy.top/Article/details/gt2eiwcurqp.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2cqtwqkjq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhengqikj.top/Article/details/gt2tuyouyfx.html

[R35] 后台执行并等待
来源：http://dali.ppjwa.cn/Article/details/gt2vxlgugbv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.chenlongwang.top/Article/details/gt2prvuzbtg.html

[R36] 并发执行多个任务
来源：http://dali.daxiang520.top/Article/details/gt2dqmoxxek.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.sufxvd.cn/Article/details/gt2ecmhluxy.html

[R37] 把输出赋给变量
来源：http://dali.xuetiantiany.cn/Article/details/gt2dpqnecdf.html

files=$(ls -1)
来源：http://dali.shuidangran.top/Article/details/gt2xlhwptmk.html

[R38] 管道串联
来源：http://dali.fengsongda.top/Article/details/gt2ewjbwafs.html

cat a.txt | grep -i error | wc -l
来源：http://dali.svipenyu.cn/Article/details/gt2iuffcgve.html

[R39] 重定向标准输出与错误
来源：http://dali.yanxiufei.cn/Article/details/gt2mlsuixwv.html

cmd > out.log 2>&1
来源：http://dali.zhengqikj.top/Article/details/gt2ptbpwctv.html

[R40] 追加写日志
来源：http://dali.ppjwa.cn/Article/details/gt2cxkeqxer.html

echo "log" >> out.log
来源：http://dali.tianlin.xyz/Article/details/gt2yogmtzwv.html

[R41] 丢弃输出
来源：http://dali.ivvv.top/Article/details/gt2cwjqwwls.html

cmd >/dev/null 2>&1
来源：http://dali.vqdsnc.cn/Article/details/gt2jpwnojil.html

[R42] 输入重定向
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jrgdyert.html

wc -l < a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gt2rgtbzsls.html

[R43] 按名字查找文件
来源：http://dali.cucudq.cn/Article/details/gt2mhwzifds.html

find . -name "*.log" -type f
来源：http://dali.meibo888.top/Article/details/gt2kcogcrtx.html

[R44] 按修改时间查找
来源：http://dali.cucudq.cn/Article/details/gt2mktglfwi.html

find . -mtime -7 -type f
来源：http://dali.yuxming.cn/Article/details/gt2jhdipmkv.html

[R45] 批量删除
来源：http://dali.ehwqpu.com/Article/details/gt2mtewjwda.html

find . -name "*.tmp" -delete
来源：http://dali.nanxuanxn.top/Article/details/gt2gaxtdzgl.html

[R46] 递归替换文件内容
来源：http://dali.aizwys.cn/Article/details/gt2rbfigrqi.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.tanke756.top/Article/details/gt2lubuahqz.html

[R47] sed 单行替换
来源：http://dali.daxiang520.top/Article/details/gt2zszakqwb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.316326.xyz/Article/details/gt2rmubssma.html

[R48] awk 取指定列
来源：http://dali.vqdsnc.cn/Article/details/gt2rjmqfvkq.html

awk '{print $1, $3}' a.txt
来源：http://dali.hnqzz.top/Article/details/gt2ftclvoew.html

[R49] awk 带条件
来源：http://dali.jinqigfzy.top/Article/details/gt2rzuntohk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shzxlz.cn/Article/details/gt2tngpzqku.html

[R50] awk 求和
来源：http://dali.havefunace.top/Article/details/gt2byyedgds.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hhaernlo.html

[R51] 排序去重取前几
来源：http://dali.cqqwz.cn/Article/details/gt2zbvhkhlg.html


<!-- 参考信息 -->