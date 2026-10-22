代发 wailian999

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.daria6918.cn/Article/details/gt2wkbecybu.html

[Q18] 模糊匹配
来源：http://dali.bjfxy.top/Article/details/gt2zxnwqych.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zycfv.cn/Article/details/gt2hreaogkn.html

[Q19] 范围查询
来源：http://dali.shangyingyoupin.top/Article/details/gt2vbundfey.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.fzhhl.top/Article/details/gt2uzpegqfx.html

[Q20] IN 列表
来源：http://dali.shuidangran.top/Article/details/gt2gukyubvt.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yonumen.top/Article/details/gt2wqvrfxmh.html

[Q21] 空值判断
来源：http://dali.dashuyun.cn/Article/details/gt2ljuisxww.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2idxsqbqa.html

[Q22] 排序
来源：http://dali.hammf.cn/Article/details/gt2shiknosc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.guannengcc.top/Article/details/gt2cmbwqiui.html

[Q23] 分页
来源：http://dali.xylfe.cn/Article/details/gt2vyvfttcy.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.sxryk.cn/Article/details/gt2zkpnnhde.html

[Q24] 去重
来源：http://dali.xuanzx.com/Article/details/gt2wgwuqzyc.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2zoflavjd.html

[Q25] 只取前 N 条
来源：http://dali.xinyue.icu/Article/details/gt2stsdsmdw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.tian-w.cn/Article/details/gt2blryczaq.html

[Q26] 计数
来源：http://dali.ehwqpu.com/Article/details/gt2mlvlqqom.html

SELECT COUNT(*) FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2cxvikzho.html

[Q27] 条件计数
来源：http://dali.chenjidiqi.icu/Article/details/gt2mqvhncgq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2oduprgzj.html

[Q28] 求和与平均
来源：http://dali.aizwys.cn/Article/details/gt2ijpryljs.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gt2tidawpww.html

[Q29] 最大最小值
来源：http://dali.yanxiufei.cn/Article/details/gt2fearhwjj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2dwuakeig.html

[Q30] 分组统计
来源：http://dali.xuanzx.com/Article/details/gt2olacjrqd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ehwqpu.com/Article/details/gt2otweolif.html

[Q31] 分组后过滤
来源：http://dali.cucudq.cn/Article/details/gt2cljzaiwz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cheryme.top/Article/details/gt2sdrusciy.html

[Q32] 分组拼接字符串
来源：http://dali.xylfe.cn/Article/details/gt2zjjwznqx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yanxiufei.cn/Article/details/gt2citlgdni.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.wangshuangyany.cn/Article/details/gt2srupbsrh.html

[Q33] 多列分组
来源：http://dali.aibaodan.cn/Article/details/gt2bczciecy.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yanxiufei.cn/Article/details/gt2tbogvlty.html

[Q34] 每组取第一条
来源：http://dali.xziqi.cn/Article/details/gt2sjcaiquh.html

SELECT * FROM (
来源：http://dali.mhx1999.top/Article/details/gt2cwnerwpo.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jianghu66.top/Article/details/gt2rfmquisj.html

) t WHERE rn = 1;
来源：http://dali.0kj1m.cn/Article/details/gt2comxgaln.html

[Q35] 内连接
来源：http://dali.gzhubu.top/Article/details/gt2sskgbqro.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.svipenyu.cn/Article/details/gt2phvkatvx.html

[Q36] 左连接
来源：http://dali.yueranfly.top/Article/details/gt2ybjwcnuc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.0kj1m.cn/Article/details/gt2kvxrdqiu.html

[Q37] 右连接
来源：http://dali.vqdsnc.cn/Article/details/gt2wrmrntaa.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ixbfacbm.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yueranfly.top/Article/details/gt2gajcglte.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.kuanghao11.cn/Article/details/gt2nzgbkdln.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2zsxfojle.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.wangdashe.top/Article/details/gt2rfovbywc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cashguo.top/Article/details/gt2wtviwrsv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gogol.net.cn/Article/details/gt2eyqmrjss.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yanxiufei.cn/Article/details/gt2yygamskz.html

[Q41] 多表连接
来源：http://dali.hfpthk.cn/Article/details/gt2jyjeivoz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ybcxt.top/Article/details/gt2fswqgkoj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.316326.xyz/Article/details/gt2ovjcjxxv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhixingplan.top/Article/details/gt2yavmdjxc.html

