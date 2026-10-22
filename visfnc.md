代发 wailian999

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cheryme.top/Article/details/gt2acymtdpy.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvzysbh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.svipenyu.cn/Article/details/gt2tfhoccpe.html

[Q19] 范围查询
来源：http://dali.hfpthk.cn/Article/details/gt2sbjeihqw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.0kj1m.cn/Article/details/gt2butgnufb.html

[Q20] IN 列表
来源：http://dali.dashuyun.cn/Article/details/gt2wasncbnl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ydzc1.top/Article/details/gt2xfaufdjw.html

[Q21] 空值判断
来源：http://dali.ppjwa.cn/Article/details/gt2hztezquu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhengqikj.top/Article/details/gt2zlppmbrt.html

[Q22] 排序
来源：http://dali.hnqzz.top/Article/details/gt2mrekstmc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.bjfxy.top/Article/details/gt2tavkviwu.html

[Q23] 分页
来源：http://dali.ppjwa.cn/Article/details/gt2nxaxyobv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jinqigufen.top/Article/details/gt2fsmudtqi.html

[Q24] 去重
来源：http://dali.ydzc1.top/Article/details/gt2vqhgumpv.html

SELECT DISTINCT city FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2luvizwzy.html

[Q25] 只取前 N 条
来源：http://dali.tanke756.top/Article/details/gt2eitvgzvg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.quarkkingdee.top/Article/details/gt2yeaatqgp.html

[Q26] 计数
来源：http://dali.haohaochexian.top/Article/details/gt2nzqxbtsq.html

SELECT COUNT(*) FROM users;
来源：http://dali.cashguo.top/Article/details/gt2rpmzhyro.html

[Q27] 条件计数
来源：http://dali.jiagoushi.top/Article/details/gt2foezwwyd.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2wagrpdbs.html

[Q28] 求和与平均
来源：http://dali.yuxming.cn/Article/details/gt2byznjkho.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gt2cgkggucy.html

[Q29] 最大最小值
来源：http://dali.yonumen.top/Article/details/gt2ekqluhxg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2taxgbgmt.html

[Q30] 分组统计
来源：http://dali.yj202588.top/Article/details/gt2vgnvijpr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ppjwa.cn/Article/details/gt2dptzgibu.html

[Q31] 分组后过滤
来源：http://dali.yanxiufei.cn/Article/details/gt2bwopryjw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cdnleiting.top/Article/details/gt2hbkwispb.html

[Q32] 分组拼接字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2luopnhmy.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jiagoushi.top/Article/details/gt2koodoxdp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yueranfly.top/Article/details/gt2rgzsupam.html

[Q33] 多列分组
来源：http://dali.daria6918.cn/Article/details/gt2nqlrehhr.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.tianlin.xyz/Article/details/gt2nenvbuux.html

[Q34] 每组取第一条
来源：http://dali.jqgfzy.top/Article/details/gt2kygskeav.html

SELECT * FROM (
来源：http://dali.nanxuanxn.top/Article/details/gt2ybfdnbnv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yuanzhike.top/Article/details/gt2wgvwzrns.html

) t WHERE rn = 1;
来源：http://dali.9152youxi.cn/Article/details/gt2beaneggx.html

[Q35] 内连接
来源：http://dali.chenlongwang.top/Article/details/gt2edquzjrb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxuanxn.top/Article/details/gt2zrwgmlqi.html

[Q36] 左连接
来源：http://dali.chenlongwang.top/Article/details/gt2mhzgugdl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cheryme.top/Article/details/gt2iqjvplms.html

[Q37] 右连接
来源：http://dali.xylfe.cn/Article/details/gt2bzvktfwb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.smart0.xyz/Article/details/gt2levnfnty.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jlsjyb.cn/Article/details/gt2tmsiudrh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.chenjidiqi.icu/Article/details/gt2dbrxksfy.html

