代发 wailian999

[Q33] 多列分组
来源：http://dali.bjfxy.top/Article/details/gt2widbcqgl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.chenlongwang.top/Article/details/gt2rgqgmbqo.html

[Q34] 每组取第一条
来源：http://dali.iojbl.cn/Article/details/gt2hjmpcexl.html

SELECT * FROM (
来源：http://dali.ivvv.top/Article/details/gt2wcctlptd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.tian-w.cn/Article/details/gt2groxxyjq.html

) t WHERE rn = 1;
来源：http://dali.ppjwa.cn/Article/details/gt2wiafrubj.html

[Q35] 内连接
来源：http://dali.hongshengwenyu.top/Article/details/gt2emhtvolq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.andypj.xyz/Article/details/gt2jcfxxxnm.html

[Q36] 左连接
来源：http://dali.zhongyouzk.top/Article/details/gt2cstalmeb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.snrcjt.cn/Article/details/gt2xhyqrjkk.html

[Q37] 右连接
来源：http://dali.ehwqpu.com/Article/details/gt2btsooxce.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yongpay.top/Article/details/gt2rxgjtffc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.redwolf501.top/Article/details/gt2fchfoyoa.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jqgfzy.top/Article/details/gt2izhpftjj.html

[Q39] 自连接（查上下级）
来源：http://dali.hywenlv.cn/Article/details/gt2jsijsnsf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xylfe.cn/Article/details/gt2zzfrgseg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhoulong.xyz/Article/details/gt2ogoutgxd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cucudq.cn/Article/details/gt2simcjdxv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jiagoushi.top/Article/details/gt2elzlkwuo.html

[Q41] 多表连接
来源：http://dali.xylfe.cn/Article/details/gt2cuophlmk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yj202588.top/Article/details/gt2eclymmrc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.tian-w.cn/Article/details/gt2gkhwaugt.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jsciwtjd.html

[Q42] 连接条件附加过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sakkwhqq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.tianlin.xyz/Article/details/gt2jqarxpbr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xylfe.cn/Article/details/gt2dayyupno.html

[Q43] 标量子查询
来源：http://dali.snrcjt.cn/Article/details/gt2suylhguj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.pengpengdd.cyou/Article/details/gt2hhagivbm.html

[Q44] IN 子查询
来源：http://dali.guannengcc.top/Article/details/gt2ynpslvpy.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.mhx1999.top/Article/details/gt2bptlhfqd.html

[Q45] EXISTS 判断存在
来源：http://dali.cdnleiting.top/Article/details/gt2rsvzrnmz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2plcdaxgq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jianghu66.top/Article/details/gt2hirsskbv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.iojbl.cn/Article/details/gt2dscomjft.html

[Q47] 与平均值比较
来源：http://dali.zhoulong.xyz/Article/details/gt2uymrakcc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hnxiangtu.top/Article/details/gt2gurfuldh.html

[Q48] CTE 公用表表达式
来源：http://dali.daria6918.cn/Article/details/gt2tmbddhnb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.gogol.net.cn/Article/details/gt2dbfixpnz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gotoacloud.top/Article/details/gt2oyouylwh.html

[Q49] 更新单行
来源：http://dali.ydzc1.top/Article/details/gt2clkcieau.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jqgfzy.top/Article/details/gt2qgmhtkcl.html

[Q50] 批量更新
来源：http://dali.ehwqpu.com/Article/details/gt2wehuebfq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hfpthk.cn/Article/details/gt2ypptmiym.html

[Q51] 用子查询更新
来源：http://dali.nanxinkj.top/Article/details/gt2ucxzcyum.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ydzc1.top/Article/details/gt2gzvzvtzq.html

[Q52] 删除指定行
来源：http://dali.jlsjyb.cn/Article/details/gt2ocjggbmx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhengqikj.top/Article/details/gt2jsejwgcv.html

[Q53] 按条件删除
来源：http://dali.cashguo.top/Article/details/gt2ckzubvog.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qpheoxtu.html

[Q54] 清空表
来源：http://dali.cheryme.top/Article/details/gt2nvjhwfhp.html

TRUNCATE TABLE logs;
来源：http://dali.sysykeji.top/Article/details/gt2onqzexgx.html

[Q55] 排名（并列占位）
来源：http://dali.nwbrower.top/Article/details/gt2ioczwknv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cashguo.top/Article/details/gt2rgmbrovb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hfpthk.cn/Article/details/gt2pvzuovda.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jqgfzy.top/Article/details/gt2kucmvkhr.html

