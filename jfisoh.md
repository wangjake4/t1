代发 wailian999

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtjqwzdaej.html

[Q28] 求和与平均
来源：http://dali.cucudq.cn/Article/details/gtmzktorvj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.daria6918.cn/Article/details/gtlglbxzkd.html

[Q29] 最大最小值
来源：http://dali.hfpthk.cn/Article/details/gtfntwvaji.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtudnvomni.html

[Q30] 分组统计
来源：http://dali.hysaishi.cn/Article/details/gtslivsoan.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.gotoacloud.top/Article/details/gtqmtxgjlr.html

[Q31] 分组后过滤
来源：http://dali.wangshuangyany.cn/Article/details/gtwgjuchkj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cucudq.cn/Article/details/gtmdolesvz.html

[Q32] 分组拼接字符串
来源：http://dali.redwolf501.top/Article/details/gtpmucoyhp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yanxiufei.cn/Article/details/gtkyexfneu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.tianlin.xyz/Article/details/gtqjgbenis.html

[Q33] 多列分组
来源：http://dali.zhongyouzk.top/Article/details/gtcdmnuzdq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.iojbl.cn/Article/details/gtqjvcwusj.html

[Q34] 每组取第一条
来源：http://dali.zycfv.cn/Article/details/gttfgsnnvt.html

SELECT * FROM (
来源：http://dali.guowangkeji.top/Article/details/gtrlmbrazt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yangfankeji.com/Article/details/gtbrkqjihf.html

) t WHERE rn = 1;
来源：http://dali.hywenlv.cn/Article/details/gtpwohwsgl.html

[Q35] 内连接
来源：http://dali.xinyue.icu/Article/details/gtfetcjowq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxuanxn.top/Article/details/gtqrpmjipp.html

[Q36] 左连接
来源：http://dali.shangyingyoupin.top/Article/details/gtayuhioka.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zdqjudy.top/Article/details/gtduesdweu.html

[Q37] 右连接
来源：http://dali.chenzaomai.com/Article/details/gtlkpnppmc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjyhmzflx.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.svipenyu.cn/Article/details/gtbzwznzby.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.dianchejie.cn/Article/details/gtjoioebpd.html

[Q39] 自连接（查上下级）
来源：http://dali.cdnleiting.top/Article/details/gtqgbknamu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.quarkkingdee.top/Article/details/gtionhoobc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.fzhhl.top/Article/details/gtkgnrjocj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.wangdashe.top/Article/details/gtuyobvzja.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.9152youxi.cn/Article/details/gtlgcnaimg.html

[Q41] 多表连接
来源：http://dali.ivvv.top/Article/details/gttvpotpww.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.daria6918.cn/Article/details/gteipyhkwq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cheryme.top/Article/details/gtfojkjzea.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shzxlz.cn/Article/details/gtkgvywuzs.html

[Q42] 连接条件附加过滤
来源：http://dali.shzxlz.cn/Article/details/gtvrkxwmmc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.aizwys.cn/Article/details/gtjqqnrumo.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shzxlz.cn/Article/details/gtqvpxchlo.html

[Q43] 标量子查询
来源：http://dali.jinqigufen.top/Article/details/gtjozfnggg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shangyingyoupin.top/Article/details/gtvmoldsuj.html

[Q44] IN 子查询
来源：http://dali.jiagoushi.top/Article/details/gtkpkwwcse.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.mhx1999.top/Article/details/gtreulwjip.html

[Q45] EXISTS 判断存在
来源：http://dali.9152youxi.cn/Article/details/gthbrtteuv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yongpay.top/Article/details/gtifexcsew.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yangfankeji.com/Article/details/gtfqsncgux.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.aibaodan.cn/Article/details/gtfdsqyyku.html

[Q47] 与平均值比较
来源：http://dali.hammf.cn/Article/details/gtosdkhxbz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.feifeiyinyue.top/Article/details/gtoglohxkc.html

[Q48] CTE 公用表表达式
来源：http://dali.ydzc1.top/Article/details/gtjbrgjsni.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xinyue.icu/Article/details/gtnbtzwdti.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hfpthk.cn/Article/details/gtoshewkfp.html

[Q49] 更新单行
来源：http://dali.aizwys.cn/Article/details/gtdjxzphbi.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.sxryk.cn/Article/details/gtyubndesp.html

[Q50] 批量更新
来源：http://dali.kuanghao11.cn/Article/details/gtvratdpqo.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtplydlzaf.html

