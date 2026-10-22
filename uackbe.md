代发 wailian999

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xylfe.cn/Article/details/gt2efgxphre.html

[Q22] 排序
来源：http://dali.yj202588.top/Article/details/gt2hoeiskzh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yueranfly.top/Article/details/gt2osoupnhf.html

[Q23] 分页
来源：http://dali.yuxming.cn/Article/details/gt2wyvaizax.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.smart0.xyz/Article/details/gt2ticfiucy.html

[Q24] 去重
来源：http://dali.0kj1m.cn/Article/details/gt2dnlozbcn.html

SELECT DISTINCT city FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2pernnjtu.html

[Q25] 只取前 N 条
来源：http://dali.yj20258888.top/Article/details/gt2fzxtaivq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.wangdashe.top/Article/details/gt2tsadnwbt.html

[Q26] 计数
来源：http://dali.cashguo.top/Article/details/gt2vkxnzygs.html

SELECT COUNT(*) FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2ayvxcced.html

[Q27] 条件计数
来源：http://dali.shangyingyoupin.top/Article/details/gt2uefvemcs.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jzbzqugp.html

[Q28] 求和与平均
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zkdztvoh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yongpay.top/Article/details/gt2iyqivnld.html

[Q29] 最大最小值
来源：http://dali.fzhhl.top/Article/details/gt2quhfqigd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2mtfielpn.html

[Q30] 分组统计
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ompdsjej.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shuidangran.top/Article/details/gt2qjouzhnx.html

[Q31] 分组后过滤
来源：http://dali.daxiang520.top/Article/details/gt2anfkjsxb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xinyue.icu/Article/details/gt2uygkxucw.html

[Q32] 分组拼接字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zukbqszq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.smart0.xyz/Article/details/gt2qumlamzl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.birdmap.top/Article/details/gt2kjfojfsr.html

[Q33] 多列分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qkzbkyyj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.vqdsnc.cn/Article/details/gt2thxcznco.html

[Q34] 每组取第一条
来源：http://dali.yanxiufei.cn/Article/details/gt2afjhkhag.html

SELECT * FROM (
来源：http://dali.gzhubu.top/Article/details/gt2zyzefynx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.snrcjt.cn/Article/details/gt2yjxpyzwm.html

) t WHERE rn = 1;
来源：http://dali.yuanzhike.top/Article/details/gt2dmupvdsp.html

[Q35] 内连接
来源：http://dali.316326.xyz/Article/details/gt2glnghxko.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.bjfxy.top/Article/details/gt2jffpwlym.html

[Q36] 左连接
来源：http://dali.wangshuangyany.cn/Article/details/gt2venoabah.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ydzc1.top/Article/details/gt2wmbaoxuw.html

[Q37] 右连接
来源：http://dali.jinqigfzy.top/Article/details/gt2jnpvpxla.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.andypj.xyz/Article/details/gt2tyhtqtji.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xuanzx.com/Article/details/gt2ptpsblho.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ybcxt.top/Article/details/gt2sockqhqz.html

[Q39] 自连接（查上下级）
来源：http://dali.sweek.top/Article/details/gt2vngaxaxf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jyoumei.cn/Article/details/gt2wezxztok.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qqdzpvkn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vihsnirr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xziqi.cn/Article/details/gt2cnymxcme.html

[Q41] 多表连接
来源：http://dali.ydzc1.top/Article/details/gt2chghiooo.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.bjfxy.top/Article/details/gt2sarkiqce.html

JOIN users u ON u.id = o.user_id
来源：http://dali.tianlin.xyz/Article/details/gt2jcqghvzv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yongpay.top/Article/details/gt2cwpiqoad.html

[Q42] 连接条件附加过滤
来源：http://dali.pengpengdd.cyou/Article/details/gt2tkccscea.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xuetiantiany.cn/Article/details/gt2vivmqasb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jianghu66.top/Article/details/gt2ovnhpylz.html