[Q39] 自连接（查上下级）
来源：http://dali.yongpay.top/Article/details/gt2rskvoptt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.andypj.xyz/Article/details/gt2wqhfvzkx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.quarkkingdee.top/Article/details/gt2wyrskgrv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.redwolf501.top/Article/details/gt2oeqiupeq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jinqigfzy.top/Article/details/gt2fdvzremt.html

[Q41] 多表连接
来源：http://dali.yvedp.cn/Article/details/gt2lnpddzmb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yuanzhike.top/Article/details/gt2kfoeskuu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.guannengcc.top/Article/details/gt2alyoyvdp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.svipenyu.cn/Article/details/gt2givmpnoc.html

[Q42] 连接条件附加过滤
来源：http://dali.c1oappe.top/Article/details/gt2nqytqcli.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hywenlv.cn/Article/details/gt2hexrqsly.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.fengsongda.top/Article/details/gt2ijzhfnij.html

[Q43] 标量子查询
来源：http://dali.sufxvd.cn/Article/details/gt2iacovbpe.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shangyingyoupin.top/Article/details/gt2khhdebig.html

[Q44] IN 子查询
来源：http://dali.yongpay.top/Article/details/gt2kbcfnppk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yuxming.cn/Article/details/gt2umeuvyqb.html

[Q45] EXISTS 判断存在
来源：http://dali.guowangkeji.top/Article/details/gt2qqajlibs.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gzhubu.top/Article/details/gt2mjnixfcu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.feifeiyinyue.top/Article/details/gt2dxjlqjog.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj202588.top/Article/details/gt2ywtbyqdz.html

[Q47] 与平均值比较
来源：http://dali.yueranfly.top/Article/details/gt2jvljqmnp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.wangshuangyany.cn/Article/details/gt2aavtywhb.html

[Q48] CTE 公用表表达式
来源：http://dali.zhiwuduotai.top/Article/details/gt2nknypsmg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.wangshuangyany.cn/Article/details/gt2sndptwig.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ydzc1.top/Article/details/gt2pxlmlloo.html

[Q49] 更新单行
来源：http://dali.hfpthk.cn/Article/details/gt2fkpwjwkh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.daria6918.cn/Article/details/gt2wrcaumwr.html

[Q50] 批量更新
来源：http://dali.zhongyouzk.top/Article/details/gt2pqgsdylb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhoulong.xyz/Article/details/gt2tufrzqjn.html

[Q51] 用子查询更新
来源：http://dali.quarkkingdee.top/Article/details/gt2gpumbmll.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.quarkkingdee.top/Article/details/gt2tahiezya.html

[Q52] 删除指定行
来源：http://dali.jianghu66.top/Article/details/gt2lcltzkjp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.sufxvd.cn/Article/details/gt2ypwblgbf.html

[Q53] 按条件删除
来源：http://dali.dashuyun.cn/Article/details/gt2nfpfekgm.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.chenlongwang.top/Article/details/gt2pagybhhg.html

[Q54] 清空表
来源：http://dali.fzhhl.top/Article/details/gt2yjuecghb.html

TRUNCATE TABLE logs;
来源：http://dali.yanxiufei.cn/Article/details/gt2yvosyakn.html

[Q55] 排名（并列占位）
来源：http://dali.andypj.xyz/Article/details/gt2vbiiilav.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.meibo888.top/Article/details/gt2bymwtaca.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cucudq.cn/Article/details/gt2sfzzvcnr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xinyue.icu/Article/details/gt2qmjixrpa.html

[Q57] 行号
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fwwxpnbw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2ujnjenmt.html

[Q58] 累计求和
来源：http://dali.pycfn.com/Article/details/gt2hzhplnoa.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gt2wwikujgm.html

[Q59] 分组内累计
来源：http://dali.tian-w.cn/Article/details/gt2uyuqqddo.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xinyue.icu/Article/details/gt2tjzjslqs.html

