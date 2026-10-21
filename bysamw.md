代发 wailian999

SELECT * FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtoignlvsw.html

[Q16] 查询指定列
来源：http://dali.birdmap.top/Article/details/gtcbveprrk.html

SELECT id, name FROM users;
来源：http://dali.hammf.cn/Article/details/gtkixdialy.html

[Q17] 条件查询
来源：http://dali.daria6918.cn/Article/details/gtrwmhnjze.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gtpqudfjqz.html

[Q18] 模糊匹配
来源：http://dali.ehwqpu.com/Article/details/gtkvxxghlw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shanyushiyangkeji.top/Article/details/gtexiapqfr.html

[Q19] 范围查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcdazlqpf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinghuilouyu.cn/Article/details/gtawqgshes.html

[Q20] IN 列表
来源：http://dali.yj202588.top/Article/details/gthxbsbuad.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwtbfrgoi.html

[Q21] 空值判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsqcdcufo.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.chenlongwang.top/Article/details/gtogrygmhx.html

[Q22] 排序
来源：http://dali.nwbrower.top/Article/details/gthuotbhny.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.feifeiyinyue.top/Article/details/gtpsvlqufc.html

[Q23] 分页
来源：http://dali.shangyingyoupin.top/Article/details/gtopqppdfi.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.sufxvd.cn/Article/details/gtsvwiefke.html

[Q24] 去重
来源：http://dali.shuidangran.top/Article/details/gttjnyyeik.html

SELECT DISTINCT city FROM users;
来源：http://dali.fengsongda.top/Article/details/gtdfxkysek.html

[Q25] 只取前 N 条
来源：http://dali.chenjidiqi.icu/Article/details/gtfsrpcuqp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.chenzaomai.com/Article/details/gtxrkupdqm.html

[Q26] 计数
来源：http://dali.yj20258.top/Article/details/gtupzfaqhi.html

SELECT COUNT(*) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtcuixakod.html

[Q27] 条件计数
来源：http://dali.andypj.xyz/Article/details/gtricoqmpj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yueranfly.top/Article/details/gtgbpgsqea.html

[Q28] 求和与平均
来源：http://dali.yj20258888.top/Article/details/gtzdqymszn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.andypj.xyz/Article/details/gtggiwtfyn.html

[Q29] 最大最小值
来源：http://dali.daria6918.cn/Article/details/gtfayliebk.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gttoywildd.html

[Q30] 分组统计
来源：http://dali.havefunace.top/Article/details/gtvkusxvhy.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.redwolf501.top/Article/details/gtdeesacxs.html

[Q31] 分组后过滤
来源：http://dali.yongpay.top/Article/details/gtyubefeqw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.wangshuangyany.cn/Article/details/gtxiwqnmrp.html

[Q32] 分组拼接字符串
来源：http://dali.hnqzz.top/Article/details/gtcfusrpgs.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yj202588.top/Article/details/gtgmoejgss.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.chenlongwang.top/Article/details/gtzvpxquye.html

[Q33] 多列分组
来源：http://dali.ybcxt.top/Article/details/gtjhmeouel.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gaohongyu789.top/Article/details/gtkbiaeihp.html

[Q34] 每组取第一条
来源：http://dali.haohaochexian.top/Article/details/gtfjjqmdzm.html

SELECT * FROM (
来源：http://dali.pycfn.com/Article/details/gtlwoycatv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jlsjyb.cn/Article/details/gtyqzjstmo.html

) t WHERE rn = 1;
来源：http://dali.andypj.xyz/Article/details/gtdvgbsczw.html

[Q35] 内连接
来源：http://dali.redwolf501.top/Article/details/gtfjqxrtup.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ydzc1.top/Article/details/gtulkrixid.html

[Q36] 左连接
来源：http://dali.zhiwuduotai.top/Article/details/gtrvbavyfq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhixingplan.top/Article/details/gtvuobuoxd.html

[Q37] 右连接
来源：http://dali.guowangkeji.top/Article/details/gtzssctiii.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.chenlongwang.top/Article/details/gtbugwbrfw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.daxiang520.top/Article/details/gtfscysgwz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.nanxinkj.top/Article/details/gtjtpuxiwy.html

[Q39] 自连接（查上下级）
来源：http://dali.wangshuangyany.cn/Article/details/gthaploiud.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.guowangkeji.top/Article/details/gtoeebacqj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jianghu66.top/Article/details/gtoqfvligs.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhiwuduotai.top/Article/details/gtepwvnfbe.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sweek.top/Article/details/gtliplkmbk.html

