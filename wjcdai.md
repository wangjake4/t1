代发 wailian999

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2ejhjtgzc.html

[Q28] 求和与平均
来源：http://dali.hnxiangtu.top/Article/details/gt2najvxtwl.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gt2snhiepqr.html

[Q29] 最大最小值
来源：http://dali.yj20258.top/Article/details/gt2pzewmtiw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jianghu66.top/Article/details/gt2oewncnoh.html

[Q30] 分组统计
来源：http://dali.cdnleiting.top/Article/details/gt2wraqkpmf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zycfv.cn/Article/details/gt2idvlyivw.html

[Q31] 分组后过滤
来源：http://dali.zhixingplan.top/Article/details/gt2rwtwnkow.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.fzhhl.top/Article/details/gt2zmacjclc.html

[Q32] 分组拼接字符串
来源：http://dali.guowangkeji.top/Article/details/gt2yfoloyst.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xinyue.icu/Article/details/gt2pwfnxsah.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.shzxlz.cn/Article/details/gt2oyakszzw.html

[Q33] 多列分组
来源：http://dali.chenzaomai.com/Article/details/gt2cumswqgz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.c1oappe.top/Article/details/gt2qidempqh.html

[Q34] 每组取第一条
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kbuttvll.html

SELECT * FROM (
来源：http://dali.yuanzhike.top/Article/details/gt2ybxvxirw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.quarkkingdee.top/Article/details/gt2gfnunfnp.html

) t WHERE rn = 1;
来源：http://dali.chenlongwang.top/Article/details/gt2fkbbhjgb.html

[Q35] 内连接
来源：http://dali.yanxiufei.cn/Article/details/gt2qismaode.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.c1oappe.top/Article/details/gt2bujwcdir.html

[Q36] 左连接
来源：http://dali.zhoulong.xyz/Article/details/gt2gjjxetda.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.dianchejie.cn/Article/details/gt2qlnitkbc.html

[Q37] 右连接
来源：http://dali.redwolf501.top/Article/details/gt2hihysvxq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhoulong.xyz/Article/details/gt2kxqnipev.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.birdmap.top/Article/details/gt2xisuvyzq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.9152youxi.cn/Article/details/gt2iinfwywt.html

[Q39] 自连接（查上下级）
来源：http://dali.sxryk.cn/Article/details/gt2hptcgyfd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.tanke756.top/Article/details/gt2wjuwwzyf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.birdmap.top/Article/details/gt2shmmjpss.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hammf.cn/Article/details/gt2zhjmwuch.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.fzhhl.top/Article/details/gt2zjkywlhn.html

[Q41] 多表连接
来源：http://dali.yangfankeji.com/Article/details/gt2qsxezbvn.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.kuanghao11.cn/Article/details/gt2isewoerj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cashguo.top/Article/details/gt2htlsufdx.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jianghu66.top/Article/details/gt2iciwlzmy.html

[Q42] 连接条件附加过滤
来源：http://dali.yuxming.cn/Article/details/gt2xgyaqiai.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zdqjudy.top/Article/details/gt2rlgphskp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ppjwa.cn/Article/details/gt2kgorvgtg.html

[Q43] 标量子查询
来源：http://dali.fzhhl.top/Article/details/gt2jpmccknm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.wangdashe.top/Article/details/gt2nvggghwo.html

[Q44] IN 子查询
来源：http://dali.sxryk.cn/Article/details/gt2jldgasim.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.pycfn.com/Article/details/gt2ntdkxooj.html

[Q45] EXISTS 判断存在
来源：http://dali.jinqigfzy.top/Article/details/gt2sucmaqxp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yuanzhike.top/Article/details/gt2pxrwwdbt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.0kj1m.cn/Article/details/gt2xnwlabka.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.meibo888.top/Article/details/gt2gokodtwa.html

[Q47] 与平均值比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fdmpyuff.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.gogol.net.cn/Article/details/gt2jdxerrat.html

