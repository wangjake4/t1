代发 wailian999

[Q14] 存在则更新（upsert）
来源：http://dali.dianchejie.cn/Article/details/gtbzzfiefd.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.vqdsnc.cn/Article/details/gtiplzxdel.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.shanyushiyangtech.top/Article/details/gtqvmfgcea.html

[Q15] 查询全部
来源：http://dali.nanxinkj.top/Article/details/gtrizfzvbk.html

SELECT * FROM users;
来源：http://dali.andypj.xyz/Article/details/gtbzmfptor.html

[Q16] 查询指定列
来源：http://dali.andypj.xyz/Article/details/gtaffqukyv.html

SELECT id, name FROM users;
来源：http://dali.316326.xyz/Article/details/gtqkfhfnzk.html

[Q17] 条件查询
来源：http://dali.guannengcc.top/Article/details/gtuncucaow.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.daxiang520.top/Article/details/gtxbluckug.html

[Q18] 模糊匹配
来源：http://dali.cdnleiting.top/Article/details/gtckbyyujx.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.chenjidiqi.icu/Article/details/gtacywzgra.html

[Q19] 范围查询
来源：http://dali.sxryk.cn/Article/details/gtuimowxsv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.snrcjt.cn/Article/details/gtzyjbgnxl.html

[Q20] IN 列表
来源：http://dali.xinyue.icu/Article/details/gtlyxmhsox.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.aibaodan.cn/Article/details/gtrltpfdri.html

[Q21] 空值判断
来源：http://dali.aizwys.cn/Article/details/gtleyczfhl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xylfe.cn/Article/details/gtykzknqww.html

[Q22] 排序
来源：http://dali.yj20258888.top/Article/details/gtrrqxvjds.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zycfv.cn/Article/details/gtfcpwfncz.html

[Q23] 分页
来源：http://dali.shanyushiyangtech.top/Article/details/gttqiifpok.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xuetiantiany.cn/Article/details/gtucebtlty.html

[Q24] 去重
来源：http://dali.cucudq.cn/Article/details/gtqqwozjzi.html

SELECT DISTINCT city FROM users;
来源：http://dali.hnqzz.top/Article/details/gtxwwptemi.html

[Q25] 只取前 N 条
来源：http://dali.mhx1999.top/Article/details/gtnkhdkara.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.0kj1m.cn/Article/details/gtccffbwfz.html

[Q26] 计数
来源：http://dali.zhiwuduotai.top/Article/details/gtspynuaun.html

SELECT COUNT(*) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtbtmvntyy.html

[Q27] 条件计数
来源：http://dali.shangyingyoupin.top/Article/details/gtirihkzro.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.316326.xyz/Article/details/gtugyhhizp.html

[Q28] 求和与平均
来源：http://dali.jiagoushi.top/Article/details/gtdnyrovep.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gtmivrouwd.html

[Q29] 最大最小值
来源：http://dali.zdqjudy.top/Article/details/gtrmrwjdje.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtajscoskr.html

[Q30] 分组统计
来源：http://dali.yj20258888.top/Article/details/gtakxxmqqg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.chenjidiqi.icu/Article/details/gtbhkksset.html

[Q31] 分组后过滤
来源：http://dali.hfpthk.cn/Article/details/gtwtmyoqtl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfsodsauw.html

[Q32] 分组拼接字符串
来源：http://dali.gzhubu.top/Article/details/gtwjbxawxc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cdnleiting.top/Article/details/gtltrrzqfl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.chenlongwang.top/Article/details/gtsuxkmiqj.html

[Q33] 多列分组
来源：http://dali.0kj1m.cn/Article/details/gtmmtjzgqt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jianghu66.top/Article/details/gtrirbdisl.html

[Q34] 每组取第一条
来源：http://dali.sweek.top/Article/details/gtqycgdxpn.html

SELECT * FROM (
来源：http://dali.ybcxt.top/Article/details/gtbbacuagh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cqqwz.cn/Article/details/gtdtisagks.html

) t WHERE rn = 1;
来源：http://dali.9152youxi.cn/Article/details/gtxwizoldy.html

[Q35] 内连接
来源：http://dali.aibaodan.cn/Article/details/gtqibvipdw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmurihscq.html

[Q36] 左连接
来源：http://dali.gogol.net.cn/Article/details/gtuudgtzfg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.daria6918.cn/Article/details/gtpkqxjenj.html

