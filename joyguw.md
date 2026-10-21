代发 wailian999

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xylfe.cn/Article/details/gtbyrixxrc.html

[Q18] 模糊匹配
来源：http://dali.fengsongda.top/Article/details/gtriphwbcz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.gotoacloud.top/Article/details/gtzmbllgtl.html

[Q19] 范围查询
来源：http://dali.jinqigfzy.top/Article/details/gtwdcxjpwe.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtudbbfmgj.html

[Q20] IN 列表
来源：http://dali.gzhubu.top/Article/details/gtpklbklpc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yangfankeji.com/Article/details/gtfselwkam.html

[Q21] 空值判断
来源：http://dali.shuidangran.top/Article/details/gtdlsjojuy.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hysaishi.cn/Article/details/gtlikgmhvl.html

[Q22] 排序
来源：http://dali.jqgufenzy.top/Article/details/gtjnebhtbk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.daria6918.cn/Article/details/gtogksfuzx.html

[Q23] 分页
来源：http://dali.meibo888.top/Article/details/gthpbolllh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hongshengwenyu.top/Article/details/gtbyluckpr.html

[Q24] 去重
来源：http://dali.dashuyun.cn/Article/details/gtzcrbhzhk.html

SELECT DISTINCT city FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtoftxongr.html

[Q25] 只取前 N 条
来源：http://dali.ydzc1.top/Article/details/gtgifgejvx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.kuanghao11.cn/Article/details/gtnruhapcf.html

[Q26] 计数
来源：http://dali.havefunace.top/Article/details/gtypmjlbwy.html

SELECT COUNT(*) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gthfgnwjhn.html

[Q27] 条件计数
来源：http://dali.meibo888.top/Article/details/gtmuajkwmq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yj202588.top/Article/details/gtvlxwpvmv.html

[Q28] 求和与平均
来源：http://dali.ywan-chungtsiang.top/Article/details/gtimfwmckm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gtwledlpdb.html

[Q29] 最大最小值
来源：http://dali.snrcjt.cn/Article/details/gttcadaqdc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtqsqhassj.html

[Q30] 分组统计
来源：http://dali.vqdsnc.cn/Article/details/gtnqdimmog.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzfvcxiqo.html

[Q31] 分组后过滤
来源：http://dali.wangshuangyany.cn/Article/details/gtyckuellh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtijvtqgkk.html

[Q32] 分组拼接字符串
来源：http://dali.zhongyouzk.top/Article/details/gtyqzfudzw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jlsjyb.cn/Article/details/gtzrtrmupg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hnxiangtu.top/Article/details/gtniqphxtm.html

[Q33] 多列分组
来源：http://dali.sweek.top/Article/details/gtkqdtpehj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.guowangkeji.top/Article/details/gtzrpcgqdt.html

[Q34] 每组取第一条
来源：http://dali.iojbl.cn/Article/details/gtculoinzd.html

SELECT * FROM (
来源：http://dali.yuanzhike.top/Article/details/gtpavxouve.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.dianchejie.cn/Article/details/gtyvrojmoh.html

) t WHERE rn = 1;
来源：http://dali.shuidangran.top/Article/details/gtupynxcjo.html

[Q35] 内连接
来源：http://dali.316326.xyz/Article/details/gtjakmkpsi.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.dashuyun.cn/Article/details/gtntrwcycv.html

[Q36] 左连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcdklzsoi.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cucudq.cn/Article/details/gtlcosfsax.html

[Q37] 右连接
来源：http://dali.sufxvd.cn/Article/details/gtqdpkgbsg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yuanzhike.top/Article/details/gtlsoifaqt.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.iojbl.cn/Article/details/gthygcoorz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.sxryk.cn/Article/details/gtoxfgbunl.html

[Q39] 自连接（查上下级）
来源：http://dali.gotoacloud.top/Article/details/gtehvmeoua.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cheryme.top/Article/details/gtgzsnrngg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xuanzx.com/Article/details/gtrwpajson.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ehwqpu.com/Article/details/gthqodxfie.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.meibo888.top/Article/details/gttfdinxlu.html

[Q41] 多表连接
来源：http://dali.pengpengdd.cyou/Article/details/gtcajokuxx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shuidangran.top/Article/details/gtjhvssjpk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yueranfly.top/Article/details/gtqlicfzwi.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.9152youxi.cn/Article/details/gtgusjlidl.html

