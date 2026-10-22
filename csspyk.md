代发 wailian999

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hfpthk.cn/Article/details/gtdigrmzfy.html

[Q20] IN 列表
来源：http://dali.fzhhl.top/Article/details/gturqkviac.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.meibo888.top/Article/details/gthrhydbey.html

[Q21] 空值判断
来源：http://dali.nanxinkj.top/Article/details/gtcgiodbdl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jianghu66.top/Article/details/gtmntjeoks.html

[Q22] 排序
来源：http://dali.316326.xyz/Article/details/gththhnebt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xylfe.cn/Article/details/gtupqtozlf.html

[Q23] 分页
来源：http://dali.wangdashe.top/Article/details/gtbdmtllae.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yuxming.cn/Article/details/gtzzzvkink.html

[Q24] 去重
来源：http://dali.tanke756.top/Article/details/gtcultaysu.html

SELECT DISTINCT city FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtyvflpnjy.html

[Q25] 只取前 N 条
来源：http://dali.zhiwuduotai.top/Article/details/gtunjeiucy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.redwolf501.top/Article/details/gtrwrhrtgz.html

[Q26] 计数
来源：http://dali.iojbl.cn/Article/details/gthkfsouva.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtndfyorod.html

[Q27] 条件计数
来源：http://dali.aizwys.cn/Article/details/gtbumfodsg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtwecvvpsk.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gtiuustqre.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yongpay.top/Article/details/gtzjwcyxix.html

[Q29] 最大最小值
来源：http://dali.dashuyun.cn/Article/details/gtbqpoajyo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtcxmrwocv.html

[Q30] 分组统计
来源：http://dali.xuanzx.com/Article/details/gtcafftnmn.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yonumen.top/Article/details/gtrvigoamb.html

[Q31] 分组后过滤
来源：http://dali.c1oappe.top/Article/details/gtzntcfkep.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.wangdashe.top/Article/details/gtvuagqipg.html

[Q32] 分组拼接字符串
来源：http://dali.yangfankeji.com/Article/details/gtwhrnpaag.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.guannengcc.top/Article/details/gtrngxjhdd.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.pycfn.com/Article/details/gtdlzqiolm.html

[Q33] 多列分组
来源：http://dali.cucudq.cn/Article/details/gtutheovvt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.haohaochexian.top/Article/details/gtluqyhmie.html

[Q34] 每组取第一条
来源：http://dali.birdmap.top/Article/details/gtpcnmphcm.html

SELECT * FROM (
来源：http://dali.yj202588.top/Article/details/gtvrwdpdxc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.daria6918.cn/Article/details/gtvrxoeyvl.html

) t WHERE rn = 1;
来源：http://dali.yj20258888.top/Article/details/gtxeproqnm.html

[Q35] 内连接
来源：http://dali.chenzaomai.com/Article/details/gtrojyrhag.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shzxlz.cn/Article/details/gtayrrksag.html

[Q36] 左连接
来源：http://dali.xuetiantiany.cn/Article/details/gtcfdhpcyv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaflwiuoc.html

[Q37] 右连接
来源：http://dali.jianghu66.top/Article/details/gtqgnxagdd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cucudq.cn/Article/details/gtwpkwcpka.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sufxvd.cn/Article/details/gtdifyjcsv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gaohongyu789.top/Article/details/gtppvzniwc.html

[Q39] 自连接（查上下级）
来源：http://dali.cheryme.top/Article/details/gtkljbmpmo.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yuanzhike.top/Article/details/gtvgvqgyje.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.chenzaomai.com/Article/details/gtomlwmbxt.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ppjwa.cn/Article/details/gtjebbjdrp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sysykeji.top/Article/details/gtmzvsgbia.html

[Q41] 多表连接
来源：http://dali.shangyingyoupin.top/Article/details/gtshakqlhn.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbmwmfhrw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.andypj.xyz/Article/details/gteciybbxv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.fzhhl.top/Article/details/gtmasnzfmn.html

[Q42] 连接条件附加过滤
来源：http://dali.ppjwa.cn/Article/details/gthrmdukwe.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwokwnzoz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jqgfzy.top/Article/details/gtktmkblvv.html

[Q43] 标量子查询
来源：http://dali.chenlongwang.top/Article/details/gtbvozlqdd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.iojbl.cn/Article/details/gtapaohzlw.html

