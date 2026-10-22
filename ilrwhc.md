代发 wailian999

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uiwbqqil.html

[Q22] 排序
来源：http://dali.mhx1999.top/Article/details/gt2mhlvbdzn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhiwuduotai.top/Article/details/gt2tpepzdbk.html

[Q23] 分页
来源：http://dali.shuidangran.top/Article/details/gt2mkdfjgfm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.sufxvd.cn/Article/details/gt2fouyvorb.html

[Q24] 去重
来源：http://dali.ydzc1.top/Article/details/gt2ysnhrbpa.html

SELECT DISTINCT city FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2qchpfmco.html

[Q25] 只取前 N 条
来源：http://dali.jianghu66.top/Article/details/gt2diucukxj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shzxlz.cn/Article/details/gt2vnijhcne.html

[Q26] 计数
来源：http://dali.dashuyun.cn/Article/details/gt2cybvhphh.html

SELECT COUNT(*) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2eavufgnv.html

[Q27] 条件计数
来源：http://dali.jianghu66.top/Article/details/gt2clmxaoht.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ubawvljf.html

[Q28] 求和与平均
来源：http://dali.guannengcc.top/Article/details/gt2pxloopss.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.birdmap.top/Article/details/gt2sifakayg.html

[Q29] 最大最小值
来源：http://dali.aizwys.cn/Article/details/gt2uzfbjrpa.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2boniqnyu.html

[Q30] 分组统计
来源：http://dali.yuanzhike.top/Article/details/gt2trkyejhy.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yvedp.cn/Article/details/gt2xrcnbtch.html

[Q31] 分组后过滤
来源：http://dali.chenjidiqi.icu/Article/details/gt2yngsxieh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhoulong.xyz/Article/details/gt2vkstoijz.html

[Q32] 分组拼接字符串
来源：http://dali.tianlin.xyz/Article/details/gt2jrpoxxok.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.feifeiyinyue.top/Article/details/gt2bwuwkuax.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zdqjudy.top/Article/details/gt2nhekuxdt.html

[Q33] 多列分组
来源：http://dali.cheryme.top/Article/details/gt2swffgdpj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.vqdsnc.cn/Article/details/gt2ionbkavm.html

[Q34] 每组取第一条
来源：http://dali.jinqigfzy.top/Article/details/gt2tcdqjpqz.html

SELECT * FROM (
来源：http://dali.ivvv.top/Article/details/gt2dxxpqajs.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.wangdashe.top/Article/details/gt2jtomwokd.html

) t WHERE rn = 1;
来源：http://dali.haohaochexian.top/Article/details/gt2kvlswfen.html

[Q35] 内连接
来源：http://dali.pengpengdd.cyou/Article/details/gt2gyzfzism.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuanzhike.top/Article/details/gt2thfkfuhj.html

[Q36] 左连接
来源：http://dali.xuanzx.com/Article/details/gt2qldntftj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhengqikj.top/Article/details/gt2gctxpyoo.html

[Q37] 右连接
来源：http://dali.dianchejie.cn/Article/details/gt2mtymweug.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.chenjidiqi.icu/Article/details/gt2qkjcbtyd.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.nwbrower.top/Article/details/gt2yvupblim.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.feifeiyinyue.top/Article/details/gt2gsrvbzvb.html

[Q39] 自连接（查上下级）
来源：http://dali.ehwqpu.com/Article/details/gt2mjrwsfuh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhengqikj.top/Article/details/gt2veliwlzh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.sweek.top/Article/details/gt2cztkcdtv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.snrcjt.cn/Article/details/gt2kkofziwc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ehwqpu.com/Article/details/gt2cqmowagd.html

[Q41] 多表连接
来源：http://dali.feifeiyinyue.top/Article/details/gt2sjzvawbl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jyoumei.cn/Article/details/gt2dibroind.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jqgfzy.top/Article/details/gt2ytosbbll.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shangyingyoupin.top/Article/details/gt2rwamrwgx.html

