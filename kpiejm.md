代发 wailian999

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.sxryk.cn/Article/details/gtywvoydkf.html

[Q09] 创建唯一索引
来源：http://dali.yangfankeji.com/Article/details/gtotlodaud.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.iojbl.cn/Article/details/gtzjrasqos.html

[Q10] 插入单行
来源：http://dali.jqgufenzy.top/Article/details/gtycbksgyd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.andypj.xyz/Article/details/gtrkkohnmi.html

[Q11] 一次插入多行
来源：http://dali.haohaochexian.top/Article/details/gtvmljjuqr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shuidangran.top/Article/details/gtvtuaifrm.html

[Q12] 插入后取自增 ID
来源：http://dali.yuxming.cn/Article/details/gtmwknkkqp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cucudq.cn/Article/details/gtxophvgil.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.guowangkeji.top/Article/details/gtqjdhxcly.html

[Q13] 忽略重复插入
来源：http://dali.hywenlv.cn/Article/details/gtjbuinpme.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinqigfzy.top/Article/details/gtjqjavhet.html

[Q14] 存在则更新（upsert）
来源：http://dali.0kj1m.cn/Article/details/gtndsrchxr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.tianlin.xyz/Article/details/gtqgicnpnc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.c1oappe.top/Article/details/gtkrxhbvzz.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gthebncpjl.html

SELECT * FROM users;
来源：http://dali.sweek.top/Article/details/gtnarrnhyq.html

[Q16] 查询指定列
来源：http://dali.kuanghao11.cn/Article/details/gtcfxgwxlu.html

SELECT id, name FROM users;
来源：http://dali.yonumen.top/Article/details/gtbcemsvsi.html

[Q17] 条件查询
来源：http://dali.yangfankeji.com/Article/details/gtnfxmewwa.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jqgfzy.top/Article/details/gtyfkmjims.html

[Q18] 模糊匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtclzzeurd.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jianghu66.top/Article/details/gtkwyaoidu.html

[Q19] 范围查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gtarvuhvfp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zdqjudy.top/Article/details/gtzezgpebi.html

[Q20] IN 列表
来源：http://dali.jlsjyb.cn/Article/details/gtgryredjg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gotoacloud.top/Article/details/gttbqnrudj.html

[Q21] 空值判断
来源：http://dali.sysykeji.top/Article/details/gtjkwgbfgo.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.dianchejie.cn/Article/details/gtuoubjefg.html

[Q22] 排序
来源：http://dali.xylfe.cn/Article/details/gtrihkycqk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.mhx1999.top/Article/details/gtfdqbdmuk.html

[Q23] 分页
来源：http://dali.jyoumei.cn/Article/details/gtlsjumwtu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.daria6918.cn/Article/details/gtdczbergh.html

[Q24] 去重
来源：http://dali.tianlin.xyz/Article/details/gtaajdbfft.html

SELECT DISTINCT city FROM users;
来源：http://dali.havefunace.top/Article/details/gtfwocjuau.html

[Q25] 只取前 N 条
来源：http://dali.c1oappe.top/Article/details/gttncfssrt.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cqqwz.cn/Article/details/gtyfkvsdhb.html

[Q26] 计数
来源：http://dali.ppjwa.cn/Article/details/gtbxgaxkpr.html

SELECT COUNT(*) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtqtzvltic.html

[Q27] 条件计数
来源：http://dali.shangyingyoupin.top/Article/details/gtmulqdfkt.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.guannengcc.top/Article/details/gtpqbavdqf.html

[Q28] 求和与平均
来源：http://dali.shanyushiyangtech.top/Article/details/gtfmumghcu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gtedaqwmvd.html

[Q29] 最大最小值
来源：http://dali.yuxming.cn/Article/details/gtctbwcqyl.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtwzmyiwpx.html

[Q30] 分组统计
来源：http://dali.xuanzx.com/Article/details/gtndpafwsu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cdnleiting.top/Article/details/gtsbjzyhcw.html

[Q31] 分组后过滤
来源：http://dali.hnqzz.top/Article/details/gtvaymarwg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jlsjyb.cn/Article/details/gtwhstvsjk.html

[Q32] 分组拼接字符串
来源：http://dali.yvedp.cn/Article/details/gtowroofve.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xuanzx.com/Article/details/gtvzangrag.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ppjwa.cn/Article/details/gtdrsnclfu.html

