代发 wailian999

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hnqzz.top/Article/details/gtyyhwwbui.html

[Q26] 计数
来源：http://dali.yongpay.top/Article/details/gthtyruary.html

SELECT COUNT(*) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtrtfdejsl.html

[Q27] 条件计数
来源：http://dali.redwolf501.top/Article/details/gtbzatnmhx.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ydzc1.top/Article/details/gtjvrbyqlq.html

[Q28] 求和与平均
来源：http://dali.gzhubu.top/Article/details/gtlqtzskwh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.gzhubu.top/Article/details/gtbzfdgryc.html

[Q29] 最大最小值
来源：http://dali.shzxlz.cn/Article/details/gtawirhwkv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.pycfn.com/Article/details/gtelxxxpor.html

[Q30] 分组统计
来源：http://dali.guowangkeji.top/Article/details/gtuqqzlqba.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jyoumei.cn/Article/details/gtnjcljbwa.html

[Q31] 分组后过滤
来源：http://dali.bjfxy.top/Article/details/gtdsreypcz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.bjfxy.top/Article/details/gtgahkxlmi.html

[Q32] 分组拼接字符串
来源：http://dali.ybcxt.top/Article/details/gtxafbpuyu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.guowangkeji.top/Article/details/gtvlmagqpq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.chenzaomai.com/Article/details/gtowwjlolg.html

[Q33] 多列分组
来源：http://dali.shanyushiyangtech.top/Article/details/gtdglxwrmj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.tanke756.top/Article/details/gtytnxavib.html

[Q34] 每组取第一条
来源：http://dali.ydzc1.top/Article/details/gtngwpague.html

SELECT * FROM (
来源：http://dali.sysykeji.top/Article/details/gtmwvghpzi.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.dianchejie.cn/Article/details/gtworehtxm.html

) t WHERE rn = 1;
来源：http://dali.cheryme.top/Article/details/gtufpznfie.html

[Q35] 内连接
来源：http://dali.shanyushiyangtech.top/Article/details/gtfsjfpyop.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinqigufen.top/Article/details/gtpvmifkhb.html

[Q36] 左连接
来源：http://dali.gzhubu.top/Article/details/gtbnmzrfko.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gtppzbjksf.html

[Q37] 右连接
来源：http://dali.yvedp.cn/Article/details/gtuivtmrnt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gogol.net.cn/Article/details/gtjfgxjrvm.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shanyushiyangtech.top/Article/details/gtzihlcavk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpvgihupk.html

[Q39] 自连接（查上下级）
来源：http://dali.andypj.xyz/Article/details/gtdwuoughe.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jqgfzy.top/Article/details/gtdmmlquet.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.feifeiyinyue.top/Article/details/gthukxnlir.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.bjfxy.top/Article/details/gtohadxift.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvtatfnwe.html

[Q41] 多表连接
来源：http://dali.ehwqpu.com/Article/details/gtfcdithca.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yuxming.cn/Article/details/gtxhhqtzhr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ybcxt.top/Article/details/gtbmbmkesd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hammf.cn/Article/details/gtdsugtefh.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gtwyqvixtn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jinyuanbaomall.cn/Article/details/gtafncrasd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.fengsongda.top/Article/details/gtbpqfplkf.html

[Q43] 标量子查询
来源：http://dali.hysaishi.cn/Article/details/gtvuzdhmpf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.gogol.net.cn/Article/details/gtclivlogn.html

[Q44] IN 子查询
来源：http://dali.shuidangran.top/Article/details/gtzpjbkubr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xziqi.cn/Article/details/gtmrncagae.html

[Q45] EXISTS 判断存在
来源：http://dali.ivvv.top/Article/details/gtjwbpbzut.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.dashuyun.cn/Article/details/gtrxcitzco.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhoulong.xyz/Article/details/gthmyfqlut.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhengqikj.top/Article/details/gtvqrnueap.html

[Q47] 与平均值比较
来源：http://dali.haohaochexian.top/Article/details/gtxfwnntle.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinqigufen.top/Article/details/gtwmmzvonu.html

[Q48] CTE 公用表表达式
来源：http://dali.cdnleiting.top/Article/details/gtehbptaru.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.pycfn.com/Article/details/gtmiqxxxqn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shanyushiyangtech.top/Article/details/gteghneyvz.html

[Q49] 更新单行
来源：http://dali.zycfv.cn/Article/details/gthseinret.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.gzhubu.top/Article/details/gtwecyxytp.html