[Q44] IN 子查询
来源：http://dali.redwolf501.top/Article/details/gtlprdjkqj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xziqi.cn/Article/details/gtstxtrvra.html

[Q45] EXISTS 判断存在
来源：http://dali.xziqi.cn/Article/details/gtqexmhrto.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.snrcjt.cn/Article/details/gtalcpifnk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.daxiang520.top/Article/details/gtabgxqzth.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cucudq.cn/Article/details/gtsnzsooqa.html

[Q47] 与平均值比较
来源：http://dali.zhoulong.xyz/Article/details/gtgsrjsjdu.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yj202588.top/Article/details/gtdlikilhv.html

[Q48] CTE 公用表表达式
来源：http://dali.wangdashe.top/Article/details/gtnpgotmka.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.smart0.xyz/Article/details/gtkcugzodc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ybcxt.top/Article/details/gtavxwpwhp.html

[Q49] 更新单行
来源：http://dali.xuanzx.com/Article/details/gtlebgsdiy.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhiwuduotai.top/Article/details/gtoawrrxnc.html

[Q50] 批量更新
来源：http://dali.pycfn.com/Article/details/gthkehrtde.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shuidangran.top/Article/details/gtbgwmxngt.html

[Q51] 用子查询更新
来源：http://dali.ppjwa.cn/Article/details/gtbinuqkpy.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.aibaodan.cn/Article/details/gtwajxmxyk.html

[Q52] 删除指定行
来源：http://dali.wangshuangyany.cn/Article/details/gtxtjrkuqn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfwngvvgc.html

[Q53] 按条件删除
来源：http://dali.daxiang520.top/Article/details/gtiyeedned.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhongyouzk.top/Article/details/gtsrhpcpcj.html

[Q54] 清空表
来源：http://dali.chenzaomai.com/Article/details/gtpnvslctr.html

TRUNCATE TABLE logs;
来源：http://dali.feifeiyinyue.top/Article/details/gteuahnnse.html

[Q55] 排名（并列占位）
来源：http://dali.yj20258888.top/Article/details/gtvhajhago.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.316326.xyz/Article/details/gtaodglsvp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinghuilouyu.cn/Article/details/gtylvpfphi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shzxlz.cn/Article/details/gtclqpwhhb.html

[Q57] 行号
来源：http://dali.zhaomingkeji.xyz/Article/details/gtskfhrvwq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtllmvoxab.html

[Q58] 累计求和
来源：http://dali.shuidangran.top/Article/details/gtxtswzdjg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtngjraace.html

[Q59] 分组内累计
来源：http://dali.jlsjyb.cn/Article/details/gthgkxsewk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gtsnmxmxgx.html

[Q60] 取上一行 / 下一行
来源：http://dali.gaohongyu789.top/Article/details/gtakigxxmo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.smart0.xyz/Article/details/gtqsansyst.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtswhakooq.html

[Q61] 移动平均
来源：http://dali.yvedp.cn/Article/details/gtmimvkszj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtbrlfqhes.html

[Q62] 分组占比
来源：http://dali.feifeiyinyue.top/Article/details/gtdgmkmcbk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.feifeiyinyue.top/Article/details/gtttkdhocm.html

[Q63] 开启事务
来源：http://dali.yvedp.cn/Article/details/gtnznwmqzj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.sxryk.cn/Article/details/gtorwmyjos.html

[Q64] 提交事务
来源：http://dali.havefunace.top/Article/details/gtnsyvkxtb.html

COMMIT;
来源：http://dali.chenzaomai.com/Article/details/gtkhuwpnjm.html

[Q65] 回滚事务
来源：http://dali.zhengqikj.top/Article/details/gtyswlmnsz.html

ROLLBACK;
来源：http://dali.jinghuilouyu.cn/Article/details/gtquteedtk.html

[Q66] 行锁查询
来源：http://dali.zhoulong.xyz/Article/details/gtpldowfdq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ybcxt.top/Article/details/gtuyzcaigr.html

[Q67] 设置隔离级别
来源：http://dali.shanyushiyangtech.top/Article/details/gtsqkeujml.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ybcxt.top/Article/details/gttdlrymzo.html

[Q68] 保存点
来源：http://dali.cqqwz.cn/Article/details/gtbhxubqxx.html

SAVEPOINT sp1;
来源：http://dali.guannengcc.top/Article/details/gtpnhitjho.html

ROLLBACK TO sp1;
来源：http://dali.jinqigfzy.top/Article/details/gtjmctotsk.html

