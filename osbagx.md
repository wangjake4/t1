代发 wailian999

CREATE TABLE users (
来源：http://dali.sweek.top/Article/details/gtxyoumtyu.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ybcxt.top/Article/details/gtcqmejbag.html

name VARCHAR(50) NOT NULL,
来源：http://dali.tian-w.cn/Article/details/gtuiocmotf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhongyouzk.top/Article/details/gtcqawcjmz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.wangshuangyany.cn/Article/details/gtyumuopmk.html

);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaajhbhlb.html

[Q02] 创建带外键的表
来源：http://dali.smart0.xyz/Article/details/gtybcfurre.html

CREATE TABLE orders (
来源：http://dali.tanke756.top/Article/details/gtaauzmswt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nwbrower.top/Article/details/gtbhjlfixh.html

user_id INT NOT NULL,
来源：http://dali.feifeiyinyue.top/Article/details/gtpqxafsxr.html

amount DECIMAL(10, 2),
来源：http://dali.smart0.xyz/Article/details/gtrhutmtkt.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hysaishi.cn/Article/details/gtscxncavy.html

);
来源：http://dali.yvedp.cn/Article/details/gtkqfhbvvn.html

[Q03] 增加列
来源：http://dali.jlsjyb.cn/Article/details/gtiizdenwi.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sysykeji.top/Article/details/gtfdfiaman.html

[Q04] 修改列类型
来源：http://dali.nanxuanxn.top/Article/details/gtfofuwhdw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gtfenzmddf.html

[Q05] 重命名列
来源：http://dali.zhongyouzk.top/Article/details/gtncjfbuwv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.nanxuanxn.top/Article/details/gtbjoflkhe.html

[Q06] 删除列
来源：http://dali.9152youxi.cn/Article/details/gtpypzjtrj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.vqdsnc.cn/Article/details/gtwkljpbeh.html

[Q07] 删除表
来源：http://dali.mhx1999.top/Article/details/gtygzvleva.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yueranfly.top/Article/details/gtzueznejx.html

[Q08] 创建普通索引
来源：http://dali.quarkkingdee.top/Article/details/gtwrjllgis.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cheryme.top/Article/details/gtnswxjvdu.html

[Q09] 创建唯一索引
来源：http://dali.yj202588.top/Article/details/gtmrygmzfi.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.guowangkeji.top/Article/details/gtlbicwttn.html

[Q10] 插入单行
来源：http://dali.zhixingplan.top/Article/details/gtwnzpeecz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkyackzgu.html

[Q11] 一次插入多行
来源：http://dali.jianghu66.top/Article/details/gtxoonrlqx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhengqikj.top/Article/details/gtsikzyhzj.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gtggidaxzz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yanxiufei.cn/Article/details/gtmoodirlw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.dashuyun.cn/Article/details/gtgabtpiwt.html

[Q13] 忽略重复插入
来源：http://dali.nanxinkj.top/Article/details/gtqhukqqvu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.wangshuangyany.cn/Article/details/gtdqmtzrka.html

[Q14] 存在则更新（upsert）
来源：http://dali.svipenyu.cn/Article/details/gtymjermzh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.aibaodan.cn/Article/details/gteojrqohw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gotoacloud.top/Article/details/gtpxdfxzds.html

[Q15] 查询全部
来源：http://dali.316326.xyz/Article/details/gtxrrrlgft.html

SELECT * FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtwarkecds.html

[Q16] 查询指定列
来源：http://dali.cucudq.cn/Article/details/gtiquffzrn.html

SELECT id, name FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtwemyerzy.html

[Q17] 条件查询
来源：http://dali.yongpay.top/Article/details/gtgcyqnrzc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.guannengcc.top/Article/details/gtfudqktdh.html

[Q18] 模糊匹配
来源：http://dali.guannengcc.top/Article/details/gtprwmxxgd.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.quarkkingdee.top/Article/details/gthdclhhhx.html

[Q19] 范围查询
来源：http://dali.cheryme.top/Article/details/gtppzkkhto.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ehwqpu.com/Article/details/gtpcipmywt.html

[Q20] IN 列表
来源：http://dali.jiagoushi.top/Article/details/gtounmatjb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.fengsongda.top/Article/details/gtygeymfte.html

