代发 wailian999

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.fengsongda.top/Article/details/gtnjqdoquw.html

[Q30] 分组统计
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqnojhfeb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shuidangran.top/Article/details/gtzsglkgal.html

[Q31] 分组后过滤
来源：http://dali.gaohongyu789.top/Article/details/gtbzpgtocb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yuxming.cn/Article/details/gtxpkuionq.html

[Q32] 分组拼接字符串
来源：http://dali.meibo888.top/Article/details/gtwoflsrgp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkrnrymmi.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xziqi.cn/Article/details/gtsgwlgjra.html

[Q33] 多列分组
来源：http://dali.dianchejie.cn/Article/details/gtxxuctolq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cucudq.cn/Article/details/gtebemrelh.html

[Q34] 每组取第一条
来源：http://dali.aizwys.cn/Article/details/gtxutnmbif.html

SELECT * FROM (
来源：http://dali.ppjwa.cn/Article/details/gtphowcgez.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.nanxuanxn.top/Article/details/gtbobotuew.html

) t WHERE rn = 1;
来源：http://dali.yuanzhike.top/Article/details/gttflzpuca.html

[Q35] 内连接
来源：http://dali.wangshuangyany.cn/Article/details/gtonqlxdoz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yangfankeji.com/Article/details/gtilphrlek.html

[Q36] 左连接
来源：http://dali.yuanzhike.top/Article/details/gtwgxwapgn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gogol.net.cn/Article/details/gtheaylpyv.html

[Q37] 右连接
来源：http://dali.hnqzz.top/Article/details/gtkrzgzech.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.fzhhl.top/Article/details/gtvmwisops.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hywenlv.cn/Article/details/gtrrprrocv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyjwpxliz.html

[Q39] 自连接（查上下级）
来源：http://dali.cqqwz.cn/Article/details/gtuiwhexgz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yanxiufei.cn/Article/details/gtntbiaxkz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.tanke756.top/Article/details/gtfevxlxge.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtikymrjkf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.snrcjt.cn/Article/details/gtkvvlacqu.html

[Q41] 多表连接
来源：http://dali.jiagoushi.top/Article/details/gtxrlykdmr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.nanxuanxn.top/Article/details/gtmbewbyrs.html

JOIN users u ON u.id = o.user_id
来源：http://dali.bjfxy.top/Article/details/gtntatovza.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.fengsongda.top/Article/details/gthphqgoct.html

[Q42] 连接条件附加过滤
来源：http://dali.gaohongyu789.top/Article/details/gtzxsrujvj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.meibo888.top/Article/details/gtrhrrjjpw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.snrcjt.cn/Article/details/gtdjzyklxg.html

[Q43] 标量子查询
来源：http://dali.yanxiufei.cn/Article/details/gtjxaldmlr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.redwolf501.top/Article/details/gtlmavmozk.html

[Q44] IN 子查询
来源：http://dali.dianchejie.cn/Article/details/gtvknreuax.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtipydjucl.html

[Q45] EXISTS 判断存在
来源：http://dali.0kj1m.cn/Article/details/gtdyplfnjj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgszhfplq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xuetiantiany.cn/Article/details/gtfbvgbbrw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xinyue.icu/Article/details/gtjgydmltr.html

[Q47] 与平均值比较
来源：http://dali.yuanzhike.top/Article/details/gtsyoznbca.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hongshengwenyu.top/Article/details/gtfrnksgsg.html

[Q48] CTE 公用表表达式
来源：http://dali.gaohongyu789.top/Article/details/gthkqkpgrc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.aizwys.cn/Article/details/gtcimvdjer.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhongyouzk.top/Article/details/gtpglhoees.html

[Q49] 更新单行
来源：http://dali.fzhhl.top/Article/details/gtqtswhheb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.birdmap.top/Article/details/gttvlihoaq.html

[Q50] 批量更新
来源：http://dali.smart0.xyz/Article/details/gtpzxgopfq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.nwbrower.top/Article/details/gtjuzmcooc.html

[Q51] 用子查询更新
来源：http://dali.mhx1999.top/Article/details/gtlsjaqhsi.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtuseuvgty.html

[Q52] 删除指定行
来源：http://dali.birdmap.top/Article/details/gtrhlrglud.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqkedvsqw.html

[Q53] 按条件删除
来源：http://dali.quarkkingdee.top/Article/details/gthcxlwutq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.chenzaomai.com/Article/details/gtamrjkmtp.html