[Q43] 标量子查询
来源：http://dali.daxiang520.top/Article/details/gt2elkscrnk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yueranfly.top/Article/details/gt2cpmlbatg.html

[Q44] IN 子查询
来源：http://dali.guowangkeji.top/Article/details/gt2qnxqhnse.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jiagoushi.top/Article/details/gt2nxylpvol.html

[Q45] EXISTS 判断存在
来源：http://dali.mhx1999.top/Article/details/gt2kxynspcm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhixingplan.top/Article/details/gt2qxffmelh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.vqdsnc.cn/Article/details/gt2bozevgqy.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.dashuyun.cn/Article/details/gt2ptogfnkd.html

[Q47] 与平均值比较
来源：http://dali.havefunace.top/Article/details/gt2kbyfumfb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.feifeiyinyue.top/Article/details/gt2anifqsel.html

[Q48] CTE 公用表表达式
来源：http://dali.chenjidiqi.icu/Article/details/gt2cwcntanp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.0kj1m.cn/Article/details/gt2dikumhwl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.daria6918.cn/Article/details/gt2jeduzzwg.html

[Q49] 更新单行
来源：http://dali.redwolf501.top/Article/details/gt2rporikax.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ppjwa.cn/Article/details/gt2zriwroeq.html

[Q50] 批量更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2afhblnpz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jyoumei.cn/Article/details/gt2uzhosvkt.html

[Q51] 用子查询更新
来源：http://dali.pycfn.com/Article/details/gt2mqzrqlku.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinqigfzy.top/Article/details/gt2rxqkmbji.html

[Q52] 删除指定行
来源：http://dali.gotoacloud.top/Article/details/gt2xfzhcwwf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hammf.cn/Article/details/gt2jecpmyds.html

[Q53] 按条件删除
来源：http://dali.yuanzhike.top/Article/details/gt2szemvpyr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yj20258888.top/Article/details/gt2gwyjiwed.html

[Q54] 清空表
来源：http://dali.yj20258.top/Article/details/gt2xkfnymur.html

TRUNCATE TABLE logs;
来源：http://dali.gogol.net.cn/Article/details/gt2seaqtfoz.html

[Q55] 排名（并列占位）
来源：http://dali.chenjidiqi.icu/Article/details/gt2rslehlsf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.chenjidiqi.icu/Article/details/gt2xumujqbm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.chenjidiqi.icu/Article/details/gt2zbrgabms.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xuetiantiany.cn/Article/details/gt2lsvmfllx.html

[Q57] 行号
来源：http://dali.svipenyu.cn/Article/details/gt2psbbwrex.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2ddedwsvv.html

[Q58] 累计求和
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pviqifhh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yongpay.top/Article/details/gt2qhyofwuk.html

[Q59] 分组内累计
来源：http://dali.dashuyun.cn/Article/details/gt2fkbcwbpv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xylfe.cn/Article/details/gt2jjkbfzgh.html

[Q60] 取上一行 / 下一行
来源：http://dali.gaohongyu789.top/Article/details/gt2lotyvpjq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ozkrcxax.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sxryk.cn/Article/details/gt2pwmvihvm.html

[Q61] 移动平均
来源：http://dali.aizwys.cn/Article/details/gt2pxayddxl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xylfe.cn/Article/details/gt2pxtidosn.html

[Q62] 分组占比
来源：http://dali.ehwqpu.com/Article/details/gt2uuzbrerf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.sxryk.cn/Article/details/gt2pjiltwrv.html

[Q63] 开启事务
来源：http://dali.xinyue.icu/Article/details/gt2wzpoviug.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.chenzaomai.com/Article/details/gt2ttjerjod.html

[Q64] 提交事务
来源：http://dali.hnxiangtu.top/Article/details/gt2kbqjfnll.html

COMMIT;
来源：http://dali.9152youxi.cn/Article/details/gt2tnfxuthc.html