[Q42] 连接条件附加过滤
来源：http://dali.chenjidiqi.icu/Article/details/gtivgjnsmr.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhixingplan.top/Article/details/gtdxqqjqvy.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zycfv.cn/Article/details/gtcnmudziw.html

[Q43] 标量子查询
来源：http://dali.cucudq.cn/Article/details/gtojwcymbj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyikqkqus.html

[Q44] IN 子查询
来源：http://dali.ybcxt.top/Article/details/gtsvpoulhr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jiagoushi.top/Article/details/gtwrozczsb.html

[Q45] EXISTS 判断存在
来源：http://dali.pycfn.com/Article/details/gtodpnqtqp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenzaomai.com/Article/details/gtiyczvduw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpcdjduqj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.guowangkeji.top/Article/details/gtmgycruaq.html

[Q47] 与平均值比较
来源：http://dali.shuidangran.top/Article/details/gtpzrtuuhl.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.tian-w.cn/Article/details/gtocbjrlbv.html

[Q48] CTE 公用表表达式
来源：http://dali.jinqigufen.top/Article/details/gtohltwgkk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cqqwz.cn/Article/details/gtbxgeusni.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yuanzhike.top/Article/details/gtmrbnqojb.html

[Q49] 更新单行
来源：http://dali.daria6918.cn/Article/details/gtbsffcpwy.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hnqzz.top/Article/details/gtrygodwnb.html

[Q50] 批量更新
来源：http://dali.xuetiantiany.cn/Article/details/gtyexnqztk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zdqjudy.top/Article/details/gtnijiwldx.html

[Q51] 用子查询更新
来源：http://dali.hongshengwenyu.top/Article/details/gtiwhvqnps.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.nanxinkj.top/Article/details/gthjtdywpg.html

[Q52] 删除指定行
来源：http://dali.jinqigfzy.top/Article/details/gtwuwvqrzy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yj20258.top/Article/details/gtidoiylbw.html

[Q53] 按条件删除
来源：http://dali.jqgfzy.top/Article/details/gtlkbgqwwq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinghuilouyu.cn/Article/details/gtapcmnpop.html

[Q54] 清空表
来源：http://dali.yuxming.cn/Article/details/gtdqeoekgy.html

TRUNCATE TABLE logs;
来源：http://dali.jinghuilouyu.cn/Article/details/gtliscfdzo.html

[Q55] 排名（并列占位）
来源：http://dali.guannengcc.top/Article/details/gtcfuypdta.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.pycfn.com/Article/details/gtlxuabjyq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shanyushiyangtech.top/Article/details/gtjfvmoqaj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xuanzx.com/Article/details/gtacvgjukd.html

[Q57] 行号
来源：http://dali.svipenyu.cn/Article/details/gtlsniovor.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtvrhlbuuw.html

[Q58] 累计求和
来源：http://dali.iojbl.cn/Article/details/gtrypcamcf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gtddwijpbn.html

[Q59] 分组内累计
来源：http://dali.yj20258.top/Article/details/gtoqksritz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gtdmoyosig.html

[Q60] 取上一行 / 下一行
来源：http://dali.yueranfly.top/Article/details/gthfjrecmb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shanyushiyangtech.top/Article/details/gtpcefdqis.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtntakysxu.html

[Q61] 移动平均
来源：http://dali.meibo888.top/Article/details/gtufmzjbag.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cashguo.top/Article/details/gtdqlwmfpk.html

[Q62] 分组占比
来源：http://dali.havefunace.top/Article/details/gtgtkfjffi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cheryme.top/Article/details/gtgwdsvcdc.html

[Q63] 开启事务
来源：http://dali.yonumen.top/Article/details/gtbmnzsdbo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cdnleiting.top/Article/details/gtlzdkgzrg.html

[Q64] 提交事务
来源：http://dali.yueranfly.top/Article/details/gtjwmwwzvu.html

COMMIT;
来源：http://dali.gaohongyu789.top/Article/details/gtqpisitzm.html

[Q65] 回滚事务
来源：http://dali.kuanghao11.cn/Article/details/gtmfuepert.html

ROLLBACK;
来源：http://dali.sxryk.cn/Article/details/gthflaaxej.html

[Q66] 行锁查询
来源：http://dali.cdnleiting.top/Article/details/gtltrspbiy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.chenjidiqi.icu/Article/details/gtaksohmdf.html