[Q41] 多表连接
来源：http://dali.316326.xyz/Article/details/gtfzhopqhz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.vqdsnc.cn/Article/details/gtfzrflkbn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.aibaodan.cn/Article/details/gtxkyxyfod.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.svipenyu.cn/Article/details/gthhnarmdm.html

[Q42] 连接条件附加过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvehqodpi.html

SELECT u.name, o.amount FROM users u
来源：http://dali.smart0.xyz/Article/details/gtsbvpdvdg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.guannengcc.top/Article/details/gteldiiyem.html

[Q43] 标量子查询
来源：http://dali.nanxuanxn.top/Article/details/gtcbwfelcj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.iojbl.cn/Article/details/gtnuapxbec.html

[Q44] IN 子查询
来源：http://dali.daxiang520.top/Article/details/gtbacctnvr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xylfe.cn/Article/details/gtdallzjbh.html

[Q45] EXISTS 判断存在
来源：http://dali.yongpay.top/Article/details/gtwklivbqv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yuanzhike.top/Article/details/gtezkukzgu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ppjwa.cn/Article/details/gtnolbblfo.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sweek.top/Article/details/gtyfkqwfjg.html

[Q47] 与平均值比较
来源：http://dali.cqqwz.cn/Article/details/gtbuuirorq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xinyue.icu/Article/details/gtmeczxuzj.html

[Q48] CTE 公用表表达式
来源：http://dali.havefunace.top/Article/details/gtqllojlka.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.pycfn.com/Article/details/gtrfgrnwtw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.redwolf501.top/Article/details/gtogiyjyme.html

[Q49] 更新单行
来源：http://dali.yj20258888.top/Article/details/gtiotxrcch.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.smart0.xyz/Article/details/gtebnrbolk.html

[Q50] 批量更新
来源：http://dali.jianghu66.top/Article/details/gtyhfqzggs.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jianghu66.top/Article/details/gtdstosfof.html

[Q51] 用子查询更新
来源：http://dali.316326.xyz/Article/details/gtpxiebhko.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jqgufenzy.top/Article/details/gtmkpkqzuk.html

[Q52] 删除指定行
来源：http://dali.zhixingplan.top/Article/details/gtrxvwgril.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinqigufen.top/Article/details/gtlhunkovu.html

[Q53] 按条件删除
来源：http://dali.yj20258.top/Article/details/gtbkbesgij.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.daxiang520.top/Article/details/gtadcptoir.html

[Q54] 清空表
来源：http://dali.chenzaomai.com/Article/details/gtcjinbsks.html

TRUNCATE TABLE logs;
来源：http://dali.hammf.cn/Article/details/gtxbutxagp.html

[Q55] 排名（并列占位）
来源：http://dali.nanxinkj.top/Article/details/gtxhnudpyg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shzxlz.cn/Article/details/gtovappxwe.html

[Q56] 密集排名（并列不占位）
来源：http://dali.wangdashe.top/Article/details/gtmovwdazs.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.feifeiyinyue.top/Article/details/gtqctbbiqx.html

[Q57] 行号
来源：http://dali.ybcxt.top/Article/details/gtmevvbcva.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xylfe.cn/Article/details/gtgxkwhtoe.html

[Q58] 累计求和
来源：http://dali.0kj1m.cn/Article/details/gtteetsdyj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gtueurcmgs.html

[Q59] 分组内累计
来源：http://dali.havefunace.top/Article/details/gtpfvaitet.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtxsmfoetx.html

[Q60] 取上一行 / 下一行
来源：http://dali.wangshuangyany.cn/Article/details/gtheczxbiq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sufxvd.cn/Article/details/gtruoxrrws.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtmoxlpmic.html

[Q61] 移动平均
来源：http://dali.zhoulong.xyz/Article/details/gtuoyjwwkf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtwlkxbxso.html

[Q62] 分组占比
来源：http://dali.zdqjudy.top/Article/details/gtljvmosmr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhoulong.xyz/Article/details/gtxibiqflh.html

[Q63] 开启事务
来源：http://dali.dashuyun.cn/Article/details/gtmrhlrnuj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvnkkkthw.html

[Q64] 提交事务
来源：http://dali.jqgufenzy.top/Article/details/gtjpxqeaqu.html

COMMIT;
来源：http://dali.shangyingyoupin.top/Article/details/gtslnpdzyr.html

