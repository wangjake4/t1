代发 wailian999

[Q14] 存在则更新（upsert）
来源：http://dali.xziqi.cn/Article/details/gtxjfwkdlq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.guannengcc.top/Article/details/gtkmtznbnm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cucudq.cn/Article/details/gtosztjfow.html

[Q15] 查询全部
来源：http://dali.xziqi.cn/Article/details/gtaqcmnvay.html

SELECT * FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtvexrrmar.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gtocznsiam.html

SELECT id, name FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtbrleecgn.html

[Q17] 条件查询
来源：http://dali.dashuyun.cn/Article/details/gtznwygkch.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.chenlongwang.top/Article/details/gtchmizvxg.html

[Q18] 模糊匹配
来源：http://dali.hnxiangtu.top/Article/details/gtyjkwwmzq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.fengsongda.top/Article/details/gtwnftcrjs.html

[Q19] 范围查询
来源：http://dali.chenjidiqi.icu/Article/details/gtowueybgn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cashguo.top/Article/details/gtvhihneiw.html

[Q20] IN 列表
来源：http://dali.yuxming.cn/Article/details/gtxhfqecjy.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.guowangkeji.top/Article/details/gtyzexefqz.html

[Q21] 空值判断
来源：http://dali.zhengqikj.top/Article/details/gtwxmmukja.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hongshengwenyu.top/Article/details/gtvnczjlab.html

[Q22] 排序
来源：http://dali.snrcjt.cn/Article/details/gtsjxqrtpv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaptobjag.html

[Q23] 分页
来源：http://dali.wangshuangyany.cn/Article/details/gtsyuqelbx.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenlongwang.top/Article/details/gtdldnjeix.html

[Q24] 去重
来源：http://dali.svipenyu.cn/Article/details/gtwfybsxuf.html

SELECT DISTINCT city FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxkpflnql.html

[Q25] 只取前 N 条
来源：http://dali.zhixingplan.top/Article/details/gtbvxslfpx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ydzc1.top/Article/details/gtdqszktvb.html

[Q26] 计数
来源：http://dali.hfpthk.cn/Article/details/gtprixbeqk.html

SELECT COUNT(*) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gttgsqymff.html

[Q27] 条件计数
来源：http://dali.xziqi.cn/Article/details/gttybxnxin.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.aizwys.cn/Article/details/gtcompwwpq.html

[Q28] 求和与平均
来源：http://dali.hammf.cn/Article/details/gtvbvdgicy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtawznqzun.html

[Q29] 最大最小值
来源：http://dali.feifeiyinyue.top/Article/details/gticmufmyh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvnmmjdso.html

[Q30] 分组统计
来源：http://dali.yongpay.top/Article/details/gtwslxlyrq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shzxlz.cn/Article/details/gtgfvoatau.html

[Q31] 分组后过滤
来源：http://dali.jinqigfzy.top/Article/details/gtllqilezw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.birdmap.top/Article/details/gtitwqnfhv.html

[Q32] 分组拼接字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtkyhvntqg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yj20258888.top/Article/details/gtvfynktkk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.havefunace.top/Article/details/gthfcretgu.html

[Q33] 多列分组
来源：http://dali.meibo888.top/Article/details/gtdvuklbih.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.vqdsnc.cn/Article/details/gtdjivsysw.html

[Q34] 每组取第一条
来源：http://dali.kuanghao11.cn/Article/details/gtqhvagosb.html

SELECT * FROM (
来源：http://dali.smart0.xyz/Article/details/gtcxmiplnw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gogol.net.cn/Article/details/gtnsuogwqi.html

) t WHERE rn = 1;
来源：http://dali.daria6918.cn/Article/details/gtmphyqkrk.html

[Q35] 内连接
来源：http://dali.nanxuanxn.top/Article/details/gtqofklrlo.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.sweek.top/Article/details/gttzmgkjgg.html

[Q36] 左连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgjmmtczb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.fengsongda.top/Article/details/gtrobawhbt.html

[Q37] 右连接
来源：http://dali.nwbrower.top/Article/details/gtikphwmgu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvgjsnlxg.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zycfv.cn/Article/details/gtextwdmup.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.birdmap.top/Article/details/gthjrzboeg.html