[Q50] 批量更新
来源：http://dali.zhengqikj.top/Article/details/gtbdvrdqex.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.daria6918.cn/Article/details/gtyhbmusku.html

[Q51] 用子查询更新
来源：http://dali.jianghu66.top/Article/details/gtqvrwubuy.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.havefunace.top/Article/details/gtbkehqypv.html

[Q52] 删除指定行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtljyycvwr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.pycfn.com/Article/details/gtrrjveoro.html

[Q53] 按条件删除
来源：http://dali.bjfxy.top/Article/details/gtwnbizflz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yongpay.top/Article/details/gtjjcmrqhb.html

[Q54] 清空表
来源：http://dali.vqdsnc.cn/Article/details/gtnjwsngec.html

TRUNCATE TABLE logs;
来源：http://dali.sweek.top/Article/details/gtpeufmxqc.html

[Q55] 排名（并列占位）
来源：http://dali.yanxiufei.cn/Article/details/gthvajwbyj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.bjfxy.top/Article/details/gtwfisnnxa.html

[Q56] 密集排名（并列不占位）
来源：http://dali.gotoacloud.top/Article/details/gtaxsycpus.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cheryme.top/Article/details/gtwbmauweb.html

[Q57] 行号
来源：http://dali.yonumen.top/Article/details/gtqatcjnjo.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xinyue.icu/Article/details/gtxgdbwznl.html

[Q58] 累计求和
来源：http://dali.yuanzhike.top/Article/details/gtuykvfjhq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtgrvyvujk.html

[Q59] 分组内累计
来源：http://dali.quarkkingdee.top/Article/details/gtpchaelgo.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gtjhieuwad.html

[Q60] 取上一行 / 下一行
来源：http://dali.guannengcc.top/Article/details/gtjulazxgr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shzxlz.cn/Article/details/gtftdaiacd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gtanmrletj.html

[Q61] 移动平均
来源：http://dali.svipenyu.cn/Article/details/gtxmburlpg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yj202588.top/Article/details/gtrsibmdnd.html

[Q62] 分组占比
来源：http://dali.zhongyouzk.top/Article/details/gthtqegjgo.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.iojbl.cn/Article/details/gtggqeiycu.html

[Q63] 开启事务
来源：http://dali.cucudq.cn/Article/details/gtojutifel.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.chenjidiqi.icu/Article/details/gtdnboqnfy.html

[Q64] 提交事务
来源：http://dali.cheryme.top/Article/details/gtyvwakwou.html

COMMIT;
来源：http://dali.kuanghao11.cn/Article/details/gtxvzhwtkh.html

[Q65] 回滚事务
来源：http://dali.gogol.net.cn/Article/details/gtodexzcfh.html

ROLLBACK;
来源：http://dali.shuidangran.top/Article/details/gttvejsgud.html

[Q66] 行锁查询
来源：http://dali.sysykeji.top/Article/details/gtcyvulozz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.vqdsnc.cn/Article/details/gtwgontnbx.html

[Q67] 设置隔离级别
来源：http://dali.zhoulong.xyz/Article/details/gtmufbgzjb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.tianlin.xyz/Article/details/gtjlyskfxy.html

[Q68] 保存点
来源：http://dali.pycfn.com/Article/details/gtmlzfhjyi.html

SAVEPOINT sp1;
来源：http://dali.xziqi.cn/Article/details/gtyjdekigh.html

ROLLBACK TO sp1;
来源：http://dali.cashguo.top/Article/details/gthxmyhkms.html

[Q69] 查看执行计划
来源：http://dali.yj20258888.top/Article/details/gthvnteyzu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ppjwa.cn/Article/details/gtdygddeou.html

[Q70] 更新统计信息
来源：http://dali.zhoulong.xyz/Article/details/gtbnckagap.html

ANALYZE TABLE users;
来源：http://dali.meibo888.top/Article/details/gteehbxata.html

[Q71] 查看建表语句
来源：http://dali.cucudq.cn/Article/details/gtqqwtnvwt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yuxming.cn/Article/details/gtlslyjjzk.html

[Q72] 查看索引
来源：http://dali.cdnleiting.top/Article/details/gtwhcaqrdo.html

SHOW INDEX FROM users;
来源：http://dali.yj20258.top/Article/details/gtapjjjlcs.html

