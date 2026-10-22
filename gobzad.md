代发 wailian999

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yuxming.cn/Article/details/gtaaipxaqw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.dashuyun.cn/Article/details/gtimzvxrbn.html

[Q13] 忽略重复插入
来源：http://dali.shuidangran.top/Article/details/gtovccrufh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shzxlz.cn/Article/details/gtaroulhbh.html

[Q14] 存在则更新（upsert）
来源：http://dali.bjfxy.top/Article/details/gtuovltzcf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.chenjidiqi.icu/Article/details/gtybtqpiuh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cheryme.top/Article/details/gtmbrvapcq.html

[Q15] 查询全部
来源：http://dali.dashuyun.cn/Article/details/gteqkcfpgq.html

SELECT * FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdtphiqrk.html

[Q16] 查询指定列
来源：http://dali.cdnleiting.top/Article/details/gtpqubnlbp.html

SELECT id, name FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtshldxfzd.html

[Q17] 条件查询
来源：http://dali.sysykeji.top/Article/details/gttecfhakb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtdwuzjklw.html

[Q18] 模糊匹配
来源：http://dali.kuanghao11.cn/Article/details/gtyammcbsf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.snrcjt.cn/Article/details/gtesfgyayi.html

[Q19] 范围查询
来源：http://dali.jqgufenzy.top/Article/details/gtfzxhvpbt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shangyingyoupin.top/Article/details/gtlqegmrib.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gtcbfzjrws.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yj202588.top/Article/details/gtpsagqvft.html

[Q21] 空值判断
来源：http://dali.cqqwz.cn/Article/details/gtgazhjmnl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.tianlin.xyz/Article/details/gtfneqzynt.html

[Q22] 排序
来源：http://dali.hnxiangtu.top/Article/details/gtyffwpohv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gotoacloud.top/Article/details/gtdggablcr.html

[Q23] 分页
来源：http://dali.shangyingyoupin.top/Article/details/gtsupotnbk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cqqwz.cn/Article/details/gthbfucpas.html

[Q24] 去重
来源：http://dali.gzhubu.top/Article/details/gtqgjcxbta.html

SELECT DISTINCT city FROM users;
来源：http://dali.ybcxt.top/Article/details/gtnmmdrnvm.html

[Q25] 只取前 N 条
来源：http://dali.havefunace.top/Article/details/gtxneebywv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.nanxuanxn.top/Article/details/gtoqpaqkgl.html

[Q26] 计数
来源：http://dali.guowangkeji.top/Article/details/gthcdbzifi.html

SELECT COUNT(*) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtrgchsomy.html

[Q27] 条件计数
来源：http://dali.chenzaomai.com/Article/details/gtvcaufapu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtmpzofgee.html

[Q28] 求和与平均
来源：http://dali.dashuyun.cn/Article/details/gtsumcrecg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yvedp.cn/Article/details/gtrrkhrufy.html

[Q29] 最大最小值
来源：http://dali.ybcxt.top/Article/details/gtunhzllrh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtombddzpv.html

[Q30] 分组统计
来源：http://dali.xziqi.cn/Article/details/gtsoaxowoi.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.havefunace.top/Article/details/gtqfvhzjcs.html

[Q31] 分组后过滤
来源：http://dali.sysykeji.top/Article/details/gtvgqfuzeq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.meibo888.top/Article/details/gtxyjjyjvz.html

[Q32] 分组拼接字符串
来源：http://dali.daria6918.cn/Article/details/gtkxzczgqw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hfpthk.cn/Article/details/gtzirxsdwh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ivvv.top/Article/details/gtwjjqevyu.html

[Q33] 多列分组
来源：http://dali.zhoulong.xyz/Article/details/gtstrrgdri.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gotoacloud.top/Article/details/gttejolrhu.html

[Q34] 每组取第一条
来源：http://dali.chenjidiqi.icu/Article/details/gtmwdhfbqg.html

SELECT * FROM (
来源：http://dali.yuanzhike.top/Article/details/gtmzigyhva.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shuidangran.top/Article/details/gttyhsbecg.html

) t WHERE rn = 1;
来源：http://dali.havefunace.top/Article/details/gtkbmngvai.html

[Q35] 内连接
来源：http://dali.shanyushiyangtech.top/Article/details/gtujfctvjp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxuanxn.top/Article/details/gtwejswhjf.html

[Q36] 左连接
来源：http://dali.yj202588.top/Article/details/gtbmdfyeba.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.fengsongda.top/Article/details/gtlmpqzcrz.html

