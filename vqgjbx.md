代发 wailian999

[Q33] 多列分组
来源：http://dali.bjfxy.top/Article/details/gt2qegtgpkc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xuetiantiany.cn/Article/details/gt2uguwixdg.html

[Q34] 每组取第一条
来源：http://dali.shzxlz.cn/Article/details/gt2jmpzrmgm.html

SELECT * FROM (
来源：http://dali.jqgfzy.top/Article/details/gt2zhbdkklt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhengqikj.top/Article/details/gt2xvjcvuoa.html

) t WHERE rn = 1;
来源：http://dali.kuanghao11.cn/Article/details/gt2noskylwb.html

[Q35] 内连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ahafsxxx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.svipenyu.cn/Article/details/gt2hjldkeup.html

[Q36] 左连接
来源：http://dali.wangshuangyany.cn/Article/details/gt2bejmnwih.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jqgfzy.top/Article/details/gt2twhenany.html

[Q37] 右连接
来源：http://dali.xylfe.cn/Article/details/gt2pwobdyus.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ydzc1.top/Article/details/gt2ykmyytph.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yueranfly.top/Article/details/gt2hejqyfan.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.pycfn.com/Article/details/gt2jffmtkwp.html

[Q39] 自连接（查上下级）
来源：http://dali.daxiang520.top/Article/details/gt2rbbkxhzk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.c1oappe.top/Article/details/gt2egtyyvpf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hammf.cn/Article/details/gt2dndowaqw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shzxlz.cn/Article/details/gt2bddyzinm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhengqikj.top/Article/details/gt2nzjggshd.html

[Q41] 多表连接
来源：http://dali.cashguo.top/Article/details/gt2pleuyorr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.guowangkeji.top/Article/details/gt2atoyxqof.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jinqigfzy.top/Article/details/gt2idzofmxp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yj20258888.top/Article/details/gt2kscjahcn.html

[Q42] 连接条件附加过滤
来源：http://dali.xinyue.icu/Article/details/gt2bdtliqjk.html

SELECT u.name, o.amount FROM users u
来源：http://dali.dashuyun.cn/Article/details/gt2gmxwkvgl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hnxiangtu.top/Article/details/gt2aiysuwto.html

[Q43] 标量子查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yqdglcqy.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.snrcjt.cn/Article/details/gt2gecbnqrb.html

[Q44] IN 子查询
来源：http://dali.hongshengwenyu.top/Article/details/gt2vptipifm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.quarkkingdee.top/Article/details/gt2cbxfszci.html

[Q45] EXISTS 判断存在
来源：http://dali.9152youxi.cn/Article/details/gt2sjeoizuf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tian-w.cn/Article/details/gt2hnklezno.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.haohaochexian.top/Article/details/gt2fuqopnbm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.9152youxi.cn/Article/details/gt2hgyymqhs.html

[Q47] 与平均值比较
来源：http://dali.svipenyu.cn/Article/details/gt2rwjrflij.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xziqi.cn/Article/details/gt2iyltpvzb.html

[Q48] CTE 公用表表达式
来源：http://dali.aizwys.cn/Article/details/gt2sejonnrz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.andypj.xyz/Article/details/gt2trctuikb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinqigfzy.top/Article/details/gt2ufevlduy.html

[Q49] 更新单行
来源：http://dali.zdqjudy.top/Article/details/gt2ycwjeccg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.pycfn.com/Article/details/gt2jmnbbsgi.html

[Q50] 批量更新
来源：http://dali.guannengcc.top/Article/details/gt2pqijagza.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhongyouzk.top/Article/details/gt2mrnxcihq.html

[Q51] 用子查询更新
来源：http://dali.cucudq.cn/Article/details/gt2rsigfcfn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sxryk.cn/Article/details/gt2gkobfutt.html

[Q52] 删除指定行
来源：http://dali.bjfxy.top/Article/details/gt2uyoqqtfw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhengqikj.top/Article/details/gt2acbmxquh.html

