代发 wailian999

CREATE TABLE users (
来源：http://dali.yuanzhike.top/Article/details/gtcpofgkwr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daxiang520.top/Article/details/gtbfaopqsb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yuxming.cn/Article/details/gtfyceqvbb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jinghuilouyu.cn/Article/details/gtkwuqygnm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinyuanbaomall.cn/Article/details/gtorwvmiji.html

);
来源：http://dali.nanxinkj.top/Article/details/gtokrefdsy.html

[Q02] 创建带外键的表
来源：http://dali.cdnleiting.top/Article/details/gtxegtlinv.html

CREATE TABLE orders (
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtysqyvqet.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fengsongda.top/Article/details/gtpuwzeuxg.html

user_id INT NOT NULL,
来源：http://dali.316326.xyz/Article/details/gtgezamcfx.html

amount DECIMAL(10, 2),
来源：http://dali.fzhhl.top/Article/details/gtgtcifyco.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hywenlv.cn/Article/details/gtwktzztfp.html

);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyrtwynxw.html

[Q03] 增加列
来源：http://dali.jiagoushi.top/Article/details/gttmgshmsw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sufxvd.cn/Article/details/gtxhmborbv.html

[Q04] 修改列类型
来源：http://dali.kuanghao11.cn/Article/details/gtwjdoofee.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xuetiantiany.cn/Article/details/gtbnpmncum.html

[Q05] 重命名列
来源：http://dali.shangyingyoupin.top/Article/details/gtwbzzrrfx.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jqgfzy.top/Article/details/gthmwrpqau.html

[Q06] 删除列
来源：http://dali.daria6918.cn/Article/details/gtmlirqafn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yuanzhike.top/Article/details/gtlxgjojfp.html

[Q07] 删除表
来源：http://dali.hnqzz.top/Article/details/gtwyzlocni.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sysykeji.top/Article/details/gtdykvraap.html

[Q08] 创建普通索引
来源：http://dali.iojbl.cn/Article/details/gtfjnahuov.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.wangshuangyany.cn/Article/details/gtoxhjnsor.html

[Q09] 创建唯一索引
来源：http://dali.svipenyu.cn/Article/details/gtazqmcxnn.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.sxryk.cn/Article/details/gtvgdzimpc.html

[Q10] 插入单行
来源：http://dali.yj20258.top/Article/details/gtvroownsn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.fzhhl.top/Article/details/gtlhtwpkkz.html

[Q11] 一次插入多行
来源：http://dali.chenlongwang.top/Article/details/gtwgcyrbvm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yj20258.top/Article/details/gtgnhctthr.html

[Q12] 插入后取自增 ID
来源：http://dali.vqdsnc.cn/Article/details/gtpirttfcl.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hnxiangtu.top/Article/details/gtmdobcgpq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinqigfzy.top/Article/details/gtclroebkb.html

[Q13] 忽略重复插入
来源：http://dali.gzhubu.top/Article/details/gtsqhrcirp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xylfe.cn/Article/details/gtpskqnnef.html

[Q14] 存在则更新（upsert）
来源：http://dali.xuetiantiany.cn/Article/details/gtazytfemp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhongyouzk.top/Article/details/gtaseqzbmh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.dashuyun.cn/Article/details/gtmfpjyexr.html

[Q15] 查询全部
来源：http://dali.chenzaomai.com/Article/details/gtvqvqkwjk.html

SELECT * FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtuphhjpnv.html

[Q16] 查询指定列
来源：http://dali.gogol.net.cn/Article/details/gtekvaddez.html

SELECT id, name FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtztdijzsp.html

[Q17] 条件查询
来源：http://dali.ehwqpu.com/Article/details/gthakwxjrt.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jlsjyb.cn/Article/details/gtjqfilgrf.html

[Q18] 模糊匹配
来源：http://dali.birdmap.top/Article/details/gtliskbhnu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.aizwys.cn/Article/details/gtpdxesuwl.html

[Q19] 范围查询
来源：http://dali.kuanghao11.cn/Article/details/gtfemnkyii.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.redwolf501.top/Article/details/gtbncufxkc.html

[Q20] IN 列表
来源：http://dali.gotoacloud.top/Article/details/gtarhlbguk.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.dashuyun.cn/Article/details/gtyuacytuk.html