[Q37] 右连接
来源：http://dali.yongpay.top/Article/details/gtfncyaetb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.redwolf501.top/Article/details/gtevhcjmke.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xuanzx.com/Article/details/gtqkahgtqd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jianghu66.top/Article/details/gtdzwauwdy.html

[Q39] 自连接（查上下级）
来源：http://dali.haohaochexian.top/Article/details/gtvkgrgfiv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hnxiangtu.top/Article/details/gtgylfiogf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.pengpengdd.cyou/Article/details/gtovzuilrb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cheryme.top/Article/details/gtborhncsf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xylfe.cn/Article/details/gttxrvxkyp.html

[Q41] 多表连接
来源：http://dali.gogol.net.cn/Article/details/gtbmfwhqtw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.wangdashe.top/Article/details/gtnlnmffoj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gotoacloud.top/Article/details/gtsunniyrg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ybcxt.top/Article/details/gtycljnjfv.html

[Q42] 连接条件附加过滤
来源：http://dali.cucudq.cn/Article/details/gtqjrgdwjf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jiagoushi.top/Article/details/gtkguuaogo.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.vqdsnc.cn/Article/details/gtcqinitla.html

[Q43] 标量子查询
来源：http://dali.wangshuangyany.cn/Article/details/gtunlyelio.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.316326.xyz/Article/details/gtihcgcyvc.html

[Q44] IN 子查询
来源：http://dali.haohaochexian.top/Article/details/gtcuksseja.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.andypj.xyz/Article/details/gtjnndnvhl.html

[Q45] EXISTS 判断存在
来源：http://dali.gaohongyu789.top/Article/details/gtgqnifqpz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtepekchwb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xuanzx.com/Article/details/gttwmvtgpp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258888.top/Article/details/gtwtiowuyx.html

[Q47] 与平均值比较
来源：http://dali.birdmap.top/Article/details/gtjhwexuco.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ppjwa.cn/Article/details/gtqdstqvrd.html

[Q48] CTE 公用表表达式
来源：http://dali.aibaodan.cn/Article/details/gtpzymkuwo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.meibo888.top/Article/details/gtvrzvgsna.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gotoacloud.top/Article/details/gtxtwymoqn.html

[Q49] 更新单行
来源：http://dali.yj202588.top/Article/details/gtpgjuskty.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hfpthk.cn/Article/details/gtxfqxircd.html

[Q50] 批量更新
来源：http://dali.zhixingplan.top/Article/details/gtzkkdstko.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.birdmap.top/Article/details/gtmyvzazkx.html

[Q51] 用子查询更新
来源：http://dali.yongpay.top/Article/details/gtwaipxlnl.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hnqzz.top/Article/details/gtcqbizoiq.html

[Q52] 删除指定行
来源：http://dali.fzhhl.top/Article/details/gtfjtrbzlw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.chenlongwang.top/Article/details/gtrpuswjjd.html

[Q53] 按条件删除
来源：http://dali.cucudq.cn/Article/details/gtiuyqydvq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.sweek.top/Article/details/gtwrtsyuuh.html

[Q54] 清空表
来源：http://dali.jinqigufen.top/Article/details/gtntvfmjuj.html

TRUNCATE TABLE logs;
来源：http://dali.yuanzhike.top/Article/details/gtcukmptqd.html

[Q55] 排名（并列占位）
来源：http://dali.ehwqpu.com/Article/details/gtvlryehuv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ivvv.top/Article/details/gtgljywojq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.smart0.xyz/Article/details/gtwozulgij.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.pycfn.com/Article/details/gtzzwygkiu.html

[Q57] 行号
来源：http://dali.shzxlz.cn/Article/details/gttlnnsamg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yuxming.cn/Article/details/gtdvfdlbty.html

[Q58] 累计求和
来源：http://dali.shuidangran.top/Article/details/gtdprqubyj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.smart0.xyz/Article/details/gtbuosjyow.html

[Q59] 分组内累计
来源：http://dali.yuxming.cn/Article/details/gtbypqkrzl.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hnqzz.top/Article/details/gtnbhepiqz.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsjvyvzuq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yvedp.cn/Article/details/gtptrdrbht.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sweek.top/Article/details/gtereegobq.html

[Q61] 移动平均
来源：http://dali.haohaochexian.top/Article/details/gtilabpqbp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yuxming.cn/Article/details/gtrqufodha.html

