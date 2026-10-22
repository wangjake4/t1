代发 wailian999

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ppjwa.cn/Article/details/gt2lbnnbjkm.html

[Q20] IN 列表
来源：http://dali.zhengqikj.top/Article/details/gt2vwtrlnbb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.bjfxy.top/Article/details/gt2pkdnwpaf.html

[Q21] 空值判断
来源：http://dali.gotoacloud.top/Article/details/gt2jwjclrwm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yvedp.cn/Article/details/gt2lxgoxmls.html

[Q22] 排序
来源：http://dali.jinqigufen.top/Article/details/gt2fdbetoyx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.sufxvd.cn/Article/details/gt2ydndfpqw.html

[Q23] 分页
来源：http://dali.xziqi.cn/Article/details/gt2mdsofnki.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jlsjyb.cn/Article/details/gt2ncptbppx.html

[Q24] 去重
来源：http://dali.zycfv.cn/Article/details/gt2wilfccoa.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ujzpqasm.html

[Q25] 只取前 N 条
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ecoeanmp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.redwolf501.top/Article/details/gt2indhcqfm.html

[Q26] 计数
来源：http://dali.c1oappe.top/Article/details/gt2hmfdfqvt.html

SELECT COUNT(*) FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2ffsmhtir.html

[Q27] 条件计数
来源：http://dali.redwolf501.top/Article/details/gt2ktunuuuf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2lxhcajvf.html

[Q28] 求和与平均
来源：http://dali.zhongyouzk.top/Article/details/gt2qxelwvaj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yj202588.top/Article/details/gt2zvenqshu.html

[Q29] 最大最小值
来源：http://dali.yvedp.cn/Article/details/gt2caguuqnf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2taexzcew.html

[Q30] 分组统计
来源：http://dali.jinqigufen.top/Article/details/gt2ornsyued.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.nanxinkj.top/Article/details/gt2jpbfiltr.html

[Q31] 分组后过滤
来源：http://dali.daxiang520.top/Article/details/gt2ctajsddh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shzxlz.cn/Article/details/gt2sqlmpgfa.html

[Q32] 分组拼接字符串
来源：http://dali.yongpay.top/Article/details/gt2mpcttusu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.smart0.xyz/Article/details/gt2pisuzgqi.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.iojbl.cn/Article/details/gt2vbsuultu.html

[Q33] 多列分组
来源：http://dali.kuanghao11.cn/Article/details/gt2vgjxtxha.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hnxiangtu.top/Article/details/gt2oxylasmy.html

[Q34] 每组取第一条
来源：http://dali.jianghu66.top/Article/details/gt2qlneefev.html

SELECT * FROM (
来源：http://dali.fengsongda.top/Article/details/gt2lelwuowc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.nanxinkj.top/Article/details/gt2xnijfiur.html

) t WHERE rn = 1;
来源：http://dali.jlsjyb.cn/Article/details/gt2yrgmckdp.html

[Q35] 内连接
来源：http://dali.ybcxt.top/Article/details/gt2jrbxyhoh.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xylfe.cn/Article/details/gt2hiooxgig.html

[Q36] 左连接
来源：http://dali.jqgufenzy.top/Article/details/gt2rcqfctyn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangdashe.top/Article/details/gt2ozrwehsy.html

[Q37] 右连接
来源：http://dali.xziqi.cn/Article/details/gt2mybgndbk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yanxiufei.cn/Article/details/gt2tqsqhjie.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.tianlin.xyz/Article/details/gt2trhicgcf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.andypj.xyz/Article/details/gt2qamowzmo.html

[Q39] 自连接（查上下级）
来源：http://dali.yueranfly.top/Article/details/gt2sflezvkw.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.fengsongda.top/Article/details/gt2cgmpwdps.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhoulong.xyz/Article/details/gt2bqqjpfsm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vxobehfy.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.gotoacloud.top/Article/details/gt2rbzpwyje.html

[Q41] 多表连接
来源：http://dali.zhoulong.xyz/Article/details/gt2qstufmdu.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hammf.cn/Article/details/gt2ycdaknnn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cfnwwixg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jlsjyb.cn/Article/details/gt2bavidxzo.html

[Q42] 连接条件附加过滤
来源：http://dali.jqgfzy.top/Article/details/gt2wqthvxsu.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jinqigfzy.top/Article/details/gt2mlvbawpg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.fengsongda.top/Article/details/gt2qoixzfmt.html