[Q73] 查看表状态
来源：http://dali.yueranfly.top/Article/details/gtcasxmxic.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.tian-w.cn/Article/details/gtsezqkrlh.html

[Q74] 强制使用索引
来源：http://dali.haohaochexian.top/Article/details/gtqwdcapfw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.0kj1m.cn/Article/details/gtlygpdgkz.html

[Q75] 日期格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzjqzxllr.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shuidangran.top/Article/details/gtlxxbaetk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jlsjyb.cn/Article/details/gtfyawpdwo.html

[Q76] 按天统计
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgozextlf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.svipenyu.cn/Article/details/gtmwwmeqkf.html

[Q77] 时间加减
来源：http://dali.haohaochexian.top/Article/details/gttxehkrgt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ywan-chungtsiang.top/Article/details/gtabervyjp.html

[Q78] 当前时间
来源：http://dali.snrcjt.cn/Article/details/gtspzgoahx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shangyingyoupin.top/Article/details/gtcbyczhis.html

[Q79] 字符串拼接
来源：http://dali.shanyushiyangtech.top/Article/details/gtqqxrndtd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yongpay.top/Article/details/gtfzkprhjb.html

[Q80] 字符串截取
来源：http://dali.daria6918.cn/Article/details/gthkmhrdoz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtaqmhtree.html

[Q81] 字符串替换
来源：http://dali.gaohongyu789.top/Article/details/gtjhxaqnxa.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtfiikscnp.html

[Q82] 字符长度与字节长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzjokhbsb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtpeuepkoz.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gtjnnmtfvr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpgvcwxep.html

[Q84] 去除首尾空格
来源：http://dali.zdqjudy.top/Article/details/gtsylwisrn.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtwcuahmpx.html

[Q85] 数值取整
来源：http://dali.jinghuilouyu.cn/Article/details/gtminrdqum.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbtczocid.html

[Q86] 读取 JSON 字段
来源：http://dali.fzhhl.top/Article/details/gtqrjzzrvn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.kuanghao11.cn/Article/details/gtvudjucex.html

[Q87] JSON 字段做条件
来源：http://dali.fengsongda.top/Article/details/gtaaidfygg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.kuanghao11.cn/Article/details/gtfuvcttqr.html

[Q88] 行转列（条件聚合）
来源：http://dali.0kj1m.cn/Article/details/gthronhbnt.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.tianlin.xyz/Article/details/gtvovczucs.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtanjjnyfe.html

[Q89] 判断表是否存在
来源：http://dali.cheryme.top/Article/details/gtihfzmaql.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ydzc1.top/Article/details/gtufbkkgtn.html

[Q90] 生成序号列
来源：http://dali.9152youxi.cn/Article/details/gtwgbseehg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.fengsongda.top/Article/details/gtqecccpgu.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtphjyeskw.html

R. Bash 专题
来源：http://dali.shanyushiyangtech.top/Article/details/gtylpzfdfh.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtocefqngh.html

[R01] shebang 与严格模式
来源：http://dali.mhx1999.top/Article/details/gtrhlhlhud.html

#!/usr/bin/env bash
来源：http://dali.ybcxt.top/Article/details/gtcywddvmm.html

set -euo pipefail
来源：http://dali.yanxiufei.cn/Article/details/gtiexuizjn.html

[R02] 变量赋值与使用
来源：http://dali.feifeiyinyue.top/Article/details/gtrpieodbh.html

name="Tom"; echo "$name"
来源：http://dali.jqgfzy.top/Article/details/gtgkiieexp.html

[R03] 只读变量
来源：http://dali.chenjidiqi.icu/Article/details/gtoiqklisx.html

readonly PI=3.14
来源：http://dali.zhengqikj.top/Article/details/gtjkmgkeys.html

[R04] 位置参数
来源：http://dali.shzxlz.cn/Article/details/gtxamdbthp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yj20258888.top/Article/details/gtmcxybvgc.html

[R05] 参数默认值
来源：http://dali.0kj1m.cn/Article/details/gtushwvuqa.html

name="${1:-default}"
来源：http://dali.xuetiantiany.cn/Article/details/gtizhazaqd.html

[R06] 判断命令是否存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtshmyskor.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sufxvd.cn/Article/details/gtcqwmqgdg.html

[R07] if 判断文件
来源：http://dali.pengpengdd.cyou/Article/details/gtkrxohxue.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shuidangran.top/Article/details/gtkxhgxpni.html