[Q57] 行号
来源：http://dali.fzhhl.top/Article/details/gt2mkgjsieg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2raudkhlp.html

[Q58] 累计求和
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dtzqnkaz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.pycfn.com/Article/details/gt2vwotklqo.html

[Q59] 分组内累计
来源：http://dali.zhixingplan.top/Article/details/gt2tkyzsbrg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gt2pahcsbfw.html

[Q60] 取上一行 / 下一行
来源：http://dali.wangdashe.top/Article/details/gt2wxirlcfz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.redwolf501.top/Article/details/gt2mvsmpwmw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gt2jpmbonjc.html

[Q61] 移动平均
来源：http://dali.shzxlz.cn/Article/details/gt2vixqgcpq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xziqi.cn/Article/details/gt2yifuurpg.html

[Q62] 分组占比
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ijduvbvq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhengqikj.top/Article/details/gt2otwjjpcb.html

[Q63] 开启事务
来源：http://dali.iojbl.cn/Article/details/gt2mdegfxsd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yongpay.top/Article/details/gt2yhicxqmt.html

[Q64] 提交事务
来源：http://dali.vqdsnc.cn/Article/details/gt2gfqbwekg.html

COMMIT;
来源：http://dali.cashguo.top/Article/details/gt2jbadtlqf.html

[Q65] 回滚事务
来源：http://dali.meibo888.top/Article/details/gt2pnhcjkif.html

ROLLBACK;
来源：http://dali.yangfankeji.com/Article/details/gt2yavlghsb.html

[Q66] 行锁查询
来源：http://dali.meibo888.top/Article/details/gt2rrjymavx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xuetiantiany.cn/Article/details/gt2jefcwgpy.html

[Q67] 设置隔离级别
来源：http://dali.shzxlz.cn/Article/details/gt2dwrbygke.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xuanzx.com/Article/details/gt2ezphfcfw.html

[Q68] 保存点
来源：http://dali.zycfv.cn/Article/details/gt2mngwgdng.html

SAVEPOINT sp1;
来源：http://dali.jinqigfzy.top/Article/details/gt2zzbbterz.html

ROLLBACK TO sp1;
来源：http://dali.yonumen.top/Article/details/gt2vkbvvsec.html

[Q69] 查看执行计划
来源：http://dali.wangdashe.top/Article/details/gt2egeiheoq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ppjwa.cn/Article/details/gt2ecxkkywz.html

[Q70] 更新统计信息
来源：http://dali.dianchejie.cn/Article/details/gt2reqcqxwz.html

ANALYZE TABLE users;
来源：http://dali.hysaishi.cn/Article/details/gt2crtfnymf.html

[Q71] 查看建表语句
来源：http://dali.sufxvd.cn/Article/details/gt2vpwpmfcw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.tanke756.top/Article/details/gt2ljsebfbf.html

[Q72] 查看索引
来源：http://dali.gzhubu.top/Article/details/gt2ljixzqfg.html

SHOW INDEX FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2wywcymgq.html

[Q73] 查看表状态
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2twkkltxj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ygbpunmw.html

[Q74] 强制使用索引
来源：http://dali.jinqigufen.top/Article/details/gt2vrafiyji.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.fzhhl.top/Article/details/gt2aqanbrck.html

[Q75] 日期格式化
来源：http://dali.9152youxi.cn/Article/details/gt2thlclxuq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gt2iziuvhty.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.wangdashe.top/Article/details/gt2hxzlvplv.html

[Q76] 按天统计
来源：http://dali.dashuyun.cn/Article/details/gt2xymajvuc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yuanzhike.top/Article/details/gt2xqqibuxq.html

[Q77] 时间加减
来源：http://dali.hfpthk.cn/Article/details/gt2fptbeadt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.tian-w.cn/Article/details/gt2tqacxpks.html

[Q78] 当前时间
来源：http://dali.kuanghao11.cn/Article/details/gt2ssuvegbs.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.nanxuanxn.top/Article/details/gt2xtlddrgi.html

[Q79] 字符串拼接
来源：http://dali.yj20258.top/Article/details/gt2cazdjoty.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xuetiantiany.cn/Article/details/gt2sjlulmce.html

[Q80] 字符串截取
来源：http://dali.feifeiyinyue.top/Article/details/gt2wzruwmez.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2alayixrc.html

[Q81] 字符串替换
来源：http://dali.yj20258888.top/Article/details/gt2oozsawtc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2jglspeyq.html