[Q43] 标量子查询
来源：http://dali.yongpay.top/Article/details/gt2sgfxifgg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.gaohongyu789.top/Article/details/gt2cqfnibzv.html

[Q44] IN 子查询
来源：http://dali.gzhubu.top/Article/details/gt2artuejvs.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.pengpengdd.cyou/Article/details/gt2omjvdrjd.html

[Q45] EXISTS 判断存在
来源：http://dali.yueranfly.top/Article/details/gt2vfrywuqm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.0kj1m.cn/Article/details/gt2fzmjocok.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.birdmap.top/Article/details/gt2fzjdgqtt.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.316326.xyz/Article/details/gt2uvwmshpi.html

[Q47] 与平均值比较
来源：http://dali.c1oappe.top/Article/details/gt2qwiztmnj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.nwbrower.top/Article/details/gt2tofzheho.html

[Q48] CTE 公用表表达式
来源：http://dali.snrcjt.cn/Article/details/gt2zcpgopov.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hammf.cn/Article/details/gt2qjfcgcvg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hfpthk.cn/Article/details/gt2uudrpssy.html

[Q49] 更新单行
来源：http://dali.jinqigfzy.top/Article/details/gt2yukzyyok.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2leuhndwn.html

[Q50] 批量更新
来源：http://dali.jinqigfzy.top/Article/details/gt2lvqiuqpo.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.aizwys.cn/Article/details/gt2vmeogmaz.html

[Q51] 用子查询更新
来源：http://dali.smart0.xyz/Article/details/gt2cqgsqmrz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.nanxinkj.top/Article/details/gt2qvfiuzis.html

[Q52] 删除指定行
来源：http://dali.yangfankeji.com/Article/details/gt2bilyjlhk.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hnqzz.top/Article/details/gt2jwyzhxbi.html

[Q53] 按条件删除
来源：http://dali.9152youxi.cn/Article/details/gt2yygfzwdi.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhoulong.xyz/Article/details/gt2pjeeebla.html

[Q54] 清空表
来源：http://dali.dianchejie.cn/Article/details/gt2xmhgxjmu.html

TRUNCATE TABLE logs;
来源：http://dali.9152youxi.cn/Article/details/gt2rsvgkuad.html

[Q55] 排名（并列占位）
来源：http://dali.jinqigfzy.top/Article/details/gt2wkvtzlmh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.fengsongda.top/Article/details/gt2qycjwasj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xylfe.cn/Article/details/gt2kibxvcpe.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hammf.cn/Article/details/gt2rmbbonlv.html

[Q57] 行号
来源：http://dali.dashuyun.cn/Article/details/gt2bnjckeel.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2funeadgo.html

[Q58] 累计求和
来源：http://dali.feifeiyinyue.top/Article/details/gt2wpzpqpne.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gt2yoiqytft.html

[Q59] 分组内累计
来源：http://dali.dashuyun.cn/Article/details/gt2vsaazpoq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.wangdashe.top/Article/details/gt2wlkpafua.html

[Q60] 取上一行 / 下一行
来源：http://dali.sysykeji.top/Article/details/gt2vgapjumx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.c1oappe.top/Article/details/gt2pvjgdwjq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.aizwys.cn/Article/details/gt2vpbfofdj.html

[Q61] 移动平均
来源：http://dali.0kj1m.cn/Article/details/gt2wfpgxlko.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.daxiang520.top/Article/details/gt2wxtjnlsu.html

[Q62] 分组占比
来源：http://dali.c1oappe.top/Article/details/gt2uxdjqfte.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xuanzx.com/Article/details/gt2azmsyjyk.html

[Q63] 开启事务
来源：http://dali.yuxming.cn/Article/details/gt2lkzsrwwa.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.snrcjt.cn/Article/details/gt2uyfblwsq.html

[Q64] 提交事务
来源：http://dali.gogol.net.cn/Article/details/gt2urixxrcv.html

COMMIT;
来源：http://dali.shangyingyoupin.top/Article/details/gt2gpccggqt.html

[Q65] 回滚事务
来源：http://dali.dianchejie.cn/Article/details/gt2dwapwtnm.html

ROLLBACK;
来源：http://dali.daria6918.cn/Article/details/gt2wemicmzj.html

[Q66] 行锁查询
来源：http://dali.jqgufenzy.top/Article/details/gt2vdtbdbbs.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cashguo.top/Article/details/gt2hllguiij.html

[Q67] 设置隔离级别
来源：http://dali.zdqjudy.top/Article/details/gt2lzcjoatc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hongshengwenyu.top/Article/details/gt2oqrsqsof.html

