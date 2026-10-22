代发 wailian999

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.sweek.top/Article/details/gt2vkgirhwb.html

[Q18] 模糊匹配
来源：http://dali.hnqzz.top/Article/details/gt2sytennrj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shangyingyoupin.top/Article/details/gt2iilaugyt.html

[Q19] 范围查询
来源：http://dali.tian-w.cn/Article/details/gt2obyhvmdn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cashguo.top/Article/details/gt2tjnnawqe.html

[Q20] IN 列表
来源：http://dali.zhiwuduotai.top/Article/details/gt2ubwkwkjn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.dianchejie.cn/Article/details/gt2sgxbsqal.html

[Q21] 空值判断
来源：http://dali.xylfe.cn/Article/details/gt2jynwdqra.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.mhx1999.top/Article/details/gt2thbsiplb.html

[Q22] 排序
来源：http://dali.xziqi.cn/Article/details/gt2glfgsddf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.andypj.xyz/Article/details/gt2bxcdfxmb.html

[Q23] 分页
来源：http://dali.yueranfly.top/Article/details/gt2nusonlxt.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhengqikj.top/Article/details/gt2ewgogkvp.html

[Q24] 去重
来源：http://dali.jyoumei.cn/Article/details/gt2ylwkdttv.html

SELECT DISTINCT city FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2zizwiyhq.html

[Q25] 只取前 N 条
来源：http://dali.ydzc1.top/Article/details/gt2jlqyxebw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cdnleiting.top/Article/details/gt2upmnltpj.html

[Q26] 计数
来源：http://dali.zhengqikj.top/Article/details/gt2xmsmwmho.html

SELECT COUNT(*) FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2uggskcgu.html

[Q27] 条件计数
来源：http://dali.smart0.xyz/Article/details/gt2gdvevisu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.sxryk.cn/Article/details/gt2rhyzzaxw.html

[Q28] 求和与平均
来源：http://dali.svipenyu.cn/Article/details/gt2mvsjlojx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gt2ivfgungl.html

[Q29] 最大最小值
来源：http://dali.zhiwuduotai.top/Article/details/gt2thqqxine.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.tanke756.top/Article/details/gt2vjqdiwaq.html

[Q30] 分组统计
来源：http://dali.ehwqpu.com/Article/details/gt2bpkxpqxi.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zdqjudy.top/Article/details/gt2arbswbuy.html

[Q31] 分组后过滤
来源：http://dali.wangshuangyany.cn/Article/details/gt2xzexehii.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xuetiantiany.cn/Article/details/gt2hvxprfyd.html

[Q32] 分组拼接字符串
来源：http://dali.yangfankeji.com/Article/details/gt2lhhnemyh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhoulong.xyz/Article/details/gt2ddrcpksn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uwylmdxz.html

[Q33] 多列分组
来源：http://dali.gzhubu.top/Article/details/gt2zeoydnhv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.0kj1m.cn/Article/details/gt2beavhbbe.html

[Q34] 每组取第一条
来源：http://dali.yongpay.top/Article/details/gt2irhvanze.html

SELECT * FROM (
来源：http://dali.snrcjt.cn/Article/details/gt2khfbtgxl.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.tianlin.xyz/Article/details/gt2psbzgvvh.html

) t WHERE rn = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ktwisqhq.html

[Q35] 内连接
来源：http://dali.cucudq.cn/Article/details/gt2awpialkl.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gotoacloud.top/Article/details/gt2lzhgbrmc.html

[Q36] 左连接
来源：http://dali.nwbrower.top/Article/details/gt2yvvfyghb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.havefunace.top/Article/details/gt2auygobmq.html

[Q37] 右连接
来源：http://dali.yj20258888.top/Article/details/gt2fbosjsua.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.guannengcc.top/Article/details/gt2uupvdouu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.andypj.xyz/Article/details/gt2kvbpkbol.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.quarkkingdee.top/Article/details/gt2eypziaoj.html

[Q39] 自连接（查上下级）
来源：http://dali.jiagoushi.top/Article/details/gt2cnukgyge.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cheryme.top/Article/details/gt2nqhoixgv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.meibo888.top/Article/details/gt2gfptwgjj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yonumen.top/Article/details/gt2uylpbjyd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sxryk.cn/Article/details/gt2ohxgyytk.html

[Q41] 多表连接
来源：http://dali.meibo888.top/Article/details/gt2xtzqqvwm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.daxiang520.top/Article/details/gt2dvrtuppg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gzhubu.top/Article/details/gt2pwzimftc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zycfv.cn/Article/details/gt2ndgdwbip.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hyhilove.html

