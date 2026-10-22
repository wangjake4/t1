代发 wailian999

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yonumen.top/Article/details/gt2fgqcwcqp.html

[Q20] IN 列表
来源：http://dali.zhongyouzk.top/Article/details/gt2tmxolqze.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.bjfxy.top/Article/details/gt2snqhrfeo.html

[Q21] 空值判断
来源：http://dali.cdnleiting.top/Article/details/gt2wjelqoyg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.bjfxy.top/Article/details/gt2lwdgnxin.html

[Q22] 排序
来源：http://dali.hywenlv.cn/Article/details/gt2dteruuom.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.aibaodan.cn/Article/details/gt2srepwesf.html

[Q23] 分页
来源：http://dali.bjfxy.top/Article/details/gt2wtgmnlte.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hammf.cn/Article/details/gt2binbsbdi.html

[Q24] 去重
来源：http://dali.pycfn.com/Article/details/gt2toutadvm.html

SELECT DISTINCT city FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2menjnzxu.html

[Q25] 只取前 N 条
来源：http://dali.smart0.xyz/Article/details/gt2oobmzrqj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.nwbrower.top/Article/details/gt2edzfxmry.html

[Q26] 计数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kolprkry.html

SELECT COUNT(*) FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2ueafjrxp.html

[Q27] 条件计数
来源：http://dali.yuanzhike.top/Article/details/gt2pvwbcqdj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2ujvtyfno.html

[Q28] 求和与平均
来源：http://dali.xinyue.icu/Article/details/gt2tewzmrmc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xinyue.icu/Article/details/gt2ffbgvexi.html

[Q29] 最大最小值
来源：http://dali.fengsongda.top/Article/details/gt2vnzihzyh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2yddnsoll.html

[Q30] 分组统计
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zhcyfbxo.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jqgufenzy.top/Article/details/gt2bdhuhyli.html

[Q31] 分组后过滤
来源：http://dali.shuidangran.top/Article/details/gt2izjemzku.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yongpay.top/Article/details/gt2apynmaqm.html

[Q32] 分组拼接字符串
来源：http://dali.wangdashe.top/Article/details/gt2mbbfyamv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hammf.cn/Article/details/gt2pkmkkoao.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hfpthk.cn/Article/details/gt2zafeqpuw.html

[Q33] 多列分组
来源：http://dali.gzhubu.top/Article/details/gt2mjxajvdk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.vqdsnc.cn/Article/details/gt2fzilioul.html

[Q34] 每组取第一条
来源：http://dali.wangdashe.top/Article/details/gt2jymafsjt.html

SELECT * FROM (
来源：http://dali.aizwys.cn/Article/details/gt2cicrpile.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.chenjidiqi.icu/Article/details/gt2tjfqcxdz.html

) t WHERE rn = 1;
来源：http://dali.zdqjudy.top/Article/details/gt2jmpsatgt.html

[Q35] 内连接
来源：http://dali.hnxiangtu.top/Article/details/gt2esbnsdto.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.redwolf501.top/Article/details/gt2shndywkc.html

[Q36] 左连接
来源：http://dali.zhongyouzk.top/Article/details/gt2yvqvsqxh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.tanke756.top/Article/details/gt2wlqtvkaw.html

[Q37] 右连接
来源：http://dali.gaohongyu789.top/Article/details/gt2figogkfw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hysaishi.cn/Article/details/gt2lexkgavv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cqqwz.cn/Article/details/gt2ryupxuwp.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.nwbrower.top/Article/details/gt2agkfwzcl.html

[Q39] 自连接（查上下级）
来源：http://dali.gogol.net.cn/Article/details/gt2zapudlab.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hfpthk.cn/Article/details/gt2hsyjbyws.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bxnjbnks.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.kuanghao11.cn/Article/details/gt2gfzxfqxj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.dianchejie.cn/Article/details/gt2wrdliytt.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2exbtkjlb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wvgjuuml.html

JOIN users u ON u.id = o.user_id
来源：http://dali.fengsongda.top/Article/details/gt2hdguodbb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.aibaodan.cn/Article/details/gt2qzxdebzp.html

[Q42] 连接条件附加过滤
来源：http://dali.gotoacloud.top/Article/details/gt2nkqbusyx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.dashuyun.cn/Article/details/gt2jsxvkhrj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.sweek.top/Article/details/gt2zoxpxyru.html

[Q43] 标量子查询
来源：http://dali.ppjwa.cn/Article/details/gt2gyfpiruz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kscfsema.html