[Q42] 连接条件附加过滤
来源：http://dali.smart0.xyz/Article/details/gt2qsyhgnvp.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cucudq.cn/Article/details/gt2ycsjmuio.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yj20258.top/Article/details/gt2emmsztcg.html

[Q43] 标量子查询
来源：http://dali.zhongyouzk.top/Article/details/gt2ldchfzpo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.redwolf501.top/Article/details/gt2uzsehrth.html

[Q44] IN 子查询
来源：http://dali.yj202588.top/Article/details/gt2bwtkmmwr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhongyouzk.top/Article/details/gt2coyzrtwc.html

[Q45] EXISTS 判断存在
来源：http://dali.aibaodan.cn/Article/details/gt2tvpwokcj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.bjfxy.top/Article/details/gt2nbopcjnk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.daxiang520.top/Article/details/gt2keqhwdyd.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuetiantiany.cn/Article/details/gt2jqazevpe.html

[Q47] 与平均值比较
来源：http://dali.0kj1m.cn/Article/details/gt2bbhygqhh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.vqdsnc.cn/Article/details/gt2befvezuc.html

[Q48] CTE 公用表表达式
来源：http://dali.xuetiantiany.cn/Article/details/gt2pfcskwvj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jqgfzy.top/Article/details/gt2vhfcoppp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.nanxinkj.top/Article/details/gt2djwbmbgi.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2grjiqvli.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.bjfxy.top/Article/details/gt2cnruwszk.html

[Q50] 批量更新
来源：http://dali.redwolf501.top/Article/details/gt2xilmcoty.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.daxiang520.top/Article/details/gt2kjilltyu.html

[Q51] 用子查询更新
来源：http://dali.yuanzhike.top/Article/details/gt2ffovshua.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hnqzz.top/Article/details/gt2eyqapgrj.html

[Q52] 删除指定行
来源：http://dali.redwolf501.top/Article/details/gt2iibmcqqd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.guowangkeji.top/Article/details/gt2vpmtxjqd.html

[Q53] 按条件删除
来源：http://dali.smart0.xyz/Article/details/gt2rhnyvhne.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.wangshuangyany.cn/Article/details/gt2xnpxonwr.html

[Q54] 清空表
来源：http://dali.xuetiantiany.cn/Article/details/gt2tmexfxan.html

TRUNCATE TABLE logs;
来源：http://dali.meibo888.top/Article/details/gt2rprpamod.html

[Q55] 排名（并列占位）
来源：http://dali.sweek.top/Article/details/gt2wxjuetdk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.vqdsnc.cn/Article/details/gt2efetuxcj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.iojbl.cn/Article/details/gt2nndugwlx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.nanxuanxn.top/Article/details/gt2hvzcqwkb.html

[Q57] 行号
来源：http://dali.pycfn.com/Article/details/gt2zuoeqkek.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2kuzjdbjz.html

[Q58] 累计求和
来源：http://dali.guowangkeji.top/Article/details/gt2fnvqcnbw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.fengsongda.top/Article/details/gt2xpppqiji.html

[Q59] 分组内累计
来源：http://dali.pengpengdd.cyou/Article/details/gt2vvyxldet.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gt2qkpmegsa.html

[Q60] 取上一行 / 下一行
来源：http://dali.ydzc1.top/Article/details/gt2sbwuxvbq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ydzc1.top/Article/details/gt2knwdifrb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gt2zbtqjffk.html

[Q61] 移动平均
来源：http://dali.chenjidiqi.icu/Article/details/gt2uxbjdyju.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.meibo888.top/Article/details/gt2tdazswjg.html

[Q62] 分组占比
来源：http://dali.havefunace.top/Article/details/gt2yfdhhlcj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hongshengwenyu.top/Article/details/gt2ikmezwok.html