[Q65] 回滚事务
来源：http://dali.wangshuangyany.cn/Article/details/gtxhiuensr.html

ROLLBACK;
来源：http://dali.guannengcc.top/Article/details/gtihmoiwmf.html

[Q66] 行锁查询
来源：http://dali.pengpengdd.cyou/Article/details/gtiazkjkyh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.gogol.net.cn/Article/details/gtrvvnwsyg.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gtrldkpdiq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ydzc1.top/Article/details/gtclgdhgjb.html

[Q68] 保存点
来源：http://dali.tian-w.cn/Article/details/gtrxikbebp.html

SAVEPOINT sp1;
来源：http://dali.shzxlz.cn/Article/details/gtiboardjk.html

ROLLBACK TO sp1;
来源：http://dali.hnxiangtu.top/Article/details/gtqyrofkov.html

[Q69] 查看执行计划
来源：http://dali.gogol.net.cn/Article/details/gtkbmvcnol.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cdnleiting.top/Article/details/gtpimkrgyy.html

[Q70] 更新统计信息
来源：http://dali.c1oappe.top/Article/details/gtallohkdh.html

ANALYZE TABLE users;
来源：http://dali.daxiang520.top/Article/details/gtxueeojld.html

[Q71] 查看建表语句
来源：http://dali.zhengqikj.top/Article/details/gtacklaacf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhoulong.xyz/Article/details/gtmzayonht.html

[Q72] 查看索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcrlrgjcg.html

SHOW INDEX FROM users;
来源：http://dali.ivvv.top/Article/details/gthyiywmxu.html

[Q73] 查看表状态
来源：http://dali.yj20258.top/Article/details/gtrmjvlmsr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cqqwz.cn/Article/details/gtysncjjtl.html

[Q74] 强制使用索引
来源：http://dali.cdnleiting.top/Article/details/gtkksfyflt.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.nanxinkj.top/Article/details/gtulmnzpjp.html

[Q75] 日期格式化
来源：http://dali.jinqigufen.top/Article/details/gthsmbdqbo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gtfthncxos.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hywenlv.cn/Article/details/gtkfdmkpmp.html

[Q76] 按天统计
来源：http://dali.quarkkingdee.top/Article/details/gtakidbgbv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hongshengwenyu.top/Article/details/gtvrzlgail.html

[Q77] 时间加减
来源：http://dali.hammf.cn/Article/details/gtszjcvtdf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yonumen.top/Article/details/gtnhqmqkmf.html

[Q78] 当前时间
来源：http://dali.kuanghao11.cn/Article/details/gtjanlhotl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.nanxuanxn.top/Article/details/gttczafbtl.html

[Q79] 字符串拼接
来源：http://dali.xuetiantiany.cn/Article/details/gtqhzwetdb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gaohongyu789.top/Article/details/gtxkftbnvb.html

[Q80] 字符串截取
来源：http://dali.yj20258888.top/Article/details/gtllkqzrrq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.redwolf501.top/Article/details/gtfwvvioxi.html

[Q81] 字符串替换
来源：http://dali.jyoumei.cn/Article/details/gtbofhdhcb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrvwjfcfo.html

[Q82] 字符长度与字节长度
来源：http://dali.shzxlz.cn/Article/details/gtkruvpbuu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtcootbwtx.html

[Q83] 大小写转换
来源：http://dali.yonumen.top/Article/details/gtunuxtqge.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.daxiang520.top/Article/details/gtbeierosh.html

[Q84] 去除首尾空格
来源：http://dali.zycfv.cn/Article/details/gtvmmcjnki.html

SELECT TRIM(name) FROM users;
来源：http://dali.c1oappe.top/Article/details/gtaxmxhqio.html

[Q85] 数值取整
来源：http://dali.ivvv.top/Article/details/gtgsljmuzr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.fzhhl.top/Article/details/gtrdilxwld.html

[Q86] 读取 JSON 字段
来源：http://dali.shanyushiyangtech.top/Article/details/gtmdlqfvzp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.daxiang520.top/Article/details/gtrrthnqzq.html

[Q87] JSON 字段做条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtulgrcipv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yanxiufei.cn/Article/details/gtvazzpyxg.html

[Q88] 行转列（条件聚合）
来源：http://dali.ybcxt.top/Article/details/gtomzllmqt.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhixingplan.top/Article/details/gtbjyehbaj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cashguo.top/Article/details/gtrbfgcigk.html

