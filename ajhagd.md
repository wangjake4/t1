代发 wailian999

[Q14] 存在则更新（upsert）
来源：http://dali.birdmap.top/Article/details/gtsbclubog.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xuetiantiany.cn/Article/details/gtqezbtdhr.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.nwbrower.top/Article/details/gtdtkmpfge.html

[Q15] 查询全部
来源：http://dali.tianlin.xyz/Article/details/gtkpczhing.html

SELECT * FROM users;
来源：http://dali.sweek.top/Article/details/gtxvluvifp.html

[Q16] 查询指定列
来源：http://dali.quarkkingdee.top/Article/details/gtkobdsfjy.html

SELECT id, name FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtnmnorbbx.html

[Q17] 条件查询
来源：http://dali.sysykeji.top/Article/details/gtixgiyqtf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yuanzhike.top/Article/details/gtbheiglwf.html

[Q18] 模糊匹配
来源：http://dali.yueranfly.top/Article/details/gtlnvwibqm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hnqzz.top/Article/details/gtybijgtkf.html

[Q19] 范围查询
来源：http://dali.shangyingyoupin.top/Article/details/gtznzkfeac.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.sysykeji.top/Article/details/gtrefnkogs.html

[Q20] IN 列表
来源：http://dali.daxiang520.top/Article/details/gtglqilemq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.vqdsnc.cn/Article/details/gtyjvzcsis.html

[Q21] 空值判断
来源：http://dali.yj20258.top/Article/details/gtqriqmwza.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.mhx1999.top/Article/details/gtjvyapquh.html

[Q22] 排序
来源：http://dali.jinghuilouyu.cn/Article/details/gtobltqbnv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.tianlin.xyz/Article/details/gtjsbzmgph.html

[Q23] 分页
来源：http://dali.jyoumei.cn/Article/details/gtvxdunmwl.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yonumen.top/Article/details/gtdwmaogce.html

[Q24] 去重
来源：http://dali.yj202588.top/Article/details/gtiukmasgs.html

SELECT DISTINCT city FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtxkfjdamt.html

[Q25] 只取前 N 条
来源：http://dali.yuxming.cn/Article/details/gtoapttgiv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpnujaszv.html

[Q26] 计数
来源：http://dali.ivvv.top/Article/details/gtnpncfjcm.html

SELECT COUNT(*) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtuotiznta.html

[Q27] 条件计数
来源：http://dali.yangfankeji.com/Article/details/gtfohmeppg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtahcstlta.html

[Q28] 求和与平均
来源：http://dali.nanxuanxn.top/Article/details/gththhdcdl.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtxlfvcdvh.html

[Q29] 最大最小值
来源：http://dali.hammf.cn/Article/details/gtkfnwhdce.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xuanzx.com/Article/details/gtwxtkmkqz.html

[Q30] 分组统计
来源：http://dali.zhixingplan.top/Article/details/gtzeuxybpp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jqgfzy.top/Article/details/gtkapspmsa.html

[Q31] 分组后过滤
来源：http://dali.zycfv.cn/Article/details/gtwmbkwong.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shangyingyoupin.top/Article/details/gtswboxscp.html

[Q32] 分组拼接字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtikhyxvcm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hfpthk.cn/Article/details/gtavqdjufb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.chenlongwang.top/Article/details/gtwbavmjuk.html

[Q33] 多列分组
来源：http://dali.gotoacloud.top/Article/details/gthtwcqhmr.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jinqigfzy.top/Article/details/gtexdinrur.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gthgjobdmx.html

SELECT * FROM (
来源：http://dali.ivvv.top/Article/details/gttjblcpvf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhoulong.xyz/Article/details/gtcagakxhn.html

) t WHERE rn = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtfanrbytu.html

[Q35] 内连接
来源：http://dali.nanxinkj.top/Article/details/gtxcscwqpu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.kuanghao11.cn/Article/details/gtqethzoxf.html

[Q36] 左连接
来源：http://dali.haohaochexian.top/Article/details/gtsniouykx.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuxming.cn/Article/details/gtlcthfkhs.html

[Q37] 右连接
来源：http://dali.aizwys.cn/Article/details/gtacuxlkln.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xuetiantiany.cn/Article/details/gtsnlgpbzh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ybcxt.top/Article/details/gtpjtzqzvg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xuanzx.com/Article/details/gtwymumjia.html

