代发 wailian999

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yj20258.top/Article/details/gtsivckqvp.html

);
来源：http://dali.snrcjt.cn/Article/details/gtfuecodfv.html

[Q02] 创建带外键的表
来源：http://dali.havefunace.top/Article/details/gtcmytyjme.html

CREATE TABLE orders (
来源：http://dali.c1oappe.top/Article/details/gtdtajiqkv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yuanzhike.top/Article/details/gtadgykspi.html

user_id INT NOT NULL,
来源：http://dali.cucudq.cn/Article/details/gtiltcgbfe.html

amount DECIMAL(10, 2),
来源：http://dali.bjfxy.top/Article/details/gtpuexovfi.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.nanxinkj.top/Article/details/gtsqxxkoug.html

);
来源：http://dali.sweek.top/Article/details/gtqnszxgyp.html

[Q03] 增加列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdxqkuttx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ybcxt.top/Article/details/gtskfhmknr.html

[Q04] 修改列类型
来源：http://dali.0kj1m.cn/Article/details/gtutvytxxh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yanxiufei.cn/Article/details/gtxbqrnfvo.html

[Q05] 重命名列
来源：http://dali.zycfv.cn/Article/details/gtdrwneohp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.wangshuangyany.cn/Article/details/gtzqnqhafs.html

[Q06] 删除列
来源：http://dali.jqgufenzy.top/Article/details/gtzqdzxlcn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jyoumei.cn/Article/details/gtofxzgjgy.html

[Q07] 删除表
来源：http://dali.guowangkeji.top/Article/details/gtjbqmwump.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jyoumei.cn/Article/details/gtpwawuonp.html

[Q08] 创建普通索引
来源：http://dali.yuanzhike.top/Article/details/gtguicdoau.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hnqzz.top/Article/details/gtggxgmdrf.html

[Q09] 创建唯一索引
来源：http://dali.wangdashe.top/Article/details/gtgkyjhjmd.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hammf.cn/Article/details/gtnffgjhzr.html

[Q10] 插入单行
来源：http://dali.jiagoushi.top/Article/details/gtnxgjuafw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yuxming.cn/Article/details/gtbqzelbom.html

[Q11] 一次插入多行
来源：http://dali.yvedp.cn/Article/details/gtykqgoemy.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.vqdsnc.cn/Article/details/gtcgevtzvi.html

[Q12] 插入后取自增 ID
来源：http://dali.vqdsnc.cn/Article/details/gtilllulns.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.fzhhl.top/Article/details/gtaidgvvkv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.dianchejie.cn/Article/details/gttkajesjj.html

[Q13] 忽略重复插入
来源：http://dali.gaohongyu789.top/Article/details/gtjpdixbiv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.gzhubu.top/Article/details/gtonofbkyw.html

[Q14] 存在则更新（upsert）
来源：http://dali.yangfankeji.com/Article/details/gtpqxncizj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jlsjyb.cn/Article/details/gtunppatkl.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xuanzx.com/Article/details/gterqpchpp.html

[Q15] 查询全部
来源：http://dali.sysykeji.top/Article/details/gtowmnivrg.html

SELECT * FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtftqxctkw.html

[Q16] 查询指定列
来源：http://dali.pycfn.com/Article/details/gtswrpxagr.html

SELECT id, name FROM users;
来源：http://dali.cashguo.top/Article/details/gtuvokowjm.html

[Q17] 条件查询
来源：http://dali.ydzc1.top/Article/details/gtdxtcfwjj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yvedp.cn/Article/details/gtiimvhifk.html

[Q18] 模糊匹配
来源：http://dali.ppjwa.cn/Article/details/gtidmijkyi.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhiwuduotai.top/Article/details/gtdhydxelz.html

[Q19] 范围查询
来源：http://dali.havefunace.top/Article/details/gtpwxidvqu.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.sysykeji.top/Article/details/gttdzydewl.html

[Q20] IN 列表
来源：http://dali.mhx1999.top/Article/details/gtpwulineh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gotoacloud.top/Article/details/gtmoickvtx.html

[Q21] 空值判断
来源：http://dali.c1oappe.top/Article/details/gtzybbbbgu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjtlomnnj.html

[Q22] 排序
来源：http://dali.nanxuanxn.top/Article/details/gttyfyhjbv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfjkikffz.html