[Q60] 取上一行 / 下一行
来源：http://dali.sufxvd.cn/Article/details/gt2wmoyiuzj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shangyingyoupin.top/Article/details/gt2xcgjkeyf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gt2imqyjvbt.html

[Q61] 移动平均
来源：http://dali.andypj.xyz/Article/details/gt2jzurjjea.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yj20258.top/Article/details/gt2hniabdhv.html

[Q62] 分组占比
来源：http://dali.shanyushiyangtech.top/Article/details/gt2shbfcxqi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gotoacloud.top/Article/details/gt2diogmqon.html

[Q63] 开启事务
来源：http://dali.xziqi.cn/Article/details/gt2fjamfsnq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hammf.cn/Article/details/gt2axyhjtzz.html

[Q64] 提交事务
来源：http://dali.yj202588.top/Article/details/gt2iqwxfsil.html

COMMIT;
来源：http://dali.svipenyu.cn/Article/details/gt2blwwyhhw.html

[Q65] 回滚事务
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qxcwmstc.html

ROLLBACK;
来源：http://dali.yanxiufei.cn/Article/details/gt2aviswpzf.html

[Q66] 行锁查询
来源：http://dali.gotoacloud.top/Article/details/gt2fceacevl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.feifeiyinyue.top/Article/details/gt2mjzfzprk.html

[Q67] 设置隔离级别
来源：http://dali.quarkkingdee.top/Article/details/gt2behpbiij.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.quarkkingdee.top/Article/details/gt2ganrnduq.html

[Q68] 保存点
来源：http://dali.daxiang520.top/Article/details/gt2hirlmqsc.html

SAVEPOINT sp1;
来源：http://dali.nwbrower.top/Article/details/gt2niwvbmez.html

ROLLBACK TO sp1;
来源：http://dali.pycfn.com/Article/details/gt2ciakrhbx.html

[Q69] 查看执行计划
来源：http://dali.yj20258888.top/Article/details/gt2fvkgkohd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cqqwz.cn/Article/details/gt2zlzbmkel.html

[Q70] 更新统计信息
来源：http://dali.pengpengdd.cyou/Article/details/gt2iovsifdj.html

ANALYZE TABLE users;
来源：http://dali.yongpay.top/Article/details/gt2varaqgbu.html

[Q71] 查看建表语句
来源：http://dali.redwolf501.top/Article/details/gt2jqjgdijj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xinyue.icu/Article/details/gt2vkzmbvlw.html

[Q72] 查看索引
来源：http://dali.0kj1m.cn/Article/details/gt2qxgbckfg.html

SHOW INDEX FROM users;
来源：http://dali.yj202588.top/Article/details/gt2zrzjfyci.html

[Q73] 查看表状态
来源：http://dali.xziqi.cn/Article/details/gt2zsojmsmf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.dashuyun.cn/Article/details/gt2xwwqbeyt.html

[Q74] 强制使用索引
来源：http://dali.daxiang520.top/Article/details/gt2fdjugfwp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.chenjidiqi.icu/Article/details/gt2yokfucms.html

[Q75] 日期格式化
来源：http://dali.havefunace.top/Article/details/gt2irzphjcv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gt2lhjklsex.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fdsimfdy.html

[Q76] 按天统计
来源：http://dali.zycfv.cn/Article/details/gt2jdxtcyif.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shuidangran.top/Article/details/gt2norzpwdc.html

[Q77] 时间加减
来源：http://dali.gzhubu.top/Article/details/gt2zqjpvtuv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.pycfn.com/Article/details/gt2rlmgbvva.html

[Q78] 当前时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yjeftfgo.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.gzhubu.top/Article/details/gt2jctfwaih.html

[Q79] 字符串拼接
来源：http://dali.smart0.xyz/Article/details/gt2vgzuntvo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.tianlin.xyz/Article/details/gt2qbaxmjss.html

[Q80] 字符串截取
来源：http://dali.ivvv.top/Article/details/gt2xconfqvk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2vtkyghrr.html