[Q53] 按条件删除
来源：http://dali.redwolf501.top/Article/details/gt2cxnwyido.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.nanxinkj.top/Article/details/gt2vojzfsau.html

[Q54] 清空表
来源：http://dali.jianghu66.top/Article/details/gt2wusvlfvg.html

TRUNCATE TABLE logs;
来源：http://dali.sweek.top/Article/details/gt2crjuwopa.html

[Q55] 排名（并列占位）
来源：http://dali.sxryk.cn/Article/details/gt2nreerugp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.guowangkeji.top/Article/details/gt2qdfymhgy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.nwbrower.top/Article/details/gt2jjuxnumc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hammf.cn/Article/details/gt2nwhtyzvg.html

[Q57] 行号
来源：http://dali.shangyingyoupin.top/Article/details/gt2cdtjxgqy.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2zknrxzgc.html

[Q58] 累计求和
来源：http://dali.zhoulong.xyz/Article/details/gt2pfjqzxaf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.guannengcc.top/Article/details/gt2fdobiptd.html

[Q59] 分组内累计
来源：http://dali.guannengcc.top/Article/details/gt2plhjjjxa.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.aizwys.cn/Article/details/gt2uqnvsnmc.html

[Q60] 取上一行 / 下一行
来源：http://dali.andypj.xyz/Article/details/gt2legiqghj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gaohongyu789.top/Article/details/gt2xkzzyklm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gt2wadybqil.html

[Q61] 移动平均
来源：http://dali.cashguo.top/Article/details/gt2nyqfvbpw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gt2qfxruarw.html

[Q62] 分组占比
来源：http://dali.nanxuanxn.top/Article/details/gt2spapfxus.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.9152youxi.cn/Article/details/gt2pozmryve.html

[Q63] 开启事务
来源：http://dali.dianchejie.cn/Article/details/gt2vexdxisq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hnqzz.top/Article/details/gt2fhtpxqbf.html

[Q64] 提交事务
来源：http://dali.jlsjyb.cn/Article/details/gt2vwsowqph.html

COMMIT;
来源：http://dali.hywenlv.cn/Article/details/gt2wzojbluk.html

[Q65] 回滚事务
来源：http://dali.redwolf501.top/Article/details/gt2qdshzuss.html

ROLLBACK;
来源：http://dali.sweek.top/Article/details/gt2aqerpntq.html

[Q66] 行锁查询
来源：http://dali.yj202588.top/Article/details/gt2dvvrevui.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.guowangkeji.top/Article/details/gt2nzmfrjcn.html

[Q67] 设置隔离级别
来源：http://dali.birdmap.top/Article/details/gt2kmvpvolh.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.svipenyu.cn/Article/details/gt2nhcceghk.html

[Q68] 保存点
来源：http://dali.yangfankeji.com/Article/details/gt2smqglcgx.html

SAVEPOINT sp1;
来源：http://dali.haohaochexian.top/Article/details/gt2pmvnydzo.html

ROLLBACK TO sp1;
来源：http://dali.tanke756.top/Article/details/gt2mhlngsvv.html

[Q69] 查看执行计划
来源：http://dali.jinqigufen.top/Article/details/gt2zfjpkysa.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.fzhhl.top/Article/details/gt2kvcxavdj.html

[Q70] 更新统计信息
来源：http://dali.ydzc1.top/Article/details/gt2vixapdit.html

ANALYZE TABLE users;
来源：http://dali.zhoulong.xyz/Article/details/gt2lhyumtsq.html

[Q71] 查看建表语句
来源：http://dali.hammf.cn/Article/details/gt2vqhhfmmn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.dashuyun.cn/Article/details/gt2tvfnoguz.html

[Q72] 查看索引
来源：http://dali.jyoumei.cn/Article/details/gt2urswvneb.html

SHOW INDEX FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2elmsfefl.html