[Q63] 开启事务
来源：http://dali.smart0.xyz/Article/details/gt2schwmrff.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.aizwys.cn/Article/details/gt2evxaxlpk.html

[Q64] 提交事务
来源：http://dali.xuanzx.com/Article/details/gt2dzipiwyq.html

COMMIT;
来源：http://dali.zdqjudy.top/Article/details/gt2mbsczpbq.html

[Q65] 回滚事务
来源：http://dali.birdmap.top/Article/details/gt2ddnnmlnv.html

ROLLBACK;
来源：http://dali.ybcxt.top/Article/details/gt2arempmtp.html

[Q66] 行锁查询
来源：http://dali.nanxuanxn.top/Article/details/gt2qudjbdmp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hongshengwenyu.top/Article/details/gt2towhvuqz.html

[Q67] 设置隔离级别
来源：http://dali.ivvv.top/Article/details/gt2utclwgkd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.feifeiyinyue.top/Article/details/gt2nkdubdov.html

[Q68] 保存点
来源：http://dali.gzhubu.top/Article/details/gt2fwbyzvhi.html

SAVEPOINT sp1;
来源：http://dali.yj202588.top/Article/details/gt2murhckih.html

ROLLBACK TO sp1;
来源：http://dali.gzhubu.top/Article/details/gt2bcmazgec.html

[Q69] 查看执行计划
来源：http://dali.yuxming.cn/Article/details/gt2ibmtmwnh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.sufxvd.cn/Article/details/gt2mgvliwvt.html

[Q70] 更新统计信息
来源：http://dali.0kj1m.cn/Article/details/gt2muascpvl.html

ANALYZE TABLE users;
来源：http://dali.shzxlz.cn/Article/details/gt2vrcpofaa.html

[Q71] 查看建表语句
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iqdlpguy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ivvv.top/Article/details/gt2rduiygbq.html

[Q72] 查看索引
来源：http://dali.smart0.xyz/Article/details/gt2rxdnvxte.html

SHOW INDEX FROM users;
来源：http://dali.yj202588.top/Article/details/gt2zawwexwj.html

[Q73] 查看表状态
来源：http://dali.ydzc1.top/Article/details/gt2bcumyfrl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gotoacloud.top/Article/details/gt2ggpoleze.html

[Q74] 强制使用索引
来源：http://dali.sweek.top/Article/details/gt2cwdikcng.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhoulong.xyz/Article/details/gt2bfgslqlv.html

[Q75] 日期格式化
来源：http://dali.316326.xyz/Article/details/gt2idgzpiyg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cheryme.top/Article/details/gt2furvrcex.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sxryk.cn/Article/details/gt2vyqmvukq.html

[Q76] 按天统计
来源：http://dali.zhiwuduotai.top/Article/details/gt2mhpymlog.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cucudq.cn/Article/details/gt2jkdvxlph.html

[Q77] 时间加减
来源：http://dali.jyoumei.cn/Article/details/gt2brvivynl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sufxvd.cn/Article/details/gt2lckaunkh.html

[Q78] 当前时间
来源：http://dali.hnqzz.top/Article/details/gt2xjkyfjcy.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yj202588.top/Article/details/gt2sqvthsel.html

[Q79] 字符串拼接
来源：http://dali.guannengcc.top/Article/details/gt2gymapxth.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hywenlv.cn/Article/details/gt2gpqhlpqk.html

[Q80] 字符串截取
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ljqdoszi.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2ndjtbcrs.html

[Q81] 字符串替换
来源：http://dali.chenzaomai.com/Article/details/gt2eurpvpov.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2mjavxwob.html

[Q82] 字符长度与字节长度
来源：http://dali.yonumen.top/Article/details/gt2gwjxtwxo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2aodjamjq.html

[Q83] 大小写转换
来源：http://dali.pycfn.com/Article/details/gt2cquisseq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2mkrhzfsq.html

[Q84] 去除首尾空格
来源：http://dali.svipenyu.cn/Article/details/gt2fezsasys.html

