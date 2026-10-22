代发 wailian999

[Q14] 存在则更新（upsert）
来源：http://dali.wangdashe.top/Article/details/gt2viozjvoq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.sxryk.cn/Article/details/gt2geglalms.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sysykeji.top/Article/details/gt2evkpnzyf.html

[Q15] 查询全部
来源：http://dali.sufxvd.cn/Article/details/gt2xpgzkual.html

SELECT * FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2ikmfclpg.html

[Q16] 查询指定列
来源：http://dali.fengsongda.top/Article/details/gt2ehgrvsoc.html

SELECT id, name FROM users;
来源：http://dali.jinqigufen.top/Article/details/gt2vdbcpppo.html

[Q17] 条件查询
来源：http://dali.aizwys.cn/Article/details/gt2xolxphpt.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gt2onhqrpqf.html

[Q18] 模糊匹配
来源：http://dali.yuxming.cn/Article/details/gt2nlrycuzh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cheryme.top/Article/details/gt2qnoqcdxo.html

[Q19] 范围查询
来源：http://dali.cucudq.cn/Article/details/gt2wosrlckq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jiagoushi.top/Article/details/gt2gcokstdo.html

[Q20] IN 列表
来源：http://dali.snrcjt.cn/Article/details/gt2nsxcafpz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ehwqpu.com/Article/details/gt2pvymkszk.html

[Q21] 空值判断
来源：http://dali.fengsongda.top/Article/details/gt2zzifkana.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jlsjyb.cn/Article/details/gt2plrlvmpv.html

[Q22] 排序
来源：http://dali.jianghu66.top/Article/details/gt2cydzlcqa.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.dianchejie.cn/Article/details/gt2qyeiunbf.html

[Q23] 分页
来源：http://dali.pengpengdd.cyou/Article/details/gt2hwfapvso.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jqgufenzy.top/Article/details/gt2ymehkezp.html

[Q24] 去重
来源：http://dali.tian-w.cn/Article/details/gt2gzxjpiwh.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2agwgnuvg.html

[Q25] 只取前 N 条
来源：http://dali.hfpthk.cn/Article/details/gt2thiocqje.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.quarkkingdee.top/Article/details/gt2bhxlugoh.html

[Q26] 计数
来源：http://dali.zhongyouzk.top/Article/details/gt2tlpdqcxy.html

SELECT COUNT(*) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2kseakfvr.html

[Q27] 条件计数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dhitbcme.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2tdohtgay.html

[Q28] 求和与平均
来源：http://dali.redwolf501.top/Article/details/gt2atkbodpn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gt2uhguikrz.html

[Q29] 最大最小值
来源：http://dali.havefunace.top/Article/details/gt2ibukwewd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.sweek.top/Article/details/gt2chhckkox.html

[Q30] 分组统计
来源：http://dali.yj202588.top/Article/details/gt2rvafrkdf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jinqigufen.top/Article/details/gt2qnvbheak.html

[Q31] 分组后过滤
来源：http://dali.xziqi.cn/Article/details/gt2bpyvjpfp.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.gogol.net.cn/Article/details/gt2alrtgzsj.html

[Q32] 分组拼接字符串
来源：http://dali.gzhubu.top/Article/details/gt2zyetgcbo.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jlsjyb.cn/Article/details/gt2mdtejncf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xuetiantiany.cn/Article/details/gt2ntcnuuwb.html

[Q33] 多列分组
来源：http://dali.jinqigfzy.top/Article/details/gt2smnctekk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jyyhfprv.html

[Q34] 每组取第一条
来源：http://dali.cheryme.top/Article/details/gt2xilquweo.html

SELECT * FROM (
来源：http://dali.yj20258.top/Article/details/gt2qfkpbown.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cdnleiting.top/Article/details/gt2rgeqzkqz.html

) t WHERE rn = 1;
来源：http://dali.fengsongda.top/Article/details/gt2wqawozrz.html

[Q35] 内连接
来源：http://dali.pengpengdd.cyou/Article/details/gt2prepuhhn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.316326.xyz/Article/details/gt2ihdkmwns.html

[Q36] 左连接
来源：http://dali.sxryk.cn/Article/details/gt2chthgmgw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.9152youxi.cn/Article/details/gt2umpoaipw.html

[Q37] 右连接
来源：http://dali.yangfankeji.com/Article/details/gt2tfirtbgj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xinyue.icu/Article/details/gt2wztqbjqr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.daria6918.cn/Article/details/gt2xrnkupul.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cucudq.cn/Article/details/gt2nauucseh.html