[Q73] 查看表状态
来源：http://dali.ehwqpu.com/Article/details/gt2pgoudedx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.nanxinkj.top/Article/details/gt2zdjemrde.html

[Q74] 强制使用索引
来源：http://dali.yanxiufei.cn/Article/details/gt2pbsaeiwa.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ivvv.top/Article/details/gt2fsossbuf.html

[Q75] 日期格式化
来源：http://dali.wangshuangyany.cn/Article/details/gt2cqbjosmn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bntopuap.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.nwbrower.top/Article/details/gt2jqnxbkkc.html

[Q76] 按天统计
来源：http://dali.cucudq.cn/Article/details/gt2acfvwwwp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hgcussdb.html

[Q77] 时间加减
来源：http://dali.wangdashe.top/Article/details/gt2qjvdmslq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yj202588.top/Article/details/gt2xuofjfvs.html

[Q78] 当前时间
来源：http://dali.nanxinkj.top/Article/details/gt2mzoraoqb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hammf.cn/Article/details/gt2czoypgmy.html

[Q79] 字符串拼接
来源：http://dali.zhiwuduotai.top/Article/details/gt2ebepqqzg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.aizwys.cn/Article/details/gt2gvodfyxz.html

[Q80] 字符串截取
来源：http://dali.wangshuangyany.cn/Article/details/gt2twoypkby.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2lbjevfwm.html

[Q81] 字符串替换
来源：http://dali.smart0.xyz/Article/details/gt2hiowjccq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2nwxxlwwu.html

[Q82] 字符长度与字节长度
来源：http://dali.dianchejie.cn/Article/details/gt2tseaudhi.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.meibo888.top/Article/details/gt2nalxqzpn.html

[Q83] 大小写转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tmujhqsl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.meibo888.top/Article/details/gt2qqusjsms.html

[Q84] 去除首尾空格
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nflshaxv.html

SELECT TRIM(name) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2eqbwqsit.html

[Q85] 数值取整
来源：http://dali.xinyue.icu/Article/details/gt2esvelprl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ppjwa.cn/Article/details/gt2dloqpuuy.html

[Q86] 读取 JSON 字段
来源：http://dali.hnxiangtu.top/Article/details/gt2bkgxujdc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.gzhubu.top/Article/details/gt2xofujceh.html

[Q87] JSON 字段做条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2khnbaiqe.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.bjfxy.top/Article/details/gt2pvjonoxu.html

[Q88] 行转列（条件聚合）
来源：http://dali.snrcjt.cn/Article/details/gt2tmmaamhr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.sysykeji.top/Article/details/gt2cmujzrul.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2sgdjufay.html

[Q89] 判断表是否存在
来源：http://dali.hnqzz.top/Article/details/gt2juqjoqgr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.bjfxy.top/Article/details/gt2mrzbbxbf.html

[Q90] 生成序号列
来源：http://dali.xuetiantiany.cn/Article/details/gt2kwqudany.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinqigufen.top/Article/details/gt2gsbkjcvi.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2tsfkllot.html

R. Bash 专题
来源：http://dali.jyoumei.cn/Article/details/gt2xhuydndn.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2grvkcvkf.html

[R01] shebang 与严格模式
来源：http://dali.gogol.net.cn/Article/details/gt2drrkiwpq.html

#!/usr/bin/env bash
来源：http://dali.shzxlz.cn/Article/details/gt2qznmezjg.html

set -euo pipefail
来源：http://dali.smart0.xyz/Article/details/gt2iwfturwg.html

[R02] 变量赋值与使用
来源：http://dali.shuidangran.top/Article/details/gt2ayyxrulz.html

name="Tom"; echo "$name"
来源：http://dali.daria6918.cn/Article/details/gt2wizzntoy.html

[R03] 只读变量
来源：http://dali.xylfe.cn/Article/details/gt2ffonoskd.html

readonly PI=3.14
来源：http://dali.smart0.xyz/Article/details/gt2sosmagwr.html