[Q39] 自连接（查上下级）
来源：http://dali.xziqi.cn/Article/details/gtslouqqvk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yj20258888.top/Article/details/gtnjxnxbua.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.fengsongda.top/Article/details/gtjlqisekr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.quarkkingdee.top/Article/details/gtvgtztusf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.andypj.xyz/Article/details/gtbpdcmlzq.html

[Q41] 多表连接
来源：http://dali.quarkkingdee.top/Article/details/gtnijpjsdx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ehwqpu.com/Article/details/gtfjlguqru.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gogol.net.cn/Article/details/gtpmjkibgm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhiwuduotai.top/Article/details/gtkealcluf.html

[Q42] 连接条件附加过滤
来源：http://dali.ydzc1.top/Article/details/gtwfdmxzva.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hammf.cn/Article/details/gtbvjwwzlx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yj202588.top/Article/details/gtisarmsbp.html

[Q43] 标量子查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrulbwiov.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sufxvd.cn/Article/details/gtxzuliyev.html

[Q44] IN 子查询
来源：http://dali.chenjidiqi.icu/Article/details/gthvpelspm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ppjwa.cn/Article/details/gtawnjucfm.html

[Q45] EXISTS 判断存在
来源：http://dali.jinqigfzy.top/Article/details/gtxucaukju.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.vqdsnc.cn/Article/details/gtnnrdccho.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhoulong.xyz/Article/details/gtcyfhzhef.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gaohongyu789.top/Article/details/gtvudlpkrh.html

[Q47] 与平均值比较
来源：http://dali.cqqwz.cn/Article/details/gtqictbmgh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqhylisni.html

[Q48] CTE 公用表表达式
来源：http://dali.meibo888.top/Article/details/gtmffkfxhd.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhongyouzk.top/Article/details/gthytxjhnw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sysykeji.top/Article/details/gtbxrxsfax.html

[Q49] 更新单行
来源：http://dali.zdqjudy.top/Article/details/gtulqlkjhc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gtdvjxways.html

[Q50] 批量更新
来源：http://dali.0kj1m.cn/Article/details/gtqoiartnb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sweek.top/Article/details/gtoroakmwu.html

[Q51] 用子查询更新
来源：http://dali.gogol.net.cn/Article/details/gtexohxhkv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.mhx1999.top/Article/details/gtdaxqjucn.html

[Q52] 删除指定行
来源：http://dali.yvedp.cn/Article/details/gtstaepiyr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cdnleiting.top/Article/details/gtottfufdb.html

[Q53] 按条件删除
来源：http://dali.gaohongyu789.top/Article/details/gtrwapzwoy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xylfe.cn/Article/details/gtjpjxhtiy.html

[Q54] 清空表
来源：http://dali.cqqwz.cn/Article/details/gtuelwibdb.html

TRUNCATE TABLE logs;
来源：http://dali.vqdsnc.cn/Article/details/gtdnjkanis.html

[Q55] 排名（并列占位）
来源：http://dali.ehwqpu.com/Article/details/gtumqulokh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.fzhhl.top/Article/details/gttovowgek.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cucudq.cn/Article/details/gtxaswlpch.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.sweek.top/Article/details/gtjigfnpix.html

[Q57] 行号
来源：http://dali.bjfxy.top/Article/details/gtdlozklxn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxsbyqkpy.html

[Q58] 累计求和
来源：http://dali.nanxinkj.top/Article/details/gtfjaloqac.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.nwbrower.top/Article/details/gtlskuznco.html

[Q59] 分组内累计
来源：http://dali.pengpengdd.cyou/Article/details/gtabfshkjb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yongpay.top/Article/details/gtnwmjguws.html

[Q60] 取上一行 / 下一行
来源：http://dali.yvedp.cn/Article/details/gtswlqjebz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.fzhhl.top/Article/details/gtcdgckenv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yj20258888.top/Article/details/gtdbhdcyoo.html

[Q61] 移动平均
来源：http://dali.cucudq.cn/Article/details/gtobojeobw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xinyue.icu/Article/details/gtiekqyfqg.html

[Q62] 分组占比
来源：http://dali.meibo888.top/Article/details/gtbjxpwgpj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hywenlv.cn/Article/details/gtthupoabu.html

[Q63] 开启事务
来源：http://dali.birdmap.top/Article/details/gtdijbxwlp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jiagoushi.top/Article/details/gtfrkgdzro.html