[R08] 数值比较
来源：http://dali.bjfxy.top/Article/details/gtlkjmpnur.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shangyingyoupin.top/Article/details/gtduzeewks.html

[R09] 字符串比较
来源：http://dali.daria6918.cn/Article/details/gtitvhzpcx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yangfankeji.com/Article/details/gthqznmzzv.html

[R10] 正则匹配
来源：http://dali.shzxlz.cn/Article/details/gtrdmnkqvr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gtyuaslqaf.html

[R11] case 多分支
来源：http://dali.zhoulong.xyz/Article/details/gteamiwkus.html

case "$1" in
来源：http://dali.dashuyun.cn/Article/details/gtirrxfato.html

start) echo "启动" ;;
来源：http://dali.jinqigfzy.top/Article/details/gtqbatydhs.html

stop)  echo "停止" ;;
来源：http://dali.zdqjudy.top/Article/details/gtiacpndbe.html

*)     echo "未知命令" ;;
来源：http://dali.guannengcc.top/Article/details/gtxupwbcfi.html

esac
来源：http://dali.hammf.cn/Article/details/gtowvbbshc.html

[R12] for 遍历文件
来源：http://dali.xuetiantiany.cn/Article/details/gtfggbydyv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.birdmap.top/Article/details/gtubsvafsd.html

[R13] for 计数循环
来源：http://dali.0kj1m.cn/Article/details/gtgtkehhfw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hfpthk.cn/Article/details/gtddzusmxd.html

[R14] C 风格 for
来源：http://dali.feifeiyinyue.top/Article/details/gtkhnewmyv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.vqdsnc.cn/Article/details/gtmbmrddfg.html

[R15] while 逐行读文件
来源：http://dali.jinqigfzy.top/Article/details/gthgfymtuv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrdaztxse.html

[R16] until 等待条件
来源：http://dali.dianchejie.cn/Article/details/gtfijwhwvb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsbsqotsa.html

[R17] 数组定义与取值
来源：http://dali.guannengcc.top/Article/details/gtzswxrgbc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinqigufen.top/Article/details/gtalzwgjxw.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gtlrxuvezm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.birdmap.top/Article/details/gtvujhgwzz.html

[R19] 数组长度
来源：http://dali.chenzaomai.com/Article/details/gtzmytgrtd.html

echo "${#arr[@]}"
来源：http://dali.shangyingyoupin.top/Article/details/gtsipgckwr.html

[R20] 关联数组（字典）
来源：http://dali.xziqi.cn/Article/details/gttoqugggs.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhoulong.xyz/Article/details/gtncnwxite.html

[R21] 字符串长度
来源：http://dali.hysaishi.cn/Article/details/gtgtbygnkv.html

echo "${#s}"
来源：http://dali.yongpay.top/Article/details/gtwrjyihwm.html

[R22] 截取子串
来源：http://dali.redwolf501.top/Article/details/gtuqngmncq.html

echo "${s:0:5}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdmajubyi.html

[R23] 字符串替换
来源：http://dali.xuetiantiany.cn/Article/details/gtvjdnvwve.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.smart0.xyz/Article/details/gtrrqmpgyk.html

[R24] 大小写转换
来源：http://dali.yuxming.cn/Article/details/gtgrujgoti.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.aibaodan.cn/Article/details/gtmiwzjqdy.html

[R25] 去后缀 / 去前缀
来源：http://dali.fzhhl.top/Article/details/gtyuojxbxf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.aibaodan.cn/Article/details/gtnptzkcqe.html

[R26] 命令替换
来源：http://dali.daria6918.cn/Article/details/gtxzgyywyv.html

now=$(date +%F); echo "$now"
来源：http://dali.cashguo.top/Article/details/gttxrlcwsy.html

[R27] 算术展开
来源：http://dali.zhiwuduotai.top/Article/details/gtsfuoakny.html

echo $((1 + 2 * 3))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtllgzifqf.html

[R28] 浮点运算
来源：http://dali.haohaochexian.top/Article/details/gthtyrpsfo.html

echo "scale=2; 10/3" | bc
来源：http://dali.ydzc1.top/Article/details/gtezemkcfu.html

[R29] 定义函数
来源：http://dali.tanke756.top/Article/details/gtdusqvqxv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yangfankeji.com/Article/details/gtmnrhvbpq.html

[R30] 函数返回状态码
来源：http://dali.zhixingplan.top/Article/details/gtryvugkvp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpuolrazv.html