SELECT u.name, o.amount FROM users u
来源：http://dali.316326.xyz/Article/details/gt2wuudaagk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhengqikj.top/Article/details/gt2hlmhaoio.html

[Q43] 标量子查询
来源：http://dali.ppjwa.cn/Article/details/gt2jdhrqvqo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.dianchejie.cn/Article/details/gt2nlnrkuwn.html

[Q44] IN 子查询
来源：http://dali.daxiang520.top/Article/details/gt2qbcndsnc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhiwuduotai.top/Article/details/gt2fldxtpzf.html

[Q45] EXISTS 判断存在
来源：http://dali.ybcxt.top/Article/details/gt2pptzovvq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgfzy.top/Article/details/gt2ysnhcpfo.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hfpthk.cn/Article/details/gt2weymomxs.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gogol.net.cn/Article/details/gt2rmqgsbqy.html

[Q47] 与平均值比较
来源：http://dali.yongpay.top/Article/details/gt2xybhcqay.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cucudq.cn/Article/details/gt2iwhogmth.html

[Q48] CTE 公用表表达式
来源：http://dali.shangyingyoupin.top/Article/details/gt2qeczmpbz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cdnleiting.top/Article/details/gt2kzhcnrix.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gzhubu.top/Article/details/gt2wplephfg.html

[Q49] 更新单行
来源：http://dali.smart0.xyz/Article/details/gt2vlpgzmym.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.chenlongwang.top/Article/details/gt2ihqubrsi.html

[Q50] 批量更新
来源：http://dali.pycfn.com/Article/details/gt2pasdotzm.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.smart0.xyz/Article/details/gt2fwoftjua.html

[Q51] 用子查询更新
来源：http://dali.zhoulong.xyz/Article/details/gt2dzfdngpr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shuidangran.top/Article/details/gt2mnuvalhg.html

[Q52] 删除指定行
来源：http://dali.yuxming.cn/Article/details/gt2oooytrzc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shuidangran.top/Article/details/gt2thlhohbv.html

[Q53] 按条件删除
来源：http://dali.nanxuanxn.top/Article/details/gt2ctkyxahs.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.smart0.xyz/Article/details/gt2oxuxqkrz.html

[Q54] 清空表
来源：http://dali.yvedp.cn/Article/details/gt2qldodzqt.html

TRUNCATE TABLE logs;
来源：http://dali.zhongyouzk.top/Article/details/gt2ahuxbrts.html

[Q55] 排名（并列占位）
来源：http://dali.shzxlz.cn/Article/details/gt2wbslrdza.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.c1oappe.top/Article/details/gt2gbjudluo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.sweek.top/Article/details/gt2zuiwuvhw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.wangdashe.top/Article/details/gt2kuqroffy.html

[Q57] 行号
来源：http://dali.xylfe.cn/Article/details/gt2wpwqdalc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2fdshhiaw.html

[Q58] 累计求和
来源：http://dali.shzxlz.cn/Article/details/gt2dzhylvdo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gt2skobluhy.html

[Q59] 分组内累计
来源：http://dali.guowangkeji.top/Article/details/gt2zbkecndx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gt2jcnhukpq.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinqigfzy.top/Article/details/gt2xgbwpgjf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.mhx1999.top/Article/details/gt2qvlexchn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gt2ymqdqsfa.html

[Q61] 移动平均
来源：http://dali.yj20258.top/Article/details/gt2zhnmjxef.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gt2pixbynuh.html

[Q62] 分组占比
来源：http://dali.chenzaomai.com/Article/details/gt2waqussci.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xuetiantiany.cn/Article/details/gt2ijcnagon.html

[Q63] 开启事务
来源：http://dali.yvedp.cn/Article/details/gt2xclgwvgl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ybcxt.top/Article/details/gt2inzxwpgu.html

[Q64] 提交事务
来源：http://dali.yongpay.top/Article/details/gt2yqkgkurf.html

COMMIT;
来源：http://dali.zycfv.cn/Article/details/gt2nevdznsv.html

[Q65] 回滚事务
来源：http://dali.jianghu66.top/Article/details/gt2jopnehdj.html

ROLLBACK;
来源：http://dali.shangyingyoupin.top/Article/details/gt2bqmnlfvb.html

[Q66] 行锁查询
来源：http://dali.snrcjt.cn/Article/details/gt2lhrihtlg.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhoulong.xyz/Article/details/gt2okocursj.html

