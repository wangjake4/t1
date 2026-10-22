代发 wailian999

[Q33] 多列分组
来源：http://dali.andypj.xyz/Article/details/gt2lhopvstr.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.pycfn.com/Article/details/gt2ksvozcal.html

[Q34] 每组取第一条
来源：http://dali.yj20258888.top/Article/details/gt2sqfrwidd.html

SELECT * FROM (
来源：http://dali.nanxinkj.top/Article/details/gt2dsgppznu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zdqjudy.top/Article/details/gt2fqyxxdvi.html

) t WHERE rn = 1;
来源：http://dali.bjfxy.top/Article/details/gt2jgandoqn.html

[Q35] 内连接
来源：http://dali.tanke756.top/Article/details/gt2dtndhalq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xuetiantiany.cn/Article/details/gt2pzamqwdb.html

[Q36] 左连接
来源：http://dali.zhiwuduotai.top/Article/details/gt2hfhvspyz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.svipenyu.cn/Article/details/gt2mridlcuj.html

[Q37] 右连接
来源：http://dali.xziqi.cn/Article/details/gt2lxaowprn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhongyouzk.top/Article/details/gt2rjlkdayw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhengqikj.top/Article/details/gt2scshzlee.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.guowangkeji.top/Article/details/gt2bjqwbvsa.html

[Q39] 自连接（查上下级）
来源：http://dali.jqgfzy.top/Article/details/gt2ditxaauk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.smart0.xyz/Article/details/gt2snjbrqqs.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yongpay.top/Article/details/gt2sxxkojrh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ivvv.top/Article/details/gt2wxropomh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.gotoacloud.top/Article/details/gt2ybqwcmqe.html

[Q41] 多表连接
来源：http://dali.316326.xyz/Article/details/gt2agugfehg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.pengpengdd.cyou/Article/details/gt2xavsdopb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgiwjyr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jinqigfzy.top/Article/details/gt2oapajzbm.html

[Q42] 连接条件附加过滤
来源：http://dali.xylfe.cn/Article/details/gt2abtkxjac.html

SELECT u.name, o.amount FROM users u
来源：http://dali.kuanghao11.cn/Article/details/gt2grgdahwx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.redwolf501.top/Article/details/gt2omtjkjiz.html

[Q43] 标量子查询
来源：http://dali.smart0.xyz/Article/details/gt2ijcwynyv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xziqi.cn/Article/details/gt2tshcipoc.html

[Q44] IN 子查询
来源：http://dali.yvedp.cn/Article/details/gt2eagpacxp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.chenzaomai.com/Article/details/gt2agvqgmey.html

[Q45] EXISTS 判断存在
来源：http://dali.chenjidiqi.icu/Article/details/gt2nlfpgajc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sufxvd.cn/Article/details/gt2xuqiulop.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.quarkkingdee.top/Article/details/gt2tgxvrbnh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2enqgajbt.html

[Q47] 与平均值比较
来源：http://dali.svipenyu.cn/Article/details/gt2cdnzodhu.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2awgymplm.html

[Q48] CTE 公用表表达式
来源：http://dali.yj20258.top/Article/details/gt2dfnrmtgj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shuidangran.top/Article/details/gt2tyiviwyo.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhoulong.xyz/Article/details/gt2yzaapjqy.html

[Q49] 更新单行
来源：http://dali.aibaodan.cn/Article/details/gt2ieqfhrkf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.snrcjt.cn/Article/details/gt2lpupfdlj.html

[Q50] 批量更新
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tcvhdfjc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jlsjyb.cn/Article/details/gt2nqynhsxd.html

[Q51] 用子查询更新
来源：http://dali.yuanzhike.top/Article/details/gt2jgbfiajo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zdqjudy.top/Article/details/gt2jeazhskr.html

[Q52] 删除指定行
来源：http://dali.zhiwuduotai.top/Article/details/gt2pvzotvcg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.gotoacloud.top/Article/details/gt2rimomqks.html