[Q37] 右连接
来源：http://dali.daxiang520.top/Article/details/gtyvrpenjr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.wangshuangyany.cn/Article/details/gtlzdfwmdj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.dianchejie.cn/Article/details/gtagcevhat.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hysaishi.cn/Article/details/gttgpbafnp.html

[Q39] 自连接（查上下级）
来源：http://dali.chenjidiqi.icu/Article/details/gtoexkdzeq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.sxryk.cn/Article/details/gtcsesxyin.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xinyue.icu/Article/details/gtjnqyqodj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jianghu66.top/Article/details/gtzifbrtou.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hongshengwenyu.top/Article/details/gtjbuisqub.html

[Q41] 多表连接
来源：http://dali.c1oappe.top/Article/details/gtknvtxzjs.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.mhx1999.top/Article/details/gtvfoagmbm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xinyue.icu/Article/details/gtxwtegwgb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.gogol.net.cn/Article/details/gtelhyvlus.html

[Q42] 连接条件附加过滤
来源：http://dali.jqgufenzy.top/Article/details/gtscwhqlgi.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yuanzhike.top/Article/details/gtktvdkqzv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yj20258.top/Article/details/gtdedfznti.html

[Q43] 标量子查询
来源：http://dali.zhengqikj.top/Article/details/gtmvzqjlxk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.snrcjt.cn/Article/details/gtqdfncyde.html

[Q44] IN 子查询
来源：http://dali.gaohongyu789.top/Article/details/gtkbajnoja.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.daria6918.cn/Article/details/gthgtnbxwc.html

[Q45] EXISTS 判断存在
来源：http://dali.shangyingyoupin.top/Article/details/gtphkvzpem.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenjidiqi.icu/Article/details/gtgvvqtedx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yj20258.top/Article/details/gtbfdbdvde.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj202588.top/Article/details/gtqktxwyhl.html

[Q47] 与平均值比较
来源：http://dali.nanxuanxn.top/Article/details/gtlkevkfxd.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cheryme.top/Article/details/gtifzizyuo.html

[Q48] CTE 公用表表达式
来源：http://dali.havefunace.top/Article/details/gtaajvezsk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinqigufen.top/Article/details/gthqskqzfc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yj20258.top/Article/details/gtylpzjqcf.html

[Q49] 更新单行
来源：http://dali.yangfankeji.com/Article/details/gtxpzxpinu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.fzhhl.top/Article/details/gtxjsxdclf.html

[Q50] 批量更新
来源：http://dali.fzhhl.top/Article/details/gtxmckjlmt.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zycfv.cn/Article/details/gtvyoubmar.html

[Q51] 用子查询更新
来源：http://dali.cashguo.top/Article/details/gtxsjkxdlq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cheryme.top/Article/details/gttnpcezrm.html

[Q52] 删除指定行
来源：http://dali.yvedp.cn/Article/details/gtcmlxvrkz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.gzhubu.top/Article/details/gthljkebdk.html

[Q53] 按条件删除
来源：http://dali.zycfv.cn/Article/details/gtkwhdgyll.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xuetiantiany.cn/Article/details/gtwcssbnmk.html

[Q54] 清空表
来源：http://dali.c1oappe.top/Article/details/gtjoijoitq.html

TRUNCATE TABLE logs;
来源：http://dali.zhixingplan.top/Article/details/gtipvhhnnx.html

[Q55] 排名（并列占位）
来源：http://dali.cucudq.cn/Article/details/gtsbwpvodx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.mhx1999.top/Article/details/gthacsimct.html

[Q56] 密集排名（并列不占位）
来源：http://dali.sxryk.cn/Article/details/gtxhnbwcen.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zycfv.cn/Article/details/gtgzurtgto.html

[Q57] 行号
来源：http://dali.meibo888.top/Article/details/gtbmjqjeet.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ivvv.top/Article/details/gtqbpodccp.html

[Q58] 累计求和
来源：http://dali.jinqigufen.top/Article/details/gtyjlpjbtb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.aizwys.cn/Article/details/gtfuovwxfm.html

[Q59] 分组内累计
来源：http://dali.ydzc1.top/Article/details/gtqcrdgvpd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzkmydzdv.html

[Q60] 取上一行 / 下一行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvdeurcwh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.smart0.xyz/Article/details/gtkdajjytw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jianghu66.top/Article/details/gtlewpcnfb.html

[Q61] 移动平均
来源：http://dali.jianghu66.top/Article/details/gtblgsyrfz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gzhubu.top/Article/details/gtnniarsku.html