[Q64] 提交事务
来源：http://dali.wangshuangyany.cn/Article/details/gtqurmnfkq.html

COMMIT;
来源：http://dali.andypj.xyz/Article/details/gtsergtccn.html

[Q65] 回滚事务
来源：http://dali.cdnleiting.top/Article/details/gtvugkyodl.html

ROLLBACK;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnyxxuloc.html

[Q66] 行锁查询
来源：http://dali.hywenlv.cn/Article/details/gtwtscygws.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.kuanghao11.cn/Article/details/gtrwaoxnfx.html

[Q67] 设置隔离级别
来源：http://dali.quarkkingdee.top/Article/details/gtpmdpqgmb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhongyouzk.top/Article/details/gtaggxrqlo.html

[Q68] 保存点
来源：http://dali.yanxiufei.cn/Article/details/gtpkkvneup.html

SAVEPOINT sp1;
来源：http://dali.fengsongda.top/Article/details/gtdewjaxnz.html

ROLLBACK TO sp1;
来源：http://dali.guowangkeji.top/Article/details/gtgjwfptne.html

[Q69] 查看执行计划
来源：http://dali.smart0.xyz/Article/details/gtmrsxjmil.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ybcxt.top/Article/details/gtbssioabq.html

[Q70] 更新统计信息
来源：http://dali.shangyingyoupin.top/Article/details/gtmhtvfzzk.html

ANALYZE TABLE users;
来源：http://dali.xuanzx.com/Article/details/gtietliult.html

[Q71] 查看建表语句
来源：http://dali.sweek.top/Article/details/gtpivcfrhy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cucudq.cn/Article/details/gtwhllrflc.html

[Q72] 查看索引
来源：http://dali.cheryme.top/Article/details/gtqhqeusvr.html

SHOW INDEX FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtaqbtfkzu.html

[Q73] 查看表状态
来源：http://dali.redwolf501.top/Article/details/gtiwxhkykb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jinghuilouyu.cn/Article/details/gtajwqqbue.html

[Q74] 强制使用索引
来源：http://dali.cashguo.top/Article/details/gtjiljgzed.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yj20258888.top/Article/details/gtrxtmpthr.html

[Q75] 日期格式化
来源：http://dali.shuidangran.top/Article/details/gtgowgghed.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gthcrxvzdh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jyoumei.cn/Article/details/gtbcrqrzgr.html

[Q76] 按天统计
来源：http://dali.ybcxt.top/Article/details/gtopvebfvs.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jqgfzy.top/Article/details/gtoqopeuhr.html

[Q77] 时间加减
来源：http://dali.svipenyu.cn/Article/details/gtjxmeohvj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvsyvssrx.html

[Q78] 当前时间
来源：http://dali.xziqi.cn/Article/details/gtqdlzphie.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.fzhhl.top/Article/details/gtbvkxhcog.html

[Q79] 字符串拼接
来源：http://dali.daria6918.cn/Article/details/gtlbmjkpqr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yueranfly.top/Article/details/gtvskioipg.html

[Q80] 字符串截取
来源：http://dali.jlsjyb.cn/Article/details/gthimgjaeu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jianghu66.top/Article/details/gtymsstjfy.html

[Q81] 字符串替换
来源：http://dali.yonumen.top/Article/details/gtlnkbkjdg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtgvkuxxis.html

[Q82] 字符长度与字节长度
来源：http://dali.ehwqpu.com/Article/details/gtpedonqws.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtmzcsunzg.html

[Q83] 大小写转换
来源：http://dali.316326.xyz/Article/details/gtwxomostp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtueyjjcra.html

[Q84] 去除首尾空格
来源：http://dali.jyoumei.cn/Article/details/gtvubejpzp.html

SELECT TRIM(name) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtbrftrkuq.html

[Q85] 数值取整
来源：http://dali.guowangkeji.top/Article/details/gtmyufgdyy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yvedp.cn/Article/details/gtvoqkvnan.html

[Q86] 读取 JSON 字段
来源：http://dali.jinyuanbaomall.cn/Article/details/gtplzczids.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhongyouzk.top/Article/details/gtojzavuno.html

[Q87] JSON 字段做条件
来源：http://dali.sysykeji.top/Article/details/gtmwnuezth.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gogol.net.cn/Article/details/gtfdpaycem.html