[Q53] 按条件删除
来源：http://dali.dianchejie.cn/Article/details/gt2ccyanwcr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xziqi.cn/Article/details/gt2rfwqeacz.html

[Q54] 清空表
来源：http://dali.ehwqpu.com/Article/details/gt2mboconvd.html

TRUNCATE TABLE logs;
来源：http://dali.pengpengdd.cyou/Article/details/gt2mjloxpvd.html

[Q55] 排名（并列占位）
来源：http://dali.zhoulong.xyz/Article/details/gt2uumlecsp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bcqoctaw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhengqikj.top/Article/details/gt2ykkpeclr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.c1oappe.top/Article/details/gt2bzdparoj.html

[Q57] 行号
来源：http://dali.xuetiantiany.cn/Article/details/gt2mwtojwzw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.havefunace.top/Article/details/gt2ihsheohl.html

[Q58] 累计求和
来源：http://dali.nanxinkj.top/Article/details/gt2hcnlveer.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yonumen.top/Article/details/gt2rspwwnjg.html

[Q59] 分组内累计
来源：http://dali.quarkkingdee.top/Article/details/gt2qzwrwiam.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cheryme.top/Article/details/gt2aaafcdvt.html

[Q60] 取上一行 / 下一行
来源：http://dali.hongshengwenyu.top/Article/details/gt2zmuuxetc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jianghu66.top/Article/details/gt2rufcpwfw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.daxiang520.top/Article/details/gt2qktgslzg.html

[Q61] 移动平均
来源：http://dali.yj20258888.top/Article/details/gt2pzmlhszd.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gt2nqbxpter.html

[Q62] 分组占比
来源：http://dali.fengsongda.top/Article/details/gt2dnjliifh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.havefunace.top/Article/details/gt2bmywinev.html

[Q63] 开启事务
来源：http://dali.yueranfly.top/Article/details/gt2qgiheyzi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cheryme.top/Article/details/gt2xjogemqa.html

[Q64] 提交事务
来源：http://dali.quarkkingdee.top/Article/details/gt2nltlnzjc.html

COMMIT;
来源：http://dali.shuidangran.top/Article/details/gt2fdpsgbcz.html

[Q65] 回滚事务
来源：http://dali.zhixingplan.top/Article/details/gt2xlthyjnu.html

ROLLBACK;
来源：http://dali.chenlongwang.top/Article/details/gt2vwweegtp.html

[Q66] 行锁查询
来源：http://dali.0kj1m.cn/Article/details/gt2vydmsqoc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.daxiang520.top/Article/details/gt2jvzigkui.html

[Q67] 设置隔离级别
来源：http://dali.kuanghao11.cn/Article/details/gt2uuehzuwz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.316326.xyz/Article/details/gt2wmvssggr.html

[Q68] 保存点
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2viaxtcqt.html

SAVEPOINT sp1;
来源：http://dali.tianlin.xyz/Article/details/gt2uxwgnttk.html

ROLLBACK TO sp1;
来源：http://dali.kuanghao11.cn/Article/details/gt2wtwucjif.html

[Q69] 查看执行计划
来源：http://dali.daxiang520.top/Article/details/gt2skztcdyz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.mhx1999.top/Article/details/gt2nmyqdivo.html

[Q70] 更新统计信息
来源：http://dali.yvedp.cn/Article/details/gt2xpmhmxvy.html

ANALYZE TABLE users;
来源：http://dali.jyoumei.cn/Article/details/gt2hjmardtc.html

[Q71] 查看建表语句
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ojuedltp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.tianlin.xyz/Article/details/gt2hsqabcjz.html

[Q72] 查看索引
来源：http://dali.hammf.cn/Article/details/gt2nqttufxv.html

SHOW INDEX FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2bqlpujsq.html