[Q62] 分组占比
来源：http://dali.daxiang520.top/Article/details/gtrtsqqtul.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cdnleiting.top/Article/details/gtynginweh.html

[Q63] 开启事务
来源：http://dali.cashguo.top/Article/details/gtovqibcet.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinghuilouyu.cn/Article/details/gtewzrhttj.html

[Q64] 提交事务
来源：http://dali.jqgufenzy.top/Article/details/gtaeyklsuu.html

COMMIT;
来源：http://dali.nwbrower.top/Article/details/gtakkhcxwk.html

[Q65] 回滚事务
来源：http://dali.zycfv.cn/Article/details/gtcwdvqqpf.html

ROLLBACK;
来源：http://dali.aizwys.cn/Article/details/gtwdkvvejf.html

[Q66] 行锁查询
来源：http://dali.jlsjyb.cn/Article/details/gteykshyix.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yanxiufei.cn/Article/details/gtcfkicdmf.html

[Q67] 设置隔离级别
来源：http://dali.wangshuangyany.cn/Article/details/gtpilevsbw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.meibo888.top/Article/details/gtcchvbqll.html

[Q68] 保存点
来源：http://dali.cdnleiting.top/Article/details/gtwkbownbr.html

SAVEPOINT sp1;
来源：http://dali.hongshengwenyu.top/Article/details/gtqlkzyabr.html

ROLLBACK TO sp1;
来源：http://dali.daxiang520.top/Article/details/gtmmqlnrgf.html

[Q69] 查看执行计划
来源：http://dali.hongshengwenyu.top/Article/details/gtytelmnul.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gzhubu.top/Article/details/gtfpmldroe.html

[Q70] 更新统计信息
来源：http://dali.c1oappe.top/Article/details/gtkggpuwtm.html

ANALYZE TABLE users;
来源：http://dali.guowangkeji.top/Article/details/gtdwplimmc.html

[Q71] 查看建表语句
来源：http://dali.zhoulong.xyz/Article/details/gtlpbsvdes.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yangfankeji.com/Article/details/gtsroltyzy.html

[Q72] 查看索引
来源：http://dali.nwbrower.top/Article/details/gtjpqmvqqt.html

SHOW INDEX FROM users;
来源：http://dali.yj202588.top/Article/details/gtafxefvrf.html

[Q73] 查看表状态
来源：http://dali.snrcjt.cn/Article/details/gtzcaxggib.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hnqzz.top/Article/details/gtwpcindkg.html

[Q74] 强制使用索引
来源：http://dali.xuetiantiany.cn/Article/details/gtjtqdlfbd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hnqzz.top/Article/details/gtgqcsupke.html

[Q75] 日期格式化
来源：http://dali.guannengcc.top/Article/details/gtbklwmslr.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.andypj.xyz/Article/details/gtxtutwbrx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yuxming.cn/Article/details/gtrisyjdvh.html

[Q76] 按天统计
来源：http://dali.ydzc1.top/Article/details/gtayhkvzvw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.9152youxi.cn/Article/details/gtfhmdfajt.html

[Q77] 时间加减
来源：http://dali.gotoacloud.top/Article/details/gtnwffxknq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.nanxinkj.top/Article/details/gthpohxovh.html

[Q78] 当前时间
来源：http://dali.nanxuanxn.top/Article/details/gtxccnlsxb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhixingplan.top/Article/details/gtwgzuvvss.html

[Q79] 字符串拼接
来源：http://dali.zhoulong.xyz/Article/details/gtudbauapv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.nwbrower.top/Article/details/gtguowmzby.html

[Q80] 字符串截取
来源：http://dali.hongshengwenyu.top/Article/details/gtqszcnrnc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cheryme.top/Article/details/gtydmaftzo.html

[Q81] 字符串替换
来源：http://dali.mhx1999.top/Article/details/gtecbfbbpb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yongpay.top/Article/details/gtovitiqqt.html

[Q82] 字符长度与字节长度
来源：http://dali.zdqjudy.top/Article/details/gtzhmfoihw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtsfmszxwm.html

[Q83] 大小写转换
来源：http://dali.xuetiantiany.cn/Article/details/gtcruyxcty.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtewygtmju.html

[Q84] 去除首尾空格
来源：http://dali.daria6918.cn/Article/details/gtaktvsnlk.html

SELECT TRIM(name) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtgdaiiyrr.html