SELECT TRIM(name) FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2qviezowd.html

[Q85] 数值取整
来源：http://dali.yj202588.top/Article/details/gt2gpjpcgdz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jiagoushi.top/Article/details/gt2ewviuoat.html

[Q86] 读取 JSON 字段
来源：http://dali.zhixingplan.top/Article/details/gt2rzhhpqsm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.haohaochexian.top/Article/details/gt2jjcfoxpe.html

[Q87] JSON 字段做条件
来源：http://dali.ppjwa.cn/Article/details/gt2fubcyfkm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xuanzx.com/Article/details/gt2xsvdhokb.html

[Q88] 行转列（条件聚合）
来源：http://dali.yj202588.top/Article/details/gt2jxthxcza.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jqgufenzy.top/Article/details/gt2nkppbsde.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2wdjqmvhl.html

[Q89] 判断表是否存在
来源：http://dali.zhiwuduotai.top/Article/details/gt2pzjogbcg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.redwolf501.top/Article/details/gt2viktciah.html

[Q90] 生成序号列
来源：http://dali.wangshuangyany.cn/Article/details/gt2gxlxzrmq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.316326.xyz/Article/details/gt2horarztq.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2kfmixtus.html

R. Bash 专题
来源：http://dali.guannengcc.top/Article/details/gt2nrjgbccm.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2wayaubdz.html

[R01] shebang 与严格模式
来源：http://dali.ivvv.top/Article/details/gt2gnnuqqlc.html

#!/usr/bin/env bash
来源：http://dali.cucudq.cn/Article/details/gt2naxseqrp.html

set -euo pipefail
来源：http://dali.shzxlz.cn/Article/details/gt2noimeyor.html

[R02] 变量赋值与使用
来源：http://dali.snrcjt.cn/Article/details/gt2hnvxbfoc.html

name="Tom"; echo "$name"
来源：http://dali.jqgfzy.top/Article/details/gt2sykmhxrx.html

[R03] 只读变量
来源：http://dali.zhengqikj.top/Article/details/gt2apneuihj.html

readonly PI=3.14
来源：http://dali.hammf.cn/Article/details/gt2crwqvjht.html

[R04] 位置参数
来源：http://dali.fengsongda.top/Article/details/gt2sgxzedna.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.fengsongda.top/Article/details/gt2qyxsgvsp.html

[R05] 参数默认值
来源：http://dali.xylfe.cn/Article/details/gt2nzdapsvq.html

name="${1:-default}"
来源：http://dali.hfpthk.cn/Article/details/gt2iyjplbfl.html

[R06] 判断命令是否存在
来源：http://dali.snrcjt.cn/Article/details/gt2xfffioyo.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.0kj1m.cn/Article/details/gt2ajgoifrc.html

[R07] if 判断文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2awylkpbx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sysykeji.top/Article/details/gt2pytnkiwc.html

[R08] 数值比较
来源：http://dali.gzhubu.top/Article/details/gt2dbsxqlis.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yuanzhike.top/Article/details/gt2wvxsmbpq.html

[R09] 字符串比较
来源：http://dali.yonumen.top/Article/details/gt2gddqofwd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhiwuduotai.top/Article/details/gt2uzokjkvv.html

[R10] 正则匹配
来源：http://dali.yvedp.cn/Article/details/gt2gmhfoxnt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.kuanghao11.cn/Article/details/gt2xggyezwq.html

[R11] case 多分支
来源：http://dali.xziqi.cn/Article/details/gt2ecjtzncj.html

case "$1" in
来源：http://dali.smart0.xyz/Article/details/gt2pgemahje.html

start) echo "启动" ;;
来源：http://dali.birdmap.top/Article/details/gt2qurqxqqw.html

stop)  echo "停止" ;;
来源：http://dali.redwolf501.top/Article/details/gt2wuizjwdp.html