[Q54] 清空表
来源：http://dali.nanxuanxn.top/Article/details/gtqelwnsfc.html

TRUNCATE TABLE logs;
来源：http://dali.meibo888.top/Article/details/gtxzsdkpku.html

[Q55] 排名（并列占位）
来源：http://dali.andypj.xyz/Article/details/gtmrxcyglo.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yj202588.top/Article/details/gtltmtjrhr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.haohaochexian.top/Article/details/gtgxboamfb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhongyouzk.top/Article/details/gtivghtxvg.html

[Q57] 行号
来源：http://dali.ppjwa.cn/Article/details/gtonrgqtnh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtngjdgxov.html

[Q58] 累计求和
来源：http://dali.zycfv.cn/Article/details/gthiiurhut.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gtwhcqbgcd.html

[Q59] 分组内累计
来源：http://dali.aibaodan.cn/Article/details/gtnankzebx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtikurflwj.html

[Q60] 取上一行 / 下一行
来源：http://dali.gogol.net.cn/Article/details/gtdrgrxgke.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gaohongyu789.top/Article/details/gtdihgbkqx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gttyswxjty.html

[Q61] 移动平均
来源：http://dali.shzxlz.cn/Article/details/gtehekhjye.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gtcpapwdhx.html

[Q62] 分组占比
来源：http://dali.chenjidiqi.icu/Article/details/gtkssqkxjb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gaohongyu789.top/Article/details/gtquoohdqq.html

[Q63] 开启事务
来源：http://dali.tian-w.cn/Article/details/gtpanloolk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yuxming.cn/Article/details/gtewplzkhu.html

[Q64] 提交事务
来源：http://dali.feifeiyinyue.top/Article/details/gttnnuypak.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gtrxutrsrs.html

[Q65] 回滚事务
来源：http://dali.meibo888.top/Article/details/gtxsegfqts.html

ROLLBACK;
来源：http://dali.aizwys.cn/Article/details/gttbmmfrrv.html

[Q66] 行锁查询
来源：http://dali.feifeiyinyue.top/Article/details/gtxsqvjliv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.iojbl.cn/Article/details/gtyoijgxaz.html

[Q67] 设置隔离级别
来源：http://dali.hysaishi.cn/Article/details/gtfrhfsrnu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yanxiufei.cn/Article/details/gtksyrmgyk.html

[Q68] 保存点
来源：http://dali.dianchejie.cn/Article/details/gtrkznetci.html

SAVEPOINT sp1;
来源：http://dali.yongpay.top/Article/details/gtaqicgtnw.html

ROLLBACK TO sp1;
来源：http://dali.hfpthk.cn/Article/details/gtckfdsrqq.html

[Q69] 查看执行计划
来源：http://dali.gzhubu.top/Article/details/gtdlsducth.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zycfv.cn/Article/details/gtcesawodr.html

[Q70] 更新统计信息
来源：http://dali.xinyue.icu/Article/details/gtssnmyrcn.html

ANALYZE TABLE users;
来源：http://dali.zhoulong.xyz/Article/details/gtnxjgbjsf.html

[Q71] 查看建表语句
来源：http://dali.316326.xyz/Article/details/gthvrdsehe.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yuanzhike.top/Article/details/gtlsvguihm.html

[Q72] 查看索引
来源：http://dali.316326.xyz/Article/details/gthwjmhvgi.html

SHOW INDEX FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gttsqnjtjj.html

[Q73] 查看表状态
来源：http://dali.pycfn.com/Article/details/gtnppaumlf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ehwqpu.com/Article/details/gtzqtvenrr.html

[Q74] 强制使用索引
来源：http://dali.yj20258.top/Article/details/gttjhgkyzr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.pengpengdd.cyou/Article/details/gtaxfpjvgi.html

[Q75] 日期格式化
来源：http://dali.cucudq.cn/Article/details/gtkkzjcokd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.aizwys.cn/Article/details/gthonysfdy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.chenzaomai.com/Article/details/gtkbnuzpue.html

[Q76] 按天统计
来源：http://dali.sufxvd.cn/Article/details/gtekrocjtn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.birdmap.top/Article/details/gtmbwxvejj.html

[Q77] 时间加减
来源：http://dali.chenlongwang.top/Article/details/gtccdpyoim.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.kuanghao11.cn/Article/details/gtsorabdxj.html

[Q78] 当前时间
来源：http://dali.jianghu66.top/Article/details/gtmahjyaky.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhengqikj.top/Article/details/gtwditvrlq.html