[Q73] 查看表状态
来源：http://dali.zhixingplan.top/Article/details/gt2mmtpqxkw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shzxlz.cn/Article/details/gt2ijtrvbvt.html

[Q74] 强制使用索引
来源：http://dali.meibo888.top/Article/details/gt2ucwjnvif.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.meibo888.top/Article/details/gt2wrvkszsd.html

[Q75] 日期格式化
来源：http://dali.andypj.xyz/Article/details/gt2bqftfngx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hammf.cn/Article/details/gt2xrqkmaim.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cashguo.top/Article/details/gt2negusabk.html

[Q76] 按天统计
来源：http://dali.hongshengwenyu.top/Article/details/gt2dflkpksf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.c1oappe.top/Article/details/gt2giitfyni.html

[Q77] 时间加减
来源：http://dali.yj20258888.top/Article/details/gt2inuiuhgn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.chenjidiqi.icu/Article/details/gt2meirteud.html

[Q78] 当前时间
来源：http://dali.yj20258.top/Article/details/gt2mimaqdum.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.haohaochexian.top/Article/details/gt2oqzvqxbn.html

[Q79] 字符串拼接
来源：http://dali.gogol.net.cn/Article/details/gt2nrpipjuf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cqqwz.cn/Article/details/gt2sscgbkso.html

[Q80] 字符串截取
来源：http://dali.cashguo.top/Article/details/gt2kqmhuxky.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uqztjglk.html

[Q81] 字符串替换
来源：http://dali.hongshengwenyu.top/Article/details/gt2brjnlksi.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2gijpaqlh.html

[Q82] 字符长度与字节长度
来源：http://dali.gzhubu.top/Article/details/gt2drfctddi.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sxryk.cn/Article/details/gt2stccjngu.html

[Q83] 大小写转换
来源：http://dali.yangfankeji.com/Article/details/gt2yrpoqqhp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2ddmmqrck.html

[Q84] 去除首尾空格
来源：http://dali.yuxming.cn/Article/details/gt2zyqauphm.html

SELECT TRIM(name) FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2qiblsqpj.html

[Q85] 数值取整
来源：http://dali.sweek.top/Article/details/gt2pqeglsxv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gaohongyu789.top/Article/details/gt2zsfgcpej.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2tfbmgkqg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mwcdgtyx.html

[Q87] JSON 字段做条件
来源：http://dali.pycfn.com/Article/details/gt2cptxntip.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.dashuyun.cn/Article/details/gt2nidknfty.html

[Q88] 行转列（条件聚合）
来源：http://dali.aibaodan.cn/Article/details/gt2ywvwwffb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.havefunace.top/Article/details/gt2qlauqetu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hgdmmeag.html

[Q89] 判断表是否存在
来源：http://dali.yonumen.top/Article/details/gt2kgomwpnf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ydzc1.top/Article/details/gt2cvgvvvhm.html

[Q90] 生成序号列
来源：http://dali.jqgfzy.top/Article/details/gt2ccqtlmjq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rolkvrdi.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2ozgpdzbn.html

R. Bash 专题
来源：http://dali.jyoumei.cn/Article/details/gt2zduytmvy.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2kfkfveqi.html

[R01] shebang 与严格模式
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pfizsfre.html

#!/usr/bin/env bash
来源：http://dali.bjfxy.top/Article/details/gt2vsnwoyeq.html

set -euo pipefail
来源：http://dali.ivvv.top/Article/details/gt2tvhyuxdx.html

[R02] 变量赋值与使用
来源：http://dali.ydzc1.top/Article/details/gt2itpmqiij.html

name="Tom"; echo "$name"
来源：http://dali.tian-w.cn/Article/details/gt2tmahenny.html

[R03] 只读变量
来源：http://dali.vqdsnc.cn/Article/details/gt2yxofdbfz.html

readonly PI=3.14
来源：http://dali.sweek.top/Article/details/gt2wpipbzrm.html