[Q44] IN 子查询
来源：http://dali.hongshengwenyu.top/Article/details/gt2zlsbojui.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.mhx1999.top/Article/details/gt2bsjqnqtp.html

[Q45] EXISTS 判断存在
来源：http://dali.tianlin.xyz/Article/details/gt2baqfcdep.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuanzx.com/Article/details/gt2fxzjpzmm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.dashuyun.cn/Article/details/gt2jftnbwdd.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hywenlv.cn/Article/details/gt2uqzwsttp.html

[Q47] 与平均值比较
来源：http://dali.wangdashe.top/Article/details/gt2anafjbms.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.pycfn.com/Article/details/gt2slzpzcje.html

[Q48] CTE 公用表表达式
来源：http://dali.jyoumei.cn/Article/details/gt2bqgajlis.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jlsjyb.cn/Article/details/gt2wjexrdcu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.nwbrower.top/Article/details/gt2ojpfntrl.html

[Q49] 更新单行
来源：http://dali.shuidangran.top/Article/details/gt2hwkguprm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cheryme.top/Article/details/gt2wbtmlhjl.html

[Q50] 批量更新
来源：http://dali.gogol.net.cn/Article/details/gt2aonhvvsg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2klqcymlv.html

[Q51] 用子查询更新
来源：http://dali.xinyue.icu/Article/details/gt2zhtiejkv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.daxiang520.top/Article/details/gt2vtpwhqli.html

[Q52] 删除指定行
来源：http://dali.birdmap.top/Article/details/gt2bmxfuyea.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yangfankeji.com/Article/details/gt2ocmyivyf.html

[Q53] 按条件删除
来源：http://dali.dashuyun.cn/Article/details/gt2lnmroagp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xylfe.cn/Article/details/gt2lgcybbpi.html

[Q54] 清空表
来源：http://dali.jlsjyb.cn/Article/details/gt2bzxbhdju.html

TRUNCATE TABLE logs;
来源：http://dali.316326.xyz/Article/details/gt2uarwxxbs.html

[Q55] 排名（并列占位）
来源：http://dali.yuanzhike.top/Article/details/gt2ouphiixs.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jyoumei.cn/Article/details/gt2uvlagnpr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xziqi.cn/Article/details/gt2japlxvbj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.nwbrower.top/Article/details/gt2yndikysw.html

[Q57] 行号
来源：http://dali.fzhhl.top/Article/details/gt2erzrgnpb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2yndrqfsj.html

[Q58] 累计求和
来源：http://dali.hnqzz.top/Article/details/gt2usmlyqof.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.andypj.xyz/Article/details/gt2sicphzvh.html

[Q59] 分组内累计
来源：http://dali.tanke756.top/Article/details/gt2ggvswvda.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gt2lbkvzain.html

[Q60] 取上一行 / 下一行
来源：http://dali.cqqwz.cn/Article/details/gt2jsxqjjsz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhixingplan.top/Article/details/gt2bluhqkaw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yongpay.top/Article/details/gt2prkbtras.html

[Q61] 移动平均
来源：http://dali.guannengcc.top/Article/details/gt2riqdjgfn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gt2pgwlslfn.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbvnmrh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.guowangkeji.top/Article/details/gt2fupqtbut.html

[Q63] 开启事务
来源：http://dali.yanxiufei.cn/Article/details/gt2ahundjez.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.pycfn.com/Article/details/gt2ytpiughg.html

[Q64] 提交事务
来源：http://dali.meibo888.top/Article/details/gt2ypxhqpxt.html

COMMIT;
来源：http://dali.kuanghao11.cn/Article/details/gt2bnngdypt.html

[Q65] 回滚事务
来源：http://dali.nanxinkj.top/Article/details/gt2fpjqaehs.html

ROLLBACK;
来源：http://dali.dashuyun.cn/Article/details/gt2numkoxjh.html

[Q66] 行锁查询
来源：http://dali.daria6918.cn/Article/details/gt2jpmtxgut.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.andypj.xyz/Article/details/gt2izhdeiyk.html

[Q67] 设置隔离级别
来源：http://dali.yuxming.cn/Article/details/gt2bastgtuq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.quarkkingdee.top/Article/details/gt2xvrljvfg.html

[Q68] 保存点
来源：http://dali.zhoulong.xyz/Article/details/gt2lhgcvxxd.html

SAVEPOINT sp1;
来源：http://dali.0kj1m.cn/Article/details/gt2lopawdht.html