[Q51] 用子查询更新
来源：http://dali.ybcxt.top/Article/details/gtogxdbhjz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gogol.net.cn/Article/details/gtdfaubaao.html

[Q52] 删除指定行
来源：http://dali.yanxiufei.cn/Article/details/gtapsntiwx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gtdiriqphc.html

[Q53] 按条件删除
来源：http://dali.xuetiantiany.cn/Article/details/gtidensqnh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.cheryme.top/Article/details/gtahhkruyd.html

[Q54] 清空表
来源：http://dali.zhengqikj.top/Article/details/gtohdqfdda.html

TRUNCATE TABLE logs;
来源：http://dali.yangfankeji.com/Article/details/gtefulbiqy.html

[Q55] 排名（并列占位）
来源：http://dali.jqgufenzy.top/Article/details/gtosddadjr.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ivvv.top/Article/details/gtpkwqncpz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hnqzz.top/Article/details/gtmlpchbhg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ivvv.top/Article/details/gthvtdecyc.html

[Q57] 行号
来源：http://dali.c1oappe.top/Article/details/gtmaytzuvg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yj20258888.top/Article/details/gtjgqfkdez.html

[Q58] 累计求和
来源：http://dali.haohaochexian.top/Article/details/gtqdnhvhnb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtvdjtiuiw.html

[Q59] 分组内累计
来源：http://dali.yuxming.cn/Article/details/gtwrtnlzet.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtjxbgvxtb.html

[Q60] 取上一行 / 下一行
来源：http://dali.gogol.net.cn/Article/details/gtgneqrene.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.guowangkeji.top/Article/details/gtnphmnunb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfshelhfd.html

[Q61] 移动平均
来源：http://dali.wangshuangyany.cn/Article/details/gtdrverycj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtlewscugy.html

[Q62] 分组占比
来源：http://dali.hongshengwenyu.top/Article/details/gtmaczvswe.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xuetiantiany.cn/Article/details/gtwnsdpepy.html

[Q63] 开启事务
来源：http://dali.yanxiufei.cn/Article/details/gtxopqwhxl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zdqjudy.top/Article/details/gtkmcnwibq.html

[Q64] 提交事务
来源：http://dali.mhx1999.top/Article/details/gtwykbjnmz.html

COMMIT;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwfuybtux.html

[Q65] 回滚事务
来源：http://dali.gogol.net.cn/Article/details/gtuyogxroy.html

ROLLBACK;
来源：http://dali.mhx1999.top/Article/details/gttlqernlw.html

[Q66] 行锁查询
来源：http://dali.jinqigufen.top/Article/details/gtwuztupwv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.pycfn.com/Article/details/gtkhnfcubz.html

[Q67] 设置隔离级别
来源：http://dali.mhx1999.top/Article/details/gtqumpvfwi.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdhrbajtr.html

[Q68] 保存点
来源：http://dali.chenzaomai.com/Article/details/gtbexzgdct.html

SAVEPOINT sp1;
来源：http://dali.zhiwuduotai.top/Article/details/gtcvjzewrl.html

ROLLBACK TO sp1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtavoyykpn.html

[Q69] 查看执行计划
来源：http://dali.hammf.cn/Article/details/gthnmlqzap.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.nanxuanxn.top/Article/details/gtfgjdipol.html

[Q70] 更新统计信息
来源：http://dali.sysykeji.top/Article/details/gtsmltetah.html

ANALYZE TABLE users;
来源：http://dali.jinqigufen.top/Article/details/gtspslffcp.html

[Q71] 查看建表语句
来源：http://dali.fengsongda.top/Article/details/gtabrfwcej.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.bjfxy.top/Article/details/gtoutivuyo.html

[Q72] 查看索引
来源：http://dali.jinqigfzy.top/Article/details/gtkysxoflw.html

SHOW INDEX FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtgxtmsdih.html

[Q73] 查看表状态
来源：http://dali.meibo888.top/Article/details/gtigzekbtw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zdqjudy.top/Article/details/gtswtixjiu.html

[Q74] 强制使用索引
来源：http://dali.gotoacloud.top/Article/details/gtaqicdgmr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yuxming.cn/Article/details/gtvutnelsb.html

[Q75] 日期格式化
来源：http://dali.nwbrower.top/Article/details/gtvhwldcrw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gtibwnbqgz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yongpay.top/Article/details/gtuballowp.html