[Q39] 自连接（查上下级）
来源：http://dali.jinqigfzy.top/Article/details/gtyuwudyts.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinyuanbaomall.cn/Article/details/gtakghudxm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.sufxvd.cn/Article/details/gttexdhvht.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.bjfxy.top/Article/details/gtolbssnjw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cheryme.top/Article/details/gtqprfjywa.html

[Q41] 多表连接
来源：http://dali.nanxuanxn.top/Article/details/gtaeakyvje.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhengqikj.top/Article/details/gthgzsikvy.html

JOIN users u ON u.id = o.user_id
来源：http://dali.pengpengdd.cyou/Article/details/gtuxauahlg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ybcxt.top/Article/details/gtkwktvlky.html

[Q42] 连接条件附加过滤
来源：http://dali.hnxiangtu.top/Article/details/gtbfapeohf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yongpay.top/Article/details/gtqokyiark.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.haohaochexian.top/Article/details/gtxavtvffu.html

[Q43] 标量子查询
来源：http://dali.nanxuanxn.top/Article/details/gtpjijqwcs.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.meibo888.top/Article/details/gtnlsuuexx.html

[Q44] IN 子查询
来源：http://dali.hfpthk.cn/Article/details/gtvlhvgpui.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.wangdashe.top/Article/details/gtiyqidkzi.html

[Q45] EXISTS 判断存在
来源：http://dali.cqqwz.cn/Article/details/gtcrgwecup.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhengqikj.top/Article/details/gtjekizxli.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shangyingyoupin.top/Article/details/gtxztpfxsn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.andypj.xyz/Article/details/gtwotjjgzf.html

[Q47] 与平均值比较
来源：http://dali.gogol.net.cn/Article/details/gtmknjddye.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hnxiangtu.top/Article/details/gtaewwbfpv.html

[Q48] CTE 公用表表达式
来源：http://dali.ydzc1.top/Article/details/gtpmbkgipu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zycfv.cn/Article/details/gtwlrwvcyv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.vqdsnc.cn/Article/details/gtwnwxihnn.html

[Q49] 更新单行
来源：http://dali.snrcjt.cn/Article/details/gtvyxcwtzi.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.gotoacloud.top/Article/details/gtniwtugtx.html

[Q50] 批量更新
来源：http://dali.xylfe.cn/Article/details/gtipvlredg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zdqjudy.top/Article/details/gtzxttrlmc.html

[Q51] 用子查询更新
来源：http://dali.gogol.net.cn/Article/details/gtjghofuji.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gtcxlwypnq.html

[Q52] 删除指定行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtblwzwixo.html

DELETE FROM users WHERE id = 10;
来源：http://dali.fengsongda.top/Article/details/gtlqxebybh.html

[Q53] 按条件删除
来源：http://dali.yangfankeji.com/Article/details/gtlglbwdvw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xylfe.cn/Article/details/gtctrgoxfq.html

[Q54] 清空表
来源：http://dali.zdqjudy.top/Article/details/gtsrbigwms.html

TRUNCATE TABLE logs;
来源：http://dali.jinqigfzy.top/Article/details/gtbjejvsoz.html

[Q55] 排名（并列占位）
来源：http://dali.gotoacloud.top/Article/details/gtzuxevmqm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hywenlv.cn/Article/details/gtsfhzzpgp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.andypj.xyz/Article/details/gtrdawrwsb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cdnleiting.top/Article/details/gtctfnozmv.html

[Q57] 行号
来源：http://dali.iojbl.cn/Article/details/gtoiiljngz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiqtgvyex.html

[Q58] 累计求和
来源：http://dali.xylfe.cn/Article/details/gttgmllrym.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gtypfhensv.html

[Q59] 分组内累计
来源：http://dali.dashuyun.cn/Article/details/gtvbuqahqr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtwziftkas.html

[Q60] 取上一行 / 下一行
来源：http://dali.xinyue.icu/Article/details/gtzmxfqgbd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.snrcjt.cn/Article/details/gtrqpkrktr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xylfe.cn/Article/details/gtujhvxmel.html

[Q61] 移动平均
来源：http://dali.gotoacloud.top/Article/details/gtmvophbdz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrugzezpj.html

[Q62] 分组占比
来源：http://dali.snrcjt.cn/Article/details/gtinrpfwle.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xylfe.cn/Article/details/gtesvsknbj.html

[Q63] 开启事务
来源：http://dali.sufxvd.cn/Article/details/gtkixjvgix.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.mhx1999.top/Article/details/gturjswhes.html