[Q82] 字符长度与字节长度
来源：http://dali.jlsjyb.cn/Article/details/gt2snisbbvu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2lxdosnmz.html

[Q83] 大小写转换
来源：http://dali.hammf.cn/Article/details/gt2yxaclodj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yongpay.top/Article/details/gt2xbtbfbmy.html

[Q84] 去除首尾空格
来源：http://dali.yonumen.top/Article/details/gt2whjwkyuv.html

SELECT TRIM(name) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2krxkwrxu.html

[Q85] 数值取整
来源：http://dali.cheryme.top/Article/details/gt2vegxxjwh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.andypj.xyz/Article/details/gt2buwndlga.html

[Q86] 读取 JSON 字段
来源：http://dali.daxiang520.top/Article/details/gt2civdyqtg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.snrcjt.cn/Article/details/gt2hiuyyxro.html

[Q87] JSON 字段做条件
来源：http://dali.hammf.cn/Article/details/gt2lgoidyzj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.birdmap.top/Article/details/gt2jdpxjthd.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhiwuduotai.top/Article/details/gt2mcdfuqej.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hfpthk.cn/Article/details/gt2ijvyzvne.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2swvujxmi.html

[Q89] 判断表是否存在
来源：http://dali.cqqwz.cn/Article/details/gt2rosxxgmp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xuanzx.com/Article/details/gt2eclkbuij.html

[Q90] 生成序号列
来源：http://dali.havefunace.top/Article/details/gt2jicozqeq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yanxiufei.cn/Article/details/gt2mwcnlzsa.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2bruplpag.html

R. Bash 专题
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tpmvvvdt.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2slwzooly.html

[R01] shebang 与严格模式
来源：http://dali.xuetiantiany.cn/Article/details/gt2frblmjep.html

#!/usr/bin/env bash
来源：http://dali.guowangkeji.top/Article/details/gt2vkeyhcqk.html

set -euo pipefail
来源：http://dali.nwbrower.top/Article/details/gt2gessblnd.html

[R02] 变量赋值与使用
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2djgaduqv.html

name="Tom"; echo "$name"
来源：http://dali.xylfe.cn/Article/details/gt2ytifurgd.html

[R03] 只读变量
来源：http://dali.yangfankeji.com/Article/details/gt2dkgwhymo.html

readonly PI=3.14
来源：http://dali.yvedp.cn/Article/details/gt2oqmydivj.html

[R04] 位置参数
来源：http://dali.chenzaomai.com/Article/details/gt2vntljzix.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jianghu66.top/Article/details/gt2gzoxknyu.html

[R05] 参数默认值
来源：http://dali.hysaishi.cn/Article/details/gt2lrdcumwn.html

name="${1:-default}"
来源：http://dali.birdmap.top/Article/details/gt2dfyanwyq.html

[R06] 判断命令是否存在
来源：http://dali.zycfv.cn/Article/details/gt2adovncoo.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xziqi.cn/Article/details/gt2imfaibdo.html

[R07] if 判断文件
来源：http://dali.ydzc1.top/Article/details/gt2ckbpidns.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vtzskbgd.html

[R08] 数值比较
来源：http://dali.andypj.xyz/Article/details/gt2hpbtsrfz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sysykeji.top/Article/details/gt2wdyirwck.html

[R09] 字符串比较
来源：http://dali.shzxlz.cn/Article/details/gt2mspsinmd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yueranfly.top/Article/details/gt2ohszzxft.html

[R10] 正则匹配
来源：http://dali.zhiwuduotai.top/Article/details/gt2qkvhjvyr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cdnleiting.top/Article/details/gt2aajbyssf.html

[R11] case 多分支
来源：http://dali.guannengcc.top/Article/details/gt2edhejxqs.html

case "$1" in
来源：http://dali.meibo888.top/Article/details/gt2dpohboas.html

start) echo "启动" ;;
来源：http://dali.xinyue.icu/Article/details/gt2gfoojndi.html

stop)  echo "停止" ;;
来源：http://dali.smart0.xyz/Article/details/gt2qqswmahb.html

*)     echo "未知命令" ;;
来源：http://dali.guannengcc.top/Article/details/gt2vgetaimd.html

esac
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dzyvszun.html

[R12] for 遍历文件
来源：http://dali.redwolf501.top/Article/details/gt2qdpsyuvy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shuidangran.top/Article/details/gt2lmhjhyso.html

[R13] for 计数循环
来源：http://dali.fengsongda.top/Article/details/gt2ojeuzxph.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jianghu66.top/Article/details/gt2fwefnuhf.html