[Q81] 字符串替换
来源：http://dali.cdnleiting.top/Article/details/gt2alwhckta.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2rrqzvbdr.html

[Q82] 字符长度与字节长度
来源：http://dali.jqgufenzy.top/Article/details/gt2tqedztln.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2ynlezplo.html

[Q83] 大小写转换
来源：http://dali.sxryk.cn/Article/details/gt2vhenltbp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2txnztrtc.html

[Q84] 去除首尾空格
来源：http://dali.ehwqpu.com/Article/details/gt2jamzkrap.html

SELECT TRIM(name) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2suzmydav.html

[Q85] 数值取整
来源：http://dali.fzhhl.top/Article/details/gt2edrupgtp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhengqikj.top/Article/details/gt2rgbtwqum.html

[Q86] 读取 JSON 字段
来源：http://dali.birdmap.top/Article/details/gt2xxmudwre.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.nwbrower.top/Article/details/gt2imlskplx.html

[Q87] JSON 字段做条件
来源：http://dali.shzxlz.cn/Article/details/gt2ueijovgq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhiwuduotai.top/Article/details/gt2pjonjloi.html

[Q88] 行转列（条件聚合）
来源：http://dali.jiagoushi.top/Article/details/gt2fafqdrsp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.fengsongda.top/Article/details/gt2bvfcangh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2huhijehu.html

[Q89] 判断表是否存在
来源：http://dali.sweek.top/Article/details/gt2drcxwrjc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.wangdashe.top/Article/details/gt2misbxnsa.html

[Q90] 生成序号列
来源：http://dali.xylfe.cn/Article/details/gt2wnzkfbqm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xuetiantiany.cn/Article/details/gt2hkfphzii.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2yqbueacf.html

R. Bash 专题
来源：http://dali.dashuyun.cn/Article/details/gt2oiwwdaet.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2xgpokfbm.html

[R01] shebang 与严格模式
来源：http://dali.ydzc1.top/Article/details/gt2optafzwd.html

#!/usr/bin/env bash
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uxhrdqbq.html

set -euo pipefail
来源：http://dali.vqdsnc.cn/Article/details/gt2jvcmmruh.html

[R02] 变量赋值与使用
来源：http://dali.zhixingplan.top/Article/details/gt2rlmgwxwy.html

name="Tom"; echo "$name"
来源：http://dali.hywenlv.cn/Article/details/gt2smlwrdwm.html

[R03] 只读变量
来源：http://dali.jiagoushi.top/Article/details/gt2tdxxwrsi.html

readonly PI=3.14
来源：http://dali.shangyingyoupin.top/Article/details/gt2polgptwg.html

[R04] 位置参数
来源：http://dali.yongpay.top/Article/details/gt2qgsmwbjv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.snrcjt.cn/Article/details/gt2pitsgkib.html

[R05] 参数默认值
来源：http://dali.sweek.top/Article/details/gt2bmwyytfr.html

name="${1:-default}"
来源：http://dali.xuanzx.com/Article/details/gt2aybjpjne.html

[R06] 判断命令是否存在
来源：http://dali.aibaodan.cn/Article/details/gt2ayizmhao.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.chenzaomai.com/Article/details/gt2smcsaxex.html

[R07] if 判断文件
来源：http://dali.haohaochexian.top/Article/details/gt2bxuzjzzs.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.guowangkeji.top/Article/details/gt2yutfuwdq.html

[R08] 数值比较
来源：http://dali.zhengqikj.top/Article/details/gt2apdwysak.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hnxiangtu.top/Article/details/gt2edmbiryp.html

[R09] 字符串比较
来源：http://dali.aibaodan.cn/Article/details/gt2hyjmcyah.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.dianchejie.cn/Article/details/gt2lbkxosnt.html

