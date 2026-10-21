代发 wailian999

INSERT INTO users (name) VALUES ('C');
来源：http://dali.wangdashe.top/Article/details/gtlkdqdnqd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.chenjidiqi.icu/Article/details/gtqnhrfoez.html

[Q13] 忽略重复插入
来源：http://dali.yuxming.cn/Article/details/gtreabaowm.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.iojbl.cn/Article/details/gtfxtznofi.html

[Q14] 存在则更新（upsert）
来源：http://dali.ppjwa.cn/Article/details/gtrkjtkkof.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cucudq.cn/Article/details/gtltiuxgcv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.guannengcc.top/Article/details/gtxzpbjmks.html

[Q15] 查询全部
来源：http://dali.jiagoushi.top/Article/details/gtymnmagri.html

SELECT * FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtqavuximt.html

[Q16] 查询指定列
来源：http://dali.hnxiangtu.top/Article/details/gtbwmsisuw.html

SELECT id, name FROM users;
来源：http://dali.wangdashe.top/Article/details/gtoglfesof.html

[Q17] 条件查询
来源：http://dali.shzxlz.cn/Article/details/gtvxtkdyew.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.andypj.xyz/Article/details/gthhfgfzjb.html

[Q18] 模糊匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtkklakhsp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.feifeiyinyue.top/Article/details/gtobjieklv.html

[Q19] 范围查询
来源：http://dali.nanxinkj.top/Article/details/gtxtpmgusk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.guannengcc.top/Article/details/gtbxdgbrel.html

[Q20] IN 列表
来源：http://dali.yj202588.top/Article/details/gttqkbqelx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.chenzaomai.com/Article/details/gtyoduwrof.html

[Q21] 空值判断
来源：http://dali.zdqjudy.top/Article/details/gtnkcmwdzm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.0kj1m.cn/Article/details/gtddtfnksq.html

[Q22] 排序
来源：http://dali.cdnleiting.top/Article/details/gtgqtictns.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xuetiantiany.cn/Article/details/gtxryqowak.html

[Q23] 分页
来源：http://dali.fengsongda.top/Article/details/gtigaoovmk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.aizwys.cn/Article/details/gtyddsrrag.html

[Q24] 去重
来源：http://dali.jqgufenzy.top/Article/details/gtktisfjgl.html

SELECT DISTINCT city FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtxicsxzpl.html

[Q25] 只取前 N 条
来源：http://dali.aizwys.cn/Article/details/gtunwgqqee.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xuanzx.com/Article/details/gtvjwyxdwz.html

[Q26] 计数
来源：http://dali.aizwys.cn/Article/details/gtemktttnq.html

SELECT COUNT(*) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtyhnpexkh.html

[Q27] 条件计数
来源：http://dali.jqgfzy.top/Article/details/gtcedalnmc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.andypj.xyz/Article/details/gtendvivio.html

[Q28] 求和与平均
来源：http://dali.nanxuanxn.top/Article/details/gtdgudiwcx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtmtwuighc.html

[Q29] 最大最小值
来源：http://dali.aibaodan.cn/Article/details/gtwtkffsmp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtrzyjodwd.html

[Q30] 分组统计
来源：http://dali.fengsongda.top/Article/details/gtmttkobyg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yonumen.top/Article/details/gtbmuzndzm.html

[Q31] 分组后过滤
来源：http://dali.feifeiyinyue.top/Article/details/gtmvybujbo.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtejqauawx.html

[Q32] 分组拼接字符串
来源：http://dali.tanke756.top/Article/details/gtsgwzhkkb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.feifeiyinyue.top/Article/details/gtqqfnyjfn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.snrcjt.cn/Article/details/gtsqnhkfrw.html

[Q33] 多列分组
来源：http://dali.svipenyu.cn/Article/details/gtrquejheg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jinqigfzy.top/Article/details/gtjaooqfht.html

[Q34] 每组取第一条
来源：http://dali.feifeiyinyue.top/Article/details/gtyavcrjvw.html

SELECT * FROM (
来源：http://dali.cdnleiting.top/Article/details/gtasgaztql.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xinyue.icu/Article/details/gtzetaxviy.html

) t WHERE rn = 1;
来源：http://dali.yuanzhike.top/Article/details/gtmbibychc.html

[Q35] 内连接
来源：http://dali.ivvv.top/Article/details/gtedixusqp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.dashuyun.cn/Article/details/gthwbcbdbo.html

