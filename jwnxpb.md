代发 wailian999

[Q14] 存在则更新（upsert）
来源：http://dali.316326.xyz/Article/details/gtbillycxr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yonumen.top/Article/details/gtdzchjfgo.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.havefunace.top/Article/details/gtjwjscimi.html

[Q15] 查询全部
来源：http://dali.yj202588.top/Article/details/gtbskbikvx.html

SELECT * FROM users;
来源：http://dali.yuxming.cn/Article/details/gtarjwuuvd.html

[Q16] 查询指定列
来源：http://dali.sweek.top/Article/details/gtubhrjtbu.html

SELECT id, name FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtwtkyuysv.html

[Q17] 条件查询
来源：http://dali.mhx1999.top/Article/details/gtumopjtrc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jqgfzy.top/Article/details/gtrczzysjl.html

[Q18] 模糊匹配
来源：http://dali.0kj1m.cn/Article/details/gtpyylxotr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.wangdashe.top/Article/details/gtvwxxsinb.html

[Q19] 范围查询
来源：http://dali.mhx1999.top/Article/details/gtmiszpzur.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.nanxinkj.top/Article/details/gtypfvnvik.html

[Q20] IN 列表
来源：http://dali.zhengqikj.top/Article/details/gtmigufshl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hammf.cn/Article/details/gtehwrewco.html

[Q21] 空值判断
来源：http://dali.guowangkeji.top/Article/details/gtbztlypfo.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.aizwys.cn/Article/details/gtbnopbxbn.html

[Q22] 排序
来源：http://dali.jinqigfzy.top/Article/details/gtsfeswuhw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yangfankeji.com/Article/details/gthqkivwcl.html

[Q23] 分页
来源：http://dali.xylfe.cn/Article/details/gtblqubplm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrzzambki.html

[Q24] 去重
来源：http://dali.tanke756.top/Article/details/gteupaliul.html

SELECT DISTINCT city FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtjwsvkgwj.html

[Q25] 只取前 N 条
来源：http://dali.tianlin.xyz/Article/details/gttzuizbvd.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.daxiang520.top/Article/details/gtcgczblsc.html

[Q26] 计数
来源：http://dali.zhongyouzk.top/Article/details/gtxrzibezp.html

SELECT COUNT(*) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtvcwejmjr.html

[Q27] 条件计数
来源：http://dali.mhx1999.top/Article/details/gttyrqvwkl.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.redwolf501.top/Article/details/gtwcbgnmdq.html

[Q28] 求和与平均
来源：http://dali.dianchejie.cn/Article/details/gtwpwqodfe.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gticevndov.html

[Q29] 最大最小值
来源：http://dali.gaohongyu789.top/Article/details/gtzxswkuvq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtiutpywup.html

[Q30] 分组统计
来源：http://dali.hnqzz.top/Article/details/gtvgmwgfdd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sysykeji.top/Article/details/gtljzznauj.html

[Q31] 分组后过滤
来源：http://dali.xinyue.icu/Article/details/gtbjpobbtp.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jiagoushi.top/Article/details/gtarqydvdl.html

[Q32] 分组拼接字符串
来源：http://dali.fzhhl.top/Article/details/gtvhfnnwlf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cucudq.cn/Article/details/gtudstvmld.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.aibaodan.cn/Article/details/gtvumrhtkh.html

[Q33] 多列分组
来源：http://dali.tianlin.xyz/Article/details/gtkvuhuynx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ydzc1.top/Article/details/gtkjqfmyih.html

[Q34] 每组取第一条
来源：http://dali.jlsjyb.cn/Article/details/gtdpzjyptu.html

SELECT * FROM (
来源：http://dali.kuanghao11.cn/Article/details/gtonxqdtrp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.daria6918.cn/Article/details/gtfiyanssa.html

) t WHERE rn = 1;
来源：http://dali.mhx1999.top/Article/details/gtcnmypwrz.html

[Q35] 内连接
来源：http://dali.gzhubu.top/Article/details/gtdhtiujzu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinqigufen.top/Article/details/gtfnopgiwu.html

[Q36] 左连接
来源：http://dali.shuidangran.top/Article/details/gtltphxcuy.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.tianlin.xyz/Article/details/gtnxrddmox.html

[Q37] 右连接
来源：http://dali.zhongyouzk.top/Article/details/gthezxxnzj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ydzc1.top/Article/details/gtxnosqxlg.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.chenjidiqi.icu/Article/details/gthehiumwu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.dianchejie.cn/Article/details/gtcnbgcdjq.html

