代发 wailian999

[Q14] 存在则更新（upsert）
来源：http://dali.yonumen.top/Article/details/gtmlthvnyv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.vqdsnc.cn/Article/details/gthynqmqfq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hywenlv.cn/Article/details/gtnszfxcdv.html

[Q15] 查询全部
来源：http://dali.birdmap.top/Article/details/gtlbjrcfyr.html

SELECT * FROM users;
来源：http://dali.yj20258888.top/Article/details/gtxwbrheui.html

[Q16] 查询指定列
来源：http://dali.yangfankeji.com/Article/details/gthkwbaduq.html

SELECT id, name FROM users;
来源：http://dali.xuanzx.com/Article/details/gtdhdbzajf.html

[Q17] 条件查询
来源：http://dali.zhongyouzk.top/Article/details/gtnwuwdeyi.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hywenlv.cn/Article/details/gtljthgynh.html

[Q18] 模糊匹配
来源：http://dali.hnxiangtu.top/Article/details/gtjqkjciaq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.snrcjt.cn/Article/details/gtrwjvnhdj.html

[Q19] 范围查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzthqdunf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinqigufen.top/Article/details/gtmbuwzaal.html

[Q20] IN 列表
来源：http://dali.hnqzz.top/Article/details/gtssegrxbd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnrsklhko.html

[Q21] 空值判断
来源：http://dali.chenlongwang.top/Article/details/gtthmtvrbe.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jyoumei.cn/Article/details/gtivewrlkv.html

[Q22] 排序
来源：http://dali.dianchejie.cn/Article/details/gtzmnqsqax.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yj20258888.top/Article/details/gtjqnscnnq.html

[Q23] 分页
来源：http://dali.ybcxt.top/Article/details/gtwxrnrdej.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.nanxinkj.top/Article/details/gtguvwkrat.html

[Q24] 去重
来源：http://dali.chenzaomai.com/Article/details/gtunnwmjcd.html

SELECT DISTINCT city FROM users;
来源：http://dali.fengsongda.top/Article/details/gtuuneqgzu.html

[Q25] 只取前 N 条
来源：http://dali.fengsongda.top/Article/details/gtzwkhvkck.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ybcxt.top/Article/details/gtyimjwtya.html

[Q26] 计数
来源：http://dali.jqgufenzy.top/Article/details/gtxanqruvu.html

SELECT COUNT(*) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtxyxjrdcc.html

[Q27] 条件计数
来源：http://dali.zdqjudy.top/Article/details/gtshcghagq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtigrjwjxj.html

[Q28] 求和与平均
来源：http://dali.guowangkeji.top/Article/details/gtwpjnqhcr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gtgbfsitzi.html

[Q29] 最大最小值
来源：http://dali.iojbl.cn/Article/details/gtpmmdkwla.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.andypj.xyz/Article/details/gtzprtagos.html

[Q30] 分组统计
来源：http://dali.svipenyu.cn/Article/details/gtrgiidilr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.316326.xyz/Article/details/gtslvfjajk.html

[Q31] 分组后过滤
来源：http://dali.ehwqpu.com/Article/details/gtbyoyjiuh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.pycfn.com/Article/details/gtcimmbesc.html

[Q32] 分组拼接字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtoqudqtdb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cucudq.cn/Article/details/gtheooxmns.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.pycfn.com/Article/details/gthmywyajd.html

[Q33] 多列分组
来源：http://dali.nanxuanxn.top/Article/details/gtdbhcuryu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.nanxinkj.top/Article/details/gthqdvuhfw.html

[Q34] 每组取第一条
来源：http://dali.zhengqikj.top/Article/details/gtcwucjtyt.html

SELECT * FROM (
来源：http://dali.cheryme.top/Article/details/gtjbrtrpwk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shanyushiyangtech.top/Article/details/gtarndsijs.html

) t WHERE rn = 1;
来源：http://dali.pycfn.com/Article/details/gtxlbnxefq.html

[Q35] 内连接
来源：http://dali.yvedp.cn/Article/details/gtbcxwohaf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.aizwys.cn/Article/details/gteindydfr.html

[Q36] 左连接
来源：http://dali.sysykeji.top/Article/details/gthxalgcex.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.iojbl.cn/Article/details/gtwyotdail.html

[Q37] 右连接
来源：http://dali.yvedp.cn/Article/details/gtwxghidax.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.svipenyu.cn/Article/details/gtvbkcyihz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cdnleiting.top/Article/details/gtqcwnsatu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cheryme.top/Article/details/gtdcnhcdzy.html

