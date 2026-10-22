代发 wailian999

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.fengsongda.top/Article/details/gt2dlvgozzd.html

[Q20] IN 列表
来源：http://dali.9152youxi.cn/Article/details/gt2nglubszd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.quarkkingdee.top/Article/details/gt2ndhcnuxj.html

[Q21] 空值判断
来源：http://dali.ivvv.top/Article/details/gt2givkvjqu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yvedp.cn/Article/details/gt2yjjicgxs.html

[Q22] 排序
来源：http://dali.yvedp.cn/Article/details/gt2fmpsikzu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ydzc1.top/Article/details/gt2ajiqgvxu.html

[Q23] 分页
来源：http://dali.cqqwz.cn/Article/details/gt2xicusrru.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.meibo888.top/Article/details/gt2aieyczxe.html

[Q24] 去重
来源：http://dali.yuanzhike.top/Article/details/gt2ovpldvsz.html

SELECT DISTINCT city FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2tgqfnjtp.html

[Q25] 只取前 N 条
来源：http://dali.fengsongda.top/Article/details/gt2srxduzgj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xuanzx.com/Article/details/gt2zdvuvcyc.html

[Q26] 计数
来源：http://dali.nanxinkj.top/Article/details/gt2shqfjyvn.html

SELECT COUNT(*) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2igaevsmp.html

[Q27] 条件计数
来源：http://dali.9152youxi.cn/Article/details/gt2wtsszywn.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2bapinqon.html

[Q28] 求和与平均
来源：http://dali.c1oappe.top/Article/details/gt2adtzhhbk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ybcxt.top/Article/details/gt2tcsztezw.html

[Q29] 最大最小值
来源：http://dali.316326.xyz/Article/details/gt2fonaqfpz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2lnieoykx.html

[Q30] 分组统计
来源：http://dali.hysaishi.cn/Article/details/gt2duatrten.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jiagoushi.top/Article/details/gt2hsqmnbtn.html

[Q31] 分组后过滤
来源：http://dali.cheryme.top/Article/details/gt2midahfhx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.nanxinkj.top/Article/details/gt2bmixebrd.html

[Q32] 分组拼接字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zcohrgng.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.svipenyu.cn/Article/details/gt2njskgrxt.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.aizwys.cn/Article/details/gt2oockzkow.html

[Q33] 多列分组
来源：http://dali.zhiwuduotai.top/Article/details/gt2bbzkkpvt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ezmdozsa.html

[Q34] 每组取第一条
来源：http://dali.aizwys.cn/Article/details/gt2laujmjfa.html

SELECT * FROM (
来源：http://dali.cqqwz.cn/Article/details/gt2epjgxmxa.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.andypj.xyz/Article/details/gt2pmhdtdel.html

) t WHERE rn = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gt2lxjqucjl.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jteezljg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hysaishi.cn/Article/details/gt2zttwtnjv.html

[Q36] 左连接
来源：http://dali.jqgufenzy.top/Article/details/gt2sgmklqul.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gaohongyu789.top/Article/details/gt2aaelcnuq.html

[Q37] 右连接
来源：http://dali.snrcjt.cn/Article/details/gt2wvzwsupf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.sufxvd.cn/Article/details/gt2iskapmdq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.gzhubu.top/Article/details/gt2ellpadwz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.daria6918.cn/Article/details/gt2rmqywfqj.html

[Q39] 自连接（查上下级）
来源：http://dali.aizwys.cn/Article/details/gt2grzixauk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rdbvimrp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhoulong.xyz/Article/details/gt2rrwdarel.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2capnxhrr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sxryk.cn/Article/details/gt2igqtysrb.html

[Q41] 多表连接
来源：http://dali.jinqigufen.top/Article/details/gt2ecssqchp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yonumen.top/Article/details/gt2gktxgcxx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.smart0.xyz/Article/details/gt2tjmfoauc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xylfe.cn/Article/details/gt2pbnogfsh.html

