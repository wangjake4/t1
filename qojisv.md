代发 wailian999

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2gvmstufa.html

[Q30] 分组统计
来源：http://dali.chenzaomai.com/Article/details/gt2evegtolu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.gzhubu.top/Article/details/gt2jyoszrmf.html

[Q31] 分组后过滤
来源：http://dali.yvedp.cn/Article/details/gt2mhijskgh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yj202588.top/Article/details/gt2bteiarlv.html

[Q32] 分组拼接字符串
来源：http://dali.nanxinkj.top/Article/details/gt2ekiazxqn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bulnhpha.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.tanke756.top/Article/details/gt2ylfxcons.html

[Q33] 多列分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kzlmgxpm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xylfe.cn/Article/details/gt2lixhyphp.html

[Q34] 每组取第一条
来源：http://dali.xuetiantiany.cn/Article/details/gt2nikzgbjq.html

SELECT * FROM (
来源：http://dali.guannengcc.top/Article/details/gt2jjxpydza.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.aibaodan.cn/Article/details/gt2oblguggf.html

) t WHERE rn = 1;
来源：http://dali.xinyue.icu/Article/details/gt2ikablfxe.html

[Q35] 内连接
来源：http://dali.hywenlv.cn/Article/details/gt2tpbgcfuc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.snrcjt.cn/Article/details/gt2rcqtwgnc.html

[Q36] 左连接
来源：http://dali.gzhubu.top/Article/details/gt2mlatkssu.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ybcxt.top/Article/details/gt2jgfuydkz.html

[Q37] 右连接
来源：http://dali.daria6918.cn/Article/details/gt2dojegkgx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.wangshuangyany.cn/Article/details/gt2jaieiyeq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.dianchejie.cn/Article/details/gt2pkyzwbnb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yj20258888.top/Article/details/gt2oegstjbh.html

[Q39] 自连接（查上下级）
来源：http://dali.dashuyun.cn/Article/details/gt2yyryvuqp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.feifeiyinyue.top/Article/details/gt2rkjumwqn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zycfv.cn/Article/details/gt2idodevof.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cdnleiting.top/Article/details/gt2yrnugqqo.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.aibaodan.cn/Article/details/gt2znnzizri.html

[Q41] 多表连接
来源：http://dali.yuxming.cn/Article/details/gt2qsdmtjnp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhongyouzk.top/Article/details/gt2neeqamhu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.dianchejie.cn/Article/details/gt2zprluqfd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xziqi.cn/Article/details/gt2cxkmtwhm.html

[Q42] 连接条件附加过滤
来源：http://dali.shangyingyoupin.top/Article/details/gt2pennsdmu.html

SELECT u.name, o.amount FROM users u
来源：http://dali.nanxuanxn.top/Article/details/gt2wudvjiee.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinqigfzy.top/Article/details/gt2gywcpiwh.html

[Q43] 标量子查询
来源：http://dali.birdmap.top/Article/details/gt2rrplvnit.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fwykglnv.html

[Q44] IN 子查询
来源：http://dali.aizwys.cn/Article/details/gt2ptxugqpf.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.feifeiyinyue.top/Article/details/gt2zoicpmql.html

[Q45] EXISTS 判断存在
来源：http://dali.yj202588.top/Article/details/gt2allpignr.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.daria6918.cn/Article/details/gt2ugxcdmyb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ydzc1.top/Article/details/gt2nylytfsx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zdqjudy.top/Article/details/gt2bszzqkqn.html

[Q47] 与平均值比较
来源：http://dali.wangshuangyany.cn/Article/details/gt2sblkhlyc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zplclcan.html

[Q48] CTE 公用表表达式
来源：http://dali.hongshengwenyu.top/Article/details/gt2vjeokhmt.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.guannengcc.top/Article/details/gt2znjpimuq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shangyingyoupin.top/Article/details/gt2zdvjtkmn.html

[Q49] 更新单行
来源：http://dali.gaohongyu789.top/Article/details/gt2yrywgfhg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.snrcjt.cn/Article/details/gt2tkhygmuu.html

[Q50] 批量更新
来源：http://dali.jyoumei.cn/Article/details/gt2cadibrqb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.redwolf501.top/Article/details/gt2oolyefnz.html

[Q51] 用子查询更新
来源：http://dali.hongshengwenyu.top/Article/details/gt2rctwoblk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.guowangkeji.top/Article/details/gt2wpdytlxi.html

[Q52] 删除指定行
来源：http://dali.zhixingplan.top/Article/details/gt2rzllzgau.html