[Q21] 空值判断
来源：http://dali.chenzaomai.com/Article/details/gtqefapzjs.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yj202588.top/Article/details/gtivkjjeig.html

[Q22] 排序
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwcrrdmht.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.fzhhl.top/Article/details/gtauzjrgvk.html

[Q23] 分页
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyyzkrxwm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.gotoacloud.top/Article/details/gtozaesuwl.html

[Q24] 去重
来源：http://dali.hammf.cn/Article/details/gtfcwmgjmf.html

SELECT DISTINCT city FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtrbugcrvh.html

[Q25] 只取前 N 条
来源：http://dali.zycfv.cn/Article/details/gtbihfkhoy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hywenlv.cn/Article/details/gtygzbfuwo.html

[Q26] 计数
来源：http://dali.yangfankeji.com/Article/details/gtjotobgob.html

SELECT COUNT(*) FROM users;
来源：http://dali.yj202588.top/Article/details/gtoysnzfnv.html

[Q27] 条件计数
来源：http://dali.chenlongwang.top/Article/details/gtwlrqdvve.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnapzxyor.html

[Q28] 求和与平均
来源：http://dali.hywenlv.cn/Article/details/gtuhnzeare.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gtsnouznlg.html

[Q29] 最大最小值
来源：http://dali.havefunace.top/Article/details/gtmmeealnv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtyrcsnnwq.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gtckmwuwhv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jyoumei.cn/Article/details/gtnqzgyxor.html

[Q31] 分组后过滤
来源：http://dali.andypj.xyz/Article/details/gtunlteikz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfvhuwkad.html

[Q32] 分组拼接字符串
来源：http://dali.jqgfzy.top/Article/details/gtywrkmixj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yangfankeji.com/Article/details/gtujzgnhrq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yueranfly.top/Article/details/gtnnsrazsv.html

[Q33] 多列分组
来源：http://dali.chenzaomai.com/Article/details/gtcmvlfbjb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hfpthk.cn/Article/details/gtqvjolhoo.html

[Q34] 每组取第一条
来源：http://dali.yueranfly.top/Article/details/gtzcawojlh.html

SELECT * FROM (
来源：http://dali.ybcxt.top/Article/details/gthbfnvtxe.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.quarkkingdee.top/Article/details/gtafebwpww.html

) t WHERE rn = 1;
来源：http://dali.jyoumei.cn/Article/details/gtslmmdrhs.html

[Q35] 内连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgnoldgxq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xinyue.icu/Article/details/gtjvkmicfu.html

[Q36] 左连接
来源：http://dali.daxiang520.top/Article/details/gtffhifwui.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.aibaodan.cn/Article/details/gtcsyvlosu.html

[Q37] 右连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsxurtqam.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zdqjudy.top/Article/details/gtnmhhfhqf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jinghuilouyu.cn/Article/details/gtddghqiqa.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shuidangran.top/Article/details/gthgcejpfy.html

[Q39] 自连接（查上下级）
来源：http://dali.hfpthk.cn/Article/details/gtfvetlxty.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hnxiangtu.top/Article/details/gtzbyodhgw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.sysykeji.top/Article/details/gtisjerbkc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xuanzx.com/Article/details/gteyuxoere.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.tanke756.top/Article/details/gtmpyllomv.html

[Q41] 多表连接
来源：http://dali.andypj.xyz/Article/details/gtwtxcyoks.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yangfankeji.com/Article/details/gtnwjyigey.html

JOIN users u ON u.id = o.user_id
来源：http://dali.svipenyu.cn/Article/details/gtbcylaoua.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.smart0.xyz/Article/details/gttcfvxnns.html

[Q42] 连接条件附加过滤
来源：http://dali.hammf.cn/Article/details/gtcprezqzi.html

SELECT u.name, o.amount FROM users u
来源：http://dali.bjfxy.top/Article/details/gtuyszjfah.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinghuilouyu.cn/Article/details/gtysekpsos.html

[Q43] 标量子查询
来源：http://dali.quarkkingdee.top/Article/details/gtrfjzhdxk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.iojbl.cn/Article/details/gtjbtrvgse.html

[Q44] IN 子查询
来源：http://dali.tianlin.xyz/Article/details/gtupubytat.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gtuoopczyt.html