[Q42] 连接条件附加过滤
来源：http://dali.pycfn.com/Article/details/gt2mlzddeuz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhengqikj.top/Article/details/gt2efsjptws.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.svipenyu.cn/Article/details/gt2igdkeged.html

[Q43] 标量子查询
来源：http://dali.chenjidiqi.icu/Article/details/gt2fcslumwa.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.tian-w.cn/Article/details/gt2lqzpwhxi.html

[Q44] IN 子查询
来源：http://dali.jyoumei.cn/Article/details/gt2seosntxr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.fzhhl.top/Article/details/gt2warhhfqo.html

[Q45] EXISTS 判断存在
来源：http://dali.cashguo.top/Article/details/gt2zzgosvqf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.havefunace.top/Article/details/gt2jxbksuck.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.dianchejie.cn/Article/details/gt2yjxrttna.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.dashuyun.cn/Article/details/gt2otpihkja.html

[Q47] 与平均值比较
来源：http://dali.redwolf501.top/Article/details/gt2rdcbvaye.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jianghu66.top/Article/details/gt2qkgkofsg.html

[Q48] CTE 公用表表达式
来源：http://dali.cashguo.top/Article/details/gt2wsvfhwcf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.kuanghao11.cn/Article/details/gt2zxllcoss.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.quarkkingdee.top/Article/details/gt2yvdndaff.html

[Q49] 更新单行
来源：http://dali.xylfe.cn/Article/details/gt2paqfqqxx.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ybcxt.top/Article/details/gt2wgdbvypz.html

[Q50] 批量更新
来源：http://dali.meibo888.top/Article/details/gt2jlleegex.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sufxvd.cn/Article/details/gt2rnxagqda.html

[Q51] 用子查询更新
来源：http://dali.tian-w.cn/Article/details/gt2lztepnii.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gt2vkwdnnfb.html

[Q52] 删除指定行
来源：http://dali.guannengcc.top/Article/details/gt2kqzlapvv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hongshengwenyu.top/Article/details/gt2mnhnkjih.html

[Q53] 按条件删除
来源：http://dali.c1oappe.top/Article/details/gt2oenjrmrl.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hnqzz.top/Article/details/gt2xhbvpvgw.html

[Q54] 清空表
来源：http://dali.zycfv.cn/Article/details/gt2efwtynpj.html

TRUNCATE TABLE logs;
来源：http://dali.feifeiyinyue.top/Article/details/gt2tmkqzcom.html

[Q55] 排名（并列占位）
来源：http://dali.snrcjt.cn/Article/details/gt2fhxyxcfz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.fzhhl.top/Article/details/gt2achoyxeu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yueranfly.top/Article/details/gt2xkoepmce.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.snrcjt.cn/Article/details/gt2tivhwcwc.html

[Q57] 行号
来源：http://dali.hongshengwenyu.top/Article/details/gt2okjpknoh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yaysocnp.html

[Q58] 累计求和
来源：http://dali.yanxiufei.cn/Article/details/gt2uqybygar.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gt2nlkaxtrd.html

[Q59] 分组内累计
来源：http://dali.jyoumei.cn/Article/details/gt2lqprgqyu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gt2tsgtevnr.html

[Q60] 取上一行 / 下一行
来源：http://dali.wangdashe.top/Article/details/gt2hpccvgrv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hnxiangtu.top/Article/details/gt2ebiydmqb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gt2rjsgoknd.html

[Q61] 移动平均
来源：http://dali.jyoumei.cn/Article/details/gt2fefscsrn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gt2ijyzujze.html

[Q62] 分组占比
来源：http://dali.jianghu66.top/Article/details/gt2pthfxtbx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.chenzaomai.com/Article/details/gt2ivcvlyub.html

[Q63] 开启事务
来源：http://dali.gotoacloud.top/Article/details/gt2vclhgmlq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yj20258888.top/Article/details/gt2tpohkbwv.html

