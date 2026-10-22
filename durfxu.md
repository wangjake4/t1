代发 wailian999

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.meibo888.top/Article/details/gtqtboifoj.html

[Q24] 去重
来源：http://dali.andypj.xyz/Article/details/gtczpcuhbe.html

SELECT DISTINCT city FROM users;
来源：http://dali.ybcxt.top/Article/details/gtumlfbcwp.html

[Q25] 只取前 N 条
来源：http://dali.yonumen.top/Article/details/gtkoxmfitm.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.chenlongwang.top/Article/details/gtapaogakq.html

[Q26] 计数
来源：http://dali.shangyingyoupin.top/Article/details/gtirodqgpn.html

SELECT COUNT(*) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtciuonocx.html

[Q27] 条件计数
来源：http://dali.sufxvd.cn/Article/details/gtsfyovzhi.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtzqdxiwgn.html

[Q28] 求和与平均
来源：http://dali.hongshengwenyu.top/Article/details/gthzzokmil.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtnxxldfyj.html

[Q29] 最大最小值
来源：http://dali.cqqwz.cn/Article/details/gtbfkorxrb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jianghu66.top/Article/details/gtjcdqxvrc.html

[Q30] 分组统计
来源：http://dali.cashguo.top/Article/details/gtrzwikbiv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhiwuduotai.top/Article/details/gtqlspkndv.html

[Q31] 分组后过滤
来源：http://dali.xuanzx.com/Article/details/gtzbsaxlon.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvegolunp.html

[Q32] 分组拼接字符串
来源：http://dali.zycfv.cn/Article/details/gtckrzrzsh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jinghuilouyu.cn/Article/details/gtksppszie.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.vqdsnc.cn/Article/details/gtldbdeezq.html

[Q33] 多列分组
来源：http://dali.redwolf501.top/Article/details/gtuqzebjws.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jqgufenzy.top/Article/details/gtxxxmqswg.html

[Q34] 每组取第一条
来源：http://dali.gaohongyu789.top/Article/details/gtxhipfpeo.html

SELECT * FROM (
来源：http://dali.chenjidiqi.icu/Article/details/gtucbwknag.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ehwqpu.com/Article/details/gtkiiygfgm.html

) t WHERE rn = 1;
来源：http://dali.jiagoushi.top/Article/details/gtlnbhtkwl.html

[Q35] 内连接
来源：http://dali.kuanghao11.cn/Article/details/gtgkmcdcwg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ydzc1.top/Article/details/gtwwuiexmr.html

[Q36] 左连接
来源：http://dali.ivvv.top/Article/details/gtrmrfekwh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.c1oappe.top/Article/details/gtugomvgeg.html

[Q37] 右连接
来源：http://dali.c1oappe.top/Article/details/gturpxducb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yanxiufei.cn/Article/details/gtfprgffeh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.smart0.xyz/Article/details/gtiozcrdpk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.pengpengdd.cyou/Article/details/gtfoarrgec.html

[Q39] 自连接（查上下级）
来源：http://dali.yongpay.top/Article/details/gtszcwqfau.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.aibaodan.cn/Article/details/gtsyzcirvn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.redwolf501.top/Article/details/gtbcknlsmd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.kuanghao11.cn/Article/details/gttwdhseim.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.quarkkingdee.top/Article/details/gtnzzkggae.html

[Q41] 多表连接
来源：http://dali.yj202588.top/Article/details/gtmiuentqn.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sufxvd.cn/Article/details/gtajbyraqb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ivvv.top/Article/details/gtzxqhdytp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jqgfzy.top/Article/details/gtwhwxooyu.html

[Q42] 连接条件附加过滤
来源：http://dali.gzhubu.top/Article/details/gtsjfbskra.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhengqikj.top/Article/details/gtekvudeow.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yangfankeji.com/Article/details/gtkpbwymjp.html