[Q67] 设置隔离级别
来源：http://dali.yangfankeji.com/Article/details/gtcigwawjy.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.gogol.net.cn/Article/details/gtropgsefe.html

[Q68] 保存点
来源：http://dali.sweek.top/Article/details/gtptacttqt.html

SAVEPOINT sp1;
来源：http://dali.zdqjudy.top/Article/details/gtuynnekee.html

ROLLBACK TO sp1;
来源：http://dali.fengsongda.top/Article/details/gtlxfhbuyf.html

[Q69] 查看执行计划
来源：http://dali.feifeiyinyue.top/Article/details/gtkcbzcoxg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.tanke756.top/Article/details/gtmqakfpqw.html

[Q70] 更新统计信息
来源：http://dali.xuanzx.com/Article/details/gtagtqwlsa.html

ANALYZE TABLE users;
来源：http://dali.yj20258888.top/Article/details/gthsnzfoix.html

[Q71] 查看建表语句
来源：http://dali.yj202588.top/Article/details/gtsraynumt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.meibo888.top/Article/details/gtihsftalf.html

[Q72] 查看索引
来源：http://dali.cdnleiting.top/Article/details/gtzymhzkzs.html

SHOW INDEX FROM users;
来源：http://dali.gzhubu.top/Article/details/gttpnuxinq.html

[Q73] 查看表状态
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrhualqvw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jlsjyb.cn/Article/details/gtkymxpxxn.html

[Q74] 强制使用索引
来源：http://dali.cdnleiting.top/Article/details/gtkgakiqkn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yj20258888.top/Article/details/gtjtirgdmf.html

[Q75] 日期格式化
来源：http://dali.zdqjudy.top/Article/details/gtvtuhyaof.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gttdfdexby.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.meibo888.top/Article/details/gtbqcrmkyd.html

[Q76] 按天统计
来源：http://dali.wangdashe.top/Article/details/gttlsnhcou.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shangyingyoupin.top/Article/details/gtaqkbeglb.html

[Q77] 时间加减
来源：http://dali.hfpthk.cn/Article/details/gtjlrfidgn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hammf.cn/Article/details/gtzffmsxar.html

[Q78] 当前时间
来源：http://dali.zdqjudy.top/Article/details/gttszfnbbr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.chenzaomai.com/Article/details/gtgobpfgsv.html

[Q79] 字符串拼接
来源：http://dali.zycfv.cn/Article/details/gtqkkchqcc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.nanxuanxn.top/Article/details/gtbhbqwjrk.html

[Q80] 字符串截取
来源：http://dali.zycfv.cn/Article/details/gtrbedmvxt.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtmxtpgdnd.html

[Q81] 字符串替换
来源：http://dali.c1oappe.top/Article/details/gtbosgzbze.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cashguo.top/Article/details/gtrjqksrhq.html

[Q82] 字符长度与字节长度
来源：http://dali.gaohongyu789.top/Article/details/gtzqbpyoql.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtvjobhzvv.html

[Q83] 大小写转换
来源：http://dali.guannengcc.top/Article/details/gtpsjkwzas.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtnhdbtwrc.html

[Q84] 去除首尾空格
来源：http://dali.svipenyu.cn/Article/details/gtnxonrwqk.html

SELECT TRIM(name) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gttyukuict.html

[Q85] 数值取整
来源：http://dali.tanke756.top/Article/details/gthfzjojnc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sysykeji.top/Article/details/gtpixxnsee.html

[Q86] 读取 JSON 字段
来源：http://dali.316326.xyz/Article/details/gtbnebjlfb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xinyue.icu/Article/details/gtbabwnnbp.html

[Q87] JSON 字段做条件
来源：http://dali.pengpengdd.cyou/Article/details/gtbucgbdqt.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hnqzz.top/Article/details/gtbfrzbhvr.html

[Q88] 行转列（条件聚合）
来源：http://dali.shangyingyoupin.top/Article/details/gtmmwdtogs.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.nwbrower.top/Article/details/gtoitultpy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtvyanubbn.html

[Q89] 判断表是否存在
来源：http://dali.0kj1m.cn/Article/details/gtkzjulvkc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nanxinkj.top/Article/details/gtuspainvx.html

[Q90] 生成序号列
来源：http://dali.daria6918.cn/Article/details/gtalwrlqfw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.svipenyu.cn/Article/details/gtwiuotbvo.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtvczmthlr.html