[Q45] EXISTS 判断存在
来源：http://dali.aizwys.cn/Article/details/gtdsmeenuj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sxryk.cn/Article/details/gtmacsxbqo.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.daria6918.cn/Article/details/gtzjkhssto.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yuanzhike.top/Article/details/gtpirpejrr.html

[Q47] 与平均值比较
来源：http://dali.mhx1999.top/Article/details/gtmzqlxkcy.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.snrcjt.cn/Article/details/gtmopzjgbb.html

[Q48] CTE 公用表表达式
来源：http://dali.yuanzhike.top/Article/details/gtivybvxys.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shangyingyoupin.top/Article/details/gtovlfpebj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.daria6918.cn/Article/details/gtuvlyifca.html

[Q49] 更新单行
来源：http://dali.xuetiantiany.cn/Article/details/gtcocgewvt.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.fzhhl.top/Article/details/gtgxthrdiv.html

[Q50] 批量更新
来源：http://dali.hnqzz.top/Article/details/gtjrydrums.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hnqzz.top/Article/details/gtpvdjirse.html

[Q51] 用子查询更新
来源：http://dali.yanxiufei.cn/Article/details/gtocrdscbm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinqigufen.top/Article/details/gtlbaealeg.html

[Q52] 删除指定行
来源：http://dali.jinqigufen.top/Article/details/gtukciegwn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jianghu66.top/Article/details/gtjjfouyui.html

[Q53] 按条件删除
来源：http://dali.cashguo.top/Article/details/gtadhebsiw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.bjfxy.top/Article/details/gtdwicibja.html

[Q54] 清空表
来源：http://dali.jinghuilouyu.cn/Article/details/gtflilpwot.html

TRUNCATE TABLE logs;
来源：http://dali.daria6918.cn/Article/details/gtpcyvspnb.html

[Q55] 排名（并列占位）
来源：http://dali.9152youxi.cn/Article/details/gtjnhoeiyg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jlsjyb.cn/Article/details/gtgpwaxgns.html

[Q56] 密集排名（并列不占位）
来源：http://dali.guowangkeji.top/Article/details/gtvdjdddpp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.guowangkeji.top/Article/details/gtwtxjhavx.html

[Q57] 行号
来源：http://dali.fzhhl.top/Article/details/gtskwnzuas.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtepbvixti.html

[Q58] 累计求和
来源：http://dali.daxiang520.top/Article/details/gtrctxoxzt.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtxjdmmbvf.html

[Q59] 分组内累计
来源：http://dali.hnqzz.top/Article/details/gtveeyfkwj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtryqpxzvv.html

[Q60] 取上一行 / 下一行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtofsmvoiu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xuetiantiany.cn/Article/details/gtcbwmhgmw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtxwgkimty.html

[Q61] 移动平均
来源：http://dali.ybcxt.top/Article/details/gtrcznalzi.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtgesfgnyx.html

[Q62] 分组占比
来源：http://dali.jiagoushi.top/Article/details/gtblewrxpg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.bjfxy.top/Article/details/gttnvzaxod.html

[Q63] 开启事务
来源：http://dali.jinqigufen.top/Article/details/gtamjeskgc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.0kj1m.cn/Article/details/gtfvmltcta.html

[Q64] 提交事务
来源：http://dali.yj20258888.top/Article/details/gtqfxfstsp.html

COMMIT;
来源：http://dali.sysykeji.top/Article/details/gtidcxtkps.html

[Q65] 回滚事务
来源：http://dali.birdmap.top/Article/details/gtrgxhsmdy.html

ROLLBACK;
来源：http://dali.wangshuangyany.cn/Article/details/gtppuajjtl.html

[Q66] 行锁查询
来源：http://dali.gzhubu.top/Article/details/gtyskxhsgw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xziqi.cn/Article/details/gtdzujskgk.html

[Q67] 设置隔离级别
来源：http://dali.gotoacloud.top/Article/details/gtpixqeeun.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.snrcjt.cn/Article/details/gtfldkgndq.html

[Q68] 保存点
来源：http://dali.yangfankeji.com/Article/details/gtfsgswoxq.html

SAVEPOINT sp1;
来源：http://dali.dianchejie.cn/Article/details/gtsnknefbj.html

ROLLBACK TO sp1;
来源：http://dali.zdqjudy.top/Article/details/gtzzrbztca.html

[Q69] 查看执行计划
来源：http://dali.nwbrower.top/Article/details/gtxzmsaoof.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yangfankeji.com/Article/details/gtfwwwcekt.html

