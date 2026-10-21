代发 wailian999

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jianghu66.top/Article/details/gtoceqeger.html

[Q24] 去重
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiwiaskht.html

SELECT DISTINCT city FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtlfzgdjfu.html

[Q25] 只取前 N 条
来源：http://dali.mhx1999.top/Article/details/gtrqeqcgix.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ehwqpu.com/Article/details/gtmecroido.html

[Q26] 计数
来源：http://dali.xylfe.cn/Article/details/gtonjooocm.html

SELECT COUNT(*) FROM users;
来源：http://dali.cashguo.top/Article/details/gtgcuzmgcf.html

[Q27] 条件计数
来源：http://dali.tianlin.xyz/Article/details/gtrbzvpdnr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtjdfsddtn.html

[Q28] 求和与平均
来源：http://dali.andypj.xyz/Article/details/gtanjkovdc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gtvcwebqbt.html

[Q29] 最大最小值
来源：http://dali.cashguo.top/Article/details/gtvfwrlzwq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.nwbrower.top/Article/details/gtxerpuhki.html

[Q30] 分组统计
来源：http://dali.jqgfzy.top/Article/details/gtdohgbngn.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.gzhubu.top/Article/details/gtsflzicbo.html

[Q31] 分组后过滤
来源：http://dali.9152youxi.cn/Article/details/gtmqwykiwd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xuetiantiany.cn/Article/details/gtplzfnbad.html

[Q32] 分组拼接字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtvyrqsinv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.smart0.xyz/Article/details/gtqygjbtwx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jianghu66.top/Article/details/gtcrzklbpa.html

[Q33] 多列分组
来源：http://dali.zycfv.cn/Article/details/gtdfvxxjrl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.guannengcc.top/Article/details/gtgeevitdi.html

[Q34] 每组取第一条
来源：http://dali.zycfv.cn/Article/details/gtcckxbwdo.html

SELECT * FROM (
来源：http://dali.jiagoushi.top/Article/details/gtyhletemy.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.feifeiyinyue.top/Article/details/gtuijmkcwn.html

) t WHERE rn = 1;
来源：http://dali.yj202588.top/Article/details/gtqoczeqgh.html

[Q35] 内连接
来源：http://dali.xuanzx.com/Article/details/gtsagdroyq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hywenlv.cn/Article/details/gtomtivvhy.html

[Q36] 左连接
来源：http://dali.sufxvd.cn/Article/details/gtlauwbsay.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ehwqpu.com/Article/details/gtscofjplk.html

[Q37] 右连接
来源：http://dali.yueranfly.top/Article/details/gtlodqmuyh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkmdwdprn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.birdmap.top/Article/details/gtlmngucql.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvdpkfeyl.html

[Q39] 自连接（查上下级）
来源：http://dali.ppjwa.cn/Article/details/gtliertzcg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.daxiang520.top/Article/details/gtjibhdhyu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.chenjidiqi.icu/Article/details/gtsotdiivl.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cqqwz.cn/Article/details/gtihavzntl.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jinqigufen.top/Article/details/gtmpyiffkr.html

[Q41] 多表连接
来源：http://dali.kuanghao11.cn/Article/details/gtntuilzsf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hnxiangtu.top/Article/details/gtqwsvuatt.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthlvfqexc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yj20258.top/Article/details/gtebvhleld.html

[Q42] 连接条件附加过滤
来源：http://dali.redwolf501.top/Article/details/gtdosiqsoi.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yueranfly.top/Article/details/gtwjfbzwtv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hongshengwenyu.top/Article/details/gtxzipthxe.html

[Q43] 标量子查询
来源：http://dali.yuanzhike.top/Article/details/gttmgtvsik.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ppjwa.cn/Article/details/gtghuisplm.html

[Q44] IN 子查询
来源：http://dali.cucudq.cn/Article/details/gtjaprawiz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.smart0.xyz/Article/details/gtdkwvykkk.html

[Q45] EXISTS 判断存在
来源：http://dali.sufxvd.cn/Article/details/gtzmtmohyk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.haohaochexian.top/Article/details/gtjrexrkyg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xylfe.cn/Article/details/gthtmjlygm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.dianchejie.cn/Article/details/gtdtcwrrku.html

[Q47] 与平均值比较
来源：http://dali.redwolf501.top/Article/details/gtkmspmwhn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.guowangkeji.top/Article/details/gtjcfrjfpj.html

