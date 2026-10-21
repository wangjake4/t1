代发 wailian999

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhongyouzk.top/Article/details/gtfvcpjgwv.html

[Q26] 计数
来源：http://dali.jlsjyb.cn/Article/details/gthwexqpsg.html

SELECT COUNT(*) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtkcuoyale.html

[Q27] 条件计数
来源：http://dali.0kj1m.cn/Article/details/gtfarvpyhm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtywugfvuz.html

[Q28] 求和与平均
来源：http://dali.hysaishi.cn/Article/details/gtmswvvzek.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gtrlsfbzic.html

[Q29] 最大最小值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjgtwznvc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyyarujek.html

[Q30] 分组统计
来源：http://dali.jianghu66.top/Article/details/gtgnyvmjdd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ivvv.top/Article/details/gtzgajvwbf.html

[Q31] 分组后过滤
来源：http://dali.zhoulong.xyz/Article/details/gtteeqcmem.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.redwolf501.top/Article/details/gtlhoyoutv.html

[Q32] 分组拼接字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgdkacjhk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jqgfzy.top/Article/details/gtprbrrlhe.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.tianlin.xyz/Article/details/gttqdmgfxo.html

[Q33] 多列分组
来源：http://dali.zhiwuduotai.top/Article/details/gtrjirjded.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yanxiufei.cn/Article/details/gtpveoksfi.html

[Q34] 每组取第一条
来源：http://dali.xylfe.cn/Article/details/gtjiqqztej.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gtfoyigdmc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.fzhhl.top/Article/details/gtnuwztvth.html

) t WHERE rn = 1;
来源：http://dali.meibo888.top/Article/details/gtxdaxwnys.html

[Q35] 内连接
来源：http://dali.wangshuangyany.cn/Article/details/gtrcvxjcwx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258.top/Article/details/gtrmquwzxs.html

[Q36] 左连接
来源：http://dali.zhengqikj.top/Article/details/gtgbotorua.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gotoacloud.top/Article/details/gthnexikcz.html

[Q37] 右连接
来源：http://dali.shanyushiyangtech.top/Article/details/gtdvkaxrtq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gtfzrvgkqj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.wangdashe.top/Article/details/gthfyykqmo.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hongshengwenyu.top/Article/details/gtbrmldcyx.html

[Q39] 自连接（查上下级）
来源：http://dali.yj202588.top/Article/details/gtgmrhkind.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shanyushiyangtech.top/Article/details/gtjaredtxh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.c1oappe.top/Article/details/gtylpjmoql.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtatprtrbw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.smart0.xyz/Article/details/gtqqjwkprn.html

[Q41] 多表连接
来源：http://dali.jianghu66.top/Article/details/gtbnlmrhia.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.dianchejie.cn/Article/details/gtlsstflwl.html

JOIN users u ON u.id = o.user_id
来源：http://dali.andypj.xyz/Article/details/gttkswaior.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gttangbxen.html

[Q42] 连接条件附加过滤
来源：http://dali.ivvv.top/Article/details/gtnireuorl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.smart0.xyz/Article/details/gtaztjlqkn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtadekloxx.html

[Q43] 标量子查询
来源：http://dali.xziqi.cn/Article/details/gtpgubfzgh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yj20258888.top/Article/details/gtjabmbvfw.html

[Q44] IN 子查询
来源：http://dali.jianghu66.top/Article/details/gtnbshtglr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.chenjidiqi.icu/Article/details/gtruqggxxg.html

[Q45] EXISTS 判断存在
来源：http://dali.nwbrower.top/Article/details/gtgwunwbrd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zdqjudy.top/Article/details/gtfkmllmww.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jianghu66.top/Article/details/gtsjqzfyxt.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zdqjudy.top/Article/details/gtmzesulrh.html

[Q47] 与平均值比较
来源：http://dali.9152youxi.cn/Article/details/gtswpywjme.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmccuavdm.html

[Q48] CTE 公用表表达式
来源：http://dali.ydzc1.top/Article/details/gtpvyffzfj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.0kj1m.cn/Article/details/gtiqiapwkv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gzhubu.top/Article/details/gtknjvylqk.html

[Q49] 更新单行
来源：http://dali.ivvv.top/Article/details/gtbrmjhqxw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.redwolf501.top/Article/details/gtksdgzjph.html

