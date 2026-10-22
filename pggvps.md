代发 wailian999

CREATE TABLE users (
来源：http://dali.ivvv.top/Article/details/gt2ejlafysf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.kuanghao11.cn/Article/details/gt2zcmskald.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhixingplan.top/Article/details/gt2qeehjexo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jinqigfzy.top/Article/details/gt2jeuxufjf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xziqi.cn/Article/details/gt2rsjysoua.html

);
来源：http://dali.zycfv.cn/Article/details/gt2lnzovfpe.html

[Q02] 创建带外键的表
来源：http://dali.yanxiufei.cn/Article/details/gt2fugzxyfp.html

CREATE TABLE orders (
来源：http://dali.cashguo.top/Article/details/gt2lumrmylb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sxryk.cn/Article/details/gt2ktehatni.html

user_id INT NOT NULL,
来源：http://dali.guannengcc.top/Article/details/gt2skfgqnye.html

amount DECIMAL(10, 2),
来源：http://dali.kuanghao11.cn/Article/details/gt2fsqmuogb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.meibo888.top/Article/details/gt2wrguodfk.html

);
来源：http://dali.hongshengwenyu.top/Article/details/gt2hztkucmx.html

[Q03] 增加列
来源：http://dali.hywenlv.cn/Article/details/gt2ikicssji.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sufxvd.cn/Article/details/gt2laeqrqgh.html

[Q04] 修改列类型
来源：http://dali.shangyingyoupin.top/Article/details/gt2kbudqfem.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zycfv.cn/Article/details/gt2cgrvbckm.html

[Q05] 重命名列
来源：http://dali.gzhubu.top/Article/details/gt2dqhaixod.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.daxiang520.top/Article/details/gt2bvpgxpya.html

[Q06] 删除列
来源：http://dali.hywenlv.cn/Article/details/gt2srtqxftl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.tian-w.cn/Article/details/gt2yhgmeqqy.html

[Q07] 删除表
来源：http://dali.shzxlz.cn/Article/details/gt2jgkyyvut.html

DROP TABLE IF EXISTS orders;
来源：http://dali.aibaodan.cn/Article/details/gt2tijwbxdw.html

[Q08] 创建普通索引
来源：http://dali.jqgfzy.top/Article/details/gt2jejjngwx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.guannengcc.top/Article/details/gt2wwhgjlzy.html

[Q09] 创建唯一索引
来源：http://dali.fengsongda.top/Article/details/gt2vacjgajl.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.tian-w.cn/Article/details/gt2usvlqdje.html

[Q10] 插入单行
来源：http://dali.cqqwz.cn/Article/details/gt2mlptyuea.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.smart0.xyz/Article/details/gt2vevjosfi.html

[Q11] 一次插入多行
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pzlhnbav.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yvedp.cn/Article/details/gt2iaxomgwr.html

[Q12] 插入后取自增 ID
来源：http://dali.nanxinkj.top/Article/details/gt2ujpkumdb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.aizwys.cn/Article/details/gt2ardwmpqo.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.sweek.top/Article/details/gt2zbxxdhgy.html

[Q13] 忽略重复插入
来源：http://dali.cucudq.cn/Article/details/gt2rctxmcgg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.pycfn.com/Article/details/gt2jvxrdhkn.html

[Q14] 存在则更新（upsert）
来源：http://dali.shangyingyoupin.top/Article/details/gt2pswlrtcx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yangfankeji.com/Article/details/gt2jwyxpmfj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yj20258888.top/Article/details/gt2tsejvpzu.html

[Q15] 查询全部
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vysfxnah.html

SELECT * FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2hcmkbvyr.html

[Q16] 查询指定列
来源：http://dali.daria6918.cn/Article/details/gt2bhexummm.html

SELECT id, name FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2fjnimnge.html

[Q17] 条件查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bcigrzrn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gt2edrcgsmf.html

[Q18] 模糊匹配
来源：http://dali.cheryme.top/Article/details/gt2ovldmlru.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.nanxinkj.top/Article/details/gt2lxuixzsk.html

[Q19] 范围查询
来源：http://dali.ivvv.top/Article/details/gt2sabcwzzj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xziqi.cn/Article/details/gt2hmoduyab.html

[Q20] IN 列表
来源：http://dali.xziqi.cn/Article/details/gt2aaqcbkzf.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.0kj1m.cn/Article/details/gt2yjzqfiic.html