R. Bash 专题
来源：http://dali.xuetiantiany.cn/Article/details/gtdwdradvh.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtaqfhaolj.html

[R01] shebang 与严格模式
来源：http://dali.gaohongyu789.top/Article/details/gtskmapqpv.html

#!/usr/bin/env bash
来源：http://dali.jinyuanbaomall.cn/Article/details/gteekjnbef.html

set -euo pipefail
来源：http://dali.hnqzz.top/Article/details/gthlolpqkb.html

[R02] 变量赋值与使用
来源：http://dali.shanyushiyangtech.top/Article/details/gtkaefyzsk.html

name="Tom"; echo "$name"
来源：http://dali.guowangkeji.top/Article/details/gtvvqououh.html

[R03] 只读变量
来源：http://dali.yj202588.top/Article/details/gtasmalgbs.html

readonly PI=3.14
来源：http://dali.hnqzz.top/Article/details/gtdgznbfrg.html

[R04] 位置参数
来源：http://dali.sufxvd.cn/Article/details/gttdediuxq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.nanxuanxn.top/Article/details/gtkxebvbsz.html

[R05] 参数默认值
来源：http://dali.gogol.net.cn/Article/details/gtbfinprpz.html

name="${1:-default}"
来源：http://dali.bjfxy.top/Article/details/gtjoacdfhw.html

[R06] 判断命令是否存在
来源：http://dali.feifeiyinyue.top/Article/details/gtfyhvzpem.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jianghu66.top/Article/details/gtnpejrflq.html

[R07] if 判断文件
来源：http://dali.bjfxy.top/Article/details/gtyzmxhgmc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yuanzhike.top/Article/details/gtdmhoizqp.html

[R08] 数值比较
来源：http://dali.jinghuilouyu.cn/Article/details/gtyfpufagt.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.daria6918.cn/Article/details/gtzukpfkqr.html

[R09] 字符串比较
来源：http://dali.c1oappe.top/Article/details/gtjmvzpgdl.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gtiqphjgcp.html

[R10] 正则匹配
来源：http://dali.xziqi.cn/Article/details/gtdeczgano.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gtnnoqclov.html

[R11] case 多分支
来源：http://dali.0kj1m.cn/Article/details/gtjmiyhbjq.html

case "$1" in
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsgwvepwz.html

start) echo "启动" ;;
来源：http://dali.hywenlv.cn/Article/details/gtnxmnyzgg.html

stop)  echo "停止" ;;
来源：http://dali.ehwqpu.com/Article/details/gtigphrlgh.html

*)     echo "未知命令" ;;
来源：http://dali.nanxinkj.top/Article/details/gtkpojwgct.html

esac
来源：http://dali.shanyushiyangtech.top/Article/details/gthiortpyp.html

[R12] for 遍历文件
来源：http://dali.hywenlv.cn/Article/details/gtmwjjqiyj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhongyouzk.top/Article/details/gtitxojoav.html

[R13] for 计数循环
来源：http://dali.havefunace.top/Article/details/gtjfzrizpp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yvedp.cn/Article/details/gtymtpavtf.html

[R14] C 风格 for
来源：http://dali.aibaodan.cn/Article/details/gtmpiwsutd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ydzc1.top/Article/details/gtiqhbiofm.html

[R15] while 逐行读文件
来源：http://dali.daxiang520.top/Article/details/gtuywpsewf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sysykeji.top/Article/details/gtiwetfsua.html

[R16] until 等待条件
来源：http://dali.bjfxy.top/Article/details/gtagbwnrig.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtuajzqucz.html

[R17] 数组定义与取值
来源：http://dali.chenjidiqi.icu/Article/details/gtlxwhavzd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.fengsongda.top/Article/details/gtrlorfbxy.html

[R18] 遍历数组
来源：http://dali.tanke756.top/Article/details/gtkjbbfcgl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.dashuyun.cn/Article/details/gtzylqbmqo.html

[R19] 数组长度
来源：http://dali.gotoacloud.top/Article/details/gtrzinihbu.html

echo "${#arr[@]}"
来源：http://dali.kuanghao11.cn/Article/details/gthtsitakl.html

[R20] 关联数组（字典）
来源：http://dali.jinqigufen.top/Article/details/gtyshsqjfh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.pycfn.com/Article/details/gtfgglvsol.html

[R21] 字符串长度
来源：http://dali.cashguo.top/Article/details/gtsyilivka.html