[Q21] 空值判断
来源：http://dali.aizwys.cn/Article/details/gteyjerirn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hnqzz.top/Article/details/gtxighbqyk.html

[Q22] 排序
来源：http://dali.yueranfly.top/Article/details/gttctpjqfw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzepukrgm.html

[Q23] 分页
来源：http://dali.pengpengdd.cyou/Article/details/gtzvsvcspl.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.guannengcc.top/Article/details/gtmsphqkiu.html

[Q24] 去重
来源：http://dali.cucudq.cn/Article/details/gtbssganrn.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtmzesppmw.html

[Q25] 只取前 N 条
来源：http://dali.0kj1m.cn/Article/details/gtjpmmiohr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.haohaochexian.top/Article/details/gtegedwbjl.html

[Q26] 计数
来源：http://dali.mhx1999.top/Article/details/gtudyfjgxw.html

SELECT COUNT(*) FROM users;
来源：http://dali.cucudq.cn/Article/details/gtnhmzbdiw.html

[Q27] 条件计数
来源：http://dali.redwolf501.top/Article/details/gtnllmhnwg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtlrbutskx.html

[Q28] 求和与平均
来源：http://dali.daxiang520.top/Article/details/gtptruugqo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gtovmtvahl.html

[Q29] 最大最小值
来源：http://dali.xylfe.cn/Article/details/gtvqnetpvu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtgotmipkq.html

[Q30] 分组统计
来源：http://dali.zdqjudy.top/Article/details/gtmtfdaocp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.9152youxi.cn/Article/details/gtqralkzzu.html

[Q31] 分组后过滤
来源：http://dali.yvedp.cn/Article/details/gtsbzmxjhy.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinqigfzy.top/Article/details/gtnyqgpkio.html

[Q32] 分组拼接字符串
来源：http://dali.redwolf501.top/Article/details/gtngfniugy.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hnxiangtu.top/Article/details/gtfbgiehrb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.gzhubu.top/Article/details/gtkmkxddju.html

[Q33] 多列分组
来源：http://dali.yueranfly.top/Article/details/gtafzymlqm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ydzc1.top/Article/details/gtcufoazib.html

[Q34] 每组取第一条
来源：http://dali.hnxiangtu.top/Article/details/gtolnmbnmo.html

SELECT * FROM (
来源：http://dali.xinyue.icu/Article/details/gtltmimbzk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zycfv.cn/Article/details/gtmsqtszfc.html

) t WHERE rn = 1;
来源：http://dali.gzhubu.top/Article/details/gtmzjtrguu.html

[Q35] 内连接
来源：http://dali.svipenyu.cn/Article/details/gtiwlmfqop.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.guowangkeji.top/Article/details/gthknotxwh.html

[Q36] 左连接
来源：http://dali.iojbl.cn/Article/details/gtqxyyrcaq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.dashuyun.cn/Article/details/gtgpvowcak.html

[Q37] 右连接
来源：http://dali.cashguo.top/Article/details/gteevhqbdv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jiagoushi.top/Article/details/gttgsctagl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.dashuyun.cn/Article/details/gtjaduwags.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yanxiufei.cn/Article/details/gtckwnofib.html

[Q39] 自连接（查上下级）
来源：http://dali.guowangkeji.top/Article/details/gtsgjcjosr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.nwbrower.top/Article/details/gtryhnvewt.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.bjfxy.top/Article/details/gtjgsihysc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.birdmap.top/Article/details/gtlfbickfm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jinqigfzy.top/Article/details/gtsjyfdvqp.html

[Q41] 多表连接
来源：http://dali.gotoacloud.top/Article/details/gttvwvxylc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.andypj.xyz/Article/details/gtiegkagrk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yj20258.top/Article/details/gttsohdjdp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ydzc1.top/Article/details/gtpnotqoxb.html

[Q42] 连接条件附加过滤
来源：http://dali.jlsjyb.cn/Article/details/gtmnzmvhcb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ppjwa.cn/Article/details/gtghvwdkpm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xuanzx.com/Article/details/gtspyucbmv.html

[Q43] 标量子查询
来源：http://dali.daria6918.cn/Article/details/gtbotniskw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.daria6918.cn/Article/details/gtdyhbcrue.html

[Q44] IN 子查询
来源：http://dali.hnxiangtu.top/Article/details/gtoqoebcmn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yvedp.cn/Article/details/gtvzvnespj.html