[Q39] 自连接（查上下级）
来源：http://dali.sweek.top/Article/details/gtpvxkxjtj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cheryme.top/Article/details/gticqtdegh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.quarkkingdee.top/Article/details/gtnaswzjrm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.pengpengdd.cyou/Article/details/gtaoubxqql.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xuetiantiany.cn/Article/details/gtvcpgyrqq.html

[Q41] 多表连接
来源：http://dali.haohaochexian.top/Article/details/gtmluicvxy.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.havefunace.top/Article/details/gtkyfqvtyb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gtpljacthq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.9152youxi.cn/Article/details/gtmfidnzmx.html

[Q42] 连接条件附加过滤
来源：http://dali.jiagoushi.top/Article/details/gtkghgbzzv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jiagoushi.top/Article/details/gtxjrrjdfl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hammf.cn/Article/details/gtdnbjvpwg.html

[Q43] 标量子查询
来源：http://dali.hywenlv.cn/Article/details/gttwjydflq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.nwbrower.top/Article/details/gtmffgjddp.html

[Q44] IN 子查询
来源：http://dali.dashuyun.cn/Article/details/gtflzlfged.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmjosvpsw.html

[Q45] EXISTS 判断存在
来源：http://dali.jqgfzy.top/Article/details/gtnlovfycj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jiagoushi.top/Article/details/gtdgvecgqn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.dashuyun.cn/Article/details/gteqeyefsz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinqigfzy.top/Article/details/gteezofvhh.html

[Q47] 与平均值比较
来源：http://dali.hfpthk.cn/Article/details/gtoibfklgw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.guannengcc.top/Article/details/gtvtttugcm.html

[Q48] CTE 公用表表达式
来源：http://dali.cucudq.cn/Article/details/gtrdfgvcnd.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jiagoushi.top/Article/details/gtuemqaijc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yueranfly.top/Article/details/gtvcpvkolx.html

[Q49] 更新单行
来源：http://dali.cashguo.top/Article/details/gttizneinr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.wangdashe.top/Article/details/gtarcptxkf.html

[Q50] 批量更新
来源：http://dali.yangfankeji.com/Article/details/gtjacpjmnq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hnxiangtu.top/Article/details/gtjykjvupd.html

[Q51] 用子查询更新
来源：http://dali.quarkkingdee.top/Article/details/gtjfqafopt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shzxlz.cn/Article/details/gtnsqgvndq.html

[Q52] 删除指定行
来源：http://dali.yj202588.top/Article/details/gtkbcqckrz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.chenlongwang.top/Article/details/gtkxnugmgz.html

[Q53] 按条件删除
来源：http://dali.dashuyun.cn/Article/details/gtxphueogy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.aibaodan.cn/Article/details/gtilmuufwa.html

[Q54] 清空表
来源：http://dali.shangyingyoupin.top/Article/details/gtflvndbxn.html

TRUNCATE TABLE logs;
来源：http://dali.ivvv.top/Article/details/gtzstmaixo.html

[Q55] 排名（并列占位）
来源：http://dali.ppjwa.cn/Article/details/gtaxwsaktb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtprwxsaox.html

[Q56] 密集排名（并列不占位）
来源：http://dali.aibaodan.cn/Article/details/gtpifolcrl.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jianghu66.top/Article/details/gtrodaweel.html

[Q57] 行号
来源：http://dali.xinyue.icu/Article/details/gtworkwkvg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yueranfly.top/Article/details/gtipucuvxy.html

[Q58] 累计求和
来源：http://dali.aibaodan.cn/Article/details/gttifinlhw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ydzc1.top/Article/details/gtqfrrxpef.html

[Q59] 分组内累计
来源：http://dali.jinqigufen.top/Article/details/gtnmcpvgbu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtonzmnzyr.html

[Q60] 取上一行 / 下一行
来源：http://dali.gotoacloud.top/Article/details/gtxlgqyygx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.havefunace.top/Article/details/gtfylrqggr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gtsfpoiumc.html

[Q61] 移动平均
来源：http://dali.shangyingyoupin.top/Article/details/gtcmonowbs.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.pycfn.com/Article/details/gtbgfkusio.html

[Q62] 分组占比
来源：http://dali.yj20258.top/Article/details/gtxvtpdxup.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.chenjidiqi.icu/Article/details/gtlakatajh.html