ROLLBACK TO sp1;
来源：http://dali.chenjidiqi.icu/Article/details/gt2qodhvpkv.html

[Q69] 查看执行计划
来源：http://dali.yj20258888.top/Article/details/gt2qaiwrcmx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.tian-w.cn/Article/details/gt2ipxxgxsl.html

[Q70] 更新统计信息
来源：http://dali.c1oappe.top/Article/details/gt2etjjgilf.html

ANALYZE TABLE users;
来源：http://dali.zycfv.cn/Article/details/gt2jlganohv.html

[Q71] 查看建表语句
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nfaezcwu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bmhpcsoi.html

[Q72] 查看索引
来源：http://dali.xziqi.cn/Article/details/gt2jriznsda.html

SHOW INDEX FROM users;
来源：http://dali.sweek.top/Article/details/gt2iyugdduc.html

[Q73] 查看表状态
来源：http://dali.gotoacloud.top/Article/details/gt2tdcobwnc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ppjwa.cn/Article/details/gt2peeevtmi.html

[Q74] 强制使用索引
来源：http://dali.sysykeji.top/Article/details/gt2ffdbzjqi.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.bjfxy.top/Article/details/gt2zvqfoobt.html

[Q75] 日期格式化
来源：http://dali.nanxinkj.top/Article/details/gt2vvjpiwfr.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gt2cmcljlmc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.quarkkingdee.top/Article/details/gt2hxatdqjt.html

[Q76] 按天统计
来源：http://dali.vqdsnc.cn/Article/details/gt2spxkpclg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hnqzz.top/Article/details/gt2tbkqwpnw.html

[Q77] 时间加减
来源：http://dali.cucudq.cn/Article/details/gt2eiirorth.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.kuanghao11.cn/Article/details/gt2jeacmjlz.html

[Q78] 当前时间
来源：http://dali.nanxinkj.top/Article/details/gt2cqvxzcfj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.gaohongyu789.top/Article/details/gt2qixytubc.html

[Q79] 字符串拼接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ykebudrv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jlsjyb.cn/Article/details/gt2qykkqony.html

[Q80] 字符串截取
来源：http://dali.shuidangran.top/Article/details/gt2zikjsvzo.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2ffscuera.html

[Q81] 字符串替换
来源：http://dali.hysaishi.cn/Article/details/gt2eaitjiyy.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2eesayvwc.html

[Q82] 字符长度与字节长度
来源：http://dali.jyoumei.cn/Article/details/gt2kvlnwqdi.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gt2xtqrspdh.html

[Q83] 大小写转换
来源：http://dali.quarkkingdee.top/Article/details/gt2umywnyqo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2deeandap.html

[Q84] 去除首尾空格
来源：http://dali.meibo888.top/Article/details/gt2xeaojdts.html

SELECT TRIM(name) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jqsywaow.html

[Q85] 数值取整
来源：http://dali.jinqigufen.top/Article/details/gt2fmcygxbg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.fengsongda.top/Article/details/gt2cfxdhqag.html

[Q86] 读取 JSON 字段
来源：http://dali.pengpengdd.cyou/Article/details/gt2ohjfluad.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yj20258888.top/Article/details/gt2znsonlyt.html

[Q87] JSON 字段做条件
来源：http://dali.sufxvd.cn/Article/details/gt2iqnpirfi.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eiwvfjpa.html

[Q88] 行转列（条件聚合）
来源：http://dali.shzxlz.cn/Article/details/gt2wqguulri.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.haohaochexian.top/Article/details/gt2ndmnitva.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2fxfjihnx.html

[Q89] 判断表是否存在
来源：http://dali.fengsongda.top/Article/details/gt2fsonofal.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.daxiang520.top/Article/details/gt2xyarxsan.html

[Q90] 生成序号列
来源：http://dali.dashuyun.cn/Article/details/gt2kanbbftl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jyoumei.cn/Article/details/gt2fweilfwb.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2vfgqxpnt.html

R. Bash 专题
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tsjyymek.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2ajealifr.html

[R01] shebang 与严格模式
来源：http://dali.sysykeji.top/Article/details/gt2sleluhmu.html

#!/usr/bin/env bash
来源：http://dali.yanxiufei.cn/Article/details/gt2ypywhsne.html

set -euo pipefail
来源：http://dali.vqdsnc.cn/Article/details/gt2bffhzgwk.html

[R02] 变量赋值与使用
来源：http://dali.yangfankeji.com/Article/details/gt2ldfsrvvm.html