[Q67] 设置隔离级别
来源：http://dali.zhengqikj.top/Article/details/gt2jqclwvnf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jianghu66.top/Article/details/gt2emfjzxbq.html

[Q68] 保存点
来源：http://dali.dianchejie.cn/Article/details/gt2mgeyukhb.html

SAVEPOINT sp1;
来源：http://dali.yvedp.cn/Article/details/gt2gzhzjrjq.html

ROLLBACK TO sp1;
来源：http://dali.chenlongwang.top/Article/details/gt2pckcrwuf.html

[Q69] 查看执行计划
来源：http://dali.yuxming.cn/Article/details/gt2cswxnxpc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yvedp.cn/Article/details/gt2iobivggq.html

[Q70] 更新统计信息
来源：http://dali.chenlongwang.top/Article/details/gt2vvcriebi.html

ANALYZE TABLE users;
来源：http://dali.smart0.xyz/Article/details/gt2tfdsgdej.html

[Q71] 查看建表语句
来源：http://dali.fengsongda.top/Article/details/gt2urmhzvtv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jzklqxig.html

[Q72] 查看索引
来源：http://dali.shuidangran.top/Article/details/gt2khhrzkpx.html

SHOW INDEX FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2whmcqgab.html

[Q73] 查看表状态
来源：http://dali.xziqi.cn/Article/details/gt2plqwdtsn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.nanxuanxn.top/Article/details/gt2zvuwxsuj.html

[Q74] 强制使用索引
来源：http://dali.daxiang520.top/Article/details/gt2zryqkbre.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cqqwz.cn/Article/details/gt2ujmhgdpa.html

[Q75] 日期格式化
来源：http://dali.fzhhl.top/Article/details/gt2tjgdmssc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.c1oappe.top/Article/details/gt2dgrjmrcp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qsxvebgz.html

[Q76] 按天统计
来源：http://dali.redwolf501.top/Article/details/gt2zixdegzs.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yvedp.cn/Article/details/gt2hyxofhlq.html

[Q77] 时间加减
来源：http://dali.daria6918.cn/Article/details/gt2dplzhayi.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yueranfly.top/Article/details/gt2wuyzqhyl.html

[Q78] 当前时间
来源：http://dali.pengpengdd.cyou/Article/details/gt2yjmgvvzr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.316326.xyz/Article/details/gt2bydrsjpg.html

[Q79] 字符串拼接
来源：http://dali.xziqi.cn/Article/details/gt2vvwtkbsu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hnxiangtu.top/Article/details/gt2vhczvkld.html

[Q80] 字符串截取
来源：http://dali.yueranfly.top/Article/details/gt2sdaprmje.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2lxradpub.html

[Q81] 字符串替换
来源：http://dali.hnqzz.top/Article/details/gt2ltvfgumz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ozrmufcz.html

[Q82] 字符长度与字节长度
来源：http://dali.shuidangran.top/Article/details/gt2hjhmlzhp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2cjitxpjv.html

[Q83] 大小写转换
来源：http://dali.iojbl.cn/Article/details/gt2loyphypy.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2spjzbqni.html

[Q84] 去除首尾空格
来源：http://dali.shuidangran.top/Article/details/gt2ybbaasyg.html

SELECT TRIM(name) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2ncvufuwo.html

[Q85] 数值取整
来源：http://dali.hywenlv.cn/Article/details/gt2mgpwpsgn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.feifeiyinyue.top/Article/details/gt2erkvontc.html

[Q86] 读取 JSON 字段
来源：http://dali.sxryk.cn/Article/details/gt2jcczubod.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.feifeiyinyue.top/Article/details/gt2suqmqqvg.html

[Q87] JSON 字段做条件
来源：http://dali.havefunace.top/Article/details/gt2xunsyowo.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jyoumei.cn/Article/details/gt2itxsbvni.html

[Q88] 行转列（条件聚合）
来源：http://dali.sufxvd.cn/Article/details/gt2xsspryfk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.daxiang520.top/Article/details/gt2mnksyqgv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.birdmap.top/Article/details/gt2vuoqwnck.html

[Q89] 判断表是否存在
来源：http://dali.hysaishi.cn/Article/details/gt2ygtnlsnj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.redwolf501.top/Article/details/gt2fdisuyzx.html

[Q90] 生成序号列
来源：http://dali.0kj1m.cn/Article/details/gt2aoqbnvll.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hysaishi.cn/Article/details/gt2keoxfsgp.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2lnvscwhx.html