[R04] 位置参数
来源：http://dali.sufxvd.cn/Article/details/gt2noyhfybc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.sxryk.cn/Article/details/gt2shuhojqz.html

[R05] 参数默认值
来源：http://dali.hnqzz.top/Article/details/gt2ssfghuqp.html

name="${1:-default}"
来源：http://dali.xylfe.cn/Article/details/gt2fkqjmiqm.html

[R06] 判断命令是否存在
来源：http://dali.shangyingyoupin.top/Article/details/gt2yzwkqrbq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2cberudme.html

[R07] if 判断文件
来源：http://dali.yangfankeji.com/Article/details/gt2ixvanrsh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xinyue.icu/Article/details/gt2mzdsqxhw.html

[R08] 数值比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ekxabzlv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jyoumei.cn/Article/details/gt2nxxibgxb.html

[R09] 字符串比较
来源：http://dali.sweek.top/Article/details/gt2fxdnjbmk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.daxiang520.top/Article/details/gt2ikdvtzan.html

[R10] 正则匹配
来源：http://dali.quarkkingdee.top/Article/details/gt2sdeqsssh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hammf.cn/Article/details/gt2kdnwbqfz.html

[R11] case 多分支
来源：http://dali.andypj.xyz/Article/details/gt2opwnmpyp.html

case "$1" in
来源：http://dali.wangdashe.top/Article/details/gt2aabrviqe.html

start) echo "启动" ;;
来源：http://dali.birdmap.top/Article/details/gt2gilgpbgg.html

stop)  echo "停止" ;;
来源：http://dali.pengpengdd.cyou/Article/details/gt2lyhmzgvc.html

*)     echo "未知命令" ;;
来源：http://dali.zycfv.cn/Article/details/gt2snzsfxxv.html

esac
来源：http://dali.yonumen.top/Article/details/gt2fqjbcxkw.html

[R12] for 遍历文件
来源：http://dali.hnqzz.top/Article/details/gt2hwtvgony.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jinqigufen.top/Article/details/gt2exkpagwl.html

[R13] for 计数循环
来源：http://dali.chenjidiqi.icu/Article/details/gt2nygtvulg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.316326.xyz/Article/details/gt2ybxaehqo.html

[R14] C 风格 for
来源：http://dali.aibaodan.cn/Article/details/gt2rcgvjrsz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ehwqpu.com/Article/details/gt2ykukfijq.html

[R15] while 逐行读文件
来源：http://dali.jinqigfzy.top/Article/details/gt2ijssukro.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mznjxpeq.html

[R16] until 等待条件
来源：http://dali.yuanzhike.top/Article/details/gt2wwcxwbxo.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xuanzx.com/Article/details/gt2rujdaoco.html

[R17] 数组定义与取值
来源：http://dali.xziqi.cn/Article/details/gt2qzwflmaw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oqnjynev.html

[R18] 遍历数组
来源：http://dali.0kj1m.cn/Article/details/gt2nddoemof.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hysaishi.cn/Article/details/gt2cguspnvd.html

[R19] 数组长度
来源：http://dali.wangdashe.top/Article/details/gt2cmipeqnm.html

echo "${#arr[@]}"
来源：http://dali.meibo888.top/Article/details/gt2dukfdqan.html

[R20] 关联数组（字典）
来源：http://dali.hammf.cn/Article/details/gt2qlvkyjes.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hfpthk.cn/Article/details/gt2pvktzfgu.html

[R21] 字符串长度
来源：http://dali.redwolf501.top/Article/details/gt2cenvfuwt.html

echo "${#s}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2okhcrlap.html

[R22] 截取子串
来源：http://dali.redwolf501.top/Article/details/gt2cgshzwsf.html

echo "${s:0:5}"
来源：http://dali.quarkkingdee.top/Article/details/gt2ytardojk.html

[R23] 字符串替换
来源：http://dali.sweek.top/Article/details/gt2tfaxzdvp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xziqi.cn/Article/details/gt2miyuztgn.html

