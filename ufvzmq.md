代发 wailian999

[Q36] 左连接
来源：http://dali.sysykeji.top/Article/details/gt2lyeifhti.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.pycfn.com/Article/details/gt2bfhmxuhz.html

[Q37] 右连接
来源：http://dali.shzxlz.cn/Article/details/gt2ylmgnkoz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.daria6918.cn/Article/details/gt2scgylwqy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhixingplan.top/Article/details/gt2rnhvtsxv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.quarkkingdee.top/Article/details/gt2thybkjpa.html

[Q39] 自连接（查上下级）
来源：http://dali.nanxinkj.top/Article/details/gt2rosfcmwx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lhbeuxss.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cdnleiting.top/Article/details/gt2imgokusw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.fengsongda.top/Article/details/gt2fjpxvpgt.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.svipenyu.cn/Article/details/gt2ptaitzat.html

[Q41] 多表连接
来源：http://dali.snrcjt.cn/Article/details/gt2aduwwndl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yj20258888.top/Article/details/gt2qeysggkd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cucudq.cn/Article/details/gt2fstlsonf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jfwptlsb.html

[Q42] 连接条件附加过滤
来源：http://dali.xuanzx.com/Article/details/gt2bggraadx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.havefunace.top/Article/details/gt2nqcnbtbf.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.quarkkingdee.top/Article/details/gt2rudgunwn.html

[Q43] 标量子查询
来源：http://dali.yuanzhike.top/Article/details/gt2pnvvekmm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jinqigufen.top/Article/details/gt2ccpjyvau.html

[Q44] IN 子查询
来源：http://dali.sysykeji.top/Article/details/gt2chyxtlax.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hfpthk.cn/Article/details/gt2bilikils.html

[Q45] EXISTS 判断存在
来源：http://dali.9152youxi.cn/Article/details/gt2gzyidxct.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.pengpengdd.cyou/Article/details/gt2xrqhggkv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wraqwwfz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tianlin.xyz/Article/details/gt2gckvehko.html

[Q47] 与平均值比较
来源：http://dali.fzhhl.top/Article/details/gt2xnhxdepl.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dmzjfvce.html

[Q48] CTE 公用表表达式
来源：http://dali.hammf.cn/Article/details/gt2eutpqztk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhengqikj.top/Article/details/gt2mwquqryz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtyqtmli.html

[Q49] 更新单行
来源：http://dali.svipenyu.cn/Article/details/gt2iuenxtkz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.tianlin.xyz/Article/details/gt2vczlnmcu.html

[Q50] 批量更新
来源：http://dali.vqdsnc.cn/Article/details/gt2vwiqozax.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.chenlongwang.top/Article/details/gt2jcozgegz.html

[Q51] 用子查询更新
来源：http://dali.sxryk.cn/Article/details/gt2ntmaejgn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hfpthk.cn/Article/details/gt2mqlpbjug.html

[Q52] 删除指定行
来源：http://dali.haohaochexian.top/Article/details/gt2suzzdjbp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hysaishi.cn/Article/details/gt2ucibiirq.html

[Q53] 按条件删除
来源：http://dali.nanxuanxn.top/Article/details/gt2kwyevqww.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yj202588.top/Article/details/gt2rcvekkfv.html

[Q54] 清空表
来源：http://dali.chenjidiqi.icu/Article/details/gt2hdimaqeu.html

TRUNCATE TABLE logs;
来源：http://dali.yanxiufei.cn/Article/details/gt2ounlkugz.html

[Q55] 排名（并列占位）
来源：http://dali.yj202588.top/Article/details/gt2owekjgzq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ppjwa.cn/Article/details/gt2sggkqhrg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xuanzx.com/Article/details/gt2sxlvuhfe.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yongpay.top/Article/details/gt2jzczqnxb.html

[Q57] 行号
来源：http://dali.hywenlv.cn/Article/details/gt2ticduscw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2wnhoektn.html