[Q79] 字符串拼接
来源：http://dali.haohaochexian.top/Article/details/gthfwfdbwg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.quarkkingdee.top/Article/details/gtmjyrauur.html

[Q80] 字符串截取
来源：http://dali.yonumen.top/Article/details/gtjtsfwyne.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.wangdashe.top/Article/details/gtjjbenpdv.html

[Q81] 字符串替换
来源：http://dali.dashuyun.cn/Article/details/gtvutwretf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jianghu66.top/Article/details/gtnzyogwzi.html

[Q82] 字符长度与字节长度
来源：http://dali.zhiwuduotai.top/Article/details/gtuidlkala.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtsukaicfa.html

[Q83] 大小写转换
来源：http://dali.jqgufenzy.top/Article/details/gtrbctqtzg.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtkwdmbbkt.html

[Q84] 去除首尾空格
来源：http://dali.sxryk.cn/Article/details/gtiineipfs.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtdqfrxvdi.html

[Q85] 数值取整
来源：http://dali.shzxlz.cn/Article/details/gtpitfyrwo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hnqzz.top/Article/details/gtskoeveyh.html

[Q86] 读取 JSON 字段
来源：http://dali.shanyushiyangtech.top/Article/details/gtfqmijnjp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.pengpengdd.cyou/Article/details/gtlvpuowki.html

[Q87] JSON 字段做条件
来源：http://dali.smart0.xyz/Article/details/gtzrcmstyh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gaohongyu789.top/Article/details/gtqudinhhz.html

[Q88] 行转列（条件聚合）
来源：http://dali.chenlongwang.top/Article/details/gthepbxxrk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.daria6918.cn/Article/details/gtcfinidyj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtwqfnognv.html

[Q89] 判断表是否存在
来源：http://dali.jianghu66.top/Article/details/gtbvpatdbq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yueranfly.top/Article/details/gtxanggent.html

[Q90] 生成序号列
来源：http://dali.jyoumei.cn/Article/details/gtknrflsce.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jqgufenzy.top/Article/details/gtsgwyqvfz.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxpdobqmv.html

R. Bash 专题
来源：http://dali.cqqwz.cn/Article/details/gtviqhijvi.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtstsigzex.html

[R01] shebang 与严格模式
来源：http://dali.sufxvd.cn/Article/details/gtkfuvelzm.html

#!/usr/bin/env bash
来源：http://dali.yuxming.cn/Article/details/gtnuynufkn.html

set -euo pipefail
来源：http://dali.yuanzhike.top/Article/details/gtsdkhdyxm.html

[R02] 变量赋值与使用
来源：http://dali.yj202588.top/Article/details/gtwhxfoofp.html

name="Tom"; echo "$name"
来源：http://dali.dianchejie.cn/Article/details/gtwmvztfgd.html

[R03] 只读变量
来源：http://dali.jiagoushi.top/Article/details/gtemmyigec.html

readonly PI=3.14
来源：http://dali.gotoacloud.top/Article/details/gtaixxkiby.html

[R04] 位置参数
来源：http://dali.cdnleiting.top/Article/details/gtezpvosrx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.mhx1999.top/Article/details/gtzececjww.html

[R05] 参数默认值
来源：http://dali.zhongyouzk.top/Article/details/gtdemurgdo.html

name="${1:-default}"
来源：http://dali.cashguo.top/Article/details/gtrwwtgoqz.html

[R06] 判断命令是否存在
来源：http://dali.cdnleiting.top/Article/details/gtlqtysvmh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jlsjyb.cn/Article/details/gtyvcpfosd.html

[R07] if 判断文件
来源：http://dali.feifeiyinyue.top/Article/details/gtuqnuspla.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sweek.top/Article/details/gtswbogeyk.html

[R08] 数值比较
来源：http://dali.havefunace.top/Article/details/gtlgerrita.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sufxvd.cn/Article/details/gtvgjfeptl.html

[R09] 字符串比较
来源：http://dali.jinghuilouyu.cn/Article/details/gtrvumikaj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yuanzhike.top/Article/details/gtpsupaddo.html

[R10] 正则匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtxvwrfelf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sysykeji.top/Article/details/gttiracsio.html

[R11] case 多分支
来源：http://dali.tianlin.xyz/Article/details/gtmufizglc.html

case "$1" in
来源：http://dali.zhixingplan.top/Article/details/gtlefaimfl.html

start) echo "启动" ;;
来源：http://dali.yanxiufei.cn/Article/details/gtyrxzlnvt.html