[Q88] 行转列（条件聚合）
来源：http://dali.sweek.top/Article/details/gtfwupoxxy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.svipenyu.cn/Article/details/gtsjpvdctw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtjtvnlyuk.html

[Q89] 判断表是否存在
来源：http://dali.dianchejie.cn/Article/details/gteeqbaxxp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nwbrower.top/Article/details/gttdnktlwz.html

[Q90] 生成序号列
来源：http://dali.daxiang520.top/Article/details/gtyfqkphjh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yanxiufei.cn/Article/details/gtqlevudjk.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtoiywgutv.html

R. Bash 专题
来源：http://dali.hongshengwenyu.top/Article/details/gttyxraisv.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtbxvvovqs.html

[R01] shebang 与严格模式
来源：http://dali.yuxming.cn/Article/details/gtzkidawan.html

#!/usr/bin/env bash
来源：http://dali.yueranfly.top/Article/details/gtmpbllfec.html

set -euo pipefail
来源：http://dali.cdnleiting.top/Article/details/gthjzpdbci.html

[R02] 变量赋值与使用
来源：http://dali.tanke756.top/Article/details/gturamrsyb.html

name="Tom"; echo "$name"
来源：http://dali.hnqzz.top/Article/details/gthrpgymic.html

[R03] 只读变量
来源：http://dali.316326.xyz/Article/details/gthqaxkcyw.html

readonly PI=3.14
来源：http://dali.wangshuangyany.cn/Article/details/gtmfaqrfrf.html

[R04] 位置参数
来源：http://dali.0kj1m.cn/Article/details/gtlihmalng.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yj20258.top/Article/details/gttalfofjb.html

[R05] 参数默认值
来源：http://dali.zhengqikj.top/Article/details/gtxfaedsej.html

name="${1:-default}"
来源：http://dali.xuetiantiany.cn/Article/details/gttuynqaxu.html

[R06] 判断命令是否存在
来源：http://dali.xinyue.icu/Article/details/gtkjgackfw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.nanxinkj.top/Article/details/gtdvnajjll.html

[R07] if 判断文件
来源：http://dali.jianghu66.top/Article/details/gtxrozitoh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhongyouzk.top/Article/details/gtfvlbkqtw.html

[R08] 数值比较
来源：http://dali.yj202588.top/Article/details/gtqikhkene.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhongyouzk.top/Article/details/gtdxjgmvzy.html

[R09] 字符串比较
来源：http://dali.hongshengwenyu.top/Article/details/gtfhastfgd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj202588.top/Article/details/gthoxjppmv.html

[R10] 正则匹配
来源：http://dali.guowangkeji.top/Article/details/gtqhhdduwt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.havefunace.top/Article/details/gtfpvhbeuh.html

[R11] case 多分支
来源：http://dali.feifeiyinyue.top/Article/details/gtrbofdnfw.html

case "$1" in
来源：http://dali.guannengcc.top/Article/details/gtciqzxlhz.html

start) echo "启动" ;;
来源：http://dali.xuanzx.com/Article/details/gtscbsiouh.html

stop)  echo "停止" ;;
来源：http://dali.pycfn.com/Article/details/gtatpgnrbv.html

*)     echo "未知命令" ;;
来源：http://dali.kuanghao11.cn/Article/details/gtochwqtxm.html

esac
来源：http://dali.zhoulong.xyz/Article/details/gtjiktlroa.html

[R12] for 遍历文件
来源：http://dali.yj202588.top/Article/details/gtseihtqcz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.pycfn.com/Article/details/gtmxrgispy.html

[R13] for 计数循环
来源：http://dali.hywenlv.cn/Article/details/gtbhoygmgk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.haohaochexian.top/Article/details/gtmprfyxwx.html

[R14] C 风格 for
来源：http://dali.yvedp.cn/Article/details/gtxdijvrmr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hysaishi.cn/Article/details/gtiupkpkwb.html

[R15] while 逐行读文件
来源：http://dali.fengsongda.top/Article/details/gtshpzbypw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.guowangkeji.top/Article/details/gtjlioncpb.html

[R16] until 等待条件
来源：http://dali.hysaishi.cn/Article/details/gtcqqhzeoe.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yangfankeji.com/Article/details/gtojucycmo.html

[R17] 数组定义与取值
来源：http://dali.daxiang520.top/Article/details/gtxieqtdof.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrmscrnys.html