name="Tom"; echo "$name"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2viegambj.html

[R03] 只读变量
来源：http://dali.sxryk.cn/Article/details/gt2nabgofpo.html

readonly PI=3.14
来源：http://dali.xinyue.icu/Article/details/gt2cpctlude.html

[R04] 位置参数
来源：http://dali.jinqigfzy.top/Article/details/gt2mwcxosyz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yvedp.cn/Article/details/gt2zfdbzmsl.html

[R05] 参数默认值
来源：http://dali.gotoacloud.top/Article/details/gt2gkxpfuvj.html

name="${1:-default}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zisrfjat.html

[R06] 判断命令是否存在
来源：http://dali.0kj1m.cn/Article/details/gt2dcdjlrxz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jlsjyb.cn/Article/details/gt2sytdcuwv.html

[R07] if 判断文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ypwndpip.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhoulong.xyz/Article/details/gt2gygmibru.html

[R08] 数值比较
来源：http://dali.ybcxt.top/Article/details/gt2ctyqnqgi.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hysaishi.cn/Article/details/gt2uyuqqflo.html

[R09] 字符串比较
来源：http://dali.cashguo.top/Article/details/gt2vyyctjuu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.nanxuanxn.top/Article/details/gt2awcphvwv.html

[R10] 正则匹配
来源：http://dali.yanxiufei.cn/Article/details/gt2bfptbyii.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hammf.cn/Article/details/gt2kgioifex.html

[R11] case 多分支
来源：http://dali.dashuyun.cn/Article/details/gt2fihnxofl.html

case "$1" in
来源：http://dali.jinqigfzy.top/Article/details/gt2rqsdyxgy.html

start) echo "启动" ;;
来源：http://dali.iojbl.cn/Article/details/gt2deurhqms.html

stop)  echo "停止" ;;
来源：http://dali.xuetiantiany.cn/Article/details/gt2dxmkkeyv.html

*)     echo "未知命令" ;;
来源：http://dali.yonumen.top/Article/details/gt2riapcrhs.html

esac
来源：http://dali.jqgfzy.top/Article/details/gt2icfficet.html

[R12] for 遍历文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ksvlckko.html

for f in *.txt; do echo "$f"; done
来源：http://dali.316326.xyz/Article/details/gt2crgpabdq.html

[R13] for 计数循环
来源：http://dali.xinyue.icu/Article/details/gt2yhgxqifv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.pengpengdd.cyou/Article/details/gt2zyrjdfpv.html

[R14] C 风格 for
来源：http://dali.jqgufenzy.top/Article/details/gt2dazcbjod.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.tanke756.top/Article/details/gt2wbhkltdk.html

[R15] while 逐行读文件
来源：http://dali.xylfe.cn/Article/details/gt2ajdpplsk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ybcxt.top/Article/details/gt2jgdaceah.html

[R16] until 等待条件
来源：http://dali.vqdsnc.cn/Article/details/gt2swmrhxlr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.guannengcc.top/Article/details/gt2nysxfjsh.html

[R17] 数组定义与取值
来源：http://dali.hammf.cn/Article/details/gt2tqplzxnr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2guzlpefb.html

[R18] 遍历数组
来源：http://dali.chenzaomai.com/Article/details/gt2esjbgfye.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hnxiangtu.top/Article/details/gt2afuynroi.html

[R19] 数组长度
来源：http://dali.jiagoushi.top/Article/details/gt2chjksbjy.html

echo "${#arr[@]}"
来源：http://dali.jianghu66.top/Article/details/gt2xgejnsvr.html

[R20] 关联数组（字典）
来源：http://dali.guowangkeji.top/Article/details/gt2xtxeffxo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shuidangran.top/Article/details/gt2ezlvolll.html

[R21] 字符串长度
来源：http://dali.wangshuangyany.cn/Article/details/gt2lgzeikkm.html

echo "${#s}"
来源：http://dali.guannengcc.top/Article/details/gt2rsencymp.html

[R22] 截取子串
来源：http://dali.aizwys.cn/Article/details/gt2elwrghty.html

echo "${s:0:5}"
来源：http://dali.sufxvd.cn/Article/details/gt2cqhoblrp.html

[R23] 字符串替换
来源：http://dali.birdmap.top/Article/details/gt2whacigcl.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yuxming.cn/Article/details/gt2fdwgcilu.html

[R24] 大小写转换
来源：http://dali.c1oappe.top/Article/details/gt2avzqzotm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.kuanghao11.cn/Article/details/gt2hasvkxmg.html