[Q63] 开启事务
来源：http://dali.yanxiufei.cn/Article/details/gtzhnpedsu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.dianchejie.cn/Article/details/gturnrvmmc.html

[Q64] 提交事务
来源：http://dali.yvedp.cn/Article/details/gtfssvuhuv.html

COMMIT;
来源：http://dali.yangfankeji.com/Article/details/gthshehejq.html

[Q65] 回滚事务
来源：http://dali.yuanzhike.top/Article/details/gtrfyilfgb.html

ROLLBACK;
来源：http://dali.birdmap.top/Article/details/gtjhzxctho.html

[Q66] 行锁查询
来源：http://dali.yuanzhike.top/Article/details/gtvcztfilr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.quarkkingdee.top/Article/details/gtrylmyfut.html

[Q67] 设置隔离级别
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkdfqjzbq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yvedp.cn/Article/details/gtyrkgspej.html

[Q68] 保存点
来源：http://dali.yj20258.top/Article/details/gtkuiwppkm.html

SAVEPOINT sp1;
来源：http://dali.cucudq.cn/Article/details/gtbbyicakb.html

ROLLBACK TO sp1;
来源：http://dali.sysykeji.top/Article/details/gtjmlimndq.html

[Q69] 查看执行计划
来源：http://dali.sweek.top/Article/details/gtebvwhdhs.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yj202588.top/Article/details/gtebilvmcu.html

[Q70] 更新统计信息
来源：http://dali.yuanzhike.top/Article/details/gtsrkqyirr.html

ANALYZE TABLE users;
来源：http://dali.gzhubu.top/Article/details/gtyuugrhfi.html

[Q71] 查看建表语句
来源：http://dali.gogol.net.cn/Article/details/gtcrcmface.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yj20258888.top/Article/details/gtmykfvtpg.html

[Q72] 查看索引
来源：http://dali.cqqwz.cn/Article/details/gtfoxsufyc.html

SHOW INDEX FROM users;
来源：http://dali.sweek.top/Article/details/gtfkifzhfu.html

[Q73] 查看表状态
来源：http://dali.jinyuanbaomall.cn/Article/details/gtckdymtvx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yanxiufei.cn/Article/details/gtkvwigxfs.html

[Q74] 强制使用索引
来源：http://dali.gzhubu.top/Article/details/gtonhxxuqz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqsyvvxla.html

[Q75] 日期格式化
来源：http://dali.pycfn.com/Article/details/gtheebwxma.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yongpay.top/Article/details/gtomrgewfc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.meibo888.top/Article/details/gtrjatlhvi.html

[Q76] 按天统计
来源：http://dali.tanke756.top/Article/details/gtmnwemoiw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.wangdashe.top/Article/details/gtdcqqjdfg.html

[Q77] 时间加减
来源：http://dali.gogol.net.cn/Article/details/gtgycnradc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyaxafftj.html

[Q78] 当前时间
来源：http://dali.yj202588.top/Article/details/gtirbjpbmc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.snrcjt.cn/Article/details/gtderegvdx.html

[Q79] 字符串拼接
来源：http://dali.hongshengwenyu.top/Article/details/gtissuahgk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gzhubu.top/Article/details/gttblgnwwt.html

[Q80] 字符串截取
来源：http://dali.tianlin.xyz/Article/details/gtxoewykgy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.wangdashe.top/Article/details/gtnnklluyq.html

[Q81] 字符串替换
来源：http://dali.wangdashe.top/Article/details/gtktgdcqiz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.birdmap.top/Article/details/gtxhutqnqg.html

[Q82] 字符长度与字节长度
来源：http://dali.chenzaomai.com/Article/details/gtfzwokiir.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtotjewlsq.html

[Q83] 大小写转换
来源：http://dali.xinyue.icu/Article/details/gtzmcmbagz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.wangdashe.top/Article/details/gtqhghhlza.html

[Q84] 去除首尾空格
来源：http://dali.bjfxy.top/Article/details/gtghxtayrr.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtccvsvwxm.html

[Q85] 数值取整
来源：http://dali.wangshuangyany.cn/Article/details/gtgwhoviod.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hammf.cn/Article/details/gtoaqsddrx.html

[Q86] 读取 JSON 字段
来源：http://dali.xinyue.icu/Article/details/gtpiiaesyh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yongpay.top/Article/details/gtsknjdsee.html

[Q87] JSON 字段做条件
来源：http://dali.ybcxt.top/Article/details/gtxlmfhmnp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.snrcjt.cn/Article/details/gttfjoaduv.html