[Q43] 标量子查询
来源：http://dali.hysaishi.cn/Article/details/gtxdtrnkxd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xylfe.cn/Article/details/gtuicuqpel.html

[Q44] IN 子查询
来源：http://dali.ivvv.top/Article/details/gttotqwiye.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.guowangkeji.top/Article/details/gtsahdzlza.html

[Q45] EXISTS 判断存在
来源：http://dali.vqdsnc.cn/Article/details/gtotwpmnbg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.guannengcc.top/Article/details/gtykccazyz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shuidangran.top/Article/details/gtdxlnzmlh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shuidangran.top/Article/details/gtakjjelkl.html

[Q47] 与平均值比较
来源：http://dali.ydzc1.top/Article/details/gtssnfkfbc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.chenjidiqi.icu/Article/details/gtoxigymvm.html

[Q48] CTE 公用表表达式
来源：http://dali.cdnleiting.top/Article/details/gtagrjnkaa.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.fengsongda.top/Article/details/gtrloqqdfd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gtxlghyguk.html

[Q49] 更新单行
来源：http://dali.pengpengdd.cyou/Article/details/gttstjdptl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.nanxuanxn.top/Article/details/gtrxsouqci.html

[Q50] 批量更新
来源：http://dali.ybcxt.top/Article/details/gticmsoesf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yuxming.cn/Article/details/gtvpzvyvvz.html

[Q51] 用子查询更新
来源：http://dali.daxiang520.top/Article/details/gteppzzhof.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sufxvd.cn/Article/details/gtbwxjjmmv.html

[Q52] 删除指定行
来源：http://dali.gotoacloud.top/Article/details/gtgrbhgjzv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jiagoushi.top/Article/details/gtnnrxkjdw.html

[Q53] 按条件删除
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvivarduz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinqigfzy.top/Article/details/gtobjvxugm.html

[Q54] 清空表
来源：http://dali.chenlongwang.top/Article/details/gtcbnshbmb.html

TRUNCATE TABLE logs;
来源：http://dali.mhx1999.top/Article/details/gtgdkdjwft.html

[Q55] 排名（并列占位）
来源：http://dali.mhx1999.top/Article/details/gtvkocejxz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.nanxinkj.top/Article/details/gtwxidzyzi.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yj202588.top/Article/details/gtsjlpeaiq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.sxryk.cn/Article/details/gtbkkekppl.html

[Q57] 行号
来源：http://dali.hysaishi.cn/Article/details/gtmyarhemn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtczudebzp.html

[Q58] 累计求和
来源：http://dali.jinqigfzy.top/Article/details/gtougrowuj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtrfkklrpd.html

[Q59] 分组内累计
来源：http://dali.sufxvd.cn/Article/details/gtoqxyhphu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gtamzukted.html

[Q60] 取上一行 / 下一行
来源：http://dali.sweek.top/Article/details/gtttyiceih.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yuxming.cn/Article/details/gtmxrqbisd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.daxiang520.top/Article/details/gttryxoedi.html

[Q61] 移动平均
来源：http://dali.zhongyouzk.top/Article/details/gtpvmfujle.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gtzywzeemi.html

[Q62] 分组占比
来源：http://dali.yangfankeji.com/Article/details/gtrzhkqycx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jyoumei.cn/Article/details/gtpiynyvbw.html

[Q63] 开启事务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdlquhibg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yj20258.top/Article/details/gtfxqztive.html

[Q64] 提交事务
来源：http://dali.hnxiangtu.top/Article/details/gthskhtrjx.html

COMMIT;
来源：http://dali.cdnleiting.top/Article/details/gtblmkmksi.html

[Q65] 回滚事务
来源：http://dali.yonumen.top/Article/details/gtkqnyavme.html

ROLLBACK;
来源：http://dali.jlsjyb.cn/Article/details/gtavxqdggr.html