[Q76] 按天统计
来源：http://dali.zhiwuduotai.top/Article/details/gtjxmcgklp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yj202588.top/Article/details/gthkvdzfoj.html

[Q77] 时间加减
来源：http://dali.yj20258888.top/Article/details/gtwpsirjvx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.smart0.xyz/Article/details/gtnnjyefvf.html

[Q78] 当前时间
来源：http://dali.shangyingyoupin.top/Article/details/gtmfztjtdp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jlsjyb.cn/Article/details/gtngyvudkw.html

[Q79] 字符串拼接
来源：http://dali.cashguo.top/Article/details/gtsereevsf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.havefunace.top/Article/details/gtiltjmqzc.html

[Q80] 字符串截取
来源：http://dali.daxiang520.top/Article/details/gtxoqtwzhl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtojmuhiwq.html

[Q81] 字符串替换
来源：http://dali.yongpay.top/Article/details/gtrllpwgml.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jianghu66.top/Article/details/gtnosojikm.html

[Q82] 字符长度与字节长度
来源：http://dali.316326.xyz/Article/details/gtjdpnejjl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtawugghqk.html

[Q83] 大小写转换
来源：http://dali.fengsongda.top/Article/details/gtumvwmcif.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ydzc1.top/Article/details/gttnnxbkvq.html

[Q84] 去除首尾空格
来源：http://dali.jqgufenzy.top/Article/details/gtesccfxue.html

SELECT TRIM(name) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtltwtbziv.html

[Q85] 数值取整
来源：http://dali.hnxiangtu.top/Article/details/gtpoafgwuh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.daxiang520.top/Article/details/gtrmdqhxoo.html

[Q86] 读取 JSON 字段
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzduwfckl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.0kj1m.cn/Article/details/gtlwzuwkoj.html

[Q87] JSON 字段做条件
来源：http://dali.jqgufenzy.top/Article/details/gtyfnyktrk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.tanke756.top/Article/details/gtpwvvptdf.html

[Q88] 行转列（条件聚合）
来源：http://dali.nanxinkj.top/Article/details/gtudohrlcf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hongshengwenyu.top/Article/details/gtwetpvtgz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ydzc1.top/Article/details/gtitdkihna.html

[Q89] 判断表是否存在
来源：http://dali.haohaochexian.top/Article/details/gtfzwzjfah.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cqqwz.cn/Article/details/gtxakmyhxp.html

[Q90] 生成序号列
来源：http://dali.yonumen.top/Article/details/gtcpsqujka.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.pengpengdd.cyou/Article/details/gtaxqtwvne.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtcxgclvby.html

R. Bash 专题
来源：http://dali.smart0.xyz/Article/details/gtqqsidhmc.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtxybwkork.html

[R01] shebang 与严格模式
来源：http://dali.fengsongda.top/Article/details/gtuzrzbgne.html

#!/usr/bin/env bash
来源：http://dali.kuanghao11.cn/Article/details/gtjmrpbxaa.html

set -euo pipefail
来源：http://dali.zhiwuduotai.top/Article/details/gtyqrodsmh.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gtigkeahgm.html

name="Tom"; echo "$name"
来源：http://dali.ivvv.top/Article/details/gtxknwjqrh.html

[R03] 只读变量
来源：http://dali.xinyue.icu/Article/details/gtgntgukvy.html

readonly PI=3.14
来源：http://dali.jinqigufen.top/Article/details/gtborxvenn.html

[R04] 位置参数
来源：http://dali.wangshuangyany.cn/Article/details/gtmzxfmiva.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.c1oappe.top/Article/details/gtfstbpvls.html

[R05] 参数默认值
来源：http://dali.jiagoushi.top/Article/details/gttiuphkgr.html

name="${1:-default}"
来源：http://dali.cqqwz.cn/Article/details/gtjiqxheco.html

[R06] 判断命令是否存在
来源：http://dali.yj202588.top/Article/details/gtfpndabrm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.kuanghao11.cn/Article/details/gtvuzyrufo.html

[R07] if 判断文件
来源：http://dali.cucudq.cn/Article/details/gtzfvhduux.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.kuanghao11.cn/Article/details/gtzfjlvicq.html

[R08] 数值比较
来源：http://dali.xinyue.icu/Article/details/gtwjahrjef.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.mhx1999.top/Article/details/gtlwqhbwym.html

[R09] 字符串比较
来源：http://dali.chenzaomai.com/Article/details/gtvkvjxbsn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cashguo.top/Article/details/gtknjrwuns.html