[Q50] 批量更新
来源：http://dali.yj20258.top/Article/details/gtpxswaxwv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.guowangkeji.top/Article/details/gtemovwlmz.html

[Q51] 用子查询更新
来源：http://dali.pengpengdd.cyou/Article/details/gtwwgxkbac.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gtrblzkxgp.html

[Q52] 删除指定行
来源：http://dali.bjfxy.top/Article/details/gtojbufhov.html

DELETE FROM users WHERE id = 10;
来源：http://dali.quarkkingdee.top/Article/details/gtfgcqcyfm.html

[Q53] 按条件删除
来源：http://dali.guannengcc.top/Article/details/gtwexmqwrf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.aizwys.cn/Article/details/gtwnrsubvn.html

[Q54] 清空表
来源：http://dali.ydzc1.top/Article/details/gtaswitihu.html

TRUNCATE TABLE logs;
来源：http://dali.guowangkeji.top/Article/details/gtmnzmmipt.html

[Q55] 排名（并列占位）
来源：http://dali.cdnleiting.top/Article/details/gteehozpmh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.redwolf501.top/Article/details/gtopddpjfr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jqgufenzy.top/Article/details/gtmcehiemi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.chenzaomai.com/Article/details/gtsftkxmeg.html

[Q57] 行号
来源：http://dali.jlsjyb.cn/Article/details/gthfwtanmm.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtmadahnum.html

[Q58] 累计求和
来源：http://dali.guowangkeji.top/Article/details/gtitezmyaj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cashguo.top/Article/details/gtrcpyiqxb.html

[Q59] 分组内累计
来源：http://dali.hywenlv.cn/Article/details/gtthsjrimx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gtzjyzpbjt.html

[Q60] 取上一行 / 下一行
来源：http://dali.yj20258.top/Article/details/gtdecpbcgf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sweek.top/Article/details/gthtchymkg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.redwolf501.top/Article/details/gtqhmekiyb.html

[Q61] 移动平均
来源：http://dali.zycfv.cn/Article/details/gtuelwzrym.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.c1oappe.top/Article/details/gtehvcknkb.html

[Q62] 分组占比
来源：http://dali.zhoulong.xyz/Article/details/gtutfrmuii.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yj20258888.top/Article/details/gtlxnfyinp.html

[Q63] 开启事务
来源：http://dali.dashuyun.cn/Article/details/gtojaxzfkq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hammf.cn/Article/details/gtuuaphvvw.html

[Q64] 提交事务
来源：http://dali.meibo888.top/Article/details/gtfebeimir.html

COMMIT;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgvgqeyxg.html

[Q65] 回滚事务
来源：http://dali.yuanzhike.top/Article/details/gtoasbkvux.html

ROLLBACK;
来源：http://dali.xuetiantiany.cn/Article/details/gtbttrorzz.html

[Q66] 行锁查询
来源：http://dali.gotoacloud.top/Article/details/gtbwmprjne.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.snrcjt.cn/Article/details/gtdycosmve.html

[Q67] 设置隔离级别
来源：http://dali.svipenyu.cn/Article/details/gtontdyffz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbcucxahj.html

[Q68] 保存点
来源：http://dali.jinghuilouyu.cn/Article/details/gtnsgtfflk.html

SAVEPOINT sp1;
来源：http://dali.hywenlv.cn/Article/details/gtjdjiafrp.html

ROLLBACK TO sp1;
来源：http://dali.wangdashe.top/Article/details/gtzcnqkzbd.html

[Q69] 查看执行计划
来源：http://dali.wangshuangyany.cn/Article/details/gtanladnnn.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gogol.net.cn/Article/details/gtehtkuqwx.html

[Q70] 更新统计信息
来源：http://dali.dianchejie.cn/Article/details/gtzwdaokjo.html

ANALYZE TABLE users;
来源：http://dali.316326.xyz/Article/details/gtfjkazbxy.html

[Q71] 查看建表语句
来源：http://dali.cdnleiting.top/Article/details/gtpwtnjsod.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cheryme.top/Article/details/gtdorkwwfp.html

[Q72] 查看索引
来源：http://dali.xylfe.cn/Article/details/gtlawogncj.html

SHOW INDEX FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtoqwzqkvv.html

[Q73] 查看表状态
来源：http://dali.jqgfzy.top/Article/details/gtsfggwohx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhoulong.xyz/Article/details/gtjsmeuums.html