[Q33] 多列分组
来源：http://dali.jinghuilouyu.cn/Article/details/gtlaxbjiwa.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ydzc1.top/Article/details/gtaqmejzln.html

[Q34] 每组取第一条
来源：http://dali.gotoacloud.top/Article/details/gtthvmsnga.html

SELECT * FROM (
来源：http://dali.fzhhl.top/Article/details/gthztkqwfr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xuetiantiany.cn/Article/details/gttgaoptkh.html

) t WHERE rn = 1;
来源：http://dali.yj20258888.top/Article/details/gtnooxcvkj.html

[Q35] 内连接
来源：http://dali.yvedp.cn/Article/details/gtlgskhdgs.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zycfv.cn/Article/details/gtiuinavyn.html

[Q36] 左连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtarvmzkfo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yongpay.top/Article/details/gtuipafqqf.html

[Q37] 右连接
来源：http://dali.cdnleiting.top/Article/details/gtdkryjmup.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yj202588.top/Article/details/gtlwtjxenr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jinqigfzy.top/Article/details/gtujrzbjfb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.wangshuangyany.cn/Article/details/gttsxrhqrv.html

[Q39] 自连接（查上下级）
来源：http://dali.gaohongyu789.top/Article/details/gthhdylrlg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.wangdashe.top/Article/details/gtfnovwtuz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hongshengwenyu.top/Article/details/gtdenkzezx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shuidangran.top/Article/details/gttoskwpkc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jinqigufen.top/Article/details/gtrjkguuaa.html

[Q41] 多表连接
来源：http://dali.shuidangran.top/Article/details/gtwqrmtpfg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.aibaodan.cn/Article/details/gteclwkzcw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jiagoushi.top/Article/details/gtmvwxnsgv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.birdmap.top/Article/details/gtzuneurfg.html

[Q42] 连接条件附加过滤
来源：http://dali.gotoacloud.top/Article/details/gtixczbsge.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ivvv.top/Article/details/gthpqsnpgy.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.bjfxy.top/Article/details/gtmccgxviy.html

[Q43] 标量子查询
来源：http://dali.sufxvd.cn/Article/details/gtartwllda.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sxryk.cn/Article/details/gtigsbthnq.html

[Q44] IN 子查询
来源：http://dali.c1oappe.top/Article/details/gtqtkyoszc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.wangshuangyany.cn/Article/details/gtpjvlydcy.html

[Q45] EXISTS 判断存在
来源：http://dali.hnqzz.top/Article/details/gtjlyfvivp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.birdmap.top/Article/details/gtxsxzfqxg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhoulong.xyz/Article/details/gtcdjpsefp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gaohongyu789.top/Article/details/gtrievngym.html

[Q47] 与平均值比较
来源：http://dali.hfpthk.cn/Article/details/gtjqkmhvfb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.aizwys.cn/Article/details/gtipughrhs.html

[Q48] CTE 公用表表达式
来源：http://dali.yueranfly.top/Article/details/gtqkccibbr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.wangdashe.top/Article/details/gtqdundcif.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.kuanghao11.cn/Article/details/gtcxmbxppu.html

[Q49] 更新单行
来源：http://dali.hongshengwenyu.top/Article/details/gtfpqogcfe.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinqigufen.top/Article/details/gtkcinzapp.html

[Q50] 批量更新
来源：http://dali.hfpthk.cn/Article/details/gtsejahmjd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhixingplan.top/Article/details/gtdjaqvrkl.html

[Q51] 用子查询更新
来源：http://dali.jqgfzy.top/Article/details/gtfzhozcpt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sysykeji.top/Article/details/gtvatxjjdu.html

[Q52] 删除指定行
来源：http://dali.hongshengwenyu.top/Article/details/gtpzlllafy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yuxming.cn/Article/details/gtlphnnvwu.html

[Q53] 按条件删除
来源：http://dali.fengsongda.top/Article/details/gtwjxocwzi.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.mhx1999.top/Article/details/gtrdijxkpi.html

[Q54] 清空表
来源：http://dali.iojbl.cn/Article/details/gtgbxmelgj.html

TRUNCATE TABLE logs;
来源：http://dali.jyoumei.cn/Article/details/gtbyfjryhh.html

[Q55] 排名（并列占位）
来源：http://dali.316326.xyz/Article/details/gtslyukaqk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hammf.cn/Article/details/gtxckljtbk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xuetiantiany.cn/Article/details/gtjojpryxu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jlsjyb.cn/Article/details/gtpgjdbrzp.html