[Q23] 分页
来源：http://dali.tianlin.xyz/Article/details/gtrhzwxzmk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jqgfzy.top/Article/details/gtpycqakdm.html

[Q24] 去重
来源：http://dali.vqdsnc.cn/Article/details/gtmjzbvtwq.html

SELECT DISTINCT city FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtikampjhb.html

[Q25] 只取前 N 条
来源：http://dali.0kj1m.cn/Article/details/gtbzjbyvlv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xziqi.cn/Article/details/gtgcdilaag.html

[Q26] 计数
来源：http://dali.aibaodan.cn/Article/details/gtbzolgszc.html

SELECT COUNT(*) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtfdskjozm.html

[Q27] 条件计数
来源：http://dali.c1oappe.top/Article/details/gtjqvlapks.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.redwolf501.top/Article/details/gtdcqgyuec.html

[Q28] 求和与平均
来源：http://dali.zhixingplan.top/Article/details/gtsbbpwzkd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ybcxt.top/Article/details/gtauuxfhlg.html

[Q29] 最大最小值
来源：http://dali.ppjwa.cn/Article/details/gtdfzvqryw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.tanke756.top/Article/details/gtpedcdsqr.html

[Q30] 分组统计
来源：http://dali.yj20258888.top/Article/details/gtvqayblds.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.nanxuanxn.top/Article/details/gtejwzhdwf.html

[Q31] 分组后过滤
来源：http://dali.aibaodan.cn/Article/details/gtgmntrneg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.gogol.net.cn/Article/details/gtcqqzpqfx.html

[Q32] 分组拼接字符串
来源：http://dali.sysykeji.top/Article/details/gtmkplbmgs.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.nwbrower.top/Article/details/gtnckdeipz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.fzhhl.top/Article/details/gtiterdaaw.html

[Q33] 多列分组
来源：http://dali.jqgufenzy.top/Article/details/gtsrsfmbhs.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpemakgtk.html

[Q34] 每组取第一条
来源：http://dali.shangyingyoupin.top/Article/details/gtmjmnqhyp.html

SELECT * FROM (
来源：http://dali.shangyingyoupin.top/Article/details/gtbqdpdwzw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.snrcjt.cn/Article/details/gtupznvpxy.html

) t WHERE rn = 1;
来源：http://dali.yangfankeji.com/Article/details/gtgxqyhbio.html

[Q35] 内连接
来源：http://dali.cucudq.cn/Article/details/gtivlsemnv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xylfe.cn/Article/details/gtlmzizrhw.html

[Q36] 左连接
来源：http://dali.zhiwuduotai.top/Article/details/gtznimmzzi.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ivvv.top/Article/details/gtlvpydwtb.html

[Q37] 右连接
来源：http://dali.yanxiufei.cn/Article/details/gthveerosj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cheryme.top/Article/details/gthkilyone.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yuxming.cn/Article/details/gtaoremozn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.guowangkeji.top/Article/details/gtsqcgorys.html

[Q39] 自连接（查上下级）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsxlhgaen.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.snrcjt.cn/Article/details/gtdvlgfurx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jinqigufen.top/Article/details/gtgseztvga.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jiagoushi.top/Article/details/gtbpvfdhmr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhiwuduotai.top/Article/details/gtghnqfgzt.html

[Q41] 多表连接
来源：http://dali.ybcxt.top/Article/details/gtxocfliba.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.iojbl.cn/Article/details/gtsdsverbm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtutsipotx.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yangfankeji.com/Article/details/gttftaveuw.html

[Q42] 连接条件附加过滤
来源：http://dali.ydzc1.top/Article/details/gttauoetta.html

SELECT u.name, o.amount FROM users u
来源：http://dali.haohaochexian.top/Article/details/gtfugaswvs.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hnxiangtu.top/Article/details/gtkilktcxz.html

[Q43] 标量子查询
来源：http://dali.yonumen.top/Article/details/gtdqrxegkd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtleklcuvd.html

[Q44] IN 子查询
来源：http://dali.xuetiantiany.cn/Article/details/gteatcuumy.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.pengpengdd.cyou/Article/details/gtrkoraoir.html

[Q45] EXISTS 判断存在
来源：http://dali.sxryk.cn/Article/details/gtqkadfrjk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.guowangkeji.top/Article/details/gtrddtdqnc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.smart0.xyz/Article/details/gtmgvsnrpk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.0kj1m.cn/Article/details/gtuhrffgtk.html