[Q42] 连接条件附加过滤
来源：http://dali.aizwys.cn/Article/details/gt2cyxvfltu.html

SELECT u.name, o.amount FROM users u
来源：http://dali.fzhhl.top/Article/details/gt2tanhxvep.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgdlmduv.html

[Q43] 标量子查询
来源：http://dali.fzhhl.top/Article/details/gt2hhmoxisr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jiagoushi.top/Article/details/gt2ongtbnme.html

[Q44] IN 子查询
来源：http://dali.gogol.net.cn/Article/details/gt2jofwbgfk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hnxiangtu.top/Article/details/gt2cqupmide.html

[Q45] EXISTS 判断存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xtugvqxh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.dianchejie.cn/Article/details/gt2jjvmsnop.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hysaishi.cn/Article/details/gt2vgchldyy.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gotoacloud.top/Article/details/gt2lfavpqjs.html

[Q47] 与平均值比较
来源：http://dali.tianlin.xyz/Article/details/gt2pwrjqzze.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.chenlongwang.top/Article/details/gt2hzhrjtjj.html

[Q48] CTE 公用表表达式
来源：http://dali.yj20258888.top/Article/details/gt2bqzzdoli.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yuxming.cn/Article/details/gt2bjjsqmdb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cqqwz.cn/Article/details/gt2giorgffk.html

[Q49] 更新单行
来源：http://dali.zdqjudy.top/Article/details/gt2xfczvsyo.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cheryme.top/Article/details/gt2vagizwzy.html

[Q50] 批量更新
来源：http://dali.nwbrower.top/Article/details/gt2inglhttj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.dianchejie.cn/Article/details/gt2ltbdehuy.html

[Q51] 用子查询更新
来源：http://dali.dashuyun.cn/Article/details/gt2tyrkdgio.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.vqdsnc.cn/Article/details/gt2mczfnosv.html

[Q52] 删除指定行
来源：http://dali.aizwys.cn/Article/details/gt2hmsiynwx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.quarkkingdee.top/Article/details/gt2tduiebjh.html

[Q53] 按条件删除
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rqgvzztp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yueranfly.top/Article/details/gt2sbytqqzd.html

[Q54] 清空表
来源：http://dali.meibo888.top/Article/details/gt2rrdwjjnq.html

TRUNCATE TABLE logs;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ocuubsls.html

[Q55] 排名（并列占位）
来源：http://dali.gotoacloud.top/Article/details/gt2ptdvpwbz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.aizwys.cn/Article/details/gt2irjzbqie.html

[Q56] 密集排名（并列不占位）
来源：http://dali.iojbl.cn/Article/details/gt2zutsaajb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.meibo888.top/Article/details/gt2brttmuwy.html

[Q57] 行号
来源：http://dali.chenzaomai.com/Article/details/gt2zdkotfaz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.bjfxy.top/Article/details/gt2tqinpftg.html

[Q58] 累计求和
来源：http://dali.sysykeji.top/Article/details/gt2selkfzyi.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gt2stwuitas.html

[Q59] 分组内累计
来源：http://dali.zhoulong.xyz/Article/details/gt2mqixfbri.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gt2fzwkppyf.html

[Q60] 取上一行 / 下一行
来源：http://dali.yj20258.top/Article/details/gt2cietmemb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hysaishi.cn/Article/details/gt2admotbid.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gt2akjtxysu.html

[Q61] 移动平均
来源：http://dali.hnqzz.top/Article/details/gt2tmiyrqdc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gt2ixrjvmet.html

[Q62] 分组占比
来源：http://dali.hnqzz.top/Article/details/gt2zdtqosoo.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fbybdcyq.html

[Q63] 开启事务
来源：http://dali.dianchejie.cn/Article/details/gt2hjnwslvn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.quarkkingdee.top/Article/details/gt2idatjqni.html

[Q64] 提交事务
来源：http://dali.sysykeji.top/Article/details/gt2adwflbjp.html

COMMIT;
来源：http://dali.fzhhl.top/Article/details/gt2mitcglym.html

[Q65] 回滚事务
来源：http://dali.sufxvd.cn/Article/details/gt2chnylnbc.html

ROLLBACK;
来源：http://dali.dashuyun.cn/Article/details/gt2yiddfymd.html

[Q66] 行锁查询
来源：http://dali.9152youxi.cn/Article/details/gt2nvgacsgt.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.daria6918.cn/Article/details/gt2moeenisq.html