[Q70] 更新统计信息
来源：http://dali.yueranfly.top/Article/details/gtqvrfejus.html

ANALYZE TABLE users;
来源：http://dali.sysykeji.top/Article/details/gtsqwlrcky.html

[Q71] 查看建表语句
来源：http://dali.yangfankeji.com/Article/details/gtqcsrfzwo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.iojbl.cn/Article/details/gttqlyhtqu.html

[Q72] 查看索引
来源：http://dali.gogol.net.cn/Article/details/gtggaspidw.html

SHOW INDEX FROM users;
来源：http://dali.gzhubu.top/Article/details/gtvihvrzdy.html

[Q73] 查看表状态
来源：http://dali.gotoacloud.top/Article/details/gtiqgjvmwz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhiwuduotai.top/Article/details/gtzjbmgese.html

[Q74] 强制使用索引
来源：http://dali.pengpengdd.cyou/Article/details/gtbfdlgckg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xziqi.cn/Article/details/gtkgzknylv.html

[Q75] 日期格式化
来源：http://dali.wangdashe.top/Article/details/gtrrprgajx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yonumen.top/Article/details/gtwyoavoth.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yonumen.top/Article/details/gtxmrrmmot.html

[Q76] 按天统计
来源：http://dali.hongshengwenyu.top/Article/details/gtcrfopjmf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhiwuduotai.top/Article/details/gtlrrqcxyj.html

[Q77] 时间加减
来源：http://dali.jianghu66.top/Article/details/gtsodtdbun.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gzhubu.top/Article/details/gtvlqylhlp.html

[Q78] 当前时间
来源：http://dali.zhiwuduotai.top/Article/details/gtzpimgsfa.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cheryme.top/Article/details/gtohjkvlbx.html

[Q79] 字符串拼接
来源：http://dali.hammf.cn/Article/details/gtqqngvtco.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.nwbrower.top/Article/details/gtztvmiemb.html

[Q80] 字符串截取
来源：http://dali.sysykeji.top/Article/details/gtpawsgnoo.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yongpay.top/Article/details/gtmydjjhkb.html

[Q81] 字符串替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtorllieej.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.nwbrower.top/Article/details/gtemxmnowy.html

[Q82] 字符长度与字节长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtunpbkvse.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtowdzbviy.html

[Q83] 大小写转换
来源：http://dali.birdmap.top/Article/details/gttgptxbwk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtnjuvbvoi.html

[Q84] 去除首尾空格
来源：http://dali.jiagoushi.top/Article/details/gtjsasdcls.html

SELECT TRIM(name) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtchrnzfbp.html

[Q85] 数值取整
来源：http://dali.xuetiantiany.cn/Article/details/gtsxfkmjjn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yuxming.cn/Article/details/gtbtptcmqw.html

[Q86] 读取 JSON 字段
来源：http://dali.tian-w.cn/Article/details/gtzzxtsobd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinqigfzy.top/Article/details/gtivfgeoja.html

[Q87] JSON 字段做条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtngvnppzs.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jqgfzy.top/Article/details/gtxheydcmn.html

[Q88] 行转列（条件聚合）
来源：http://dali.iojbl.cn/Article/details/gtpyboqsyp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.feifeiyinyue.top/Article/details/gtphufxort.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yj202588.top/Article/details/gtjacwzwdq.html

[Q89] 判断表是否存在
来源：http://dali.pycfn.com/Article/details/gtylhgbfvm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.bjfxy.top/Article/details/gtbvnflnfw.html

[Q90] 生成序号列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwxailvqd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cqqwz.cn/Article/details/gtuxotskzg.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtsalxkzlx.html

R. Bash 专题
来源：http://dali.gotoacloud.top/Article/details/gtmmpxynnx.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyxbgtiml.html

[R01] shebang 与严格模式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlhebixpe.html

#!/usr/bin/env bash
来源：http://dali.nwbrower.top/Article/details/gtkahdhqeg.html

set -euo pipefail
来源：http://dali.cheryme.top/Article/details/gtvdizfkbv.html

[R02] 变量赋值与使用
来源：http://dali.ivvv.top/Article/details/gtjrbuqfnl.html

name="Tom"; echo "$name"
来源：http://dali.feifeiyinyue.top/Article/details/gtwbwqlwnl.html