[Q58] 累计求和
来源：http://dali.zdqjudy.top/Article/details/gt2qmdcjxgt.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gt2dpoglemo.html

[Q59] 分组内累计
来源：http://dali.yongpay.top/Article/details/gt2iidcmfzo.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.316326.xyz/Article/details/gt2lcnhmrub.html

[Q60] 取上一行 / 下一行
来源：http://dali.316326.xyz/Article/details/gt2nislgbhx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jianghu66.top/Article/details/gt2jhrjmdjo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gt2ltcjkjvq.html

[Q61] 移动平均
来源：http://dali.xziqi.cn/Article/details/gt2qsgccpwf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gt2mrqnsedx.html

[Q62] 分组占比
来源：http://dali.yvedp.cn/Article/details/gt2dvydgilo.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.havefunace.top/Article/details/gt2vqkansvq.html

[Q63] 开启事务
来源：http://dali.fengsongda.top/Article/details/gt2xoozhokb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shuidangran.top/Article/details/gt2xyuacjye.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwavjza.html

COMMIT;
来源：http://dali.zhiwuduotai.top/Article/details/gt2lyyaykyy.html

[Q65] 回滚事务
来源：http://dali.hongshengwenyu.top/Article/details/gt2uldwwgch.html

ROLLBACK;
来源：http://dali.sxryk.cn/Article/details/gt2xglwckiz.html

[Q66] 行锁查询
来源：http://dali.cqqwz.cn/Article/details/gt2okfuvrlk.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.gogol.net.cn/Article/details/gt2iiftxrzu.html

[Q67] 设置隔离级别
来源：http://dali.316326.xyz/Article/details/gt2qzfcifen.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cheryme.top/Article/details/gt2euvolnii.html

[Q68] 保存点
来源：http://dali.yuxming.cn/Article/details/gt2iodgnwuv.html

SAVEPOINT sp1;
来源：http://dali.jqgufenzy.top/Article/details/gt2yaxizwth.html

ROLLBACK TO sp1;
来源：http://dali.dianchejie.cn/Article/details/gt2zxbodhdx.html

[Q69] 查看执行计划
来源：http://dali.nanxuanxn.top/Article/details/gt2waeuikqk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cdnleiting.top/Article/details/gt2bcddvnwb.html

[Q70] 更新统计信息
来源：http://dali.jlsjyb.cn/Article/details/gt2wdcrilca.html

ANALYZE TABLE users;
来源：http://dali.chenzaomai.com/Article/details/gt2dnzincmt.html

[Q71] 查看建表语句
来源：http://dali.guowangkeji.top/Article/details/gt2yybmqurp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.haohaochexian.top/Article/details/gt2winzqkne.html

[Q72] 查看索引
来源：http://dali.cheryme.top/Article/details/gt2txqhbmmj.html

SHOW INDEX FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gt2lrtemqha.html

[Q73] 查看表状态
来源：http://dali.snrcjt.cn/Article/details/gt2blkwuvuy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhengqikj.top/Article/details/gt2karqcmcz.html

[Q74] 强制使用索引
来源：http://dali.jiagoushi.top/Article/details/gt2npxjvyxh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhoulong.xyz/Article/details/gt2azpkrryd.html

[Q75] 日期格式化
来源：http://dali.yj202588.top/Article/details/gt2qpckygfg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.c1oappe.top/Article/details/gt2ikuawhew.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yonumen.top/Article/details/gt2nxpapuzw.html

[Q76] 按天统计
来源：http://dali.shuidangran.top/Article/details/gt2twkytuov.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cdnleiting.top/Article/details/gt2beoxbacf.html

[Q77] 时间加减
来源：http://dali.vqdsnc.cn/Article/details/gt2ghiddfgk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shangyingyoupin.top/Article/details/gt2sknyxugx.html