[R10] 正则匹配
来源：http://dali.zhengqikj.top/Article/details/gt2adpfjtfz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.aizwys.cn/Article/details/gt2hpguqtqs.html

[R11] case 多分支
来源：http://dali.guannengcc.top/Article/details/gt2iascqfon.html

case "$1" in
来源：http://dali.ppjwa.cn/Article/details/gt2bkuxizel.html

start) echo "启动" ;;
来源：http://dali.hnqzz.top/Article/details/gt2vfnkpieg.html

stop)  echo "停止" ;;
来源：http://dali.svipenyu.cn/Article/details/gt2wxvhvlad.html

*)     echo "未知命令" ;;
来源：http://dali.dashuyun.cn/Article/details/gt2vkjylayt.html

esac
来源：http://dali.vqdsnc.cn/Article/details/gt2mimjzizm.html

[R12] for 遍历文件
来源：http://dali.birdmap.top/Article/details/gt2sufvrklc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.tanke756.top/Article/details/gt2aopjggbk.html

[R13] for 计数循环
来源：http://dali.0kj1m.cn/Article/details/gt2nskpoefp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gaohongyu789.top/Article/details/gt2idceupre.html

[R14] C 风格 for
来源：http://dali.snrcjt.cn/Article/details/gt2pcjpojtt.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jiagoushi.top/Article/details/gt2tcqpprak.html

[R15] while 逐行读文件
来源：http://dali.sysykeji.top/Article/details/gt2hxxemekn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.wangshuangyany.cn/Article/details/gt2lyladyye.html

[R16] until 等待条件
来源：http://dali.shzxlz.cn/Article/details/gt2thifkvds.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.pycfn.com/Article/details/gt2kbamqagt.html

[R17] 数组定义与取值
来源：http://dali.redwolf501.top/Article/details/gt2ikgylhej.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.guowangkeji.top/Article/details/gt2mdnlbowa.html

[R18] 遍历数组
来源：http://dali.cqqwz.cn/Article/details/gt2auenuyul.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cdnleiting.top/Article/details/gt2ypitoztc.html

[R19] 数组长度
来源：http://dali.cucudq.cn/Article/details/gt2ealaebjr.html

echo "${#arr[@]}"
来源：http://dali.gotoacloud.top/Article/details/gt2skazqbuz.html

[R20] 关联数组（字典）
来源：http://dali.dianchejie.cn/Article/details/gt2rwholluy.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cashguo.top/Article/details/gt2nlisnmvp.html

[R21] 字符串长度
来源：http://dali.ivvv.top/Article/details/gt2hoxpqyed.html

echo "${#s}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2anpvsvqd.html

[R22] 截取子串
来源：http://dali.vqdsnc.cn/Article/details/gt2rrfhrvig.html

echo "${s:0:5}"
来源：http://dali.jyoumei.cn/Article/details/gt2plhzlyll.html

[R23] 字符串替换
来源：http://dali.daria6918.cn/Article/details/gt2tboonzgy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hongshengwenyu.top/Article/details/gt2xnnokwkf.html

[R24] 大小写转换
来源：http://dali.xinyue.icu/Article/details/gt2masiczpf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yj202588.top/Article/details/gt2oymekzyj.html

[R25] 去后缀 / 去前缀
来源：http://dali.pengpengdd.cyou/Article/details/gt2vfrfkkvj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.nanxuanxn.top/Article/details/gt2wgchozha.html

[R26] 命令替换
来源：http://dali.yvedp.cn/Article/details/gt2lunwmadv.html

now=$(date +%F); echo "$now"
来源：http://dali.hnqzz.top/Article/details/gt2zbcikkoz.html

[R27] 算术展开
来源：http://dali.bjfxy.top/Article/details/gt2wiwweztu.html

echo $((1 + 2 * 3))
来源：http://dali.yj202588.top/Article/details/gt2jcxrwmby.html

[R28] 浮点运算
来源：http://dali.ivvv.top/Article/details/gt2leobvzgk.html