[Q47] 与平均值比较
来源：http://dali.xylfe.cn/Article/details/gttwxumcms.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cheryme.top/Article/details/gtryzjeawb.html

[Q48] CTE 公用表表达式
来源：http://dali.yj20258.top/Article/details/gtynzlipez.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shangyingyoupin.top/Article/details/gtihrjtzti.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinqigufen.top/Article/details/gtgvgeoxqb.html

[Q49] 更新单行
来源：http://dali.ydzc1.top/Article/details/gtlygjxoch.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xinyue.icu/Article/details/gtddczllzd.html

[Q50] 批量更新
来源：http://dali.jianghu66.top/Article/details/gtbvffgztk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.gogol.net.cn/Article/details/gtaudbauao.html

[Q51] 用子查询更新
来源：http://dali.jlsjyb.cn/Article/details/gtzinmejfo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.316326.xyz/Article/details/gtzxbjehpn.html

[Q52] 删除指定行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqbngfkaj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ehwqpu.com/Article/details/gtoxozwxjz.html

[Q53] 按条件删除
来源：http://dali.iojbl.cn/Article/details/gtwsldesbi.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.9152youxi.cn/Article/details/gtwwubbfzw.html

[Q54] 清空表
来源：http://dali.xuetiantiany.cn/Article/details/gtksjwwkzr.html

TRUNCATE TABLE logs;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtghkktckm.html

[Q55] 排名（并列占位）
来源：http://dali.smart0.xyz/Article/details/gtmacuptyt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zdqjudy.top/Article/details/gtywcopqku.html

[Q56] 密集排名（并列不占位）
来源：http://dali.mhx1999.top/Article/details/gtncpaznrr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.chenzaomai.com/Article/details/gtbqmjgcyx.html

[Q57] 行号
来源：http://dali.shanyushiyangtech.top/Article/details/gtvxwwbwvf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.smart0.xyz/Article/details/gtgicnbdgq.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gtnkcarkwr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.316326.xyz/Article/details/gtkoqekeyu.html

[Q59] 分组内累计
来源：http://dali.zhongyouzk.top/Article/details/gtpaesywyj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtsdjlbtnm.html

[Q60] 取上一行 / 下一行
来源：http://dali.gotoacloud.top/Article/details/gtidqwhemb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cucudq.cn/Article/details/gtsciqvbia.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gtokuwkcei.html

[Q61] 移动平均
来源：http://dali.jqgufenzy.top/Article/details/gtezagjdan.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gtfkqwnezz.html

[Q62] 分组占比
来源：http://dali.fzhhl.top/Article/details/gtwotjyalg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinqigufen.top/Article/details/gtfhzozsmp.html

[Q63] 开启事务
来源：http://dali.fengsongda.top/Article/details/gtfejggwrq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yongpay.top/Article/details/gtijcozdfz.html

[Q64] 提交事务
来源：http://dali.shangyingyoupin.top/Article/details/gtlyghallk.html

COMMIT;
来源：http://dali.316326.xyz/Article/details/gtyjnfchmz.html

[Q65] 回滚事务
来源：http://dali.zhixingplan.top/Article/details/gtmseyzmgp.html

ROLLBACK;
来源：http://dali.birdmap.top/Article/details/gtexjoauzd.html

[Q66] 行锁查询
来源：http://dali.yuxming.cn/Article/details/gtkpddrqfg.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ivvv.top/Article/details/gtysiatwuz.html

[Q67] 设置隔离级别
来源：http://dali.yj20258.top/Article/details/gtbsifugwc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.tanke756.top/Article/details/gtzetqvulj.html

[Q68] 保存点
来源：http://dali.kuanghao11.cn/Article/details/gtlwuyslme.html

SAVEPOINT sp1;
来源：http://dali.yuxming.cn/Article/details/gtsnxbwjfj.html

ROLLBACK TO sp1;
来源：http://dali.sxryk.cn/Article/details/gtqdnoapth.html

[Q69] 查看执行计划
来源：http://dali.jinghuilouyu.cn/Article/details/gtusqlzpfs.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.havefunace.top/Article/details/gtpicqpozi.html

[Q70] 更新统计信息
来源：http://dali.yuanzhike.top/Article/details/gtnhreddwp.html

ANALYZE TABLE users;
来源：http://dali.andypj.xyz/Article/details/gtssihysif.html