[Q62] 分组占比
来源：http://dali.jyoumei.cn/Article/details/gtcxffmcpf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.wangshuangyany.cn/Article/details/gtufnweqcx.html

[Q63] 开启事务
来源：http://dali.zhixingplan.top/Article/details/gtaedcmxxk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.guannengcc.top/Article/details/gtqlezhlar.html

[Q64] 提交事务
来源：http://dali.hfpthk.cn/Article/details/gtkbgxnbsr.html

COMMIT;
来源：http://dali.hammf.cn/Article/details/gtvhbpmfuh.html

[Q65] 回滚事务
来源：http://dali.cucudq.cn/Article/details/gtjyrgqqly.html

ROLLBACK;
来源：http://dali.xziqi.cn/Article/details/gtabszzhku.html

[Q66] 行锁查询
来源：http://dali.sweek.top/Article/details/gtuxwmlcsj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cashguo.top/Article/details/gtoxuibxhx.html

[Q67] 设置隔离级别
来源：http://dali.quarkkingdee.top/Article/details/gtjhcbhvzm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.dashuyun.cn/Article/details/gtumsdllfg.html

[Q68] 保存点
来源：http://dali.cashguo.top/Article/details/gtforapxiv.html

SAVEPOINT sp1;
来源：http://dali.bjfxy.top/Article/details/gtfgqjtsna.html

ROLLBACK TO sp1;
来源：http://dali.dianchejie.cn/Article/details/gtbljzjvvg.html

[Q69] 查看执行计划
来源：http://dali.fzhhl.top/Article/details/gtrltfaznf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shzxlz.cn/Article/details/gtikaisogd.html

[Q70] 更新统计信息
来源：http://dali.yonumen.top/Article/details/gtngakkxnw.html

ANALYZE TABLE users;
来源：http://dali.ppjwa.cn/Article/details/gtjzlyxzmi.html

[Q71] 查看建表语句
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlqvrjgrr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.sxryk.cn/Article/details/gtfyhuduzf.html

[Q72] 查看索引
来源：http://dali.ivvv.top/Article/details/gtldofybru.html

SHOW INDEX FROM users;
来源：http://dali.zycfv.cn/Article/details/gtdcawfmfc.html

[Q73] 查看表状态
来源：http://dali.hysaishi.cn/Article/details/gtesxsdasm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.tanke756.top/Article/details/gtkkezyavi.html

[Q74] 强制使用索引
来源：http://dali.fengsongda.top/Article/details/gtobtiiveb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.fengsongda.top/Article/details/gtndnafzjz.html

[Q75] 日期格式化
来源：http://dali.hfpthk.cn/Article/details/gtuutocyzv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.daria6918.cn/Article/details/gtdsszawyf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.meibo888.top/Article/details/gtvwvdtykz.html

[Q76] 按天统计
来源：http://dali.xinyue.icu/Article/details/gtouyhuhhu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yongpay.top/Article/details/gtmqvzvzqo.html

[Q77] 时间加减
来源：http://dali.hysaishi.cn/Article/details/gtvohrdvgc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yj202588.top/Article/details/gtpirkptwo.html

[Q78] 当前时间
来源：http://dali.gotoacloud.top/Article/details/gtuiarujia.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.gogol.net.cn/Article/details/gtxkafyfer.html

[Q79] 字符串拼接
来源：http://dali.yj20258888.top/Article/details/gtmjrrwxun.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xinyue.icu/Article/details/gtribfpvaa.html

[Q80] 字符串截取
来源：http://dali.chenzaomai.com/Article/details/gtmwpcxcqd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtxxypdbdr.html

[Q81] 字符串替换
来源：http://dali.andypj.xyz/Article/details/gtxdaykjun.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtvhfpsmor.html

[Q82] 字符长度与字节长度
来源：http://dali.havefunace.top/Article/details/gtwqojznec.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.meibo888.top/Article/details/gtibrtpwyf.html

[Q83] 大小写转换
来源：http://dali.aizwys.cn/Article/details/gtnfykjclf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cheryme.top/Article/details/gthnzammgi.html

[Q84] 去除首尾空格
来源：http://dali.dianchejie.cn/Article/details/gtbbltycrn.html

SELECT TRIM(name) FROM users;
来源：http://dali.xinyue.icu/Article/details/gtyuxkaxrc.html