[Q74] 强制使用索引
来源：http://dali.gogol.net.cn/Article/details/gtwopwhorw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yj20258.top/Article/details/gtmkhqymyx.html

[Q75] 日期格式化
来源：http://dali.nanxuanxn.top/Article/details/gtzltnkcha.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yonumen.top/Article/details/gtcsuasvcv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.fengsongda.top/Article/details/gtehduywhl.html

[Q76] 按天统计
来源：http://dali.chenzaomai.com/Article/details/gtpqcmbsje.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xziqi.cn/Article/details/gtpakbsfmv.html

[Q77] 时间加减
来源：http://dali.ydzc1.top/Article/details/gtmskdfyev.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.vqdsnc.cn/Article/details/gtgtjmclok.html

[Q78] 当前时间
来源：http://dali.iojbl.cn/Article/details/gthvgenylw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.andypj.xyz/Article/details/gtczrwovwc.html

[Q79] 字符串拼接
来源：http://dali.pycfn.com/Article/details/gtywluqczf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.feifeiyinyue.top/Article/details/gtwjvtjqgv.html

[Q80] 字符串截取
来源：http://dali.hnqzz.top/Article/details/gtnfzxdeax.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ydzc1.top/Article/details/gtvyoaoszf.html

[Q81] 字符串替换
来源：http://dali.yonumen.top/Article/details/gtukvjsuky.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtffzbqcvp.html

[Q82] 字符长度与字节长度
来源：http://dali.ybcxt.top/Article/details/gtzibubqch.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtwlddmrsd.html

[Q83] 大小写转换
来源：http://dali.yangfankeji.com/Article/details/gtctsuvhnu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.bjfxy.top/Article/details/gtwswvaexv.html

[Q84] 去除首尾空格
来源：http://dali.andypj.xyz/Article/details/gtvhxcqfrr.html

SELECT TRIM(name) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtnrakevgh.html

[Q85] 数值取整
来源：http://dali.zhongyouzk.top/Article/details/gtqubxvvpz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.havefunace.top/Article/details/gtxaxwnafl.html

[Q86] 读取 JSON 字段
来源：http://dali.zhiwuduotai.top/Article/details/gtnolgpazg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.dianchejie.cn/Article/details/gtzoyijxjj.html

[Q87] JSON 字段做条件
来源：http://dali.guannengcc.top/Article/details/gtaozvvzbs.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shuidangran.top/Article/details/gtbvrdytku.html

[Q88] 行转列（条件聚合）
来源：http://dali.yangfankeji.com/Article/details/gtlkmlmlkl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hysaishi.cn/Article/details/gtspbbzqud.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtrcisdulk.html

[Q89] 判断表是否存在
来源：http://dali.daxiang520.top/Article/details/gtbgmkqagf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yonumen.top/Article/details/gtrsldnzpp.html

[Q90] 生成序号列
来源：http://dali.jiagoushi.top/Article/details/gtleteokvt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.smart0.xyz/Article/details/gtlyspfvqz.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtwofqokcc.html

R. Bash 专题
来源：http://dali.fzhhl.top/Article/details/gtfixavrzy.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtmepoxirg.html

[R01] shebang 与严格模式
来源：http://dali.svipenyu.cn/Article/details/gtyifpdmlp.html

#!/usr/bin/env bash
来源：http://dali.redwolf501.top/Article/details/gtrhvrgjbo.html

set -euo pipefail
来源：http://dali.yonumen.top/Article/details/gtrdnbwcfb.html

[R02] 变量赋值与使用
来源：http://dali.wangshuangyany.cn/Article/details/gtovlbuhuz.html

name="Tom"; echo "$name"
来源：http://dali.tanke756.top/Article/details/gtqtpdwunx.html

[R03] 只读变量
来源：http://dali.jqgufenzy.top/Article/details/gtzscpbaum.html

readonly PI=3.14
来源：http://dali.guowangkeji.top/Article/details/gtwfhimlvy.html

[R04] 位置参数
来源：http://dali.yuanzhike.top/Article/details/gtegznsoal.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yj20258.top/Article/details/gtsraalqqy.html

[R05] 参数默认值
来源：http://dali.gogol.net.cn/Article/details/gtgozrwsin.html

name="${1:-default}"
来源：http://dali.yonumen.top/Article/details/gtspxscpbd.html