[Q64] 提交事务
来源：http://dali.feifeiyinyue.top/Article/details/gt2mxndmwqr.html

COMMIT;
来源：http://dali.smart0.xyz/Article/details/gt2sfsvvgab.html

[Q65] 回滚事务
来源：http://dali.shzxlz.cn/Article/details/gt2atewpffn.html

ROLLBACK;
来源：http://dali.haohaochexian.top/Article/details/gt2uisclawu.html

[Q66] 行锁查询
来源：http://dali.havefunace.top/Article/details/gt2qrvdyalz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhengqikj.top/Article/details/gt2maimuogj.html

[Q67] 设置隔离级别
来源：http://dali.chenjidiqi.icu/Article/details/gt2utfxjaib.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.snrcjt.cn/Article/details/gt2yppcwclu.html

[Q68] 保存点
来源：http://dali.cqqwz.cn/Article/details/gt2rqgupgwa.html

SAVEPOINT sp1;
来源：http://dali.zhoulong.xyz/Article/details/gt2wyauhdxa.html

ROLLBACK TO sp1;
来源：http://dali.aibaodan.cn/Article/details/gt2zyvcbybh.html

[Q69] 查看执行计划
来源：http://dali.wangdashe.top/Article/details/gt2tnqiobqa.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cqqwz.cn/Article/details/gt2abiwlsdw.html

[Q70] 更新统计信息
来源：http://dali.hnqzz.top/Article/details/gt2dgeaylnx.html

ANALYZE TABLE users;
来源：http://dali.aibaodan.cn/Article/details/gt2nzttxyew.html

[Q71] 查看建表语句
来源：http://dali.daria6918.cn/Article/details/gt2llghnlyj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.sxryk.cn/Article/details/gt2ofklfvcj.html

[Q72] 查看索引
来源：http://dali.svipenyu.cn/Article/details/gt2ofzlyqxf.html

SHOW INDEX FROM users;
来源：http://dali.yj202588.top/Article/details/gt2tnrrynan.html

[Q73] 查看表状态
来源：http://dali.shzxlz.cn/Article/details/gt2gehcksmg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.haohaochexian.top/Article/details/gt2dwivqbnk.html

[Q74] 强制使用索引
来源：http://dali.gzhubu.top/Article/details/gt2qogxofnu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.gaohongyu789.top/Article/details/gt2iiqtewsh.html

[Q75] 日期格式化
来源：http://dali.tian-w.cn/Article/details/gt2fdwzqboc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gt2prkevwku.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2usoeiorh.html

[Q76] 按天统计
来源：http://dali.fzhhl.top/Article/details/gt2ozymeanx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhongyouzk.top/Article/details/gt2jpxtiykc.html

[Q77] 时间加减
来源：http://dali.jlsjyb.cn/Article/details/gt2kiziluui.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hysaishi.cn/Article/details/gt2aburtrah.html

[Q78] 当前时间
来源：http://dali.hfpthk.cn/Article/details/gt2mtadojrc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinqigfzy.top/Article/details/gt2rzkubaya.html

[Q79] 字符串拼接
来源：http://dali.shangyingyoupin.top/Article/details/gt2itipywni.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.guowangkeji.top/Article/details/gt2lfblthej.html

[Q80] 字符串截取
来源：http://dali.yuanzhike.top/Article/details/gt2bdaajkvs.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2zzrswrvy.html

[Q81] 字符串替换
来源：http://dali.9152youxi.cn/Article/details/gt2yinsmwzo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2amgnvppx.html

[Q82] 字符长度与字节长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vdagfipt.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cwyjqtab.html

[Q83] 大小写转换
来源：http://dali.c1oappe.top/Article/details/gt2ysrjvupe.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.havefunace.top/Article/details/gt2wbcjophx.html