[Q66] 行锁查询
来源：http://dali.yj202588.top/Article/details/gtwlrimzcd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.fzhhl.top/Article/details/gtenxlxtql.html

[Q67] 设置隔离级别
来源：http://dali.andypj.xyz/Article/details/gtxhqcstlo.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.pengpengdd.cyou/Article/details/gthojrlbrq.html

[Q68] 保存点
来源：http://dali.jinqigfzy.top/Article/details/gtdnbgxlfu.html

SAVEPOINT sp1;
来源：http://dali.smart0.xyz/Article/details/gthsdmzmtc.html

ROLLBACK TO sp1;
来源：http://dali.hysaishi.cn/Article/details/gtzyacmlgh.html

[Q69] 查看执行计划
来源：http://dali.hysaishi.cn/Article/details/gtiowswlft.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.wangshuangyany.cn/Article/details/gtoozgjjlc.html

[Q70] 更新统计信息
来源：http://dali.chenjidiqi.icu/Article/details/gtqmxzxkav.html

ANALYZE TABLE users;
来源：http://dali.chenjidiqi.icu/Article/details/gtkbnnrzqj.html

[Q71] 查看建表语句
来源：http://dali.tanke756.top/Article/details/gtyupozmws.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hysaishi.cn/Article/details/gtulsuyein.html

[Q72] 查看索引
来源：http://dali.zhixingplan.top/Article/details/gtmscijrht.html

SHOW INDEX FROM users;
来源：http://dali.yueranfly.top/Article/details/gtzsefdiib.html

[Q73] 查看表状态
来源：http://dali.cucudq.cn/Article/details/gtrimdmnmr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shanyushiyangkeji.top/Article/details/gtscshktsb.html

[Q74] 强制使用索引
来源：http://dali.zhoulong.xyz/Article/details/gtaaavbrlu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yongpay.top/Article/details/gtpluzezrj.html

[Q75] 日期格式化
来源：http://dali.tian-w.cn/Article/details/gtxqbmpdna.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gtmlxmhjow.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.iojbl.cn/Article/details/gtfnvdvdsk.html

[Q76] 按天统计
来源：http://dali.xuetiantiany.cn/Article/details/gtizetynyp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xziqi.cn/Article/details/gtktnyrjmu.html

[Q77] 时间加减
来源：http://dali.tianlin.xyz/Article/details/gtxptfpgeu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.guannengcc.top/Article/details/gtfllntnxx.html

[Q78] 当前时间
来源：http://dali.316326.xyz/Article/details/gtnqmiuhar.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shuidangran.top/Article/details/gthpyzwlib.html

[Q79] 字符串拼接
来源：http://dali.nwbrower.top/Article/details/gtbutbsysq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.chenlongwang.top/Article/details/gtvdgfywtw.html

[Q80] 字符串截取
来源：http://dali.aibaodan.cn/Article/details/gtpgcqrnea.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtzmqwmjuu.html

[Q81] 字符串替换
来源：http://dali.shuidangran.top/Article/details/gtrrebsdcu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.pycfn.com/Article/details/gtvfbnvulj.html

[Q82] 字符长度与字节长度
来源：http://dali.xuanzx.com/Article/details/gtvgqlretk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtkqsiaafw.html

[Q83] 大小写转换
来源：http://dali.jinqigufen.top/Article/details/gtheinurxw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.birdmap.top/Article/details/gtvmsqdefz.html

[Q84] 去除首尾空格
来源：http://dali.yj20258888.top/Article/details/gtvvbumrcd.html

SELECT TRIM(name) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtukimtzom.html

[Q85] 数值取整
来源：http://dali.yj202588.top/Article/details/gtbrsvonir.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.0kj1m.cn/Article/details/gtesufxxyj.html

[Q86] 读取 JSON 字段
来源：http://dali.meibo888.top/Article/details/gthflajejs.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yangfankeji.com/Article/details/gtptxihsve.html