[Q21] 空值判断
来源：http://dali.yangfankeji.com/Article/details/gt2gsvjljif.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.feifeiyinyue.top/Article/details/gt2gtsvailk.html

[Q22] 排序
来源：http://dali.meibo888.top/Article/details/gt2jmdotuep.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.c1oappe.top/Article/details/gt2gpjackha.html

[Q23] 分页
来源：http://dali.aizwys.cn/Article/details/gt2fjhdtoir.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xuetiantiany.cn/Article/details/gt2tscrzmob.html

[Q24] 去重
来源：http://dali.sufxvd.cn/Article/details/gt2zcumyoeo.html

SELECT DISTINCT city FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2tysmjmar.html

[Q25] 只取前 N 条
来源：http://dali.zhixingplan.top/Article/details/gt2cvmapjpo.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.svipenyu.cn/Article/details/gt2hfrnwkzk.html

[Q26] 计数
来源：http://dali.jinqigufen.top/Article/details/gt2kuxmcgjy.html

SELECT COUNT(*) FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2pqrjsaec.html

[Q27] 条件计数
来源：http://dali.quarkkingdee.top/Article/details/gt2poffcmbf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2nrnfolmh.html

[Q28] 求和与平均
来源：http://dali.tian-w.cn/Article/details/gt2gosnzjux.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sgmlpivv.html

[Q29] 最大最小值
来源：http://dali.yj20258.top/Article/details/gt2ecifyeoo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2inygntho.html

[Q30] 分组统计
来源：http://dali.gzhubu.top/Article/details/gt2udichjqy.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.0kj1m.cn/Article/details/gt2dgfokrwx.html

[Q31] 分组后过滤
来源：http://dali.guowangkeji.top/Article/details/gt2vayufxhh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.sufxvd.cn/Article/details/gt2pgdtfxxs.html

[Q32] 分组拼接字符串
来源：http://dali.jlsjyb.cn/Article/details/gt2qrvsplnw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yj20258.top/Article/details/gt2fxupryem.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.feifeiyinyue.top/Article/details/gt2lbckvbku.html

[Q33] 多列分组
来源：http://dali.fengsongda.top/Article/details/gt2uwzypygt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.mhx1999.top/Article/details/gt2whugjwwh.html

[Q34] 每组取第一条
来源：http://dali.havefunace.top/Article/details/gt2vckujofg.html

SELECT * FROM (
来源：http://dali.chenjidiqi.icu/Article/details/gt2gqfapsai.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ybcxt.top/Article/details/gt2imwpixbt.html

) t WHERE rn = 1;
来源：http://dali.haohaochexian.top/Article/details/gt2mmaertoh.html

[Q35] 内连接
来源：http://dali.cheryme.top/Article/details/gt2kytnumqr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.havefunace.top/Article/details/gt2dvvxpede.html

[Q36] 左连接
来源：http://dali.guannengcc.top/Article/details/gt2vdkqrsuc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.tianlin.xyz/Article/details/gt2yfyxowvj.html

[Q37] 右连接
来源：http://dali.zhengqikj.top/Article/details/gt2kkcjqqlo.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.meibo888.top/Article/details/gt2fcxfryll.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yongpay.top/Article/details/gt2tbfyqbed.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.quarkkingdee.top/Article/details/gt2efadswpc.html

[Q39] 自连接（查上下级）
来源：http://dali.quarkkingdee.top/Article/details/gt2sjndzfoh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yj202588.top/Article/details/gt2jarmenqn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.nanxinkj.top/Article/details/gt2luzcstws.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gotoacloud.top/Article/details/gt2jwzhaqix.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.nanxinkj.top/Article/details/gt2wwmicmne.html

[Q41] 多表连接
来源：http://dali.ehwqpu.com/Article/details/gt2vxehqclo.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yonumen.top/Article/details/gt2cjzwiint.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ydmxhmwt.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hfpthk.cn/Article/details/gt2bapbaemr.html

[Q42] 连接条件附加过滤
来源：http://dali.cucudq.cn/Article/details/gt2quwrvhqh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gotoacloud.top/Article/details/gt2ugzlrrzs.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xziqi.cn/Article/details/gt2ywjsdsjq.html

[Q43] 标量子查询
来源：http://dali.yueranfly.top/Article/details/gt2jrzdhmyh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.nanxinkj.top/Article/details/gt2sdqjdgmj.html

[Q44] IN 子查询
来源：http://dali.yueranfly.top/Article/details/gt2dlqeigrn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2foyoauxd.html