[R24] 大小写转换
来源：http://dali.9152youxi.cn/Article/details/gt2jxxajbtk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.snrcjt.cn/Article/details/gt2beefzowy.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2skltlhhw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.smart0.xyz/Article/details/gt2cwyxffjv.html

[R26] 命令替换
来源：http://dali.yvedp.cn/Article/details/gt2enhenopm.html

now=$(date +%F); echo "$now"
来源：http://dali.jqgfzy.top/Article/details/gt2abqccuco.html

[R27] 算术展开
来源：http://dali.jinqigufen.top/Article/details/gt2rxtrguyr.html

echo $((1 + 2 * 3))
来源：http://dali.hywenlv.cn/Article/details/gt2zfetmkrp.html

[R28] 浮点运算
来源：http://dali.yvedp.cn/Article/details/gt2ngkiokbg.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinqigufen.top/Article/details/gt2rqlyptoo.html

[R29] 定义函数
来源：http://dali.quarkkingdee.top/Article/details/gt2cqbmduzh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.c1oappe.top/Article/details/gt2xhwhzdpy.html

[R30] 函数返回状态码
来源：http://dali.guannengcc.top/Article/details/gt2nmdgilkt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cashguo.top/Article/details/gt2igushybl.html

[R31] 局部变量
来源：http://dali.sysykeji.top/Article/details/gt2xcbfslzc.html

f() { local x=1; echo "$x"; }
来源：http://dali.cdnleiting.top/Article/details/gt2xwymonga.html

[R32] 参数个数校验
来源：http://dali.hammf.cn/Article/details/gt2atelhzxv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.smart0.xyz/Article/details/gt2othsjtvx.html

[R33] 捕获错误并提示行号
来源：http://dali.chenjidiqi.icu/Article/details/gt2zisfehgv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.bjfxy.top/Article/details/gt2exaabqkx.html

[R34] 退出时清理
来源：http://dali.feifeiyinyue.top/Article/details/gt2crvrnhav.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.0kj1m.cn/Article/details/gt2lofkvbkq.html

[R35] 后台执行并等待
来源：http://dali.shzxlz.cn/Article/details/gt2aptuotth.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cqqwz.cn/Article/details/gt2fnpbsnvl.html

[R36] 并发执行多个任务
来源：http://dali.wangdashe.top/Article/details/gt2dtuhbfta.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.sweek.top/Article/details/gt2dbmcpqre.html

[R37] 把输出赋给变量
来源：http://dali.daria6918.cn/Article/details/gt2yzcyhzar.html

files=$(ls -1)
来源：http://dali.cqqwz.cn/Article/details/gt2knspfhcm.html

[R38] 管道串联
来源：http://dali.xziqi.cn/Article/details/gt2tjhtjgeq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.vqdsnc.cn/Article/details/gt2wohoodku.html

[R39] 重定向标准输出与错误
来源：http://dali.chenjidiqi.icu/Article/details/gt2njhzfcyn.html

cmd > out.log 2>&1
来源：http://dali.jiagoushi.top/Article/details/gt2srzzwlwb.html

[R40] 追加写日志
来源：http://dali.jqgfzy.top/Article/details/gt2lmgmzslm.html

echo "log" >> out.log
来源：http://dali.bjfxy.top/Article/details/gt2hmxewwnl.html

[R41] 丢弃输出
来源：http://dali.wangshuangyany.cn/Article/details/gt2ztlavdss.html

cmd >/dev/null 2>&1
来源：http://dali.iojbl.cn/Article/details/gt2xatwfahq.html

[R42] 输入重定向
来源：http://dali.sweek.top/Article/details/gt2tzkkovos.html

wc -l < a.txt
来源：http://dali.havefunace.top/Article/details/gt2jqjelxpe.html

[R43] 按名字查找文件
来源：http://dali.yuanzhike.top/Article/details/gt2pkedrjro.html