[R04] 位置参数
来源：http://dali.yueranfly.top/Article/details/gt2mzhodare.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yvedp.cn/Article/details/gt2atvmiclj.html

[R05] 参数默认值
来源：http://dali.yongpay.top/Article/details/gt2utukrofk.html

name="${1:-default}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2pdglsdyh.html

[R06] 判断命令是否存在
来源：http://dali.nanxinkj.top/Article/details/gt2owzftgzn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.316326.xyz/Article/details/gt2hkocrjla.html

[R07] if 判断文件
来源：http://dali.xziqi.cn/Article/details/gt2ebkooxtl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.svipenyu.cn/Article/details/gt2cydqtlfv.html

[R08] 数值比较
来源：http://dali.jlsjyb.cn/Article/details/gt2hcaaldbx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shuidangran.top/Article/details/gt2owfmkxzu.html

[R09] 字符串比较
来源：http://dali.jlsjyb.cn/Article/details/gt2xpbzxalh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jiagoushi.top/Article/details/gt2yncylrqq.html

[R10] 正则匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bmnjjuuv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.iojbl.cn/Article/details/gt2hganofqh.html

[R11] case 多分支
来源：http://dali.hnxiangtu.top/Article/details/gt2vuizosig.html

case "$1" in
来源：http://dali.ehwqpu.com/Article/details/gt2rzkrvglb.html

start) echo "启动" ;;
来源：http://dali.aibaodan.cn/Article/details/gt2prnojcav.html

stop)  echo "停止" ;;
来源：http://dali.havefunace.top/Article/details/gt2syzthkmg.html

*)     echo "未知命令" ;;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iqboilub.html

esac
来源：http://dali.yonumen.top/Article/details/gt2oaccoxzr.html

[R12] for 遍历文件
来源：http://dali.c1oappe.top/Article/details/gt2lptadmet.html

for f in *.txt; do echo "$f"; done
来源：http://dali.guowangkeji.top/Article/details/gt2hscihwag.html

[R13] for 计数循环
来源：http://dali.fzhhl.top/Article/details/gt2uzveyekh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hfpthk.cn/Article/details/gt2ajnlrscj.html

[R14] C 风格 for
来源：http://dali.yvedp.cn/Article/details/gt2eoacawkt.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.smart0.xyz/Article/details/gt2wwqyyvzb.html

[R15] while 逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gt2uooapddx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.snrcjt.cn/Article/details/gt2zikmffnu.html

[R16] until 等待条件
来源：http://dali.feifeiyinyue.top/Article/details/gt2dvligfqs.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.chenlongwang.top/Article/details/gt2gedoxhcq.html

[R17] 数组定义与取值
来源：http://dali.dianchejie.cn/Article/details/gt2baulsukr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cdnleiting.top/Article/details/gt2xvbigpkn.html

[R18] 遍历数组
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kamyhzxc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jqgfzy.top/Article/details/gt2tgjmxaua.html

[R19] 数组长度
来源：http://dali.ppjwa.cn/Article/details/gt2ocvbaaet.html

echo "${#arr[@]}"
来源：http://dali.tanke756.top/Article/details/gt2zxfqwonw.html

[R20] 关联数组（字典）
来源：http://dali.cheryme.top/Article/details/gt2spimrffd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shzxlz.cn/Article/details/gt2achvbydz.html

[R21] 字符串长度
来源：http://dali.yvedp.cn/Article/details/gt2sythzxmy.html

echo "${#s}"
来源：http://dali.jlsjyb.cn/Article/details/gt2vzkhizkm.html

[R22] 截取子串
来源：http://dali.hfpthk.cn/Article/details/gt2gtxxbgoz.html

echo "${s:0:5}"
来源：http://dali.daxiang520.top/Article/details/gt2pbrxiykm.html

[R23] 字符串替换
来源：http://dali.0kj1m.cn/Article/details/gt2ttveutpa.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yangfankeji.com/Article/details/gt2adphwmiy.html