DELETE FROM users WHERE id = 10;
来源：http://dali.sufxvd.cn/Article/details/gt2eshcicit.html

[Q53] 按条件删除
来源：http://dali.meibo888.top/Article/details/gt2dfhmvwsk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xuanzx.com/Article/details/gt2uzfotbwu.html

[Q54] 清空表
来源：http://dali.dianchejie.cn/Article/details/gt2kdvpwwjt.html

TRUNCATE TABLE logs;
来源：http://dali.birdmap.top/Article/details/gt2iaeetndt.html

[Q55] 排名（并列占位）
来源：http://dali.jianghu66.top/Article/details/gt2xlqqfjwo.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jlsjyb.cn/Article/details/gt2ezojahdh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.gotoacloud.top/Article/details/gt2xhzcckmq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.redwolf501.top/Article/details/gt2zcufsgja.html

[Q57] 行号
来源：http://dali.iojbl.cn/Article/details/gt2habawtdn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gt2uvppxfmh.html

[Q58] 累计求和
来源：http://dali.hongshengwenyu.top/Article/details/gt2aqxosekf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gt2muuufhmc.html

[Q59] 分组内累计
来源：http://dali.hammf.cn/Article/details/gt2wjzqkbsi.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gt2ecivarsb.html

[Q60] 取上一行 / 下一行
来源：http://dali.birdmap.top/Article/details/gt2snhjkbac.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.quarkkingdee.top/Article/details/gt2bigckjyu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gt2idkmaebo.html

[Q61] 移动平均
来源：http://dali.guowangkeji.top/Article/details/gt2fsbchcwx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2twhfhwcy.html

[Q62] 分组占比
来源：http://dali.hnxiangtu.top/Article/details/gt2owsqacxe.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yangfankeji.com/Article/details/gt2yenbtdoa.html

[Q63] 开启事务
来源：http://dali.xziqi.cn/Article/details/gt2qpcojuuj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.gogol.net.cn/Article/details/gt2ijrjucsp.html

[Q64] 提交事务
来源：http://dali.sweek.top/Article/details/gt2hnewogvm.html

COMMIT;
来源：http://dali.havefunace.top/Article/details/gt2oyqioplh.html

[Q65] 回滚事务
来源：http://dali.yj20258.top/Article/details/gt2encxvaja.html

ROLLBACK;
来源：http://dali.xuetiantiany.cn/Article/details/gt2olbeuemu.html

[Q66] 行锁查询
来源：http://dali.tian-w.cn/Article/details/gt2ohexecni.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sweek.top/Article/details/gt2laianipg.html

[Q67] 设置隔离级别
来源：http://dali.yvedp.cn/Article/details/gt2eokcmgme.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cqqwz.cn/Article/details/gt2wfhpkllk.html

[Q68] 保存点
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pivdqlku.html

SAVEPOINT sp1;
来源：http://dali.sweek.top/Article/details/gt2kkxqjoqf.html

ROLLBACK TO sp1;
来源：http://dali.hammf.cn/Article/details/gt2tkhhjtnj.html

[Q69] 查看执行计划
来源：http://dali.nwbrower.top/Article/details/gt2mxtttlhc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yj20258888.top/Article/details/gt2gdpmanln.html

[Q70] 更新统计信息
来源：http://dali.meibo888.top/Article/details/gt2vvnrmqlj.html

ANALYZE TABLE users;
来源：http://dali.aizwys.cn/Article/details/gt2eaxruqrl.html

[Q71] 查看建表语句
来源：http://dali.jianghu66.top/Article/details/gt2alfoovvt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.bjfxy.top/Article/details/gt2ppbjcfmy.html

[Q72] 查看索引
来源：http://dali.pengpengdd.cyou/Article/details/gt2cmpezdxr.html

SHOW INDEX FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gt2opnehfjx.html

[Q73] 查看表状态
来源：http://dali.pycfn.com/Article/details/gt2etktrlse.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ybcxt.top/Article/details/gt2vvqqjkfp.html

[Q74] 强制使用索引
来源：http://dali.shuidangran.top/Article/details/gt2thkvtoby.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jlsjyb.cn/Article/details/gt2vnqrmgpz.html

[Q75] 日期格式化
来源：http://dali.yangfankeji.com/Article/details/gt2fftgjgjf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gt2zqnnppyx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cqqwz.cn/Article/details/gt2hiiayvde.html

