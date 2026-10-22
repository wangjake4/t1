代发 wailian999

CREATE TABLE users (
来源：http://dali.yj202588.top/Article/details/gt2uwgjhykd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hysaishi.cn/Article/details/gt2uqxyejbq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gogol.net.cn/Article/details/gt2mszsqocb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sxryk.cn/Article/details/gt2ezzysrrr.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.sxryk.cn/Article/details/gt2wmunyrhf.html

);
来源：http://dali.guannengcc.top/Article/details/gt2clonfivy.html

[Q02] 创建带外键的表
来源：http://dali.ehwqpu.com/Article/details/gt2iciczcjo.html

CREATE TABLE orders (
来源：http://dali.chenjidiqi.icu/Article/details/gt2aitdlarb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ehwqpu.com/Article/details/gt2yeuogvrg.html

user_id INT NOT NULL,
来源：http://dali.yangfankeji.com/Article/details/gt2fngvprln.html

amount DECIMAL(10, 2),
来源：http://dali.0kj1m.cn/Article/details/gt2nmcwaclq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.fzhhl.top/Article/details/gt2riniuuqk.html

);
来源：http://dali.cheryme.top/Article/details/gt2bwyjsswa.html

[Q03] 增加列
来源：http://dali.meibo888.top/Article/details/gt2umirtmkq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yvedp.cn/Article/details/gt2jcknabcn.html

[Q04] 修改列类型
来源：http://dali.bjfxy.top/Article/details/gt2adsucnpa.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.mhx1999.top/Article/details/gt2hpgjpdtr.html

[Q05] 重命名列
来源：http://dali.cucudq.cn/Article/details/gt2ilorjegv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jlsjyb.cn/Article/details/gt2kalwplok.html

[Q06] 删除列
来源：http://dali.xinyue.icu/Article/details/gt2htwlimdy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yj20258.top/Article/details/gt2hivtprts.html

[Q07] 删除表
来源：http://dali.nwbrower.top/Article/details/gt2vhtbxxpy.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ydzc1.top/Article/details/gt2ueiciqqg.html

[Q08] 创建普通索引
来源：http://dali.gaohongyu789.top/Article/details/gt2fsxsjwrn.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cucudq.cn/Article/details/gt2vumozhzm.html

[Q09] 创建唯一索引
来源：http://dali.ivvv.top/Article/details/gt2yshqjoho.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.gaohongyu789.top/Article/details/gt2ibxjrhko.html

[Q10] 插入单行
来源：http://dali.yj20258888.top/Article/details/gt2zdkuregg.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yuanzhike.top/Article/details/gt2fynrxlvq.html

[Q11] 一次插入多行
来源：http://dali.wangshuangyany.cn/Article/details/gt2pzzpfgey.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.iojbl.cn/Article/details/gt2rxizhwnl.html

[Q12] 插入后取自增 ID
来源：http://dali.iojbl.cn/Article/details/gt2lvkzkxpu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.snrcjt.cn/Article/details/gt2jebcnrcn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinqigufen.top/Article/details/gt2fejstrhl.html

[Q13] 忽略重复插入
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2arkxvtjg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.gogol.net.cn/Article/details/gt2ufndbors.html

[Q14] 存在则更新（upsert）
来源：http://dali.sufxvd.cn/Article/details/gt2mezhcmdl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zdqjudy.top/Article/details/gt2wibvqfjh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yj20258.top/Article/details/gt2nxjilxon.html

[Q15] 查询全部
来源：http://dali.havefunace.top/Article/details/gt2jxgsbqwg.html

SELECT * FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2bryctolq.html

[Q16] 查询指定列
来源：http://dali.guowangkeji.top/Article/details/gt2irltavzi.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2blbleipf.html

[Q17] 条件查询
来源：http://dali.fengsongda.top/Article/details/gt2evxmgtxw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.birdmap.top/Article/details/gt2pktgddbc.html

[Q18] 模糊匹配
来源：http://dali.sweek.top/Article/details/gt2cnwmvqpz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dfyvrueq.html

[Q19] 范围查询
来源：http://dali.0kj1m.cn/Article/details/gt2hpnnnxuc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hnqzz.top/Article/details/gt2mzewpbpv.html

[Q20] IN 列表
来源：http://dali.aibaodan.cn/Article/details/gt2ccviraml.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.sufxvd.cn/Article/details/gt2oynbxcag.html

