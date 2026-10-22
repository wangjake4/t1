代发 wailian999

[Q14] 存在则更新（upsert）
来源：http://dali.meibo888.top/Article/details/gtmlpxraoh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.fzhhl.top/Article/details/gtdrslfmdb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqjfqnqmc.html

[Q15] 查询全部
来源：http://dali.0kj1m.cn/Article/details/gtcnnojsko.html

SELECT * FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtxaidixwv.html

[Q16] 查询指定列
来源：http://dali.nanxinkj.top/Article/details/gtopcthfec.html

SELECT id, name FROM users;
来源：http://dali.tanke756.top/Article/details/gttwnocqwv.html

[Q17] 条件查询
来源：http://dali.zycfv.cn/Article/details/gtyllakhtf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xuanzx.com/Article/details/gtvuturacq.html

[Q18] 模糊匹配
来源：http://dali.cucudq.cn/Article/details/gtachwueem.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sufxvd.cn/Article/details/gtvtkwqmnj.html

[Q19] 范围查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcgqvxytg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shuidangran.top/Article/details/gtboknyhxz.html

[Q20] IN 列表
来源：http://dali.gaohongyu789.top/Article/details/gtwoaiiujd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.havefunace.top/Article/details/gtdxftkjvu.html

[Q21] 空值判断
来源：http://dali.jqgufenzy.top/Article/details/gtohdlgebo.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.redwolf501.top/Article/details/gtymwuguaw.html

[Q22] 排序
来源：http://dali.tian-w.cn/Article/details/gtdxqnaakd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xinyue.icu/Article/details/gtwplrnhag.html

[Q23] 分页
来源：http://dali.nanxinkj.top/Article/details/gteuhqlqyb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gtxkopadjc.html

[Q24] 去重
来源：http://dali.shzxlz.cn/Article/details/gtkzjzpscq.html

SELECT DISTINCT city FROM users;
来源：http://dali.yj20258.top/Article/details/gthnaochyw.html

[Q25] 只取前 N 条
来源：http://dali.nanxinkj.top/Article/details/gtdjtpddqq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.wangshuangyany.cn/Article/details/gtzqxtacnn.html

[Q26] 计数
来源：http://dali.jinqigufen.top/Article/details/gtqvhzehqv.html

SELECT COUNT(*) FROM users;
来源：http://dali.meibo888.top/Article/details/gtvtrcoabq.html

[Q27] 条件计数
来源：http://dali.bjfxy.top/Article/details/gtqsjqjjoh.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.gzhubu.top/Article/details/gtvgthsrcc.html

[Q28] 求和与平均
来源：http://dali.gaohongyu789.top/Article/details/gtmujkrhrb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtpxosovpt.html

[Q29] 最大最小值
来源：http://dali.zhongyouzk.top/Article/details/gtrlhiigwd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwrgtgjsy.html

[Q30] 分组统计
来源：http://dali.jqgufenzy.top/Article/details/gteuduayic.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.pycfn.com/Article/details/gthjvsxcqb.html

[Q31] 分组后过滤
来源：http://dali.0kj1m.cn/Article/details/gtcamtmvjd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinqigfzy.top/Article/details/gtwxijmrdy.html

[Q32] 分组拼接字符串
来源：http://dali.snrcjt.cn/Article/details/gtmtzjxeke.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xuetiantiany.cn/Article/details/gtfxlsvuar.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnmxotyrc.html

[Q33] 多列分组
来源：http://dali.xziqi.cn/Article/details/gtkrjrqwkx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yj202588.top/Article/details/gtqnvwfmrj.html

[Q34] 每组取第一条
来源：http://dali.fengsongda.top/Article/details/gtzwvrnyoc.html

SELECT * FROM (
来源：http://dali.jyoumei.cn/Article/details/gtdlwhpnax.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.0kj1m.cn/Article/details/gtdceugbbr.html

) t WHERE rn = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtmrfwxnqy.html

[Q35] 内连接
来源：http://dali.daria6918.cn/Article/details/gtxcagzfno.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenlongwang.top/Article/details/gtkvvammpj.html

[Q36] 左连接
来源：http://dali.nwbrower.top/Article/details/gtsgkmgtix.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.snrcjt.cn/Article/details/gtzurmldnk.html

[Q37] 右连接
来源：http://dali.ybcxt.top/Article/details/gtkxazfhki.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.nwbrower.top/Article/details/gtvscbpuhd.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zdqjudy.top/Article/details/gtqegqcqmd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmauainzd.html