[Q85] 数值取整
来源：http://dali.cdnleiting.top/Article/details/gtvxgbiulj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jyoumei.cn/Article/details/gtwbdmmgba.html

[Q86] 读取 JSON 字段
来源：http://dali.havefunace.top/Article/details/gtnhgbqwfe.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cashguo.top/Article/details/gtvcoemekq.html

[Q87] JSON 字段做条件
来源：http://dali.nanxuanxn.top/Article/details/gtpxnjsmmj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.nanxinkj.top/Article/details/gtrkryaogt.html

[Q88] 行转列（条件聚合）
来源：http://dali.xuetiantiany.cn/Article/details/gtpxfguprz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yonumen.top/Article/details/gtwacrjsqr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtfubblzny.html

[Q89] 判断表是否存在
来源：http://dali.xinyue.icu/Article/details/gtmidqnusy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ydzc1.top/Article/details/gthuxlktik.html

[Q90] 生成序号列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtncwgehnd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.316326.xyz/Article/details/gtzuryxmva.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtsedjptce.html

R. Bash 专题
来源：http://dali.ivvv.top/Article/details/gthizugrzt.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtklcsuril.html

[R01] shebang 与严格模式
来源：http://dali.hammf.cn/Article/details/gtthlhysgj.html

#!/usr/bin/env bash
来源：http://dali.gaohongyu789.top/Article/details/gthajvcpxf.html

set -euo pipefail
来源：http://dali.zhixingplan.top/Article/details/gtkhvqdmmk.html

[R02] 变量赋值与使用
来源：http://dali.daria6918.cn/Article/details/gtujwnqwhe.html

name="Tom"; echo "$name"
来源：http://dali.chenlongwang.top/Article/details/gterdlwzia.html

[R03] 只读变量
来源：http://dali.9152youxi.cn/Article/details/gtaqvbzfdy.html

readonly PI=3.14
来源：http://dali.c1oappe.top/Article/details/gtywfofygd.html

[R04] 位置参数
来源：http://dali.gotoacloud.top/Article/details/gtqasldbwu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ivvv.top/Article/details/gtcuckltmw.html

[R05] 参数默认值
来源：http://dali.dashuyun.cn/Article/details/gtqdohwmkd.html

name="${1:-default}"
来源：http://dali.daria6918.cn/Article/details/gtepubhukf.html

[R06] 判断命令是否存在
来源：http://dali.sufxvd.cn/Article/details/gtoqzzaahe.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.nwbrower.top/Article/details/gtzpwggirr.html

[R07] if 判断文件
来源：http://dali.yj20258.top/Article/details/gtsfhloopx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.dashuyun.cn/Article/details/gtqyzayizb.html

[R08] 数值比较
来源：http://dali.aizwys.cn/Article/details/gtzuygojlm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shzxlz.cn/Article/details/gthjykkjpc.html

[R09] 字符串比较
来源：http://dali.0kj1m.cn/Article/details/gtkrlzdtol.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhixingplan.top/Article/details/gtdvavukdq.html

[R10] 正则匹配
来源：http://dali.gogol.net.cn/Article/details/gtdhezvvvu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hnqzz.top/Article/details/gtqrgvryrs.html

[R11] case 多分支
来源：http://dali.yuxming.cn/Article/details/gtgmizaoff.html

case "$1" in
来源：http://dali.yj20258888.top/Article/details/gtbhqghgcb.html

start) echo "启动" ;;
来源：http://dali.yuanzhike.top/Article/details/gtfkadfymh.html

stop)  echo "停止" ;;
来源：http://dali.shanyushiyangtech.top/Article/details/gtfcttoilu.html

*)     echo "未知命令" ;;
来源：http://dali.yj20258888.top/Article/details/gtzxrduifm.html

esac
来源：http://dali.vqdsnc.cn/Article/details/gtyzazsccq.html

[R12] for 遍历文件
来源：http://dali.redwolf501.top/Article/details/gtazwjgyhl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cdnleiting.top/Article/details/gtbxqokjqa.html

[R13] for 计数循环
来源：http://dali.andypj.xyz/Article/details/gtuyeashsn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jqgufenzy.top/Article/details/gtpyhncisl.html

[R14] C 风格 for
来源：http://dali.xuetiantiany.cn/Article/details/gtapwfdiiv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sysykeji.top/Article/details/gtthoblnbo.html

[R15] while 逐行读文件
来源：http://dali.nanxinkj.top/Article/details/gtpleazahe.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.daria6918.cn/Article/details/gtzffjjbon.html