[R25] 去后缀 / 去前缀
来源：http://dali.ehwqpu.com/Article/details/gt2ttvohmnp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xylfe.cn/Article/details/gt2fifuwngv.html

[R26] 命令替换
来源：http://dali.hnqzz.top/Article/details/gt2jeodqgxo.html

now=$(date +%F); echo "$now"
来源：http://dali.guowangkeji.top/Article/details/gt2rhtjaslh.html

[R27] 算术展开
来源：http://dali.guowangkeji.top/Article/details/gt2inuaagmp.html

echo $((1 + 2 * 3))
来源：http://dali.yanxiufei.cn/Article/details/gt2kvezcsnb.html

[R28] 浮点运算
来源：http://dali.redwolf501.top/Article/details/gt2zhybuepm.html

echo "scale=2; 10/3" | bc
来源：http://dali.jqgfzy.top/Article/details/gt2ccwsofda.html

[R29] 定义函数
来源：http://dali.yongpay.top/Article/details/gt2fjuidfsn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.guowangkeji.top/Article/details/gt2bslmkntc.html

[R30] 函数返回状态码
来源：http://dali.bjfxy.top/Article/details/gt2xnuighny.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sysykeji.top/Article/details/gt2eumcwvrb.html

[R31] 局部变量
来源：http://dali.ybcxt.top/Article/details/gt2zztjgmoq.html

f() { local x=1; echo "$x"; }
来源：http://dali.smart0.xyz/Article/details/gt2jwzhsrka.html

[R32] 参数个数校验
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sjbejjuj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.dashuyun.cn/Article/details/gt2epzadppy.html

[R33] 捕获错误并提示行号
来源：http://dali.hnxiangtu.top/Article/details/gt2glsvlsar.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xuetiantiany.cn/Article/details/gt2gbthgbqq.html

[R34] 退出时清理
来源：http://dali.zhoulong.xyz/Article/details/gt2xgzjdscw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.meibo888.top/Article/details/gt2lffnikrl.html

[R35] 后台执行并等待
来源：http://dali.hongshengwenyu.top/Article/details/gt2qbcqgtmc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ivvv.top/Article/details/gt2qhbywggn.html

[R36] 并发执行多个任务
来源：http://dali.jinqigufen.top/Article/details/gt2zcufasrt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.nanxinkj.top/Article/details/gt2gfaeltys.html

[R37] 把输出赋给变量
来源：http://dali.xinyue.icu/Article/details/gt2dsmfspxd.html

files=$(ls -1)
来源：http://dali.yuxming.cn/Article/details/gt2hknsncrt.html

[R38] 管道串联
来源：http://dali.gogol.net.cn/Article/details/gt2rutpqjis.html

cat a.txt | grep -i error | wc -l
来源：http://dali.meibo888.top/Article/details/gt2scjqmbhg.html

[R39] 重定向标准输出与错误
来源：http://dali.smart0.xyz/Article/details/gt2giuoghrw.html

cmd > out.log 2>&1
来源：http://dali.yongpay.top/Article/details/gt2ioosyxsg.html

[R40] 追加写日志
来源：http://dali.shuidangran.top/Article/details/gt2cdxjinpw.html

echo "log" >> out.log
来源：http://dali.cheryme.top/Article/details/gt2nvbxrvjt.html

[R41] 丢弃输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tdqlgdby.html

cmd >/dev/null 2>&1
来源：http://dali.xziqi.cn/Article/details/gt2rfifoeqz.html

[R42] 输入重定向
来源：http://dali.havefunace.top/Article/details/gt2vcrcnwyb.html

wc -l < a.txt
来源：http://dali.quarkkingdee.top/Article/details/gt2czvpailf.html

[R43] 按名字查找文件
来源：http://dali.sysykeji.top/Article/details/gt2frymtoaz.html

find . -name "*.log" -type f
来源：http://dali.meibo888.top/Article/details/gt2hstxynsn.html

[R44] 按修改时间查找
来源：http://dali.hnxiangtu.top/Article/details/gt2uahnepiw.html

find . -mtime -7 -type f
来源：http://dali.hysaishi.cn/Article/details/gt2sorkivtp.html

[R45] 批量删除
来源：http://dali.haohaochexian.top/Article/details/gt2xhpkruyh.html

find . -name "*.tmp" -delete
来源：http://dali.yuxming.cn/Article/details/gt2knqhjbfy.html