[Q48] CTE 公用表表达式
来源：http://dali.feifeiyinyue.top/Article/details/gttzjojklx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtunzintqw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gogol.net.cn/Article/details/gtpgqfomdo.html

[Q49] 更新单行
来源：http://dali.xuanzx.com/Article/details/gtlftngnmn.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhixingplan.top/Article/details/gtxicrlfaj.html

[Q50] 批量更新
来源：http://dali.sysykeji.top/Article/details/gtxnsfjlpe.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.nwbrower.top/Article/details/gtgupzyiar.html

[Q51] 用子查询更新
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbcicvchs.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtmezoghpv.html

[Q52] 删除指定行
来源：http://dali.zdqjudy.top/Article/details/gteuazpkxk.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gthovoucms.html

[Q53] 按条件删除
来源：http://dali.smart0.xyz/Article/details/gtewqqsjle.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhixingplan.top/Article/details/gtdxpabehm.html

[Q54] 清空表
来源：http://dali.shzxlz.cn/Article/details/gtdqgbruhr.html

TRUNCATE TABLE logs;
来源：http://dali.jinghuilouyu.cn/Article/details/gtphzefqpn.html

[Q55] 排名（并列占位）
来源：http://dali.9152youxi.cn/Article/details/gtzzdlnnxv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.andypj.xyz/Article/details/gtogzzansp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shuidangran.top/Article/details/gtuompplxi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hywenlv.cn/Article/details/gtzcbzllgu.html

[Q57] 行号
来源：http://dali.dianchejie.cn/Article/details/gtbbiffwzd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtsrhwmgdr.html

[Q58] 累计求和
来源：http://dali.fzhhl.top/Article/details/gtwmzqdvun.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gttfctfrgb.html

[Q59] 分组内累计
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnorvxkbv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.meibo888.top/Article/details/gtcetbezky.html

[Q60] 取上一行 / 下一行
来源：http://dali.sweek.top/Article/details/gtzoooxvko.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.snrcjt.cn/Article/details/gtfzcutppw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtmrjyoxka.html

[Q61] 移动平均
来源：http://dali.jyoumei.cn/Article/details/gtzfpradzq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hnqzz.top/Article/details/gtjodwfeiy.html

[Q62] 分组占比
来源：http://dali.yueranfly.top/Article/details/gtdwibvmqx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.daxiang520.top/Article/details/gtddthihwf.html

[Q63] 开启事务
来源：http://dali.nanxinkj.top/Article/details/gtnjkstisl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hammf.cn/Article/details/gteybwqwbz.html

[Q64] 提交事务
来源：http://dali.yj20258.top/Article/details/gteshskqbp.html

COMMIT;
来源：http://dali.daria6918.cn/Article/details/gtnjktdfgi.html

[Q65] 回滚事务
来源：http://dali.hnxiangtu.top/Article/details/gtjwarsfbi.html

ROLLBACK;
来源：http://dali.pengpengdd.cyou/Article/details/gtrulswkxu.html

[Q66] 行锁查询
来源：http://dali.tanke756.top/Article/details/gtmwtddfhm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xinyue.icu/Article/details/gtphgaxcsv.html

[Q67] 设置隔离级别
来源：http://dali.yuxming.cn/Article/details/gtegvhtqrn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzvdpwlil.html

[Q68] 保存点
来源：http://dali.zhongyouzk.top/Article/details/gtamcwvwsz.html

SAVEPOINT sp1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgtxmedty.html

ROLLBACK TO sp1;
来源：http://dali.hongshengwenyu.top/Article/details/gtrsyadboa.html

[Q69] 查看执行计划
来源：http://dali.jlsjyb.cn/Article/details/gtryljdyrr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.sysykeji.top/Article/details/gtpgwaodpy.html

[Q70] 更新统计信息
来源：http://dali.316326.xyz/Article/details/gtahfvuwmo.html

ANALYZE TABLE users;
来源：http://dali.daria6918.cn/Article/details/gtxogbodqm.html

[Q71] 查看建表语句
来源：http://dali.hnxiangtu.top/Article/details/gtaiafrzlu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shangyingyoupin.top/Article/details/gtnoszdkrq.html

[Q72] 查看索引
来源：http://dali.hfpthk.cn/Article/details/gtbbccmsuk.html

SHOW INDEX FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtdrlotaph.html

[Q73] 查看表状态
来源：http://dali.cashguo.top/Article/details/gthmvdrpmu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.iojbl.cn/Article/details/gtycqkbwig.html