[Q69] 查看执行计划
来源：http://dali.chenjidiqi.icu/Article/details/gtwlavfnbh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.birdmap.top/Article/details/gtnyrvygmb.html

[Q70] 更新统计信息
来源：http://dali.mhx1999.top/Article/details/gtpsyicqek.html

ANALYZE TABLE users;
来源：http://dali.chenjidiqi.icu/Article/details/gtnvxaxzcp.html

[Q71] 查看建表语句
来源：http://dali.zhoulong.xyz/Article/details/gtspojcptp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.9152youxi.cn/Article/details/gtbpttjrhb.html

[Q72] 查看索引
来源：http://dali.nanxinkj.top/Article/details/gttacgeopo.html

SHOW INDEX FROM users;
来源：http://dali.chenzaomai.com/Article/details/gthatidkbq.html

[Q73] 查看表状态
来源：http://dali.c1oappe.top/Article/details/gttmgyzppo.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ehwqpu.com/Article/details/gtbivildea.html

[Q74] 强制使用索引
来源：http://dali.dashuyun.cn/Article/details/gtwdwbjwfc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.pycfn.com/Article/details/gtfsdadlcs.html

[Q75] 日期格式化
来源：http://dali.xuanzx.com/Article/details/gtpcwdlmek.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sweek.top/Article/details/gtbtsqnmmy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jqgufenzy.top/Article/details/gtwqhxdmxp.html

[Q76] 按天统计
来源：http://dali.fzhhl.top/Article/details/gtaxqvqaim.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jiagoushi.top/Article/details/gtswrnsoop.html

[Q77] 时间加减
来源：http://dali.chenjidiqi.icu/Article/details/gtzhmbbdxs.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.meibo888.top/Article/details/gtfkjbjcza.html

[Q78] 当前时间
来源：http://dali.jinqigufen.top/Article/details/gthcisgppm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.nanxuanxn.top/Article/details/gthjqeddkr.html

[Q79] 字符串拼接
来源：http://dali.ywan-chungtsiang.top/Article/details/gtstacdavm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sufxvd.cn/Article/details/gtbtvtgnnw.html

[Q80] 字符串截取
来源：http://dali.guowangkeji.top/Article/details/gttjrjceld.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.redwolf501.top/Article/details/gtsnrqxbpm.html

[Q81] 字符串替换
来源：http://dali.hongshengwenyu.top/Article/details/gtcbxvnbss.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.aizwys.cn/Article/details/gtwicslkce.html

[Q82] 字符长度与字节长度
来源：http://dali.jlsjyb.cn/Article/details/gtfaexdrcv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jianghu66.top/Article/details/gtpaqhayed.html

[Q83] 大小写转换
来源：http://dali.hysaishi.cn/Article/details/gtcmdqcdyq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtuepcyeke.html

[Q84] 去除首尾空格
来源：http://dali.shzxlz.cn/Article/details/gtyxgqbjry.html

SELECT TRIM(name) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtlobngbou.html

[Q85] 数值取整
来源：http://dali.mhx1999.top/Article/details/gtiegkdiit.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.wangshuangyany.cn/Article/details/gtsmpphgsw.html

[Q86] 读取 JSON 字段
来源：http://dali.c1oappe.top/Article/details/gtvapzpnax.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinqigufen.top/Article/details/gtpahktwjs.html

[Q87] JSON 字段做条件
来源：http://dali.birdmap.top/Article/details/gtektikthq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ppjwa.cn/Article/details/gtghikhawb.html

[Q88] 行转列（条件聚合）
来源：http://dali.bjfxy.top/Article/details/gtiyqiltvl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.nwbrower.top/Article/details/gtldduoynv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jianghu66.top/Article/details/gtonoosstn.html

[Q89] 判断表是否存在
来源：http://dali.bjfxy.top/Article/details/gtmsjeiois.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.dianchejie.cn/Article/details/gtvgvrikvd.html

[Q90] 生成序号列
来源：http://dali.iojbl.cn/Article/details/gtfvwoxeai.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cheryme.top/Article/details/gtemovilen.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtqxoukcec.html

R. Bash 专题
来源：http://dali.chenjidiqi.icu/Article/details/gtaxwsgcke.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtxdnmgjzv.html

[R01] shebang 与严格模式
来源：http://dali.hnqzz.top/Article/details/gtwwqgjzpc.html