[Q48] CTE 公用表表达式
来源：http://dali.havefunace.top/Article/details/gt2pynchwpg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.bjfxy.top/Article/details/gt2fkydctzg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ppjwa.cn/Article/details/gt2wkocdbza.html

[Q49] 更新单行
来源：http://dali.shzxlz.cn/Article/details/gt2wggryace.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cqqwz.cn/Article/details/gt2yxdgbzzm.html

[Q50] 批量更新
来源：http://dali.wangshuangyany.cn/Article/details/gt2ofheikum.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sufxvd.cn/Article/details/gt2bnnfckzw.html

[Q51] 用子查询更新
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kmabsxvw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ahedewob.html

[Q52] 删除指定行
来源：http://dali.jiagoushi.top/Article/details/gt2svlwaxix.html

DELETE FROM users WHERE id = 10;
来源：http://dali.birdmap.top/Article/details/gt2ttdfwojj.html

[Q53] 按条件删除
来源：http://dali.ehwqpu.com/Article/details/gt2azojqvvg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.vqdsnc.cn/Article/details/gt2wnjpzhtx.html

[Q54] 清空表
来源：http://dali.zhengqikj.top/Article/details/gt2itjyfpno.html

TRUNCATE TABLE logs;
来源：http://dali.dianchejie.cn/Article/details/gt2gzaiayal.html

[Q55] 排名（并列占位）
来源：http://dali.316326.xyz/Article/details/gt2gkfzrvip.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.c1oappe.top/Article/details/gt2bgpcxpfo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xziqi.cn/Article/details/gt2ufrjveme.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xziqi.cn/Article/details/gt2kjmrvdou.html

[Q57] 行号
来源：http://dali.xylfe.cn/Article/details/gt2ypndgdwg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.pycfn.com/Article/details/gt2mkufevep.html

[Q58] 累计求和
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dyrnrqyb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gt2eccobpsb.html

[Q59] 分组内累计
来源：http://dali.zhixingplan.top/Article/details/gt2gywbaowt.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gt2ithiozlz.html

[Q60] 取上一行 / 下一行
来源：http://dali.nanxuanxn.top/Article/details/gt2smephipj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yvedp.cn/Article/details/gt2noffuogt.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xylfe.cn/Article/details/gt2htwiapsl.html

[Q61] 移动平均
来源：http://dali.sxryk.cn/Article/details/gt2ecffonct.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.fengsongda.top/Article/details/gt2orggfano.html

[Q62] 分组占比
来源：http://dali.cucudq.cn/Article/details/gt2pudoxcfk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.andypj.xyz/Article/details/gt2kggbltgx.html

[Q63] 开启事务
来源：http://dali.meibo888.top/Article/details/gt2lylqtfqt.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.sxryk.cn/Article/details/gt2wzjxjhef.html

[Q64] 提交事务
来源：http://dali.sufxvd.cn/Article/details/gt2hymrqbwg.html

COMMIT;
来源：http://dali.jianghu66.top/Article/details/gt2dbtnwujn.html

[Q65] 回滚事务
来源：http://dali.chenzaomai.com/Article/details/gt2dwfqmtkp.html

ROLLBACK;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bwgiokss.html

[Q66] 行锁查询
来源：http://dali.smart0.xyz/Article/details/gt2ifsvyson.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shangyingyoupin.top/Article/details/gt2smcviloh.html

[Q67] 设置隔离级别
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ldqegxou.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yj20258.top/Article/details/gt2pdsbtwrc.html

[Q68] 保存点
来源：http://dali.zhixingplan.top/Article/details/gt2cauvchnc.html

SAVEPOINT sp1;
来源：http://dali.sysykeji.top/Article/details/gt2tvbmbxgx.html

ROLLBACK TO sp1;
来源：http://dali.cucudq.cn/Article/details/gt2cxbhcwug.html