[Q65] 回滚事务
来源：http://dali.mhx1999.top/Article/details/gt2liprinlp.html

ROLLBACK;
来源：http://dali.yj20258.top/Article/details/gt2bdjdpbax.html

[Q66] 行锁查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uftwlnvq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cqqwz.cn/Article/details/gt2wgaeeyjq.html

[Q67] 设置隔离级别
来源：http://dali.daxiang520.top/Article/details/gt2zdlyzskr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yuxming.cn/Article/details/gt2expjezyz.html

[Q68] 保存点
来源：http://dali.zhongyouzk.top/Article/details/gt2vqbxojuo.html

SAVEPOINT sp1;
来源：http://dali.ivvv.top/Article/details/gt2oopkfgqi.html

ROLLBACK TO sp1;
来源：http://dali.tianlin.xyz/Article/details/gt2kddpkgrk.html

[Q69] 查看执行计划
来源：http://dali.zhoulong.xyz/Article/details/gt2joebqdmz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinqigfzy.top/Article/details/gt2scoroyds.html

[Q70] 更新统计信息
来源：http://dali.9152youxi.cn/Article/details/gt2ytjyncuw.html

ANALYZE TABLE users;
来源：http://dali.wangdashe.top/Article/details/gt2qkkzjqwh.html

[Q71] 查看建表语句
来源：http://dali.hnxiangtu.top/Article/details/gt2wedcxasw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jiagoushi.top/Article/details/gt2tekmbkcs.html

[Q72] 查看索引
来源：http://dali.chenlongwang.top/Article/details/gt2xiynjuge.html

SHOW INDEX FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2lzpiaytm.html

[Q73] 查看表状态
来源：http://dali.cdnleiting.top/Article/details/gt2aooxucmu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.snrcjt.cn/Article/details/gt2bqrqbzqu.html

[Q74] 强制使用索引
来源：http://dali.xuetiantiany.cn/Article/details/gt2lelntivv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ppjwa.cn/Article/details/gt2xdgnbird.html

[Q75] 日期格式化
来源：http://dali.yj20258888.top/Article/details/gt2bpwxizjx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xylfe.cn/Article/details/gt2gmfqgkfg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.chenlongwang.top/Article/details/gt2mndmffjs.html

[Q76] 按天统计
来源：http://dali.cqqwz.cn/Article/details/gt2koqbenil.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xzthcfck.html

[Q77] 时间加减
来源：http://dali.zdqjudy.top/Article/details/gt2ealardpt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.316326.xyz/Article/details/gt2rayurkur.html

[Q78] 当前时间
来源：http://dali.havefunace.top/Article/details/gt2zopaferi.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xuanzx.com/Article/details/gt2djvknafp.html

[Q79] 字符串拼接
来源：http://dali.pycfn.com/Article/details/gt2gynrnssw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhiwuduotai.top/Article/details/gt2gcjkwpfz.html

[Q80] 字符串截取
来源：http://dali.cucudq.cn/Article/details/gt2qxhdmlem.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2giypkzwf.html

[Q81] 字符串替换
来源：http://dali.yj202588.top/Article/details/gt2qdsujtzi.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjqdhau.html

[Q82] 字符长度与字节长度
来源：http://dali.ivvv.top/Article/details/gt2lhppdirw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2alqohucb.html

[Q83] 大小写转换
来源：http://dali.chenlongwang.top/Article/details/gt2iamzxsfs.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2aqdsyduu.html

[Q84] 去除首尾空格
来源：http://dali.ydzc1.top/Article/details/gt2kclkltuw.html

SELECT TRIM(name) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2coisvcap.html

[Q85] 数值取整
来源：http://dali.shangyingyoupin.top/Article/details/gt2ixwjjuxt.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gogol.net.cn/Article/details/gt2lupmtqdb.html