[Q21] 空值判断
来源：http://dali.daxiang520.top/Article/details/gt2idqpejxm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zgaztotv.html

[Q22] 排序
来源：http://dali.yangfankeji.com/Article/details/gt2qkfhttos.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2idthtvly.html

[Q23] 分页
来源：http://dali.wangdashe.top/Article/details/gt2reuqmezg.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.tanke756.top/Article/details/gt2zhqlzqeb.html

[Q24] 去重
来源：http://dali.hongshengwenyu.top/Article/details/gt2exgmlufp.html

SELECT DISTINCT city FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2eynnqutn.html

[Q25] 只取前 N 条
来源：http://dali.c1oappe.top/Article/details/gt2oabkbjdv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jyoumei.cn/Article/details/gt2zxgpvtsg.html

[Q26] 计数
来源：http://dali.hfpthk.cn/Article/details/gt2qjvijsuy.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2hhzakjju.html

[Q27] 条件计数
来源：http://dali.nanxuanxn.top/Article/details/gt2kewphuaw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2cmwjtvwt.html

[Q28] 求和与平均
来源：http://dali.yj202588.top/Article/details/gt2exaybxqe.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.iojbl.cn/Article/details/gt2msdgtzea.html

[Q29] 最大最小值
来源：http://dali.c1oappe.top/Article/details/gt2cxemwvrc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2xglzjhlf.html

[Q30] 分组统计
来源：http://dali.jlsjyb.cn/Article/details/gt2dmmzzhou.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yuanzhike.top/Article/details/gt2wielxhbk.html

[Q31] 分组后过滤
来源：http://dali.jinqigfzy.top/Article/details/gt2heapafmj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.smart0.xyz/Article/details/gt2hwfyuqgk.html

[Q32] 分组拼接字符串
来源：http://dali.shzxlz.cn/Article/details/gt2qpaeddsu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hnqzz.top/Article/details/gt2rybuygrj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.gaohongyu789.top/Article/details/gt2mqmccwfs.html

[Q33] 多列分组
来源：http://dali.kuanghao11.cn/Article/details/gt2ftpypits.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hnqzz.top/Article/details/gt2ulzbrsnn.html

[Q34] 每组取第一条
来源：http://dali.dashuyun.cn/Article/details/gt2accwyfvy.html

SELECT * FROM (
来源：http://dali.ybcxt.top/Article/details/gt2mjtglywd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zdqjudy.top/Article/details/gt2iqvlayxv.html

) t WHERE rn = 1;
来源：http://dali.xziqi.cn/Article/details/gt2tlahqton.html

[Q35] 内连接
来源：http://dali.fzhhl.top/Article/details/gt2apdqhoza.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuanzhike.top/Article/details/gt2klivbhyt.html

[Q36] 左连接
来源：http://dali.cucudq.cn/Article/details/gt2oudkcimt.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.bjfxy.top/Article/details/gt2zzaydnyb.html

[Q37] 右连接
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bpwbyqiq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.daria6918.cn/Article/details/gt2fiuqqjpo.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.c1oappe.top/Article/details/gt2ikfvoghv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.c1oappe.top/Article/details/gt2fooestaa.html

[Q39] 自连接（查上下级）
来源：http://dali.ybcxt.top/Article/details/gt2jnhekexu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.9152youxi.cn/Article/details/gt2ejqhwoel.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.feifeiyinyue.top/Article/details/gt2tqydnerw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gaohongyu789.top/Article/details/gt2hcracpqm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sxryk.cn/Article/details/gt2cdcoczfn.html

[Q41] 多表连接
来源：http://dali.mhx1999.top/Article/details/gt2scaotoyg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gotoacloud.top/Article/details/gt2xgxvudfl.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cdnleiting.top/Article/details/gt2iynjefvp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yuxming.cn/Article/details/gt2zslhwquk.html

[Q42] 连接条件附加过滤
来源：http://dali.yongpay.top/Article/details/gt2chgdngoy.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ppjwa.cn/Article/details/gt2okiuubfd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ybcxt.top/Article/details/gt2qvwgdspt.html

[Q43] 标量子查询
来源：http://dali.shangyingyoupin.top/Article/details/gt2ekshaign.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ivvv.top/Article/details/gt2xmquvzcs.html

[Q44] IN 子查询
来源：http://dali.9152youxi.cn/Article/details/gt2nkbgjhdk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hnqzz.top/Article/details/gt2cogjfaui.html