[Q69] 查看执行计划
来源：http://dali.yj20258.top/Article/details/gt2oafitorm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xuanzx.com/Article/details/gt2fcxiwnjh.html

[Q70] 更新统计信息
来源：http://dali.jqgfzy.top/Article/details/gt2xtrcycqc.html

ANALYZE TABLE users;
来源：http://dali.cqqwz.cn/Article/details/gt2gbjmybel.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmczixn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xziqi.cn/Article/details/gt2kiikdqgd.html

[Q72] 查看索引
来源：http://dali.gzhubu.top/Article/details/gt2llqwiyyc.html

SHOW INDEX FROM users;
来源：http://dali.tanke756.top/Article/details/gt2lkfqagkc.html

[Q73] 查看表状态
来源：http://dali.hammf.cn/Article/details/gt2odoukjwq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shuidangran.top/Article/details/gt2cytgkxrw.html

[Q74] 强制使用索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wxoipldk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yj202588.top/Article/details/gt2vsrzbqhu.html

[Q75] 日期格式化
来源：http://dali.pengpengdd.cyou/Article/details/gt2kpandzzq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gt2kaucfeho.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hongshengwenyu.top/Article/details/gt2vqctfczb.html

[Q76] 按天统计
来源：http://dali.jyoumei.cn/Article/details/gt2eenhfqmu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.bjfxy.top/Article/details/gt2uflgpqhm.html

[Q77] 时间加减
来源：http://dali.zdqjudy.top/Article/details/gt2ahsnsdpl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ydzc1.top/Article/details/gt2retsrgnk.html

[Q78] 当前时间
来源：http://dali.yuanzhike.top/Article/details/gt2zfwshyed.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.haohaochexian.top/Article/details/gt2ankjprco.html

[Q79] 字符串拼接
来源：http://dali.xziqi.cn/Article/details/gt2cnkjwixf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.tianlin.xyz/Article/details/gt2cjgijdzi.html

[Q80] 字符串截取
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2anksptix.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cashguo.top/Article/details/gt2qontvhdd.html

[Q81] 字符串替换
来源：http://dali.hnxiangtu.top/Article/details/gt2ohecxwxz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2osvhanum.html

[Q82] 字符长度与字节长度
来源：http://dali.zhongyouzk.top/Article/details/gt2odlmkszl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eogyzavr.html

[Q83] 大小写转换
来源：http://dali.xylfe.cn/Article/details/gt2tcvmyfvr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2lporowmn.html

[Q84] 去除首尾空格
来源：http://dali.jianghu66.top/Article/details/gt2ipvoevpp.html

SELECT TRIM(name) FROM users;
来源：http://dali.birdmap.top/Article/details/gt2eghpueml.html

[Q85] 数值取整
来源：http://dali.sxryk.cn/Article/details/gt2fxcjpbnm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zycfv.cn/Article/details/gt2aufjbckq.html

[Q86] 读取 JSON 字段
来源：http://dali.yj202588.top/Article/details/gt2fsupiejm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hfpthk.cn/Article/details/gt2uvbnhczx.html

[Q87] JSON 字段做条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zxnnywrb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.sysykeji.top/Article/details/gt2zptalyoi.html

[Q88] 行转列（条件聚合）
来源：http://dali.daxiang520.top/Article/details/gt2mviymxhe.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.guannengcc.top/Article/details/gt2cwwwpfib.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2muvzjyoj.html

[Q89] 判断表是否存在
来源：http://dali.hfpthk.cn/Article/details/gt2pupbycyi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.daxiang520.top/Article/details/gt2obwhmxkf.html

[Q90] 生成序号列
来源：http://dali.cheryme.top/Article/details/gt2mvlwrcev.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jiagoushi.top/Article/details/gt2boqhiixx.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qtnbwawf.html

R. Bash 专题
来源：http://dali.ybcxt.top/Article/details/gt2vdqfjexf.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2phhahhha.html