[Q45] EXISTS 判断存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpayweqtc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sysykeji.top/Article/details/gtooypynau.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hfpthk.cn/Article/details/gtwwrivulw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258888.top/Article/details/gtrzhfehmv.html

[Q47] 与平均值比较
来源：http://dali.cashguo.top/Article/details/gtyxultdnt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.dianchejie.cn/Article/details/gtrtylhfxx.html

[Q48] CTE 公用表表达式
来源：http://dali.jiagoushi.top/Article/details/gtnrjjzrwm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ppjwa.cn/Article/details/gtasneylmu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.meibo888.top/Article/details/gtzhjqbljo.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gtjhdgofhs.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.gzhubu.top/Article/details/gtvplynaxa.html

[Q50] 批量更新
来源：http://dali.chenlongwang.top/Article/details/gtohqeello.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yj20258888.top/Article/details/gtnprybshs.html

[Q51] 用子查询更新
来源：http://dali.gogol.net.cn/Article/details/gtcipvcben.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yonumen.top/Article/details/gtpqojsrdd.html

[Q52] 删除指定行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuhhiiihm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yj20258888.top/Article/details/gtdkbqjuqx.html

[Q53] 按条件删除
来源：http://dali.xuetiantiany.cn/Article/details/gtqkabzfzu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.haohaochexian.top/Article/details/gtmrrutkir.html

[Q54] 清空表
来源：http://dali.ydzc1.top/Article/details/gtkfhmrjeg.html

TRUNCATE TABLE logs;
来源：http://dali.316326.xyz/Article/details/gtfpsdcbqz.html

[Q55] 排名（并列占位）
来源：http://dali.316326.xyz/Article/details/gtveosimjy.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yj202588.top/Article/details/gttuztnynd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xziqi.cn/Article/details/gtkxklrngq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yueranfly.top/Article/details/gtgrecefvt.html

[Q57] 行号
来源：http://dali.gotoacloud.top/Article/details/gtbomadxcn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hywenlv.cn/Article/details/gttkexmpjj.html

[Q58] 累计求和
来源：http://dali.tian-w.cn/Article/details/gtpxqzxjfd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.fengsongda.top/Article/details/gtllvbbimt.html

[Q59] 分组内累计
来源：http://dali.yongpay.top/Article/details/gtejqekjyh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.andypj.xyz/Article/details/gtwiqjnspd.html

[Q60] 取上一行 / 下一行
来源：http://dali.cucudq.cn/Article/details/gtorvjtuqs.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.nanxinkj.top/Article/details/gtohnghruy.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtsnywktac.html

[Q61] 移动平均
来源：http://dali.shzxlz.cn/Article/details/gtviptklfg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.tian-w.cn/Article/details/gtcpynmupd.html

[Q62] 分组占比
来源：http://dali.gogol.net.cn/Article/details/gtysnrptil.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gtfbygslff.html

[Q63] 开启事务
来源：http://dali.zycfv.cn/Article/details/gteficvpqm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.haohaochexian.top/Article/details/gtxboavsjp.html

[Q64] 提交事务
来源：http://dali.cucudq.cn/Article/details/gtxhinqnze.html

COMMIT;
来源：http://dali.zhongyouzk.top/Article/details/gtlyqzgqjk.html

[Q65] 回滚事务
来源：http://dali.redwolf501.top/Article/details/gtbylcwroj.html

ROLLBACK;
来源：http://dali.jlsjyb.cn/Article/details/gtnjhwxoyt.html

[Q66] 行锁查询
来源：http://dali.quarkkingdee.top/Article/details/gtnhwiofwa.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.nanxinkj.top/Article/details/gtvtxynqdn.html

[Q67] 设置隔离级别
来源：http://dali.vqdsnc.cn/Article/details/gtckxkgbzo.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.daria6918.cn/Article/details/gtlfnkjwbp.html

[Q68] 保存点
来源：http://dali.chenzaomai.com/Article/details/gtlzkgtbie.html

SAVEPOINT sp1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnyiqfxkd.html

ROLLBACK TO sp1;
来源：http://dali.aizwys.cn/Article/details/gtkukaahwl.html

