代发 wailian999

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zdqjudy.top/Article/details/gtzdzwhuuk.html

[Q11] 一次插入多行
来源：http://dali.wangshuangyany.cn/Article/details/gtixcnycvp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.fengsongda.top/Article/details/gtcbtlqshq.html

[Q12] 插入后取自增 ID
来源：http://dali.fzhhl.top/Article/details/gtayrwghex.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.kuanghao11.cn/Article/details/gtdfwsoihh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.tian-w.cn/Article/details/gttazyrbjt.html

[Q13] 忽略重复插入
来源：http://dali.daxiang520.top/Article/details/gtntvvvzmc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ywan-chungtsiang.top/Article/details/gttmpqftpl.html

[Q14] 存在则更新（upsert）
来源：http://dali.yj20258888.top/Article/details/gthjqbusjo.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yuxming.cn/Article/details/gttswhjxcs.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmbtblypr.html

[Q15] 查询全部
来源：http://dali.hnqzz.top/Article/details/gtrdcqvnnu.html

SELECT * FROM users;
来源：http://dali.yj202588.top/Article/details/gtylunlvvn.html

[Q16] 查询指定列
来源：http://dali.ehwqpu.com/Article/details/gtcwvrpaza.html

SELECT id, name FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtqkdprnxg.html

[Q17] 条件查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkplolvvf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.fengsongda.top/Article/details/gtyazefwpr.html

[Q18] 模糊匹配
来源：http://dali.iojbl.cn/Article/details/gtbqqoubxq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.tian-w.cn/Article/details/gtkovknidd.html

[Q19] 范围查询
来源：http://dali.wangshuangyany.cn/Article/details/gtkpktxvmo.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.0kj1m.cn/Article/details/gtaahcnlql.html

[Q20] IN 列表
来源：http://dali.kuanghao11.cn/Article/details/gteeazahpo.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jqgfzy.top/Article/details/gtigrmtzii.html

[Q21] 空值判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzzkktwuv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.bjfxy.top/Article/details/gtbjzxvhwa.html

[Q22] 排序
来源：http://dali.cheryme.top/Article/details/gtpxnstbkd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zdqjudy.top/Article/details/gtadsstrom.html

[Q23] 分页
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnbxzinzc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hnxiangtu.top/Article/details/gtwysddxle.html

[Q24] 去重
来源：http://dali.yj20258.top/Article/details/gteogjclya.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtlsilywox.html

[Q25] 只取前 N 条
来源：http://dali.0kj1m.cn/Article/details/gtjdiihguz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.fzhhl.top/Article/details/gteqvcifks.html

[Q26] 计数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrhqfgaji.html

SELECT COUNT(*) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtxarvrpjc.html

[Q27] 条件计数
来源：http://dali.daria6918.cn/Article/details/gtuexgztdd.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtysizrxxx.html

[Q28] 求和与平均
来源：http://dali.chenzaomai.com/Article/details/gtisyutrel.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gtepbvddyw.html

[Q29] 最大最小值
来源：http://dali.wangshuangyany.cn/Article/details/gtajizzvbp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtvcixradz.html

[Q30] 分组统计
来源：http://dali.shuidangran.top/Article/details/gtweeajrqx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.tanke756.top/Article/details/gtrdwxxsxr.html

[Q31] 分组后过滤
来源：http://dali.cheryme.top/Article/details/gtfixkyvmp.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.bjfxy.top/Article/details/gthabnipoh.html

[Q32] 分组拼接字符串
来源：http://dali.yvedp.cn/Article/details/gtsdiitbsd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.wangdashe.top/Article/details/gtjnorhrez.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jyoumei.cn/Article/details/gthjuhwxtf.html

[Q33] 多列分组
来源：http://dali.jyoumei.cn/Article/details/gtwyvuziqu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.chenlongwang.top/Article/details/gtpacibmuo.html

[Q34] 每组取第一条
来源：http://dali.zhixingplan.top/Article/details/gtyvzbenyg.html

SELECT * FROM (
来源：http://dali.hongshengwenyu.top/Article/details/gtelivnxpf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.fzhhl.top/Article/details/gtwxqfpaif.html

) t WHERE rn = 1;
来源：http://dali.tanke756.top/Article/details/gtkssbcqiw.html

[Q35] 内连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvqyrwuwe.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ivvv.top/Article/details/gtzhxlourl.html