echo "scale=2; 10/3" | bc
来源：http://dali.xuetiantiany.cn/Article/details/gt2jqnuwsxo.html

[R29] 定义函数
来源：http://dali.9152youxi.cn/Article/details/gt2hgiywmuq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zdqjudy.top/Article/details/gt2okmtfaxs.html

[R30] 函数返回状态码
来源：http://dali.nanxuanxn.top/Article/details/gt2hpsyrzoi.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhiwuduotai.top/Article/details/gt2ikenmvoq.html

[R31] 局部变量
来源：http://dali.hfpthk.cn/Article/details/gt2omcsqyle.html

f() { local x=1; echo "$x"; }
来源：http://dali.nanxinkj.top/Article/details/gt2rhmhmwfs.html

[R32] 参数个数校验
来源：http://dali.xuetiantiany.cn/Article/details/gt2rbanhkpq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yvedp.cn/Article/details/gt2mvxyvwit.html

[R33] 捕获错误并提示行号
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nxtpjght.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gaohongyu789.top/Article/details/gt2wdcpozhj.html

[R34] 退出时清理
来源：http://dali.gogol.net.cn/Article/details/gt2vpsjdrvr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shzxlz.cn/Article/details/gt2zhtszenf.html

[R35] 后台执行并等待
来源：http://dali.zdqjudy.top/Article/details/gt2scfwknus.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhengqikj.top/Article/details/gt2bgyimbds.html

[R36] 并发执行多个任务
来源：http://dali.hongshengwenyu.top/Article/details/gt2xihznebp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ehwqpu.com/Article/details/gt2fuyexgmu.html

[R37] 把输出赋给变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vshtlozf.html

files=$(ls -1)
来源：http://dali.zhongyouzk.top/Article/details/gt2dtzhtnch.html

[R38] 管道串联
来源：http://dali.shanyushiyangtech.top/Article/details/gt2arbjcwnf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.quarkkingdee.top/Article/details/gt2qtfqburj.html

[R39] 重定向标准输出与错误
来源：http://dali.daria6918.cn/Article/details/gt2kwllaajp.html

cmd > out.log 2>&1
来源：http://dali.haohaochexian.top/Article/details/gt2mukfklvg.html

[R40] 追加写日志
来源：http://dali.daria6918.cn/Article/details/gt2wrrjkvsp.html

echo "log" >> out.log
来源：http://dali.birdmap.top/Article/details/gt2raellxts.html

[R41] 丢弃输出
来源：http://dali.wangshuangyany.cn/Article/details/gt2mysfmcab.html

cmd >/dev/null 2>&1
来源：http://dali.sufxvd.cn/Article/details/gt2iwpvuhvv.html

[R42] 输入重定向
来源：http://dali.yongpay.top/Article/details/gt2awgticze.html

wc -l < a.txt
来源：http://dali.bjfxy.top/Article/details/gt2wxodbatw.html

[R43] 按名字查找文件
来源：http://dali.guannengcc.top/Article/details/gt2mtkqgfcl.html

find . -name "*.log" -type f
来源：http://dali.kuanghao11.cn/Article/details/gt2nxdioqda.html

[R44] 按修改时间查找
来源：http://dali.dashuyun.cn/Article/details/gt2cjarbtmx.html

find . -mtime -7 -type f
来源：http://dali.yvedp.cn/Article/details/gt2zfizkocb.html

[R45] 批量删除
来源：http://dali.quarkkingdee.top/Article/details/gt2cxtcbkqq.html

find . -name "*.tmp" -delete
来源：http://dali.daria6918.cn/Article/details/gt2rzdbuaad.html

[R46] 递归替换文件内容
来源：http://dali.dashuyun.cn/Article/details/gt2wqjlyyda.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hfpthk.cn/Article/details/gt2hqggsama.html

[R47] sed 单行替换
来源：http://dali.zhongyouzk.top/Article/details/gt2ucbzvwxv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wtqsbdzz.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwupnza.html