[Q39] 自连接（查上下级）
来源：http://dali.gogol.net.cn/Article/details/gt2fvhqhnkq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ivvv.top/Article/details/gt2vdtckixd.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.feifeiyinyue.top/Article/details/gt2gffrzcmz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jiagoushi.top/Article/details/gt2mlkvvacq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jyoumei.cn/Article/details/gt2iftweqqh.html

[Q41] 多表连接
来源：http://dali.zhengqikj.top/Article/details/gt2fjkfgaqa.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xuanzx.com/Article/details/gt2gvnjintd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xziqi.cn/Article/details/gt2xnybadbv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shangyingyoupin.top/Article/details/gt2muyeslni.html

[Q42] 连接条件附加过滤
来源：http://dali.gotoacloud.top/Article/details/gt2jbcuihwr.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhengqikj.top/Article/details/gt2duikokpb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.feifeiyinyue.top/Article/details/gt2peusczqc.html

[Q43] 标量子查询
来源：http://dali.cdnleiting.top/Article/details/gt2bbqtbyaf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.gaohongyu789.top/Article/details/gt2fjsmwpxn.html

[Q44] IN 子查询
来源：http://dali.nwbrower.top/Article/details/gt2mhfmjxht.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jqgufenzy.top/Article/details/gt2kkwudmvp.html

[Q45] EXISTS 判断存在
来源：http://dali.iojbl.cn/Article/details/gt2cktrqaoi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nwbrower.top/Article/details/gt2axrwrwsb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jinqigfzy.top/Article/details/gt2izxuspox.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.snrcjt.cn/Article/details/gt2ztkohiux.html

[Q47] 与平均值比较
来源：http://dali.xuanzx.com/Article/details/gt2ogkawnnt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ydzc1.top/Article/details/gt2pwswjffr.html

[Q48] CTE 公用表表达式
来源：http://dali.hnqzz.top/Article/details/gt2ybvjphsk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zlhsdcxt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.kuanghao11.cn/Article/details/gt2pagmudnx.html

[Q49] 更新单行
来源：http://dali.andypj.xyz/Article/details/gt2qrfjzmko.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.haohaochexian.top/Article/details/gt2rqqbvrbw.html

[Q50] 批量更新
来源：http://dali.mhx1999.top/Article/details/gt2qooznmtf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sweek.top/Article/details/gt2scxamtej.html

[Q51] 用子查询更新
来源：http://dali.zhiwuduotai.top/Article/details/gt2qwrwtwnb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cucudq.cn/Article/details/gt2nnmhmxgk.html

[Q52] 删除指定行
来源：http://dali.tian-w.cn/Article/details/gt2rxqesmni.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shzxlz.cn/Article/details/gt2qhipsahp.html

[Q53] 按条件删除
来源：http://dali.jinqigfzy.top/Article/details/gt2plbtpdsz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hongshengwenyu.top/Article/details/gt2fhhriqfe.html

[Q54] 清空表
来源：http://dali.hammf.cn/Article/details/gt2bduhyjsc.html

TRUNCATE TABLE logs;
来源：http://dali.hnxiangtu.top/Article/details/gt2eeqibhob.html

[Q55] 排名（并列占位）
来源：http://dali.cucudq.cn/Article/details/gt2lryqdoka.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2igywhuww.html

[Q56] 密集排名（并列不占位）
来源：http://dali.guowangkeji.top/Article/details/gt2txqtmnyf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hammf.cn/Article/details/gt2msmhgqri.html

[Q57] 行号
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eubbqrzo.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hammf.cn/Article/details/gt2isggtiej.html

[Q58] 累计求和
来源：http://dali.chenlongwang.top/Article/details/gt2dgbkipwu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.iojbl.cn/Article/details/gt2lyzvyagm.html

[Q59] 分组内累计
来源：http://dali.hysaishi.cn/Article/details/gt2briihnts.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jianghu66.top/Article/details/gt2aoomylzk.html

[Q60] 取上一行 / 下一行
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2klocpnsv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.9152youxi.cn/Article/details/gt2tixfttbq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.tian-w.cn/Article/details/gt2dagirwqb.html

[Q61] 移动平均
来源：http://dali.daxiang520.top/Article/details/gt2thilzpvo.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gt2bmnwyarq.html

[Q62] 分组占比
来源：http://dali.svipenyu.cn/Article/details/gt2mjugztxr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yvedp.cn/Article/details/gt2xfpkmtos.html

