代发 wailian999

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ckhalmpn.html

[Q24] 去重
来源：http://dali.birdmap.top/Article/details/gt2hpvxojpd.html

SELECT DISTINCT city FROM users;
来源：http://dali.birdmap.top/Article/details/gt2fkqvjyfa.html

[Q25] 只取前 N 条
来源：http://dali.tian-w.cn/Article/details/gt2qrmfaguq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.aibaodan.cn/Article/details/gt2gtgbangc.html

[Q26] 计数
来源：http://dali.guowangkeji.top/Article/details/gt2urgtjrkz.html

SELECT COUNT(*) FROM users;
来源：http://dali.meibo888.top/Article/details/gt2mdbmtzdu.html

[Q27] 条件计数
来源：http://dali.shzxlz.cn/Article/details/gt2wcrbrifu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2dtmlaznh.html

[Q28] 求和与平均
来源：http://dali.ivvv.top/Article/details/gt2rrijxhma.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gt2tfsqjfmc.html

[Q29] 最大最小值
来源：http://dali.yj202588.top/Article/details/gt2uxoouwci.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2dnmxquzn.html

[Q30] 分组统计
来源：http://dali.9152youxi.cn/Article/details/gt2tpbhkada.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhiwuduotai.top/Article/details/gt2wlqmibxz.html

[Q31] 分组后过滤
来源：http://dali.chenjidiqi.icu/Article/details/gt2gibrvmlq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yj202588.top/Article/details/gt2rjqziqiq.html

[Q32] 分组拼接字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2vtaicuuu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.tanke756.top/Article/details/gt2nymhmykx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.aizwys.cn/Article/details/gt2pdquqqbl.html

[Q33] 多列分组
来源：http://dali.sweek.top/Article/details/gt2oosqfqep.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.havefunace.top/Article/details/gt2nvxpgapg.html

[Q34] 每组取第一条
来源：http://dali.jyoumei.cn/Article/details/gt2bgqpshlb.html

SELECT * FROM (
来源：http://dali.9152youxi.cn/Article/details/gt2qzieuafq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.sufxvd.cn/Article/details/gt2lcukwzpq.html

) t WHERE rn = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nexbclrg.html

[Q35] 内连接
来源：http://dali.sufxvd.cn/Article/details/gt2znebdqfp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.sweek.top/Article/details/gt2gbdzearo.html

[Q36] 左连接
来源：http://dali.shuidangran.top/Article/details/gt2ocdqxlff.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.smart0.xyz/Article/details/gt2uqrpvzry.html

[Q37] 右连接
来源：http://dali.gzhubu.top/Article/details/gt2pigwimuq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gzhubu.top/Article/details/gt2xnzxufws.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cashguo.top/Article/details/gt2ptqppais.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cdnleiting.top/Article/details/gt2uozebnxm.html

[Q39] 自连接（查上下级）
来源：http://dali.dashuyun.cn/Article/details/gt2mymzaher.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.wangshuangyany.cn/Article/details/gt2rcyooeyz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ybcxt.top/Article/details/gt2aiajpwar.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zschqtqq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cdnleiting.top/Article/details/gt2aprzuauj.html

[Q41] 多表连接
来源：http://dali.c1oappe.top/Article/details/gt2vrzljrlk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yj20258.top/Article/details/gt2dxmphuly.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hongshengwenyu.top/Article/details/gt2onwjmhmb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.smart0.xyz/Article/details/gt2zgxkpqll.html

[Q42] 连接条件附加过滤
来源：http://dali.meibo888.top/Article/details/gt2nobazztw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jinqigufen.top/Article/details/gt2fvivianz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ivvv.top/Article/details/gt2ucbgqgrk.html

[Q43] 标量子查询
来源：http://dali.xuanzx.com/Article/details/gt2abrknunv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cheryme.top/Article/details/gt2miusaxrw.html

[Q44] IN 子查询
来源：http://dali.hongshengwenyu.top/Article/details/gt2dkgbxpks.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xylfe.cn/Article/details/gt2osaviqwy.html

[Q45] EXISTS 判断存在
来源：http://dali.kuanghao11.cn/Article/details/gt2jzsbwoze.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.quarkkingdee.top/Article/details/gt2vejmyqvg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.0kj1m.cn/Article/details/gt2boflinqz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cucudq.cn/Article/details/gt2dqsitpdi.html