[R14] C 风格 for
来源：http://dali.dianchejie.cn/Article/details/gt2tnbqtdge.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.c1oappe.top/Article/details/gt2ufdgdsgb.html

[R15] while 逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gt2lmwrvgsh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.feifeiyinyue.top/Article/details/gt2yvncwjkf.html

[R16] until 等待条件
来源：http://dali.jinqigufen.top/Article/details/gt2egwfusjy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gcnszhxy.html

[R17] 数组定义与取值
来源：http://dali.sweek.top/Article/details/gt2ptclizmf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zycfv.cn/Article/details/gt2hpiibaqn.html

[R18] 遍历数组
来源：http://dali.cucudq.cn/Article/details/gt2llmsrwpg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gzhubu.top/Article/details/gt2wsjhwint.html

[R19] 数组长度
来源：http://dali.mhx1999.top/Article/details/gt2qfeouody.html

echo "${#arr[@]}"
来源：http://dali.gogol.net.cn/Article/details/gt2liownysg.html

[R20] 关联数组（字典）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2irqmsdvz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cdnleiting.top/Article/details/gt2xvokteun.html

[R21] 字符串长度
来源：http://dali.jqgfzy.top/Article/details/gt2fomdmtfd.html

echo "${#s}"
来源：http://dali.nanxuanxn.top/Article/details/gt2wvldjfgo.html

[R22] 截取子串
来源：http://dali.316326.xyz/Article/details/gt2tvvhlhvq.html

echo "${s:0:5}"
来源：http://dali.meibo888.top/Article/details/gt2yumjjgqd.html

[R23] 字符串替换
来源：http://dali.zhoulong.xyz/Article/details/gt2dgoljpcg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.pengpengdd.cyou/Article/details/gt2ikaufscn.html

[R24] 大小写转换
来源：http://dali.yueranfly.top/Article/details/gt2qxguulns.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hnqzz.top/Article/details/gt2jaxoqobg.html

[R25] 去后缀 / 去前缀
来源：http://dali.hongshengwenyu.top/Article/details/gt2pnrbtjvh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yanxiufei.cn/Article/details/gt2osdmeyvb.html

[R26] 命令替换
来源：http://dali.cucudq.cn/Article/details/gt2qmadbtcr.html

now=$(date +%F); echo "$now"
来源：http://dali.yj202588.top/Article/details/gt2bafkaskf.html

[R27] 算术展开
来源：http://dali.quarkkingdee.top/Article/details/gt2esaidkkx.html

echo $((1 + 2 * 3))
来源：http://dali.zhixingplan.top/Article/details/gt2ackiubhr.html

[R28] 浮点运算
来源：http://dali.yanxiufei.cn/Article/details/gt2meqkwkfr.html

echo "scale=2; 10/3" | bc
来源：http://dali.pycfn.com/Article/details/gt2wqwkfsxh.html

[R29] 定义函数
来源：http://dali.haohaochexian.top/Article/details/gt2xmgjmdwi.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rovgmxya.html

[R30] 函数返回状态码
来源：http://dali.zycfv.cn/Article/details/gt2aihuicjr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sxryk.cn/Article/details/gt2qdwuggzt.html

[R31] 局部变量
来源：http://dali.gzhubu.top/Article/details/gt2ttojordr.html

f() { local x=1; echo "$x"; }
来源：http://dali.aizwys.cn/Article/details/gt2vqvsrnlx.html

[R32] 参数个数校验
来源：http://dali.chenjidiqi.icu/Article/details/gt2gvfzjgui.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.316326.xyz/Article/details/gt2wstlakbi.html

[R33] 捕获错误并提示行号
来源：http://dali.xziqi.cn/Article/details/gt2dmhkfvyu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hammf.cn/Article/details/gt2dqgtamiy.html

[R34] 退出时清理
来源：http://dali.ivvv.top/Article/details/gt2lsbvidif.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.meibo888.top/Article/details/gt2uprjqkvs.html

[R35] 后台执行并等待
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ldkwaxlo.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.wangdashe.top/Article/details/gt2tpfstasg.html

[R36] 并发执行多个任务
来源：http://dali.hammf.cn/Article/details/gt2ozqoygud.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhengqikj.top/Article/details/gt2zeibsviu.html

[R37] 把输出赋给变量
来源：http://dali.cucudq.cn/Article/details/gt2vwdsmesm.html

files=$(ls -1)
来源：http://dali.c1oappe.top/Article/details/gt2lwsxxngf.html