[Q69] 查看执行计划
来源：http://dali.yuanzhike.top/Article/details/gtjszgxzht.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cheryme.top/Article/details/gtzehyvvuj.html

[Q70] 更新统计信息
来源：http://dali.0kj1m.cn/Article/details/gtdukynjzz.html

ANALYZE TABLE users;
来源：http://dali.guowangkeji.top/Article/details/gtczvsxfmc.html

[Q71] 查看建表语句
来源：http://dali.svipenyu.cn/Article/details/gtmhycujhk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.haohaochexian.top/Article/details/gtpddkyetp.html

[Q72] 查看索引
来源：http://dali.jyoumei.cn/Article/details/gtuihwffxx.html

SHOW INDEX FROM users;
来源：http://dali.zycfv.cn/Article/details/gtatpkabzy.html

[Q73] 查看表状态
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxqsapqnz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.tanke756.top/Article/details/gtelgwbisr.html

[Q74] 强制使用索引
来源：http://dali.yuanzhike.top/Article/details/gtrrmbxfcg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.quarkkingdee.top/Article/details/gtmufdifvz.html

[Q75] 日期格式化
来源：http://dali.sysykeji.top/Article/details/gtjcrtsvqc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtsoogfikv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sweek.top/Article/details/gtaregicdv.html

[Q76] 按天统计
来源：http://dali.kuanghao11.cn/Article/details/gtlxckycih.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yuxming.cn/Article/details/gtnqrzjwjn.html

[Q77] 时间加减
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdboplhui.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ybcxt.top/Article/details/gtpkcewzmq.html

[Q78] 当前时间
来源：http://dali.jqgfzy.top/Article/details/gtdxpsutyv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.kuanghao11.cn/Article/details/gtwayzmzmw.html

[Q79] 字符串拼接
来源：http://dali.wangdashe.top/Article/details/gtiwmipkhi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ywan-chungtsiang.top/Article/details/gtphxcijxz.html

[Q80] 字符串截取
来源：http://dali.vqdsnc.cn/Article/details/gtesirgvud.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shuidangran.top/Article/details/gtbttjlacj.html

[Q81] 字符串替换
来源：http://dali.bjfxy.top/Article/details/gtdvnnoake.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtrfkqeozd.html

[Q82] 字符长度与字节长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtnjvzrdue.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zycfv.cn/Article/details/gtzugnwskf.html

[Q83] 大小写转换
来源：http://dali.shangyingyoupin.top/Article/details/gtxrwjwdim.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtoldjjgxn.html

[Q84] 去除首尾空格
来源：http://dali.ppjwa.cn/Article/details/gtsvtizlkc.html

SELECT TRIM(name) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtyyfqmwlh.html

[Q85] 数值取整
来源：http://dali.fengsongda.top/Article/details/gthebpnvlc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ppjwa.cn/Article/details/gtedqlewvh.html

[Q86] 读取 JSON 字段
来源：http://dali.kuanghao11.cn/Article/details/gtuneqzbmm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.tian-w.cn/Article/details/gtvhmcfgew.html

[Q87] JSON 字段做条件
来源：http://dali.smart0.xyz/Article/details/gtlunutpkf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jyoumei.cn/Article/details/gtnofzwnqk.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhoulong.xyz/Article/details/gttjzbzoyx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jqgufenzy.top/Article/details/gtgtthphjj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtslvrnraa.html

[Q89] 判断表是否存在
来源：http://dali.gotoacloud.top/Article/details/gthvvcwikx.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.tianlin.xyz/Article/details/gtfokqehfl.html

[Q90] 生成序号列
来源：http://dali.ppjwa.cn/Article/details/gteqrmjwsj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.pengpengdd.cyou/Article/details/gtupjbrzab.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtavklhurx.html

R. Bash 专题
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvedlfdvp.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtpcgksnde.html

[R01] shebang 与严格模式
来源：http://dali.shanyushiyangtech.top/Article/details/gtyrjdhbbj.html

#!/usr/bin/env bash
来源：http://dali.jyoumei.cn/Article/details/gtbordcpbz.html

set -euo pipefail
来源：http://dali.dashuyun.cn/Article/details/gtxpexqjbh.html

[R02] 变量赋值与使用
来源：http://dali.guowangkeji.top/Article/details/gtmtdcinbb.html

name="Tom"; echo "$name"
来源：http://dali.zycfv.cn/Article/details/gtciezunll.html