[R06] 判断命令是否存在
来源：http://dali.tanke756.top/Article/details/gtlfshiafq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.dianchejie.cn/Article/details/gtntzncrxc.html

[R07] if 判断文件
来源：http://dali.zhixingplan.top/Article/details/gtnwxeecqc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ppjwa.cn/Article/details/gtqnqocquj.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gtnltmqsug.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gtenqfeele.html

[R09] 字符串比较
来源：http://dali.jiagoushi.top/Article/details/gtxuxbnlim.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gtdsfqpuvv.html

[R10] 正则匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gtqogwtegr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gtqwjluglx.html

[R11] case 多分支
来源：http://dali.shzxlz.cn/Article/details/gtuhlpwloz.html

case "$1" in
来源：http://dali.c1oappe.top/Article/details/gtyzmwfmsx.html

start) echo "启动" ;;
来源：http://dali.birdmap.top/Article/details/gtpfphmsmz.html

stop)  echo "停止" ;;
来源：http://dali.jqgfzy.top/Article/details/gtxnkhcnvj.html

*)     echo "未知命令" ;;
来源：http://dali.gzhubu.top/Article/details/gtwvfuiklv.html

esac
来源：http://dali.dianchejie.cn/Article/details/gtxekwpmnk.html

[R12] for 遍历文件
来源：http://dali.hongshengwenyu.top/Article/details/gtzdeexpwr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hywenlv.cn/Article/details/gtcpaottsn.html

[R13] for 计数循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtmsaeexqk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sweek.top/Article/details/gthnlotnoy.html

[R14] C 风格 for
来源：http://dali.hammf.cn/Article/details/gtfjmowsha.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gaohongyu789.top/Article/details/gtcyizhjrx.html

[R15] while 逐行读文件
来源：http://dali.shangyingyoupin.top/Article/details/gtgmsnvfvr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtbpuxjomf.html

[R16] until 等待条件
来源：http://dali.shzxlz.cn/Article/details/gtnjftbyin.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xylfe.cn/Article/details/gtnggdtaaf.html

[R17] 数组定义与取值
来源：http://dali.nanxuanxn.top/Article/details/gtwatzjjdy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.c1oappe.top/Article/details/gtbdakksgp.html

[R18] 遍历数组
来源：http://dali.hnqzz.top/Article/details/gtmegznsbl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinqigufen.top/Article/details/gtzipefbns.html

[R19] 数组长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuoxxxhyv.html

echo "${#arr[@]}"
来源：http://dali.yj20258888.top/Article/details/gtvnnaiwqt.html

[R20] 关联数组（字典）
来源：http://dali.nanxinkj.top/Article/details/gthwkzukoi.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.meibo888.top/Article/details/gthezybnnt.html

[R21] 字符串长度
来源：http://dali.xziqi.cn/Article/details/gthmqnaeqf.html

echo "${#s}"
来源：http://dali.snrcjt.cn/Article/details/gteduzqacc.html

[R22] 截取子串
来源：http://dali.hammf.cn/Article/details/gtwbyicnzu.html

echo "${s:0:5}"
来源：http://dali.cashguo.top/Article/details/gtzixitjur.html

[R23] 字符串替换
来源：http://dali.hnqzz.top/Article/details/gthodvudma.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.haohaochexian.top/Article/details/gtwyqcxivc.html

[R24] 大小写转换
来源：http://dali.svipenyu.cn/Article/details/gtdjankqay.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yuxming.cn/Article/details/gtaeahqryw.html

[R25] 去后缀 / 去前缀
来源：http://dali.gzhubu.top/Article/details/gtexiwckbw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hfpthk.cn/Article/details/gtucqfohqc.html

[R26] 命令替换
来源：http://dali.ppjwa.cn/Article/details/gtjztpgbwd.html

now=$(date +%F); echo "$now"
来源：http://dali.sxryk.cn/Article/details/gtibywsmqz.html

[R27] 算术展开
来源：http://dali.tianlin.xyz/Article/details/gtqmmijgyg.html

echo $((1 + 2 * 3))
来源：http://dali.jyoumei.cn/Article/details/gtdxpjtrbw.html

[R28] 浮点运算
来源：http://dali.yuxming.cn/Article/details/gtmkuqbajv.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhoulong.xyz/Article/details/gtanlqrbav.html

[R29] 定义函数
来源：http://dali.gzhubu.top/Article/details/gtvtpuseou.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.snrcjt.cn/Article/details/gtapmmcslr.html