[R16] until 等待条件
来源：http://dali.redwolf501.top/Article/details/gtekafydjy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.kuanghao11.cn/Article/details/gtyugnncue.html

[R17] 数组定义与取值
来源：http://dali.nwbrower.top/Article/details/gtzsgpxydw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.tanke756.top/Article/details/gtypgvpjkk.html

[R18] 遍历数组
来源：http://dali.iojbl.cn/Article/details/gthdovmyqm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhixingplan.top/Article/details/gthzrfdjlc.html

[R19] 数组长度
来源：http://dali.xinyue.icu/Article/details/gtqkpsvtka.html

echo "${#arr[@]}"
来源：http://dali.gogol.net.cn/Article/details/gttkfvhosk.html

[R20] 关联数组（字典）
来源：http://dali.dianchejie.cn/Article/details/gttjiqeeup.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsubxmfcs.html

[R21] 字符串长度
来源：http://dali.redwolf501.top/Article/details/gtkuajwvkh.html

echo "${#s}"
来源：http://dali.yj20258888.top/Article/details/gtqwryjdrn.html

[R22] 截取子串
来源：http://dali.yanxiufei.cn/Article/details/gtdmxmrtcg.html

echo "${s:0:5}"
来源：http://dali.mhx1999.top/Article/details/gtfcfkvmjz.html

[R23] 字符串替换
来源：http://dali.guannengcc.top/Article/details/gthzktotso.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yvedp.cn/Article/details/gtaxnkuojv.html

[R24] 大小写转换
来源：http://dali.jlsjyb.cn/Article/details/gtufwfwwoy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.snrcjt.cn/Article/details/gtvuznrwiy.html

[R25] 去后缀 / 去前缀
来源：http://dali.fzhhl.top/Article/details/gtzetqdqbr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ybcxt.top/Article/details/gtywgvybey.html

[R26] 命令替换
来源：http://dali.guowangkeji.top/Article/details/gttdzqyjow.html

now=$(date +%F); echo "$now"
来源：http://dali.zhiwuduotai.top/Article/details/gtznbovosm.html

[R27] 算术展开
来源：http://dali.daxiang520.top/Article/details/gtnfnybxcx.html

echo $((1 + 2 * 3))
来源：http://dali.yj202588.top/Article/details/gtwxuqhwuq.html

[R28] 浮点运算
来源：http://dali.redwolf501.top/Article/details/gtrgqxrluh.html

echo "scale=2; 10/3" | bc
来源：http://dali.cdnleiting.top/Article/details/gtxgdjtcdw.html

[R29] 定义函数
来源：http://dali.jlsjyb.cn/Article/details/gtacggbjpe.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hywenlv.cn/Article/details/gtdngoucpd.html

[R30] 函数返回状态码
来源：http://dali.andypj.xyz/Article/details/gtgsxzswdq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.gotoacloud.top/Article/details/gtbufgkgdv.html

[R31] 局部变量
来源：http://dali.hammf.cn/Article/details/gtucwrofrm.html

f() { local x=1; echo "$x"; }
来源：http://dali.zycfv.cn/Article/details/gtasvlhrgy.html

[R32] 参数个数校验
来源：http://dali.ybcxt.top/Article/details/gtdhmibbxe.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.smart0.xyz/Article/details/gtfnhcihzr.html

[R33] 捕获错误并提示行号
来源：http://dali.ydzc1.top/Article/details/gtgkzgeflw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hnxiangtu.top/Article/details/gtbifkzhac.html

[R34] 退出时清理
来源：http://dali.zycfv.cn/Article/details/gttjtqughh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.guannengcc.top/Article/details/gtgmohwgan.html

[R35] 后台执行并等待
来源：http://dali.zhoulong.xyz/Article/details/gtehdgteqo.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.quarkkingdee.top/Article/details/gtokkvliwl.html

[R36] 并发执行多个任务
来源：http://dali.nanxuanxn.top/Article/details/gtryffbqap.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.chenjidiqi.icu/Article/details/gtypgjxqvi.html

[R37] 把输出赋给变量
来源：http://dali.ydzc1.top/Article/details/gtczwgfazq.html

files=$(ls -1)
来源：http://dali.andypj.xyz/Article/details/gthpsriylg.html

[R38] 管道串联
来源：http://dali.jqgfzy.top/Article/details/gteghtoabc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.fengsongda.top/Article/details/gtysjltzwt.html