[Q64] 提交事务
来源：http://dali.sweek.top/Article/details/gtjtqgfsjc.html

COMMIT;
来源：http://dali.chenlongwang.top/Article/details/gtvsnlwrny.html

[Q65] 回滚事务
来源：http://dali.mhx1999.top/Article/details/gtupvobijq.html

ROLLBACK;
来源：http://dali.sysykeji.top/Article/details/gtelyybpld.html

[Q66] 行锁查询
来源：http://dali.yuanzhike.top/Article/details/gtkshmlgkr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.andypj.xyz/Article/details/gtcydbspkf.html

[Q67] 设置隔离级别
来源：http://dali.yueranfly.top/Article/details/gtcuczkshq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.sysykeji.top/Article/details/gtixscmmmc.html

[Q68] 保存点
来源：http://dali.xuetiantiany.cn/Article/details/gtqnzbklxz.html

SAVEPOINT sp1;
来源：http://dali.mhx1999.top/Article/details/gtzlfoeumi.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gtjzayghlk.html

[Q69] 查看执行计划
来源：http://dali.zhixingplan.top/Article/details/gtypybgntt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gtiqgcovdr.html

[Q70] 更新统计信息
来源：http://dali.jlsjyb.cn/Article/details/gtjbzqygjb.html

ANALYZE TABLE users;
来源：http://dali.fzhhl.top/Article/details/gtgeanihpw.html

[Q71] 查看建表语句
来源：http://dali.zhixingplan.top/Article/details/gtldmnckkd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hysaishi.cn/Article/details/gtzdisrwtc.html

[Q72] 查看索引
来源：http://dali.xylfe.cn/Article/details/gtfrwjblgk.html

SHOW INDEX FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtzahkgzgu.html

[Q73] 查看表状态
来源：http://dali.cucudq.cn/Article/details/gtpmvanzru.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.aibaodan.cn/Article/details/gtxreoytvm.html

[Q74] 强制使用索引
来源：http://dali.jiagoushi.top/Article/details/gtbxgaiyru.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.9152youxi.cn/Article/details/gtyfcbndou.html

[Q75] 日期格式化
来源：http://dali.jianghu66.top/Article/details/gtwkslnnzm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.meibo888.top/Article/details/gtjyzkeagf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.chenlongwang.top/Article/details/gtafkagixu.html

[Q76] 按天统计
来源：http://dali.ehwqpu.com/Article/details/gtktrtrmki.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.dashuyun.cn/Article/details/gtvwipoamu.html

[Q77] 时间加减
来源：http://dali.nanxuanxn.top/Article/details/gtktstniyf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.nanxinkj.top/Article/details/gtrhahccap.html

[Q78] 当前时间
来源：http://dali.kuanghao11.cn/Article/details/gtvtncdurk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hysaishi.cn/Article/details/gtpoyemqth.html

[Q79] 字符串拼接
来源：http://dali.chenzaomai.com/Article/details/gtiqawpfic.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sysykeji.top/Article/details/gtntxdkakd.html

[Q80] 字符串截取
来源：http://dali.quarkkingdee.top/Article/details/gteairqits.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtfcqenvsi.html

[Q81] 字符串替换
来源：http://dali.gzhubu.top/Article/details/gtfomuprlj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtvpxsuamn.html

[Q82] 字符长度与字节长度
来源：http://dali.kuanghao11.cn/Article/details/gthyjvjdjg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gthmeursyz.html

[Q83] 大小写转换
来源：http://dali.guannengcc.top/Article/details/gtjwxezdqb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtabfhslrk.html

[Q84] 去除首尾空格
来源：http://dali.dashuyun.cn/Article/details/gtsdddltgb.html

SELECT TRIM(name) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtdcqifplc.html

[Q85] 数值取整
来源：http://dali.shangyingyoupin.top/Article/details/gtsrgclxyo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.0kj1m.cn/Article/details/gttttaclsz.html

[Q86] 读取 JSON 字段
来源：http://dali.yueranfly.top/Article/details/gtanylqufd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.0kj1m.cn/Article/details/gtbqpklhdx.html

[Q87] JSON 字段做条件
来源：http://dali.hfpthk.cn/Article/details/gthcbnqxgp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xziqi.cn/Article/details/gtojdhumlp.html