[R24] 大小写转换
来源：http://dali.c1oappe.top/Article/details/gt2tknypxai.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.guowangkeji.top/Article/details/gt2pxwncpsy.html

[R25] 去后缀 / 去前缀
来源：http://dali.sufxvd.cn/Article/details/gt2eylqhjkt.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yanxiufei.cn/Article/details/gt2jntnzyzc.html

[R26] 命令替换
来源：http://dali.yueranfly.top/Article/details/gt2hnnuepnh.html

now=$(date +%F); echo "$now"
来源：http://dali.hywenlv.cn/Article/details/gt2aafmopla.html

[R27] 算术展开
来源：http://dali.chenzaomai.com/Article/details/gt2dplucfwp.html

echo $((1 + 2 * 3))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2szwnwqli.html

[R28] 浮点运算
来源：http://dali.feifeiyinyue.top/Article/details/gt2mdekzmtz.html

echo "scale=2; 10/3" | bc
来源：http://dali.pycfn.com/Article/details/gt2qzqclczf.html

[R29] 定义函数
来源：http://dali.mhx1999.top/Article/details/gt2hygkozvx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.pengpengdd.cyou/Article/details/gt2xergfvom.html

[R30] 函数返回状态码
来源：http://dali.haohaochexian.top/Article/details/gt2ngrrnxdr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.dashuyun.cn/Article/details/gt2hythgcda.html

[R31] 局部变量
来源：http://dali.svipenyu.cn/Article/details/gt2kpmnvxmj.html

f() { local x=1; echo "$x"; }
来源：http://dali.yj20258.top/Article/details/gt2ynfvirvd.html

[R32] 参数个数校验
来源：http://dali.svipenyu.cn/Article/details/gt2uqaobtyo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yonumen.top/Article/details/gt2owpislsr.html

[R33] 捕获错误并提示行号
来源：http://dali.316326.xyz/Article/details/gt2igrjlbdb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yuanzhike.top/Article/details/gt2gjcbnmvr.html

[R34] 退出时清理
来源：http://dali.smart0.xyz/Article/details/gt2xtfhzqvc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hywenlv.cn/Article/details/gt2ucqghgeh.html

[R35] 后台执行并等待
来源：http://dali.hongshengwenyu.top/Article/details/gt2ncltktcq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.nwbrower.top/Article/details/gt2jxipnefc.html

[R36] 并发执行多个任务
来源：http://dali.zdqjudy.top/Article/details/gt2yqevqjjr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.bjfxy.top/Article/details/gt2ffxvjdiy.html

[R37] 把输出赋给变量
来源：http://dali.jlsjyb.cn/Article/details/gt2tqejsvft.html

files=$(ls -1)
来源：http://dali.gogol.net.cn/Article/details/gt2whyzljfs.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2fnurvulq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yj20258.top/Article/details/gt2vnatucaq.html

[R39] 重定向标准输出与错误
来源：http://dali.yuxming.cn/Article/details/gt2uvolykkd.html

cmd > out.log 2>&1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2npsmtnoy.html

[R40] 追加写日志
来源：http://dali.jqgfzy.top/Article/details/gt2xalxijgn.html

echo "log" >> out.log
来源：http://dali.hnxiangtu.top/Article/details/gt2tqtqtvyq.html

[R41] 丢弃输出
来源：http://dali.haohaochexian.top/Article/details/gt2nvppqgal.html

cmd >/dev/null 2>&1
来源：http://dali.chenjidiqi.icu/Article/details/gt2zgfkcwro.html

[R42] 输入重定向
来源：http://dali.wangdashe.top/Article/details/gt2heilzqjv.html

wc -l < a.txt
来源：http://dali.haohaochexian.top/Article/details/gt2oiwqwghl.html

[R43] 按名字查找文件
来源：http://dali.guannengcc.top/Article/details/gt2wjrngioi.html