[Q47] 与平均值比较
来源：http://dali.kuanghao11.cn/Article/details/gt2sxmdezbe.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yuxming.cn/Article/details/gt2xkjrufwr.html

[Q48] CTE 公用表表达式
来源：http://dali.ivvv.top/Article/details/gt2zqlivwpm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qcxiabpb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sweek.top/Article/details/gt2acdiiisl.html

[Q49] 更新单行
来源：http://dali.yj202588.top/Article/details/gt2kfdzhnfj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ppjwa.cn/Article/details/gt2oembepcj.html

[Q50] 批量更新
来源：http://dali.zhoulong.xyz/Article/details/gt2edumashm.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.tian-w.cn/Article/details/gt2izlxxrus.html

[Q51] 用子查询更新
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dywaorkl.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hfpthk.cn/Article/details/gt2qefaefze.html

[Q52] 删除指定行
来源：http://dali.svipenyu.cn/Article/details/gt2aakfmmlb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhixingplan.top/Article/details/gt2aqnmddve.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjzpgpj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhongyouzk.top/Article/details/gt2mlayvaei.html

[Q54] 清空表
来源：http://dali.hywenlv.cn/Article/details/gt2ruuxfuhj.html

TRUNCATE TABLE logs;
来源：http://dali.zhengqikj.top/Article/details/gt2dcqgvzlp.html

[Q55] 排名（并列占位）
来源：http://dali.sysykeji.top/Article/details/gt2rydvajuv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.wangshuangyany.cn/Article/details/gt2tjwtsqjr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.wangdashe.top/Article/details/gt2dwaxmkbk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.quarkkingdee.top/Article/details/gt2ysjfcoiz.html

[Q57] 行号
来源：http://dali.yj202588.top/Article/details/gt2udolcebx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2vtcgwdgc.html

[Q58] 累计求和
来源：http://dali.zycfv.cn/Article/details/gt2jkostell.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gt2ozjprtsr.html

[Q59] 分组内累计
来源：http://dali.yj20258.top/Article/details/gt2utotnusa.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gt2zygaydkd.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhiwuduotai.top/Article/details/gt2rdguycre.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hnqzz.top/Article/details/gt2oajitdud.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gzhubu.top/Article/details/gt2wueqyyfh.html

[Q61] 移动平均
来源：http://dali.0kj1m.cn/Article/details/gt2tbosgzjl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.316326.xyz/Article/details/gt2gfriuqqd.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2dhbbyhjp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.chenlongwang.top/Article/details/gt2qanxfilh.html

[Q63] 开启事务
来源：http://dali.9152youxi.cn/Article/details/gt2wnujojyc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jianghu66.top/Article/details/gt2gdgkmxge.html

[Q64] 提交事务
来源：http://dali.ivvv.top/Article/details/gt2zazejqfi.html

COMMIT;
来源：http://dali.hnxiangtu.top/Article/details/gt2ozsgaegr.html

[Q65] 回滚事务
来源：http://dali.tianlin.xyz/Article/details/gt2jdllmcnr.html

ROLLBACK;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2egqzhawk.html

[Q66] 行锁查询
来源：http://dali.daria6918.cn/Article/details/gt2fxuuyggl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhoulong.xyz/Article/details/gt2zwelkrer.html

[Q67] 设置隔离级别
来源：http://dali.yueranfly.top/Article/details/gt2pprfnaad.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.aizwys.cn/Article/details/gt2wznjewnn.html

[Q68] 保存点
来源：http://dali.birdmap.top/Article/details/gt2poczbbsd.html

SAVEPOINT sp1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gibbbkwm.html

ROLLBACK TO sp1;
来源：http://dali.daxiang520.top/Article/details/gt2yhtfmqid.html

[Q69] 查看执行计划
来源：http://dali.tianlin.xyz/Article/details/gt2hjpfawcq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.vqdsnc.cn/Article/details/gt2wfjgfpbb.html

[Q70] 更新统计信息
来源：http://dali.yj20258888.top/Article/details/gt2jbkkovzy.html

ANALYZE TABLE users;
来源：http://dali.aizwys.cn/Article/details/gt2vnuhooxo.html

[Q71] 查看建表语句
来源：http://dali.xinyue.icu/Article/details/gt2ppexodkq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jianghu66.top/Article/details/gt2swxhhldg.html

[Q72] 查看索引
来源：http://dali.smart0.xyz/Article/details/gt2kwnmzgkb.html

SHOW INDEX FROM users;
来源：http://dali.hammf.cn/Article/details/gt2jpwwouan.html