[R38] 管道串联
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qycgazrj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ppjwa.cn/Article/details/gt2bqyqlgfh.html

[R39] 重定向标准输出与错误
来源：http://dali.316326.xyz/Article/details/gt2dvavdmmu.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2arcfjwtp.html

[R40] 追加写日志
来源：http://dali.snrcjt.cn/Article/details/gt2sfxrtqwo.html

echo "log" >> out.log
来源：http://dali.aibaodan.cn/Article/details/gt2urlofssq.html

[R41] 丢弃输出
来源：http://dali.guannengcc.top/Article/details/gt2iqyzfzia.html

cmd >/dev/null 2>&1
来源：http://dali.guannengcc.top/Article/details/gt2emhgjhzu.html

[R42] 输入重定向
来源：http://dali.fzhhl.top/Article/details/gt2rgvyxagj.html

wc -l < a.txt
来源：http://dali.dashuyun.cn/Article/details/gt2edrtwafv.html

[R43] 按名字查找文件
来源：http://dali.gogol.net.cn/Article/details/gt2zgeuqdeo.html

find . -name "*.log" -type f
来源：http://dali.bjfxy.top/Article/details/gt2neaqgkrp.html

[R44] 按修改时间查找
来源：http://dali.jinqigfzy.top/Article/details/gt2whpoywjo.html

find . -mtime -7 -type f
来源：http://dali.andypj.xyz/Article/details/gt2learwsme.html

[R45] 批量删除
来源：http://dali.ppjwa.cn/Article/details/gt2cvlfwmnf.html

find . -name "*.tmp" -delete
来源：http://dali.chenzaomai.com/Article/details/gt2tuhpoqxh.html

[R46] 递归替换文件内容
来源：http://dali.xziqi.cn/Article/details/gt2tulzxnhe.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.wangshuangyany.cn/Article/details/gt2aqvkfxmm.html

[R47] sed 单行替换
来源：http://dali.hfpthk.cn/Article/details/gt2mdonxdlw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yangfankeji.com/Article/details/gt2yhidpwfs.html

[R48] awk 取指定列
来源：http://dali.feifeiyinyue.top/Article/details/gt2egwftxjk.html

awk '{print $1, $3}' a.txt
来源：http://dali.xziqi.cn/Article/details/gt2mpxclkfc.html

[R49] awk 带条件
来源：http://dali.daxiang520.top/Article/details/gt2lcujzajc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jianghu66.top/Article/details/gt2rlraqyne.html

[R50] awk 求和
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vpkobqmb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gt2ehrcwqth.html

[R51] 排序去重取前几
来源：http://dali.kuanghao11.cn/Article/details/gt2lfjokptl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.nwbrower.top/Article/details/gt2xiuscsde.html

[R52] 统计行数
来源：http://dali.jqgfzy.top/Article/details/gt2ptkvmljw.html

wc -l a.txt
来源：http://dali.guannengcc.top/Article/details/gt2cxtooqii.html

[R53] 查看文件头与实时尾
来源：http://dali.iojbl.cn/Article/details/gt2ysqdmxoo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.pengpengdd.cyou/Article/details/gt2dpqdmkix.html

[R54] 比较两个文件
来源：http://dali.snrcjt.cn/Article/details/gt2twebjged.html

diff a.txt b.txt
来源：http://dali.xinyue.icu/Article/details/gt2uqmowpjn.html

[R55] 压缩与解压
来源：http://dali.xziqi.cn/Article/details/gt2coyhflsp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yuxming.cn/Article/details/gt2ofjqbzgn.html

[R56] 远程拷贝
来源：http://dali.ehwqpu.com/Article/details/gt2xttxumcq.html

scp file user@host:/path/
来源：http://dali.bjfxy.top/Article/details/gt2yicbkbiz.html

[R57] 远程执行命令
来源：http://dali.zhoulong.xyz/Article/details/gt2sowopdqz.html

ssh user@host 'uptime'
来源：http://dali.zdqjudy.top/Article/details/gt2ijmnyetc.html

[R58] 下载文件
来源：http://dali.dianchejie.cn/Article/details/gt2ubwqxliz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.pengpengdd.cyou/Article/details/gt2covtlmwd.html

[R59] 发 POST JSON
来源：http://dali.hammf.cn/Article/details/gt2eqmquvbv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hnxiangtu.top/Article/details/gt2hfeedvne.html