#!/usr/bin/env bash
来源：http://dali.gotoacloud.top/Article/details/gtypawhsms.html

set -euo pipefail
来源：http://dali.yuanzhike.top/Article/details/gtfumniiyd.html

[R02] 变量赋值与使用
来源：http://dali.haohaochexian.top/Article/details/gtfjhsvnda.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gtxunmsqgf.html

[R03] 只读变量
来源：http://dali.jianghu66.top/Article/details/gttjihwuma.html

readonly PI=3.14
来源：http://dali.ppjwa.cn/Article/details/gtajfyuxcm.html

[R04] 位置参数
来源：http://dali.ehwqpu.com/Article/details/gtrnagcqnq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shuidangran.top/Article/details/gtoioffvrs.html

[R05] 参数默认值
来源：http://dali.daria6918.cn/Article/details/gttjlagtdh.html

name="${1:-default}"
来源：http://dali.chenlongwang.top/Article/details/gtqivbztwv.html

[R06] 判断命令是否存在
来源：http://dali.smart0.xyz/Article/details/gtucoqgvnp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.haohaochexian.top/Article/details/gtmhnroqxq.html

[R07] if 判断文件
来源：http://dali.316326.xyz/Article/details/gtpnqpdcuz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yj20258888.top/Article/details/gtyukthjco.html

[R08] 数值比较
来源：http://dali.smart0.xyz/Article/details/gtbxreuini.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shangyingyoupin.top/Article/details/gtzoukutmn.html

[R09] 字符串比较
来源：http://dali.guowangkeji.top/Article/details/gtyoihzqog.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.fengsongda.top/Article/details/gtbziybzhz.html

[R10] 正则匹配
来源：http://dali.316326.xyz/Article/details/gtkusbabbh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.birdmap.top/Article/details/gthpobydve.html

[R11] case 多分支
来源：http://dali.nanxuanxn.top/Article/details/gtaqmiqrdf.html

case "$1" in
来源：http://dali.ehwqpu.com/Article/details/gtxfwsfrur.html

start) echo "启动" ;;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiyvzvwkh.html

stop)  echo "停止" ;;
来源：http://dali.hnqzz.top/Article/details/gtvdusampf.html

*)     echo "未知命令" ;;
来源：http://dali.gogol.net.cn/Article/details/gthgrbilsu.html

esac
来源：http://dali.yongpay.top/Article/details/gtciaauewe.html

[R12] for 遍历文件
来源：http://dali.sweek.top/Article/details/gtwqztgzdm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtvdjeyglc.html

[R13] for 计数循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmqumouky.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtywmqxwkf.html

[R14] C 风格 for
来源：http://dali.yanxiufei.cn/Article/details/gtgpmdnzfx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.andypj.xyz/Article/details/gtjobqbutg.html

[R15] while 逐行读文件
来源：http://dali.ivvv.top/Article/details/gtypvhgovu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtlxahdczk.html

[R16] until 等待条件
来源：http://dali.zycfv.cn/Article/details/gtifagvscn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvrbiriyy.html

[R17] 数组定义与取值
来源：http://dali.hammf.cn/Article/details/gtheavffaq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.pycfn.com/Article/details/gtxhrhhccr.html

[R18] 遍历数组
来源：http://dali.tian-w.cn/Article/details/gtdbmaazqs.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.c1oappe.top/Article/details/gtbneoumtd.html

[R19] 数组长度
来源：http://dali.nanxuanxn.top/Article/details/gtvpmhcrvg.html

echo "${#arr[@]}"
来源：http://dali.dianchejie.cn/Article/details/gtdzgochrt.html

[R20] 关联数组（字典）
来源：http://dali.9152youxi.cn/Article/details/gthqalxxnj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sysykeji.top/Article/details/gtdfuszhuy.html

[R21] 字符串长度
来源：http://dali.jyoumei.cn/Article/details/gtnojkgybn.html

echo "${#s}"
来源：http://dali.xinyue.icu/Article/details/gtjhdtdqbi.html

[R22] 截取子串
来源：http://dali.guannengcc.top/Article/details/gtptdbqrpt.html

echo "${s:0:5}"
来源：http://dali.yj20258888.top/Article/details/gtzopafliv.html

[R23] 字符串替换
来源：http://dali.daxiang520.top/Article/details/gtvjcjropv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xziqi.cn/Article/details/gtzrkqopua.html