stop)  echo "停止" ;;
来源：http://dali.cheryme.top/Article/details/gtwgaxfvqi.html

*)     echo "未知命令" ;;
来源：http://dali.316326.xyz/Article/details/gtmbtxepvu.html

esac
来源：http://dali.meibo888.top/Article/details/gtblnssjis.html

[R12] for 遍历文件
来源：http://dali.jqgufenzy.top/Article/details/gtlatjizho.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhiwuduotai.top/Article/details/gtvjxuoroy.html

[R13] for 计数循环
来源：http://dali.316326.xyz/Article/details/gthlcwaetn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shuidangran.top/Article/details/gtbfztilue.html

[R14] C 风格 for
来源：http://dali.sweek.top/Article/details/gtpivvscab.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hysaishi.cn/Article/details/gthxgwecyk.html

[R15] while 逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gtyxzecbrt.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.guowangkeji.top/Article/details/gtcrbumkcp.html

[R16] until 等待条件
来源：http://dali.316326.xyz/Article/details/gtigdnxabj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.nanxinkj.top/Article/details/gtuhghlugh.html

[R17] 数组定义与取值
来源：http://dali.hywenlv.cn/Article/details/gtqudalukq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.dianchejie.cn/Article/details/gtmxvcreqe.html

[R18] 遍历数组
来源：http://dali.daxiang520.top/Article/details/gtcolkebmn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.tanke756.top/Article/details/gtjdhvxnfr.html

[R19] 数组长度
来源：http://dali.c1oappe.top/Article/details/gtpvqvwfhp.html

echo "${#arr[@]}"
来源：http://dali.quarkkingdee.top/Article/details/gtlrmyskwe.html

[R20] 关联数组（字典）
来源：http://dali.gogol.net.cn/Article/details/gtjwxdyyfc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hnxiangtu.top/Article/details/gtwhohfxaj.html

[R21] 字符串长度
来源：http://dali.smart0.xyz/Article/details/gtecddqcpv.html

echo "${#s}"
来源：http://dali.yanxiufei.cn/Article/details/gtcudhlhck.html

[R22] 截取子串
来源：http://dali.shzxlz.cn/Article/details/gteuxcgepy.html

echo "${s:0:5}"
来源：http://dali.cashguo.top/Article/details/gtmpsdytet.html

[R23] 字符串替换
来源：http://dali.yj202588.top/Article/details/gtvtwcoezh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hammf.cn/Article/details/gttnrdioao.html

[R24] 大小写转换
来源：http://dali.yonumen.top/Article/details/gtkskycmtg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gtotgozuxg.html

[R25] 去后缀 / 去前缀
来源：http://dali.xylfe.cn/Article/details/gtfglacvzv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sufxvd.cn/Article/details/gtjeuvamtv.html

[R26] 命令替换
来源：http://dali.tian-w.cn/Article/details/gtxugmsnkv.html

now=$(date +%F); echo "$now"
来源：http://dali.jlsjyb.cn/Article/details/gtthdlntqn.html

[R27] 算术展开
来源：http://dali.daxiang520.top/Article/details/gtgrobltcz.html

echo $((1 + 2 * 3))
来源：http://dali.jqgufenzy.top/Article/details/gtxagpzqdo.html

[R28] 浮点运算
来源：http://dali.daxiang520.top/Article/details/gtdbepwasy.html

echo "scale=2; 10/3" | bc
来源：http://dali.sufxvd.cn/Article/details/gtztfjpclf.html

[R29] 定义函数
来源：http://dali.yangfankeji.com/Article/details/gtrvasakdb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.pengpengdd.cyou/Article/details/gtycqrxngc.html

[R30] 函数返回状态码
来源：http://dali.9152youxi.cn/Article/details/gtwotgbelo.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hongshengwenyu.top/Article/details/gtcqjuricr.html

[R31] 局部变量
来源：http://dali.guannengcc.top/Article/details/gtfiqndhlq.html

f() { local x=1; echo "$x"; }
来源：http://dali.haohaochexian.top/Article/details/gtkkcncrpo.html

[R32] 参数个数校验
来源：http://dali.kuanghao11.cn/Article/details/gtbsdiemns.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cashguo.top/Article/details/gtbkfmmaws.html

[R33] 捕获错误并提示行号
来源：http://dali.pycfn.com/Article/details/gtoeldxdfu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhoulong.xyz/Article/details/gtnlgobsla.html