[Q45] EXISTS 判断存在
来源：http://dali.tianlin.xyz/Article/details/gt2mrlrnxee.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuanzx.com/Article/details/gt2whdnnsoe.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jyoumei.cn/Article/details/gt2mfkvfocg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.kuanghao11.cn/Article/details/gt2fcllsrcl.html

[Q47] 与平均值比较
来源：http://dali.yonumen.top/Article/details/gt2whcwuphc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.sufxvd.cn/Article/details/gt2zfuokbih.html

[Q48] CTE 公用表表达式
来源：http://dali.ybcxt.top/Article/details/gt2uvdbzkin.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhiwuduotai.top/Article/details/gt2cdbjmmhu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jqgufenzy.top/Article/details/gt2hrvzhlfz.html

[Q49] 更新单行
来源：http://dali.hammf.cn/Article/details/gt2ccxuiftf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hongshengwenyu.top/Article/details/gt2nwibbixe.html

[Q50] 批量更新
来源：http://dali.nanxuanxn.top/Article/details/gt2thsihhqc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhixingplan.top/Article/details/gt2glbjnsya.html

[Q51] 用子查询更新
来源：http://dali.aibaodan.cn/Article/details/gt2vwmsdowj.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.vqdsnc.cn/Article/details/gt2ojnmtalk.html

[Q52] 删除指定行
来源：http://dali.xinyue.icu/Article/details/gt2agssgxhr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hywenlv.cn/Article/details/gt2vpculnzi.html

[Q53] 按条件删除
来源：http://dali.snrcjt.cn/Article/details/gt2souipkot.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hammf.cn/Article/details/gt2bthwfibj.html

[Q54] 清空表
来源：http://dali.nanxinkj.top/Article/details/gt2qnmtjpey.html

TRUNCATE TABLE logs;
来源：http://dali.shzxlz.cn/Article/details/gt2xwvzzlje.html

[Q55] 排名（并列占位）
来源：http://dali.yuxming.cn/Article/details/gt2khwjfnsh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cashguo.top/Article/details/gt2cihxoaqe.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tipqbmml.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gzhubu.top/Article/details/gt2ruahxydr.html

[Q57] 行号
来源：http://dali.cqqwz.cn/Article/details/gt2bfhqqbbf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2jacgprxn.html

[Q58] 累计求和
来源：http://dali.mhx1999.top/Article/details/gt2joigthze.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yueranfly.top/Article/details/gt2konucwdu.html

[Q59] 分组内累计
来源：http://dali.zhixingplan.top/Article/details/gt2snstofus.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gt2rxirtdil.html

[Q60] 取上一行 / 下一行
来源：http://dali.sysykeji.top/Article/details/gt2hddnqsiu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sysykeji.top/Article/details/gt2mpxyqjyi.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gt2piopobqe.html

[Q61] 移动平均
来源：http://dali.yj20258888.top/Article/details/gt2vvezlofz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gt2ejogusji.html

[Q62] 分组占比
来源：http://dali.chenlongwang.top/Article/details/gt2reqvttap.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zycfv.cn/Article/details/gt2skynxqlg.html

[Q63] 开启事务
来源：http://dali.0kj1m.cn/Article/details/gt2umvdorss.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.mhx1999.top/Article/details/gt2lwqxocfj.html

[Q64] 提交事务
来源：http://dali.guannengcc.top/Article/details/gt2vuuwjvhu.html

COMMIT;
来源：http://dali.zhoulong.xyz/Article/details/gt2zkxhhmaz.html

[Q65] 回滚事务
来源：http://dali.zdqjudy.top/Article/details/gt2enpetlfh.html

ROLLBACK;
来源：http://dali.yuanzhike.top/Article/details/gt2ntbzjsbk.html

[Q66] 行锁查询
来源：http://dali.shzxlz.cn/Article/details/gt2jsunnrbq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ydzc1.top/Article/details/gt2hxmrgrfz.html

[Q67] 设置隔离级别
来源：http://dali.ybcxt.top/Article/details/gt2fzznyhlu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ivvv.top/Article/details/gt2hkydszhu.html

[Q68] 保存点
来源：http://dali.jinqigufen.top/Article/details/gt2nmunkcze.html

SAVEPOINT sp1;
来源：http://dali.cdnleiting.top/Article/details/gt2gimwbhmb.html

ROLLBACK TO sp1;
来源：http://dali.c1oappe.top/Article/details/gt2afsyxsgf.html