[Q89] 判断表是否存在
来源：http://dali.hnqzz.top/Article/details/gtyrtlaiig.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.quarkkingdee.top/Article/details/gtuqutumgc.html

[Q90] 生成序号列
来源：http://dali.hfpthk.cn/Article/details/gtywyohjlw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.chenzaomai.com/Article/details/gtqyzsdrbg.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtjrzijzkp.html

R. Bash 专题
来源：http://dali.smart0.xyz/Article/details/gtbkjhdbca.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtdhzvwgdo.html

[R01] shebang 与严格模式
来源：http://dali.jinqigufen.top/Article/details/gtyzglqpqh.html

#!/usr/bin/env bash
来源：http://dali.zycfv.cn/Article/details/gthchgbhgb.html

set -euo pipefail
来源：http://dali.zycfv.cn/Article/details/gthmjmtelp.html

[R02] 变量赋值与使用
来源：http://dali.ydzc1.top/Article/details/gtfuyugbce.html

name="Tom"; echo "$name"
来源：http://dali.yongpay.top/Article/details/gtfjklywlt.html

[R03] 只读变量
来源：http://dali.jyoumei.cn/Article/details/gtkeshtgrj.html

readonly PI=3.14
来源：http://dali.ydzc1.top/Article/details/gtzhlxpvlc.html

[R04] 位置参数
来源：http://dali.tian-w.cn/Article/details/gtyzyiwmqy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.c1oappe.top/Article/details/gtcbxwonme.html

[R05] 参数默认值
来源：http://dali.chenlongwang.top/Article/details/gtglaypurl.html

name="${1:-default}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtotsaoaic.html

[R06] 判断命令是否存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmloxmawe.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yangfankeji.com/Article/details/gtnkffwiky.html

[R07] if 判断文件
来源：http://dali.gaohongyu789.top/Article/details/gtkvctvgpl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gtujmvfbgn.html

[R08] 数值比较
来源：http://dali.zdqjudy.top/Article/details/gtdkyehrek.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ivvv.top/Article/details/gtbxrxjbhw.html

[R09] 字符串比较
来源：http://dali.tian-w.cn/Article/details/gtprenoelt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.guannengcc.top/Article/details/gtjjtaxodc.html

[R10] 正则匹配
来源：http://dali.yj202588.top/Article/details/gtliqbrfpe.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.haohaochexian.top/Article/details/gtkmqtsnbh.html

[R11] case 多分支
来源：http://dali.fengsongda.top/Article/details/gtmuincsas.html

case "$1" in
来源：http://dali.chenlongwang.top/Article/details/gttfbzafdu.html

start) echo "启动" ;;
来源：http://dali.hammf.cn/Article/details/gtshlomrnm.html

stop)  echo "停止" ;;
来源：http://dali.kuanghao11.cn/Article/details/gtqzffpbrr.html

*)     echo "未知命令" ;;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtadhcczrk.html

esac
来源：http://dali.vqdsnc.cn/Article/details/gtelbqqpqw.html

[R12] for 遍历文件
来源：http://dali.0kj1m.cn/Article/details/gtyktaaitz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yj20258.top/Article/details/gtqicwavcr.html

[R13] for 计数循环
来源：http://dali.guowangkeji.top/Article/details/gtfocemupc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cheryme.top/Article/details/gtlbidxjxp.html

[R14] C 风格 for
来源：http://dali.mhx1999.top/Article/details/gtfywjkxtu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.0kj1m.cn/Article/details/gtyucdvssd.html

[R15] while 逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gtwzwmkpgu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.nwbrower.top/Article/details/gtvzysiawh.html

[R16] until 等待条件
来源：http://dali.dianchejie.cn/Article/details/gtyqvosila.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.tian-w.cn/Article/details/gthjmmxwjd.html

[R17] 数组定义与取值
来源：http://dali.birdmap.top/Article/details/gtagomzxfb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.andypj.xyz/Article/details/gtwclqgyqt.html

[R18] 遍历数组
来源：http://dali.yongpay.top/Article/details/gtqjlommos.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jiagoushi.top/Article/details/gtrkpvvxex.html

[R19] 数组长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gteficcwez.html

echo "${#arr[@]}"
来源：http://dali.dianchejie.cn/Article/details/gtpqbfnuiq.html

[R20] 关联数组（字典）
来源：http://dali.hammf.cn/Article/details/gtqgoyctkm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhixingplan.top/Article/details/gtiifzkqax.html