[Q74] 强制使用索引
来源：http://dali.zhixingplan.top/Article/details/gtkzospwwe.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.nanxinkj.top/Article/details/gtjqjlczqv.html

[Q75] 日期格式化
来源：http://dali.jqgfzy.top/Article/details/gtwxdufmjg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtlucgafnt.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jlsjyb.cn/Article/details/gtwmdahegc.html

[Q76] 按天统计
来源：http://dali.xinyue.icu/Article/details/gtyzuoyuqg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.sufxvd.cn/Article/details/gtxhcpkjym.html

[Q77] 时间加减
来源：http://dali.aibaodan.cn/Article/details/gtxwdonksc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.wangshuangyany.cn/Article/details/gtrwvdbvwo.html

[Q78] 当前时间
来源：http://dali.jinqigfzy.top/Article/details/gtwqgfruze.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.iojbl.cn/Article/details/gtulcsmlcu.html

[Q79] 字符串拼接
来源：http://dali.chenlongwang.top/Article/details/gtoqqnwtbg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shzxlz.cn/Article/details/gtfgoqxxxd.html

[Q80] 字符串截取
来源：http://dali.ydzc1.top/Article/details/gtjlunojde.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.aizwys.cn/Article/details/gtodprqact.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gtyfzdjiok.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ydzc1.top/Article/details/gtcgrnvvdy.html

[Q82] 字符长度与字节长度
来源：http://dali.smart0.xyz/Article/details/gtvxohwpeo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtrgtpdbub.html

[Q83] 大小写转换
来源：http://dali.hysaishi.cn/Article/details/gtihlgbksv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtuvmddtfr.html

[Q84] 去除首尾空格
来源：http://dali.ybcxt.top/Article/details/gtuzvxmnod.html

SELECT TRIM(name) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtbihgemqz.html

[Q85] 数值取整
来源：http://dali.havefunace.top/Article/details/gtzyshwfhz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jianghu66.top/Article/details/gtzmnpaqzw.html

[Q86] 读取 JSON 字段
来源：http://dali.nwbrower.top/Article/details/gtshbrkrmn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.mhx1999.top/Article/details/gtvnqjzvyz.html

[Q87] JSON 字段做条件
来源：http://dali.chenlongwang.top/Article/details/gtkhpyyhpq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.wangdashe.top/Article/details/gtuzvnjqou.html

[Q88] 行转列（条件聚合）
来源：http://dali.hysaishi.cn/Article/details/gtuamptaok.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hongshengwenyu.top/Article/details/gtogbudkww.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yj20258.top/Article/details/gtzfeuztey.html

[Q89] 判断表是否存在
来源：http://dali.zhoulong.xyz/Article/details/gtpvxemsfg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nwbrower.top/Article/details/gtqgyjilyx.html

[Q90] 生成序号列
来源：http://dali.cdnleiting.top/Article/details/gtijlcmsbf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhiwuduotai.top/Article/details/gtcfuslswg.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtfmhabahd.html

R. Bash 专题
来源：http://dali.yanxiufei.cn/Article/details/gtijzujlgl.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtbxclzqkb.html

[R01] shebang 与严格模式
来源：http://dali.hnqzz.top/Article/details/gttlvpaypv.html

#!/usr/bin/env bash
来源：http://dali.xylfe.cn/Article/details/gtieumcmbn.html

set -euo pipefail
来源：http://dali.chenlongwang.top/Article/details/gtelwbthmd.html

[R02] 变量赋值与使用
来源：http://dali.snrcjt.cn/Article/details/gtypkcybis.html

name="Tom"; echo "$name"
来源：http://dali.nanxuanxn.top/Article/details/gtwmhnqqfd.html

[R03] 只读变量
来源：http://dali.snrcjt.cn/Article/details/gtxbkmrsks.html

readonly PI=3.14
来源：http://dali.andypj.xyz/Article/details/gtcrbyjago.html

[R04] 位置参数
来源：http://dali.shzxlz.cn/Article/details/gtypzkulgr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.aizwys.cn/Article/details/gtmrrhjycg.html

[R05] 参数默认值
来源：http://dali.yuxming.cn/Article/details/gtmqjjybrz.html

name="${1:-default}"
来源：http://dali.vqdsnc.cn/Article/details/gteunhomhh.html

[R06] 判断命令是否存在
来源：http://dali.jlsjyb.cn/Article/details/gtnezoozbj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ivvv.top/Article/details/gtvbkfqhik.html