[Q68] 保存点
来源：http://dali.feifeiyinyue.top/Article/details/gt2bspbbnix.html

SAVEPOINT sp1;
来源：http://dali.andypj.xyz/Article/details/gt2dzvwoqad.html

ROLLBACK TO sp1;
来源：http://dali.gzhubu.top/Article/details/gt2jvxvbptt.html

[Q69] 查看执行计划
来源：http://dali.xylfe.cn/Article/details/gt2rxatszae.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.chenzaomai.com/Article/details/gt2cxuqhgse.html

[Q70] 更新统计信息
来源：http://dali.xziqi.cn/Article/details/gt2vmtavakg.html

ANALYZE TABLE users;
来源：http://dali.yvedp.cn/Article/details/gt2rcikormw.html

[Q71] 查看建表语句
来源：http://dali.yangfankeji.com/Article/details/gt2lnvnukeo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.smart0.xyz/Article/details/gt2ygpwslwe.html

[Q72] 查看索引
来源：http://dali.ppjwa.cn/Article/details/gt2vxdlbcst.html

SHOW INDEX FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2nmnqkqkd.html

[Q73] 查看表状态
来源：http://dali.bjfxy.top/Article/details/gt2cmaavjhg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cheryme.top/Article/details/gt2ppfloesz.html

[Q74] 强制使用索引
来源：http://dali.shangyingyoupin.top/Article/details/gt2pswuzmaq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.birdmap.top/Article/details/gt2jiqykbvd.html

[Q75] 日期格式化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oiwoseeu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yj20258888.top/Article/details/gt2xvwlognv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hysaishi.cn/Article/details/gt2mhlsbbuj.html

[Q76] 按天统计
来源：http://dali.cheryme.top/Article/details/gt2zwibtgew.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.tianlin.xyz/Article/details/gt2xgloxcjf.html

[Q77] 时间加减
来源：http://dali.guowangkeji.top/Article/details/gt2tsjkwjpi.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jlsjyb.cn/Article/details/gt2oxmlgvvq.html

[Q78] 当前时间
来源：http://dali.meibo888.top/Article/details/gt2hfplsrcm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.nwbrower.top/Article/details/gt2uctixooo.html

[Q79] 字符串拼接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iryoaakh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.tian-w.cn/Article/details/gt2uhcponro.html

[Q80] 字符串截取
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dlnlwwwn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gt2xrwqllsz.html

[Q81] 字符串替换
来源：http://dali.316326.xyz/Article/details/gt2ujhxcsgu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2kzjpavdg.html

[Q82] 字符长度与字节长度
来源：http://dali.jianghu66.top/Article/details/gt2mjmoxeku.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.tanke756.top/Article/details/gt2duylaofy.html

[Q83] 大小写转换
来源：http://dali.hysaishi.cn/Article/details/gt2afcavnqz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2dieadrdg.html

[Q84] 去除首尾空格
来源：http://dali.xuanzx.com/Article/details/gt2iotbukyo.html

SELECT TRIM(name) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uulgbdtl.html

[Q85] 数值取整
来源：http://dali.gotoacloud.top/Article/details/gt2qxfrvdsi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vrkjlwiu.html

[Q86] 读取 JSON 字段
来源：http://dali.ybcxt.top/Article/details/gt2nympmhvy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yuxming.cn/Article/details/gt2yjbehvcs.html

[Q87] JSON 字段做条件
来源：http://dali.nwbrower.top/Article/details/gt2pprzukwf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.chenzaomai.com/Article/details/gt2roymwsgm.html

[Q88] 行转列（条件聚合）
来源：http://dali.ehwqpu.com/Article/details/gt2yhedziux.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jinqigfzy.top/Article/details/gt2knusqsbr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2inbchkci.html

[Q89] 判断表是否存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zbghruqp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.feifeiyinyue.top/Article/details/gt2warstaat.html

[Q90] 生成序号列
来源：http://dali.dashuyun.cn/Article/details/gt2lhgavyvc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cheryme.top/Article/details/gt2taienvvf.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2elvmozlb.html

R. Bash 专题
来源：http://dali.yangfankeji.com/Article/details/gt2nsicsmub.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2wcimijem.html

[R01] shebang 与严格模式
来源：http://dali.316326.xyz/Article/details/gt2lupnoduk.html

#!/usr/bin/env bash
来源：http://dali.gotoacloud.top/Article/details/gt2cdaoddka.html

set -euo pipefail
来源：http://dali.yangfankeji.com/Article/details/gt2gqupabhk.html