[R30] 函数返回状态码
来源：http://dali.bjfxy.top/Article/details/gtixnmmlcj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.redwolf501.top/Article/details/gtdchfgkof.html

[R31] 局部变量
来源：http://dali.dianchejie.cn/Article/details/gtpxxiibfj.html

f() { local x=1; echo "$x"; }
来源：http://dali.andypj.xyz/Article/details/gtrbseycqm.html

[R32] 参数个数校验
来源：http://dali.jinghuilouyu.cn/Article/details/gtmeakaewb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gotoacloud.top/Article/details/gtlyrjcyoj.html

[R33] 捕获错误并提示行号
来源：http://dali.nwbrower.top/Article/details/gtgoqhdcei.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hnqzz.top/Article/details/gtahyoilue.html

[R34] 退出时清理
来源：http://dali.hfpthk.cn/Article/details/gtilwkbvkw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuetiantiany.cn/Article/details/gtqxpuegnt.html

[R35] 后台执行并等待
来源：http://dali.zhaomingkeji.xyz/Article/details/gtflvfbvcw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.redwolf501.top/Article/details/gtzbpfzxne.html

[R36] 并发执行多个任务
来源：http://dali.gotoacloud.top/Article/details/gtykuujyrb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.daxiang520.top/Article/details/gtdqrqpbqm.html

[R37] 把输出赋给变量
来源：http://dali.hongshengwenyu.top/Article/details/gtedyjvtol.html

files=$(ls -1)
来源：http://dali.andypj.xyz/Article/details/gtrcvmzzia.html

[R38] 管道串联
来源：http://dali.chenjidiqi.icu/Article/details/gtjdauyzje.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hfpthk.cn/Article/details/gtnwfbnlmg.html

[R39] 重定向标准输出与错误
来源：http://dali.yvedp.cn/Article/details/gtprthdaxe.html

cmd > out.log 2>&1
来源：http://dali.jqgufenzy.top/Article/details/gtyslewfjo.html

[R40] 追加写日志
来源：http://dali.cheryme.top/Article/details/gtxavtiqmy.html

echo "log" >> out.log
来源：http://dali.shuidangran.top/Article/details/gtgorkcbhi.html

[R41] 丢弃输出
来源：http://dali.quarkkingdee.top/Article/details/gtmoreldok.html

cmd >/dev/null 2>&1
来源：http://dali.xuanzx.com/Article/details/gtxmgeyqro.html

[R42] 输入重定向
来源：http://dali.fengsongda.top/Article/details/gtemzrkjlg.html

wc -l < a.txt
来源：http://dali.xinyue.icu/Article/details/gthahzupky.html

[R43] 按名字查找文件
来源：http://dali.havefunace.top/Article/details/gtjvlugdnz.html

find . -name "*.log" -type f
来源：http://dali.meibo888.top/Article/details/gtphouiqsd.html

[R44] 按修改时间查找
来源：http://dali.guannengcc.top/Article/details/gtmmxdvdpv.html

find . -mtime -7 -type f
来源：http://dali.kuanghao11.cn/Article/details/gtaggavjzf.html

[R45] 批量删除
来源：http://dali.zhongyouzk.top/Article/details/gtleelakka.html

find . -name "*.tmp" -delete
来源：http://dali.feifeiyinyue.top/Article/details/gtsyhapqrb.html

[R46] 递归替换文件内容
来源：http://dali.hnqzz.top/Article/details/gtniorijsa.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cucudq.cn/Article/details/gtibhklrli.html

[R47] sed 单行替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxxladhdj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sweek.top/Article/details/gtlghdqnhg.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gtjizssvuw.html

awk '{print $1, $3}' a.txt
来源：http://dali.havefunace.top/Article/details/gtqjjteszg.html

[R49] awk 带条件
来源：http://dali.yuanzhike.top/Article/details/gthimzvjrx.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yanxiufei.cn/Article/details/gtspsdbexg.html

[R50] awk 求和
来源：http://dali.zhoulong.xyz/Article/details/gtjkvyhglf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xuanzx.com/Article/details/gtroxwkpqt.html

[R51] 排序去重取前几
来源：http://dali.wangdashe.top/Article/details/gtsdbyzxiv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xuanzx.com/Article/details/gtrukkvlna.html

[R52] 统计行数
来源：http://dali.jlsjyb.cn/Article/details/gtgumjvpoz.html