[Q57] 行号
来源：http://dali.yvedp.cn/Article/details/gtniefqbse.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtmjbiqmlw.html

[Q58] 累计求和
来源：http://dali.yueranfly.top/Article/details/gticssvknm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ivvv.top/Article/details/gtwxnzoyjz.html

[Q59] 分组内累计
来源：http://dali.zhixingplan.top/Article/details/gthtveajlp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtprtjbqvs.html

[Q60] 取上一行 / 下一行
来源：http://dali.sufxvd.cn/Article/details/gtlwwnuupa.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gogol.net.cn/Article/details/gtqjazbhos.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gtvoniuava.html

[Q61] 移动平均
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmlotsgih.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gtvnixloli.html

[Q62] 分组占比
来源：http://dali.cdnleiting.top/Article/details/gttidjgloq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinghuilouyu.cn/Article/details/gtajzwccxt.html

[Q63] 开启事务
来源：http://dali.jinghuilouyu.cn/Article/details/gtxoszdxed.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.wangshuangyany.cn/Article/details/gtgwhecmiu.html

[Q64] 提交事务
来源：http://dali.tanke756.top/Article/details/gtpvxbhdgz.html

COMMIT;
来源：http://dali.hnqzz.top/Article/details/gtwocdehrq.html

[Q65] 回滚事务
来源：http://dali.meibo888.top/Article/details/gtcnxvmyue.html

ROLLBACK;
来源：http://dali.shuidangran.top/Article/details/gtzuwnvyzz.html

[Q66] 行锁查询
来源：http://dali.jinghuilouyu.cn/Article/details/gtsiktgktx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.redwolf501.top/Article/details/gtjnjjlvuz.html

[Q67] 设置隔离级别
来源：http://dali.hywenlv.cn/Article/details/gtlhqkwwsr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.daxiang520.top/Article/details/gteoceakuy.html

[Q68] 保存点
来源：http://dali.mhx1999.top/Article/details/gtrybgcctr.html

SAVEPOINT sp1;
来源：http://dali.chenjidiqi.icu/Article/details/gtmonpgndy.html

ROLLBACK TO sp1;
来源：http://dali.hammf.cn/Article/details/gtzqrouplf.html

[Q69] 查看执行计划
来源：http://dali.redwolf501.top/Article/details/gtnydvumky.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gtaofzogah.html

[Q70] 更新统计信息
来源：http://dali.aibaodan.cn/Article/details/gtxiicoskv.html

ANALYZE TABLE users;
来源：http://dali.pycfn.com/Article/details/gteaaulfez.html

[Q71] 查看建表语句
来源：http://dali.hnqzz.top/Article/details/gtamzbdvdv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenzaomai.com/Article/details/gtbssvxaoi.html

[Q72] 查看索引
来源：http://dali.c1oappe.top/Article/details/gtwgufjald.html

SHOW INDEX FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtxscjkgdv.html

[Q73] 查看表状态
来源：http://dali.zhengqikj.top/Article/details/gtysdeuvvs.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gzhubu.top/Article/details/gttinfkahc.html

[Q74] 强制使用索引
来源：http://dali.xziqi.cn/Article/details/gtaolcuqck.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yuanzhike.top/Article/details/gtryepuuum.html

[Q75] 日期格式化
来源：http://dali.shzxlz.cn/Article/details/gtaxpnehjg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtcviwtomu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gogol.net.cn/Article/details/gtldjmomif.html

[Q76] 按天统计
来源：http://dali.redwolf501.top/Article/details/gtxdcjxjdh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpbiomlrj.html

[Q77] 时间加减
来源：http://dali.cucudq.cn/Article/details/gtoqfsmgle.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xylfe.cn/Article/details/gtmynybqml.html

[Q78] 当前时间
来源：http://dali.zhengqikj.top/Article/details/gtufsucsys.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.sweek.top/Article/details/gttainirtr.html

[Q79] 字符串拼接
来源：http://dali.tanke756.top/Article/details/gtnzjgeugu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.chenjidiqi.icu/Article/details/gtoaohnsyv.html

[Q80] 字符串截取
来源：http://dali.cqqwz.cn/Article/details/gtionhckmj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yj202588.top/Article/details/gtdpndsiry.html

[Q81] 字符串替换
来源：http://dali.hfpthk.cn/Article/details/gtembvougo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.fzhhl.top/Article/details/gtuvxukvuv.html