[Q88] 行转列（条件聚合）
来源：http://dali.jinqigfzy.top/Article/details/gtigosafsu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jiagoushi.top/Article/details/gtgdrxpeya.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtgoeimhjf.html

[Q89] 判断表是否存在
来源：http://dali.shangyingyoupin.top/Article/details/gtmbkdjvoa.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.wangdashe.top/Article/details/gtdbtweded.html

[Q90] 生成序号列
来源：http://dali.jianghu66.top/Article/details/gticjnetqm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.pengpengdd.cyou/Article/details/gtdcvaxksk.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtodkxbfnd.html

R. Bash 专题
来源：http://dali.yueranfly.top/Article/details/gtwlkzpuxn.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtjisxavba.html

[R01] shebang 与严格模式
来源：http://dali.meibo888.top/Article/details/gttrfbdjed.html

#!/usr/bin/env bash
来源：http://dali.havefunace.top/Article/details/gtppqrrgfw.html

set -euo pipefail
来源：http://dali.shzxlz.cn/Article/details/gtndcbbefw.html

[R02] 变量赋值与使用
来源：http://dali.gaohongyu789.top/Article/details/gtzoihclyu.html

name="Tom"; echo "$name"
来源：http://dali.yonumen.top/Article/details/gtvdittmrr.html

[R03] 只读变量
来源：http://dali.hongshengwenyu.top/Article/details/gtxsbzfggy.html

readonly PI=3.14
来源：http://dali.snrcjt.cn/Article/details/gtdwvlqyux.html

[R04] 位置参数
来源：http://dali.gzhubu.top/Article/details/gtjgygeofk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yj20258.top/Article/details/gtgmxlufhn.html

[R05] 参数默认值
来源：http://dali.yongpay.top/Article/details/gtmtcjhsar.html

name="${1:-default}"
来源：http://dali.ybcxt.top/Article/details/gtbjlemyzy.html

[R06] 判断命令是否存在
来源：http://dali.xinyue.icu/Article/details/gtsfhtijun.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cdnleiting.top/Article/details/gtahvgivbh.html

[R07] if 判断文件
来源：http://dali.feifeiyinyue.top/Article/details/gtjcfxrbpu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ppjwa.cn/Article/details/gtiyhvfjow.html

[R08] 数值比较
来源：http://dali.nanxinkj.top/Article/details/gtmnevboau.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zdqjudy.top/Article/details/gtijkmqocj.html

[R09] 字符串比较
来源：http://dali.jqgfzy.top/Article/details/gteflrqkex.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.wangdashe.top/Article/details/gtbsmkcpoj.html

[R10] 正则匹配
来源：http://dali.chenjidiqi.icu/Article/details/gtmatcwggr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.smart0.xyz/Article/details/gtkwuzooay.html

[R11] case 多分支
来源：http://dali.zhengqikj.top/Article/details/gtnstxdaen.html

case "$1" in
来源：http://dali.guannengcc.top/Article/details/gtwpduqcxh.html

start) echo "启动" ;;
来源：http://dali.jiagoushi.top/Article/details/gtlfnytlwf.html

stop)  echo "停止" ;;
来源：http://dali.bjfxy.top/Article/details/gtgfuwxxxm.html

*)     echo "未知命令" ;;
来源：http://dali.vqdsnc.cn/Article/details/gtidhjiwtg.html

esac
来源：http://dali.ivvv.top/Article/details/gtjmwoctly.html

[R12] for 遍历文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtflkgjlci.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hfpthk.cn/Article/details/gtsprmbunb.html

[R13] for 计数循环
来源：http://dali.shuidangran.top/Article/details/gtmktxniwe.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.vqdsnc.cn/Article/details/gtshheowmy.html

[R14] C 风格 for
来源：http://dali.nanxuanxn.top/Article/details/gtrnuomjra.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtoqsxirmn.html

[R15] while 逐行读文件
来源：http://dali.jianghu66.top/Article/details/gtboifwgfh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xinyue.icu/Article/details/gtgqgigmql.html

[R16] until 等待条件
来源：http://dali.yuxming.cn/Article/details/gtzilrloxw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.guannengcc.top/Article/details/gtlmkmhlng.html

[R17] 数组定义与取值
来源：http://dali.svipenyu.cn/Article/details/gtzanggnbg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.tian-w.cn/Article/details/gtsddlppzh.html