[Q88] 行转列（条件聚合）
来源：http://dali.cqqwz.cn/Article/details/gtwjhidolh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.haohaochexian.top/Article/details/gtpblvtqbd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.tanke756.top/Article/details/gthnmemoas.html

[Q89] 判断表是否存在
来源：http://dali.zhiwuduotai.top/Article/details/gthzelwdjs.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.quarkkingdee.top/Article/details/gtlskkwtde.html

[Q90] 生成序号列
来源：http://dali.jqgufenzy.top/Article/details/gtfdwehqob.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.aizwys.cn/Article/details/gtgwmdnbjc.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtozhyppwy.html

R. Bash 专题
来源：http://dali.ivvv.top/Article/details/gtwelejgig.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtnhmllnar.html

[R01] shebang 与严格模式
来源：http://dali.pengpengdd.cyou/Article/details/gtlfsqqnov.html

#!/usr/bin/env bash
来源：http://dali.tianlin.xyz/Article/details/gtbfxymefs.html

set -euo pipefail
来源：http://dali.bjfxy.top/Article/details/gtzsrxilzr.html

[R02] 变量赋值与使用
来源：http://dali.mhx1999.top/Article/details/gtpodcaeip.html

name="Tom"; echo "$name"
来源：http://dali.cheryme.top/Article/details/gtfaaoeuuy.html

[R03] 只读变量
来源：http://dali.hnqzz.top/Article/details/gttrwdxlvz.html

readonly PI=3.14
来源：http://dali.smart0.xyz/Article/details/gttyeriyun.html

[R04] 位置参数
来源：http://dali.daxiang520.top/Article/details/gtyhqkdujb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xuetiantiany.cn/Article/details/gtmetlgzaj.html

[R05] 参数默认值
来源：http://dali.yj20258888.top/Article/details/gtucrdmgdw.html

name="${1:-default}"
来源：http://dali.haohaochexian.top/Article/details/gtcfaurdff.html

[R06] 判断命令是否存在
来源：http://dali.gaohongyu789.top/Article/details/gtswxhtctn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.nanxuanxn.top/Article/details/gttsscazzd.html

[R07] if 判断文件
来源：http://dali.yj20258.top/Article/details/gtmbjkneez.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cheryme.top/Article/details/gtxxyogbal.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gtzqrafdin.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jyoumei.cn/Article/details/gtbltpbici.html

[R09] 字符串比较
来源：http://dali.hnxiangtu.top/Article/details/gtgokrfjtw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.dianchejie.cn/Article/details/gtxkndapol.html

[R10] 正则匹配
来源：http://dali.9152youxi.cn/Article/details/gtzwqfzmzs.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jinghuilouyu.cn/Article/details/gtvywzoccy.html

[R11] case 多分支
来源：http://dali.xuanzx.com/Article/details/gthywmdzvq.html

case "$1" in
来源：http://dali.yanxiufei.cn/Article/details/gtbssaxagr.html

start) echo "启动" ;;
来源：http://dali.yanxiufei.cn/Article/details/gttvvmyrpv.html

stop)  echo "停止" ;;
来源：http://dali.hnxiangtu.top/Article/details/gtblbktuee.html

*)     echo "未知命令" ;;
来源：http://dali.ydzc1.top/Article/details/gtnpxhcwuc.html

esac
来源：http://dali.xylfe.cn/Article/details/gtpfgktbdz.html

[R12] for 遍历文件
来源：http://dali.yj20258.top/Article/details/gtysyxpzmz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sufxvd.cn/Article/details/gtolzxryki.html

[R13] for 计数循环
来源：http://dali.jqgufenzy.top/Article/details/gtazvgkcxg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shzxlz.cn/Article/details/gtpaihvqju.html

[R14] C 风格 for
来源：http://dali.gzhubu.top/Article/details/gtdtnvstqi.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ydzc1.top/Article/details/gtuvrvjapw.html

[R15] while 逐行读文件
来源：http://dali.yongpay.top/Article/details/gtivhsigke.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.smart0.xyz/Article/details/gthecyexgq.html

[R16] until 等待条件
来源：http://dali.pycfn.com/Article/details/gtutzqaqgo.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gtticnmowh.html

[R17] 数组定义与取值
来源：http://dali.dashuyun.cn/Article/details/gtlunuehjh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjdorsqjd.html