[R07] if 判断文件
来源：http://dali.bjfxy.top/Article/details/gtutewajfx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.316326.xyz/Article/details/gtdfnlodyz.html

[R08] 数值比较
来源：http://dali.guowangkeji.top/Article/details/gtklvpiahy.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yanxiufei.cn/Article/details/gtihvsedvr.html

[R09] 字符串比较
来源：http://dali.yvedp.cn/Article/details/gtuhvbljhw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.quarkkingdee.top/Article/details/gtymrbqodw.html

[R10] 正则匹配
来源：http://dali.sweek.top/Article/details/gtsivpgqwq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ivvv.top/Article/details/gtoxqjlnib.html

[R11] case 多分支
来源：http://dali.wangdashe.top/Article/details/gtrilplgqs.html

case "$1" in
来源：http://dali.nanxinkj.top/Article/details/gtuvgpedoj.html

start) echo "启动" ;;
来源：http://dali.316326.xyz/Article/details/gtaberhota.html

stop)  echo "停止" ;;
来源：http://dali.0kj1m.cn/Article/details/gtioevribj.html

*)     echo "未知命令" ;;
来源：http://dali.dianchejie.cn/Article/details/gtpzsxeznn.html

esac
来源：http://dali.jiagoushi.top/Article/details/gtcefbrdiy.html

[R12] for 遍历文件
来源：http://dali.meibo888.top/Article/details/gtgdblokiw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hywenlv.cn/Article/details/gtybhrbwip.html

[R13] for 计数循环
来源：http://dali.fengsongda.top/Article/details/gtmfytqlkm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.dianchejie.cn/Article/details/gttuuhunyr.html

[R14] C 风格 for
来源：http://dali.daria6918.cn/Article/details/gtmufgpdmc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.aizwys.cn/Article/details/gtwewtemep.html

[R15] while 逐行读文件
来源：http://dali.zycfv.cn/Article/details/gtggbpeooo.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gotoacloud.top/Article/details/gtljjrnxok.html

[R16] until 等待条件
来源：http://dali.yj20258888.top/Article/details/gtgaedykbl.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhongyouzk.top/Article/details/gtbcimqqsp.html

[R17] 数组定义与取值
来源：http://dali.gzhubu.top/Article/details/gtwgltfxbr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hongshengwenyu.top/Article/details/gtrensehbp.html

[R18] 遍历数组
来源：http://dali.ivvv.top/Article/details/gtkfixidjl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.tian-w.cn/Article/details/gtqlzibjtc.html

[R19] 数组长度
来源：http://dali.ehwqpu.com/Article/details/gtmqawodmr.html

echo "${#arr[@]}"
来源：http://dali.gzhubu.top/Article/details/gtircjfvdj.html

[R20] 关联数组（字典）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkwtirxae.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.gogol.net.cn/Article/details/gtelftwfbq.html

[R21] 字符串长度
来源：http://dali.jinqigfzy.top/Article/details/gtbvnjginu.html

echo "${#s}"
来源：http://dali.dashuyun.cn/Article/details/gtrgggiyko.html

[R22] 截取子串
来源：http://dali.tianlin.xyz/Article/details/gtwnwyffdh.html

echo "${s:0:5}"
来源：http://dali.chenzaomai.com/Article/details/gtcnojgttd.html

[R23] 字符串替换
来源：http://dali.meibo888.top/Article/details/gtyxzoghpc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.tanke756.top/Article/details/gtmfnokoon.html

[R24] 大小写转换
来源：http://dali.wangshuangyany.cn/Article/details/gtbyuymyob.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shuidangran.top/Article/details/gtvwutynnp.html

[R25] 去后缀 / 去前缀
来源：http://dali.yueranfly.top/Article/details/gtjdvpeovq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtcitmcdho.html

[R26] 命令替换
来源：http://dali.wangshuangyany.cn/Article/details/gtrlqovrci.html

now=$(date +%F); echo "$now"
来源：http://dali.jinqigufen.top/Article/details/gttqwhfooq.html

[R27] 算术展开
来源：http://dali.sxryk.cn/Article/details/gtzxpokxkk.html

echo $((1 + 2 * 3))
来源：http://dali.zhongyouzk.top/Article/details/gttqiunqkz.html

[R28] 浮点运算
来源：http://dali.jlsjyb.cn/Article/details/gtyndblqqw.html

