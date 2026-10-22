代发 wailian999

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2tltjqdhl.html

[Q30] 分组统计
来源：http://dali.jiagoushi.top/Article/details/gt2tpyuioly.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sxryk.cn/Article/details/gt2ptyllrkz.html

[Q31] 分组后过滤
来源：http://dali.chenzaomai.com/Article/details/gt2wfotaqyu.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vkqgbtww.html

[Q32] 分组拼接字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2lyjjaqht.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.aizwys.cn/Article/details/gt2ybwdoipt.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zdqjudy.top/Article/details/gt2pwdmthfp.html

[Q33] 多列分组
来源：http://dali.jqgfzy.top/Article/details/gt2iexguwgx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.wangdashe.top/Article/details/gt2iiwfaojr.html

[Q34] 每组取第一条
来源：http://dali.birdmap.top/Article/details/gt2actcpndc.html

SELECT * FROM (
来源：http://dali.shuidangran.top/Article/details/gt2edkjcsgo.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gotoacloud.top/Article/details/gt2ilhoxngl.html

) t WHERE rn = 1;
来源：http://dali.316326.xyz/Article/details/gt2noibmlur.html

[Q35] 内连接
来源：http://dali.cucudq.cn/Article/details/gt2lqdbnsqd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.smart0.xyz/Article/details/gt2bdimysoz.html

[Q36] 左连接
来源：http://dali.cheryme.top/Article/details/gt2ldavgrrd.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gzhubu.top/Article/details/gt2ioekhbib.html

[Q37] 右连接
来源：http://dali.yuanzhike.top/Article/details/gt2mayxrqnv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shuidangran.top/Article/details/gt2lntuzsmz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yanxiufei.cn/Article/details/gt2narxtlzi.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.snrcjt.cn/Article/details/gt2rizmyyle.html

[Q39] 自连接（查上下级）
来源：http://dali.jlsjyb.cn/Article/details/gt2yuioexrt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhongyouzk.top/Article/details/gt2sjgiuygb.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhengqikj.top/Article/details/gt2kqtdswpf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jinqigufen.top/Article/details/gt2xpylloac.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.redwolf501.top/Article/details/gt2ldgctbsd.html

[Q41] 多表连接
来源：http://dali.jlsjyb.cn/Article/details/gt2mtyzmewq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ivvv.top/Article/details/gt2xqsjybaz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.redwolf501.top/Article/details/gt2vfrwlxyz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jlsjyb.cn/Article/details/gt2rtvtiijl.html

[Q42] 连接条件附加过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jelbkehv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.tianlin.xyz/Article/details/gt2molmhrvg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.dashuyun.cn/Article/details/gt2wmyahofm.html

[Q43] 标量子查询
来源：http://dali.bjfxy.top/Article/details/gt2otrcfcaa.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jinqigfzy.top/Article/details/gt2ggavxvnw.html

[Q44] IN 子查询
来源：http://dali.0kj1m.cn/Article/details/gt2wlpcaeyb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cqqwz.cn/Article/details/gt2veflxrft.html

[Q45] EXISTS 判断存在
来源：http://dali.xinyue.icu/Article/details/gt2vgswlaqt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hammf.cn/Article/details/gt2bvgwztii.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jinqigfzy.top/Article/details/gt2jngkoqtw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nanxuanxn.top/Article/details/gt2dcvhptzx.html

[Q47] 与平均值比较
来源：http://dali.yuanzhike.top/Article/details/gt2gkrjyprb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.redwolf501.top/Article/details/gt2sphxuhnd.html

[Q48] CTE 公用表表达式
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dcdmwouo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yuxming.cn/Article/details/gt2cxpaybss.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shuidangran.top/Article/details/gt2pqvajnle.html

[Q49] 更新单行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jhcblqgp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.daxiang520.top/Article/details/gt2vimsmjer.html