[R18] 遍历数组
来源：http://dali.ybcxt.top/Article/details/gtgbdgyreh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gotoacloud.top/Article/details/gtilzqcxxh.html

[R19] 数组长度
来源：http://dali.jinqigfzy.top/Article/details/gtyclodmob.html

echo "${#arr[@]}"
来源：http://dali.bjfxy.top/Article/details/gtqgectfnz.html

[R20] 关联数组（字典）
来源：http://dali.ehwqpu.com/Article/details/gtvzbhzxdm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.pengpengdd.cyou/Article/details/gtwzovqkta.html

[R21] 字符串长度
来源：http://dali.yj20258.top/Article/details/gtfzqwdmhd.html

echo "${#s}"
来源：http://dali.cqqwz.cn/Article/details/gtumeczokb.html

[R22] 截取子串
来源：http://dali.pengpengdd.cyou/Article/details/gtsbwytcxd.html

echo "${s:0:5}"
来源：http://dali.jiagoushi.top/Article/details/gtwpiqqvnk.html

[R23] 字符串替换
来源：http://dali.hywenlv.cn/Article/details/gtwseeciwm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsnitxedp.html

[R24] 大小写转换
来源：http://dali.chenzaomai.com/Article/details/gtexsxlcfr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yongpay.top/Article/details/gtivicwrfn.html

[R25] 去后缀 / 去前缀
来源：http://dali.daxiang520.top/Article/details/gtrfvywnpf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhixingplan.top/Article/details/gtmmzatwbn.html

[R26] 命令替换
来源：http://dali.redwolf501.top/Article/details/gtycgxvndm.html

now=$(date +%F); echo "$now"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxphhlfsq.html

[R27] 算术展开
来源：http://dali.ydzc1.top/Article/details/gtsgkxvkzg.html

echo $((1 + 2 * 3))
来源：http://dali.wangdashe.top/Article/details/gtbmryplkj.html

[R28] 浮点运算
来源：http://dali.yvedp.cn/Article/details/gtpsdlbqyt.html

echo "scale=2; 10/3" | bc
来源：http://dali.bjfxy.top/Article/details/gtpxxmypbw.html

[R29] 定义函数
来源：http://dali.daria6918.cn/Article/details/gtallttwsx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.nwbrower.top/Article/details/gteydqvbbi.html

[R30] 函数返回状态码
来源：http://dali.shuidangran.top/Article/details/gtuyxycbza.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.nanxinkj.top/Article/details/gteqzqaslx.html

[R31] 局部变量
来源：http://dali.ehwqpu.com/Article/details/gtwvkrxzvt.html

f() { local x=1; echo "$x"; }
来源：http://dali.guowangkeji.top/Article/details/gtovipntdk.html

[R32] 参数个数校验
来源：http://dali.cucudq.cn/Article/details/gtanrftkde.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.pengpengdd.cyou/Article/details/gtwlmpuzxr.html

[R33] 捕获错误并提示行号
来源：http://dali.havefunace.top/Article/details/gtwcpwufkv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.316326.xyz/Article/details/gtzosrpbdm.html

[R34] 退出时清理
来源：http://dali.yj20258888.top/Article/details/gtagiqbuov.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwzuqwjdx.html

[R35] 后台执行并等待
来源：http://dali.shanyushiyangtech.top/Article/details/gtgpmclqva.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.tanke756.top/Article/details/gtokhluhdz.html

[R36] 并发执行多个任务
来源：http://dali.quarkkingdee.top/Article/details/gteakihbay.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jiagoushi.top/Article/details/gtdywxwqmw.html

[R37] 把输出赋给变量
来源：http://dali.bjfxy.top/Article/details/gtpbabqwgk.html

files=$(ls -1)
来源：http://dali.sysykeji.top/Article/details/gtawexhune.html

[R38] 管道串联
来源：http://dali.haohaochexian.top/Article/details/gtvdlxdoga.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhixingplan.top/Article/details/gtfivkeuor.html

[R39] 重定向标准输出与错误
来源：http://dali.chenlongwang.top/Article/details/gtruhghrzd.html

cmd > out.log 2>&1
来源：http://dali.ybcxt.top/Article/details/gtzxidvgiz.html

[R40] 追加写日志
来源：http://dali.daxiang520.top/Article/details/gtquhdrkdt.html

echo "log" >> out.log
来源：http://dali.pycfn.com/Article/details/gtelubexzh.html

[R41] 丢弃输出
来源：http://dali.hammf.cn/Article/details/gtuvufzmdg.html