awk '{print $1, $3}' a.txt
来源：http://dali.hysaishi.cn/Article/details/gt2fgfzstrv.html

[R49] awk 带条件
来源：http://dali.ivvv.top/Article/details/gt2grcberff.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.nanxuanxn.top/Article/details/gt2qnmfpezo.html

[R50] awk 求和
来源：http://dali.xuanzx.com/Article/details/gt2iwqnerfg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.dianchejie.cn/Article/details/gt2xvwgjsad.html

[R51] 排序去重取前几
来源：http://dali.daria6918.cn/Article/details/gt2jgntpfwj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.0kj1m.cn/Article/details/gt2lrztykzy.html

[R52] 统计行数
来源：http://dali.pengpengdd.cyou/Article/details/gt2olueiuyt.html

wc -l a.txt
来源：http://dali.guannengcc.top/Article/details/gt2sryhsprn.html

[R53] 查看文件头与实时尾
来源：http://dali.yvedp.cn/Article/details/gt2fjjeyzoy.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.daria6918.cn/Article/details/gt2xspfahlg.html

[R54] 比较两个文件
来源：http://dali.ybcxt.top/Article/details/gt2dhifmqxv.html

diff a.txt b.txt
来源：http://dali.smart0.xyz/Article/details/gt2trlfbcum.html

[R55] 压缩与解压
来源：http://dali.zhixingplan.top/Article/details/gt2cmtwkfuw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhiwuduotai.top/Article/details/gt2dgybjwza.html

[R56] 远程拷贝
来源：http://dali.daria6918.cn/Article/details/gt2ukmfbauj.html

scp file user@host:/path/
来源：http://dali.redwolf501.top/Article/details/gt2aefkuygt.html

[R57] 远程执行命令
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zfzdzmjf.html

ssh user@host 'uptime'
来源：http://dali.xuanzx.com/Article/details/gt2iauuhzrm.html

[R58] 下载文件
来源：http://dali.aizwys.cn/Article/details/gt2enknhjwv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhixingplan.top/Article/details/gt2zlavkqmp.html

[R59] 发 POST JSON
来源：http://dali.shuidangran.top/Article/details/gt2mxvoewas.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.smart0.xyz/Article/details/gt2zxfqyzvy.html

[R60] 只看 HTTP 状态码
来源：http://dali.feifeiyinyue.top/Article/details/gt2wkmiyjah.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhongyouzk.top/Article/details/gt2omzmnzvn.html

[R61] 磁盘占用
来源：http://dali.yuxming.cn/Article/details/gt2vbzfjxqy.html

df -h;  du -sh *
来源：http://dali.yj20258888.top/Article/details/gt2raaihdwy.html

[R62] 找最占空间的文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2djzmauwt.html

du -ah . | sort -rh | head -10
来源：http://dali.hammf.cn/Article/details/gt2ivfvrgbz.html

[R63] 内存与进程
来源：http://dali.yuxming.cn/Article/details/gt2umutkcec.html

free -h;  ps aux | grep nginx
来源：http://dali.xylfe.cn/Article/details/gt2eiuoztcx.html

[R64] 结束进程
来源：http://dali.zhongyouzk.top/Article/details/gt2jeemuxfd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.havefunace.top/Article/details/gt2opzkskui.html

[R65] 查看端口占用
来源：http://dali.daxiang520.top/Article/details/gt2rfwgjlzc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jqgfzy.top/Article/details/gt2nxmdiyxt.html

[R66] 定时任务
来源：http://dali.birdmap.top/Article/details/gt2idhvwexl.html

crontab -e;  crontab -l
来源：http://dali.yj20258.top/Article/details/gt2olctmdef.html

[R67] 生成随机十六进制串
来源：http://dali.jinqigufen.top/Article/details/gt2hnkuqflf.html


<!-- 参考信息 -->