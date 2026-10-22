代发 wailian999

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gt2rsjyqzlx.html

[Q28] 求和与平均
来源：http://dali.feifeiyinyue.top/Article/details/gt2mmebgwme.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yj20258.top/Article/details/gt2yvynuzfb.html

[Q29] 最大最小值
来源：http://dali.tianlin.xyz/Article/details/gt2hiswyqel.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2qiravuyn.html

[Q30] 分组统计
来源：http://dali.ivvv.top/Article/details/gt2uvcmtrsq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yvedp.cn/Article/details/gt2pkmwklwk.html

[Q31] 分组后过滤
来源：http://dali.hywenlv.cn/Article/details/gt2cjngblbp.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yj202588.top/Article/details/gt2tirvdkcw.html

[Q32] 分组拼接字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2baxazzwl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.meibo888.top/Article/details/gt2kullhfhl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.c1oappe.top/Article/details/gt2qmjvdmpi.html

[Q33] 多列分组
来源：http://dali.cashguo.top/Article/details/gt2itfzpbag.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hnqzz.top/Article/details/gt2jrpwcknh.html

[Q34] 每组取第一条
来源：http://dali.quarkkingdee.top/Article/details/gt2zzplsrso.html

SELECT * FROM (
来源：http://dali.hammf.cn/Article/details/gt2smvbkihk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yueranfly.top/Article/details/gt2fybnvxvt.html

) t WHERE rn = 1;
来源：http://dali.jinqigufen.top/Article/details/gt2oqyqppde.html

[Q35] 内连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mwwamymn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yvedp.cn/Article/details/gt2hyifysdq.html

[Q36] 左连接
来源：http://dali.hnqzz.top/Article/details/gt2adfgvqli.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yedkbghd.html

[Q37] 右连接
来源：http://dali.yj202588.top/Article/details/gt2amhuszrt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.tian-w.cn/Article/details/gt2vvxsryda.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mwaiuqgw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.wangshuangyany.cn/Article/details/gt2inzultdq.html

[Q39] 自连接（查上下级）
来源：http://dali.mhx1999.top/Article/details/gt2tseeymsh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.smart0.xyz/Article/details/gt2hkctsxsu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhengqikj.top/Article/details/gt2kfplndrf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ehwqpu.com/Article/details/gt2uvlgfojp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hongshengwenyu.top/Article/details/gt2uxejpmsd.html

[Q41] 多表连接
来源：http://dali.cashguo.top/Article/details/gt2nnbxyxid.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xuanzx.com/Article/details/gt2dcietzvl.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ydzc1.top/Article/details/gt2hhcnrnho.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.meibo888.top/Article/details/gt2ueidgece.html

[Q42] 连接条件附加过滤
来源：http://dali.svipenyu.cn/Article/details/gt2daxxmdbt.html

SELECT u.name, o.amount FROM users u
来源：http://dali.meibo888.top/Article/details/gt2zejxttqj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.smart0.xyz/Article/details/gt2rvhhvlhb.html

[Q43] 标量子查询
来源：http://dali.jqgfzy.top/Article/details/gt2ihxxelui.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.fzhhl.top/Article/details/gt2wquqsvkr.html

[Q44] IN 子查询
来源：http://dali.ehwqpu.com/Article/details/gt2bormucex.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinqigufen.top/Article/details/gt2plmpwlcs.html

[Q45] EXISTS 判断存在
来源：http://dali.zhengqikj.top/Article/details/gt2jaqslpjd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cqqwz.cn/Article/details/gt2ecvsrqhl.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhengqikj.top/Article/details/gt2gmrypddk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangshuangyany.cn/Article/details/gt2okvznfqp.html

[Q47] 与平均值比较
来源：http://dali.svipenyu.cn/Article/details/gt2uuqnegqu.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhoulong.xyz/Article/details/gt2faskgbvg.html

[Q48] CTE 公用表表达式
来源：http://dali.yj20258.top/Article/details/gt2vnanbdmg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yonumen.top/Article/details/gt2gkrxpwob.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zdqjudy.top/Article/details/gt2tjxxvmat.html

[Q49] 更新单行
来源：http://dali.gaohongyu789.top/Article/details/gt2xcrdwbxj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yj20258.top/Article/details/gt2ksofhnff.html

[Q50] 批量更新
来源：http://dali.guowangkeji.top/Article/details/gt2etdspyqu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yuanzhike.top/Article/details/gt2cyfonvvg.html