[Q73] 查看表状态
来源：http://dali.tian-w.cn/Article/details/gt2seatoblq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xuetiantiany.cn/Article/details/gt2rjuqqggc.html

[Q74] 强制使用索引
来源：http://dali.ybcxt.top/Article/details/gt2kyhijkwo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.fzhhl.top/Article/details/gt2nczeosdc.html

[Q75] 日期格式化
来源：http://dali.andypj.xyz/Article/details/gt2expfvbyd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gt2iewvgffq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.mhx1999.top/Article/details/gt2tltpwoor.html

[Q76] 按天统计
来源：http://dali.snrcjt.cn/Article/details/gt2biamdugy.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jinqigfzy.top/Article/details/gt2vohejjyo.html

[Q77] 时间加减
来源：http://dali.hammf.cn/Article/details/gt2xyxjexai.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hysaishi.cn/Article/details/gt2hsslzmdj.html

[Q78] 当前时间
来源：http://dali.sysykeji.top/Article/details/gt2rdkklbbc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shuidangran.top/Article/details/gt2mcjmohnc.html

[Q79] 字符串拼接
来源：http://dali.shangyingyoupin.top/Article/details/gt2hskqrbef.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhengqikj.top/Article/details/gt2fhgwuyhi.html

[Q80] 字符串截取
来源：http://dali.ppjwa.cn/Article/details/gt2pshhvpml.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2ryjukntv.html

[Q81] 字符串替换
来源：http://dali.tianlin.xyz/Article/details/gt2jikmhrmd.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2sedjvgxk.html

[Q82] 字符长度与字节长度
来源：http://dali.316326.xyz/Article/details/gt2piwawnlv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gt2jqhtumax.html

[Q83] 大小写转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ehrfvwwv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2wnxftbth.html

[Q84] 去除首尾空格
来源：http://dali.redwolf501.top/Article/details/gt2glvitrso.html

SELECT TRIM(name) FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2ucuayymo.html

[Q85] 数值取整
来源：http://dali.yueranfly.top/Article/details/gt2ozgytoyg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yj202588.top/Article/details/gt2epmzyjlw.html

[Q86] 读取 JSON 字段
来源：http://dali.smart0.xyz/Article/details/gt2bsvdpqfx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.nanxinkj.top/Article/details/gt2wfnaxhta.html

[Q87] JSON 字段做条件
来源：http://dali.havefunace.top/Article/details/gt2oljwdona.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.sxryk.cn/Article/details/gt2jgntklin.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhiwuduotai.top/Article/details/gt2qgudvndi.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.meibo888.top/Article/details/gt2slxlnlvl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cheryme.top/Article/details/gt2ptpufarz.html

[Q89] 判断表是否存在
来源：http://dali.yuxming.cn/Article/details/gt2pivmxpyi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lzjivckr.html

[Q90] 生成序号列
来源：http://dali.nwbrower.top/Article/details/gt2sfdukqkt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tanke756.top/Article/details/gt2sckieqmf.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2robgpubp.html

R. Bash 专题
来源：http://dali.vqdsnc.cn/Article/details/gt2yjhhgmqv.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2qqturftn.html

[R01] shebang 与严格模式
来源：http://dali.zycfv.cn/Article/details/gt2fomidnds.html

#!/usr/bin/env bash
来源：http://dali.sxryk.cn/Article/details/gt2ujibugfy.html

set -euo pipefail
来源：http://dali.fzhhl.top/Article/details/gt2lzukhctd.html

[R02] 变量赋值与使用
来源：http://dali.smart0.xyz/Article/details/gt2kksmfosj.html

name="Tom"; echo "$name"
来源：http://dali.meibo888.top/Article/details/gt2neqtevid.html

[R03] 只读变量
来源：http://dali.gotoacloud.top/Article/details/gt2jvaxjbxd.html

readonly PI=3.14
来源：http://dali.xylfe.cn/Article/details/gt2cuvjjzbb.html

[R04] 位置参数
来源：http://dali.nwbrower.top/Article/details/gt2lngjuwzu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hnxiangtu.top/Article/details/gt2dlfwjdiy.html

[R05] 参数默认值
来源：http://dali.yvedp.cn/Article/details/gt2bcgikkgv.html

name="${1:-default}"
来源：http://dali.ybcxt.top/Article/details/gt2oszfbbgn.html