[Q84] 去除首尾空格
来源：http://dali.yuanzhike.top/Article/details/gt2drrngkal.html

SELECT TRIM(name) FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2onsiztpm.html

[Q85] 数值取整
来源：http://dali.aibaodan.cn/Article/details/gt2csmrhhck.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gaohongyu789.top/Article/details/gt2xncerern.html

[Q86] 读取 JSON 字段
来源：http://dali.c1oappe.top/Article/details/gt2zseyjphu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.fengsongda.top/Article/details/gt2ymoeubsj.html

[Q87] JSON 字段做条件
来源：http://dali.yvedp.cn/Article/details/gt2pjqsmvie.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zjngigpq.html

[Q88] 行转列（条件聚合）
来源：http://dali.ydzc1.top/Article/details/gt2fvaceemf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yongpay.top/Article/details/gt2inxojzud.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2yzsedleo.html

[Q89] 判断表是否存在
来源：http://dali.hywenlv.cn/Article/details/gt2qhlxsdyc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nanxuanxn.top/Article/details/gt2rxyijqrv.html

[Q90] 生成序号列
来源：http://dali.yanxiufei.cn/Article/details/gt2gxkachwa.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.haohaochexian.top/Article/details/gt2hxmwtbxk.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2kjzjqpxm.html

R. Bash 专题
来源：http://dali.jqgufenzy.top/Article/details/gt2favpmier.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2atpkdjff.html

[R01] shebang 与严格模式
来源：http://dali.dianchejie.cn/Article/details/gt2ikrpdngg.html

#!/usr/bin/env bash
来源：http://dali.quarkkingdee.top/Article/details/gt2xwjgmiua.html

set -euo pipefail
来源：http://dali.hammf.cn/Article/details/gt2urixocug.html

[R02] 变量赋值与使用
来源：http://dali.xylfe.cn/Article/details/gt2kdexpdit.html

name="Tom"; echo "$name"
来源：http://dali.snrcjt.cn/Article/details/gt2axubjmer.html

[R03] 只读变量
来源：http://dali.chenjidiqi.icu/Article/details/gt2vfawkfrk.html

readonly PI=3.14
来源：http://dali.daria6918.cn/Article/details/gt2lbpegvsj.html

[R04] 位置参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2dfxoatxj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.daria6918.cn/Article/details/gt2uuubvaeh.html

[R05] 参数默认值
来源：http://dali.chenjidiqi.icu/Article/details/gt2ktlaqrww.html

name="${1:-default}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2nvswgpdl.html

[R06] 判断命令是否存在
来源：http://dali.ybcxt.top/Article/details/gt2zruvzbzo.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2zfjhfopv.html

[R07] if 判断文件
来源：http://dali.jqgufenzy.top/Article/details/gt2ougndbar.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ydzc1.top/Article/details/gt2xhtfsxtv.html

[R08] 数值比较
来源：http://dali.zhengqikj.top/Article/details/gt2xudtrosk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.iojbl.cn/Article/details/gt2zjbmglxg.html

[R09] 字符串比较
来源：http://dali.cucudq.cn/Article/details/gt2rlbhhuij.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eudwqmsp.html

[R10] 正则匹配
来源：http://dali.mhx1999.top/Article/details/gt2ewddjdkk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.redwolf501.top/Article/details/gt2jvrruuzf.html

[R11] case 多分支
来源：http://dali.nwbrower.top/Article/details/gt2spcgnpau.html

case "$1" in
来源：http://dali.yvedp.cn/Article/details/gt2smujboji.html

start) echo "启动" ;;
来源：http://dali.svipenyu.cn/Article/details/gt2eismgxnx.html

stop)  echo "停止" ;;
来源：http://dali.kuanghao11.cn/Article/details/gt2xobtwdoy.html

*)     echo "未知命令" ;;
来源：http://dali.sysykeji.top/Article/details/gt2pnmanrbi.html