[Q45] EXISTS 判断存在
来源：http://dali.guannengcc.top/Article/details/gt2wgkexxup.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinqigufen.top/Article/details/gt2lophwvti.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xylfe.cn/Article/details/gt2jaefsajg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.c1oappe.top/Article/details/gt2kkeuvzkj.html

[Q47] 与平均值比较
来源：http://dali.yj20258.top/Article/details/gt2dxyybltc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cucudq.cn/Article/details/gt2shznqpkk.html

[Q48] CTE 公用表表达式
来源：http://dali.tian-w.cn/Article/details/gt2kbfeexhn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.daria6918.cn/Article/details/gt2unyxbgti.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.birdmap.top/Article/details/gt2naxnldsj.html

[Q49] 更新单行
来源：http://dali.meibo888.top/Article/details/gt2qgcczpfv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fugmrxaj.html

[Q50] 批量更新
来源：http://dali.yj20258.top/Article/details/gt2zoondpqb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.bjfxy.top/Article/details/gt2kmjryfox.html

[Q51] 用子查询更新
来源：http://dali.andypj.xyz/Article/details/gt2vxevydyk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.0kj1m.cn/Article/details/gt2ilgeiurs.html

[Q52] 删除指定行
来源：http://dali.gzhubu.top/Article/details/gt2dyrrpmhf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.c1oappe.top/Article/details/gt2rotvgtyo.html

[Q53] 按条件删除
来源：http://dali.meibo888.top/Article/details/gt2zhbtsfmd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hongshengwenyu.top/Article/details/gt2ruhblagm.html

[Q54] 清空表
来源：http://dali.jiagoushi.top/Article/details/gt2vgenfaky.html

TRUNCATE TABLE logs;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ttnsnduy.html

[Q55] 排名（并列占位）
来源：http://dali.gotoacloud.top/Article/details/gt2rvurdlox.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cashguo.top/Article/details/gt2dgarfexc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.chenjidiqi.icu/Article/details/gt2tdueyluk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.wangshuangyany.cn/Article/details/gt2lvzzoceb.html

[Q57] 行号
来源：http://dali.sysykeji.top/Article/details/gt2qxkcznvn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2wwtjvwrb.html

[Q58] 累计求和
来源：http://dali.yongpay.top/Article/details/gt2tpxmzzsg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.c1oappe.top/Article/details/gt2qbnnyqyr.html

[Q59] 分组内累计
来源：http://dali.yuanzhike.top/Article/details/gt2ofuomrya.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yj202588.top/Article/details/gt2uutyaych.html

[Q60] 取上一行 / 下一行
来源：http://dali.havefunace.top/Article/details/gt2dsiyosbd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yuanzhike.top/Article/details/gt2wjfxvsyd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.fengsongda.top/Article/details/gt2lxkwkvzm.html

[Q61] 移动平均
来源：http://dali.316326.xyz/Article/details/gt2zzgqzmdu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gt2lfohtxin.html

[Q62] 分组占比
来源：http://dali.hfpthk.cn/Article/details/gt2oeezabsx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinqigfzy.top/Article/details/gt2yszsncqj.html

[Q63] 开启事务
来源：http://dali.quarkkingdee.top/Article/details/gt2tvayosiq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.wangshuangyany.cn/Article/details/gt2xdurklvz.html

[Q64] 提交事务
来源：http://dali.pycfn.com/Article/details/gt2piewhfht.html

COMMIT;
来源：http://dali.birdmap.top/Article/details/gt2cketnrnv.html

[Q65] 回滚事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gvxmvcol.html

ROLLBACK;
来源：http://dali.daria6918.cn/Article/details/gt2pdcfdbdj.html

[Q66] 行锁查询
来源：http://dali.wangshuangyany.cn/Article/details/gt2qeyuwakz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.aizwys.cn/Article/details/gt2nhlgqcdx.html

[Q67] 设置隔离级别
来源：http://dali.yongpay.top/Article/details/gt2vbtivzvf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjgivraf.html

[Q68] 保存点
来源：http://dali.yj20258888.top/Article/details/gt2uqqiketx.html

SAVEPOINT sp1;
来源：http://dali.yonumen.top/Article/details/gt2ypxlsedk.html

ROLLBACK TO sp1;
来源：http://dali.shuidangran.top/Article/details/gt2ljdsldvf.html