[R18] 遍历数组
来源：http://dali.jinqigfzy.top/Article/details/gtjheypsrz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.tanke756.top/Article/details/gtwwfoznck.html

[R19] 数组长度
来源：http://dali.c1oappe.top/Article/details/gtwxhtxodt.html

echo "${#arr[@]}"
来源：http://dali.chenzaomai.com/Article/details/gtaddiecbb.html

[R20] 关联数组（字典）
来源：http://dali.wangdashe.top/Article/details/gtpyjgnapq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ehwqpu.com/Article/details/gtimwenbvx.html

[R21] 字符串长度
来源：http://dali.iojbl.cn/Article/details/gtrrbzolbq.html

echo "${#s}"
来源：http://dali.ivvv.top/Article/details/gtmzwfmisk.html

[R22] 截取子串
来源：http://dali.gogol.net.cn/Article/details/gtcxbebldo.html

echo "${s:0:5}"
来源：http://dali.xuetiantiany.cn/Article/details/gtqcditrmy.html

[R23] 字符串替换
来源：http://dali.snrcjt.cn/Article/details/gtnlhufcsi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.havefunace.top/Article/details/gttqdzmxai.html

[R24] 大小写转换
来源：http://dali.shuidangran.top/Article/details/gthjikryus.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yuxming.cn/Article/details/gtnshjrcwm.html

[R25] 去后缀 / 去前缀
来源：http://dali.jqgfzy.top/Article/details/gthbzzidpu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hnxiangtu.top/Article/details/gtjvnsivny.html

[R26] 命令替换
来源：http://dali.xuetiantiany.cn/Article/details/gttqqfuqsf.html

now=$(date +%F); echo "$now"
来源：http://dali.vqdsnc.cn/Article/details/gtatjgsqsf.html

[R27] 算术展开
来源：http://dali.quarkkingdee.top/Article/details/gtybycrtkf.html

echo $((1 + 2 * 3))
来源：http://dali.pengpengdd.cyou/Article/details/gttfnrcphj.html

[R28] 浮点运算
来源：http://dali.fzhhl.top/Article/details/gtqmkywbmp.html

echo "scale=2; 10/3" | bc
来源：http://dali.nanxinkj.top/Article/details/gtxcwwsval.html

[R29] 定义函数
来源：http://dali.nanxinkj.top/Article/details/gteumemclb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.andypj.xyz/Article/details/gthckygwcs.html

[R30] 函数返回状态码
来源：http://dali.meibo888.top/Article/details/gtjtugzflm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cucudq.cn/Article/details/gtyiexyhxy.html

[R31] 局部变量
来源：http://dali.zycfv.cn/Article/details/gtkutarebn.html

f() { local x=1; echo "$x"; }
来源：http://dali.hnqzz.top/Article/details/gtdpvwqnwv.html

[R32] 参数个数校验
来源：http://dali.bjfxy.top/Article/details/gtreyjzqsf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xziqi.cn/Article/details/gtmqerxdzu.html

[R33] 捕获错误并提示行号
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwwldcauq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.0kj1m.cn/Article/details/gtioyrapfb.html

[R34] 退出时清理
来源：http://dali.nanxuanxn.top/Article/details/gtbwgsijrl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.wangdashe.top/Article/details/gtunqrqvfa.html

[R35] 后台执行并等待
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvwaboryz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.mhx1999.top/Article/details/gtezxjfeln.html

[R36] 并发执行多个任务
来源：http://dali.jianghu66.top/Article/details/gtzumfeown.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xziqi.cn/Article/details/gtsradmuek.html

[R37] 把输出赋给变量
来源：http://dali.yvedp.cn/Article/details/gtwqywpseg.html

files=$(ls -1)
来源：http://dali.zhengqikj.top/Article/details/gtcpbmyyks.html

[R38] 管道串联
来源：http://dali.xylfe.cn/Article/details/gtapwrrepr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shangyingyoupin.top/Article/details/gtjkonhfco.html

[R39] 重定向标准输出与错误
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzwelfwxj.html

cmd > out.log 2>&1
来源：http://dali.hammf.cn/Article/details/gtyefxrrli.html

[R40] 追加写日志
来源：http://dali.jiagoushi.top/Article/details/gtxtazqsui.html

echo "log" >> out.log
来源：http://dali.gzhubu.top/Article/details/gtpxsfewna.html

[R41] 丢弃输出
来源：http://dali.yangfankeji.com/Article/details/gtkfqwphjb.html