[Q82] 字符长度与字节长度
来源：http://dali.xuetiantiany.cn/Article/details/gtepszgehs.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.iojbl.cn/Article/details/gtmmuhkvcs.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gtutclttsk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtlfgpfrkn.html

[Q84] 去除首尾空格
来源：http://dali.nanxinkj.top/Article/details/gtmiikutob.html

SELECT TRIM(name) FROM users;
来源：http://dali.zycfv.cn/Article/details/gtxdgpqcbj.html

[Q85] 数值取整
来源：http://dali.ydzc1.top/Article/details/gtkbmpevct.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jiagoushi.top/Article/details/gtawpfoetp.html

[Q86] 读取 JSON 字段
来源：http://dali.jqgufenzy.top/Article/details/gtnwdfggut.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yj202588.top/Article/details/gtsnfmrgmw.html

[Q87] JSON 字段做条件
来源：http://dali.yangfankeji.com/Article/details/gtngpoaruu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cdnleiting.top/Article/details/gtqvtigvsx.html

[Q88] 行转列（条件聚合）
来源：http://dali.quarkkingdee.top/Article/details/gtdysqiuro.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hywenlv.cn/Article/details/gtgeiqtotf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yj20258888.top/Article/details/gtxbcybmaz.html

[Q89] 判断表是否存在
来源：http://dali.jiagoushi.top/Article/details/gtqvtxqfdy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xinyue.icu/Article/details/gtzalhshon.html

[Q90] 生成序号列
来源：http://dali.daria6918.cn/Article/details/gtkhbmkxea.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jianghu66.top/Article/details/gthbmnxule.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtsneviatb.html

R. Bash 专题
来源：http://dali.fengsongda.top/Article/details/gtluumskdo.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtakzjpfjc.html

[R01] shebang 与严格模式
来源：http://dali.xinyue.icu/Article/details/gtzfsknirq.html

#!/usr/bin/env bash
来源：http://dali.xziqi.cn/Article/details/gtxnirulvo.html

set -euo pipefail
来源：http://dali.svipenyu.cn/Article/details/gtlgfnwasc.html

[R02] 变量赋值与使用
来源：http://dali.gaohongyu789.top/Article/details/gtkrzlasxz.html

name="Tom"; echo "$name"
来源：http://dali.chenlongwang.top/Article/details/gtgmkonpux.html

[R03] 只读变量
来源：http://dali.tanke756.top/Article/details/gttdntnafv.html

readonly PI=3.14
来源：http://dali.xuanzx.com/Article/details/gthrgesdye.html

[R04] 位置参数
来源：http://dali.daxiang520.top/Article/details/gtltxqvnyu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.sweek.top/Article/details/gtumqdlxcd.html

[R05] 参数默认值
来源：http://dali.jinghuilouyu.cn/Article/details/gtvcmzqmld.html

name="${1:-default}"
来源：http://dali.aizwys.cn/Article/details/gtfidptguv.html

[R06] 判断命令是否存在
来源：http://dali.snrcjt.cn/Article/details/gteolhuyzh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.nanxinkj.top/Article/details/gthpxyjafc.html

[R07] if 判断文件
来源：http://dali.zycfv.cn/Article/details/gtewxvhjum.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.andypj.xyz/Article/details/gtadwgcqmb.html

[R08] 数值比较
来源：http://dali.cashguo.top/Article/details/gtrovzojqo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhixingplan.top/Article/details/gtyjgpntrd.html

[R09] 字符串比较
来源：http://dali.xylfe.cn/Article/details/gtcdffdjek.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hysaishi.cn/Article/details/gtlgcohyxv.html

[R10] 正则匹配
来源：http://dali.nwbrower.top/Article/details/gtpkvnrcze.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xuanzx.com/Article/details/gtzjhirrea.html

[R11] case 多分支
来源：http://dali.sysykeji.top/Article/details/gtttohlcxm.html

case "$1" in
来源：http://dali.svipenyu.cn/Article/details/gtaaocvqqe.html

start) echo "启动" ;;
来源：http://dali.birdmap.top/Article/details/gteclssjtw.html

stop)  echo "停止" ;;
来源：http://dali.tian-w.cn/Article/details/gtafgksejt.html

*)     echo "未知命令" ;;
来源：http://dali.nanxinkj.top/Article/details/gtemsgcjjf.html