find . -name "*.log" -type f
来源：http://dali.sufxvd.cn/Article/details/gt2jlvcwuli.html

[R44] 按修改时间查找
来源：http://dali.zhiwuduotai.top/Article/details/gt2ssdqoofx.html

find . -mtime -7 -type f
来源：http://dali.tanke756.top/Article/details/gt2gjupcdrs.html

[R45] 批量删除
来源：http://dali.chenjidiqi.icu/Article/details/gt2mviltpeb.html

find . -name "*.tmp" -delete
来源：http://dali.ybcxt.top/Article/details/gt2ultiicdm.html

[R46] 递归替换文件内容
来源：http://dali.9152youxi.cn/Article/details/gt2sebmodix.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.fzhhl.top/Article/details/gt2xhionewy.html

[R47] sed 单行替换
来源：http://dali.redwolf501.top/Article/details/gt2gsignydj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dokblyod.html

[R48] awk 取指定列
来源：http://dali.c1oappe.top/Article/details/gt2xiyavbnx.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uwzixgzi.html

[R49] awk 带条件
来源：http://dali.xziqi.cn/Article/details/gt2heutndrv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.birdmap.top/Article/details/gt2bpiuvrls.html

[R50] awk 求和
来源：http://dali.ydzc1.top/Article/details/gt2abdytnwu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hfpthk.cn/Article/details/gt2ifsuzlfu.html

[R51] 排序去重取前几
来源：http://dali.xylfe.cn/Article/details/gt2vmkxzlhz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.dianchejie.cn/Article/details/gt2jeuldutt.html

[R52] 统计行数
来源：http://dali.guowangkeji.top/Article/details/gt2bvgttyzv.html

wc -l a.txt
来源：http://dali.xziqi.cn/Article/details/gt2assupxsp.html

[R53] 查看文件头与实时尾
来源：http://dali.nwbrower.top/Article/details/gt2kfsvkdfx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.c1oappe.top/Article/details/gt2hmmjnbro.html

[R54] 比较两个文件
来源：http://dali.yj20258888.top/Article/details/gt2wqzyviyq.html

diff a.txt b.txt
来源：http://dali.tanke756.top/Article/details/gt2zbvtirjo.html

[R55] 压缩与解压
来源：http://dali.zhongyouzk.top/Article/details/gt2dfvrdnjk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.sysykeji.top/Article/details/gt2jnkvvzzi.html

[R56] 远程拷贝
来源：http://dali.dashuyun.cn/Article/details/gt2awhmkmrv.html

scp file user@host:/path/
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ksajrmfs.html

[R57] 远程执行命令
来源：http://dali.jlsjyb.cn/Article/details/gt2vsvhjgzv.html

ssh user@host 'uptime'
来源：http://dali.hysaishi.cn/Article/details/gt2pspcxfcu.html

[R58] 下载文件
来源：http://dali.shzxlz.cn/Article/details/gt2orsqcimw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ehwqpu.com/Article/details/gt2lscoaaht.html

[R59] 发 POST JSON
来源：http://dali.guowangkeji.top/Article/details/gt2lzijbxso.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jianghu66.top/Article/details/gt2qjxcaxoo.html

[R60] 只看 HTTP 状态码
来源：http://dali.jyoumei.cn/Article/details/gt2lwzaltff.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yj20258888.top/Article/details/gt2cyhexved.html

[R61] 磁盘占用
来源：http://dali.snrcjt.cn/Article/details/gt2jibfcstw.html

df -h;  du -sh *
来源：http://dali.daria6918.cn/Article/details/gt2kmfaileo.html

[R62] 找最占空间的文件
来源：http://dali.fzhhl.top/Article/details/gt2ykgplqca.html

du -ah . | sort -rh | head -10
来源：http://dali.nanxinkj.top/Article/details/gt2gppdkbjj.html