[R03] 只读变量
来源：http://dali.pycfn.com/Article/details/gtdifopevt.html

readonly PI=3.14
来源：http://dali.sysykeji.top/Article/details/gtaudltzue.html

[R04] 位置参数
来源：http://dali.meibo888.top/Article/details/gtjjkpxfzx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgfyxgpql.html

[R05] 参数默认值
来源：http://dali.chenzaomai.com/Article/details/gtfmuxzclt.html

name="${1:-default}"
来源：http://dali.ehwqpu.com/Article/details/gtnzuvomnu.html

[R06] 判断命令是否存在
来源：http://dali.tianlin.xyz/Article/details/gtadnuubib.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.smart0.xyz/Article/details/gtxtmvehbr.html

[R07] if 判断文件
来源：http://dali.nwbrower.top/Article/details/gtpuklgyeu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xuanzx.com/Article/details/gtjykgontf.html

[R08] 数值比较
来源：http://dali.yonumen.top/Article/details/gtwplbvhec.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jinqigfzy.top/Article/details/gtgqrhqnmb.html

[R09] 字符串比较
来源：http://dali.yanxiufei.cn/Article/details/gtxgxjunso.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hywenlv.cn/Article/details/gtnmvlihol.html

[R10] 正则匹配
来源：http://dali.kuanghao11.cn/Article/details/gtvsrjzzah.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sufxvd.cn/Article/details/gtkkmsdxwo.html

[R11] case 多分支
来源：http://dali.feifeiyinyue.top/Article/details/gtgbloozjy.html

case "$1" in
来源：http://dali.yanxiufei.cn/Article/details/gtafknpgwf.html

start) echo "启动" ;;
来源：http://dali.nanxuanxn.top/Article/details/gtxmdbzxmo.html

stop)  echo "停止" ;;
来源：http://dali.dianchejie.cn/Article/details/gtqpzfrmwo.html

*)     echo "未知命令" ;;
来源：http://dali.zhiwuduotai.top/Article/details/gtvajrixpr.html

esac
来源：http://dali.cdnleiting.top/Article/details/gtwrvmhdxo.html

[R12] for 遍历文件
来源：http://dali.daxiang520.top/Article/details/gtiibjvzxo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yj20258888.top/Article/details/gtshbkizqv.html

[R13] for 计数循环
来源：http://dali.cdnleiting.top/Article/details/gtbztupwtv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yanxiufei.cn/Article/details/gttaozipxv.html

[R14] C 风格 for
来源：http://dali.gaohongyu789.top/Article/details/gtyvgoxnxh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ydzc1.top/Article/details/gttxomlhrn.html

[R15] while 逐行读文件
来源：http://dali.gogol.net.cn/Article/details/gtddhylqdu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xinyue.icu/Article/details/gthfhhsbbz.html

[R16] until 等待条件
来源：http://dali.xylfe.cn/Article/details/gtzdjgeefd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jyoumei.cn/Article/details/gtjikmymfu.html

[R17] 数组定义与取值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfketzcqu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jiagoushi.top/Article/details/gtsjsymfok.html

[R18] 遍历数组
来源：http://dali.hywenlv.cn/Article/details/gtimprwuhl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.nanxuanxn.top/Article/details/gtuegagmdw.html

[R19] 数组长度
来源：http://dali.sufxvd.cn/Article/details/gtpmsyklla.html

echo "${#arr[@]}"
来源：http://dali.9152youxi.cn/Article/details/gtarreuceg.html

[R20] 关联数组（字典）
来源：http://dali.cucudq.cn/Article/details/gteonnnkij.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.316326.xyz/Article/details/gtinwtbnbr.html

[R21] 字符串长度
来源：http://dali.chenjidiqi.icu/Article/details/gtgbnqhnzt.html

echo "${#s}"
来源：http://dali.shangyingyoupin.top/Article/details/gtlfsmfnbj.html

[R22] 截取子串
来源：http://dali.cashguo.top/Article/details/gtlqltsmxl.html

echo "${s:0:5}"
来源：http://dali.daxiang520.top/Article/details/gtwbpgcnfy.html

[R23] 字符串替换
来源：http://dali.cucudq.cn/Article/details/gtdbvfiqtz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.meibo888.top/Article/details/gttamqsslz.html