[Q39] 自连接（查上下级）
来源：http://dali.xylfe.cn/Article/details/gtyvqvohlt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yj20258888.top/Article/details/gtsqqrahyg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jinqigfzy.top/Article/details/gttxclqlqf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhiwuduotai.top/Article/details/gtjytultrb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.gotoacloud.top/Article/details/gteetsqlvo.html

[Q41] 多表连接
来源：http://dali.cashguo.top/Article/details/gttiaqtzlk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.daria6918.cn/Article/details/gtsbhxqfaa.html

JOIN users u ON u.id = o.user_id
来源：http://dali.guowangkeji.top/Article/details/gtfvqpvqob.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.daxiang520.top/Article/details/gtwunbpbez.html

[Q42] 连接条件附加过滤
来源：http://dali.ybcxt.top/Article/details/gtiihuyinn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yangfankeji.com/Article/details/gtioxkcwqs.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.daxiang520.top/Article/details/gtbxmnqoki.html

[Q43] 标量子查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuzagdguq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ehwqpu.com/Article/details/gtgcfftzkx.html

[Q44] IN 子查询
来源：http://dali.c1oappe.top/Article/details/gttjkjtono.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.nanxuanxn.top/Article/details/gtkzyawjfj.html

[Q45] EXISTS 判断存在
来源：http://dali.sweek.top/Article/details/gtyflppmrt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gaohongyu789.top/Article/details/gttijizvjc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shuidangran.top/Article/details/gtxwaugdfz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinqigufen.top/Article/details/gtupizhkqq.html

[Q47] 与平均值比较
来源：http://dali.jqgfzy.top/Article/details/gthfaayawm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hongshengwenyu.top/Article/details/gtkowippfl.html

[Q48] CTE 公用表表达式
来源：http://dali.ybcxt.top/Article/details/gtjntdrjyz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.wangdashe.top/Article/details/gtdbsdwgsr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sufxvd.cn/Article/details/gtrhcpukvx.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gtedvuudjd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.smart0.xyz/Article/details/gtaimutqkp.html

[Q50] 批量更新
来源：http://dali.gzhubu.top/Article/details/gtqeyzrlnj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jqgufenzy.top/Article/details/gtukduuyug.html

[Q51] 用子查询更新
来源：http://dali.316326.xyz/Article/details/gtkvekfoht.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkipbhmms.html

[Q52] 删除指定行
来源：http://dali.tanke756.top/Article/details/gtfcysaqhn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhiwuduotai.top/Article/details/gtwjodudfv.html

[Q53] 按条件删除
来源：http://dali.shuidangran.top/Article/details/gtsnydccmb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jyoumei.cn/Article/details/gttkckralj.html

[Q54] 清空表
来源：http://dali.yj202588.top/Article/details/gtiyumbvbg.html

TRUNCATE TABLE logs;
来源：http://dali.sxryk.cn/Article/details/gtbkcvgiqh.html

[Q55] 排名（并列占位）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrcskdbzl.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hongshengwenyu.top/Article/details/gtektpitgp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.wangshuangyany.cn/Article/details/gtvhjqnmut.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cqqwz.cn/Article/details/gtqdayyvnm.html

[Q57] 行号
来源：http://dali.c1oappe.top/Article/details/gtxfsulyhe.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtnqmbhfzo.html

[Q58] 累计求和
来源：http://dali.nanxuanxn.top/Article/details/gticqtoxwo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.redwolf501.top/Article/details/gtrargmirn.html

[Q59] 分组内累计
来源：http://dali.ppjwa.cn/Article/details/gthnzthdla.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtppzmdpgr.html

[Q60] 取上一行 / 下一行
来源：http://dali.zycfv.cn/Article/details/gtifblhyug.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhengqikj.top/Article/details/gttzloaiaw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gtfgcgogvk.html

[Q61] 移动平均
来源：http://dali.haohaochexian.top/Article/details/gtyvphiliv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtttqwbijt.html

[Q62] 分组占比
来源：http://dali.aibaodan.cn/Article/details/gtuvlrymoa.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hnqzz.top/Article/details/gtiuqkblpz.html

[Q63] 开启事务
来源：http://dali.cheryme.top/Article/details/gtsnmxqyzm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ydzc1.top/Article/details/gtocrmpqws.html