[Q36] 左连接
来源：http://dali.hfpthk.cn/Article/details/gtgyxzaufo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shuidangran.top/Article/details/gtcnpqhzcp.html

[Q37] 右连接
来源：http://dali.c1oappe.top/Article/details/gtrdpgatmd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yangfankeji.com/Article/details/gtmpbehqob.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.gzhubu.top/Article/details/gtiatzsymz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.dianchejie.cn/Article/details/gttpjsslnc.html

[Q39] 自连接（查上下级）
来源：http://dali.tian-w.cn/Article/details/gthyxqkmet.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hywenlv.cn/Article/details/gtijrrmrte.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jqgufenzy.top/Article/details/gtntxhesnh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuucxazro.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sweek.top/Article/details/gtazhcjion.html

[Q41] 多表连接
来源：http://dali.yj20258.top/Article/details/gtkerdzkde.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.meibo888.top/Article/details/gtbldpkhog.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sufxvd.cn/Article/details/gtcnizgbgl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.guowangkeji.top/Article/details/gtlbzhcsae.html

[Q42] 连接条件附加过滤
来源：http://dali.cdnleiting.top/Article/details/gtlfieecnu.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hongshengwenyu.top/Article/details/gterfnmnrc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.dashuyun.cn/Article/details/gtaivvfmms.html

[Q43] 标量子查询
来源：http://dali.chenlongwang.top/Article/details/gthkjwrneh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.pengpengdd.cyou/Article/details/gtslhogquc.html

[Q44] IN 子查询
来源：http://dali.c1oappe.top/Article/details/gtfvdcxfwm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.guannengcc.top/Article/details/gtmlnhwjsc.html

[Q45] EXISTS 判断存在
来源：http://dali.havefunace.top/Article/details/gtzvweeucm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cdnleiting.top/Article/details/gtbkwvdolr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ybcxt.top/Article/details/gtqlxijxpy.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shangyingyoupin.top/Article/details/gtsdnnrmzw.html

[Q47] 与平均值比较
来源：http://dali.cdnleiting.top/Article/details/gtyyonxfng.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.iojbl.cn/Article/details/gtehbdrbvs.html

[Q48] CTE 公用表表达式
来源：http://dali.yvedp.cn/Article/details/gtdmpjqbhw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yonumen.top/Article/details/gtsflxrbjx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.aizwys.cn/Article/details/gtjcfbfpae.html

[Q49] 更新单行
来源：http://dali.hongshengwenyu.top/Article/details/gtgnjhaoxf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ppjwa.cn/Article/details/gtmzseoljq.html

[Q50] 批量更新
来源：http://dali.yonumen.top/Article/details/gtjdoymuxo.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zdqjudy.top/Article/details/gtjufldaqs.html

[Q51] 用子查询更新
来源：http://dali.jqgufenzy.top/Article/details/gtdzfoudxz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.guowangkeji.top/Article/details/gtvtsladqj.html

[Q52] 删除指定行
来源：http://dali.smart0.xyz/Article/details/gtqzoyclad.html

DELETE FROM users WHERE id = 10;
来源：http://dali.svipenyu.cn/Article/details/gtotponuwm.html

[Q53] 按条件删除
来源：http://dali.hongshengwenyu.top/Article/details/gtnpxooyav.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.svipenyu.cn/Article/details/gttbzstdbs.html

[Q54] 清空表
来源：http://dali.shuidangran.top/Article/details/gtftbzfngu.html

TRUNCATE TABLE logs;
来源：http://dali.shuidangran.top/Article/details/gtoxjizulu.html

[Q55] 排名（并列占位）
来源：http://dali.yonumen.top/Article/details/gtximzkzxp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ydzc1.top/Article/details/gtaxpzztjk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.fengsongda.top/Article/details/gthwslkgaw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.bjfxy.top/Article/details/gtgayrfmbg.html

[Q57] 行号
来源：http://dali.wangshuangyany.cn/Article/details/gtmjrdgqfn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtezuuavqb.html

[Q58] 累计求和
来源：http://dali.yonumen.top/Article/details/gtihycxsrp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jianghu66.top/Article/details/gtjbltlygb.html

[Q59] 分组内累计
来源：http://dali.tanke756.top/Article/details/gtwvwsmanl.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtitapqbit.html

[Q60] 取上一行 / 下一行
来源：http://dali.hongshengwenyu.top/Article/details/gtipqxzsjl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.havefunace.top/Article/details/gtagvxekfu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cashguo.top/Article/details/gtbduvrrfr.html