echo "scale=2; 10/3" | bc
来源：http://dali.sxryk.cn/Article/details/gtlrnfadan.html

[R29] 定义函数
来源：http://dali.svipenyu.cn/Article/details/gtlzuwitkr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.daria6918.cn/Article/details/gtxegpwneu.html

[R30] 函数返回状态码
来源：http://dali.nanxuanxn.top/Article/details/gtanfzieec.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.svipenyu.cn/Article/details/gtfcdiwzmy.html

[R31] 局部变量
来源：http://dali.fengsongda.top/Article/details/gtkvikohez.html

f() { local x=1; echo "$x"; }
来源：http://dali.hammf.cn/Article/details/gtbofedoka.html

[R32] 参数个数校验
来源：http://dali.jianghu66.top/Article/details/gtrwpmmjci.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.dashuyun.cn/Article/details/gtpvrogboa.html

[R33] 捕获错误并提示行号
来源：http://dali.fzhhl.top/Article/details/gtmpavgqot.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shangyingyoupin.top/Article/details/gtgaaizwkz.html

[R34] 退出时清理
来源：http://dali.sweek.top/Article/details/gtlamyncbh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jlsjyb.cn/Article/details/gtrhionsje.html

[R35] 后台执行并等待
来源：http://dali.quarkkingdee.top/Article/details/gtyjkludcv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hysaishi.cn/Article/details/gtgskacthw.html

[R36] 并发执行多个任务
来源：http://dali.gzhubu.top/Article/details/gtnrlmdrgi.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.sysykeji.top/Article/details/gtjmbnfazq.html

[R37] 把输出赋给变量
来源：http://dali.jinqigufen.top/Article/details/gtaiqssays.html