[Q51] 用子查询更新
来源：http://dali.smart0.xyz/Article/details/gt2kskxukwg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zdqjudy.top/Article/details/gt2cynqjnkx.html

[Q52] 删除指定行
来源：http://dali.smart0.xyz/Article/details/gt2axpjaxpe.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cheryme.top/Article/details/gt2hphszntm.html

[Q53] 按条件删除
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2djvbkpnz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.vqdsnc.cn/Article/details/gt2hjegsdmw.html

[Q54] 清空表
来源：http://dali.snrcjt.cn/Article/details/gt2vdvqbypi.html

TRUNCATE TABLE logs;
来源：http://dali.yj20258888.top/Article/details/gt2sxcghslz.html

[Q55] 排名（并列占位）
来源：http://dali.xinyue.icu/Article/details/gt2ftqbyiwz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.guannengcc.top/Article/details/gt2eawfvxoe.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hnqzz.top/Article/details/gt2ufjnlosm.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ivvv.top/Article/details/gt2ponnnxxo.html

[Q57] 行号
来源：http://dali.cdnleiting.top/Article/details/gt2xieyuros.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gt2wtzwidbf.html

[Q58] 累计求和
来源：http://dali.pengpengdd.cyou/Article/details/gt2hozsoufd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gt2djbtswxn.html

[Q59] 分组内累计
来源：http://dali.chenzaomai.com/Article/details/gt2bdaazosg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gt2gwfrbtms.html

[Q60] 取上一行 / 下一行
来源：http://dali.ppjwa.cn/Article/details/gt2mfchuygc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yj20258.top/Article/details/gt2piavfbix.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gt2zbpdwali.html

[Q61] 移动平均
来源：http://dali.shanyushiyangtech.top/Article/details/gt2isqwissj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2czfxwijq.html

[Q62] 分组占比
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2taqbswcn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cashguo.top/Article/details/gt2nlbrqhcl.html

[Q63] 开启事务
来源：http://dali.hnqzz.top/Article/details/gt2ewefeghr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.chenlongwang.top/Article/details/gt2fqhxrewc.html

[Q64] 提交事务
来源：http://dali.nanxuanxn.top/Article/details/gt2fptmompj.html

COMMIT;
来源：http://dali.sxryk.cn/Article/details/gt2yupkyald.html

[Q65] 回滚事务
来源：http://dali.xziqi.cn/Article/details/gt2hjobcnyi.html

ROLLBACK;
来源：http://dali.feifeiyinyue.top/Article/details/gt2ifjezsyv.html

[Q66] 行锁查询
来源：http://dali.yj20258.top/Article/details/gt2unpwtocb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cheryme.top/Article/details/gt2cmgakosf.html

[Q67] 设置隔离级别
来源：http://dali.hywenlv.cn/Article/details/gt2dixgztwz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.dianchejie.cn/Article/details/gt2cwpmekai.html

[Q68] 保存点
来源：http://dali.zhixingplan.top/Article/details/gt2pmryqplo.html

SAVEPOINT sp1;
来源：http://dali.sysykeji.top/Article/details/gt2lqkboqnk.html

ROLLBACK TO sp1;
来源：http://dali.sxryk.cn/Article/details/gt2arfklzfg.html

[Q69] 查看执行计划
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2taajrfbh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vsmoksmi.html

[Q70] 更新统计信息
来源：http://dali.yuanzhike.top/Article/details/gt2oszfwkvr.html

ANALYZE TABLE users;
来源：http://dali.jqgufenzy.top/Article/details/gt2dcyjgbbu.html

[Q71] 查看建表语句
来源：http://dali.gotoacloud.top/Article/details/gt2ovevlegf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ydzc1.top/Article/details/gt2nyzkaxjd.html

[Q72] 查看索引
来源：http://dali.smart0.xyz/Article/details/gt2qxweaavp.html

SHOW INDEX FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2zzvhcffa.html

[Q73] 查看表状态
来源：http://dali.meibo888.top/Article/details/gt2syxhkpsx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.guannengcc.top/Article/details/gt2jdiumwnw.html

[Q74] 强制使用索引
来源：http://dali.aizwys.cn/Article/details/gt2zeejwiff.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhengqikj.top/Article/details/gt2rnsohkjw.html

[Q75] 日期格式化
来源：http://dali.wangshuangyany.cn/Article/details/gt2hplkobcz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yueranfly.top/Article/details/gt2yzcxdaju.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinqigufen.top/Article/details/gt2vjevtciv.html