[Q61] 移动平均
来源：http://dali.xinyue.icu/Article/details/gtjxjfepbu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.c1oappe.top/Article/details/gtpedcvhle.html

[Q62] 分组占比
来源：http://dali.wangshuangyany.cn/Article/details/gtqlhakyit.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gotoacloud.top/Article/details/gtyvmsmuml.html

[Q63] 开启事务
来源：http://dali.zhongyouzk.top/Article/details/gtfkwwbrbl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xinyue.icu/Article/details/gtottrunqm.html

[Q64] 提交事务
来源：http://dali.jianghu66.top/Article/details/gtbgukcoyg.html

COMMIT;
来源：http://dali.hongshengwenyu.top/Article/details/gtyzmoeplc.html

[Q65] 回滚事务
来源：http://dali.cdnleiting.top/Article/details/gtfjuozeeo.html

ROLLBACK;
来源：http://dali.cqqwz.cn/Article/details/gtgkzdttrl.html

[Q66] 行锁查询
来源：http://dali.hywenlv.cn/Article/details/gtakcfmvyw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zycfv.cn/Article/details/gtltuwytzf.html

[Q67] 设置隔离级别
来源：http://dali.xinyue.icu/Article/details/gtbecnfeav.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinqigufen.top/Article/details/gteamrnuus.html

[Q68] 保存点
来源：http://dali.hywenlv.cn/Article/details/gtwxnzhdsj.html

SAVEPOINT sp1;
来源：http://dali.pengpengdd.cyou/Article/details/gtgefklvcw.html

ROLLBACK TO sp1;
来源：http://dali.zhengqikj.top/Article/details/gtdjfkjlxt.html

[Q69] 查看执行计划
来源：http://dali.daria6918.cn/Article/details/gtbgkteoas.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.dashuyun.cn/Article/details/gtxmsrqxyl.html

[Q70] 更新统计信息
来源：http://dali.zhoulong.xyz/Article/details/gtkqqwsvkd.html

ANALYZE TABLE users;
来源：http://dali.316326.xyz/Article/details/gtmzndgsao.html

[Q71] 查看建表语句
来源：http://dali.cashguo.top/Article/details/gtbfahddkr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jianghu66.top/Article/details/gtoltvcocl.html

[Q72] 查看索引
来源：http://dali.kuanghao11.cn/Article/details/gtceqolkiq.html

SHOW INDEX FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmbtqnoxz.html

[Q73] 查看表状态
来源：http://dali.yonumen.top/Article/details/gtahrdapip.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yuxming.cn/Article/details/gtjlqvhrza.html

[Q74] 强制使用索引
来源：http://dali.quarkkingdee.top/Article/details/gtftdovvlp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jqgufenzy.top/Article/details/gtxlaubznh.html

[Q75] 日期格式化
来源：http://dali.chenlongwang.top/Article/details/gtwrjviqfo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtnsfddgef.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.nanxinkj.top/Article/details/gtjbwyubgj.html

[Q76] 按天统计
来源：http://dali.ybcxt.top/Article/details/gtespqksqk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yuanzhike.top/Article/details/gtmzeuzlav.html

[Q77] 时间加减
来源：http://dali.yj20258.top/Article/details/gtjchvqgak.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.nanxuanxn.top/Article/details/gtrahmywhr.html

[Q78] 当前时间
来源：http://dali.ivvv.top/Article/details/gtclomclvg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.9152youxi.cn/Article/details/gtpzbngkor.html

[Q79] 字符串拼接
来源：http://dali.zhiwuduotai.top/Article/details/gtikirzexe.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.dashuyun.cn/Article/details/gtlzbskavi.html

[Q80] 字符串截取
来源：http://dali.ybcxt.top/Article/details/gtavwmtxen.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtzihqlbdd.html

[Q81] 字符串替换
来源：http://dali.chenzaomai.com/Article/details/gtezxyuexg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.daxiang520.top/Article/details/gtojclsopd.html

[Q82] 字符长度与字节长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtreoymplb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.wangdashe.top/Article/details/gtbtdvgucd.html

[Q83] 大小写转换
来源：http://dali.zhongyouzk.top/Article/details/gtlxybltyf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtzffnahxg.html

[Q84] 去除首尾空格
来源：http://dali.yj20258.top/Article/details/gtzqruzldv.html

SELECT TRIM(name) FROM users;
来源：http://dali.aizwys.cn/Article/details/gthvyqfknd.html