[Q64] 提交事务
来源：http://dali.yueranfly.top/Article/details/gtujolutah.html

COMMIT;
来源：http://dali.9152youxi.cn/Article/details/gtpjtglukf.html

[Q65] 回滚事务
来源：http://dali.daxiang520.top/Article/details/gtlcldrcwv.html

ROLLBACK;
来源：http://dali.redwolf501.top/Article/details/gtqjdpjdcm.html

[Q66] 行锁查询
来源：http://dali.yj20258888.top/Article/details/gtwblpnler.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jinqigufen.top/Article/details/gtsmecngdc.html

[Q67] 设置隔离级别
来源：http://dali.dianchejie.cn/Article/details/gtwlzetrpo.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.iojbl.cn/Article/details/gtywtnkzxz.html

[Q68] 保存点
来源：http://dali.ybcxt.top/Article/details/gtnkirnybm.html

SAVEPOINT sp1;
来源：http://dali.gaohongyu789.top/Article/details/gtbdtowcsx.html

ROLLBACK TO sp1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlfvpoorh.html

[Q69] 查看执行计划
来源：http://dali.feifeiyinyue.top/Article/details/gtfqldhelv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gzhubu.top/Article/details/gtvhzchoao.html

[Q70] 更新统计信息
来源：http://dali.jqgfzy.top/Article/details/gthpvwyeym.html

ANALYZE TABLE users;
来源：http://dali.jinqigufen.top/Article/details/gtxdyocncz.html

[Q71] 查看建表语句
来源：http://dali.jqgufenzy.top/Article/details/gtswonyqfo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jinqigufen.top/Article/details/gtwcovohab.html

[Q72] 查看索引
来源：http://dali.andypj.xyz/Article/details/gtjmhgxpps.html

SHOW INDEX FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtwhisluwj.html

[Q73] 查看表状态
来源：http://dali.ppjwa.cn/Article/details/gtrjqqqdhr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jiagoushi.top/Article/details/gtpetoezvu.html

[Q74] 强制使用索引
来源：http://dali.shangyingyoupin.top/Article/details/gtsqypoece.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.gaohongyu789.top/Article/details/gthvebxlnu.html

[Q75] 日期格式化
来源：http://dali.dianchejie.cn/Article/details/gtuohfggth.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.mhx1999.top/Article/details/gtllodwobe.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.316326.xyz/Article/details/gtgjrzgile.html

[Q76] 按天统计
来源：http://dali.zhixingplan.top/Article/details/gtchmaomft.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.quarkkingdee.top/Article/details/gtiqwdokgb.html

[Q77] 时间加减
来源：http://dali.hnxiangtu.top/Article/details/gtjguzkwjl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yuanzhike.top/Article/details/gtnkkpklyx.html

[Q78] 当前时间
来源：http://dali.9152youxi.cn/Article/details/gtgtltdgdw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yanxiufei.cn/Article/details/gtqciagukp.html

[Q79] 字符串拼接
来源：http://dali.0kj1m.cn/Article/details/gtaaphoekc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.aizwys.cn/Article/details/gtkpsadzdl.html

[Q80] 字符串截取
来源：http://dali.yanxiufei.cn/Article/details/gtpmxtvnjg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtvupvnfng.html

[Q81] 字符串替换
来源：http://dali.vqdsnc.cn/Article/details/gtqnneqsam.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtonmhdvbr.html

[Q82] 字符长度与字节长度
来源：http://dali.tianlin.xyz/Article/details/gtsrlqqapj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gtcogzuekt.html

[Q83] 大小写转换
来源：http://dali.yvedp.cn/Article/details/gttztypzsq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtwimguvdc.html

[Q84] 去除首尾空格
来源：http://dali.zhongyouzk.top/Article/details/gtirjgkham.html

SELECT TRIM(name) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvlxnspay.html

[Q85] 数值取整
来源：http://dali.quarkkingdee.top/Article/details/gtzinsgkpp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.nanxuanxn.top/Article/details/gtgfyoqicu.html

[Q86] 读取 JSON 字段
来源：http://dali.dashuyun.cn/Article/details/gtikmsasvx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cdnleiting.top/Article/details/gtvkzauucz.html

[Q87] JSON 字段做条件
来源：http://dali.pycfn.com/Article/details/gtgwczpvcn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yuxming.cn/Article/details/gtyjrpeccx.html