[R18] 遍历数组
来源：http://dali.sufxvd.cn/Article/details/gtlwopeixx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.fzhhl.top/Article/details/gtuihatfqv.html

[R19] 数组长度
来源：http://dali.nwbrower.top/Article/details/gtgitvkbuf.html

echo "${#arr[@]}"
来源：http://dali.birdmap.top/Article/details/gtmlgwrbiy.html

[R20] 关联数组（字典）
来源：http://dali.c1oappe.top/Article/details/gtklakktqb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtownfsrro.html

[R21] 字符串长度
来源：http://dali.yj202588.top/Article/details/gtyxankdly.html

echo "${#s}"
来源：http://dali.redwolf501.top/Article/details/gtwynmaitp.html

[R22] 截取子串
来源：http://dali.sufxvd.cn/Article/details/gtbytpnpik.html

echo "${s:0:5}"
来源：http://dali.kuanghao11.cn/Article/details/gtmxnyliln.html

[R23] 字符串替换
来源：http://dali.0kj1m.cn/Article/details/gtlecwelqn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yangfankeji.com/Article/details/gtyesgdbcw.html

[R24] 大小写转换
来源：http://dali.yanxiufei.cn/Article/details/gtfrtduqtr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.9152youxi.cn/Article/details/gthgvvrpiz.html

[R25] 去后缀 / 去前缀
来源：http://dali.guannengcc.top/Article/details/gtehmjuobb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.9152youxi.cn/Article/details/gtzclwquwa.html

[R26] 命令替换
来源：http://dali.zhixingplan.top/Article/details/gthyabbubb.html

now=$(date +%F); echo "$now"
来源：http://dali.sysykeji.top/Article/details/gtedgmzcsi.html

[R27] 算术展开
来源：http://dali.xziqi.cn/Article/details/gtwdewckaw.html

echo $((1 + 2 * 3))
来源：http://dali.sufxvd.cn/Article/details/gthnjvevpg.html

[R28] 浮点运算
来源：http://dali.sufxvd.cn/Article/details/gtgrbkvhow.html

echo "scale=2; 10/3" | bc
来源：http://dali.nanxinkj.top/Article/details/gtxekfgzew.html

[R29] 定义函数
来源：http://dali.hammf.cn/Article/details/gtyzyinayt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yj20258.top/Article/details/gtfzrylrcq.html

[R30] 函数返回状态码
来源：http://dali.bjfxy.top/Article/details/gtnezsjqjk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.gogol.net.cn/Article/details/gtsubvvjgw.html

[R31] 局部变量
来源：http://dali.gotoacloud.top/Article/details/gttxrrzbkj.html