[Q39] 自连接（查上下级）
来源：http://dali.zhengqikj.top/Article/details/gtpmxssqhw.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkiqvmpdn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jinqigufen.top/Article/details/gtifhmbiog.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yonumen.top/Article/details/gtdqqonchl.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.nanxinkj.top/Article/details/gtsshgkfue.html

[Q41] 多表连接
来源：http://dali.cashguo.top/Article/details/gtursumzna.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.feifeiyinyue.top/Article/details/gtxvcszyxv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shuidangran.top/Article/details/gtwdknkpvu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.tianlin.xyz/Article/details/gtktwzewel.html

[Q42] 连接条件附加过滤
来源：http://dali.pycfn.com/Article/details/gtkpypisbn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhaomingkeji.xyz/Article/details/gtohojbimp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.aizwys.cn/Article/details/gtaflqsbub.html

[Q43] 标量子查询
来源：http://dali.c1oappe.top/Article/details/gtznulsxlf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jqgufenzy.top/Article/details/gtywafeqci.html

[Q44] IN 子查询
来源：http://dali.yanxiufei.cn/Article/details/gtyuajefyw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.snrcjt.cn/Article/details/gtwtkclube.html

[Q45] EXISTS 判断存在
来源：http://dali.gzhubu.top/Article/details/gtbfzvfimi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.316326.xyz/Article/details/gtmysfdxso.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hnqzz.top/Article/details/gtiyvovbbo.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.9152youxi.cn/Article/details/gtlpzefpla.html

[Q47] 与平均值比较
来源：http://dali.iojbl.cn/Article/details/gtldyduajq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.iojbl.cn/Article/details/gtgvhviyzt.html

[Q48] CTE 公用表表达式
来源：http://dali.redwolf501.top/Article/details/gtjecjejre.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yuanzhike.top/Article/details/gtsoalwkfj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.vqdsnc.cn/Article/details/gtckvvbsfp.html

[Q49] 更新单行
来源：http://dali.birdmap.top/Article/details/gtjskxiemo.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.c1oappe.top/Article/details/gtgmjzulvv.html

[Q50] 批量更新
来源：http://dali.jyoumei.cn/Article/details/gtnawmoeiu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sxryk.cn/Article/details/gtgrhpyijp.html

[Q51] 用子查询更新
来源：http://dali.dashuyun.cn/Article/details/gtapefvhcb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sxryk.cn/Article/details/gtizubjjsg.html

[Q52] 删除指定行
来源：http://dali.shuidangran.top/Article/details/gtnulvvsvg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jlsjyb.cn/Article/details/gtstrmppao.html

[Q53] 按条件删除
来源：http://dali.gogol.net.cn/Article/details/gtpmlpgvpt.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ivvv.top/Article/details/gttukvihvp.html

[Q54] 清空表
来源：http://dali.yueranfly.top/Article/details/gtjuxsxzcl.html

TRUNCATE TABLE logs;
来源：http://dali.mhx1999.top/Article/details/gtkfbjrrll.html

[Q55] 排名（并列占位）
来源：http://dali.shangyingyoupin.top/Article/details/gtvzzokkrb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwudnsmcy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.andypj.xyz/Article/details/gtiehaqcms.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yuxming.cn/Article/details/gthrupnxxz.html

[Q57] 行号
来源：http://dali.aizwys.cn/Article/details/gtnonzgmfz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtdxiawyfi.html

[Q58] 累计求和
来源：http://dali.jqgfzy.top/Article/details/gtiiryapas.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gtysjvenke.html

[Q59] 分组内累计
来源：http://dali.c1oappe.top/Article/details/gtvhnuohpr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtoaaavpbl.html

[Q60] 取上一行 / 下一行
来源：http://dali.jiagoushi.top/Article/details/gtzaravfda.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.316326.xyz/Article/details/gtgjyffvgd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.316326.xyz/Article/details/gtfrylpmts.html

[Q61] 移动平均
来源：http://dali.chenjidiqi.icu/Article/details/gthenhmxrc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cashguo.top/Article/details/gtpcyujdfv.html

[Q62] 分组占比
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwgavnesy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.daxiang520.top/Article/details/gtjzobmrwr.html

[Q63] 开启事务
来源：http://dali.hnxiangtu.top/Article/details/gtcxxzqgbk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.dianchejie.cn/Article/details/gtjhlvtqqc.html