R. Bash 专题
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2digvgmvu.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2fsbbdpea.html

[R01] shebang 与严格模式
来源：http://dali.yongpay.top/Article/details/gt2nkpdivmd.html

#!/usr/bin/env bash
来源：http://dali.fengsongda.top/Article/details/gt2zolltjxc.html

set -euo pipefail
来源：http://dali.daxiang520.top/Article/details/gt2ofbucyst.html

[R02] 变量赋值与使用
来源：http://dali.daria6918.cn/Article/details/gt2fkahxgms.html

name="Tom"; echo "$name"
来源：http://dali.zhiwuduotai.top/Article/details/gt2wpvowgme.html

[R03] 只读变量
来源：http://dali.hfpthk.cn/Article/details/gt2qnyakfzn.html

readonly PI=3.14
来源：http://dali.zhoulong.xyz/Article/details/gt2gmhklmhw.html

[R04] 位置参数
来源：http://dali.zhengqikj.top/Article/details/gt2mnokplbz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cucudq.cn/Article/details/gt2rttwnxiu.html

[R05] 参数默认值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2amuazyhh.html

name="${1:-default}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2aexexkjs.html

[R06] 判断命令是否存在
来源：http://dali.snrcjt.cn/Article/details/gt2nmgikuhs.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.9152youxi.cn/Article/details/gt2hsexuizc.html

[R07] if 判断文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fpfbagin.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhengqikj.top/Article/details/gt2zcrsaaxd.html

[R08] 数值比较
来源：http://dali.svipenyu.cn/Article/details/gt2spfbvzqo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.chenlongwang.top/Article/details/gt2sflazsjj.html

[R09] 字符串比较
来源：http://dali.sysykeji.top/Article/details/gt2cdcqjuhu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.andypj.xyz/Article/details/gt2amqxzvpp.html

[R10] 正则匹配
来源：http://dali.dianchejie.cn/Article/details/gt2ivpklino.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.pycfn.com/Article/details/gt2bhwtgash.html

[R11] case 多分支
来源：http://dali.tian-w.cn/Article/details/gt2imqazopg.html

case "$1" in
来源：http://dali.cheryme.top/Article/details/gt2cynscvyg.html

start) echo "启动" ;;
来源：http://dali.yongpay.top/Article/details/gt2yzmjeicm.html

stop)  echo "停止" ;;
来源：http://dali.snrcjt.cn/Article/details/gt2rwphlbjq.html

*)     echo "未知命令" ;;
来源：http://dali.0kj1m.cn/Article/details/gt2dxqdxkac.html

esac
来源：http://dali.sxryk.cn/Article/details/gt2ywdfbywv.html

[R12] for 遍历文件
来源：http://dali.dashuyun.cn/Article/details/gt2usunfjrs.html

for f in *.txt; do echo "$f"; done
来源：http://dali.nanxinkj.top/Article/details/gt2qahjvboy.html

[R13] for 计数循环
来源：http://dali.dashuyun.cn/Article/details/gt2rhooxlid.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinqigfzy.top/Article/details/gt2wxuncoqw.html

[R14] C 风格 for
来源：http://dali.yj20258.top/Article/details/gt2bqbkelcs.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shzxlz.cn/Article/details/gt2wvjghgtg.html

[R15] while 逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2qafkkyqo.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gogol.net.cn/Article/details/gt2rvnzxlml.html

[R16] until 等待条件
来源：http://dali.0kj1m.cn/Article/details/gt2xlfeuidm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.snrcjt.cn/Article/details/gt2tqdtvzos.html

[R17] 数组定义与取值
来源：http://dali.chenzaomai.com/Article/details/gt2fynwccrt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.chenzaomai.com/Article/details/gt2kmfsxlxg.html

[R18] 遍历数组
来源：http://dali.yuxming.cn/Article/details/gt2rrqzqutu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.smart0.xyz/Article/details/gt2xgposuxp.html

[R19] 数组长度
来源：http://dali.zhengqikj.top/Article/details/gt2aalxrulg.html

echo "${#arr[@]}"
来源：http://dali.kuanghao11.cn/Article/details/gt2hrmpaozz.html

[R20] 关联数组（字典）
来源：http://dali.sysykeji.top/Article/details/gt2eakryqve.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cashguo.top/Article/details/gt2vidfxaxt.html

[R21] 字符串长度
来源：http://dali.yj20258888.top/Article/details/gt2shibhddx.html