[Q76] 按天统计
来源：http://dali.ehwqpu.com/Article/details/gt2rpwxtkor.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yvedp.cn/Article/details/gt2nricrwbr.html

[Q77] 时间加减
来源：http://dali.316326.xyz/Article/details/gt2povijhvy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.chenlongwang.top/Article/details/gt2kybzavfv.html

[Q78] 当前时间
来源：http://dali.jlsjyb.cn/Article/details/gt2hiuwhuva.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cashguo.top/Article/details/gt2jrqyosks.html

[Q79] 字符串拼接
来源：http://dali.fengsongda.top/Article/details/gt2mbbjqbji.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.fzhhl.top/Article/details/gt2yorajdti.html

[Q80] 字符串截取
来源：http://dali.zycfv.cn/Article/details/gt2mqgeylmp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uikoneuq.html

[Q81] 字符串替换
来源：http://dali.9152youxi.cn/Article/details/gt2gslkkxml.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.havefunace.top/Article/details/gt2hiymmhst.html

[Q82] 字符长度与字节长度
来源：http://dali.shangyingyoupin.top/Article/details/gt2uifejmao.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2xehzjwue.html

[Q83] 大小写转换
来源：http://dali.gaohongyu789.top/Article/details/gt2kysmbvzk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jianghu66.top/Article/details/gt2brfuraii.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ukkamizi.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2jodozyfv.html

[Q85] 数值取整
来源：http://dali.cheryme.top/Article/details/gt2cukrrltz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sufxvd.cn/Article/details/gt2xdnqsbpg.html

[Q86] 读取 JSON 字段
来源：http://dali.fengsongda.top/Article/details/gt2zfxkwkgy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hysaishi.cn/Article/details/gt2nfhfzhen.html

[Q87] JSON 字段做条件
来源：http://dali.gaohongyu789.top/Article/details/gt2bathzpmk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xinyue.icu/Article/details/gt2ksqyngla.html

[Q88] 行转列（条件聚合）
来源：http://dali.wangdashe.top/Article/details/gt2xayanzdu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yongpay.top/Article/details/gt2bxueplvw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2nghsgjjs.html

[Q89] 判断表是否存在
来源：http://dali.aizwys.cn/Article/details/gt2gzwqkqit.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.wangshuangyany.cn/Article/details/gt2sjghuyoi.html

[Q90] 生成序号列
来源：http://dali.jqgfzy.top/Article/details/gt2amglauia.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.kuanghao11.cn/Article/details/gt2dpxamrje.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2ohfilyka.html

R. Bash 专题
来源：http://dali.havefunace.top/Article/details/gt2jjfrgtyq.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2dlyblqen.html

[R01] shebang 与严格模式
来源：http://dali.fzhhl.top/Article/details/gt2tdkgiltw.html

#!/usr/bin/env bash
来源：http://dali.iojbl.cn/Article/details/gt2lishbrro.html

set -euo pipefail
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tterqmiw.html

[R02] 变量赋值与使用
来源：http://dali.cqqwz.cn/Article/details/gt2avclhiqt.html

name="Tom"; echo "$name"
来源：http://dali.yanxiufei.cn/Article/details/gt2bmjphhlr.html

[R03] 只读变量
来源：http://dali.yueranfly.top/Article/details/gt2fbowjfjy.html

readonly PI=3.14
来源：http://dali.birdmap.top/Article/details/gt2mbwutxjc.html

[R04] 位置参数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jlheuvid.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hywenlv.cn/Article/details/gt2pbngjsot.html

[R05] 参数默认值
来源：http://dali.shuidangran.top/Article/details/gt2ltetyzng.html

name="${1:-default}"
来源：http://dali.hfpthk.cn/Article/details/gt2wjcqfzws.html

[R06] 判断命令是否存在
来源：http://dali.meibo888.top/Article/details/gt2bfcekbhj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.birdmap.top/Article/details/gt2musjcamh.html

[R07] if 判断文件
来源：http://dali.nanxinkj.top/Article/details/gt2bhqwjnvj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.guannengcc.top/Article/details/gt2fgalzoxy.html

[R08] 数值比较
来源：http://dali.yonumen.top/Article/details/gt2ldfplszx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.guowangkeji.top/Article/details/gt2lmylnmsh.html

[R09] 字符串比较
来源：http://dali.aibaodan.cn/Article/details/gt2vkyijkyw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hywenlv.cn/Article/details/gt2upxqmztp.html

[R10] 正则匹配
来源：http://dali.ehwqpu.com/Article/details/gt2krshjgch.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shzxlz.cn/Article/details/gt2emxuegji.html