[Q69] 查看执行计划
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bkstlnqv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yuanzhike.top/Article/details/gt2mteoehcl.html

[Q70] 更新统计信息
来源：http://dali.bjfxy.top/Article/details/gt2aswjbfpi.html

ANALYZE TABLE users;
来源：http://dali.tianlin.xyz/Article/details/gt2epimoftp.html

[Q71] 查看建表语句
来源：http://dali.cucudq.cn/Article/details/gt2yxoboxxn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yangfankeji.com/Article/details/gt2etbvajtd.html

[Q72] 查看索引
来源：http://dali.feifeiyinyue.top/Article/details/gt2kngdftvq.html

SHOW INDEX FROM users;
来源：http://dali.meibo888.top/Article/details/gt2audwltjt.html

[Q73] 查看表状态
来源：http://dali.hysaishi.cn/Article/details/gt2eipfdmcq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qiicxgst.html

[Q74] 强制使用索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gibtbnty.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.guowangkeji.top/Article/details/gt2crjurkyg.html

[Q75] 日期格式化
来源：http://dali.xuanzx.com/Article/details/gt2kwtkzybp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.mhx1999.top/Article/details/gt2phyliorz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.kuanghao11.cn/Article/details/gt2lefyzpcb.html

[Q76] 按天统计
来源：http://dali.hysaishi.cn/Article/details/gt2vokzdbti.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.tian-w.cn/Article/details/gt2arlajxww.html

[Q77] 时间加减
来源：http://dali.yangfankeji.com/Article/details/gt2vqlkhfji.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.chenlongwang.top/Article/details/gt2ntgwmzon.html

[Q78] 当前时间
来源：http://dali.birdmap.top/Article/details/gt2hiwrluia.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.aibaodan.cn/Article/details/gt2xoybavfk.html

[Q79] 字符串拼接
来源：http://dali.feifeiyinyue.top/Article/details/gt2hxeeuwpw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.birdmap.top/Article/details/gt2ybydcoyy.html

[Q80] 字符串截取
来源：http://dali.hysaishi.cn/Article/details/gt2idijzrko.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2hnludpha.html

[Q81] 字符串替换
来源：http://dali.bjfxy.top/Article/details/gt2jrsoxkfy.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2eimnuisa.html

[Q82] 字符长度与字节长度
来源：http://dali.0kj1m.cn/Article/details/gt2hmcivjjp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yongpay.top/Article/details/gt2qjlaaeys.html

[Q83] 大小写转换
来源：http://dali.yueranfly.top/Article/details/gt2zfztfmob.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gt2tlrhlcbm.html

[Q84] 去除首尾空格
来源：http://dali.jinqigufen.top/Article/details/gt2iyrptlgs.html

SELECT TRIM(name) FROM users;
来源：http://dali.zycfv.cn/Article/details/gt2vjnxbmet.html

[Q85] 数值取整
来源：http://dali.ybcxt.top/Article/details/gt2xqrywrhx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sufxvd.cn/Article/details/gt2dcryketp.html

[Q86] 读取 JSON 字段
来源：http://dali.chenjidiqi.icu/Article/details/gt2usthttez.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.aibaodan.cn/Article/details/gt2ocdyvvae.html

[Q87] JSON 字段做条件
来源：http://dali.yangfankeji.com/Article/details/gt2beuounpi.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lzierjcv.html

[Q88] 行转列（条件聚合）
来源：http://dali.9152youxi.cn/Article/details/gt2viaaeqtk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhiwuduotai.top/Article/details/gt2svgkpomf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sxryk.cn/Article/details/gt2jomufswe.html

[Q89] 判断表是否存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xvjivbpn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nanxinkj.top/Article/details/gt2jfnsqcek.html

[Q90] 生成序号列
来源：http://dali.chenlongwang.top/Article/details/gt2knjhsidz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zycfv.cn/Article/details/gt2orlchvgf.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2zbwtlfii.html

R. Bash 专题
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pibvqiwz.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2katdbxap.html

[R01] shebang 与严格模式
来源：http://dali.xuetiantiany.cn/Article/details/gt2xbkyktvr.html

#!/usr/bin/env bash
来源：http://dali.snrcjt.cn/Article/details/gt2sopycomq.html

set -euo pipefail
来源：http://dali.fzhhl.top/Article/details/gt2rireoywe.html

[R02] 变量赋值与使用
来源：http://dali.gogol.net.cn/Article/details/gt2ofbenfsk.html