[Q86] 读取 JSON 字段
来源：http://dali.xuetiantiany.cn/Article/details/gt2tvwqmvwr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hywenlv.cn/Article/details/gt2qqhfigkx.html

[Q87] JSON 字段做条件
来源：http://dali.yuanzhike.top/Article/details/gt2bjvfrkgk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.nanxuanxn.top/Article/details/gt2hrxxspcy.html

[Q88] 行转列（条件聚合）
来源：http://dali.yj202588.top/Article/details/gt2sesukicj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.wangdashe.top/Article/details/gt2irwnuuft.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2kiqejnwz.html

[Q89] 判断表是否存在
来源：http://dali.316326.xyz/Article/details/gt2tpcsumul.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.tanke756.top/Article/details/gt2jgtqomuz.html

[Q90] 生成序号列
来源：http://dali.fengsongda.top/Article/details/gt2hrhbvact.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jiagoushi.top/Article/details/gt2cbukjobf.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2dcyiplra.html

R. Bash 专题
来源：http://dali.birdmap.top/Article/details/gt2iyvcagyl.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2oaqcetpv.html

[R01] shebang 与严格模式
来源：http://dali.yongpay.top/Article/details/gt2pahdhtbe.html

#!/usr/bin/env bash
来源：http://dali.fzhhl.top/Article/details/gt2vtsdcivd.html

set -euo pipefail
来源：http://dali.mhx1999.top/Article/details/gt2pcihgyza.html

[R02] 变量赋值与使用
来源：http://dali.shanyushiyangtech.top/Article/details/gt2euxlxbkv.html

name="Tom"; echo "$name"
来源：http://dali.wangshuangyany.cn/Article/details/gt2yxctwvbo.html

[R03] 只读变量
来源：http://dali.zhoulong.xyz/Article/details/gt2wgcqrruj.html

readonly PI=3.14
来源：http://dali.cashguo.top/Article/details/gt2vcvnrvyq.html

[R04] 位置参数
来源：http://dali.sxryk.cn/Article/details/gt2xkhqxeyo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nvmoxxsl.html

[R05] 参数默认值
来源：http://dali.jyoumei.cn/Article/details/gt2ontduder.html

name="${1:-default}"
来源：http://dali.chenlongwang.top/Article/details/gt2motqwpfx.html

[R06] 判断命令是否存在
来源：http://dali.hfpthk.cn/Article/details/gt2asizwuqt.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gogol.net.cn/Article/details/gt2cgxitmeh.html

[R07] if 判断文件
来源：http://dali.fengsongda.top/Article/details/gt2qvzuuuyo.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yj202588.top/Article/details/gt2yfnejwie.html

[R08] 数值比较
来源：http://dali.dianchejie.cn/Article/details/gt2wpylkeet.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.vqdsnc.cn/Article/details/gt2iuvmoqbq.html

[R09] 字符串比较
来源：http://dali.snrcjt.cn/Article/details/gt2rgyhinmo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.nanxinkj.top/Article/details/gt2dijxrtre.html

[R10] 正则匹配
来源：http://dali.sysykeji.top/Article/details/gt2iyolmkiz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.guannengcc.top/Article/details/gt2svqckofk.html

[R11] case 多分支
来源：http://dali.aizwys.cn/Article/details/gt2njlriryp.html

case "$1" in
来源：http://dali.haohaochexian.top/Article/details/gt2acassawr.html

start) echo "启动" ;;
来源：http://dali.quarkkingdee.top/Article/details/gt2gmuikiwu.html

stop)  echo "停止" ;;
来源：http://dali.gogol.net.cn/Article/details/gt2rtixfeul.html

*)     echo "未知命令" ;;
来源：http://dali.ivvv.top/Article/details/gt2ozglobtb.html

esac
来源：http://dali.cdnleiting.top/Article/details/gt2tngptaph.html

[R12] for 遍历文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2pncdcepn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.pycfn.com/Article/details/gt2rrqvofgy.html