[Q69] 查看执行计划
来源：http://dali.chenlongwang.top/Article/details/gt2nvuvhjgg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ydzc1.top/Article/details/gt2ffuksmor.html

[Q70] 更新统计信息
来源：http://dali.hammf.cn/Article/details/gt2wgyjkayi.html

ANALYZE TABLE users;
来源：http://dali.sweek.top/Article/details/gt2yslxmcrk.html

[Q71] 查看建表语句
来源：http://dali.yonumen.top/Article/details/gt2ejukdayw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.quarkkingdee.top/Article/details/gt2neoduswn.html

[Q72] 查看索引
来源：http://dali.gzhubu.top/Article/details/gt2mciebxna.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbzqmrrq.html

[Q73] 查看表状态
来源：http://dali.sufxvd.cn/Article/details/gt2orjiunwq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yuanzhike.top/Article/details/gt2ghhkgayu.html

[Q74] 强制使用索引
来源：http://dali.tian-w.cn/Article/details/gt2aendtwfv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.gaohongyu789.top/Article/details/gt2nexejtst.html

[Q75] 日期格式化
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rooslwhs.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zycfv.cn/Article/details/gt2kjsewkhf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xuetiantiany.cn/Article/details/gt2swxlymcv.html

[Q76] 按天统计
来源：http://dali.tian-w.cn/Article/details/gt2uhdpgsnn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.dianchejie.cn/Article/details/gt2nwgifodl.html

[Q77] 时间加减
来源：http://dali.dianchejie.cn/Article/details/gt2iodteuts.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hywenlv.cn/Article/details/gt2onumxicq.html

[Q78] 当前时间
来源：http://dali.birdmap.top/Article/details/gt2fkxunvkn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jlsjyb.cn/Article/details/gt2ldvskgzi.html

[Q79] 字符串拼接
来源：http://dali.mhx1999.top/Article/details/gt2trmavbzp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cdnleiting.top/Article/details/gt2xuedjyus.html

[Q80] 字符串截取
来源：http://dali.yuanzhike.top/Article/details/gt2ovrqffcf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2tqpinbrh.html

[Q81] 字符串替换
来源：http://dali.andypj.xyz/Article/details/gt2vgksqrti.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2zisftlas.html

[Q82] 字符长度与字节长度
来源：http://dali.zdqjudy.top/Article/details/gt2vuwlqxiv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2uvqitlji.html

[Q83] 大小写转换
来源：http://dali.jinqigufen.top/Article/details/gt2pesnmdxg.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.tian-w.cn/Article/details/gt2nejstbav.html

[Q84] 去除首尾空格
来源：http://dali.ydzc1.top/Article/details/gt2dhssnzjt.html

SELECT TRIM(name) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2husmlgna.html

[Q85] 数值取整
来源：http://dali.hysaishi.cn/Article/details/gt2xvxtfipc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.feifeiyinyue.top/Article/details/gt2vvmhjhmw.html

[Q86] 读取 JSON 字段
来源：http://dali.wangshuangyany.cn/Article/details/gt2cbpetteq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.guowangkeji.top/Article/details/gt2lbjlccvn.html

[Q87] JSON 字段做条件
来源：http://dali.nwbrower.top/Article/details/gt2flkoebgs.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.fzhhl.top/Article/details/gt2jvrzjctl.html

[Q88] 行转列（条件聚合）
来源：http://dali.tian-w.cn/Article/details/gt2nwgijycz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hnqzz.top/Article/details/gt2jaqndbhl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2rzjxahpi.html

[Q89] 判断表是否存在
来源：http://dali.aizwys.cn/Article/details/gt2tadrwdfh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cucudq.cn/Article/details/gt2mkzpqepi.html

[Q90] 生成序号列
来源：http://dali.zhoulong.xyz/Article/details/gt2xmitehzj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mnuulced.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2eftxpcwg.html

R. Bash 专题
来源：http://dali.cqqwz.cn/Article/details/gt2hatczolh.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2yawfvdca.html

[R01] shebang 与严格模式
来源：http://dali.meibo888.top/Article/details/gt2qfpyxpcl.html

#!/usr/bin/env bash
来源：http://dali.kuanghao11.cn/Article/details/gt2wlnaypew.html

set -euo pipefail
来源：http://dali.tanke756.top/Article/details/gt2kwhknyle.html

[R02] 变量赋值与使用
来源：http://dali.gzhubu.top/Article/details/gt2tzzhhhjf.html