name="Tom"; echo "$name"
来源：http://dali.sysykeji.top/Article/details/gt2muxzzwya.html

[R03] 只读变量
来源：http://dali.daxiang520.top/Article/details/gt2phzajklt.html

readonly PI=3.14
来源：http://dali.c1oappe.top/Article/details/gt2vouwhurm.html

[R04] 位置参数
来源：http://dali.316326.xyz/Article/details/gt2cmuyxotq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.mhx1999.top/Article/details/gt2qyyorofs.html

[R05] 参数默认值
来源：http://dali.316326.xyz/Article/details/gt2webdydai.html

name="${1:-default}"
来源：http://dali.nanxinkj.top/Article/details/gt2siahacfm.html

[R06] 判断命令是否存在
来源：http://dali.cheryme.top/Article/details/gt2wfejhufx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.c1oappe.top/Article/details/gt2ejvjsjrl.html

[R07] if 判断文件
来源：http://dali.chenzaomai.com/Article/details/gt2gkloxetj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xuetiantiany.cn/Article/details/gt2vstaksoy.html

[R08] 数值比较
来源：http://dali.zhiwuduotai.top/Article/details/gt2lrzndkld.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.mhx1999.top/Article/details/gt2omivupdn.html

[R09] 字符串比较
来源：http://dali.zhoulong.xyz/Article/details/gt2rtosclsh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hywenlv.cn/Article/details/gt2pkuykjfe.html

[R10] 正则匹配
来源：http://dali.yj20258.top/Article/details/gt2eszbzqjz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.nwbrower.top/Article/details/gt2gppgbmus.html

[R11] case 多分支
来源：http://dali.sweek.top/Article/details/gt2ikyrxwtn.html

case "$1" in
来源：http://dali.kuanghao11.cn/Article/details/gt2wuvcvckp.html

start) echo "启动" ;;
来源：http://dali.cashguo.top/Article/details/gt2vnuhtrax.html

stop)  echo "停止" ;;
来源：http://dali.wangdashe.top/Article/details/gt2sezrssfr.html

*)     echo "未知命令" ;;
来源：http://dali.sufxvd.cn/Article/details/gt2wgshjply.html

esac
来源：http://dali.xziqi.cn/Article/details/gt2bwkwztut.html

[R12] for 遍历文件
来源：http://dali.nwbrower.top/Article/details/gt2iccnffag.html

for f in *.txt; do echo "$f"; done
来源：http://dali.pycfn.com/Article/details/gt2fedihyar.html

[R13] for 计数循环
来源：http://dali.guannengcc.top/Article/details/gt2qtbfjjsj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zycfv.cn/Article/details/gt2lbdqqiwh.html

[R14] C 风格 for
来源：http://dali.kuanghao11.cn/Article/details/gt2entkrgkz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hysaishi.cn/Article/details/gt2pldlnjrm.html

[R15] while 逐行读文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cielytbv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.fzhhl.top/Article/details/gt2otoevyxp.html

[R16] until 等待条件
来源：http://dali.cucudq.cn/Article/details/gt2yofsomzd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hysaishi.cn/Article/details/gt2dmughvnq.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2cwsrbvyr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.guowangkeji.top/Article/details/gt2kokpszev.html

[R18] 遍历数组
来源：http://dali.zhoulong.xyz/Article/details/gt2yplltmjm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hongshengwenyu.top/Article/details/gt2rdkvqkwa.html

[R19] 数组长度
来源：http://dali.fengsongda.top/Article/details/gt2kbszexbm.html

echo "${#arr[@]}"
来源：http://dali.shuidangran.top/Article/details/gt2ybxqxptv.html

[R20] 关联数组（字典）
来源：http://dali.vqdsnc.cn/Article/details/gt2ehzoklic.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cqqwz.cn/Article/details/gt2eltmkhlq.html

[R21] 字符串长度
来源：http://dali.zhengqikj.top/Article/details/gt2pezqnemk.html

echo "${#s}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eeakqphr.html

[R22] 截取子串
来源：http://dali.xuanzx.com/Article/details/gt2txppwmcf.html

echo "${s:0:5}"
来源：http://dali.shzxlz.cn/Article/details/gt2cqtbkhle.html

[R23] 字符串替换
来源：http://dali.yuanzhike.top/Article/details/gt2hwodqrvo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hfpthk.cn/Article/details/gt2auehxvzb.html