find . -name "*.log" -type f
来源：http://dali.ydzc1.top/Article/details/gt2lqwnrlzn.html

[R44] 按修改时间查找
来源：http://dali.zhengqikj.top/Article/details/gt2wtfriuqw.html

find . -mtime -7 -type f
来源：http://dali.cashguo.top/Article/details/gt2tfioowtw.html

[R45] 批量删除
来源：http://dali.quarkkingdee.top/Article/details/gt2dfhtlboa.html

find . -name "*.tmp" -delete
来源：http://dali.ivvv.top/Article/details/gt2yolyykhy.html

[R46] 递归替换文件内容
来源：http://dali.ybcxt.top/Article/details/gt2hvfhdhbi.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cashguo.top/Article/details/gt2mpdkhnbl.html

[R47] sed 单行替换
来源：http://dali.cucudq.cn/Article/details/gt2uflioxud.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hammf.cn/Article/details/gt2oljkxpoy.html

[R48] awk 取指定列
来源：http://dali.sysykeji.top/Article/details/gt2lnwhhhvx.html

awk '{print $1, $3}' a.txt
来源：http://dali.jyoumei.cn/Article/details/gt2najokrer.html

[R49] awk 带条件
来源：http://dali.yonumen.top/Article/details/gt2scyfusqe.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hywenlv.cn/Article/details/gt2cvkthctu.html

[R50] awk 求和
来源：http://dali.yuanzhike.top/Article/details/gt2izfzatfw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jqgufenzy.top/Article/details/gt2yahkvxez.html

[R51] 排序去重取前几
来源：http://dali.jiagoushi.top/Article/details/gt2kvfthagw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.kuanghao11.cn/Article/details/gt2xlxpxfkp.html

[R52] 统计行数
来源：http://dali.yanxiufei.cn/Article/details/gt2qnnqtwlf.html

wc -l a.txt
来源：http://dali.yueranfly.top/Article/details/gt2pycyozrv.html

[R53] 查看文件头与实时尾
来源：http://dali.bjfxy.top/Article/details/gt2wosooklu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yonumen.top/Article/details/gt2hbwwyzlq.html

[R54] 比较两个文件
来源：http://dali.yvedp.cn/Article/details/gt2ntswkand.html

diff a.txt b.txt
来源：http://dali.vqdsnc.cn/Article/details/gt2rprngkhy.html

[R55] 压缩与解压
来源：http://dali.yangfankeji.com/Article/details/gt2qhnvgtqw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vphtxzas.html

[R56] 远程拷贝
来源：http://dali.tian-w.cn/Article/details/gt2mugrqgnw.html

scp file user@host:/path/
来源：http://dali.c1oappe.top/Article/details/gt2lvtvcfdp.html

[R57] 远程执行命令
来源：http://dali.fengsongda.top/Article/details/gt2rvoflvum.html

ssh user@host 'uptime'
来源：http://dali.gaohongyu789.top/Article/details/gt2ssikmpsk.html

[R58] 下载文件
来源：http://dali.xuanzx.com/Article/details/gt2lwwjbrzc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shzxlz.cn/Article/details/gt2gizzgznp.html

[R59] 发 POST JSON
来源：http://dali.daxiang520.top/Article/details/gt2whyzbdys.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gzhubu.top/Article/details/gt2xlheikar.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhoulong.xyz/Article/details/gt2npivcqby.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jianghu66.top/Article/details/gt2hcrxmqfw.html

[R61] 磁盘占用
来源：http://dali.shzxlz.cn/Article/details/gt2wjyjaags.html

df -h;  du -sh *
来源：http://dali.gzhubu.top/Article/details/gt2kkglmipz.html

[R62] 找最占空间的文件
来源：http://dali.sysykeji.top/Article/details/gt2bemavkug.html

du -ah . | sort -rh | head -10
来源：http://dali.jlsjyb.cn/Article/details/gt2tjujulkv.html