[Q71] 查看建表语句
来源：http://dali.jiagoushi.top/Article/details/gtjqezqtyp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jiagoushi.top/Article/details/gtfnkjrxdr.html

[Q72] 查看索引
来源：http://dali.sxryk.cn/Article/details/gtniijvojl.html

SHOW INDEX FROM users;
来源：http://dali.guannengcc.top/Article/details/gtgkpfgvwp.html

[Q73] 查看表状态
来源：http://dali.yuanzhike.top/Article/details/gtrilnntnl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cqqwz.cn/Article/details/gtccfidxar.html

[Q74] 强制使用索引
来源：http://dali.hywenlv.cn/Article/details/gtymeryatm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.0kj1m.cn/Article/details/gtqyskyhvz.html

[Q75] 日期格式化
来源：http://dali.nanxuanxn.top/Article/details/gtjiqzeuok.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtvfcviuij.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.daxiang520.top/Article/details/gttahrkmbv.html

[Q76] 按天统计
来源：http://dali.daxiang520.top/Article/details/gtpdtfyltc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yj20258.top/Article/details/gtsyernzrg.html

[Q77] 时间加减
来源：http://dali.wangshuangyany.cn/Article/details/gtsvanbljr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.aibaodan.cn/Article/details/gtzhxsaxwe.html

[Q78] 当前时间
来源：http://dali.tianlin.xyz/Article/details/gttyogiboy.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.chenzaomai.com/Article/details/gtloatowqd.html

[Q79] 字符串拼接
来源：http://dali.yuanzhike.top/Article/details/gtecvjytdl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gtbcfrkqtc.html

[Q80] 字符串截取
来源：http://dali.zhoulong.xyz/Article/details/gtnuawzulk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yuxming.cn/Article/details/gtzjsuntqp.html

[Q81] 字符串替换
来源：http://dali.zhengqikj.top/Article/details/gtnfxyqwqu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtiztkceut.html

[Q82] 字符长度与字节长度
来源：http://dali.tanke756.top/Article/details/gtxvnlviro.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yj20258888.top/Article/details/gtleppbwog.html

[Q83] 大小写转换
来源：http://dali.hnqzz.top/Article/details/gtnhobheky.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtboecbbwn.html

[Q84] 去除首尾空格
来源：http://dali.gogol.net.cn/Article/details/gthxzmjyik.html

SELECT TRIM(name) FROM users;
来源：http://dali.xylfe.cn/Article/details/gtjoznzsez.html

[Q85] 数值取整
来源：http://dali.ehwqpu.com/Article/details/gtvsjqzvnf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhiwuduotai.top/Article/details/gtasvvpqvz.html

[Q86] 读取 JSON 字段
来源：http://dali.guowangkeji.top/Article/details/gtkjxjeptj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.guannengcc.top/Article/details/gtuwkfbsbd.html

[Q87] JSON 字段做条件
来源：http://dali.jlsjyb.cn/Article/details/gtolipslmk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xuanzx.com/Article/details/gtuirsiods.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhongyouzk.top/Article/details/gtzkltitmf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hnqzz.top/Article/details/gtygohbzjh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtebiliemn.html

[Q89] 判断表是否存在
来源：http://dali.shangyingyoupin.top/Article/details/gtezvjveuf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yangfankeji.com/Article/details/gtbwdduqko.html

[Q90] 生成序号列
来源：http://dali.shzxlz.cn/Article/details/gtidqzsrte.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinghuilouyu.cn/Article/details/gthfrwbizm.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtarglsmzj.html

R. Bash 专题
来源：http://dali.zhengqikj.top/Article/details/gtkwooseii.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gthbkzsopq.html

[R01] shebang 与严格模式
来源：http://dali.pengpengdd.cyou/Article/details/gtyuikuyql.html

#!/usr/bin/env bash
来源：http://dali.jqgufenzy.top/Article/details/gtbbvloofu.html

set -euo pipefail
来源：http://dali.yangfankeji.com/Article/details/gtvnyqhtzz.html

[R02] 变量赋值与使用
来源：http://dali.nanxuanxn.top/Article/details/gthtmxvbza.html

name="Tom"; echo "$name"
来源：http://dali.fengsongda.top/Article/details/gtmuiqrnaq.html

[R03] 只读变量
来源：http://dali.zdqjudy.top/Article/details/gtmccgiuox.html