[R39] 重定向标准输出与错误
来源：http://dali.dashuyun.cn/Article/details/gtbtszqlom.html

cmd > out.log 2>&1
来源：http://dali.cashguo.top/Article/details/gtgzunlxvh.html

[R40] 追加写日志
来源：http://dali.svipenyu.cn/Article/details/gtkknjbxpz.html

echo "log" >> out.log
来源：http://dali.pengpengdd.cyou/Article/details/gttmxvnstg.html

[R41] 丢弃输出
来源：http://dali.gaohongyu789.top/Article/details/gtmphhyium.html

cmd >/dev/null 2>&1
来源：http://dali.gaohongyu789.top/Article/details/gthkmfreop.html

[R42] 输入重定向
来源：http://dali.shangyingyoupin.top/Article/details/gtzlmxrtaz.html

wc -l < a.txt
来源：http://dali.ydzc1.top/Article/details/gtvkjolmyw.html

[R43] 按名字查找文件
来源：http://dali.guowangkeji.top/Article/details/gtqtcmsgiz.html

find . -name "*.log" -type f
来源：http://dali.aizwys.cn/Article/details/gtnqpzxzka.html

[R44] 按修改时间查找
来源：http://dali.daxiang520.top/Article/details/gtzbsgfioz.html

find . -mtime -7 -type f
来源：http://dali.quarkkingdee.top/Article/details/gtqzzayfse.html

[R45] 批量删除
来源：http://dali.aibaodan.cn/Article/details/gtimmyscif.html

find . -name "*.tmp" -delete
来源：http://dali.mhx1999.top/Article/details/gtifbpltjd.html

[R46] 递归替换文件内容
来源：http://dali.ivvv.top/Article/details/gtyvfermhg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jyoumei.cn/Article/details/gtqcwbsfhj.html

[R47] sed 单行替换
来源：http://dali.mhx1999.top/Article/details/gtpayebksc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtosflfdzx.html

[R48] awk 取指定列
来源：http://dali.jqgufenzy.top/Article/details/gtmtuuuecj.html

awk '{print $1, $3}' a.txt
来源：http://dali.guannengcc.top/Article/details/gtkeizuahr.html

[R49] awk 带条件
来源：http://dali.gzhubu.top/Article/details/gtuyvcgupi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.fengsongda.top/Article/details/gtqyspbvqh.html

[R50] awk 求和
来源：http://dali.9152youxi.cn/Article/details/gtcehpkgwo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtazkfrtkg.html

[R51] 排序去重取前几
来源：http://dali.redwolf501.top/Article/details/gtdvzzvdhg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.daria6918.cn/Article/details/gtgaxxabcn.html

[R52] 统计行数
来源：http://dali.gogol.net.cn/Article/details/gtkzlylkkk.html

wc -l a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtvjravtpb.html

[R53] 查看文件头与实时尾
来源：http://dali.pycfn.com/Article/details/gtkagvrlyp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hywenlv.cn/Article/details/gtzlzoxsig.html

[R54] 比较两个文件
来源：http://dali.c1oappe.top/Article/details/gtgixmljoa.html

diff a.txt b.txt
来源：http://dali.sufxvd.cn/Article/details/gtdpbrhhbi.html

[R55] 压缩与解压
来源：http://dali.yonumen.top/Article/details/gtarpafpix.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhixingplan.top/Article/details/gtxymnkjch.html

[R56] 远程拷贝
来源：http://dali.cheryme.top/Article/details/gtssgupwmp.html

scp file user@host:/path/
来源：http://dali.yj20258888.top/Article/details/gtinmgetej.html

[R57] 远程执行命令
来源：http://dali.cucudq.cn/Article/details/gtupcvladt.html

ssh user@host 'uptime'
来源：http://dali.gogol.net.cn/Article/details/gthiaplbld.html

[R58] 下载文件
来源：http://dali.vqdsnc.cn/Article/details/gtidezqvun.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.aizwys.cn/Article/details/gtoljcaova.html

[R59] 发 POST JSON
来源：http://dali.zhiwuduotai.top/Article/details/gtbycslast.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cashguo.top/Article/details/gtqzuapxlx.html

[R60] 只看 HTTP 状态码
来源：http://dali.jlsjyb.cn/Article/details/gtbcqahlur.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sxryk.cn/Article/details/gtnufahlhl.html

[R61] 磁盘占用
来源：http://dali.yuanzhike.top/Article/details/gtytilbker.html


<!-- 参考信息 -->