[R21] 字符串长度
来源：http://dali.yonumen.top/Article/details/gtwwtbecxq.html

echo "${#s}"
来源：http://dali.yanxiufei.cn/Article/details/gtwhlnzlla.html

[R22] 截取子串
来源：http://dali.jianghu66.top/Article/details/gteybuoqhn.html

echo "${s:0:5}"
来源：http://dali.ybcxt.top/Article/details/gtxpcudewe.html

[R23] 字符串替换
来源：http://dali.jqgfzy.top/Article/details/gtccdgyrdm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.chenjidiqi.icu/Article/details/gtoualtpfs.html

[R24] 大小写转换
来源：http://dali.gotoacloud.top/Article/details/gtlnkawlku.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.tanke756.top/Article/details/gtahhgayxj.html

[R25] 去后缀 / 去前缀
来源：http://dali.shzxlz.cn/Article/details/gtnotarrdp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hnqzz.top/Article/details/gthajglwiz.html

[R26] 命令替换
来源：http://dali.yvedp.cn/Article/details/gtkjphtssh.html

now=$(date +%F); echo "$now"
来源：http://dali.chenzaomai.com/Article/details/gtxmkmoivs.html

[R27] 算术展开
来源：http://dali.pengpengdd.cyou/Article/details/gtrjwbaqvk.html

echo $((1 + 2 * 3))
来源：http://dali.pycfn.com/Article/details/gtfpkmilbn.html

[R28] 浮点运算
来源：http://dali.pengpengdd.cyou/Article/details/gtwzckbbci.html

echo "scale=2; 10/3" | bc
来源：http://dali.nanxinkj.top/Article/details/gtdeqqvmxf.html

[R29] 定义函数
来源：http://dali.hywenlv.cn/Article/details/gtaegfedvs.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.chenjidiqi.icu/Article/details/gtrnwqxutz.html

[R30] 函数返回状态码
来源：http://dali.jinqigufen.top/Article/details/gteqtnqvzu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yj20258.top/Article/details/gtcutpfcxl.html

[R31] 局部变量
来源：http://dali.hnxiangtu.top/Article/details/gtyxtvosyf.html

f() { local x=1; echo "$x"; }
来源：http://dali.hfpthk.cn/Article/details/gtjtrcwrdi.html

[R32] 参数个数校验
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttyxkpwhc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.havefunace.top/Article/details/gtamreirqa.html

[R33] 捕获错误并提示行号
来源：http://dali.shanyushiyangkeji.top/Article/details/gttmmbzlaw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gzhubu.top/Article/details/gtoyojajoa.html

[R34] 退出时清理
来源：http://dali.aibaodan.cn/Article/details/gttlrcwfge.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.svipenyu.cn/Article/details/gtwtemmrfh.html

[R35] 后台执行并等待
来源：http://dali.hammf.cn/Article/details/gtwizgphuz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shuidangran.top/Article/details/gtxacoqzib.html

[R36] 并发执行多个任务
来源：http://dali.meibo888.top/Article/details/gtozshvfgv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.kuanghao11.cn/Article/details/gtpqxgelnl.html

[R37] 把输出赋给变量
来源：http://dali.ybcxt.top/Article/details/gtkgtibqxt.html

files=$(ls -1)
来源：http://dali.fzhhl.top/Article/details/gtlhwknyan.html

[R38] 管道串联
来源：http://dali.chenjidiqi.icu/Article/details/gtqjwxivth.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hammf.cn/Article/details/gtpdeaivvu.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gtoilxvecd.html

cmd > out.log 2>&1
来源：http://dali.svipenyu.cn/Article/details/gtdgnyupqa.html

[R40] 追加写日志
来源：http://dali.yuxming.cn/Article/details/gtctnzihdg.html

echo "log" >> out.log
来源：http://dali.hnqzz.top/Article/details/gtkibvywpz.html

[R41] 丢弃输出
来源：http://dali.jqgufenzy.top/Article/details/gtvswxtefz.html

cmd >/dev/null 2>&1
来源：http://dali.jqgufenzy.top/Article/details/gtjiqrlnbg.html

[R42] 输入重定向
来源：http://dali.ywan-chungtsiang.top/Article/details/gthqrieiuu.html

wc -l < a.txt
来源：http://dali.aizwys.cn/Article/details/gtyuwezlzo.html

[R43] 按名字查找文件
来源：http://dali.jlsjyb.cn/Article/details/gtsycdjzat.html