[Q78] 当前时间
来源：http://dali.tian-w.cn/Article/details/gt2tnanpojv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cqqwz.cn/Article/details/gt2cimboazt.html

[Q79] 字符串拼接
来源：http://dali.zhoulong.xyz/Article/details/gt2mavjfeef.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.tian-w.cn/Article/details/gt2jnalbpsp.html

[Q80] 字符串截取
来源：http://dali.yvedp.cn/Article/details/gt2reqtttfy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2xuzrnpuo.html

[Q81] 字符串替换
来源：http://dali.havefunace.top/Article/details/gt2viynjfcf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yongpay.top/Article/details/gt2fwhuqspi.html

[Q82] 字符长度与字节长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rhqzihib.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2lerqqdrb.html

[Q83] 大小写转换
来源：http://dali.chenlongwang.top/Article/details/gt2idkumsuk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cheryme.top/Article/details/gt2huaupose.html

[Q84] 去除首尾空格
来源：http://dali.jqgufenzy.top/Article/details/gt2oybjkamv.html

SELECT TRIM(name) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2kvycexwa.html

[Q85] 数值取整
来源：http://dali.pycfn.com/Article/details/gt2ayzjgian.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hfpthk.cn/Article/details/gt2cnrlgqrx.html

[Q86] 读取 JSON 字段
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iylzyyiy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.guannengcc.top/Article/details/gt2mqtgxbtc.html

[Q87] JSON 字段做条件
来源：http://dali.yuanzhike.top/Article/details/gt2lhfqzymr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shangyingyoupin.top/Article/details/gt2lbxwgugc.html

[Q88] 行转列（条件聚合）
来源：http://dali.cdnleiting.top/Article/details/gt2byksuwut.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cashguo.top/Article/details/gt2ioxheagz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2lifnsclv.html

[Q89] 判断表是否存在
来源：http://dali.chenjidiqi.icu/Article/details/gt2uzhetiqw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.0kj1m.cn/Article/details/gt2djrczhnc.html

[Q90] 生成序号列
来源：http://dali.snrcjt.cn/Article/details/gt2ltzlcjlo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gzhubu.top/Article/details/gt2tercznrs.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2xlrnqlup.html

R. Bash 专题
来源：http://dali.zdqjudy.top/Article/details/gt2ycbvhjbe.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2bpdpkujp.html

[R01] shebang 与严格模式
来源：http://dali.xinyue.icu/Article/details/gt2ntmztyqy.html

#!/usr/bin/env bash
来源：http://dali.jinqigufen.top/Article/details/gt2rjthjdnx.html

set -euo pipefail
来源：http://dali.0kj1m.cn/Article/details/gt2quiggxmt.html

[R02] 变量赋值与使用
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yijukndu.html

name="Tom"; echo "$name"
来源：http://dali.fzhhl.top/Article/details/gt2yhjfnvzb.html

[R03] 只读变量
来源：http://dali.havefunace.top/Article/details/gt2nvdqftwa.html

readonly PI=3.14
来源：http://dali.wangshuangyany.cn/Article/details/gt2qbyxkxbv.html

[R04] 位置参数
来源：http://dali.tianlin.xyz/Article/details/gt2ghzmnduw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jiagoushi.top/Article/details/gt2peacpwxf.html

[R05] 参数默认值
来源：http://dali.jyoumei.cn/Article/details/gt2gsbzcwwi.html

name="${1:-default}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2kolrbjiq.html

[R06] 判断命令是否存在
来源：http://dali.9152youxi.cn/Article/details/gt2ahnqeeil.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.pycfn.com/Article/details/gt2dfvcbyht.html

[R07] if 判断文件
来源：http://dali.yueranfly.top/Article/details/gt2lxsghtbl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhixingplan.top/Article/details/gt2dhxtwrbg.html

[R08] 数值比较
来源：http://dali.haohaochexian.top/Article/details/gt2teldfbvo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ydzc1.top/Article/details/gt2ezxvgxxf.html