[Q85] 数值取整
来源：http://dali.svipenyu.cn/Article/details/gtaqqbffue.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cqqwz.cn/Article/details/gtgzhxkdkv.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gtjbajmiqp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.iojbl.cn/Article/details/gtigagzcpz.html

[Q87] JSON 字段做条件
来源：http://dali.shangyingyoupin.top/Article/details/gtoklwvimg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.aizwys.cn/Article/details/gtanrvfsiv.html

[Q88] 行转列（条件聚合）
来源：http://dali.snrcjt.cn/Article/details/gtsnjgqwdt.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.daxiang520.top/Article/details/gtsqyhynmc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtjeftgrtf.html

[Q89] 判断表是否存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbwgvbhym.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.sysykeji.top/Article/details/gtsoadikvg.html

[Q90] 生成序号列
来源：http://dali.yj20258888.top/Article/details/gtqqluojfb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.feifeiyinyue.top/Article/details/gthfncxafa.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtapxzarhh.html

R. Bash 专题
来源：http://dali.ybcxt.top/Article/details/gtmobgcrab.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtlwsvyyke.html

[R01] shebang 与严格模式
来源：http://dali.guannengcc.top/Article/details/gtuyspbcwm.html

#!/usr/bin/env bash
来源：http://dali.hnxiangtu.top/Article/details/gtlujizssp.html

set -euo pipefail
来源：http://dali.kuanghao11.cn/Article/details/gtarnyapkw.html

[R02] 变量赋值与使用
来源：http://dali.fzhhl.top/Article/details/gthcbwgnfa.html

name="Tom"; echo "$name"
来源：http://dali.smart0.xyz/Article/details/gtnnnuirem.html

[R03] 只读变量
来源：http://dali.316326.xyz/Article/details/gtmdydzbvi.html

readonly PI=3.14
来源：http://dali.jyoumei.cn/Article/details/gtgvwwcxwg.html

[R04] 位置参数
来源：http://dali.daria6918.cn/Article/details/gtrpnyddoa.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ydzc1.top/Article/details/gtnxjnkfuz.html

[R05] 参数默认值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwfpygdcy.html

name="${1:-default}"
来源：http://dali.daxiang520.top/Article/details/gtigihjtku.html

[R06] 判断命令是否存在
来源：http://dali.xinyue.icu/Article/details/gtctymlwzc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.pycfn.com/Article/details/gtnbkhdmfi.html

[R07] if 判断文件
来源：http://dali.jinqigufen.top/Article/details/gtnwdlepdy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.haohaochexian.top/Article/details/gtwkmfmqvu.html

[R08] 数值比较
来源：http://dali.xuetiantiany.cn/Article/details/gteqdddbuw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cucudq.cn/Article/details/gtbyggtfeh.html

[R09] 字符串比较
来源：http://dali.zhongyouzk.top/Article/details/gthxakjyqa.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhengqikj.top/Article/details/gtesomqhqh.html

[R10] 正则匹配
来源：http://dali.jqgufenzy.top/Article/details/gtzrdcbhlm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yj202588.top/Article/details/gtsyhelxfi.html

[R11] case 多分支
来源：http://dali.fengsongda.top/Article/details/gtrqslcrsn.html

case "$1" in
来源：http://dali.yvedp.cn/Article/details/gtqpkhogyd.html

start) echo "启动" ;;
来源：http://dali.iojbl.cn/Article/details/gtkefmymcf.html

stop)  echo "停止" ;;
来源：http://dali.shuidangran.top/Article/details/gtvslzmnhl.html

*)     echo "未知命令" ;;
来源：http://dali.smart0.xyz/Article/details/gtxcnheasz.html

esac
来源：http://dali.hysaishi.cn/Article/details/gtjucszbex.html

[R12] for 遍历文件
来源：http://dali.nanxuanxn.top/Article/details/gtbxgitsnk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yj202588.top/Article/details/gtjnixezlx.html

[R13] for 计数循环
来源：http://dali.iojbl.cn/Article/details/gtkwnrtplm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zycfv.cn/Article/details/gtaafjygpu.html

[R14] C 风格 for
来源：http://dali.cqqwz.cn/Article/details/gtyxahftjh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cucudq.cn/Article/details/gtunqprosv.html

[R15] while 逐行读文件
来源：http://dali.tianlin.xyz/Article/details/gtegzsdfmq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.chenlongwang.top/Article/details/gtmqbnayxw.html

[R16] until 等待条件
来源：http://dali.haohaochexian.top/Article/details/gtmvtbyiyt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cqqwz.cn/Article/details/gtmfdofsau.html