esac
来源：http://dali.bjfxy.top/Article/details/gt2dbvzmlpu.html

[R12] for 遍历文件
来源：http://dali.xinyue.icu/Article/details/gt2urizzzcy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jyoumei.cn/Article/details/gt2fgzrhdpp.html

[R13] for 计数循环
来源：http://dali.chenzaomai.com/Article/details/gt2itaxsxcq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.redwolf501.top/Article/details/gt2stwonmdr.html

[R14] C 风格 for
来源：http://dali.cdnleiting.top/Article/details/gt2qrerjsam.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hysaishi.cn/Article/details/gt2dwtihzhw.html

[R15] while 逐行读文件
来源：http://dali.aizwys.cn/Article/details/gt2rinzrrxs.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yj202588.top/Article/details/gt2qqelakhz.html

[R16] until 等待条件
来源：http://dali.yj20258.top/Article/details/gt2fmehimvn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.meibo888.top/Article/details/gt2buqhfjhi.html

[R17] 数组定义与取值
来源：http://dali.svipenyu.cn/Article/details/gt2xwdceyiz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sysykeji.top/Article/details/gt2xzuzlmvc.html

[R18] 遍历数组
来源：http://dali.zhiwuduotai.top/Article/details/gt2dugdvcfn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhongyouzk.top/Article/details/gt2clceffjk.html

[R19] 数组长度
来源：http://dali.nanxuanxn.top/Article/details/gt2cmngynql.html

echo "${#arr[@]}"
来源：http://dali.daxiang520.top/Article/details/gt2lhvivtjy.html

[R20] 关联数组（字典）
来源：http://dali.ivvv.top/Article/details/gt2uvsaioeq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shangyingyoupin.top/Article/details/gt2hsgeizso.html

[R21] 字符串长度
来源：http://dali.sufxvd.cn/Article/details/gt2oosueyxk.html

echo "${#s}"
来源：http://dali.hywenlv.cn/Article/details/gt2cwpyittr.html

[R22] 截取子串
来源：http://dali.0kj1m.cn/Article/details/gt2ioyxiyjw.html

echo "${s:0:5}"
来源：http://dali.fengsongda.top/Article/details/gt2seuvwsgz.html

[R23] 字符串替换
来源：http://dali.0kj1m.cn/Article/details/gt2nzzazlcn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhengqikj.top/Article/details/gt2mwswodrg.html

[R24] 大小写转换
来源：http://dali.nanxinkj.top/Article/details/gt2mgqbbpba.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.svipenyu.cn/Article/details/gt2qouflvmz.html

[R25] 去后缀 / 去前缀
来源：http://dali.yuanzhike.top/Article/details/gt2fsqgwlim.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jyoumei.cn/Article/details/gt2kngxwnbo.html

[R26] 命令替换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kjvauzty.html

now=$(date +%F); echo "$now"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mguuturc.html

[R27] 算术展开
来源：http://dali.yj20258.top/Article/details/gt2dwwadxgw.html

echo $((1 + 2 * 3))
来源：http://dali.meibo888.top/Article/details/gt2cvoqbvrz.html

[R28] 浮点运算
来源：http://dali.zhiwuduotai.top/Article/details/gt2dxjdukry.html

echo "scale=2; 10/3" | bc
来源：http://dali.tanke756.top/Article/details/gt2cphvdwgp.html

[R29] 定义函数
来源：http://dali.jinqigfzy.top/Article/details/gt2awrnvpck.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.fzhhl.top/Article/details/gt2kvcvqxnv.html

[R30] 函数返回状态码
来源：http://dali.sxryk.cn/Article/details/gt2ttmagcce.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinqigfzy.top/Article/details/gt2hwddrcwy.html

[R31] 局部变量
来源：http://dali.shuidangran.top/Article/details/gt2qnfmcvwx.html

f() { local x=1; echo "$x"; }
来源：http://dali.yangfankeji.com/Article/details/gt2pauaoqhx.html