[R09] 字符串比较
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xgozwnio.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xuetiantiany.cn/Article/details/gt2jxvqvbfy.html

[R10] 正则匹配
来源：http://dali.yvedp.cn/Article/details/gt2eobrxegu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zycfv.cn/Article/details/gt2irtlxcyk.html

[R11] case 多分支
来源：http://dali.jqgfzy.top/Article/details/gt2patgnnvr.html

case "$1" in
来源：http://dali.jiagoushi.top/Article/details/gt2xlnxsngk.html

start) echo "启动" ;;
来源：http://dali.haohaochexian.top/Article/details/gt2khbgrxva.html

stop)  echo "停止" ;;
来源：http://dali.daria6918.cn/Article/details/gt2qbictadm.html

*)     echo "未知命令" ;;
来源：http://dali.tianlin.xyz/Article/details/gt2lyioyybv.html

esac
来源：http://dali.0kj1m.cn/Article/details/gt2ehobrsmr.html

[R12] for 遍历文件
来源：http://dali.kuanghao11.cn/Article/details/gt2swqmmzsg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.tian-w.cn/Article/details/gt2vtyzdwli.html

[R13] for 计数循环
来源：http://dali.fzhhl.top/Article/details/gt2dmkgrzxu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gogol.net.cn/Article/details/gt2usmtwxhn.html

[R14] C 风格 for
来源：http://dali.hysaishi.cn/Article/details/gt2tprtftvw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhengqikj.top/Article/details/gt2vrlovmec.html

[R15] while 逐行读文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2ekheppcf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jyoumei.cn/Article/details/gt2mszhvhsy.html

[R16] until 等待条件
来源：http://dali.nanxinkj.top/Article/details/gt2iisjiosq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.haohaochexian.top/Article/details/gt2bdinxwhp.html

[R17] 数组定义与取值
来源：http://dali.aibaodan.cn/Article/details/gt2rtvqeulm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinqigfzy.top/Article/details/gt2nhiwclim.html

[R18] 遍历数组
来源：http://dali.sufxvd.cn/Article/details/gt2fvylwfev.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinqigufen.top/Article/details/gt2sfpyycyz.html

[R19] 数组长度
来源：http://dali.daria6918.cn/Article/details/gt2kaswniyl.html

echo "${#arr[@]}"
来源：http://dali.hongshengwenyu.top/Article/details/gt2veobwqsg.html

[R20] 关联数组（字典）
来源：http://dali.chenjidiqi.icu/Article/details/gt2akimcaim.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ehwqpu.com/Article/details/gt2jlgivfqc.html

[R21] 字符串长度
来源：http://dali.yj20258.top/Article/details/gt2osgsbhmi.html

echo "${#s}"
来源：http://dali.yueranfly.top/Article/details/gt2nuyerzhb.html

[R22] 截取子串
来源：http://dali.redwolf501.top/Article/details/gt2qvdjdrdp.html

echo "${s:0:5}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2joruziur.html

[R23] 字符串替换
来源：http://dali.smart0.xyz/Article/details/gt2wwryzrxl.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qolnaesu.html

[R24] 大小写转换
来源：http://dali.hywenlv.cn/Article/details/gt2kfvaokuc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.fzhhl.top/Article/details/gt2ztvnaedi.html

[R25] 去后缀 / 去前缀
来源：http://dali.hysaishi.cn/Article/details/gt2mugkuoml.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shzxlz.cn/Article/details/gt2vfkygndi.html

[R26] 命令替换
来源：http://dali.aizwys.cn/Article/details/gt2pzsamvzp.html

now=$(date +%F); echo "$now"
来源：http://dali.316326.xyz/Article/details/gt2ugsxsjez.html

[R27] 算术展开
来源：http://dali.mhx1999.top/Article/details/gt2jsuoqyiz.html

echo $((1 + 2 * 3))
来源：http://dali.xylfe.cn/Article/details/gt2oacnqtjr.html