wc -l a.txt
来源：http://dali.zhongyouzk.top/Article/details/gtvyxtuojg.html

[R53] 查看文件头与实时尾
来源：http://dali.dianchejie.cn/Article/details/gtqmcjrpit.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdzvetpqs.html

[R54] 比较两个文件
来源：http://dali.nwbrower.top/Article/details/gtwhqkeeqc.html

diff a.txt b.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzdetjxxt.html

[R55] 压缩与解压
来源：http://dali.smart0.xyz/Article/details/gtdqrayhaz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.nwbrower.top/Article/details/gtyixutfis.html

[R56] 远程拷贝
来源：http://dali.wangdashe.top/Article/details/gtoxhkixya.html

scp file user@host:/path/
来源：http://dali.kuanghao11.cn/Article/details/gtnrrwyjgg.html

[R57] 远程执行命令
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxsofkrju.html

ssh user@host 'uptime'
来源：http://dali.wangshuangyany.cn/Article/details/gtdhhkozvw.html

[R58] 下载文件
来源：http://dali.aibaodan.cn/Article/details/gtiyotnmcg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ehwqpu.com/Article/details/gtkrrkxrzw.html

[R59] 发 POST JSON
来源：http://dali.tian-w.cn/Article/details/gtdgedhjab.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.daria6918.cn/Article/details/gtntuorojv.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhiwuduotai.top/Article/details/gtowtpxafg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cdnleiting.top/Article/details/gtgwtylsru.html

[R61] 磁盘占用
来源：http://dali.zdqjudy.top/Article/details/gtrroswtan.html

df -h;  du -sh *
来源：http://dali.wangdashe.top/Article/details/gtwzskupbu.html

[R62] 找最占空间的文件
来源：http://dali.guannengcc.top/Article/details/gtrgictivn.html

du -ah . | sort -rh | head -10
来源：http://dali.gotoacloud.top/Article/details/gtpxjvtkhk.html

[R63] 内存与进程
来源：http://dali.jinyuanbaomall.cn/Article/details/gtelqseond.html

free -h;  ps aux | grep nginx
来源：http://dali.gotoacloud.top/Article/details/gthoyxwdrs.html

[R64] 结束进程
来源：http://dali.redwolf501.top/Article/details/gtttgcxccq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yj20258888.top/Article/details/gtgwjrpsed.html

[R65] 查看端口占用
来源：http://dali.zycfv.cn/Article/details/gtsqcmofsh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jqgufenzy.top/Article/details/gtowfpzbow.html

[R66] 定时任务
来源：http://dali.yj20258888.top/Article/details/gthcpmwcny.html

crontab -e;  crontab -l
来源：http://dali.316326.xyz/Article/details/gttxmzoqoc.html

[R67] 生成随机十六进制串
来源：http://dali.hnqzz.top/Article/details/gtotkvrrvd.html

openssl rand -hex 16
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbjgypvlc.html

[R68] 计算文件校验值
来源：http://dali.pengpengdd.cyou/Article/details/gtelpiebpe.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtvadioerg.html

[R69] 生成随机密码
来源：http://dali.xuanzx.com/Article/details/gtrthfkhzz.html

head -c 16 /dev/urandom | base64
来源：http://dali.yueranfly.top/Article/details/gtcpvozlxk.html

[R70] 时间戳与互转
来源：http://dali.haohaochexian.top/Article/details/gtxtnlzwcn.html

date +%s;  date -d @1700000000
来源：http://dali.jianghu66.top/Article/details/gtzywhmmti.html

[R71] 日期格式化
来源：http://dali.yuxming.cn/Article/details/gtcbcgohfq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.wangshuangyany.cn/Article/details/gtmpophiza.html

[R72] 等待端口就绪
来源：http://dali.ppjwa.cn/Article/details/gtsysddbrw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.nanxuanxn.top/Article/details/gtequtnivn.html

[R73] 分割大日志
来源：http://dali.zhiwuduotai.top/Article/details/gtmbwuevjl.html

split -l 1000 big.log part_
来源：http://dali.yueranfly.top/Article/details/gtlbxpyktm.html

[R74] 批量重命名
来源：http://dali.aizwys.cn/Article/details/gttvtajsdl.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yonumen.top/Article/details/gtjyrcteqn.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gtmavdxywh.html


<!-- 参考信息 -->