[R34] 退出时清理
来源：http://dali.fengsongda.top/Article/details/gtkqdoiagm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnqzz.top/Article/details/gtbmqdcebd.html

[R35] 后台执行并等待
来源：http://dali.nanxinkj.top/Article/details/gtuxnwlvrf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ybcxt.top/Article/details/gthclwjxyr.html

[R36] 并发执行多个任务
来源：http://dali.chenjidiqi.icu/Article/details/gtjmgceyxa.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.sxryk.cn/Article/details/gtkpgmxupe.html

[R37] 把输出赋给变量
来源：http://dali.yj20258.top/Article/details/gthfsujdtt.html

files=$(ls -1)
来源：http://dali.xziqi.cn/Article/details/gttkjdtdvr.html

[R38] 管道串联
来源：http://dali.wangdashe.top/Article/details/gtuoftjejq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hongshengwenyu.top/Article/details/gtyswuxssh.html

[R39] 重定向标准输出与错误
来源：http://dali.tanke756.top/Article/details/gtkhuqnzip.html

cmd > out.log 2>&1
来源：http://dali.svipenyu.cn/Article/details/gtmhedssyo.html

[R40] 追加写日志
来源：http://dali.iojbl.cn/Article/details/gtdovcqbqk.html

echo "log" >> out.log
来源：http://dali.zdqjudy.top/Article/details/gtmmozwnep.html

[R41] 丢弃输出
来源：http://dali.jyoumei.cn/Article/details/gtcsrlqcai.html

cmd >/dev/null 2>&1
来源：http://dali.jinqigfzy.top/Article/details/gtuyxlypvq.html

[R42] 输入重定向
来源：http://dali.hywenlv.cn/Article/details/gtbcqlyjhg.html

wc -l < a.txt
来源：http://dali.tianlin.xyz/Article/details/gtbeikkisg.html

[R43] 按名字查找文件
来源：http://dali.meibo888.top/Article/details/gtxcpjzjpd.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gtfaoukwor.html

[R44] 按修改时间查找
来源：http://dali.meibo888.top/Article/details/gtelqfvsma.html

find . -mtime -7 -type f
来源：http://dali.jqgfzy.top/Article/details/gtjcrofjrf.html

[R45] 批量删除
来源：http://dali.sweek.top/Article/details/gtecwrpkrk.html

find . -name "*.tmp" -delete
来源：http://dali.tanke756.top/Article/details/gtmyjgjacw.html

[R46] 递归替换文件内容
来源：http://dali.pengpengdd.cyou/Article/details/gtwjscetdd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ehwqpu.com/Article/details/gtyigqaskr.html

[R47] sed 单行替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpejvjrwc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.snrcjt.cn/Article/details/gttpxbgmlm.html

[R48] awk 取指定列
来源：http://dali.redwolf501.top/Article/details/gtzetofvll.html

awk '{print $1, $3}' a.txt
来源：http://dali.9152youxi.cn/Article/details/gtwauetolj.html

[R49] awk 带条件
来源：http://dali.havefunace.top/Article/details/gtdgramgec.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.haohaochexian.top/Article/details/gtgjbianhb.html

[R50] awk 求和
来源：http://dali.guowangkeji.top/Article/details/gtgbqszlre.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gzhubu.top/Article/details/gticjgmurp.html

[R51] 排序去重取前几
来源：http://dali.mhx1999.top/Article/details/gtkatvicbg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhixingplan.top/Article/details/gtxnupgnjj.html

[R52] 统计行数
来源：http://dali.tian-w.cn/Article/details/gtyhfqiupp.html

wc -l a.txt
来源：http://dali.andypj.xyz/Article/details/gtvvzadpun.html

[R53] 查看文件头与实时尾
来源：http://dali.cucudq.cn/Article/details/gtncjjoayl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.daxiang520.top/Article/details/gtnfqfwpfz.html

[R54] 比较两个文件
来源：http://dali.yangfankeji.com/Article/details/gtfwklkzlk.html

diff a.txt b.txt
来源：http://dali.hnqzz.top/Article/details/gtnoetjakz.html

[R55] 压缩与解压
来源：http://dali.hfpthk.cn/Article/details/gtdhmruzsw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yonumen.top/Article/details/gtyowxhllv.html

[R56] 远程拷贝
来源：http://dali.zhaomingkeji.xyz/Article/details/gtddqercsc.html

scp file user@host:/path/
来源：http://dali.yueranfly.top/Article/details/gtnvcciihf.html