readonly PI=3.14
来源：http://dali.cqqwz.cn/Article/details/gtovnkjkbo.html

[R04] 位置参数
来源：http://dali.316326.xyz/Article/details/gtpejmypil.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xuetiantiany.cn/Article/details/gtqkshqwbu.html

[R05] 参数默认值
来源：http://dali.meibo888.top/Article/details/gtpjkkffmc.html

name="${1:-default}"
来源：http://dali.cdnleiting.top/Article/details/gtyzrunzjb.html

[R06] 判断命令是否存在
来源：http://dali.sweek.top/Article/details/gtyngvlqei.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.nanxinkj.top/Article/details/gtearwakka.html

[R07] if 判断文件
来源：http://dali.pengpengdd.cyou/Article/details/gtocgjnzbo.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.guowangkeji.top/Article/details/gtheruecnt.html

[R08] 数值比较
来源：http://dali.meibo888.top/Article/details/gtaabfwzlw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.pycfn.com/Article/details/gtonruwwul.html

[R09] 字符串比较
来源：http://dali.feifeiyinyue.top/Article/details/gtcsqtjhei.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.dianchejie.cn/Article/details/gtzqmwzwft.html

[R10] 正则匹配
来源：http://dali.yangfankeji.com/Article/details/gtxvoqukxk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hammf.cn/Article/details/gtfpxqbidc.html

[R11] case 多分支
来源：http://dali.jqgfzy.top/Article/details/gtjslzcaiw.html

case "$1" in
来源：http://dali.jiagoushi.top/Article/details/gtgqytjfyz.html

start) echo "启动" ;;
来源：http://dali.fengsongda.top/Article/details/gthhqzjhgj.html

stop)  echo "停止" ;;
来源：http://dali.bjfxy.top/Article/details/gtizqtzjkc.html

*)     echo "未知命令" ;;
来源：http://dali.zhengqikj.top/Article/details/gtghmlgbxr.html

esac
来源：http://dali.yueranfly.top/Article/details/gtqqlzyojm.html

[R12] for 遍历文件
来源：http://dali.jinqigfzy.top/Article/details/gthvubtubv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.smart0.xyz/Article/details/gtspqzfdxc.html

[R13] for 计数循环
来源：http://dali.ybcxt.top/Article/details/gtimidkvnd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzrxzpijq.html

[R14] C 风格 for
来源：http://dali.havefunace.top/Article/details/gtwdjdcdcd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.tianlin.xyz/Article/details/gtxwttmpjv.html

[R15] while 逐行读文件
来源：http://dali.yangfankeji.com/Article/details/gtmofiffep.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yuxming.cn/Article/details/gtihqvtfsh.html

[R16] until 等待条件
来源：http://dali.xinyue.icu/Article/details/gtwjphfmtn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jlsjyb.cn/Article/details/gtitccvkmf.html

[R17] 数组定义与取值
来源：http://dali.pycfn.com/Article/details/gtmnbkzlhp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xinyue.icu/Article/details/gtophfgtdz.html

[R18] 遍历数组
来源：http://dali.quarkkingdee.top/Article/details/gtckzdskcn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yueranfly.top/Article/details/gtpzsnoxcr.html

[R19] 数组长度
来源：http://dali.yuanzhike.top/Article/details/gtegewynzz.html

echo "${#arr[@]}"
来源：http://dali.zhiwuduotai.top/Article/details/gtknbrawwq.html

[R20] 关联数组（字典）
来源：http://dali.sweek.top/Article/details/gtfqdqselt.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.fzhhl.top/Article/details/gtgojpthrj.html

[R21] 字符串长度
来源：http://dali.shzxlz.cn/Article/details/gtumdpndxc.html

echo "${#s}"
来源：http://dali.fzhhl.top/Article/details/gtkkksqgeq.html

[R22] 截取子串
来源：http://dali.daria6918.cn/Article/details/gtuqsbpxzp.html

echo "${s:0:5}"
来源：http://dali.yanxiufei.cn/Article/details/gthhkyhzmm.html

[R23] 字符串替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnpjosmbp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.vqdsnc.cn/Article/details/gtcvgnncqt.html

[R24] 大小写转换
来源：http://dali.pengpengdd.cyou/Article/details/gtacyfipim.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.fengsongda.top/Article/details/gttfinddll.html

[R25] 去后缀 / 去前缀
来源：http://dali.cucudq.cn/Article/details/gtbwnckkha.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.redwolf501.top/Article/details/gtxmrcmmaj.html