echo "${#s}"
来源：http://dali.guannengcc.top/Article/details/gt2xgvddnuu.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2iostklon.html

echo "${s:0:5}"
来源：http://dali.sysykeji.top/Article/details/gt2llfwgtxd.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fbcpffew.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oimtaztd.html

[R24] 大小写转换
来源：http://dali.hnxiangtu.top/Article/details/gt2lyefdekk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yuanzhike.top/Article/details/gt2tjmcwdoj.html

[R25] 去后缀 / 去前缀
来源：http://dali.xziqi.cn/Article/details/gt2jbcqqmkm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tacdmiog.html

[R26] 命令替换
来源：http://dali.gzhubu.top/Article/details/gt2mvnpjdzc.html

now=$(date +%F); echo "$now"
来源：http://dali.chenlongwang.top/Article/details/gt2aisynlaf.html

[R27] 算术展开
来源：http://dali.hnqzz.top/Article/details/gt2bjblzhxx.html

echo $((1 + 2 * 3))
来源：http://dali.hnxiangtu.top/Article/details/gt2wfwnnuah.html

[R28] 浮点运算
来源：http://dali.gogol.net.cn/Article/details/gt2mhwwcoia.html

echo "scale=2; 10/3" | bc
来源：http://dali.guowangkeji.top/Article/details/gt2yaxortal.html

[R29] 定义函数
来源：http://dali.ppjwa.cn/Article/details/gt2cafhoweb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.meibo888.top/Article/details/gt2fmekdkdi.html

[R30] 函数返回状态码
来源：http://dali.redwolf501.top/Article/details/gt2yjnbgbgt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ydzc1.top/Article/details/gt2onjnrmlf.html

[R31] 局部变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eymvfmiw.html

f() { local x=1; echo "$x"; }
来源：http://dali.ppjwa.cn/Article/details/gt2arsfrnaf.html

[R32] 参数个数校验
来源：http://dali.hysaishi.cn/Article/details/gt2jupieldd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.nwbrower.top/Article/details/gt2imjqwpcn.html

[R33] 捕获错误并提示行号
来源：http://dali.bjfxy.top/Article/details/gt2nqxiqeaa.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.smart0.xyz/Article/details/gt2etpasrgg.html

[R34] 退出时清理
来源：http://dali.gogol.net.cn/Article/details/gt2hgytccjq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xylfe.cn/Article/details/gt2wdaroime.html

[R35] 后台执行并等待
来源：http://dali.haohaochexian.top/Article/details/gt2lutsiyfh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.sxryk.cn/Article/details/gt2ewgdvuyu.html

[R36] 并发执行多个任务
来源：http://dali.daria6918.cn/Article/details/gt2tmybcxof.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.snrcjt.cn/Article/details/gt2yqoyephe.html

[R37] 把输出赋给变量
来源：http://dali.mhx1999.top/Article/details/gt2xqejgler.html

files=$(ls -1)
来源：http://dali.0kj1m.cn/Article/details/gt2dwtqtydt.html

[R38] 管道串联
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mkzvcxpq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jqgfzy.top/Article/details/gt2cibypmro.html

[R39] 重定向标准输出与错误
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nqdtzjsy.html

cmd > out.log 2>&1
来源：http://dali.wangshuangyany.cn/Article/details/gt2zzjrlrpj.html

[R40] 追加写日志
来源：http://dali.hfpthk.cn/Article/details/gt2rqnljoga.html

echo "log" >> out.log
来源：http://dali.xylfe.cn/Article/details/gt2valktwfw.html

[R41] 丢弃输出
来源：http://dali.zhixingplan.top/Article/details/gt2bvnjrbau.html

cmd >/dev/null 2>&1
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bukoazbm.html

[R42] 输入重定向
来源：http://dali.ydzc1.top/Article/details/gt2xmffppkc.html

wc -l < a.txt
来源：http://dali.hywenlv.cn/Article/details/gt2zbrnidgu.html

[R43] 按名字查找文件
来源：http://dali.iojbl.cn/Article/details/gt2zkxumifp.html

find . -name "*.log" -type f
来源：http://dali.sweek.top/Article/details/gt2eowgjqwe.html

[R44] 按修改时间查找
来源：http://dali.nanxinkj.top/Article/details/gt2jqtewtcs.html

find . -mtime -7 -type f
来源：http://dali.yj20258888.top/Article/details/gt2sqrxnfhi.html

[R45] 批量删除
来源：http://dali.hywenlv.cn/Article/details/gt2blxuiejv.html