[R11] case 多分支
来源：http://dali.xinyue.icu/Article/details/gt2fntdmhlw.html

case "$1" in
来源：http://dali.0kj1m.cn/Article/details/gt2tsxdjevz.html

start) echo "启动" ;;
来源：http://dali.xuanzx.com/Article/details/gt2vgomtmrq.html

stop)  echo "停止" ;;
来源：http://dali.jianghu66.top/Article/details/gt2gwwdnluh.html

*)     echo "未知命令" ;;
来源：http://dali.snrcjt.cn/Article/details/gt2sxwwizvd.html

esac
来源：http://dali.dianchejie.cn/Article/details/gt2qlauiiun.html

[R12] for 遍历文件
来源：http://dali.chenlongwang.top/Article/details/gt2sipeqgbv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yj202588.top/Article/details/gt2jjcunkme.html

[R13] for 计数循环
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nfgfqjgc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xinyue.icu/Article/details/gt2rmtberol.html

[R14] C 风格 for
来源：http://dali.kuanghao11.cn/Article/details/gt2jldbyjdn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhongyouzk.top/Article/details/gt2qbtkphag.html

[R15] while 逐行读文件
来源：http://dali.cheryme.top/Article/details/gt2pdgcsmyb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hammf.cn/Article/details/gt2lwukusuz.html

[R16] until 等待条件
来源：http://dali.yueranfly.top/Article/details/gt2lfuygqnj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shzxlz.cn/Article/details/gt2jhhvwegz.html

[R17] 数组定义与取值
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ipobuvna.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hongshengwenyu.top/Article/details/gt2jbjmxrjm.html

[R18] 遍历数组
来源：http://dali.cqqwz.cn/Article/details/gt2giytbmlh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pgyomvcv.html

[R19] 数组长度
来源：http://dali.hammf.cn/Article/details/gt2vtqsvudj.html

echo "${#arr[@]}"
来源：http://dali.yvedp.cn/Article/details/gt2ogzrhdul.html

[R20] 关联数组（字典）
来源：http://dali.fzhhl.top/Article/details/gt2mpphlwoi.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.smart0.xyz/Article/details/gt2phsxsxcj.html

[R21] 字符串长度
来源：http://dali.yanxiufei.cn/Article/details/gt2vznlqfpl.html

echo "${#s}"
来源：http://dali.aibaodan.cn/Article/details/gt2mejoybdi.html

[R22] 截取子串
来源：http://dali.yangfankeji.com/Article/details/gt2jbpkkfcz.html

echo "${s:0:5}"
来源：http://dali.sweek.top/Article/details/gt2dadapgjf.html

[R23] 字符串替换
来源：http://dali.iojbl.cn/Article/details/gt2fsdgyylx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.fzhhl.top/Article/details/gt2defkiobp.html

[R24] 大小写转换
来源：http://dali.9152youxi.cn/Article/details/gt2wykhkdqe.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zdqjudy.top/Article/details/gt2kldzashc.html

[R25] 去后缀 / 去前缀
来源：http://dali.aibaodan.cn/Article/details/gt2xenkualr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.pycfn.com/Article/details/gt2bzqgegws.html

[R26] 命令替换
来源：http://dali.hysaishi.cn/Article/details/gt2mimtrkjr.html

now=$(date +%F); echo "$now"
来源：http://dali.yj20258888.top/Article/details/gt2xcdbgrsk.html

[R27] 算术展开
来源：http://dali.havefunace.top/Article/details/gt2tlibeglf.html

echo $((1 + 2 * 3))
来源：http://dali.yueranfly.top/Article/details/gt2wtdoxdkq.html

[R28] 浮点运算
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tespjcaf.html

echo "scale=2; 10/3" | bc
来源：http://dali.yongpay.top/Article/details/gt2jloxghnl.html

[R29] 定义函数
来源：http://dali.ivvv.top/Article/details/gt2lmldupaa.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.havefunace.top/Article/details/gt2ihzdeexp.html

[R30] 函数返回状态码
来源：http://dali.jinqigfzy.top/Article/details/gt2tdsxzhgk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2suynayae.html

[R31] 局部变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bhxfhkvz.html

f() { local x=1; echo "$x"; }
来源：http://dali.cashguo.top/Article/details/gt2mutveusw.html

[R32] 参数个数校验
来源：http://dali.pengpengdd.cyou/Article/details/gt2nyzktcyg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.haohaochexian.top/Article/details/gt2dasonnrb.html