[Q85] 数值取整
来源：http://dali.pengpengdd.cyou/Article/details/gtwaugcmpc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cucudq.cn/Article/details/gtpuyklkmg.html

[Q86] 读取 JSON 字段
来源：http://dali.tianlin.xyz/Article/details/gtisygvzqd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.chenzaomai.com/Article/details/gtqfqsyzlk.html

[Q87] JSON 字段做条件
来源：http://dali.wangshuangyany.cn/Article/details/gtsfkmxgqx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hysaishi.cn/Article/details/gtlmlxbign.html

[Q88] 行转列（条件聚合）
来源：http://dali.svipenyu.cn/Article/details/gtlabcqpve.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.c1oappe.top/Article/details/gtxasmuefb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtsjabhnbb.html

[Q89] 判断表是否存在
来源：http://dali.yj202588.top/Article/details/gtwfasqyja.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.gotoacloud.top/Article/details/gtziktanoa.html

[Q90] 生成序号列
来源：http://dali.bjfxy.top/Article/details/gtkeotcfrn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zdqjudy.top/Article/details/gteqjyjbjw.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gttlawfxdo.html

R. Bash 专题
来源：http://dali.pycfn.com/Article/details/gtkgybenqi.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtiejywgxo.html

[R01] shebang 与严格模式
来源：http://dali.wangshuangyany.cn/Article/details/gttekgcily.html

#!/usr/bin/env bash
来源：http://dali.hysaishi.cn/Article/details/gtxegugyio.html

set -euo pipefail
来源：http://dali.dashuyun.cn/Article/details/gtxsdnzjog.html

[R02] 变量赋值与使用
来源：http://dali.nwbrower.top/Article/details/gtqbnhiuno.html

name="Tom"; echo "$name"
来源：http://dali.hnxiangtu.top/Article/details/gtijxxzacx.html

[R03] 只读变量
来源：http://dali.yuxming.cn/Article/details/gtmcoilsnr.html

readonly PI=3.14
来源：http://dali.guowangkeji.top/Article/details/gtolicinjq.html

[R04] 位置参数
来源：http://dali.cdnleiting.top/Article/details/gtsstjelfy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shzxlz.cn/Article/details/gtxndthbsf.html

[R05] 参数默认值
来源：http://dali.jiagoushi.top/Article/details/gtrxfdibsc.html

name="${1:-default}"
来源：http://dali.chenjidiqi.icu/Article/details/gtwodpubzx.html

[R06] 判断命令是否存在
来源：http://dali.yuxming.cn/Article/details/gtfojuvnet.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.tanke756.top/Article/details/gtdckhqoll.html

[R07] if 判断文件
来源：http://dali.svipenyu.cn/Article/details/gtcmjbkduy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gtkdsftymz.html

[R08] 数值比较
来源：http://dali.yvedp.cn/Article/details/gtkoiezudj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shzxlz.cn/Article/details/gtwlwbzhpr.html

[R09] 字符串比较
来源：http://dali.jqgfzy.top/Article/details/gtaqmcfzls.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.birdmap.top/Article/details/gtjewgagmy.html

[R10] 正则匹配
来源：http://dali.daxiang520.top/Article/details/gtxhncznei.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yj20258.top/Article/details/gtyzulefuv.html

[R11] case 多分支
来源：http://dali.jiagoushi.top/Article/details/gtslecjjvc.html

case "$1" in
来源：http://dali.shanyushiyangtech.top/Article/details/gtxbnlwidn.html

start) echo "启动" ;;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqaqifqyk.html

stop)  echo "停止" ;;
来源：http://dali.hongshengwenyu.top/Article/details/gtwbyfdbzj.html

*)     echo "未知命令" ;;
来源：http://dali.yvedp.cn/Article/details/gtetqfkclu.html

esac
来源：http://dali.jinqigufen.top/Article/details/gtyubcgsvs.html

[R12] for 遍历文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiaafgtsf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.andypj.xyz/Article/details/gtvxzjwbmw.html

[R13] for 计数循环
来源：http://dali.jianghu66.top/Article/details/gtkojrfhye.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.iojbl.cn/Article/details/gtdlemqrbp.html

[R14] C 风格 for
来源：http://dali.cashguo.top/Article/details/gtedjcryne.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shangyingyoupin.top/Article/details/gttuibihkg.html

[R15] while 逐行读文件
来源：http://dali.daria6918.cn/Article/details/gtwzvknvqz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yangfankeji.com/Article/details/gtmxmaxdtq.html