[Q36] 左连接
来源：http://dali.9152youxi.cn/Article/details/gtguwxlubk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sweek.top/Article/details/gtaonffqlq.html

[Q37] 右连接
来源：http://dali.zdqjudy.top/Article/details/gtpgqbdzbu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jqgufenzy.top/Article/details/gtnvrvugpr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jyoumei.cn/Article/details/gtizxbdfdy.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.wangshuangyany.cn/Article/details/gtvmrhqtct.html

[Q39] 自连接（查上下级）
来源：http://dali.kuanghao11.cn/Article/details/gtbtoxwvxq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jyoumei.cn/Article/details/gtprdsafxz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hysaishi.cn/Article/details/gtynlylsvn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hysaishi.cn/Article/details/gtjdoxlbwr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.iojbl.cn/Article/details/gtvqctuxwc.html

[Q41] 多表连接
来源：http://dali.shuidangran.top/Article/details/gtuuihdetg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.pengpengdd.cyou/Article/details/gtvqlksavw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.kuanghao11.cn/Article/details/gtixgmsrie.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sysykeji.top/Article/details/gtufpunpop.html

[Q42] 连接条件附加过滤
来源：http://dali.sweek.top/Article/details/gtibrgrnud.html

SELECT u.name, o.amount FROM users u
来源：http://dali.feifeiyinyue.top/Article/details/gtheigeoda.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlavnjgrx.html

[Q43] 标量子查询
来源：http://dali.jqgufenzy.top/Article/details/gtjlkhnrpn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.gotoacloud.top/Article/details/gtbxniwdml.html

[Q44] IN 子查询
来源：http://dali.daria6918.cn/Article/details/gtnglqduqu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.meibo888.top/Article/details/gtqbvtlcjt.html

[Q45] EXISTS 判断存在
来源：http://dali.jlsjyb.cn/Article/details/gthldddswb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yanxiufei.cn/Article/details/gtqcrtnxvk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shzxlz.cn/Article/details/gtynfvwynv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hammf.cn/Article/details/gtsejgrqii.html

[Q47] 与平均值比较
来源：http://dali.cashguo.top/Article/details/gtummlamdc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xylfe.cn/Article/details/gtbalhwgca.html

[Q48] CTE 公用表表达式
来源：http://dali.cucudq.cn/Article/details/gthbjwoqxi.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.wangdashe.top/Article/details/gtzexysbhy.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yj20258.top/Article/details/gtnrgsqzps.html

[Q49] 更新单行
来源：http://dali.shuidangran.top/Article/details/gtfzohkcpy.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhiwuduotai.top/Article/details/gtfrqltths.html

[Q50] 批量更新
来源：http://dali.pycfn.com/Article/details/gttxnehaar.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cashguo.top/Article/details/gtvqprlgot.html

[Q51] 用子查询更新
来源：http://dali.ppjwa.cn/Article/details/gtbyzgjgme.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yonumen.top/Article/details/gtjqbnemxh.html

[Q52] 删除指定行
来源：http://dali.jinghuilouyu.cn/Article/details/gtppzrkhbd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.c1oappe.top/Article/details/gtkgjpvmja.html

[Q53] 按条件删除
来源：http://dali.xinyue.icu/Article/details/gtscxkhzuf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jyoumei.cn/Article/details/gtpckqpwxa.html

[Q54] 清空表
来源：http://dali.sufxvd.cn/Article/details/gtnohxvzsh.html

TRUNCATE TABLE logs;
来源：http://dali.yvedp.cn/Article/details/gtsktrsolw.html

[Q55] 排名（并列占位）
来源：http://dali.cucudq.cn/Article/details/gtouahmrpx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jqgfzy.top/Article/details/gtxgubhjqt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cashguo.top/Article/details/gtagrlzdzm.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.haohaochexian.top/Article/details/gtikzmgmvw.html

[Q57] 行号
来源：http://dali.iojbl.cn/Article/details/gtdjlkjltw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbqtvlvsv.html

[Q58] 累计求和
来源：http://dali.daria6918.cn/Article/details/gtgjsjhvgq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gtzgwwvneu.html

[Q59] 分组内累计
来源：http://dali.yanxiufei.cn/Article/details/gtfwvuqsjw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gtlzdqeqxw.html