[Q67] 设置隔离级别
来源：http://dali.havefunace.top/Article/details/gt2ritnises.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.iojbl.cn/Article/details/gt2xynwhomw.html

[Q68] 保存点
来源：http://dali.gaohongyu789.top/Article/details/gt2zbbksmkg.html

SAVEPOINT sp1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ydftvgwv.html

ROLLBACK TO sp1;
来源：http://dali.fzhhl.top/Article/details/gt2cfpwcwpd.html

[Q69] 查看执行计划
来源：http://dali.jinqigufen.top/Article/details/gt2vslptgtp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.feifeiyinyue.top/Article/details/gt2skhjpfib.html

[Q70] 更新统计信息
来源：http://dali.zhoulong.xyz/Article/details/gt2uebbiqhy.html

ANALYZE TABLE users;
来源：http://dali.yangfankeji.com/Article/details/gt2lfoqjuyw.html

[Q71] 查看建表语句
来源：http://dali.gaohongyu789.top/Article/details/gt2iumfkszx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hongshengwenyu.top/Article/details/gt2swqromod.html

[Q72] 查看索引
来源：http://dali.cheryme.top/Article/details/gt2ggryhptg.html

SHOW INDEX FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2guwenzje.html

[Q73] 查看表状态
来源：http://dali.sufxvd.cn/Article/details/gt2alnbsuna.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.9152youxi.cn/Article/details/gt2ewhpzmvg.html

[Q74] 强制使用索引
来源：http://dali.yanxiufei.cn/Article/details/gt2mwqjmwle.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lvukoxiz.html

[Q75] 日期格式化
来源：http://dali.cashguo.top/Article/details/gt2dchpmrnq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yueranfly.top/Article/details/gt2epntluly.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yj20258888.top/Article/details/gt2ovcxiydb.html

[Q76] 按天统计
来源：http://dali.xuanzx.com/Article/details/gt2dhtgqahp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.andypj.xyz/Article/details/gt2keuhbzsj.html

[Q77] 时间加减
来源：http://dali.xuetiantiany.cn/Article/details/gt2wbydxodm.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.chenzaomai.com/Article/details/gt2rnlrswvc.html

[Q78] 当前时间
来源：http://dali.xuetiantiany.cn/Article/details/gt2gmqrzlsw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.chenjidiqi.icu/Article/details/gt2twjnghaj.html

[Q79] 字符串拼接
来源：http://dali.nwbrower.top/Article/details/gt2dabnpqnu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hongshengwenyu.top/Article/details/gt2rmhyxdtg.html

[Q80] 字符串截取
来源：http://dali.ybcxt.top/Article/details/gt2nhgqjozi.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.316326.xyz/Article/details/gt2jxtvcgup.html

[Q81] 字符串替换
来源：http://dali.gzhubu.top/Article/details/gt2xkfcmehb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2aoyswony.html

[Q82] 字符长度与字节长度
来源：http://dali.xziqi.cn/Article/details/gt2cunpfynv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2pxricbwi.html

[Q83] 大小写转换
来源：http://dali.ivvv.top/Article/details/gt2arlrhskl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yj202588.top/Article/details/gt2ifqxayea.html

[Q84] 去除首尾空格
来源：http://dali.zhixingplan.top/Article/details/gt2rxndtzdf.html

SELECT TRIM(name) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2ouxyitii.html

[Q85] 数值取整
来源：http://dali.hnqzz.top/Article/details/gt2opajfkqi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.haohaochexian.top/Article/details/gt2mbqpcmeu.html

[Q86] 读取 JSON 字段
来源：http://dali.jinqigufen.top/Article/details/gt2artjqvnb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xuanzx.com/Article/details/gt2pizxxghl.html

[Q87] JSON 字段做条件
来源：http://dali.ybcxt.top/Article/details/gt2xqftoiou.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yuxming.cn/Article/details/gt2mdvemgtw.html

[Q88] 行转列（条件聚合）
来源：http://dali.cheryme.top/Article/details/gt2uuwuoclt.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ruxjtwxa.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2ngbqazsi.html

[Q89] 判断表是否存在
来源：http://dali.shuidangran.top/Article/details/gt2ruhdshto.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nanxuanxn.top/Article/details/gt2imthgdkm.html

[Q90] 生成序号列
来源：http://dali.xziqi.cn/Article/details/gt2wtrnnflc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.redwolf501.top/Article/details/gt2airezuyd.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2niudcpnl.html