esac
来源：http://dali.zdqjudy.top/Article/details/gtwfvhxcmr.html

[R12] for 遍历文件
来源：http://dali.feifeiyinyue.top/Article/details/gtoekyrqtj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdazziyvy.html

[R13] for 计数循环
来源：http://dali.xziqi.cn/Article/details/gtyjcyfmnb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yuxming.cn/Article/details/gttwyrbdcu.html

[R14] C 风格 for
来源：http://dali.zhongyouzk.top/Article/details/gtsmcdbwgm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.tian-w.cn/Article/details/gtufsvkyeu.html

[R15] while 逐行读文件
来源：http://dali.cqqwz.cn/Article/details/gtuiwdkdrr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtmcaedecy.html

[R16] until 等待条件
来源：http://dali.shzxlz.cn/Article/details/gtsjzglsdu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.dashuyun.cn/Article/details/gtbtifqddc.html

[R17] 数组定义与取值
来源：http://dali.pengpengdd.cyou/Article/details/gtjimumzop.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shzxlz.cn/Article/details/gttcbxgwwi.html

[R18] 遍历数组
来源：http://dali.hnqzz.top/Article/details/gtkmvkfbbh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhongyouzk.top/Article/details/gtrmzrcgok.html

[R19] 数组长度
来源：http://dali.haohaochexian.top/Article/details/gtltgzavon.html

echo "${#arr[@]}"
来源：http://dali.aizwys.cn/Article/details/gtnobczyrp.html

[R20] 关联数组（字典）
来源：http://dali.cashguo.top/Article/details/gtmrooeabv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yuxming.cn/Article/details/gtgheqhsgt.html

[R21] 字符串长度
来源：http://dali.hywenlv.cn/Article/details/gtxsmsvafy.html

echo "${#s}"
来源：http://dali.kuanghao11.cn/Article/details/gtpuucmqzj.html

[R22] 截取子串
来源：http://dali.yuxming.cn/Article/details/gtcqwhfbfy.html

echo "${s:0:5}"
来源：http://dali.haohaochexian.top/Article/details/gtzrzewwoy.html

[R23] 字符串替换
来源：http://dali.nwbrower.top/Article/details/gtafvbujwo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yj20258888.top/Article/details/gtjbtadres.html

[R24] 大小写转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtpxwtthpe.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ivvv.top/Article/details/gtmzxginfr.html

[R25] 去后缀 / 去前缀
来源：http://dali.hfpthk.cn/Article/details/gtwjnppzkh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hywenlv.cn/Article/details/gtsbktoljl.html

[R26] 命令替换
来源：http://dali.tian-w.cn/Article/details/gtibnsshfk.html

now=$(date +%F); echo "$now"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvbuhjxyr.html

[R27] 算术展开
来源：http://dali.quarkkingdee.top/Article/details/gtqeedivyk.html

echo $((1 + 2 * 3))
来源：http://dali.ywan-chungtsiang.top/Article/details/gthwflmvpt.html

[R28] 浮点运算
来源：http://dali.chenlongwang.top/Article/details/gtjqddqhcw.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinyuanbaomall.cn/Article/details/gtddewktdy.html

[R29] 定义函数
来源：http://dali.yonumen.top/Article/details/gtxwhjcajk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jianghu66.top/Article/details/gtfmoyuwju.html

[R30] 函数返回状态码
来源：http://dali.shanyushiyangtech.top/Article/details/gtdinrrcrp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ydzc1.top/Article/details/gtquhslbyz.html

[R31] 局部变量
来源：http://dali.aibaodan.cn/Article/details/gtkxnvmaoc.html

f() { local x=1; echo "$x"; }
来源：http://dali.shuidangran.top/Article/details/gtsyasvqae.html

[R32] 参数个数校验
来源：http://dali.jianghu66.top/Article/details/gtjsbieily.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.tian-w.cn/Article/details/gtcfiygysd.html

[R33] 捕获错误并提示行号
来源：http://dali.hfpthk.cn/Article/details/gtrmbgnksm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.chenjidiqi.icu/Article/details/gtujtdkego.html

[R34] 退出时清理
来源：http://dali.sweek.top/Article/details/gthqaurujq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ppjwa.cn/Article/details/gtpayjrsic.html

[R35] 后台执行并等待
来源：http://dali.daxiang520.top/Article/details/gtqkltrghm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.quarkkingdee.top/Article/details/gtitajhniu.html