*)     echo "未知命令" ;;
来源：http://dali.yonumen.top/Article/details/gt2kakxhkwy.html

esac
来源：http://dali.jyoumei.cn/Article/details/gt2baiwgifu.html

[R12] for 遍历文件
来源：http://dali.yvedp.cn/Article/details/gt2hiuehpol.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jianghu66.top/Article/details/gt2ifsyokxf.html

[R13] for 计数循环
来源：http://dali.gotoacloud.top/Article/details/gt2fzdabkym.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.daxiang520.top/Article/details/gt2iepnogqk.html

[R14] C 风格 for
来源：http://dali.hysaishi.cn/Article/details/gt2snvzhxlh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cucudq.cn/Article/details/gt2wndrnkii.html

[R15] while 逐行读文件
来源：http://dali.guannengcc.top/Article/details/gt2sbntrhkw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jqgufenzy.top/Article/details/gt2ehxwlymf.html

[R16] until 等待条件
来源：http://dali.xziqi.cn/Article/details/gt2espqbhsi.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wiebakuy.html

[R17] 数组定义与取值
来源：http://dali.andypj.xyz/Article/details/gt2rdpoklcy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.chenlongwang.top/Article/details/gt2oaeacuyl.html

[R18] 遍历数组
来源：http://dali.jiagoushi.top/Article/details/gt2wvusqpwi.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.316326.xyz/Article/details/gt2mbmszhbk.html

[R19] 数组长度
来源：http://dali.hongshengwenyu.top/Article/details/gt2uhfmdjaz.html

echo "${#arr[@]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qmspyuxo.html

[R20] 关联数组（字典）
来源：http://dali.zhixingplan.top/Article/details/gt2wgqbknua.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jqgufenzy.top/Article/details/gt2mcxyerin.html

[R21] 字符串长度
来源：http://dali.cdnleiting.top/Article/details/gt2prjdzlba.html

echo "${#s}"
来源：http://dali.yvedp.cn/Article/details/gt2sitmwnsx.html

[R22] 截取子串
来源：http://dali.jqgfzy.top/Article/details/gt2kqqysgtu.html

echo "${s:0:5}"
来源：http://dali.zhengqikj.top/Article/details/gt2kurcskjs.html

[R23] 字符串替换
来源：http://dali.xylfe.cn/Article/details/gt2ffxcfvsr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cheryme.top/Article/details/gt2seoybkpc.html

[R24] 大小写转换
来源：http://dali.nwbrower.top/Article/details/gt2okdpqxwy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ybcxt.top/Article/details/gt2jziyrqgv.html

[R25] 去后缀 / 去前缀
来源：http://dali.birdmap.top/Article/details/gt2cnfaymdq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.gotoacloud.top/Article/details/gt2ivwjybbx.html

[R26] 命令替换
来源：http://dali.cucudq.cn/Article/details/gt2hjjwqhmy.html

now=$(date +%F); echo "$now"
来源：http://dali.gaohongyu789.top/Article/details/gt2cgoiaplh.html

[R27] 算术展开
来源：http://dali.yangfankeji.com/Article/details/gt2zrawqiyr.html

echo $((1 + 2 * 3))
来源：http://dali.jqgufenzy.top/Article/details/gt2sizqqvxh.html

[R28] 浮点运算
来源：http://dali.andypj.xyz/Article/details/gt2ebehoxvw.html

echo "scale=2; 10/3" | bc
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ukrtkxod.html

[R29] 定义函数
来源：http://dali.tanke756.top/Article/details/gt2fmystygz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zdqjudy.top/Article/details/gt2lvcrqraj.html

[R30] 函数返回状态码
来源：http://dali.tian-w.cn/Article/details/gt2zzscxesy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ybcxt.top/Article/details/gt2hojvstrt.html

[R31] 局部变量
来源：http://dali.hywenlv.cn/Article/details/gt2psthpszf.html