[Q88] 行转列（条件聚合）
来源：http://dali.kuanghao11.cn/Article/details/gtbgqjyrrq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ybcxt.top/Article/details/gttyfsqyds.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yj20258888.top/Article/details/gtnsfobxlg.html

[Q89] 判断表是否存在
来源：http://dali.ehwqpu.com/Article/details/gtfxysdazi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbhntsdpt.html

[Q90] 生成序号列
来源：http://dali.nanxinkj.top/Article/details/gtsmmzlmko.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhiwuduotai.top/Article/details/gtzdvhshat.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtlnwzeisv.html

R. Bash 专题
来源：http://dali.ivvv.top/Article/details/gtnnitwbwe.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtchztzxfb.html

[R01] shebang 与严格模式
来源：http://dali.nanxinkj.top/Article/details/gtkkzcrris.html

#!/usr/bin/env bash
来源：http://dali.ydzc1.top/Article/details/gtzwfosnlq.html

set -euo pipefail
来源：http://dali.gzhubu.top/Article/details/gtnjastgpk.html

[R02] 变量赋值与使用
来源：http://dali.tian-w.cn/Article/details/gtlquawgjg.html

name="Tom"; echo "$name"
来源：http://dali.jiagoushi.top/Article/details/gtglzchgru.html

[R03] 只读变量
来源：http://dali.aibaodan.cn/Article/details/gtziteysgc.html

readonly PI=3.14
来源：http://dali.cqqwz.cn/Article/details/gticctokye.html

[R04] 位置参数
来源：http://dali.fengsongda.top/Article/details/gttadkprtz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhoulong.xyz/Article/details/gtcznsblxv.html

[R05] 参数默认值
来源：http://dali.hywenlv.cn/Article/details/gtxcnwnfqc.html

name="${1:-default}"
来源：http://dali.xuanzx.com/Article/details/gtlawggtfg.html

[R06] 判断命令是否存在
来源：http://dali.hfpthk.cn/Article/details/gthjpuctia.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shangyingyoupin.top/Article/details/gtkprbwlmq.html

[R07] if 判断文件
来源：http://dali.xinyue.icu/Article/details/gtdrbmiyit.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sweek.top/Article/details/gtuirphhud.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gtauwyfpsr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jinqigfzy.top/Article/details/gtdnmjqaxu.html

[R09] 字符串比较
来源：http://dali.smart0.xyz/Article/details/gtttijblls.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ehwqpu.com/Article/details/gtyaqkvilz.html

[R10] 正则匹配
来源：http://dali.fengsongda.top/Article/details/gtfflvsplg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gtxnrtbcdx.html

[R11] case 多分支
来源：http://dali.xziqi.cn/Article/details/gtlchjrhwv.html

case "$1" in
来源：http://dali.ivvv.top/Article/details/gtunkxjipj.html

start) echo "启动" ;;
来源：http://dali.tian-w.cn/Article/details/gtiojehudd.html

stop)  echo "停止" ;;
来源：http://dali.yuxming.cn/Article/details/gtxsfdlucq.html

*)     echo "未知命令" ;;
来源：http://dali.pycfn.com/Article/details/gtldxjpogg.html

esac
来源：http://dali.ydzc1.top/Article/details/gtwatmphrd.html

[R12] for 遍历文件
来源：http://dali.xziqi.cn/Article/details/gtmjbqygce.html

for f in *.txt; do echo "$f"; done
来源：http://dali.dashuyun.cn/Article/details/gtqlicfjwi.html

[R13] for 计数循环
来源：http://dali.gzhubu.top/Article/details/gtliphmhgv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xziqi.cn/Article/details/gtlqmzumqc.html

[R14] C 风格 for
来源：http://dali.ehwqpu.com/Article/details/gtfxvikkni.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hywenlv.cn/Article/details/gtmyzsmwhv.html

[R15] while 逐行读文件
来源：http://dali.fengsongda.top/Article/details/gtyeniiebb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.svipenyu.cn/Article/details/gtlbgvgpkm.html

[R16] until 等待条件
来源：http://dali.gotoacloud.top/Article/details/gtstpgkcyi.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.havefunace.top/Article/details/gtiuwjrqwd.html

[R17] 数组定义与取值
来源：http://dali.ehwqpu.com/Article/details/gtvnbtdbtl.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.andypj.xyz/Article/details/gtkbpkvjzl.html

[R18] 遍历数组
来源：http://dali.cashguo.top/Article/details/gtwoxayjck.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhixingplan.top/Article/details/gtxvfesaoy.html