[Q63] 开启事务
来源：http://dali.zycfv.cn/Article/details/gt2ogmjinmw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ehwqpu.com/Article/details/gt2yplpdcwx.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cduwelrf.html

COMMIT;
来源：http://dali.ppjwa.cn/Article/details/gt2hyjcibfn.html

[Q65] 回滚事务
来源：http://dali.jinghuilouyu.cn/Article/details/gt2chcifblh.html

ROLLBACK;
来源：http://dali.chenlongwang.top/Article/details/gt2olnnkmwg.html

[Q66] 行锁查询
来源：http://dali.andypj.xyz/Article/details/gt2djtbmziw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.nanxinkj.top/Article/details/gt2fssikscx.html

[Q67] 设置隔离级别
来源：http://dali.jqgufenzy.top/Article/details/gt2qtprjykx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jianghu66.top/Article/details/gt2koibjbmo.html

[Q68] 保存点
来源：http://dali.tanke756.top/Article/details/gt2toupymmp.html

SAVEPOINT sp1;
来源：http://dali.ehwqpu.com/Article/details/gt2hqsvtvzv.html

ROLLBACK TO sp1;
来源：http://dali.316326.xyz/Article/details/gt2uenetrqa.html

[Q69] 查看执行计划
来源：http://dali.chenlongwang.top/Article/details/gt2klhoqtqm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.bjfxy.top/Article/details/gt2blhkiveo.html

[Q70] 更新统计信息
来源：http://dali.shzxlz.cn/Article/details/gt2hanxpdwu.html

ANALYZE TABLE users;
来源：http://dali.cqqwz.cn/Article/details/gt2jfbqhmsp.html

[Q71] 查看建表语句
来源：http://dali.0kj1m.cn/Article/details/gt2zwzyfpjb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zdqjudy.top/Article/details/gt2xnfmymel.html

[Q72] 查看索引
来源：http://dali.cdnleiting.top/Article/details/gt2qqbaoffc.html

SHOW INDEX FROM users;
来源：http://dali.ivvv.top/Article/details/gt2ecuvgqnl.html

[Q73] 查看表状态
来源：http://dali.tanke756.top/Article/details/gt2ihuatqks.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yj202588.top/Article/details/gt2dqcexsoc.html

[Q74] 强制使用索引
来源：http://dali.gogol.net.cn/Article/details/gt2tdtenmau.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.dashuyun.cn/Article/details/gt2iuxsyeqh.html

[Q75] 日期格式化
来源：http://dali.tian-w.cn/Article/details/gt2yucomyiq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gt2hgmrwfmr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hongshengwenyu.top/Article/details/gt2muhzswvf.html

[Q76] 按天统计
来源：http://dali.meibo888.top/Article/details/gt2tgioltms.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhoulong.xyz/Article/details/gt2gnmumnki.html

[Q77] 时间加减
来源：http://dali.meibo888.top/Article/details/gt2rkruqxna.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jqgufenzy.top/Article/details/gt2zmuyojri.html

[Q78] 当前时间
来源：http://dali.shangyingyoupin.top/Article/details/gt2nvmnkwnb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinqigfzy.top/Article/details/gt2kxmmtqvr.html

[Q79] 字符串拼接
来源：http://dali.ehwqpu.com/Article/details/gt2xnoiwwca.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ivvv.top/Article/details/gt2ktudjvgh.html

[Q80] 字符串截取
来源：http://dali.xuanzx.com/Article/details/gt2navtjkoh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2qsuipsdc.html

[Q81] 字符串替换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vllbopba.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2wzdlqaxb.html

[Q82] 字符长度与字节长度
来源：http://dali.sweek.top/Article/details/gt2bggjqduu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hammf.cn/Article/details/gt2zfwimrud.html

[Q83] 大小写转换
来源：http://dali.yueranfly.top/Article/details/gt2gppxwtpd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yj202588.top/Article/details/gt2zxogonqs.html

[Q84] 去除首尾空格
来源：http://dali.haohaochexian.top/Article/details/gt2utnthifq.html

SELECT TRIM(name) FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2fashbefy.html

[Q85] 数值取整
来源：http://dali.hfpthk.cn/Article/details/gt2ckuoxyno.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xuetiantiany.cn/Article/details/gt2oiiwbpak.html

[Q86] 读取 JSON 字段
来源：http://dali.fengsongda.top/Article/details/gt2dajnuwod.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ydzc1.top/Article/details/gt2ubcwqilr.html