[R31] 局部变量
来源：http://dali.daria6918.cn/Article/details/gtivchztmp.html

f() { local x=1; echo "$x"; }
来源：http://dali.chenzaomai.com/Article/details/gtikhxnmzn.html

[R32] 参数个数校验
来源：http://dali.xuanzx.com/Article/details/gtwxtyqmtg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ybcxt.top/Article/details/gtslhnfqvt.html

[R33] 捕获错误并提示行号
来源：http://dali.zhiwuduotai.top/Article/details/gtztdrgoat.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yangfankeji.com/Article/details/gtxqmipiwq.html

[R34] 退出时清理
来源：http://dali.zhoulong.xyz/Article/details/gtyhmffkea.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.redwolf501.top/Article/details/gtwfwhxvse.html

[R35] 后台执行并等待
来源：http://dali.ydzc1.top/Article/details/gtcbknkbuj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.aizwys.cn/Article/details/gtysfeqlqq.html

[R36] 并发执行多个任务
来源：http://dali.hnxiangtu.top/Article/details/gtxdxoihnx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.aizwys.cn/Article/details/gtwbmnifee.html

[R37] 把输出赋给变量
来源：http://dali.jianghu66.top/Article/details/gtjwcbfvac.html

files=$(ls -1)
来源：http://dali.fzhhl.top/Article/details/gtmbdfhoju.html

[R38] 管道串联
来源：http://dali.feifeiyinyue.top/Article/details/gteuzscfon.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhixingplan.top/Article/details/gtbevbqhkk.html

[R39] 重定向标准输出与错误
来源：http://dali.daxiang520.top/Article/details/gtngbwecvr.html

cmd > out.log 2>&1
来源：http://dali.mhx1999.top/Article/details/gtibtopxjl.html

[R40] 追加写日志
来源：http://dali.cashguo.top/Article/details/gtiuysuagz.html

echo "log" >> out.log
来源：http://dali.shanyushiyangtech.top/Article/details/gtdmcahksz.html

[R41] 丢弃输出
来源：http://dali.gotoacloud.top/Article/details/gtxojgiwlk.html

cmd >/dev/null 2>&1
来源：http://dali.zdqjudy.top/Article/details/gtwdlaptmz.html

[R42] 输入重定向
来源：http://dali.cucudq.cn/Article/details/gtpdjmdgxl.html

wc -l < a.txt
来源：http://dali.zhengqikj.top/Article/details/gtnpdkobla.html

[R43] 按名字查找文件
来源：http://dali.aizwys.cn/Article/details/gtlmiwnqow.html

find . -name "*.log" -type f
来源：http://dali.xuanzx.com/Article/details/gtftzabatj.html

[R44] 按修改时间查找
来源：http://dali.svipenyu.cn/Article/details/gtmsgvagxn.html

find . -mtime -7 -type f
来源：http://dali.yuanzhike.top/Article/details/gtxjvcuzln.html

[R45] 批量删除
来源：http://dali.mhx1999.top/Article/details/gtkdtwamur.html

find . -name "*.tmp" -delete
来源：http://dali.yonumen.top/Article/details/gtvbkuyquy.html

[R46] 递归替换文件内容
来源：http://dali.shanyushiyangtech.top/Article/details/gtivpoynji.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.gotoacloud.top/Article/details/gtelhobfxr.html

[R47] sed 单行替换
来源：http://dali.chenzaomai.com/Article/details/gtulxdmsxr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gteeuejuun.html

[R48] awk 取指定列
来源：http://dali.xylfe.cn/Article/details/gtijujvcsf.html

awk '{print $1, $3}' a.txt
来源：http://dali.yj202588.top/Article/details/gtudryxbtp.html

[R49] awk 带条件
来源：http://dali.sufxvd.cn/Article/details/gtfgwqpiai.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yj20258.top/Article/details/gtrbwsxzyn.html

[R50] awk 求和
来源：http://dali.nanxinkj.top/Article/details/gtcdvkoway.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yuanzhike.top/Article/details/gttulqpnig.html

[R51] 排序去重取前几
来源：http://dali.tianlin.xyz/Article/details/gtmwidlkry.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yj20258.top/Article/details/gtbdwbzrrr.html

[R52] 统计行数
来源：http://dali.c1oappe.top/Article/details/gtkahgomov.html

wc -l a.txt
来源：http://dali.ydzc1.top/Article/details/gtkjdpxtet.html