[Q50] 批量更新
来源：http://dali.xuanzx.com/Article/details/gt2cywynung.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sufxvd.cn/Article/details/gt2drmbowqf.html

[Q51] 用子查询更新
来源：http://dali.jqgfzy.top/Article/details/gt2fvyjdhgr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tooesdxo.html

[Q52] 删除指定行
来源：http://dali.cheryme.top/Article/details/gt2rgvtsdsl.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mssbunrb.html

[Q53] 按条件删除
来源：http://dali.dianchejie.cn/Article/details/gt2htbelpuo.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.haohaochexian.top/Article/details/gt2krkepltl.html

[Q54] 清空表
来源：http://dali.xziqi.cn/Article/details/gt2oofegnpl.html

TRUNCATE TABLE logs;
来源：http://dali.meibo888.top/Article/details/gt2neypdmsz.html

[Q55] 排名（并列占位）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qedqhzsp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.dianchejie.cn/Article/details/gt2dyhbagmu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shuidangran.top/Article/details/gt2paorwvhu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hfpthk.cn/Article/details/gt2teopvcal.html

[Q57] 行号
来源：http://dali.pycfn.com/Article/details/gt2jnfpvvab.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2bbarupnj.html

[Q58] 累计求和
来源：http://dali.dashuyun.cn/Article/details/gt2hqeimhog.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yongpay.top/Article/details/gt2hiffqfcc.html

[Q59] 分组内累计
来源：http://dali.cheryme.top/Article/details/gt2uwymswha.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gt2njvvglva.html

[Q60] 取上一行 / 下一行
来源：http://dali.nanxuanxn.top/Article/details/gt2mdbwfbrs.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shangyingyoupin.top/Article/details/gt2yhaldnuv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gt2cdnqltdc.html

[Q61] 移动平均
来源：http://dali.yongpay.top/Article/details/gt2ksfjwfrk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gt2hsnwnmuy.html

[Q62] 分组占比
来源：http://dali.gaohongyu789.top/Article/details/gt2kkkfygsi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.smart0.xyz/Article/details/gt2mndobqqs.html

[Q63] 开启事务
来源：http://dali.c1oappe.top/Article/details/gt2krbxlimb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.svipenyu.cn/Article/details/gt2gczhemhi.html

[Q64] 提交事务
来源：http://dali.ivvv.top/Article/details/gt2iuivalfl.html

COMMIT;
来源：http://dali.cheryme.top/Article/details/gt2rbfuygzo.html

[Q65] 回滚事务
来源：http://dali.shuidangran.top/Article/details/gt2bsxectpu.html

ROLLBACK;
来源：http://dali.redwolf501.top/Article/details/gt2eeczducj.html

[Q66] 行锁查询
来源：http://dali.gotoacloud.top/Article/details/gt2itarlzfv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xuetiantiany.cn/Article/details/gt2efojbdwz.html

[Q67] 设置隔离级别
来源：http://dali.tian-w.cn/Article/details/gt2ktmphbpc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.chenlongwang.top/Article/details/gt2stjywack.html

[Q68] 保存点
来源：http://dali.shangyingyoupin.top/Article/details/gt2fpofdghc.html

SAVEPOINT sp1;
来源：http://dali.jinqigfzy.top/Article/details/gt2vlkwdxlt.html

ROLLBACK TO sp1;
来源：http://dali.yj20258888.top/Article/details/gt2dsfbnagv.html

[Q69] 查看执行计划
来源：http://dali.jyoumei.cn/Article/details/gt2gncvlotb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinqigufen.top/Article/details/gt2wnqapblz.html

[Q70] 更新统计信息
来源：http://dali.cheryme.top/Article/details/gt2vjxoqcbm.html

ANALYZE TABLE users;
来源：http://dali.hywenlv.cn/Article/details/gt2rtleqxhr.html

[Q71] 查看建表语句
来源：http://dali.yj20258.top/Article/details/gt2zawobubz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.wangdashe.top/Article/details/gt2ayisrukp.html