[R19] 数组长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkyytkxul.html

echo "${#arr[@]}"
来源：http://dali.iojbl.cn/Article/details/gtqpafecrk.html

[R20] 关联数组（字典）
来源：http://dali.shangyingyoupin.top/Article/details/gtxpgwaqdu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zycfv.cn/Article/details/gtnrtbysjj.html

[R21] 字符串长度
来源：http://dali.yonumen.top/Article/details/gtjrapgukg.html

echo "${#s}"
来源：http://dali.ydzc1.top/Article/details/gtvhmzvcpv.html

[R22] 截取子串
来源：http://dali.hysaishi.cn/Article/details/gtnudlzoag.html

echo "${s:0:5}"
来源：http://dali.jinqigfzy.top/Article/details/gtdmwqcygd.html

[R23] 字符串替换
来源：http://dali.yuxming.cn/Article/details/gtbomlpqly.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhongyouzk.top/Article/details/gtutbnfkxw.html

[R24] 大小写转换
来源：http://dali.kuanghao11.cn/Article/details/gtwkepgcby.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yj20258.top/Article/details/gtqsnmesto.html

[R25] 去后缀 / 去前缀
来源：http://dali.sxryk.cn/Article/details/gtqyizbwbs.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.gotoacloud.top/Article/details/gtxklsqltx.html

[R26] 命令替换
来源：http://dali.yueranfly.top/Article/details/gtrpmgtygq.html

now=$(date +%F); echo "$now"
来源：http://dali.sxryk.cn/Article/details/gtcravmviy.html

[R27] 算术展开
来源：http://dali.cucudq.cn/Article/details/gtmsurmlbw.html

echo $((1 + 2 * 3))
来源：http://dali.cheryme.top/Article/details/gtxosxqvsr.html

[R28] 浮点运算
来源：http://dali.tianlin.xyz/Article/details/gtmyjmgxkv.html

echo "scale=2; 10/3" | bc
来源：http://dali.xziqi.cn/Article/details/gtmskvxhpx.html

[R29] 定义函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtilhsiriw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhixingplan.top/Article/details/gtzsbokukn.html

[R30] 函数返回状态码
来源：http://dali.316326.xyz/Article/details/gtrtcrjqbp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zycfv.cn/Article/details/gtmykckpjv.html

[R31] 局部变量
来源：http://dali.xinyue.icu/Article/details/gtbehxumac.html

f() { local x=1; echo "$x"; }
来源：http://dali.nanxinkj.top/Article/details/gtvhrnupmr.html

[R32] 参数个数校验
来源：http://dali.haohaochexian.top/Article/details/gtilturmvv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.daria6918.cn/Article/details/gtwjpmcjtc.html

[R33] 捕获错误并提示行号
来源：http://dali.havefunace.top/Article/details/gtkoocyetp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jinqigufen.top/Article/details/gtkvczlbye.html

[R34] 退出时清理
来源：http://dali.shanyushiyangtech.top/Article/details/gtjbvxftja.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.nwbrower.top/Article/details/gtwiagzsrk.html

[R35] 后台执行并等待
来源：http://dali.xylfe.cn/Article/details/gtuilxrqet.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgbfghuei.html

[R36] 并发执行多个任务
来源：http://dali.cucudq.cn/Article/details/gtcrtjbufl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yonumen.top/Article/details/gtjxylhara.html

[R37] 把输出赋给变量
来源：http://dali.gotoacloud.top/Article/details/gtkawcycni.html

files=$(ls -1)
来源：http://dali.nwbrower.top/Article/details/gtxekgypgj.html

[R38] 管道串联
来源：http://dali.dashuyun.cn/Article/details/gtaqgdphce.html

cat a.txt | grep -i error | wc -l
来源：http://dali.dashuyun.cn/Article/details/gtyorplvqs.html

[R39] 重定向标准输出与错误
来源：http://dali.haohaochexian.top/Article/details/gttaxefazy.html

cmd > out.log 2>&1
来源：http://dali.zycfv.cn/Article/details/gtllgktuxg.html

[R40] 追加写日志
来源：http://dali.xuetiantiany.cn/Article/details/gtaqgarpml.html

echo "log" >> out.log
来源：http://dali.quarkkingdee.top/Article/details/gtmdvpbdyg.html