[Q60] 取上一行 / 下一行
来源：http://dali.316326.xyz/Article/details/gtnfqzfqsh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sweek.top/Article/details/gtpnnhekev.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtzlnjiwps.html

[Q61] 移动平均
来源：http://dali.yongpay.top/Article/details/gtwijavvrx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cheryme.top/Article/details/gtmjjjobiz.html

[Q62] 分组占比
来源：http://dali.chenlongwang.top/Article/details/gtruqeisil.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cucudq.cn/Article/details/gteclzptax.html

[Q63] 开启事务
来源：http://dali.hongshengwenyu.top/Article/details/gtbxosdvfr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqayagrif.html

[Q64] 提交事务
来源：http://dali.hysaishi.cn/Article/details/gtawavbmim.html

COMMIT;
来源：http://dali.kuanghao11.cn/Article/details/gtiexqabxx.html

[Q65] 回滚事务
来源：http://dali.jianghu66.top/Article/details/gtuuffonka.html

ROLLBACK;
来源：http://dali.yuxming.cn/Article/details/gtflovvbui.html

[Q66] 行锁查询
来源：http://dali.chenlongwang.top/Article/details/gtaawkwuwm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ybcxt.top/Article/details/gtkyuyhtqj.html

[Q67] 设置隔离级别
来源：http://dali.nwbrower.top/Article/details/gtboouwuvp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ppjwa.cn/Article/details/gtkjoamozi.html

[Q68] 保存点
来源：http://dali.9152youxi.cn/Article/details/gtjkpkrrzu.html

SAVEPOINT sp1;
来源：http://dali.nwbrower.top/Article/details/gtkfhaqzqn.html

ROLLBACK TO sp1;
来源：http://dali.sxryk.cn/Article/details/gtrxgpgyls.html

[Q69] 查看执行计划
来源：http://dali.tian-w.cn/Article/details/gttiazdeug.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.tian-w.cn/Article/details/gtlpgbehpo.html

[Q70] 更新统计信息
来源：http://dali.cashguo.top/Article/details/gtwpvbwogu.html

ANALYZE TABLE users;
来源：http://dali.yangfankeji.com/Article/details/gtgtyegcbb.html

[Q71] 查看建表语句
来源：http://dali.tianlin.xyz/Article/details/gtrultubiz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.wangshuangyany.cn/Article/details/gtbpucexlo.html

[Q72] 查看索引
来源：http://dali.yvedp.cn/Article/details/gtkvcgpygv.html

SHOW INDEX FROM users;
来源：http://dali.yuxming.cn/Article/details/gtpqaownrp.html

[Q73] 查看表状态
来源：http://dali.cdnleiting.top/Article/details/gthtuwqhnu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkwbgekds.html

[Q74] 强制使用索引
来源：http://dali.sysykeji.top/Article/details/gtirhhnqhu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.pycfn.com/Article/details/gthepuemvu.html

[Q75] 日期格式化
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvqpiejho.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gtcinpokwt.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yangfankeji.com/Article/details/gtesitdyye.html

[Q76] 按天统计
来源：http://dali.316326.xyz/Article/details/gtudsujohz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.fzhhl.top/Article/details/gtczwfzshu.html

[Q77] 时间加减
来源：http://dali.yanxiufei.cn/Article/details/gteznigbol.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yuanzhike.top/Article/details/gtqmbcjyrh.html

[Q78] 当前时间
来源：http://dali.zhoulong.xyz/Article/details/gtxlrkuwwb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ppjwa.cn/Article/details/gthesxepjd.html

[Q79] 字符串拼接
来源：http://dali.jiagoushi.top/Article/details/gtovhojbnl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jlsjyb.cn/Article/details/gtnrhifkvj.html

[Q80] 字符串截取
来源：http://dali.aibaodan.cn/Article/details/gtcvqxxawm.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtovfwgkzs.html

[Q81] 字符串替换
来源：http://dali.wangshuangyany.cn/Article/details/gtlubtrctj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtklkkzhjz.html

[Q82] 字符长度与字节长度
来源：http://dali.chenzaomai.com/Article/details/gtivttnphz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtyjdlxize.html

[Q83] 大小写转换
来源：http://dali.guowangkeji.top/Article/details/gtmcptsnuc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtosxcpyds.html

[Q84] 去除首尾空格
来源：http://dali.dianchejie.cn/Article/details/gttvxvkfvp.html

SELECT TRIM(name) FROM users;
来源：http://dali.sxryk.cn/Article/details/gtymvkjitq.html