[Q64] 提交事务
来源：http://dali.chenzaomai.com/Article/details/gtpbgnygdo.html

COMMIT;
来源：http://dali.chenlongwang.top/Article/details/gtenvzvhxq.html

[Q65] 回滚事务
来源：http://dali.zhengqikj.top/Article/details/gtuhkkpooh.html

ROLLBACK;
来源：http://dali.shzxlz.cn/Article/details/gticavnbni.html

[Q66] 行锁查询
来源：http://dali.vqdsnc.cn/Article/details/gtfgqwzcay.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhoulong.xyz/Article/details/gtxlicvjmi.html

[Q67] 设置隔离级别
来源：http://dali.ivvv.top/Article/details/gtodyecddd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yueranfly.top/Article/details/gterevnspx.html

[Q68] 保存点
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmzvmxjzk.html

SAVEPOINT sp1;
来源：http://dali.dashuyun.cn/Article/details/gtjhjlhucj.html

ROLLBACK TO sp1;
来源：http://dali.hnqzz.top/Article/details/gtnxfuoigz.html

[Q69] 查看执行计划
来源：http://dali.birdmap.top/Article/details/gtlekdbgoz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shangyingyoupin.top/Article/details/gtxklkkeer.html

[Q70] 更新统计信息
来源：http://dali.yangfankeji.com/Article/details/gtpvtqximm.html

ANALYZE TABLE users;
来源：http://dali.aibaodan.cn/Article/details/gtroyxxtds.html

[Q71] 查看建表语句
来源：http://dali.gzhubu.top/Article/details/gtmxtqcelf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenlongwang.top/Article/details/gtsbpzdbtj.html

[Q72] 查看索引
来源：http://dali.316326.xyz/Article/details/gtztjpvurg.html

SHOW INDEX FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtrppiyzyl.html

[Q73] 查看表状态
来源：http://dali.pengpengdd.cyou/Article/details/gtwcnyuwnr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shuidangran.top/Article/details/gtvnorieqb.html

[Q74] 强制使用索引
来源：http://dali.jinghuilouyu.cn/Article/details/gtyaykvrit.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ivvv.top/Article/details/gtxtbndgwt.html

[Q75] 日期格式化
来源：http://dali.sysykeji.top/Article/details/gtojlkmqol.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtfghmuwtg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jyoumei.cn/Article/details/gtpnadahdq.html

[Q76] 按天统计
来源：http://dali.kuanghao11.cn/Article/details/gtohmlmgho.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cheryme.top/Article/details/gtezdytmie.html

[Q77] 时间加减
来源：http://dali.hywenlv.cn/Article/details/gtddyidaqe.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.0kj1m.cn/Article/details/gthwsgixvu.html

[Q78] 当前时间
来源：http://dali.jiagoushi.top/Article/details/gtteszaxze.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hywenlv.cn/Article/details/gtxrdblfcz.html

[Q79] 字符串拼接
来源：http://dali.ehwqpu.com/Article/details/gtxaeypdqh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ybcxt.top/Article/details/gtmzieyhvp.html

[Q80] 字符串截取
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyakokusr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtgxtczqkr.html

[Q81] 字符串替换
来源：http://dali.daria6918.cn/Article/details/gthdbwipot.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.birdmap.top/Article/details/gtxbbenweq.html

[Q82] 字符长度与字节长度
来源：http://dali.shuidangran.top/Article/details/gtmpirrfgh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gttyhlszmi.html

[Q83] 大小写转换
来源：http://dali.jinqigfzy.top/Article/details/gtobsfbcmp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cheryme.top/Article/details/gtafwrfxbd.html

[Q84] 去除首尾空格
来源：http://dali.haohaochexian.top/Article/details/gthetmtycn.html

SELECT TRIM(name) FROM users;
来源：http://dali.zycfv.cn/Article/details/gtcmcxlwgq.html

[Q85] 数值取整
来源：http://dali.meibo888.top/Article/details/gtqzuxpitm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.tanke756.top/Article/details/gtbnykrdig.html

[Q86] 读取 JSON 字段
来源：http://dali.jiagoushi.top/Article/details/gtgjkdfmdq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.guowangkeji.top/Article/details/gtwurfrfcy.html

[Q87] JSON 字段做条件
来源：http://dali.zycfv.cn/Article/details/gtavpbgjqe.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zdqjudy.top/Article/details/gtycczmygd.html