[R32] 参数个数校验
来源：http://dali.jyoumei.cn/Article/details/gt2tvhfzayc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.aibaodan.cn/Article/details/gt2jvqpibcg.html

[R33] 捕获错误并提示行号
来源：http://dali.sweek.top/Article/details/gt2roxnhuqh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zdqjudy.top/Article/details/gt2gbyzxhhp.html

[R34] 退出时清理
来源：http://dali.zhengqikj.top/Article/details/gt2rejisfxl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.kuanghao11.cn/Article/details/gt2boawzorb.html

[R35] 后台执行并等待
来源：http://dali.sysykeji.top/Article/details/gt2ivtvcedm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jqgufenzy.top/Article/details/gt2fahfkjix.html

[R36] 并发执行多个任务
来源：http://dali.ybcxt.top/Article/details/gt2rjeaxkrg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.0kj1m.cn/Article/details/gt2btbrsmbf.html

[R37] 把输出赋给变量
来源：http://dali.ehwqpu.com/Article/details/gt2akcsstqv.html

files=$(ls -1)
来源：http://dali.snrcjt.cn/Article/details/gt2zzoahlmg.html

[R38] 管道串联
来源：http://dali.snrcjt.cn/Article/details/gt2frwndiva.html

cat a.txt | grep -i error | wc -l
来源：http://dali.svipenyu.cn/Article/details/gt2ckmlebpj.html

[R39] 重定向标准输出与错误
来源：http://dali.hnqzz.top/Article/details/gt2hmrzoybb.html

cmd > out.log 2>&1
来源：http://dali.hywenlv.cn/Article/details/gt2gffnicnf.html

[R40] 追加写日志
来源：http://dali.wangshuangyany.cn/Article/details/gt2sdhbpdyf.html

echo "log" >> out.log
来源：http://dali.mhx1999.top/Article/details/gt2frrgcfzy.html

[R41] 丢弃输出
来源：http://dali.chenlongwang.top/Article/details/gt2wilqrjuw.html

cmd >/dev/null 2>&1
来源：http://dali.havefunace.top/Article/details/gt2ocbecpuo.html

[R42] 输入重定向
来源：http://dali.cashguo.top/Article/details/gt2tqmqlttf.html

wc -l < a.txt
来源：http://dali.tianlin.xyz/Article/details/gt2hgrlkoeh.html

[R43] 按名字查找文件
来源：http://dali.xuanzx.com/Article/details/gt2pfkjpbka.html

find . -name "*.log" -type f
来源：http://dali.chenjidiqi.icu/Article/details/gt2mncijnhw.html

[R44] 按修改时间查找
来源：http://dali.jqgufenzy.top/Article/details/gt2asffrnwg.html

find . -mtime -7 -type f
来源：http://dali.snrcjt.cn/Article/details/gt2mzqsosce.html

[R45] 批量删除
来源：http://dali.redwolf501.top/Article/details/gt2xyyrjzev.html

find . -name "*.tmp" -delete
来源：http://dali.gzhubu.top/Article/details/gt2websxnpc.html

[R46] 递归替换文件内容
来源：http://dali.zhixingplan.top/Article/details/gt2mmqbvptk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hfpthk.cn/Article/details/gt2kymqvoom.html

[R47] sed 单行替换
来源：http://dali.yonumen.top/Article/details/gt2gczrmfnz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cucudq.cn/Article/details/gt2lqftimvw.html

[R48] awk 取指定列
来源：http://dali.jyoumei.cn/Article/details/gt2hwucswht.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhoulong.xyz/Article/details/gt2cdzxvcbt.html

[R49] awk 带条件
来源：http://dali.mhx1999.top/Article/details/gt2vxjdmquu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yj202588.top/Article/details/gt2akzbobkz.html