[R63] 内存与进程
来源：http://dali.smart0.xyz/Article/details/gt2dnjhzxoq.html

free -h;  ps aux | grep nginx
来源：http://dali.dianchejie.cn/Article/details/gt2fjzcljvb.html

[R64] 结束进程
来源：http://dali.cheryme.top/Article/details/gt2lrhftpgc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhengqikj.top/Article/details/gt2cmpdeyhk.html

[R65] 查看端口占用
来源：http://dali.yonumen.top/Article/details/gt2edisplkt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhoulong.xyz/Article/details/gt2mpxxnlni.html

[R66] 定时任务
来源：http://dali.quarkkingdee.top/Article/details/gt2temcmzfp.html

crontab -e;  crontab -l
来源：http://dali.kuanghao11.cn/Article/details/gt2evfzayqo.html

[R67] 生成随机十六进制串
来源：http://dali.havefunace.top/Article/details/gt2rhbyelan.html

openssl rand -hex 16
来源：http://dali.c1oappe.top/Article/details/gt2igdufgsv.html

[R68] 计算文件校验值
来源：http://dali.zhixingplan.top/Article/details/gt2nvtbgcrm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jlsjyb.cn/Article/details/gt2mifevbmv.html

[R69] 生成随机密码
来源：http://dali.ydzc1.top/Article/details/gt2qknqpjju.html

head -c 16 /dev/urandom | base64
来源：http://dali.shzxlz.cn/Article/details/gt2oadibbta.html

[R70] 时间戳与互转
来源：http://dali.yj20258888.top/Article/details/gt2bewhhvrw.html

date +%s;  date -d @1700000000
来源：http://dali.svipenyu.cn/Article/details/gt2awhydeul.html

[R71] 日期格式化
来源：http://dali.ehwqpu.com/Article/details/gt2ecqfqibx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yonumen.top/Article/details/gt2xgqsdtfp.html

[R72] 等待端口就绪
来源：http://dali.yj202588.top/Article/details/gt2syfmojco.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.nanxinkj.top/Article/details/gt2bzriglfh.html

[R73] 分割大日志
来源：http://dali.xuanzx.com/Article/details/gt2qfwvmemg.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2wqecnram.html

[R74] 批量重命名
来源：http://dali.chenlongwang.top/Article/details/gt2rwyvbyzi.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.9152youxi.cn/Article/details/gt2akltmpbq.html

[R75] 导出环境变量
来源：http://dali.zdqjudy.top/Article/details/gt2rbbgvuqr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.tian-w.cn/Article/details/gt2uewinhgt.html

[R76] 使用临时文件
来源：http://dali.sweek.top/Article/details/gt2ywvcpyii.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.dashuyun.cn/Article/details/gt2thnfmvsg.html

[R77] 读取用户输入
来源：http://dali.yuxming.cn/Article/details/gt2detnklrz.html

read -rp "请输入: " ans
来源：http://dali.9152youxi.cn/Article/details/gt2guagsasn.html

[R78] 交互式菜单
来源：http://dali.fzhhl.top/Article/details/gt2bttctmlp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cheryme.top/Article/details/gt2wclebiij.html

[R79] 解析命令行选项
来源：http://dali.xinyue.icu/Article/details/gt2jttlblzf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.chenjidiqi.icu/Article/details/gt2faptvfxk.html

[R80] 查看脚本执行耗时
来源：http://dali.hnqzz.top/Article/details/gt2hetufqal.html

time ./run.sh
来源：http://dali.yonumen.top/Article/details/gt2ayynhgym.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2sygifoca.html

S. C / C++ 专题
来源：http://dali.sweek.top/Article/details/gt2pnzuwike.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2zbrsdlcp.html

[S01] C：Hello World
来源：http://dali.hysaishi.cn/Article/details/gt2aaatmkxp.html

#include <stdio.h>
来源：http://dali.yangfankeji.com/Article/details/gt2qkyoxoly.html


<!-- 参考信息 -->