name="Tom"; echo "$name"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tgahciwy.html

[R03] 只读变量
来源：http://dali.xuetiantiany.cn/Article/details/gt2agrxbnue.html

readonly PI=3.14
来源：http://dali.guowangkeji.top/Article/details/gt2cvsnmtok.html

[R04] 位置参数
来源：http://dali.shuidangran.top/Article/details/gt2qunkzoob.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yuanzhike.top/Article/details/gt2wniidnwn.html

[R05] 参数默认值
来源：http://dali.sweek.top/Article/details/gt2eoclkuuz.html

name="${1:-default}"
来源：http://dali.mhx1999.top/Article/details/gt2weweugvm.html

[R06] 判断命令是否存在
来源：http://dali.gogol.net.cn/Article/details/gt2tccrcikx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.daxiang520.top/Article/details/gt2meynfhpy.html

[R07] if 判断文件
来源：http://dali.dianchejie.cn/Article/details/gt2dznrjrau.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xuetiantiany.cn/Article/details/gt2jaabhzxu.html

[R08] 数值比较
来源：http://dali.andypj.xyz/Article/details/gt2ujhfphoe.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yuanzhike.top/Article/details/gt2hhmniduj.html

[R09] 字符串比较
来源：http://dali.sysykeji.top/Article/details/gt2fdpdibsy.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cheryme.top/Article/details/gt2ndgrwqll.html

[R10] 正则匹配
来源：http://dali.yj202588.top/Article/details/gt2tbmxnqmm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hnxiangtu.top/Article/details/gt2jkfhpthb.html

[R11] case 多分支
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ffmsbihw.html

case "$1" in
来源：http://dali.bjfxy.top/Article/details/gt2ygoakwtg.html

start) echo "启动" ;;
来源：http://dali.yanxiufei.cn/Article/details/gt2tlzvpnmp.html

stop)  echo "停止" ;;
来源：http://dali.sysykeji.top/Article/details/gt2vhgpoyoz.html

*)     echo "未知命令" ;;
来源：http://dali.sweek.top/Article/details/gt2pnfljfpo.html

esac
来源：http://dali.316326.xyz/Article/details/gt2aptefzum.html

[R12] for 遍历文件
来源：http://dali.ydzc1.top/Article/details/gt2ipmlylhf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yanxiufei.cn/Article/details/gt2dldkakgx.html

[R13] for 计数循环
来源：http://dali.ivvv.top/Article/details/gt2lmvewgsx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.tanke756.top/Article/details/gt2yolpgtqf.html

[R14] C 风格 for
来源：http://dali.9152youxi.cn/Article/details/gt2kgohkeai.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhongyouzk.top/Article/details/gt2dsyketzl.html

[R15] while 逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gt2fiaizbto.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.fzhhl.top/Article/details/gt2uzeflctn.html

[R16] until 等待条件
来源：http://dali.wangshuangyany.cn/Article/details/gt2rtcvqeoy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinqigufen.top/Article/details/gt2joqibqoc.html

[R17] 数组定义与取值
来源：http://dali.xylfe.cn/Article/details/gt2fdgkzhde.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.tian-w.cn/Article/details/gt2blebgvil.html

[R18] 遍历数组
来源：http://dali.nwbrower.top/Article/details/gt2benkozqp.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.316326.xyz/Article/details/gt2enrzbibl.html

[R19] 数组长度
来源：http://dali.gaohongyu789.top/Article/details/gt2pjtpibfh.html

echo "${#arr[@]}"
来源：http://dali.chenlongwang.top/Article/details/gt2usfwdnjf.html

[R20] 关联数组（字典）
来源：http://dali.gzhubu.top/Article/details/gt2tkswckhh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.fzhhl.top/Article/details/gt2ytwdrlpv.html

[R21] 字符串长度
来源：http://dali.ppjwa.cn/Article/details/gt2lkonixsz.html

echo "${#s}"
来源：http://dali.yangfankeji.com/Article/details/gt2fpplhkph.html

[R22] 截取子串
来源：http://dali.yanxiufei.cn/Article/details/gt2gsxkbang.html

echo "${s:0:5}"
来源：http://dali.fengsongda.top/Article/details/gt2dgrasikt.html

[R23] 字符串替换
来源：http://dali.jinqigufen.top/Article/details/gt2qpubcybc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vwvdpwsf.html