[R26] 命令替换
来源：http://dali.zhongyouzk.top/Article/details/gtcotogoxa.html

now=$(date +%F); echo "$now"
来源：http://dali.chenlongwang.top/Article/details/gtwqjwlzqx.html

[R27] 算术展开
来源：http://dali.hnxiangtu.top/Article/details/gtwpdwzmqv.html

echo $((1 + 2 * 3))
来源：http://dali.snrcjt.cn/Article/details/gtlkyfntqs.html

[R28] 浮点运算
来源：http://dali.cashguo.top/Article/details/gtzuxdcvhb.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinghuilouyu.cn/Article/details/gtifwaqees.html

[R29] 定义函数
来源：http://dali.bjfxy.top/Article/details/gtffuzksiq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.feifeiyinyue.top/Article/details/gtfljatevi.html

[R30] 函数返回状态码
来源：http://dali.ppjwa.cn/Article/details/gtepxgxsra.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yuanzhike.top/Article/details/gtuyarxjav.html

[R31] 局部变量
来源：http://dali.chenzaomai.com/Article/details/gtxotyulzw.html

f() { local x=1; echo "$x"; }
来源：http://dali.daxiang520.top/Article/details/gtegaiwfzq.html

[R32] 参数个数校验
来源：http://dali.birdmap.top/Article/details/gtjxaebxut.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.wangshuangyany.cn/Article/details/gtdjpjrlts.html

[R33] 捕获错误并提示行号
来源：http://dali.xinyue.icu/Article/details/gtideddmiw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.andypj.xyz/Article/details/gtlyqstxzf.html

[R34] 退出时清理
来源：http://dali.yonumen.top/Article/details/gtvzcbetjp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj20258.top/Article/details/gtrctbzqvl.html

[R35] 后台执行并等待
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsrpikcpv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.chenzaomai.com/Article/details/gtnkaacmss.html

[R36] 并发执行多个任务
来源：http://dali.ybcxt.top/Article/details/gtjujzrkce.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xuanzx.com/Article/details/gtotjxspti.html

[R37] 把输出赋给变量
来源：http://dali.wangshuangyany.cn/Article/details/gtaalflrla.html

files=$(ls -1)
来源：http://dali.ehwqpu.com/Article/details/gtqspggikm.html

[R38] 管道串联
来源：http://dali.tian-w.cn/Article/details/gtknejviem.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhoulong.xyz/Article/details/gtzhsfsogq.html

[R39] 重定向标准输出与错误
来源：http://dali.jiagoushi.top/Article/details/gtqnwikunt.html

cmd > out.log 2>&1
来源：http://dali.zhiwuduotai.top/Article/details/gtdlhozruh.html

[R40] 追加写日志
来源：http://dali.vqdsnc.cn/Article/details/gtllnxvnty.html

echo "log" >> out.log
来源：http://dali.hongshengwenyu.top/Article/details/gtkethauve.html

[R41] 丢弃输出
来源：http://dali.chenzaomai.com/Article/details/gtffeuvxdp.html

cmd >/dev/null 2>&1
来源：http://dali.yonumen.top/Article/details/gteddiefaz.html

[R42] 输入重定向
来源：http://dali.9152youxi.cn/Article/details/gtsimoaxdj.html

wc -l < a.txt
来源：http://dali.sweek.top/Article/details/gtcywvdnzl.html

[R43] 按名字查找文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtcpbxywof.html

find . -name "*.log" -type f
来源：http://dali.cheryme.top/Article/details/gtktbyzlwg.html

[R44] 按修改时间查找
来源：http://dali.sysykeji.top/Article/details/gtzrggjxfu.html

find . -mtime -7 -type f
来源：http://dali.haohaochexian.top/Article/details/gtumwgnifc.html

[R45] 批量删除
来源：http://dali.0kj1m.cn/Article/details/gtekwvajzv.html

find . -name "*.tmp" -delete
来源：http://dali.zdqjudy.top/Article/details/gtdetmghjj.html

[R46] 递归替换文件内容
来源：http://dali.guannengcc.top/Article/details/gtwbztzswe.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jyoumei.cn/Article/details/gtpsfhizga.html

[R47] sed 单行替换
来源：http://dali.cdnleiting.top/Article/details/gtvznikbdh.html


<!-- 参考信息 -->