[Q72] 查看索引
来源：http://dali.316326.xyz/Article/details/gt2hmmvmpit.html

SHOW INDEX FROM users;
来源：http://dali.zycfv.cn/Article/details/gt2kvsxerae.html

[Q73] 查看表状态
来源：http://dali.gaohongyu789.top/Article/details/gt2kefgbdfe.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhongyouzk.top/Article/details/gt2fdggsgsi.html

[Q74] 强制使用索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dsuucgbq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.dashuyun.cn/Article/details/gt2vjkxnqxk.html

[Q75] 日期格式化
来源：http://dali.yonumen.top/Article/details/gt2zozczdpx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.smart0.xyz/Article/details/gt2jlsiskxy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tiptaqol.html

[Q76] 按天统计
来源：http://dali.yvedp.cn/Article/details/gt2btpnroec.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gotoacloud.top/Article/details/gt2hsqofdge.html

[Q77] 时间加减
来源：http://dali.jqgfzy.top/Article/details/gt2wzvzqvjc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.haohaochexian.top/Article/details/gt2xihsamva.html

[Q78] 当前时间
来源：http://dali.yuxming.cn/Article/details/gt2fynmydwj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ydzc1.top/Article/details/gt2cookcuaf.html

[Q79] 字符串拼接
来源：http://dali.yongpay.top/Article/details/gt2lzwlssfp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.chenjidiqi.icu/Article/details/gt2iwsamrzl.html

[Q80] 字符串截取
来源：http://dali.ybcxt.top/Article/details/gt2kkskjaje.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2lnelpkqh.html

[Q81] 字符串替换
来源：http://dali.chenjidiqi.icu/Article/details/gt2ssxwhvrq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2zwrybbbw.html

[Q82] 字符长度与字节长度
来源：http://dali.sufxvd.cn/Article/details/gt2fjiulilj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bbdafslc.html

[Q83] 大小写转换
来源：http://dali.sysykeji.top/Article/details/gt2hmsrfsdr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2qjgpojes.html

[Q84] 去除首尾空格
来源：http://dali.chenlongwang.top/Article/details/gt2xoekbvil.html

SELECT TRIM(name) FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2lwbzlstf.html

[Q85] 数值取整
来源：http://dali.yj20258888.top/Article/details/gt2qiffjozj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhoulong.xyz/Article/details/gt2eweicaih.html

[Q86] 读取 JSON 字段
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wmfblivc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.tian-w.cn/Article/details/gt2gclseecp.html

[Q87] JSON 字段做条件
来源：http://dali.9152youxi.cn/Article/details/gt2glmygxsd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.0kj1m.cn/Article/details/gt2ipkzuvjw.html

[Q88] 行转列（条件聚合）
来源：http://dali.dianchejie.cn/Article/details/gt2cslebmuy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.redwolf501.top/Article/details/gt2cfhiybnp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2oaojkvhi.html

[Q89] 判断表是否存在
来源：http://dali.iojbl.cn/Article/details/gt2jjyaeump.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.vqdsnc.cn/Article/details/gt2jhpvzojs.html

[Q90] 生成序号列
来源：http://dali.hywenlv.cn/Article/details/gt2ialtzfpl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.guannengcc.top/Article/details/gt2stvlbune.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2lapbsjpk.html

R. Bash 专题
来源：http://dali.smart0.xyz/Article/details/gt2pwhxptmc.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2qffuqwyc.html

[R01] shebang 与严格模式
来源：http://dali.hysaishi.cn/Article/details/gt2dwyrdzhy.html

#!/usr/bin/env bash
来源：http://dali.vqdsnc.cn/Article/details/gt2vjvailzv.html

set -euo pipefail
来源：http://dali.yuanzhike.top/Article/details/gt2bhcdsrqa.html

[R02] 变量赋值与使用
来源：http://dali.cheryme.top/Article/details/gt2dvroravn.html