[Q87] JSON 字段做条件
来源：http://dali.andypj.xyz/Article/details/gtbtdpbfkt.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.tian-w.cn/Article/details/gtnzovaszi.html

[Q88] 行转列（条件聚合）
来源：http://dali.yueranfly.top/Article/details/gtbcleyyxd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gzhubu.top/Article/details/gtzcvafyhk.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hammf.cn/Article/details/gtploptfvf.html

[Q89] 判断表是否存在
来源：http://dali.smart0.xyz/Article/details/gtlulzydzo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.tianlin.xyz/Article/details/gtigpwruun.html

[Q90] 生成序号列
来源：http://dali.birdmap.top/Article/details/gtvztevhbf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdbodqylf.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtcdshsqbi.html

R. Bash 专题
来源：http://dali.jqgfzy.top/Article/details/gtgkjdxgqg.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtzyspygta.html

[R01] shebang 与严格模式
来源：http://dali.chenzaomai.com/Article/details/gtqnbubktt.html

#!/usr/bin/env bash
来源：http://dali.sufxvd.cn/Article/details/gtntinlhdx.html

set -euo pipefail
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnekknrqs.html

[R02] 变量赋值与使用
来源：http://dali.zhiwuduotai.top/Article/details/gtjkttvyvc.html

name="Tom"; echo "$name"
来源：http://dali.9152youxi.cn/Article/details/gtzluhlkkl.html

[R03] 只读变量
来源：http://dali.mhx1999.top/Article/details/gtrzownamy.html

readonly PI=3.14
来源：http://dali.ppjwa.cn/Article/details/gtuupefabz.html

[R04] 位置参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtxnexismd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jlsjyb.cn/Article/details/gtiswsvfve.html

[R05] 参数默认值
来源：http://dali.shanyushiyangtech.top/Article/details/gttjqeklpj.html

name="${1:-default}"
来源：http://dali.shzxlz.cn/Article/details/gtdufdnrfb.html

[R06] 判断命令是否存在
来源：http://dali.bjfxy.top/Article/details/gtjkudlzxy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cqqwz.cn/Article/details/gtshizykfd.html

[R07] if 判断文件
来源：http://dali.quarkkingdee.top/Article/details/gtbjkftzro.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xziqi.cn/Article/details/gtodrqilci.html

[R08] 数值比较
来源：http://dali.yvedp.cn/Article/details/gtrqjuyvlu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhoulong.xyz/Article/details/gtqjiicxya.html

[R09] 字符串比较
来源：http://dali.pengpengdd.cyou/Article/details/gtvgnmzzrx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yanxiufei.cn/Article/details/gtyrrpwndf.html

[R10] 正则匹配
来源：http://dali.nwbrower.top/Article/details/gthvpzknmj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.chenlongwang.top/Article/details/gtsemqppyo.html

[R11] case 多分支
来源：http://dali.shzxlz.cn/Article/details/gthbyqgofu.html

case "$1" in
来源：http://dali.9152youxi.cn/Article/details/gtshdgsemg.html

start) echo "启动" ;;
来源：http://dali.feifeiyinyue.top/Article/details/gtlikebnek.html

stop)  echo "停止" ;;
来源：http://dali.xuetiantiany.cn/Article/details/gteczqfgwj.html

*)     echo "未知命令" ;;
来源：http://dali.yuanzhike.top/Article/details/gtangdtkgc.html

esac
来源：http://dali.hysaishi.cn/Article/details/gtqmwtkoww.html

[R12] for 遍历文件
来源：http://dali.yj20258888.top/Article/details/gtaootztjj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtlyhnwkiv.html

[R13] for 计数循环
来源：http://dali.aibaodan.cn/Article/details/gtsdsnrbgo.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.daria6918.cn/Article/details/gtpjxtgghr.html

[R14] C 风格 for
来源：http://dali.haohaochexian.top/Article/details/gtyoywymlg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.pengpengdd.cyou/Article/details/gthvwaerar.html