[Q76] 按天统计
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2subzztyd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jlsjyb.cn/Article/details/gt2khhvdtxl.html

[Q77] 时间加减
来源：http://dali.tian-w.cn/Article/details/gt2ehmsghot.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shangyingyoupin.top/Article/details/gt2emosxkdi.html

[Q78] 当前时间
来源：http://dali.daria6918.cn/Article/details/gt2dwvoehod.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jqgufenzy.top/Article/details/gt2ipsqaqep.html

[Q79] 字符串拼接
来源：http://dali.ehwqpu.com/Article/details/gt2pydvmjwa.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.aibaodan.cn/Article/details/gt2ydmqkett.html

[Q80] 字符串截取
来源：http://dali.bjfxy.top/Article/details/gt2claeiskd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.meibo888.top/Article/details/gt2kiinvakf.html

[Q81] 字符串替换
来源：http://dali.yj20258.top/Article/details/gt2sgqinxln.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2hnfbdefd.html

[Q82] 字符长度与字节长度
来源：http://dali.mhx1999.top/Article/details/gt2nkztugnd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2iilsessi.html

[Q83] 大小写转换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2stdfllce.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2byszoqmf.html

[Q84] 去除首尾空格
来源：http://dali.tianlin.xyz/Article/details/gt2iwdkhftn.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mivlxhdf.html

[Q85] 数值取整
来源：http://dali.jianghu66.top/Article/details/gt2mlgcbxyl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.haohaochexian.top/Article/details/gt2tslqjmya.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2phncjkxf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jqgufenzy.top/Article/details/gt2rxldsygb.html

[Q87] JSON 字段做条件
来源：http://dali.nanxuanxn.top/Article/details/gt2ehqdyahy.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zycfv.cn/Article/details/gt2ezyebykw.html

[Q88] 行转列（条件聚合）
来源：http://dali.snrcjt.cn/Article/details/gt2nxikhnxj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xziqi.cn/Article/details/gt2dxvlsaav.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2wrxxussr.html

[Q89] 判断表是否存在
来源：http://dali.yuxming.cn/Article/details/gt2xhpbsbux.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xuetiantiany.cn/Article/details/gt2msgcaqka.html

[Q90] 生成序号列
来源：http://dali.sxryk.cn/Article/details/gt2wmertbzp.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ghctqsrs.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2tilvznzs.html

R. Bash 专题
来源：http://dali.cdnleiting.top/Article/details/gt2yvikcuxx.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2apmtqgeq.html

[R01] shebang 与严格模式
来源：http://dali.jqgfzy.top/Article/details/gt2kganvwpl.html

#!/usr/bin/env bash
来源：http://dali.sxryk.cn/Article/details/gt2jtajnoow.html

set -euo pipefail
来源：http://dali.tianlin.xyz/Article/details/gt2bqwqumrb.html

[R02] 变量赋值与使用
来源：http://dali.hongshengwenyu.top/Article/details/gt2bisvrhdu.html

name="Tom"; echo "$name"
来源：http://dali.yj20258888.top/Article/details/gt2fgyyuhbk.html

[R03] 只读变量
来源：http://dali.gzhubu.top/Article/details/gt2wedtbjds.html

readonly PI=3.14
来源：http://dali.quarkkingdee.top/Article/details/gt2sgkzrfdu.html

[R04] 位置参数
来源：http://dali.yuxming.cn/Article/details/gt2pbmmkkag.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.mhx1999.top/Article/details/gt2dlxrxmbs.html

[R05] 参数默认值
来源：http://dali.wangshuangyany.cn/Article/details/gt2snfdowib.html

name="${1:-default}"
来源：http://dali.yj202588.top/Article/details/gt2yyvsnizf.html

[R06] 判断命令是否存在
来源：http://dali.yongpay.top/Article/details/gt2okwuzycg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hnqzz.top/Article/details/gt2mzffvgdd.html

[R07] if 判断文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2kqdohrid.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cashguo.top/Article/details/gt2sgtoxacf.html

[R08] 数值比较
来源：http://dali.pycfn.com/Article/details/gt2cpflxver.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sxryk.cn/Article/details/gt2nkqhiljc.html

[R09] 字符串比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nfpifpkt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.snrcjt.cn/Article/details/gt2apdlrznu.html

[R10] 正则匹配
来源：http://dali.jiagoushi.top/Article/details/gt2yacbmhfs.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hysaishi.cn/Article/details/gt2voovqopq.html