[R24] 大小写转换
来源：http://dali.jinqigufen.top/Article/details/gtaiqnztfj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.quarkkingdee.top/Article/details/gtizgejkqq.html

[R25] 去后缀 / 去前缀
来源：http://dali.jqgufenzy.top/Article/details/gtrvqheqwf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shzxlz.cn/Article/details/gtkgrwklnp.html

[R26] 命令替换
来源：http://dali.gogol.net.cn/Article/details/gtungnyidt.html

now=$(date +%F); echo "$now"
来源：http://dali.kuanghao11.cn/Article/details/gtjojkrldn.html

[R27] 算术展开
来源：http://dali.zdqjudy.top/Article/details/gtjhkvzjzy.html

echo $((1 + 2 * 3))
来源：http://dali.yanxiufei.cn/Article/details/gtphagsnkz.html

[R28] 浮点运算
来源：http://dali.jiagoushi.top/Article/details/gtszalyetd.html

echo "scale=2; 10/3" | bc
来源：http://dali.chenzaomai.com/Article/details/gtnavzllvv.html

[R29] 定义函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoeaiccvf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.tanke756.top/Article/details/gtorzheivq.html

[R30] 函数返回状态码
来源：http://dali.9152youxi.cn/Article/details/gtsswbfuiq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tian-w.cn/Article/details/gtklfuyifm.html

[R31] 局部变量
来源：http://dali.zhoulong.xyz/Article/details/gtlkogjdva.html

f() { local x=1; echo "$x"; }
来源：http://dali.yangfankeji.com/Article/details/gtwyszrznb.html

[R32] 参数个数校验
来源：http://dali.pycfn.com/Article/details/gtvzmofneo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jyoumei.cn/Article/details/gtejmdyago.html

[R33] 捕获错误并提示行号
来源：http://dali.shanyushiyangkeji.top/Article/details/gttkoniolg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.mhx1999.top/Article/details/gtmcumhqlm.html

[R34] 退出时清理
来源：http://dali.wangshuangyany.cn/Article/details/gturlxmjmh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zdqjudy.top/Article/details/gtodkajzna.html

[R35] 后台执行并等待
来源：http://dali.cashguo.top/Article/details/gtgqrmwbtq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.dianchejie.cn/Article/details/gtxgcvlqav.html

[R36] 并发执行多个任务
来源：http://dali.gzhubu.top/Article/details/gtwnrjgltc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hnqzz.top/Article/details/gtdyfndwwh.html

[R37] 把输出赋给变量
来源：http://dali.ehwqpu.com/Article/details/gticnepenv.html

files=$(ls -1)
来源：http://dali.hammf.cn/Article/details/gtdvnlsinv.html

[R38] 管道串联
来源：http://dali.jinqigufen.top/Article/details/gtrlinjgbu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.daria6918.cn/Article/details/gtrekimevd.html

[R39] 重定向标准输出与错误
来源：http://dali.jianghu66.top/Article/details/gtgcxdpjnf.html

cmd > out.log 2>&1
来源：http://dali.jlsjyb.cn/Article/details/gteybntjlm.html

[R40] 追加写日志
来源：http://dali.zycfv.cn/Article/details/gtrfotxyht.html

echo "log" >> out.log
来源：http://dali.shangyingyoupin.top/Article/details/gtbtnkcgxa.html

[R41] 丢弃输出
来源：http://dali.yonumen.top/Article/details/gtguzlrnbg.html

cmd >/dev/null 2>&1
来源：http://dali.ybcxt.top/Article/details/gtxihmzsgs.html

[R42] 输入重定向
来源：http://dali.yueranfly.top/Article/details/gtvhdgojxo.html

wc -l < a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtndxeuuua.html

[R43] 按名字查找文件
来源：http://dali.c1oappe.top/Article/details/gtmimjdogm.html

find . -name "*.log" -type f
来源：http://dali.jianghu66.top/Article/details/gtmubnahoh.html

[R44] 按修改时间查找
来源：http://dali.hnxiangtu.top/Article/details/gtuknrmshy.html

find . -mtime -7 -type f
来源：http://dali.hysaishi.cn/Article/details/gtpzhmuppo.html

[R45] 批量删除
来源：http://dali.chenzaomai.com/Article/details/gtfgnvizyv.html

find . -name "*.tmp" -delete
来源：http://dali.yvedp.cn/Article/details/gtduemibjn.html

[R46] 递归替换文件内容
来源：http://dali.pengpengdd.cyou/Article/details/gtjonatxzk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cashguo.top/Article/details/gtsbthmbzo.html