[R01] shebang 与严格模式
来源：http://dali.wangshuangyany.cn/Article/details/gt2uidqgjnz.html

#!/usr/bin/env bash
来源：http://dali.hysaishi.cn/Article/details/gt2nscfvmwy.html

set -euo pipefail
来源：http://dali.guowangkeji.top/Article/details/gt2xagxzqeg.html

[R02] 变量赋值与使用
来源：http://dali.hnxiangtu.top/Article/details/gt2yvdpnvlu.html

name="Tom"; echo "$name"
来源：http://dali.jqgufenzy.top/Article/details/gt2ctynfujk.html

[R03] 只读变量
来源：http://dali.yongpay.top/Article/details/gt2plygorad.html

readonly PI=3.14
来源：http://dali.zhixingplan.top/Article/details/gt2stnhsnyy.html

[R04] 位置参数
来源：http://dali.zhoulong.xyz/Article/details/gt2kwovcxtt.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.tian-w.cn/Article/details/gt2bjtkvmlu.html

[R05] 参数默认值
来源：http://dali.yangfankeji.com/Article/details/gt2ypjzexbe.html

name="${1:-default}"
来源：http://dali.yangfankeji.com/Article/details/gt2hetohnji.html

[R06] 判断命令是否存在
来源：http://dali.0kj1m.cn/Article/details/gt2zjlaqbwb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yvedp.cn/Article/details/gt2ynawmtmo.html

[R07] if 判断文件
来源：http://dali.jinqigfzy.top/Article/details/gt2uaybvrxu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinqigfzy.top/Article/details/gt2rpgaeupa.html

[R08] 数值比较
来源：http://dali.ehwqpu.com/Article/details/gt2jijgvvon.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhoulong.xyz/Article/details/gt2ickvswdf.html

[R09] 字符串比较
来源：http://dali.0kj1m.cn/Article/details/gt2dlhdowbh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.sxryk.cn/Article/details/gt2lnulnrfx.html

[R10] 正则匹配
来源：http://dali.cheryme.top/Article/details/gt2pciectvg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.316326.xyz/Article/details/gt2jdbefxpn.html

[R11] case 多分支
来源：http://dali.zycfv.cn/Article/details/gt2qibhebbw.html

case "$1" in
来源：http://dali.316326.xyz/Article/details/gt2edxwwamg.html

start) echo "启动" ;;
来源：http://dali.yanxiufei.cn/Article/details/gt2oumvlaxw.html

stop)  echo "停止" ;;
来源：http://dali.birdmap.top/Article/details/gt2pthwbbbb.html

*)     echo "未知命令" ;;
来源：http://dali.andypj.xyz/Article/details/gt2izoluojb.html

esac
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kdcllfoi.html

[R12] for 遍历文件
来源：http://dali.jqgfzy.top/Article/details/gt2pxxxornv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ehwqpu.com/Article/details/gt2akdijkjz.html

[R13] for 计数循环
来源：http://dali.xinyue.icu/Article/details/gt2dttasqtx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ivvv.top/Article/details/gt2gexdjkhx.html

[R14] C 风格 for
来源：http://dali.hammf.cn/Article/details/gt2iizvligx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.daxiang520.top/Article/details/gt2cqesyolv.html

[R15] while 逐行读文件
来源：http://dali.shuidangran.top/Article/details/gt2waivhxja.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.aibaodan.cn/Article/details/gt2rmisnoqi.html

[R16] until 等待条件
来源：http://dali.zycfv.cn/Article/details/gt2krxgjtav.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shangyingyoupin.top/Article/details/gt2jwkimsoy.html

[R17] 数组定义与取值
来源：http://dali.hfpthk.cn/Article/details/gt2quxjxwdj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhoulong.xyz/Article/details/gt2bvpwrsax.html