[Q88] 行转列（条件聚合）
来源：http://dali.nwbrower.top/Article/details/gtfbrcjycb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.aibaodan.cn/Article/details/gtamvqeugp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtrlwjltwb.html

[Q89] 判断表是否存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzaamtubj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ivvv.top/Article/details/gtwcqonavf.html

[Q90] 生成序号列
来源：http://dali.xuetiantiany.cn/Article/details/gtzqbwitvk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.iojbl.cn/Article/details/gtiabvkjal.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtaislmzqv.html

R. Bash 专题
来源：http://dali.zhoulong.xyz/Article/details/gtnutvkuky.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtkuiwqxcj.html

[R01] shebang 与严格模式
来源：http://dali.daria6918.cn/Article/details/gtkxdiuptw.html

#!/usr/bin/env bash
来源：http://dali.quarkkingdee.top/Article/details/gtpnquaxpv.html

set -euo pipefail
来源：http://dali.xuetiantiany.cn/Article/details/gtanpszais.html

[R02] 变量赋值与使用
来源：http://dali.sxryk.cn/Article/details/gtspuiayim.html

name="Tom"; echo "$name"
来源：http://dali.jianghu66.top/Article/details/gtxltmpest.html

[R03] 只读变量
来源：http://dali.tanke756.top/Article/details/gtmbpymzlu.html

readonly PI=3.14
来源：http://dali.guowangkeji.top/Article/details/gtlxtblpdt.html

[R04] 位置参数
来源：http://dali.gaohongyu789.top/Article/details/gtpdjoobys.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cdnleiting.top/Article/details/gtmgfnejdv.html

[R05] 参数默认值
来源：http://dali.hongshengwenyu.top/Article/details/gtuumbeuga.html

name="${1:-default}"
来源：http://dali.cheryme.top/Article/details/gtbpwflqtz.html

[R06] 判断命令是否存在
来源：http://dali.redwolf501.top/Article/details/gtnhnzveuq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.haohaochexian.top/Article/details/gtwjxamkfj.html

[R07] if 判断文件
来源：http://dali.mhx1999.top/Article/details/gtadgjscij.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xylfe.cn/Article/details/gtxpldkdrn.html

[R08] 数值比较
来源：http://dali.316326.xyz/Article/details/gtkjtctvyz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jinghuilouyu.cn/Article/details/gtuqtcajcm.html

[R09] 字符串比较
来源：http://dali.tianlin.xyz/Article/details/gttjcmrazk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.andypj.xyz/Article/details/gtqgrtrlgo.html

[R10] 正则匹配
来源：http://dali.c1oappe.top/Article/details/gtzhtdumdd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cashguo.top/Article/details/gtozururhq.html

[R11] case 多分支
来源：http://dali.haohaochexian.top/Article/details/gtwksiixic.html

case "$1" in
来源：http://dali.aibaodan.cn/Article/details/gtzdsxwlgh.html

start) echo "启动" ;;
来源：http://dali.316326.xyz/Article/details/gtwurhsqkf.html

stop)  echo "停止" ;;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxofzcifx.html

*)     echo "未知命令" ;;
来源：http://dali.zhixingplan.top/Article/details/gtwbcznugn.html

esac
来源：http://dali.chenzaomai.com/Article/details/gtqziuqjzc.html

[R12] for 遍历文件
来源：http://dali.cashguo.top/Article/details/gtjtucsqvl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.daxiang520.top/Article/details/gtbojtucna.html

[R13] for 计数循环
来源：http://dali.jinqigufen.top/Article/details/gtqjpumclo.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cucudq.cn/Article/details/gtaxjzgvdy.html

[R14] C 风格 for
来源：http://dali.shzxlz.cn/Article/details/gtowpwyiew.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gtwthlpcmw.html

[R15] while 逐行读文件
来源：http://dali.shuidangran.top/Article/details/gtcmaxesns.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.tianlin.xyz/Article/details/gthphugbdh.html

[R16] until 等待条件
来源：http://dali.gogol.net.cn/Article/details/gtnyfiduwh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.tanke756.top/Article/details/gtmqjkphdn.html

[R17] 数组定义与取值
来源：http://dali.xuanzx.com/Article/details/gthnmxeeng.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.meibo888.top/Article/details/gtguwoukqo.html