[R03] 只读变量
来源：http://dali.daxiang520.top/Article/details/gtmusuuxmz.html

readonly PI=3.14
来源：http://dali.fengsongda.top/Article/details/gthwtzdamm.html

[R04] 位置参数
来源：http://dali.jinqigfzy.top/Article/details/gtpduntrna.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.nanxuanxn.top/Article/details/gthjwvgzkl.html

[R05] 参数默认值
来源：http://dali.nanxinkj.top/Article/details/gtiqhkfepb.html

name="${1:-default}"
来源：http://dali.guowangkeji.top/Article/details/gtjkdbszgq.html

[R06] 判断命令是否存在
来源：http://dali.smart0.xyz/Article/details/gtaponanil.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yj20258.top/Article/details/gtvlksibai.html

[R07] if 判断文件
来源：http://dali.jinqigufen.top/Article/details/gtowwrshju.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yvedp.cn/Article/details/gtrbkgsdow.html

[R08] 数值比较
来源：http://dali.zhengqikj.top/Article/details/gthwnfjios.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xziqi.cn/Article/details/gtcsgdfhqq.html

[R09] 字符串比较
来源：http://dali.daria6918.cn/Article/details/gtfznzazhw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj202588.top/Article/details/gtqdopodew.html

[R10] 正则匹配
来源：http://dali.quarkkingdee.top/Article/details/gtydokjsqn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.snrcjt.cn/Article/details/gtimuurpxs.html

[R11] case 多分支
来源：http://dali.shangyingyoupin.top/Article/details/gtbepncnwa.html

case "$1" in
来源：http://dali.chenjidiqi.icu/Article/details/gtquetuocg.html

start) echo "启动" ;;
来源：http://dali.wangdashe.top/Article/details/gtvqopkjqv.html

stop)  echo "停止" ;;
来源：http://dali.zhoulong.xyz/Article/details/gtjxbcxndq.html

*)     echo "未知命令" ;;
来源：http://dali.sufxvd.cn/Article/details/gtubuowpqr.html

esac
来源：http://dali.zhengqikj.top/Article/details/gtawwyeozu.html

[R12] for 遍历文件
来源：http://dali.chenlongwang.top/Article/details/gtoztgwgwt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtvnlchzcb.html

[R13] for 计数循环
来源：http://dali.birdmap.top/Article/details/gtqvynkrwe.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhiwuduotai.top/Article/details/gtdjfiufmb.html

[R14] C 风格 for
来源：http://dali.zdqjudy.top/Article/details/gtajrhumgm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.nwbrower.top/Article/details/gtuacqupap.html

[R15] while 逐行读文件
来源：http://dali.xuetiantiany.cn/Article/details/gtmpajeaxf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.kuanghao11.cn/Article/details/gtynbkaqnm.html

[R16] until 等待条件
来源：http://dali.gzhubu.top/Article/details/gtmwjdupgz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.iojbl.cn/Article/details/gtfraqqlgi.html

[R17] 数组定义与取值
来源：http://dali.cqqwz.cn/Article/details/gtrbxxgemu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jqgufenzy.top/Article/details/gtyexzqrfw.html

[R18] 遍历数组
来源：http://dali.xziqi.cn/Article/details/gtdmzitart.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.pengpengdd.cyou/Article/details/gtdubfffuh.html

[R19] 数组长度
来源：http://dali.nwbrower.top/Article/details/gtoiwzjbks.html

echo "${#arr[@]}"
来源：http://dali.xinyue.icu/Article/details/gtsphiwdlg.html

[R20] 关联数组（字典）
来源：http://dali.yuxming.cn/Article/details/gtdqaqdwyu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.tian-w.cn/Article/details/gtvrcvozwb.html

[R21] 字符串长度
来源：http://dali.cdnleiting.top/Article/details/gthnqhfpup.html

echo "${#s}"
来源：http://dali.haohaochexian.top/Article/details/gtzcxtjwwh.html

[R22] 截取子串
来源：http://dali.nanxinkj.top/Article/details/gtzkjnolug.html

echo "${s:0:5}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtuwbhtqel.html

[R23] 字符串替换
来源：http://dali.xinyue.icu/Article/details/gtlchyzhmn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.chenzaomai.com/Article/details/gtijsvqsju.html