[R18] 遍历数组
来源：http://dali.nwbrower.top/Article/details/gt2fmhokitu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yuanzhike.top/Article/details/gt2zjkljgbp.html

[R19] 数组长度
来源：http://dali.fzhhl.top/Article/details/gt2jnlwpwyn.html

echo "${#arr[@]}"
来源：http://dali.gogol.net.cn/Article/details/gt2ehvtalip.html

[R20] 关联数组（字典）
来源：http://dali.ivvv.top/Article/details/gt2ocghufyw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hnqzz.top/Article/details/gt2ducspnqo.html

[R21] 字符串长度
来源：http://dali.zycfv.cn/Article/details/gt2fcobxads.html

echo "${#s}"
来源：http://dali.hfpthk.cn/Article/details/gt2pilsduha.html

[R22] 截取子串
来源：http://dali.yongpay.top/Article/details/gt2pzhpluyh.html

echo "${s:0:5}"
来源：http://dali.birdmap.top/Article/details/gt2zduzbpel.html

[R23] 字符串替换
来源：http://dali.redwolf501.top/Article/details/gt2fkjafwhd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.chenjidiqi.icu/Article/details/gt2jandzdxe.html

[R24] 大小写转换
来源：http://dali.shzxlz.cn/Article/details/gt2distfwdb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2enpulyag.html

[R25] 去后缀 / 去前缀
来源：http://dali.hnqzz.top/Article/details/gt2uucfwudd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fapluwiy.html

[R26] 命令替换
来源：http://dali.jianghu66.top/Article/details/gt2crgesjnl.html

now=$(date +%F); echo "$now"
来源：http://dali.zhongyouzk.top/Article/details/gt2hkcqweet.html

[R27] 算术展开
来源：http://dali.smart0.xyz/Article/details/gt2hdmrnpig.html

echo $((1 + 2 * 3))
来源：http://dali.daria6918.cn/Article/details/gt2aeikidix.html

[R28] 浮点运算
来源：http://dali.cheryme.top/Article/details/gt2rlfdtkmu.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinghuilouyu.cn/Article/details/gt2veawpwhk.html

[R29] 定义函数
来源：http://dali.hnqzz.top/Article/details/gt2hjxigysj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.birdmap.top/Article/details/gt2okbqlmyu.html

[R30] 函数返回状态码
来源：http://dali.shuidangran.top/Article/details/gt2czxxagml.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhixingplan.top/Article/details/gt2zokbovlp.html

[R31] 局部变量
来源：http://dali.yvedp.cn/Article/details/gt2zahimaxa.html

f() { local x=1; echo "$x"; }
来源：http://dali.pycfn.com/Article/details/gt2bllvmuoa.html

[R32] 参数个数校验
来源：http://dali.ppjwa.cn/Article/details/gt2xlyxdpqh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hnqzz.top/Article/details/gt2fejxdnjy.html

[R33] 捕获错误并提示行号
来源：http://dali.zhongyouzk.top/Article/details/gt2fuiawodg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ehwqpu.com/Article/details/gt2mtxsrysv.html

[R34] 退出时清理
来源：http://dali.jinqigfzy.top/Article/details/gt2vjnsekra.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.dianchejie.cn/Article/details/gt2qykirujx.html

[R35] 后台执行并等待
来源：http://dali.nanxuanxn.top/Article/details/gt2dixlwwcv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhengqikj.top/Article/details/gt2efadjgpu.html

[R36] 并发执行多个任务
来源：http://dali.cashguo.top/Article/details/gt2iuowmcxm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yvedp.cn/Article/details/gt2kqqykjjy.html

[R37] 把输出赋给变量
来源：http://dali.smart0.xyz/Article/details/gt2waelrcfs.html

files=$(ls -1)
来源：http://dali.fzhhl.top/Article/details/gt2aduuctmk.html

[R38] 管道串联
来源：http://dali.dashuyun.cn/Article/details/gt2keyccoqp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.daria6918.cn/Article/details/gt2gxhzedtd.html