[R53] 查看文件头与实时尾
来源：http://dali.nanxinkj.top/Article/details/gtxancjnnw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.havefunace.top/Article/details/gtgtmceisl.html

[R54] 比较两个文件
来源：http://dali.hysaishi.cn/Article/details/gtcltkxtjg.html

diff a.txt b.txt
来源：http://dali.hnqzz.top/Article/details/gtwefwckvv.html

[R55] 压缩与解压
来源：http://dali.guowangkeji.top/Article/details/gtscwajhxa.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.haohaochexian.top/Article/details/gtseddmvux.html

[R56] 远程拷贝
来源：http://dali.xylfe.cn/Article/details/gtdovbfupq.html

scp file user@host:/path/
来源：http://dali.xziqi.cn/Article/details/gtzfutcjdf.html

[R57] 远程执行命令
来源：http://dali.jianghu66.top/Article/details/gtfsjmozow.html

ssh user@host 'uptime'
来源：http://dali.yueranfly.top/Article/details/gtomcrrooy.html

[R58] 下载文件
来源：http://dali.andypj.xyz/Article/details/gtqeqewrsu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.dianchejie.cn/Article/details/gteajunwgf.html

[R59] 发 POST JSON
来源：http://dali.ybcxt.top/Article/details/gtgnzcstry.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.fzhhl.top/Article/details/gtusrzvrle.html

[R60] 只看 HTTP 状态码
来源：http://dali.gogol.net.cn/Article/details/gtmytkomgs.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.daxiang520.top/Article/details/gtaydgvcvm.html

[R61] 磁盘占用
来源：http://dali.vqdsnc.cn/Article/details/gtpncmnhtf.html

df -h;  du -sh *
来源：http://dali.birdmap.top/Article/details/gtcpkabccq.html

[R62] 找最占空间的文件
来源：http://dali.cheryme.top/Article/details/gtufkppzmo.html

du -ah . | sort -rh | head -10
来源：http://dali.xuanzx.com/Article/details/gtmulnlmrk.html

[R63] 内存与进程
来源：http://dali.xylfe.cn/Article/details/gtfxxeuabo.html

free -h;  ps aux | grep nginx
来源：http://dali.aizwys.cn/Article/details/gtcmytmvoq.html

[R64] 结束进程
来源：http://dali.feifeiyinyue.top/Article/details/gtzuajhxnm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shangyingyoupin.top/Article/details/gtizlvuwmu.html

[R65] 查看端口占用
来源：http://dali.jqgfzy.top/Article/details/gtgpgbqtbc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj20258888.top/Article/details/gtphmbuqik.html

[R66] 定时任务
来源：http://dali.cqqwz.cn/Article/details/gtlewrtiqc.html

crontab -e;  crontab -l
来源：http://dali.dashuyun.cn/Article/details/gtzixgylop.html

[R67] 生成随机十六进制串
来源：http://dali.yongpay.top/Article/details/gtholldwnu.html

openssl rand -hex 16
来源：http://dali.chenlongwang.top/Article/details/gtbcmnawmv.html

[R68] 计算文件校验值
来源：http://dali.jinghuilouyu.cn/Article/details/gterwzpswy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtptntkmur.html

[R69] 生成随机密码
来源：http://dali.yongpay.top/Article/details/gtjorctvwa.html

head -c 16 /dev/urandom | base64
来源：http://dali.ivvv.top/Article/details/gtughhwcxr.html

[R70] 时间戳与互转
来源：http://dali.jyoumei.cn/Article/details/gteudpvrxh.html

date +%s;  date -d @1700000000
来源：http://dali.xuetiantiany.cn/Article/details/gtfggtyysx.html

[R71] 日期格式化
来源：http://dali.meibo888.top/Article/details/gtkwtemkqj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.sufxvd.cn/Article/details/gtcrfyntvz.html

[R72] 等待端口就绪
来源：http://dali.jqgfzy.top/Article/details/gtgloxfcdg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.mhx1999.top/Article/details/gtpcpksenu.html

[R73] 分割大日志
来源：http://dali.zhongyouzk.top/Article/details/gtjpyjgeeq.html

split -l 1000 big.log part_
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpvslwuos.html

[R74] 批量重命名
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbbzykrsi.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xuanzx.com/Article/details/gtuxcsjwgo.html

[R75] 导出环境变量
来源：http://dali.gogol.net.cn/Article/details/gtuadynxmw.html


<!-- 参考信息 -->