[Q85] 数值取整
来源：http://dali.yongpay.top/Article/details/gtldjlxhsc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jinqigufen.top/Article/details/gtlcavqcis.html

[Q86] 读取 JSON 字段
来源：http://dali.shanyushiyangtech.top/Article/details/gtodkbqyyc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hywenlv.cn/Article/details/gtcxokgrqe.html

[Q87] JSON 字段做条件
来源：http://dali.chenlongwang.top/Article/details/gtuacqmugk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinqigufen.top/Article/details/gtvcequzzf.html

[Q88] 行转列（条件聚合）
来源：http://dali.zdqjudy.top/Article/details/gtbxlnmris.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xuanzx.com/Article/details/gtittftrwl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtpoboequz.html

[Q89] 判断表是否存在
来源：http://dali.bjfxy.top/Article/details/gtoijfmvlv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.iojbl.cn/Article/details/gtqcudzale.html

[Q90] 生成序号列
来源：http://dali.hywenlv.cn/Article/details/gtrlxvepea.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yanxiufei.cn/Article/details/gtaharysfw.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtqchjjjez.html

R. Bash 专题
来源：http://dali.cucudq.cn/Article/details/gtrdegjjxe.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtvuphftpt.html

[R01] shebang 与严格模式
来源：http://dali.316326.xyz/Article/details/gtolfjnput.html

#!/usr/bin/env bash
来源：http://dali.andypj.xyz/Article/details/gtcophitpy.html

set -euo pipefail
来源：http://dali.yj20258888.top/Article/details/gttpiotkde.html

[R02] 变量赋值与使用
来源：http://dali.yvedp.cn/Article/details/gtshqdvnol.html

name="Tom"; echo "$name"
来源：http://dali.yonumen.top/Article/details/gtafqfdpeb.html

[R03] 只读变量
来源：http://dali.snrcjt.cn/Article/details/gtuzctxogn.html

readonly PI=3.14
来源：http://dali.jinyuanbaomall.cn/Article/details/gtktxkigqm.html

[R04] 位置参数
来源：http://dali.9152youxi.cn/Article/details/gtjfdqohye.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xziqi.cn/Article/details/gtsvxbdvkd.html

[R05] 参数默认值
来源：http://dali.tanke756.top/Article/details/gtacvzaeki.html

name="${1:-default}"
来源：http://dali.jlsjyb.cn/Article/details/gtrhjqjypj.html

[R06] 判断命令是否存在
来源：http://dali.xinyue.icu/Article/details/gtqqauxaht.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yj20258.top/Article/details/gtxeohyexz.html

[R07] if 判断文件
来源：http://dali.guowangkeji.top/Article/details/gtbpfpaeth.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhengqikj.top/Article/details/gtmeidxfas.html

[R08] 数值比较
来源：http://dali.jiagoushi.top/Article/details/gtlokynxkb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.nwbrower.top/Article/details/gtjhkpgzkr.html

[R09] 字符串比较
来源：http://dali.redwolf501.top/Article/details/gtxkgjwbiu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cheryme.top/Article/details/gtiqqreqdo.html

[R10] 正则匹配
来源：http://dali.pycfn.com/Article/details/gtkvsfzwyt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.tanke756.top/Article/details/gtueotntim.html

[R11] case 多分支
来源：http://dali.wangshuangyany.cn/Article/details/gteqehydrq.html

case "$1" in
来源：http://dali.zhoulong.xyz/Article/details/gtrozktxpv.html

start) echo "启动" ;;
来源：http://dali.ppjwa.cn/Article/details/gtqwodipko.html

stop)  echo "停止" ;;
来源：http://dali.yongpay.top/Article/details/gtbpxokoxg.html

*)     echo "未知命令" ;;
来源：http://dali.nanxuanxn.top/Article/details/gtfmuqyxps.html

esac
来源：http://dali.nanxuanxn.top/Article/details/gtigalymjr.html

[R12] for 遍历文件
来源：http://dali.yj202588.top/Article/details/gtkgsnrzmt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.vqdsnc.cn/Article/details/gtnxsmjnod.html

[R13] for 计数循环
来源：http://dali.zhengqikj.top/Article/details/gtrjkuxyqs.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jqgufenzy.top/Article/details/gtebqgvvff.html