[R24] 大小写转换
来源：http://dali.jianghu66.top/Article/details/gtwimjxvow.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhongyouzk.top/Article/details/gttrrgfnap.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinghuilouyu.cn/Article/details/gtjsspwlof.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jyoumei.cn/Article/details/gtgfzmdtpe.html

[R26] 命令替换
来源：http://dali.sysykeji.top/Article/details/gtunobaeda.html

now=$(date +%F); echo "$now"
来源：http://dali.jyoumei.cn/Article/details/gtrgwjfbqo.html

[R27] 算术展开
来源：http://dali.aizwys.cn/Article/details/gtucfaucee.html

echo $((1 + 2 * 3))
来源：http://dali.redwolf501.top/Article/details/gtdpzjdeca.html

[R28] 浮点运算
来源：http://dali.gaohongyu789.top/Article/details/gtycevfwmz.html

echo "scale=2; 10/3" | bc
来源：http://dali.iojbl.cn/Article/details/gtfdesfqbq.html

[R29] 定义函数
来源：http://dali.jianghu66.top/Article/details/gtsyvpjbye.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.wangdashe.top/Article/details/gtmmjdrbdw.html

[R30] 函数返回状态码
来源：http://dali.yanxiufei.cn/Article/details/gtomffmhmj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shangyingyoupin.top/Article/details/gtfbezmutm.html

[R31] 局部变量
来源：http://dali.daria6918.cn/Article/details/gtrexjacnc.html

f() { local x=1; echo "$x"; }
来源：http://dali.hammf.cn/Article/details/gtjtkjxudz.html

[R32] 参数个数校验
来源：http://dali.nwbrower.top/Article/details/gtxnnapdzu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jlsjyb.cn/Article/details/gtzklgdidb.html

[R33] 捕获错误并提示行号
来源：http://dali.0kj1m.cn/Article/details/gtgteccsyy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtradotpdf.html

[R34] 退出时清理
来源：http://dali.fengsongda.top/Article/details/gtvrjcjxho.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.svipenyu.cn/Article/details/gtjbheouzv.html

[R35] 后台执行并等待
来源：http://dali.haohaochexian.top/Article/details/gtgigwcvsq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jianghu66.top/Article/details/gtgmggoqoy.html

[R36] 并发执行多个任务
来源：http://dali.gaohongyu789.top/Article/details/gtjzaesnkz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.tian-w.cn/Article/details/gteyoscpgx.html

[R37] 把输出赋给变量
来源：http://dali.zycfv.cn/Article/details/gtdxlvpybd.html

files=$(ls -1)
来源：http://dali.zhixingplan.top/Article/details/gtrduhlfyi.html

[R38] 管道串联
来源：http://dali.zdqjudy.top/Article/details/gtaesqohbf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sufxvd.cn/Article/details/gtnvbrzyvp.html

[R39] 重定向标准输出与错误
来源：http://dali.kuanghao11.cn/Article/details/gtqzpomcmp.html

cmd > out.log 2>&1
来源：http://dali.chenzaomai.com/Article/details/gtjvoauzfu.html

[R40] 追加写日志
来源：http://dali.0kj1m.cn/Article/details/gtwrknntlc.html

echo "log" >> out.log
来源：http://dali.bjfxy.top/Article/details/gtfonyirft.html

[R41] 丢弃输出
来源：http://dali.fzhhl.top/Article/details/gtfvpfumva.html

cmd >/dev/null 2>&1
来源：http://dali.zhoulong.xyz/Article/details/gttkklcokt.html

[R42] 输入重定向
来源：http://dali.sysykeji.top/Article/details/gtjagzhiqv.html

wc -l < a.txt
来源：http://dali.316326.xyz/Article/details/gtsjppmmyk.html

[R43] 按名字查找文件
来源：http://dali.shangyingyoupin.top/Article/details/gttxokmjkl.html

find . -name "*.log" -type f
来源：http://dali.nwbrower.top/Article/details/gttevouujb.html

[R44] 按修改时间查找
来源：http://dali.guannengcc.top/Article/details/gthdhwoaah.html

find . -mtime -7 -type f
来源：http://dali.gogol.net.cn/Article/details/gtshqeqnzf.html

[R45] 批量删除
来源：http://dali.yongpay.top/Article/details/gtoeyaibsp.html


<!-- 参考信息 -->