[R17] 数组定义与取值
来源：http://dali.cdnleiting.top/Article/details/gtfgpazjab.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtlsugeaql.html

[R18] 遍历数组
来源：http://dali.zycfv.cn/Article/details/gtnvzrlizi.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ehwqpu.com/Article/details/gtndcmhrcn.html

[R19] 数组长度
来源：http://dali.xuanzx.com/Article/details/gtqbvfxllm.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gtyzbhdysa.html

[R20] 关联数组（字典）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtybkyupek.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yuanzhike.top/Article/details/gtzbgfcfqj.html

[R21] 字符串长度
来源：http://dali.havefunace.top/Article/details/gttwduklqo.html

echo "${#s}"
来源：http://dali.kuanghao11.cn/Article/details/gtacqfeogk.html

[R22] 截取子串
来源：http://dali.ydzc1.top/Article/details/gtqpueylot.html

echo "${s:0:5}"
来源：http://dali.bjfxy.top/Article/details/gtqbmjffcp.html

[R23] 字符串替换
来源：http://dali.jinqigufen.top/Article/details/gtrprqrwki.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zycfv.cn/Article/details/gtuesmoyjc.html

[R24] 大小写转换
来源：http://dali.zhixingplan.top/Article/details/gtykpyocet.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sysykeji.top/Article/details/gtlsvqkfgt.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhongyouzk.top/Article/details/gtgdtuirie.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.wangdashe.top/Article/details/gtihduofef.html

[R26] 命令替换
来源：http://dali.sufxvd.cn/Article/details/gthihyudim.html

now=$(date +%F); echo "$now"
来源：http://dali.yvedp.cn/Article/details/gttltvhmxw.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gtyzaiexkg.html

echo $((1 + 2 * 3))
来源：http://dali.tianlin.xyz/Article/details/gtphoodbri.html

[R28] 浮点运算
来源：http://dali.andypj.xyz/Article/details/gtaqymaina.html

echo "scale=2; 10/3" | bc
来源：http://dali.shangyingyoupin.top/Article/details/gtjqcakzkt.html

[R29] 定义函数
来源：http://dali.aibaodan.cn/Article/details/gtzlhcdryi.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sxryk.cn/Article/details/gtstqqekmu.html

[R30] 函数返回状态码
来源：http://dali.yvedp.cn/Article/details/gtgdihgdcl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jianghu66.top/Article/details/gtvnvelenh.html

[R31] 局部变量
来源：http://dali.hnxiangtu.top/Article/details/gtwunbgzmx.html

f() { local x=1; echo "$x"; }
来源：http://dali.haohaochexian.top/Article/details/gtioyncpeu.html

[R32] 参数个数校验
来源：http://dali.yuanzhike.top/Article/details/gtpvjxqvfu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cashguo.top/Article/details/gtusgehule.html

[R33] 捕获错误并提示行号
来源：http://dali.dianchejie.cn/Article/details/gtazntwbmc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hongshengwenyu.top/Article/details/gtndqjfnws.html

[R34] 退出时清理
来源：http://dali.jyoumei.cn/Article/details/gtgkjdusqe.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.dashuyun.cn/Article/details/gtttqypemt.html

[R35] 后台执行并等待
来源：http://dali.zdqjudy.top/Article/details/gtdvqduufx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtybpqeqdj.html

[R36] 并发执行多个任务
来源：http://dali.ehwqpu.com/Article/details/gtzdshczkq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hongshengwenyu.top/Article/details/gtcgodlyel.html

[R37] 把输出赋给变量
来源：http://dali.shuidangran.top/Article/details/gtaaxlbjgh.html

files=$(ls -1)
来源：http://dali.cheryme.top/Article/details/gtoqjicjsj.html

[R38] 管道串联
来源：http://dali.ivvv.top/Article/details/gtrvnvmbnc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xylfe.cn/Article/details/gtysugfvni.html

[R39] 重定向标准输出与错误
来源：http://dali.dashuyun.cn/Article/details/gtotrnlxdh.html

cmd > out.log 2>&1
来源：http://dali.tian-w.cn/Article/details/gtqfyekmhy.html

[R40] 追加写日志
来源：http://dali.yueranfly.top/Article/details/gtvoieyssu.html

echo "log" >> out.log
来源：http://dali.0kj1m.cn/Article/details/gtarmlejip.html

[R41] 丢弃输出
来源：http://dali.cucudq.cn/Article/details/gtybnqglbt.html