[Q87] JSON 字段做条件
来源：http://dali.svipenyu.cn/Article/details/gt2ksolldyh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gaohongyu789.top/Article/details/gt2tephfxgy.html

[Q88] 行转列（条件聚合）
来源：http://dali.aibaodan.cn/Article/details/gt2mwagnkxm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.aizwys.cn/Article/details/gt2bjqzhvcm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2ymkncgfw.html

[Q89] 判断表是否存在
来源：http://dali.zycfv.cn/Article/details/gt2lowsjbmf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cqqwz.cn/Article/details/gt2gmornesu.html

[Q90] 生成序号列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tttegkhr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cheryme.top/Article/details/gt2zixizwno.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2yezlseok.html

R. Bash 专题
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cgokybly.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2mwlzinrk.html

[R01] shebang 与严格模式
来源：http://dali.shangyingyoupin.top/Article/details/gt2umrauoph.html

#!/usr/bin/env bash
来源：http://dali.yj20258.top/Article/details/gt2tiuhnimp.html

set -euo pipefail
来源：http://dali.zhongyouzk.top/Article/details/gt2pdbanszj.html

[R02] 变量赋值与使用
来源：http://dali.gzhubu.top/Article/details/gt2kqowmuri.html

name="Tom"; echo "$name"
来源：http://dali.hysaishi.cn/Article/details/gt2ckyuthuh.html

[R03] 只读变量
来源：http://dali.cdnleiting.top/Article/details/gt2jlubpkhm.html

readonly PI=3.14
来源：http://dali.sxryk.cn/Article/details/gt2mzsckxxv.html

[R04] 位置参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nucocngn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.quarkkingdee.top/Article/details/gt2ubzvqnmn.html

[R05] 参数默认值
来源：http://dali.fzhhl.top/Article/details/gt2loxchtzh.html

name="${1:-default}"
来源：http://dali.fengsongda.top/Article/details/gt2nkvnvbsc.html

[R06] 判断命令是否存在
来源：http://dali.meibo888.top/Article/details/gt2wvvwzlrz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hnqzz.top/Article/details/gt2rrhiwbjy.html

[R07] if 判断文件
来源：http://dali.hammf.cn/Article/details/gt2rijtzmll.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sweek.top/Article/details/gt2gntnjenw.html

[R08] 数值比较
来源：http://dali.daria6918.cn/Article/details/gt2rgqnjaby.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qtljmtwy.html

[R09] 字符串比较
来源：http://dali.nanxinkj.top/Article/details/gt2dldfphca.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.quarkkingdee.top/Article/details/gt2nnqjtxbn.html

[R10] 正则匹配
来源：http://dali.meibo888.top/Article/details/gt2wvnppbfb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.guannengcc.top/Article/details/gt2scpjmqua.html

[R11] case 多分支
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wlalwstg.html

case "$1" in
来源：http://dali.tanke756.top/Article/details/gt2temjwnga.html

start) echo "启动" ;;
来源：http://dali.cheryme.top/Article/details/gt2dssugeez.html

stop)  echo "停止" ;;
来源：http://dali.havefunace.top/Article/details/gt2xmclvqpq.html

*)     echo "未知命令" ;;
来源：http://dali.mhx1999.top/Article/details/gt2clxfvcbg.html

esac
来源：http://dali.zhoulong.xyz/Article/details/gt2ldmidyaq.html

[R12] for 遍历文件
来源：http://dali.yonumen.top/Article/details/gt2dmxmppnm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.birdmap.top/Article/details/gt2kxkwowbs.html

[R13] for 计数循环
来源：http://dali.wangshuangyany.cn/Article/details/gt2jnvpyzsm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.guannengcc.top/Article/details/gt2fdvoiplj.html

[R14] C 风格 for
来源：http://dali.sxryk.cn/Article/details/gt2lmnoppjx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hywenlv.cn/Article/details/gt2wwydivxy.html

[R15] while 逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gt2fbnhdhrb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cashguo.top/Article/details/gt2nqmhbmyx.html

[R16] until 等待条件
来源：http://dali.pycfn.com/Article/details/gt2qepgamiu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hnxiangtu.top/Article/details/gt2dukdpfsx.html

[R17] 数组定义与取值
来源：http://dali.yuanzhike.top/Article/details/gt2jqpceugo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.fzhhl.top/Article/details/gt2xwrocqyi.html