[R11] case 多分支
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dnudbjnt.html

case "$1" in
来源：http://dali.iojbl.cn/Article/details/gt2eimamccc.html

start) echo "启动" ;;
来源：http://dali.quarkkingdee.top/Article/details/gt2hrcmurla.html

stop)  echo "停止" ;;
来源：http://dali.daxiang520.top/Article/details/gt2pxzaslds.html

*)     echo "未知命令" ;;
来源：http://dali.bjfxy.top/Article/details/gt2thuffwoe.html

esac
来源：http://dali.tanke756.top/Article/details/gt2ialgxntp.html

[R12] for 遍历文件
来源：http://dali.jlsjyb.cn/Article/details/gt2vwstucjf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cashguo.top/Article/details/gt2rqvemfev.html

[R13] for 计数循环
来源：http://dali.kuanghao11.cn/Article/details/gt2osxotdpx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhixingplan.top/Article/details/gt2nixrihea.html

[R14] C 风格 for
来源：http://dali.gaohongyu789.top/Article/details/gt2khoymcyt.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yanxiufei.cn/Article/details/gt2uhpxsfvt.html

[R15] while 逐行读文件
来源：http://dali.xuanzx.com/Article/details/gt2vhumlpcx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhixingplan.top/Article/details/gt2hxpwnlrd.html

[R16] until 等待条件
来源：http://dali.dashuyun.cn/Article/details/gt2mffuhstp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.tanke756.top/Article/details/gt2kjiaeofj.html

[R17] 数组定义与取值
来源：http://dali.hysaishi.cn/Article/details/gt2mknqitla.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sxryk.cn/Article/details/gt2zpioqvwl.html

[R18] 遍历数组
来源：http://dali.gzhubu.top/Article/details/gt2vrgwgbza.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.nanxinkj.top/Article/details/gt2dmkmqafm.html

[R19] 数组长度
来源：http://dali.xylfe.cn/Article/details/gt2gjkovfgn.html

echo "${#arr[@]}"
来源：http://dali.daxiang520.top/Article/details/gt2nshcwdbq.html

[R20] 关联数组（字典）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cdvwenhw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xziqi.cn/Article/details/gt2unnlsmio.html

[R21] 字符串长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2srwblkck.html

echo "${#s}"
来源：http://dali.daxiang520.top/Article/details/gt2wuwsenqn.html

[R22] 截取子串
来源：http://dali.hammf.cn/Article/details/gt2ejcmtiyz.html

echo "${s:0:5}"
来源：http://dali.c1oappe.top/Article/details/gt2ptmcsutd.html

[R23] 字符串替换
来源：http://dali.yonumen.top/Article/details/gt2hsrnfhen.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.haohaochexian.top/Article/details/gt2dczwgxmf.html

[R24] 大小写转换
来源：http://dali.ehwqpu.com/Article/details/gt2gkijfgri.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinqigufen.top/Article/details/gt2yvaixvbh.html

[R25] 去后缀 / 去前缀
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tgzndtrh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shuidangran.top/Article/details/gt2bvzqfsws.html

[R26] 命令替换
来源：http://dali.9152youxi.cn/Article/details/gt2vphkvyzm.html

now=$(date +%F); echo "$now"
来源：http://dali.xziqi.cn/Article/details/gt2cyeavxni.html

[R27] 算术展开
来源：http://dali.cdnleiting.top/Article/details/gt2xxjkufjw.html

echo $((1 + 2 * 3))
来源：http://dali.xuanzx.com/Article/details/gt2bggrjuxb.html

[R28] 浮点运算
来源：http://dali.sweek.top/Article/details/gt2qevlrapc.html

echo "scale=2; 10/3" | bc
来源：http://dali.cqqwz.cn/Article/details/gt2qzpyogof.html

[R29] 定义函数
来源：http://dali.zhongyouzk.top/Article/details/gt2mdovzjcw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jqgfzy.top/Article/details/gt2advwecrt.html

[R30] 函数返回状态码
来源：http://dali.iojbl.cn/Article/details/gt2yuurilqu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.gogol.net.cn/Article/details/gt2cxehmqcy.html

[R31] 局部变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zudzlwov.html