[R46] 递归替换文件内容
来源：http://dali.iojbl.cn/Article/details/gt2uzaohvvb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hnqiulzu.html

[R47] sed 单行替换
来源：http://dali.chenjidiqi.icu/Article/details/gt2zibzmetl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ydzc1.top/Article/details/gt2cqrssoqv.html

[R48] awk 取指定列
来源：http://dali.nwbrower.top/Article/details/gt2opgsmqhy.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhoulong.xyz/Article/details/gt2vopgkxod.html

[R49] awk 带条件
来源：http://dali.sxryk.cn/Article/details/gt2jdrssrre.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.iojbl.cn/Article/details/gt2krjiijrb.html

[R50] awk 求和
来源：http://dali.feifeiyinyue.top/Article/details/gt2voxsbmni.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.guowangkeji.top/Article/details/gt2cbsdjxuf.html

[R51] 排序去重取前几
来源：http://dali.xziqi.cn/Article/details/gt2gcwkahkg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gotoacloud.top/Article/details/gt2qysjeuov.html

[R52] 统计行数
来源：http://dali.aibaodan.cn/Article/details/gt2xpuspqhg.html

wc -l a.txt
来源：http://dali.jianghu66.top/Article/details/gt2iepwebqo.html

[R53] 查看文件头与实时尾
来源：http://dali.daxiang520.top/Article/details/gt2khjirdbz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.sxryk.cn/Article/details/gt2tliwsgtl.html

[R54] 比较两个文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2owccvtin.html

diff a.txt b.txt
来源：http://dali.gzhubu.top/Article/details/gt2qewgzdmg.html

[R55] 压缩与解压
来源：http://dali.sufxvd.cn/Article/details/gt2dsqznbej.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cheryme.top/Article/details/gt2rlcinzft.html

[R56] 远程拷贝
来源：http://dali.zhengqikj.top/Article/details/gt2palokofy.html

scp file user@host:/path/
来源：http://dali.ppjwa.cn/Article/details/gt2cnsbzjzp.html

[R57] 远程执行命令
来源：http://dali.yangfankeji.com/Article/details/gt2mbbjodlp.html

ssh user@host 'uptime'
来源：http://dali.tanke756.top/Article/details/gt2ymojwzxc.html

[R58] 下载文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2boaqwmlo.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.quarkkingdee.top/Article/details/gt2rcdkmsda.html

[R59] 发 POST JSON
来源：http://dali.ivvv.top/Article/details/gt2ngvcslwq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.snrcjt.cn/Article/details/gt2bbubmbsr.html

[R60] 只看 HTTP 状态码
来源：http://dali.nanxuanxn.top/Article/details/gt2dwrbdtca.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jinqigfzy.top/Article/details/gt2kbqeskrq.html

[R61] 磁盘占用
来源：http://dali.mhx1999.top/Article/details/gt2dmklknib.html

df -h;  du -sh *
来源：http://dali.nanxuanxn.top/Article/details/gt2zitrasgj.html

[R62] 找最占空间的文件
来源：http://dali.sysykeji.top/Article/details/gt2vyqjjusj.html

du -ah . | sort -rh | head -10
来源：http://dali.nanxuanxn.top/Article/details/gt2lphyrosu.html

[R63] 内存与进程
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fhsvlupc.html

free -h;  ps aux | grep nginx
来源：http://dali.xuetiantiany.cn/Article/details/gt2bjrlcvlu.html

[R64] 结束进程
来源：http://dali.ydzc1.top/Article/details/gt2cglpdadn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.mhx1999.top/Article/details/gt2lwhytkow.html

[R65] 查看端口占用
来源：http://dali.jinqigufen.top/Article/details/gt2krfpntos.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.chenjidiqi.icu/Article/details/gt2utyrsilk.html

[R66] 定时任务
来源：http://dali.yuxming.cn/Article/details/gt2ixehnjyy.html

crontab -e;  crontab -l
来源：http://dali.jiagoushi.top/Article/details/gt2zkydifsj.html

[R67] 生成随机十六进制串
来源：http://dali.redwolf501.top/Article/details/gt2zgifgnid.html

openssl rand -hex 16
来源：http://dali.ybcxt.top/Article/details/gt2claluwss.html

[R68] 计算文件校验值
来源：http://dali.sxryk.cn/Article/details/gt2mxowtpoq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zycfv.cn/Article/details/gt2yrumhxww.html

[R69] 生成随机密码
来源：http://dali.xinyue.icu/Article/details/gt2wstcmoms.html


<!-- 参考信息 -->