[R18] 遍历数组
来源：http://dali.bjfxy.top/Article/details/gt2ygsqpocw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xuanzx.com/Article/details/gt2nrhirlms.html

[R19] 数组长度
来源：http://dali.nanxuanxn.top/Article/details/gt2gfhbxpck.html

echo "${#arr[@]}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jnqsunuu.html

[R20] 关联数组（字典）
来源：http://dali.svipenyu.cn/Article/details/gt2jbwiighz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.nanxinkj.top/Article/details/gt2ymjlwqeg.html

[R21] 字符串长度
来源：http://dali.ydzc1.top/Article/details/gt2rtqusels.html

echo "${#s}"
来源：http://dali.shangyingyoupin.top/Article/details/gt2thgvbifh.html

[R22] 截取子串
来源：http://dali.kuanghao11.cn/Article/details/gt2nzckvnwu.html

echo "${s:0:5}"
来源：http://dali.9152youxi.cn/Article/details/gt2ttteuhxw.html

[R23] 字符串替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bmndjghr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cdnleiting.top/Article/details/gt2rjywozkc.html

[R24] 大小写转换
来源：http://dali.hnqzz.top/Article/details/gt2tngbfsla.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sxryk.cn/Article/details/gt2cftyhofb.html

[R25] 去后缀 / 去前缀
来源：http://dali.nanxinkj.top/Article/details/gt2hbkecbhh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yzjedjhb.html

[R26] 命令替换
来源：http://dali.hnxiangtu.top/Article/details/gt2exnsvfcs.html

now=$(date +%F); echo "$now"
来源：http://dali.chenzaomai.com/Article/details/gt2zpvoyrhs.html

[R27] 算术展开
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kpgjklpk.html

echo $((1 + 2 * 3))
来源：http://dali.xuanzx.com/Article/details/gt2dqyixpsp.html

[R28] 浮点运算
来源：http://dali.chenlongwang.top/Article/details/gt2onjtbcll.html

echo "scale=2; 10/3" | bc
来源：http://dali.xinyue.icu/Article/details/gt2dkktpovg.html

[R29] 定义函数
来源：http://dali.cqqwz.cn/Article/details/gt2wfuxlrcx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gogol.net.cn/Article/details/gt2lislmjbx.html

[R30] 函数返回状态码
来源：http://dali.chenlongwang.top/Article/details/gt2zlqmeqmk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.9152youxi.cn/Article/details/gt2jukzjmtw.html

[R31] 局部变量
来源：http://dali.zhengqikj.top/Article/details/gt2yawlbnli.html

f() { local x=1; echo "$x"; }
来源：http://dali.chenlongwang.top/Article/details/gt2gwzgpxhi.html

[R32] 参数个数校验
来源：http://dali.xuanzx.com/Article/details/gt2hqeyikpo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gwjctgwv.html

[R33] 捕获错误并提示行号
来源：http://dali.yj202588.top/Article/details/gt2rbzamndy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sysykeji.top/Article/details/gt2nhgatdrj.html

[R34] 退出时清理
来源：http://dali.gzhubu.top/Article/details/gt2dlwmcmhc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zdqjudy.top/Article/details/gt2mvipszsm.html

[R35] 后台执行并等待
来源：http://dali.ppjwa.cn/Article/details/gt2vnungahi.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yongpay.top/Article/details/gt2mtoawihk.html

[R36] 并发执行多个任务
来源：http://dali.xuetiantiany.cn/Article/details/gt2wuaixpfi.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shuidangran.top/Article/details/gt2xbtbghcj.html

[R37] 把输出赋给变量
来源：http://dali.chenlongwang.top/Article/details/gt2alhaoklj.html

files=$(ls -1)
来源：http://dali.jinqigfzy.top/Article/details/gt2wghitpmx.html

[R38] 管道串联
来源：http://dali.zhoulong.xyz/Article/details/gt2emcpvshl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhixingplan.top/Article/details/gt2qlhljwke.html

[R39] 重定向标准输出与错误
来源：http://dali.chenzaomai.com/Article/details/gt2uaaixzrw.html

cmd > out.log 2>&1
来源：http://dali.daria6918.cn/Article/details/gt2nkhundod.html

[R40] 追加写日志
来源：http://dali.mhx1999.top/Article/details/gt2gvtzpcyu.html

echo "log" >> out.log
来源：http://dali.wangshuangyany.cn/Article/details/gt2dxtscxrd.html

[R41] 丢弃输出
来源：http://dali.yongpay.top/Article/details/gt2rzdxuyym.html