[R41] 丢弃输出
来源：http://dali.chenzaomai.com/Article/details/gtgmanddpy.html

cmd >/dev/null 2>&1
来源：http://dali.yvedp.cn/Article/details/gtypqrlrlx.html

[R42] 输入重定向
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcxkcxwhd.html

wc -l < a.txt
来源：http://dali.gotoacloud.top/Article/details/gtstisbwnq.html

[R43] 按名字查找文件
来源：http://dali.yuxming.cn/Article/details/gtlmtpiyke.html

find . -name "*.log" -type f
来源：http://dali.c1oappe.top/Article/details/gtbpvlpvrn.html

[R44] 按修改时间查找
来源：http://dali.jinghuilouyu.cn/Article/details/gtajybukqb.html

find . -mtime -7 -type f
来源：http://dali.andypj.xyz/Article/details/gtsjsoobcm.html

[R45] 批量删除
来源：http://dali.smart0.xyz/Article/details/gteyuwypxz.html

find . -name "*.tmp" -delete
来源：http://dali.yvedp.cn/Article/details/gtdlejnngg.html

[R46] 递归替换文件内容
来源：http://dali.shanyushiyangtech.top/Article/details/gtqhhuxljm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yvedp.cn/Article/details/gtwzahzgil.html

[R47] sed 单行替换
来源：http://dali.gaohongyu789.top/Article/details/gtfjtrmblw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ppjwa.cn/Article/details/gtcnlhwomw.html

[R48] awk 取指定列
来源：http://dali.sweek.top/Article/details/gtkxyuhrye.html

awk '{print $1, $3}' a.txt
来源：http://dali.cashguo.top/Article/details/gtpnhrfwsi.html

[R49] awk 带条件
来源：http://dali.jlsjyb.cn/Article/details/gtdiovdzxt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.tanke756.top/Article/details/gtlxstrcun.html

[R50] awk 求和
来源：http://dali.xylfe.cn/Article/details/gtzqiulbtr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtuovkuviu.html

[R51] 排序去重取前几
来源：http://dali.feifeiyinyue.top/Article/details/gtlvdkcawt.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqnitxesi.html

[R52] 统计行数
来源：http://dali.gzhubu.top/Article/details/gtcgljqlbs.html

wc -l a.txt
来源：http://dali.yj20258.top/Article/details/gtgzgnzwio.html

[R53] 查看文件头与实时尾
来源：http://dali.daria6918.cn/Article/details/gtcadztloc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwuybmavv.html

[R54] 比较两个文件
来源：http://dali.yj20258888.top/Article/details/gtuzgdgzbj.html

diff a.txt b.txt
来源：http://dali.sysykeji.top/Article/details/gtqrmwfrws.html

[R55] 压缩与解压
来源：http://dali.chenzaomai.com/Article/details/gtpybixtpd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.daxiang520.top/Article/details/gtgapjrrqt.html

[R56] 远程拷贝
来源：http://dali.zhengqikj.top/Article/details/gtsiuusnpu.html

scp file user@host:/path/
来源：http://dali.guowangkeji.top/Article/details/gtdqyvpppn.html

[R57] 远程执行命令
来源：http://dali.yangfankeji.com/Article/details/gtjywcllzf.html

ssh user@host 'uptime'
来源：http://dali.daria6918.cn/Article/details/gtbdrbrcav.html

[R58] 下载文件
来源：http://dali.xylfe.cn/Article/details/gtphxjtqss.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.chenjidiqi.icu/Article/details/gtpwjovcsw.html

[R59] 发 POST JSON
来源：http://dali.cqqwz.cn/Article/details/gtbgacswzt.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shanyushiyangtech.top/Article/details/gtxsoknhdz.html

[R60] 只看 HTTP 状态码
来源：http://dali.iojbl.cn/Article/details/gtonnqpeql.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.chenlongwang.top/Article/details/gtuhhvusru.html

[R61] 磁盘占用
来源：http://dali.iojbl.cn/Article/details/gtzlywzhue.html

df -h;  du -sh *
来源：http://dali.iojbl.cn/Article/details/gtpkwtihhz.html

[R62] 找最占空间的文件
来源：http://dali.aizwys.cn/Article/details/gtbfenkmhv.html

du -ah . | sort -rh | head -10
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdnrkewfd.html

[R63] 内存与进程
来源：http://dali.guowangkeji.top/Article/details/gtlqpdglng.html


<!-- 参考信息 -->