[R28] 浮点运算
来源：http://dali.nwbrower.top/Article/details/gt2vwtwsrhd.html

echo "scale=2; 10/3" | bc
来源：http://dali.9152youxi.cn/Article/details/gt2vzvoiyil.html

[R29] 定义函数
来源：http://dali.cashguo.top/Article/details/gt2nrnqhoxu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhongyouzk.top/Article/details/gt2nlychwbd.html

[R30] 函数返回状态码
来源：http://dali.hywenlv.cn/Article/details/gt2tnagwmpu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.redwolf501.top/Article/details/gt2ymjwtfwt.html

[R31] 局部变量
来源：http://dali.zhiwuduotai.top/Article/details/gt2ddsyukmw.html

f() { local x=1; echo "$x"; }
来源：http://dali.xuanzx.com/Article/details/gt2psczjmob.html

[R32] 参数个数校验
来源：http://dali.yangfankeji.com/Article/details/gt2awrzmloa.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shuidangran.top/Article/details/gt2gttoszmn.html

[R33] 捕获错误并提示行号
来源：http://dali.hywenlv.cn/Article/details/gt2gyqsjgpw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shuidangran.top/Article/details/gt2kzcbjfik.html

[R34] 退出时清理
来源：http://dali.jqgufenzy.top/Article/details/gt2tuwfdshv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xylfe.cn/Article/details/gt2xpsiljir.html

[R35] 后台执行并等待
来源：http://dali.jqgfzy.top/Article/details/gt2hsphglnz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.aibaodan.cn/Article/details/gt2grfrpcvu.html

[R36] 并发执行多个任务
来源：http://dali.9152youxi.cn/Article/details/gt2wwxjjmnq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.sxryk.cn/Article/details/gt2gdxqzfov.html

[R37] 把输出赋给变量
来源：http://dali.jinqigufen.top/Article/details/gt2mehgpxhl.html

files=$(ls -1)
来源：http://dali.redwolf501.top/Article/details/gt2makuvttx.html

[R38] 管道串联
来源：http://dali.chenzaomai.com/Article/details/gt2svavacmw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shangyingyoupin.top/Article/details/gt2cmleieyt.html

[R39] 重定向标准输出与错误
来源：http://dali.daxiang520.top/Article/details/gt2slketwvj.html

cmd > out.log 2>&1
来源：http://dali.shuidangran.top/Article/details/gt2atyoluaj.html

[R40] 追加写日志
来源：http://dali.zdqjudy.top/Article/details/gt2gfvrjsqm.html

echo "log" >> out.log
来源：http://dali.ybcxt.top/Article/details/gt2uzgyyhcv.html

[R41] 丢弃输出
来源：http://dali.jiagoushi.top/Article/details/gt2ufrshhzy.html

cmd >/dev/null 2>&1
来源：http://dali.nwbrower.top/Article/details/gt2drwcqahs.html

[R42] 输入重定向
来源：http://dali.hfpthk.cn/Article/details/gt2djlwcvlv.html

wc -l < a.txt
来源：http://dali.jqgfzy.top/Article/details/gt2yvlvxmhw.html

[R43] 按名字查找文件
来源：http://dali.tianlin.xyz/Article/details/gt2fqahlumz.html

find . -name "*.log" -type f
来源：http://dali.jiagoushi.top/Article/details/gt2bnhdxauj.html

[R44] 按修改时间查找
来源：http://dali.hnxiangtu.top/Article/details/gt2ajgcveoo.html

find . -mtime -7 -type f
来源：http://dali.vqdsnc.cn/Article/details/gt2nvqagubd.html

[R45] 批量删除
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2azlqhozc.html

find . -name "*.tmp" -delete
来源：http://dali.ppjwa.cn/Article/details/gt2rhfoblxm.html

[R46] 递归替换文件内容
来源：http://dali.pycfn.com/Article/details/gt2lbawvmak.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yueranfly.top/Article/details/gt2vbhjhmbl.html