name="Tom"; echo "$name"
来源：http://dali.zhiwuduotai.top/Article/details/gt2izjucwac.html

[R03] 只读变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rglvtyuo.html

readonly PI=3.14
来源：http://dali.jinqigfzy.top/Article/details/gt2bizeowcw.html

[R04] 位置参数
来源：http://dali.birdmap.top/Article/details/gt2vzuplbuq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gaohongyu789.top/Article/details/gt2mnsjuofa.html

[R05] 参数默认值
来源：http://dali.xziqi.cn/Article/details/gt2falaowjz.html

name="${1:-default}"
来源：http://dali.yonumen.top/Article/details/gt2elwuegyh.html

[R06] 判断命令是否存在
来源：http://dali.hywenlv.cn/Article/details/gt2hwsxmmvj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xinyue.icu/Article/details/gt2edhqalqf.html

[R07] if 判断文件
来源：http://dali.daria6918.cn/Article/details/gt2mcxgeslz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yongpay.top/Article/details/gt2gojdobrj.html

[R08] 数值比较
来源：http://dali.gzhubu.top/Article/details/gt2wizxscnm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sufxvd.cn/Article/details/gt2ddmxjjer.html

[R09] 字符串比较
来源：http://dali.pycfn.com/Article/details/gt2uiikxdxp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.dashuyun.cn/Article/details/gt2khqevpfw.html

[R10] 正则匹配
来源：http://dali.c1oappe.top/Article/details/gt2ghwabqok.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.guowangkeji.top/Article/details/gt2hpkyzijl.html

[R11] case 多分支
来源：http://dali.zhoulong.xyz/Article/details/gt2jjpendxd.html

case "$1" in
来源：http://dali.yueranfly.top/Article/details/gt2qqvfsyrv.html

start) echo "启动" ;;
来源：http://dali.nanxuanxn.top/Article/details/gt2gkidxgtd.html

stop)  echo "停止" ;;
来源：http://dali.aibaodan.cn/Article/details/gt2diyaffix.html

*)     echo "未知命令" ;;
来源：http://dali.smart0.xyz/Article/details/gt2sdjzyhwk.html

esac
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rulleznl.html

[R12] for 遍历文件
来源：http://dali.tianlin.xyz/Article/details/gt2gdjpcgnu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ppjwa.cn/Article/details/gt2hkoxmqyg.html

[R13] for 计数循环
来源：http://dali.xylfe.cn/Article/details/gt2nwadbdfd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.chenlongwang.top/Article/details/gt2bxkcrmlo.html

[R14] C 风格 for
来源：http://dali.kuanghao11.cn/Article/details/gt2roijvgei.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xziqi.cn/Article/details/gt2zhigmwix.html

[R15] while 逐行读文件
来源：http://dali.sxryk.cn/Article/details/gt2isrgrgdj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.daria6918.cn/Article/details/gt2tkcbhnif.html

[R16] until 等待条件
来源：http://dali.dianchejie.cn/Article/details/gt2gtwhjxjr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhixingplan.top/Article/details/gt2ctejdrwi.html

[R17] 数组定义与取值
来源：http://dali.andypj.xyz/Article/details/gt2ekezsaog.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cqqwz.cn/Article/details/gt2bmhmscrb.html

[R18] 遍历数组
来源：http://dali.xuetiantiany.cn/Article/details/gt2drfpucvz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.nanxuanxn.top/Article/details/gt2qbjfqbag.html

[R19] 数组长度
来源：http://dali.cucudq.cn/Article/details/gt2zqfroymp.html

echo "${#arr[@]}"
来源：http://dali.aizwys.cn/Article/details/gt2iazdiaym.html

[R20] 关联数组（字典）
来源：http://dali.hfpthk.cn/Article/details/gt2diojzrvb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.andypj.xyz/Article/details/gt2formzkam.html

[R21] 字符串长度
来源：http://dali.daxiang520.top/Article/details/gt2vdspczxe.html