[R24] 大小写转换
来源：http://dali.zdqjudy.top/Article/details/gt2tkvfotfs.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.tanke756.top/Article/details/gt2jkghtxdn.html

[R25] 去后缀 / 去前缀
来源：http://dali.yuanzhike.top/Article/details/gt2acvqykwi.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.0kj1m.cn/Article/details/gt2exvmhtkp.html

[R26] 命令替换
来源：http://dali.mhx1999.top/Article/details/gt2smwfluvq.html

now=$(date +%F); echo "$now"
来源：http://dali.daria6918.cn/Article/details/gt2hmnlnzgd.html

[R27] 算术展开
来源：http://dali.chenzaomai.com/Article/details/gt2bjyfkneq.html

echo $((1 + 2 * 3))
来源：http://dali.sufxvd.cn/Article/details/gt2jlbhizzk.html

[R28] 浮点运算
来源：http://dali.snrcjt.cn/Article/details/gt2twfuvzgq.html

echo "scale=2; 10/3" | bc
来源：http://dali.cqqwz.cn/Article/details/gt2tkvhjptq.html

[R29] 定义函数
来源：http://dali.bjfxy.top/Article/details/gt2fgjdcwas.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xziqi.cn/Article/details/gt2zqkcrkut.html

[R30] 函数返回状态码
来源：http://dali.c1oappe.top/Article/details/gt2rftgvwph.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.dianchejie.cn/Article/details/gt2sxgobyay.html

[R31] 局部变量
来源：http://dali.quarkkingdee.top/Article/details/gt2cuakjpdx.html

f() { local x=1; echo "$x"; }
来源：http://dali.dashuyun.cn/Article/details/gt2ysrapvds.html

[R32] 参数个数校验
来源：http://dali.316326.xyz/Article/details/gt2tqqvhacp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.wangdashe.top/Article/details/gt2zqolmgmu.html

[R33] 捕获错误并提示行号
来源：http://dali.yangfankeji.com/Article/details/gt2ojejdyck.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sxryk.cn/Article/details/gt2wxjkxcxn.html

[R34] 退出时清理
来源：http://dali.sysykeji.top/Article/details/gt2bgzjuvwi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xinyue.icu/Article/details/gt2itsbriqj.html

[R35] 后台执行并等待
来源：http://dali.jinqigfzy.top/Article/details/gt2aublxwdb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hnqzz.top/Article/details/gt2egoxmdjm.html

[R36] 并发执行多个任务
来源：http://dali.chenlongwang.top/Article/details/gt2aecqhajw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gzhubu.top/Article/details/gt2cpeqyscb.html

[R37] 把输出赋给变量
来源：http://dali.hysaishi.cn/Article/details/gt2kpnapgcg.html

files=$(ls -1)
来源：http://dali.mhx1999.top/Article/details/gt2wmjirezq.html

[R38] 管道串联
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nlyurvcn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2drgawmus.html

[R39] 重定向标准输出与错误
来源：http://dali.jinqigufen.top/Article/details/gt2ujmruhqy.html

cmd > out.log 2>&1
来源：http://dali.yueranfly.top/Article/details/gt2dnqczyyf.html

[R40] 追加写日志
来源：http://dali.zhongyouzk.top/Article/details/gt2pjztltkv.html

echo "log" >> out.log
来源：http://dali.jqgufenzy.top/Article/details/gt2sugoyqiq.html

[R41] 丢弃输出
来源：http://dali.iojbl.cn/Article/details/gt2bqjsthpu.html

cmd >/dev/null 2>&1
来源：http://dali.sxryk.cn/Article/details/gt2vfnazvrd.html

[R42] 输入重定向
来源：http://dali.shangyingyoupin.top/Article/details/gt2qblfedse.html

wc -l < a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ixsjwfyk.html

[R43] 按名字查找文件
来源：http://dali.yonumen.top/Article/details/gt2eidvygjd.html

find . -name "*.log" -type f
来源：http://dali.chenlongwang.top/Article/details/gt2sxhmuvpa.html

[R44] 按修改时间查找
来源：http://dali.redwolf501.top/Article/details/gt2twgoqfov.html

find . -mtime -7 -type f
来源：http://dali.zdqjudy.top/Article/details/gt2njlfvzex.html

[R45] 批量删除
来源：http://dali.zdqjudy.top/Article/details/gt2njaxrsvd.html


<!-- 参考信息 -->