files=$(ls -1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttlbnkdgi.html

[R38] 管道串联
来源：http://dali.wangshuangyany.cn/Article/details/gtddyebpyx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gogol.net.cn/Article/details/gtbmopjzuh.html

[R39] 重定向标准输出与错误
来源：http://dali.jlsjyb.cn/Article/details/gtwjpibtqk.html

cmd > out.log 2>&1
来源：http://dali.dashuyun.cn/Article/details/gtyluozpfn.html

[R40] 追加写日志
来源：http://dali.shangyingyoupin.top/Article/details/gtplvreihf.html

echo "log" >> out.log
来源：http://dali.daxiang520.top/Article/details/gtamlqjebj.html

[R41] 丢弃输出
来源：http://dali.nwbrower.top/Article/details/gtxwulcggp.html

cmd >/dev/null 2>&1
来源：http://dali.zhoulong.xyz/Article/details/gtnwvukdsn.html

[R42] 输入重定向
来源：http://dali.hywenlv.cn/Article/details/gtwnbgksmy.html

wc -l < a.txt
来源：http://dali.ppjwa.cn/Article/details/gtncnumbmb.html

[R43] 按名字查找文件
来源：http://dali.gaohongyu789.top/Article/details/gtpbrzuykv.html

find . -name "*.log" -type f
来源：http://dali.hnqzz.top/Article/details/gtddcpunxm.html

[R44] 按修改时间查找
来源：http://dali.mhx1999.top/Article/details/gtwuvleskv.html

find . -mtime -7 -type f
来源：http://dali.jianghu66.top/Article/details/gtncaxrbpf.html

[R45] 批量删除
来源：http://dali.guannengcc.top/Article/details/gtejnrwcdy.html

find . -name "*.tmp" -delete
来源：http://dali.shzxlz.cn/Article/details/gtwznopgaa.html

[R46] 递归替换文件内容
来源：http://dali.hnqzz.top/Article/details/gtdfvwghkd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.chenjidiqi.icu/Article/details/gtnotljtht.html

[R47] sed 单行替换
来源：http://dali.tian-w.cn/Article/details/gtnrrdajyl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.nanxuanxn.top/Article/details/gtsvthnfwq.html

[R48] awk 取指定列
来源：http://dali.wangdashe.top/Article/details/gtxutetvaj.html

awk '{print $1, $3}' a.txt
来源：http://dali.0kj1m.cn/Article/details/gtkcqgxczy.html

[R49] awk 带条件
来源：http://dali.pengpengdd.cyou/Article/details/gtmkklvrij.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.wangshuangyany.cn/Article/details/gtcmipjgah.html

[R50] awk 求和
来源：http://dali.dashuyun.cn/Article/details/gtlykcabea.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jqgufenzy.top/Article/details/gthyuzxijc.html

[R51] 排序去重取前几
来源：http://dali.havefunace.top/Article/details/gtkvlmupcv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.aizwys.cn/Article/details/gtxwjatygr.html

[R52] 统计行数
来源：http://dali.ydzc1.top/Article/details/gtzvxodydu.html

wc -l a.txt
来源：http://dali.nanxinkj.top/Article/details/gtlfrxgfjj.html

[R53] 查看文件头与实时尾
来源：http://dali.jiagoushi.top/Article/details/gtbvpeeyru.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinqigfzy.top/Article/details/gtwteoehwf.html

[R54] 比较两个文件
来源：http://dali.dianchejie.cn/Article/details/gtxtjynlvl.html

diff a.txt b.txt
来源：http://dali.iojbl.cn/Article/details/gtmuqhitvg.html

[R55] 压缩与解压
来源：http://dali.c1oappe.top/Article/details/gtclfhbypi.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xinyue.icu/Article/details/gtoklzzfja.html

[R56] 远程拷贝
来源：http://dali.quarkkingdee.top/Article/details/gtatixsceo.html

scp file user@host:/path/
来源：http://dali.gaohongyu789.top/Article/details/gtvydysdbh.html

[R57] 远程执行命令
来源：http://dali.ybcxt.top/Article/details/gtbcnugcjt.html

ssh user@host 'uptime'
来源：http://dali.c1oappe.top/Article/details/gtjtupsntx.html

[R58] 下载文件
来源：http://dali.jiagoushi.top/Article/details/gtvmnbmjof.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.snrcjt.cn/Article/details/gtcelnrfky.html

[R59] 发 POST JSON
来源：http://dali.yuanzhike.top/Article/details/gtuhdhsdcb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.pycfn.com/Article/details/gthelzyzgz.html

[R60] 只看 HTTP 状态码
来源：http://dali.nwbrower.top/Article/details/gtqlsdhcoq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.chenlongwang.top/Article/details/gtchpoppzh.html

[R61] 磁盘占用
来源：http://dali.hfpthk.cn/Article/details/gtbyfsnssu.html

df -h;  du -sh *
来源：http://dali.yanxiufei.cn/Article/details/gtmmztzvbu.html

[R62] 找最占空间的文件
来源：http://dali.9152youxi.cn/Article/details/gtwzliyxgj.html

du -ah . | sort -rh | head -10
来源：http://dali.tianlin.xyz/Article/details/gtdypbiggs.html

[R63] 内存与进程
来源：http://dali.chenlongwang.top/Article/details/gtbjawvwni.html

free -h;  ps aux | grep nginx
来源：http://dali.yvedp.cn/Article/details/gtmcuvvbot.html

[R64] 结束进程
来源：http://dali.shzxlz.cn/Article/details/gtqhoraxpl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.meibo888.top/Article/details/gtgfwhmbjx.html

[R65] 查看端口占用
来源：http://dali.shzxlz.cn/Article/details/gtsekurcil.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yonumen.top/Article/details/gtzohxhkwz.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gtxekbtolt.html

crontab -e;  crontab -l
来源：http://dali.daria6918.cn/Article/details/gtqhvpgohw.html

[R67] 生成随机十六进制串
来源：http://dali.cheryme.top/Article/details/gtlivrvucp.html

openssl rand -hex 16
来源：http://dali.nanxinkj.top/Article/details/gtllgzclnq.html

[R68] 计算文件校验值
来源：http://dali.jqgufenzy.top/Article/details/gttlxtfcqs.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yueranfly.top/Article/details/gtyvtcuugw.html

[R69] 生成随机密码
来源：http://dali.shangyingyoupin.top/Article/details/gtbyuxritl.html

head -c 16 /dev/urandom | base64
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrfqdbhdp.html

[R70] 时间戳与互转
来源：http://dali.zhixingplan.top/Article/details/gtkqidtjce.html

date +%s;  date -d @1700000000
来源：http://dali.gotoacloud.top/Article/details/gthwiliuda.html

[R71] 日期格式化
来源：http://dali.yongpay.top/Article/details/gtidphbgyw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xuetiantiany.cn/Article/details/gtoptfqmeg.html

[R72] 等待端口就绪
来源：http://dali.zycfv.cn/Article/details/gturprgsoi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinqigfzy.top/Article/details/gtobjqzlxm.html

[R73] 分割大日志
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsxlivtwj.html


<!-- 参考信息 -->