f() { local x=1; echo "$x"; }
来源：http://dali.bjfxy.top/Article/details/gt2swocpnyg.html

[R32] 参数个数校验
来源：http://dali.hfpthk.cn/Article/details/gt2bvtjypff.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.tian-w.cn/Article/details/gt2vzaafhir.html

[R33] 捕获错误并提示行号
来源：http://dali.hnqzz.top/Article/details/gt2sufydffm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xuetiantiany.cn/Article/details/gt2fcqgafyu.html

[R34] 退出时清理
来源：http://dali.daria6918.cn/Article/details/gt2uqbspmci.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.gaohongyu789.top/Article/details/gt2lelearld.html

[R35] 后台执行并等待
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bslurwdl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xinyue.icu/Article/details/gt2vnbfsmie.html

[R36] 并发执行多个任务
来源：http://dali.jqgfzy.top/Article/details/gt2qkivranf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yj20258.top/Article/details/gt2rxxkrpda.html

[R37] 把输出赋给变量
来源：http://dali.chenzaomai.com/Article/details/gt2paatnuui.html

files=$(ls -1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2yjnzlkac.html

[R38] 管道串联
来源：http://dali.guannengcc.top/Article/details/gt2ydzxdntz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vejhdfrf.html

[R39] 重定向标准输出与错误
来源：http://dali.zhiwuduotai.top/Article/details/gt2htrstjof.html

cmd > out.log 2>&1
来源：http://dali.yj20258.top/Article/details/gt2qovmgwvh.html

[R40] 追加写日志
来源：http://dali.daria6918.cn/Article/details/gt2rakqgnoq.html

echo "log" >> out.log
来源：http://dali.jiagoushi.top/Article/details/gt2pbgaeulq.html

[R41] 丢弃输出
来源：http://dali.yuxming.cn/Article/details/gt2fcmuzhvy.html

cmd >/dev/null 2>&1
来源：http://dali.gzhubu.top/Article/details/gt2hizbunmm.html

[R42] 输入重定向
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gqoikzdd.html

wc -l < a.txt
来源：http://dali.cqqwz.cn/Article/details/gt2pimhvnii.html

[R43] 按名字查找文件
来源：http://dali.jiagoushi.top/Article/details/gt2vuoktfao.html

find . -name "*.log" -type f
来源：http://dali.aibaodan.cn/Article/details/gt2pbpndhuv.html

[R44] 按修改时间查找
来源：http://dali.c1oappe.top/Article/details/gt2reumeukr.html

find . -mtime -7 -type f
来源：http://dali.gzhubu.top/Article/details/gt2irypyjkw.html

[R45] 批量删除
来源：http://dali.chenzaomai.com/Article/details/gt2vmioqxqb.html

find . -name "*.tmp" -delete
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2frszlqyf.html

[R46] 递归替换文件内容
来源：http://dali.nwbrower.top/Article/details/gt2wlvmcxqw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.chenjidiqi.icu/Article/details/gt2akpvubdl.html

[R47] sed 单行替换
来源：http://dali.jiagoushi.top/Article/details/gt2vfjfjlgp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hysaishi.cn/Article/details/gt2cysfatpu.html

[R48] awk 取指定列
来源：http://dali.hongshengwenyu.top/Article/details/gt2tuubmhri.html

awk '{print $1, $3}' a.txt
来源：http://dali.xinyue.icu/Article/details/gt2lnfathjf.html

[R49] awk 带条件
来源：http://dali.iojbl.cn/Article/details/gt2xwniqddw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xuanzx.com/Article/details/gt2dctfwdah.html

[R50] awk 求和
来源：http://dali.zdqjudy.top/Article/details/gt2mzgazxks.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gt2qeyoxppn.html

[R51] 排序去重取前几
来源：http://dali.guannengcc.top/Article/details/gt2hoicnklb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.nanxinkj.top/Article/details/gt2xqlmmncn.html

[R52] 统计行数
来源：http://dali.jyoumei.cn/Article/details/gt2ojvpakaw.html

wc -l a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vdyktwkv.html

[R53] 查看文件头与实时尾
来源：http://dali.pycfn.com/Article/details/gt2rinuraup.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jyoumei.cn/Article/details/gt2uwwoygcg.html

[R54] 比较两个文件
来源：http://dali.0kj1m.cn/Article/details/gt2agtfrmzr.html

diff a.txt b.txt
来源：http://dali.sufxvd.cn/Article/details/gt2mwjnkyvc.html

[R55] 压缩与解压
来源：http://dali.daria6918.cn/Article/details/gt2weznenco.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.tian-w.cn/Article/details/gt2ahfxujez.html

[R56] 远程拷贝
来源：http://dali.316326.xyz/Article/details/gt2dlozxxew.html

scp file user@host:/path/
来源：http://dali.cdnleiting.top/Article/details/gt2hjtbthyy.html

[R57] 远程执行命令
来源：http://dali.yj20258.top/Article/details/gt2trixavnn.html

ssh user@host 'uptime'
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2icdfoucd.html

[R58] 下载文件
来源：http://dali.sufxvd.cn/Article/details/gt2pomxedql.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sysykeji.top/Article/details/gt2kcihxyuo.html

[R59] 发 POST JSON
来源：http://dali.feifeiyinyue.top/Article/details/gt2yckjhiel.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yueranfly.top/Article/details/gt2hsgiksdy.html

[R60] 只看 HTTP 状态码
来源：http://dali.aizwys.cn/Article/details/gt2acvovyvb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sxryk.cn/Article/details/gt2pkfnecfh.html

[R61] 磁盘占用
来源：http://dali.9152youxi.cn/Article/details/gt2jskhjvxy.html

df -h;  du -sh *
来源：http://dali.smart0.xyz/Article/details/gt2cokpgcys.html

[R62] 找最占空间的文件
来源：http://dali.hnqzz.top/Article/details/gt2dntebwym.html

du -ah . | sort -rh | head -10
来源：http://dali.dianchejie.cn/Article/details/gt2wejmfnlu.html

[R63] 内存与进程
来源：http://dali.bjfxy.top/Article/details/gt2wqytbkyg.html

free -h;  ps aux | grep nginx
来源：http://dali.cucudq.cn/Article/details/gt2cfiaxwzn.html

[R64] 结束进程
来源：http://dali.yj202588.top/Article/details/gt2kdsynkmi.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yj20258888.top/Article/details/gt2ghyhgtvk.html

[R65] 查看端口占用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pflbolew.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.wangshuangyany.cn/Article/details/gt2mzihxygw.html

[R66] 定时任务
来源：http://dali.aizwys.cn/Article/details/gt2ksqhcnqo.html

crontab -e;  crontab -l
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ngmhanfa.html

[R67] 生成随机十六进制串
来源：http://dali.ydzc1.top/Article/details/gt2lmxnvbuv.html

openssl rand -hex 16
来源：http://dali.yj20258.top/Article/details/gt2hgqicoum.html

[R68] 计算文件校验值
来源：http://dali.shangyingyoupin.top/Article/details/gt2gblphxwe.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.fzhhl.top/Article/details/gt2ololuhvl.html

[R69] 生成随机密码
来源：http://dali.tian-w.cn/Article/details/gt2mcsctteg.html

head -c 16 /dev/urandom | base64
来源：http://dali.gotoacloud.top/Article/details/gt2nhqjzyjo.html

[R70] 时间戳与互转
来源：http://dali.hongshengwenyu.top/Article/details/gt2rfknxfrb.html

date +%s;  date -d @1700000000
来源：http://dali.fengsongda.top/Article/details/gt2etepjtxi.html

[R71] 日期格式化
来源：http://dali.yongpay.top/Article/details/gt2kksmgijr.html


<!-- 参考信息 -->