[R13] for 计数循环
来源：http://dali.gogol.net.cn/Article/details/gt2kahlyvju.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.tanke756.top/Article/details/gt2yvrukzkz.html

[R14] C 风格 for
来源：http://dali.bjfxy.top/Article/details/gt2fbjkyuav.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.guowangkeji.top/Article/details/gt2ysbnnocf.html

[R15] while 逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gt2cwuwprdm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yj20258888.top/Article/details/gt2khccuygh.html

[R16] until 等待条件
来源：http://dali.cqqwz.cn/Article/details/gt2jeymxlgq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jyoumei.cn/Article/details/gt2gsffzopm.html

[R17] 数组定义与取值
来源：http://dali.ivvv.top/Article/details/gt2dhwgbhia.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.snrcjt.cn/Article/details/gt2tzaestqf.html

[R18] 遍历数组
来源：http://dali.jianghu66.top/Article/details/gt2qoobpvav.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cdnleiting.top/Article/details/gt2vpomdvum.html

[R19] 数组长度
来源：http://dali.yonumen.top/Article/details/gt2qlcmnhnj.html

echo "${#arr[@]}"
来源：http://dali.jiagoushi.top/Article/details/gt2ryakwohk.html

[R20] 关联数组（字典）
来源：http://dali.hammf.cn/Article/details/gt2cdzxjhdp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2outjfero.html

[R21] 字符串长度
来源：http://dali.pengpengdd.cyou/Article/details/gt2ezbleztl.html

echo "${#s}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tpqpqefi.html

[R22] 截取子串
来源：http://dali.zhengqikj.top/Article/details/gt2ajmdhdcn.html

echo "${s:0:5}"
来源：http://dali.hysaishi.cn/Article/details/gt2chmgzrcc.html

[R23] 字符串替换
来源：http://dali.svipenyu.cn/Article/details/gt2txdemfwc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shangyingyoupin.top/Article/details/gt2szhxrfac.html

[R24] 大小写转换
来源：http://dali.fengsongda.top/Article/details/gt2uortjgbu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ydzc1.top/Article/details/gt2utrxbfru.html

[R25] 去后缀 / 去前缀
来源：http://dali.dianchejie.cn/Article/details/gt2cghztayh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.nwbrower.top/Article/details/gt2orkyphne.html

[R26] 命令替换
来源：http://dali.vqdsnc.cn/Article/details/gt2kdkcfqyz.html

now=$(date +%F); echo "$now"
来源：http://dali.chenlongwang.top/Article/details/gt2rjbgzngf.html

[R27] 算术展开
来源：http://dali.sxryk.cn/Article/details/gt2wqlqpfgq.html

echo $((1 + 2 * 3))
来源：http://dali.nanxinkj.top/Article/details/gt2oilzulcl.html

[R28] 浮点运算
来源：http://dali.zycfv.cn/Article/details/gt2dacxxrmp.html

echo "scale=2; 10/3" | bc
来源：http://dali.ppjwa.cn/Article/details/gt2tsjrtonk.html

[R29] 定义函数
来源：http://dali.cdnleiting.top/Article/details/gt2ntaqfzev.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhoulong.xyz/Article/details/gt2yaqtronh.html

[R30] 函数返回状态码
来源：http://dali.zycfv.cn/Article/details/gt2dbrrbycb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.0kj1m.cn/Article/details/gt2pqzigkxt.html

[R31] 局部变量
来源：http://dali.yuxming.cn/Article/details/gt2estgupot.html

f() { local x=1; echo "$x"; }
来源：http://dali.havefunace.top/Article/details/gt2posbokau.html

[R32] 参数个数校验
来源：http://dali.xinyue.icu/Article/details/gt2xmiidokl.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.nwbrower.top/Article/details/gt2luylkfze.html