[R02] 变量赋值与使用
来源：http://dali.kuanghao11.cn/Article/details/gt2crukijtt.html

name="Tom"; echo "$name"
来源：http://dali.redwolf501.top/Article/details/gt2viakoksd.html

[R03] 只读变量
来源：http://dali.jyoumei.cn/Article/details/gt2xsknaemq.html

readonly PI=3.14
来源：http://dali.yvedp.cn/Article/details/gt2tszlzuok.html

[R04] 位置参数
来源：http://dali.hnxiangtu.top/Article/details/gt2alzqxcis.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jiagoushi.top/Article/details/gt2faiqulnr.html

[R05] 参数默认值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2leffdonc.html

name="${1:-default}"
来源：http://dali.dashuyun.cn/Article/details/gt2cemzhcno.html

[R06] 判断命令是否存在
来源：http://dali.cheryme.top/Article/details/gt2tucwwqfa.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.tian-w.cn/Article/details/gt2imyffdky.html

[R07] if 判断文件
来源：http://dali.hnqzz.top/Article/details/gt2wysvvjzp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jqgufenzy.top/Article/details/gt2wylgavks.html

[R08] 数值比较
来源：http://dali.wangshuangyany.cn/Article/details/gt2wfnrkaxb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gt2vbufxgmh.html

[R09] 字符串比较
来源：http://dali.tanke756.top/Article/details/gt2rcrgriau.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.meibo888.top/Article/details/gt2xaergtxi.html

[R10] 正则匹配
来源：http://dali.yuxming.cn/Article/details/gt2qkcwowxc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yuanzhike.top/Article/details/gt2oojmntuu.html

[R11] case 多分支
来源：http://dali.gzhubu.top/Article/details/gt2oazfgdxa.html

case "$1" in
来源：http://dali.hysaishi.cn/Article/details/gt2oacjviff.html

start) echo "启动" ;;
来源：http://dali.chenlongwang.top/Article/details/gt2bfywnvnc.html

stop)  echo "停止" ;;
来源：http://dali.chenjidiqi.icu/Article/details/gt2babgbpfn.html

*)     echo "未知命令" ;;
来源：http://dali.quarkkingdee.top/Article/details/gt2lhbbwayr.html

esac
来源：http://dali.smart0.xyz/Article/details/gt2oupfcgkb.html

[R12] for 遍历文件
来源：http://dali.zhoulong.xyz/Article/details/gt2ljnfvugv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jianghu66.top/Article/details/gt2ufffimou.html

[R13] for 计数循环
来源：http://dali.zhixingplan.top/Article/details/gt2wbtlkiwq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yvedp.cn/Article/details/gt2qfpqpldp.html

[R14] C 风格 for
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pqlnyiax.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.feifeiyinyue.top/Article/details/gt2hcgalokr.html

[R15] while 逐行读文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2ahvsxoze.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yuanzhike.top/Article/details/gt2yzmyskfy.html

[R16] until 等待条件
来源：http://dali.gogol.net.cn/Article/details/gt2qvmucerl.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yanxiufei.cn/Article/details/gt2erkwuwck.html

[R17] 数组定义与取值
来源：http://dali.pycfn.com/Article/details/gt2lhprznlf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.tianlin.xyz/Article/details/gt2dzxdobjw.html

[R18] 遍历数组
来源：http://dali.hnxiangtu.top/Article/details/gt2zahhdlvt.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yuanzhike.top/Article/details/gt2oswatvaa.html

[R19] 数组长度
来源：http://dali.iojbl.cn/Article/details/gt2iajorvvm.html

echo "${#arr[@]}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2njkuequv.html

[R20] 关联数组（字典）
来源：http://dali.shzxlz.cn/Article/details/gt2bgywuwwv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.chenjidiqi.icu/Article/details/gt2nfvcpmlk.html

[R21] 字符串长度
来源：http://dali.xinyue.icu/Article/details/gt2hswbxbgb.html

echo "${#s}"
来源：http://dali.zhixingplan.top/Article/details/gt2ikiorxrr.html

[R22] 截取子串
来源：http://dali.ivvv.top/Article/details/gt2juvsilgp.html

echo "${s:0:5}"
来源：http://dali.shzxlz.cn/Article/details/gt2adillzai.html

[R23] 字符串替换
来源：http://dali.pycfn.com/Article/details/gt2piawyktc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xinyue.icu/Article/details/gt2mhvqkcvq.html