R. Bash 专题
来源：http://dali.hnxiangtu.top/Article/details/gt2jpwwxicd.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xbhezuyk.html

[R01] shebang 与严格模式
来源：http://dali.yueranfly.top/Article/details/gt2yjriybog.html

#!/usr/bin/env bash
来源：http://dali.snrcjt.cn/Article/details/gt2zfwbqwpc.html

set -euo pipefail
来源：http://dali.shzxlz.cn/Article/details/gt2orzvjogg.html

[R02] 变量赋值与使用
来源：http://dali.cdnleiting.top/Article/details/gt2qabyfbnf.html

name="Tom"; echo "$name"
来源：http://dali.jiagoushi.top/Article/details/gt2mxyjdjpn.html

[R03] 只读变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sylawuyf.html

readonly PI=3.14
来源：http://dali.hywenlv.cn/Article/details/gt2kfzskapc.html

[R04] 位置参数
来源：http://dali.yangfankeji.com/Article/details/gt2rzvomkay.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.dianchejie.cn/Article/details/gt2kpnapjtm.html

[R05] 参数默认值
来源：http://dali.9152youxi.cn/Article/details/gt2vwpuymbs.html

name="${1:-default}"
来源：http://dali.yanxiufei.cn/Article/details/gt2tuevqsky.html

[R06] 判断命令是否存在
来源：http://dali.jqgfzy.top/Article/details/gt2zlvujsxj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yuxming.cn/Article/details/gt2hlafuxfm.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hyapshol.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.tanke756.top/Article/details/gt2rbdjprud.html

[R08] 数值比较
来源：http://dali.c1oappe.top/Article/details/gt2lvvgcucw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ivvv.top/Article/details/gt2dkkodric.html

[R09] 字符串比较
来源：http://dali.yueranfly.top/Article/details/gt2kwdbecvm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.daria6918.cn/Article/details/gt2dvqmqeqd.html

[R10] 正则匹配
来源：http://dali.pengpengdd.cyou/Article/details/gt2ilqbiqcd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gzhubu.top/Article/details/gt2ebxjpmcf.html

[R11] case 多分支
来源：http://dali.smart0.xyz/Article/details/gt2omcyglwc.html

case "$1" in
来源：http://dali.meibo888.top/Article/details/gt2liaxlhou.html

start) echo "启动" ;;
来源：http://dali.zhengqikj.top/Article/details/gt2mcuuixad.html

stop)  echo "停止" ;;
来源：http://dali.xylfe.cn/Article/details/gt2qzyyxkge.html

*)     echo "未知命令" ;;
来源：http://dali.fengsongda.top/Article/details/gt2lduhqlps.html

esac
来源：http://dali.redwolf501.top/Article/details/gt2nxxxdnqr.html

[R12] for 遍历文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kadjvegw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shangyingyoupin.top/Article/details/gt2squmozyc.html

[R13] for 计数循环
来源：http://dali.guowangkeji.top/Article/details/gt2rgvbozoq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hammf.cn/Article/details/gt2lobkoqvj.html

[R14] C 风格 for
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wsgxbfmj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ntiutlez.html

[R15] while 逐行读文件
来源：http://dali.shzxlz.cn/Article/details/gt2pubnthee.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.aizwys.cn/Article/details/gt2evrenfcu.html

[R16] until 等待条件
来源：http://dali.yongpay.top/Article/details/gt2vjfarqzc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.guowangkeji.top/Article/details/gt2kdaghchf.html

[R17] 数组定义与取值
来源：http://dali.kuanghao11.cn/Article/details/gt2qjdfdsll.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.316326.xyz/Article/details/gt2jfbgaagb.html

[R18] 遍历数组
来源：http://dali.gotoacloud.top/Article/details/gt2qwggxxuj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yuanzhike.top/Article/details/gt2fehexkeg.html

[R19] 数组长度
来源：http://dali.yanxiufei.cn/Article/details/gt2huvpmnev.html

echo "${#arr[@]}"
来源：http://dali.jianghu66.top/Article/details/gt2kpktowxd.html

[R20] 关联数组（字典）
来源：http://dali.gotoacloud.top/Article/details/gt2ajxnbzsk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.pycfn.com/Article/details/gt2ljadeydh.html

[R21] 字符串长度
来源：http://dali.zycfv.cn/Article/details/gt2lbzepips.html

echo "${#s}"
来源：http://dali.iojbl.cn/Article/details/gt2tgmyheoi.html