[R33] 捕获错误并提示行号
来源：http://dali.yuxming.cn/Article/details/gt2membeutb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hywenlv.cn/Article/details/gt2aqqdltss.html

[R34] 退出时清理
来源：http://dali.hongshengwenyu.top/Article/details/gt2mqslhyzn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.andypj.xyz/Article/details/gt2tsnvxgos.html

[R35] 后台执行并等待
来源：http://dali.gzhubu.top/Article/details/gt2aurubehw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yanxiufei.cn/Article/details/gt2sdelnobd.html

[R36] 并发执行多个任务
来源：http://dali.yangfankeji.com/Article/details/gt2qybdtaww.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zdqjudy.top/Article/details/gt2hvbfbdrb.html

[R37] 把输出赋给变量
来源：http://dali.daxiang520.top/Article/details/gt2wmlpblxs.html

files=$(ls -1)
来源：http://dali.aibaodan.cn/Article/details/gt2nouvvrfi.html

[R38] 管道串联
来源：http://dali.yonumen.top/Article/details/gt2kdomdbqj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.chenzaomai.com/Article/details/gt2exvytpjr.html

[R39] 重定向标准输出与错误
来源：http://dali.shuidangran.top/Article/details/gt2ozjpejly.html

cmd > out.log 2>&1
来源：http://dali.ehwqpu.com/Article/details/gt2ymrjliva.html

[R40] 追加写日志
来源：http://dali.pengpengdd.cyou/Article/details/gt2tkrtzhzf.html

echo "log" >> out.log
来源：http://dali.ybcxt.top/Article/details/gt2cwaoacvc.html

[R41] 丢弃输出
来源：http://dali.hfpthk.cn/Article/details/gt2amgqriml.html

cmd >/dev/null 2>&1
来源：http://dali.gzhubu.top/Article/details/gt2oscpyhzn.html

[R42] 输入重定向
来源：http://dali.birdmap.top/Article/details/gt2wvlttxwp.html

wc -l < a.txt
来源：http://dali.gogol.net.cn/Article/details/gt2ratqpegq.html

[R43] 按名字查找文件
来源：http://dali.gogol.net.cn/Article/details/gt2qnvjvmjf.html

find . -name "*.log" -type f
来源：http://dali.nwbrower.top/Article/details/gt2axdlfmeq.html

[R44] 按修改时间查找
来源：http://dali.daxiang520.top/Article/details/gt2quvzpodz.html

find . -mtime -7 -type f
来源：http://dali.yj20258888.top/Article/details/gt2xgreuzti.html

[R45] 批量删除
来源：http://dali.cucudq.cn/Article/details/gt2udaqficc.html

find . -name "*.tmp" -delete
来源：http://dali.pycfn.com/Article/details/gt2mzojqmub.html

[R46] 递归替换文件内容
来源：http://dali.yvedp.cn/Article/details/gt2qaizrbiz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hongshengwenyu.top/Article/details/gt2uaomltmt.html

[R47] sed 单行替换
来源：http://dali.dashuyun.cn/Article/details/gt2yuvitjvo.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.mhx1999.top/Article/details/gt2bbflsrfe.html

[R48] awk 取指定列
来源：http://dali.gaohongyu789.top/Article/details/gt2tpnxvcds.html

awk '{print $1, $3}' a.txt
来源：http://dali.ybcxt.top/Article/details/gt2nvgsunns.html

[R49] awk 带条件
来源：http://dali.cqqwz.cn/Article/details/gt2dxuydnyx.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.9152youxi.cn/Article/details/gt2heeyqsxs.html

[R50] awk 求和
来源：http://dali.yongpay.top/Article/details/gt2huicgvyk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.havefunace.top/Article/details/gt2zbyfmszh.html

[R51] 排序去重取前几
来源：http://dali.sysykeji.top/Article/details/gt2blvsdogx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.sufxvd.cn/Article/details/gt2bxnawbxz.html