[R10] 正则匹配
来源：http://dali.c1oappe.top/Article/details/gtotaapvbn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcqictogs.html

[R11] case 多分支
来源：http://dali.aizwys.cn/Article/details/gtpvdcjitn.html

case "$1" in
来源：http://dali.jlsjyb.cn/Article/details/gtnzwwcvwe.html

start) echo "启动" ;;
来源：http://dali.daria6918.cn/Article/details/gtetlcsnvv.html

stop)  echo "停止" ;;
来源：http://dali.zhengqikj.top/Article/details/gtzluyyxdr.html

*)     echo "未知命令" ;;
来源：http://dali.ppjwa.cn/Article/details/gtbpipumad.html

esac
来源：http://dali.yangfankeji.com/Article/details/gtwyqrnqqr.html

[R12] for 遍历文件
来源：http://dali.vqdsnc.cn/Article/details/gtwkigsdmq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.tianlin.xyz/Article/details/gtixpotajs.html

[R13] for 计数循环
来源：http://dali.cdnleiting.top/Article/details/gthujcawab.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.nanxinkj.top/Article/details/gtjprshhgr.html

[R14] C 风格 for
来源：http://dali.tian-w.cn/Article/details/gtalefytbx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinqigufen.top/Article/details/gtoipbnzub.html

[R15] while 逐行读文件
来源：http://dali.yvedp.cn/Article/details/gtqykhiwsq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shzxlz.cn/Article/details/gtqzkgwdbd.html

[R16] until 等待条件
来源：http://dali.aibaodan.cn/Article/details/gtbhtcukyp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.tian-w.cn/Article/details/gtdpubpxib.html

[R17] 数组定义与取值
来源：http://dali.cashguo.top/Article/details/gtdigwpqkd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xuanzx.com/Article/details/gtbdcpicph.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gtbsqnysbx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sweek.top/Article/details/gtfxxvlcdw.html

[R19] 数组长度
来源：http://dali.xinyue.icu/Article/details/gtlwxvpiyd.html

echo "${#arr[@]}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgvdxiywu.html

[R20] 关联数组（字典）
来源：http://dali.ppjwa.cn/Article/details/gthribagxs.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.chenlongwang.top/Article/details/gtmvitlueb.html

[R21] 字符串长度
来源：http://dali.andypj.xyz/Article/details/gtsfucsjci.html

echo "${#s}"
来源：http://dali.yj20258.top/Article/details/gtntgvlxpt.html

[R22] 截取子串
来源：http://dali.jqgufenzy.top/Article/details/gtqpgpryzd.html

echo "${s:0:5}"
来源：http://dali.sufxvd.cn/Article/details/gtcylduisq.html

[R23] 字符串替换
来源：http://dali.hammf.cn/Article/details/gtpcvvhyyd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ivvv.top/Article/details/gturdvxpzj.html

[R24] 大小写转换
来源：http://dali.0kj1m.cn/Article/details/gtnofbikya.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jiagoushi.top/Article/details/gtgiopoffz.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhixingplan.top/Article/details/gtgevosrmo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hywenlv.cn/Article/details/gtmirfntvd.html

[R26] 命令替换
来源：http://dali.jlsjyb.cn/Article/details/gtlsomxqxd.html

now=$(date +%F); echo "$now"
来源：http://dali.andypj.xyz/Article/details/gtvylxxdvz.html

[R27] 算术展开
来源：http://dali.zhoulong.xyz/Article/details/gtiyjbsngy.html

echo $((1 + 2 * 3))
来源：http://dali.zhiwuduotai.top/Article/details/gtsrhvqpuu.html

[R28] 浮点运算
来源：http://dali.ybcxt.top/Article/details/gtxhlcqwxq.html

echo "scale=2; 10/3" | bc
来源：http://dali.gaohongyu789.top/Article/details/gtenkzpfgp.html

[R29] 定义函数
来源：http://dali.fengsongda.top/Article/details/gtvphnratu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.fzhhl.top/Article/details/gtiljdvegk.html

[R30] 函数返回状态码
来源：http://dali.chenlongwang.top/Article/details/gtackqmfjo.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shzxlz.cn/Article/details/gtwuttzjof.html

[R31] 局部变量
来源：http://dali.hammf.cn/Article/details/gtxgicfeao.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhixingplan.top/Article/details/gtdhrltqsm.html

[R32] 参数个数校验
来源：http://dali.gaohongyu789.top/Article/details/gtfwrfpkio.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cqqwz.cn/Article/details/gtpijcyaaz.html