echo "${#s}"
来源：http://dali.meibo888.top/Article/details/gtssiupzgj.html

[R22] 截取子串
来源：http://dali.jianghu66.top/Article/details/gthhqpnclq.html

echo "${s:0:5}"
来源：http://dali.smart0.xyz/Article/details/gttcvcbigf.html

[R23] 字符串替换
来源：http://dali.yvedp.cn/Article/details/gtfnlwzjdv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.birdmap.top/Article/details/gtjfqtmheh.html

[R24] 大小写转换
来源：http://dali.gogol.net.cn/Article/details/gtdoixoemi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtuomekwgl.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhoulong.xyz/Article/details/gtfsrlmcpd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cheryme.top/Article/details/gtcrrclzvs.html

[R26] 命令替换
来源：http://dali.dianchejie.cn/Article/details/gttbeklhge.html

now=$(date +%F); echo "$now"
来源：http://dali.birdmap.top/Article/details/gtsgqoqmvy.html

[R27] 算术展开
来源：http://dali.zdqjudy.top/Article/details/gtvzahhzbv.html

echo $((1 + 2 * 3))
来源：http://dali.daria6918.cn/Article/details/gtzymuismv.html

[R28] 浮点运算
来源：http://dali.aizwys.cn/Article/details/gtwfwrguws.html

echo "scale=2; 10/3" | bc
来源：http://dali.316326.xyz/Article/details/gtawcquakh.html

[R29] 定义函数
来源：http://dali.jiagoushi.top/Article/details/gtyfxsokze.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.316326.xyz/Article/details/gtrksnbcxa.html

[R30] 函数返回状态码
来源：http://dali.sxryk.cn/Article/details/gtypdhkvwy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hammf.cn/Article/details/gtbhcnyall.html

[R31] 局部变量
来源：http://dali.yuxming.cn/Article/details/gtwyoviwel.html

f() { local x=1; echo "$x"; }
来源：http://dali.hysaishi.cn/Article/details/gtwgvafpwm.html

[R32] 参数个数校验
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfodhfvwq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hnxiangtu.top/Article/details/gtxkvwfdnw.html

[R33] 捕获错误并提示行号
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqaxswkpm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.chenjidiqi.icu/Article/details/gtrjmvdnsp.html

[R34] 退出时清理
来源：http://dali.zhiwuduotai.top/Article/details/gtwkuszqxe.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shuidangran.top/Article/details/gtclypbobf.html

[R35] 后台执行并等待
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmmnhoxlv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.quarkkingdee.top/Article/details/gtbwljxjyc.html

[R36] 并发执行多个任务
来源：http://dali.jiagoushi.top/Article/details/gtveyzmelx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hywenlv.cn/Article/details/gtwbqsqxac.html

[R37] 把输出赋给变量
来源：http://dali.dashuyun.cn/Article/details/gtfvojxuru.html

files=$(ls -1)
来源：http://dali.nwbrower.top/Article/details/gtaapxvhjs.html

[R38] 管道串联
来源：http://dali.jqgufenzy.top/Article/details/gtbijofsib.html

cat a.txt | grep -i error | wc -l
来源：http://dali.c1oappe.top/Article/details/gtvwvtodil.html

[R39] 重定向标准输出与错误
来源：http://dali.zhengqikj.top/Article/details/gtfsvuidqg.html

cmd > out.log 2>&1
来源：http://dali.jinqigufen.top/Article/details/gtjgxrgsgp.html

[R40] 追加写日志
来源：http://dali.mhx1999.top/Article/details/gtauwgwgtz.html

echo "log" >> out.log
来源：http://dali.nwbrower.top/Article/details/gtqxqmzxds.html

[R41] 丢弃输出
来源：http://dali.redwolf501.top/Article/details/gtrcaczicl.html

cmd >/dev/null 2>&1
来源：http://dali.vqdsnc.cn/Article/details/gtftipbovp.html

[R42] 输入重定向
来源：http://dali.wangdashe.top/Article/details/gtfosyjrxo.html

wc -l < a.txt
来源：http://dali.xinyue.icu/Article/details/gtostsphjm.html

[R43] 按名字查找文件
来源：http://dali.redwolf501.top/Article/details/gtoupgwbzn.html

find . -name "*.log" -type f
来源：http://dali.aibaodan.cn/Article/details/gtyrwtbwhz.html