[R33] 捕获错误并提示行号
来源：http://dali.jinqigufen.top/Article/details/gt2gllkhsii.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yongpay.top/Article/details/gt2gliosezf.html

[R34] 退出时清理
来源：http://dali.nanxinkj.top/Article/details/gt2abxlloup.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.dianchejie.cn/Article/details/gt2bikkosli.html

[R35] 后台执行并等待
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2krqvxnfx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhixingplan.top/Article/details/gt2gffwoayo.html

[R36] 并发执行多个任务
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kqwytkum.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ugavovik.html

[R37] 把输出赋给变量
来源：http://dali.gogol.net.cn/Article/details/gt2alhsjqxp.html

files=$(ls -1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dfpgwbiw.html

[R38] 管道串联
来源：http://dali.hywenlv.cn/Article/details/gt2cgomhypa.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhoulong.xyz/Article/details/gt2qwdscfay.html

[R39] 重定向标准输出与错误
来源：http://dali.vqdsnc.cn/Article/details/gt2httukvgq.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2izswgfac.html

[R40] 追加写日志
来源：http://dali.zhiwuduotai.top/Article/details/gt2twdpxpmp.html

echo "log" >> out.log
来源：http://dali.zhiwuduotai.top/Article/details/gt2bmgapoil.html

[R41] 丢弃输出
来源：http://dali.feifeiyinyue.top/Article/details/gt2qftgffns.html

cmd >/dev/null 2>&1
来源：http://dali.xuanzx.com/Article/details/gt2ormetmzq.html

[R42] 输入重定向
来源：http://dali.xuetiantiany.cn/Article/details/gt2pzgaymqb.html

wc -l < a.txt
来源：http://dali.hnxiangtu.top/Article/details/gt2lllzxywk.html

[R43] 按名字查找文件
来源：http://dali.xuanzx.com/Article/details/gt2rjablbfi.html

find . -name "*.log" -type f
来源：http://dali.zhengqikj.top/Article/details/gt2gnypmrgj.html

[R44] 按修改时间查找
来源：http://dali.shangyingyoupin.top/Article/details/gt2gqfrfkty.html

find . -mtime -7 -type f
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qjxhtujw.html

[R45] 批量删除
来源：http://dali.sxryk.cn/Article/details/gt2kginaoft.html

find . -name "*.tmp" -delete
来源：http://dali.hammf.cn/Article/details/gt2ptlhkvcx.html

[R46] 递归替换文件内容
来源：http://dali.0kj1m.cn/Article/details/gt2esltyvck.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.c1oappe.top/Article/details/gt2iyxbgcgs.html

[R47] sed 单行替换
来源：http://dali.haohaochexian.top/Article/details/gt2aszxoymw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yj202588.top/Article/details/gt2ijsumzfe.html

[R48] awk 取指定列
来源：http://dali.gzhubu.top/Article/details/gt2bngejswq.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhoulong.xyz/Article/details/gt2blqghurq.html

[R49] awk 带条件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2azvxvedo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sysykeji.top/Article/details/gt2lqovlkia.html

[R50] awk 求和
来源：http://dali.9152youxi.cn/Article/details/gt2okxylmit.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cucudq.cn/Article/details/gt2pksgwkee.html

[R51] 排序去重取前几
来源：http://dali.daxiang520.top/Article/details/gt2yxafitkq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cheryme.top/Article/details/gt2kizasqbb.html

[R52] 统计行数
来源：http://dali.gotoacloud.top/Article/details/gt2trcvhgsu.html

wc -l a.txt
来源：http://dali.hammf.cn/Article/details/gt2zlaoubfz.html

[R53] 查看文件头与实时尾
来源：http://dali.vqdsnc.cn/Article/details/gt2ambkcgpf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.aizwys.cn/Article/details/gt2itusdvdk.html

[R54] 比较两个文件
来源：http://dali.yanxiufei.cn/Article/details/gt2riubqagr.html

diff a.txt b.txt
来源：http://dali.jinqigfzy.top/Article/details/gt2dobzfbbw.html

[R55] 压缩与解压
来源：http://dali.yj20258.top/Article/details/gt2kolbyucg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gzhubu.top/Article/details/gt2xkogrdzi.html

[R56] 远程拷贝
来源：http://dali.ehwqpu.com/Article/details/gt2cfqxhzgs.html

scp file user@host:/path/
来源：http://dali.zhongyouzk.top/Article/details/gt2fnwbmqmb.html

[R57] 远程执行命令
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2izsvmsty.html

ssh user@host 'uptime'
来源：http://dali.zhixingplan.top/Article/details/gt2jlownwgb.html

[R58] 下载文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2mhhrqanb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.wangshuangyany.cn/Article/details/gt2ylhnrheb.html

[R59] 发 POST JSON
来源：http://dali.xylfe.cn/Article/details/gt2vdzasrqo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.c1oappe.top/Article/details/gt2gncrhsuv.html

[R60] 只看 HTTP 状态码
来源：http://dali.quarkkingdee.top/Article/details/gt2ejpvdkoe.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.haohaochexian.top/Article/details/gt2yeepsext.html

[R61] 磁盘占用
来源：http://dali.vqdsnc.cn/Article/details/gt2nkzskkrt.html

df -h;  du -sh *
来源：http://dali.hammf.cn/Article/details/gt2nshxdubi.html

[R62] 找最占空间的文件
来源：http://dali.aibaodan.cn/Article/details/gt2fhrdekzr.html

du -ah . | sort -rh | head -10
来源：http://dali.hongshengwenyu.top/Article/details/gt2sjbdynqm.html

[R63] 内存与进程
来源：http://dali.0kj1m.cn/Article/details/gt2cxigxsji.html

free -h;  ps aux | grep nginx
来源：http://dali.ydzc1.top/Article/details/gt2ghpoauqm.html

[R64] 结束进程
来源：http://dali.xuanzx.com/Article/details/gt2bjngzvcv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.vqdsnc.cn/Article/details/gt2bjhogefg.html

[R65] 查看端口占用
来源：http://dali.iojbl.cn/Article/details/gt2fkaaqxwx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj20258888.top/Article/details/gt2muihoewr.html

[R66] 定时任务
来源：http://dali.ydzc1.top/Article/details/gt2lvavwkek.html

crontab -e;  crontab -l
来源：http://dali.0kj1m.cn/Article/details/gt2kjztzaio.html

[R67] 生成随机十六进制串
来源：http://dali.sweek.top/Article/details/gt2peiddrbb.html

openssl rand -hex 16
来源：http://dali.aibaodan.cn/Article/details/gt2erygdlxc.html

[R68] 计算文件校验值
来源：http://dali.jiagoushi.top/Article/details/gt2wgdlkrjl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yvedp.cn/Article/details/gt2wzkjxgpz.html

[R69] 生成随机密码
来源：http://dali.mhx1999.top/Article/details/gt2ebubzksf.html

head -c 16 /dev/urandom | base64
来源：http://dali.sxryk.cn/Article/details/gt2fmcfxbxe.html

[R70] 时间戳与互转
来源：http://dali.svipenyu.cn/Article/details/gt2cnwaeoni.html

date +%s;  date -d @1700000000
来源：http://dali.daria6918.cn/Article/details/gt2aizwcioq.html

[R71] 日期格式化
来源：http://dali.ivvv.top/Article/details/gt2ztduoawq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.feifeiyinyue.top/Article/details/gt2ierdcqej.html

[R72] 等待端口就绪
来源：http://dali.9152youxi.cn/Article/details/gt2ivfxxudm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hammf.cn/Article/details/gt2ztbkbdhm.html

[R73] 分割大日志
来源：http://dali.chenlongwang.top/Article/details/gt2ywymqecc.html

split -l 1000 big.log part_
来源：http://dali.xuetiantiany.cn/Article/details/gt2pbwthwop.html

[R74] 批量重命名
来源：http://dali.nanxinkj.top/Article/details/gt2kbpryvpk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.svipenyu.cn/Article/details/gt2wmtedyxi.html

[R75] 导出环境变量
来源：http://dali.tian-w.cn/Article/details/gt2ppocwibm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yuanzhike.top/Article/details/gt2gaxpyzgg.html

[R76] 使用临时文件
来源：http://dali.yj202588.top/Article/details/gt2trdwlroj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.redwolf501.top/Article/details/gt2hfblxxkc.html

[R77] 读取用户输入
来源：http://dali.sufxvd.cn/Article/details/gt2oaygcppx.html

read -rp "请输入: " ans
来源：http://dali.wangdashe.top/Article/details/gt2mspfrnwe.html

[R78] 交互式菜单
来源：http://dali.yvedp.cn/Article/details/gt2kotbwyee.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jianghu66.top/Article/details/gt2zkhsrtsn.html

[R79] 解析命令行选项
来源：http://dali.ehwqpu.com/Article/details/gt2fillfunu.html


<!-- 参考信息 -->