find . -name "*.tmp" -delete
来源：http://dali.shangyingyoupin.top/Article/details/gt2ipvsdgtv.html

[R46] 递归替换文件内容
来源：http://dali.yanxiufei.cn/Article/details/gt2mvuwwnpf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.iojbl.cn/Article/details/gt2npidogig.html

[R47] sed 单行替换
来源：http://dali.jqgfzy.top/Article/details/gt2hqydbpbu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.chenzaomai.com/Article/details/gt2rdahklwz.html

[R48] awk 取指定列
来源：http://dali.guannengcc.top/Article/details/gt2dugtjwuq.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tjltylbl.html

[R49] awk 带条件
来源：http://dali.hywenlv.cn/Article/details/gt2ugevoufd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hysaishi.cn/Article/details/gt2lbpivwnm.html

[R50] awk 求和
来源：http://dali.9152youxi.cn/Article/details/gt2qgpjosfv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ppjwa.cn/Article/details/gt2pqobmasr.html

[R51] 排序去重取前几
来源：http://dali.pycfn.com/Article/details/gt2nqopthbe.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.mhx1999.top/Article/details/gt2rbglaaew.html

[R52] 统计行数
来源：http://dali.wangshuangyany.cn/Article/details/gt2ltzprwdf.html

wc -l a.txt
来源：http://dali.zdqjudy.top/Article/details/gt2iplvijjn.html

[R53] 查看文件头与实时尾
来源：http://dali.xuetiantiany.cn/Article/details/gt2qnbdrjea.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.sweek.top/Article/details/gt2necootjs.html

[R54] 比较两个文件
来源：http://dali.bjfxy.top/Article/details/gt2sxvrqcmc.html

diff a.txt b.txt
来源：http://dali.nwbrower.top/Article/details/gt2gqzpimhs.html

[R55] 压缩与解压
来源：http://dali.chenzaomai.com/Article/details/gt2rgcdjaxh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yonumen.top/Article/details/gt2jokzxkhq.html

[R56] 远程拷贝
来源：http://dali.jlsjyb.cn/Article/details/gt2xocvmaeo.html

scp file user@host:/path/
来源：http://dali.chenlongwang.top/Article/details/gt2nvizprmz.html

[R57] 远程执行命令
来源：http://dali.meibo888.top/Article/details/gt2kksnzery.html

ssh user@host 'uptime'
来源：http://dali.zhengqikj.top/Article/details/gt2fzrdddck.html

[R58] 下载文件
来源：http://dali.tanke756.top/Article/details/gt2wrurxotg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhixingplan.top/Article/details/gt2vcczjuab.html

[R59] 发 POST JSON
来源：http://dali.daxiang520.top/Article/details/gt2yvwxipaj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.nanxinkj.top/Article/details/gt2fwqwgser.html

[R60] 只看 HTTP 状态码
来源：http://dali.gaohongyu789.top/Article/details/gt2ofpkxnfo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jlsjyb.cn/Article/details/gt2vasrfofo.html

[R61] 磁盘占用
来源：http://dali.ehwqpu.com/Article/details/gt2yazlrgnh.html

df -h;  du -sh *
来源：http://dali.wangdashe.top/Article/details/gt2elobrwlz.html

[R62] 找最占空间的文件
来源：http://dali.dianchejie.cn/Article/details/gt2uudgieih.html

du -ah . | sort -rh | head -10
来源：http://dali.xylfe.cn/Article/details/gt2hjqebwli.html

[R63] 内存与进程
来源：http://dali.sufxvd.cn/Article/details/gt2bsnvoqec.html

free -h;  ps aux | grep nginx
来源：http://dali.zhengqikj.top/Article/details/gt2bviuojho.html

[R64] 结束进程
来源：http://dali.0kj1m.cn/Article/details/gt2yosxolxd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.chenzaomai.com/Article/details/gt2eijevqyj.html

[R65] 查看端口占用
来源：http://dali.dashuyun.cn/Article/details/gt2ourgwinl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yuanzhike.top/Article/details/gt2vquxcfpu.html

[R66] 定时任务
来源：http://dali.guowangkeji.top/Article/details/gt2cceezccg.html

crontab -e;  crontab -l
来源：http://dali.zdqjudy.top/Article/details/gt2iblvyiqj.html

[R67] 生成随机十六进制串
来源：http://dali.9152youxi.cn/Article/details/gt2afrkcyhd.html


<!-- 参考信息 -->