[R24] 大小写转换
来源：http://dali.yongpay.top/Article/details/gt2ziqxltbe.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.iojbl.cn/Article/details/gt2qrdptclw.html

[R25] 去后缀 / 去前缀
来源：http://dali.hnxiangtu.top/Article/details/gt2nmxhgwtu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yj20258.top/Article/details/gt2peajzsoc.html

[R26] 命令替换
来源：http://dali.ydzc1.top/Article/details/gt2anqkfgnh.html

now=$(date +%F); echo "$now"
来源：http://dali.pycfn.com/Article/details/gt2mltmyxwu.html

[R27] 算术展开
来源：http://dali.daxiang520.top/Article/details/gt2ruxdcehf.html

echo $((1 + 2 * 3))
来源：http://dali.0kj1m.cn/Article/details/gt2bipsuvul.html

[R28] 浮点运算
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uvlceyhl.html

echo "scale=2; 10/3" | bc
来源：http://dali.meibo888.top/Article/details/gt2iypzltzm.html

[R29] 定义函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2bfiedkkz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.quarkkingdee.top/Article/details/gt2kohwvtxz.html

[R30] 函数返回状态码
来源：http://dali.iojbl.cn/Article/details/gt2zrcwoqfc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yuanzhike.top/Article/details/gt2beemwmhd.html

[R31] 局部变量
来源：http://dali.nanxinkj.top/Article/details/gt2quuegrjw.html

f() { local x=1; echo "$x"; }
来源：http://dali.9152youxi.cn/Article/details/gt2anpwgpnh.html

[R32] 参数个数校验
来源：http://dali.shuidangran.top/Article/details/gt2jnjoanba.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jlsjyb.cn/Article/details/gt2uzgebdwh.html

[R33] 捕获错误并提示行号
来源：http://dali.bjfxy.top/Article/details/gt2kvayogae.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jyoumei.cn/Article/details/gt2ykellgom.html

[R34] 退出时清理
来源：http://dali.zycfv.cn/Article/details/gt2zrdlhywv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ehwqpu.com/Article/details/gt2ewqagbnn.html

[R35] 后台执行并等待
来源：http://dali.cdnleiting.top/Article/details/gt2lrkkdxhm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.vqdsnc.cn/Article/details/gt2tliwkkfq.html

[R36] 并发执行多个任务
来源：http://dali.hnqzz.top/Article/details/gt2cekwvejr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hnqzz.top/Article/details/gt2qvhdiltb.html

[R37] 把输出赋给变量
来源：http://dali.xuanzx.com/Article/details/gt2zmihxdye.html

files=$(ls -1)
来源：http://dali.yangfankeji.com/Article/details/gt2nhlndftx.html

[R38] 管道串联
来源：http://dali.jqgufenzy.top/Article/details/gt2oplgotay.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rurmgqpk.html

[R39] 重定向标准输出与错误
来源：http://dali.quarkkingdee.top/Article/details/gt2ysgcyrkx.html

cmd > out.log 2>&1
来源：http://dali.9152youxi.cn/Article/details/gt2taqgrfnd.html

[R40] 追加写日志
来源：http://dali.svipenyu.cn/Article/details/gt2jffpbkyq.html

echo "log" >> out.log
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2scztkchf.html

[R41] 丢弃输出
来源：http://dali.snrcjt.cn/Article/details/gt2igqgugqc.html

cmd >/dev/null 2>&1
来源：http://dali.ydzc1.top/Article/details/gt2eiqnoijp.html

[R42] 输入重定向
来源：http://dali.ydzc1.top/Article/details/gt2dobwnrhf.html

wc -l < a.txt
来源：http://dali.iojbl.cn/Article/details/gt2exqqishl.html

[R43] 按名字查找文件
来源：http://dali.zdqjudy.top/Article/details/gt2fxwnjhvw.html

find . -name "*.log" -type f
来源：http://dali.sweek.top/Article/details/gt2qsddrtqp.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdfalov.html

find . -mtime -7 -type f
来源：http://dali.feifeiyinyue.top/Article/details/gt2jbrsnodw.html

[R45] 批量删除
来源：http://dali.zhoulong.xyz/Article/details/gt2cpshuzzp.html

find . -name "*.tmp" -delete
来源：http://dali.jiagoushi.top/Article/details/gt2gncvaywp.html

[R46] 递归替换文件内容
来源：http://dali.316326.xyz/Article/details/gt2ltahlffm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cheryme.top/Article/details/gt2uuykkokq.html