find . -name "*.log" -type f
来源：http://dali.sweek.top/Article/details/gtbpqtayte.html

[R44] 按修改时间查找
来源：http://dali.xylfe.cn/Article/details/gtupgocvbx.html

find . -mtime -7 -type f
来源：http://dali.yuxming.cn/Article/details/gtnycsgysc.html

[R45] 批量删除
来源：http://dali.yvedp.cn/Article/details/gtwfmadqea.html

find . -name "*.tmp" -delete
来源：http://dali.tianlin.xyz/Article/details/gtspoyonef.html

[R46] 递归替换文件内容
来源：http://dali.sweek.top/Article/details/gtfrpfjbqp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shuidangran.top/Article/details/gtforokaho.html

[R47] sed 单行替换
来源：http://dali.vqdsnc.cn/Article/details/gtceahfutf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.guowangkeji.top/Article/details/gtzddgwxvm.html

[R48] awk 取指定列
来源：http://dali.bjfxy.top/Article/details/gteksasvpa.html

awk '{print $1, $3}' a.txt
来源：http://dali.guowangkeji.top/Article/details/gtzmfhqzkk.html

[R49] awk 带条件
来源：http://dali.shuidangran.top/Article/details/gtgbtcrvem.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yueranfly.top/Article/details/gtvnhdqmss.html

[R50] awk 求和
来源：http://dali.dashuyun.cn/Article/details/gtunzvyzlx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.316326.xyz/Article/details/gtxdawjhjt.html

[R51] 排序去重取前几
来源：http://dali.wangshuangyany.cn/Article/details/gtxgvrlzbb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yj20258.top/Article/details/gtrmodxqad.html

[R52] 统计行数
来源：http://dali.cheryme.top/Article/details/gtcscdzgaq.html

wc -l a.txt
来源：http://dali.smart0.xyz/Article/details/gtvszqyoiv.html

[R53] 查看文件头与实时尾
来源：http://dali.aizwys.cn/Article/details/gtvqqfmznm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hammf.cn/Article/details/gtmlcfjhcy.html

[R54] 比较两个文件
来源：http://dali.cdnleiting.top/Article/details/gtpgobkcbw.html

diff a.txt b.txt
来源：http://dali.zhixingplan.top/Article/details/gttbztptji.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gtkrbavgvi.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.kuanghao11.cn/Article/details/gtcywtoych.html

[R56] 远程拷贝
来源：http://dali.9152youxi.cn/Article/details/gtaujilxhi.html

scp file user@host:/path/
来源：http://dali.ywan-chungtsiang.top/Article/details/gtviwcykbc.html

[R57] 远程执行命令
来源：http://dali.yj20258.top/Article/details/gtyuwpjwva.html

ssh user@host 'uptime'
来源：http://dali.ydzc1.top/Article/details/gtkrxnsyzn.html

[R58] 下载文件
来源：http://dali.smart0.xyz/Article/details/gtmkwbckul.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ywan-chungtsiang.top/Article/details/gteewoozlu.html

[R59] 发 POST JSON
来源：http://dali.jqgfzy.top/Article/details/gtqablllpw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.chenzaomai.com/Article/details/gtlukcxyoq.html

[R60] 只看 HTTP 状态码
来源：http://dali.meibo888.top/Article/details/gtedmjduvf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.pengpengdd.cyou/Article/details/gtgvjvhvbe.html

[R61] 磁盘占用
来源：http://dali.yvedp.cn/Article/details/gtougahgkt.html

df -h;  du -sh *
来源：http://dali.yuxming.cn/Article/details/gtdkutdpur.html

[R62] 找最占空间的文件
来源：http://dali.cashguo.top/Article/details/gtfqmgebjh.html

du -ah . | sort -rh | head -10
来源：http://dali.nwbrower.top/Article/details/gtucfyklvf.html

[R63] 内存与进程
来源：http://dali.zhiwuduotai.top/Article/details/gtzkbqnjbt.html

free -h;  ps aux | grep nginx
来源：http://dali.wangdashe.top/Article/details/gtkanyklod.html

[R64] 结束进程
来源：http://dali.andypj.xyz/Article/details/gtlblfvsom.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xinyue.icu/Article/details/gtvqiwmwwa.html

[R65] 查看端口占用
来源：http://dali.yueranfly.top/Article/details/gtyrntfsmt.html


<!-- 参考信息 -->