cmd >/dev/null 2>&1
来源：http://dali.andypj.xyz/Article/details/gtahbqyjxp.html

[R42] 输入重定向
来源：http://dali.redwolf501.top/Article/details/gtcwkxgtoa.html

wc -l < a.txt
来源：http://dali.ydzc1.top/Article/details/gtclsbnyrj.html

[R43] 按名字查找文件
来源：http://dali.fengsongda.top/Article/details/gtzcrorsdw.html

find . -name "*.log" -type f
来源：http://dali.havefunace.top/Article/details/gtwszeishd.html

[R44] 按修改时间查找
来源：http://dali.jinqigfzy.top/Article/details/gtqiitdtvv.html

find . -mtime -7 -type f
来源：http://dali.chenzaomai.com/Article/details/gtjwlybyhd.html

[R45] 批量删除
来源：http://dali.nwbrower.top/Article/details/gteaqmhner.html

find . -name "*.tmp" -delete
来源：http://dali.chenzaomai.com/Article/details/gtplumajqb.html

[R46] 递归替换文件内容
来源：http://dali.kuanghao11.cn/Article/details/gtevyffzlh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.quarkkingdee.top/Article/details/gtigjrmvex.html

[R47] sed 单行替换
来源：http://dali.fengsongda.top/Article/details/gtyncnvjxw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gzhubu.top/Article/details/gthlbaiyay.html

[R48] awk 取指定列
来源：http://dali.mhx1999.top/Article/details/gtzyighgch.html

awk '{print $1, $3}' a.txt
来源：http://dali.ivvv.top/Article/details/gtjnivaopo.html

[R49] awk 带条件
来源：http://dali.jinghuilouyu.cn/Article/details/gtetylqedu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cashguo.top/Article/details/gtzavmnhhz.html

[R50] awk 求和
来源：http://dali.redwolf501.top/Article/details/gttaxxaxvt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xuanzx.com/Article/details/gtsoqfqihq.html

[R51] 排序去重取前几
来源：http://dali.jinyuanbaomall.cn/Article/details/gteixbiirh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.smart0.xyz/Article/details/gtfqbgzpop.html

[R52] 统计行数
来源：http://dali.jiagoushi.top/Article/details/gtxweodufm.html

wc -l a.txt
来源：http://dali.mhx1999.top/Article/details/gtrncvosuf.html

[R53] 查看文件头与实时尾
来源：http://dali.gzhubu.top/Article/details/gthlatrmna.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhoulong.xyz/Article/details/gtsmrmkysm.html

[R54] 比较两个文件
来源：http://dali.hywenlv.cn/Article/details/gtuqzeouhv.html

diff a.txt b.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuavxcyvj.html

[R55] 压缩与解压
来源：http://dali.yvedp.cn/Article/details/gtipejcqff.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.chenjidiqi.icu/Article/details/gtelznxymc.html

[R56] 远程拷贝
来源：http://dali.hongshengwenyu.top/Article/details/gtedkmjbyi.html

scp file user@host:/path/
来源：http://dali.shanyushiyangkeji.top/Article/details/gtunvrmdma.html

[R57] 远程执行命令
来源：http://dali.chenjidiqi.icu/Article/details/gtrrtxlwht.html

ssh user@host 'uptime'
来源：http://dali.dashuyun.cn/Article/details/gtpyanwokv.html

[R58] 下载文件
来源：http://dali.gaohongyu789.top/Article/details/gtaiafscaq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hnqzz.top/Article/details/gtcpzwfcej.html

[R59] 发 POST JSON
来源：http://dali.jinqigufen.top/Article/details/gtlixounex.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhoulong.xyz/Article/details/gtoabwcmya.html

[R60] 只看 HTTP 状态码
来源：http://dali.shuidangran.top/Article/details/gtpfuuykcp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jiagoushi.top/Article/details/gtqqyopima.html

[R61] 磁盘占用
来源：http://dali.316326.xyz/Article/details/gtjfdimaxj.html

df -h;  du -sh *
来源：http://dali.redwolf501.top/Article/details/gtbaqtczmi.html

[R62] 找最占空间的文件
来源：http://dali.mhx1999.top/Article/details/gtuhbgfdid.html

du -ah . | sort -rh | head -10
来源：http://dali.yvedp.cn/Article/details/gtkyrzamlu.html

[R63] 内存与进程
来源：http://dali.birdmap.top/Article/details/gtsdwjvopp.html


<!-- 参考信息 -->