[R22] 截取子串
来源：http://dali.quarkkingdee.top/Article/details/gt2nsgsleew.html

echo "${s:0:5}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lvtzroqo.html

[R23] 字符串替换
来源：http://dali.jinqigfzy.top/Article/details/gt2odnpuynf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gotoacloud.top/Article/details/gt2yfwrpkov.html

[R24] 大小写转换
来源：http://dali.chenjidiqi.icu/Article/details/gt2ykvfsxrw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhengqikj.top/Article/details/gt2hqdgpfot.html

[R25] 去后缀 / 去前缀
来源：http://dali.hywenlv.cn/Article/details/gt2qqebzysa.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ydzc1.top/Article/details/gt2lhcwoysu.html

[R26] 命令替换
来源：http://dali.jianghu66.top/Article/details/gt2wbbhunit.html

now=$(date +%F); echo "$now"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ropalbdg.html

[R27] 算术展开
来源：http://dali.zdqjudy.top/Article/details/gt2ydphgjoi.html

echo $((1 + 2 * 3))
来源：http://dali.xuetiantiany.cn/Article/details/gt2wayatwun.html

[R28] 浮点运算
来源：http://dali.nanxuanxn.top/Article/details/gt2icxdnays.html

echo "scale=2; 10/3" | bc
来源：http://dali.sweek.top/Article/details/gt2qchktncx.html

[R29] 定义函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2krlcsafh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wpgwozvd.html

[R30] 函数返回状态码
来源：http://dali.hfpthk.cn/Article/details/gt2yfauwujz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.havefunace.top/Article/details/gt2rukhhzns.html

[R31] 局部变量
来源：http://dali.tianlin.xyz/Article/details/gt2cmpuifor.html