f() { local x=1; echo "$x"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaoqvtedv.html

[R32] 参数个数校验
来源：http://dali.meibo888.top/Article/details/gtffjeioeb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhiwuduotai.top/Article/details/gtteytaacq.html

[R33] 捕获错误并提示行号
来源：http://dali.jqgfzy.top/Article/details/gtpxozbpsm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hammf.cn/Article/details/gtupcythkd.html

[R34] 退出时清理
来源：http://dali.hnxiangtu.top/Article/details/gtclhpbmbj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.tianlin.xyz/Article/details/gtshpclnyr.html

[R35] 后台执行并等待
来源：http://dali.kuanghao11.cn/Article/details/gtxryuncdr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.tian-w.cn/Article/details/gtvetwcwgw.html

[R36] 并发执行多个任务
来源：http://dali.gotoacloud.top/Article/details/gtdotpilmp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.wangshuangyany.cn/Article/details/gtwmsqxuuc.html

[R37] 把输出赋给变量
来源：http://dali.snrcjt.cn/Article/details/gtdrklizro.html

files=$(ls -1)
来源：http://dali.jinqigfzy.top/Article/details/gtjvcnsoxz.html

[R38] 管道串联
来源：http://dali.yanxiufei.cn/Article/details/gtrvodmttq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gtyonluutb.html

[R39] 重定向标准输出与错误
来源：http://dali.316326.xyz/Article/details/gtsyayfcha.html

cmd > out.log 2>&1
来源：http://dali.shuidangran.top/Article/details/gtpqqilgoi.html

[R40] 追加写日志
来源：http://dali.cashguo.top/Article/details/gtapnkvzru.html

echo "log" >> out.log
来源：http://dali.haohaochexian.top/Article/details/gtbepfoqih.html

[R41] 丢弃输出
来源：http://dali.cashguo.top/Article/details/gtxdyqnlci.html

cmd >/dev/null 2>&1
来源：http://dali.feifeiyinyue.top/Article/details/gtywedayyo.html

[R42] 输入重定向
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbkucxxpg.html

wc -l < a.txt
来源：http://dali.hnqzz.top/Article/details/gtugqqbrjt.html

[R43] 按名字查找文件
来源：http://dali.meibo888.top/Article/details/gtzzbrvtna.html

find . -name "*.log" -type f
来源：http://dali.quarkkingdee.top/Article/details/gtudgoalpj.html

[R44] 按修改时间查找
来源：http://dali.meibo888.top/Article/details/gtoifeigui.html

find . -mtime -7 -type f
来源：http://dali.yvedp.cn/Article/details/gtrqwzrhaq.html

[R45] 批量删除
来源：http://dali.nanxuanxn.top/Article/details/gtupheekwm.html

find . -name "*.tmp" -delete
来源：http://dali.shzxlz.cn/Article/details/gtafbxrhjp.html

[R46] 递归替换文件内容
来源：http://dali.wangshuangyany.cn/Article/details/gthjvzuutt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.tianlin.xyz/Article/details/gtjzpzwfjc.html

[R47] sed 单行替换
来源：http://dali.yj20258888.top/Article/details/gtjlqnigkh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtnfirvpwh.html

[R48] awk 取指定列
来源：http://dali.tian-w.cn/Article/details/gtnysvztqc.html

awk '{print $1, $3}' a.txt
来源：http://dali.tanke756.top/Article/details/gtzonjrmvo.html

[R49] awk 带条件
来源：http://dali.c1oappe.top/Article/details/gtjaqbmolq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shuidangran.top/Article/details/gtwwsccxgr.html

[R50] awk 求和
来源：http://dali.sweek.top/Article/details/gtutxdadun.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ppjwa.cn/Article/details/gtilescxoi.html

[R51] 排序去重取前几
来源：http://dali.ehwqpu.com/Article/details/gtbqzrteac.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.chenlongwang.top/Article/details/gtgdyrsynl.html

[R52] 统计行数
来源：http://dali.yuxming.cn/Article/details/gttxalgsew.html

wc -l a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtqoztodic.html

[R53] 查看文件头与实时尾
来源：http://dali.shangyingyoupin.top/Article/details/gtkpufrawg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.nwbrower.top/Article/details/gtloovrtbl.html

[R54] 比较两个文件
来源：http://dali.hammf.cn/Article/details/gttoxvcssi.html

diff a.txt b.txt
来源：http://dali.zdqjudy.top/Article/details/gtkyfwdtnv.html

[R55] 压缩与解压
来源：http://dali.nwbrower.top/Article/details/gtkmoacaqd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shangyingyoupin.top/Article/details/gtxwkqukdx.html

[R56] 远程拷贝
来源：http://dali.yuanzhike.top/Article/details/gtivvgddty.html

scp file user@host:/path/
来源：http://dali.yongpay.top/Article/details/gtptqtnisv.html

[R57] 远程执行命令
来源：http://dali.nanxuanxn.top/Article/details/gtqtfprlqj.html

ssh user@host 'uptime'
来源：http://dali.havefunace.top/Article/details/gtayqycfjc.html

[R58] 下载文件
来源：http://dali.pycfn.com/Article/details/gtinmtcwbe.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.pycfn.com/Article/details/gtkoxiolzq.html

[R59] 发 POST JSON
来源：http://dali.gzhubu.top/Article/details/gtgucekvmx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yuanzhike.top/Article/details/gtxmbasygl.html

[R60] 只看 HTTP 状态码
来源：http://dali.tian-w.cn/Article/details/gtujwzmyeh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkiibdbhh.html

[R61] 磁盘占用
来源：http://dali.haohaochexian.top/Article/details/gtprwpxqhr.html

df -h;  du -sh *
来源：http://dali.dashuyun.cn/Article/details/gtarldqtws.html

[R62] 找最占空间的文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfenutanv.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gtnzckyzee.html

[R63] 内存与进程
来源：http://dali.shangyingyoupin.top/Article/details/gtekrvsaac.html


<!-- 参考信息 -->