echo "${#s}"
来源：http://dali.mhx1999.top/Article/details/gt2wskhzaun.html

[R22] 截取子串
来源：http://dali.chenlongwang.top/Article/details/gt2dwzwdkze.html

echo "${s:0:5}"
来源：http://dali.xinyue.icu/Article/details/gt2leuephwd.html

[R23] 字符串替换
来源：http://dali.smart0.xyz/Article/details/gt2riopronm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhongyouzk.top/Article/details/gt2awwqtnrf.html

[R24] 大小写转换
来源：http://dali.havefunace.top/Article/details/gt2bbviwlyx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2shshstkn.html

[R25] 去后缀 / 去前缀
来源：http://dali.yongpay.top/Article/details/gt2vmnxnbpo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.gogol.net.cn/Article/details/gt2fcrglejt.html

[R26] 命令替换
来源：http://dali.9152youxi.cn/Article/details/gt2oxisegre.html

now=$(date +%F); echo "$now"
来源：http://dali.zhengqikj.top/Article/details/gt2yqtkyftl.html

[R27] 算术展开
来源：http://dali.haohaochexian.top/Article/details/gt2sbatlbns.html

echo $((1 + 2 * 3))
来源：http://dali.nanxinkj.top/Article/details/gt2wsnvttlg.html

[R28] 浮点运算
来源：http://dali.hywenlv.cn/Article/details/gt2eyhhusks.html

echo "scale=2; 10/3" | bc
来源：http://dali.jqgfzy.top/Article/details/gt2yyyvygdm.html

[R29] 定义函数
来源：http://dali.mhx1999.top/Article/details/gt2fgudmrdw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cucudq.cn/Article/details/gt2eflykgkl.html

[R30] 函数返回状态码
来源：http://dali.zhoulong.xyz/Article/details/gt2elchhtig.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hfpthk.cn/Article/details/gt2crofadmc.html

[R31] 局部变量
来源：http://dali.wangdashe.top/Article/details/gt2xqdppamm.html

f() { local x=1; echo "$x"; }
来源：http://dali.dashuyun.cn/Article/details/gt2ihjyebjj.html

[R32] 参数个数校验
来源：http://dali.yuanzhike.top/Article/details/gt2qffguiro.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jlsjyb.cn/Article/details/gt2breizrkv.html

[R33] 捕获错误并提示行号
来源：http://dali.gzhubu.top/Article/details/gt2cnlatmen.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cashguo.top/Article/details/gt2fqhkhhvp.html

[R34] 退出时清理
来源：http://dali.hammf.cn/Article/details/gt2hcmcrzsk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.birdmap.top/Article/details/gt2hmafcyqa.html

[R35] 后台执行并等待
来源：http://dali.yj20258888.top/Article/details/gt2cnzpahaw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jyoumei.cn/Article/details/gt2vvoevfqr.html

[R36] 并发执行多个任务
来源：http://dali.sufxvd.cn/Article/details/gt2ofzpuokz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jyoumei.cn/Article/details/gt2ndzoqyxw.html

[R37] 把输出赋给变量
来源：http://dali.birdmap.top/Article/details/gt2estwofwe.html

files=$(ls -1)
来源：http://dali.aibaodan.cn/Article/details/gt2stgfkkwa.html

[R38] 管道串联
来源：http://dali.zdqjudy.top/Article/details/gt2kxfigfqs.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hongshengwenyu.top/Article/details/gt2bcszmzma.html

[R39] 重定向标准输出与错误
来源：http://dali.0kj1m.cn/Article/details/gt2gznahhbt.html

cmd > out.log 2>&1
来源：http://dali.gaohongyu789.top/Article/details/gt2jlgrcnth.html

[R40] 追加写日志
来源：http://dali.xuanzx.com/Article/details/gt2kbqcosbt.html

echo "log" >> out.log
来源：http://dali.fengsongda.top/Article/details/gt2kmxaatxr.html