[R24] 大小写转换
来源：http://dali.316326.xyz/Article/details/gt2oisvwbfs.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hysaishi.cn/Article/details/gt2daapherr.html

[R25] 去后缀 / 去前缀
来源：http://dali.shuidangran.top/Article/details/gt2unznxtqw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.dianchejie.cn/Article/details/gt2omgwivek.html

[R26] 命令替换
来源：http://dali.yj20258.top/Article/details/gt2akpdkkoj.html

now=$(date +%F); echo "$now"
来源：http://dali.nanxinkj.top/Article/details/gt2lnbcyrzc.html

[R27] 算术展开
来源：http://dali.fengsongda.top/Article/details/gt2lamrlqnv.html

echo $((1 + 2 * 3))
来源：http://dali.hnxiangtu.top/Article/details/gt2ydmoweaw.html

[R28] 浮点运算
来源：http://dali.fengsongda.top/Article/details/gt2taackfrc.html

echo "scale=2; 10/3" | bc
来源：http://dali.gaohongyu789.top/Article/details/gt2dnwcnbrm.html

[R29] 定义函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2zitaeojy.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ppjwa.cn/Article/details/gt2oulxcnrg.html

[R30] 函数返回状态码
来源：http://dali.c1oappe.top/Article/details/gt2budzlxto.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jianghu66.top/Article/details/gt2lsbzunll.html

[R31] 局部变量
来源：http://dali.nwbrower.top/Article/details/gt2bdfvkpfl.html

f() { local x=1; echo "$x"; }
来源：http://dali.yj20258888.top/Article/details/gt2rnisysbn.html

[R32] 参数个数校验
来源：http://dali.haohaochexian.top/Article/details/gt2zjimokwt.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.vqdsnc.cn/Article/details/gt2jrzlhfyl.html

[R33] 捕获错误并提示行号
来源：http://dali.hysaishi.cn/Article/details/gt2lmgqktud.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.smart0.xyz/Article/details/gt2fdstdbny.html

[R34] 退出时清理
来源：http://dali.gogol.net.cn/Article/details/gt2qxfhlpon.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.nanxinkj.top/Article/details/gt2liwbotvn.html

[R35] 后台执行并等待
来源：http://dali.xziqi.cn/Article/details/gt2jizbfsmr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jqgufenzy.top/Article/details/gt2iwtzfdmi.html

[R36] 并发执行多个任务
来源：http://dali.ppjwa.cn/Article/details/gt2dwtuiofj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xuetiantiany.cn/Article/details/gt2oroixqdc.html

[R37] 把输出赋给变量
来源：http://dali.nanxinkj.top/Article/details/gt2mkhqchcm.html

files=$(ls -1)
来源：http://dali.jlsjyb.cn/Article/details/gt2purabffa.html

[R38] 管道串联
来源：http://dali.0kj1m.cn/Article/details/gt2jgtobyxj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yangfankeji.com/Article/details/gt2prknzfnn.html

[R39] 重定向标准输出与错误
来源：http://dali.yanxiufei.cn/Article/details/gt2mwwdvvgz.html

cmd > out.log 2>&1
来源：http://dali.iojbl.cn/Article/details/gt2bbuvhdro.html

[R40] 追加写日志
来源：http://dali.hysaishi.cn/Article/details/gt2aexnvcfj.html

echo "log" >> out.log
来源：http://dali.feifeiyinyue.top/Article/details/gt2kxkzuhoz.html

[R41] 丢弃输出
来源：http://dali.yvedp.cn/Article/details/gt2rpuovtds.html

cmd >/dev/null 2>&1
来源：http://dali.c1oappe.top/Article/details/gt2kitemgrp.html

[R42] 输入重定向
来源：http://dali.xziqi.cn/Article/details/gt2kpdjgzdi.html

wc -l < a.txt
来源：http://dali.tanke756.top/Article/details/gt2jkywtgmw.html

[R43] 按名字查找文件
来源：http://dali.jinqigufen.top/Article/details/gt2kgzzhend.html

find . -name "*.log" -type f
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qmwgkjfm.html

[R44] 按修改时间查找
来源：http://dali.pengpengdd.cyou/Article/details/gt2zjqeiorb.html

find . -mtime -7 -type f
来源：http://dali.hywenlv.cn/Article/details/gt2kyvcnasi.html

[R45] 批量删除
来源：http://dali.sufxvd.cn/Article/details/gt2dbmsvtwb.html


<!-- 参考信息 -->