[R16] until 等待条件
来源：http://dali.haohaochexian.top/Article/details/gtixklilvf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yvedp.cn/Article/details/gtlxtqdwnb.html

[R17] 数组定义与取值
来源：http://dali.svipenyu.cn/Article/details/gtctsfruge.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xylfe.cn/Article/details/gtmyveckon.html

[R18] 遍历数组
来源：http://dali.jqgfzy.top/Article/details/gtolhindsw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.chenjidiqi.icu/Article/details/gtlapphqio.html

[R19] 数组长度
来源：http://dali.feifeiyinyue.top/Article/details/gtswclereu.html

echo "${#arr[@]}"
来源：http://dali.nanxinkj.top/Article/details/gtqasjrrgp.html

[R20] 关联数组（字典）
来源：http://dali.cucudq.cn/Article/details/gtxmosrafb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.mhx1999.top/Article/details/gtlrbivnbz.html

[R21] 字符串长度
来源：http://dali.yanxiufei.cn/Article/details/gtxoiheone.html

echo "${#s}"
来源：http://dali.c1oappe.top/Article/details/gtleoufywd.html

[R22] 截取子串
来源：http://dali.yongpay.top/Article/details/gtorfhxcbd.html

echo "${s:0:5}"
来源：http://dali.yj20258.top/Article/details/gtxyhkfxzc.html

[R23] 字符串替换
来源：http://dali.mhx1999.top/Article/details/gthtahibsb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hongshengwenyu.top/Article/details/gtoqnbmtms.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gtdaeyzpvy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.svipenyu.cn/Article/details/gtupuqzdnt.html

[R25] 去后缀 / 去前缀
来源：http://dali.hongshengwenyu.top/Article/details/gttgsyuggz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.pengpengdd.cyou/Article/details/gtgknkeqov.html

[R26] 命令替换
来源：http://dali.gzhubu.top/Article/details/gttoywekct.html

now=$(date +%F); echo "$now"
来源：http://dali.quarkkingdee.top/Article/details/gtkrifliss.html

[R27] 算术展开
来源：http://dali.cdnleiting.top/Article/details/gtevgoyxnu.html

echo $((1 + 2 * 3))
来源：http://dali.gaohongyu789.top/Article/details/gthpdjpirc.html

[R28] 浮点运算
来源：http://dali.bjfxy.top/Article/details/gtivelnmkq.html

echo "scale=2; 10/3" | bc
来源：http://dali.yuxming.cn/Article/details/gtdzkfhhwx.html

[R29] 定义函数
来源：http://dali.haohaochexian.top/Article/details/gtsiruustw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yj20258.top/Article/details/gtjprwckke.html

[R30] 函数返回状态码
来源：http://dali.ehwqpu.com/Article/details/gtlqwdwxcm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.wangshuangyany.cn/Article/details/gthmlyxqud.html

[R31] 局部变量
来源：http://dali.svipenyu.cn/Article/details/gtkceivolw.html

f() { local x=1; echo "$x"; }
来源：http://dali.shzxlz.cn/Article/details/gtwwwykcrj.html

[R32] 参数个数校验
来源：http://dali.cucudq.cn/Article/details/gtbpkhzpny.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yonumen.top/Article/details/gteopsnofy.html

[R33] 捕获错误并提示行号
来源：http://dali.cucudq.cn/Article/details/gtsxwltgaf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yuanzhike.top/Article/details/gtcuhkhtnz.html

[R34] 退出时清理
来源：http://dali.ppjwa.cn/Article/details/gtbljqiaig.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zdqjudy.top/Article/details/gtfgpehzpx.html

[R35] 后台执行并等待
来源：http://dali.gogol.net.cn/Article/details/gtkhuentvc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.guowangkeji.top/Article/details/gtsoqqjaik.html

[R36] 并发执行多个任务
来源：http://dali.jinghuilouyu.cn/Article/details/gtmaardyca.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.chenjidiqi.icu/Article/details/gtdqzqxjry.html

[R37] 把输出赋给变量
来源：http://dali.pycfn.com/Article/details/gtwjngnehz.html

files=$(ls -1)
来源：http://dali.pycfn.com/Article/details/gtdwyjicor.html

[R38] 管道串联
来源：http://dali.yvedp.cn/Article/details/gtvfwwebax.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xylfe.cn/Article/details/gthgkzbthc.html

[R39] 重定向标准输出与错误
来源：http://dali.nanxinkj.top/Article/details/gtabviccqt.html