[R18] 遍历数组
来源：http://dali.cheryme.top/Article/details/gtmclhkcgu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cashguo.top/Article/details/gtbmtfviaj.html

[R19] 数组长度
来源：http://dali.zhongyouzk.top/Article/details/gtosrunipp.html

echo "${#arr[@]}"
来源：http://dali.daxiang520.top/Article/details/gtuqhiqvmq.html

[R20] 关联数组（字典）
来源：http://dali.redwolf501.top/Article/details/gtwijsanet.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.daxiang520.top/Article/details/gtmawbitdo.html

[R21] 字符串长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtsojpiceg.html

echo "${#s}"
来源：http://dali.sysykeji.top/Article/details/gtumyhrkgu.html

[R22] 截取子串
来源：http://dali.dianchejie.cn/Article/details/gtwlcmgodr.html

echo "${s:0:5}"
来源：http://dali.daxiang520.top/Article/details/gtbdwxlrgu.html

[R23] 字符串替换
来源：http://dali.yj20258.top/Article/details/gtvnwdbrpt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yuxming.cn/Article/details/gtpdkxxpcq.html

[R24] 大小写转换
来源：http://dali.shzxlz.cn/Article/details/gtmrmctpsg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.snrcjt.cn/Article/details/gtcudvrhsw.html

[R25] 去后缀 / 去前缀
来源：http://dali.quarkkingdee.top/Article/details/gtqoqlssxm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzcosalli.html

[R26] 命令替换
来源：http://dali.nanxuanxn.top/Article/details/gtesiexujt.html

now=$(date +%F); echo "$now"
来源：http://dali.daria6918.cn/Article/details/gtlhnhbxhj.html

[R27] 算术展开
来源：http://dali.zhoulong.xyz/Article/details/gttpdwhjhz.html

echo $((1 + 2 * 3))
来源：http://dali.kuanghao11.cn/Article/details/gtibyahigi.html

[R28] 浮点运算
来源：http://dali.quarkkingdee.top/Article/details/gtofuadjvi.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhixingplan.top/Article/details/gtzkcbgbbo.html

[R29] 定义函数
来源：http://dali.zhoulong.xyz/Article/details/gttugnueyx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jianghu66.top/Article/details/gtzbjnsswv.html

[R30] 函数返回状态码
来源：http://dali.andypj.xyz/Article/details/gthdieqgje.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yanxiufei.cn/Article/details/gtvwvcydim.html

[R31] 局部变量
来源：http://dali.pycfn.com/Article/details/gtfcpzalgq.html

f() { local x=1; echo "$x"; }
来源：http://dali.sysykeji.top/Article/details/gtdffwqbnj.html

[R32] 参数个数校验
来源：http://dali.hfpthk.cn/Article/details/gtiamoggnn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.aibaodan.cn/Article/details/gtusscnwnf.html

[R33] 捕获错误并提示行号
来源：http://dali.dianchejie.cn/Article/details/gtkywdcygv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.iojbl.cn/Article/details/gtbvdweezi.html

[R34] 退出时清理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbddamnnv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuetiantiany.cn/Article/details/gttzlghhtr.html

[R35] 后台执行并等待
来源：http://dali.pycfn.com/Article/details/gtvzohrbrs.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gzhubu.top/Article/details/gtulrvuyza.html

[R36] 并发执行多个任务
来源：http://dali.wangshuangyany.cn/Article/details/gtgrdlwgob.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.aizwys.cn/Article/details/gtzbsxntdx.html

[R37] 把输出赋给变量
来源：http://dali.aibaodan.cn/Article/details/gtdotzbfyi.html

files=$(ls -1)
来源：http://dali.cheryme.top/Article/details/gtsjvjkxch.html

[R38] 管道串联
来源：http://dali.snrcjt.cn/Article/details/gtbhenmocq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cdnleiting.top/Article/details/gtlfyrnsbw.html

[R39] 重定向标准输出与错误
来源：http://dali.sxryk.cn/Article/details/gtomrhyrzg.html

cmd > out.log 2>&1
来源：http://dali.yj202588.top/Article/details/gtrbmhrjfk.html

[R40] 追加写日志
来源：http://dali.cashguo.top/Article/details/gtailccjzi.html

echo "log" >> out.log
来源：http://dali.gzhubu.top/Article/details/gtpvcuytoo.html

[R41] 丢弃输出
来源：http://dali.snrcjt.cn/Article/details/gtnnqceesb.html