[R41] 丢弃输出
来源：http://dali.ivvv.top/Article/details/gt2fpwdjwdp.html

cmd >/dev/null 2>&1
来源：http://dali.hysaishi.cn/Article/details/gt2qtejobjc.html

[R42] 输入重定向
来源：http://dali.hongshengwenyu.top/Article/details/gt2mnegkduk.html

wc -l < a.txt
来源：http://dali.0kj1m.cn/Article/details/gt2zbzogmdn.html

[R43] 按名字查找文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jxxejdml.html

find . -name "*.log" -type f
来源：http://dali.9152youxi.cn/Article/details/gt2zldqngpb.html

[R44] 按修改时间查找
来源：http://dali.yangfankeji.com/Article/details/gt2lblfmujq.html

find . -mtime -7 -type f
来源：http://dali.cashguo.top/Article/details/gt2gowvlpmo.html

[R45] 批量删除
来源：http://dali.316326.xyz/Article/details/gt2nipujqfd.html

find . -name "*.tmp" -delete
来源：http://dali.jiagoushi.top/Article/details/gt2gbspysbt.html

[R46] 递归替换文件内容
来源：http://dali.fzhhl.top/Article/details/gt2rtgpnemm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ybcxt.top/Article/details/gt2yoqqlvxs.html

[R47] sed 单行替换
来源：http://dali.wangshuangyany.cn/Article/details/gt2hkrvghly.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.haohaochexian.top/Article/details/gt2pttwrhnu.html

[R48] awk 取指定列
来源：http://dali.iojbl.cn/Article/details/gt2qdhplmyi.html

awk '{print $1, $3}' a.txt
来源：http://dali.guannengcc.top/Article/details/gt2wedzhyzo.html

[R49] awk 带条件
来源：http://dali.aizwys.cn/Article/details/gt2iiwtzrzm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.wangshuangyany.cn/Article/details/gt2oyxwldhi.html

[R50] awk 求和
来源：http://dali.jinqigufen.top/Article/details/gt2idooyboi.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ivvv.top/Article/details/gt2sehbaxak.html

[R51] 排序去重取前几
来源：http://dali.hnqzz.top/Article/details/gt2yzqmnefo.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhixingplan.top/Article/details/gt2dtigobhc.html

[R52] 统计行数
来源：http://dali.iojbl.cn/Article/details/gt2dkqbzuqw.html

wc -l a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gt2ovfdrxzb.html

[R53] 查看文件头与实时尾
来源：http://dali.gotoacloud.top/Article/details/gt2cpqyzewn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shuidangran.top/Article/details/gt2zjowuerw.html

[R54] 比较两个文件
来源：http://dali.daria6918.cn/Article/details/gt2imgyyfqy.html

diff a.txt b.txt
来源：http://dali.yangfankeji.com/Article/details/gt2ughibkwz.html

[R55] 压缩与解压
来源：http://dali.yonumen.top/Article/details/gt2vcxjkplr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2weiulcri.html

[R56] 远程拷贝
来源：http://dali.jqgfzy.top/Article/details/gt2ohpipsqd.html

scp file user@host:/path/
来源：http://dali.hnxiangtu.top/Article/details/gt2wcjhkaqu.html

[R57] 远程执行命令
来源：http://dali.c1oappe.top/Article/details/gt2kmkmyccr.html

ssh user@host 'uptime'
来源：http://dali.aizwys.cn/Article/details/gt2peacuvrk.html

[R58] 下载文件
来源：http://dali.zhoulong.xyz/Article/details/gt2dqeeakqr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.havefunace.top/Article/details/gt2ccbabqmg.html

[R59] 发 POST JSON
来源：http://dali.fzhhl.top/Article/details/gt2wismqgcc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.9152youxi.cn/Article/details/gt2qnxnmyzl.html

[R60] 只看 HTTP 状态码
来源：http://dali.aizwys.cn/Article/details/gt2uqcjzxsw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.kuanghao11.cn/Article/details/gt2zwqdudkw.html