[R47] sed 单行替换
来源：http://dali.zhiwuduotai.top/Article/details/gt2imgfxjth.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zdqjudy.top/Article/details/gt2xaiklmuf.html

[R48] awk 取指定列
来源：http://dali.daria6918.cn/Article/details/gt2mgsmpqfh.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zrmrltqj.html

[R49] awk 带条件
来源：http://dali.ybcxt.top/Article/details/gt2opksorkn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gzhubu.top/Article/details/gt2dqygbmaw.html

[R50] awk 求和
来源：http://dali.nwbrower.top/Article/details/gt2zmqmzadc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.tanke756.top/Article/details/gt2kiiqjmdb.html

[R51] 排序去重取前几
来源：http://dali.hnqzz.top/Article/details/gt2ekhreajz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tbqrtgzc.html

[R52] 统计行数
来源：http://dali.yvedp.cn/Article/details/gt2pmgzybmz.html

wc -l a.txt
来源：http://dali.yanxiufei.cn/Article/details/gt2mtojfvxs.html

[R53] 查看文件头与实时尾
来源：http://dali.gaohongyu789.top/Article/details/gt2fdnpolut.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yj202588.top/Article/details/gt2ngcscpzu.html

[R54] 比较两个文件
来源：http://dali.wangdashe.top/Article/details/gt2ljglgqqm.html

diff a.txt b.txt
来源：http://dali.shuidangran.top/Article/details/gt2rxxgbgcf.html

[R55] 压缩与解压
来源：http://dali.cucudq.cn/Article/details/gt2phxobrqj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yanxiufei.cn/Article/details/gt2gwduemka.html

[R56] 远程拷贝
来源：http://dali.jyoumei.cn/Article/details/gt2rdzwqpvq.html

scp file user@host:/path/
来源：http://dali.jqgfzy.top/Article/details/gt2gllhqeus.html

[R57] 远程执行命令
来源：http://dali.0kj1m.cn/Article/details/gt2puksyilq.html

ssh user@host 'uptime'
来源：http://dali.yj20258888.top/Article/details/gt2wiodhxmv.html

[R58] 下载文件
来源：http://dali.yangfankeji.com/Article/details/gt2olndvnge.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.316326.xyz/Article/details/gt2ukhaqzfn.html

[R59] 发 POST JSON
来源：http://dali.kuanghao11.cn/Article/details/gt2gyeeetmj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.guowangkeji.top/Article/details/gt2arynfvzf.html

[R60] 只看 HTTP 状态码
来源：http://dali.nwbrower.top/Article/details/gt2mcvpfcdw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.pengpengdd.cyou/Article/details/gt2xkloefio.html

[R61] 磁盘占用
来源：http://dali.dashuyun.cn/Article/details/gt2rkbjdbur.html

df -h;  du -sh *
来源：http://dali.hnxiangtu.top/Article/details/gt2xctveurr.html

[R62] 找最占空间的文件
来源：http://dali.9152youxi.cn/Article/details/gt2zwkmrsfd.html

du -ah . | sort -rh | head -10
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bopxftba.html

[R63] 内存与进程
来源：http://dali.fzhhl.top/Article/details/gt2lqkhnykj.html

free -h;  ps aux | grep nginx
来源：http://dali.vqdsnc.cn/Article/details/gt2xmjmsegc.html

[R64] 结束进程
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2syecjrir.html

kill -9 $(pgrep -f app.py)
来源：http://dali.nanxuanxn.top/Article/details/gt2diwzkmfy.html

[R65] 查看端口占用
来源：http://dali.zhixingplan.top/Article/details/gt2bkrxfpct.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.pengpengdd.cyou/Article/details/gt2zpfjzyhy.html

[R66] 定时任务
来源：http://dali.ybcxt.top/Article/details/gt2zagswtss.html