[R47] sed 单行替换
来源：http://dali.svipenyu.cn/Article/details/gt2mjwnrjqa.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.iojbl.cn/Article/details/gt2uwxncdwg.html

[R48] awk 取指定列
来源：http://dali.hnxiangtu.top/Article/details/gt2odlyjjyk.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhixingplan.top/Article/details/gt2tuqliuza.html

[R49] awk 带条件
来源：http://dali.fzhhl.top/Article/details/gt2ldlhckti.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yj202588.top/Article/details/gt2kjcbbznj.html

[R50] awk 求和
来源：http://dali.c1oappe.top/Article/details/gt2cybhpsfs.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shzxlz.cn/Article/details/gt2tqbtrphi.html

[R51] 排序去重取前几
来源：http://dali.yanxiufei.cn/Article/details/gt2ulgxyiri.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ppjwa.cn/Article/details/gt2fdmmtvgb.html

[R52] 统计行数
来源：http://dali.pengpengdd.cyou/Article/details/gt2alyrhhii.html

wc -l a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gt2rlbczzki.html

[R53] 查看文件头与实时尾
来源：http://dali.jiagoushi.top/Article/details/gt2yvmhuson.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhengqikj.top/Article/details/gt2cqidzudz.html

[R54] 比较两个文件
来源：http://dali.guowangkeji.top/Article/details/gt2odaqchen.html

diff a.txt b.txt
来源：http://dali.xuetiantiany.cn/Article/details/gt2idghzfpl.html

[R55] 压缩与解压
来源：http://dali.dianchejie.cn/Article/details/gt2iiyeztfq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yongpay.top/Article/details/gt2bcxkjxxs.html

[R56] 远程拷贝
来源：http://dali.mhx1999.top/Article/details/gt2rffktnmi.html

scp file user@host:/path/
来源：http://dali.jianghu66.top/Article/details/gt2wzwziuut.html

[R57] 远程执行命令
来源：http://dali.nanxuanxn.top/Article/details/gt2madrozeh.html

ssh user@host 'uptime'
来源：http://dali.wangdashe.top/Article/details/gt2mvmnhljp.html

[R58] 下载文件
来源：http://dali.yangfankeji.com/Article/details/gt2wlrekrru.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.chenjidiqi.icu/Article/details/gt2qabkidcv.html

[R59] 发 POST JSON
来源：http://dali.zhoulong.xyz/Article/details/gt2yoxzbown.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.vqdsnc.cn/Article/details/gt2econmltk.html

[R60] 只看 HTTP 状态码
来源：http://dali.tanke756.top/Article/details/gt2cnfvdobl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yanxiufei.cn/Article/details/gt2qlovsenh.html

[R61] 磁盘占用
来源：http://dali.chenjidiqi.icu/Article/details/gt2gqkbnhzs.html

df -h;  du -sh *
来源：http://dali.sxryk.cn/Article/details/gt2ecslqilz.html

[R62] 找最占空间的文件
来源：http://dali.aizwys.cn/Article/details/gt2rwahbvvb.html

du -ah . | sort -rh | head -10
来源：http://dali.zhixingplan.top/Article/details/gt2mwulxzdm.html

[R63] 内存与进程
来源：http://dali.birdmap.top/Article/details/gt2nqmeiaug.html

free -h;  ps aux | grep nginx
来源：http://dali.zhiwuduotai.top/Article/details/gt2gsdmxsop.html

[R64] 结束进程
来源：http://dali.smart0.xyz/Article/details/gt2ykdyzyct.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhoulong.xyz/Article/details/gt2wjlnlbyf.html

[R65] 查看端口占用
来源：http://dali.fengsongda.top/Article/details/gt2dqkukptu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yuanzhike.top/Article/details/gt2yechcbjn.html

[R66] 定时任务
来源：http://dali.jinghuilouyu.cn/Article/details/gt2snbxkqnp.html

crontab -e;  crontab -l
来源：http://dali.jianghu66.top/Article/details/gt2xrerffsi.html

[R67] 生成随机十六进制串
来源：http://dali.mhx1999.top/Article/details/gt2sgokhbjq.html

openssl rand -hex 16
来源：http://dali.hywenlv.cn/Article/details/gt2hbcoxkvr.html

[R68] 计算文件校验值
来源：http://dali.cqqwz.cn/Article/details/gt2asfrafky.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.fengsongda.top/Article/details/gt2stsoiowb.html

[R69] 生成随机密码
来源：http://dali.ppjwa.cn/Article/details/gt2kflymsay.html


<!-- 参考信息 -->