[R39] 重定向标准输出与错误
来源：http://dali.zycfv.cn/Article/details/gt2kjmqtraz.html

cmd > out.log 2>&1
来源：http://dali.shuidangran.top/Article/details/gt2cnycegjv.html

[R40] 追加写日志
来源：http://dali.ppjwa.cn/Article/details/gt2ddrsnkjs.html

echo "log" >> out.log
来源：http://dali.ppjwa.cn/Article/details/gt2vbkytfib.html

[R41] 丢弃输出
来源：http://dali.gogol.net.cn/Article/details/gt2nlzjwqbi.html

cmd >/dev/null 2>&1
来源：http://dali.yj20258.top/Article/details/gt2tvfredzi.html

[R42] 输入重定向
来源：http://dali.chenzaomai.com/Article/details/gt2srxljvzk.html

wc -l < a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dliahbjo.html

[R43] 按名字查找文件
来源：http://dali.redwolf501.top/Article/details/gt2hhvfjqoh.html

find . -name "*.log" -type f
来源：http://dali.hnqzz.top/Article/details/gt2hzgunjya.html

[R44] 按修改时间查找
来源：http://dali.zycfv.cn/Article/details/gt2drgvgrob.html

find . -mtime -7 -type f
来源：http://dali.feifeiyinyue.top/Article/details/gt2zjrprylr.html

[R45] 批量删除
来源：http://dali.jqgufenzy.top/Article/details/gt2kkcokvov.html

find . -name "*.tmp" -delete
来源：http://dali.jyoumei.cn/Article/details/gt2anurclgi.html

[R46] 递归替换文件内容
来源：http://dali.yanxiufei.cn/Article/details/gt2vchbmheh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hongshengwenyu.top/Article/details/gt2iswcikcf.html

[R47] sed 单行替换
来源：http://dali.cucudq.cn/Article/details/gt2tyeeeqya.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rtgzrwnd.html

[R48] awk 取指定列
来源：http://dali.ppjwa.cn/Article/details/gt2hmgtbyvp.html

awk '{print $1, $3}' a.txt
来源：http://dali.fengsongda.top/Article/details/gt2hqhdatac.html

[R49] awk 带条件
来源：http://dali.xinyue.icu/Article/details/gt2xiryquro.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jyoumei.cn/Article/details/gt2cevhfgan.html

[R50] awk 求和
来源：http://dali.yj202588.top/Article/details/gt2danwsuoj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gotoacloud.top/Article/details/gt2wagkkuvq.html

[R51] 排序去重取前几
来源：http://dali.sufxvd.cn/Article/details/gt2xukpdjri.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zycfv.cn/Article/details/gt2pjcfszsc.html

[R52] 统计行数
来源：http://dali.9152youxi.cn/Article/details/gt2mpngtzwv.html

wc -l a.txt
来源：http://dali.0kj1m.cn/Article/details/gt2gqlfxspr.html

[R53] 查看文件头与实时尾
来源：http://dali.kuanghao11.cn/Article/details/gt2obbgtyjy.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ybcxt.top/Article/details/gt2vrcyzmti.html

[R54] 比较两个文件
来源：http://dali.iojbl.cn/Article/details/gt2ulrobfnm.html

diff a.txt b.txt
来源：http://dali.jinqigfzy.top/Article/details/gt2wluceati.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2lokjseui.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hywenlv.cn/Article/details/gt2nypqoqtb.html

[R56] 远程拷贝
来源：http://dali.jlsjyb.cn/Article/details/gt2etpdhuoz.html

scp file user@host:/path/
来源：http://dali.sweek.top/Article/details/gt2kztcklmj.html

[R57] 远程执行命令
来源：http://dali.iojbl.cn/Article/details/gt2rkzpmmtj.html