cmd >/dev/null 2>&1
来源：http://dali.nanxinkj.top/Article/details/gtmogldlbx.html

[R42] 输入重定向
来源：http://dali.hywenlv.cn/Article/details/gtamcjvclr.html

wc -l < a.txt
来源：http://dali.haohaochexian.top/Article/details/gtntjlgupy.html

[R43] 按名字查找文件
来源：http://dali.zhoulong.xyz/Article/details/gtmnghpmdw.html

find . -name "*.log" -type f
来源：http://dali.xuetiantiany.cn/Article/details/gtlewxjrgb.html

[R44] 按修改时间查找
来源：http://dali.hysaishi.cn/Article/details/gttpjloyil.html

find . -mtime -7 -type f
来源：http://dali.fengsongda.top/Article/details/gtkhehpwry.html

[R45] 批量删除
来源：http://dali.xylfe.cn/Article/details/gtwqddtxgu.html

find . -name "*.tmp" -delete
来源：http://dali.yj202588.top/Article/details/gtmngoyphz.html

[R46] 递归替换文件内容
来源：http://dali.yj20258888.top/Article/details/gtlgnxsjkn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.chenlongwang.top/Article/details/gtcatbifwi.html

[R47] sed 单行替换
来源：http://dali.ybcxt.top/Article/details/gtokpdcoaw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.andypj.xyz/Article/details/gtqbsdchdh.html

[R48] awk 取指定列
来源：http://dali.jiagoushi.top/Article/details/gtiraiioae.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhongyouzk.top/Article/details/gtgorfzwaa.html

[R49] awk 带条件
来源：http://dali.quarkkingdee.top/Article/details/gtjuesdiwa.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ppjwa.cn/Article/details/gtkvsaxmsp.html

[R50] awk 求和
来源：http://dali.iojbl.cn/Article/details/gtphbdurfd.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gtdbpbrtba.html

[R51] 排序去重取前几
来源：http://dali.jlsjyb.cn/Article/details/gtygoqhrbf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.redwolf501.top/Article/details/gttyltfsdw.html

[R52] 统计行数
来源：http://dali.wangshuangyany.cn/Article/details/gtbfjywuqn.html

wc -l a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtnengplxl.html

[R53] 查看文件头与实时尾
来源：http://dali.aizwys.cn/Article/details/gtpjhckauu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.0kj1m.cn/Article/details/gtkcrwhhci.html

[R54] 比较两个文件
来源：http://dali.fengsongda.top/Article/details/gtfhhtqmct.html

diff a.txt b.txt
来源：http://dali.smart0.xyz/Article/details/gtujtxjokn.html

[R55] 压缩与解压
来源：http://dali.mhx1999.top/Article/details/gtuyxcjutu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xinyue.icu/Article/details/gtrlzcftmx.html

[R56] 远程拷贝
来源：http://dali.wangshuangyany.cn/Article/details/gtugrcbnkv.html

scp file user@host:/path/
来源：http://dali.daria6918.cn/Article/details/gtsraebdse.html

[R57] 远程执行命令
来源：http://dali.jinqigufen.top/Article/details/gtliplnuzu.html

ssh user@host 'uptime'
来源：http://dali.ydzc1.top/Article/details/gtiqwdkxlj.html

[R58] 下载文件
来源：http://dali.0kj1m.cn/Article/details/gtulqgeeyk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gzhubu.top/Article/details/gtwmmpsnff.html

[R59] 发 POST JSON
来源：http://dali.jiagoushi.top/Article/details/gthktmzrvs.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xuetiantiany.cn/Article/details/gtcfewjqxo.html

[R60] 只看 HTTP 状态码
来源：http://dali.hnxiangtu.top/Article/details/gthmokkfzo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.vqdsnc.cn/Article/details/gtcnxjpyuc.html

[R61] 磁盘占用
来源：http://dali.9152youxi.cn/Article/details/gtornwrwdk.html

df -h;  du -sh *
来源：http://dali.0kj1m.cn/Article/details/gtceqrhvsx.html

[R62] 找最占空间的文件
来源：http://dali.ehwqpu.com/Article/details/gtyskorycc.html

du -ah . | sort -rh | head -10
来源：http://dali.nanxinkj.top/Article/details/gtcattwvfm.html

[R63] 内存与进程
来源：http://dali.yvedp.cn/Article/details/gtsbetahbz.html


<!-- 参考信息 -->