[R60] 只看 HTTP 状态码
来源：http://dali.yangfankeji.com/Article/details/gt2trmgkjmo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.snrcjt.cn/Article/details/gt2bykykkhs.html

[R61] 磁盘占用
来源：http://dali.zdqjudy.top/Article/details/gt2duglkfhq.html

df -h;  du -sh *
来源：http://dali.xziqi.cn/Article/details/gt2uolauhof.html

[R62] 找最占空间的文件
来源：http://dali.nwbrower.top/Article/details/gt2ubzmcpej.html

du -ah . | sort -rh | head -10
来源：http://dali.tanke756.top/Article/details/gt2luuxtdea.html

[R63] 内存与进程
来源：http://dali.xuanzx.com/Article/details/gt2pqdfjldt.html

free -h;  ps aux | grep nginx
来源：http://dali.hysaishi.cn/Article/details/gt2odgubzwa.html

[R64] 结束进程
来源：http://dali.birdmap.top/Article/details/gt2rzxgtfqr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cqqwz.cn/Article/details/gt2rrsbumkg.html

[R65] 查看端口占用
来源：http://dali.kuanghao11.cn/Article/details/gt2yherdwfx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.fengsongda.top/Article/details/gt2vagtxkbj.html

[R66] 定时任务
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ixwieucl.html

crontab -e;  crontab -l
来源：http://dali.zhixingplan.top/Article/details/gt2xnqjttgh.html

[R67] 生成随机十六进制串
来源：http://dali.iojbl.cn/Article/details/gt2nbezbrkc.html

openssl rand -hex 16
来源：http://dali.jqgufenzy.top/Article/details/gt2jsxesmak.html

[R68] 计算文件校验值
来源：http://dali.wangshuangyany.cn/Article/details/gt2mbcnqgxr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.9152youxi.cn/Article/details/gt2picinfgh.html

[R69] 生成随机密码
来源：http://dali.xinyue.icu/Article/details/gt2tagdyzzt.html

head -c 16 /dev/urandom | base64
来源：http://dali.havefunace.top/Article/details/gt2rgsyzvqf.html

[R70] 时间戳与互转
来源：http://dali.shangyingyoupin.top/Article/details/gt2sycnrcvv.html

date +%s;  date -d @1700000000
来源：http://dali.redwolf501.top/Article/details/gt2bsfnoyvz.html

[R71] 日期格式化
来源：http://dali.yueranfly.top/Article/details/gt2afggcvoi.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.meibo888.top/Article/details/gt2fwaccwng.html

[R72] 等待端口就绪
来源：http://dali.sweek.top/Article/details/gt2vilfpjwz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.redwolf501.top/Article/details/gt2gliuhtpr.html

[R73] 分割大日志
来源：http://dali.nanxinkj.top/Article/details/gt2jpbwjhjm.html

split -l 1000 big.log part_
来源：http://dali.zhongyouzk.top/Article/details/gt2kwpzdftx.html

[R74] 批量重命名
来源：http://dali.ybcxt.top/Article/details/gt2ftifnlpo.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xylfe.cn/Article/details/gt2bpnhzxpn.html

[R75] 导出环境变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uajkkqrn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.guannengcc.top/Article/details/gt2gqeeyhiq.html

[R76] 使用临时文件
来源：http://dali.ybcxt.top/Article/details/gt2zrcbsxef.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.tian-w.cn/Article/details/gt2udjxwktj.html

[R77] 读取用户输入
来源：http://dali.jinqigufen.top/Article/details/gt2zmfrkwyf.html

read -rp "请输入: " ans
来源：http://dali.zhoulong.xyz/Article/details/gt2neddaxlh.html

[R78] 交互式菜单
来源：http://dali.hfpthk.cn/Article/details/gt2vqxyknfy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sufxvd.cn/Article/details/gt2euzjbbdb.html

[R79] 解析命令行选项
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ngzgfnyn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jxkpmczs.html

[R80] 查看脚本执行耗时
来源：http://dali.zhengqikj.top/Article/details/gt2dgxlfkdd.html

time ./run.sh
来源：http://dali.shanyushiyangtech.top/Article/details/gt2grprxjug.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2bbhleaxt.html

S. C / C++ 专题
来源：http://dali.guowangkeji.top/Article/details/gt2gatfpwfy.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2rkftbije.html

[S01] C：Hello World
来源：http://dali.redwolf501.top/Article/details/gt2hqwqjgrx.html

#include <stdio.h>
来源：http://dali.aizwys.cn/Article/details/gt2qkyecpun.html


<!-- 参考信息 -->