f() { local x=1; echo "$x"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2blprdjod.html

[R32] 参数个数校验
来源：http://dali.meibo888.top/Article/details/gt2xonytqkl.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xziqi.cn/Article/details/gt2njodpxeg.html

[R33] 捕获错误并提示行号
来源：http://dali.wangshuangyany.cn/Article/details/gt2xbszvvqe.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jiagoushi.top/Article/details/gt2djbvbuzn.html

[R34] 退出时清理
来源：http://dali.c1oappe.top/Article/details/gt2pxullhbw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ivvv.top/Article/details/gt2mulkkzgr.html

[R35] 后台执行并等待
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rzrdwavj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jiagoushi.top/Article/details/gt2yfintfah.html

[R36] 并发执行多个任务
来源：http://dali.smart0.xyz/Article/details/gt2slmlsdlu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ppjwa.cn/Article/details/gt2pqwytrsf.html

[R37] 把输出赋给变量
来源：http://dali.shuidangran.top/Article/details/gt2oexclzbo.html

files=$(ls -1)
来源：http://dali.fengsongda.top/Article/details/gt2rzrsspjr.html

[R38] 管道串联
来源：http://dali.hysaishi.cn/Article/details/gt2jyzkafgp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinqigfzy.top/Article/details/gt2ggjezrrw.html

[R39] 重定向标准输出与错误
来源：http://dali.cucudq.cn/Article/details/gt2xkryzldo.html

cmd > out.log 2>&1
来源：http://dali.mhx1999.top/Article/details/gt2avmpvoel.html

[R40] 追加写日志
来源：http://dali.jinqigfzy.top/Article/details/gt2lfcyvaai.html

echo "log" >> out.log
来源：http://dali.haohaochexian.top/Article/details/gt2xzntkojh.html

[R41] 丢弃输出
来源：http://dali.yangfankeji.com/Article/details/gt2sagcameq.html

cmd >/dev/null 2>&1
来源：http://dali.zhoulong.xyz/Article/details/gt2kbeaveoo.html

[R42] 输入重定向
来源：http://dali.nanxinkj.top/Article/details/gt2jykoqsgz.html

wc -l < a.txt
来源：http://dali.vqdsnc.cn/Article/details/gt2izenvtcb.html

[R43] 按名字查找文件
来源：http://dali.birdmap.top/Article/details/gt2iermpjhl.html

find . -name "*.log" -type f
来源：http://dali.cucudq.cn/Article/details/gt2vltrprxe.html

[R44] 按修改时间查找
来源：http://dali.gogol.net.cn/Article/details/gt2hvytqitw.html

find . -mtime -7 -type f
来源：http://dali.316326.xyz/Article/details/gt2hmdhzqjn.html

[R45] 批量删除
来源：http://dali.smart0.xyz/Article/details/gt2lttglmtq.html

find . -name "*.tmp" -delete
来源：http://dali.yuxming.cn/Article/details/gt2cuhecubi.html

[R46] 递归替换文件内容
来源：http://dali.ydzc1.top/Article/details/gt2qtscusvm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.kuanghao11.cn/Article/details/gt2somjxmhb.html

[R47] sed 单行替换
来源：http://dali.ydzc1.top/Article/details/gt2xqshezda.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ydzc1.top/Article/details/gt2lnxcncan.html

[R48] awk 取指定列
来源：http://dali.redwolf501.top/Article/details/gt2ijdkablb.html

awk '{print $1, $3}' a.txt
来源：http://dali.zdqjudy.top/Article/details/gt2mberkxik.html

[R49] awk 带条件
来源：http://dali.yvedp.cn/Article/details/gt2wajpfdpo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jqgfzy.top/Article/details/gt2whtydeok.html

[R50] awk 求和
来源：http://dali.cdnleiting.top/Article/details/gt2zukluxcm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.aibaodan.cn/Article/details/gt2icquiiik.html

[R51] 排序去重取前几
来源：http://dali.guowangkeji.top/Article/details/gt2nxhqsnzi.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uvaaxcxz.html

[R52] 统计行数
来源：http://dali.bjfxy.top/Article/details/gt2rhuubzgn.html

wc -l a.txt
来源：http://dali.smart0.xyz/Article/details/gt2bwpdodms.html

[R53] 查看文件头与实时尾
来源：http://dali.chenlongwang.top/Article/details/gt2cgvyqmha.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.sufxvd.cn/Article/details/gt2exzqzpmg.html

[R54] 比较两个文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2keghpbfe.html

diff a.txt b.txt
来源：http://dali.tian-w.cn/Article/details/gt2uwjlvxew.html

[R55] 压缩与解压
来源：http://dali.jiagoushi.top/Article/details/gt2rxgkuhij.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gfslbskg.html

[R56] 远程拷贝
来源：http://dali.meibo888.top/Article/details/gt2khnquqef.html

scp file user@host:/path/
来源：http://dali.chenjidiqi.icu/Article/details/gt2xttooowj.html

[R57] 远程执行命令
来源：http://dali.jlsjyb.cn/Article/details/gt2xqptxloh.html

ssh user@host 'uptime'
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2awapteox.html

[R58] 下载文件
来源：http://dali.sufxvd.cn/Article/details/gt2zrpavnpf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2soxssnsi.html

[R59] 发 POST JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ntvqokkk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.vqdsnc.cn/Article/details/gt2msvdcjue.html

[R60] 只看 HTTP 状态码
来源：http://dali.xuanzx.com/Article/details/gt2vpcfxhhe.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhengqikj.top/Article/details/gt2pltjcitw.html

[R61] 磁盘占用
来源：http://dali.guannengcc.top/Article/details/gt2unvqbclk.html

df -h;  du -sh *
来源：http://dali.aibaodan.cn/Article/details/gt2jefkkwrv.html

[R62] 找最占空间的文件
来源：http://dali.jinqigfzy.top/Article/details/gt2sjmeqmgz.html

du -ah . | sort -rh | head -10
来源：http://dali.gzhubu.top/Article/details/gt2tqmupgbz.html

[R63] 内存与进程
来源：http://dali.kuanghao11.cn/Article/details/gt2zzlqltjq.html

free -h;  ps aux | grep nginx
来源：http://dali.yj20258888.top/Article/details/gt2mcluadpy.html

[R64] 结束进程
来源：http://dali.xziqi.cn/Article/details/gt2knfvgvwe.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shangyingyoupin.top/Article/details/gt2iwzrwmti.html

[R65] 查看端口占用
来源：http://dali.hongshengwenyu.top/Article/details/gt2aqsvesuj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.wangshuangyany.cn/Article/details/gt2dcvyrmse.html

[R66] 定时任务
来源：http://dali.ybcxt.top/Article/details/gt2ohpntlcn.html

crontab -e;  crontab -l
来源：http://dali.feifeiyinyue.top/Article/details/gt2jrfpeedf.html

[R67] 生成随机十六进制串
来源：http://dali.smart0.xyz/Article/details/gt2mukgxrcg.html


<!-- 参考信息 -->