[R14] C 风格 for
来源：http://dali.meibo888.top/Article/details/gtedvwbule.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.chenzaomai.com/Article/details/gtwdikywnd.html

[R15] while 逐行读文件
来源：http://dali.jiagoushi.top/Article/details/gtitfkpoto.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gzhubu.top/Article/details/gtttqbysoz.html

[R16] until 等待条件
来源：http://dali.shanyushiyangtech.top/Article/details/gtnvmjvibq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yangfankeji.com/Article/details/gtumagtncu.html

[R17] 数组定义与取值
来源：http://dali.tanke756.top/Article/details/gtnpodyhdu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cucudq.cn/Article/details/gtmaeuzqhd.html

[R18] 遍历数组
来源：http://dali.daria6918.cn/Article/details/gtxygibzxh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hywenlv.cn/Article/details/gtxsbuatrb.html

[R19] 数组长度
来源：http://dali.xuetiantiany.cn/Article/details/gteqadkhal.html

echo "${#arr[@]}"
来源：http://dali.c1oappe.top/Article/details/gtimasovdd.html

[R20] 关联数组（字典）
来源：http://dali.ydzc1.top/Article/details/gthiepwfbl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.9152youxi.cn/Article/details/gtequntzds.html

[R21] 字符串长度
来源：http://dali.jlsjyb.cn/Article/details/gtdzrmpokn.html

echo "${#s}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtyohisvsc.html

[R22] 截取子串
来源：http://dali.hongshengwenyu.top/Article/details/gtpgcyjrsi.html

echo "${s:0:5}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtxrcozkfl.html

[R23] 字符串替换
来源：http://dali.nanxinkj.top/Article/details/gtwffqdihg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xuetiantiany.cn/Article/details/gtkzsyyesy.html

[R24] 大小写转换
来源：http://dali.zhoulong.xyz/Article/details/gtgxskfsxi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zdqjudy.top/Article/details/gttdqsxynb.html

[R25] 去后缀 / 去前缀
来源：http://dali.jyoumei.cn/Article/details/gtftwhmmyd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hnqzz.top/Article/details/gthywmexhn.html

[R26] 命令替换
来源：http://dali.guannengcc.top/Article/details/gtigogqwtx.html

now=$(date +%F); echo "$now"
来源：http://dali.jianghu66.top/Article/details/gtzmmedmgb.html

[R27] 算术展开
来源：http://dali.smart0.xyz/Article/details/gtlgslvixj.html

echo $((1 + 2 * 3))
来源：http://dali.xinyue.icu/Article/details/gtwhjrbtzg.html

[R28] 浮点运算
来源：http://dali.aibaodan.cn/Article/details/gtrkcfnvqw.html

echo "scale=2; 10/3" | bc
来源：http://dali.meibo888.top/Article/details/gtzqqlrapj.html

[R29] 定义函数
来源：http://dali.gzhubu.top/Article/details/gtrnqhvzwx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.andypj.xyz/Article/details/gtklopcbfo.html

[R30] 函数返回状态码
来源：http://dali.jinqigufen.top/Article/details/gtrjnhalld.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinghuilouyu.cn/Article/details/gtyafdkoce.html

[R31] 局部变量
来源：http://dali.dianchejie.cn/Article/details/gtectiieva.html

f() { local x=1; echo "$x"; }
来源：http://dali.svipenyu.cn/Article/details/gtkxuabhuz.html

[R32] 参数个数校验
来源：http://dali.yj202588.top/Article/details/gtdpprlxli.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ehwqpu.com/Article/details/gtoworscnn.html

[R33] 捕获错误并提示行号
来源：http://dali.jqgufenzy.top/Article/details/gtfydpfyzm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvjdquxfe.html

[R34] 退出时清理
来源：http://dali.fengsongda.top/Article/details/gtdfsqeppc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ydzc1.top/Article/details/gtzahqugmo.html

[R35] 后台执行并等待
来源：http://dali.daxiang520.top/Article/details/gtjmiwwcjp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hywenlv.cn/Article/details/gtfiiegrmq.html

[R36] 并发执行多个任务
来源：http://dali.zhengqikj.top/Article/details/gtbnipdviy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zdqjudy.top/Article/details/gtodgvlygm.html

[R37] 把输出赋给变量
来源：http://dali.zhengqikj.top/Article/details/gtyblbasvj.html