[R24] 大小写转换
来源：http://dali.xuetiantiany.cn/Article/details/gttzvvqzdq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.guannengcc.top/Article/details/gtdpylmvgx.html

[R25] 去后缀 / 去前缀
来源：http://dali.yongpay.top/Article/details/gtpcbeqfbj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.tanke756.top/Article/details/gtaeylgsmk.html

[R26] 命令替换
来源：http://dali.kuanghao11.cn/Article/details/gtwygxzbro.html

now=$(date +%F); echo "$now"
来源：http://dali.iojbl.cn/Article/details/gtlzhjdvek.html

[R27] 算术展开
来源：http://dali.cucudq.cn/Article/details/gtlbnztjbk.html

echo $((1 + 2 * 3))
来源：http://dali.vqdsnc.cn/Article/details/gtmlmqfgwg.html

[R28] 浮点运算
来源：http://dali.wangdashe.top/Article/details/gtqtvzqivd.html

echo "scale=2; 10/3" | bc
来源：http://dali.zycfv.cn/Article/details/gttpqvlsdh.html

[R29] 定义函数
来源：http://dali.mhx1999.top/Article/details/gtmsloxeoi.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.aizwys.cn/Article/details/gtaklpbyua.html

[R30] 函数返回状态码
来源：http://dali.chenzaomai.com/Article/details/gtimwaqmiv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbcccajxm.html

[R31] 局部变量
来源：http://dali.hnxiangtu.top/Article/details/gtqkryokel.html

f() { local x=1; echo "$x"; }
来源：http://dali.snrcjt.cn/Article/details/gtmakuwuzh.html

[R32] 参数个数校验
来源：http://dali.chenlongwang.top/Article/details/gtlyhktpqe.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgomkhsik.html

[R33] 捕获错误并提示行号
来源：http://dali.yj20258.top/Article/details/gtocooquvz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.svipenyu.cn/Article/details/gtaasszwfu.html

[R34] 退出时清理
来源：http://dali.hongshengwenyu.top/Article/details/gtskhigqlv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shanyushiyangtech.top/Article/details/gtrmmlmuci.html

[R35] 后台执行并等待
来源：http://dali.zhoulong.xyz/Article/details/gtthdcvrxj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cheryme.top/Article/details/gtdbqjeede.html

[R36] 并发执行多个任务
来源：http://dali.fengsongda.top/Article/details/gtjcwocveh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.daria6918.cn/Article/details/gtrqddqzjj.html

[R37] 把输出赋给变量
来源：http://dali.ppjwa.cn/Article/details/gtzdcwpmds.html

files=$(ls -1)
来源：http://dali.sxryk.cn/Article/details/gthxzoadxt.html

[R38] 管道串联
来源：http://dali.zhiwuduotai.top/Article/details/gtzmnvuwiu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.chenlongwang.top/Article/details/gttphhdbli.html

[R39] 重定向标准输出与错误
来源：http://dali.cdnleiting.top/Article/details/gtsmcbuzcn.html

cmd > out.log 2>&1
来源：http://dali.sweek.top/Article/details/gtmqerlgxw.html

[R40] 追加写日志
来源：http://dali.yongpay.top/Article/details/gtodfkekcz.html

echo "log" >> out.log
来源：http://dali.yueranfly.top/Article/details/gtigumavta.html

[R41] 丢弃输出
来源：http://dali.tian-w.cn/Article/details/gttrwnubtm.html

cmd >/dev/null 2>&1
来源：http://dali.quarkkingdee.top/Article/details/gtlbfkdpkt.html

[R42] 输入重定向
来源：http://dali.xinyue.icu/Article/details/gtognonmmx.html

wc -l < a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtsethxqza.html

[R43] 按名字查找文件
来源：http://dali.chenjidiqi.icu/Article/details/gteltgubzc.html

find . -name "*.log" -type f
来源：http://dali.nanxuanxn.top/Article/details/gtzqkwmmif.html

[R44] 按修改时间查找
来源：http://dali.jinqigufen.top/Article/details/gtwylcsqts.html

find . -mtime -7 -type f
来源：http://dali.yangfankeji.com/Article/details/gtgpbbnnbf.html

[R45] 批量删除
来源：http://dali.zdqjudy.top/Article/details/gtzsmolnqj.html


<!-- 参考信息 -->