f() { local x=1; echo "$x"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2thxnkuhd.html

[R32] 参数个数校验
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2luolsqbe.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shzxlz.cn/Article/details/gt2ofcqdsde.html

[R33] 捕获错误并提示行号
来源：http://dali.cqqwz.cn/Article/details/gt2pcroukre.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.birdmap.top/Article/details/gt2homjfgsy.html

[R34] 退出时清理
来源：http://dali.tian-w.cn/Article/details/gt2bygmugqa.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.bjfxy.top/Article/details/gt2zjvvvgkf.html

[R35] 后台执行并等待
来源：http://dali.hnxiangtu.top/Article/details/gt2kqtuardz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinqigufen.top/Article/details/gt2pabwykmk.html

[R36] 并发执行多个任务
来源：http://dali.nwbrower.top/Article/details/gt2ziylfrzn.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cheryme.top/Article/details/gt2ktywdfdh.html

[R37] 把输出赋给变量
来源：http://dali.nanxuanxn.top/Article/details/gt2ghegnuoj.html

files=$(ls -1)
来源：http://dali.gaohongyu789.top/Article/details/gt2diyfgfqx.html

[R38] 管道串联
来源：http://dali.chenlongwang.top/Article/details/gt2njweflkq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cqqwz.cn/Article/details/gt2oscpiong.html

[R39] 重定向标准输出与错误
来源：http://dali.yueranfly.top/Article/details/gt2olemffuv.html

cmd > out.log 2>&1
来源：http://dali.xuetiantiany.cn/Article/details/gt2mjbdbegh.html

[R40] 追加写日志
来源：http://dali.dianchejie.cn/Article/details/gt2eexcequg.html

echo "log" >> out.log
来源：http://dali.jianghu66.top/Article/details/gt2emfqlgqm.html

[R41] 丢弃输出
来源：http://dali.cdnleiting.top/Article/details/gt2uxsqxkqj.html

cmd >/dev/null 2>&1
来源：http://dali.mhx1999.top/Article/details/gt2cmwdgsov.html

[R42] 输入重定向
来源：http://dali.cqqwz.cn/Article/details/gt2okwnbljd.html

wc -l < a.txt
来源：http://dali.daxiang520.top/Article/details/gt2heghzqai.html

[R43] 按名字查找文件
来源：http://dali.yvedp.cn/Article/details/gt2ubvqrqzo.html

find . -name "*.log" -type f
来源：http://dali.meibo888.top/Article/details/gt2pwqksgsu.html

[R44] 按修改时间查找
来源：http://dali.jinqigufen.top/Article/details/gt2dfmzoagg.html

find . -mtime -7 -type f
来源：http://dali.chenjidiqi.icu/Article/details/gt2lhpiboud.html

[R45] 批量删除
来源：http://dali.snrcjt.cn/Article/details/gt2tbjckitk.html

find . -name "*.tmp" -delete
来源：http://dali.jlsjyb.cn/Article/details/gt2kiaairuz.html

[R46] 递归替换文件内容
来源：http://dali.hfpthk.cn/Article/details/gt2shogbldf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yueranfly.top/Article/details/gt2fcdpwieg.html

[R47] sed 单行替换
来源：http://dali.zhixingplan.top/Article/details/gt2mlbdygvt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yueranfly.top/Article/details/gt2xbldwcfo.html

[R48] awk 取指定列
来源：http://dali.sweek.top/Article/details/gt2miygqagh.html

awk '{print $1, $3}' a.txt
来源：http://dali.xuanzx.com/Article/details/gt2gifybojp.html

[R49] awk 带条件
来源：http://dali.jlsjyb.cn/Article/details/gt2utkmbjmu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhongyouzk.top/Article/details/gt2qcknpelg.html

[R50] awk 求和
来源：http://dali.shangyingyoupin.top/Article/details/gt2mgfvqmce.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hfpthk.cn/Article/details/gt2prhxchqa.html

[R51] 排序去重取前几
来源：http://dali.jiagoushi.top/Article/details/gt2xhwilzla.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhixingplan.top/Article/details/gt2jpxilcqv.html

[R52] 统计行数
来源：http://dali.nanxinkj.top/Article/details/gt2ucbedywh.html

wc -l a.txt
来源：http://dali.daxiang520.top/Article/details/gt2byspkojg.html

[R53] 查看文件头与实时尾
来源：http://dali.hnxiangtu.top/Article/details/gt2hplvkudc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.chenjidiqi.icu/Article/details/gt2cerdgyjf.html

[R54] 比较两个文件
来源：http://dali.yvedp.cn/Article/details/gt2gdnfwkvl.html

diff a.txt b.txt
来源：http://dali.hongshengwenyu.top/Article/details/gt2yxfhrhur.html

[R55] 压缩与解压
来源：http://dali.jiagoushi.top/Article/details/gt2pceoggpz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gogol.net.cn/Article/details/gt2uylkvqhu.html

[R56] 远程拷贝
来源：http://dali.ybcxt.top/Article/details/gt2egkfweou.html

scp file user@host:/path/
来源：http://dali.yonumen.top/Article/details/gt2jufunkrp.html

[R57] 远程执行命令
来源：http://dali.hnqzz.top/Article/details/gt2cfvsqhqk.html

ssh user@host 'uptime'
来源：http://dali.yj20258.top/Article/details/gt2mvjutahd.html

[R58] 下载文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2eouziemx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cheryme.top/Article/details/gt2dfvjiikh.html

[R59] 发 POST JSON
来源：http://dali.kuanghao11.cn/Article/details/gt2czrzaepy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhiwuduotai.top/Article/details/gt2oxpvaszq.html

[R60] 只看 HTTP 状态码
来源：http://dali.cucudq.cn/Article/details/gt2fgmronnh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.birdmap.top/Article/details/gt2rtahdvpp.html

[R61] 磁盘占用
来源：http://dali.smart0.xyz/Article/details/gt2csejyisi.html

df -h;  du -sh *
来源：http://dali.jqgufenzy.top/Article/details/gt2dqycobin.html

[R62] 找最占空间的文件
来源：http://dali.hfpthk.cn/Article/details/gt2xcazqzya.html

du -ah . | sort -rh | head -10
来源：http://dali.yj20258.top/Article/details/gt2bjtkrrvi.html

[R63] 内存与进程
来源：http://dali.vqdsnc.cn/Article/details/gt2vwvcyzko.html

free -h;  ps aux | grep nginx
来源：http://dali.bjfxy.top/Article/details/gt2doytmafo.html

[R64] 结束进程
来源：http://dali.pycfn.com/Article/details/gt2hygqpshe.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shuidangran.top/Article/details/gt2kscopwix.html

[R65] 查看端口占用
来源：http://dali.jlsjyb.cn/Article/details/gt2uyjwvjov.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cucudq.cn/Article/details/gt2fudskfay.html

[R66] 定时任务
来源：http://dali.ybcxt.top/Article/details/gt2xeaxrykv.html

crontab -e;  crontab -l
来源：http://dali.fengsongda.top/Article/details/gt2mkzsngat.html

[R67] 生成随机十六进制串
来源：http://dali.gzhubu.top/Article/details/gt2iiqvbkca.html

openssl rand -hex 16
来源：http://dali.hysaishi.cn/Article/details/gt2amiroxsl.html

[R68] 计算文件校验值
来源：http://dali.nwbrower.top/Article/details/gt2hthjoarz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xylfe.cn/Article/details/gt2vzvdbwhv.html

[R69] 生成随机密码
来源：http://dali.cqqwz.cn/Article/details/gt2vkbhcocy.html

head -c 16 /dev/urandom | base64
来源：http://dali.yuanzhike.top/Article/details/gt2ffckbnhx.html

[R70] 时间戳与互转
来源：http://dali.hfpthk.cn/Article/details/gt2penjfyse.html

date +%s;  date -d @1700000000
来源：http://dali.jyoumei.cn/Article/details/gt2cnsxojdp.html

[R71] 日期格式化
来源：http://dali.ivvv.top/Article/details/gt2dnykwfbu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hammf.cn/Article/details/gt2ccatjkuz.html

[R72] 等待端口就绪
来源：http://dali.yj202588.top/Article/details/gt2lzwxtyjh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.kuanghao11.cn/Article/details/gt2ykjxmpfd.html

[R73] 分割大日志
来源：http://dali.0kj1m.cn/Article/details/gt2yzaywchc.html

split -l 1000 big.log part_
来源：http://dali.xuanzx.com/Article/details/gt2rbopmdjs.html

[R74] 批量重命名
来源：http://dali.quarkkingdee.top/Article/details/gt2rhavygnz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cashguo.top/Article/details/gt2pmqczcyj.html

[R75] 导出环境变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2xxqhuxny.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jianghu66.top/Article/details/gt2iadqynoa.html

[R76] 使用临时文件
来源：http://dali.mhx1999.top/Article/details/gt2bqmewibs.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.sufxvd.cn/Article/details/gt2wicqhmyr.html

[R77] 读取用户输入
来源：http://dali.mhx1999.top/Article/details/gt2pgylutee.html


<!-- 参考信息 -->