cmd >/dev/null 2>&1
来源：http://dali.daxiang520.top/Article/details/gt2cwtpazji.html

[R42] 输入重定向
来源：http://dali.c1oappe.top/Article/details/gt2bxqhszut.html

wc -l < a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gt2wyivcuxe.html

[R43] 按名字查找文件
来源：http://dali.aizwys.cn/Article/details/gt2fubiatle.html

find . -name "*.log" -type f
来源：http://dali.ybcxt.top/Article/details/gt2uwtbgauq.html

[R44] 按修改时间查找
来源：http://dali.meibo888.top/Article/details/gt2cmppnqkq.html

find . -mtime -7 -type f
来源：http://dali.mhx1999.top/Article/details/gt2jweodkqe.html

[R45] 批量删除
来源：http://dali.fengsongda.top/Article/details/gt2mnylxaos.html

find . -name "*.tmp" -delete
来源：http://dali.zhiwuduotai.top/Article/details/gt2usclnazo.html

[R46] 递归替换文件内容
来源：http://dali.sysykeji.top/Article/details/gt2easervzd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.fzhhl.top/Article/details/gt2klgwkrce.html

[R47] sed 单行替换
来源：http://dali.ybcxt.top/Article/details/gt2fyazopcp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cucudq.cn/Article/details/gt2dukitkro.html

[R48] awk 取指定列
来源：http://dali.hnqzz.top/Article/details/gt2ydojnzgh.html

awk '{print $1, $3}' a.txt
来源：http://dali.shzxlz.cn/Article/details/gt2ndftidqd.html

[R49] awk 带条件
来源：http://dali.xylfe.cn/Article/details/gt2txbhthnk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.aibaodan.cn/Article/details/gt2hcpufsqu.html

[R50] awk 求和
来源：http://dali.jiagoushi.top/Article/details/gt2iawxpuxh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jrcsyqcq.html

[R51] 排序去重取前几
来源：http://dali.zdqjudy.top/Article/details/gt2wppoyibj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hongshengwenyu.top/Article/details/gt2aqrclsyj.html

[R52] 统计行数
来源：http://dali.zhixingplan.top/Article/details/gt2zspnjesr.html

wc -l a.txt
来源：http://dali.zhongyouzk.top/Article/details/gt2jtipuukw.html

[R53] 查看文件头与实时尾
来源：http://dali.9152youxi.cn/Article/details/gt2vfehhonz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xyfzivvw.html

[R54] 比较两个文件
来源：http://dali.jinqigufen.top/Article/details/gt2zlmbpcdr.html

diff a.txt b.txt
来源：http://dali.zdqjudy.top/Article/details/gt2mhsfhnju.html

[R55] 压缩与解压
来源：http://dali.hammf.cn/Article/details/gt2jorjkoce.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yongpay.top/Article/details/gt2hjpzcxpl.html

[R56] 远程拷贝
来源：http://dali.zhixingplan.top/Article/details/gt2trelhmxy.html

scp file user@host:/path/
来源：http://dali.gaohongyu789.top/Article/details/gt2imwukrpr.html

[R57] 远程执行命令
来源：http://dali.chenlongwang.top/Article/details/gt2ylaftgsq.html

ssh user@host 'uptime'
来源：http://dali.ivvv.top/Article/details/gt2smpdzxch.html

[R58] 下载文件
来源：http://dali.yj20258.top/Article/details/gt2cbgdwaru.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.fzhhl.top/Article/details/gt2dyzwlnax.html

[R59] 发 POST JSON
来源：http://dali.zhengqikj.top/Article/details/gt2vllmqgsd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hongshengwenyu.top/Article/details/gt2njqgvvxc.html

[R60] 只看 HTTP 状态码
来源：http://dali.svipenyu.cn/Article/details/gt2geayywct.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhoulong.xyz/Article/details/gt2yyogrpzy.html

[R61] 磁盘占用
来源：http://dali.yj202588.top/Article/details/gt2eskitste.html

df -h;  du -sh *
来源：http://dali.chenzaomai.com/Article/details/gt2smcvwvka.html

[R62] 找最占空间的文件
来源：http://dali.hnxiangtu.top/Article/details/gt2ujxclbfe.html

du -ah . | sort -rh | head -10
来源：http://dali.c1oappe.top/Article/details/gt2eqjzfbxj.html

[R63] 内存与进程
来源：http://dali.dianchejie.cn/Article/details/gt2rjcebaka.html


<!-- 参考信息 -->