[R15] while 逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gtjnjqhgpm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sxryk.cn/Article/details/gthvgfsjgu.html

[R16] until 等待条件
来源：http://dali.guowangkeji.top/Article/details/gtcsruzdzn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj20258888.top/Article/details/gtibqvtjpm.html

[R17] 数组定义与取值
来源：http://dali.pengpengdd.cyou/Article/details/gtdlgcumnq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cheryme.top/Article/details/gtecswgijz.html

[R18] 遍历数组
来源：http://dali.redwolf501.top/Article/details/gtckbwycbl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkzrlmyii.html

[R19] 数组长度
来源：http://dali.nanxinkj.top/Article/details/gtsdxphsqd.html

echo "${#arr[@]}"
来源：http://dali.zhoulong.xyz/Article/details/gtynfqtlqg.html

[R20] 关联数组（字典）
来源：http://dali.cashguo.top/Article/details/gtdtphpquc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jianghu66.top/Article/details/gtedsnspzj.html

[R21] 字符串长度
来源：http://dali.bjfxy.top/Article/details/gtobqellwh.html

echo "${#s}"
来源：http://dali.ivvv.top/Article/details/gtqxbouyul.html

[R22] 截取子串
来源：http://dali.zhengqikj.top/Article/details/gtiljttple.html

echo "${s:0:5}"
来源：http://dali.nanxinkj.top/Article/details/gtgfvwnmht.html

[R23] 字符串替换
来源：http://dali.sweek.top/Article/details/gtgugfsyxh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jqgufenzy.top/Article/details/gtevxlrlmj.html

[R24] 大小写转换
来源：http://dali.316326.xyz/Article/details/gtmzpuqalu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yuanzhike.top/Article/details/gtiqyndcrn.html

[R25] 去后缀 / 去前缀
来源：http://dali.yangfankeji.com/Article/details/gtvuqxhzpe.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xylfe.cn/Article/details/gthvzmelej.html

[R26] 命令替换
来源：http://dali.yuanzhike.top/Article/details/gtrcjlrdir.html

now=$(date +%F); echo "$now"
来源：http://dali.fzhhl.top/Article/details/gthwvzbmpg.html

[R27] 算术展开
来源：http://dali.ywan-chungtsiang.top/Article/details/gtznawzbzk.html

echo $((1 + 2 * 3))
来源：http://dali.guannengcc.top/Article/details/gtigxcjvsq.html

[R28] 浮点运算
来源：http://dali.fengsongda.top/Article/details/gtxnbqxirx.html

echo "scale=2; 10/3" | bc
来源：http://dali.pengpengdd.cyou/Article/details/gtyiyzgjjw.html

[R29] 定义函数
来源：http://dali.dashuyun.cn/Article/details/gtoogqpjlm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.dianchejie.cn/Article/details/gtsqyyyxti.html

[R30] 函数返回状态码
来源：http://dali.ydzc1.top/Article/details/gtziwvwomg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.bjfxy.top/Article/details/gtcbbqdwqq.html

[R31] 局部变量
来源：http://dali.mhx1999.top/Article/details/gtxbhtoxvo.html