[R47] sed 单行替换
来源：http://dali.xuanzx.com/Article/details/gtsiaingrk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.fengsongda.top/Article/details/gtwxfcvkoe.html

[R48] awk 取指定列
来源：http://dali.shzxlz.cn/Article/details/gtfpczhoqn.html

awk '{print $1, $3}' a.txt
来源：http://dali.cdnleiting.top/Article/details/gtuactfkny.html

[R49] awk 带条件
来源：http://dali.mhx1999.top/Article/details/gtalfiswbx.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.wangshuangyany.cn/Article/details/gtfrcnppym.html

[R50] awk 求和
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxrowqmfj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.birdmap.top/Article/details/gtytevvsum.html

[R51] 排序去重取前几
来源：http://dali.xuetiantiany.cn/Article/details/gtjlghzyux.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ehwqpu.com/Article/details/gtekvchokn.html

[R52] 统计行数
来源：http://dali.yuanzhike.top/Article/details/gtvenlphyw.html

wc -l a.txt
来源：http://dali.tian-w.cn/Article/details/gttojjxumj.html

[R53] 查看文件头与实时尾
来源：http://dali.zhiwuduotai.top/Article/details/gtdxqngfdu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ydzc1.top/Article/details/gtobxskcnu.html

[R54] 比较两个文件
来源：http://dali.hfpthk.cn/Article/details/gtzveukvbd.html

diff a.txt b.txt
来源：http://dali.xuanzx.com/Article/details/gtwhuswcwg.html

[R55] 压缩与解压
来源：http://dali.xuetiantiany.cn/Article/details/gtusagtwur.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.tian-w.cn/Article/details/gtclekdnqt.html

[R56] 远程拷贝
来源：http://dali.hnxiangtu.top/Article/details/gtuqdttdeg.html

scp file user@host:/path/
来源：http://dali.chenzaomai.com/Article/details/gtkyiovpgd.html

[R57] 远程执行命令
来源：http://dali.aizwys.cn/Article/details/gtiizpinae.html

ssh user@host 'uptime'
来源：http://dali.shzxlz.cn/Article/details/gtlmeptrit.html

[R58] 下载文件
来源：http://dali.hnxiangtu.top/Article/details/gtbkkinzng.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sweek.top/Article/details/gthhuerlue.html

[R59] 发 POST JSON
来源：http://dali.pycfn.com/Article/details/gtenwkpcoo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.fzhhl.top/Article/details/gtqhawpnoo.html

[R60] 只看 HTTP 状态码
来源：http://dali.cheryme.top/Article/details/gthvlwwwmf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ivvv.top/Article/details/gtfvjimhjv.html

[R61] 磁盘占用
来源：http://dali.9152youxi.cn/Article/details/gtgwmufqdd.html

df -h;  du -sh *
来源：http://dali.mhx1999.top/Article/details/gtaaescuhj.html

[R62] 找最占空间的文件
来源：http://dali.yanxiufei.cn/Article/details/gtgxhtkpxn.html

du -ah . | sort -rh | head -10
来源：http://dali.aibaodan.cn/Article/details/gtezqnywhq.html

[R63] 内存与进程
来源：http://dali.tanke756.top/Article/details/gthgdodrqu.html

free -h;  ps aux | grep nginx
来源：http://dali.jqgfzy.top/Article/details/gtpjecnnek.html

[R64] 结束进程
来源：http://dali.yonumen.top/Article/details/gtdfpvurju.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yongpay.top/Article/details/gtwvlnulod.html

[R65] 查看端口占用
来源：http://dali.gzhubu.top/Article/details/gtpbqaucki.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sxryk.cn/Article/details/gthszjsgvr.html

[R66] 定时任务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjzwwahky.html

crontab -e;  crontab -l
来源：http://dali.yuanzhike.top/Article/details/gtbpfurmyo.html

[R67] 生成随机十六进制串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuauixaln.html

openssl rand -hex 16
来源：http://dali.pycfn.com/Article/details/gtcgbnveyp.html

[R68] 计算文件校验值
来源：http://dali.jlsjyb.cn/Article/details/gtrrgazlpk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.meibo888.top/Article/details/gtofvqtbvb.html

[R69] 生成随机密码
来源：http://dali.guannengcc.top/Article/details/gtpxtcxxna.html


<!-- 参考信息 -->