cmd > out.log 2>&1
来源：http://dali.gogol.net.cn/Article/details/gtzoedjngy.html

[R40] 追加写日志
来源：http://dali.daxiang520.top/Article/details/gtsnltsvtv.html

echo "log" >> out.log
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyajkemen.html

[R41] 丢弃输出
来源：http://dali.shanyushiyangtech.top/Article/details/gtavcyfkta.html

cmd >/dev/null 2>&1
来源：http://dali.gotoacloud.top/Article/details/gtlgyvjmdr.html

[R42] 输入重定向
来源：http://dali.gzhubu.top/Article/details/gteaalmizw.html

wc -l < a.txt
来源：http://dali.ehwqpu.com/Article/details/gtorkhwgjq.html

[R43] 按名字查找文件
来源：http://dali.zhiwuduotai.top/Article/details/gtwyrhtgca.html

find . -name "*.log" -type f
来源：http://dali.ydzc1.top/Article/details/gtehjjxsio.html

[R44] 按修改时间查找
来源：http://dali.andypj.xyz/Article/details/gtcbqyugzf.html

find . -mtime -7 -type f
来源：http://dali.xziqi.cn/Article/details/gtghtbpllu.html

[R45] 批量删除
来源：http://dali.cucudq.cn/Article/details/gtqhaclqrr.html

find . -name "*.tmp" -delete
来源：http://dali.yj20258888.top/Article/details/gtfsynxrgy.html

[R46] 递归替换文件内容
来源：http://dali.yuanzhike.top/Article/details/gtdwynrcdh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ppjwa.cn/Article/details/gtetvovmpw.html

[R47] sed 单行替换
来源：http://dali.chenzaomai.com/Article/details/gttwvgwldm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.snrcjt.cn/Article/details/gtlrnedutj.html

[R48] awk 取指定列
来源：http://dali.guowangkeji.top/Article/details/gtlqdhsxkr.html

awk '{print $1, $3}' a.txt
来源：http://dali.birdmap.top/Article/details/gtnyaqlldu.html

[R49] awk 带条件
来源：http://dali.hysaishi.cn/Article/details/gtpinyxzhh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ydzc1.top/Article/details/gtixpcjybq.html

[R50] awk 求和
来源：http://dali.ybcxt.top/Article/details/gtjlvfdafy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cqqwz.cn/Article/details/gtffpjeyjn.html

[R51] 排序去重取前几
来源：http://dali.ivvv.top/Article/details/gtbepnjxms.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.sysykeji.top/Article/details/gtmixfelkn.html

[R52] 统计行数
来源：http://dali.zhixingplan.top/Article/details/gtdxlkguwt.html

wc -l a.txt
来源：http://dali.hnqzz.top/Article/details/gthnvkoggr.html

[R53] 查看文件头与实时尾
来源：http://dali.wangdashe.top/Article/details/gthsgicwea.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.feifeiyinyue.top/Article/details/gtjtgktkio.html

[R54] 比较两个文件
来源：http://dali.sxryk.cn/Article/details/gtbcjxjwzc.html

diff a.txt b.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtskwxdnfs.html

[R55] 压缩与解压
来源：http://dali.daxiang520.top/Article/details/gtqakjbqjk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gotoacloud.top/Article/details/gthwbzexwh.html

[R56] 远程拷贝
来源：http://dali.shangyingyoupin.top/Article/details/gtrljmhnni.html

scp file user@host:/path/
来源：http://dali.jinyuanbaomall.cn/Article/details/gtotxzbpql.html

[R57] 远程执行命令
来源：http://dali.yanxiufei.cn/Article/details/gtjjtzbrww.html

ssh user@host 'uptime'
来源：http://dali.hammf.cn/Article/details/gtqodoccfv.html

[R58] 下载文件
来源：http://dali.tanke756.top/Article/details/gtcxiaungd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shzxlz.cn/Article/details/gtamiosizg.html

[R59] 发 POST JSON
来源：http://dali.gzhubu.top/Article/details/gtvytxaoaq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.dianchejie.cn/Article/details/gtyfxfrhha.html

[R60] 只看 HTTP 状态码
来源：http://dali.ehwqpu.com/Article/details/gtmbelphnw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.wangshuangyany.cn/Article/details/gtjxqqtxgz.html

[R61] 磁盘占用
来源：http://dali.jqgufenzy.top/Article/details/gtiopzoviq.html


<!-- 参考信息 -->