[R63] 内存与进程
来源：http://dali.nanxuanxn.top/Article/details/gt2bdpkmeja.html

free -h;  ps aux | grep nginx
来源：http://dali.hammf.cn/Article/details/gt2bbeainyo.html

[R64] 结束进程
来源：http://dali.ydzc1.top/Article/details/gt2bgbvcufu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.c1oappe.top/Article/details/gt2fzepnlyc.html

[R65] 查看端口占用
来源：http://dali.jqgfzy.top/Article/details/gt2xtckueoc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jqgufenzy.top/Article/details/gt2gipyzwry.html

[R66] 定时任务
来源：http://dali.aibaodan.cn/Article/details/gt2udvtxrri.html

crontab -e;  crontab -l
来源：http://dali.feifeiyinyue.top/Article/details/gt2hhcvixtz.html

[R67] 生成随机十六进制串
来源：http://dali.zhoulong.xyz/Article/details/gt2oyzucakj.html

openssl rand -hex 16
来源：http://dali.zhiwuduotai.top/Article/details/gt2pedggqxr.html

[R68] 计算文件校验值
来源：http://dali.zhoulong.xyz/Article/details/gt2ehbhmfma.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gt2vrcaxmhr.html

[R69] 生成随机密码
来源：http://dali.dashuyun.cn/Article/details/gt2aaxkhkrc.html

head -c 16 /dev/urandom | base64
来源：http://dali.pengpengdd.cyou/Article/details/gt2ybaijvqm.html

[R70] 时间戳与互转
来源：http://dali.xziqi.cn/Article/details/gt2scieblqs.html

date +%s;  date -d @1700000000
来源：http://dali.hammf.cn/Article/details/gt2yvuxyzyt.html

[R71] 日期格式化
来源：http://dali.jlsjyb.cn/Article/details/gt2uywissfh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fiwdtxpc.html

[R72] 等待端口就绪
来源：http://dali.jiagoushi.top/Article/details/gt2rfkmymuc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.tanke756.top/Article/details/gt2lunmzokw.html

[R73] 分割大日志
来源：http://dali.nanxinkj.top/Article/details/gt2zkhjmobf.html

split -l 1000 big.log part_
来源：http://dali.cashguo.top/Article/details/gt2glxbczzt.html

[R74] 批量重命名
来源：http://dali.zdqjudy.top/Article/details/gt2vkerysol.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.kuanghao11.cn/Article/details/gt2jtaaxrhk.html

[R75] 导出环境变量
来源：http://dali.wangdashe.top/Article/details/gt2dntxcgob.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jianghu66.top/Article/details/gt2npgdycsh.html

[R76] 使用临时文件
来源：http://dali.haohaochexian.top/Article/details/gt2lfelooeo.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qpymepdq.html

[R77] 读取用户输入
来源：http://dali.cucudq.cn/Article/details/gt2wgyzeazu.html

read -rp "请输入: " ans
来源：http://dali.gotoacloud.top/Article/details/gt2qkyniuku.html

[R78] 交互式菜单
来源：http://dali.shzxlz.cn/Article/details/gt2cazkffck.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shangyingyoupin.top/Article/details/gt2pldnjxij.html

[R79] 解析命令行选项
来源：http://dali.zhongyouzk.top/Article/details/gt2gavgqafz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yonumen.top/Article/details/gt2svxgaoem.html

[R80] 查看脚本执行耗时
来源：http://dali.chenjidiqi.icu/Article/details/gt2nmbivdey.html

time ./run.sh
来源：http://dali.yvedp.cn/Article/details/gt2kqjtpfro.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2xdpggonm.html

S. C / C++ 专题
来源：http://dali.jinqigfzy.top/Article/details/gt2jzhhjzdx.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2ortpsyom.html

[S01] C：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gt2rpppnwiv.html

#include <stdio.h>
来源：http://dali.ivvv.top/Article/details/gt2fwwehddr.html


<!-- 参考信息 -->