[R06] 判断命令是否存在
来源：http://dali.dashuyun.cn/Article/details/gt2rixuovsm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ydzc1.top/Article/details/gt2elaarclo.html

[R07] if 判断文件
来源：http://dali.ydzc1.top/Article/details/gt2iichzkia.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.tanke756.top/Article/details/gt2cmzbamay.html

[R08] 数值比较
来源：http://dali.shuidangran.top/Article/details/gt2rsammrzb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhoulong.xyz/Article/details/gt2swsfdvaw.html

[R09] 字符串比较
来源：http://dali.yueranfly.top/Article/details/gt2fzchqmqz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shzxlz.cn/Article/details/gt2flwkhvlz.html

[R10] 正则匹配
来源：http://dali.nwbrower.top/Article/details/gt2hsovbnxh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.vqdsnc.cn/Article/details/gt2cdiqnrgl.html

[R11] case 多分支
来源：http://dali.ivvv.top/Article/details/gt2hfgiabmc.html

case "$1" in
来源：http://dali.xuetiantiany.cn/Article/details/gt2jsnxilkl.html

start) echo "启动" ;;
来源：http://dali.sxryk.cn/Article/details/gt2vbboanod.html

stop)  echo "停止" ;;
来源：http://dali.hongshengwenyu.top/Article/details/gt2znzofsvs.html

*)     echo "未知命令" ;;
来源：http://dali.birdmap.top/Article/details/gt2dqvtxgbt.html

esac
来源：http://dali.shangyingyoupin.top/Article/details/gt2bviztdla.html

[R12] for 遍历文件
来源：http://dali.jinqigufen.top/Article/details/gt2iwnfqtoa.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jlsjyb.cn/Article/details/gt2hdzdijmz.html

[R13] for 计数循环
来源：http://dali.sweek.top/Article/details/gt2eddgwpum.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.iojbl.cn/Article/details/gt2zgxldimf.html

[R14] C 风格 for
来源：http://dali.yj20258.top/Article/details/gt2jaagsbtp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhoulong.xyz/Article/details/gt2ynnerfsw.html

[R15] while 逐行读文件
来源：http://dali.c1oappe.top/Article/details/gt2yyserkxx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yj202588.top/Article/details/gt2nxlhxcms.html

[R16] until 等待条件
来源：http://dali.jqgfzy.top/Article/details/gt2uhgpnqfg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.smart0.xyz/Article/details/gt2ghmblsab.html

[R17] 数组定义与取值
来源：http://dali.nanxinkj.top/Article/details/gt2mpmperep.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sxryk.cn/Article/details/gt2qbbeghic.html

[R18] 遍历数组
来源：http://dali.jlsjyb.cn/Article/details/gt2gcmqqwlx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cdnleiting.top/Article/details/gt2rbuxsodv.html

[R19] 数组长度
来源：http://dali.0kj1m.cn/Article/details/gt2yowwrunq.html

echo "${#arr[@]}"
来源：http://dali.ydzc1.top/Article/details/gt2bwdofrmm.html

[R20] 关联数组（字典）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2etxetess.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sysykeji.top/Article/details/gt2rpguabug.html

[R21] 字符串长度
来源：http://dali.andypj.xyz/Article/details/gt2azghjeit.html

echo "${#s}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2ofeclkia.html

[R22] 截取子串
来源：http://dali.hammf.cn/Article/details/gt2claxktwz.html

echo "${s:0:5}"
来源：http://dali.yuxming.cn/Article/details/gt2mjtflthh.html

[R23] 字符串替换
来源：http://dali.chenlongwang.top/Article/details/gt2bzxbilve.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.dashuyun.cn/Article/details/gt2owdeeihs.html

[R24] 大小写转换
来源：http://dali.xinyue.icu/Article/details/gt2kdklxhxb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nbbocrka.html

[R25] 去后缀 / 去前缀
来源：http://dali.pengpengdd.cyou/Article/details/gt2eeixukqx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bzoyqyov.html

[R26] 命令替换
来源：http://dali.pycfn.com/Article/details/gt2wciotuxn.html

now=$(date +%F); echo "$now"
来源：http://dali.cdnleiting.top/Article/details/gt2mwbvcnfm.html

[R27] 算术展开
来源：http://dali.316326.xyz/Article/details/gt2lacbidne.html

echo $((1 + 2 * 3))
来源：http://dali.9152youxi.cn/Article/details/gt2decqrgss.html

[R28] 浮点运算
来源：http://dali.wangshuangyany.cn/Article/details/gt2amlbiupc.html