[R52] 统计行数
来源：http://dali.jqgufenzy.top/Article/details/gt2pqofvlza.html

wc -l a.txt
来源：http://dali.iojbl.cn/Article/details/gt2uqdbpjpm.html

[R53] 查看文件头与实时尾
来源：http://dali.gotoacloud.top/Article/details/gt2cuiocgas.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.316326.xyz/Article/details/gt2fvjgwiqp.html

[R54] 比较两个文件
来源：http://dali.xylfe.cn/Article/details/gt2vdafinak.html

diff a.txt b.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hlyzsxmc.html

[R55] 压缩与解压
来源：http://dali.xuetiantiany.cn/Article/details/gt2brkkyebn.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.bjfxy.top/Article/details/gt2denkroqu.html

[R56] 远程拷贝
来源：http://dali.sweek.top/Article/details/gt2vxuotzsl.html

scp file user@host:/path/
来源：http://dali.haohaochexian.top/Article/details/gt2fxmmlkyd.html

[R57] 远程执行命令
来源：http://dali.cucudq.cn/Article/details/gt2xosxgkth.html

ssh user@host 'uptime'
来源：http://dali.jiagoushi.top/Article/details/gt2rkjkavom.html

[R58] 下载文件
来源：http://dali.zhixingplan.top/Article/details/gt2ytoypmwd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gzhubu.top/Article/details/gt2wvjrvybh.html

[R59] 发 POST JSON
来源：http://dali.chenjidiqi.icu/Article/details/gt2scaynyuu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xuetiantiany.cn/Article/details/gt2abyocrex.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhongyouzk.top/Article/details/gt2pylniqbg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.fengsongda.top/Article/details/gt2kcbylyfz.html

[R61] 磁盘占用
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sjyfgqtn.html

df -h;  du -sh *
来源：http://dali.xuetiantiany.cn/Article/details/gt2yywgrsot.html

[R62] 找最占空间的文件
来源：http://dali.sxryk.cn/Article/details/gt2uqichzgz.html

du -ah . | sort -rh | head -10
来源：http://dali.zhiwuduotai.top/Article/details/gt2pdeodmzi.html

[R63] 内存与进程
来源：http://dali.hammf.cn/Article/details/gt2siwqsent.html

free -h;  ps aux | grep nginx
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oesmgseb.html

[R64] 结束进程
来源：http://dali.quarkkingdee.top/Article/details/gt2zoplxcrm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jiagoushi.top/Article/details/gt2jconjpqx.html

[R65] 查看端口占用
来源：http://dali.quarkkingdee.top/Article/details/gt2lmaohhpw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ehwqpu.com/Article/details/gt2bvbflowg.html

[R66] 定时任务
来源：http://dali.tianlin.xyz/Article/details/gt2nrvoddhr.html

crontab -e;  crontab -l
来源：http://dali.9152youxi.cn/Article/details/gt2zvqcsxkk.html

[R67] 生成随机十六进制串
来源：http://dali.feifeiyinyue.top/Article/details/gt2vavvxcnj.html

openssl rand -hex 16
来源：http://dali.guowangkeji.top/Article/details/gt2hwppdcie.html

[R68] 计算文件校验值
来源：http://dali.ppjwa.cn/Article/details/gt2lrqebukf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.daxiang520.top/Article/details/gt2vdxrdndu.html

[R69] 生成随机密码
来源：http://dali.9152youxi.cn/Article/details/gt2ugpxysiw.html

head -c 16 /dev/urandom | base64
来源：http://dali.snrcjt.cn/Article/details/gt2wvoqqkpv.html

[R70] 时间戳与互转
来源：http://dali.bjfxy.top/Article/details/gt2vfymjurr.html

date +%s;  date -d @1700000000
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pxvwxpmn.html

[R71] 日期格式化
来源：http://dali.pycfn.com/Article/details/gt2xjarzoiq.html


<!-- 参考信息 -->