crontab -e;  crontab -l
来源：http://dali.sysykeji.top/Article/details/gt2bozzucuq.html

[R67] 生成随机十六进制串
来源：http://dali.yuxming.cn/Article/details/gt2wwxkwozc.html

openssl rand -hex 16
来源：http://dali.chenjidiqi.icu/Article/details/gt2hmpzrwch.html

[R68] 计算文件校验值
来源：http://dali.aizwys.cn/Article/details/gt2ywwaivrg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yueranfly.top/Article/details/gt2oobfvmeo.html

[R69] 生成随机密码
来源：http://dali.svipenyu.cn/Article/details/gt2gpdhphjh.html

head -c 16 /dev/urandom | base64
来源：http://dali.dianchejie.cn/Article/details/gt2uovqwpta.html

[R70] 时间戳与互转
来源：http://dali.chenjidiqi.icu/Article/details/gt2eryywnqm.html

date +%s;  date -d @1700000000
来源：http://dali.hysaishi.cn/Article/details/gt2topmxend.html

[R71] 日期格式化
来源：http://dali.shangyingyoupin.top/Article/details/gt2lallcfxu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pzlnpgku.html

[R72] 等待端口就绪
来源：http://dali.ydzc1.top/Article/details/gt2jditoxbc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.fzhhl.top/Article/details/gt2qxfmlndc.html

[R73] 分割大日志
来源：http://dali.tian-w.cn/Article/details/gt2iuavjhew.html

split -l 1000 big.log part_
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ejihghgz.html

[R74] 批量重命名
来源：http://dali.9152youxi.cn/Article/details/gt2laagorpw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.chenjidiqi.icu/Article/details/gt2xcmysfez.html

[R75] 导出环境变量
来源：http://dali.gogol.net.cn/Article/details/gt2oarcvtwm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jqgufenzy.top/Article/details/gt2iwxetshw.html

[R76] 使用临时文件
来源：http://dali.jinqigfzy.top/Article/details/gt2cceigzwk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xziqi.cn/Article/details/gt2wisaccog.html

[R77] 读取用户输入
来源：http://dali.hnxiangtu.top/Article/details/gt2gtupgsko.html

read -rp "请输入: " ans
来源：http://dali.yj20258888.top/Article/details/gt2tlcqddhz.html

[R78] 交互式菜单
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2seugrbtk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2txthevci.html

[R79] 解析命令行选项
来源：http://dali.yangfankeji.com/Article/details/gt2pmroedct.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.redwolf501.top/Article/details/gt2dtvumtoh.html

[R80] 查看脚本执行耗时
来源：http://dali.iojbl.cn/Article/details/gt2jcultvvc.html

time ./run.sh
来源：http://dali.fengsongda.top/Article/details/gt2ulzkihmx.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2hqvpmbxa.html

S. C / C++ 专题
来源：http://dali.feifeiyinyue.top/Article/details/gt2xtqqkauk.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ejvlvhcy.html

[S01] C：Hello World
来源：http://dali.svipenyu.cn/Article/details/gt2axcqmyap.html

#include <stdio.h>
来源：http://dali.bjfxy.top/Article/details/gt2yicrticb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ydzc1.top/Article/details/gt2nmbwmxdc.html

[S02] C：变量与格式化输出
来源：http://dali.hammf.cn/Article/details/gt2tyfqlsvl.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpycebsw.html

[S03] C：读入整数
来源：http://dali.zhengqikj.top/Article/details/gt2irbyvbtg.html

int x; scanf("%d", &x);
来源：http://dali.tian-w.cn/Article/details/gt2bwmtgqvr.html

[S04] C：字符串复制
来源：http://dali.yueranfly.top/Article/details/gt2mpjmtvob.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gt2xswvdqst.html

[S05] C：字符串长度
来源：http://dali.0kj1m.cn/Article/details/gt2lkfmxwtb.html


<!-- 参考信息 -->