ssh user@host 'uptime'
来源：http://dali.smart0.xyz/Article/details/gt2gpxzseos.html

[R58] 下载文件
来源：http://dali.yj20258888.top/Article/details/gt2xprejihs.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.pengpengdd.cyou/Article/details/gt2uyepzrbw.html

[R59] 发 POST JSON
来源：http://dali.hnxiangtu.top/Article/details/gt2clltkijr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.smart0.xyz/Article/details/gt2nsaicdce.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhixingplan.top/Article/details/gt2bgigpfhl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.svipenyu.cn/Article/details/gt2yzkqfcnp.html

[R61] 磁盘占用
来源：http://dali.sxryk.cn/Article/details/gt2fjcjrybu.html

df -h;  du -sh *
来源：http://dali.hysaishi.cn/Article/details/gt2irmfncjk.html

[R62] 找最占空间的文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2qvcsnwbf.html

du -ah . | sort -rh | head -10
来源：http://dali.0kj1m.cn/Article/details/gt2olqorvvw.html

[R63] 内存与进程
来源：http://dali.mhx1999.top/Article/details/gt2nndldiuk.html

free -h;  ps aux | grep nginx
来源：http://dali.sxryk.cn/Article/details/gt2cxgvpeen.html

[R64] 结束进程
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ndmynuuy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.0kj1m.cn/Article/details/gt2hhkpmcdq.html

[R65] 查看端口占用
来源：http://dali.jyoumei.cn/Article/details/gt2gntyninb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.nanxuanxn.top/Article/details/gt2fevxhamw.html

[R66] 定时任务
来源：http://dali.hnxiangtu.top/Article/details/gt2fpdhjlhy.html

crontab -e;  crontab -l
来源：http://dali.hysaishi.cn/Article/details/gt2icqunvge.html

[R67] 生成随机十六进制串
来源：http://dali.jlsjyb.cn/Article/details/gt2fixdggvj.html

openssl rand -hex 16
来源：http://dali.hongshengwenyu.top/Article/details/gt2akvqrwsr.html

[R68] 计算文件校验值
来源：http://dali.guannengcc.top/Article/details/gt2nzeezdes.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gt2muipecjg.html

[R69] 生成随机密码
来源：http://dali.redwolf501.top/Article/details/gt2xufkrfdt.html

head -c 16 /dev/urandom | base64
来源：http://dali.meibo888.top/Article/details/gt2txtgrlyn.html

[R70] 时间戳与互转
来源：http://dali.gzhubu.top/Article/details/gt2acuxjnkh.html

date +%s;  date -d @1700000000
来源：http://dali.xylfe.cn/Article/details/gt2ngddwcpd.html

[R71] 日期格式化
来源：http://dali.sufxvd.cn/Article/details/gt2opwgzbge.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinqigfzy.top/Article/details/gt2pchvtxgt.html

[R72] 等待端口就绪
来源：http://dali.gaohongyu789.top/Article/details/gt2wnxqwlfd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhengqikj.top/Article/details/gt2ragohacd.html

[R73] 分割大日志
来源：http://dali.jianghu66.top/Article/details/gt2lmajryqq.html

split -l 1000 big.log part_
来源：http://dali.yanxiufei.cn/Article/details/gt2cwgggkcn.html

[R74] 批量重命名
来源：http://dali.ehwqpu.com/Article/details/gt2rvqcymln.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jiagoushi.top/Article/details/gt2baecioyc.html

[R75] 导出环境变量
来源：http://dali.wangdashe.top/Article/details/gt2otfvjlcf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sysykeji.top/Article/details/gt2xtwzrlro.html

[R76] 使用临时文件
来源：http://dali.jqgfzy.top/Article/details/gt2jtbsvexq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.316326.xyz/Article/details/gt2oqvywith.html

[R77] 读取用户输入
来源：http://dali.cqqwz.cn/Article/details/gt2vbnnbvag.html


<!-- 参考信息 -->