cmd >/dev/null 2>&1
来源：http://dali.zdqjudy.top/Article/details/gtjibtimnd.html

[R42] 输入重定向
来源：http://dali.guowangkeji.top/Article/details/gtjzmsypyd.html

wc -l < a.txt
来源：http://dali.jinqigufen.top/Article/details/gtsmnpesye.html

[R43] 按名字查找文件
来源：http://dali.shuidangran.top/Article/details/gtpafvuqpm.html

find . -name "*.log" -type f
来源：http://dali.fzhhl.top/Article/details/gtzvxvgvnk.html

[R44] 按修改时间查找
来源：http://dali.nanxuanxn.top/Article/details/gtoowrfmfa.html

find . -mtime -7 -type f
来源：http://dali.shzxlz.cn/Article/details/gtoeojnewz.html

[R45] 批量删除
来源：http://dali.zhiwuduotai.top/Article/details/gtytvanuul.html

find . -name "*.tmp" -delete
来源：http://dali.tianlin.xyz/Article/details/gttlvytcku.html

[R46] 递归替换文件内容
来源：http://dali.daxiang520.top/Article/details/gtdfheplgb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xylfe.cn/Article/details/gtylwckbkt.html

[R47] sed 单行替换
来源：http://dali.daxiang520.top/Article/details/gtpvqpuzgc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.guannengcc.top/Article/details/gttumwqxkq.html

[R48] awk 取指定列
来源：http://dali.zhongyouzk.top/Article/details/gtlflwbheh.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtjexdripi.html

[R49] awk 带条件
来源：http://dali.ybcxt.top/Article/details/gtasksiglp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.pycfn.com/Article/details/gtucgbxugw.html

[R50] awk 求和
来源：http://dali.dianchejie.cn/Article/details/gttpqyroip.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhongyouzk.top/Article/details/gtfxkoicyl.html

[R51] 排序去重取前几
来源：http://dali.sxryk.cn/Article/details/gtarjehqmh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yanxiufei.cn/Article/details/gteekcuvhj.html

[R52] 统计行数
来源：http://dali.daria6918.cn/Article/details/gtnbhtdnja.html

wc -l a.txt
来源：http://dali.aibaodan.cn/Article/details/gtylzenxfb.html

[R53] 查看文件头与实时尾
来源：http://dali.shanyushiyangtech.top/Article/details/gtjzzltham.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gogol.net.cn/Article/details/gtvmsjlwqx.html

[R54] 比较两个文件
来源：http://dali.snrcjt.cn/Article/details/gtdxpmnmvc.html

diff a.txt b.txt
来源：http://dali.bjfxy.top/Article/details/gtsddowlkc.html

[R55] 压缩与解压
来源：http://dali.0kj1m.cn/Article/details/gtfixifwry.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhoulong.xyz/Article/details/gtnapdwwcy.html

[R56] 远程拷贝
来源：http://dali.jianghu66.top/Article/details/gtttdjfgvi.html

scp file user@host:/path/
来源：http://dali.aizwys.cn/Article/details/gtzretgsmi.html

[R57] 远程执行命令
来源：http://dali.quarkkingdee.top/Article/details/gtcafsexmq.html

ssh user@host 'uptime'
来源：http://dali.daria6918.cn/Article/details/gtywikpsth.html

[R58] 下载文件
来源：http://dali.daria6918.cn/Article/details/gthpgdsvjr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.andypj.xyz/Article/details/gtjrnqfabc.html

[R59] 发 POST JSON
来源：http://dali.dashuyun.cn/Article/details/gtlbswqnkh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.wangshuangyany.cn/Article/details/gttaaujgak.html

[R60] 只看 HTTP 状态码
来源：http://dali.shuidangran.top/Article/details/gtghveqbxo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.svipenyu.cn/Article/details/gtqwlvdgdu.html

[R61] 磁盘占用
来源：http://dali.bjfxy.top/Article/details/gtunicksle.html

df -h;  du -sh *
来源：http://dali.xuanzx.com/Article/details/gtsbqwdzke.html

[R62] 找最占空间的文件
来源：http://dali.hnqzz.top/Article/details/gtdpfhhqoq.html

du -ah . | sort -rh | head -10
来源：http://dali.dashuyun.cn/Article/details/gttucfntxa.html

[R63] 内存与进程
来源：http://dali.daxiang520.top/Article/details/gtqegojxhk.html


<!-- 参考信息 -->