echo "scale=2; 10/3" | bc
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wguqajcr.html

[R29] 定义函数
来源：http://dali.aibaodan.cn/Article/details/gt2ldufegxp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gotoacloud.top/Article/details/gt2tfuklpzg.html

[R30] 函数返回状态码
来源：http://dali.iojbl.cn/Article/details/gt2ozpxybrc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yueranfly.top/Article/details/gt2mojghasq.html

[R31] 局部变量
来源：http://dali.zycfv.cn/Article/details/gt2oagqlggh.html

f() { local x=1; echo "$x"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2oqdjwbgr.html

[R32] 参数个数校验
来源：http://dali.sysykeji.top/Article/details/gt2yxqbmbfv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jqgfzy.top/Article/details/gt2imukfttm.html

[R33] 捕获错误并提示行号
来源：http://dali.cucudq.cn/Article/details/gt2xahqpopp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.tanke756.top/Article/details/gt2piipjshs.html

[R34] 退出时清理
来源：http://dali.iojbl.cn/Article/details/gt2pvcbigdg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.kuanghao11.cn/Article/details/gt2xjgowloq.html

[R35] 后台执行并等待
来源：http://dali.ydzc1.top/Article/details/gt2ifwsqvyd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.aibaodan.cn/Article/details/gt2kggvjhxe.html

[R36] 并发执行多个任务
来源：http://dali.vqdsnc.cn/Article/details/gt2bihmksvj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ogolxkoy.html

[R37] 把输出赋给变量
来源：http://dali.chenjidiqi.icu/Article/details/gt2zvmtnvgy.html

files=$(ls -1)
来源：http://dali.wangdashe.top/Article/details/gt2noytcsgk.html

[R38] 管道串联
来源：http://dali.zdqjudy.top/Article/details/gt2xtaptolq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhixingplan.top/Article/details/gt2eciscydz.html

[R39] 重定向标准输出与错误
来源：http://dali.snrcjt.cn/Article/details/gt2bfvasrue.html

cmd > out.log 2>&1
来源：http://dali.guowangkeji.top/Article/details/gt2scxeaqfu.html

[R40] 追加写日志
来源：http://dali.cqqwz.cn/Article/details/gt2nbspejwl.html

echo "log" >> out.log
来源：http://dali.mhx1999.top/Article/details/gt2btvrhijq.html

[R41] 丢弃输出
来源：http://dali.zhiwuduotai.top/Article/details/gt2gjtrzrmd.html

cmd >/dev/null 2>&1
来源：http://dali.gaohongyu789.top/Article/details/gt2avgjutyq.html

[R42] 输入重定向
来源：http://dali.jinqigfzy.top/Article/details/gt2tdcdgjjb.html

wc -l < a.txt
来源：http://dali.birdmap.top/Article/details/gt2htoakkan.html

[R43] 按名字查找文件
来源：http://dali.gaohongyu789.top/Article/details/gt2lirotbax.html

find . -name "*.log" -type f
来源：http://dali.cqqwz.cn/Article/details/gt2uzimkdgr.html

[R44] 按修改时间查找
来源：http://dali.fzhhl.top/Article/details/gt2xbqovglx.html

find . -mtime -7 -type f
来源：http://dali.gaohongyu789.top/Article/details/gt2dnmtayyv.html

[R45] 批量删除
来源：http://dali.shangyingyoupin.top/Article/details/gt2inlsyycd.html

find . -name "*.tmp" -delete
来源：http://dali.jinghuilouyu.cn/Article/details/gt2famjosvc.html

[R46] 递归替换文件内容
来源：http://dali.0kj1m.cn/Article/details/gt2jsruhbrh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hktdfrfh.html

[R47] sed 单行替换
来源：http://dali.cqqwz.cn/Article/details/gt2ufbssqwl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.dashuyun.cn/Article/details/gt2fylufrbv.html

[R48] awk 取指定列
来源：http://dali.meibo888.top/Article/details/gt2amafyhmd.html

awk '{print $1, $3}' a.txt
来源：http://dali.xylfe.cn/Article/details/gt2jrwtrbxn.html

[R49] awk 带条件
来源：http://dali.aizwys.cn/Article/details/gt2mdapbtwv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.tanke756.top/Article/details/gt2qxsoubrg.html

[R50] awk 求和
来源：http://dali.chenjidiqi.icu/Article/details/gt2zddhqsar.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hfpthk.cn/Article/details/gt2vcooewcz.html

[R51] 排序去重取前几
来源：http://dali.jinqigufen.top/Article/details/gt2tfmjqlyt.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zycfv.cn/Article/details/gt2meewtfni.html

[R52] 统计行数
来源：http://dali.cashguo.top/Article/details/gt2mtflncsr.html

wc -l a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xwlraluk.html

[R53] 查看文件头与实时尾
来源：http://dali.jinqigfzy.top/Article/details/gt2mkanybnn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhengqikj.top/Article/details/gt2gnfkolgs.html

[R54] 比较两个文件
来源：http://dali.guowangkeji.top/Article/details/gt2plhnbqgb.html

diff a.txt b.txt
来源：http://dali.sysykeji.top/Article/details/gt2gknyhdif.html

[R55] 压缩与解压
来源：http://dali.gzhubu.top/Article/details/gt2zwonalwz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.pengpengdd.cyou/Article/details/gt2cstfaznk.html

[R56] 远程拷贝
来源：http://dali.bjfxy.top/Article/details/gt2wchamiws.html

scp file user@host:/path/
来源：http://dali.dianchejie.cn/Article/details/gt2pthfpzjv.html

[R57] 远程执行命令
来源：http://dali.aizwys.cn/Article/details/gt2raekfqby.html

ssh user@host 'uptime'
来源：http://dali.quarkkingdee.top/Article/details/gt2jkaccptl.html

[R58] 下载文件
来源：http://dali.jyoumei.cn/Article/details/gt2sxlsmijz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sxryk.cn/Article/details/gt2iiqomuqd.html

[R59] 发 POST JSON
来源：http://dali.tian-w.cn/Article/details/gt2tmsfjdjg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.feifeiyinyue.top/Article/details/gt2wiqhpayx.html

[R60] 只看 HTTP 状态码
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hoefmloo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.daxiang520.top/Article/details/gt2kfowysui.html

[R61] 磁盘占用
来源：http://dali.nanxuanxn.top/Article/details/gt2ihywnrjz.html

df -h;  du -sh *
来源：http://dali.svipenyu.cn/Article/details/gt2nwmlpyen.html

[R62] 找最占空间的文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hlxyekki.html

du -ah . | sort -rh | head -10
来源：http://dali.sweek.top/Article/details/gt2umetujny.html

[R63] 内存与进程
来源：http://dali.aibaodan.cn/Article/details/gt2fgvnqmea.html

free -h;  ps aux | grep nginx
来源：http://dali.vqdsnc.cn/Article/details/gt2wnumymcq.html

[R64] 结束进程
来源：http://dali.hnxiangtu.top/Article/details/gt2wwfklkta.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhengqikj.top/Article/details/gt2jevsxrhd.html

[R65] 查看端口占用
来源：http://dali.nwbrower.top/Article/details/gt2lwyxmfkk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hongshengwenyu.top/Article/details/gt2jupoaedj.html

[R66] 定时任务
来源：http://dali.xuanzx.com/Article/details/gt2bwpekjsy.html

crontab -e;  crontab -l
来源：http://dali.yuxming.cn/Article/details/gt2nmjkiqrt.html

[R67] 生成随机十六进制串
来源：http://dali.yuxming.cn/Article/details/gt2qiqszusd.html

openssl rand -hex 16
来源：http://dali.gogol.net.cn/Article/details/gt2erbqfufv.html

[R68] 计算文件校验值
来源：http://dali.c1oappe.top/Article/details/gt2swpulujf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.dianchejie.cn/Article/details/gt2bqlnvbii.html

[R69] 生成随机密码
来源：http://dali.jianghu66.top/Article/details/gt2ubhbtkry.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ctuymwfk.html

[R70] 时间戳与互转
来源：http://dali.zycfv.cn/Article/details/gt2zkmvhzbi.html

date +%s;  date -d @1700000000
来源：http://dali.bjfxy.top/Article/details/gt2jajdypqb.html

[R71] 日期格式化
来源：http://dali.zhengqikj.top/Article/details/gt2nnlqahbg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.c1oappe.top/Article/details/gt2khikpmdl.html

[R72] 等待端口就绪
来源：http://dali.andypj.xyz/Article/details/gt2nymnupwx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jlsjyb.cn/Article/details/gt2pdyayvhm.html

[R73] 分割大日志
来源：http://dali.redwolf501.top/Article/details/gt2ywtifawm.html


<!-- 参考信息 -->