[R61] 磁盘占用
来源：http://dali.havefunace.top/Article/details/gt2brwjbblh.html

df -h;  du -sh *
来源：http://dali.redwolf501.top/Article/details/gt2mgkbmpkg.html

[R62] 找最占空间的文件
来源：http://dali.9152youxi.cn/Article/details/gt2twmyhpnk.html

du -ah . | sort -rh | head -10
来源：http://dali.redwolf501.top/Article/details/gt2mzozhomv.html

[R63] 内存与进程
来源：http://dali.fzhhl.top/Article/details/gt2bldugjbp.html

free -h;  ps aux | grep nginx
来源：http://dali.jyoumei.cn/Article/details/gt2fbvckjuf.html

[R64] 结束进程
来源：http://dali.yj20258.top/Article/details/gt2sidkshla.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gotoacloud.top/Article/details/gt2dknpmvef.html

[R65] 查看端口占用
来源：http://dali.vqdsnc.cn/Article/details/gt2lzeyttof.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.svipenyu.cn/Article/details/gt2rilagkzs.html

[R66] 定时任务
来源：http://dali.nanxuanxn.top/Article/details/gt2roscadgc.html

crontab -e;  crontab -l
来源：http://dali.cdnleiting.top/Article/details/gt2ovamxiup.html

[R67] 生成随机十六进制串
来源：http://dali.quarkkingdee.top/Article/details/gt2mqpzstam.html

openssl rand -hex 16
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ippnrqoh.html

[R68] 计算文件校验值
来源：http://dali.shzxlz.cn/Article/details/gt2bwdjbwtf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jqgufenzy.top/Article/details/gt2ibjillnk.html

[R69] 生成随机密码
来源：http://dali.zdqjudy.top/Article/details/gt2hzxtculb.html

head -c 16 /dev/urandom | base64
来源：http://dali.xylfe.cn/Article/details/gt2pnceyqcd.html

[R70] 时间戳与互转
来源：http://dali.havefunace.top/Article/details/gt2mwjhcqum.html

date +%s;  date -d @1700000000
来源：http://dali.ybcxt.top/Article/details/gt2uvhuxesc.html

[R71] 日期格式化
来源：http://dali.yj20258888.top/Article/details/gt2vechoxvo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yuanzhike.top/Article/details/gt2fejwytyt.html

[R72] 等待端口就绪
来源：http://dali.yueranfly.top/Article/details/gt2lqkftfwm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hywenlv.cn/Article/details/gt2vosudesi.html

[R73] 分割大日志
来源：http://dali.chenjidiqi.icu/Article/details/gt2crnuctmy.html

split -l 1000 big.log part_
来源：http://dali.vqdsnc.cn/Article/details/gt2ufepqsxa.html

[R74] 批量重命名
来源：http://dali.jinqigufen.top/Article/details/gt2xbmekdmo.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.daria6918.cn/Article/details/gt2wijpznnj.html

[R75] 导出环境变量
来源：http://dali.cdnleiting.top/Article/details/gt2kmrsnkpv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.iojbl.cn/Article/details/gt2wzvyfeng.html

[R76] 使用临时文件
来源：http://dali.bjfxy.top/Article/details/gt2sezyhaso.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgufenzy.top/Article/details/gt2kmlftwgd.html

[R77] 读取用户输入
来源：http://dali.cashguo.top/Article/details/gt2pkkjpjny.html

read -rp "请输入: " ans
来源：http://dali.jiagoushi.top/Article/details/gt2sjwkplra.html

[R78] 交互式菜单
来源：http://dali.hysaishi.cn/Article/details/gt2mzxwjaez.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhoulong.xyz/Article/details/gt2ququhupc.html

[R79] 解析命令行选项
来源：http://dali.fzhhl.top/Article/details/gt2ugbzvrak.html


<!-- 参考信息 -->