[R50] awk 求和
来源：http://dali.pengpengdd.cyou/Article/details/gt2eowlzqvj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gt2wuoyfsjb.html

[R51] 排序去重取前几
来源：http://dali.andypj.xyz/Article/details/gt2ggrwdobg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hysaishi.cn/Article/details/gt2hpkckizk.html

[R52] 统计行数
来源：http://dali.ybcxt.top/Article/details/gt2jipcqfpt.html

wc -l a.txt
来源：http://dali.0kj1m.cn/Article/details/gt2aslnsjsv.html

[R53] 查看文件头与实时尾
来源：http://dali.yj20258888.top/Article/details/gt2ubqesyqw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ppjwa.cn/Article/details/gt2eanepffl.html

[R54] 比较两个文件
来源：http://dali.jiagoushi.top/Article/details/gt2xbbvxvnv.html

diff a.txt b.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ykxononw.html

[R55] 压缩与解压
来源：http://dali.hfpthk.cn/Article/details/gt2fsnhyxwm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jiagoushi.top/Article/details/gt2jbvjcbyq.html

[R56] 远程拷贝
来源：http://dali.ydzc1.top/Article/details/gt2skysalss.html

scp file user@host:/path/
来源：http://dali.jiagoushi.top/Article/details/gt2fumpakmk.html

[R57] 远程执行命令
来源：http://dali.smart0.xyz/Article/details/gt2ohlrlpsd.html

ssh user@host 'uptime'
来源：http://dali.gotoacloud.top/Article/details/gt2xaeyurvp.html

[R58] 下载文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2udrcpqga.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xinyue.icu/Article/details/gt2rlypfenk.html

[R59] 发 POST JSON
来源：http://dali.wangdashe.top/Article/details/gt2qgqvuheq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gogol.net.cn/Article/details/gt2vthcjhca.html

[R60] 只看 HTTP 状态码
来源：http://dali.haohaochexian.top/Article/details/gt2uyjbmjai.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ivvv.top/Article/details/gt2szvnftfy.html

[R61] 磁盘占用
来源：http://dali.tanke756.top/Article/details/gt2yewtrtuc.html

df -h;  du -sh *
来源：http://dali.yvedp.cn/Article/details/gt2zrlyreur.html

[R62] 找最占空间的文件
来源：http://dali.nanxuanxn.top/Article/details/gt2oimielwa.html

du -ah . | sort -rh | head -10
来源：http://dali.daxiang520.top/Article/details/gt2zxgqalln.html

[R63] 内存与进程
来源：http://dali.pengpengdd.cyou/Article/details/gt2lefkeauj.html

free -h;  ps aux | grep nginx
来源：http://dali.haohaochexian.top/Article/details/gt2hbatggvy.html

[R64] 结束进程
来源：http://dali.redwolf501.top/Article/details/gt2ysaxrkif.html

kill -9 $(pgrep -f app.py)
来源：http://dali.nanxinkj.top/Article/details/gt2ghgplpbv.html

[R65] 查看端口占用
来源：http://dali.yonumen.top/Article/details/gt2dfbonshs.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jinqigufen.top/Article/details/gt2bjnbcnaf.html

[R66] 定时任务
来源：http://dali.gotoacloud.top/Article/details/gt2rgealurb.html

crontab -e;  crontab -l
来源：http://dali.hnxiangtu.top/Article/details/gt2yjftkyxe.html

[R67] 生成随机十六进制串
来源：http://dali.havefunace.top/Article/details/gt2oxfltdxn.html

openssl rand -hex 16
来源：http://dali.guowangkeji.top/Article/details/gt2mqspkvst.html

[R68] 计算文件校验值
来源：http://dali.redwolf501.top/Article/details/gt2pbphsqez.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xinyue.icu/Article/details/gt2gygcvyqx.html

[R69] 生成随机密码
来源：http://dali.cashguo.top/Article/details/gt2zyrmbvkm.html


<!-- 参考信息 -->