files=$(ls -1)
来源：http://dali.daria6918.cn/Article/details/gtcxkfjcwt.html

[R38] 管道串联
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrtmjcxnw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.nanxuanxn.top/Article/details/gthwhoalth.html

[R39] 重定向标准输出与错误
来源：http://dali.kuanghao11.cn/Article/details/gtidmhxhhu.html

cmd > out.log 2>&1
来源：http://dali.bjfxy.top/Article/details/gtckyfnqst.html

[R40] 追加写日志
来源：http://dali.tian-w.cn/Article/details/gtrnnxubhx.html

echo "log" >> out.log
来源：http://dali.0kj1m.cn/Article/details/gthvdcgkjv.html

[R41] 丢弃输出
来源：http://dali.xuanzx.com/Article/details/gtbubdsrdz.html

cmd >/dev/null 2>&1
来源：http://dali.daxiang520.top/Article/details/gtgarmlqgu.html

[R42] 输入重定向
来源：http://dali.ivvv.top/Article/details/gtocmtctyz.html

wc -l < a.txt
来源：http://dali.ybcxt.top/Article/details/gtslfzbnnd.html

[R43] 按名字查找文件
来源：http://dali.andypj.xyz/Article/details/gtytsuhxbq.html

find . -name "*.log" -type f
来源：http://dali.zhaomingkeji.xyz/Article/details/gtetibmjrp.html

[R44] 按修改时间查找
来源：http://dali.jianghu66.top/Article/details/gtlevmfbbr.html

find . -mtime -7 -type f
来源：http://dali.hammf.cn/Article/details/gtzoccbils.html

[R45] 批量删除
来源：http://dali.hysaishi.cn/Article/details/gtrsyleuvy.html

find . -name "*.tmp" -delete
来源：http://dali.hnqzz.top/Article/details/gtmaerlebi.html

[R46] 递归替换文件内容
来源：http://dali.sweek.top/Article/details/gtztnjrioh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yongpay.top/Article/details/gtigtfhppd.html

[R47] sed 单行替换
来源：http://dali.hongshengwenyu.top/Article/details/gttpfvwwaz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.guannengcc.top/Article/details/gtmhovmzyz.html

[R48] awk 取指定列
来源：http://dali.kuanghao11.cn/Article/details/gtqwjtalsx.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhengqikj.top/Article/details/gtcafahhrb.html

[R49] awk 带条件
来源：http://dali.zhiwuduotai.top/Article/details/gthsodoecl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.tianlin.xyz/Article/details/gtqgkaacik.html

[R50] awk 求和
来源：http://dali.wangdashe.top/Article/details/gtlceitseo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sweek.top/Article/details/gtmvdelflr.html

[R51] 排序去重取前几
来源：http://dali.hnxiangtu.top/Article/details/gtbrpxhevf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hammf.cn/Article/details/gtqpjckuob.html

[R52] 统计行数
来源：http://dali.9152youxi.cn/Article/details/gtxoxrwhjl.html

wc -l a.txt
来源：http://dali.yvedp.cn/Article/details/gtyioztjtd.html

[R53] 查看文件头与实时尾
来源：http://dali.tianlin.xyz/Article/details/gtcaulzcse.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xuanzx.com/Article/details/gtgvpiemdw.html

[R54] 比较两个文件
来源：http://dali.shangyingyoupin.top/Article/details/gtxfnvdmjo.html

diff a.txt b.txt
来源：http://dali.quarkkingdee.top/Article/details/gtyqunvibu.html

[R55] 压缩与解压
来源：http://dali.dianchejie.cn/Article/details/gtriguowdd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yuxming.cn/Article/details/gtniciupqo.html

[R56] 远程拷贝
来源：http://dali.nanxinkj.top/Article/details/gtqxhipcbs.html

scp file user@host:/path/
来源：http://dali.jinghuilouyu.cn/Article/details/gtjiojzgsx.html

[R57] 远程执行命令
来源：http://dali.tanke756.top/Article/details/gtgogohcrh.html

ssh user@host 'uptime'
来源：http://dali.cashguo.top/Article/details/gtlqbhkrgl.html

[R58] 下载文件
来源：http://dali.feifeiyinyue.top/Article/details/gtzsamaxgq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gtdauvozpx.html

[R59] 发 POST JSON
来源：http://dali.yanxiufei.cn/Article/details/gthjfkvbbe.html


<!-- 参考信息 -->