[R36] 并发执行多个任务
来源：http://dali.quarkkingdee.top/Article/details/gtygxjsumk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yanxiufei.cn/Article/details/gthmrdfbzf.html

[R37] 把输出赋给变量
来源：http://dali.jinqigfzy.top/Article/details/gtlblmckvk.html

files=$(ls -1)
来源：http://dali.snrcjt.cn/Article/details/gtaoauhpgh.html

[R38] 管道串联
来源：http://dali.aizwys.cn/Article/details/gtpjheyjee.html

cat a.txt | grep -i error | wc -l
来源：http://dali.guannengcc.top/Article/details/gtbkoqaaou.html

[R39] 重定向标准输出与错误
来源：http://dali.chenlongwang.top/Article/details/gtqnnbiorl.html

cmd > out.log 2>&1
来源：http://dali.zhixingplan.top/Article/details/gtvaywfxnp.html

[R40] 追加写日志
来源：http://dali.jyoumei.cn/Article/details/gtnlguqivk.html

echo "log" >> out.log
来源：http://dali.yonumen.top/Article/details/gtuaaxgfgd.html

[R41] 丢弃输出
来源：http://dali.chenzaomai.com/Article/details/gtfjjxachn.html

cmd >/dev/null 2>&1
来源：http://dali.haohaochexian.top/Article/details/gtgzyklumk.html

[R42] 输入重定向
来源：http://dali.bjfxy.top/Article/details/gtfanjmqgx.html

wc -l < a.txt
来源：http://dali.yvedp.cn/Article/details/gtynrcoyqd.html

[R43] 按名字查找文件
来源：http://dali.yangfankeji.com/Article/details/gtenpxntwp.html

find . -name "*.log" -type f
来源：http://dali.smart0.xyz/Article/details/gtwdjtiach.html

[R44] 按修改时间查找
来源：http://dali.feifeiyinyue.top/Article/details/gtjodqbott.html

find . -mtime -7 -type f
来源：http://dali.yongpay.top/Article/details/gtyoxrqpol.html

[R45] 批量删除
来源：http://dali.zycfv.cn/Article/details/gttthhlolo.html

find . -name "*.tmp" -delete
来源：http://dali.jinghuilouyu.cn/Article/details/gtwobydkhu.html

[R46] 递归替换文件内容
来源：http://dali.xuanzx.com/Article/details/gtzdlgmyoa.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xinyue.icu/Article/details/gtjglrwxxf.html

[R47] sed 单行替换
来源：http://dali.jinqigfzy.top/Article/details/gtctkciais.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jqgfzy.top/Article/details/gtqwgjdzpb.html

[R48] awk 取指定列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcasvpqoh.html

awk '{print $1, $3}' a.txt
来源：http://dali.chenzaomai.com/Article/details/gturunmmme.html

[R49] awk 带条件
来源：http://dali.chenzaomai.com/Article/details/gtveuswscj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.tian-w.cn/Article/details/gtztzfhipk.html

[R50] awk 求和
来源：http://dali.nanxinkj.top/Article/details/gtqdwkgwch.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtvnwasgrr.html

[R51] 排序去重取前几
来源：http://dali.aibaodan.cn/Article/details/gtqdyjdfmq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.nanxinkj.top/Article/details/gtqjhpjcql.html

[R52] 统计行数
来源：http://dali.jinqigfzy.top/Article/details/gtniudhwxf.html

wc -l a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtdlkpkhwx.html

[R53] 查看文件头与实时尾
来源：http://dali.guowangkeji.top/Article/details/gtuxljvbpc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhoulong.xyz/Article/details/gttitzmyro.html

[R54] 比较两个文件
来源：http://dali.shangyingyoupin.top/Article/details/gtfetmgfkn.html

diff a.txt b.txt
来源：http://dali.yvedp.cn/Article/details/gtwihqkarm.html

[R55] 压缩与解压
来源：http://dali.nanxuanxn.top/Article/details/gtunybyzdr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yj20258888.top/Article/details/gtcmqkjsna.html

[R56] 远程拷贝
来源：http://dali.guowangkeji.top/Article/details/gtyedourbp.html

scp file user@host:/path/
来源：http://dali.meibo888.top/Article/details/gtvqcfapyj.html

[R57] 远程执行命令
来源：http://dali.jlsjyb.cn/Article/details/gtjxfdjyqi.html


<!-- 参考信息 -->