[R33] 捕获错误并提示行号
来源：http://dali.tian-w.cn/Article/details/gtptcoxsxr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhixingplan.top/Article/details/gtrnltawqw.html

[R34] 退出时清理
来源：http://dali.xylfe.cn/Article/details/gtyqnqunik.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.gotoacloud.top/Article/details/gtwryalgvk.html

[R35] 后台执行并等待
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfqhwsztv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yuxming.cn/Article/details/gthtcslmpi.html

[R36] 并发执行多个任务
来源：http://dali.sysykeji.top/Article/details/gtbiycdgey.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.meibo888.top/Article/details/gtgysvmolg.html

[R37] 把输出赋给变量
来源：http://dali.dashuyun.cn/Article/details/gtyzaxuwxw.html

files=$(ls -1)
来源：http://dali.hongshengwenyu.top/Article/details/gthkvzqdpd.html

[R38] 管道串联
来源：http://dali.yangfankeji.com/Article/details/gttloobbfa.html

cat a.txt | grep -i error | wc -l
来源：http://dali.chenlongwang.top/Article/details/gtydhwdpsv.html

[R39] 重定向标准输出与错误
来源：http://dali.cashguo.top/Article/details/gtxiogdtch.html

cmd > out.log 2>&1
来源：http://dali.yj20258888.top/Article/details/gtemczxkhg.html

[R40] 追加写日志
来源：http://dali.ydzc1.top/Article/details/gttbqywtek.html

echo "log" >> out.log
来源：http://dali.daria6918.cn/Article/details/gtjfmwoahf.html

[R41] 丢弃输出
来源：http://dali.svipenyu.cn/Article/details/gtmjusdaqd.html

cmd >/dev/null 2>&1
来源：http://dali.quarkkingdee.top/Article/details/gtcyvpvjvu.html

[R42] 输入重定向
来源：http://dali.xylfe.cn/Article/details/gtiaizhqmi.html

wc -l < a.txt
来源：http://dali.shzxlz.cn/Article/details/gtthcjvbye.html

[R43] 按名字查找文件
来源：http://dali.aizwys.cn/Article/details/gtiiqljicm.html

find . -name "*.log" -type f
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnzjsrkqq.html

[R44] 按修改时间查找
来源：http://dali.shangyingyoupin.top/Article/details/gtxslflspt.html

find . -mtime -7 -type f
来源：http://dali.quarkkingdee.top/Article/details/gtcxtmcqho.html

[R45] 批量删除
来源：http://dali.jinyuanbaomall.cn/Article/details/gtudgkwknu.html

find . -name "*.tmp" -delete
来源：http://dali.xuanzx.com/Article/details/gtkikosodk.html

[R46] 递归替换文件内容
来源：http://dali.yj20258888.top/Article/details/gtefgokolz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xziqi.cn/Article/details/gtbzafdpbt.html

[R47] sed 单行替换
来源：http://dali.cheryme.top/Article/details/gtyuyglkmt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cashguo.top/Article/details/gtikbfcmtl.html

[R48] awk 取指定列
来源：http://dali.hongshengwenyu.top/Article/details/gtqpbohwfi.html

awk '{print $1, $3}' a.txt
来源：http://dali.havefunace.top/Article/details/gtylgyqsth.html

[R49] awk 带条件
来源：http://dali.shzxlz.cn/Article/details/gtahisuzmq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.aizwys.cn/Article/details/gtrdpuwhmh.html

[R50] awk 求和
来源：http://dali.yj20258.top/Article/details/gtsellzzvo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jianghu66.top/Article/details/gtjjtnogxl.html

[R51] 排序去重取前几
来源：http://dali.quarkkingdee.top/Article/details/gtfwalcuzb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.aibaodan.cn/Article/details/gtegecfcqu.html

[R52] 统计行数
来源：http://dali.gaohongyu789.top/Article/details/gtgcamdknq.html

wc -l a.txt
来源：http://dali.zhongyouzk.top/Article/details/gtiefkolfo.html

[R53] 查看文件头与实时尾
来源：http://dali.cqqwz.cn/Article/details/gtwzyjnwxj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.quarkkingdee.top/Article/details/gtovnmtuqb.html

[R54] 比较两个文件
来源：http://dali.gogol.net.cn/Article/details/gthowqjfrr.html

diff a.txt b.txt
来源：http://dali.hysaishi.cn/Article/details/gtuwgxxfyv.html