f() { local x=1; echo "$x"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gthzoxdeth.html

[R32] 参数个数校验
来源：http://dali.iojbl.cn/Article/details/gtbeoblyjp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gtsgknmdox.html

[R33] 捕获错误并提示行号
来源：http://dali.hongshengwenyu.top/Article/details/gtlhokqkxs.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.kuanghao11.cn/Article/details/gtymxkxgxm.html

[R34] 退出时清理
来源：http://dali.zhengqikj.top/Article/details/gtifucwvvb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.dashuyun.cn/Article/details/gtamshungk.html

[R35] 后台执行并等待
来源：http://dali.c1oappe.top/Article/details/gtpilwdxrc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinqigufen.top/Article/details/gtmndgslqc.html

[R36] 并发执行多个任务
来源：http://dali.sysykeji.top/Article/details/gtlgllasnu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.svipenyu.cn/Article/details/gthmlzigvd.html

[R37] 把输出赋给变量
来源：http://dali.zdqjudy.top/Article/details/gtuvfdolqm.html

files=$(ls -1)
来源：http://dali.gotoacloud.top/Article/details/gtvpxvngtb.html

[R38] 管道串联
来源：http://dali.yangfankeji.com/Article/details/gtrarxopga.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xziqi.cn/Article/details/gtglbwbpwb.html

[R39] 重定向标准输出与错误
来源：http://dali.9152youxi.cn/Article/details/gtlziujgbk.html

cmd > out.log 2>&1
来源：http://dali.yongpay.top/Article/details/gtakwrxlcq.html

[R40] 追加写日志
来源：http://dali.tanke756.top/Article/details/gtdhnhykry.html

echo "log" >> out.log
来源：http://dali.tian-w.cn/Article/details/gtnumlkeoq.html

[R41] 丢弃输出
来源：http://dali.jinghuilouyu.cn/Article/details/gtcmvnaqhr.html

cmd >/dev/null 2>&1
来源：http://dali.ydzc1.top/Article/details/gtxpnsztuc.html

[R42] 输入重定向
来源：http://dali.c1oappe.top/Article/details/gtledvxruu.html

wc -l < a.txt
来源：http://dali.gzhubu.top/Article/details/gttveiiaku.html

[R43] 按名字查找文件
来源：http://dali.iojbl.cn/Article/details/gtfgbmxvib.html

find . -name "*.log" -type f
来源：http://dali.jianghu66.top/Article/details/gtspbjnlqx.html

[R44] 按修改时间查找
来源：http://dali.fengsongda.top/Article/details/gtqqreceaj.html

find . -mtime -7 -type f
来源：http://dali.jinqigufen.top/Article/details/gtuaabuigr.html

[R45] 批量删除
来源：http://dali.xylfe.cn/Article/details/gtaezfnaml.html

find . -name "*.tmp" -delete
来源：http://dali.nanxuanxn.top/Article/details/gtpehwhhij.html

[R46] 递归替换文件内容
来源：http://dali.zhixingplan.top/Article/details/gtegynvvjr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.tanke756.top/Article/details/gthgolexzv.html

[R47] sed 单行替换
来源：http://dali.cashguo.top/Article/details/gtvaxknwmz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.iojbl.cn/Article/details/gtxbxdpqof.html

[R48] awk 取指定列
来源：http://dali.smart0.xyz/Article/details/gtdtviqfhr.html

awk '{print $1, $3}' a.txt
来源：http://dali.gzhubu.top/Article/details/gtoptpqdux.html

[R49] awk 带条件
来源：http://dali.nanxinkj.top/Article/details/gtnrkkcsto.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.vqdsnc.cn/Article/details/gtasomffod.html

[R50] awk 求和
来源：http://dali.hammf.cn/Article/details/gtrgowiiqx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.pycfn.com/Article/details/gtirybuslj.html

[R51] 排序去重取前几
来源：http://dali.ybcxt.top/Article/details/gtvmnxsgkx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.dianchejie.cn/Article/details/gtulyeyunm.html

[R52] 统计行数
来源：http://dali.zhoulong.xyz/Article/details/gtmftiejki.html

wc -l a.txt
来源：http://dali.yonumen.top/Article/details/gthnlbvawr.html

[R53] 查看文件头与实时尾
来源：http://dali.nwbrower.top/Article/details/gtdvdwnfij.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.nwbrower.top/Article/details/gtscdbpkrd.html

[R54] 比较两个文件
来源：http://dali.shangyingyoupin.top/Article/details/gtgcnkqxsv.html

diff a.txt b.txt
来源：http://dali.feifeiyinyue.top/Article/details/gttlqwuyyl.html

[R55] 压缩与解压
来源：http://dali.jinqigfzy.top/Article/details/gtupnmpamm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.c1oappe.top/Article/details/gtmdqjfdpb.html

[R56] 远程拷贝
来源：http://dali.bjfxy.top/Article/details/gtmgxnpcvf.html

scp file user@host:/path/
来源：http://dali.dianchejie.cn/Article/details/gtnsvukcqt.html

[R57] 远程执行命令
来源：http://dali.cqqwz.cn/Article/details/gtugvfhbln.html

ssh user@host 'uptime'
来源：http://dali.bjfxy.top/Article/details/gtjspnceag.html

[R58] 下载文件
来源：http://dali.cdnleiting.top/Article/details/gtwfcrfiju.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.bjfxy.top/Article/details/gtctaatbeh.html

[R59] 发 POST JSON
来源：http://dali.iojbl.cn/Article/details/gtdssdqvlx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.aibaodan.cn/Article/details/gtrnjuysgt.html

[R60] 只看 HTTP 状态码
来源：http://dali.haohaochexian.top/Article/details/gttjcjwqov.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hnxiangtu.top/Article/details/gtkpdnvxiy.html

[R61] 磁盘占用
来源：http://dali.bjfxy.top/Article/details/gtjajikbpx.html

df -h;  du -sh *
来源：http://dali.smart0.xyz/Article/details/gtskseiegg.html

[R62] 找最占空间的文件
来源：http://dali.xylfe.cn/Article/details/gtabiohslo.html

du -ah . | sort -rh | head -10
来源：http://dali.yuxming.cn/Article/details/gtaiypiwvz.html

[R63] 内存与进程
来源：http://dali.shangyingyoupin.top/Article/details/gtjylqaiwl.html

free -h;  ps aux | grep nginx
来源：http://dali.xziqi.cn/Article/details/gtixukjuwa.html

[R64] 结束进程
来源：http://dali.birdmap.top/Article/details/gtaczyzxsk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.tian-w.cn/Article/details/gtpjdjxwqc.html

[R65] 查看端口占用
来源：http://dali.kuanghao11.cn/Article/details/gttpsmsyyq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sxryk.cn/Article/details/gtuwchupdt.html

[R66] 定时任务
来源：http://dali.yj20258.top/Article/details/gtdtjqsxsr.html

crontab -e;  crontab -l
来源：http://dali.ybcxt.top/Article/details/gtdtcgsrmy.html

[R67] 生成随机十六进制串
来源：http://dali.hnxiangtu.top/Article/details/gtcaouycnk.html

openssl rand -hex 16
来源：http://dali.sxryk.cn/Article/details/gthiciieaa.html

[R68] 计算文件校验值
来源：http://dali.dashuyun.cn/Article/details/gttkinnjif.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sxryk.cn/Article/details/gtbnlihyqf.html

[R69] 生成随机密码
来源：http://dali.xuetiantiany.cn/Article/details/gtutblfokx.html

head -c 16 /dev/urandom | base64
来源：http://dali.sysykeji.top/Article/details/gtsskbhqpa.html

[R70] 时间戳与互转
来源：http://dali.0kj1m.cn/Article/details/gtluvnafwi.html

date +%s;  date -d @1700000000
来源：http://dali.cheryme.top/Article/details/gtmmewsftv.html

[R71] 日期格式化
来源：http://dali.birdmap.top/Article/details/gtmmzqubdq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jianghu66.top/Article/details/gtbuixzgni.html

[R72] 等待端口就绪
来源：http://dali.andypj.xyz/Article/details/gtlmzmirfs.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.vqdsnc.cn/Article/details/gtopkocpsy.html

[R73] 分割大日志
来源：http://dali.yvedp.cn/Article/details/gtzxrpgnrl.html


<!-- 参考信息 -->