[R44] 按修改时间查找
来源：http://dali.jianghu66.top/Article/details/gtgzrsrete.html

find . -mtime -7 -type f
来源：http://dali.jyoumei.cn/Article/details/gtqieedfzg.html

[R45] 批量删除
来源：http://dali.dashuyun.cn/Article/details/gtzyqxwqfc.html

find . -name "*.tmp" -delete
来源：http://dali.mhx1999.top/Article/details/gtoauyqsdf.html

[R46] 递归替换文件内容
来源：http://dali.yj202588.top/Article/details/gtgoyxefot.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yonumen.top/Article/details/gtpnuspyph.html

[R47] sed 单行替换
来源：http://dali.tanke756.top/Article/details/gtfquwuvdw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtszemhqrb.html

[R48] awk 取指定列
来源：http://dali.vqdsnc.cn/Article/details/gtvzrsmqrx.html

awk '{print $1, $3}' a.txt
来源：http://dali.0kj1m.cn/Article/details/gtcyvepbwd.html

[R49] awk 带条件
来源：http://dali.shzxlz.cn/Article/details/gtlkhnxswv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.havefunace.top/Article/details/gtengwduwj.html

[R50] awk 求和
来源：http://dali.ydzc1.top/Article/details/gtyckdhntc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtmvbmqftb.html

[R51] 排序去重取前几
来源：http://dali.xinyue.icu/Article/details/gtrsuftnfy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.dianchejie.cn/Article/details/gtytmpcviv.html

[R52] 统计行数
来源：http://dali.tian-w.cn/Article/details/gtgejlxioh.html

wc -l a.txt
来源：http://dali.yongpay.top/Article/details/gturklihyc.html

[R53] 查看文件头与实时尾
来源：http://dali.smart0.xyz/Article/details/gtkclbcdgp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmmuppnoz.html

[R54] 比较两个文件
来源：http://dali.gotoacloud.top/Article/details/gtbhuxurop.html

diff a.txt b.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtokseuqne.html

[R55] 压缩与解压
来源：http://dali.yuxming.cn/Article/details/gtsospwiem.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.aizwys.cn/Article/details/gtilkbbzgd.html

[R56] 远程拷贝
来源：http://dali.hfpthk.cn/Article/details/gtgfnngkdw.html

scp file user@host:/path/
来源：http://dali.zhongyouzk.top/Article/details/gtcqfmfkyv.html

[R57] 远程执行命令
来源：http://dali.jyoumei.cn/Article/details/gtatbbpvqz.html

ssh user@host 'uptime'
来源：http://dali.jlsjyb.cn/Article/details/gtnccaalca.html

[R58] 下载文件
来源：http://dali.havefunace.top/Article/details/gtyamvmwqt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.iojbl.cn/Article/details/gtqtbthexw.html

[R59] 发 POST JSON
来源：http://dali.yuanzhike.top/Article/details/gtqvlwpjsd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinghuilouyu.cn/Article/details/gtwhmbendu.html

[R60] 只看 HTTP 状态码
来源：http://dali.jyoumei.cn/Article/details/gtgfnzacop.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yuxming.cn/Article/details/gtndzmrfcj.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gtftiexybm.html

df -h;  du -sh *
来源：http://dali.shzxlz.cn/Article/details/gtpcuxeqff.html

[R62] 找最占空间的文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtrucxbprh.html

du -ah . | sort -rh | head -10
来源：http://dali.daxiang520.top/Article/details/gtgksylhcr.html

[R63] 内存与进程
来源：http://dali.fzhhl.top/Article/details/gtqtkkuove.html

free -h;  ps aux | grep nginx
来源：http://dali.jqgfzy.top/Article/details/gtxofocaoj.html

[R64] 结束进程
来源：http://dali.chenzaomai.com/Article/details/gtsmtwwhrj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.fzhhl.top/Article/details/gtxsrqmzhs.html

[R65] 查看端口占用
来源：http://dali.shzxlz.cn/Article/details/gteqifbely.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.nwbrower.top/Article/details/gtppmohvgi.html

[R66] 定时任务
来源：http://dali.birdmap.top/Article/details/gtxweehdls.html

crontab -e;  crontab -l
来源：http://dali.nanxinkj.top/Article/details/gtuympgfuk.html

[R67] 生成随机十六进制串
来源：http://dali.shanyushiyangtech.top/Article/details/gtaurywjoa.html


<!-- 参考信息 -->