[R55] 压缩与解压
来源：http://dali.xziqi.cn/Article/details/gttlpxxlji.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.havefunace.top/Article/details/gtqlvuxdem.html

[R56] 远程拷贝
来源：http://dali.shangyingyoupin.top/Article/details/gtnuymqjuw.html

scp file user@host:/path/
来源：http://dali.jqgfzy.top/Article/details/gtstotlnqt.html

[R57] 远程执行命令
来源：http://dali.gzhubu.top/Article/details/gtmmcufdve.html

ssh user@host 'uptime'
来源：http://dali.aibaodan.cn/Article/details/gtvtpwkdjs.html

[R58] 下载文件
来源：http://dali.andypj.xyz/Article/details/gtsedophtd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cheryme.top/Article/details/gtrpewpsks.html

[R59] 发 POST JSON
来源：http://dali.andypj.xyz/Article/details/gtbiaxzsjr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yonumen.top/Article/details/gtapizsjrq.html

[R60] 只看 HTTP 状态码
来源：http://dali.yongpay.top/Article/details/gteznhumxp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.havefunace.top/Article/details/gtgfkhnekf.html

[R61] 磁盘占用
来源：http://dali.sufxvd.cn/Article/details/gtapflmjut.html

df -h;  du -sh *
来源：http://dali.chenlongwang.top/Article/details/gtxekzjpdu.html

[R62] 找最占空间的文件
来源：http://dali.jqgfzy.top/Article/details/gtpdkkcbrx.html

du -ah . | sort -rh | head -10
来源：http://dali.daria6918.cn/Article/details/gtbjjrvebn.html

[R63] 内存与进程
来源：http://dali.yuanzhike.top/Article/details/gtelmuoule.html

free -h;  ps aux | grep nginx
来源：http://dali.jyoumei.cn/Article/details/gtyvrpgklj.html

[R64] 结束进程
来源：http://dali.xziqi.cn/Article/details/gtmwfnedpl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhongyouzk.top/Article/details/gtgfdltuup.html

[R65] 查看端口占用
来源：http://dali.yongpay.top/Article/details/gtuvnjcqta.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jinghuilouyu.cn/Article/details/gtrecbqqhb.html

[R66] 定时任务
来源：http://dali.yvedp.cn/Article/details/gtlmjlldjm.html

crontab -e;  crontab -l
来源：http://dali.aizwys.cn/Article/details/gthmtgxfsl.html

[R67] 生成随机十六进制串
来源：http://dali.tanke756.top/Article/details/gtkrripqrs.html

openssl rand -hex 16
来源：http://dali.bjfxy.top/Article/details/gtjvkkqeiw.html

[R68] 计算文件校验值
来源：http://dali.yj20258.top/Article/details/gtdwthqmul.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hysaishi.cn/Article/details/gttqdhhbsf.html

[R69] 生成随机密码
来源：http://dali.yuanzhike.top/Article/details/gtptdkglmq.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinghuilouyu.cn/Article/details/gtnliueleh.html

[R70] 时间戳与互转
来源：http://dali.yj20258.top/Article/details/gtwtebsbdk.html

date +%s;  date -d @1700000000
来源：http://dali.xuanzx.com/Article/details/gtnioukkge.html

[R71] 日期格式化
来源：http://dali.yj20258888.top/Article/details/gtboolkpfq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yuxming.cn/Article/details/gtuyjpxrxz.html

[R72] 等待端口就绪
来源：http://dali.redwolf501.top/Article/details/gtmvioixgq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cashguo.top/Article/details/gtkjrkwiqm.html

[R73] 分割大日志
来源：http://dali.zhaomingkeji.xyz/Article/details/gttnydrpeq.html

split -l 1000 big.log part_
来源：http://dali.mhx1999.top/Article/details/gtzvijzzrt.html

[R74] 批量重命名
来源：http://dali.yvedp.cn/Article/details/gtgjjgpokg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jiagoushi.top/Article/details/gtiijujbtx.html

[R75] 导出环境变量
来源：http://dali.zhiwuduotai.top/Article/details/gtdmhjvorf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.dianchejie.cn/Article/details/gtbizwdnsn.html

[R76] 使用临时文件
来源：http://dali.jianghu66.top/Article/details/gtcyycngij.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yueranfly.top/Article/details/gttrcycgcy.html

[R77] 读取用户输入
来源：http://dali.yuanzhike.top/Article/details/gtykyvbrms.html


<!-- 参考信息 -->