[R57] 远程执行命令
来源：http://dali.vqdsnc.cn/Article/details/gtedrgwlka.html

ssh user@host 'uptime'
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyuyxaicf.html

[R58] 下载文件
来源：http://dali.hfpthk.cn/Article/details/gtgrmdtmtt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jinqigufen.top/Article/details/gtrkajrtod.html

[R59] 发 POST JSON
来源：http://dali.shzxlz.cn/Article/details/gtohqvivvs.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.bjfxy.top/Article/details/gtipaqlmla.html

[R60] 只看 HTTP 状态码
来源：http://dali.hywenlv.cn/Article/details/gtdhmisxtb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shangyingyoupin.top/Article/details/gtdxyzdoqs.html

[R61] 磁盘占用
来源：http://dali.zycfv.cn/Article/details/gtglytaxvy.html

df -h;  du -sh *
来源：http://dali.sysykeji.top/Article/details/gtjhqniags.html

[R62] 找最占空间的文件
来源：http://dali.aizwys.cn/Article/details/gtoqrfqmts.html

du -ah . | sort -rh | head -10
来源：http://dali.yangfankeji.com/Article/details/gtqkuxdjcw.html

[R63] 内存与进程
来源：http://dali.sysykeji.top/Article/details/gtgvbqttdt.html

free -h;  ps aux | grep nginx
来源：http://dali.gaohongyu789.top/Article/details/gthltilmns.html

[R64] 结束进程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlzpprxbd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.tian-w.cn/Article/details/gtlajjobya.html

[R65] 查看端口占用
来源：http://dali.jlsjyb.cn/Article/details/gtwjlcrvyg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shzxlz.cn/Article/details/gtmtoujvxs.html

[R66] 定时任务
来源：http://dali.ivvv.top/Article/details/gtxrzzfmto.html

crontab -e;  crontab -l
来源：http://dali.chenjidiqi.icu/Article/details/gtplstulpy.html

[R67] 生成随机十六进制串
来源：http://dali.cqqwz.cn/Article/details/gtybdpuixx.html

openssl rand -hex 16
来源：http://dali.dashuyun.cn/Article/details/gtqkbyortu.html

[R68] 计算文件校验值
来源：http://dali.zhoulong.xyz/Article/details/gtyynugrar.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.redwolf501.top/Article/details/gtucszcndk.html

[R69] 生成随机密码
来源：http://dali.aibaodan.cn/Article/details/gtoqqrlsbe.html

head -c 16 /dev/urandom | base64
来源：http://dali.sweek.top/Article/details/gtwzlvdutb.html

[R70] 时间戳与互转
来源：http://dali.kuanghao11.cn/Article/details/gtsxnxnhxn.html

date +%s;  date -d @1700000000
来源：http://dali.tianlin.xyz/Article/details/gtuvetrwjx.html

[R71] 日期格式化
来源：http://dali.jianghu66.top/Article/details/gtqiobqzgb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xylfe.cn/Article/details/gtzlakbtpy.html

[R72] 等待端口就绪
来源：http://dali.hysaishi.cn/Article/details/gtfyxtjgyh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xinyue.icu/Article/details/gtnzizripb.html

[R73] 分割大日志
来源：http://dali.jqgufenzy.top/Article/details/gtqcdaxmue.html

split -l 1000 big.log part_
来源：http://dali.xinyue.icu/Article/details/gtimdvzrpo.html

[R74] 批量重命名
来源：http://dali.xziqi.cn/Article/details/gtxqzjwmsy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.iojbl.cn/Article/details/gtiahukiab.html

[R75] 导出环境变量
来源：http://dali.quarkkingdee.top/Article/details/gtyonzunld.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.9152youxi.cn/Article/details/gtxutizvgh.html

[R76] 使用临时文件
来源：http://dali.hywenlv.cn/Article/details/gtiuviphhb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.andypj.xyz/Article/details/gtsvftocgx.html

[R77] 读取用户输入
来源：http://dali.yueranfly.top/Article/details/gtieiwrcry.html

read -rp "请输入: " ans
来源：http://dali.wangdashe.top/Article/details/gtktmnuapc.html

[R78] 交互式菜单
来源：http://dali.tanke756.top/Article/details/gtgaqxqeih.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yueranfly.top/Article/details/gtrtqpzpzb.html

[R79] 解析命令行选项
来源：http://dali.jyoumei.cn/Article/details/gtsazokade.html


<!-- 参考信息 -->