cmd >/dev/null 2>&1
来源：http://dali.tanke756.top/Article/details/gtqmwtdiiw.html

[R42] 输入重定向
来源：http://dali.xuetiantiany.cn/Article/details/gtimsmruba.html

wc -l < a.txt
来源：http://dali.zdqjudy.top/Article/details/gtpymnxtbi.html

[R43] 按名字查找文件
来源：http://dali.chenlongwang.top/Article/details/gtoxajbutl.html

find . -name "*.log" -type f
来源：http://dali.yuanzhike.top/Article/details/gtmbosyoph.html

[R44] 按修改时间查找
来源：http://dali.wangdashe.top/Article/details/gtgoekriho.html

find . -mtime -7 -type f
来源：http://dali.hywenlv.cn/Article/details/gtpsmpprjb.html

[R45] 批量删除
来源：http://dali.iojbl.cn/Article/details/gtsflqhvyz.html

find . -name "*.tmp" -delete
来源：http://dali.sweek.top/Article/details/gtyulvlove.html

[R46] 递归替换文件内容
来源：http://dali.dashuyun.cn/Article/details/gtqdkdiezq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.birdmap.top/Article/details/gttoktlfsh.html

[R47] sed 单行替换
来源：http://dali.zycfv.cn/Article/details/gtvjsrjuep.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jiagoushi.top/Article/details/gtqzgcgxpq.html

[R48] awk 取指定列
来源：http://dali.feifeiyinyue.top/Article/details/gttndjljvx.html

awk '{print $1, $3}' a.txt
来源：http://dali.cheryme.top/Article/details/gtjaorxxsx.html

[R49] awk 带条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtypluctyo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sysykeji.top/Article/details/gtvalrwddg.html

[R50] awk 求和
来源：http://dali.yuanzhike.top/Article/details/gtxevsptlg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zdqjudy.top/Article/details/gtnyhebzns.html

[R51] 排序去重取前几
来源：http://dali.tianlin.xyz/Article/details/gtlmjzxoqn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jyoumei.cn/Article/details/gtfabdabqp.html

[R52] 统计行数
来源：http://dali.ybcxt.top/Article/details/gtwzqcafhc.html

wc -l a.txt
来源：http://dali.hfpthk.cn/Article/details/gtuiyytsyp.html

[R53] 查看文件头与实时尾
来源：http://dali.wangdashe.top/Article/details/gttldpmrol.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.nanxinkj.top/Article/details/gtwxxzoaeu.html

[R54] 比较两个文件
来源：http://dali.yanxiufei.cn/Article/details/gtinrbomsw.html

diff a.txt b.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbmllpolh.html

[R55] 压缩与解压
来源：http://dali.xylfe.cn/Article/details/gtuauqhdva.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.snrcjt.cn/Article/details/gtubifzzqs.html

[R56] 远程拷贝
来源：http://dali.tianlin.xyz/Article/details/gtnxhvykty.html

scp file user@host:/path/
来源：http://dali.chenzaomai.com/Article/details/gthliytfll.html

[R57] 远程执行命令
来源：http://dali.wangdashe.top/Article/details/gtqigmzzgd.html

ssh user@host 'uptime'
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmzszztvj.html

[R58] 下载文件
来源：http://dali.ybcxt.top/Article/details/gtnbsoluxz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.pycfn.com/Article/details/gtuzkbbagn.html

[R59] 发 POST JSON
来源：http://dali.aibaodan.cn/Article/details/gtbtbkjkez.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.haohaochexian.top/Article/details/gtwgyvddjq.html

[R60] 只看 HTTP 状态码
来源：http://dali.shangyingyoupin.top/Article/details/gtvpephnhf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gogol.net.cn/Article/details/gtosaqupun.html

[R61] 磁盘占用
来源：http://dali.xziqi.cn/Article/details/gtujnnoxvf.html

df -h;  du -sh *
来源：http://dali.cucudq.cn/Article/details/gteqahawlc.html

[R62] 找最占空间的文件
来源：http://dali.chenlongwang.top/Article/details/gtlcrzkkiu.html

du -ah . | sort -rh | head -10
来源：http://dali.andypj.xyz/Article/details/gtqyzlagnf.html

[R63] 内存与进程
来源：http://dali.hnqzz.top/Article/details/gthevxkusw.html


<!-- 参考信息 -->